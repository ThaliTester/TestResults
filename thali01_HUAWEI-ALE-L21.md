#### Test 51790364c93db41_thali01_HUAWEI-ALE-L21 Logs


```
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
,--------- beginning of main
I/appproc ( 6881): CLASSPATH=/system/framework/am.jar
I/appproc ( 6881): Command=app_process /system/bin com.android.commands.am.Am start -n com.test.thalitest/com.test.thalitest.MainActivity 
I/appproc ( 6881): app_process:number,5,0
I/AndroidRuntime( 6881): readDownloadBoosterConfig: 'false'
I/        ( 6881): power log dlsym ok
E/android_hardware_fm.cpp( 6881): register_android_hardware_fm_fmradio
I/android_hardware_fm.cpp( 6881): ========64bit long size = 8
E/FM_HAL  ( 6881): [FM_HAL], libname is libhisifm_if
I/fm_hisi ( 6881): FM::[fm_device_open:4653] fm_device_open
I/fm_hisi ( 6881): 
I/fm_hisi ( 6881): FM::[fm_device_open:4664] find the id:libhisifm_if and begins to open the device
I/fm_hisi ( 6881): 
I/fm_hisi ( 6881): FM::[fm_device_open:4708] device open sucess
I/fm_hisi ( 6881): 
E/android_hardware_fm.cpp( 6881): register_android_hardware_fm_fmradio, ret is 0
I/art     ( 2937): Can not find class: Lcom/android/server/wm/WindowState$2;
I/art     ( 2937): Can not find class: Lcom/android/server/am/TaskPersister$TaskWriteQueueItem;
I/art     ( 2937): Can not find class: Lcom/android/server/am/TaskPersister$WriteQueueItem;
I/art     ( 2937): Can not find class: Lcom/android/server/am/ActivityStack$2;
I/HwSystemManager( 4085): AppLockService:applock password not initial or function is closed
I/HwSystemManager( 4085): AppLockService:applock password not initial or function is closed
I/HwLauncher( 3936): Launcher  onWindowVisibilityChanged visibility = 8
I/HwLauncher( 3936): DynamicIcon onWindowVisibilityChanged 8 - com.android.calendar
I/HwLauncher( 3936): DynamicIcon onWindowVisibilityChanged 8 - com.android.deskclock
I/HwSystemManager( 4085): AppManager:getNetAppInfoFromDB cursor lenth = 1
I/HwLauncher( 3936): DynamicIcon onVisibilityChanged 4 - com.android.calendar
I/HwLauncher( 3936): DynamicIcon onVisibilityChanged 4 - com.android.deskclock
I/WebViewFactory( 6900): Loading com.android.webview version 37 (eng.jenkinswh-arm64) (code 199992)
,I/LibraryLoader( 6900): Loading: webviewchromium
I/LibraryLoader( 6900): Time to load native libraries: 55 ms (timestamps 1881-1936)
I/LibraryLoader( 6900): Expected native library version number "",actual native library version number ""
I/LibraryLoader( 6900): Expected native library version number "",actual native library version number ""
I/chromium( 6900): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6900): Initializing chromium process, renderers=0
W/art     ( 6900): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6900): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium( 6900): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6900): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=46092 len=2953
I/chromium( 6900): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:38 off:228796 len:643667
W/chromium( 6900): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6900): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/chromium( 6900): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/art     ( 6900): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6900): onDetachedFromWindow called when already detached. Ignoring
I/art     ( 6900): Can not find class: Landroid/widget/ViewStub;
I/art     ( 6900): Can not find class: Landroid/webkit/ViewStub;
I/art     ( 6900): Can not find class: Landroid/app/ViewStub;
W/art     ( 6900): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6900): Attempt to remove local handle scope entry from IRT, ignoring
E/Thermal-daemon( 2331): [charger_ic] temp_new :31  temp_old :32
I/PhoneStatusBar( 3472): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
I/PhoneStatusBar( 3472): shouldTranslucent:true
I/PhoneStatusBar( 3472): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
I/OpenGLRenderer( 6900): Initialized EGL, version 1.4
I/ActivityManager( 2937): Displayed com.test.thalitest/.MainActivity: +1s49ms (total +1s122ms)
W/IInputConnectionWrapper( 6900): showStatusIcon on inactive InputConnection
,I/chromium( 6900): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6900): 
,W/jxcore-log( 6900): Initializing JXcore engine
W/jxcore-log( 6900): JXcore engine is ready
,W/jxcore-log( 6900): Starting JXcore engine
,W/jxcore-log( 6900): Platform android
W/jxcore-log( 6900): 
W/jxcore-log( 6900): Process ARCH arm
W/jxcore-log( 6900): 
,I/art     ( 2937): Can not find class: Lcom/android/server/am/TaskPersister$ImageWriteQueueItem;
,I/art     ( 5839): Can not find class: Lcom/google/android/gms/common/internal/GmsLogger;
,I/jxcore-log( 6900): JXcore Cordova bridge is ready!
I/jxcore-log( 6900): 
W/jxcore-log( 6900): JXcore engine is started
,I/jxcore-log( 6900): Toggling radios to true
I/jxcore-log( 6900): 
,I/BluetoothAdapter( 6900): Start to enable Bluetooth!
,I/HwSystemManager( 4085): HoldService:checkBeforeShowDialog: uid:10295 pid:6900, permissionType:8388608
I/HwSystemManager( 4085): OverseaCfgHelper:permissionStatus is 0
,I/art     ( 2937): Can not find class: Lcom/android/server/DropBoxManagerService$1$1;
,I/HwSystemManager( 4085): HoldService:checkBeforeShowDialog: uid:10295 pid:6900, permissionType:2097152
I/HwSystemManager( 4085): OverseaCfgHelper:permissionStatus is 0
,I/ConnectPermission( 2937): allowOpenWifi blocked:false
,E/WifiStateMachine( 2937):  InitialState CMD_START_SUPPLICANT 0 0
,I/jxcore-log( 6900): Radios toggled
I/jxcore-log( 6900): 
,I/art     ( 2937): Can not find class: Lcom/android/server/NativeDaemonConnector$Command;
,E/WifiHW  ( 2937): wifi_start_supplicant: last serial = 117440512
,I/ActivityManager( 2937): filter receiver for action = android.net.wifi.WIFI_STATE_CHANGED
,I/HwSystemManager( 4085): MainReceiver:receive action:android.net.wifi.WIFI_STATE_CHANGED
,W/System.err( 2937): java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
,I/wpa_supplicant( 6987): Hisi ini file config lowpower_wake_interval param value:27
I/wpa_supplicant( 6987): set current WIFI status to BT!
I/wpa_supplicant( 6987): failed to connect to: /data/misc/bluedroid/.coex_bt (Connection refused)
I/wpa_supplicant( 6987): set BT_STATE_OFF
I/wpa_supplicant( 6987): Successfully initialized wpa_supplicant
,W/System.err( 2937): 	at com.huawei.android.server.wifi.ReportTool.getUserType(ReportTool.java:86)
W/System.err( 2937): 	at com.huawei.android.server.wifi.ReportTool.isBetaUser(ReportTool.java:73)
W/System.err( 2937): 	at com.huawei.android.server.wifi.ReportTool.report(ReportTool.java:58)
W/System.err( 2937): 	at com.huawei.android.server.wifi.DataUploader.e(DataUploader.java:57)
W/System.err( 2937): 	at com.android.server.wifi.WifiStateMachine$InitialState.processMessage(WifiStateMachine.java:5254)
W/System.err( 2937): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/System.err( 2937): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/System.err( 2937): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2937): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2937): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ReportTools( 2937): This is not beta user build
,I/WifiTracker( 3472): STATE =2
,I/wpa_supplicant( 6987): rfkill: Cannot open RFKILL control device
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/HsmCoreServiceImpl( 2937): onTransact in code is: 102
I/MediaProcessHandler( 2937): processOp opType: 1, uid: 10041, pid: 5923
W/MediaProcessHandler( 2937): remove target not exist, maybe the UI process: uid: 10041, pid: 5923
I/HwSystemManager( 4085): BgPowerManagerService:onProcessDied uid = 10041
I/HwSystemManager( 4085): HoldService:uid:10041 pid:5923 died
I/HwSystemManager( 4085): HoldService:oldVersionKey:10041,5923
,I/bluedroid( 6965): bt interface: [open_bluetooth_stack]
I/bluedroid( 6965): bt interface: [bluetooth__get_bluetooth_interface]
,I/BluetoothAdapterState( 6965): Entering OffState
,I/BluetoothServiceJni( 6965): OoO sJniCallbacksObj has init before init? 0
I/RadioStateMachine( 6965): Entering OffState
I/bluedroid( 6965): bt interface: [init]
,I/bte_main( 6965): OoO log conf is : false
I/bte_conf( 6965): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/BT_UTILS( 6965): onetrack,g_type=hi110x
,I/bluedroid( 6965): bt interface: [get_profile_interface]: get_profile_interface socket
I/bluedroid( 6965): bt interface: [get_profile_interface]: get_profile_interface map_client
,I/bluedroid( 6965): bt interface: [get_adapter_property]
I/bluedroid( 6965): bt interface: [get_adapter_property]
,I/GKI_LINUX( 6965): gki_task_entry task_id=1 [BTIF] starting
,W/bt-btif ( 6965): HAL bt_hal_cbacks->thread_evt_cb
,W/bt-btif ( 6965): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 6965): adapterPropertyChangedCallback with type:2 len:6
,W/bt-btif ( 6965): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 6965): adapterPropertyChangedCallback with type:1 len:7
,I/bluedroid( 6965): bt interface: [config_hci_snoop_log]
,I/BluetoothAdapterState( 6965): Bluetooth adapter state changed: 10-> 11
,I/ActivityManager( 2937): filter receiver for action = android.bluetooth.adapter.action.STATE_CHANGED
,I/HwCust  ( 3669): Constructor found for class com.android.settings.bluetooth.HwCustBluetoothPlatformImpImpl
,I/BluetoothBondStateMachine( 6965): StableState(): Entering Off State
,I/BluetoothHeadsetServiceJni( 6965): classInitNative: succeeds
,I/BluetoothAdapterState( 6965): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/HeadsetPhoneState( 6965): getPhoneStateListener subId:1
,I/bluedroid( 6965): bt interface: [get_profile_interface]: get_profile_interface handsfree
,I/BluetoothAvrcpServiceJni( 6965): classInitNative: succeeds
,I/bluedroid( 6965): bt interface: [get_profile_interface]: get_profile_interface avrcp
,I/art     ( 2937): Can not find class: Lcom/android/server/media/MediaSessionService$SessionsListenerRecord;
,E/RemoteController( 6965): Cannot set synchronization mode on an unregistered RemoteController
,I/BluetoothA2dpServiceJni( 6965): classInitNative: succeeds
,I/bluedroid( 6965): bt interface: [get_profile_interface]: get_profile_interface a2dp
I/GKI_LINUX( 6965): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,I/BluetoothHidServiceJni( 6965): classInitNative: succeeds
,I/bluedroid( 6965): bt interface: [get_profile_interface]: get_profile_interface hidhost
,I/BluetoothHealthServiceJni( 6965): classInitNative: succeeds
,I/bluedroid( 6965): bt interface: [get_profile_interface]: get_profile_interface health
,I/BluetoothPanServiceJni( 6965): classInitNative(L105): succeeds
,I/bluedroid( 6965): bt interface: [get_profile_interface]: get_profile_interface pan
,I/BtGatt.JNI( 6965): classInitNative(L863): classInitNative: Success!
,I/bluedroid( 6965): bt interface: [get_profile_interface]: get_profile_interface gatt
,I/bluedroid( 6965): bt interface: [enable]
I/bluetooth-coex( 6965): coex_lock_init: coex_mutex init
,I/GKI_LINUX( 6965): gki_task_entry task_id=0 [BTU] starting
I/bt_hci_bdroid( 6965): init
I/bt-btu  ( 6965): btu_task pending for preload complete event
,I/        ( 6965): [vendor/huawei_platform/connectivity/hisi/hisi_connectivity/bt/hal/src/bt_vendor_hisi.c: hisi_init 238][bt_vendor] bt vendor init
,I/bluetooth-coex( 6965): bt_coex_init: bt_coex_init
I/        ( 6965): >>>>>g_vd.uart_fd:-1
I/bluetooth-coex( 6965): btcoex_socket_server: created socket fd 69, /data/misc/bluedroid/.coex_bt
I/bluetooth-coex( 6965): btcoex_send_msg: send bt_state(1) to wifi, sock_fd(70)
,I/art     ( 2937): Can not find class: Lcom/android/server/connectivity/Tethering$TetherInterfaceSM;
,I/art     ( 2937): Can not find class: Lcom/android/server/connectivity/Tethering$TetherInterfaceSM$InitialState;
,I/art     ( 2937): Can not find class: Lcom/android/server/connectivity/Tethering$TetherInterfaceSM$StartingState;
,I/art     ( 2937): Can not find class: Lcom/android/server/connectivity/Tethering$TetherInterfaceSM$TetheredState;
I/art     ( 2937): Can not find class: Lcom/android/server/connectivity/Tethering$TetherInterfaceSM$UnavailableState;
,I/        ( 6965): [vendor/huawei_platform/connectivity/hisi/hisi_connectivity/bt/hal/src/bt_vendor_hisi.c: hw_config_set_bdaddr 142][bt_vendor] hw_config_set_bdaddr 582af7ed96be
,I/bt-btu  ( 6965): btu_task received preload complete event
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
E/TEST-APN( 3890): query for APN: check-permission succ 
E/TEST-APN( 3890): Telephony query SQL: SELECT type, proxy, port FROM carriers WHERE (numeric = ',' and carrier_enabled = 1)
E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,I/        ( 6965): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6965): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6965): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6965): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6965): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6965): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6965): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6965): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6965): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6965): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6965): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6965): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6965): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6965): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6965): BTE_InitTraceLevels -- TRC_BTIF
,I/ActivityManager( 2937): filter receiver for action = android.net.conn.TETHER_STATE_CHANGED
I/art     ( 2937): Can not find class: Lcom/android/server/wifi/WifiStateMachine$TetherStateChange;
,W/wpa_supplicant( 6987): check_associate_result func start
,I/HwSystemManager( 4085): aor:Network Stats Updated
I/HwSystemManager( 4085): aoi:onNetworkStatsUpdated
I/HwSystemManager( 4085): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,W/wpa_supplicant( 6987): STA MODE: Set shutdown wlan cmd SUCCESS
,W/wpa_supplicant( 6987): check_associate_result func start
,E/HwSystemManager( 4085): getSimCardType:/getSimCardInfo: imsi is null
I/wpa_supplicant( 6987): wlan is down..., now start up...
,E/HwSystemManager( 4085): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 4085): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 4085): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 4085): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
I/HwSystemManager( 4085): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,W/bt-btif ( 6965):  bta_dm_sys_hw_cback with event: 1
E/bt-btm  ( 6965): BTM_SecRegister:p_cb_info->p_le_callback == 0xe3961b31 
E/bt-btm  ( 6965): BTM_SecRegister: btm_cb.api.p_le_callback = 0xe3961b31 
,E/HwSystemManager( 4085): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 4085): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 4085): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 4085): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 4085): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
,I/HwSystemManager( 4085): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/bt-btif ( 6965): Calling BTA_HhEnable
E/bt-btif ( 6965): btif_storage_get_adapter_property service_mask:0x2140040
W/bt-btif ( 6965): HAL bt_hal_cbacks->adapter_properties_cb
,I/BluetoothAdapterProperties( 6965): adapterPropertyChangedCallback with type:2 len:6
I/BluetoothAdapterProperties( 6965): adapterPropertyChangedCallback with type:1 len:7
,I/BluetoothAdapterProperties( 6965): adapterPropertyChangedCallback with type:7 len:4
,I/BluetoothAdapterProperties( 6965): adapterPropertyChangedCallback with type:9 len:4,
I/BluetoothAdapterProperties( 6965): adapterPropertyChangedCallback with type:8 len:0
I/BluetoothAdapterProperties( 6965): adapterPropertyChangedCallback with type:3 len:48
W/bt-btif ( 6965): bte_main_enable_lpm
I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
W/bt-btm  ( 6965): BTM_SetDiscoverability
W/bt-btm  ( 6965): BTM_SetConnectability
W/bt-btm  ( 6965): BTM_SetDiscoverability
W/bt-btm  ( 6965): BTM_SetConnectability
W/bt-btif ( 6965): HAL bt_hal_cbacks->adapter_state_changed_cb
I/bluedroid( 6965): bt interface: [set_adapter_property]
I/bluedroid( 6965): bt interface: [set_adapter_property]
,I/BluetoothAdapterState( 6965): Bluetooth adapter state changed: 11-> 12
E/HwSystemManager( 4085): getSimCardType:/getSimCardInfo: imsi is null
W/bt-btif ( 6965): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterState( 6965): Entering On State
I/BluetoothAdapterProperties( 6965): adapterPropertyChangedCallback with type:7 len:4
W/bt-btm  ( 6965): BTM_SetDiscoverability
W/bt-btm  ( 6965): BTM_SetConnectability
W/bt-btif ( 6965): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 6965): adapterPropertyChangedCallback with type:9 len:4
,E/HwSystemManager( 4085): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 4085): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 4085): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 4085): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
,I/ActivityManager( 2937): filter receiver for action = android.bluetooth.adapter.action.STATE_CHANGED,
I/Telecom ( 3847): BluetoothPhoneService: handleMessage: request is null
,W/BluetoothAdapter( 6965): getBluetoothService() called with no BluetoothManagerCallback
,I/bluedroid( 6965): bt interface: [set_adapter_property],
W/bt-btif ( 6965): HAL bt_hal_cbacks->adapter_properties_cb
I/bluedroid( 6965): bt interface: [set_adapter_property]
I/BluetoothAdapterProperties( 6965): adapterPropertyChangedCallback with type:9 len:4
W/bt-btm  ( 6965): BTM_SetDiscoverability
,W/bt-btm  ( 6965): BTM_SetConnectability
W/bt-btif ( 6965): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 6965): adapterPropertyChangedCallback with type:7 len:4
,W/View    ( 3472): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{51589be V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during layout: running second layout pass
,I/HwSystemManager( 4085): WifiApStateReceiver:onReceive: action = android.net.conn.TETHER_STATE_CHANGED
I/HwSystemManager( 4085): HoldService:uid:10084 pid:6434 died
I/HwSystemManager( 4085): BgPowerManagerService:onProcessDied uid = 10084
I/HwSystemManager( 4085): HoldService:oldVersionKey:10084,6434
,E/HsmCoreServiceImpl( 2937): onTransact in code is: 102
I/MediaProcessHandler( 2937): processOp opType: 1, uid: 10084, pid: 6434
W/MediaProcessHandler( 2937): remove target not exist, maybe the UI process: uid: 10084, pid: 6434
,I/HwSystemManager( 4085): HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@88bdc3d
I/HwSystemManager( 4085): HsmIntentService:started for intent:Intent { act=android.net.conn.TETHER_STATE_CHANGED flg=0x24000010 cmp=com.huawei.systemmanager/com.huawei.netassistant.wifiap.WifiApStateReceiver (has extras) }, action:android.net.conn.TETHER_STATE_CHANGED, class:com.huawei.netassistant.wifiap.WifiApStateReceiver
,I/HwSystemManager( 4085): HsmIntentService:invoked com.huawei.netassistant.wifiap.WifiApStateReceiver
,I/HwSystemManager( 4085): WifiApStateReceiver:handleTetherStateChange: Wifi AP is not enabled ,skip
I/HwSystemManager( 4085): HsmIntentService:task completed for intent:Intent { act=android.net.conn.TETHER_STATE_CHANGED flg=0x24000010 cmp=com.huawei.systemmanager/com.huawei.netassistant.wifiap.WifiApStateReceiver (has extras) }, action:android.net.conn.TETHER_STATE_CHANGED
I/HwSystemManager( 4085): HsmIntentService:in thread:Thread[HsmIntentServiceTask #2,5,main], current active tasksize:1, queue size:0
I/HwSystemManager( 4085): HsmIntentService:last work complete! lets stop service.
,I/art     ( 3669): Can not find class: Lhuawei/android/view/LinearLayout;
I/art     ( 3669): Can not find class: Lhuawei/android/widget/LinearLayout;
,I/art     ( 3669): Can not find class: Lhuawei/android/view/TextView;
,I/art     ( 3669): Can not find class: Lhuawei/android/widget/TextView;
,I/art     ( 2937): Can not find class: Lcom/android/server/notification/NotificationManagerService$ToastRecord;
,I/art     ( 2937): Can not find class: Lcom/android/server/am/ActivityManagerService$ForegroundToken;
,I/art     ( 2937): Can not find class: Lcom/android/server/am/ActivityManagerService$10;
,I/HwSystemManager( 4085): HsmIntentService:destroyed. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@88bdc3d
,W/BluetoothAdapter( 6965): getBluetoothService() called with no BluetoothManagerCallback
,W/BluetoothAdapter( 6965): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 6965): Accept thread started.
,W/wpa_supplicant( 6987): STA MODE: Open wlan cmd SUCCEESS
I/wpa_supplicant( 6987): set current WIFI status to BT!
,I/bluetooth-coex( 6965): btcoex_socket_server: accept socket success
I/bluetooth-coex( 6965): set_bt_coex_mode_ext: wlan common protect scheduling
I/bluetooth-coex( 6965): btcoex_set_a2dp_priority: bdaddr: 000000000000
I/bluetooth-coex( 6965): btcoex_set_a2dp_priority: A2DP - no link control block
I/bluetooth-coex( 6965): set_bt_coex_mode_ext: wlan common protect, no need to set bt priority
I/wpa_supplicant( 6987): set current WIFI status to BT!
I/bluetooth-coex( 6965): btcoex_socket_server: accept socket success
I/bluetooth-coex( 6965): set_bt_coex_mode_ext: WIFI_ACTIVE
I/wpa_supplicant( 6987): wlan0: CTRL-EVENT-SCAN-STARTED 
I/art     ( 2937): Can not find class: Lcom/android/server/wifi/WifiMonitor$MonitorThread;
,E/WifiStateMachine( 2937):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 2937): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 2937):  SupplicantStartingState CMD_START_DRIVER 0 0
,E/WifiMonitor( 2937): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 2937):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
,E/WifiStateMachine( 2937):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 2937):  SupplicantStartingState CMD_DISCONNECT 0 0
E/WifiStateMachine( 2937):  DefaultState CMD_DISCONNECT 0 0
,E/WifiStateMachine( 2937):  SupplicantStartingState CMD_RECONNECT 0 0
E/WifiStateMachine( 2937):  DefaultState CMD_RECONNECT 0 0
E/WifiStateMachine( 2937):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 2937):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,E/WifiStateMachine( 2937):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
,I/ActivityManager( 2937): filter receiver for action = android.net.wifi.WIFI_STATE_CHANGED
E/SUPL20_LocMan( 3913): WIFI_STATE not have mac address
,I/HwSystemManager( 4085): MainReceiver:receive action:android.net.wifi.WIFI_STATE_CHANGED
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
E/WifiConfigStore( 2937): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,I/art     ( 2937): Can not find class: Lcom/huawei/android/service/wifi/HwWifiConfigStoreManagerImpl;
,I/WifiTracker( 3472): STATE =1
,W/Settings( 5975): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiNative-HAL( 2937): startHal
,E/wifi    ( 2937): getStaticLongField sWifiHalHandle 0x7f7de0d390
I/WifiHAL ( 2937): Initializing wifi
I/WifiHAL ( 2937): Creating socket
,E/WifiHAL ( 2937): Could not find group vendor
,I/WifiHAL ( 2937): Initialized Wifi HAL Successfully; vendor cmd = 103
E/wifi    ( 2937): getStaticLongField sWifiHalHandle 0x7f7de0d300
,I/WifiNative-HAL( 2937): interface[0] = wlan0
,I/art     ( 2937): Can not find class: Lcom/android/server/wifi/WifiNative$MonitorThread;
,E/WifiHAL ( 2937): failed to set scanning mac OUI; result = -95
,I/WifiNative-HAL( 2937): Waiting for HAL events mWifiHalHandle=367835534928
E/wifi    ( 2937): getStaticLongField sWifiHalHandle 0x7f7ecde7b0
,I/ActivityManager( 2937): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/art     ( 2937): Can not find class: Lcom/android/server/wifi/WifiNotificationController$2;
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,I/art     ( 2937): Can not find class: Lcom/android/server/wifi/ArpVerifier$2;
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,E/native  ( 2937): do suspend true
,E/WifiStateMachine( 2937): Driverstarted State enter done
,E/WifiStateMachine( 2937):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= false screenOn=false
I/WifiNative-HAL( 2937): startHal
,I/art     ( 2937): Can not find class: Lcom/android/server/wifi/WifiNative$ScanCapabilities;
E/WifiStateMachine( 2937): setScanAlarm true period 10000 initial delay 200
E/WifiScanningService( 2937): could not get scan capabilities
,E/WifiStateMachine( 2937):  DisconnectedState CMD_START_DRIVER 0 0
,E/WifiStateMachine( 2937):  ConnectModeState CMD_START_DRIVER 0 0
,E/WifiStateMachine( 2937):  DriverStartedState CMD_START_DRIVER 0 0
,E/WifiStateMachine( 2937):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
,E/WifiStateMachine( 2937):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 2937):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
,W/CommandListener( 2308): Failed to retrieve HW addr for p2p0 (No such device)
E/WifiStateMachine( 2937): did set frequency band 0
,E/wpa_supplicant( 6987): Ongoing scan action - ignore new request for first scan
,E/WifiStateMachine( 2937): done set frequency band 0
E/WifiStateMachine( 2937):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=107104  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,I/ActivityManager( 2937): filter receiver for action = android.net.wifi.p2p.STATE_CHANGED
E/WifiStateMachine( 2937): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
I/ActivityManager( 2937): filter receiver for action = android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 2937):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=107106  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,I/art     ( 2937): Can not find class: Lcom/android/server/wifi/SupplicantStateTracker$1;
,I/art     ( 2937): Can not find class: Lcom/android/server/display/WifiDisplayController$2;
,I/ActivityManager( 2937): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
I/ActivityManager( 2937): filter receiver for action = android.net.wifi.p2p.THIS_DEVICE_CHANGED
,I/NetworkSpeedManagerEx( 3472): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3472): wifiManager = android.net.wifi.WifiManager@24dacd11
,I/NetworkSpeedManagerEx( 3472): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3472): stop
,I/wpa_supplicant( 6987): set current WIFI status to BT!
I/bluetooth-coex( 6965): btcoex_socket_server: accept socket success
I/bluetooth-coex( 6965): set_bt_coex_mode_ext: wlan common protect cancelled, nothing to do
E/WifiMonitor( 2937): handleEvent 12  CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:48
E/WifiMonitor( 2937): handleEvent 12  CTRL-EVENT-BSS-ADDED 1 c2:ff:d4:d3:aa:48
E/WifiMonitor( 2937): handleEvent 12  CTRL-EVENT-BSS-ADDED 2 38:f8:89:11:e9:11
E/WifiMonitor( 2937): handleEvent 12  CTRL-EVENT-BSS-ADDED 3 06:7c:34:12:7f:81
E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=6 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 2937): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=7 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 2937): couldn't identify event type - WPS-AP-AVAILABLE 
I/NetworkSpeedManagerEx( 3472): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3472): wifiManager = android.net.wifi.WifiManager@24dacd11
I/NetworkSpeedManagerEx( 3472): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
I/NetworkSpeedManagerEx( 3472): stop
E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/WifiStateMachine( 2937):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
,I/WifiTracker( 3472): STATE =1
E/WifiStateMachine( 2937):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 2937):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 2937):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/wifi    ( 2937): android_net_wifi_getLinkLayerStats: failed to get link statistics
E/WifiStateMachine( 2937): [1,448,458,053,635 ms] noteScanEnd no scan source
,E/WifiStateMachine( 2937): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@16ca61d3 sup_state=SCANNING debouncing=false
,I/WifiTracker( 3472): STATE =1
,E/WifiAutoJoinController ( 2937): NG700 c0:ff:d4:d3:aa:48 rssi=-61 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController ( 2937): 01ABC c2:ff:d4:d3:aa:48 rssi=-62 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController ( 2937): Gonzos 38:f8:89:11:e9:11 rssi=-84 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController ( 2937): UPC Wi-Free 06:7c:34:12:7f:81 rssi=-88 cap [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS] is not scored
,E/WifiAutoJoinController ( 2937): ageScanResultsOut delay 40000 size 4 now 1448458053645
E/WifiAutoJoinController ( 2937): newSupplicantResults size=4 known=1 true
,E/WifiAutoJoinController ( 2937): attemptAutoJoin() status=wpa_state=SCANNING
E/WifiAutoJoinController ( 2937): p2p_device_address=58:2a:f7:ed:a4:6c
E/WifiAutoJoinController ( 2937): address=58:2a:f7:ed:a4:6c
E/WifiAutoJoinController ( 2937): uuid=fc3e6a12-87ef-50cc-87ec-720c7386849f split=4
,E/WifiAutoJoinController ( 2937): attemptAutoJoin() num recent config 1 ---> suppNetId=-1
,E/WifiAutoJoinController ( 2937): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-61,-127) num=(1,0)
E/WifiAutoJoinController ( 2937): attemptAutoJoin trying id=0 "NG700"WPA_PSK status=0
E/WifiAutoJoinController ( 2937): look up all configurations network done, candidate = "NG700"
E/WifiAutoJoinController ( 2937): attemptAutoJoin networkSwitching candidate "NG700"WPA_PSK linked=false : delta=1000 
,E/WifiStateMachine( 2937): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiAutoJoinController ( 2937): AutoJoin auto connect with netId 0 to "NG700"WPA_PSK
,E/WifiAutoJoinController ( 2937): Done attemptAutoJoin status=3
,I/art     ( 2937): Can not find class: Lcom/android/server/net/DelayedDiskWrite$1;
,I/ActivityManager( 2937): filter receiver for action = android.net.wifi.SCAN_RESULTS
,E/WifiStateMachine( 2937):  DisconnectedState CMD_AUTO_CONNECT 0 3 "NG700"WPA_PSK [1 ,-61 ;0 ,-127] any roam=0 rt=107229
E/WifiStateMachine( 2937):  ConnectModeState CMD_AUTO_CONNECT 0 3 "NG700"WPA_PSK [1 ,-61 ;0 ,-127] any roam=0 rt=107229
,E/WifiStateMachine( 2937): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
I/art     ( 2937): Can not find class: Lcom/huawei/android/server/wifi/HwCustWifiConfigStoreImpl;
,E/WifiStateMachine( 2937): CMD_AUTO_CONNECT will save config -> "NG700" nid=0
I/System.out( 3913): BitString length 17
I/System.out( 3913): MAC Addressc0:ff:d4:d3:aa:48
I/System.out( 3913): BitString length 17
I/System.out( 3913): MAC Addressc2:ff:d4:d3:aa:48
I/System.out( 3913): BitString length 17
I/System.out( 3913): MAC Address38:f8:89:11:e9:11
I/System.out( 3913): BitString length 17
I/System.out( 3913): MAC Address06:7c:34:12:7f:81
,E/PhoneInterfaceManager( 3890): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/SUPL20_LocMan( 3913): Phone type:GSM
,I/SUPL20_LocMan( 3913): NULL Value received for network operator
I/SUPL20_LocMan( 3913):  cellInfo NetworkType:NOT RETERIVE,21
,I/SUPL20_SPIMESLP-SENDING( 3913): m_bPacket.length 341
I/SUPL20_SPIMESLP-SENDING( 3913): bBrokenPipe = false
,E/WifiConfigStore( 2937): Setting BSSID for "NG700"WPA_PSK to c0:ff:d4:d3:aa:48
,E/WifiConfigStore( 2937): will read network variables netId=0
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/WifiStateMachine( 2937): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiNative: ( 2937): [107,399,760 us] enableNetwork nid=0 disableOthers=false stack:logDbg - enableNetwork - enableNetworkWithoutBroadcast - processMessage - processMsg
,E/WifiConfigStore( 2937): will read network variables netId=0
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,I/HwSystemManager( 4085): HoldService:uid:10050 pid:6592 died
I/HwSystemManager( 4085): BgPowerManagerService:onProcessDied uid = 10050
I/HwSystemManager( 4085): HoldService:oldVersionKey:10050,6592
E/HsmCoreServiceImpl( 2937): onTransact in code is: 102
I/MediaProcessHandler( 2937): processOp opType: 1, uid: 10050, pid: 6592
W/MediaProcessHandler( 2937): remove target not exist, maybe the UI process: uid: 10050, pid: 6592
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/WifiNative: ( 2937): [107,431,316 us] enableNetwork nid=0 disableOthers=true stack:logDbg - enableNetwork - enableNetworkWithoutBroadcast - selectNetwork - processMessage
,I/wpa_supplicant( 6987): Trying to associate with c0:**:**:**:aa:48 (SSID='NG700' freq=2462 MHz),
E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=8 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,W/wpa_supplicant( 6987): check_associate_result func start
E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00:00:00:00:00:00 SSID=NG700
,E/WifiNative: ( 2937): [107,434,674 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
,I/wpa_supplicant( 6987): set current WIFI status to BT!
,I/bluetooth-coex( 6965): btcoex_socket_server: accept socket success
I/bluetooth-coex( 6965): set_bt_coex_mode_ext: wlan common protect scheduling
I/bluetooth-coex( 6965): btcoex_set_a2dp_priority: bdaddr: 000000000000
I/bluetooth-coex( 6965): btcoex_set_a2dp_priority: A2DP - no link control block
I/bluetooth-coex( 6965): set_bt_coex_mode_ext: wlan common protect, no need to set bt priority
,E/WifiConfigStore( 2937): setLastSelectedConfiguration -1
,E/WifiStateMachine( 2937):  DisconnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):18 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:1054075120] from screen [on:0 period:1054075120]
,E/WifiStateMachine( 2937):  DisconnectedState CMD_TARGET_BSSID 8 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=3 rt=107441
,E/WifiStateMachine( 2937):  ConnectModeState CMD_TARGET_BSSID 8 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=3 rt=107441
E/WifiStateMachine( 2937):  DriverStartedState CMD_TARGET_BSSID 8 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=3 rt=107442
,E/WifiStateMachine( 2937):  SupplicantStartedState CMD_TARGET_BSSID 8 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=3 rt=107442
,E/WifiStateMachine( 2937):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 9 0 rt=107442  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATING
E/WifiStateMachine( 2937): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
,I/ActivityManager( 2937): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2937): filter receiver for action = android.net.wifi.STATE_CHANGE,
,E/WifiStateMachine( 2937):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 9 0 rt=107448  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATING,
,I/ActivityManager( 2937): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3472): receive:android.net.wifi.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3472): wifiManager = android.net.wifi.WifiManager@24dacd11
I/NetworkSpeedManagerEx( 3472): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3472): stop
,I/NetworkSpeedManagerEx( 3472): receive:android.net.wifi.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3472): wifiManager = android.net.wifi.WifiManager@24dacd11
I/NetworkSpeedManagerEx( 3472): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3472): stop
,I/WifiTracker( 3472): STATE =1
,I/WifiTracker( 3472): STATE =1
,I/jxcore-log( 6900): Got Device Bluetooth address: 58:2A:F7:ED:96:BE
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): my name is : HUAWEI-ALE-L21_PT9762
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): attempting to connect to test coordinator
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): check test folder
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): found test : ./testFindPeers.js
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): found test : ./testReConnect.js
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): found test : ./testSendData.js
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): Test app app.js loaded
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6900): 
,I/chromium( 6900): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/chromium( 6900): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/wpa_supplicant( 6987): check_associate_result func start
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=10 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,I/wpa_supplicant( 6987): wlan0: Associated with c0:ff:d4:d3:aa:48
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=11 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
,E/WifiStateMachine( 2937):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 10 0 rt=108392  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 2937): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
,I/ActivityManager( 2937): filter receiver for action = android.net.wifi.STATE_CHANGE
,E/WifiStateMachine( 2937):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 10 0 rt=108394  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,E/WifiStateMachine( 2937): fetchRssiLinkSpeedAndFrequencyNative rssi=-61 linkspeed=72 SSID="NG700"
,W/wpa_supplicant( 6987): check_associate_result func start
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/WifiStateMachine( 2937):  DisconnectedState CMD_ASSOCIATED_BSSID 11 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=3 rt=108408
,E/WifiStateMachine( 2937):  ConnectModeState CMD_ASSOCIATED_BSSID 11 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=3 rt=108409
E/WifiStateMachine( 2937):  DriverStartedState CMD_ASSOCIATED_BSSID 11 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=3 rt=108409
,E/WifiStateMachine( 2937):  SupplicantStartedState CMD_ASSOCIATED_BSSID 11 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=3 rt=108409
,E/WifiStateMachine( 2937):  DefaultState CMD_ASSOCIATED_BSSID 11 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=3 rt=108410
,E/WifiStateMachine( 2937):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=108410  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 2937): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,I/ActivityManager( 2937): filter receiver for action = android.net.wifi.STATE_CHANGE
,E/WifiStateMachine( 2937):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=108412  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
,I/ActivityManager( 2937): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE,
W/wpa_supplicant( 6987): check_associate_result func start
,W/wpa_supplicant( 6987): check_associate_result func start
E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=13 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 6987): WPA: Key negotiation completed with c0:**:**:**:aa:48 [PTK=CCMP GTK=CCMP]
E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=14 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 2937): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 6987): set current WIFI status to BT!
I/bluetooth-coex( 6965): btcoex_socket_server: accept socket success
I/wpa_supplicant( 6987): set current WIFI status to BT!
I/bluetooth-coex( 6965): set_bt_coex_mode_ext: BT_COEX_PAUSE cancel
I/bluetooth-coex( 6965): btcoex_socket_server: accept socket success,
I/bluetooth-coex( 6965): set_bt_coex_mode_ext: BT_COEX_CHANNEL, fist[47]last[73]afh_result[0]
E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
E/WifiMonitor( 2937): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 6987): CTRL-EVENT-CONNECTED - Connection to c0:**:**:**:aa:48 completed (auth) [id=0 id_str=]
,W/wpa_supplicant( 6987): check_associate_result func start
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=16 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/ActivityManager( 2937): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
E/WifiStateMachine( 2937):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 13 0 rt=108426  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 2937): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 2937):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 13 0 rt=108427  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 2937):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=108428
E/WifiStateMachine( 2937):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=108429
,I/ActivityManager( 2937): filter receiver for action = android.net.wifi.STATE_CHANGE,
,W/System.err( 2937): java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
,W/System.err( 2937): 	at com.huawei.android.server.wifi.ReportTool.getUserType(ReportTool.java:86),
,W/System.err( 2937): ,	at com.huawei.android.server.wifi.ReportTool.isBetaUser(ReportTool.java:73)
W/System.err( 2937): 	at com.huawei.android.server.wifi.ReportTool.report(ReportTool.java:58)
W/System.err( 2937): 	at com.huawei.android.server.wifi.DataUploader.e(DataUploader.java:57)
,W/System.err( 2937): 	at com.android.server.wifi.WifiStateMachine$ConnectModeState.processMessage(WifiStateMachine.java:7299)
W/System.err( 2937): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/System.err( 2937): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/System.err( 2937): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2937): 	at android.os.Looper.loop(Looper.java:135)
,W/System.err( 2937): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ReportTools( 2937): This is not beta user build
I/WiFi_PRO( 2937): obtaining wifi is conencted
,I/ActivityManager( 2937): filter receiver for action = android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 2937): setScanAlarm false period 0 initial delay 0
,I/WiFi_PRO( 2937): obtaining wifi is conencted
,I/ActivityManager( 2937): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/art     ( 2937): Can not find class: Lcom/android/server/connectivity/NetworkMonitor;,
,I/NetworkSpeedManagerEx( 3472): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3472): wifiManager = android.net.wifi.WifiManager@24dacd11
I/NetworkSpeedManagerEx( 3472): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3472): stop
,I/art     ( 2937): Can not find class: Lcom/android/server/connectivity/NetworkMonitor$DefaultState;
,I/art     ( 2937): Can not find class: Lcom/android/server/connectivity/NetworkMonitor$OfflineState;
,I/art     ( 2937): Can not find class: Lcom/android/server/connectivity/NetworkMonitor$ValidatedState;
,I/art     ( 2937): Can not find class: Lcom/android/server/connectivity/NetworkMonitor$EvaluatingState;
,I/art     ( 2937): Can not find class: Lcom/android/server/connectivity/NetworkMonitor$UserPromptedState;
,I/art     ( 2937): Can not find class: Lcom/android/server/connectivity/NetworkMonitor$CaptivePortalState;
,I/art     ( 2937): Can not find class: Lcom/android/server/connectivity/NetworkMonitor$LingeringState;
,E/WifiStateMachine( 2937): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid c0:ff:d4:d3:aa:48
,E/WifiStateMachine( 2937): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 2937): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/WifiStateMachine( 2937): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
,E/WifiStateMachine( 2937): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 2937): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/NetworkSpeedManagerEx( 3472): receive:android.net.wifi.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3472): wifiManager = android.net.wifi.WifiManager@24dacd11
I/NetworkSpeedManagerEx( 3472): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3472): stop
,E/WifiStateMachine( 2937): Start Dhcp Watchdog 1
,E/WifiStateMachine( 2937):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 16 0 rt=108510  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine( 2937):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 16 0 rt=108510  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine( 2937):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 16 0 rt=108511  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,I/ActivityManager( 2937): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,E/WifiStateMachine( 2937):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2937):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0,
E/WifiStateMachine( 2937):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2937):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2937):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2937): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 2937):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
,E/WifiStateMachine( 2937):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
,I/wpa_supplicant( 6987): set current WIFI status to BT!
,I/bluetooth-coex( 6965): btcoex_socket_server: accept socket success
I/bluetooth-coex( 6965): set_bt_coex_mode_ext: get dhcp start, wait for complete msg
,E/native  ( 2937): do suspend false
,E/WifiStateMachine( 2937): Unexpected BatchedScanResults :OK
,E/WifiStateMachine( 2937): noteBatchedScanstop()
,I/ActivityManager( 2937): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3472): receive:android.net.wifi.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3472): wifiManager = android.net.wifi.WifiManager@24dacd11
I/NetworkSpeedManagerEx( 3472): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
,I/NetworkSpeedManagerEx( 3472): stop
,I/NetworkSpeedManagerEx( 3472): receive:android.net.wifi.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3472): wifiManager = android.net.wifi.WifiManager@24dacd11
I/NetworkSpeedManagerEx( 3472): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
,I/NetworkSpeedManagerEx( 3472): stop
,I/WifiTracker( 3472): STATE =1,
,I/NetworkSpeedManagerEx( 3472): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3472): wifiManager = android.net.wifi.WifiManager@24dacd11
,I/NetworkSpeedManagerEx( 3472): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
,I/NetworkSpeedManagerEx( 3472): stop
,I/WifiTracker( 3472): STATE =1
,I/WifiTracker( 3472): STATE =1
,I/WifiTracker( 3472): STATE =1
,I/WifiTracker( 3472): STATE =1
,I/DHCPCD  ( 7134): version 5.5.6 starting
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,W/DHCPCD  ( 7134): hw_parse_xidfile 
,I/DHCPCD  ( 7134): wlan0: dhcp start reboot
I/DHCPCD  ( 7134): wlan0: rebinding lease of 192.168.1.118
,I/DHCPCD  ( 7134): wlan0: dhcp ack, acknowledged 192.168.1.118 from 192.168.1.1
,I/DHCPCD  ( 7134): wlan0: checking for 192.168.1.118
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6900): 
,E/WifiStateMachine( 2937):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2937):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2937):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2937):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2937): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/DHCPCD  ( 7134): wlan0: leased 192.168.1.118 for 86400 seconds
,E/WifiStateMachine( 2937):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2937):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2937):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2937):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2937):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2937): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine( 2937):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
,E/WifiStateMachine( 2937):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
,E/native  ( 2937): do suspend true
,I/wpa_supplicant( 6987): set current WIFI status to BT!
,I/bluetooth-coex( 6965): btcoex_socket_server: accept socket success
I/bluetooth-coex( 6965): set_bt_coex_mode_ext: get dhcp done, stop timer during reserved time
,E/WifiStateMachine( 2937): wifistatemachine handleIPv4Success <IP address 192.168.1.118/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
E/WifiStateMachine( 2937): link address 192.168.1.118/24
,E/WifiStateMachine( 2937): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine( 2937): updateWifiIp  StateMachine 192.168.1.118
,E/WifiStateMachine( 2937):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,I/ActivityManager( 2937): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2937): filter receiver for action = android.net.wifi.STATE_CHANGE,
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/wifi_log/wifi_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/ActivityManager( 2937): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2937): filter receiver for action = android.net.wifi.STATE_CHANGE
,E/WifiStateMachine( 2937): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
,E/WifiStateMachine( 2937): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/WifiStateMachine( 2937): updateDefaultRouteMacAddress reachable (tried again) :192.168.1.1 found c0:ff:d4:d3:aa:48
,I/NetworkSpeedManagerEx( 3472): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3472): wifiManager = android.net.wifi.WifiManager@24dacd11
,I/NetworkSpeedManagerEx( 3472): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = true, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3472): stop
,I/HwSystemManager( 4085): aor:Network Stats Updated
I/HwSystemManager( 4085): aoi:onNetworkStatsUpdated
,I/HwSystemManager( 4085): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 4085): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 4085): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 4085): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 4085): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 4085): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
I/HwSystemManager( 4085): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 4085): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 4085): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 4085): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 4085): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,I/NetworkSpeedManagerEx( 3472): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3472): wifiManager = android.net.wifi.WifiManager@24dacd11
E/HwSystemManager( 4085): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/NetworkSpeedManagerEx( 3472): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = true, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3472): stop
I/HwSystemManager( 4085): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 4085): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 4085): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 4085): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 4085): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 4085): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
,I/NetworkSpeedManagerEx( 3472): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3472): wifiManager = android.net.wifi.WifiManager@24dacd11
,I/NetworkSpeedManagerEx( 3472): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = true, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3472): stop
,I/NetworkSpeedManagerEx( 3472): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3472): wifiManager = android.net.wifi.WifiManager@24dacd11
,I/NetworkSpeedManagerEx( 3472): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = true, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3472): stop
,I/WifiTracker( 3472): STATE =1
,W/View    ( 3472): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{51589be V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during layout: running second layout pass
,W/View    ( 3472): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{51589be V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during second layout pass: posting in next frame
,I/WifiTracker( 3472): STATE =1
,I/WifiTracker( 3472): STATE =1
,I/WifiTracker( 3472): STATE =1
,W/View    ( 3472): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{51589be V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during second layout pass: posting in next frame
,I/System  ( 2937): core_booster, getBoosterConfig = false
,E/WifiStateMachine( 2937):  ConnectedState CMD_UNWANTED_NETWORK 3 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2462 sc=0 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2775] from screen [on:0 period:1054077896]
,I/wpa_supplicant( 6987): set current WIFI status to BT!
,I/bluetooth-coex( 6965): btcoex_socket_server: accept socket success
I/bluetooth-coex( 6965): set_bt_coex_mode_ext: BT_COEX_CHANNEL, fist[47]last[73]afh_result[0]
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 6900): 
,W/ArpVerifier( 2937): ignore msg MSG_CHECK_WIFI_STATE, msg token = 2, expected token = 3
,I/ActivityManager( 2937): filter receiver for action = android.net.conn.CONNECTIVITY_CHANGE
,I/SUPL20_SCM( 3913): Network connection true
,I/SUPL20_SPIMESLP-SENDING( 3913): m_bPacket.length 8
I/SUPL20_SPIMESLP-SENDING( 3913): bBrokenPipe = false
,I/art     ( 2937): Can not find class: Lcom/android/server/content/SyncManager$ActiveSyncContext;
,I/art     ( 2937): Can not find class: Lcom/android/server/content/SyncStorageEngine$SyncHistoryItem;
,E/WifiStateMachine( 2937):  ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 2937):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,E/WifiStateMachine( 2937):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,I/art     ( 2937): Explicit concurrent mark sweep GC freed 57950(3MB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 28MB/42MB, paused 2.045ms total 204.090ms
,I/art     ( 2937): Can not find class: Lcom/android/server/content/SyncManager$ServiceConnectionData;
,I/TimeManager( 3472): receiver action = android.intent.action.TIME_SET
I/HwLauncher( 3936): Model  onReceive intent=Intent { act=android.intent.action.TIME_SET flg=0x24000010 }
,I/TimeManager( 3472): hand message 1
I/TimeManager( 3472): notify time change. size = 2
,I/TimeLayout( 3472): time = 14:27
,I/TimeLayout( 3472): updateDate date = 11/25/2015
,I/TimeLayout( 3472): weekDay = Wednesday
,I/HwSystemManager( 4085): aor:Network Stats Updated
I/HwSystemManager( 4085): aoi:onNetworkStatsUpdated
,E/HwSystemManager( 4085): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 4085): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 4085): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
,I/HwSystemManager( 4085): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 4085): getSimCardType:/getSimCardInfo: imsi is null
,I/HwEmailTag( 7177): MailAppProvider->onCreate->begin, consuming 1448458060739ms->-prefixstartupperformance-
,E/HwSystemManager( 4085): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 4085): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 4085): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
W/SyncManager( 2937): SyncManager manageSyncAlarmLocked SET_WAKE_ALARM
,E/HwSystemManager( 4085): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
,I/HwSystemManager( 4085): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 4085): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 4085): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 4085): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 4085): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 4085): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/HwSystemManager( 4085): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/TEST-APN( 3890): query for APN: check-permission succ 
E/TEST-APN( 3890): Telephony query SQL: SELECT apn FROM carriers WHERE (_id = -1)
,E/HwSystemManager( 4085): getSimCardType:/getSimCardInfo: imsi is null
,E/GpsLocationProvider( 2937): No APN found to select.
,E/HwSystemManager( 4085): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 4085): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 4085): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 4085): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
,W/GNSS_ADAPTER( 2937): This function not used.
W/GNSS_ADAPTER( 2937): This function not used.
,I/HwEmailTag( 7177): MailAppProvider->onCreate->end, consuming 1448458060778ms->-prefixstartupperformance-
,I/HwCust  ( 7177): Constructor found for class com.android.email.service.HwCustImapServiceImpl
,I/HwCust  ( 7177): Constructor found for class com.android.email.HwCustUtilityImpl
,I/HwCust  ( 7177): Constructor found for class com.android.email.provider.HwCustEmailProviderImpl
,I/HwCust  ( 7177): Constructor found for class com.android.email.activity.setup.HwCustEmailInviteResponseImpl
,I/HwEmailTag( 7177): EmailProvider->onCreate->start. -prefixstartupperformance-
I/HwEmailTag( 7177): EmailProvider->onCreate->start. -prefixstartupperformance-
I/HwEmailTag( 7177): HwUtils->initStaticVarsAsync
I/HwEmailTag( 7177): HwUtils->initStaticVarsAsync
,I/HwCust  ( 7177): Constructor found for class com.android.emailcommon.provider.HwCustPolicyImpl
,I/HwEmailTag( 7177): EmailContent->init->consuming:18ms->;-prefixstartupperformance-
,I/HwEmailTag( 7177): EmailProvider->sURIMatcher is initialized
,I/HwEmailTag( 7177): EmailProvider->INTEGRITY_CHECK_URI != null
,I/HwEmailTag( 7177): EmailProvider->onCreate->end, consuming 34ms->-prefixstartupperformance-
,I/HwEmailTag( 7177): EmailProvider->onCreate->end, consuming 35ms->-prefixstartupperformance-
I/HwEmailTag( 7177): EmailProvider->resetVisibleLimits->start:1448458060842 ->-prefixstartupperformance-
,I/HwCust  ( 7177): Constructor found for class com.huawei.email.provider.HwCustRecipientDBHelperImpl
,I/HwEmailTag( 7177): EmailProvider->resetVisibleLimits->start:1448458060846 ->-prefixstartupperformance-
,I/HwEmailTag( 7177): DBHelper->onOpen-> EmailProvider.db
,I/HwEmailTag( 7177): HwUtils->initStaticVarsAsync->run:consuming:63ms; bidiFormatter:android.support.v4.text.BidiFormatter@339c1f55;accountsProjSize:42
,I/HwEmailTag( 7177): HwUtils->initStaticVarsAsync->run:consuming:63ms; bidiFormatter:android.support.v4.text.BidiFormatter@339c1f55;accountsProjSize:42
,I/HwEmailTag( 7177): EmailProvider->getDatabase->-prefixstartupperformance-database, consuming = 32ms.
,I/HwEmailTag( 7177): DBHelper->onOpen-> EmailProvider.db
,I/HwEmailTag( 7177): EmailApplication->onCreate->begin, consuming 87ms->-prefixstartupperformance-
,I/HwEmailTag( 7177): EmailApplication->triggerPeriodSyncForAllAccountsDelayed->delay start.
,I/art     ( 2937): Can not find class: Lcom/android/server/location/GpsLocationProvider$7;
,I/HwCust  ( 7177): Constructor found for class com.huawei.email.utils.HwCustSignatureHelperImpl
,I/HwCust  ( 7177): Constructor found for class com.huawei.email.utils.HwCustSignatureUtilsImpl
,I/HwEmailTag( 7177): EmailApplication->onCreate->end, consuming 94ms->-prefixstartupperformance-
,E/GNSS_ADAPTER( 2937): gnss adapter is not inited, fail to inject time!
I/HwEmailTag( 7177): EmailBroadcastReceiver->onReceive->action:android.net.conn.CONNECTIVITY_CHANGE
,I/HwEmailTag( 7177): HwUtils->notifyNetworkChanged->
,I/HwEmailTag( 7177): EmailProvider->notifyNetworkChanged->
,E/Thermal-daemon( 2331): [charger_ic] temp_new :32  temp_old :31
,I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6647): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,E/Auth.Api.Credentials( 5839): [CredentialSyncAdapter] Unknown sync event.
,I/PG Utils( 6647): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/HwEmailTag( 7177): EmailProvider->initBuildCache->start->1448458061035->-prefixstartupperformance-
,I/HwEmailTag( 7177): EmailProvider->buildCache->end, consuming:2ms;
I/HwEmailTag( 7177): EmailProvider->initBuildCache->start->1448458061035; consuming:2->-prefixstartupperformance-
I/HwEmailTag( 7177): EmailProvider->resetVisibleLimits->getDatabase, consuming:196ms;-prefixstartupperformance-
I/HwEmailTag( 7177): EmailProvider->startupperformance->resetVisibleLimits->no account, return directly.
,I/HwEmailTag( 7177): EmailProvider->uiAccounts->start:1448458061040
,I/ActivityManager( 2937): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/HwEmailTag( 7177): DBHelper->onOpen-> EmailProvider.db
,I/art     ( 2937): Can not find class: Lcom/android/server/content/SyncManager$SyncHandlerMessagePayload;
,I/HwEmailTag( 7177): EmailProvider->getDatabase->-prefixstartupperformance-database, consuming = 17ms.
,I/HwEmailTag( 7177): DBHelper->onOpen-> EmailProvider.db
,I/MusicStore( 7215): Database version: 120
,I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 7215): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/HwEmailTag( 7177): EmailProvider->resetVisibleLimits->getDatabase, consuming:331ms;-prefixstartupperformance-
I/HwEmailTag( 7177): EmailProvider->startupperformance->resetVisibleLimits->no account, return directly.
,I/HwEmailTag( 7177): EmailProvider->uiAccounts->start:1448458061040;end,consuming:142
,I/HwEmailTag( 7177): EmailProvider->query->1448458060842;end;;consuming:340ms;
,W/ContextImpl( 7215): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ContextImpl( 7215): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ContextImpl( 7215): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,E/ConnectivityChangeReceiver( 5839): Ignoring connectivity change
,I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 7215): Can not find class: Lcom/google/android/gms/org/conscrypt/OpenSSLSocketFactoryImpl;
,W/System  ( 7215): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@50ab80b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7215): Installed default security provider GmsCore_OpenSSL
,I/PG Utils( 6647): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/ConfigStore( 7215): Config Database version: 1
,I/PG Utils( 6647): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,E/Thermal-daemon( 2331): [ap] temp_new :32  temp_old :31
,I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/AbstractGoogleClient( 7249): Application name is not set. Call Builder#setApplicationName.
,I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/art     ( 6647): Attempt to remove local handle scope entry from IRT, ignoring
,I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/MediaRouter( 7215): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=6, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/NetworkMonitor( 7215): type=WIFI subType= reason=null isConnected=true
,I/PG Utils( 7249): acquire_providerpkg:[com.android.providers.calendar] pid:[]  maybe timeout , send to PG
,I/PG Utils( 7249): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 3984): Explicit concurrent mark sweep GC freed 7570(464KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 18MB/30MB, paused 1.111ms total 77.799ms
,W/StubController( 7274): calendar access!
I/PG Utils( 7249): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/NetworkMonitor( 7215): type=WIFI subType= reason=null isConnected=true
,W/DriveInitializer( 5839): Awaiting to be initialized
,W/DriveInitializer( 5839): Background init thread started
,I/PG Utils( 7215): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/DownloadManager( 3496): enter DownloadReceiver::onReceive(action:android.net.conn.CONNECTIVITY_CHANGE intent:Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.providers.downloads/.DownloadReceiver (has extras) })
,I/HwCust  ( 6392): Constructor found for class com.huawei.mms.util.HwCustUpdateUserBehaviorImpl
,I/HwCust  ( 6392): Constructor found for class com.huawei.mms.util.HwCustHwMessageUtilsImpl
,I/Mms_TXM_SVC( 6392): onStartCommand send EVENT_NEW_INTENT. service-id 1
,W/Mms_TXM_SVC( 6392): ConnectivityBroadcastReceiver.onReceive() action: android.net.conn.CONNECTIVITY_CHANGE
,W/ContextImpl( 5839): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.gms/files
,I/MagazineUtils( 3404): is magazine unlock on, now is lock screen diabled mode
,W/StubController( 7249): calendar access!
,I/GHttpClientFactory( 7215): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/GoogleURLConnFactory( 7215): Using platform SSLCertificateSocketFactory
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6900): 
,W/System.err( 2937): java.lang.SecurityException: WifiService: Neither user 10084 nor current process has android.permission.CHANGE_WIFI_STATE.
W/System.err( 2937): 	at android.app.ContextImpl.enforce(ContextImpl.java:1962)
W/System.err( 2937): 	at android.app.ContextImpl.enforceCallingOrSelfPermission(ContextImpl.java:1991)
W/System.err( 2937): 	at com.android.server.wifi.WifiServiceImpl.enforceChangePermission(WifiServiceImpl.java:784)
W/System.err( 2937): 	at com.android.server.wifi.WifiServiceImpl.getWifiServiceMessenger(WifiServiceImpl.java:1903)
W/System.err( 2937): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:495)
W/System.err( 2937): 	at com.android.server.wifi.HwWifiService.onTransact(HwWifiService.java:61)
W/System.err( 2937): 	at android.os.Binder.execTransact(Binder.java:446)
,E/WifiManager( 7215): WifiServiceMessenger == null
,I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 7249): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/StubController( 7249): calendar access!
,E/HwOUC   ( 7311): [main-1]load system config caught FileNotFoundException(/HwOucConfig.java:1298)
,I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
W/DriveInitializer( 5839): Background init thread ended
,I/art     ( 7311): Can not find class: Lcom/huawei/pad/Product;
,E/HwOUC   ( 7311): [main-1]method invoke failed(/HwOucUtility.java:471)
I/HwOUC   ( 7311): [main-1]isTablet() = false(/HwOucUtility.java:474)
,I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/HwOUC   ( 7311): [main-1]baseVersionOfNewVersion is ALE-L21C432B132;isInstallingStatus is false(/HwOucUtility.java:2228)
,I/HwOUC   ( 7311): [main-1]HwOucApplication--onCreate, cacheCpuInfo is 8_1.2GHz(hwouc/HwOucApplication.java:48)
,I/HwOUC   ( 7311): [main-1]Network changed(hwouc/DownloadReceiver.java:138)
,I/HwOUC   ( 7311): [main-1]Network available(hwouc/DownloadReceiver.java:142)
,I/HwOUC   ( 7311): [main-1]Push apk is not exists !(hwouc/DownloadReceiver.java:454)
,I/HwOUC   ( 7311): [main-1]checkRequestSendSuccessFlag is true(hwouc/DownloadReceiver.java:163)
,I/HwOUC   ( 7311): [main-1]is6HourReportedFlag is true(hwouc/DownloadReceiver.java:178)
,I/art     ( 2324): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 192us total 23.914ms
,I/art     ( 2324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 191us total 22.233ms
,I/art     ( 2324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 190us total 21.861ms
,I/art     ( 2937): Explicit concurrent mark sweep GC freed 22823(1302KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 28MB/42MB, paused 2.030ms total 191.044ms
,I/HwOUC   ( 7311): [Thread-109-109]isExternalSdcardExist, no External SDCard(hwouc/HwOucUtility.java:995)
,I/HwOUC   ( 7311): [Thread-109-109]isCheckAutoAndReport is true(hwouc/KillMyselfProcessCheckThread.java:370)
,W/asset   ( 7347): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/Process ( 7311): Sending signal. PID: 7311 SIG: 9
,I/HwSystemManager( 4085): HoldService:uid:10004 pid:6349 died
I/HwSystemManager( 4085): HoldService:oldVersionKey:10004,6349
I/HwSystemManager( 4085): BgPowerManagerService:onProcessDied uid = 10004
E/HsmCoreServiceImpl( 2937): onTransact in code is: 102
I/MediaProcessHandler( 2937): processOp opType: 1, uid: 10004, pid: 6349
W/MediaProcessHandler( 2937): remove target not exist, maybe the UI process: uid: 10004, pid: 6349
I/HwSystemManager( 4085): HoldService:uid:10010 pid:6224 died
I/HwSystemManager( 4085): HoldService:oldVersionKey:10010,6224
I/HwSystemManager( 4085): BgPowerManagerService:onProcessDied uid = 10010
,E/HsmCoreServiceImpl( 2937): onTransact in code is: 102
I/MediaProcessHandler( 2937): processOp opType: 1, uid: 10010, pid: 6224
W/MediaProcessHandler( 2937): remove target not exist, maybe the UI process: uid: 10010, pid: 6224
,I/PG Utils( 7249): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/HwCust  ( 7347): Constructor found for class com.huawei.android.thememanager.common.HwCustThemeHelperImpl
,I/art     ( 7347): Can not find class: Landroid/provider/Settings$Systemex;
,E/HwThemeManager( 7347): ThemeHelperretry to get Settings
,I/System  ( 7249): core_booster, getBoosterConfig = false
,I/HwSystemManager( 4085): HoldService:uid:10052 pid:7311 died
I/HwSystemManager( 4085): HoldService:oldVersionKey:10052,7311
E/HsmCoreServiceImpl( 2937): onTransact in code is: 102
I/HwSystemManager( 4085): BgPowerManagerService:onProcessDied uid = 10052
I/MediaProcessHandler( 2937): processOp opType: 1, uid: 10052, pid: 7311
W/MediaProcessHandler( 2937): remove target not exist, maybe the UI process: uid: 10052, pid: 7311
,I/System  ( 7249): core_booster, getBoosterConfig = false
,I/PG Utils( 6647): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/asset   ( 7374): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/HwCust  ( 7374): Constructor found for class com.huawei.android.totemweather.HwCustWeatherAppHwBaseImpl
,E/HwSystemManager( 6614): SecurityBroadcastReceiver:SecurityBroadcastReceiver the rainbow is not enabled!
,W/StubController( 7249): calendar access!
,I/CalendarProvider2( 7274): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 7274): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager( 2937): filter receiver for action = android.intent.action.PROVIDER_CHANGED
,I/PG Utils( 7249): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6647): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 7249): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/HwEmailTag( 7177): EmailProvider->query->1448458062846;end;;consuming:3ms;
,I/HwEmailTag( 7177): EmailApplication->handleMessage->startService CleanRecipientAddressService
,I/HwSystemManager( 4085): BgPowerManagerService:onProcessDied uid = 1000
I/HwEmailTag( 7177): Device->updateDeviceIdIfNeeded
E/HsmCoreServiceImpl( 2937): onTransact in code is: 102
W/MediaProcessHandler( 2937): processOp uid 1000 is not concerned!
,I/HwEmailTag( 7177): CleanRecipient->onCreate
,I/HwSystemManager( 4085): HoldService:uid:1000 pid:6706 died
I/HwSystemManager( 4085): HoldService:oldVersionKey:1000,6706
,I/HwEmailTag( 7177): CleanRecipient->onStartCommand->action is null
,I/HwEmailTag( 7177): Device->updateDeviceIdIfNeeded->doInBackground
,I/HwEmailTag( 7177): CleanRecipient->onHandleIntent->action is null
,I/HwEmailTag( 7177): Device->getDeviceId->
,I/HwEmailTag( 7177): Device->getDeviceIdInternal->isUpdate:false
,I/HwEmailTag( 7177): Device->getDeviceIdInternal->get id from deviceName, return successfully.
,I/HwEmailTag( 7177): Device->updateDeviceIdIfNeeded->deviceId is consistent id , return directly.
,I/HwEmailTag( 7177): CleanRecipient->onHandleIntent-> clean RecipientAddress done, nothing changed!!
,I/HwEmailTag( 7177): CleanRecipient->onDestroy
,I/PG Utils( 7249): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/HwEmailTag( 7177): AccountReconciler->reconcileAccountsInternal->consuming:197ms
,I/HwCust  ( 7426): Constructor found for class com.android.emailcommon.provider.HwCustPolicyImpl
,I/HwEmailTag( 7426): EmailContent->init->consuming:17ms->;-prefixstartupperformance-
,I/HwEmailTag( 7426): Exchange->onCreate
,I/HwSystemManager( 4085): HoldService:uid:10044 pid:6738 died
I/HwSystemManager( 4085): HoldService:oldVersionKey:10044,6738
I/HwSystemManager( 4085): BgPowerManagerService:onProcessDied uid = 10044
E/HsmCoreServiceImpl( 2937): onTransact in code is: 102
I/MediaProcessHandler( 2937): processOp opType: 1, uid: 10044, pid: 6738
W/MediaProcessHandler( 2937): remove target not exist, maybe the UI process: uid: 10044, pid: 6738
,I/PG Utils( 7426): acquire_providerpkg:[com.android.email] pid:[]  maybe timeout , send to PG
,I/PG Utils( 7249): acquire_providerpkg:[com.android.providers.calendar] pid:[]  maybe timeout , send to PG
,I/HwEmailTag( 7177): EmailProvider->query->1448458063605;end;;consuming:2ms;
,E/HsmCoreServiceImpl( 2937): onTransact in code is: 102
I/HwSystemManager( 4085): HoldService:uid:10001 pid:6558 died
I/MediaProcessHandler( 2937): processOp opType: 1, uid: 10001, pid: 6558
I/HwSystemManager( 4085): HoldService:oldVersionKey:10001,6558
W/MediaProcessHandler( 2937): remove target not exist, maybe the UI process: uid: 10001, pid: 6558
,I/HwSystemManager( 4085): BgPowerManagerService:onProcessDied uid = 10001
,W/StubController( 7249): calendar access!
,I/HwEmailTag( 7426): PingSyncSynchronizer->PSS->->PSS has no active accounts; stopping service.
,I/PG Utils( 7249): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/StubController( 7249): calendar access!
,I/PG Utils( 7249): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 7249): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 7249): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/ContextImpl( 7447): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/PG Utils( 7249): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/ContextImpl( 7447): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/PG Utils( 7249): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/ContextImpl( 7447): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/PG Utils( 7249): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/GAv4    ( 7447): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7447):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7447):   adb logcat -s GAv4
,W/ContextImpl( 7447): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7447): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7447): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7447): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/PG Utils( 7447): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 7447): Can not find class: Ljava/util/ConcurrentNavigableMap;
,I/HwEmailTag( 7177): EmailProvider->handleNetworkChanged->network is good, start new EmailConnectivityTask
,I/HwEmailTag( 7177): EmailProvider->triggerAllPeriodSync
I/HwEmailTag( 7177): EmailProvider->triggerPeroidSync->accountId:-1
,I/HwEmailTag( 7177): EmailConnectivityTask->syncOutbox
,I/HwEmailTag( 7177): EmailProvider->query->1448458063911;end;;consuming:2ms;
,I/WebViewFactory( 7447): Loading com.android.webview version 37 (eng.jenkinswh-arm64) (code 199992)
,I/PG Utils( 7249): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/LibraryLoader( 7447): Loading: webviewchromium
,I/LibraryLoader( 7447): Time to load native libraries: 4 ms (timestamps 6597-6601)
,I/LibraryLoader( 7447): Expected native library version number "",actual native library version number ""
,I/LibraryLoader( 7447): Expected native library version number "",actual native library version number ""
,I/chromium( 7447): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7447): Initializing chromium process, renderers=0
,W/art     ( 7447): Attempt to remove local handle scope entry from IRT, ignoring
,W/AudioManagerAndroid( 7447): Requires BLUETOOTH permission
,W/chromium( 7447): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7447): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=46092 len=2953
,I/chromium( 7447): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:45 off:228796 len:643667
,E/HsmCoreServiceImpl( 2937): onTransact in code is: 102
I/HwSystemManager( 4085): HoldService:uid:10026 pid:6191 died
I/HwSystemManager( 4085): HoldService:oldVersionKey:10026,6191
I/HwSystemManager( 4085): BgPowerManagerService:onProcessDied uid = 10026
I/MediaProcessHandler( 2937): processOp opType: 1, uid: 10026, pid: 6191
W/MediaProcessHandler( 2937): remove target not exist, maybe the UI process: uid: 10026, pid: 6191
,I/NSApplication( 7447): Starting up...
,I/HwSystemManager( 4085): HoldService:uid:10007 pid:6807 died
I/HwSystemManager( 4085): HoldService:oldVersionKey:10007,6807
I/HwSystemManager( 4085): BgPowerManagerService:onProcessDied uid = 10007
E/HsmCoreServiceImpl( 2937): onTransact in code is: 102
I/MediaProcessHandler( 2937): processOp opType: 1, uid: 10007, pid: 6807
W/MediaProcessHandler( 2937): remove target not exist, maybe the UI process: uid: 10007, pid: 6807
,I/System  ( 5975): core_booster, getBoosterConfig = false
,I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/iu.SyncManager( 5839): SYNC; picasa accounts
,I/iu.Environment( 5839): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 5839): num queued entries: 0
,I/iu.UploadsManager( 5839): num updated entries: 0
I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/iu.SyncManager( 5839): NEXT; no task
,I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/Babel   ( 5975): connection state changed from UNKNOWN to CONNECTED
I/System  ( 3984): core_booster, getBoosterConfig = false
I/System  ( 3984): core_booster, getBoosterConfig = false
,I/HwEmailTag( 7177): PeakSchedulingService->onHandleIntent : intent.getAction() -> com.huawei.email.service.PEAK_TIME_SET
,I/HwEmailTag( 7177): EmailProvider->query->1448458064558;end;;consuming:2ms;
,I/GCM     ( 3984): GCM config loaded
,I/HwSystemManager( 4085): HoldService:uid:10025 pid:6147 died
I/HwSystemManager( 4085): HoldService:oldVersionKey:10025,6147
E/HsmCoreServiceImpl( 2937): onTransact in code is: 102
I/HwSystemManager( 4085): BgPowerManagerService:onProcessDied uid = 10025
I/MediaProcessHandler( 2937): processOp opType: 1, uid: 10025, pid: 6147
W/MediaProcessHandler( 2937): remove target not exist, maybe the UI process: uid: 10025, pid: 6147
,W/StubController( 7558): calendar access!
,I/PG Utils( 7558): acquire_providerpkg:[com.android.providers.calendar] pid:[]  maybe timeout , send to PG
,I/ActivityManager( 2937): filter receiver for action = com.google.android.gcm.CONNECTED
,W/StubController( 7558): calendar access!
,I/PG Utils( 7558): acquire_providerpkg:[com.android.providers.calendar] pid:[]  maybe timeout , send to PG
,I/HwSystemManager( 4085): HoldService:uid:10042 pid:7034 died
E/HsmCoreServiceImpl( 2937): onTransact in code is: 102
I/HwSystemManager( 4085): HoldService:oldVersionKey:10042,7034
I/HwSystemManager( 4085): BgPowerManagerService:onProcessDied uid = 10042
I/MediaProcessHandler( 2937): processOp opType: 1, uid: 10042, pid: 7034
W/MediaProcessHandler( 2937): remove target not exist, maybe the UI process: uid: 10042, pid: 7034
,W/StubController( 7558): calendar access!
,I/HwSystemManager( 4085): HoldService:uid:1000 pid:6988 died
I/HwSystemManager( 4085): HoldService:oldVersionKey:1000,6988
I/HwSystemManager( 4085): BgPowerManagerService:onProcessDied uid = 1000
E/HsmCoreServiceImpl( 2937): onTransact in code is: 102
W/MediaProcessHandler( 2937): processOp uid 1000 is not concerned!
,I/Process ( 7585): Sending signal. PID: 7585 SIG: 9
,I/ActivityManager( 2937): filter receiver for action = com.android.calendar.APPWIDGET_UPDATE
,I/DeskClockApplication( 7609): onCreate
,I/AlarmInitReceiver( 7609): AlarmInitReceiver->OnReceive->AsyncHandler : needSetSnoozeAlert = false alarmnow = false
,I/HwSystemManager( 4085): HoldService:uid:1001 pid:7585 died
I/HwSystemManager( 4085): BgPowerManagerService:onProcessDied uid = 1001
I/HwSystemManager( 4085): HoldService:oldVersionKey:1001,7585
E/HsmCoreServiceImpl( 2937): onTransact in code is: 102
W/MediaProcessHandler( 2937): processOp uid 1001 is not concerned!
,I/art     ( 2937): Explicit concurrent mark sweep GC freed 20660(1118KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 28MB/42MB, paused 2.166ms total 202.296ms
,W/StubController( 7558): calendar access!
,I/HwSystemManager( 4085): HoldService:uid:10057 pid:7105 died
I/HwSystemManager( 4085): BgPowerManagerService:onProcessDied uid = 10057
E/HsmCoreServiceImpl( 2937): onTransact in code is: 102
I/HwSystemManager( 4085): HoldService:oldVersionKey:10057,7105
I/MediaProcessHandler( 2937): processOp opType: 1, uid: 10057, pid: 7105
W/MediaProcessHandler( 2937): remove target not exist, maybe the UI process: uid: 10057, pid: 7105
,I/PG Utils( 7558): acquire_providerpkg:[com.android.providers.calendar] pid:[]  maybe timeout , send to PG
,E/HwOUC   ( 7633): [main-1]load system config caught FileNotFoundException(/HwOucConfig.java:1298)
,I/art     ( 7633): Can not find class: Lcom/huawei/pad/Product;
,E/HwOUC   ( 7633): [main-1]method invoke failed(/HwOucUtility.java:471)
I/HwOUC   ( 7633): [main-1]isTablet() = false(/HwOucUtility.java:474)
,I/HwOUC   ( 7633): [main-1]baseVersionOfNewVersion is ALE-L21C432B132;isInstallingStatus is false(/HwOucUtility.java:2228)
,I/HwOUC   ( 7633): [main-1]HwOucApplication--onCreate, cacheCpuInfo is 8_1.2GHz(hwouc/HwOucApplication.java:48)
,I/HwOUC   ( 7633): [main-1]Intent.ACTION_TIME_CHANGED nextInstallRemindTime:Thu Jan 01 00:59:59 GMT+01:00 1970(hwouc/DownloadReceiver.java:370)
,I/HwOUC   ( 7633): [main-1]Intent.ACTION_TIME_CHANGED alarmRegistTime:Thu Jan 01 00:59:59 GMT+01:00 1970(hwouc/DownloadReceiver.java:372)
I/HwOUC   ( 7633): [main-1]Intent.ACTION_TIME_CHANGED nextCheckNewVersionTime:Thu Nov 26 13:46:32 GMT+01:00 2015(hwouc/DownloadReceiver.java:400)
,I/HwOUC   ( 7633): [main-1]Intent.ACTION_TIME_CHANGED startTime:Wed Nov 25 13:46:32 GMT+01:00 2015(hwouc/DownloadReceiver.java:402)
I/HwOUC   ( 7633): [main-1]Intent.ACTION_TIME_CHANGED currentTime:Wed Nov 25 14:27:45 GMT+01:00 2015(hwouc/DownloadReceiver.java:404)
,I/HwSystemManager( 6614): PreventReceiver:RreventReceiver receive the action :android.intent.action.TIME_SET
,I/HwSystemManager( 6614): PreventReceiver:TriggerAgainTask-doInBackground: time switch = false, time list size = 0
,I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/CheckinService( 5839): Checkin interval check for package: unspecified last checkin: 1448013111636 min interval config: 0 actual interval: 444954226
,I/HwEmailTag( 7177): HwUtils->triggerPeriodSync->
,I/HwEmailTag( 7177): EmailProvider->call->triggerPeroidSync,accountId:-1
I/HwEmailTag( 7177): EmailProvider->triggerPeroidSync->accountId:-1
,I/HwSystemManager( 4085): HoldService:uid:10084 pid:7215 died
I/HwSystemManager( 4085): HoldService:oldVersionKey:10084,7215
I/HwSystemManager( 4085): BgPowerManagerService:onProcessDied uid = 10084
E/HsmCoreServiceImpl( 2937): onTransact in code is: 102
I/MediaProcessHandler( 2937): processOp opType: 1, uid: 10084, pid: 7215
W/MediaProcessHandler( 2937): remove target not exist, maybe the UI process: uid: 10084, pid: 7215
I/HwEmailTag( 7177): BaseWidgetProvider->WidgetProvider->onReceive->action is com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,W/StubController( 7558): calendar access!
,W/StubController( 7558): calendar access!
,I/CalendarSimpleUiPRovider( 7558): onReceive[intent]Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.simpleui.CalendarSimpleUiPRovider }
I/CalendarSimpleUiPRovider( 7558): onConfigurationChanged
,I/CalendarSimpleUiPRovider( 7558): initParams20151125T142746Europe/Warsaw(3,328,3600,0,1448458066)
,I/PG Utils( 7558): acquire_providerpkg:[com.android.providers.calendar] pid:[]  maybe timeout , send to PG
I/PG Utils( 7558): acquire_providerpkg:[com.android.providers.calendar] pid:[]  maybe timeout , send to PG
,I/ActivityManager( 2937): filter receiver for action = com.google.android.gms.gcm.ACTION_CHECK_QUEUE
,W/StubController( 7558): calendar access!
,W/StubController( 7558): calendar access!
,I/CalendarSimpleUiPRovider( 7558): loadEvent end update UI0
,I/VacuumService( 3984): Vacuum at: now=1448458066198 tag=VacuumService
,I/ActivityManager( 2937): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/PG Utils( 7669): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/System.err( 2937): java.lang.SecurityException: WifiService: Neither user 10025 nor current process has android.permission.CHANGE_WIFI_STATE.
W/System.err( 2937): 	at android.app.ContextImpl.enforce(ContextImpl.java:1962)
W/System.err( 2937): 	at android.app.ContextImpl.enforceCallingOrSelfPermission(ContextImpl.java:1991)
W/System.err( 2937): 	at com.android.server.wifi.WifiServiceImpl.enforceChangePermission(WifiServiceImpl.java:784)
W/System.err( 2937): 	at com.android.server.wifi.WifiServiceImpl.getWifiServiceMessenger(WifiServiceImpl.java:1903)
W/System.err( 2937): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:495)
W/System.err( 2937): 	at com.android.server.wifi.HwWifiService.onTransact(HwWifiService.java:61)
W/System.err( 2937): 	at android.os.Binder.execTransact(Binder.java:446)
E/WifiManager( 7669): WifiServiceMessenger == null
,W/Settings( 7669): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7669): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PG Utils( 7669): acquire_providerpkg:[com.android.providers.downloads] pid:[]  maybe timeout , send to PG
,I/PG Utils( 7669): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6900): 
,I/PG Utils( 7669): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 7669): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 7669): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 7669): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 7669): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/System  ( 7669): core_booster, getBoosterConfig = false
,I/System  ( 7669): core_booster, getBoosterConfig = false
,I/HwSystemManager( 4085): BgPowerManagerService:onProcessDied uid = 10004
I/HwSystemManager( 4085): HoldService:uid:10004 pid:6392 died
E/HsmCoreServiceImpl( 2937): onTransact in code is: 102
I/HwSystemManager( 4085): HoldService:oldVersionKey:10004,6392
I/MediaProcessHandler( 2937): processOp opType: 1, uid: 10004, pid: 6392
W/MediaProcessHandler( 2937): remove target not exist, maybe the UI process: uid: 10004, pid: 6392
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 0
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=17 dispatchEvent: HEART-BEAT-ACK: 0
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/AlarmInitReceiver( 7609): handleMessage : AlarmInitReceiver, will exit app. Config.exit_count: 0
,I/art     ( 7609): System.exit called, status: 0
I/AndroidRuntime( 7609): VM exiting with result code 0, cleanup skipped.
,I/HwSystemManager( 4085): HoldService:uid:10045 pid:7609 died
I/HwSystemManager( 4085): HoldService:oldVersionKey:10045,7609
E/HsmCoreServiceImpl( 2937): onTransact in code is: 102
I/MediaProcessHandler( 2937): processOp opType: 1, uid: 10045, pid: 7609
W/MediaProcessHandler( 2937): remove target not exist, maybe the UI process: uid: 10045, pid: 7609
,I/HwSystemManager( 4085): BgPowerManagerService:onProcessDied uid = 10045
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6900): 
,I/HwSystemManager( 4085): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4085): BgPowerManagerService: mTimes = 33813 firstTime = 92756 firstmBatteryCapacity =2203
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6900): 
,E/Thermal-daemon( 2331): [charger_ic] temp_new :31  temp_old :32
,E/Thermal-daemon( 2331): [ap] temp_new :31  temp_old :32
,I/art     ( 7347): System.exit called, status: 0
I/AndroidRuntime( 7347): VM exiting with result code 0, cleanup skipped.
,I/HwSystemManager( 4085): HoldService:uid:10060 pid:7347 died
I/HwSystemManager( 4085): BgPowerManagerService:onProcessDied uid = 10060
I/HwSystemManager( 4085): HoldService:oldVersionKey:10060,7347
E/HsmCoreServiceImpl( 2937): onTransact in code is: 102
I/MediaProcessHandler( 2937): processOp opType: 1, uid: 10060, pid: 7347
W/MediaProcessHandler( 2937): remove target not exist, maybe the UI process: uid: 10060, pid: 7347
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6900): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 1
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=18 dispatchEvent: HEART-BEAT-ACK: 1
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6900): 
,I/HwLauncher( 3936): Model  onReceive intent=Intent { act=android.intent.action.TIME_TICK flg=0x50000014 (has extras) }
,I/TimeManager( 3472): receiver action = android.intent.action.TIME_TICK
I/TimeManager( 3472): hand message 1
I/TimeManager( 3472): notify time change. size = 2
,I/TimeLayout( 3472): time = 14:28
,I/TimeLayout( 3472): updateDate date = 11/25/2015
,I/TimeLayout( 3472): weekDay = Wednesday
,W/SyncManager( 2937): SyncManager manageSyncAlarmLocked SET_WAKE_ALARM
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6900): 
,E/WifiStateMachine( 2937):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 2937):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 2937):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 2937):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 2937):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 2937):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,I/HwSystemManager( 4085): InputMethodStringPredicate:InputMethodStringPredicate :: inputMethods = [com.nuance.swype.emui, com.nuance.swype.input.HuaweiIME, com.android.inputmethod.latin]
,I/HwSystemManager( 4085): LauncherPredicate:get default launcher is null, set hwlauncher
,I/HwSystemManager( 4085): SmartMemoryCleanService:Smcs provider called method:execSQLS
,W/HwSystemManager( 4085): HsmContentProvider:call: Unknown call method = execSQLS
,I/HwSystemManager( 4085): SmartMemoryCleanService:Smcs provider called method:execSQLS
,W/HwSystemManager( 4085): HsmContentProvider:call: Unknown call method = execSQLS
,I/HwSystemManager( 4085): SmartMemoryCleanService:Smcs provider called method:execSQLS
,W/HwSystemManager( 4085): HsmContentProvider:call: Unknown call method = execSQLS
,I/HwSystemManager( 4085): SmartMemoryCleanService:SMCSDataManager.checkAvailMemory.: availMem 1151385600 [332800000,437657600,542515200]
I/HwSystemManager( 4085): SmartMemoryCleanService:SMCSControl.handleSMCSTimerOut call startCPUMeMMonitor start
,I/HwSystemManager( 4085): SmartMemoryCleanService:SMCSControl.handleSMCSTimerOut call startCPUMeMMonitor end
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6900): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 2
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=19 dispatchEvent: HEART-BEAT-ACK: 2
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 4085): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4085): BgPowerManagerService: mTimes = 60156 firstTime = 92756 firstmBatteryCapacity =2203
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6900): 
,I/ClearcutLoggerApiImpl( 3793): disconnect managed GoogleApiClient
,E/Lss     ( 7756): Unable to open cell info file /data/gnss/pgps/cell_info.dat
E/Lss     ( 7756): No reference location.
W/Lss     ( 7756): Cannot calculate visible satellites. Returning all odd satellite ids
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6900): 
,E/Thermal-daemon( 2331): [ap] temp_new :30  temp_old :31
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6900): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 3
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=20 dispatchEvent: HEART-BEAT-ACK: 3
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,E/Thermal-daemon( 2331): [ap] temp_new :31  temp_old :30
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6900): 
,E/Thermal-daemon( 2331): [ap] temp_new :30  temp_old :31
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6900): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 4
E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=21 dispatchEvent: HEART-BEAT-ACK: 4
E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6900): 
,E/Thermal-daemon( 2331): [charger_ic] temp_new :30  temp_old :31
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6900): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 5
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=22 dispatchEvent: HEART-BEAT-ACK: 5
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6900): 
,I/ClearcutLoggerApiImpl( 3984): disconnect managed GoogleApiClient
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6900): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 6
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=23 dispatchEvent: HEART-BEAT-ACK: 6
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 4085): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4085): BgPowerManagerService: mTimes = 120308 firstTime = 92756 firstmBatteryCapacity =2203
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6900): 
,I/ActivityManager( 2937): filter receiver for action = android.bluetooth.intent.DISCOVERABLE_TIMEOUT
,I/HwLauncher( 3936): Model  onReceive intent=Intent { act=android.intent.action.TIME_TICK flg=0x50000014 (has extras) }
,I/TimeManager( 3472): receiver action = android.intent.action.TIME_TICK
,I/TimeManager( 3472): hand message 1
I/TimeManager( 3472): notify time change. size = 2
,I/TimeLayout( 3472): time = 14:29
,I/TimeLayout( 3472): updateDate date = 11/25/2015
,I/TimeLayout( 3472): weekDay = Wednesday
I/bluedroid( 6965): bt interface: [set_adapter_property]
I/bluedroid( 6965): bt interface: [set_adapter_property]
W/bt-btif ( 6965): HAL bt_hal_cbacks->adapter_properties_cb
W/bt-btm  ( 6965): BTM_SetDiscoverability
I/BluetoothAdapterProperties( 6965): adapterPropertyChangedCallback with type:9 len:4
,W/bt-btm  ( 6965): HAL bt_hal_cbacks->adapter_properties_cb
W/bt-btif ( 6965): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 6965): adapterPropertyChangedCallback with type:7 len:4
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6900): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 7
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=24 dispatchEvent: HEART-BEAT-ACK: 7
E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6900): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 8
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=25 dispatchEvent: HEART-BEAT-ACK: 8
E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6900): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 9
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=26 dispatchEvent: HEART-BEAT-ACK: 9
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6900): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 10
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=27 dispatchEvent: HEART-BEAT-ACK: 10
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6900): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 11
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=28 dispatchEvent: HEART-BEAT-ACK: 11
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/jxcore-log( 6900): DBG, CoordinatorConnector connect called
I/jxcore-log( 6900): 
I/jxcore-log( 6900): Coordinator is now connected to the server!
I/jxcore-log( 6900): 
,I/chromium( 6900): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 c2:ff:d4:d3:aa:48
E/WifiMonitor( 2937): handleEvent 13  CTRL-EVENT-BSS-REMOVED 1 c2:ff:d4:d3:aa:48
E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11
E/WifiMonitor( 2937): handleEvent 13  CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11
E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 06:7c:34:12:7f:81
E/WifiMonitor( 2937): handleEvent 13  CTRL-EVENT-BSS-REMOVED 3 06:7c:34:12:7f:81
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 12
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=32 dispatchEvent: HEART-BEAT-ACK: 12
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 4085): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4085): BgPowerManagerService: mTimes = 210556 firstTime = 92756 firstmBatteryCapacity =2203
,I/HwSystemManager( 4085): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4085): BgPowerManagerService: mTimes = 213817 firstTime = 92756 firstmBatteryCapacity =2203
,I/art     ( 2937): Can not find class: Lcom/android/server/power/PowerManagerService$5$1;
,I/System  ( 2937): core_booster, getBoosterConfig = false
,I/System  ( 2937): core_booster, getBoosterConfig = false
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 13
E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=33 dispatchEvent: HEART-BEAT-ACK: 13
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 14
E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=34 dispatchEvent: HEART-BEAT-ACK: 14
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/art     ( 2937): Can not find class: Lcom/android/server/am/ActivityManagerService$31$1;
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 15
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=35 dispatchEvent: HEART-BEAT-ACK: 15
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/art     ( 2937): Can not find class: Lcom/android/server/am/ActivityManagerService$33$1;
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 16
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=36 dispatchEvent: HEART-BEAT-ACK: 16
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 17
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=37 dispatchEvent: HEART-BEAT-ACK: 17
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 18
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=38 dispatchEvent: HEART-BEAT-ACK: 18
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 19
E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=39 dispatchEvent: HEART-BEAT-ACK: 19
E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/jxcore-log( 6900): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): DBG, CoordinatorConnector command called
I/jxcore-log( 6900): 
I/jxcore-log( 6900): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":20,"addressList":[{"address":"34:FC:EF:11:AE:67","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"34:FC:EF:9D:93:0B","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"50:2E:6C:AC:21:50","tryCount":0},{"address":"B4:CE:F6:AB:A4
,I/jxcore-log( 6900): Start now : testSendData.js
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 20
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): check server
I/jxcore-log( 6900): 
I/jxcore-log( 6900): serverPort is 43439
I/jxcore-log( 6900): 
,I/        ( 6900): Stoping All
I/        ( 6900): Stopping services
I/        ( 6900): Stop Bluetooth
,I/        ( 6900): Start-My BT: 58:2A:F7:ED:96:BE
,I/        ( 6900):  mInstanceString : {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT9762","ra":"58:2A:F7:ED:96:BE"}
,I/        ( 6900): All stuff available and enabled
I/        ( 6900): Stoping All
I/        ( 6900): Stopping services
I/        ( 6900): Stop Bluetooth
I/        ( 6900): Starting All
I/        ( 6900): Stopping services
I/        ( 6900): Starting services address: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT9762","ra":"58:2A:F7:ED:96:BE"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@2e0538ae
,I/        ( 6900): Stopping services
,I/        ( 6900): Starting services address: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT9762","ra":"58:2A:F7:ED:96:BE"}
,I/        ( 6900): Add local service :{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT9762","ra":"58:2A:F7:ED:96:BE"}, length : 80
,I/        ( 6900): peerDiscoveryTimer timeout value:6883
,I/art     ( 2937): Can not find class: Lcom/android/server/wifi/p2p/WifiP2pServiceImpl$ClientInfo;
,I/        ( 6900): Stop Bluetooth
I/        ( 6900): StartBluetooth listener
,I/        ( 6900): StartBluetooth listener
,W/BluetoothAdapter( 6900): getBluetoothService() called with no BluetoothManagerCallback
,I/BTListenerThread( 6900): starting to listen
,I/jxcore-log( 6900): StartBroadcasting started ok
I/jxcore-log( 6900): 
I/BTListenerThread( 6900): waiting to accept incoming Connection
I/jxcore-log( 6900): do fake peer & start
I/jxcore-log( 6900): 
I/jxcore-log( 6900): Connect to fake peer: 7C:F9:0E:37:96:AB
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:32:36.525Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:36.525Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:32:36.525Z SendDataConnector.js: do connect now
I/jxcore-log( 6900): 
,I/        ( 6900): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/BTConnectToThread( 6900): Starting to connect,
,W/BluetoothAdapter( 6900): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 6900): Connecting to null, at 7C:F9:0E:37:96:AB
I/jxcore-log( 6900): 2015-11-25T13:32:36.533Z SendDataTCPServer.js: TCP/IP server is bound to port: 43439
I/jxcore-log( 6900): 
,I/WB      ( 6900): We already were running, thus doing nothing
I/        ( 6900): Adding local service failed, error code 0
I/        ( 6900): Cleared service requests
I/        ( 6900): Stopping peer discovery failed, error code 0
I/        ( 6900): Starting peer discovery failed, error code 0
,I/chromium( 6900): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/wifi_log/wifi_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btm  ( 6965): sec_bd_name = 
W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b082ac rs_disc_pending=0
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,E/bt-l2cap( 6965): l2cu_adjust_out_mps bad packet size: 0  will use MPS: 0
,W/bt-btif ( 6965): HAL bt_hal_cbacks->remote_device_properties_cb
,W/bt-btif ( 6965): HAL bt_hal_cbacks->bond_state_changed_cb
,I/BluetoothBondStateMachine( 6965): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 6965): check_cod: remote_cod = 0x5a020c
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
I/ActivityManager( 2937): filter receiver for action = android.bluetooth.device.action.BOND_STATE_CHANGED
,I/BluetoothBondStateMachine( 6965): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 6965): Entering PendingCommandState State
,W/BluetoothEventManager( 3669): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3669): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,W/bt-btif ( 6965): HAL bt_hal_cbacks->bond_state_changed_cb
,I/BluetoothBondStateMachine( 6965): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,I/ActivityManager( 2937): filter receiver for action = android.bluetooth.device.action.BOND_STATE_CHANGED
,I/BluetoothBondStateMachine( 6965): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
W/BluetoothEventManager( 3669): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3669): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/BluetoothBondStateMachine( 6965): StableState(): Entering Off State
,E/bt-l2cap( 6965): l2cu_adjust_out_mps bad packet size: 0  will use MPS: 0
,W/bt-btif ( 6965): new conn_srvc id:26, app_id:255
,I/BTListenerThread( 6900): we got incoming connection
,I/BTHandshakeSocketThread( 6900): Creating BTHandshakeSocketThread
I/BTListenerThread( 6900): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 6900): BTHandshakeSocketThread started
,I/BTListenerThread( 6900): got MESSAGE_READ 77 bytes.
,I/BTListenerThread( 6900): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 6900): MESSAGE_WRITE 80 bytes.
,I/HS      ( 6900): Incoming connection Hand Shake finished for : LGE-LG-H815_PT1965
,I/BTHandshakeSocketThread( 6900): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 6900): Starting the connected thread incoming : true, LGE-LG-H815_PT1965
,I/BtToSocketBase( 6900): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 6900): Creating BTConnectedThread
I/BtConnectorHelper( 6900): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 6900): --DoOneRunRound started
,I/System  ( 6900): core_booster, getBoosterConfig = false
,I/BtToRequestSocket( 6900): LocalHost address: localhost/127.0.0.1, port: 43439
,I/BtToRequestSocket( 6900): --DoOneRunRound ended,
,I/jxcore-log( 6900): 2015-11-25T13:32:46.707Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6900): ,
,I/PG Utils( 7669): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/System  ( 7669): core_booster, getBoosterConfig = false
,I/System  ( 7669): core_booster, getBoosterConfig = false
,I/jxcore-log( 6900): 2015-11-25T13:32:47.292Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:47.317Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:47.330Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:47.373Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:47.394Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:47.445Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:47.482Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:47.521Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:47.576Z SendDataTCPServer.js: TCP/IP server has received 18092 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:47.610Z SendDataTCPServer.js: TCP/IP server has received 20072 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:47.613Z SendDataTCPServer.js: TCP/IP server has received 22052 bytes of data
,I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:47.645Z SendDataTCPServer.js: TCP/IP server has received 24032 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:47.682Z SendDataTCPServer.js: TCP/IP server has received 27992 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:47.689Z SendDataTCPServer.js: TCP/IP server has received 29972 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:47.709Z SendDataTCPServer.js: TCP/IP server has received 31952 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:47.714Z SendDataTCPServer.js: TCP/IP server has received 33932 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:47.751Z SendDataTCPServer.js: TCP/IP server has received 39872 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:47.786Z SendDataTCPServer.js: TCP/IP server has received 41852 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:47.790Z SendDataTCPServer.js: TCP/IP server has received 43832 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:47.841Z SendDataTCPServer.js: TCP/IP server has received 45812 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:47.860Z SendDataTCPServer.js: TCP/IP server has received 47792 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:47.864Z SendDataTCPServer.js: TCP/IP server has received 49772 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:47.893Z SendDataTCPServer.js: TCP/IP server has received 51752 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:47.904Z SendDataTCPServer.js: TCP/IP server has received 53732 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:47.942Z SendDataTCPServer.js: TCP/IP server has received 55712 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:47.983Z SendDataTCPServer.js: TCP/IP server has received 61652 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:47.987Z SendDataTCPServer.js: TCP/IP server has received 63632 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:48.020Z SendDataTCPServer.js: TCP/IP server has received 69572 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:48.072Z SendDataTCPServer.js: TCP/IP server has received 73532 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:48.091Z SendDataTCPServer.js: TCP/IP server has received 75512 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:48.133Z SendDataTCPServer.js: TCP/IP server has received 77492 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:48.173Z SendDataTCPServer.js: TCP/IP server has received 81452 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:48.179Z SendDataTCPServer.js: TCP/IP server has received 83432 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:48.212Z SendDataTCPServer.js: TCP/IP server has received 85412 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:48.257Z SendDataTCPServer.js: TCP/IP server has received 87392 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:48.298Z SendDataTCPServer.js: TCP/IP server has received 89372 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:48.339Z SendDataTCPServer.js: TCP/IP server has received 91352 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:48.350Z SendDataTCPServer.js: TCP/IP server has received 93332 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:48.397Z SendDataTCPServer.js: TCP/IP server has received 95312 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:32:48.440Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 6900): 
,W/bt-btif ( 6965): invalid rfc slot id: 4
,I/BtToSocketBase( 6900): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 6900): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 6900): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT1965
I/BtToSocketBase( 6900): Stop ReceivingThread
I/BtToSocketBase( 6900): Stop SendingThread
I/BtToSocketBase( 6900): Close local in
I/BtToSocketBase( 6900): Close LocalOutputStream
,I/BtToSocketBase( 6900): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 6900): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 6900): Close localHostSocket
I/BtConnectorHelper( 6900): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT1965
I/BtToSocketBase( 6900): Close bt in
I/BtToSocketBase( 6900): Close bt in
I/BtToSocketBase( 6900): Close bt out
I/BtToSocketBase( 6900): Close bt socket
I/BtToSocketBase( 6900): Close bt out
I/BtToSocketBase( 6900): Close bt socket
,I/jxcore-log( 6900): 2015-11-25T13:32:48.512Z SendDataTCPServer.js: TCP/IP server is ended,
I/jxcore-log( 6900): 
,W/bt-rfcomm( 6965): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
,W/bt-rfcomm( 6965): RFCOMM_DisconnectInd LCID:0x42
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 20
E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=40 dispatchEvent: HEART-BEAT-ACK: 20
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,I/ActivityManager( 2937): filter receiver for action = android.bluetooth.device.action.ACL_DISCONNECTED
,I/BTConnectionReceiver( 8017): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=G4-1, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/PG Utils( 8017): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/BluetoothClassifier( 8017): Bluetooth Device Name: G4-1
,I/HwSystemManager( 4085): HoldService:uid:10064 pid:7374 died
I/HwSystemManager( 4085): HoldService:oldVersionKey:10064,7374
E/HsmCoreServiceImpl( 2937): onTransact in code is: 102
I/MediaProcessHandler( 2937): processOp opType: 1, uid: 10064, pid: 7374
W/MediaProcessHandler( 2937): remove target not exist, maybe the UI process: uid: 10064, pid: 7374
I/HwSystemManager( 4085): BgPowerManagerService:onProcessDied uid = 10064
,I/PG Utils( 8017): acquire_providerpkg:[com.google.android.partnersetup] pid:[]  maybe timeout , send to PG
,I/PG Utils( 8048): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 8048): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 21
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=41 dispatchEvent: HEART-BEAT-ACK: 21
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,E/bt-btif ( 6965): DISCOVERY_COMP_EVT slot id:5, failed to find channle,                                       status:1, scn:0
E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=3,ble_in_encryption=0
E/bt-btm  ( 6965): invalid rfc slot id: 5
W/bt-btif ( 6965): invalid rfc slot id: 5
,I/BTConnectToThread( 6900): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 6900): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 6900): 2015-11-25T13:33:06.224Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:06.224Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:06.226Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:11.228Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:11.230Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:16.238Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:33:16.240Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:16.241Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:33:16.241Z SendDataConnector.js: do connect now
I/jxcore-log( 6900): 
,I/        ( 6900): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/BTConnectToThread( 6900): Starting to connect
W/BluetoothAdapter( 6900): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 6900): Connecting to null, at 7C:F9:0E:37:96:AB
,W/bt-sdp  ( 6965): SDP - Rcvd conn cnf with error: 0xc  CID 0x43
E/bt-btif ( 6965): DISCOVERY_COMP_EVT slot id:7, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 6965): invalid rfc slot id: 7
I/BTConnectToThread( 6900): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 6900): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 6900): 2015-11-25T13:33:16.268Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:16.269Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:33:16.270Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6900): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 22
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=42 dispatchEvent: HEART-BEAT-ACK: 22
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/jxcore-log( 6900): 2015-11-25T13:33:21.270Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:33:21.271Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 6900): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btm  ( 6965): sec_bd_name = 
W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,E/bt-l2cap( 6965): l2cu_adjust_out_mps bad packet size: 0  will use MPS: 0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 6965): HAL bt_hal_cbacks->remote_device_properties_cb
,W/bt-btif ( 6965): HAL bt_hal_cbacks->bond_state_changed_cb
,I/BluetoothBondStateMachine( 6965): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 1
E/bt-btif ( 6965): check_cod: remote_cod = 0x5a020c
,I/ActivityManager( 2937): filter receiver for action = android.bluetooth.device.action.BOND_STATE_CHANGED
,I/BluetoothBondStateMachine( 6965): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 6965): Entering PendingCommandState State
,W/BluetoothEventManager( 3669): CachedBluetoothDevice for device 34:FC:EF:11:B1:66 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3669): Got bonding state changed for 34:FC:EF:11:B1:66, but we have no record of that device.
,I/jxcore-log( 6900): 2015-11-25T13:33:26.278Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:33:26.278Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:33:26.279Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:33:26.280Z SendDataConnector.js: do connect now
I/jxcore-log( 6900): 
,I/        ( 6900): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/BTConnectToThread( 6900): Starting to connect
W/BluetoothAdapter( 6900): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 6900): Connecting to null, at 7C:F9:0E:37:96:AB
,W/bt-btif ( 6965): HAL bt_hal_cbacks->bond_state_changed_cb
,I/BluetoothBondStateMachine( 6965): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 0
,I/ActivityManager( 2937): filter receiver for action = android.bluetooth.device.action.BOND_STATE_CHANGED
I/BluetoothBondStateMachine( 6965): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 11 NewState: 10
W/BluetoothEventManager( 3669): CachedBluetoothDevice for device 34:FC:EF:11:B1:66 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3669): Got bonding state changed for 34:FC:EF:11:B1:66, but we have no record of that device.,
,I/BluetoothBondStateMachine( 6965): StableState(): Entering Off State
,E/bt-l2cap( 6965): l2cu_adjust_out_mps bad packet size: 0  will use MPS: 0
,E/bt-l2cap( 6965): l2cu_adjust_out_mps bad packet size: 0  will use MPS: 0
,W/bt-btif ( 6965): new conn_srvc id:26, app_id:255
,I/BTListenerThread( 6900): we got incoming connection
I/BTHandshakeSocketThread( 6900): Creating BTHandshakeSocketThread
I/BTListenerThread( 6900): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 6900): BTHandshakeSocketThread started
,E/bt-l2cap( 6965): l2cu_adjust_out_mps bad packet size: 0  will use MPS: 0
,I/BTListenerThread( 6900): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 6900): Got JSON from encryption:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT8083"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 6900): MESSAGE_WRITE 80 bytes.
I/HS      ( 6900): Incoming connection Hand Shake finished for : LGE-Nexus 5_PT8083
I/BTHandshakeSocketThread( 6900): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 6900): Starting the connected thread incoming : true, LGE-Nexus 5_PT8083
I/BtToSocketBase( 6900): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 6900): Creating BTConnectedThread
I/BtConnectorHelper( 6900): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 6900): --DoOneRunRound started
,I/System  ( 6900): core_booster, getBoosterConfig = false
,I/BtToRequestSocket( 6900): LocalHost address: localhost/127.0.0.1, port: 43439
,I/BtToRequestSocket( 6900): --DoOneRunRound ended
,I/jxcore-log( 6900): 2015-11-25T13:33:27.463Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:27.927Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:28.026Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:28.251Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:28.301Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:28.376Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:28.551Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:28.850Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:28.900Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:29.001Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:29.127Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:29.277Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:29.326Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:29.474Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:29.589Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:29.623Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:29.725Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:29.978Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:30.030Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:30.176Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:30.453Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:30.627Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:30.753Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:30.827Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:30.891Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:30.923Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:31.125Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:31.175Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:31.351Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 6900): 
,W/bt-sdp  ( 6965): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
E/bt-btif ( 6965): DISCOVERY_COMP_EVT slot id:8, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 6965): invalid rfc slot id: 8
I/BTConnectToThread( 6900): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 6900): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 6900): 2015-11-25T13:33:31.476Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:31.477Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:33:31.478Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:31.581Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:31.685Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 6900): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/jxcore-log( 6900): 2015-11-25T13:33:31.764Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:31.800Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 6900): 
,W/bt-btm  ( 6965): sec_bd_name = 
W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,E/bt-l2cap( 6965): l2cu_adjust_out_mps bad packet size: 0  will use MPS: 0
,I/jxcore-log( 6900): 2015-11-25T13:33:31.852Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:31.915Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:31.920Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:31.925Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:31.998Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:32.002Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:32.007Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:32.069Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:32.105Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:32.161Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:32.218Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:32.225Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:32.340Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:32.520Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:32.658Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:32.786Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:33.086Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:33.305Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 6900): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b08478 rs_disc_pending=0
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 6965): invalid rfc slot id: 6
,I/BtToSocketBase( 6900): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 6900): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 6900): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT8083
I/BtToSocketBase( 6900): Stop ReceivingThread
I/BtToSocketBase( 6900): Stop SendingThread
I/BtToSocketBase( 6900): Close local in
I/BtToSocketBase( 6900): Close LocalOutputStream
I/BtToSocketBase( 6900): Close localHostSocket
,I/BtToSocketBase( 6900): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 6900): Close bt in
I/BtConnectorHelper( 6900): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 6900): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT8083
I/BtToSocketBase( 6900): Close bt in
,I/BtToSocketBase( 6900): Close bt out
I/BtToSocketBase( 6900): Close bt socket
I/BtToSocketBase( 6900): Close bt out
I/BtToSocketBase( 6900): Close bt socket
,I/jxcore-log( 6900): 2015-11-25T13:33:33.766Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6900): 
,E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b08478 rs_disc_pending=1
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 6965): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 6965): RFCOMM_DisconnectInd LCID:0x47
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 23
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=43 dispatchEvent: HEART-BEAT-ACK: 23
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
,I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b08478 rs_disc_pending=0
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 6965): HAL bt_hal_cbacks->remote_device_properties_cb
,W/bt-btif ( 6965): HAL bt_hal_cbacks->bond_state_changed_cb
I/BluetoothBondStateMachine( 6965): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 1
,E/bt-btif ( 6965): check_cod: remote_cod = 0x5a020c
,I/ActivityManager( 2937): filter receiver for action = android.bluetooth.device.action.BOND_STATE_CHANGED,
I/BluetoothBondStateMachine( 6965): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 6965): Entering PendingCommandState State
,W/BluetoothEventManager( 3669): CachedBluetoothDevice for device 80:01:84:8A:B3:68 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3669): Got bonding state changed for 80:01:84:8A:B3:68, but we have no record of that device.
,I/jxcore-log( 6900): 2015-11-25T13:33:36.482Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:33:36.483Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 6900): 
,I/        ( 6900): Cleared service requests
,I/        ( 6900): Starting peer discovery failed, error code 0
,W/bt-btif ( 6965): HAL bt_hal_cbacks->bond_state_changed_cb
,I/BluetoothBondStateMachine( 6965): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 0
,I/ActivityManager( 2937): filter receiver for action = android.bluetooth.device.action.BOND_STATE_CHANGED
,I/BluetoothBondStateMachine( 6965): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 11 NewState: 10
,W/BluetoothEventManager( 3669): CachedBluetoothDevice for device 80:01:84:8A:B3:68 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3669): Got bonding state changed for 80:01:84:8A:B3:68, but we have no record of that device.
,I/BluetoothBondStateMachine( 6965): StableState(): Entering Off State
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,I/ActivityManager( 2937): filter receiver for action = android.bluetooth.device.action.ACL_DISCONNECTED
,I/BTConnectionReceiver( 8017): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=Nexus 5, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8017): Bluetooth Device Name: Nexus 5
,E/bt-l2cap( 6965): l2cu_adjust_out_mps bad packet size: 0  will use MPS: 0
,E/bt-l2cap( 6965): l2cu_adjust_out_mps bad packet size: 0  will use MPS: 0
,W/bt-btif ( 6965): new conn_srvc id:26, app_id:255
E/bt-l2cap( 6965): l2cu_adjust_out_mps bad packet size: 0  will use MPS: 0
I/BTListenerThread( 6900): we got incoming connection
I/BTHandshakeSocketThread( 6900): Creating BTHandshakeSocketThread
I/BTListenerThread( 6900): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 6900): BTHandshakeSocketThread started
,I/BTListenerThread( 6900): got MESSAGE_READ 83 bytes.,
I/BTListenerThread( 6900): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT501"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 6900): MESSAGE_WRITE 80 bytes.
,I/HS      ( 6900): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT501
I/BTHandshakeSocketThread( 6900): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 6900): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT501
I/BtToSocketBase( 6900): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 6900): Creating BTConnectedThread
I/BtConnectorHelper( 6900): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 6900): --DoOneRunRound started
,I/System  ( 6900): core_booster, getBoosterConfig = false
,I/BtToRequestSocket( 6900): LocalHost address: localhost/127.0.0.1, port: 43439
,I/BtToRequestSocket( 6900): --DoOneRunRound ended
,I/jxcore-log( 6900): 2015-11-25T13:33:38.490Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:38.911Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:39.000Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:39.114Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:39.432Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:39.936Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:40.031Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:40.041Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:40.328Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:40.337Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:40.737Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:40.935Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:41.037Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:41.242Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:41.494Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:33:41.495Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:33:41.496Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:33:41.496Z SendDataConnector.js: do connect now
I/jxcore-log( 6900): 
,I/        ( 6900): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/BTConnectToThread( 6900): Starting to connect
W/BluetoothAdapter( 6900): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 6900): Connecting to null, at 7C:F9:0E:37:96:AB
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/System.out( 2937): [ping, -c, 1, -w, 2, 192.168.1.1]
I/System.out( 2937): null
I/System.out( 2937): null
I/System.out( 2937): Calling by::className:com.android.server.wifi.ArpVerifier  MethodName:ping
,W/bt-sdp  ( 6965): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 6965): DISCOVERY_COMP_EVT slot id:11, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 6965): invalid rfc slot id: 11
I/BTConnectToThread( 6900): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 6900): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 6900): 2015-11-25T13:33:46.631Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:46.633Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:33:46.634Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:46.665Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:47.083Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:47.176Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:47.270Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:47.575Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:47.878Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:47.986Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:48.075Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:48.180Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:48.487Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:48.582Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:48.683Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:49.282Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:49.586Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:49.891Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 6900): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 24
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=44 dispatchEvent: HEART-BEAT-ACK: 24
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/jxcore-log( 6900): 2015-11-25T13:33:50.998Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:51.097Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 6900): 
,I/HwSystemManager( 4085): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4085): BgPowerManagerService: mTimes = 391038 firstTime = 92756 firstmBatteryCapacity =2203
,E/HwSystemManager( 4085): BgPowerManagerService: conusmPower = 0 result = 0 flag1 =false flag2 = false
,I/jxcore-log( 6900): 2015-11-25T13:33:51.201Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:51.349Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:51.636Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:33:51.637Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:51.749Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:51.951Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:52.151Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:52.455Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:52.658Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:52.856Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:53.066Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:53.264Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:53.490Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:53.504Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:53.545Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:53.581Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:53.591Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:53.622Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:53.835Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 6900): 
,I/HwSystemManager( 4085): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4085): BgPowerManagerService: mTimes = 0 firstTime = 486571 firstmBatteryCapacity =2203
,I/jxcore-log( 6900): 2015-11-25T13:33:54.146Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:54.650Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 6900): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btm  ( 6965): sec_bd_name = 
W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,E/bt-l2cap( 6965): l2cu_adjust_out_mps bad packet size: 0  will use MPS: 0
,I/jxcore-log( 6900): 2015-11-25T13:33:55.039Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:55.153Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 6900): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 6965): HAL bt_hal_cbacks->remote_device_properties_cb
,W/bt-btif ( 6965): HAL bt_hal_cbacks->bond_state_changed_cb
I/BluetoothBondStateMachine( 6965): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
E/bt-btif ( 6965): check_cod: remote_cod = 0x5a020c
,I/ActivityManager( 2937): filter receiver for action = android.bluetooth.device.action.BOND_STATE_CHANGED
,I/BluetoothBondStateMachine( 6965): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 6965): Entering PendingCommandState State
,W/BluetoothEventManager( 3669): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3669): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,W/bt-btif ( 6965): HAL bt_hal_cbacks->bond_state_changed_cb
,I/BluetoothBondStateMachine( 6965): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,I/ActivityManager( 2937): filter receiver for action = android.bluetooth.device.action.BOND_STATE_CHANGED
,I/BluetoothBondStateMachine( 6965): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
W/BluetoothEventManager( 3669): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3669): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,I/BluetoothBondStateMachine( 6965): StableState(): Entering Off State
,W/bt-btif ( 6965): invalid rfc slot id: 9
I/BtToSocketBase( 6900): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 6900): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 6900): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT501
I/BtToSocketBase( 6900): Stop ReceivingThread
I/BtToSocketBase( 6900): Stop SendingThread
I/BtToSocketBase( 6900): Close local in
I/BtToSocketBase( 6900): Close LocalOutputStream
I/BtToSocketBase( 6900): Close localHostSocket
I/BtToSocketBase( 6900): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 6900): Close bt in
I/BtConnectorHelper( 6900): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 6900): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT501
I/BtToSocketBase( 6900): Close bt in
I/BtToSocketBase( 6900): Close bt out
I/BtToSocketBase( 6900): Close bt out
I/BtToSocketBase( 6900): Close bt socket
I/BtToSocketBase( 6900): Close bt socket
,I/jxcore-log( 6900): 2015-11-25T13:33:56.621Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6900): 
,E/bt-l2cap( 6965): l2cu_adjust_out_mps bad packet size: 0  will use MPS: 0
,I/jxcore-log( 6900): 2015-11-25T13:33:56.638Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:33:56.639Z SendDataConnector.js: Connect (retry count 4) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:56.639Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:33:56.639Z SendDataConnector.js: do connect now
I/jxcore-log( 6900): 
,I/        ( 6900): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/BTConnectToThread( 6900): Starting to connect
W/BluetoothAdapter( 6900): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 6900): Connecting to null, at 7C:F9:0E:37:96:AB
,W/bt-btif ( 6965): new conn_srvc id:26, app_id:255,
I/BTListenerThread( 6900): we got incoming connection
I/BTHandshakeSocketThread( 6900): Creating BTHandshakeSocketThread
I/BTListenerThread( 6900): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 6900): BTHandshakeSocketThread started
,E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b08810 rs_disc_pending=0
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 6900): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 6900): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 6900): MESSAGE_WRITE 80 bytes.
I/HS      ( 6900): Incoming connection Hand Shake finished for : motorola-XT1072_PT9583
I/BTHandshakeSocketThread( 6900): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 6900): Starting the connected thread incoming : true, motorola-XT1072_PT9583
I/BtToSocketBase( 6900): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 6900): Creating BTConnectedThread
I/BtConnectorHelper( 6900): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 6900): --DoOneRunRound started
,I/System  ( 6900): core_booster, getBoosterConfig = false
,I/BtToRequestSocket( 6900): LocalHost address: localhost/127.0.0.1, port: 43439
,I/BtToRequestSocket( 6900): --DoOneRunRound ended
,I/jxcore-log( 6900): 2015-11-25T13:33:59.124Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:59.541Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6900): 
,W/bt-rfcomm( 6965): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
W/bt-rfcomm( 6965): RFCOMM_DisconnectInd LCID:0x4b
,I/jxcore-log( 6900): 2015-11-25T13:33:59.571Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data,
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:59.731Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:59.772Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:33:59.892Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:00.024Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:00.093Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:00.182Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:00.200Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:00.211Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 6900): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/jxcore-log( 6900): 2015-11-25T13:34:00.353Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:00.384Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:00.541Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:00.621Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:00.663Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:00.702Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:00.765Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:00.896Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:00.977Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:01.058Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:01.076Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:01.189Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:01.344Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:01.583Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:01.615Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:02.047Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:02.185Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:02.203Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:02.331Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:02.508Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:02.587Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:02.691Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:02.839Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:02.862Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:03.371Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:03.554Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:03.615Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:03.717Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:03.788Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:03.848Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:03.881Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:03.927Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:04.040Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:04.154Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:04.239Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:04.356Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:04.398Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:04.510Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:04.543Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:04.707Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:04.802Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:04.840Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 6900): 
,W/bt-btif ( 6965): invalid rfc slot id: 10
I/BtToSocketBase( 6900): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 6900): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 6900): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT9583
I/BtToSocketBase( 6900): Stop ReceivingThread
I/BtToSocketBase( 6900): Stop SendingThread
I/BtToSocketBase( 6900): Close local in
I/BtToSocketBase( 6900): Close LocalOutputStream
I/BtToSocketBase( 6900): Close localHostSocket
I/BtToSocketBase( 6900): Close bt in
I/BtToSocketBase( 6900): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 6900): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 6900): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT9583
I/BtToSocketBase( 6900): Close bt in
I/BtToSocketBase( 6900): Close bt out
I/BtToSocketBase( 6900): Close bt out
I/BtToSocketBase( 6900): Close bt socket
I/BtToSocketBase( 6900): Close bt socket
,I/jxcore-log( 6900): 2015-11-25T13:34:04.927Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6900): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 25
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=45 dispatchEvent: HEART-BEAT-ACK: 25
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,W/bt-sdp  ( 6965): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 6965): DISCOVERY_COMP_EVT slot id:12, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 6965): invalid rfc slot id: 12
I/BTConnectToThread( 6900): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 6900): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 6900): 2015-11-25T13:34:07.200Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:34:07.201Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:07.210Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:07.212Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): ---- round done--------
I/jxcore-log( 6900): 
I/jxcore-log( 6900): ---- gotta redo : 7C:F9:0E:37:96:AB, try count now: 1
I/jxcore-log( 6900): 
I/jxcore-log( 6900): do fake peer & start
I/jxcore-log( 6900): 
I/jxcore-log( 6900): Connect to fake peer: 34:FC:EF:11:AE:67
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:34:07.213Z SendDataConnector.js: Start called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:34:07.214Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:34:07.214Z SendDataConnector.js: do connect now
I/jxcore-log( 6900): 
,I/        ( 6900): Selected device address: 34:FC:EF:11:AE:67, name: null
,I/BTConnectToThread( 6900): Starting to connect
,W/BluetoothAdapter( 6900): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 6900): Connecting to null, at 34:FC:EF:11:AE:67
,I/chromium( 6900): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 7C:F9:0E:37:96:AB done with result: Connection to 7C:F9:0E:37:96:AB failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btm  ( 6965): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b08810 rs_disc_pending=2
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,I/ActivityManager( 2937): filter receiver for action = android.bluetooth.device.action.ACL_DISCONNECTED
,I/BTConnectionReceiver( 8017): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=XT1072, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8017): Bluetooth Device Name: XT1072
,W/bt-btm  ( 6965): sec_bd_name = 
W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 26
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=46 dispatchEvent: HEART-BEAT-ACK: 26
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/ActivityManager( 2937): filter receiver for action = android.bluetooth.device.action.ACL_DISCONNECTED
,I/BTConnectionReceiver( 8017): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=HTC Desire 820, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8017): Bluetooth Device Name: HTC Desire 820
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 27
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=47 dispatchEvent: HEART-BEAT-ACK: 27
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/        ( 6900): Cleared service requests
,I/        ( 6900): Starting peer discovery failed, error code 0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btif ( 6965): DISCOVERY_COMP_EVT slot id:14, failed to find channle,                                       status:1, scn:0
E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=0,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): invalid rfc slot id: 14
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
I/BTConnectToThread( 6900): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
I/CONNEC  ( 6900): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 6900): 2015-11-25T13:34:42.247Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:34:42.247Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:34:42.248Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6900): 
,I/DeviceStatsManager( 3825):  uid:1002 pid:6965 flags:1 tag:bluedroid_timer wakeup time:132539
,I/jxcore-log( 6900): 2015-11-25T13:34:47.248Z SendDataConnector.js: re-try now : 34:FC:EF:11:AE:67
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:34:47.250Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6900): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 28
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=48 dispatchEvent: HEART-BEAT-ACK: 28
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/jxcore-log( 6900): 2015-11-25T13:34:52.262Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:34:52.262Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:AE:67 with availability status: true
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:34:52.263Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:34:52.263Z SendDataConnector.js: do connect now
I/jxcore-log( 6900): 
,I/        ( 6900): Selected device address: 34:FC:EF:11:AE:67, name: null
,I/BTConnectToThread( 6900): Starting to connect
W/BluetoothAdapter( 6900): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 6900): Connecting to null, at 34:FC:EF:11:AE:67
,W/bt-btif ( 6965): info:x10
,W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-l2cap( 6965): l2cu_adjust_out_mps bad packet size: 0  will use MPS: 0
,W/bt-sdp  ( 6965): process_service_search_attr_rsp
,W/bt-btif ( 6965): HAL bt_hal_cbacks->remote_device_properties_cb
,W/bt-btif ( 6965): HAL bt_hal_cbacks->bond_state_changed_cb
,I/BluetoothBondStateMachine( 6965): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 1
E/bt-btif ( 6965): check_cod: remote_cod = 0x5a020c
,I/ActivityManager( 2937): filter receiver for action = android.bluetooth.device.action.BOND_STATE_CHANGED
I/BluetoothBondStateMachine( 6965): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 6965): Entering PendingCommandState State
W/BluetoothEventManager( 3669): CachedBluetoothDevice for device 34:FC:EF:11:AE:67 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3669): Got bonding state changed for 34:FC:EF:11:AE:67, but we have no record of that device.
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 6965): HAL bt_hal_cbacks->bond_state_changed_cb
,I/BluetoothBondStateMachine( 6965): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 0
I/ActivityManager( 2937): filter receiver for action = android.bluetooth.device.action.BOND_STATE_CHANGED
I/BluetoothBondStateMachine( 6965): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 11 NewState: 10
,W/BluetoothEventManager( 3669): CachedBluetoothDevice for device 34:FC:EF:11:AE:67 not found, calling readPairedDevices().
E/BluetoothEventManager( 3669): Got bonding state changed for 34:FC:EF:11:AE:67, but we have no record of that device.,
,I/BluetoothBondStateMachine( 6965): StableState(): Entering Off State
,E/bt-l2cap( 6965): l2cu_adjust_out_mps bad packet size: 0  will use MPS: 0
,W/bt-btif ( 6965): new conn_srvc id:26, app_id:1
,I/BTConnectToThread( 6900): Starting to Handshake
I/BTHandshakeSocketThread( 6900): Creating BTHandshakeSocketThread
I/BTConnectToThread( 6900): MESSAGE_WRITE 80 bytes.
,I/BTHandshakeSocketThread( 6900): BTHandshakeSocketThread started
,I/BTConnectToThread( 6900): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 6900): Got JSON from encryption:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6456","ra":"34:FC:EF:11:AE:67"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 6900): HandshakeOk : LGE-Nexus 5_PT6456
I/HS      ( 6900): Hand Shake finished outgoing for : LGE-Nexus 5_PT6456
,I/BTHandshakeSocketThread( 6900): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 6900): Starting the connected thread incoming : false, LGE-Nexus 5_PT6456
,I/BtToSocketBase( 6900): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 6900): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 6900): mHTTPPort  set to : 56495
,I/BtConnectorHelper( 6900): Request socket is using : 56495
I/BtToRequestSocket( 6900): Now accepting connections
I/System  ( 6900): core_booster, getBoosterConfig = false
,I/BtConnectorHelper( 6900): Calling ConnectionStatusUpdate with port :56495
,I/jxcore-log( 6900): 2015-11-25T13:34:54.796Z SendDataConnector.js: CLIENT connected to 56495, error: null
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:34:54.797Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6900): 
,I/BtToRequestSocket( 6900): incoming data from: /127.0.0.1, port: 56495
I/BtToRequestSocket( 6900): Set local streams
,I/jxcore-log( 6900): 2015-11-25T13:34:54.811Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6900): 
I/BtToRequestSocket( 6900): rin ended ---------------------------;
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btm  ( 6965): sec_bd_name = 
W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,E/bt-l2cap( 6965): l2cu_adjust_out_mps bad packet size: 0  will use MPS: 0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 6965): HAL bt_hal_cbacks->remote_device_properties_cb
,W/bt-btif ( 6965): HAL bt_hal_cbacks->bond_state_changed_cb
,I/BluetoothBondStateMachine( 6965): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
E/bt-btif ( 6965): check_cod: remote_cod = 0x5a020c
I/ActivityManager( 2937): filter receiver for action = android.bluetooth.device.action.BOND_STATE_CHANGED
I/BluetoothBondStateMachine( 6965): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 6965): Entering PendingCommandState State
,W/BluetoothEventManager( 3669): CachedBluetoothDevice for device 58:3F:54:73:64:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3669): Got bonding state changed for 58:3F:54:73:64:C0, but we have no record of that device.
,W/bt-btif ( 6965): HAL bt_hal_cbacks->bond_state_changed_cb
,I/BluetoothBondStateMachine( 6965): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
,I/ActivityManager( 2937): filter receiver for action = android.bluetooth.device.action.BOND_STATE_CHANGED
,I/BluetoothBondStateMachine( 6965): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
,W/BluetoothEventManager( 3669): CachedBluetoothDevice for device 58:3F:54:73:64:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3669): Got bonding state changed for 58:3F:54:73:64:C0, but we have no record of that device.
,I/BluetoothBondStateMachine( 6965): StableState(): Entering Off State
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-l2cap( 6965): l2cu_adjust_out_mps bad packet size: 0  will use MPS: 0
,W/bt-btif ( 6965): new conn_srvc id:26, app_id:255
,I/BTListenerThread( 6900): we got incoming connection
I/BTHandshakeSocketThread( 6900): Creating BTHandshakeSocketThread
I/BTListenerThread( 6900): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 6900): BTHandshakeSocketThread started
,I/BTListenerThread( 6900): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 6900): Got JSON from encryption:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 6900): MESSAGE_WRITE 80 bytes.
I/HS      ( 6900): Incoming connection Hand Shake finished for : LGE-LG-D855_PT4505
I/BTHandshakeSocketThread( 6900): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 6900): Starting the connected thread incoming : true, LGE-LG-D855_PT4505
I/BtToSocketBase( 6900): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 6900): Creating BTConnectedThread
I/BtConnectorHelper( 6900): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 6900): --DoOneRunRound started
,I/System  ( 6900): core_booster, getBoosterConfig = false
,I/BtToRequestSocket( 6900): LocalHost address: localhost/127.0.0.1, port: 43439
,I/BtToRequestSocket( 6900): --DoOneRunRound ended
,I/jxcore-log( 6900): 2015-11-25T13:34:59.795Z SendDataTCPServer.js: TCP/IP server connected,
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:00.420Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:00.681Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:00.732Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:00.838Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:00.861Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:01.018Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:01.196Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:01.301Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:01.623Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:01.646Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:01.775Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:01.853Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:02.007Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:02.263Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 6900): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/jxcore-log( 6900): 2015-11-25T13:35:02.421Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:02.574Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:02.728Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:03.030Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:03.236Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:03.706Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:03.860Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:03.991Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:04.146Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:04.836Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:35:04.837Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:04.838Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:35:04.840Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:04.841Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 6900): 
,I/BtToSocketBase( 6900): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 6900): Disconnect outgoing peer: LGE-Nexus 5_PT6456
I/BtToSocketBase( 6900): Stop ReceivingThread
I/BtToSocketBase( 6900): Stop SendingThread
I/BtToSocketBase( 6900): Close local in
,I/BtToSocketBase( 6900): Close LocalOutputStream
I/BtToSocketBase( 6900): Close localHostSocket
I/BtToSocketBase( 6900): Close bt in
I/BtToSocketBase( 6900): Close bt out
I/BtToSocketBase( 6900): Close bt socket
I/BtToSocketBase( 6900): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToRequestSocket( 6900): Close server socket
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 29
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=49 dispatchEvent: HEART-BEAT-ACK: 29
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/jxcore-log( 6900): 2015-11-25T13:35:09.841Z SendDataConnector.js: re-try now : 34:FC:EF:11:AE:67
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:35:09.842Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6900): 
,W/bt-btif ( 6965): dm_pm_timer expires
W/bt-btif ( 6965): dm_pm_timer expires 0
,W/bt-btif ( 6965): proc dm_pm_timer expires
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/jxcore-log( 6900): 2015-11-25T13:35:14.846Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:35:14.847Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:AE:67 with availability status: true
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:35:14.848Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:35:14.848Z SendDataConnector.js: do connect now
I/jxcore-log( 6900): 
,I/        ( 6900): Selected device address: 34:FC:EF:11:AE:67, name: Nexus 5
,I/BTConnectToThread( 6900): Starting to connect
W/BluetoothAdapter( 6900): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 6900): Connecting to Nexus 5, at 34:FC:EF:11:AE:67
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 30
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=50 dispatchEvent: HEART-BEAT-ACK: 30
E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 31
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=51 dispatchEvent: HEART-BEAT-ACK: 31
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/        ( 6900): Cleared service requests
,I/        ( 6900): Starting peer discovery failed, error code 0
,E/BTLD    ( 6965): ######################################################################
E/BTLD    ( 6965): #
E/BTLD    ( 6965): # WARNING : BTU HCI(id=0) command timeout. opcode=0x803
E/BTLD    ( 6965): #
E/BTLD    ( 6965): ######################################################################
W/bt-hci  ( 6965): HCI Cmd timeout counter 1
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=0,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): invalid rfc slot id: 13
I/BtToSocketBase( 6900): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 6900): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 6900): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D855_PT4505
I/BtToSocketBase( 6900): Stop ReceivingThread
I/BtToSocketBase( 6900): Stop SendingThread
I/BtToSocketBase( 6900): Close local in
I/BtToSocketBase( 6900): Close LocalOutputStream
I/BtToSocketBase( 6900): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 6900): Close localHostSocket
I/BtToSocketBase( 6900): Close bt in
I/BtConnectorHelper( 6900): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
W/bt-hci  ( 6965): No command in queue matching opcode 2051
I/BtConnectorHelper( 6900): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D855_PT4505
I/BtToSocketBase( 6900): Close bt in
I/BtToSocketBase( 6900): Close bt out
I/BtToSocketBase( 6900): Close bt socket
I/BtToSocketBase( 6900): Close bt out
I/BtToSocketBase( 6900): Close bt socket
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
I/ActivityManager( 2937): filter receiver for action = android.bluetooth.device.action.ACL_DISCONNECTED
,I/jxcore-log( 6900): 2015-11-25T13:35:46.424Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6900): 
,I/BTConnectionReceiver( 8017): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=G3-1, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8017): Bluetooth Device Name: G3-1
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,I/ActivityManager( 2937): filter receiver for action = android.bluetooth.device.action.ACL_CONNECTED
,I/BTConnectionReceiver( 8017): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=G3-1, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8017): Bluetooth Device Name: G3-1
,I/PG Utils( 3793): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 3793): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-l2cap( 6965): l2cu_adjust_out_mps bad packet size: 0  will use MPS: 0
,E/bt-l2cap( 6965): l2cu_adjust_out_mps bad packet size: 0  will use MPS: 0
,W/bt-btif ( 6965): new conn_srvc id:26, app_id:255
,I/BTListenerThread( 6900): we got incoming connection
I/BTHandshakeSocketThread( 6900): Creating BTHandshakeSocketThread
I/BTListenerThread( 6900): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 6900): BTHandshakeSocketThread started
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 32
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=52 dispatchEvent: HEART-BEAT-ACK: 32
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/BTListenerThread( 6900): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 6900): Got JSON from encryption:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 6900): MESSAGE_WRITE 80 bytes.
I/HS      ( 6900): Incoming connection Hand Shake finished for : LGE-LG-D855_PT4505
I/BTHandshakeSocketThread( 6900): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 6900): Starting the connected thread incoming : true, LGE-LG-D855_PT4505
,I/BtToSocketBase( 6900): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 6900): Creating BTConnectedThread
I/BtConnectorHelper( 6900): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 6900): --DoOneRunRound started
I/System  ( 6900): core_booster, getBoosterConfig = false
,I/BtToRequestSocket( 6900): LocalHost address: localhost/127.0.0.1, port: 43439
,I/jxcore-log( 6900): 2015-11-25T13:35:50.160Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6900): 
,I/BtToRequestSocket( 6900): --DoOneRunRound ended
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
,I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/jxcore-log( 6900): 2015-11-25T13:35:50.573Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:50.681Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:50.836Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:51.340Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:51.464Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:51.621Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:51.733Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:51.811Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:51.867Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:51.883Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:52.102Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:52.206Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:52.337Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:52.372Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:52.524Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:52.551Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:52.659Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:52.789Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:52.846Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:53.008Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:53.116Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:53.247Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data,
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:53.401Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:53.581Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:53.713Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:53.925Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:54.033Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 6900): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/jxcore-log( 6900): 2015-11-25T13:35:54.140Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:54.296Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:54.470Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:54.504Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:54.590Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 6900): 
,W/bt-btm  ( 6965): sec_bd_name = 
W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 6900): 2015-11-25T13:35:54.614Z SendDataTCPServer.js: TCP/IP server has received 60002 bytes of data
I/jxcore-log( 6900): 
,W/bt_h4   ( 6965): H4 - dropping incomplete ACL frame
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b08d74 rs_disc_pending=0
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,E/bt-l2cap( 6965): l2cu_adjust_out_mps bad packet size: 0  will use MPS: 0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 6965): HAL bt_hal_cbacks->remote_device_properties_cb
,W/bt-btif ( 6965): HAL bt_hal_cbacks->bond_state_changed_cb
I/BluetoothBondStateMachine( 6965): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
E/bt-btif ( 6965): check_cod: remote_cod = 0x5a020c
,I/ActivityManager( 2937): filter receiver for action = android.bluetooth.device.action.BOND_STATE_CHANGED
,I/BluetoothBondStateMachine( 6965): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 6965): Entering PendingCommandState State
,W/BluetoothEventManager( 3669): CachedBluetoothDevice for device 7C:F9:0E:34:8A:A0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3669): Got bonding state changed for 7C:F9:0E:34:8A:A0, but we have no record of that device.
,W/bt-btif ( 6965): invalid rfc slot id: 16
I/BtToSocketBase( 6900): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 6900): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 6900): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D855_PT4505
I/BtToSocketBase( 6900): Stop ReceivingThread
I/BtToSocketBase( 6900): Stop SendingThread
I/BtToSocketBase( 6900): Close local in
I/BtToSocketBase( 6900): Close LocalOutputStream
I/BtToSocketBase( 6900): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 6900): Close localHostSocket
I/BtToSocketBase( 6900): Close bt in
I/BtConnectorHelper( 6900): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 6900): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D855_PT4505
I/BtToSocketBase( 6900): Close bt in
I/BtToSocketBase( 6900): Close bt out
I/BtToSocketBase( 6900): Close bt socket
I/BtToSocketBase( 6900): Close bt out
I/BtToSocketBase( 6900): Close bt socket
,I/jxcore-log( 6900): 2015-11-25T13:35:57.365Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6900): 
,W/bt-btif ( 6965): HAL bt_hal_cbacks->bond_state_changed_cb
,I/BluetoothBondStateMachine( 6965): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,I/ActivityManager( 2937): filter receiver for action = android.bluetooth.device.action.BOND_STATE_CHANGED
I/BluetoothBondStateMachine( 6965): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
W/BluetoothEventManager( 3669): CachedBluetoothDevice for device 7C:F9:0E:34:8A:A0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3669): Got bonding state changed for 7C:F9:0E:34:8A:A0, but we have no record of that device.
,I/BluetoothBondStateMachine( 6965): StableState(): Entering Off State
,E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b08d74 rs_disc_pending=1
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 6965): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 6965): RFCOMM_DisconnectInd LCID:0x47
,E/bt-l2cap( 6965): l2cu_adjust_out_mps bad packet size: 0  will use MPS: 0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 6965): new conn_srvc id:26, app_id:255
I/BTListenerThread( 6900): we got incoming connection
I/BTHandshakeSocketThread( 6900): Creating BTHandshakeSocketThread
I/BTListenerThread( 6900): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 6900): BTHandshakeSocketThread started
,E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b08d74 rs_disc_pending=1
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 6900): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 6900): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 6900): MESSAGE_WRITE 80 bytes.
I/HS      ( 6900): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT8472
I/BTHandshakeSocketThread( 6900): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 6900): Starting the connected thread incoming : true, samsung-SM-G900F_PT8472
I/BtToSocketBase( 6900): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 6900): Creating BTConnectedThread
I/BtConnectorHelper( 6900): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 6900): --DoOneRunRound started
,I/System  ( 6900): core_booster, getBoosterConfig = false
,I/BtToRequestSocket( 6900): LocalHost address: localhost/127.0.0.1, port: 43439
,I/BtToRequestSocket( 6900): --DoOneRunRound ended
,I/jxcore-log( 6900): 2015-11-25T13:35:58.497Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:58.975Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:59.001Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:59.028Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:59.053Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:59.074Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:59.141Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:59.195Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:59.252Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:59.437Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:59.458Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 6900): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/jxcore-log( 6900): 2015-11-25T13:35:59.486Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:59.541Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:59.593Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:59.702Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:59.776Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:59.935Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:59.961Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:35:59.988Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:36:00.094Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:36:00.223Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:36:00.324Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:36:00.357Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:36:00.436Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:36:00.472Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:36:00.531Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:36:00.610Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:36:00.694Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:36:00.877Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:36:01.061Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:36:01.112Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:36:01.136Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:36:01.189Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:36:01.266Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:36:01.290Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:36:01.321Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:36:01.343Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:36:01.450Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 6900): 
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,I/ActivityManager( 2937): filter receiver for action = android.bluetooth.device.action.ACL_DISCONNECTED
,I/BTConnectionReceiver( 8017): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=G3-1, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8017): Bluetooth Device Name: G3-1
,I/jxcore-log( 6900): 2015-11-25T13:36:01.549Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:36:01.604Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:36:01.640Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:36:01.785Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:36:01.868Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:36:01.894Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:36:01.972Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:36:02.055Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:36:02.132Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:36:02.264Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:36:02.395Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:36:02.473Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:36:02.512Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:36:02.525Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:36:02.576Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:36:02.597Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 6900): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 6965): invalid rfc slot id: 18
,I/BtToSocketBase( 6900): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 6900): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 6900): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT8472
I/BtToSocketBase( 6900): Stop ReceivingThread
I/BtToSocketBase( 6900): Stop SendingThread
,I/BtToSocketBase( 6900): Close local in
I/BtToSocketBase( 6900): Close LocalOutputStream
I/BtToSocketBase( 6900): Close localHostSocket
I/BtToSocketBase( 6900): Close bt in
,I/BtToSocketBase( 6900): Close bt out
I/BtToSocketBase( 6900): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 6900): Close bt socket
I/BtConnectorHelper( 6900): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 6900): 2015-11-25T13:36:02.705Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6900): 
,E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b08d74 rs_disc_pending=0
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 6965): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
W/bt-rfcomm( 6965): RFCOMM_DisconnectInd LCID:0x4c
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 33
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=53 dispatchEvent: HEART-BEAT-ACK: 33
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,I/ActivityManager( 2937): filter receiver for action = android.bluetooth.device.action.ACL_DISCONNECTED
,I/BTConnectionReceiver( 8017): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=S5-1, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8017): Bluetooth Device Name: S5-1
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/BtConnection( 6900): connectionTimeoutTimer
E/bt-btif ( 6965): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:17, channel:-1
I/CONNEC  ( 6900): Error: Cancelled
I/BTConnectToThread( 6900): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 6900): 2015-11-25T13:36:14.863Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:36:14.864Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:36:14.865Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6900): 
,I/CONNEC  ( 6900): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,W/jxcore-log( 6900): $$jxcore_callback_20 wasn't registered
W/jxcore-log( 6900): 
,W/bt-sdp  ( 6965): SDP - Rcvd conn cnf with error: 0xeeee  CID 0x45
E/bt-btif ( 6965): DISCOVERY_COMP_EVT slot id:17, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 6965): invalid rfc slot id: 17
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/DeviceStatsManager( 3825):  uid:1002 pid:6965 flags:1 tag:bluedroid_timer wakeup time:216677
,I/jxcore-log( 6900): 2015-11-25T13:36:19.866Z SendDataConnector.js: re-try now : 34:FC:EF:11:AE:67
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:36:19.867Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6900): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 34
E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=54 dispatchEvent: HEART-BEAT-ACK: 34
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/jxcore-log( 6900): 2015-11-25T13:36:24.874Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:36:24.875Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:11:AE:67 with availability status: true
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:36:24.876Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:36:24.876Z SendDataConnector.js: do connect now
I/jxcore-log( 6900): 
,I/        ( 6900): Selected device address: 34:FC:EF:11:AE:67, name: Nexus 5
,I/BTConnectToThread( 6900): Starting to connect
W/BluetoothAdapter( 6900): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 6900): Connecting to Nexus 5, at 34:FC:EF:11:AE:67
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 35
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=55 dispatchEvent: HEART-BEAT-ACK: 35
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/        ( 6900): Cleared service requests
,I/        ( 6900): Starting peer discovery failed, error code 0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btm  ( 6965): sec_bd_name = 
W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b08f40 rs_disc_pending=1
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 36
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=56 dispatchEvent: HEART-BEAT-ACK: 36
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,W/bt-btif ( 6965): info:x10
,W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 37
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=57 dispatchEvent: HEART-BEAT-ACK: 37
E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,W/bt-btm  ( 6965): sec_bd_name = 
W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b0910c rs_disc_pending=0
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b0910c rs_disc_pending=1
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 38
E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=58 dispatchEvent: HEART-BEAT-ACK: 38
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 4085): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4085): BgPowerManagerService: mTimes = 207777 firstTime = 486571 firstmBatteryCapacity =2203
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/BtConnection( 6900): connectionTimeoutTimer
I/CONNEC  ( 6900): Error: Cancelled
E/bt-btif ( 6965): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:20, channel:-1
I/BTConnectToThread( 6900): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 6900): 2015-11-25T13:37:24.884Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:37:24.885Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:37:24.886Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6900): 
I/CONNEC  ( 6900): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,W/jxcore-log( 6900): $$jxcore_callback_22 wasn't registered
W/jxcore-log( 6900): 
,W/bt-sdp  ( 6965): SDP - Rcvd conn cnf with error: 0xeeee  CID 0x4d
,E/bt-btif ( 6965): DISCOVERY_COMP_EVT slot id:20, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 6965): invalid rfc slot id: 20
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 6900): 2015-11-25T13:37:29.887Z SendDataConnector.js: re-try now : 34:FC:EF:11:AE:67
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:37:29.888Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:37:34.894Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:37:34.895Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:11:AE:67 with availability status: true
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:37:34.896Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:37:34.896Z SendDataConnector.js: do connect now
I/jxcore-log( 6900): 
,I/        ( 6900): Selected device address: 34:FC:EF:11:AE:67, name: Nexus 5
,I/BTConnectToThread( 6900): Starting to connect
W/BluetoothAdapter( 6900): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 6900): Connecting to Nexus 5, at 34:FC:EF:11:AE:67
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 39
E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=59 dispatchEvent: HEART-BEAT-ACK: 39
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/        ( 6900): Cleared service requests
,I/        ( 6900): Starting peer discovery failed, error code 0
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b08f40 rs_disc_pending=0
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 40
E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=60 dispatchEvent: HEART-BEAT-ACK: 40
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 4085): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4085): BgPowerManagerService: mTimes = 237858 firstTime = 486571 firstmBatteryCapacity =2203
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 41
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=61 dispatchEvent: HEART-BEAT-ACK: 41
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 42
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=62 dispatchEvent: HEART-BEAT-ACK: 42
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
,I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b0910c rs_disc_pending=0
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
,I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b0910c rs_disc_pending=1
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-sdp  ( 6965): SDP - Rcvd conn cnf with error: 0xeeee  CID 0x4b
E/bt-btif ( 6965): DISCOVERY_COMP_EVT slot id:21, failed to find channle,                                       status:1, scn:0
,I/BTConnectToThread( 6900): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-btif ( 6965): invalid rfc slot id: 21
I/CONNEC  ( 6900): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 6900): 2015-11-25T13:38:33.945Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:38:33.946Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:38:33.950Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:38:33.951Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:38:33.954Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): ---- round done--------
I/jxcore-log( 6900): 
I/jxcore-log( 6900): ---- gotta redo : 34:FC:EF:11:AE:67, try count now: 1
I/jxcore-log( 6900): 
I/jxcore-log( 6900): do fake peer & start
I/jxcore-log( 6900): 
I/jxcore-log( 6900): Connect to fake peer: F8:95:C7:87:3C:51
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:38:33.956Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:38:33.956Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:38:33.957Z SendDataConnector.js: do connect now
I/jxcore-log( 6900): 
,I/        ( 6900): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,I/BTConnectToThread( 6900): Starting to connect
W/BluetoothAdapter( 6900): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 6900): Connecting to G4-1, at F8:95:C7:87:3C:51
,I/chromium( 6900): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 34:FC:EF:11:AE:67 done with result: Connection to 34:FC:EF:11:AE:67 failed", source: file:///android_asset/www/js/thali_main.js (63)
,E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b0910c rs_disc_pending=0
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 43
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=63 dispatchEvent: HEART-BEAT-ACK: 43
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/        ( 6900): Cleared service requests
,I/        ( 6900): Starting peer discovery failed, error code 0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 6965): info:x10
,W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,I/ActivityManager( 2937): filter receiver for action = android.bluetooth.device.action.ACL_CONNECTED
,I/BTConnectionReceiver( 8017): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=G4-1, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8017): Bluetooth Device Name: G4-1
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b0910c rs_disc_pending=1
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b082ac rs_disc_pending=0
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/wifi_log/wifi_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 44
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=64 dispatchEvent: HEART-BEAT-ACK: 44
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 45
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=65 dispatchEvent: HEART-BEAT-ACK: 45
E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b082ac rs_disc_pending=1
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b082ac rs_disc_pending=1
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btm  ( 6965): sec_bd_name = 
W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b082ac rs_disc_pending=0
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 46
E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=66 dispatchEvent: HEART-BEAT-ACK: 46
E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/BtConnection( 6900): connectionTimeoutTimer
I/CONNEC  ( 6900): Error: Cancelled
E/bt-btif ( 6965): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:22, channel:-1
I/BTConnectToThread( 6900): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 6900): 2015-11-25T13:39:33.963Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:39:33.964Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:39:33.965Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6900): 
,I/CONNEC  ( 6900): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,W/jxcore-log( 6900): $$jxcore_callback_26 wasn't registered
W/jxcore-log( 6900): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 47
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=67 dispatchEvent: HEART-BEAT-ACK: 47
E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/        ( 6900): Cleared service requests
,I/        ( 6900): Starting peer discovery failed, error code 0
,I/jxcore-log( 6900): 2015-11-25T13:39:38.966Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:39:38.967Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:39:43.972Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:39:43.973Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:39:43.973Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:39:43.974Z SendDataConnector.js: do connect now
I/jxcore-log( 6900): 
,I/        ( 6900): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,I/BTConnectToThread( 6900): Starting to connect
W/BluetoothAdapter( 6900): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 6900): Connecting to G4-1, at F8:95:C7:87:3C:51
,E/bt-btif ( 6965): DISCOVERY_COMP_EVT slot id:23, failed to find channle,                                       status:2, scn:-1291544406
W/bt-btif ( 6965): invalid rfc slot id: 23
,I/BTConnectToThread( 6900): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 6900): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 6900): 2015-11-25T13:39:43.992Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:39:43.992Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:39:43.993Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6900): 
,W/bt-sdp  ( 6965): SDP - Rcvd conn cnf with error: 0xeeee  CID 0x42
E/bt-btif ( 6965): DISCOVERY_COMP_EVT slot id:22, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 6965): invalid rfc slot id: 22
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=0,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/ActivityManager( 2937): filter receiver for action = android.bluetooth.device.action.ACL_DISCONNECTED,
,I/BTConnectionReceiver( 8017): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=G4-1, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8017): Bluetooth Device Name: G4-1
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 6900): 2015-11-25T13:39:48.993Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:39:48.994Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 6900): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/DeviceStatsManager( 3825):  uid:1002 pid:6965 flags:1 tag:bluedroid_timer wakeup time:421590
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 48
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=68 dispatchEvent: HEART-BEAT-ACK: 48
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,W/bt-btif ( 6965): info:x10
,W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/HwSystemManager( 4085): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4085): BgPowerManagerService: mTimes = 359998 firstTime = 486571 firstmBatteryCapacity =2203
E/HwSystemManager( 4085): BgPowerManagerService: conusmPower = -1 result = -10 flag1 =false flag2 = false
,I/jxcore-log( 6900): 2015-11-25T13:39:53.998Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:39:54.000Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:39:54.000Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:39:54.001Z SendDataConnector.js: do connect now
I/jxcore-log( 6900): 
,I/        ( 6900): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,I/BTConnectToThread( 6900): Starting to connect,
W/BluetoothAdapter( 6900): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 6900): Connecting to G4-1, at F8:95:C7:87:3C:51
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,I/ActivityManager( 2937): filter receiver for action = android.bluetooth.device.action.ACL_CONNECTED
,I/BTConnectionReceiver( 8017): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=G4-1, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8017): Bluetooth Device Name: G4-1
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 49
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=69 dispatchEvent: HEART-BEAT-ACK: 49
E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btif ( 6965): DISCOVERY_COMP_EVT slot id:24, failed to find channle,                                       status:1, scn:0
E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=0,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - 
W/bt-btif ( 6965): btm_sec_disconnected - 
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
I/BTConnectToThread( 6900): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 6900): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/ActivityManager( 2937): filter receiver for action = android.bluetooth.device.action.ACL_DISCONNECTED
,I/jxcore-log( 6900): 2015-11-25T13:40:17.833Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:40:17.833Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:40:17.834Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6900): 
,I/BTConnectionReceiver( 8017): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=G4-1, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8017): Bluetooth Device Name: G4-1
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 50
E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=70 dispatchEvent: HEART-BEAT-ACK: 50
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/jxcore-log( 6900): 2015-11-25T13:40:22.836Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:40:22.837Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 6900): 
,W/bt-btm  ( 6965): sec_bd_name = 
W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b094a4 rs_disc_pending=0
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 6900): 2015-11-25T13:40:27.842Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:40:27.843Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:40:27.845Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:40:27.846Z SendDataConnector.js: do connect now
I/jxcore-log( 6900): 
,I/        ( 6900): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,I/BTConnectToThread( 6900): Starting to connect
W/BluetoothAdapter( 6900): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 6900): Connecting to G4-1, at F8:95:C7:87:3C:51
,E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b094a4 rs_disc_pending=1
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 6965): No ag scb for peer addr
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 51
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=71 dispatchEvent: HEART-BEAT-ACK: 51
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/        ( 6900): Cleared service requests
,I/        ( 6900): Starting peer discovery failed, error code 0
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 52
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=72 dispatchEvent: HEART-BEAT-ACK: 52
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 4085): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4085): BgPowerManagerService: mTimes = 0 firstTime = 906569 firstmBatteryCapacity =2204
,I/AGNSSCONTROL( 2738): void pgps_timer_func(sigval) -- 62: Timer: overflow invoke time func
I/AGNSSCONTROL( 2738): AGNSS_STATUS_ENUM_UINT32 PACommMgr::RequestFunc() -- 488: m_pgps_mode:1
I/AGNSSCONTROL( 2738): void kill_timer(timer_t) -- 102: Timer: kill a timer 2872225664
I/AGNSSCONTROL( 2738): AGNSS_STATUS_ENUM_UINT32 PACommMgr::RequestFunc() -- 498: Timer: set a timer again 2872254952
I/AGNSSCONTROL( 2738): AGNSS_STATUS_ENUM_UINT32 PACommMgr::RequestFunc() -- 504: create thread
,I/AGNSSCONTROL( 2738): static void* PACommMgr::RequestAssistance(void*) -- 588: mcc:0, mnc:0, lac:0, cid:0
I/AGNSSCONTROL( 2738): void PACommMgr::SetAllowSendingCellIdsWlanApnToServerStatus(MyLssGwCommunicator*) -- 537: persist.sys.pgps.config=[0], not allow to send cell ids or wlan apn to server!
I/AGNSSCONTROL( 2738): void MyLssGwCommunicator::allowSendingCellIdsToServer(bool) -- 161: allowSendingCellIdsToServer allow = 0
E/Lss-gw  ( 2738): AllowSendingCellIdsToServer could not remove file. Error 2
I/AGNSSCONTROL( 2738): static void* PACommMgr::RequestAssistance(void*) -- 595: Send RequestAssistance times: 0
I/AGNSSCONTROL( 2738): static void* PACommMgr::RequestAssistance(void*) -- 621: current_time:1448458854602, wifi_time:1448458053676
I/AGNSSCONTROL( 2738): static void* PACommMgr::RequestAssistance(void*) -- 630: mac:c0:ff:d4:d3:aa:48
I/AGNSSCONTROL( 2738): static void* PACommMgr::RequestAssistance(void*) -- 630: mac:c2:ff:d4:d3:aa:48
I/AGNSSCONTROL( 2738): static void* PACommMgr::RequestAssistance(void*) -- 630: mac:38:f8:89:11:e9:11
I/AGNSSCONTROL( 2738): static void* PACommMgr::RequestAssistance(void*) -- 630: mac:06:7c:34:12:7f:81
,I/AGNSSCONTROL( 2738): static void* PACommMgr::RequestAssistance(void*) -- 630: mac:
I/AGNSSCONTROL( 2738): static void* PACommMgr::RequestAssistance(void*) -- 634: MAC ADDRESS is empty, so continue
I/AGNSSCONTROL( 2738): static void* PACommMgr::RequestAssistance(void*) -- 674: WIFI MAC ADDRESS COUNT:4
I/AGNSSCONTROL( 2738): static void* PACommMgr::RequestAssistance(void*) -- 686: Request using wifi, flag:1
I/AGNSSCONTROL( 2738): int MyLssGwCommunicator::sendRequestWithWlanInfo(EPH_TYPE, unsigned char*, int, bool) -- 73: sendRequestWithWlanInfo called, wlanLen:24
,W/Lss     ( 8535): Ephemeris estimate for SV 6 is too old. It was generated at 626975100 (sec)
W/Lss     ( 8535): Recalculating ephemeris estimate
,E/GlonassOrbitPredictor( 8535): initialize: prediction disabled for gnss=2, svId=7, toe=[TOC](4,1424,58500), gps_secs=1132492517.000000
E/Lss     ( 8535): Initializing predictor with ephemeris failed (5)
,E/Lss     ( 8535): Unable to open cell info file /data/gnss/pgps/cell_info.dat
E/Lss     ( 8535): No reference location.
W/Lss     ( 8535): Cannot calculate visible satellites. Returning all odd satellite ids
,I/AGNSSCONTROL( 2738): static void* PACommMgr::RequestAssistance(void*) -- 790: Received 3130 bytes of data
I/AGNSSCONTROL( 2738): static void* PACommMgr::RequestAssistance(void*) -- 830: Decode msg to pdu
,I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectGPSAssistance(SUPL_GPS_ASSISTANCE_DATA*) -- 1001: pstGpsAssistanceData->field_valid = 378
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectRefTime(SUPL_GPS_ASSISTANCE_DATA*) -- 1073: gpsTime.gpsWeek:848, gpsTime.gpsTOW23b:3855875, nTOWassist:0
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectIonospheric(SUPL_GPS_ASSISTANCE_DATA*) -- 1204: SUPL_IONOSPHERE_STRU size 8
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectUTCModel(SUPL_GPS_ASSISTANCE_DATA*) -- 1253: SUPL_UTC_PARAMETER_STRU size 20
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:1, acc:0, iode2:27, iode3:27, m0:-2048846223.000000, delta_n:15057.000000, ecc:128762451.000000, ek:0.000000, sqrt_a:2702003969.000000, omega_0:721972697.000000, i0:643643818.000000, omega:-1510731911.000000, omega_dot:-23038.000000, i_dot:1475.000000
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:1112.000000, cus:3097.000000, crc:8167.000000, crs:1309.000000, cic:57.000000, cis:-137.000000, group_delay:-44.000000, af0:1281236.000000, af1:8.000000, af2:0.000000, aodc:27, health:0, toc:19350, toe:19350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:27
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:5, acc:0, iode2:54, iode3:54, m0:-938092045.000000, delta_n:13998.000000, ecc:1845130.000000, ek:0.000000, sqrt_a:2701958566.000000, omega_0:744591534.000000, i0:658091053.000000, omega:2054953038.000000, omega_dot:-23109.000000, i_dot:1347.000000
,I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:1120.000000, cus:3242.000000, crc:8442.000000, crs:1192.000000, cic:34.000000, cis:12.000000, group_delay:9.000000, af0:217523.000000, af1:58.000000, af2:0.000000, aodc:54, health:0, toc:19350, toe:19350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:7, acc:0, iode2:125, iode3:125, m0:-625940.000000, delta_n:11863.000000, ecc:13295923.000000, ek:0.000000, sqrt_a:2701976974.000000, omega_0:26880780.000000, i0:657365852.000000, omega:-1122215097.000000, omega_dot:-21741.000000, i_dot:1009.000000
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-1929.000000, cus:6843.000000, crc:4348.000000, crs:-2131.000000, cic:-9.000000, cis:3.000000, group_delay:10.000000, af0:-29673.000000, af1:-12.000000, af2:0.000000, aodc:125, health:0, toc:19350, toe:19350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:11, acc:0, iode2:87, iode3:87, m0:1120250016.000000, delta_n:11067.000000, ecc:47781237.000000, ek:0.000000, sqrt_a:2701956100.000000, omega_0:-651432986.000000, i0:676822942.000000, omega:436419811.000000, omega_dot:-22617.000000, i_dot:-1081.000000
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-3793.000000, cus:2583.000000, crc:9611.000000, crs:-4296.000000, cic:-61.000000, cis:68.000000, group_delay:-27.000000, af0:747915.000000, af1:27.000000, af2:0.000000, aodc:87, health:0, toc:19350, toe:19350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:13, acc:1, iode2:99, iode3:99, m0:-982641478.000000, delta_n:11283.000000, ecc:71805057.000000, ek:0.000000, sqrt_a:2702022544.000000, omega_0:-2065101252.000000, i0:660132415.000000, omega:-1332103068.000000, omega_dot:-21692.000000, i_dot:-406.000000
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:3401.000000, cus:6980.000000, crc:4275.000000, crs:3929.000000, cic:104.000000, cis:91.000000, group_delay:-20.000000, af0:41763.000000, af1:-21.000000, af2:0.000000, aodc:99, health:0, toc:19350, toe:19350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:15, acc:0, iode2:106, iode3:106, m0:-274724199.000000, delta_n:11033.000000, ecc:70536679.000000, ek:0.000000, sqrt_a:2702004229.000000, omega_0:-638624156.000000, i0:677193255.000000, omega:214407309.000000, omega_dot:-22856.000000, i_dot:-1066.000000
,I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-3910.000000, cus:2399.000000, crc:9795.000000, crs:-4545.000000, cic:86.000000, cis:40.000000, group_delay:-22.000000, af0:-135779.000000, af1:31.000000, af2:0.000000, aodc:106, health:0, toc:19350, toe:19350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:17, acc:0, iode2:37, iode3:37, m0:108753506.000000, delta_n:16393.000000, ecc:140801145.000000, ek:0.000000, sqrt_a:2701990286.000000, omega_0:1444104849.000000, i0:632082741.000000, omega:-1318312126.000000, omega_dot:-25054.000000, i_dot:-2129.000000
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-1041.000000, cus:3872.000000, crc:7178.000000, crs:-1235.000000, cic:-88.000000, cis:69.000000, group_delay:-24.000000, af0:980103.000000, af1:33.000000, af2:0.000000, aodc:37, health:0, toc:19349, toe:19349, status:0, code_on_L2:1, fit_interval_flag:0, aodo:12
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:19, acc:0, iode2:20, iode3:20, m0:-1432231134.000000, delta_n:15906.000000, ecc:43167035.000000, ek:0.000000, sqrt_a:2702002074.000000, omega_0:1408495385.000000, i0:632893504.000000, omega:875045855.000000, omega_dot:-23845.000000, i_dot:-1653.000000
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-1119.000000, cus:3495.000000, crc:7464.000000, crs:-1298.000000, cic:29.000000, cis:44.000000, group_delay:-18.000000, af0:802403.000000, af1:25.000000, af2:0.000000, aodc:20, health:0, toc:19350, toe:19350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:24
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:21, acc:0, iode2:24, iode3:24, m0:-222683946.000000, delta_n:16442.000000, ecc:68749399.000000, ek:0.000000, sqrt_a:2702003623.000000, omega_0:1444677100.000000, i0:630603227.000000, omega:-1400775004.000000, omega_dot:-24715.000000, i_dot:-2080.000000
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-1215.000000, cus:3679.000000, crc:7215.000000, crs:-1387.000000, cic:-19.000000, cis:25.000000, group_delay:-38.000000, af0:888578.000000, af1:32.000000, af2:0.000000, aodc:24, health:0, toc:19349, toe:19349, status:0, code_on_L2:1, fit_interval_flag:0, aodo:12
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:23, acc:0, iode2:99, iode3:99, m0:2082095639.000000, delta_n:13658.000000, ecc:32378121.000000, ek:0.000000, sqrt_a:2701996181.000000, omega_0:-1414912171.000000, i0:650384611.000000, omega:204677488.000000, omega_dot:-24043.000000, i_dot:1085.000000
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:3154.000000, cus:832.000000, crc:11082.000000, crs:3593.000000, cic:21.000000, cis:-43.000000, group_delay:6.000000, af0:-18105.000000, af1:-4.000000, af2:0.000000, aodc:99, health:0, toc:19350, toe:19350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:25, acc:0, iode2:92, iode3:92, m0:506386729.000000, delta_n:12998.000000, ecc:3656506.000000, ek:0.000000, sqrt_a:2702008566.000000, omega_0:-688696924.000000, i0:656582558.000000, omega:-235865696.000000, omega_dot:-23699.000000, i_dot:-1029.000000
,I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-3948.000000, cus:1758.000000, crc:10086.000000, crs:-4552.000000, cic:18.000000, cis:11.000000, group_delay:16.000000, af0:-295037.000000, af1:-142.000000, af2:0.000000, aodc:92, health:0, toc:19350, toe:19350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:27, acc:0, iode2:44, iode3:44, m0:-419056271.000000, delta_n:11197.000000, ecc:171722530.000000, ek:0.000000, sqrt_a:2702024564.000000, omega_0:-635094368.000000, i0:676278827.000000, omega:-1125596568.000000, omega_dot:-23382.000000, i_dot:-614.000000
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-3210.000000, cus:2964.000000, crc:9381.000000, crs:-3675.000000, cic:-139.000000, cis:70.000000, group_delay:-24.000000, af0:1039163.000000, af1:24.000000, af2:0.000000, aodc:44, health:0, toc:19350, toe:19350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:29, acc:0, iode2:29, iode3:29, m0:1360430000.000000, delta_n:13619.000000, ecc:14381326.000000, ek:0.000000, sqrt_a:2702008080.000000, omega_0:-1352844560.000000, i0:652148396.000000, omega:-2140585158.000000, omega_dot:-24021.000000, i_dot:679.000000
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:2367.000000, cus:755.000000, crc:11179.000000, crs:2683.000000, cic:-6.000000, cis:30.000000, group_delay:7.000000, af0:133245.000000, af1:48.000000, af2:0.000000, aodc:29, health:0, toc:19350, toe:19350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:31, acc:0, iode2:58, iode3:58, m0:1686317703.000000, delta_n:13995.000000, ecc:97628833.000000, ek:0.000000, sqrt_a:2701996350.000000, omega_0:1516621803.000000, i0:647076903.000000, omega:124799425.000000, omega_dot:-22772.000000, i_dot:-2265.000000
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-1352.000000, cus:4530.000000, crc:6750.000000, crs:-1497.000000, cic:-121.000000, cis:0.000000, group_delay:-7.000000, af0:60189.000000, af1:105.000000, af2:0.000000, aodc:58, health:0, toc:19350, toe:19350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectAlmanac(SUPL_GPS_ASSISTANCE_DATA*) -- 1535: remainder: 80
W/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 969: pstGanssAsstData is NULL
,W/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 978: pstAddlAsstData is NULL
I/AGNSSCONTROL( 2738): static void* PACommMgr::RequestAssistance(void*) -- 892: HandleGanssAsstData called
W/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 960: pstGpsAssistanceData is NULL
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectGANSSAssistance(SUPL_GANSS_ASSISTANCE_DATA*) -- 1702: pstGanssAsstData->field_valid = 1
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectGANSSAssistance(SUPL_GANSS_ASSISTANCE_DATA*) -- 1705: ganss inject ref time
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1747: pstGanssGenAsstData->field_valid = 106656
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1751: ganss inject timemodel list
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1761: ganss inject navmodel
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:0, ucSVHealth:3, usIod:67, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:1, ucSVHealth:3, usIod:67, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:2, ucSVHealth:3, usIod:67, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:3, ucSVHealth:3, usIod:67, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:4, ucSVHealth:3, usIod:67, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:5, ucSVHealth:3, usIod:67, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
,I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:7, ucSVHealth:3, usIod:67, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:8, ucSVHealth:3, usIod:67, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:9, ucSVHealth:3, usIod:67, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:10, ucSVHealth:3, usIod:67, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:11, ucSVHealth:4, usIod:67, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:12, ucSVHealth:3, usIod:67, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:13, ucSVHealth:3, usIod:67, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:14, ucSVHealth:5, usIod:67, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:15, ucSVHealth:3, usIod:67, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:17, ucSVHealth:3, usIod:67, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
,I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:18, ucSVHealth:3, usIod:67, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:19, ucSVHealth:4, usIod:67, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:20, ucSVHealth:3, usIod:67, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:21, ucSVHealth:3, usIod:67, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:22, ucSVHealth:3, usIod:67, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:23, ucSVHealth:3, usIod:67, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2147: SUPL_GANSS_EPHEMERIS_MODEL_STRU size 11016
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1791: ganss inject alm
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1801: ganss inject addl utc model
I/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1806: ganss inject auxi info
,W/AGNSSCONTROL( 2738): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 978: pstAddlAsstData is NULL
,I/AGNSSCONTROL( 2738): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000651
,I/AGNSSCONTROL( 2738): virtual void CtrlFSMWaitState::PGPSInjectRefTime(CtrlFSM&) -- 646: PGPSInjectRefTime cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2738): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000655
I/AGNSSCONTROL( 2738): virtual void CtrlFSMWaitState::PGPSInjectIonospheric(CtrlFSM&) -- 688: PGPSInjectIonospheric cmd received by CtrlFSMWaitState
,I/AGNSSCONTROL( 2738): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000656
I/AGNSSCONTROL( 2738): virtual void CtrlFSMWaitState::PGPSInjectUTCModel(CtrlFSM&) -- 709: PGPSInjectUTCModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2738): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000654
,I/AGNSSCONTROL( 2738): virtual void CtrlFSMWaitState::PGPSInjectNavModel(CtrlFSM&) -- 751: PGPSInjectNavModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2738): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000657
,I/AGNSSCONTROL( 2738): virtual void CtrlFSMWaitState::PGPSInjectAlmanac(CtrlFSM&) -- 772: PGPSInjectAlmanac cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2738): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000659
,I/AGNSSCONTROL( 2738): virtual void CtrlFSMWaitState::PGPSInjectRTIData(CtrlFSM&) -- 814: PGPSInjectRTIData cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2738): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x0000065a
,I/AGNSSCONTROL( 2738): virtual void CtrlFSMWaitState::PGPSInjectGANSSRefTime(CtrlFSM&) -- 821: PGPSInjectGANSSRefTime cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2738): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x0000065f
,I/AGNSSCONTROL( 2738): virtual void CtrlFSMWaitState::PGPSInjectGANSSTimeModel(CtrlFSM&) -- 856: PGPSInjectGANSSTimeModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2738): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000661
I/AGNSSCONTROL( 2738): virtual void CtrlFSMWaitState::PGPSInjectGANSSNavModel(CtrlFSM&) -- 870: PGPSInjectGANSSNavModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2738): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000667
I/AGNSSCONTROL( 2738): virtual void CtrlFSMWaitState::PGPSInjectGANSSAlmanac(CtrlFSM&) -- 912: PGPSInjectGANSSAlmanac cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2738): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000669
I/AGNSSCONTROL( 2738): virtual void CtrlFSMWaitState::PGPSInjectGANSSAddlUTCModel(CtrlFSM&) -- 926: PGPSInjectGANSSAddlUTCModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2738): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x0000066a
I/AGNSSCONTROL( 2738): virtual void CtrlFSMWaitState::PGPSInjectGANSSAuxi(CtrlFSM&) -- 933: PGPSInjectGANSSAuxi cmd received by CtrlFSMWaitState
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 53
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=73 dispatchEvent: HEART-BEAT-ACK: 53
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,W/bt-btif ( 6965): info:x10
,W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btm  ( 6965): sec_bd_name = 
W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btif ( 6965): DISCOVERY_COMP_EVT slot id:25, failed to find channle,                                       status:1, scn:0
E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): invalid rfc slot id: 25
W/bt-btif ( 6965): invalid rfc slot id: 25
I/BTConnectToThread( 6900): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 6900): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 6900): 2015-11-25T13:41:20.528Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:41:20.528Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:41:20.530Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6900): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 54
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=74 dispatchEvent: HEART-BEAT-ACK: 54
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
,I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,E/bt-l2cap( 6965): L2CAP got conn_comp in bad state: 5  status: 0x15
,W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 6900): 2015-11-25T13:41:25.531Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:41:25.532Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 6900): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/jxcore-log( 6900): 2015-11-25T13:41:30.537Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:41:30.538Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:41:30.538Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:41:30.539Z SendDataConnector.js: do connect now
I/jxcore-log( 6900): 
,I/        ( 6900): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,I/BTConnectToThread( 6900): Starting to connect
W/BluetoothAdapter( 6900): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 6900): Connecting to G4-1, at F8:95:C7:87:3C:51
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 55
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=75 dispatchEvent: HEART-BEAT-ACK: 55
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/        ( 6900): Cleared service requests
,I/        ( 6900): Starting peer discovery failed, error code 0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btm  ( 6965): sec_bd_name = 
W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b0983c rs_disc_pending=0
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b0983c rs_disc_pending=1
W/bt-btif ( 6965): bta_dm_check_av:0
,W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b0983c rs_disc_pending=1
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 56
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=76 dispatchEvent: HEART-BEAT-ACK: 56
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,I/ActivityManager( 2937): filter receiver for action = android.bluetooth.device.action.ACL_CONNECTED
,I/BTConnectionReceiver( 8017): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=G4-1, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8017): Bluetooth Device Name: G4-1
,E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b0983c rs_disc_pending=1
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b082ac rs_disc_pending=0
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 57
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=77 dispatchEvent: HEART-BEAT-ACK: 57
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 58
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=78 dispatchEvent: HEART-BEAT-ACK: 58
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b082ac rs_disc_pending=1
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b0983c rs_disc_pending=0
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/BtConnection( 6900): connectionTimeoutTimer
I/CONNEC  ( 6900): Error: Cancelled
E/bt-btif ( 6965): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:26, channel:-1
I/BTConnectToThread( 6900): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 6900): 2015-11-25T13:42:30.550Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:42:30.551Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:42:30.555Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:42:30.560Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 6900): 
I/jxcore-log( 6900): ---- round done--------
I/jxcore-log( 6900): 
I/jxcore-log( 6900): ---- gotta redo : F8:95:C7:87:3C:51, try count now: 1
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): do fake peer & start
I/jxcore-log( 6900): 
I/jxcore-log( 6900): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:42:30.561Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:42:30.561Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:42:30.561Z SendDataConnector.js: do connect now
I/jxcore-log( 6900): 
,I/        ( 6900): Selected device address: 08:EC:A9:50:75:41, name: null
,I/BTConnectToThread( 6900): Starting to connect
W/BluetoothAdapter( 6900): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 6900): Connecting to null, at 08:EC:A9:50:75:41
,I/CONNEC  ( 6900): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/bt-btif ( 6965): DISCOVERY_COMP_EVT slot id:27, failed to find channle,                                       status:2, scn:-1291544406
W/bt-btif ( 6965): invalid rfc slot id: 27
,I/BTConnectToThread( 6900): socket connect failed: java.io.IOException: socket closed
I/jxcore-log( 6900): 2015-11-25T13:42:30.566Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:42:30.566Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:42:30.566Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6900): 
I/CONNEC  ( 6900): Error: java.io.IOException: socket closed
W/jxcore-log( 6900): $$jxcore_callback_36 wasn't registered
W/jxcore-log( 6900): 
,I/chromium( 6900): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F8:95:C7:87:3C:51 done with result: Connection to F8:95:C7:87:3C:51 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/jxcore-log( 6900): 2015-11-25T13:42:35.569Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:42:35.571Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 6900): 
,E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b0983c rs_disc_pending=1
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 59
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=79 dispatchEvent: HEART-BEAT-ACK: 59
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b0983c rs_disc_pending=0
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,I/        ( 6900): Cleared service requests
,I/        ( 6900): Starting peer discovery failed, error code 0
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b0983c rs_disc_pending=0
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/jxcore-log( 6900): 2015-11-25T13:42:40.579Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:42:40.580Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:42:40.581Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:42:40.581Z SendDataConnector.js: do connect now
I/jxcore-log( 6900): 
,I/        ( 6900): Selected device address: 08:EC:A9:50:75:41, name: null
,I/BTConnectToThread( 6900): Starting to connect
W/BluetoothAdapter( 6900): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 6900): Connecting to null, at 08:EC:A9:50:75:41
,E/bt-btif ( 6965): DISCOVERY_COMP_EVT slot id:28, failed to find channle,                                       status:2, scn:-1291544406
W/bt-btif ( 6965): invalid rfc slot id: 28
I/BTConnectToThread( 6900): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 6900): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 6900): 2015-11-25T13:42:40.597Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:42:40.598Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:42:40.598Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:42:45.599Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:42:45.600Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 6900): 
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/jxcore-log( 6900): 2015-11-25T13:42:50.605Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:42:50.606Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:42:50.606Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:42:50.607Z SendDataConnector.js: do connect now
I/jxcore-log( 6900): 
,I/        ( 6900): Selected device address: 08:EC:A9:50:75:41, name: null
,I/BTConnectToThread( 6900): Starting to connect
W/BluetoothAdapter( 6900): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 6900): Connecting to null, at 08:EC:A9:50:75:41
,E/bt-btif ( 6965): DISCOVERY_COMP_EVT slot id:29, failed to find channle,                                       status:2, scn:-1291544406
W/bt-btif ( 6965): invalid rfc slot id: 29
,I/BTConnectToThread( 6900): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 6900): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 6900): 2015-11-25T13:42:50.623Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:42:50.623Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:42:50.624Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6900): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 60
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=80 dispatchEvent: HEART-BEAT-ACK: 60
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-sdp  ( 6965): SDP - Rcvd conn cnf with error: 0xeeee  CID 0x45
E/bt-btif ( 6965): DISCOVERY_COMP_EVT slot id:26, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 6965): invalid rfc slot id: 26
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 6900): 2015-11-25T13:42:55.624Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:42:55.625Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 6900): 
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,I/ActivityManager( 2937): filter receiver for action = android.bluetooth.device.action.ACL_DISCONNECTED
,I/BTConnectionReceiver( 8017): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=G4-1, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8017): Bluetooth Device Name: G4-1
,I/DeviceStatsManager( 3825):  uid:1002 pid:6965 flags:1 tag:bluedroid_timer wakeup time:611673
,I/jxcore-log( 6900): 2015-11-25T13:43:00.630Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:43:00.631Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:43:00.632Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:43:00.632Z SendDataConnector.js: do connect now
I/jxcore-log( 6900): 
,I/        ( 6900): Selected device address: 08:EC:A9:50:75:41, name: null
,I/BTConnectToThread( 6900): Starting to connect
W/BluetoothAdapter( 6900): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 6900): Connecting to null, at 08:EC:A9:50:75:41
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 61
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=81 dispatchEvent: HEART-BEAT-ACK: 61
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b0983c rs_disc_pending=0
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 6965): SDP - Rcvd conn cnf with error: 0x1f  CID 0x4f
E/bt-btif ( 6965): DISCOVERY_COMP_EVT slot id:30, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 6965): invalid rfc slot id: 30
I/BTConnectToThread( 6900): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 6900): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 6900): 2015-11-25T13:43:09.502Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:43:09.503Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:43:09.504Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6900): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/DeviceStatsManager( 3825):  uid:1002 pid:6965 flags:1 tag:bluedroid_timer wakeup time:622686
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 6965): info:x10
,W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 6900): 2015-11-25T13:43:14.505Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:43:14.506Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 6900): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/DeviceStatsManager( 3825):  uid:1002 pid:6965 flags:1 tag:bluedroid_timer wakeup time:625695
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/jxcore-log( 6900): 2015-11-25T13:43:19.510Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:43:19.511Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:43:19.512Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:43:19.512Z SendDataConnector.js: do connect now
I/jxcore-log( 6900): 
,I/        ( 6900): Selected device address: 08:EC:A9:50:75:41, name: null
,I/BTConnectToThread( 6900): Starting to connect
W/BluetoothAdapter( 6900): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 6900): Connecting to null, at 08:EC:A9:50:75:41
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 62
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=82 dispatchEvent: HEART-BEAT-ACK: 62
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-sdp  ( 6965): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 6965): DISCOVERY_COMP_EVT slot id:31, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 6965): invalid rfc slot id: 31
,I/BTConnectToThread( 6900): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 6900): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 6900): 2015-11-25T13:43:31.106Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:43:31.107Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:43:31.112Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:43:31.114Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): ---- round done--------
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): ---- gotta redo : 08:EC:A9:50:75:41, try count now: 1
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): do fake peer & start
I/jxcore-log( 6900): 
I/jxcore-log( 6900): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:43:31.119Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:43:31.120Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:43:31.120Z SendDataConnector.js: do connect now
I/jxcore-log( 6900): 
,I/        ( 6900): Selected device address: 34:FC:EF:11:B1:66, name: Nexus 5
,I/BTConnectToThread( 6900): Starting to connect
W/BluetoothAdapter( 6900): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 6900): Connecting to Nexus 5, at 34:FC:EF:11:B1:66
,I/chromium( 6900): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 08:EC:A9:50:75:41 done with result: Connection to 08:EC:A9:50:75:41 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 63
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=83 dispatchEvent: HEART-BEAT-ACK: 63
E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/        ( 6900): Cleared service requests
,I/        ( 6900): Starting peer discovery failed, error code 0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 64
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=84 dispatchEvent: HEART-BEAT-ACK: 64
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b0910c rs_disc_pending=0
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,W/bt-btm  ( 6965): sec_bd_name = 
W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 65
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=85 dispatchEvent: HEART-BEAT-ACK: 65
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,W/bt-btif ( 6965): info:x10
,W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/HwLauncher( 3936): Model  onReceive intent=Intent { act=android.intent.action.TIME_TICK flg=0x50000014 (has extras) }
,I/TimeManager( 3472): receiver action = android.intent.action.TIME_TICK
,I/TimeManager( 3472): hand message 1
I/TimeManager( 3472): notify time change. size = 2
I/TimeLayout( 3472): time = 14:44
I/TimeLayout( 3472): updateDate date = 11/25/2015
I/TimeLayout( 3472): weekDay = Wednesday
,I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/EventLogService( 5839): Aggregate from 1448457251793 (log), 1448457251793 (data)
,I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5839): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PhenotypeFlagCommitter( 3984): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 3984): Using platform SSLCertificateSocketFactory
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/System  ( 3984): core_booster, getBoosterConfig = false
,I/System  ( 3984): core_booster, getBoosterConfig = false
,W/Uploader( 3984):  no longer exists, so no auth token.
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 6965): SDP - Rcvd conn cnf with error: 0x22  CID 0x41
E/bt-btif ( 6965): DISCOVERY_COMP_EVT slot id:32, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 6965): invalid rfc slot id: 32
I/BTConnectToThread( 6900): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 6900): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 6900): 2015-11-25T13:44:19.831Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:44:19.833Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:44:19.833Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6900): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 66
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=86 dispatchEvent: HEART-BEAT-ACK: 66
E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/jxcore-log( 6900): 2015-11-25T13:44:24.835Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:44:24.836Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 6900): 
,E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b09a08 rs_disc_pending=0
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/jxcore-log( 6900): 2015-11-25T13:44:29.841Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:44:29.842Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:44:29.842Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:44:29.842Z SendDataConnector.js: do connect now
I/jxcore-log( 6900): 
,I/        ( 6900): Selected device address: 34:FC:EF:11:B1:66, name: Nexus 5
,I/BTConnectToThread( 6900): Starting to connect
W/BluetoothAdapter( 6900): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 6900): Connecting to Nexus 5, at 34:FC:EF:11:B1:66
,E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b09a08 rs_disc_pending=1
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 67
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=87 dispatchEvent: HEART-BEAT-ACK: 67
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/        ( 6900): Cleared service requests
,I/        ( 6900): Starting peer discovery failed, error code 0
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=0,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 68
E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=88 dispatchEvent: HEART-BEAT-ACK: 68
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 6965): info:x10
,W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b08f40 rs_disc_pending=0
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 69
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=89 dispatchEvent: HEART-BEAT-ACK: 69
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 70
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=90 dispatchEvent: HEART-BEAT-ACK: 70
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btif ( 6965): DISCOVERY_COMP_EVT slot id:33, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 6965): invalid rfc slot id: 33
,I/BTConnectToThread( 6900): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 6900): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 6900): 2015-11-25T13:45:29.594Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:45:29.595Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:45:29.596Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6900): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/jxcore-log( 6900): 2015-11-25T13:45:34.597Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:45:34.598Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 6900): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 71
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=91 dispatchEvent: HEART-BEAT-ACK: 71
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/        ( 6900): Cleared service requests
,I/        ( 6900): Starting peer discovery failed, error code 0
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 6900): 2015-11-25T13:45:39.603Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:45:39.604Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:45:39.604Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:45:39.605Z SendDataConnector.js: do connect now
I/jxcore-log( 6900): 
,I/        ( 6900): Selected device address: 34:FC:EF:11:B1:66, name: Nexus 5
,I/BTConnectToThread( 6900): Starting to connect
W/BluetoothAdapter( 6900): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 6900): Connecting to Nexus 5, at 34:FC:EF:11:B1:66
,W/bt-btif ( 6965): No ag scb for peer addr
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-sdp  ( 6965): SDP - Rcvd conn cnf with error: 0x22  CID 0x44
E/bt-btif ( 6965): DISCOVERY_COMP_EVT slot id:34, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 6965): invalid rfc slot id: 34
I/BTConnectToThread( 6900): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 6900): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 6900): 2015-11-25T13:45:49.002Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:45:49.003Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:45:49.003Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6900): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 72
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=92 dispatchEvent: HEART-BEAT-ACK: 72
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/jxcore-log( 6900): 2015-11-25T13:45:54.004Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:45:54.005Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 6900): 
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 6900): 2015-11-25T13:45:59.010Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:45:59.011Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:45:59.011Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:45:59.012Z SendDataConnector.js: do connect now
I/jxcore-log( 6900): 
,I/        ( 6900): Selected device address: 34:FC:EF:11:B1:66, name: Nexus 5
,I/BTConnectToThread( 6900): Starting to connect
W/BluetoothAdapter( 6900): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 6900): Connecting to Nexus 5, at 34:FC:EF:11:B1:66
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 73
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=93 dispatchEvent: HEART-BEAT-ACK: 73
E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 74
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=94 dispatchEvent: HEART-BEAT-ACK: 74
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 6965): info:x10
,W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 6965): tBTM_SEC_DEV:0xe3b08f40 rs_disc_pending=1
W/bt-btif ( 6965): bta_dm_check_av:0
W/bt-btif ( 6965): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 75
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=95 dispatchEvent: HEART-BEAT-ACK: 75
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/        ( 6900): Cleared service requests
,I/        ( 6900): Starting peer discovery failed, error code 0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-sdp  ( 6965): SDP - Rcvd conn cnf with error: 0x22  CID 0x49
E/bt-btif ( 6965): DISCOVERY_COMP_EVT slot id:35, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 6965): invalid rfc slot id: 35
I/BTConnectToThread( 6900): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 6900): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 6900): 2015-11-25T13:46:43.943Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:46:43.944Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:46:43.945Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6900): 
,W/bt-btif ( 6965): info:x10
I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/DeviceStatsManager( 3825):  uid:1002 pid:6965 flags:1 tag:bluedroid_timer wakeup time:834787
,I/jxcore-log( 6900): 2015-11-25T13:46:48.947Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:46:48.947Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 6900): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
W/bt-btif ( 6965): info:x10
,W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 76
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=96 dispatchEvent: HEART-BEAT-ACK: 76
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,E/bt-btm  ( 6965): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 6965): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/DeviceStatsManager( 3825):  uid:1002 pid:6965 flags:1 tag:bluedroid_timer wakeup time:837796
,I/jxcore-log( 6900): 2015-11-25T13:46:53.952Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:46:53.953Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:46:53.953Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:46:53.954Z SendDataConnector.js: do connect now
I/jxcore-log( 6900): 
,I/        ( 6900): Selected device address: 34:FC:EF:11:B1:66, name: Nexus 5
,I/BTConnectToThread( 6900): Starting to connect
W/BluetoothAdapter( 6900): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 6900): Connecting to Nexus 5, at 34:FC:EF:11:B1:66
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 77
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=97 dispatchEvent: HEART-BEAT-ACK: 77
E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 78
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=98 dispatchEvent: HEART-BEAT-ACK: 78
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 4085): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4085): BgPowerManagerService: mTimes = 389384 firstTime = 906569 firstmBatteryCapacity =2204
E/HwSystemManager( 4085): BgPowerManagerService: conusmPower = 1 result = 9 flag1 =false flag2 = false
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/wifi_log/wifi_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 79
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=99 dispatchEvent: HEART-BEAT-ACK: 79
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/        ( 6900): Cleared service requests
,I/        ( 6900): Starting peer discovery failed, error code 0
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 80
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=100 dispatchEvent: HEART-BEAT-ACK: 80
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 4085): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4085): BgPowerManagerService: mTimes = 0 firstTime = 1326030 firstmBatteryCapacity =2203
,I/BtConnection( 6900): connectionTimeoutTimer
E/bt-btif ( 6965): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:36, channel:-1
I/CONNEC  ( 6900): Error: Cancelled
I/BTConnectToThread( 6900): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 6900): 2015-11-25T13:47:53.964Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:47:53.965Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:47:53.970Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:47:53.973Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): ---- round done--------
I/jxcore-log( 6900): 
I/jxcore-log( 6900): ---- gotta redo : 34:FC:EF:11:B1:66, try count now: 1
I/jxcore-log( 6900): 
I/jxcore-log( 6900): do fake peer & start
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:47:53.975Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:47:53.976Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:47:53.976Z SendDataConnector.js: do connect now
I/jxcore-log( 6900): 
,I/        ( 6900): Selected device address: 08:EC:A9:50:76:27, name: null
,I/BTConnectToThread( 6900): Starting to connect
,W/BluetoothAdapter( 6900): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 6900): Connecting to null, at 08:EC:A9:50:76:27
I/CONNEC  ( 6900): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 6965): DISCOVERY_COMP_EVT slot id:37, failed to find channle,                                       status:2, scn:-1291544406
W/bt-btif ( 6965): invalid rfc slot id: 37
,I/BTConnectToThread( 6900): socket connect failed: java.io.IOException: socket closed
,I/jxcore-log( 6900): 2015-11-25T13:47:53.987Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:47:53.987Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:47:53.988Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6900): 
,I/CONNEC  ( 6900): Error: java.io.IOException: socket closed
,W/jxcore-log( 6900): $$jxcore_callback_56 wasn't registered
W/jxcore-log( 6900): 
,I/chromium( 6900): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 34:FC:EF:11:B1:66 done with result: Connection to 34:FC:EF:11:B1:66 failed", source: file:///android_asset/www/js/thali_main.js (63)
,E/bt-btif ( 6965): DISCOVERY_COMP_EVT slot id:36, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 6965): invalid rfc slot id: 36
,I/DeviceStatsManager( 3825):  uid:1002 pid:6965 flags:1 tag:bluedroid_timer wakeup time:898831
,I/jxcore-log( 6900): 2015-11-25T13:47:58.990Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:47:58.991Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:03.994Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:48:03.995Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:48:03.996Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:03.996Z SendDataConnector.js: do connect now
I/jxcore-log( 6900): 
,I/        ( 6900): Selected device address: 08:EC:A9:50:76:27, name: null
,I/BTConnectToThread( 6900): Starting to connect
W/BluetoothAdapter( 6900): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 6900): Connecting to null, at 08:EC:A9:50:76:27
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 81
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=101 dispatchEvent: HEART-BEAT-ACK: 81
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 82
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=102 dispatchEvent: HEART-BEAT-ACK: 82
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 6965): info:x10
W/bt-btif ( 6965): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 6965): aclStateChangeCallback: Device is NULL
,E/BTIF_SOCK( 6965): restart bluetooth for device exception
,E/BluetoothManagerService( 2937): MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED: 1
I/DeviceStatsManager( 3825):  uid:1002 pid:6965 flags:1 tag:bluedroid_timer wakeup time:916953
,I/HwSystemManager( 4085): HoldService:uid:1002 pid:6965 died
I/HwSystemManager( 4085): BgPowerManagerService:onProcessDied uid = 1002
I/HwSystemManager( 4085): HoldService:oldVersionKey:1002,6965
E/HsmCoreServiceImpl( 2937): onTransact in code is: 102
W/MediaProcessHandler( 2937): processOp uid 1002 is not concerned!
,I/ActivityManager( 2937): filter receiver for action = android.bluetooth.adapter.action.STATE_CHANGED
,E/BluetoothDevice( 3793): BT not enabled. Cannot get Bluetooth Class
,E/BluetoothDevice( 3793): BT not enabled. Cannot get Remote Device name
E/BluetoothDevice( 3793): BT not enabled. Cannot get Remote Device Alias
E/BluetoothDevice( 3793): BT not enabled. Cannot get Bluetooth Class
E/BluetoothDevice( 3793): BT not enabled. Cannot get Bluetooth Class
E/BluetoothDevice( 3793): BT not enabled. Cannot get Remote Device name
E/BluetoothDevice( 3793): BT not enabled. Cannot get Remote Device Alias
,W/View    ( 3472): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{51589be V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during layout: running second layout pass
,I/ActivityManager( 2937): filter receiver for action = android.bluetooth.adapter.action.STATE_CHANGED
,E/BluetoothManagerService( 2937): MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED: 2
,I/BTConnectToThread( 6900): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BTListenerThread( 6900): accept socket failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 6900): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/LISTEN  ( 6900): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BTListenerThread( 6900): Stopped
I/        ( 6900): StartBluetooth listener
,W/BluetoothAdapter( 6900): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothSocket( 6900): bindListen fail, reason: bluetooth is off
W/System.err( 6900): java.io.IOException: Error: -1
,W/System.err( 6900): 	at android.bluetooth.BluetoothAdapter.createNewRfcommSocketAndRecord(BluetoothAdapter.java:1261)
W/System.err( 6900): 	at android.bluetooth.BluetoothAdapter.listenUsingInsecureRfcommWithServiceRecord(BluetoothAdapter.java:1208)
W/System.err( 6900): 	at org.thaliproject.p2p.btconnectorlib.BTListenerThread.<init>(BTListenerThread.java:40)
W/System.err( 6900): 	at org.thaliproject.p2p.btconnectorlib.BTConnector_BtConnection.StartListening(BTConnector_BtConnection.java:93)
W/System.err( 6900): 	at org.thaliproject.p2p.btconnectorlib.BTConnector_BtConnection$6.run(BTConnector_BtConnection.java:237)
W/System.err( 6900): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6900): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6900): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6900): 	at android.app.ActivityThread.main(ActivityThread.java:5538)
W/System.err( 6900): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6900): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6900): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
W/System.err( 6900): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
,I/jxcore-log( 6900): 2015-11-25T13:48:22.465Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:48:22.465Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:48:22.465Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6900): 
,I/bluedroid( 8948): bt interface: [open_bluetooth_stack]
I/bluedroid( 8948): bt interface: [bluetooth__get_bluetooth_interface]
,I/BluetoothAdapterState( 8948): Entering OffState
,I/BluetoothServiceJni( 8948): OoO sJniCallbacksObj has init before init? 0
I/bluedroid( 8948): bt interface: [init]
,I/RadioStateMachine( 8948): Entering OffState
,I/bte_main( 8948): OoO log conf is : false
,I/bte_conf( 8948): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/BT_UTILS( 8948): onetrack,g_type=hi110x
I/bluedroid( 8948): bt interface: [get_profile_interface]: get_profile_interface socket
I/bluedroid( 8948): bt interface: [get_profile_interface]: get_profile_interface map_client
I/GKI_LINUX( 8948): gki_task_entry task_id=1 [BTIF] starting
W/bt-btif ( 8948): HAL bt_hal_cbacks->thread_evt_cb
,I/bluedroid( 8948): bt interface: [get_adapter_property]
I/bluedroid( 8948): bt interface: [get_adapter_property]
W/bt-btif ( 8948): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 8948): adapterPropertyChangedCallback with type:2 len:6
,W/bt-btif ( 8948): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 8948): adapterPropertyChangedCallback with type:1 len:7
,I/bluedroid( 8948): bt interface: [config_hci_snoop_log]
,I/BtGatt.JNI( 8948): classInitNative(L863): classInitNative: Success!
,I/BluetoothAdapterState( 8948): Bluetooth adapter state changed: 10-> 11
,I/ActivityManager( 2937): filter receiver for action = android.bluetooth.adapter.action.STATE_CHANGED
,I/BluetoothBondStateMachine( 8948): StableState(): Entering Off State
,I/BluetoothAdapterState( 8948): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/BluetoothHeadsetServiceJni( 8948): classInitNative: succeeds
,I/HeadsetPhoneState( 8948): getPhoneStateListener subId:1
,I/bluedroid( 8948): bt interface: [get_profile_interface]: get_profile_interface handsfree
,I/BluetoothAvrcpServiceJni( 8948): classInitNative: succeeds
,I/bluedroid( 8948): bt interface: [get_profile_interface]: get_profile_interface avrcp
,E/RemoteController( 8948): Cannot set synchronization mode on an unregistered RemoteController
,I/BluetoothA2dpServiceJni( 8948): classInitNative: succeeds
,I/bluedroid( 8948): bt interface: [get_profile_interface]: get_profile_interface a2dp
I/GKI_LINUX( 8948): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,I/BluetoothHidServiceJni( 8948): classInitNative: succeeds
,I/bluedroid( 8948): bt interface: [get_profile_interface]: get_profile_interface hidhost
,I/BluetoothHealthServiceJni( 8948): classInitNative: succeeds
,I/bluedroid( 8948): bt interface: [get_profile_interface]: get_profile_interface health
,I/BluetoothPanServiceJni( 8948): classInitNative(L105): succeeds
,I/bluedroid( 8948): bt interface: [get_profile_interface]: get_profile_interface pan
,I/bluedroid( 8948): bt interface: [get_profile_interface]: get_profile_interface gatt
,I/bluedroid( 8948): bt interface: [enable]
I/bluetooth-coex( 8948): coex_lock_init: coex_mutex init
I/GKI_LINUX( 8948): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 8948): btu_task pending for preload complete event
I/bt_hci_bdroid( 8948): init
,I/        ( 8948): [vendor/huawei_platform/connectivity/hisi/hisi_connectivity/bt/hal/src/bt_vendor_hisi.c: hisi_init 238][bt_vendor] bt vendor init
I/bluetooth-coex( 8948): bt_coex_init: bt_coex_init
I/        ( 8948): >>>>>g_vd.uart_fd:-1
I/bluetooth-coex( 8948): btcoex_socket_server: created socket fd 69, /data/misc/bluedroid/.coex_bt
I/bluetooth-coex( 8948): btcoex_send_msg: send bt_state(1) to wifi, sock_fd(70)
,I/wpa_supplicant( 6987): set current WIFI status to BT!
,I/bluetooth-coex( 8948): btcoex_socket_server: accept socket success
I/bluetooth-coex( 8948): set_bt_coex_mode_ext: WIFI_ACTIVE
,I/        ( 8948): [vendor/huawei_platform/connectivity/hisi/hisi_connectivity/bt/hal/src/bt_vendor_hisi.c: hw_config_set_bdaddr 142][bt_vendor] hw_config_set_bdaddr 582af7ed96be
,I/bt-btu  ( 8948): btu_task received preload complete event
,I/        ( 8948): BTE_InitTraceLevels -- TRC_HCI
I/        ( 8948): BTE_InitTraceLevels -- TRC_L2CAP
,I/        ( 8948): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 8948): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 8948): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 8948): BTE_InitTraceLevels -- TRC_A2D
I/        ( 8948): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 8948): BTE_InitTraceLevels -- TRC_BTM
I/        ( 8948): BTE_InitTraceLevels -- TRC_GAP
I/        ( 8948): BTE_InitTraceLevels -- TRC_PAN
I/        ( 8948): BTE_InitTraceLevels -- TRC_SDP
I/        ( 8948): BTE_InitTraceLevels -- TRC_GATT
I/        ( 8948): BTE_InitTraceLevels -- TRC_SMP
I/        ( 8948): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 8948): BTE_InitTraceLevels -- TRC_BTIF
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
W/bt-btif ( 8948):  bta_dm_sys_hw_cback with event: 1
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
E/bt-btm  ( 8948): BTM_SecRegister:p_cb_info->p_le_callback == 0xe3961b31 
E/bt-btm  ( 8948): BTM_SecRegister: btm_cb.api.p_le_callback = 0xe3961b31 
,E/bt-btif ( 8948): Calling BTA_HhEnable
E/bt-btif ( 8948): btif_storage_get_adapter_property service_mask:0x2140040
W/bt-btif ( 8948): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 8948): adapterPropertyChangedCallback with type:2 len:6
I/BluetoothAdapterProperties( 8948): adapterPropertyChangedCallback with type:1 len:7
,I/BluetoothAdapterProperties( 8948): adapterPropertyChangedCallback with type:7 len:4
,I/BluetoothAdapterProperties( 8948): adapterPropertyChangedCallback with type:9 len:4
I/BluetoothAdapterProperties( 8948): adapterPropertyChangedCallback with type:8 len:0
I/BluetoothAdapterProperties( 8948): adapterPropertyChangedCallback with type:3 len:48
,W/bt-btif ( 8948): bte_main_enable_lpm
W/bt-btm  ( 8948): BTM_SetDiscoverability
W/bt-btm  ( 8948): BTM_SetConnectability
W/bt-btm  ( 8948): BTM_SetDiscoverability
W/bt-btm  ( 8948): BTM_SetConnectability
W/bt-btif ( 8948): HAL bt_hal_cbacks->adapter_state_changed_cb
,I/bluedroid( 8948): bt interface: [set_adapter_property]
I/bluedroid( 8948): bt interface: [set_adapter_property]
W/bt-btif ( 8948): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterState( 8948): Bluetooth adapter state changed: 11-> 12
I/BluetoothAdapterProperties( 8948): adapterPropertyChangedCallback with type:7 len:4
,I/BT      ( 6900): Bluetooth DISABLED, stopping
I/        ( 6900): Stoping All
I/        ( 6900): Stopping services
I/        ( 6900): Stopping services
I/BluetoothAdapterState( 8948): Entering On State
W/bt-btm  ( 8948): BTM_SetDiscoverability
W/bt-btm  ( 8948): BTM_SetConnectability
W/bt-btif ( 8948): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 8948): adapterPropertyChangedCallback with type:9 len:4
I/art     ( 2324): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 264us total 40.084ms
,I/        ( 6900): Stop Bluetooth
I/        ( 6900): Stop Bluetooth
I/BT      ( 6900): Bluetooth enabled, re-starting
I/        ( 6900): Stoping All
I/        ( 6900): Stopping services
I/        ( 6900): Stop Bluetooth
I/        ( 6900): Starting All
I/        ( 6900): Stopping services
I/        ( 6900): Starting services address: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT9762","ra":"58:2A:F7:ED:96:BE"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@2e0538ae
I/        ( 6900): Stopping services
I/        ( 6900): Starting services address: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT9762","ra":"58:2A:F7:ED:96:BE"}
I/        ( 6900): Add local service :{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT9762","ra":"58:2A:F7:ED:96:BE"}, length : 80
I/        ( 6900): peerDiscoveryTimer timeout value:9877
I/        ( 6900): Stop Bluetooth
I/        ( 6900): StartBluetooth listener
,I/        ( 6900): StartBluetooth listener
,W/BluetoothAdapter( 6900): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 6900): Cleared local services
I/        ( 6900): Cleared service requests
I/        ( 6900): Stopping peer discovery failed, error code 0
I/        ( 6900): Adding local service failed, error code 0
I/        ( 6900): Cleared service requests
I/        ( 6900): Stopping peer discovery failed, error code 0
I/        ( 6900): Starting peer discovery failed, error code 0
,I/BTListenerThread( 6900): starting to listen
I/BTListenerThread( 6900): waiting to accept incoming Connection
,I/art     ( 2324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 185us total 47.385ms
,I/art     ( 2324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 190us total 22.091ms
,I/HwSystemManager( 4085): HoldService:uid:10043 pid:7398 died
I/HwSystemManager( 4085): HoldService:oldVersionKey:10043,7398
I/HwSystemManager( 4085): BgPowerManagerService:onProcessDied uid = 10043
E/HsmCoreServiceImpl( 2937): onTransact in code is: 102
I/MediaProcessHandler( 2937): processOp opType: 1, uid: 10043, pid: 7398
W/MediaProcessHandler( 2937): remove target not exist, maybe the UI process: uid: 10043, pid: 7398
,I/ActivityManager( 2937): filter receiver for action = android.bluetooth.adapter.action.STATE_CHANGED
,I/Telecom ( 3847): BluetoothPhoneService: handleMessage: request is null
,W/BluetoothAdapter( 8948): getBluetoothService() called with no BluetoothManagerCallback
,W/View    ( 3472): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{51589be V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during layout: running second layout pass
,W/View    ( 3472): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{51589be V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during second layout pass: posting in next frame
,W/View    ( 3472): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{51589be V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during second layout pass: posting in next frame
,I/bluedroid( 8948): bt interface: [set_adapter_property]
I/bluedroid( 8948): bt interface: [set_adapter_property]
W/bt-btif ( 8948): HAL bt_hal_cbacks->adapter_properties_cb
W/bt-btm  ( 8948): BTM_SetDiscoverability
I/BluetoothAdapterProperties( 8948): adapterPropertyChangedCallback with type:9 len:4
W/bt-btm  ( 8948): HAL bt_hal_cbacks->ad
W/bt-btif ( 8948): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 8948): adapterPropertyChangedCallback with type:7 len:4
,I/WB      ( 6900): We already were running, thus doing nothing
,W/BluetoothAdapter( 8948): getBluetoothService() called with no BluetoothManagerCallback
,W/BluetoothAdapter( 8948): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 8948): Accept thread started.
,I/jxcore-log( 6900): 2015-11-25T13:48:27.466Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:48:27.467Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 6900): 
,I/wpa_supplicant( 6987): set current WIFI status to BT!
,I/bluetooth-coex( 8948): btcoex_socket_server: accept socket success
I/bluetooth-coex( 8948): set_bt_coex_mode_ext: BT_COEX_CHANNEL, fist[47]last[73]afh_result[0]
,I/jxcore-log( 6900): 2015-11-25T13:48:32.472Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:48:32.473Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:48:32.474Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:48:32.474Z SendDataConnector.js: do connect now
I/jxcore-log( 6900): 
,I/        ( 6900): Selected device address: 08:EC:A9:50:76:27, name: null
,I/BTConnectToThread( 6900): Starting to connect
W/BluetoothAdapter( 6900): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 6900): Connecting to null, at 08:EC:A9:50:76:27
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 83
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=103 dispatchEvent: HEART-BEAT-ACK: 83
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-l2cap( 8948): l2cu_adjust_out_mps bad packet size: 0  will use MPS: 0
,W/bt-btm  ( 8948): sec_bd_name = 
W/bt-btif ( 8948): info:x10
W/bt-btif ( 8948): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 8948): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 8948): process_service_search_attr_rsp
,E/bt-btif ( 8948): DISCOVERY_COMP_EVT slot id:5, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 8948): invalid rfc slot id: 5
I/BTConnectToThread( 6900): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 6900): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 6900): 2015-11-25T13:48:37.044Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:37.045Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:48:37.046Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6900): 
,E/bt-btm  ( 8948): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 8948): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 8948): HAL bt_hal_cbacks->acl_state_changed_cb
E/BluetoothRemoteDevices( 8948): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 6900): 2015-11-25T13:48:42.046Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:48:42.047Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:47.053Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:48:47.053Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:48:47.054Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:48:47.054Z SendDataConnector.js: do connect now
I/jxcore-log( 6900): 
,I/        ( 6900): Selected device address: 08:EC:A9:50:76:27, name: null
,I/BTConnectToThread( 6900): Starting to connect
W/BluetoothAdapter( 6900): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 6900): Connecting to null, at 08:EC:A9:50:76:27
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 8948): info:x10
W/bt-btif ( 8948): HAL bt_hal_cbacks->acl_state_changed_cb
E/BluetoothRemoteDevices( 8948): aclStateChangeCallback: Device is NULL
,E/bt-l2cap( 8948): l2cu_adjust_out_mps bad packet size: 0  will use MPS: 0
,W/bt-sdp  ( 8948): process_service_search_attr_rsp
,E/bt-btif ( 8948): DISCOVERY_COMP_EVT slot id:6, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 8948): invalid rfc slot id: 6
I/BTConnectToThread( 6900): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 6900): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 6900): 2015-11-25T13:48:49.517Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:48:49.518Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:49.518Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6900): 
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btm  ( 8948): sec_bd_name = 
W/bt-btif ( 8948): info:x10
W/bt-btif ( 8948): HAL bt_hal_cbacks->acl_state_changed_cb
E/BluetoothRemoteDevices( 8948): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 8948): tBTM_SEC_DEV:0xe3b080e0 rs_disc_pending=0
W/bt-btif ( 8948): bta_dm_check_av:0
W/bt-btif ( 8948): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 8948): tBTM_SEC_DEV:0xe3b082ac rs_disc_pending=1
W/bt-btif ( 8948): bta_dm_check_av:0
W/bt-btif ( 8948): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 84
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=104 dispatchEvent: HEART-BEAT-ACK: 84
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,E/bt-l2cap( 8948): l2cu_adjust_out_mps bad packet size: 0  will use MPS: 0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 8948): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 8948): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 8948): HAL bt_hal_cbacks->acl_state_changed_cb
E/BluetoothRemoteDevices( 8948): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 8948): HAL bt_hal_cbacks->remote_device_properties_cb
,W/bt-btif ( 8948): HAL bt_hal_cbacks->bond_state_changed_cb
,I/BluetoothBondStateMachine( 8948): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
E/bt-btif ( 8948): check_cod: remote_cod = 0x5a020c
,I/ActivityManager( 2937): filter receiver for action = android.bluetooth.device.action.BOND_STATE_CHANGED
,I/BluetoothBondStateMachine( 8948): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11,
I/BluetoothBondStateMachine( 8948): Entering PendingCommandState State
W/BluetoothEventManager( 3669): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 3669): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,W/bt-btif ( 8948): HAL bt_hal_cbacks->bond_state_changed_cb
I/BluetoothBondStateMachine( 8948): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
,I/ActivityManager( 2937): filter receiver for action = android.bluetooth.device.action.BOND_STATE_CHANGED
,I/BluetoothBondStateMachine( 8948): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
W/BluetoothEventManager( 3669): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 3669): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,I/BluetoothBondStateMachine( 8948): StableState(): Entering Off State
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file,
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-l2cap( 8948): l2cu_adjust_out_mps bad packet size: 0  will use MPS: 0
,E/bt-l2cap( 8948): l2cu_adjust_out_mps bad packet size: 0  will use MPS: 0
,W/bt-btif ( 8948): new conn_srvc id:26, app_id:255
,I/BTListenerThread( 6900): we got incoming connection
I/BTHandshakeSocketThread( 6900): Creating BTHandshakeSocketThread
I/BTListenerThread( 6900): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 6900): BTHandshakeSocketThread started
,I/jxcore-log( 6900): 2015-11-25T13:48:54.520Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:48:54.521Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 6900): 
,E/bt-btm  ( 8948): tBTM_SEC_DEV:0xe3b082ac rs_disc_pending=0
W/bt-btif ( 8948): bta_dm_check_av:0
W/bt-btif ( 8948): btif_dm_cback : unhandled event (14)
,E/bt-l2cap( 8948): l2cu_adjust_out_mps bad packet size: 0  will use MPS: 0
,I/BTListenerThread( 6900): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 6900): Got JSON from encryption:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 6900): MESSAGE_WRITE 80 bytes.
I/HS      ( 6900): Incoming connection Hand Shake finished for : LGE-LG-D802_PT4660
I/BTHandshakeSocketThread( 6900): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 6900): Starting the connected thread incoming : true, LGE-LG-D802_PT4660
I/BtToSocketBase( 6900): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 6900): Creating BTConnectedThread
I/BtConnectorHelper( 6900): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 6900): --DoOneRunRound started
,I/System  ( 6900): core_booster, getBoosterConfig = false
,I/BtToRequestSocket( 6900): LocalHost address: localhost/127.0.0.1, port: 43439
,I/BtToRequestSocket( 6900): --DoOneRunRound ended
,I/jxcore-log( 6900): 2015-11-25T13:48:54.754Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:55.212Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:55.216Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:55.251Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:55.286Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:55.312Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:55.318Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:55.364Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:55.403Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:55.408Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:55.451Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:55.490Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:55.529Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:55.563Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:55.567Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:55.639Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:55.671Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:55.682Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:55.755Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:55.761Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:55.764Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:55.838Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:55.844Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:55.892Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:55.917Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:55.970Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:55.973Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:55.977Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:56.021Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:56.029Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:56.108Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:56.120Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:56.131Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:56.153Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:56.200Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
,I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:56.204Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
,I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:56.207Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:56.254Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:56.258Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:56.355Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:56.360Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:56.397Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:56.404Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:56.442Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:56.445Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:56.450Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:56.475Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:56.532Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:56.576Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:56.581Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:48:56.603Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 6900): 
,W/bt-btif ( 8948): invalid rfc slot id: 1
I/BtToSocketBase( 6900): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 6900): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 6900): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT4660
I/BtToSocketBase( 6900): Stop ReceivingThread
I/BtToSocketBase( 6900): Stop SendingThread
I/BtToSocketBase( 6900): Close local in
I/BtToSocketBase( 6900): Close LocalOutputStream
,I/BtToSocketBase( 6900): Close localHostSocket
I/BtToSocketBase( 6900): Close bt in
I/BtToSocketBase( 6900): Close bt out
I/BtToSocketBase( 6900): Close bt socket
I/BtToSocketBase( 6900): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 6900): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 6900): 2015-11-25T13:48:56.711Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6900): 
,W/bt-rfcomm( 8948): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
,W/bt-rfcomm( 8948): RFCOMM_DisconnectInd LCID:0x43
,I/jxcore-log( 6900): 2015-11-25T13:48:59.525Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:48:59.526Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:48:59.527Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:48:59.527Z SendDataConnector.js: do connect now
I/jxcore-log( 6900): 
,I/        ( 6900): Selected device address: 08:EC:A9:50:76:27, name: null
,I/BTConnectToThread( 6900): Starting to connect
W/BluetoothAdapter( 6900): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 6900): Connecting to null, at 08:EC:A9:50:76:27
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 8948): tBTM_SEC_DEV:0xe3b082ac rs_disc_pending=1
W/bt-btif ( 8948): bta_dm_check_av:0
W/bt-btif ( 8948): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 8948): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 8948): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 8948): HAL bt_hal_cbacks->acl_state_changed_cb
,I/ActivityManager( 2937): filter receiver for action = android.bluetooth.device.action.ACL_DISCONNECTED
,I/BTConnectionReceiver( 8017): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=Thali Test's G2, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8017): Bluetooth Device Name: Thali Test's G2
,W/bt-btif ( 8948): info:x10
W/bt-btif ( 8948): HAL bt_hal_cbacks->acl_state_changed_cb
E/BluetoothRemoteDevices( 8948): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-l2cap( 8948): l2cu_adjust_out_mps bad packet size: 0  will use MPS: 0
,W/bt-sdp  ( 8948): process_service_search_attr_rsp
,E/bt-btif ( 8948): DISCOVERY_COMP_EVT slot id:8, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 8948): invalid rfc slot id: 8
I/BTConnectToThread( 6900): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 6900): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 6900): 2015-11-25T13:49:03.548Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:49:03.550Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:49:03.554Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:49:03.558Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 6900): 
I/jxcore-log( 6900): ---- round done--------
I/jxcore-log( 6900): 
I/jxcore-log( 6900): ---- gotta redo : 08:EC:A9:50:76:27, try count now: 1
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): do fake peer & start
I/jxcore-log( 6900): 
I/jxcore-log( 6900): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:49:03.560Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:49:03.561Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:49:03.561Z SendDataConnector.js: do connect now
I/jxcore-log( 6900): 
,I/        ( 6900): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/BTConnectToThread( 6900): Starting to connect
W/BluetoothAdapter( 6900): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 6900): Connecting to null, at E0:DB:10:14:E2:C0
,I/chromium( 6900): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 08:EC:A9:50:76:27 done with result: Connection to 08:EC:A9:50:76:27 failed", source: file:///android_asset/www/js/thali_main.js (63)
,E/bt-btm  ( 8948): tBTM_SEC_DEV:0xe3b080e0 rs_disc_pending=0
W/bt-btif ( 8948): bta_dm_check_av:0
W/bt-btif ( 8948): btif_dm_cback : unhandled event (14)
,W/bt-btm  ( 8948): sec_bd_name = 
W/bt-btif ( 8948): info:x10
W/bt-btif ( 8948): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 8948): aclStateChangeCallback: Device is NULL
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/bt-btm  ( 8948): tBTM_SEC_DEV:0xe3b080e0 rs_disc_pending=1
W/bt-btif ( 8948): bta_dm_check_av:0
W/bt-btif ( 8948): btif_dm_cback : unhandled event (14)
,E/bt-l2cap( 8948): l2cu_adjust_out_mps bad packet size: 0  will use MPS: 0
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 85
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=105 dispatchEvent: HEART-BEAT-ACK: 85
E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
W/bt-sdp  ( 8948): process_service_search_attr_rsp
E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,E/bt-btif ( 8948): DISCOVERY_COMP_EVT slot id:9, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 8948): invalid rfc slot id: 9
I/BTConnectToThread( 6900): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 6900): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 6900): 2015-11-25T13:49:06.262Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:49:06.263Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:49:06.263Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6900): 
,E/bt-btm  ( 8948): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 8948): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 8948): HAL bt_hal_cbacks->acl_state_changed_cb
E/BluetoothRemoteDevices( 8948): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 8948): tBTM_SEC_DEV:0xe3b08478 rs_disc_pending=0
W/bt-btif ( 8948): bta_dm_check_av:0
W/bt-btif ( 8948): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 8948): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 8948): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 8948): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 8948): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 6900): 2015-11-25T13:49:11.265Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:49:11.266Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:49:16.271Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:49:16.272Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:49:16.272Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:49:16.273Z SendDataConnector.js: do connect now
I/jxcore-log( 6900): 
,I/        ( 6900): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/BTConnectToThread( 6900): Starting to connect
W/BluetoothAdapter( 6900): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 6900): Connecting to null, at E0:DB:10:14:E2:C0
,I/jxcore-log( 6900): timeout now
I/jxcore-log( 6900): 
I/jxcore-log( 6900): dun
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): weAreDoneNow , resultArray.length: 0
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): done, now sending data to server
I/jxcore-log( 6900): 
I/jxcore-log( 6900): DBG, CoordinatorConnector sendData called
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): -- RESULT DATA {"name:":"HUAWEI-ALE-L21_PT9762","time":1000070,"result":"TIMEOUT","sendList":[{"connections":1,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:9D:93:0B","time":0,"result":"Fail"},{"connections":0,"name":"F8:CF:C5:D9:E5:61","time":0,"result":"Fail"},{"connections":0,"name":"80:01:84:8A:B3:68","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:1F:C9:5E","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"50:2E:6C:AC:21:50","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"B4:CE:F6:AB:A4:6A","time":0,"result":"Fail"},{"connections":0,"n
,I/jxcore-log( 6900): sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
I/jxcore-log( 6900): 
I/jxcore-log( 6900): Results list does not contain any items
I/jxcore-log( 6900): 
I/jxcore-log( 6900): sendList failed peers count : 7 [100 %]
I/jxcore-log( 6900): 
I/jxcore-log( 6900): - Peer ID : E0:DB:10:14:E2:C0, Tried : 1
I/jxcore-log( 6900): 
I/jxcore-log( 6900): - Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
I/jxcore-log( 6900): 
I/jxcore-log( 6900): - Peer ID : 34:FC:EF:11:AE:67, Tried : 1
I/jxcore-log( 6900): 
I/jxcore-log( 6900): - Peer ID : F8:95:C7:87:3C:51, Tried : 1
I/jxcore-log( 6900): 
I/jxcore-log( 6900): - Peer ID : 08:EC:A9:50:75:41, Tried : 1
I/jxcore-log( 6900): 
I/jxcore-log( 6900): - Peer ID : 34:FC:EF:11:B1:66, Tried : 1
I/jxcore-log( 6900): 
I/jxcore-log( 6900): - Peer ID : 08:EC:A9:50:76:27, Tried : 1
I/jxcore-log( 6900): 
I/jxcore-log( 6900): sendList never tried peers count : 13 [65 %]
I/jxcore-log( 6900): 
I/jxcore-log( 6900): - Peer ID : 7C:F9:0E:34:8A:A0
I/jxcore-log( 6900): 
I/jxcore-log( 6900): - Peer ID : F8:95:C7:87:85:54
I/jxcore-log( 6900): 
I/jxcore-log( 6900): - Peer ID : 34:FC:EF:9D:93:0B
I/jxcore-log( 6900): 
I/jxcore-log( 6900): - Peer ID : F8:CF:C5:D9:E5:61
I/jxcore-log( 6900): 
I/jxcore-log( 6900): - Peer ID : 80:01:84:8A:B3:68
I/jxcore-log( 6900): 
I/jxcore-log( 6900): - Peer ID : E0:DB:10:1F:C9:5E
I/jxcore-log( 6900): 
I/jxcore-log( 6900): - Peer ID : 44:80:EB:7B:5A:05
I/jxcore-log( 6900): 
I/jxcore-log( 6900): - Peer ID : 00:F4:6F:30:E0:6C
I/jxcore-log( 6900): 
I/jxcore-log( 6900): - Peer ID : 50:2E:6C:AC:21:50
I/jxcore-log( 6900): 
I/jxcore-log( 6900): - Peer ID : 58:3F:54:73:64:C0
I/jxcore-log( 6900): 
I/jxcore-log( 6900): - Peer ID : B0:C5:59:3F:75:69
I/jxcore-log( 6900): 
I/jxcore-log( 6900): - Peer ID : B4:CE:F6:AB:A4:6A
I/jxcore-log( 6900): 
I/jxcore-log( 6900): - Peer ID : F4:F1:E1:5C:3B:E2
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:49:16.565Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:49:16.565Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 6900): 
I/chromium( 6900): [INFO:CONSOLE(63)] "logCallback *** TIMEOUT ***", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6900): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 8948): info:x10
W/bt-btif ( 8948): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 8948): aclStateChangeCallback: Device is NULL
,E/bt-l2cap( 8948): l2cu_adjust_out_mps bad packet size: 0  will use MPS: 0
,W/bt-sdp  ( 8948): process_service_search_attr_rsp
,E/bt-btif ( 8948): DISCOVERY_COMP_EVT slot id:10, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 8948): invalid rfc slot id: 10
I/BTConnectToThread( 6900): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 6900): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 6900): 2015-11-25T13:49:17.380Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:49:17.381Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:49:17.382Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6900): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 86
E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=106 dispatchEvent: HEART-BEAT-ACK: 86
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,E/bt-btm  ( 8948): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 8948): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 8948): HAL bt_hal_cbacks->acl_state_changed_cb
E/BluetoothRemoteDevices( 8948): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 6900): 2015-11-25T13:49:22.382Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:49:22.383Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 6900): 
,I/        ( 6900): Cleared service requests
,I/        ( 6900): Starting peer discovery failed, error code 0
,I/jxcore-log( 6900): 2015-11-25T13:49:27.385Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:49:27.386Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:49:27.386Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:49:27.386Z SendDataConnector.js: do connect now
I/jxcore-log( 6900): 
,I/        ( 6900): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/BTConnectToThread( 6900): Starting to connect
W/BluetoothAdapter( 6900): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 6900): Connecting to null, at E0:DB:10:14:E2:C0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 8948): info:x10
W/bt-btif ( 8948): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 8948): aclStateChangeCallback: Device is NULL
,E/bt-l2cap( 8948): l2cu_adjust_out_mps bad packet size: 0  will use MPS: 0
,W/bt-sdp  ( 8948): process_service_search_attr_rsp
,E/bt-btif ( 8948): DISCOVERY_COMP_EVT slot id:11, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 8948): invalid rfc slot id: 11
I/BTConnectToThread( 6900): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 6900): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 6900): 2015-11-25T13:49:28.540Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:49:28.541Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:49:28.542Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6900): 
,E/bt-btm  ( 8948): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 8948): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 8948): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 8948): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 6900): 2015-11-25T13:49:33.543Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:49:33.544Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 6900): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 87
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=107 dispatchEvent: HEART-BEAT-ACK: 87
E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/jxcore-log( 6900): 2015-11-25T13:49:38.548Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:49:38.549Z SendDataConnector.js: Connect (retry count 3) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:49:38.549Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:49:38.550Z SendDataConnector.js: do connect now
I/jxcore-log( 6900): 
,I/        ( 6900): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/BTConnectToThread( 6900): Starting to connect
W/BluetoothAdapter( 6900): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 6900): Connecting to null, at E0:DB:10:14:E2:C0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 8948): info:x10
W/bt-btif ( 8948): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 8948): aclStateChangeCallback: Device is NULL
,E/bt-l2cap( 8948): l2cu_adjust_out_mps bad packet size: 0  will use MPS: 0
,W/bt-sdp  ( 8948): process_service_search_attr_rsp
,E/bt-btif ( 8948): DISCOVERY_COMP_EVT slot id:12, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 8948): invalid rfc slot id: 12
I/BTConnectToThread( 6900): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 6900): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 6900): 2015-11-25T13:49:40.197Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:49:40.198Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:49:40.198Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6900): 
,E/bt-btm  ( 8948): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 8948): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 8948): HAL bt_hal_cbacks->acl_state_changed_cb
E/BluetoothRemoteDevices( 8948): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 6900): 2015-11-25T13:49:45.200Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:49:45.201Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:49:50.205Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:49:50.206Z SendDataConnector.js: Connect (retry count 4) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:49:50.207Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:49:50.207Z SendDataConnector.js: do connect now
I/jxcore-log( 6900): 
,I/        ( 6900): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/BTConnectToThread( 6900): Starting to connect
W/BluetoothAdapter( 6900): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 6900): Connecting to null, at E0:DB:10:14:E2:C0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,W/bt-btif ( 8948): info:x10
W/bt-btif ( 8948): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 8948): aclStateChangeCallback: Device is NULL
,E/bt-l2cap( 8948): l2cu_adjust_out_mps bad packet size: 0  will use MPS: 0
,W/bt-sdp  ( 8948): process_service_search_attr_rsp
,E/bt-btif ( 8948): DISCOVERY_COMP_EVT slot id:13, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 8948): invalid rfc slot id: 13
I/BTConnectToThread( 6900): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 6900): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 6900): 2015-11-25T13:49:50.849Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 6900): 
I/jxcore-log( 6900): 2015-11-25T13:49:50.850Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:49:50.852Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:49:50.855Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 6900): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 88
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=108 dispatchEvent: HEART-BEAT-ACK: 88
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,E/bt-btm  ( 8948): btm_sec_disconnected - sec_state=6,ble_in_encryption=0
E/bt-btm  ( 8948): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 8948): HAL bt_hal_cbacks->acl_state_changed_cb
E/BluetoothRemoteDevices( 8948): aclStateChangeCallback: Device is NULL
,I/DeviceStatsManager( 3825):  uid:1002 pid:8948 flags:1 tag:bluedroid_timer wakeup time:60652
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 89
E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=109 dispatchEvent: HEART-BEAT-ACK: 89
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 90
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=110 dispatchEvent: HEART-BEAT-ACK: 90
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0,
,I/        ( 6900): Cleared service requests
,I/        ( 6900): Starting peer discovery failed, error code 0
,I/ActivityManager( 2937): filter receiver for action = android.bluetooth.intent.DISCOVERABLE_TIMEOUT
,I/HwLauncher( 3936): Model  onReceive intent=Intent { act=android.intent.action.TIME_TICK flg=0x50000014 (has extras) }
,I/TimeManager( 3472): receiver action = android.intent.action.TIME_TICK
I/TimeManager( 3472): hand message 1
I/TimeManager( 3472): notify time change. size = 2
,I/TimeLayout( 3472): time = 14:50
,I/TimeLayout( 3472): updateDate date = 11/25/2015
I/bluedroid( 8948): bt interface: [set_adapter_property]
I/bluedroid( 8948): bt interface: [set_adapter_property]
W/bt-btif ( 8948): HAL bt_hal_cbacks->adapter_properties_cb
W/bt-btm  ( 8948): BTM_SetDiscoverability
I/BluetoothAdapterProperties( 8948): adapterPropertyChangedCallback with type:9 len:4
I/TimeLayout( 3472): weekDay = Wednesday
,W/bt-btif ( 8948): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 8948): adapterPropertyChangedCallback with type:7 len:4
,I/WB      ( 6900): We already were running, thus doing nothing
,W/bt-btm  ( 8948): BTM_SetConnectability
,I/DeviceStatsManager( 3825):  uid:1002 pid:8948 flags:1 tag:bluedroid_timer wakeup time:61659
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 91
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=111 dispatchEvent: HEART-BEAT-ACK: 91
E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 92
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=112 dispatchEvent: HEART-BEAT-ACK: 92
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 93
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=113 dispatchEvent: HEART-BEAT-ACK: 93
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 94
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=114 dispatchEvent: HEART-BEAT-ACK: 94
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/        ( 6900): Cleared service requests
,I/        ( 6900): Starting peer discovery failed, error code 0
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 95
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=115 dispatchEvent: HEART-BEAT-ACK: 95
E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/wifi_log/wifi_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 96
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=116 dispatchEvent: HEART-BEAT-ACK: 96
E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 4085): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4085): BgPowerManagerService: mTimes = 240542 firstTime = 1326030 firstmBatteryCapacity =2203
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 97
E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=117 dispatchEvent: HEART-BEAT-ACK: 97
E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 98
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=118 dispatchEvent: HEART-BEAT-ACK: 98
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/        ( 6900): Cleared service requests
,I/        ( 6900): Starting peer discovery failed, error code 0
,I/HwSystemManager( 4085): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4085): BgPowerManagerService: mTimes = 270729 firstTime = 1326030 firstmBatteryCapacity =2203
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 99
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=119 dispatchEvent: HEART-BEAT-ACK: 99
E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 100
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=120 dispatchEvent: HEART-BEAT-ACK: 100
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 4085): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4085): BgPowerManagerService: mTimes = 300535 firstTime = 1326030 firstmBatteryCapacity =2203
E/HwSystemManager( 4085): BgPowerManagerService: conusmPower = 0 result = 0 flag1 =false flag2 = false
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 101
E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=121 dispatchEvent: HEART-BEAT-ACK: 101
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 6987): wlan0: HEART-BEAT-ACK: 102
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=122 dispatchEvent: HEART-BEAT-ACK: 102
,E/WifiStateMachine( 2937):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2937):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2937):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 2937):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState what:147506 0 0
,E/Thermal-daemon( 2331): [ap] temp_new :29  temp_old :30
,I/        ( 6900): Cleared service requests
,I/        ( 6900): Starting peer discovery failed, error code 0
,I/HwSystemManager( 4085): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4085): BgPowerManagerService: mTimes = 0 firstTime = 1656916 firstmBatteryCapacity =2203
,E/Thermal-daemon( 2331): [ap] temp_new :30  temp_old :29
,E/Thermal-daemon( 2331): [ap] temp_new :29  temp_old :30
,I/jxcore-log( 6900): DBG, CoordinatorConnector command called
I/jxcore-log( 6900): 
I/jxcore-log( 6900): command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): stop tests now !
I/jxcore-log( 6900): 
I/jxcore-log( 6900): stop current!
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): testSendData stopped
I/jxcore-log( 6900): 
,I/        ( 6900): Stoping All
I/        ( 6900): Stopping services
I/        ( 6900): Stopping services
,I/        ( 6900): Stop Bluetooth
I/        ( 6900): Stop Bluetooth
I/BTListenerThread( 6900): Stopped
,I/jxcore-log( 6900): StopBroadcasting went ok
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): 2015-11-25T13:53:35.994Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 6900): 
,I/        ( 6900): Cleared local services
I/        ( 6900): Cleared service requests
I/        ( 6900): Stopping peer discovery failed, error code 0
,I/chromium( 6900): [INFO:CONSOLE(63)] "logCallback stop", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6900): DBG, CoordinatorConnector command called
I/jxcore-log( 6900): 
I/jxcore-log( 6900): command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[],\"sendError\":{\"failedPeer\":[{\"connections\":1,\"name\":\"E0:DB:10:14:E2:C0\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"7C:F9:0E:37:96:AB\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"34:FC:EF:11:AE:67\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"F8:95:C7:87:3C:51\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"08:EC:A9:50:75:41\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"34:FC:EF:11:B1:66\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"08:EC:A9:50:76:27\",\"time\":0,\"result\":\"Fail\"}],\"notTriedList\":[{\"connections\":0,\"name\":\"7C:F9:0E:34:8A:A0\",\"time\":0,\"result\":\"Fail\"},{\"connections\":0,\"name\":\"F8:95:C7:87:85:54\",\"time\":0,\"result\":\"Fail\"},{\"connections\":0,\"name\":\"34:FC:EF:9D:93:0B\",\"time\":0,\"result\":\"Fail\"},{\"connections\":0,\"name\":\"F8:CF:C5:D9:E5:61\",\"tim
,I/jxcore-log( 6900): ****TEST TOOK:  ms ****
I/jxcore-log( 6900): 
I/jxcore-log( 6900): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6900): 
I/jxcore-log( 6900): stop tests now !
I/jxcore-log( 6900): 
,I/jxcore-log( 6900): end, event received
I/jxcore-log( 6900): 
I/jxcore-log( 6900): CoordinatorConnector close called
I/jxcore-log( 6900): 
I/jxcore-log( 6900): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 6900): 
I/jxcore-log( 6900): The Coordinator has disconnected!
I/jxcore-log( 6900): 
I/jxcore-log( 6900): The Coordinator has closed!
I/jxcore-log( 6900): 
I/jxcore-log( 6900): stop tests now !
I/jxcore-log( 6900): 
I/jxcore-log( 6900): turning Radios off
I/jxcore-log( 6900): 
I/jxcore-log( 6900): Toggling radios to false
I/jxcore-log( 6900): 
I/BluetoothAdapter( 6900): Start to disable Bluetooth!
I/BluetoothAdapterState( 8948): Bluetooth adapter state changed: 12-> 13
I/bluedroid( 8948): bt interface: [set_adapter_property]
W/bt-btm  ( 8948): BTM_SetDiscoverability
W/bt-btif ( 8948): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterState( 8948): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/BluetoothAdapterProperties( 8948): adapterPropertyChangedCallback with type:7 len:4
I/ActivityManager( 2937): filter receiver for action = android.bluetooth.adapter.action.STATE_CHANGED
W/bt-btm  ( 8948): BTM_SetConnectability
,I/bluedroid( 8948): bt interface: [disable]
W/bt-btif ( 8948): btif_disable_bluetooth, btif_core_radio_ref_count=0
W/bt-btif ( 8948): BTIF DISABLE BLUETOOTH
W/bt-btif ( 8948): bta_sys_disable: module 0
W/bt-btm  ( 8948): BTM_SetDiscoverability
W/bt-btm  ( 8948): BTM_SetConnectability
W/bt-btif ( 8948): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
E/BtOppRfcommListener( 8948): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-l2cap( 8948): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 8948): L2CAP - PSM: 0x0017 not found for deregistration
I/BtOppRfcommListener( 8948): stopping Accept Thread
I/BtOppRfcommListener( 8948): BluetoothSocket listen thread finished
I/bluetooth-coex( 8948): bt_coex_deinit: bt_coex_deinit
I/bluetooth-coex( 8948): btcoex_send_msg: send bt_state(0) to wifi, sock_fd(72)
I/bluetooth-coex( 8948): btcoex_socket_server: accept socket success
,I/bluetooth-coex( 8948): btcoex_send_msg: bt closing, exit coex server, sock_fd(72)
I/bluetooth-coex( 8948): btcoex_socket_server: BT_COEX_PTHREAD_EXIT
I/bluetooth-coex( 8948): bt_coex_deinit: clear coex timer list entry
I/bluetooth-coex( 8948): bt_coex_deinit: free g_bt_coex_cb
,I/HwSystemManager( 4085): HoldService:checkBeforeShowDialog: uid:10295 pid:6900, permissionType:2097152
I/HwSystemManager( 4085): OverseaCfgHelper:permissionStatus is 0
,I/ConnectPermission( 2937): allowOpenWifi blocked:false
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/bfg_log/bfg_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,E/WifiStateMachine( 2937):  ConnectedState CMD_STOP_SUPPLICANT 0 0
I/jxcore-log( 6900): Radios toggled
I/jxcore-log( 6900): 
E/WifiStateMachine( 2937):  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 2937):  ConnectModeState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 2937):  DriverStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 2937):  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 2937): WifiStateMachine: Leaving Connected state
E/WifiStateMachine( 2937): setScanAlarm false period 0 initial delay 0
E/WifiStateMachine( 2937): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 2937): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 2937): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/View    ( 3472): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{51589be V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during layout: running second layout pass
,I/art     ( 2937): Background sticky concurrent mark sweep GC freed 105754(7MB) AllocSpace objects, 14(280KB) LOS objects, 20% free, 28MB/36MB, paused 5.608ms total 107.110ms
,E/native  ( 2937): do suspend true
,I/chromium( 6900): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 6987): set current WIFI status to BT!
,I/ActivityManager( 2937): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2937): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2937): filter receiver for action = android.net.wifi.STATE_CHANGE
E/WifiConfigStore( 2937): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/ArpVerifier( 2937): current SSID is empty.
,I/ActivityManager( 2937): filter receiver for action = com.google.android.gcm.DISCONNECTED
,E/WifiStateMachine( 2937): Unexpected BatchedScanResults :OK
,E/WifiStateMachine( 2937): noteBatchedScanstop()
E/WifiStateMachine( 2937): [1,448,459,616,155 ms] noteScanEnd no scan source
E/WifiStateMachine( 2937):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2937):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2937):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2937): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine( 2937):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2937):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,I/art     ( 2937): Can not find class: Lcom/android/server/wifi/RttService$RttServiceImpl$ClientInfo;
,E/WifiStateMachine( 2937): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 2937):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2937):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2937):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2937): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 2937):  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
,E/native  ( 2937): do suspend true
,I/wpa_supplicant( 6987): set current WIFI status to BT!
,I/art     ( 2937): Can not find class: Lcom/android/server/NetworkManagementService$IdleTimerParams;
,I/ActivityManager( 2937): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/wpa_supplicant( 6987): set current WIFI status to BT!
,I/wpa_supplicant( 6987): WIFI closed already, cancel
,I/wpa_supplicant( 6987): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
W/wpa_supplicant( 6987): check_associate_result func start
I/HwSystemManager( 4085): aor:Network Stats Updated
I/HwSystemManager( 4085): aoi:onNetworkStatsUpdated
I/HwSystemManager( 4085): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=123 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 2937): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
W/wpa_supplicant( 6987): STA MODE: Set shutdown wlan cmd SUCCESS
W/wpa_supplicant( 6987): check_associate_result func start
,W/System.err( 2937): java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
W/System.err( 2937): 	at com.huawei.android.server.wifi.ReportTool.getUserType(ReportTool.java:86)
W/System.err( 2937): 	at com.huawei.android.server.wifi.ReportTool.isBetaUser(ReportTool.java:73)
W/System.err( 2937): 	at com.huawei.android.server.wifi.ReportTool.report(ReportTool.java:58)
W/System.err( 2937): 	at com.huawei.android.server.wifi.DataUploader.e(DataUploader.java:57)
W/System.err( 2937): 	at com.android.server.wifi.WifiMonitor.handleNetworkStateChange(WifiMonitor.java:1420)
W/System.err( 2937): 	at com.android.server.wifi.WifiMonitor.handleEvent(WifiMonitor.java:1018)
W/System.err( 2937): 	at com.android.server.wifi.WifiMonitor.dispatchEvent(WifiMonitor.java:988)
W/System.err( 2937): 	at com.android.server.wifi.WifiMonitor.access$500(WifiMonitor.java:55)
W/System.err( 2937): 	at com.android.server.wifi.WifiMonitor$WifiMonitorSingleton.dispatchEvent(WifiMonitor.java:701)
W/System.err( 2937): 	at com.android.server.wifi.WifiMonitor$WifiMonitorSingleton.access$700(WifiMonitor.java:586)
W/System.err( 2937): 	at com.android.server.wifi.WifiMonitor$MonitorThread.run(WifiMonitor.java:759)
E/ReportTools( 2937): This is not beta user build
,I/NetworkSpeedManagerEx( 3472): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3472): wifiManager = android.net.wifi.WifiManager@24dacd11
,I/ActivityManager( 2937): filter receiver for action = android.net.wifi.WIFI_STATE_CHANGED
,I/NetworkSpeedManagerEx( 3472): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3472): stop
,I/HwSystemManager( 4085): aor:Network Stats Updated
I/HwSystemManager( 4085): aoi:onNetworkStatsUpdated
I/HwSystemManager( 4085): MainReceiver:receive action:android.net.wifi.WIFI_STATE_CHANGED
,W/bt-btif ( 8948): bta_sys_hw_api_disable for 0, active modules: 0x0001
W/bt-btif ( 8948): bta_sys_disable: module 0
W/bt-btif ( 8948): call bta_sys_hw_co_disable
W/bt-btif ( 8948): sending BTA_SYS_EVT_DISABLED_EVT
W/bt-btif ( 8948): bta_sys_hw_evt_disabled - module 0x0
W/bt-btif ( 8948):  bta_dm_sys_hw_cback with event: 0
E/HwSystemManager( 4085): getSimCardType:/getSimCardInfo: imsi is null
,W/bt-btif ( 8948): ag scb idx 1 not allocated, btif_core_is_radio_req = 0
W/bt-btif ( 8948): ag scb idx 1 not allocated, btif_core_is_radio_req = 0
W/bt-btif ( 8948): btif_dm_disable_bt_services
W/bt-btif ( 8948): btif_dm_disable_bt_services i=6
E/bt-btif ( 8948): BTA AG is already disabled, ignoring ...
W/bt-btif ( 8948): btif_dm_disable_bt_services i=18
W/bt-btif ( 8948): btif_dm_disable_bt_ not found fo
W/bt-l2cap( 8948): btif_dm_disable_bt_ not found for deregistration
W/bt-btif ( 8948): L2CAP - PSM: 0x0017services i=25
W/bt-l2cap( 8948): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 8948): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 8948): bte_main_enable_lpm
W/bt-btif ( 8948): bte_main_enable_lpm
W/bt-l2cap( 8948): bte_main_disable
W/bt-btif ( 8948): bte_main_disable
W/bt-l2cap( 8948): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-btif ( 8948): ag scb idx 1 not allocated
E/bt-btif ( 8948): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 8948): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 8948): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 8948): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 8948): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 8948): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 8948): L2CAP - PSM: 0x0017 not found for deregistration
W/bt_lpm  ( 8948): Still busy on processing prior LPM enable/disable request...
W/bt_userial( 8948): select_read return size <=0:-1, exiting userial_read_thread
,E/HwSystemManager( 4085): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 4085): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 4085): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 4085): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
I/HwSystemManager( 4085): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/WifiMonitor( 2937): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=124 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/HwSystemManager( 4085): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 4085): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 4085): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 4085): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 4085): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/HwSystemManager( 4085): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 4085): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 4085): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 4085): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 4085): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 4085): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
,I/HwSystemManager( 4085): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 4085): getSimCardType:/getSimCardInfo: imsi is null,
,E/HwSystemManager( 4085): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 4085): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 4085): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 4085): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
I/HwSystemManager( 4085): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,I/appproc ( 9323): CLASSPATH=/system/framework/pm.jar
I/appproc ( 9323): Command=app_process /system/bin com.android.commands.pm.Pm uninstall -k com.test.thalitest 
I/appproc ( 9323): app_process:number,5,0
,E/HwSystemManager( 4085): getSimCardType:/getSimCardInfo: imsi is null
,I/AndroidRuntime( 9323): readDownloadBoosterConfig: 'false'
,E/HwSystemManager( 4085): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 4085): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 4085): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 4085): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/HwSystemManager( 4085): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,I/ActivityManager( 2937): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,E/WifiStateMachine( 2937):  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=1668923
I/NetworkSpeedManagerEx( 3472): receive:android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 2937):  DefaultState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=1668924
I/NetworkSpeedManagerEx( 3472): wifiManager = android.net.wifi.WifiManager@24dacd11
I/NetworkSpeedManagerEx( 3472): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3472): stop
E/WifiStateMachine( 2937):  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 124 0 rt=1668924  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 2937):  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 124 0 rt=1668925  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/HwSystemManager( 4085): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 4085): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 4085): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 4085): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 4085): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
,E/WifiStateMachine( 2937):  SupplicantStoppingState CMD_ON_QUIT 0 0
,E/WifiStateMachine( 2937):  DefaultState CMD_ON_QUIT 0 0
,I/NetworkSpeedManagerEx( 3472): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3472): wifiManager = android.net.wifi.WifiManager@24dacd11
,I/NetworkSpeedManagerEx( 3472): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3472): stop
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=125 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:48
E/WifiMonitor( 2937): handleEvent 13  CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:48
,I/DeviceStatsManager( 3825):  uid:1002 pid:8948 flags:1 tag:bluedroid_timer wakeup time:61960
,W/wpa_supplicant( 6987): ioctl error:ret = -1
E/wpa_supplicant( 6987): wpa_driver_set_wps_p2p_ie failed ret=-1
,I/        ( 9323): power log dlsym ok
,I/NetworkSpeedManagerEx( 3472): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3472): wifiManager = android.net.wifi.WifiManager@24dacd11
,I/NetworkSpeedManagerEx( 3472): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3472): stop
,I/WifiTracker( 3472): STATE =0
,E/HsmCoreServiceImpl( 2937): onTransact in code is: 102
I/HwSystemManager( 4085): HoldService:uid:10078 pid:7447 died
I/HwSystemManager( 4085): HoldService:oldVersionKey:10078,7447
I/MediaProcessHandler( 2937): processOp opType: 1, uid: 10078, pid: 7447
W/MediaProcessHandler( 2937): remove target not exist, maybe the UI process: uid: 10078, pid: 7447
I/HwSystemManager( 4085): BgPowerManagerService:onProcessDied uid = 10078
,E/android_hardware_fm.cpp( 9323): register_android_hardware_fm_fmradio
I/android_hardware_fm.cpp( 9323): ========64bit long size = 8
E/FM_HAL  ( 9323): [FM_HAL], libname is libhisifm_if
,I/fm_hisi ( 9323): FM::[fm_device_open:4653] fm_device_open
I/fm_hisi ( 9323): 
I/fm_hisi ( 9323): FM::[fm_device_open:4664] find the id:libhisifm_if and begins to open the device
I/fm_hisi ( 9323): 
I/fm_hisi ( 9323): FM::[fm_device_open:4708] device open sucess
I/fm_hisi ( 9323): 
E/android_hardware_fm.cpp( 9323): register_android_hardware_fm_fmradio, ret is 0
,W/View    ( 3472): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{51589be V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during layout: running second layout pass
,W/View    ( 3472): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{51589be V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during second layout pass: posting in next frame
,I/WifiTracker( 3472): STATE =0
,I/WifiTracker( 3472): STATE =0
,I/WifiTracker( 3472): STATE =0
,I/WifiTracker( 3472): STATE =0
,I/art     ( 2937): Can not find class: Lcom/android/server/pm/PackageInstallerService$PackageDeleteObserverAdapter;
,W/View    ( 3472): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{51589be V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during second layout pass: posting in next frame
,I/art     ( 2937): Can not find class: Lcom/android/server/pm/PackageManagerService$9;
,I/wpa_supplicant( 6987): wlan0: CTRL-EVENT-TERMINATING 
,E/WifiMonitor( 2937): WifiMonitor:wlan0 cnt=126 dispatchEvent: CTRL-EVENT-TERMINATING 
E/WifiStateMachine( 2937):  SupplicantStoppingState SUP_DISCONNECTION_EVENT 126 0
I/wpa_supplicant( 6987): ELOOP: remaining timeout: 0.410670 eloop_data=0x5575a35fb0 user_data=0x0 handler=0x5561d9f6c0
,I/HwSystemManager( 4085): HoldService:uid:10295 pid:6900 died
I/HwSystemManager( 4085): HoldService:oldVersionKey:10295,6900
E/HsmCoreServiceImpl( 2937): onTransact in code is: 102
I/MediaProcessHandler( 2937): processOp opType: 1, uid: 10295, pid: 6900
W/MediaProcessHandler( 2937): remove target not exist, maybe the UI process: uid: 10295, pid: 6900
,I/HwSystemManager( 4085): BgPowerManagerService:onProcessDied uid = 10295
,I/        ( 8948): [vendor/huawei_platform/connectivity/hisi/hisi_connectivity/bt/hal/src/bt_vendor_hisi.c: hisi_cleanup 354][bt_vendor] cleanup
I/GKI_LINUX( 8948): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 8948): GKI_exit_task 0 done
I/GKI_LINUX( 8948): GKI_shutdown(): task [BTU] terminated
W/bt-btif ( 8948): HAL bt_hal_cbacks->adapter_state_changed_cb
,I/ActivityManager( 2937): filter receiver for action = android.intent.action.PACKAGE_REMOVED
,E/TEST-APN( 3890): query for APN: check-permission succ 
E/TEST-APN( 3890): Telephony query SQL: SELECT type, proxy, port FROM carriers WHERE (numeric = ',' and carrier_enabled = 1)
,I/HwSystemManager( 4085): AppLockService:applock password not initial or function is closed
,I/HwSystemManager( 4085): AppManager:getNetAppInfoFromDB cursor lenth = 1
,I/InputReader( 2937): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 3793): Ignoring removeGeofence because network location is disabled.
,W/ResourceType( 2937): ResTable_typeSpec entry count inconsistent: given 1, previously 1445
I/art     ( 6614): Explicit concurrent mark sweep GC freed 31426(2MB) AllocSpace objects, 10(160KB) LOS objects, 25% free, 13MB/18MB, paused 1.093ms total 62.195ms
I/HwSystemManager( 6614): HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/HwSystemManager( 6614): HsmPackageManager:replacing:false
I/HwSystemManager( 6614): HsmPackageManager:pkgName:com.test.thalitest
I/HwSystemManager( 6614): HsmPackageManager:doAppRemoved, remove:com.test.thalitest
,I/art     ( 3936): Explicit concurrent mark sweep GC freed 16892(1055KB) AllocSpace objects, 60(3MB) LOS objects, 40% free, 22MB/37MB, paused 980us total 69.811ms
,I/HwLauncher( 3936): Model  onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/HwLauncher( 3936): Model replacing = false package = com.test.thalitest
,I/HwLauncher( 3936): Model  ACTION_PACKAGE_REMOVED replacing = false
,I/HwLauncher( 3936): MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 3 packages = [com.test.thalitest]
,I/HwLauncher( 3936): Model mAllAppsList.removePackage com.test.thalitest
,I/HwLauncher( 3936): SimpleLauncherModeaction= android.intent.action.PACKAGE_REMOVEDpackageName = com.test.thalitest
,I/HwLauncher( 3936): SimpleLauncherModedeleteBadgeItemFromDBByPkg packageName=com.test.thalitest
,E/HideAppsPagedView( 3936): removeItems begin 
,E/HideAppsPagedView( 3936): ShortcutInfo(title=ThaliTest)
,W/System.err( 2937): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 2937): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
W/System.err( 2937): 	at com.android.server.SmartHeartBeat$HeartBeatHandler.updatePackageMessage(SmartHeartBeat.java:872)
W/System.err( 2937): 	at com.android.server.SmartHeartBeat$HeartBeatHandler.handleMessage(SmartHeartBeat.java:606)
W/System.err( 2937): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2937): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2937): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/HideAppsPagedView( 3936): removeItems end 
,I/HwLauncher( 3936): Launcher.LauncherProvider  only HwLauncher can use LauncherProvider's delete method to delete badge table item 
I/HwLauncher( 3936): SimpleAllAppsList   add packageName into uninstalledSDApps 
,I/HwLauncher( 3936): SimpleLauncherModeuninstalledSDApps size > 0
W/HwLauncher( 3936): SimpleLauncherModeNobody to tell about the new app.  Launcher is probably loading.
I/HwLauncher( 3936): SimpleLauncherModeOP_REMOVE callback is null, delete simpleUI database record
,I/art     ( 4085): Explicit concurrent mark sweep GC freed 107087(7MB) AllocSpace objects, 27(432KB) LOS objects, 40% free, 14MB/23MB, paused 1.055ms total 87.652ms
,I/HwSystemManager( 4085): HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/HwSystemManager( 4085): HsmPackageManager:replacing:false
,I/HwSystemManager( 4085): HsmPackageManager:pkgName:com.test.thalitest
I/HwSystemManager( 4085): HsmPackageManager:doAppRemoved, remove:com.test.thalitest
,I/HwLauncher( 3936): Workspace removeItems info = ShortcutInfo(title=ThaliTest) isNeedDelete = true
,I/HwSystemManager( 4085): ww:deleteLockData:com.test.thalitest
,W/System.err( 3936): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,W/System.err( 3936): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
W/System.err( 3936): 	at com.huawei.android.launcher.ShortcutInfo.isAppUninstallable(ShortcutInfo.java:340)
W/System.err( 3936): 	at com.huawei.android.launcher.Workspace$10.run(Workspace.java:6784)
W/System.err( 3936): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3936): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3936): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3936): 	at android.app.ActivityThread.main(ActivityThread.java:5538)
W/System.err( 3936): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3936): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3936): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
W/System.err( 3936): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
W/System.err( 3936): java.lang.NullPointerException: null receiver
,W/System.err( 3936): 	at java.lang.reflect.Field.get(Native Method)
W/System.err( 3936): 	at java.lang.reflect.Field.get(Field.java:279)
W/System.err( 3936): 	at com.huawei.android.launcher.ShortcutInfo.isAppUninstallable(ShortcutInfo.java:365)
W/System.err( 3936): 	at com.huawei.android.launcher.Workspace$10.run(Workspace.java:6784)
W/System.err( 3936): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3936): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3936): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3936): 	at android.app.ActivityThread.main(ActivityThread.java:5538)
W/System.err( 3936): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3936): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3936): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
W/System.err( 3936): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
,I/HwLauncher( 3936): CellLayout rearrangeAfterRmItem isAutoAlign = false
,I/HwLauncher( 3936): Launcher Deferring update until onResume
,I/ActivityManager( 2937): filter receiver for action = android.intent.action.PACKAGE_FULLY_REMOVED
,I/ActivityManager( 2937): filter receiver for action = android.net.wifi.WIFI_STATE_CHANGED
W/Settings( 5975): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/System.out( 3913): Stale Location error
,I/SUPL20_SPIMESLP-SENDING( 3913): m_bPacket.length 341
I/SUPL20_SPIMESLP-SENDING( 3913): bBrokenPipe = false
,I/ActivityManager( 2937): filter receiver for action = android.net.conn.TETHER_STATE_CHANGED
,E/RegisteredServicesCache( 3869): invalidateCache set mNeedToastTableFull
,W/Settings( 3793): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/BluetoothHeadsetServiceJni( 8948): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 8948): Cleaning up Bluetooth Handsfree callback object
,I/HwSystemManager( 4085): aor:Network Stats Updated
I/HwSystemManager( 4085): aoi:onNetworkStatsUpdated
I/HwSystemManager( 4085): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,I/GKI_LINUX( 8948): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 8948): GKI_exit_task 2 done
I/GKI_LINUX( 8948): GKI_shutdown(): task [A2DP-MEDIA] terminated
,E/HwSystemManager( 4085): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 4085): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 4085): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 4085): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
W/BluetoothHidServiceJni( 8948): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 8948): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 8948): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 8948): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 8948): Cleaning up Bluetooth Health object
I/HwLauncher( 3936): Launcher  onWindowVisibilityChanged visibility = 4
I/HwLauncher( 3936): DynamicIcon onWindowVisibilityChanged 4 - com.android.calendar
I/HwLauncher( 3936): DynamicIcon onWindowVisibilityChanged 4 - com.android.deskclock
W/BluetoothPanServiceJni( 8948): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 8948): Cleaning up Bluetooth PAN callback object
,I/BluetoothAdapterState( 8948): Bluetooth adapter state changed: 13-> 10
I/BluetoothAdapterState( 8948): Entering OffState
E/HwSystemManager( 4085): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
I/HwSystemManager( 4085): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,I/WifiTracker( 3472): STATE =0
,I/HwLauncher( 3936): Launcher onStart()
I/HwLauncher( 3936): Launcher dynamicIconsRegister
I/HwLauncher( 3936): DynamicUpdater registerReceiver
I/HwLauncher( 3936): DynamicUpdater call updateFolder
I/HwLauncher( 3936): DynamicIcon onResume  isvisible = false   mAttachedToWindow:true    mWindowVisible:falsecom.android.calendar
I/HwLauncher( 3936): DynamicUpdater registerReceiver
I/HwLauncher( 3936): DynamicUpdater call updateFolder
I/HwLauncher( 3936): DynamicIcon onResume  isvisible = false   mAttachedToWindow:true    mWindowVisible:falsecom.android.deskclock
I/HwLauncher( 3936): DynamicUpdater registerReceiver
,I/HwLauncher( 3936): DynamicUpdater call updateFolder,
I/HwLauncher( 3936): DynamicIconData , getDrawableForDynamic begin, pkg = com.android.deskclock, picName = deskclock_bg
,I/HwLauncher( 3936): DynamicIcon onResume  isvisible = true   mAttachedToWindow:false    mWindowVisible:falsecom.huawei.android.totemweather
,I/HwLauncher( 3936): DynamicIcon onVisibilityChanged 0 - com.android.calendar
I/HwLauncher( 3936): DynamicIcon onVisibilityChanged 0 - com.android.deskclock
,E/HideAppsPagedView( 3936): removeHideApps  begin 
E/HideAppsPagedView( 3936): removeHideApps  end 
E/HideAppsPagedView( 3936):  syncPages mCurrentPage = 0,
,I/HwLauncher( 3936): DynamicIconData , getDrawableForDynamic end, pkg = com.android.deskclock, picName = deskclock_bg
,I/HwLauncher( 3936): DynamicIconData , getDrawableForDynamic begin, pkg = com.android.deskclock, picName = deskclock_bg
I/HwLauncher( 3936): DynamicIconData , getDrawableForDynamic end, pkg = com.android.deskclock, picName = deskclock_bg
,I/HwLauncher( 3936): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
,I/HwLauncher( 3936): ClockDynamicUpdater clock update folder at ClockDynamicUpdater,
I/HwLauncher( 3936): DynamicUpdater updateBitmap end and send update message
I/HwLauncher( 3936): WeatherDynamicUpdaterpositiveUpdate at WeatherDynamicUpdater
E/HideAppsPagedView( 3936):  syncAppsPageItems page = 0 mNumAppsPages = 1 mCurrentPage = 0
,E/HideAppsPagedView( 3936):  createAddIcon count = 0
,I/HwLauncher( 3936):  FPSMonitor snapToPage whichPage = 0 delta = 0 duration = 550
I/HwLauncher( 3936): Launcher  onWindowVisibilityChanged visibility = 0
I/HwLauncher( 3936): DynamicIcon onWindowVisibilityChanged 0 - com.android.calendar
I/HwLauncher( 3936): DynamicIcon onWindowVisibilityChanged 0 - com.android.deskclock
,E/HwSystemManager( 4085): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 4085): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 4085): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 4085): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 4085): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/HwSystemManager( 4085): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 4085): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 4085): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 4085): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 4085): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
E/HwSystemManager( 4085): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
,I/HwCust  ( 9379): Constructor found for class com.huawei.mms.util.HwCustHwBackgroundLoaderImpl
,I/HwLauncher( 3936): DynamicUpdater call updateFolder
,W/asset   ( 2937): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/ActivityManager( 2937): filter receiver for action = android.bluetooth.adapter.action.STATE_CHANGED
,I/bluedroid( 8948): bt interface: [cleanup]
,I/art     ( 2937): Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord;
W/bt-btif ( 8948): HAL bt_hal_cbacks->thread_evt_cb
I/GKI_LINUX( 8948): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 8948): GKI_exit_task 1 done
I/GKI_LINUX( 8948): GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 8948): cleanupNative: return from cleanup
I/BluetoothServiceJni( 8948): OoO sJniCallbacksObj has init before clean? 1
,I/art     ( 2937): Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord$1;
I/art     ( 2937): Can not find class: Lhuawei/com/android/server/util/ReportTool;
,I/art     ( 2937): Can not find class: Lcom/huawei/report/ReporterInterface;
E/ReportTools( 2937): Can't find sReporterClazz
,I/art     ( 2937): Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord$UploadThread;
,I/art     ( 2937): Can not find class: Lhuawei/com/android/server/util/AppInfo;
I/art     ( 8948): System.exit called, status: 0
I/AndroidRuntime( 8948): VM exiting with result code 0, cleanup skipped.
,W/System.err( 2937): java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
W/System.err( 2937): 	at huawei.com.android.server.util.ReportTool.getUserType(ReportTool.java:86)
W/System.err( 2937): 	at huawei.com.android.server.util.ReportTool.isBetaUser(ReportTool.java:73)
W/System.err( 2937): 	at huawei.com.android.server.util.ReportTool.report(ReportTool.java:58)
W/System.err( 2937): 	at huawei.com.android.server.util.UserBehaviourRecord.appExitRecord(UserBehaviourRecord.java:65)
W/System.err( 2937): 	at com.android.server.am.ActivityManagerService.cleanUpRemovedTaskLocked(ActivityManagerService.java:9036)
W/System.err( 2937): 	at com.android.server.am.ActivityManagerService.removeTaskByIdLocked(ActivityManagerService.java:9092)
W/System.err( 2937): 	at com.android.server.am.ActivityManagerService.access$1000(ActivityManagerService.java:293)
W/System.err( 2937): 	at com.android.server.am.ActivityManagerService$3.onPackageRemoved(ActivityManagerService.java:2234)
W/System.err( 2937): 	at com.android.internal.content.PackageMonitor.onReceive(PackageMonitor.java:341)
W/System.err( 2937): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:899)
W/System.err( 2937): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 2937): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 2937): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2937): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/System.err( 2937): 	at com.android.server.SystemServer.main(SystemServer.java:212)
W/System.err( 2937): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 2937): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 2937): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
W/System.err( 2937): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
E/ReportTools( 2937): This is not beta user build
,W/HWContacts( 9379): ProviderFeatureChcker - cootek package not installed
,I/PhoneStatusBar( 3472): shouldTranslucent:true
I/PhoneStatusBar( 3472): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
,E/WifiStateMachine( 2937): could not open wifi state sys nodejava.io.FileNotFoundException: /sys/devices/platform/bcmdhd_wlan.1/wifi_open_state: open failed: ENOENT (No such file or directory)
E/TmoMonitor( 9379): Add already observed target for ThreadEx's defualtExecutor TaskStack com.huawei.cspcommon.ex.ThreadEx$SerialExecutor@2da0a13f
E/WifiStateMachine( 2937):  InitialState CMD_TETHER_STATE_CHANGE 0 0
,E/WifiStateMachine( 2937):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,W/asset   ( 9405): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/HwCust  ( 9405): Constructor found for class com.huawei.android.totemweather.utils.HwCustUseBitmapConfigImpl
,I/HwCust  ( 9405): Constructor found for class com.huawei.android.totemweather.HwCustWeatherAppHwBaseImpl
,I/HwSystemManager( 4085): HoldService:uid:1002 pid:8948 died
I/HwSystemManager( 4085): HoldService:oldVersionKey:1002,8948
,I/HwSystemManager( 4085): BgPowerManagerService:onProcessDied uid = 1002
,E/HsmCoreServiceImpl( 2937): onTransact in code is: 102
W/MediaProcessHandler( 2937): processOp uid 1002 is not concerned!
,I/HwCust  ( 9379): Constructor found for class com.android.mms.data.HwCustConversationImpl
,I/HwLauncher( 3936): WeatherDynamicUpdaterreceive action = com.huawei.android.action.launcher_weather_icon_change
,I/HwLauncher( 3936): WeatherDynamicUpdaterreceiver data is int[] = [0, 0]
I/HwLauncher( 3936):  stringArray[] [unknown]
,I/Mms_threadcache( 9379): [RecipientIdCache] fill: begin
,E/MmsConfig( 9379): load /system/etc/xml/mms_config.xml MmsSettings caught FileNotFoundException
,I/art     ( 2937): Explicit concurrent mark sweep GC freed 53044(2MB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/42MB, paused 2.300ms total 372.805ms
,I/HwSystemManager( 4085): HoldService:uid:10005 pid:7426 died
I/HwSystemManager( 4085): BgPowerManagerService:onProcessDied uid = 10005
I/HwSystemManager( 4085): HoldService:oldVersionKey:10005,7426
,E/HsmCoreServiceImpl( 2937): onTransact in code is: 102
I/MediaProcessHandler( 2937): processOp opType: 1, uid: 10005, pid: 7426
W/MediaProcessHandler( 2937): remove target not exist, maybe the UI process: uid: 10005, pid: 7426
,I/EmuiFeatureManager( 9379): loadEmailAnrSupportFlag:true
,I/HwCust  ( 9379): Constructor found for class com.android.mms.transaction.HwCustMsgNotificationImpl
,E/CSP_RADAR( 9379): Message execute too long time.{ when=-139ms what=1 target=com.huawei.mms.util.HwBackgroundLoader$3 }
,I/HwCust  ( 9379): Constructor found for class com.android.mms.transaction.HwCustMessagingNotificationImpl
,I/SimFactoryManager( 9379): Inside init method of SimFactoryManger the combination is:-1
,I/SimFactoryManager( 9379): Get SIM state from SIM factory manager: 1,For slotId:0
I/SimFactoryManager( 9379): isSIM1CardPresent:1
,I/SimFactoryManager( 9379): Get SIM state from SIM factory manager: 1,For slotId:0
,I/SimFactoryManager( 9379): Get SIM state from SIM factory manager: 1,For slotId:1
,I/SimFactoryManager( 9379): updateSimState,sIsSIMCard1Present=false,sIsSIMCard1Enabled=false,sIsSIMCard2Present=false,sIsSIMCard2Enabled=false
,I/SimFactoryManager( 9379): Get SIM state from SIM factory manager: 1,For slotId:1
I/SimFactoryManager( 9379): isSIM2CardPresent:1
,I/SimFactoryManager( 9379): Get SIM state from SIM factory manager: 1,For slotId:0
,I/SimFactoryManager( 9379): Get SIM state from SIM factory manager: 1,For slotId:1
I/SimFactoryManager( 9379): updateSimState,sIsSIMCard1Present=false,sIsSIMCard1Enabled=false,sIsSIMCard2Present=false,sIsSIMCard2Enabled=false
,I/HwCust  ( 9379): Constructor found for class com.android.contacts.HwCustContactApplicationHelperImpl
,E/CSP_RADAR( 9379): Runnable execute too long time
,I/HwSystemManager( 4085): HoldService:uid:10036 pid:7249 died
I/HwSystemManager( 4085): HoldService:oldVersionKey:10036,7249
I/HwSystemManager( 4085): BgPowerManagerService:onProcessDied uid = 10036
E/HsmCoreServiceImpl( 2937): onTransact in code is: 102
I/MediaProcessHandler( 2937): processOp opType: 1, uid: 10036, pid: 7249
W/MediaProcessHandler( 2937): remove target not exist, maybe the UI process: uid: 10036, pid: 7249
,I/HwCust  ( 9379): Constructor found for class com.android.contacts.hap.HwCustCommonUtilMethodsImpl
,I/art     ( 9379): Can not find class: Lhuawei/android/view/TableLayout;
,I/art     ( 9379): Can not find class: Lhuawei/android/widget/TableLayout;
,I/art     ( 9379): Can not find class: Lhuawei/android/view/View;
,I/art     ( 9379): Can not find class: Lhuawei/android/widget/View;
I/art     ( 9379): Can not find class: Landroid/widget/View;
,I/art     ( 9379): Can not find class: Landroid/webkit/View;
,I/art     ( 9379): Can not find class: Landroid/app/View;
,I/art     ( 9379): Can not find class: Lhuawei/android/view/TableRow;
,I/art     ( 9379): Can not find class: Lhuawei/android/widget/TableRow;
,I/art     ( 9379): Can not find class: Lhuawei/android/view/LinearLayout;
,I/art     ( 9379): Can not find class: Lhuawei/android/widget/LinearLayout;
,I/art     ( 9379): Can not find class: Lhuawei/android/view/ImageButton;
,I/art     ( 9379): Can not find class: Lhuawei/android/widget/ImageButton;
,I/art     ( 9379): Can not find class: Lhuawei/android/view/TextView;
I/art     ( 9379): Can not find class: Lhuawei/android/widget/TextView;
,I/HwCust  ( 9444): Constructor found for class com.android.providers.contacts.HwCustContactsProviderHelperImpl,
,I/art     ( 9379): Can not find class: Lhuawei/android/view/RelativeLayout;,
I/art     ( 9379): Can not find class: Lhuawei/android/widget/RelativeLayout;
,I/PG Utils( 9444): acquire_providerpkg:[com.android.providers.userdictionary] pid:[]  maybe timeout , send to PG
,I/art     ( 9379): Can not find class: Lhuawei/android/view/ImageView;
,I/art     ( 9379): Can not find class: Lhuawei/android/widget/ImageView;
,I/HwCust  ( 9444): Constructor found for class com.android.providers.contacts.HwCustContactsDatabaseHelperImpl
,I/HwCust  ( 9444): Constructor found for class com.android.providers.contacts.HwCustContactsDatabaseHelperImpl
,I/HwCust  ( 9444): Constructor found for class com.android.providers.contacts.HwCustContactsProvider2Impl
,E/ContactsProtector( 9444): getHiCloudAccountData query fail
,I/HwCust  ( 9444): Constructor found for class com.android.providers.contacts.aggregation.HwCustContactAggregatorImpl
,I/art     ( 9379): Can not find class: Lhuawei/android/view/ViewStub;
,I/art     ( 9379): Can not find class: Lhuawei/android/widget/ViewStub;
I/art     ( 9379): Can not find class: Landroid/widget/ViewStub;
,I/art     ( 9379): Can not find class: Landroid/webkit/ViewStub;
I/art     ( 9379): Can not find class: Landroid/app/ViewStub;
,E/SQLiteDatabase( 9444): Failed to open database '/data/data/com.android.providers.contacts/databases/profile.db'.
E/SQLiteDatabase( 9444): android.database.sqlite.SQLiteException: not an error(Sqlite code 0): Could not open the database in read/write mode.,(OS error - 30:Read-only file system)
E/SQLiteDatabase( 9444): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 9444): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 9444): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 9444): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 9444): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 9444): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 9444): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:819)
E/SQLiteDatabase( 9444): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:804)
E/SQLiteDatabase( 9444): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:707)
E/SQLiteDatabase( 9444): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1195)
E/SQLiteDatabase( 9444): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 9444): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 9444): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 9444): 	at com.android.providers.contacts.aggregation.ContactAggregator.<init>(ContactAggregator.java:336)
E/SQLiteDatabase( 9444): 	at com.android.providers.contacts.aggregation.ProfileAggregator.<init>(ProfileAggregator.java:43)
E/SQLiteDatabase( 9444): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1933)
E/SQLiteDatabase( 9444): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2037)
E/SQLiteDatabase( 9444): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1843)
E/SQLiteDatabase( 9444): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 9444): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 9444): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 9444): Couldn't open profile.db for writing (will try read-only):
E/SQLiteOpenHelper( 9444): android.database.sqlite.SQLiteException: not an error(Sqlite code 0): Could not open the database in read/write mode.,(OS error - 30:Read-only file system)
E/SQLiteOpenHelper( 9444): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 9444): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 9444): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 9444): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 9444): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 9444): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 9444): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:819)
E/SQLiteOpenHelper( 9444): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:804)
E/SQLiteOpenHelper( 9444): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:707)
E/SQLiteOpenHelper( 9444): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1195)
E/SQLiteOpenHelper( 9444): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 9444): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 9444): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 9444): 	at com.android.providers.contacts.aggregation.ContactAggregator.<init>(ContactAggregator.java:336)
E/SQLiteOpenHelper( 9444): 	at com.android.providers.contacts.aggregation.ProfileAggregator.<init>(ProfileAggregator.java:43)
E/SQLiteOpenHelper( 9444): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1933)
E/SQLiteOpenHelper( 9444): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2037)
E/SQLiteOpenHelper( 9444): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1843)
E/SQLiteOpenHelper( 9444): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 9444): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 9444): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 9444): (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,E/AndroidRuntime( 9444): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 9444): Process: android.process.acore, PID: 9444
E/AndroidRuntime( 9444): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database(Sqlite code 8),(OS error - 2:No such file or directory)
E/AndroidRuntime( 9444): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 9444): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 9444): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 9444): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 9444): 	at android.database.sqlite.SQLiteDatabase.executeSql(SQLiteDatabase.java:1726)
E/AndroidRuntime( 9444): 	at android.database.sqlite.SQLiteDatabase.execSQL(SQLiteDatabase.java:1650)
E/AndroidRuntime( 9444): 	at com.android.providers.contacts.ContactsDatabaseHelper.onOpen(ContactsDatabaseHelper.java:1386)
E/AndroidRuntime( 9444): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:266)
E/AndroidRuntime( 9444): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/AndroidRuntime( 9444): 	at com.android.providers.contacts.aggregation.ContactAggregator.<init>(ContactAggregator.java:336)
E/AndroidRuntime( 9444): 	at com.android.providers.contacts.aggregation.ProfileAggregator.<init>(ProfileAggregator.java:43)
E/AndroidRuntime( 9444): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1933)
E/AndroidRuntime( 9444): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2037)
E/AndroidRuntime( 9444): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1843)
E/AndroidRuntime( 9444): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 9444): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 9444): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/art     ( 9379): Can not find class: Lhuawei/android/view/FrameLayout;
,I/art     ( 9379): Can not find class: Lhuawei/android/widget/FrameLayout;
,I/art     ( 9379): Can not find class: Lhuawei/android/view/EditText;
,I/art     ( 9379): Can not find class: Lhuawei/android/widget/EditText;
,E/textview( 9379): initAddtionalStyle default
,I/art     ( 9379): Can not find class: Lhuawei/android/view/ProgressBar;
I/art     ( 9379): Can not find class: Lhuawei/android/widget/ProgressBar;
,I/CommonUtilMethods isFastScrollerIsVisibleToChilds( 9379): fieldValue : protected java.lang.Object android.widget.AbsListView.getScrollerInner()

```
