#### Test 503880196dc97cd_thali08_samsung-SM-A300FU Logs


```
--------- beginning of main
D/PhoneStatusBar( 1173): updateIcon slot=volume index=23 viewIndex=5 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
W/ContextImpl( 2017): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
--------- beginning of system
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/GAV2    ( 2730): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/Zygote  ( 2854): MountEmulatedStorage()
E/Zygote  ( 2854): v2
I/SELinux ( 2854): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 2854): KNOX_SDCARD checking this for 1000
I/libpersona( 2854): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.mobeam.barcodeService for broadcast com.mobeam.barcodeService/.system.AppBroadcastReceiver: pid=2854 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/SensorService( 1017): [SO] currT = 31911072000, prevT = 31491066000, diff = 420006000, [-0.421 -0.019 9.883]
D/SensorService( 1017): [SO] -0.421 -0.019 9.883
D/SensorService( 1017): [SO] [100 -> 255]
I/SELinux ( 2854): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2854): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/TimaKeyStoreProvider( 2854): TimaSignature is unavailable
D/ActivityThread( 2854): Added TimaKeyStore provider
W/ContextImpl( 2854): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.mobeam.barcodeService.system.AppBroadcastReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.mobeam.barcodeService, destAppInfo.processName = com.mobeam.barcodeService
E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PREMIUM_SERVICES_CONFIG_REQ_V02
W/ActivityManager( 1017): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
I/splitIntent( 1017): Split this intent : android.intent.action.BOOT_COMPLETED, mSplitNum[0]=87, mSplitNum[1]=124, mSplitNum[2]=161, mBgSplitQueueNum=3 divideNum= 36 r.nextReceiver= 50 receivers.size=197
I/splitIntent( 1017): finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!
E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PREMIUM_SERVICES_CONFIG_REQ_V02
D/qmi_secgps_clnt( 1017): qmi_secgps_client_init()
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/qmi_secgps_clnt( 1017): SECGPS: qmi_client_get_service_list() returned 0 num_services = 2
D/qmi_secgps_clnt( 1017): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 0 num_services = 2
D/qmi_secgps_clnt( 1017): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 2 num_services = 2
E/Zygote  ( 2889): MountEmulatedStorage()
E/Zygote  ( 2889): v2
I/libpersona( 2889): KNOX_SDCARD checking this for 10097
I/libpersona( 2889): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc flipboard.boxer.app for broadcast flipboard.boxer.app/flipboard.boxer.receiver.BootCompleted: pid=2889 uid=10097 gids={50097, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 2889): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2889): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2889): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/DriveInitializer( 2017): Background init thread ended
E/Zygote  ( 2903): MountEmulatedStorage()
E/Zygote  ( 2903): v2
I/libpersona( 2903): KNOX_SDCARD checking this for 1000
I/libpersona( 2903): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=2903 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/TimaKeyStoreProvider( 2889): TimaSignature is unavailable
D/ActivityThread( 2889): Added TimaKeyStore provider
I/SELinux ( 2903): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2903): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2903): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SecurityLogAgent( 1717): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 1717): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 1717): StateMachine : Current State = 1
D/SecurityLogAgent( 1717): BootReceiver : completed task. Failed to return wakelock . 
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 2903): TimaSignature is unavailable
D/ActivityThread( 2903): Added TimaKeyStore provider
I/libpersona( 2924): KNOX_SDCARD checking this for 10148
E/Zygote  ( 2924): MountEmulatedStorage()
I/libpersona( 2924): KNOX_SDCARD not a persona
E/Zygote  ( 2924): v2
I/SELinux ( 2924): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=2924 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
I/SELinux ( 2924): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2924): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Killing 1495:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
I/dhcpcd  ( 1796): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 1796): wlan0: no IPv6 Routers available
D/SSRM:a  ( 1017): DeviceInfo:: 000000000000
D/SSRM:a  ( 1017): SettingsAirViewInfo:: 000000000
I/art     (  317): Explicit concurrent mark sweep GC freed 8731(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 618us total 31.466ms
I/qcom-bluetooth( 2933): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
E/LocSvc_utils_cfg( 1017): W/loc_read_sec_gps_conf: no secgps conf file, using defaults
I/qcom-bluetooth( 2941): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 891us total 19.091ms
E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
D/TimaKeyStoreProvider( 2924): TimaSignature is unavailable
D/ActivityThread( 2924): Added TimaKeyStore provider
E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
V/DownloadManager( 1227): onReceive intent + android.intent.action.BOOT_COMPLETED
E/USB_UICC(  308): Timeout! No signal received. Retry num = 26
I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 602us total 18.554ms
I/bt_vendor( 2653): bluetooth satus is on
E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SERVER_REQ_V02
I/qmi_secgps_clnt( 1017): SECGPS: Set AGPS Mode : 7
D/bt_userial_mct( 2653): userial_open(port:0)
I/bt_vendor( 2653): bt-vendor : BT_VND_OP_USERIAL_OPEN
D/qmi_secgps_clnt( 1017): SECGPS: send a qmi message to secgps_server OK
W/ResourcesManager( 2903): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
I/bt_vendor( 2653): Done intiailizing UART
I/bt_vendor( 2653): Done intiailizing UART
I/bt_userial_mct( 2653): CMD=65, EVT=65, ACL_Out=66, ACL_In=66
I/bt_vendor( 2653): Bluetooth Firmware and transport layer are initialized
D/bt_userial_mct( 2653): Entering userial_read_thread()
E/LocSvc_ApiV02( 1017): I/virtual loc_api_adapter_err LocApiV02::setSUPLVersion(uint32_t):1558]: supl version = 131072
D/SecContentProvider2( 1017): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1017): mCursor = null
D/MediaScannerReceiver( 1227): action: android.intent.action.BOOT_COMPLETED
E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
E/LocSvc_ApiV02( 1017): I/virtual loc_api_adapter_err LocApiV02::setAGLONASSProtocol(long unsigned int):1881]: aGlonassProtocolMask = 0x0
E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
I/qmi_secgps_clnt( 1017): SECGPS: Set XTRA enable : 1
D/qmi_secgps_clnt( 1017): SECGPS: send a qmi message to secgps_server OK
I/qmi_secgps_clnt( 1017): SECGPS: Set GNSS RF CONFIG : 1
D/qmi_secgps_clnt( 1017): SECGPS: send a qmi message to secgps_server OK
I/qmi_secgps_clnt( 1017): SECGPS: Set CERT TYPE : 15
D/qmi_secgps_clnt( 1017): SECGPS: send a qmi message to secgps_server OK
E/LocSvc_ApiV02( 1017): I/virtual loc_api_adapter_err LocApiV02::setLPPConfig(uint32_t):1605]: lpp profile = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_1495/cgroup.procs: No such file or directory
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
E/LocSvc_ApiV02( 1017): I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1644]: sensors disabled = 1
E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
E/LocSvc_ApiV02( 1017): E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3316]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
I/KnoxUsageLogPro( 2903): KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
I/KnoxUsageLogPro( 2903): savePreference: key = previous_sys_time value = 1448460691458
I/KnoxUsageLogPro( 2903): premStatus:2
I/KnoxUsageLogPro( 2903): isEulaShown : false
I/KnoxUsageLogPro( 2903): KnoxUsageReceiver onReceive : not Processible, just return
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/        ( 2653): BTE_InitTraceLevels -- TRC_HCI
I/        ( 2653): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 2653): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 2653): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 2653): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 2653): BTE_InitTraceLevels -- TRC_A2D
I/        ( 2653): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 2653): BTE_InitTraceLevels -- TRC_BTM
I/        ( 2653): BTE_InitTraceLevels -- TRC_GAP
I/        ( 2653): BTE_InitTraceLevels -- TRC_PAN
I/        ( 2653): BTE_InitTraceLevels -- TRC_SAP
I/        ( 2653): BTE_InitTraceLevels -- TRC_SDP
I/        ( 2653): BTE_InitTraceLevels -- TRC_GATT
I/        ( 2653): BTE_InitTraceLevels -- TRC_SMP
I/        ( 2653): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 2653): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 2653): BTE_InitTraceLevels -- TRC_PROTOCOL
E/SQLiteLog( 2924): (284) automatic index on shooting_modes(title_id)
E/Zygote  ( 2953): MountEmulatedStorage()
I/libpersona( 2953): KNOX_SDCARD checking this for 10081
E/Zygote  ( 2953): v2
I/libpersona( 2953): KNOX_SDCARD not a persona
I/SELinux ( 2953): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=2953 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 1397:com.sec.android.provider.emergencymode/u0a92 (adj 15): empty #31
I/SELinux ( 2953): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2953): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 2953): TimaSignature is unavailable
D/ActivityThread( 2953): Added TimaKeyStore provider
E/Zygote  ( 2970): MountEmulatedStorage()
E/Zygote  ( 2970): v2
I/libpersona( 2970): KNOX_SDCARD checking this for 1101
I/SELinux ( 2970): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 2970): KNOX_SDCARD not a persona
I/SELinux ( 2970): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2970): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=2970 uid=1101 gids={41101, 9997} abi=armeabi-v7a
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
I/KnoxUsageLogPro( 2903): savePreference: key = previous_elapsed_time value = 32322
W/bt-l2cap( 2653): l2c_link_processs_ble_num_bufs 16
E/ActivityThread( 2889): Failed to find provider info for flipboard.auth.internal.debug
E/bt-btm  ( 2653): BTM_SecRegister:p_cb_info->p_le_callback == 0xa4524ead 
E/bt-btm  ( 2653): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa4524ead 
I/ActivityManager( 1017): Killing 1558:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #31
E/ActivityThread( 2889): Failed to find provider info for flipboard.auth.internal
D/BluetoothAdapterProperties( 2653): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
E/bt-btif ( 2653):                : sec
E/bt-btif ( 2653): AG evt (hdl 0x0001): State 0, Event 0x0500
D/BluetoothAdapterProperties( 2653): Address is:08:EC:A9:50:76:27
E/BluetoothServiceJni( 2653): populateRssiValuesNative
I/bluedroid( 2653): getModelRssiValues
E/BluetoothServiceJni( 2653): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 2653): modelRssiValuesCallback, low, mid, high = -70,-60,127
D/BluetoothAdapterProperties( 2653): Name is: Thali Test (Galaxy A3)
D/SettingsProvider( 1017): name = bluetooth_name
D/BluetoothAdapterProperties( 2653): Scan Mode:20
D/BluetoothAdapterProperties( 2653): Discoverable Timeout:120
D/BluetoothAdapterProperties( 2653): LE Address is:C8:D9:53:A0:EC:4E
E/bt-btif ( 2653): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 2653): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
E/bt-btif ( 2653): btif_sock_init: !radio_req && !rfc_init
E/bt-btif ( 2653): btif_sock_init: !vhci_init
D/IOP_DB_BT( 2653): db_open: file /etc/bluetooth/iop_bt.db
D/TimaKeyStoreProvider( 2970): TimaSignature is unavailable
D/ActivityThread( 2970): Added TimaKeyStore provider
E/bt_mct  ( 2653): hci lib postload completed
I/ActivityManager( 1017): Killing 1875:com.sec.android.widgetapp.samsungapps/u0a134 (adj 15): empty #31
I/DrmEventReceiver( 1017): DrmEventReceiver : onReceive
I/DrmEventReceiver( 1017): DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
I/DrmEventReceiver( 1017): DrmEventReceiver : beginStartingService
I/System.out( 1017): start Service
W/ResourcesManager( 2953): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
I/System.out( 2730): Thread-326(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
W/ResourcesManager( 2953): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 2953): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2953): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2953): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
W/ResourcesManager( 2970): Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
D/IOP_DB_BT( 2653): db_open: db_open : handle 3028230160l, read 13894 bytes onto local cache
D/IOP_DB_BT( 2653): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 2653): db_query: result 1
I/        ( 2653): iop_db_open: iop_db_open status 0
D/bte_conf( 2653): Device ID record 1 : primary
D/bte_conf( 2653):   vendorId            = 0075
D/bte_conf( 2653):   vendorIdSource      = 0001
D/bte_conf( 2653):   product             = 0100
D/bte_conf( 2653):   version             = 0200
D/bte_conf( 2653):   clientExecutableURL = 
D/bte_conf( 2653):   serviceDescription  = 
D/bte_conf( 2653):   documentationURL    = 
D/bte_conf( 2653): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 2653): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 2653): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 2653): ScanMode =  20
D/BluetoothAdapterProperties( 2653): State =  11
D/SecContentProvider( 1017): uri = 3 selection = isDiscoverableEnabled
V/SmartcardService( 2970): main Received broadcast
V/SmartcardService( 2970): Starting smartcard service after boot completed
D/BluetoothAdapterProperties( 2653): Setting state to 12
I/BluetoothAdapterState( 2653): Bluetooth adapter state changed: 11-> 12
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
D/BluetoothAdapterProperties( 2653): Scan Mode:21
D/BluetoothAdapterProperties( 2653): Discoverable Timeout:120
D/SettingsProvider( 1017): name = bluetooth_a2dp_sink_mode
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
I/ActivityManager( 1017): Killing 2150:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #31
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/MediaScannerService( 1227): !@start scanning volume internal: [/system/media, /oem/media]
E/Zygote  ( 2992): MountEmulatedStorage()
E/Zygote  ( 2992): v2
I/libpersona( 2992): KNOX_SDCARD checking this for 1000
I/libpersona( 2992): KNOX_SDCARD not a persona
I/SELinux ( 2992): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2992): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/System.out( 2730): Thread-326(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 2730): Thread-326(ApacheHTTPLog):isShipBuild true
I/System.out( 2730): Thread-326(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 2730): Thread-326(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
E/SELinux ( 2992): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.sec.android.app.sysscope for broadcast com.sec.android.app.sysscope/.receiver.BootCompleteReceiver: pid=2992 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10087
W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
D/BluetoothAdapterService( 2653): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2653): updateAdapterState state is 12
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/BluetoothAdapterService( 2653): Autoconnection is available 
D/BluetoothAdapterService( 2653): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapter( 1778): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1778): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapterService( 2653): starting service from this receiver
D/BluetoothA2dp( 1017): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1439): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1439): onBluetoothStateChange: Bluetooth is on
I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
D/BluetoothAdapter( 2653): onBluetoothStateChange: up=true
D/BluetoothAdapter( 2653): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 1017): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1017): onBluetoothStateChange: Bluetooth is on
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/WVMDrmPlugIn(  284): WVMDrmPlugin::onInitialize : 3419
D/WVMDrmPlugIn(  284): WVMDrmPlugin::onSetOnInfoListener : add 3419
D/BluetoothAdapter( 1448): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1448): onBluetoothStateChange: Bluetooth is on
D/BluetoothA2dp( 2653): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1431): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1431): onBluetoothStateChange: Bluetooth is on
I/BluetoothAdapterState( 2653): Entering On State from state = 11
D/BluetoothAdapter( 2186): onBluetoothStateChange: up=true
D/BluetoothAdapter( 2186): onBluetoothStateChange: Bluetooth is on
D/MtpService( 1227): updating state; isCurrentUser=true, mMtpLocked=false
D/BluetoothAdapter( 1173): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1173): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 1626): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1626): onBluetoothStateChange: Bluetooth is on
I/BluetoothPbapService( 2653): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
D/TP/MmsProvider( 1448): Update uri=content://mms, match=0
D/TP/MmsProvider( 1448): update , handleReadChangedBroadcast
W/libprocessgroup( 1017): failed to open /acct/uid_10092/pid_1397/cgroup.procs: No such file or directory
D/TP/MmsSmsProvider( 1448): need read changed broadcast:false
D/TimaKeyStoreProvider( 2992): TimaSignature is unavailable
D/BluetoothTile( 1173):  onBluetoothStateChange:
W/libprocessgroup( 1017): failed to open /acct/uid_10134/pid_1875/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10052/pid_1558/cgroup.procs: No such file or directory
D/ActivityThread( 2992): Added TimaKeyStore provider
I/SamsungIME( 1824): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
D/BluetoothTile( 1173):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1173): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1173):  getBluetoothState : 12
W/libprocessgroup( 1017): failed to open /acct/uid_10064/pid_2150/cgroup.procs: No such file or directory
I/Mms:transaction( 2350): [MmsSystemEventReceiver] restorePduNotificationStatus count=0
D/BluetoothTile( 1173):  handleUpdatestate:false name:null
D/Mms/MessagingNotification( 2350): [start]    nonBlockingUpdateMessageIndicator() consume time = 4944.991925
I/Mms/ReservationManager( 2350): resetAfterConnected()
D/StatusBarManagerService( 1017): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
D/Mms/MessagingNotification( 2350): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2350): isDefault true
D/StatusBarManagerService( 1017): setIconVisibility slot=bluetooth visible=true
D/PhoneStatusBar( 1173): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
I/BluetoothPbapService( 2653): Handler(): got msg=1
D/BluetoothTile( 1173):  handleUpdatestate:false name:null
D/BluetoothTile( 1173):  handleUpdatestate:false name:null
D/SecContentProvider( 1017): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
D/BluetoothHeadset( 1431): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@8d9847e, true
D/TP/MmsProvider( 1448): Query uri=content://mms, match=0, calling pid = 2350
D/BluetoothHeadset( 1431): registerMessageListener
I/DrmEventService( 1017): action event :android.intent.action.BOOT_COMPLETED
I/TimaServiceEventReceiver( 1017): TimaServiceEventReceiver : onReceive
D/TP/MmsSmsProvider( 1448): query,matched:7, calling pid = 2350
V/BluetoothPbapService( 2653): PBAP Service initSocket try: 0
D/TP/MmsSmsProvider( 1448): match 7:Elapsed time : 2.089 ms
D/HeadsetService( 2653): registerMessageListener
D/HeadsetService( 2653): registerMessageListener
D/HeadsetStateMachine( 2653): Disconnected process message: 70
D/HeadsetStateMachine( 2653): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@16772730
I/Telecom ( 1431): BluetoothPhoneService: handleMessage(7) / param null
I/Telecom ( 1431): BluetoothPhoneService: updateHeadsetWithCallState
W/InputMethodManagerService( 1017): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapMasInstance( 2653): set MAP SDP message type : 1
I/Telecom ( 1431): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
I/Telecom ( 1431): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
I/Telecom ( 1431): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
I/InputMethodManagerService( 1017): [BT Setting State] State =12
I/InputMethodManagerService( 1017): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
D/HeadsetStateMachine( 2653): Disconnected process message: 9
D/HeadsetStateMachine( 2653): mNumActive: 0 mNumHeld: 0 mCallState: 6
I/ANDROID_DRM_FRWORKS_DrmManager(  284): DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
I/Mms/ReservationManager( 2350): getReservedSendMessageCount(): retMessageCount=0
W/BluetoothAdapter( 2653): getBluetoothService() called with no BluetoothManagerCallback
W/BluetoothAdapter( 2653): getBluetoothService() called with no BluetoothManagerCallback
W/ContextImpl( 2992): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/TP/MmsSmsProvider( 1448): query,matched:200, calling pid = 2350
D/TP/MmsSmsProvider( 1448): match 200:Elapsed time : 1.095 ms
D/BluetoothSocket( 2653): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
D/BluetoothSocket( 2653): bindListen(), new LocalSocket 
D/BluetoothSocket( 2653): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 2653): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1dcc7fa9
D/BluetoothSocket( 2653): channel: 19
D/BluetoothPbapService( 2653): PBAP Socket is BluetoothServerSocket
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.sysscope, destAppInfo.processName = com.sec.android.app.sysscope
D/BluetoothSocket( 2653): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
D/BluetoothSocket( 2653): bindListen(), new LocalSocket 
D/BluetoothSocket( 2653): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 2653): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@24ae092e
D/BluetoothSocket( 2653): channel: 5
D/audio_hw_primary(  285): adev_set_parameters: enter: A2dpSuspended=false
V/voice   (  285): voice_set_parameters: enter: A2dpSuspended=false
V/voice   (  285): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  285): platform_set_parameters: enter: A2dpSuspended=false
V/msm8974_platform(  285): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  285): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  285): adev_set_parameters: exit
E/HeadsetStateMachine( 2653): terminateScoUsingVirtualVoiceCall:No present call to terminate
E/CscReceiver( 1448): onReceive android.intent.action.BOOT_COMPLETED
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3017): MountEmulatedStorage()
E/Zygote  ( 3017): v2
I/libpersona( 3017): KNOX_SDCARD checking this for 10043
I/libpersona( 3017): KNOX_SDCARD not a persona
I/SELinux ( 3017): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3017): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=3017 uid=10043 gids={50043, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/SELinux ( 3017): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/Zygote  ( 3029): MountEmulatedStorage()
I/ActivityManager( 1017): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=3029 uid=10153 gids={50153, 9997} abi=armeabi-v7a
E/Zygote  ( 3029): v2
I/libpersona( 3029): KNOX_SDCARD checking this for 10153
I/SELinux ( 3029): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 3029): KNOX_SDCARD not a persona
I/SELinux ( 3029): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3029): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/CscUpdateService( 1448): onStart
E/CscUpdateService( 1448): costomer file is exists : it has been preconfiged.
I/CscUpdateService( 1448): set_CSC_version
E/CscParser( 1448): update(): xml file exist
D/TimaKeyStoreProvider( 3029): TimaSignature is unavailable
D/ActivityThread( 3029): Added TimaKeyStore provider
E/Zygote  ( 3044): MountEmulatedStorage()
E/Zygote  ( 3044): v2
,I/libpersona( 3044): KNOX_SDCARD checking this for 10002
I/libpersona( 3044): KNOX_SDCARD not a persona
I/SELinux ( 3044): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3044): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=3044 uid=10002 gids={50002, 9997, 3002, 3003, 1028} abi=armeabi-v7a
E/SELinux ( 3044): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 3017): TimaSignature is unavailable
D/ActivityThread( 3017): Added TimaKeyStore provider
D/SettingsProvider( 1017): name = next_alarm_formatted
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10081
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
I/CscUtil ( 1448): isWifiOnly = false
I/System.out( 1448): HandDataNode = null
I/CscUpdateService( 1448): PATH_CSCNAME =CustomerDataSet.CSCName
I/CscUpdateService( 1448): This is normal boot : CSC not updated
E/CscParser( 1448): update(): xml file exist
D/TimaKeyStoreProvider( 3044): TimaSignature is unavailable
D/ActivityThread( 3044): Added TimaKeyStore provider
D/TP/SmsProvider( 1448): query,matched:0, calling pid = 2350
W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10081
D/TP/SmsProvider( 1448): match 0:Elapsed time : 6.038 ms
D/Mms/SmsReceiverService( 2350): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
I/CscUpdateService( 1448): same CSC Version
D/CscUtil ( 1448): Set Build Fingerprint to samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
D/CscGPS  ( 1448): CSCGPS.updateParameters
D/CscGPS  ( 1448): supl host : null
D/CscGPS  ( 1448): SUPL Host is null or invalid
D/CscGPS  ( 1448): supl_ver : null
D/CscGPS  ( 1448): SUPL Ver is null or invalid
D/CscGPS  ( 1448): supl port : null
D/CscGPS  ( 1448): SUPL PORT is null or invalid
D/CscGPS  ( 1448): LPP : null
D/CscGPS  ( 1448): LPP is null or invalid
D/CscGPS  ( 1448): CSC don't have any AGPS value.
D/Mms/TelephonyPermission( 2350): isDefault true
D/Mms/SmsReceiverService( 2350): [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
D/Mms/SmsReceiverService( 2350): [start]    handleBootCompleted() consume time = 224.091615
W/ResourcesManager( 3017): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 3017): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3017): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 3029): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/SQLiteLog( 1227): (283) recovered 401 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/System.out( 2730): SyncManager calls detatch()
W/art     ( 2953): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 143.912ms
I/art     ( 1448): Explicit concurrent mark sweep GC freed 39265(2MB) AllocSpace objects, 11(176KB) LOS objects, 45% free, 4MB/8MB, paused 960us total 174.391ms
D/TP/SmsProvider( 1448): query,matched:51, calling pid = 2350
I/art     ( 1017): Explicit concurrent mark sweep GC freed 38587(2018KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 22MB/33MB, paused 2.176ms total 196.017ms
D/TP/SmsProvider( 1448): match 51:Elapsed time : 27.545 ms
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3072): MountEmulatedStorage()
E/Zygote  ( 3072): v2
I/libpersona( 3072): KNOX_SDCARD checking this for 1000
I/libpersona( 3072): KNOX_SDCARD not a persona
I/SELinux ( 3072): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/MediaScanner( 1227): Prescan. DB items number : 138 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
I/SELinux ( 3072): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3072): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=3072 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
D/SettingsProvider( 1017): name = block_emergency_message
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10043
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
W/ActivityManager( 1017): getTasks: caller 10043 is using old GET_TASKS but privileged; allowing
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
V/GLSActivity( 1626): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/Mms/MessagingNotification( 2350): isBlockingModeEnabled() = false, Zen mode = 0
D/TP/MmsSmsProvider( 1448): getThreadUnReadCount unreadCount=0 imUnreadCount=0
D/TP/MmsSmsProvider( 1448): deleteConversation threadId: 9223372036854775806
E/Zygote  ( 3086): MountEmulatedStorage()
E/Zygote  ( 3086): v2
I/libpersona( 3086): KNOX_SDCARD checking this for 1000
I/libpersona( 3086): KNOX_SDCARD not a persona
I/SELinux ( 3086): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3086): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=3086 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 3086): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/BadgeProvider( 1583): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
D/TimaKeyStoreProvider( 3072): TimaSignature is unavailable
D/ActivityThread( 3072): Added TimaKeyStore provider
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/TP/MmsSmsProvider( 1448): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1448): updateThread(), thread_id = 9223372036854775806
E/USB_UICC(  308): Timeout! No signal received. Retry num = 27
V/TP/MmsSmsDatabaseHelper( 1448): sUpgradeVersion = 0, db.getVersion() = 81
E/SQLiteLog( 1448): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1448): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1448): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1448): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1448): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1448): (284) automatic index on im_threads(normal_thread_id)
D/TP/MmsSmsProvider( 1448): delete threadId: 9223372036854775806
D/TP/MmsSmsProvider( 1448): need read changed broadcast:false
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 3086): TimaSignature is unavailable
D/ActivityThread( 3086): Added TimaKeyStore provider
D/Launcher.Model( 1478): reloadBadges entered.
D/BadgeProvider( 1583): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1583): sendNotify, [notify] : null
D/BadgeProvider( 1583): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1583): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1583): update, [UpdateCount] : 1
D/Mms/Conversation( 2350): deleteTempConversation(),deleted=0
V/MediaScanner( 1227): processDirectory :  /system/media
D/Mms/MessagingNotification( 2350): setBadgeCount(), count=0
D/Mms/MessagingNotification( 2350): remove alarm
I/ServiceManager(  328): Waiting for service AtCmdFwd...
D/TP/SmsProvider( 1448): query,matched:0, calling pid = 2350
I/ActivityManager( 1017): Killing 2171:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31
D/TP/SmsProvider( 1448): match 0:Elapsed time : 1.218 ms
D/SmsProvider( 1448): Update uri=content://sms/outbox, match=8
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
D/TP/MmsSmsProvider( 1448): need read changed broadcast:false
D/AndroidRuntime( 3068): 
D/AndroidRuntime( 3068): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/Mms/SmsReceiverService( 2350): moveOutboxMessagesToFailedBox messageCount: 0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/Mms/SmsReceiverService( 2350): handle boot completed, sendFirstQueuedMessage()
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/Mms/SmsReceiverService( 2350): [SIM-1]sendFirstQueuedMessage()
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/AndroidRuntime( 3068): CheckJNI is OFF
I/WifiCredService( 1301): onCreate
D/AndroidRuntime( 3068): readGMSProperty: start
D/AndroidRuntime( 3068): readGMSProperty: already setted!!
D/AndroidRuntime( 3068): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 3068): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 3068): readGMSProperty: end
D/AndroidRuntime( 3068): addProductProperty: start
E/Zygote  ( 3105): MountEmulatedStorage()
E/Zygote  ( 3105): v2
I/libpersona( 3105): KNOX_SDCARD checking this for 10155
I/libpersona( 3105): KNOX_SDCARD not a persona
I/SELinux ( 3105): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=3105 uid=10155 gids={50155, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
I/SELinux ( 3105): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3105): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Killing 2186:com.vlingo.midas/u0a28 (adj 15): empty #31
D/WifiCredService( 1301): Action received :android.net.wifi.WIFI_STATE_CHANGED
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/WifiStateMachine( 1017): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-wlan0( 1017): callSECStringApiVoid - ID [215]
E/WifiNative-wlan0( 1017): invaild command id : 215
E/Zygote  ( 3116): MountEmulatedStorage()
I/libpersona( 3116): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3116): v2
I/libpersona( 3116): KNOX_SDCARD not a persona
D/TimaKeyStoreProvider( 3105): TimaSignature is unavailable
D/ActivityThread( 3105): Added TimaKeyStore provider
I/ActivityManager( 1017): Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3116 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 3116): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1017): Killing 2206:com.sec.android.app.videoplayer/u0a45 (adj 15): empty #31
I/SELinux ( 3116): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3116): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/WifiTimerReceiver( 1301): action: android.intent.action.BOOT_COMPLETED
D/WifiTimerReceiver( 1301): extra: Bundle[mParcelledData.dataSize=84]
D/MY_TAG  ( 1301): Action boot completed received
V/MediaScanner( 1227):  prescan time: 538ms (DB items: 138)
D/Mms/MessagingNotification( 2350): [end]    nonBlockingUpdateMessageIndicator() consume time = 460.62776
V/MediaScanner( 1227):     scan time: 106ms (Caching mode: true), (makeEntry time: 37ms ~34%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1227): postscan time: 2ms (bulkDeleter : 0), (delete DeadThumbnail time : 2ms)
V/MediaScanner( 1227):    total time: 646ms
V/MediaScanner( 1227): checked files: 130  directories : 6  (I: 0, U: 0)
D/MediaScanner( 1227): checkDefaultSounds
D/MediaScanner( 1227): system alarm_alert  : Vwiurug_etwofi5wgg
W/ResourcesManager( 3105): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
D/MediaScanner( 1227): OK. alarm_alert is already exist in setting DB.
D/MediaScanner( 1227): system notification_sound  : K_Oprkltf5wgg
D/MediaScanner( 1227): OK. notification_sound is already exist in setting DB.
D/MediaScanner( 1227): system ringtone  : Wmfi_lpf_pwirywu5wgg
D/Mms/MessagingNotification( 2350): updateAllHistoryAsRead()
D/TP/SmsProvider( 1448): query,matched:26, calling pid = 2350
D/MediaScanner( 1227): OK. ringtone is already exist in setting DB.
D/MediaScannerService( 1227): !@done scanning volume internal
D/MediaScannerService( 1227): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
D/TimaKeyStoreProvider( 3116): TimaSignature is unavailable
D/ActivityThread( 3116): Added TimaKeyStore provider
D/FactoryTestApp( 2628): [DummyFtClient$mBroadcastReceiver](2628) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2628): [DummyFtClient$mBroadcastReceiver](2628) ACTION_MEDIA_SCANNER_FINISHED = /system/media
D/FactoryTestApp( 2628): [DummyFtClient$mBroadcastReceiver](2628) ACTION_MEDIA_SCANNER_FINISHED = Ignored
D/TP/SmsProvider( 1448): match 26:Elapsed time : 13.894 ms
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started
W/ResourcesManager( 3116): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/SmsReceiver( 2350): unregisterForServiceStateChanges, already unregistered
D/Mms/MessagingNotification( 2350): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2350): isDefault true
W/libprocessgroup( 1017): failed to open /acct/uid_10065/pid_2171/cgroup.procs: No such file or directory
D/TP/MmsProvider( 1448): Query uri=content://mms, match=0, calling pid = 2350
W/libprocessgroup( 1017): failed to open /acct/uid_10028/pid_2186/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10045/pid_2206/cgroup.procs: No such file or directory
D/TP/MmsSmsProvider( 1448): query,matched:200, calling pid = 2350
D/TP/MmsSmsProvider( 1448): match 200:Elapsed time : 0.893 ms
D/TP/SmsProvider( 1448): query,matched:0, calling pid = 2350
D/TP/SmsProvider( 1448): match 0:Elapsed time : 1.230 ms
D/[0]UMC:Core( 3105): onCreate(): 
D/TP/SmsProvider( 1448): query,matched:51, calling pid = 2350
D/TP/SmsProvider( 1448): match 51:Elapsed time : 1.843 ms
D/[0]UMC:DeviceInfo( 3105): USA==US==
D/Mms/MessagingNotification( 2350): isBlockingModeEnabled() = false, Zen mode = 0
D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
D/SettingsProvider( 1017): name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
D/BadgeProvider( 1583): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
V/NearbySettings( 1301): MountReceiver.mPrefHandler - 7002
D/USER_AGENT( 3105): UMC/1.3.23 (SM-A300FU) SAFE-5.3 KNOX-2.3 en_US
D/[0]UMC:AdminManager( 3105): init - start
D/[0]UMC:AdminManager( 3105): loadAdmins
E/SQLiteLog( 3086): (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
W/bdH     ( 2730): Application name is not set. Call Builder#setApplicationName.
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
D/[0]UMC:AdminManager( 3105): init - end
D/GSLBManager( 3105): migrateStoredUrlFromOldPref
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter finished
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
D/Launcher.Model( 1478): reloadBadges entered.
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
D/BadgeProvider( 1583): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1583): sendNotify, [notify] : null
D/BadgeProvider( 1583): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1583): update, [BadgeCount] : badgecount=0
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter finished
D/BadgeProvider( 1583): update, [UpdateCount] : 1
D/GSLBManager( 3105): migrateStoredUrlFromOldPref : Migration Not Needed
D/[0]UMC:UMCAdmin( 3105): deactivateUMCAdminIfNotRequired : -1
E/[0]UMC:Utils( 3105): Admin not found in package com.samsung.knoxpb.mdm
E/[0]UMC:Utils( 3105): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 3105): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 3105): isContainer : 0
D/Mms/MessagingNotification( 2350): setBadgeCount(), count=0
D/EnterpriseDeviceManagerService( 1017): isManagedProfileUser(): userId = 0
D/DSM     ( 3086): [Lines:107] Normal booted
D/DSM     ( 3086): [Lines:114] Boot completed
D/MediaScanner( 1227): Prescan. DB items number : 26 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
D/Mms/MessagingNotification( 2350): remove alarm
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
I/NearbySettings( 1301): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
I/NearbySettings( 1301): MountReceiver.onReceive - Internal Path
E/Zygote  ( 3150): MountEmulatedStorage()
E/Zygote  ( 3150): v2
I/libpersona( 3150): KNOX_SDCARD checking this for 10082
I/libpersona( 3150): KNOX_SDCARD not a persona
I/System.out( 2730): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 2730): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 2730): (HTTPLog)-Static: isShipBuild true
I/System.out( 2730): (HTTPLog)-Thread-326-24823262: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 2730): (HTTPLog)-Static: isSBSettingEnabled false
I/SELinux ( 3150): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10087
I/SELinux ( 3150): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3150): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3150 uid=10082 gids={50082, 9997, 3003} abi=armeabi-v7a
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
V/MediaScanner( 1227): processDirectory :  /storage/emulated/0
I/art     (  317): Explicit concurrent mark sweep GC freed 8703(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 614us total 26.964ms
D/TimaKeyStoreProvider( 3150): TimaSignature is unavailable
D/ActivityThread( 3150): Added TimaKeyStore provider
D/MediaScanner( 1227): Skipping:
D/MediaScanner( 1227): 7klwibgf7fvntblfd7(75ebcf7
I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 574us total 16.620ms
E/[0]UMC:UMCAdmin( 3105): No active admin owned by uid 10155
D/[0]UMC:UMCAdmin( 3105): isContainer : 0
D/[0]UMC:UMCAdmin( 3105): deactivateUMCAdmin - UMC App Admin deactivated
D/MediaScanner( 1227): Skipping:
D/[0]UMC:CoreReceiver( 3105): Intent : android.intent.action.BOOT_COMPLETED
D/MediaScanner( 1227): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
D/[0]UMC:CoreReceiver( 3105):  check PreETag 
V/MediaScanner( 1227): processDirectory :  /storage/extSdCard
W/MediaScanner( 1227): Error opening directory, reason : Permission denied.
W/MediaScanner( 1227): 7klwibgf7fxlKdCbid7
V/MediaScanner( 1227):  prescan time: 70ms (DB items: 26)
V/MediaScanner( 1227):     scan time: 27ms (Caching mode: true), (makeEntry time: 14ms ~51%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1227): postscan time: 3ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1227):    total time: 100ms
V/MediaScanner( 1227): checked files: 10  directories : 16  (I: 0, U: 0)
I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 625us total 16.439ms
I/System.out( 2730): KnoxVpnUidStorageknoxVpnSupported API value returned is false
D/[0]UMC:ByodSetupStarter( 3105): Container ID : 0
E/Zygote  ( 3170): MountEmulatedStorage()
E/Zygote  ( 3170): v2
I/libpersona( 3170): KNOX_SDCARD checking this for 1000
I/libpersona( 3170): KNOX_SDCARD not a persona
I/SELinux ( 3170): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3170): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=3170 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 3170): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Killing 2262:com.google.android.apps.magazines/u0a110 (adj 15): empty #31
D/Mms/MessagingNotification( 2350): updateAllHistoryAsRead()
D/MediaScannerService( 1227): !@done scanning volume external
V/[0]UMC:Utils( 3105): checkAppScreen() : com.sec.android.app.launcher
I/[0]UMC:Core( 3105): shutdown
D/SettingsProvider( 1017): name = personal_mode_enabled
D/TimaKeyStoreProvider( 3170): TimaSignature is unavailable
D/ActivityThread( 3170): Added TimaKeyStore provider
I/art     ( 3105): System.exit called, status: 0
I/AndroidRuntime( 3105): VM exiting with result code 0, cleanup skipped.
D/TP/SmsProvider( 1448): query,matched:0, calling pid = 2350
D/FactoryTestApp( 2628): [DummyFtClient$mBroadcastReceiver](2628) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2628): [DummyFtClient$mBroadcastReceiver](2628) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
D/FactoryTestApp( 2628): [DummyFtClient$sendBootCompletedAndFinish](2628) ...
D/FactoryTestApp( 2628): [Support$Values.getString](2628) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2628): [ModuleCommon$isConnectionModeNone](2628) mConnectionMode = gsm
D/FactoryTestApp( 2628): [IPCWriterToSecPhoneService$ResponseWriter](2628) Create IPCWriterToSecPhoneService
I/FactoryTestApp( 2628): [IPCWriterToSecPhoneService$connectToSecPhoneService](2628)  
W/ContextImpl( 2628): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
D/TP/SmsProvider( 1448): match 0:Elapsed time : 19.424 ms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
W/ResourcesManager( 3170): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
D/Mms/SmsReceiverService( 2350): [end]    handleBootCompleted() consume time = 372.702969
W/ActivityThread( 3170): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a300fu.dat
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a3ulte.dat
I/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a300fu.dat
I/ActivityManager( 1017): Process com.sec.enterprise.knox.cloudmdm.smdms (pid 3105)(adj 0) has died(45,689)
D/daemonapp( 1801): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1801): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1801): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
I/FactoryTestApp( 2628): [IPCWriterToSecPhoneService$onServiceConnected](2628) connected done
D/FactoryTestApp( 2628): [IPCWriterToSecPhoneService$write](2628) Send Response Message to SecPhone
D/FactoryTestApp( 2628): [IPCWriterToSecPhoneService$write](2628) Response ��
D/daemonapp( 1801): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
E/AffinityControl( 3068): AffinityControl: registerfunction enter
W/ResourcesManager( 1448): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1448): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1448): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1448): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1448): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1448): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/AT_Distributor(  322): Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
D/FactoryTestApp( 2628): [IPCWriterToSecPhoneService$handleMessage](2628) Send BOOTING COMPLETED done
D/daemonapp( 1801): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 1801): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
D/comsamsunglog( 1801): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1801): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
D/comsamsunglog( 1801): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1801): [MSC_Daemon]>>> ====================================================================================================================
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
D/daemonapp( 1801): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
D/daemonapp( 1801): [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_RUN_REF
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
D/SettingsProvider( 1017): name = aw_daemon_service_key_version_check
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
D/SettingsProvider( 1017): selectionArgs: 10157
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
D/LcdtestApp( 3170): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
I/LcdtestApp( 3170): [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
I/iu.UploadsManager( 2017): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/AndroidRuntime( 3068): Calling main entry com.android.commands.am.Am
W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10157
E/Zygote  ( 3193): MountEmulatedStorage()
I/libpersona( 3193): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3193): v2
I/libpersona( 3193): KNOX_SDCARD not a persona
I/SELinux ( 3193): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/daemonapp( 1801): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
I/SELinux ( 3193): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3193 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 3193): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Killing 1511:com.android.printspooler/u0a132 (adj 15): empty #31
I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
D/daemonapp( 1801): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
I/SmartcardBootCompleteReceiver( 1301): SmartcardBootCompleteReceiver - onReceive() 
I/SmartcardBootCompleteReceiver( 1301): Received intent with action - android.intent.action.BOOT_COMPLETED
E/PersonaManagerService( 1017): inState():  stateMachine is null !!
I/PersonaManagerService( 1017): PersonaId don't exist
I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
D/daemonapp( 1801): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1801): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1801): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
W/ContextImpl( 1301): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/daemonapp( 1801): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/libprocessgroup( 1017): failed to open /acct/uid_10110/pid_2262/cgroup.procs: No such file or directory
W/ActivityManager( 1017): mDVFSHelper.acquire()
D/BluetoothMediaBrowser( 2653):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
I/SurfaceFlinger(  258): id=8 createSurf (16x16),-1 flag=20004, EimLayer(Di
I/SurfaceFlinger(  258): id=9 createSurf (16x16),-1 flag=20004, EimLayer(An
D/TimaKeyStoreProvider( 3193): TimaSignature is unavailable
E/daemonapp( 1801): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
D/ActivityThread( 3193): Added TimaKeyStore provider
D/daemonapp( 1801): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1801): [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1448460692972
D/daemonapp( 1801): [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1448482260000
D/daemonapp( 1801): [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
D/daemonapp( 1801): [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
D/FocusedStackFrame( 1017): Set to : 0
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/AT_Distributor(  322): SetAtdStatus(), 1_1_0
D/InputDispatcher( 1017): Focused application set to: xxxx
D/AT_Distributor(  322): Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
D/InputDispatcher( 1017): Focus left window: 1478
D/AndroidRuntime( 3068): Shutting down VM
D/PhoneWindow( 1017): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1017): *FMB* installDecor flags : 25362712
I/SmartcardBootCompleteReceiver( 1301): Broadcast sent with current lockscreen type
D/Launcher.HomeView( 1478): onPause
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
D/Launcher( 1478): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/BluetoothMediaBrowser( 2653): no now playing list
D/BluetoothMediaBrowser( 2653):  getNowPlayingId now playing id : -1
D/daemonapp( 1801): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1448482260000
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=10 createSurf (540x960),1 flag=404, iello
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/daemonapp( 1801): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 12
D/daemonapp( 1801): [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1448482260000
E/Zygote  ( 3211): MountEmulatedStorage()
E/Zygote  ( 3211): v2
I/libpersona( 3211): KNOX_SDCARD checking this for 10333
I/libpersona( 3211): KNOX_SDCARD not a persona
I/SELinux ( 3211): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3211): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3211): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3211 uid=10333 gids={50333, 9997, 3003, 3001, 3002} abi=armeabi-v7a
W/libprocessgroup( 1017): failed to open /acct/uid_10132/pid_1511/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 3211): TimaSignature is unavailable
D/ActivityThread( 3211): Added TimaKeyStore provider
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1017): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1017): isKioskContainerExistOnDevice
I/DIAGMON_AGENT( 3193): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
D/SensorService( 1017): [SO] activate (ident=0xb87bd7d8, enabled=0)
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
E/UpdateRequestReceiver( 3150): ignoring update request
W/PsynchoHelperImpl( 2730): Error fetching or saving configuration
W/PsynchoHelperImpl( 2730): bdz: 404 Not Found
W/PsynchoHelperImpl( 2730): {
W/PsynchoHelperImpl( 2730):   "errors": [
W/PsynchoHelperImpl( 2730):     {
W/PsynchoHelperImpl( 2730):       "domain": "global",
W/PsynchoHelperImpl( 2730):       "reason": "notFound",
W/PsynchoHelperImpl( 2730):       "message": "Setting psyncho_auto_backup_promo in namespace FEATURE_SWITCH was not found",
W/PsynchoHelperImpl( 2730):       "locationType": "other",
W/PsynchoHelperImpl( 2730):       "location": "setting"
W/PsynchoHelperImpl( 2730):     }
W/PsynchoHelperImpl( 2730):   ],
W/PsynchoHelperImpl( 2730):   "code": 404,
W/PsynchoHelperImpl( 2730):   "message": "Setting psyncho_auto_backup_promo in namespace FEATURE_SWITCH was not found"
W/PsynchoHelperImpl( 2730): }
W/PsynchoHelperImpl( 2730): 	at bdP.newExceptionOnError(AbstractGoogleJsonClientRequest.java:113)
W/PsynchoHelperImpl( 2730): 	at bdP.newExceptionOnError(AbstractGoogleJsonClientRequest.java:40)
W/PsynchoHelperImpl( 2730): 	at bdK.a(AbstractGoogleClientRequest.java:321)
W/PsynchoHelperImpl( 2730): 	at bei.a(HttpRequest.java:1049)
W/PsynchoHelperImpl( 2730): 	at bdJ.executeUnparsed(AbstractGoogleClientRequest.java:419)
W/PsynchoHelperImpl( 2730): 	at bdJ.executeUnparsed(AbstractGoogleClientRequest.java:352)
W/PsynchoHelperImpl( 2730): 	at bdJ.execute(AbstractGoogleClientRequest.java:469)
W/PsynchoHelperImpl( 2730): 	at Op.a(ApiaryPsynchoConfigurationAccessor.java:142)
W/PsynchoHelperImpl( 2730): 	at Op.a(ApiaryPsynchoConfigurationAccessor.java:215)
W/PsynchoHelperImpl( 2730): 	at OQ.a(PsynchoHelperImpl.java:60)
W/PsynchoHelperImpl( 2730): 	at agr.a(DriveSpecificSyncManager.java:27)
W/PsynchoHelperImpl( 2730): 	at agO.a(LegacySyncManager.java:678)
W/PsynchoHelperImpl( 2730): 	at agO.b(LegacySyncManager.java:582)
W/PsynchoHelperImpl( 2730): 	at agO.a(LegacySyncManager.java:467)
W/PsynchoHelperImpl( 2730): 	at agO.a(LegacySyncManager.java:97)
W/PsynchoHelperImpl( 2730): 	at agQ.run(LegacySyncManager.java:419)
W/PsynchoHelperImpl( 2730): 	at ami.a(NetworkUtilitiesImpl.java:31)
W/PsynchoHelperImpl( 2730): 	at agP.run(LegacySyncManager.java:416)
D/SensorManager( 1017): unregisterListener ::   
I/Sensors ( 1017): AccelerometerSensor(0) setDelay : 66000000(ns)
D/SensorService( 1017): [SO] changed settle time [1]
D/SensorService( 1017): [SO] setDelay [66000000]
D/SensorService( 1017): [SO] activate (ident=0xb87bd7d8, enabled=1)
D/SensorService( 1017): [SO] AR_init
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
V/ActivityThread( 1478): updateVisibility : ActivityRecord{23eda95c token=android.os.BinderProxy@23e569d1 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/Launcher.HomeView( 1478): onStop
D/SensorManager( 1017): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
V/ActivityThread( 1478): updateVisibility : ActivityRecord{23eda95c token=android.os.BinderProxy@23e569d1 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1478): onTrimMemory. Level: 20
V/GLSActivity( 1626): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/UpdateRequestReceiver( 3150): ignoring update request
D/comdaemonstockapp( 1801): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
D/comdaemonstockapp( 1801): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/[SBeam] ( 1301): SBeamEnabler.initPreferenceForSbeam : 0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/UpdateRequestReceiver( 3150): ignoring update request
E/Zygote  ( 3233): MountEmulatedStorage()
I/ActivityManager( 1017): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3233 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 3233): v2
I/libpersona( 3233): KNOX_SDCARD checking this for 10161
I/libpersona( 3233): KNOX_SDCARD not a persona
I/SELinux ( 3233): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
W/art     ( 3068): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/SensorService( 1017): [SO] Reset Rotation Old [100], Init [1]
I/SELinux ( 3233): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3233): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/SettingSearch/SearchIntentReceiver( 1301): action : android.intent.action.BOOT_COMPLETED
I/SettingSearch/SearchIntentReceiver( 1301): search setting db init!!
,E/UpdateRequestReceiver( 3150): ignoring update request
,W/ContextImpl( 1301): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
,I/iu.UploadsManager( 2017): End new media; added: 0, uploading: 0, time: 329 ms
,I/System.out( 2730): Thread-326(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 2730): Thread-326(ApacheHTTPLog):isShipBuild true
I/System.out( 2730): Thread-326(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 2730): Thread-326(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10087
,I/ActivityManager( 1017): Killing 1610:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,E/UpdateRequestReceiver( 3150): ignoring update request
,D/TimaKeyStoreProvider( 3233): TimaSignature is unavailable
,D/ActivityThread( 3233): Added TimaKeyStore provider
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/SensorService( 1017): [SO] -0.421 -0.019 9.902
,D/SensorService( 1017): [SO] [100 -> 255]
,E/UpdateRequestReceiver( 3150): ignoring update request,
,I/SettingSearch/SearchIntentReceiver( 1301): BOOT_COMPLETED call InitSerachDBThread thread start!,
,E/Zygote  ( 3256): MountEmulatedStorage()
I/libpersona( 3256): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3256): v2
I/libpersona( 3256): KNOX_SDCARD not a persona
,E/USB_UICC(  308): Timeout! No signal received. Retry num = 28,
I/ActivityManager( 1017): Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3256 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/WebViewFactory( 3211): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,I/SELinux ( 3256): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/DIAGMON_AGENT( 3193): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0,
,E/SMD     (  295): DCD OFF
I/SELinux ( 3256): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3256): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DIAGMON_AGENT( 3193): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
E/Zygote  ( 3265): MountEmulatedStorage()
E/Zygote  ( 3265): v2
I/libpersona( 3265): KNOX_SDCARD checking this for 10088
I/libpersona( 3265): KNOX_SDCARD not a persona
I/SELinux ( 3265): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3265 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 2367:com.sec.tcpdumpservice/1000 (adj 15): empty #31
I/SELinux ( 3265): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3265): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 3256): TimaSignature is unavailable
D/ActivityThread( 3256): Added TimaKeyStore provider
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/DIAGMON_AGENT( 3193): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/DIAGMON_AGENT( 3193): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 3193): [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
I/DIAGMON_AGENT( 3193): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
I/ServiceManager(  328): Waiting for service AtCmdFwd...
,D/TimaKeyStoreProvider( 3265): TimaSignature is unavailable
,D/ActivityThread( 3265): Added TimaKeyStore provider
,E/Zygote  ( 3286): MountEmulatedStorage()
E/Zygote  ( 3286): v2
I/libpersona( 3286): KNOX_SDCARD checking this for 10146
I/libpersona( 3286): KNOX_SDCARD not a persona
,I/SELinux ( 3286): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3286 uid=10146 gids={50146, 9997} abi=armeabi-v7a
,I/SELinux ( 3286): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3286): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/LibraryLoader( 3211): Loading: webviewchromium
,I/ActivityManager( 1017): Waited long enough for: ServiceRecord{18cf4694 u0 com.samsung.hs20settings/.WifiHs20UtilityService}
,I/LibraryLoader( 3211): Time to load native libraries: 6 ms (timestamps 4263-4269)
I/LibraryLoader( 3211): Expected native library version number "",actual native library version number ""
,D/TimaKeyStoreProvider( 3286): TimaSignature is unavailable
D/ActivityThread( 3286): Added TimaKeyStore provider
,W/ResourcesManager( 3256): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/libprocessgroup( 1017): failed to open /acct/uid_10014/pid_1610/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2367/cgroup.procs: No such file or directory
,E/Zygote  ( 3302): MountEmulatedStorage(),
E/Zygote  ( 3302): v2
I/ActivityManager( 1017): Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3302 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/libpersona( 3302): KNOX_SDCARD checking this for 1000
I/libpersona( 3302): KNOX_SDCARD not a persona
,I/SELinux ( 3302): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3302): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 3302): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3302): TimaSignature is unavailable
,D/ActivityThread( 3302): Added TimaKeyStore provider
,I/SurfaceFlinger(  258): id=6 Removed Mauncher (5/8)
,I/SurfaceFlinger(  258): id=6 Removed Mauncher (-2/8)
,I/FOTA    ( 3256): [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 17781(896KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/33MB, paused 2.290ms total 188.261ms
,V/WebViewChromiumFactoryProvider( 3211): Binding Chromium to main looper Looper (main, tid 1) {32103788}
,I/System.out( 2730): SyncManager calls detatch()
,I/LibraryLoader( 3211): Expected native library version number "",actual native library version number ""
,I/chromium( 3211): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3211): Initializing chromium process, renderers=0
,W/art     ( 3211): Attempt to remove local handle scope entry from IRT, ignoring
,W/ResourcesManager( 3233): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3233): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/chromium( 3211): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 3211): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 3211): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3256): [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
,I/DBG_DM  ( 3256): [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
,I/DBG_DM  ( 3256): [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,E/Zygote  ( 3334): MountEmulatedStorage()
I/libpersona( 3334): KNOX_SDCARD checking this for 10088
E/Zygote  ( 3334): v2
I/libpersona( 3334): KNOX_SDCARD not a persona
,I/SELinux ( 3334): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3334 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 3334): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 3334): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/Adreno-EGL( 3211): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 3211): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 3211): Build Date: 04/06/15 Mon
I/Adreno-EGL( 3211): Local Branch: 
I/Adreno-EGL( 3211): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 3211): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 3211):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/TimaKeyStoreProvider( 3334): TimaSignature is unavailable
,D/ActivityThread( 3334): Added TimaKeyStore provider
,V/JNIHelp ( 3233): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 3302): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,E/Zygote  ( 3356): MountEmulatedStorage()
,E/Zygote  ( 3356): v2
I/libpersona( 3356): KNOX_SDCARD checking this for 10008
I/libpersona( 3356): KNOX_SDCARD not a persona
,I/SELinux ( 3356): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3356): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 3356): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 3302): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/ActivityManager( 1017): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3356 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/DBG_POLICYDM( 3302): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,I/DBG_POLICYDM( 3302): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 3302): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,I/DBG_POLICYDM( 3302): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
W/ActivityThread( 3233): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3233): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bdf865c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
D/TimaKeyStoreProvider( 3356): TimaSignature is unavailable
I/ProviderInstaller( 3233): Installed default security provider GmsCore_OpenSSL
,D/ActivityThread( 3356): Added TimaKeyStore provider,
,I/DBG_POLICYDM( 3302): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,I/DBG_POLICYDM( 3302): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,I/DBG_POLICYDM( 3302): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache]
,I/DBG_POLICYDM( 3302): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 3302): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
I/DBG_POLICYDM( 3302): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,I/DBG_POLICYDM( 3302): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 3302): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!,
I/ActivityManager( 1017): Killing 2378:com.sec.android.app.sbrowser/u0a127 (adj 15): empty #31
I/DBG_POLICYDM( 3302): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,I/DBG_POLICYDM( 3302): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,W/libprocessgroup( 1017): failed to open /acct/uid_10127/pid_2378/cgroup.procs: No such file or directory
,I/DBG_DM  ( 3256): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,I/DBG_DM  ( 3256): [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,W/ContextImpl( 3256): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,I/DBG_DM  ( 3256): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,I/DBG_DM  ( 3256): [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,I/DBG_DM  ( 3256): [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,D/OverheatReceiver( 1173): onReceive() getAction : android.intent.action.BOOT_COMPLETED
,I/DBG_DM  ( 3256): [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,I/DBG_DM  ( 3256): [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
,D/OverheatReceiver( 1173): into the SAFE_MODE_ACTION
D/OverheatReceiver( 1173): VZW on -> change to Global UX [safe mode]
,I/DBG_DM  ( 3256): [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
,I/DBG_DM  ( 3256): [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
,D/OverheatReceiver( 1173): isSafeMode = false
,D/BootupListener( 1448): intent.getAction() = android.intent.action.BOOT_COMPLETED
,D/SettingsProvider( 1017): name = internet_call_settings_visibility
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1001
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/PhoneUtilsCommon( 1448): isSupportVoLTE is false.
,I/DBG_DM  ( 3256): [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
,I/DBG_DM  ( 3256): [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
,I/DBG_DM  ( 3256): [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
,I/DBG_DM  ( 3256): [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
,I/DBG_DM  ( 3256): [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
,I/DBG_DM  ( 3256): [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,I/com.dropbox.android.service.DropboxNetworkReceiver( 3265): Setting receiver enabled: false
,I/DBG_DM  ( 3256): [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
,I/DBG_DM  ( 3256): [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
,W/ContextImpl( 3256): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
,W/GAV2    ( 2730): SyncManager-thalitester@gmail.com: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,I/DBG_DM  ( 3256): [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
,I/DBG_DM  ( 3256): [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
,I/DBG_DM  ( 3256): [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
,I/DBG_DM  ( 3256): [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
,E/ActivityThread( 3265): Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
I/Telecom ( 1431): InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,W/chromium( 3211): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,I/DBG_DM  ( 3256): [com.wssyncmldm.XDMService(155/onStartCommand)] 
,W/chromium( 3211): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 3302): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT,
,E/Zygote  ( 3389): MountEmulatedStorage()
E/Zygote  ( 3389): v2
I/libpersona( 3389): KNOX_SDCARD checking this for 10052
I/libpersona( 3389): KNOX_SDCARD not a persona
,I/DBG_POLICYDM( 3302): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
I/SELinux ( 3389): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3389): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 3389): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3389 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 2400:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,I/DBG_DM  ( 3256): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/art     (  317): Explicit concurrent mark sweep GC freed 8732(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 606us total 21.512ms
,I/DBG_POLICYDM( 3302): [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,I/DBG_POLICYDM( 3302): [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 18.263ms
,D/TimaKeyStoreProvider( 3389): TimaSignature is unavailable,
D/ActivityThread( 3389): Added TimaKeyStore provider
I/dbxyzptlk.db240408.D.h( 3265): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
W/art     ( 3211): Attempt to remove local handle scope entry from IRT, ignoring
I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 584us total 18.613ms,
I/Telecom ( 1431): InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
I/DBG_DM  ( 3256): [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,W/AwContents( 3211): onDetachedFromWindow called when already detached. Ignoring
,I/dbxyzptlk.db240408.D.h( 3265): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
,I/dbxyzptlk.db240408.D.h( 3265): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
,D/PhoneWindow( 3211): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 3211): *FMB* installDecor flags : 8456448
,I/DBG_POLICYDM( 3302): [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,I/DBG_DM  ( 3256): [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
D/SystemWebViewEngine( 3211): CordovaWebView is running on device made by: samsung
,W/art     ( 3211): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3211): Attempt to remove local handle scope entry from IRT, ignoring
,I/DBG_POLICYDM( 3302): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 3302): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 3302): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 3302): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 3302): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 3302): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 3302): [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,I/DBG_POLICYDM( 3302): [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,I/DBG_POLICYDM( 3302): [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,I/DBG_POLICYDM( 3302): [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
,I/DBG_POLICYDM( 3302): [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,I/DBG_POLICYDM( 3302): [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,I/DBG_POLICYDM( 3302): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,E/USB_UICC(  308): Timeout! No signal received. Retry num = 29
,I/DBG_POLICYDM( 3302): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2015/11/25/15:58:24
,I/DBG_POLICYDM( 3302): [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2015/11/25/15:11:34
,I/DBG_POLICYDM( 3302): [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,I/DBG_POLICYDM( 3302): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,I/DBG_POLICYDM( 3302): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,D/OpenGLRenderer( 3211): Render dirty regions requested: true
I/DBG_POLICYDM( 3302): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,I/DBG_POLICYDM( 3302): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,I/DBG_POLICYDM( 3302): [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
I/DBG_POLICYDM( 3302): [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,I/DBG_POLICYDM( 3302): [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
,I/DBG_POLICYDM( 3302): [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
,I/DBG_POLICYDM( 3302): [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
,I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false,
,D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
W/ContextImpl( 3233): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
,D/PhoneWindow( 3211): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 3211): *FMB* isFloatingMenuEnabled return false
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2400/cgroup.procs: No such file or directory
,I/SurfaceFlinger(  258): id=11 createSurf (1x1),1 flag=404, NainActivit
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/InputDispatcher( 1017): Focus entered window: 3211
,E/Zygote  ( 3417): MountEmulatedStorage()
,E/Zygote  ( 3417): v2
I/libpersona( 3417): KNOX_SDCARD checking this for 10014
I/libpersona( 3417): KNOX_SDCARD not a persona
,I/SELinux ( 3417): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1017): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3417 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 3417): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 3211): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 3211): Initialized EGL, version 1.4
,E/SELinux ( 3417): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/OpenGLRenderer( 3211): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 3211): Enabling debug mode 0
,D/TimaKeyStoreProvider( 3417): TimaSignature is unavailable
,D/ActivityThread( 3417): Added TimaKeyStore provider,
,I/DBG_POLICYDM( 3302): [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1173): Icon Only
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/PanelView( 1173): There is/are notification(s) 
,I/Timeline( 3211): Timeline: Activity_idle id: android.os.BinderProxy@390492b8 time:35315
,I/ActivityManager( 1017): Displayed Component not be shown by security: +1s451ms
,D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1017): mDVFSHelper.release()
,I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{d5ee236 u0 com.example.hello/.MainActivity t2} time:35328
,D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@11
,I/DBG_POLICYDM( 3302): [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/LocationManagerService( 1017): getProviders()=[passive]
,E/Zygote  ( 3447): MountEmulatedStorage()
E/Zygote  ( 3447): v2
I/libpersona( 3447): KNOX_SDCARD checking this for 1000
I/libpersona( 3447): KNOX_SDCARD not a persona
,I/SELinux ( 3447): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3447): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1017): Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3447 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 3447): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Killing 2512:com.sec.android.app.camera/u0a135 (adj 15): empty #31
I/ActivityManager( 1017): Killing 2496:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #32
I/ActivityManager( 1017): Killing 2447:com.wsomacp/u0a23 (adj 15): empty #33
I/dbxyzptlk.db240408.D.h( 3265): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
I/DBG_DM  ( 3256): [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
I/ActivityManager( 1017): Killing 2320:com.sec.android.app.mt/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3447): TimaSignature is unavailable
D/ActivityThread( 3447): Added TimaKeyStore provider
,I/ContactAccountLoggerTas( 3389): canRun() : Opted Out
,I/SurfaceFlinger(  258): id=10 Removed iello (7/8)
,I/SurfaceFlinger(  258): id=10 Removed iello (-2/8)
,I/DBG_POLICYDM( 3302): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,D/breakpad( 3265): breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,I/DBG_DM  ( 3256): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,V/audio_hw_primary(  285): adev_get_parameters: enter: keys - call_forwarding
,D/audio_hw_extn(  285): audio_extn_get_parameters: returns 
V/msm8974_platform(  285): platform_get_parameters: exit: returns - 
V/audio_hw_primary(  285): adev_get_parameters: exit: returns - call_forwarding=false
I/str_params(  285): key: 'call_forwarding' value: ''
V/InCall  ( 1939): ProximitySensor -  - screenonImmediately: false
V/InCall  ( 1939): ProximitySensor -  - mFromRcsShare: false
,I/InCall  ( 1939): ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,I/DBG_DM  ( 3256): [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,D/ScoverManager( 1939): serviceVersion : 16908288
,D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
,I/DBG_DM  ( 3256): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,D/InCall  ( 1939): InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
,D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
,D/InCall  ( 1939): InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
I/InCall  ( 1939): InCallPresenter -  - InCallState = NO_CALLS
,I/Telecom ( 1431): ProximitySensorManager: Proximity wake lock already released
,I/InCall  ( 1939): InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
D/InCall  ( 1939): InCallPresenter -  - dismissCoverDialog()...
,I/InCall  ( 1939): CallSContextMotion - stopPutDownListening
,I/SamsungIME( 1824): getCurrentCandidateView
,D/InCall  ( 1939): StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,E/Tethering( 1017): No numeric data
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,E/Tethering( 1017): No numeric data
,I/DBG_FMMDM( 3447): [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,D/PhoneStatusBarView( 1173): setCallBackground:0
,D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
,D/InCall  ( 1939): InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
,D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@11
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1017): failed to open /acct/uid_10139/pid_2496/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10023/pid_2447/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10135/pid_2512/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2320/cgroup.procs: No such file or directory
,E/Tethering( 1017): No numeric data
,I/chromium( 3211): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/Tethering( 1017): No numeric data
,I/DBG_POLICYDM( 3302): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
E/AndroidProtocolHandler( 3211): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/DBG_POLICYDM( 3302): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,D/VideoCallManager( 1939): Instantiating VideoCallManager
,E/Tethering( 1017): No numeric data
,E/Tethering( 1017): No numeric data
,I/DBG_FMMDM( 3447): [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,I/DBG_FMMDM( 3447): [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,I/DBG_FMMDM( 3447): [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
I/com.dropbox.sync.android.a( 3265): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/DBG_POLICYDM( 3302): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,E/Zygote  ( 3480): MountEmulatedStorage()
E/Zygote  ( 3480): v2
I/libpersona( 3480): KNOX_SDCARD checking this for 1000
I/libpersona( 3480): KNOX_SDCARD not a persona
,I/SELinux ( 3480): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3480): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3480): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3480 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,D/[SBeam] ( 1301): SBeamEnabler.isSBeamSupported : [-1]
,D/[SBeam] ( 1301): SBeamEnabler.isSBeamSupported : EXIST
,E/        ( 1939): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1939): took 2.574479ms for 0*0 texture 0
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1017): getStreamVolume 3 index 70
,D/SamsungIME( 1824): Dismiss ExpandCandiate
I/GFX generate_partition_tables( 1939): took 5.796926ms for 0*0 texture 0
,I/MediaRouter( 3389): Found default route: MediaRouter.RouteInfo{ uniqueId=android/mo:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/GFX raster( 1939): took 13.182290ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1939): Bitmap=0xb8395108 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb83949d8 counterpartCT=4 counterpartW=176 counterparth=144
,I/FavoriteContactNamesSup( 3389): get() : Execute runnable (UI thread)
,I/ContactLabelSupplier( 3389): get() : Execute runnable (UI thread)
,E/        ( 1939): GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
,I/Adreno-EGL( 1939): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1939): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1939): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1939): Local Branch: 
I/Adreno-EGL( 1939): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1939): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1939):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/JsMessageQueue( 3211): Set native->JS mode to OnlineEventsBridgeMode
,D/TimaKeyStoreProvider( 3480): TimaSignature is unavailable
,D/ActivityThread( 3480): Added TimaKeyStore provider
,I/GFX GPU raster( 1939): eglCreateImageKHR: EGL_SUCCESS,
,I/com.dropbox.sync.android.ad( 3265): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A300FU armeabi-v7a; en_US))
D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4303, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,I/glCompressedTexImage2D( 1939): took 0.339322ms for 320*61440 texture 37809
E/Tethering( 1017): No numeric data
,I/draw setup( 1939): took 12.268385ms for 320*240 texture 37809
E/GFX GPU raster( 1939): drawn
,I/ContactLabelSupplier( 3389): get() : OptedIn = false
,I/GFX GPU raster ASTC( 1939): took 46.895625ms for 320*240 texture 12
I/GFX raster( 1939): took 47.003125ms for 320*240 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1939): Bitmap=0xb8395088 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb8394bf0 counterpartCT=4 counterpartW=320 counterparth=240
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/PowerUI ( 1173): Cable  true --> true mBootCompleted : true
D/PowerUI ( 1173): Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
,E/Tethering( 1017): No numeric data
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,E/Tethering( 1017): No numeric data
,E/        ( 1939): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,I/GFX GPU raster( 1939): eglCreateImageKHR: EGL_SUCCESS,
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,I/glCompressedTexImage2D( 1939): took 0.348541ms for 480*122880 texture 37813,
I/draw setup( 1939): took 0.897396ms for 480*640 texture 37813
E/GFX GPU raster( 1939): drawn
V/HeadsetService( 2653): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,I/DBG_POLICYDM( 3302): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0],
,I/GFX GPU raster ASTC( 1939): took 9.709583ms for 480*640 texture 12,
I/GFX raster( 1939): took 9.799427ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1939): Bitmap=0xb8394bf0 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb85d6648 counterpartCT=4 counterpartW=480 counterparth=640
,D/HeadsetStateMachine( 2653): Disconnected process message: 10,
,I/chromium( 3211): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 3211): 
,I/DBG_POLICYDM( 3302): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,I/SamsungIME( 1824): getDebugLevel  : 0x4f4c
,E/        ( 1939): GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,I/GFX GPU raster( 1939): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1939): took 0.478854ms for 440*116864 texture 37809
I/draw setup( 1939): took 0.967552ms for 440*330 texture 37809
E/GFX GPU raster( 1939): drawn
,I/GFX GPU raster ASTC( 1939): took 10.581927ms for 440*330 texture 12
I/GFX raster( 1939): took 11.225833ms for 440*330 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1939): Bitmap=0xb85d6628 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb85d69f8 counterpartCT=4 counterpartW=440 counterparth=330
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/        ( 1939): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640,
,I/GFX GPU raster( 1939): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1939): took 0.698542ms for 480*163840 texture 37811
I/draw setup( 1939): took 1.193698ms for 480*640 texture 37811
E/GFX GPU raster( 1939): drawn
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/jxcore_app_log( 3211): JniHelper::setJavaVM(0xb7fea448), pthread_self() = -1202202984
,D/JX-Cordova( 3211): jxcore cordova android initializing
,I/GFX GPU raster ASTC( 1939): took 8.354167ms for 480*640 texture 12
I/GFX raster( 1939): took 8.433906ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1939): Bitmap=0xb85d6468 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb85e9490 counterpartCT=4 counterpartW=480 counterparth=640
,E/Tethering( 1017): No numeric data
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3507): MountEmulatedStorage(),
E/Zygote  ( 3507): v2
I/libpersona( 3507): KNOX_SDCARD checking this for 10055
I/libpersona( 3507): KNOX_SDCARD not a persona
I/SELinux ( 3507): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3507): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3507): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3507 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
E/        ( 1939): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/GFX construct_block_size_descriptor_2d second part( 1939): took 2.412136ms for 0*0 texture 0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/jxcore-log( 3211): Initializing JXcore engine
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/jxcore-log( 3211): JXcore engine is ready
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/jxcore-log( 3211): Starting JXcore engine,
I/GFX generate_partition_tables( 1939): took 7.892917ms for 0*0 texture 0
I/GFX raster( 1939): took 12.324532ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1939): Bitmap=0xb85c6578 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb85e94b0 counterpartCT=4 counterpartW=176 counterparth=144
,E/        ( 1939): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
E/Zygote  ( 3523): MountEmulatedStorage()
E/Zygote  ( 3523): v2
I/libpersona( 3523): KNOX_SDCARD checking this for 10090
I/libpersona( 3523): KNOX_SDCARD not a persona
I/GFX construct_block_size_descriptor_2d second part( 1939): took 2.817865ms for 0*0 texture 0
I/SELinux ( 3523): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 3523): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 3523): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GFX generate_partition_tables( 1939): took 6.760521ms for 0*0 texture 0
,I/GFX raster( 1939): took 11.988906ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1939): Bitmap=0xb85d6ad8 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb85eb1a0 counterpartCT=4 counterpartW=176 counterparth=144
,D/ScoverManager( 1939): registerListener
,D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
D/TimaKeyStoreProvider( 3507): TimaSignature is unavailable
I/ActivityManager( 1017): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3523 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
D/CoverManager.StateNotifier( 1017): registerListenerCallback : binder = android.os.BinderProxy@2b01a6ea, pid : 1939, uid : 1001, type : 1
,D/ActivityThread( 3507): Added TimaKeyStore provider
I/ActivityManager( 1017): Killing 2582:com.android.calendar/u0a131 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3523): TimaSignature is unavailable
D/ActivityThread( 3523): Added TimaKeyStore provider
,I/PCWCLIENTTRACE_LOG( 3480): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 3480): DEFAULT_LOGLEVEL : 3
,I/PCWCLIENTTRACE_DMDBOpenHelper( 3480): new DMDBOpenHelper instance
,E/audit   ( 1878): type=1400 msg=audit(1448460695.236:205): avc:  denied  { ioctl } for  pid=3211 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1878):  SEPF_SM-A300FU_5.0.2_0027
,E/audit   ( 1878): type=1300 msg=audit(1448460695.236:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=be845d58 items=0 ppid=317 ppcomm=main pid=3211 auid=4294967295 uid=10333 gid=10333 euid=10333 suid=10333 fsuid=10333 egid=10333 sgid=10333 fsgid=10333 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1878): type=1320 msg=audit(1448460695.236:205): 
,D/PCWCLIENTTRACE_DMContentProvider( 3480): [URIMatcher] - result : 2
,D/elm:15121( 3523): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,W/libprocessgroup( 1017): failed to open /acct/uid_10131/pid_2582/cgroup.procs: No such file or directory
D/elm:15121( 3523): ELMEngine.ELMEngine( context ).
,D/elm:15121( 3523): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 3523): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:15121( 3523): ElmAgentService : onCreate()
,D/elm:15121( 3523): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15121( 3523): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
D/elm:15121( 3523): BootCompletedState : startBootCompleted() call
,D/elm:15121( 3523): MDMBridge.getAllLicenseInfoFromSDK()
,I/DBG_FMMDM( 3447): [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,I/elm:15121( 3523): Get License : 0
,D/elm:15121( 3523): ElmAgentService : onDestroy().
,I/ActivityManager( 1017): Killing 2672:com.android.keychain/1000 (adj 15): empty #31
,E/USB_UICC(  308): Timeout! No signal received. Retry num = 30
,I/DBG_FMMDM( 3447): [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDM( 3447): [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/UserAnalysis.PlaceProvider( 3507): PlaceProvider onCreate()
,V/EmergencyMode( 1415): [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,E/Zygote  ( 3542): MountEmulatedStorage()
E/Zygote  ( 3542): v2
I/libpersona( 3542): KNOX_SDCARD checking this for 1000
I/libpersona( 3542): KNOX_SDCARD not a persona
,I/SELinux ( 3542): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,V/VibratorService( 1017): hasVibrator - useVibetonz: true,
I/SELinux ( 3542): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3542 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux ( 3542): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1017): Killing 2712:com.android.chrome/u0a77 (adj 15): empty #31
,I/ActivityManager( 1017): Killing 2465:com.sec.android.gallery3d/u0a39 (adj 15): empty #32
,D/InCall  ( 1939): InCallPresenter -  - Finished InCallPresenter.setUp
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/NotificationAccessSettings( 1301): Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,V/VibratorService( 1017): hasVibrator - useVibetonz: true
,D/TimaKeyStoreProvider( 3542): TimaSignature is unavailable
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
D/ActivityThread( 3542): Added TimaKeyStore provider
,I/SamsungIME( 1824): getDebugLevel  : 0x4f4c
,V/EmergencyMode( 1415): [EmergencyBase] setBootTime
,V/EmergencyMode( 1415): [EmergencyFactory] No Recovery State, kill my self.
,V/VibratorService( 1017): hasVibrator - useVibetonz: true
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/jxcore-log( 3211): Platform android,
W/jxcore-log( 3211): 
W/jxcore-log( 3211): Process ARCH arm
W/jxcore-log( 3211): 
,W/ResourcesManager( 1301): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,I/ActivityManager( 1017): Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3557 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 3557): MountEmulatedStorage()
I/libpersona( 3557): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3557): v2
I/libpersona( 3557): KNOX_SDCARD not a persona
I/SELinux ( 3557): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3557): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3557): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/UserAnalysis.SecureDbManager( 3507): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 3507): SecurePlaceDbHelper() 
D/UserAnalysis( 3507): Create SecureDbHelper
,I/System.out( 3265): Thread-429(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 3265): Thread-429(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3265): Thread-429(ApacheHTTPLog):isShipBuild true
I/System.out( 3265): Thread-429(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 3265): Thread-429(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,E/USB_UICC(  308): Timeout! No signal received. Reach maximum retries!
E/USB_UICC(  308): usb_uicc_init_qmi failed ! 
I/USB_UICC(  308): usb_uicc_cleanup, signal received: 0x3 
I/USB_UICC(  308): usb_uicc_cleanup, Issuing QMI deinit ... 
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10088
,I/SamsungIME( 1824): KeybaordView init() : load resources
,E/YouTube MDX( 3233): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/DBG_FMMDS( 3542): [50.18.150420][Line:56][onCreate] FMMDS Application Start
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2672/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10039/pid_2465/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10077/pid_2712/cgroup.procs: No such file or directory
,I/jxcore-log( 3211): JXcore Cordova bridge is ready!
I/jxcore-log( 3211): 
W/jxcore-log( 3211): JXcore engine is started
,I/DBG_FMMDS( 3542): [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,D/TimaKeyStoreProvider( 3557): TimaSignature is unavailable
,D/ActivityThread( 3557): Added TimaKeyStore provider
,D/IntelligenceServiceApplication( 3507): onCreate()
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 3507): Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/IntelligenceServiceApplication( 3507): no applications having user consent for prediction
,E/Zygote  ( 3580): MountEmulatedStorage()
E/Zygote  ( 3580): v2
I/libpersona( 3580): KNOX_SDCARD checking this for 10056
I/libpersona( 3580): KNOX_SDCARD not a persona
,I/SELinux ( 3580): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3580 uid=10056 gids={50056, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux ( 3580): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3580): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Killing 2776:com.android.email/u0a141 (adj 15): empty #31
,V/PlaceDetection v1.0.19 ( 3507): [PlaceDetection::stopService] Service stopped.
E/jxcore-log( 3211): >> samsung-SM-A300FU
E/jxcore-log( 3211): 
,I/CameraApp( 3557): CameraApp.onCreate()... mFeature : null
I/testFeature( 3557): Feature.Feature(context)
I/testFeature( 3557): Feature.readInternalDefaultXml()
I/testFeature( 3557): ResetFeatureValue
,I/jxcore-log( 3211): Total memory 1451114496
I/jxcore-log( 3211): 
I/jxcore-log( 3211): Free memory 38711296
I/jxcore-log( 3211): 
I/jxcore-log( 3211): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3211): 
I/jxcore-log( 3211): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3211): 
,I/CameraFirmware_broadcast( 3557): CameraFirmwareBroadCastReceiver...
,D/TimaKeyStoreProvider( 3580): TimaSignature is unavailable
,D/ScoverManager( 1301): serviceVersion : 16908288
I/SamsungIME( 1824): getCurrentKeyboard
I/SamsungIME( 1824): getTextKeyboard
,I/jxcore-log( 3211): userPath [ 'www' ]
I/jxcore-log( 3211): 
,D/ActivityThread( 3580): Added TimaKeyStore provider
,I/CameraApp( 3557): CameraApp.getAppFeature()...
,I/jxcore-log( 3211): Size 540 960
I/jxcore-log( 3211): 
,D/PCWCLIENTTRACE_DMContentProvider( 3480): [URIMatcher] - result : 2
I/jxcore-log( 3211): Screen Brightness 255
I/jxcore-log( 3211): 
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/jxcore-log( 3211): Dummy Error Log.
E/jxcore-log( 3211): 
,E/Zygote  ( 3601): MountEmulatedStorage()
,E/Zygote  ( 3601): v2
I/libpersona( 3601): KNOX_SDCARD checking this for 10095
I/libpersona( 3601): KNOX_SDCARD not a persona
,I/SELinux ( 3601): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1017): Start proc com.samsung.android.provider.filterprovider for broadcast com.samsung.android.provider.filterprovider/.FilterProviderReceiver: pid=3601 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
I/SELinux ( 3601): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3601): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/DBG_FMMDS( 3542): Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,D/SamsungIME( 1824): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/DBG_FMMDS( 3542): [50.18.150420][Line:43][xdbDBInit] 
,D/TimaKeyStoreProvider( 3601): TimaSignature is unavailable
D/ActivityThread( 3601): Added TimaKeyStore provider
,V/PlaceDetection v1.0.19 ( 3507): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,D/UserAnalysis.MyPlaceDbPreference( 3507): Constructor Preference
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1017): getStreamVolume 3 index 70
,W/libprocessgroup( 1017): failed to open /acct/uid_10141/pid_2776/cgroup.procs: No such file or directory
,D/PreloadFilterInstaller( 3601): uses FILTER_DB_VER_1
,E/SQLiteLog( 3601): (284) automatic index on titles(filter_id)
,I/FilterProviderReceiver( 3601): onReceive in FilterProviderReceiver
I/FilterProviderReceiver( 3601): onReceive in FilterProviderReceiver when ACTION_BOOT_COMPLETED
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3625): MountEmulatedStorage()
E/Zygote  ( 3625): v2
I/libpersona( 3625): KNOX_SDCARD checking this for 10098
I/libpersona( 3625): KNOX_SDCARD not a persona
,I/SELinux ( 3625): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3625): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3625): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3625 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 2854:com.mobeam.barcodeService/1000 (adj 15): empty #31
,I/DBG_FMMDS( 3542): [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 3625): TimaSignature is unavailable
,D/ActivityThread( 3625): Added TimaKeyStore provider
,I/DBG_FMMDS( 3542): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3542): [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,I/DBG_FMMDS( 3542): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3542): [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,I/DBG_FMMDS( 3542): [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
I/DBG_FMMDS( 3542): [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,W/ContextImpl( 3233): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,I/LockPatternUtils( 1301): isSmartCardAuthenticationAvailable: false
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3233): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3233): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,D/Settings_Utils( 1301): isSupportVNFestival SM-A300FU XEO
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/PackageIntentReceiver( 3625): ACTION_BOOT_COMPLETED
,I/ActivityManager( 1017): Killing 1717:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PackageIntentReceiver( 3625): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,W/ResourceType( 1301): Failure getting entry for 0x7f0202b4 (t=1 e=692) (error -75)
,I/FOTA_Client( 3356): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/ResourceType( 1301): Failure getting entry for 0x7f020510 (t=1 e=1296) (error -75)
,I/DBG_DM  ( 3256): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,E/Zygote  ( 3661): MountEmulatedStorage()
,E/Zygote  ( 3661): v2
I/libpersona( 3661): KNOX_SDCARD checking this for 10099
I/libpersona( 3661): KNOX_SDCARD not a persona
,I/SELinux ( 3661): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3661): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3661): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3661 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 2889:flipboard.boxer.app/u0a97 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,I/FactoryTestApp( 2628): [IPCWriterToSecPhoneService$disConnectSecPhoneService](3188)  
,I/FOTA_Client( 3356): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,I/FOTA_Client( 3356): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,I/art     (  317): Explicit concurrent mark sweep GC freed 8706(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 602us total 24.356ms
,I/ActivityManager( 1017): Killing 2903:com.sec.knox.bridge/1000 (adj 15): empty #31
,I/sCloudBackupApp( 3580): sCloudBackupApp Version Info : 4.04.7.KK_APP
,D/TimaKeyStoreProvider( 3661): TimaSignature is unavailable
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 601us total 17.572ms
,D/ActivityThread( 3661): Added TimaKeyStore provider
,I/GAV2    ( 2730): Thread[GAThread,5,main]: No campaign data found.
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 598us total 24.997ms
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2854/cgroup.procs: No such file or directory,
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_1717/cgroup.procs: No such file or directory
,E/Zygote  ( 3680): MountEmulatedStorage(),
,W/FOTA_Client( 3356): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,E/Zygote  ( 3680): v2
I/libpersona( 3680): KNOX_SDCARD checking this for 10058
I/libpersona( 3680): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3680 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 3680): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Killing 2924:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
,I/SELinux ( 3680): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/SELinux ( 3680): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/Zygote  ( 3693): MountEmulatedStorage()
E/Zygote  ( 3693): v2
I/libpersona( 3693): KNOX_SDCARD checking this for 10013
I/libpersona( 3693): KNOX_SDCARD not a persona
,I/SELinux ( 3693): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3693 uid=10013 gids={50013, 9997} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 3680): TimaSignature is unavailable
I/ActivityManager( 1017): Killing 2331:com.sec.modem.settings/1000 (adj 15): empty #31
D/ActivityThread( 3680): Added TimaKeyStore provider
I/SELinux ( 3693): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3693): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 3693): TimaSignature is unavailable
,D/ActivityThread( 3693): Added TimaKeyStore provider
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/libprocessgroup( 1017): failed to open /acct/uid_10097/pid_2889/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2903/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2331/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10148/pid_2924/cgroup.procs: No such file or directory
,I/jxcore-log( 3211): getBuffer is called!!!!
I/jxcore-log( 3211): 
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 22222(1240KB) AllocSpace objects, 3(54KB) LOS objects, 33% free, 22MB/33MB, paused 2.153ms total 227.324ms
,W/ActivityManager( 1017): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,V/OneTimeInitializerReceiver( 3693): OneTimeInitializerReceiver.onReceive
,V/VibratorService( 1017): hasVibrator - useVibetonz: true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,V/OneTimeService( 3693): OneTimeService.onHandleIntent
,I/ExternalOEMControlProvider( 3680): onCreate
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/SMD     (  295): DCD OFF,
,E/Zygote  ( 3719): MountEmulatedStorage()
,E/Zygote  ( 3719): v2
I/libpersona( 3719): KNOX_SDCARD checking this for 1000
I/libpersona( 3719): KNOX_SDCARD not a persona
,I/SELinux ( 3719): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1017): Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3719 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,I/ActivityManager( 1017): Killing 2221:flipboard.app/u0a96 (adj 15): empty #31
,I/SELinux ( 3719): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/SELinux ( 3719): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SettingsProvider( 1017): name = PREVIOUS_SYS_TIME
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1017): selectionArgs: false
W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/SettingsProvider( 1017): selectionArgs: 10058
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/SettingsProvider( 1017): ret = -1
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10058
,D/SettingsProvider( 1017): name = PREVIOUS_ELAPSED_TIME
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10058
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,I/ServiceManager(  328): Waiting for service AtCmdFwd...
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/TimaKeyStoreProvider( 3719): TimaSignature is unavailable
,D/ActivityThread( 3719): Added TimaKeyStore provider
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10058
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,I/ActivityManager( 1017): Killing 2970:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,W/ResourcesManager( 3719): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ActivityManager( 1017): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/ActivityManager( 1017): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1665): Starting #4
,I/Hs20UtilService( 1665): Message received 5003
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1017): failed to open /acct/uid_10096/pid_2221/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_1101/pid_2970/cgroup.procs: No such file or directory
,I/ServiceMode( 3719): received = ACTION_BOOT_COMPLETED
,I/ServiceMode( 3719): setReferenceIsDumpState : 0
,E/Zygote  ( 3758): MountEmulatedStorage(),
E/Zygote  ( 3758): v2
I/libpersona( 3758): KNOX_SDCARD checking this for 10018
I/libpersona( 3758): KNOX_SDCARD not a persona
,I/SELinux ( 3758): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/Gmail   ( 3661): getAccountsCursor
I/ActivityManager( 1017): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3758 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
I/Gmail   ( 3661): Observing account changes for notifications
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/SELinux ( 3758): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3758): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
W/MessageQueue( 3233): Handler (android.os.Handler) {23bc7684} sending message to a Handler on a dead thread
W/MessageQueue( 3233): java.lang.IllegalStateException: Handler (android.os.Handler) {23bc7684} sending message to a Handler on a dead thread
W/MessageQueue( 3233): 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:325)
W/MessageQueue( 3233): 	at android.os.Handler.enqueueMessage(Handler.java:631)
W/MessageQueue( 3233): 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
W/MessageQueue( 3233): 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
W/MessageQueue( 3233): 	at android.os.Handler.post(Handler.java:326)
W/MessageQueue( 3233): 	at ffw.a(SourceFile:327)
W/MessageQueue( 3233): 	at guw.a(SourceFile:120)
W/MessageQueue( 3233): 	at guf.c(SourceFile:26)
W/MessageQueue( 3233): 	at gui.run(SourceFile:297)
W/MessageQueue( 3233): 	at android.os.Handler.handleCallback(Handler.java:739)
W/MessageQueue( 3233): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/MessageQueue( 3233): 	at android.os.Looper.loop(Looper.java:145)
W/MessageQueue( 3233): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,D/PackageManager( 1017): [MSG] MCS_UNBIND
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,V/GLSActivity( 1626): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Zygote  ( 3775): MountEmulatedStorage()
E/Zygote  ( 3775): v2
I/libpersona( 3775): KNOX_SDCARD checking this for 1000
I/libpersona( 3775): KNOX_SDCARD not a persona
,I/SELinux ( 3775): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3775): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3775 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux ( 3775): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Killing 2350:com.android.mms/u0a41 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3758): TimaSignature is unavailable
,D/ActivityThread( 3758): Added TimaKeyStore provider
,I/ActivityManager( 1017): Killing 3029:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3775): TimaSignature is unavailable
,D/ActivityThread( 3775): Added TimaKeyStore provider
,I/art     ( 1626): Explicit concurrent mark sweep GC freed 12297(857KB) AllocSpace objects, 9(144KB) LOS objects, 40% free, 7MB/13MB, paused 1.074ms total 60.716ms
,I/System.out( 3265): pool-10-thread-1 calls detatch()
,D/AndroidHttpClient( 3233): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A300FU Build/LRX22G)
D/AndroidHttpClient( 3233): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,I/System.out( 3233): Thread-465(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 3233): Thread-465(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 3233): Thread-465(ApacheHTTPLog):isShipBuild true
I/System.out( 3233): Thread-465(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 3233): Thread-465(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/GAV2    ( 3661): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10161
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/RlzPingService( 3417): Setting next ping for 1449065496629
,D/NPS_WSSNPS( 3775): [] android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 3775): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 ,
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/NPS_WSSNPS( 3775): [] Service onCreate!!
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/ContextImpl( 1918): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,E/Zygote  ( 3798): MountEmulatedStorage(),
,I/libpersona( 3798): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3798): v2
,I/libpersona( 3798): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3798 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/LockPatternUtils( 1301): isSmartCardAuthenticationAvailable: false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,D/SecUISvc( 1918): Service started flags 0 startId 1
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/NPS_WSSNPS( 3775): [50.150321] NpsServiceTask Start
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/SecUISvc( 1918): Thread created.
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3808): MountEmulatedStorage()
E/Zygote  ( 3808): v2
,I/libpersona( 3808): KNOX_SDCARD checking this for 10026
I/libpersona( 3808): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3808 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/KLMS-2.5.123: ( 3758): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Nov 25 15:11:36 GMT+01:00 2015
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/KLMS-2.5.123: ( 3758): KLMSAbstractReciever(): onReceive().END.
,I/SELinux ( 3798): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3808): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3798): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3798): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SELinux ( 3808): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3758): KLMSIntentService(): onCreate()
,E/SELinux ( 3808): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/NPS_WSSNPS( 3775): [50.150321] smlDBHelper
,I/KLMS-2.5.123: ( 3758): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/System.out( 3233): Thread-465 calls detatch()
,E/Zygote  ( 3833): MountEmulatedStorage()
E/Zygote  ( 3833): v2
I/libpersona( 3833): KNOX_SDCARD checking this for 10020
I/libpersona( 3833): KNOX_SDCARD not a persona
,I/KLMS-2.5.123: ( 3758): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/SELinux ( 3833): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3833): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3833 uid=10020 gids={50020, 9997, 1028, 3003} abi=armeabi-v7a
I/KLMS-2.5.123: ( 3758): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
D/TimaKeyStoreProvider( 3808): TimaSignature is unavailable
E/SELinux ( 3833): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityThread( 3808): Added TimaKeyStore provider
,I/KLMS-2.5.123: ( 3758): KLMSIntentService(): BOOT_COMPLETED
,W/ActivityManager( 1017): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 3798): TimaSignature is unavailable
,D/ActivityThread( 3798): Added TimaKeyStore provider
,I/NPS_WSSNPS( 3775): [50.150321] AsyncBulkFlagCheck
,D/CountryDetector( 1017): No listener is left
,I/Gmail   ( 3661): getAccountsCursor
E/Gmail   ( 3661): Error finding the version of the Email provider.....
E/Gmail   ( 3661): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 3661): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 3661): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
E/Gmail   ( 3661): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 3661): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 3661): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 3661): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 3661): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 3661): We do not support migrating this version of the Email provider.
D/TimaKeyStoreProvider( 3833): TimaSignature is unavailable
,D/ActivityThread( 3833): Added TimaKeyStore provider
,I/NPS_WSSNPS( 3775): [50.150321] IsRemain_AsyncBulkCheck
,I/NPS_WSSNPS( 3775): [50.150321] IsRemain_Asyncing nothing
,W/ContextImpl( 3775): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,W/libprocessgroup( 1017): failed to open /acct/uid_10153/pid_3029/cgroup.procs: No such file or directory
,V/GLSActivity( 1626): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/KLMS-2.5.123: ( 3758): KLMSIntentService(): onDestroy()
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/NPS_WSSNPS( 3775): [50.150321] Service onDestroy
,V/GLSActivity( 1626): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DBG_DM  ( 3256): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3859): MountEmulatedStorage()
E/Zygote  ( 3859): v2
I/libpersona( 3859): KNOX_SDCARD checking this for 10102
I/libpersona( 3859): KNOX_SDCARD not a persona
,I/SELinux ( 3859): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3859): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3859): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3859 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/libprocessgroup( 1017): failed to open /acct/uid_10041/pid_2350/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 3859): TimaSignature is unavailable
,D/ActivityThread( 3859): Added TimaKeyStore provider
,D/SettingsProvider( 1017): name = access_control_enabled
,W/ResourcesManager( 3859): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3878): MountEmulatedStorage()
E/Zygote  ( 3878): v2
I/libpersona( 3878): KNOX_SDCARD checking this for 10065,
I/SELinux ( 3878): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/libpersona( 3878): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3878 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 3878): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 3878): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3887): MountEmulatedStorage()
,E/Zygote  ( 3887): v2
I/libpersona( 3887): KNOX_SDCARD checking this for 1000
I/libpersona( 3887): KNOX_SDCARD not a persona
,I/SELinux ( 3887): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3887 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 3887): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1017): Killing 3017:com.sec.android.app.safetyassurance/u0a43 (adj 15): empty #31
E/SELinux ( 3887): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1017): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/TimaKeyStoreProvider( 3878): TimaSignature is unavailable
,D/ActivityThread( 3878): Added TimaKeyStore provider
,I/art     (  317): Explicit concurrent mark sweep GC freed 8713(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 618us total 23.271ms
,I/GoogleHttpClient( 1626): GMS http client unavailable, use old client
,W/ActivityManager( 1017): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/ActivityThread( 3661): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@17a15cf5 that was originally bound here
E/ActivityThread( 3661): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@17a15cf5 that was originally bound here
E/ActivityThread( 3661): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 3661): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 3661): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 3661): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 3661): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 3661): 	at com.android.emailcommon.service.H.a(SourceFile:181)
E/ActivityThread( 3661): 	at com.android.emailcommon.service.H.mb(SourceFile:224)
E/ActivityThread( 3661): 	at com.android.email.service.n.j(SourceFile:160)
E/ActivityThread( 3661): 	at com.android.email.provider.b.a(SourceFile:171)
E/ActivityThread( 3661): 	at com.android.email.provider.b.F(SourceFile:115)
E/ActivityThread( 3661): 	at com.android.email.service.EmailBroadcastProcessorService.kD(SourceFile:305)
E/ActivityThread( 3661): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:130)
E/ActivityThread( 3661): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 3661): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3661): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3661): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager( 1017): Unbind failed: could not find connection for android.os.BinderProxy@1ce53fae
D/TimaKeyStoreProvider( 3887): TimaSignature is unavailable
,D/ActivityThread( 3887): Added TimaKeyStore provider
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 624us total 30.483ms
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 599us total 16.683ms
,E/MTPRx   ( 3887): In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,D/SecContentProvider2( 1017): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 14 selection = getSealedUsbMassStorageState
,D/SecContentProvider2( 1017): mCursor = null
,V/MTPRx   ( 3887): sealedState: false
,V/MTPRx   ( 3887): sealedUsbMassStorageState: false
,D/SettingsProvider( 1017): name = mtp_usb_connection_status
,I/NPS_WSSNPS( 3775): [50.150321] smlBRConfigurationDelete
,D/FileShare-Server( 3878): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,I/NPS_WSSNPS( 3775): [50.150321] smlBRMessageDelete
,I/NPS_WSSNPS( 3775): [50.150321] smlBREmailDelete
,I/NPS_WSSNPS( 3775): [50.150321] smlBRNetworkDelete
,I/NPS_WSSNPS( 3775): [50.150321] smlBRCallLogDelete
I/NPS_WSSNPS( 3775): [50.150321] smlBRMiniDiaryDelete
,I/NPS_WSSNPS( 3775): [50.150321] smlBRPenMemoMDelete
,I/NPS_WSSNPS( 3775): [50.150321] smlBRSMemoDelete
I/NPS_WSSNPS( 3775): [50.150321] cpuBooster release : false
,D/NPS_WSSNPS( 3775): [50.150321] dsServerSocket close
,I/ActivityManager( 1017): Killing 2953:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1017): failed to open /acct/uid_10043/pid_3017/cgroup.procs: No such file or directory
,D/SettingsProvider( 1017): name = media_player_mode
,W/ContextImpl( 1301): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,W/ContextImpl( 1301): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,W/libprocessgroup( 1017): failed to open /acct/uid_10081/pid_2953/cgroup.procs: No such file or directory
,I/SettingSearch/SearchIntentReceiver( 1301): InitSerachDBThread thread end!
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,D/SettingsProvider( 1017): name = mtp_usb_conditions_met
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,I/ActivityManager( 1017): Killing 3072:com.sec.usbsettings/1000 (adj 15): empty #31
,W/Atfwd_Sendcmd(  328): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SQLiteLog( 3661): (283) recovered 19 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,D/SettingsProvider( 1017): name = mtp_running_status
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 3808): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Babel   ( 3859): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 3859): MmsConfig.loadMmsSettings
,I/Babel   ( 3859): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3072/cgroup.procs: No such file or directory
,I/Babel   ( 3859): MmsConfig.loadFromDatabase
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,D/SettingsProvider( 1017): name = media_mount_count
,W/VideoCapabilities( 3859): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 3859): Unsupported mime audio/evrc
,W/AudioCapabilities( 3859): Unsupported mime audio/qcelp
,W/AudioCapabilities( 3859): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 3859): Unsupported mime audio/mpeg-L2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Settings( 3859): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SettingsProvider( 1017): name = mtp_sync_alive
,D/SettingsProvider( 1017): name = sdcard_launch
,W/AudioCapabilities( 3859): Unsupported mime audio/x-ms-wma
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,W/AudioCapabilities( 3859): Unsupported mime audio/x-ima
,E/Babel   ( 3859): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 3859): MmsConfig.loadFromResources
,E/Babel   ( 3859): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3859): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
W/AudioCapabilities( 3859): Unsupported mime audio/qcelp
,W/AudioCapabilities( 3859): Unsupported mime audio/evrc
,D/SettingsProvider( 1017): name = boot_time_connected
,W/VideoCapabilities( 3859): Unsupported mime video/wvc1
,W/VideoCapabilities( 3859): Unsupported mime video/x-ms-wmv
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,D/SettingsProvider( 1017): name = mtp_open_session
,E/File    ( 3661): fail readDirectory() errno=2
,I/Icing   ( 2017): Storage manager: low false usage 2.07MB avail 8.51GB capacity 9.90GB
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,I/PCWCLIENTTRACE_PushUtil( 3480): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3480): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3480): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3480): [onReceive] - android.intent.action.BOOT_COMPLETED
D/PCWCLIENTTRACE_SYSTEMReceiver( 3480): ACTION_BOOTUP - Version: 4.82
,D/PCWCLIENTTRACE_SYSTEMReceiver( 3480): ACTION_BOOTUP - Push type: [SPP, GCM]
,I/Gmail   ( 3661): notifyAccountChanged
,W/VideoCapabilities( 3859): Unrecognized profile/level 32768/2 for video/mp4v-es
,I/Gmail   ( 3661): getAccountsCursor
,W/PCWCLIENTTRACE_AccountUtil( 3480): [hasSamungAccount] - No Samsung Account
,V/GLSActivity( 1626): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3661): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/btif_config_util( 2653): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/VideoCapabilities( 3859): Unsupported mime video/wvc1
,D/Finsky  ( 3808): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/Gmail   ( 3661): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,W/Settings( 3808): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3808): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Gmail   ( 3661): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3661): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/art     ( 3859): Suspending all threads took: 64.732ms
,W/VideoCapabilities( 3859): Unsupported mime video/x-ms-wmv
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 21565(1108KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/33MB, paused 2.280ms total 134.272ms
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 3480): [GetString-S]
,W/VideoCapabilities( 3859): Unsupported mime video/x-ms-wmv7
,I/ReactiveServiceManager( 3480): Supported : 1
,W/VideoCapabilities( 3859): Unsupported mime video/x-ms-wmv8
,D/QSEECOMAPI: ( 1017): QSEECom_get_handle sb_length = 0x2040
D/QSEECOMAPI: ( 1017): App is not loaded in QSEE
W/VideoCapabilities( 3859): Unsupported mime video/mp43
W/VideoCapabilities( 3859): Unsupported mime video/sorenson
,D/QSEECOMAPI: ( 1017): Loaded image: APP id = 9
,W/VideoCapabilities( 3859): Unsupported mime video/mp4v-esdp
,D/QSEECOMAPI: ( 1017): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1017): QSEECom_shutdown_app, app_id = 9
E/terrier ( 1017): handleString: Failed to handle string(-4)
E/terrier ( 1017): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 3480): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 3480): [GetString-E]
,I/ActivityManager( 1017): Killing 3116:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
I/PCWCLIENTTRACE_PushUtil( 3480): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3480): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3480): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 3480): [ensureRegistration] - No Samsung account
,I/ActivityManager( 1017): Killing 1583:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
,W/art     ( 2017): Suspending all threads took: 34.311ms
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3954): MountEmulatedStorage()
E/Zygote  ( 3954): v2
I/libpersona( 3954): KNOX_SDCARD checking this for 10028
I/libpersona( 3954): KNOX_SDCARD not a persona
I/SELinux ( 3954): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3954 uid=10028 gids={50028, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 3086:com.sec.dsm.system/1000 (adj 15): empty #31
,I/SELinux ( 3954): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3954): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,W/ContextImpl( 1017): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3967): MountEmulatedStorage()
E/Zygote  ( 3967): v2
I/libpersona( 3967): KNOX_SDCARD checking this for 1000
I/libpersona( 3967): KNOX_SDCARD not a persona
,I/SELinux ( 3967): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3967): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1017): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3967 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 3967): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/FactoryTestApp( 2628): [DummyFtClient$onDestroy](2628) Destroy DummyFtClient service,
D/FactoryTestApp( 2628): [Support$Values.getString](2628) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2628): [ModuleCommon$isConnectionModeNone](2628) mConnectionMode = gsm
I/FactoryTestApp( 2628): [ModuleCommon$isRunningFtClient](2628) RUNNING_FTCLIENT : false
D/FactoryTestApp( 2628): [DummyFtClient$onDestroy](2628) kill process
I/Process ( 2628): Sending signal. PID: 2628 SIG: 9,
I/DBG_DM  ( 3256): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,D/TimaKeyStoreProvider( 3954): TimaSignature is unavailable
,D/ActivityThread( 3954): Added TimaKeyStore provider
I/VideoCapabilities( 3859): Unsupported profile 4 for video/mp4v-es
,V/Babel   ( 3859): babel boot account: SMS
,V/Babel   ( 3859): babel boot account: thalitester@gmail.com
,D/TimaKeyStoreProvider( 3967): TimaSignature is unavailable
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 3967): Added TimaKeyStore provider
,I/DBG_POLICYDM( 3302): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3116/cgroup.procs: No such file or directory
,D/Volley  ( 3808): [541] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 3808): [548] DiskBasedCache.clear: Cache cleared.,
,E/Zygote  ( 3988): MountEmulatedStorage()
,E/Zygote  ( 3988): v2
,I/libpersona( 3988): KNOX_SDCARD checking this for 1000
I/libpersona( 3988): KNOX_SDCARD not a persona
I/SELinux ( 3988): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1017): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=3988 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 3988): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 3988): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Killing 3170:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31,
,V/AlarmManager( 1017): waitForAlarm result :4
,D/Ads     ( 3808): Skipping gmscore version check
,D/TimaKeyStoreProvider( 3988): TimaSignature is unavailable
,I/ActivityManager( 1017): Killing 3193:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,D/ActivityThread( 3988): Added TimaKeyStore provider
,I/ActivityManager( 1017): Process com.sec.factory (pid 2628)(adj 0) has died(31,655)
,I/DBG_POLICYDM( 3302): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 3302): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 3302): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 3302): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 3302): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 3302): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 3302): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3086/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10068/pid_1583/cgroup.procs: No such file or directory
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
V/AlarmManager( 1017): waitForAlarm result :4
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3170/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3193/cgroup.procs: No such file or directory
,I/Gmail   ( 3661): getAccountsCursor
,V/GLSActivity( 1626): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/Finsky  ( 3808): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3808): [1] Libraries$2.run: Finished loading 1 libraries.
,I/System.out( 3954): Inside onCreate() of WakeupTriggerProvide
,I/System.out( 3954): Inside WakeupProvider
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/ContextImpl( 3967): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/Finsky  ( 3808): [1] GmsCoreHelper.cleanupNlp: result=false type=4,
,E/Zygote  ( 4011): MountEmulatedStorage(),
E/Zygote  ( 4011): v2
I/libpersona( 4011): KNOX_SDCARD checking this for 1000
I/libpersona( 4011): KNOX_SDCARD not a persona
,I/SELinux ( 4011): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4011): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1017): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4011 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux ( 4011): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4011): TimaSignature is unavailable
E/Zygote  ( 4024): MountEmulatedStorage()
I/libpersona( 4024): KNOX_SDCARD checking this for 1000
,E/Zygote  ( 4024): v2
I/libpersona( 4024): KNOX_SDCARD not a persona
D/ActivityThread( 4011): Added TimaKeyStore provider
,I/SELinux ( 4024): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=4024 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 4024): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4024): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/TimaKeyStoreProvider( 4024): TimaSignature is unavailable
,D/ActivityThread( 4024): Added TimaKeyStore provider
,I/VlingoApplication( 3954): VlingoApplication appVersion ='11.7.0.1.40139', coreVersion = '2.6.1.16800', ro.csc.sales_code=XEO
,W/ResourcesManager( 4024): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,E/KnoxSetupWizardClient( 4011): isShipMode : 1
,I/KnoxSetupWizardClient( 4011): onReceive : android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 4024): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,D/ShortcutReceiver( 4011):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4048): MountEmulatedStorage()
,E/Zygote  ( 4048): v2
I/libpersona( 4048): KNOX_SDCARD checking this for 1000
I/libpersona( 4048): KNOX_SDCARD not a persona
,I/SELinux ( 4048): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4048): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1017): Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=4048 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux ( 4048): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/F_PHONE ( 4024): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,W/ContextImpl( 4024): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
D/KnoxShortcutUtil( 4011): getIsShortcutMigrationFor_2_3_0_Done true
,D/ShortcutReceiver( 4011):  KnoxContainerVersion 2.3.0
D/ShortcutReceiver( 4011):  shortcut migration not required 
W/System.err( 4011): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,W/System.err( 4011): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 4011): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 4011): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
W/System.err( 4011): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
W/System.err( 4011): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 4011): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4048): TimaSignature is unavailable
,D/ActivityThread( 4048): Added TimaKeyStore provider
,I/VlingoAndroidCore( 3954): AppName: SamsungTproject, Core: 2.6.1.16800, SDK: 2.0.2137, EDM:16800
,D/Finsky  ( 3808): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/Zygote  ( 4066): MountEmulatedStorage()
E/Zygote  ( 4066): v2
I/libpersona( 4066): KNOX_SDCARD checking this for 1000
I/libpersona( 4066): KNOX_SDCARD not a persona
,I/SELinux ( 4066): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4066): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4066): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1017): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4066 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/F_PHONE ( 4024): [[com.sec.bcservice]] onServiceConnected()
I/F_PHONE ( 4024): default registerAction()
I/F_PHONE ( 4024): [[com.sec.bcservice]] sendPendingMessage()
,I/ActivityManager( 1017): Killing 3150:com.google.android.configupdater/u0a82 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4066): TimaSignature is unavailable
,D/ActivityThread( 4066): Added TimaKeyStore provider
,W/ResourcesManager( 4048): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothBDAdrressReceiver( 4048): onReceive(), action: android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 4048): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,I/ActivityManager( 1017): Killing 3265:com.dropbox.android/u0a88 (adj 15): empty #31
,W/ResourcesManager( 1448): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothBDTestService( 1448): onCreate()
,E/BluetoothBDTestService( 1448): onStart(), extra_type: BOOT_COMPLETED
E/BluetoothBDTestService( 1448): bd_address_path: /efs/bluetooth/bt_addr
E/BluetoothBDTestService( 1448): already exist!( /efs/bluetooth/bt_addr ), file length: 17
,D/StatusChecker( 4066): onReceive : android.intent.action.BOOT_COMPLETED
,I/StatusChecker( 4066): onReceive : net.mt.init : DONE
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4086): MountEmulatedStorage()
E/Zygote  ( 4086): v2
I/libpersona( 4086): KNOX_SDCARD checking this for 10113
I/libpersona( 4086): KNOX_SDCARD not a persona
,I/SELinux ( 4086): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4086 uid=10113 gids={50113, 9997} abi=armeabi-v7a
W/libprocessgroup( 1017): failed to open /acct/uid_10082/pid_3150/cgroup.procs: No such file or directory
I/ActivityManager( 1017): Killing 3286:com.sec.providers.settingsearch/u0a146 (adj 15): empty #31
,I/SELinux ( 4086): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4086): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4086): TimaSignature is unavailable
,D/ActivityThread( 4086): Added TimaKeyStore provider
,D/VlingoApplication( 3954): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 3954): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,I/PageBuddyNotiSvc( 4086): Intent received : action=android.intent.action.BOOT_COMPLETED
,W/libprocessgroup( 1017): failed to open /acct/uid_10088/pid_3265/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10146/pid_3286/cgroup.procs: No such file or directory
,W/ContextImpl( 4086): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,I/PageBuddyNotiSvc( 4086): onCreate mCpBitFlag=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/DialogFlow( 3954): initQueue()
,E/Zygote  ( 4102): MountEmulatedStorage()
E/Zygote  ( 4102): v2
I/libpersona( 4102): KNOX_SDCARD checking this for 10121
I/libpersona( 4102): KNOX_SDCARD not a persona
,I/SELinux ( 4102): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4102 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux ( 4102): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4102): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4102): TimaSignature is unavailable
,D/ActivityThread( 4102): Added TimaKeyStore provider
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=4117 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 3302:com.policydm/1000 (adj 15): empty #31,
,E/Zygote  ( 4117): MountEmulatedStorage()
E/Zygote  ( 4117): v2
I/libpersona( 4117): KNOX_SDCARD checking this for 10029
I/libpersona( 4117): KNOX_SDCARD not a persona
,I/SELinux ( 4117): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4117): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4117): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 4102): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4102): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4102): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 4117): TimaSignature is unavailable
,D/ActivityThread( 4117): Added TimaKeyStore provider
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3302/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 3967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3967): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3967): getResourcePackageName:assistantlist
I/AMMetaDataParserService( 3967): Resource data:2131165186
,W/ResourcesManager( 3967): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3967): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3967): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 3967): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3967): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
I/AMMetaDataParserService( 3967): getResourceTypeNamexml
,I/AMMetaDataParserService( 3967): Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509
,I/DBG_DM  ( 3256): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4134): MountEmulatedStorage()
,E/Zygote  ( 4134): v2
I/libpersona( 4134): KNOX_SDCARD checking this for 10030
I/libpersona( 4134): KNOX_SDCARD not a persona
,I/SELinux ( 4134): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4134 uid=10030 gids={50030, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
,I/ActivityManager( 1017): Killing 3334:com.dropbox.android:crash_uploader/u0a88 (adj 15): empty #31
,I/SELinux ( 4134): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4134): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/QuickConnect( 4102): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/SettingsProvider( 1017): name = scon_is_running
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10121
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,D/QuickConnect( 4102): Utils.setQCRunningSetting - set : 0
,I/AMMetaDataParserService( 3967): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,I/art     (  317): Explicit concurrent mark sweep GC freed 8728(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 639us total 24.420ms
,I/SecKeyguardClockSingleView( 1173): Ignore. Because it is same clock text
,I/QuickConnect( 4102): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,I/QuickConnect( 4102): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3967): Icon data: ResourceNew Tab2131755457android.intent.action.doNewWindow2130837510
,D/TimaKeyStoreProvider( 4134): TimaSignature is unavailable
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 739us total 19.191ms
,D/ActivityThread( 4134): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
,I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
,I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
,I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
,I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
,W/ContextImpl( 3967): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 746us total 20.084ms
,E/Zygote  ( 4149): MountEmulatedStorage()
,E/Zygote  ( 4149): v2
,I/libpersona( 4149): KNOX_SDCARD checking this for 10127
I/libpersona( 4149): KNOX_SDCARD not a persona
I/SELinux ( 4149): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4149 uid=10127 gids={50127, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 2730:com.google.android.apps.docs/u0a87 (adj 15): empty #31
I/SELinux ( 4149): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4149): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4149): TimaSignature is unavailable
,D/ActivityThread( 4149): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
D/PowerManagerService( 1017): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10049 pid=1173 (0x0)
I/AMMetaDataParserService( 3967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3967): getResourcePackageName:assistant
I/AMMetaDataParserService( 3967): Resource data:2131034113
,W/ResourcesManager( 3967): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3967): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3967): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/FileApkUtils( 2017): Spent 39ms computing apk sha1.
,D/FileApkUtils( 2017): Module already staged or being staged:chimera-modules/MapsModule.apk
,I/art     ( 2017): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-e5b9d8f8da13e4c453d8ac4c37e56e073c51a3ad@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-e5b9d8f8da13e4c453d8ac4c37e56e073c51a3ad/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,W/ResourcesManager( 4149): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4149): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4149): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4149): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3967): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3967): getResourceTypeNamexml
,W/libprocessgroup( 1017): failed to open /acct/uid_10088/pid_3334/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10087/pid_2730/cgroup.procs: No such file or directory
,E/        ( 3967): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/DexOptUtils( 2017): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-e5b9d8f8da13e4c453d8ac4c37e56e073c51a3ad/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 2017): Keeping up-to-date module: module-e5b9d8f8da13e4c453d8ac4c37e56e073c51a3ad
,I/GFX construct_block_size_descriptor_2d second part( 3967): took 2.915990ms for 0*0 texture 0
,D/GmsModuleFndr( 2017): Beginning GMS chimera module scan
,I/GFX generate_partition_tables( 3967): took 6.642965ms for 0*0 texture 0
,I/GFX raster( 3967): took 11.202862ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3967): Bitmap=0xb83b7858 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb83b75a0 counterpartCT=4 counterpartW=96 counterparth=96
,D/GmsModuleFndr( 2017): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping,
D/ChimeraCfgMgr( 2017): Beginning module configuration check
,D/ChimeraCfgMgr( 2017): Module APKs unchanged, check complete
,I/AMMetaDataParserService( 3967): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SBrowserFeatureFlag( 4149): initialized in static block : loadCscFeatureValue() succeed! 
,D/ManifestProvider( 4149): onCreate()
,E/NetworkSettingsReceiver( 4149): onReceive: android.intent.action.BOOT_COMPLETED
,E/        ( 3967): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3967): took 1.076198ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3967): Bitmap=0xb83b7858 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb83c54f8 counterpartCT=4 counterpartW=96 counterparth=96
,W/System.err( 4149): java.lang.NoSuchMethodException: isEnabled []
,I/AMMetaDataParserService( 3967): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/System.err( 4149): 	at java.lang.Class.getMethod(Class.java:665)
W/System.err( 4149): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.isCLipboardExsupported(SBrowserFeatureFlag.java:1217)
W/System.err( 4149): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initSupportedPkg(SBrowserFeatureFlag.java:1197)
W/System.err( 4149): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initialize(SBrowserFeatureFlag.java:1114)
W/System.err( 4149): 	at com.sec.android.app.sbrowser.preferences.SbrowserSettings.<init>(SbrowserSettings.java:221)
W/System.err( 4149): 	at com.sec.android.app.sbrowser.common.SBrowserMobileApplication.getSetting(SBrowserMobileApplication.java:111)
W/System.err( 4149): 	at com.sec.android.app.sbrowser.net.NetworkSettingsReceiver.onReceive(NetworkSettingsReceiver.java:48)
W/System.err( 4149): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 4149): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 4149): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 4149): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4149): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 4149): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 4149): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4149): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4149): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 4149): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SBrowserFeatureFlag( 4149): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@122790a3
,D/SBrowserFeatureFlag( 4149): initialize : initSupportedPkg() succeed! 
,I/VerificationLog( 4149): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4171): MountEmulatedStorage()
E/Zygote  ( 4171): v2
I/libpersona( 4171): KNOX_SDCARD checking this for 10131
I/libpersona( 4171): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4171 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 3447:com.fmm.dm/1000 (adj 15): empty #31
,I/SELinux ( 4171): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4171): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
E/SELinux ( 4171): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4171): TimaSignature is unavailable
,D/ActivityThread( 4171): Added TimaKeyStore provider
,W/ResourcesManager( 4171): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4171): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4171): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3447/cgroup.procs: No such file or directory
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  295): DCD OFF
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3967): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3967): took 2.542344ms for 0*0 texture 0
,W/ResourcesManager( 4134): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 4134): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4134): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/GCM     ( 2017): COMPAT: Multi user not supported
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/GFX generate_partition_tables( 3967): took 7.754636ms for 0*0 texture 0
,I/GFX raster( 3967): took 11.200053ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3967): Bitmap=0xb83c5128 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83c5280 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1626): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ResourcesManager( 4134): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4134): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4134): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3967): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/daemonapp( 1801): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3967): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3967): took 0.597448ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3967): Bitmap=0xb8571ca0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8571d68 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ResourcesManager( 4134): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 4134): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GCoreUlr( 2017): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3967): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,E/        ( 3967): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3967): took 0.821615ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3967): Bitmap=0xb83c4f88 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83b75a0 counterpartCT=4 counterpartW=96 counterparth=96
,I/GCoreUlr( 1778): DispatchingService.onCreate()
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3967): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,I/ActivityManager( 1017): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4198 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 4198): MountEmulatedStorage()
E/Zygote  ( 4198): v2
I/libpersona( 4198): KNOX_SDCARD checking this for 10037
I/libpersona( 4198): KNOX_SDCARD not a persona
,I/SELinux ( 4198): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/SELinux ( 4198): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 4198): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3967): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3967): took 0.622552ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3967): Bitmap=0xb83c3828 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83c3910 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/Icing   ( 2017): updateResources: need to parse f{com.google.android.gms}
I/AMMetaDataParserService( 3967): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,E/Zygote  ( 4211): MountEmulatedStorage()
E/Zygote  ( 4211): v2
I/libpersona( 4211): KNOX_SDCARD checking this for 10135
I/libpersona( 4211): KNOX_SDCARD not a persona
,I/SELinux ( 4211): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4211): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4211): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4211 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,I/CheckinService( 2017): Checkin interval check for package: unspecified last checkin: 1448443211930 min interval config: 0 actual interval: 17487619
,E/        ( 3967): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3967): took 1.405156ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3967): Bitmap=0xb8575bc0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8575c18 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4198): TimaSignature is unavailable
,D/ActivityThread( 4198): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 4211): TimaSignature is unavailable
,D/ActivityThread( 4211): Added TimaKeyStore provider
,I/CheckinService( 2017): Disabling old GoogleServicesFramework version
,W/ResourcesManager( 4198): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3967): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,D/SystemUpdateService( 2017): onCreate
,W/ResourcesManager( 4211): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 4211): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4211): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4211): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 4211): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/art     ( 2017): No such thread id for suspend: 36
,D/SystemUpdateService( 2017): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,V/AuthZen ( 2017): Handling intent: android.intent.action.BOOT_COMPLETED
,I/SystemUpdateService( 2017): cancelUpdate (empty URL)
,I/SystemUpdateService( 2017): active receiver: disabled
,E/        ( 3967): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3967): took 0.521511ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3967): Bitmap=0xb810c840 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8382258 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3967): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,D/AuthZenEventHandler( 2017): Handling event: android.intent.action.BOOT_COMPLETED
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
,I/AMMetaDataParserService( 3967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3967): getResourcePackageName:assistant
I/AMMetaDataParserService( 3967): Resource data:2131034113
,I/AMMetaDataParserService( 3967): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3967): getResourceTypeNamexml
,E/        ( 3967): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3967): took 0.844895ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3967): Bitmap=0xb814b448 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8100220 counterpartCT=4 counterpartW=96 counterparth=96
I/ActivityManager( 1017): Killing 3507:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #31
I/GCoreUlr( 1778): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
I/AMMetaDataParserService( 3967): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/CalendarProvider2( 4198): CalendarProvider2.onCreate() called
,E/Zygote  ( 4242): MountEmulatedStorage()
E/Zygote  ( 4242): v2
I/libpersona( 4242): KNOX_SDCARD checking this for 10141
I/libpersona( 4242): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4242 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/SELinux ( 4242): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4242): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4242): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4242): TimaSignature is unavailable
,D/ActivityThread( 4242): Added TimaKeyStore provider
,W/libprocessgroup( 1017): failed to open /acct/uid_10055/pid_3507/cgroup.procs: No such file or directory
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 3954): INFO:Resource not found:/Common.properties Using default values
,I/DBG_DM  ( 3256): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,W/ResourcesManager( 4242): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4242): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4242): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4242): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/CheckinService( 2017): Checking schedule, now: 1448460699821 next: 1449010138595
I/CheckinService( 2017): active receiver: disabled
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 2017): Background sticky concurrent mark sweep GC freed 14658(1228KB) AllocSpace objects, 18(288KB) LOS objects, 17% free, 8MB/10MB, paused 44.681ms total 179.623ms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/BaseAppContext( 2017): Using Auth Proxy for data requests.
,D/ChimeraCfgMgr( 2017): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 28549(1642KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 22MB/33MB, paused 2.951ms total 185.011ms
,D/PCWCLIENTTRACE_AccountAppFacade2_0( 3480): unregister AuthInfo UpdateReceiver v2.0
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,E/        ( 3967): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GFX raster( 3967): took 0.953281ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3967): Bitmap=0xb814b448 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb83a5c18 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 4117): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3967): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:"NG700"
E/        ( 3967): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/GFX raster( 3967): took 0.609323ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3967): Bitmap=0xb83a5098 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8100220 counterpartCT=4 counterpartW=96 counterparth=96
,D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/AMMetaDataParserService( 3967): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SystemUpdateService( 2017): onDestroy
,D/ChimeraCfgMgr( 2017): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,I/art     ( 1626): Explicit concurrent mark sweep GC freed 8040(423KB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 7MB/13MB, paused 1.067ms total 91.080ms
,W/ResourcesManager( 4117): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4117): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4117): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/        ( 3967): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3967): took 0.691199ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3967): Bitmap=0xb8382258 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83a5c18 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3967): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1778): No location to return for getLastLocation()
,E/        ( 3967): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3967): took 0.838438ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3967): Bitmap=0xb8100220 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83a5c18 counterpartCT=4 counterpartW=96 counterparth=96
,W/FusedLocationProvider( 2017): location=null
,I/AMMetaDataParserService( 3967): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,V/GLSActivity( 1626): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/        ( 3967): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3967): took 0.674427ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3967): Bitmap=0xb83c3828 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83a5c18 counterpartCT=4 counterpartW=96 counterparth=96
,W/Kids    ( 2017): [AbstractKidsOperation] Invalid device state 3
,W/Auth    ( 1626): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3967): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,E/        ( 3967): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3967): took 0.676563ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3967): Bitmap=0xb8575bc0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83a5c18 counterpartCT=4 counterpartW=96 counterparth=96
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3967): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534,
,E/Zygote  ( 4301): MountEmulatedStorage()
,E/Zygote  ( 4301): v2
I/libpersona( 4301): KNOX_SDCARD checking this for 10068
I/libpersona( 4301): KNOX_SDCARD not a persona
,I/SELinux ( 4301): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4301): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4301): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4301 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,W/GCoreFlp( 1778): No location to return for getLastLocation()
W/FusedLocationProvider( 2017): location=null
,D/TimaKeyStoreProvider( 4301): TimaSignature is unavailable
,D/ActivityThread( 4301): Added TimaKeyStore provider
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/Process ( 4134): Sending signal. PID: 4134 SIG: 9,
V/GLSActivity( 1626): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,V/GLSActivity( 1626): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1626): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1017): Process com.sec.android.app.sns3 (pid 4134)(adj 0) has died(28,640)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/BadgeProvider( 4301): onCreate
D/BadgeProvider( 4301): DatabaseHelper
,V/GmsCoreStatsServiceLauncher( 2017): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4324): MountEmulatedStorage()
E/Zygote  ( 4324): v2
I/libpersona( 4324): KNOX_SDCARD checking this for 10142
I/libpersona( 4324): KNOX_SDCARD not a persona
,I/SELinux ( 4324): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/AuthZen ( 2017): Fetching signing key...
,I/ActivityManager( 1017): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4324 uid=10142 gids={50142, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 4324): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4324): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BadgeProvider( 4301): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/ActivityManager( 1017): Killing 3542:com.fmm.ds/1000 (adj 15): empty #31
I/ActivityManager( 1017): Killing 3523:com.sec.esdk.elm/u0a90 (adj 15): empty #32
,V/GLSActivity( 1626): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AuthZen ( 2017): Signing key fetched successfully!
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4324): TimaSignature is unavailable
,D/ActivityThread( 4324): Added TimaKeyStore provider
,E/        ( 3967): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3967): took 0.648698ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3967): Bitmap=0xb810c840 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83a5c18 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4340): MountEmulatedStorage()
,E/Zygote  ( 4340): v2
I/libpersona( 4340): KNOX_SDCARD checking this for 10031
I/libpersona( 4340): KNOX_SDCARD not a persona
,I/SELinux ( 4340): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/AMMetaDataParserService( 3967): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/SELinux ( 4340): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4340): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4340 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,W/BaseAppContext( 2017): Using Auth Proxy for data requests.
,I/AMMetaDataParserService( 3967): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3967): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3967): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3967): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3967): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3967): getResourcePackageName:assistant
I/AMMetaDataParserService( 3967): Resource data:2131034112
,I/AMMetaDataParserService( 3967): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 3967): getResourceTypeNamexml
,E/        ( 3967): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3967): took 0.653229ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3967): Bitmap=0xb8382258 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83a5c18 counterpartCT=4 counterpartW=96 counterparth=96
,D/SSRM:n  ( 1017): SIOP:: AP = 430
,D/TimaKeyStoreProvider( 4340): TimaSignature is unavailable
,D/ActivityThread( 4340): Added TimaKeyStore provider
,D/BluetoothAdapter( 3211): disable()
,I/AMMetaDataParserService( 3967): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,W/libprocessgroup( 1017): failed to open /acct/uid_10090/pid_3523/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3542/cgroup.procs: No such file or directory
,E/        ( 3967): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3967): took 0.606875ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3967): Bitmap=0xb8382258 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83a5c18 counterpartCT=4 counterpartW=96 counterparth=96
,D/BadgeProvider( 4301): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4301): sendNotify, [notify] : null
D/BadgeProvider( 4301): update, [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 4301): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4301): update, [UpdateCount] : 1
D/Launcher.Model( 1478): reloadBadges entered.
,W/ResourcesManager( 4324): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,D/SettingsProvider( 1017): name = bluetooth_on
,V/GLSActivity( 1626): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AMMetaDataParserService( 3967): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,D/a       ( 2017): Opening database auth.proximity.permit_store...
,E/SQLiteLog( 1626): (10) POSIX Error : 11 SQLite Error : 3850
,D/BluetoothAdapterState( 2653): CURRENT_STATE=ON, MSG = USER_TURN_OFF
,D/BluetoothAdapterProperties( 2653): Setting state to 13
I/BluetoothAdapterState( 2653): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 2653): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2653): updateAdapterState state is 13
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/AuthZenTransactionCache( 2017): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 2017): Clearing transaction cache
,I/BluetoothPbapService( 2653): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,E/        ( 3967): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3967): took 0.656302ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3967): Bitmap=0xb83a5c18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb839ce00 counterpartCT=4 counterpartW=96 counterparth=96
,D/SecContentProvider( 1017): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1017): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 1017): mCursor = null
,D/WifiService( 1017): setWifiEnabled: false pid=3211, uid=10333
,D/SettingsProvider( 1017): name = wifi_on
,I/AMMetaDataParserService( 3967): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,D/BluetoothSocket( 2653): close() in, this: android.bluetooth.BluetoothSocket@2c7a1ccf, channel: 19, state: LISTENING
D/BluetoothSocket( 2653): close() this: android.bluetooth.BluetoothSocket@2c7a1ccf, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1dcc7fa9, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3bdf865cmSocket: android.net.LocalSocket@20446d65 impl:android.net.LocalSocketImpl@17958a3a fd:FileDescriptor[74]
D/BluetoothSocket( 2653): Closing mSocket: android.net.LocalSocket@20446d65 impl:android.net.LocalSocketImpl@17958a3a fd:FileDescriptor[74]
,E/        ( 3967): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,E/WifiStateMachine( 1017): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1385): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1385): wlan0: Setting scan request: 0 sec 0 usec
I/jxcore-log( 3211): ****TEST TOOK:  5155  ms ****
I/jxcore-log( 3211): 
I/wpa_supplicant( 1385): P2P: Current p2p state = IDLE
I/jxcore-log( 3211): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3211): 
I/wpa_supplicant( 1385): Scan requested (ret=0) - scan timeout 30 seconds
,D/BluetoothAdapterService( 2653): Autoconnection is available 
D/BluetoothAdapterService( 2653): updateAdapterState prevState = 12newState = 13
D/BluetoothAdapterService( 2653): terminating service from this receiver
I/GFX raster( 3967): took 0.724948ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3967): Bitmap=0xb83c3828 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83c3a68 counterpartCT=4 counterpartW=96 counterparth=96
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/BluetoothAdapterProperties( 2653): onBluetoothDisable()
D/BluetoothAdapterProperties( 2653): mDiscovering is false
D/SecContentProvider( 1017): uri = 3 selection = isDiscoverableEnabled
I/BluetoothAdapterState( 2653): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,I/AMMetaDataParserService( 3967): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
W/InputMethodManagerService( 1017): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 1017): [BT Setting State] State =13
,E/WifiConfigStore( 1017): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/BluetoothTile( 1173):  onBluetoothStateChange:
,D/BluetoothTile( 1173):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1173): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothTile( 1173):  getBluetoothState : 13
,D/BluetoothTile( 1173):  handleUpdatestate:false name:null
,D/BluetoothTile( 1173):  handleUpdatestate:false name:null
,D/STATUSBAR-QSTileView( 1173): onStateChanged: Bluetooth
,I/SamsungIME( 1824): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/BluetoothAdapterProperties( 2653): Scan Mode:20
,D/BluetoothAdapterState( 2653): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
E/bt-btif ( 2653): btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,E/bt-btif ( 2653): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,E/bt-btif ( 2653): BTA got event 0x1a1c
,D/PersistentNotificationBroadcastReceiver( 1626): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
E/bt-btm  ( 2653): btm_ble_start_auto_conn start : 0, 0
W/bt-btif ( 2653): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
W/bt-l2cap( 2653): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2653): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2653): L2CAP - PSM: 0x001b not found for deregistration
,D/btif_config_util( 2653): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/StatusBarManagerService( 1017): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/StatusBarManagerService( 1017): setIconVisibility slot=bluetooth visible=false
,D/PhoneStatusBar( 1173): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/PhoneStatusBar( 1173): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,I/ActivityManager( 1017): Waited long enough for: ServiceRecord{f5909b u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/BluetoothSocket( 2653): close() in, this: android.bluetooth.BluetoothSocket@220cac48, channel: 5, state: LISTENING
,D/BluetoothSocket( 2653): close() this: android.bluetooth.BluetoothSocket@220cac48, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@24ae092e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@23937ae1mSocket: android.net.LocalSocket@421006 impl:android.net.LocalSocketImpl@27a6d6c7 fd:FileDescriptor[76]
D/BluetoothSocket( 2653): Closing mSocket: android.net.LocalSocket@421006 impl:android.net.LocalSocketImpl@27a6d6c7 fd:FileDescriptor[76]
,I/ActivityManager( 1017): Killing 3557:com.sec.factory.camera/1000 (adj 15): empty #31
,W/ActivityManager( 1017): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/WifiP2pService( 1017): InactiveState{ what=143375 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
,D/CommandListener(  279): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1626): Read error: ssl=0xb83f1e48: I/O error during system call, Connection timed out
,V/NativeCrypto( 1626): SSL shutdown failed: ssl=0xb83f1e48: I/O error during system call, Broken pipe
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1017): updateNetworkInfo()
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
E/ConnectivityService( 1017): updateNetworkInfo()
,D/ConnectivityService( 1017): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): DefaultState{ when=-2ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/qtaguid ( 1017): Tagging socket 336 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1017, getuid(): 1000
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
,I/qtaguid ( 1017): Untagging socket 336
,I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 1000
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Validated
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3256): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,E/Zygote  ( 4369): MountEmulatedStorage(),
E/Zygote  ( 4369): v2
I/libpersona( 4369): KNOX_SDCARD checking this for 1000
I/libpersona( 4369): KNOX_SDCARD not a persona
,I/SELinux ( 4369): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4369): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4369): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4369 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
W/ActivityManager( 1017): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3557/cgroup.procs: No such file or directory
,D/WifiNetworkAgent( 1017): NetworkAgent: NetworkAgent channel lost
D/WifiP2pService( 1017): InactiveState{ what=131204 }
D/WifiP2pService( 1017): P2pEnabledState{ what=131204 }
D/WifiP2pService( 1017): sending p2p connection changed broadcast: FAILED
,I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/ActivityManager( 1017): Killing 3580:com.samsung.android.scloud.backup/u0a56 (adj 15): empty #31
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
D/WifiP2pService( 1017): sending p2p connection changed broadcast: DISCONNECTED
I/AMMetaDataPar,serService( 3967): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3967): getResourcePackageName:assistant
I/AMMetaDataParserService( 3967): Resource data:2131034113
D/WifiScanningService( 1017): SCAN_AVAILABLE : 1
D/WifiScanningService( 1017): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 1017): SCAN_AVAILABLE : 1
D/RttService( 1017): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
I/AMMetaDataParserService( 3967): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3967): getResourceTypeNamexml
E/        ( 3967): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3967): took 0.837552ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3967): Bitmap=0xb814b448 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb83b0138 counterpartCT=4 counterpartW=96 counterparth=96
D/WifiDisplayController( 1017): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 1017): onP2pDisconnected
D/IpRemoteDisplayController( 1017): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 1017): WfdBridgeServer is already null
E/WifiStateMachine( 1017): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiDisplayController( 1017): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController( 1017): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 1017): disconnect
D/WifiDisplayController( 1017): updateConnection
D/WifiDisplayController( 1017): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiP2pService( 1017): P2pDisablingState
D/WifiP2pService( 1017): P2pDisablingState{ what=147458 }
D/WifiP2pService( 1017): p2p socket connection lost
D/WifiP2pService( 1017): P2pDisabledState
D/WifiP2pService( 1017): P2pDisabledState{ what=143375 }
I/AMMetaDataParserService( 3967): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
D/WifiP2pService( 1017): DefaultState{ what=143375 }
D/AllShareCastTile( 1173): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/AllShareCastTile( 1173): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
D/WifiDisplayController( 1017): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 1017): onP2pDisconnected
D/IpRemoteDisplayController( 1017): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 1017): WfdBridgeServer is already null
D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:null
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/TimaKeyStoreProvider( 4369): TimaSignature is unavailable
D/ActivityThread( 4369): Added TimaKeyStore provider
W/bt-l2cap( 2653): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2653): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2653): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 2653): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2653): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2653): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 2653): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2653): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2653): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif ( 2653): ag scb idx 1 not allocated
W/bt-btif ( 2653): ag scb idx 2 not allocated
E/bt-btif ( 2653): BTA AG is already disabled, ignoring ...
I/bt_userial_mct( 2653): exiting userial_read_thread
D/bt_userial_mct( 2653): Leaving userial_evt_read_thread()
D/bt_userial_mct( 2653): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 2653): hw_epilog_process
D/bt_userial_mct( 2653): userial_close
I/bt_vendor( 2653): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
E/        ( 3967): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/CommandListener(  279): Clearing all IP addresses on wlan0
I/GFX raster( 3967): took 0.827604ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3967): Bitmap=0xb814b448 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb83b0138 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3967): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
D/ConnectivityService( 1017): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/ConnectivityService( 1017): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
E/Zygote  ( 4389): MountEmulatedStorage()
I/ActivityManager( 1017): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4389 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 4389): v2
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1017): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI_P2P( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
I/libpersona( 4389): KNOX_SDCARD checking this for 1000
I/libpersona( 4389): KNOX_SDCARD not a persona
D/ConnectivityManager.CallbackHandler( 1173): CM callback handler got msg 524292
I/SELinux ( 4389): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/CSLegacyTypeTracker( 1017): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::aec:a9ff:fe50:7628/64,192.168.1.133/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 1017): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/ActivityManager( 1017): Killing 3601:com.samsung.android.provider.filterprovider/u0a95 (adj 15): empty #31
I/SELinux ( 4389): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/ConnectivityManager.CallbackHandler( 2017): CM callback handler got msg 524292
D/TelephonyNetworkFactory( 1448): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1448): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/SELinux ( 4389): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/EntConnectivity( 1017): Not allowed due to - mEnabled false - primarySimSlot false
,I/wpa_supplicant( 1385): p2p0: State: DISCONNECTED -> DISCONNECTED
W/ActivityManager( 1017): getTasks: caller 10141 does not hold GET_TASKS; limiting output
,D/ConnectivityService( 1017): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): doQuit - quitNow()
E/ConnectivityService( 1017): updateNetworkInfo()
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1017): updateNetworkInfo()
,I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
,D/EntConnectivity( 1017): Not allowed due to - mEnabled false - primarySimSlot false
,W/libprocessgroup( 1017): failed to open /acct/uid_10056/pid_3580/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10095/pid_3601/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 4389): TimaSignature is unavailable
,D/ActivityThread( 4389): Added TimaKeyStore provider,
,D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/Tethering( 1017): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/Tethering( 1017): MasterInitialState.processMessage what=3
,V/NetworkStats( 1017): updateIfacesLocked()
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
,D/StatusBar.NetworkController( 1173): EthernetConnected: false
D/StatusBar.NetworkController( 1173): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1173): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1173): updateDataNetType()
D/StatusBar.NetworkController( 1173): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1173): updateLTEICONDataNetType:0
,I/Process ( 4242): Sending signal. PID: 4242 SIG: 9
,D/WIFI    ( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,W/ActivityManager( 1017): getTasks: caller 10142 does not hold GET_TASKS; limiting output
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,V/NetworkStats( 1017): performPollLocked() took 12ms
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1173): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1173): updateTelephonySignalStrength: hasService=false ss=null
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/StatusBar.NetworkController( 1173): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/wpa_supplicant( 1385): Blacklist: Clear (all) 
,I/Process ( 4324): Sending signal. PID: 4324 SIG: 9
,D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/STATUSBAR-WifiQuickSettingButton( 1173): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1173): Wifi onReceive(0)
D/HotspotTile( 1173): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-QSTileView( 1173): onStateChanged: Wi-Fi
,D/HotspotTile( 1173): onReceive : 0, 0
,D/WifiCredService( 1301): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,I/bt_vendor( 2653): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 2653): bluetooth satus is on
I/bt_vendor( 2653): bt-vendor : resetting BT status
I/bt_vendor( 2653): Starting hciattach daemon
I/bt_vendor( 2653): try to set false
I/bt_vendor( 2653): Starting hciattach daemon
I/bt_vendor( 2653): try to set false
,I/ActivityManager( 1017): Process com.android.exchange (pid 4324)(adj 9) has died(41,646)
,I/bt_vendor( 2653): cleanup
I/GKI_LINUX( 2653): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 2653): GKI_exit_task 0 done
I/GKI_LINUX( 2653): GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 2653): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 2653): isSecureModeOn:false
D/BluetoothAdapterService( 2653): mProfilesStarted : true supportedProfileServices.length : 12
W/BluetoothAdapterService( 2653): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 2653): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 2653): Not skipping com.android.bluetooth.gatt.GattService
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/BtGatt.DebugUtils( 2653): handleDebugAction() action=null
,I/wpa_supplicant( 1385): p2p0: CTRL-EVENT-TERMINATING 
,D/Tethering( 1017): interfaceLinkStateChanged p2p0, false
I/Nat464Xlat( 1017): interfaceLinkStateChanged p2p0, false
D/Tethering( 1017): interfaceStatusChanged p2p0, false
,W/BluetoothAdapterService( 2653): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2653): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 2653): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BtGatt.GattService( 2653): Received stop request...Stopping profile...
D/BtGatt.GattService( 2653): stop()
D/BtGatt.AdvertiseManager( 2653): advertise clients cleared
,E/        ( 3967): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/ActivityManager( 1017): Process com.android.email (pid 4242)(adj 9) has died(41,646)
I/GFX raster( 3967): took 0.799531ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3967): Bitmap=0xb83a5098 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83b0138 counterpartCT=4 counterpartW=96 counterparth=96
W/BluetoothAdapterService( 2653): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 2653): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,I/GCoreUlr( 1778): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
D/BluetoothAdapterService( 2653): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12ab4b07
,W/BluetoothAdapterService( 2653): Not skipping com.android.bluetooth.a2dp.A2dpService,
,D/HeadsetService( 2653): Received stop request...Stopping profile...
I/Icing   ( 2017): Internal init done: storage state 0
,I/AMMetaDataParserService( 3967): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
I/wpa_supplicant( 1385): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 1385): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1385): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 1385): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1385): wlan0: State: DISCONNECTED -> DISCONNECTED
W/BluetoothAdapterService( 2653): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 2653): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
D/Tethering( 1017): InitialState.processMessage what=4
,D/BluetoothAdapterService( 2653): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12ab4b07
,E/Tethering( 1017): No numeric data
W/BluetoothAdapterService( 2653): Not skipping com.android.bluetooth.hid.HidService
,D/AudioService( 1017): onServiceDisconnected: Bluetooth profile: 1
,D/Tethering( 1017): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1017): clearTetheredNotification()
,I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
,W/BluetoothAdapterService( 2653): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 2653): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 2653): Not skipping com.android.bluetooth.hdp.HealthService
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
,D/HotspotTile( 1173): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1173): updateTetherState():false, false
,E/        ( 3967): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): performPollLocked() took 3ms
,I/GFX raster( 3967): took 0.676562ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3967): Bitmap=0xb814b448 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8382258 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3967): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,E/        ( 3967): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/GFX raster( 3967): took 0.811615ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3967): Bitmap=0xb810c840 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8100220 counterpartCT=4 counterpartW=96 counterparth=96
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/DBG_POLICYDM( 4389): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
I/AMMetaDataParserService( 3967): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,I/DBG_POLICYDM( 4389): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,W/BluetoothAdapterService( 2653): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 2653): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 2653): Not skipping com.android.bluetooth.pan.PanService
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2653): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,D/BtSettings.ProfileConfig( 2653): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 2653): Not skipping com.android.bluetooth.map.BluetoothMapService
I/DBG_POLICYDM( 4389): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,I/DBG_POLICYDM( 4389): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/DBG_POLICYDM( 4389): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,E/        ( 3967): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/BluetoothAdapterService( 2653): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 2653): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
I/GFX raster( 3967): took 0.628229ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3967): Bitmap=0xb83a5c18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83bdbb0 counterpartCT=4 counterpartW=96 counterparth=96
,W/BluetoothAdapterService( 2653): Not skipping com.broadcom.bt.service.sap.SapService
,I/GCoreUlr( 1778): Unbound from all location providers
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2653): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 2653): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 2653): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 2653): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 2653): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,I/AMMetaDataParserService( 3967): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
W/BluetoothAdapterService( 2653): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 2653): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 2653): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 2653): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 2653): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 2653): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService( 2653): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
D/BluetoothAdapterState( 2653): Stopping profile services that were post enabled
E/BluetoothAdapterService(313215751)( 2653): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
D/A2dpService( 2653): Received stop request...Stopping profile...
,D/A2dpStateMachine( 2653): Exit Disconnected: -1
,I/DBG_POLICYDM( 4389): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,D/BluetoothAdapterService( 2653): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12ab4b07
,D/AndroidRuntime( 4361): 
D/AndroidRuntime( 4361): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
E/BluetoothAdapterService(313215751)( 2653): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2653): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2653): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp( 1017): Proxy object disconnected
D/AudioService( 1017): onServiceDisconnected: Bluetooth profile: 2
,I/DBG_POLICYDM( 4389): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
D/AndroidRuntime( 4361): CheckJNI is OFF
,D/AndroidRuntime( 4361): readGMSProperty: start
D/AndroidRuntime( 4361): readGMSProperty: already setted!!
D/AndroidRuntime( 4361): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 4361): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 4361): readGMSProperty: end
D/AndroidRuntime( 4361): addProductProperty: start
,I/DBG_POLICYDM( 4389): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,W/BluetoothHeadsetServiceJni( 2653): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 2653): Cleaning up Bluetooth Handsfree callback object
E/        ( 3967): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/DBG_POLICYDM( 4389): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,I/GFX raster( 3967): took 0.990834ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3967): Bitmap=0xb8382258 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8100220 counterpartCT=4 counterpartW=96 counterparth=96
,D/HidService( 2653): Received stop request...Stopping profile...
I/DBG_POLICYDM( 4389): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
D/HidService( 2653): Stopping Bluetooth HidService
W/BluetoothHidServiceJni( 2653): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 2653): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2653): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 2653): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12ab4b07
,I/DBG_POLICYDM( 4389): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
D/HealthService( 2653): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2653): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12ab4b07
,I/DBG_POLICYDM( 4389): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
I/DBG_POLICYDM( 4389): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 4389): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 4389): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,I/CalendarProvider2( 4198): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
I/AMMetaDataParserService( 3967): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,I/DBG_POLICYDM( 4389): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,I/DBG_POLICYDM( 4389): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.intent.action.BOOT_COMPLETED
,D/PanService( 2653): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2653): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12ab4b07
,D/PhoneApp( 1448): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,I/wpa_supplicant( 1385): Blacklist: Clear (all) 
,D/BluetoothPan( 1017): BluetoothPAN Proxy object disconnected
D/BluetoothMapService( 2653): Received stop request...Stopping profile...
D/FileWriteThread_Telephony( 1448): FileWriteThread : threadType = 3
D/PhoneApp( 1448): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/BluetoothAdapterService( 2653): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12ab4b07
,I/Icing   ( 2017): Post-init done
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
D/FileWriteThread_Telephony( 1448): FileWriteThread : threadType = 3
D/PhoneApp( 1448): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
E/        ( 3967): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3967): took 0.521667ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3967): Bitmap=0xb83bdbb0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8100220 counterpartCT=4 counterpartW=96 counterparth=96
,D/SapService( 2653): Received stop request...Stopping profile...
D/SapService( 2653): Stopping Bluetooth SapService
D/BluetoothAdapterService( 2653): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12ab4b07
,E/BluetoothAdapterService(313215751)( 2653): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2653): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2653): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp( 2653): Proxy object disconnected
D/BluetoothAdapterService( 2653): Bluetooth A2dp source service disconnected
I/GKI_LINUX( 2653): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 2653): GKI_exit_task 2 done,
I/GKI_LINUX( 2653): GKI_shutdown(): task [A2DP-MEDIA] terminated
D/FileWriteThread_Telephony( 1448): FileWriteThread : threadType = 3
D/PhoneApp( 1448): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
I/DBG_POLICYDM( 4389): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
E/BluetoothAdapterService(313215751)( 2653): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2653): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2653): Profile still running: com.android.bluetooth.map.BluetoothMapService
E/BluetoothAdapterService(313215751)( 2653): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2653): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2653): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 2653): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2653): Cleaning up Bluetooth Health object
E/BluetoothAdapterService(313215751)( 2653): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2653): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2653): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 2653): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2653): Cleaning up Bluetooth PAN callback object
,E/BluetoothAdapterService(313215751)( 2653): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2653): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 2653): Profile still running: com.broadcom.bt.service.sap.SapService
E/BluetoothAdapterService(313215751)( 2653): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
W/BluetoothSAPServiceJni( 2653): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 2653): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,D/FileWriteThread_Telephony( 1448): FileWriteThread : threadType = 3
D/PhoneApp( 1448): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/BluetoothAdapterState( 2653): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2653): Setting state to 10
I/BluetoothAdapterState( 2653): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 2653): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2653): updateAdapterState state is 10
,I/AMMetaDataParserService( 3967): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/wpa_supplicant( 1385): wlan0: CTRL-EVENT-TERMINATING 
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
,D/FileWriteThread_Telephony( 1448): FileWriteThread : threadType = 3
D/PhoneApp( 1448): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/BluetoothAdapterService( 2653): Autoconnection is available 
D/BluetoothAdapterService( 2653): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 2653): Entering OffState
D/BluetoothAdapter( 3954): onBluetoothStateChange: up=false
D/BluetoothAdapter( 3954): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 1778): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1778): Bluetooth is turned off, stop adv and scan
D/BluetoothA2dp( 1017): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1439): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1439): Bluetooth is turned off, stop adv and scan
,D/FileWriteThread_Telephony( 1448): FileWriteThread : threadType = 3
D/PhoneApp( 1448): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3967): getResourcePackageName:android.app.searchable
I/DBG_POLICYDM( 4389): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
W/ContextImpl( 3967): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3967): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3967): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,D/FileWriteThread_Telephony( 1448): FileWriteThread : threadType = 3
D/PhoneApp( 1448): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1448): FileWriteThread : threadType = 3
D/PhoneApp( 1448): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,I/DBG_POLICYDM( 4389): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 4389): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
D/FileWriteThread_Telephony( 1448): FileWriteThread : threadType = 3
D/PhoneApp( 1448): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 3967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3967): getResourcePackageName:assistant
I/AMMetaDataParserService( 3967,): Resource data:2131165203
E/Zygote  ( 4425): MountEmulatedStorage()
I/libpersona( 4425): KNOX_SDCARD checking this for 10032
E/Zygote  ( 4425): v2
I/libpersona( 4425): KNOX_SDCARD not a persona,
I/SELinux ( 4425): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4425 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4425): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4425): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/FileWriteThread_Telephony( 1448): FileWriteThread : threadType = 3
D/PhoneApp( 1448): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,I/art     (  317): Explicit concurrent mark sweep GC freed 8716(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 638us total 26.326ms
,I/ActivityManager( 1017): Killing 3625:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #31
,E/DBG_POLICYDM( 4389): [com.policydm.agent.XDMTask(174/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/FileWriteThread_Telephony( 1448): FileWriteThread : threadType = 3
D/PhoneApp( 1448): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/BluetoothAdapter( 2653): onBluetoothStateChange: up=false
D/BluetoothAdapter( 2653): Bluetooth is turned off, stop adv and scan
D/BluetoothAdapter( 1017): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1017): Bluetooth is turned off, stop adv and scan
E/AffinityControl( 4361): AffinityControl: registerfunction enter
D/FileWriteThread_Telephony( 1448): FileWriteThread : threadType = 3
D/PhoneApp( 1448): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1448): FileWriteThread : threadType = 3
D/BluetoothAdapter( 1448): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1448): Bluetooth is turned off, stop adv and scan,
D/PhoneApp( 1448): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
D/BluetoothA2dp( 2653): onBluetoothStateChange: up=false
D/FileWriteThread_Telephony( 1448): FileWriteThread : threadType = 3
D/BluetoothAdapter( 1431): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1431): Bluetooth is turned off, stop adv and scan
D/BluetoothAdapter( 1173): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1173): Bluetooth is turned off, stop adv and scan
D/BluetoothAdapter( 3211): onBluetoothStateChange: up=false
D/BluetoothAdapter( 3211): Bluetooth is turned off, stop adv and scan
D/BluetoothAdapter( 1626): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1626): Bluetooth is turned off, stop adv and scan
W/ResourcesManager( 3967): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3967): getResourceName:com.android.email:xml/email_assistant_menu
,W/ResourcesManager( 3967): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3967): getResourceTypeNamexml
W/ResourcesManager( 3967): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/PhoneApp( 1448): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
W/ResourcesManager( 3967): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 18.665ms
,D/BluetoothManagerService( 1017): Broadcasting onBluetoothServiceDown() to 10 receivers.
D/TimaKeyStoreProvider( 4425): TimaSignature is unavailable
,D/FileWriteThread_Telephony( 1448): FileWriteThread : threadType = 3
,D/AndroidRuntime( 4361): Calling main entry com.android.commands.pm.Pm
,E/WifiStateMachine( 1017): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [21]
,D/ActivityThread( 4425): Added TimaKeyStore provider
E/        ( 3967): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,D/BluetoothManagerService( 1017): Broadcasting onBluetoothServiceUp() to 0 receivers.
,W/Settings( 3859): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 22.088ms
,I/GFX construct_block_size_descriptor_2d second part( 3967): took 3.812450ms for 0*0 texture 0
,D/PersonaManagerService( 1017): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1017): START PACKAGE DELETE: observer{442098379}
D/PackageManager( 1017): pkg{<packageName>}
D/PackageManager( 1017): user{0}
D/PackageManager( 1017): caller{2000}
D/PackageManager( 1017): flags{3}
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1017): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1017): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager( 1017): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1017): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 1017): deletePackage- pkg:com.example.hello, edmuserId:-1
D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled :  enabled true
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/STATUSBAR-WifiQuickSettingButton( 1173): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1173): Wifi onReceive(1)
,D/STATUSBAR-QSTileView( 1173): onStateChanged: Wi-Fi
,D/HotspotTile( 1173): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/HotspotTile( 1173): onReceive : 1, 0
,D/WifiCredService( 1301): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/PackageManager( 1017): !@killApplicatoin: 10333, uninstall pkg
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/Settings( 1778): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/GFX generate_partition_tables( 3967): took 17.218906ms for 0*0 texture 0
I/GFX raster( 3967): took 21.601303ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3967): Bitmap=0xb83a1f98 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b7, Counterpart=0xb83a2c58 counterpartCT=4 counterpartW=80 counterparth=80
,I/AMMetaDataParserService( 3967): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576,
,E/        ( 3967): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/GFX construct_block_size_descriptor_2d second part( 3967): took 2.141510ms for 0*0 texture 0,
,I/GFX generate_partition_tables( 3967): took 5.028594ms for 0*0 texture 0,
I/GFX raster( 3967): took 8.158958ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3967): Bitmap=0xb839ac38 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb839ace0 counterpartCT=4 counterpartW=80 counterparth=80
,I/AMMetaDataParserService( 3967): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,W/PackageSettings( 1017): Skipping PackageSetting{2d27f98 com.test.thalitest/10326} due to missing metadata
,E/        ( 3967): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 3967): took 0.711198ms for 80*80 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3967): Bitmap=0xb839ac38 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb88bbac8 counterpartCT=4 counterpartW=80 counterparth=80
,I/AMMetaDataParserService( 3967): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,I/ActivityManager( 1017): Force stopping com.example.hello appid=10333 user=-1: uninstall pkg
,I/ActivityManager( 1017): Killing 3211:com.example.hello/u0a333 (adj 0): stop com.example.hello cause uninstall pkg
,W/ActivityManager( 1017): Force removing ActivityRecord{d5ee236 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,D/FocusedStackFrame( 1017): Set to : 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1017): Focused application set to: xxxx
,D/InputDispatcher( 1017): Focus left window: 3211
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,I/SurfaceFlinger(  258): id=11 Removed NainActivit (6/7),
I/SurfaceFlinger(  258): id=11 Removed NainActivit (-2/7)
,D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1017): mDVFSHelper.acquire()
,V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1017): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,E/        ( 3967): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 3967): took 0.724427ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3967): Bitmap=0xb839ac38 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb88bcfa8 counterpartCT=4 counterpartW=80 counterparth=80
,D/Launcher( 1478): onRestart, Launcher: 304582819
,I/AMMetaDataParserService( 3967): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,I/ActivityManager( 1017): Force stopping com.example.hello appid=10333 user=0: pkg removed
,E/        ( 3967): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 3967): took 0.694429ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3967): Bitmap=0xb88be3b8 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb83c4de8 counterpartCT=4 counterpartW=80 counterparth=80
,W/ActivityManager( 1017): CustomStartingWindow se packge removed so remove capture also
I/AMMetaDataParserService( 3967): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3967): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 3967): took 0.778906ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3967): Bitmap=0xb88be3b8 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb83c4de8 counterpartCT=4 counterpartW=80 counterparth=80
D/Launcher( 1478): onStart, Launcher: 304582819
D/Launcher.HomeView( 1478): onStart
,D/Launcher( 1478): onResume, Launcher: 304582819
D/SettingsProvider( 1017): name = kids_home_mode
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10006
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,D/SettingsProvider( 1017): ret = -1
,D/Launcher.HomeView( 1478): onResume
,I/GCoreUlr( 1778): DispatchingService.onDestroy()
I/GCoreUlr( 1778): Stopping handler for UlrDispSvcFast
,W/InputMethodManagerService( 1017): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1017): [BT Setting State] State =10
I/InputMethodManagerService( 1017): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/Launcher( 1478): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
I/AMMetaDataParserService( 3967): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,I/GKI_LINUX( 2653): gki_task task_id=1 [BTIF] terminating
,W/libprocessgroup( 1017): failed to open /acct/uid_10098/pid_3625/cgroup.procs: No such file or directory
,D/BluetoothAdapter( 1173): 798513638: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothTile( 1173):  onBluetoothPairedDevicesChanged:
,D/BluetoothAdapter( 1173): 798513638: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothTile( 1173): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1173):  getBluetoothState : 10
,D/BluetoothAdapter( 1173): 798513638: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1173): 798513638: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1173): 798513638: getState() :  mService = null. Returning STATE_OFF
,D/StatusBarManagerService( 1017): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
I/GAV2    ( 3661): Thread[GAThread,5,main]: No campaign data found.
,D/StatusBarManagerService( 1017): setIconVisibility slot=bluetooth visible=false
,D/PhoneStatusBar( 1173): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,I/SamsungIME( 1824): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/PhoneStatusBar( 1173): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,I/GKI_LINUX( 2653): GKI_exit_task 1 done
,I/GKI_LINUX( 2653): GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 2653): cleanupNative: return from cleanup
,D/BluetoothAdapter( 1778): 729927569: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1778): 729927569: getState() :  mService = null. Returning STATE_OFF
,I/art     ( 2653): System.exit called, status: 0
,I/AndroidRuntime( 2653): VM exiting with result code 0, cleanup skipped.
,I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3967): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
W/ContextImpl( 3967): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3967): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3967): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,E/SPPClientService( 4425): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 4425): [PushClientApplication] Push log off : This is Ship build version
,I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
,E/SPPClientService( 4425): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,E/SamsungIME( 1824): mOCRHelper is null
,D/RCPManagerService( 1017): PackageReceiver onReceive()
,W/ResourcesManager( 1448): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/DBG_DM  ( 3256): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,D/SPPClientService( 4425): PushLog.txt file is not deleted.
,D/MenuAppsGridFragment( 1478): onResume
,I/HarmonyEASService( 1017): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/ActivityManager( 1017): handle home activity for 0
I/WallpaperManagerService( 1017): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1017): post home show event for user 0
D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
,D/KnoxMUMContainerPolicy( 1017): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/SPPClientService( 4425): PushLog.txt file is not deleted.
D/SPPClientService( 4425): ============PushLog. stop!
,I/DBG_DM  ( 3256): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
,I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
V/AlarmManager( 1017): waitForAlarm result :8
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3967): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3967): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3967): getResourcePackageName:assistant
I/AMMetaDataParserService( 3967): Resource data:2131099648
,W/ResourcesManager( 3967): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 3967): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3967): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3967): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 3967): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3967): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3967): getResourceTypeNamexml
,D/EnterpriseDeviceManagerService( 1017): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1017): Admin package name: com.google.android.gms
,W/TextServicesManagerService( 1017): no available spell checker services found
,I/ActivityManager( 1017): Process com.android.bluetooth (pid 2653)(adj 0) has died(63,651)
,I/SurfaceFlinger(  258): id=12 createSurf (540x960),1 flag=4, Mauncher
,D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/AMMetaDataParserService( 3967): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/InputDispatcher( 1017): Focus entered window: 1478
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 1478): log_dcs ThreadedRenderer::initialize entered! 
I/DBG_DM  ( 3256): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,D/Launcher( 1478): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/AMMetaDataParserService( 3967): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/InputMethodManagerService( 1017): Got RemoteException sending setActive(false) notification to pid 3211 uid 10333
,D/SensorService( 1017): [SO] -0.421 -0.019 9.902
,I/AMMetaDataParserService( 3967): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/SamsungIME( 1824): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/GCoreUlr( 1778): Unbound from all location providers
,W/GeofencerStateMachine( 1778): Ignoring removeGeofence because network location is disabled.
,D/RegisteredServicesCache( 1439): empty dynamic service
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1017): mCursor = null
,I/AMMetaDataParserService( 3967): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/Tethering( 1017): interfaceRemoved wlan0
,E/Tethering( 1017): attempting to remove unknown iface (wlan0), ignoring
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3967): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/PersonaManager( 1017): isKioskContainerExistOnDevice
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4460): MountEmulatedStorage()
I/ActivityManager( 1017): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4460 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 4460): v2
I/libpersona( 4460): KNOX_SDCARD checking this for 10036
I/libpersona( 4460): KNOX_SDCARD not a persona
,I/SELinux ( 4460): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4460): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4460): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/AMMetaDataParserService( 3967): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/TimaKeyStoreProvider( 4460): TimaSignature is unavailable
,D/ActivityThread( 4460): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 3967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3967): getResourcePackageName:assistant
I/AMMetaDataParserService( 3967): Resource data:2131099648
,I/AMMetaDataParserService( 3967): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3967): getResourceTypeNamexml
,I/ActivityManager( 1017): Killing 3356:com.sec.android.fotaclient/u0a8 (adj 15): empty #31
,I/AMMetaDataParserService( 3967): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/AMMetaDataParserService( 3967): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/ActivityManager( 1017): Displayed Component not be shown by security: +442ms
,D/BackupManagerService( 1017): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 57175(3MB) AllocSpace objects, 14(272KB) LOS objects, 33% free, 22MB/34MB, paused 7.867ms total 397.249ms
,D/JobSchedulerService( 1017): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy( 1017): uID is 10333
,V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
,D/Tethering( 1017): interfaceRemoved p2p0
E/Tethering( 1017): attempting to remove unknown iface (p2p0), ignoring
,V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0,
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
,V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.example.hello
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1017): uID is 10333
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
,D/SSRM:aZ ( 1017): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.example.hello
,D/TaskPersister( 1017): removeObsoleteFile: deleting file=2_task.xml
,V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/SensorService( 1017): [SO] activate (ident=0xb87bd7d8, enabled=0)
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/PackageManager( 1017): delete codoeFile: 
,D/AASAuninstall( 1017): userId = 0, info.removedAppID = -1, info.uid = 10333, packageName = com.example.hello
I/AASA_removePackage( 1017): UID=10333 Target=com.example.hello
,D/SensorManager( 1017): unregisterListener ::   
D/PackageManager( 1017): result of delete: 1{442098379}
,I/Sensors ( 1017): AccelerometerSensor(0) setDelay : 200000000(ns)
I/AMMetaDataParserService( 3967): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/AndroidRuntime( 4361): Shutting down VM
,D/SensorService( 1017): [SO] changed settle time [0]
D/SensorService( 1017): [SO] setDelay [200000000]
D/SensorService( 1017): [SO] activate (ident=0xb87bd7d8, enabled=1)
D/SensorService( 1017): [SO] AR_init
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/AMMetaDataParserService( 3967): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/SensorManager( 1017): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1017): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@11
,I/AMMetaDataParserService( 3967): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/AMMetaDataParserService( 3967): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 3967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3967): getResourcePackageName:assistant
I/AMMetaDataParserService( 3967): Resource data:2131099648
,I/AMMetaDataParserService( 3967): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3967): getResourceTypeNamexml
,I/AMMetaDataParserService( 3967): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/ResourceType( 1017): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1017): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/WallpaperManagerService( 1017):  force update = false; persona id = 0; current user =0; current persona = 0
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/KnoxTimeoutHandler( 1017): handleHomeShow for 0 and current 0
,D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/AMMetaDataParserService( 3967): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/ApplicationPolicy( 1017): updateDataUsageMap
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/StatusBar( 1173): Icon Only
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PanelView( 1173): There is/are notification(s) 
,D/UsbSettingsManager( 1017): clearDefaults: com.example.hello
I/SA      ( 4460): [SSP] onCreated
,I/CrashAnrDetector( 1017): onPackageRemoved : com.example.hello
,D/GpsLocationProvider( 1017): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup( 1017): failed to open /acct/uid_10008/pid_3356/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3967): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/AMMetaDataParserService( 3967): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/SA      ( 4460): [TPM] There is no property file
,I/AMMetaDataParserService( 3967): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/SA      ( 4460): [SCU] isHaveSA() - false
,I/SA      ( 4460): [TPM] getModelProperty : null
,I/SA      ( 4460): [TPM] getCSCProperty : null
,I/SA      ( 4460): [DM] FLOATING AMOLED FEATURE: true
,I/SA      ( 4460): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 4460): [DM] TFT FEATURE: false
,I/AMMetaDataParserService( 3967): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/SensorService( 1017): [SO] Reset Rotation Old [100], Init [1]
,W/art     ( 4361): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,E/SMD     (  295): DCD OFF
,I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
I/AMMetaDataParserService( 3967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3967): getResourcePackageName:assistant
I/AMMetaDataParserService( 3967): Resource data:2131099648
,I/SA      ( 4460): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
I/SA      ( 4460): [DM] init START
,I/AMMetaDataParserService( 3967): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3967): getResourceTypeNamexml
I/SA      ( 4460): [DM] This device is not a Vodafone
,I/AMMetaDataParserService( 3967): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/ResourceType( 4460): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 4460): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 4460): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 4460): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 4460): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,W/ResourceType( 4460): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,W/ResourceType( 4460): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 4460): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 4460): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,W/ResourceType( 4460): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 4460): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,W/ResourceType( 4460): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 4460): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,W/ResourceType( 4460): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 4460): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,W/ResourceType( 4460): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,W/ResourceType( 4460): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,W/ResourceType( 4460): Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
,W/ResourceType( 4460): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 4460): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 4460): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,W/ResourceType( 4460): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 4460): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,W/ResourceType( 4460): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 4460): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,W/ResourceType( 4460): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,I/AMMetaDataParserService( 3967): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/SA      ( 4460): [SCU] isHaveSA() - false
I/SA      ( 4460): support phone number id : false
I/SA      ( 4460): [DM] Supports Ref Jpn : true
,I/SA      ( 4460): [DM] init END
,I/SA      ( 4460): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 4460): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
I/AMMetaDataParserService( 3967): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,I/AMMetaDataParserService( 3967): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/SA      ( 4460): [OR] onReceive END
,D/WallpaperManager( 1478): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1478): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,I/SA      ( 4460): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4460): [ODM] queryOpenData(key= GEO_IP )
,I/AMMetaDataParserService( 3967): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/SA      ( 4460): getMccForGalaxyJpn step2 GEO_IP MCC : 260
,I/SA      ( 4460): [LBE] REF_JPN : true
,I/SA      ( 4460): [BDC] create
,I/Timeline( 1478): Timeline: Activity_idle id: android.os.BinderProxy@23e569d1 time:43287
,I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{25c79768 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:43294
,I/splitIntent( 1017): Queue : background intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart  false.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/SA      ( 4460): [DBMV2] getEmailID
,I/SA      ( 4460): [DBMV2] getDataV02ForItems
I/SA      ( 4460): [SSP] query invoked
,I/AMMetaDataParserService( 3967): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/SA      ( 4460): [SCU] get signed id from samsung account2.0 DB.
,I/SA      ( 4460): [SCU] get signed id from samsung account1.0 DB.
,I/SA      ( 4460): [BDC] destroy
,V/AlarmManager( 1017): waitForAlarm result :4
,I/AMMetaDataParserService( 3967): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
,I/AMMetaDataParserService( 3967): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3967): getResourcePackageName:assistant
I/AMMetaDataParserService( 3967): Resource data:2131099648
,I/AMMetaDataParserService( 3967): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3967): getResourceTypeNamexml
,I/AMMetaDataParserService( 3967): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@11
,W/FileUtils( 3967): Failed to chmod(/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,E/SQLiteLog( 3967): (10) unixWrite() File Descriptor : 38 gets errno : 30
,W/FileUtils( 2992): Failed to chmod(/data/data/com.sec.android.app.sysscope/databases/SysScope.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,E/SQLiteDatabase( 3967): Error inserting actname=com.android.mms.ui.ReplyMessageActivity amicon=[B@dda6e14 appname=com.android.mms id=1448460702479 amtitle=Search amstate=1 amintent=com.android.mms.ui.conversationlistfragment.searchmessages amlabel=2131493240
E/SQLiteDatabase( 3967): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/SQLiteDatabase( 3967): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3967): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 3967): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3967): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3967): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 3967): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 3967): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:77)
E/SQLiteDatabase( 3967): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
E/SQLiteDatabase( 3967): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
E/SQLiteDatabase( 3967): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3967): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3967): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 3967): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 2992): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,I/AMMetaDataParserService( 3967): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/SQLiteLog( 3967): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
,I/ActivityManager( 1017): Killing 3680:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,E/SQLiteDatabase( 3967): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 3967): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3967): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3967): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 3967): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 3967): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3967): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3967): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3967): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 3967): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 3967): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 3967): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 3967): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 3967): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3967): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3967): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:63)
E/SQLiteDatabase( 3967): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
E/SQLiteDatabase( 3967): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
E/SQLiteDatabase( 3967): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3967): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3967): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 3967): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 3967): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 3967): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 3967): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err( 3967): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err( 3967): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 3967): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 3967): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 3967): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
W/System.err( 3967): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
W/System.err( 3967): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err( 3967): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
W/System.err( 3967): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err( 3967): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err( 3967): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err( 3967): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:63)
W/System.err( 3967): ,	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
W/System.err( 3967): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
W/System.err( 3967): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 3967): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3967): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3967): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 2992): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2992): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2992): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2992): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2992): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2992): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2992): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2992): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2992): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2992): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2992): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2992): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,D/SensorService( 1017): [SO] currT = 43381047000, prevT = 42911048000, diff = 469999000, [-0.421 -0.019 9.922]
,D/SensorService( 1017): [SO] -0.421 -0.019 9.922
D/SensorService( 1017): [SO] [100 -> 255]
,I/ActivityManager( 1017): Killing 3693:com.google.android.onetimeinitializer/u0a13 (adj 15): empty #31
,E/SQLiteDatabase( 2992): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2992): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2992): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2992): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2992): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2992): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2992): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2992): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2992): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2992): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2992): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2992): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2992): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2992): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2992): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2992): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2992): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2992): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2992): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2992): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2992): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2992): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteOpe,nHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2992): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2992): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2992): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2992): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2992): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2992): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2992): 	at java.lang.Thread.run(Thread.java:818)
,D/SIP     ( 1448): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,I/iu.UploadsManager( 2017): End new media; added: 0, uploading: 0, time: 67 ms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/Hs20UtilService( 1665): Starting #5
E/SQLiteLog( 2992): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
I/Hs20UtilService( 1665): Message received 5007
,E/SQLiteDatabase( 2992): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2992): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2992): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2992): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2992): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2992): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2992): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2992): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2992): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2992): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2992): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2992): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,E/SQLiteDatabase( 2992): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2992): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2992): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2992): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2992): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2992): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2992): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2992): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2992): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2992): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2992): 	at java.lang.Thread.run(Thread.java:818)
I/NearbySettings( 1301): MountReceiver.onReceive - Keep current state
,E/SQLiteLog( 2992): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2992): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2992): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2992): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2992): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2992): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2992): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2992): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2992): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2992): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2992): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2992): 	at java.lang.Thread.run(Thread.java:818)
,E/File    ( 1448): fail readDirectory() errno=2
,E/SQLiteLog( 2992): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2992): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2992): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2992): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2992): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2992): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2992): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2992): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2992): 	at java.lang.Thread.run(Thread.java:818)

```
