#### Test 61248225a3bd1fe_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
D/LCardEmulationManager( 1818): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1818): getDefaultRoute
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/LogService_Receiver( 3130): getAction is : android.intent.action.BOOT_COMPLETED
E/LogService_Receiver( 3130): Log Enable Check Value :0
E/LogService_Receiver( 3130): Log Enable Check Value :0
E/LogService_Receiver( 3130): Log Enable Check Value :0
E/LogService_Receiver( 3130): Log Enable Check Value :0
E/LogService_Receiver( 3130): Log Enable Check Value :0
E/LogService_Receiver( 3130): Log Enable Check Value :0
E/bt-btif ( 2091): bta_dm_ctrl_features_rd_cmpl_cback Ctrl BLE feature read failed: status :1
I/GKI_LINUX( 2091): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 2091): warning : media task started media_task_refcnt 1 
E/bt-btif ( 2091): Calling BTA_HhEnable
E/bt-btif ( 2091): btif_storage_get_adapter_property service_mask:0x1201c8
I/bt-btif ( 2091): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 2091): Address is:F8:95:C7:87:85:54
D/BT_PROF_AUDIO( 2091): created moving average (N=100)
D/BT_PROF_AUDIO( 2091): reset rate average
W/bt-btif ( 2091): overflow 0, enter 0, exit 0
V/BluetoothOppNotification( 2091): new notify threadi!
V/BluetoothOppNotification( 2091): send delay message
V/BluetoothOppProvider( 2091): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
W/bt-smp  ( 2091): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 2091): Plain text(LSB ~ MSB) = 78 ac 48 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2091): Encrypted text(LSB ~ MSB) = e6 68 c0 36 04 86 f9 59 ae 8f 00 a6 8d 6e cf 85 
W/bt-btm  ( 2091): Stopping oneshot timer
V/BluetoothOppProvider( 2091): created cursor android.database.sqlite.SQLiteCursor@26029f0f on behalf of 
V/BluetoothOppNotification( 2091): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 2091): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 2091): created cursor android.database.sqlite.SQLiteCursor@102e7b9c on behalf of 
V/BluetoothOppNotification( 2091): outbound: succ-0  fail-0
I/NotificationManager( 2091): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
V/BluetoothOppNotification( 2091): outbound notification was removed.
V/BluetoothOppProvider( 2091): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 2091): created cursor android.database.sqlite.SQLiteCursor@41c59a5 on behalf of 
V/BluetoothOppNotification( 2091): inbound: succ-0  fail-0
I/NotificationManager( 2091): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
,V/BluetoothOppNotification( 2091): inbound notification was removed.
V/BluetoothOppProvider( 2091): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 2091): created cursor android.database.sqlite.SQLiteCursor@1e00a17a on behalf of 
--------- beginning of system
I/ActivityManager(  855): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3159 uid=10008 gids={50008, 9997} abi=armeabi-v7a
D/BluetoothAdapterProperties( 2091): Name is: G3s-1
D/BluetoothAdapterProperties( 2091): Scan Mode:20
D/BluetoothManagerService(  855): Bluetooth Adapter name changed to G3s-1
D/BluetoothManagerService(  855): Stored Bluetooth name: G3s-1
I/ActivityManager(  855): Killing 2898:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
D/BluetoothAdapterProperties( 2091): Discoverable Timeout:120
E/bt-btif ( 2091): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 2091): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
E/bt-btif ( 2091): btif_sock_init: !radio_req && !rfc_init
I/bt-btif ( 2091): BTA_JvEnable
E/bt-btif ( 2091): btsock_vendor_hci_init: !vhci_init
D/bt-btif ( 2091): btsock_ctrl_hci_init(L191): poll handle:6
D/bt-btif ( 2091): init_hci_slots(L136): in
D/IOP_DB_BT( 2091): db_open: file /etc/bluetooth/iop_bt.db
D/IOP_DB_BT( 2091): db_open: db_open : handle 2691303388l, read 11046 bytes onto local cache
D/IOP_DB_BT( 2091): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 2091): db_query: result 1
I/        ( 2091): iop_db_open: iop_db_open status 0
E/bt-btif ( 2091): btif_sock_init, radio_req:0, rfc_init:1, vhci_init:1
D/bt-btif ( 2091): btsock_ctrl_hci_init(L191): poll handle:6
I/bt-btif ( 2091): bta_pan_co_init
D/bte_conf( 2091): Device ID record 1 : primary
D/bte_conf( 2091):   vendorId            = 00c4
D/bte_conf( 2091):   vendorIdSource      = 0001
D/bte_conf( 2091):   product             = 13a1
D/bte_conf( 2091):   version             = 1000
D/bte_conf( 2091):   clientExecutableURL = 
D/bte_conf( 2091):   serviceDescription  = 
D/bte_conf( 2091):   documentationURL    = 
D/bte_conf( 2091): bte_load_did_conf no section named DID2.
I/bt-btif ( 2091): HAL bt_hal_cbacks->adapter_state_changed_cb
E/bt-btif ( 2091): btif_hf_upstreams_evt: wrong handle = 26465 
I/bt-btif ( 2091): HAL bt_op_callbacks->opc_state_cb
D/BluetoothOPPServiceJni( 2091): opc_state_cb(L140):  opc_state_cb state:0
D/OppService( 2091): onOpcStateChange()
I/bt-btif ( 2091): HAL bt_op_callbacks->ops_state_cb
D/BluetoothOPPServiceJni( 2091): ops_state_cb(L223):  ops_state_cb state:0
D/OppService( 2091): onOpsStateChange() :0
I/bt-btif ( 2091): HAL bt_fts_callbacks->operation_cmpl_cb
D/BluetoothFTPServiceJni( 2091): operation_cmpl_callback(L192):  oper:3 status:0
I/BluetoothFTPService( 2091): onFtpServerEnabled: /storage
D/BluetoothPanServiceJni( 2091): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 2091): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 2091): ScanMode =  20
D/BluetoothAdapterProperties( 2091): State =  11
D/BluetoothAdapterProperties( 2091): mDiscoverableTimeout = 120
D/BluetoothAdapterProperties( 2091): Setting state to 12
I/BluetoothAdapterState( 2091): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService(1029591394)( 2091): updateAdapterState() - Broadcasting state to 1 receivers.
D/OppService( 2091): Recieved MESSAGE_OPC_ENABLE
D/LGBluetoothFeatureConfig( 2091): isPrivacyLogsEnabled : true
D/BluetoothManagerService(  855): Message: 60
D/BluetoothManagerService(  855): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
I/BluetoothAdapterState( 2091): Entering On State
I/BluetoothAdapterState( 2091): Entering On State from state = 11
D/BluetoothManagerService(  855): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothA2dp(  855): onBluetoothStateChange: up=true
D/BluetoothAdapterService(1029591394)( 2091): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3eee00c8
D/BluetoothAdapterService(1029591394)( 2091): isQuetModeEnabled() - Enabled = false
D/BluetoothAdapterService(1029591394)( 2091): autoConnect() - Initiate auto connection on BT on...
D/BluetoothAdapterService( 2091): [BTUI] autoConnect() : not allowed
D/LGBluetoothServiceAdapter( 2091): [BTUI] OnState
D/LGBluetoothServiceAdapter( 2091): [BTUI]         global_name: G3s-1
D/LGBluetoothServiceAdapter( 2091): [BTUI]         local_name: G3s-1
D/BluetoothHeadset( 1783): onBluetoothStateChange: up=true
D/OppService( 2091): Recieved MESSAGE_OPS_ENABLE
I/bt-btif ( 2091): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothHeadset( 1783): onBluetoothStateChange: up=true
D/BluetoothHeadset(  855): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1783): onBluetoothStateChange: up=true
D/BluetoothAdapterService(1029591394)( 2091): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3eee00c8
D/BluetoothAdapterService(1029591394)( 2091): isQuetModeEnabled() - Enabled = false
D/BluetoothAdapterService(1029591394)( 2091): autoConnect() - Initiate auto connection on BT on...
D/BluetoothAdapterService( 2091): [BTUI] autoConnect() : not allowed
D/BluetoothA2dp( 2091): onBluetoothStateChange: up=true
D/bt_h4   ( 2091): vendor lib postload completed
D/BluetoothAdapterProperties( 2091): Scan Mode:21
I/bt-btif ( 2091): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 2091): Discoverable Timeout:120
W/libprocessgroup(  855): failed to open /acct/uid_10069/pid_2898/cgroup.procs: No such file or directory
E/BluetoothManagerService(  855): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService(  855): Bluetooth State Change Intent: 11 -> 12
D/BluetoothManagerService(  855): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  855): Message: 40
D/BluetoothManagerService(  855): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothAdapterService(1029591394)( 2091): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3eee00c8
D/BluetoothAdapterService(1029591394)( 2091): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3eee00c8
D/LGBluetoothAPIService( 1836): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1836): Message: 1
D/BluetoothAdapterService(1029591394)( 2091): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3eee00c8
D/LGBluetoothAPIService( 1836): MESSAGE_BOOT_COMPLETED
I/BluetoothMapService( 2091): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 2091): STATE_ON
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1372): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
I/LGBluetoothAPIService( 1836): [BTUI] LGBluetoothAPIService Binding Success
W/ContextImpl( 2438): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/BluetoothAdapterService( 2091): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d5e5162
V/BluetoothPbapService( 2091): Pbap Service onCreate
V/BluetoothPbapService( 2091): Starting PBAP service
D/BluetoothAdapterService(1029591394)( 2091): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3eee00c8
D/LGBluetoothPbapAdapter( 2091): [BTUI] getInstance : create
V/BluetoothPbapService( 2091): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 2091): state: 12
V/BluetoothMapService( 2091): Handler(): got msg=1
D/BluetoothMapMasInstance( 2091): Map Service startRfcommSocketListener
D/BluetoothMapMasInstance( 2091): MAS initSocket()
D/LGBluetoothAPIServer( 2091): [BTUI] onCreate()
D/LGBluetoothAPIServer( 2091): [BTUI] onBind()
V/BluetoothPbapReceiver( 2091): PbapReceiver onReceive 
D/BluetoothMapMasInstance( 2091):   masId = 00
D/BluetoothMapMasInstance( 2091):   msgTypes = 0e
D/BluetoothMapMasInstance( 2091):   masName = SMS/MMS
D/BluetoothMapMasInstance( 2091):   SDP string = 000eSMS/MMS
V/BluetoothPbapReceiver( 2091): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 2091): ***********state = 12
D/LGBluetoothAPIService( 1836): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1836): Message: 100
D/LGBluetoothAPIService( 1836): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothManagerService(  855): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothPbapService( 2091): Handler(): got msg=1
V/BluetoothPbapService( 2091): Pbap Service startRfcommSocketListener
D/BluetoothAdapterService(1029591394)( 2091): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3eee00c8
D/LocalBluetoothProfileManager( 2438): Adding local A2DP profile
W/BluetoothAdapter( 2091): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothPbapService( 2091): Pbap Service initSocket
I/bt-btif ( 2091): BTA_JvCreateRecordByUser
I/bt-btif ( 2091): BTA_JvRfcommStartServer
D/BluetoothManagerService(  855): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGBluetoothServiceAdapter( 2091): [BTUI] createSocketChannel FD=83 mFd=0
V/BluetoothMapMasInstance( 2091): Succeed to create listening socket 
D/BluetoothMapMasInstance( 2091): Accepting socket connection...
D/BluetoothManagerService(  855): Message: 30
W/BluetoothAdapter( 2091): getBluetoothService() called with no BluetoothManagerCallback
D/LocalBluetoothProfileManager( 2438): Adding local HEADSET profile
I/bt-btif ( 2091): BTA_JvCreateRecordByUser
I/bt-btif ( 2091): BTA_JvRfcommStartServer
D/LGBluetoothServiceAdapter( 2091): [BTUI] createSocketChannel FD=85 mFd=83
V/BluetoothPbapService( 2091): Succeed to create listening socket 
V/BluetoothPbapService( 2091): Accepting socket connection...
D/BluetoothManagerService(  855): Message: 30
D/BluetoothManagerService(  855): Message: 30
V/OneTimeInitializerReceiver( 3159): OneTimeInitializerReceiver.onReceive
D/BluetoothManagerService(  855): Message: 30
D/LocalBluetoothProfileManager( 2438): Adding local MAP profile
D/BluetoothMap( 2438): Create BluetoothMap proxy object
D/BluetoothManagerService(  855): Message: 30
V/OneTimeService( 3159): OneTimeService.onHandleIntent
I/ActivityManager(  855): Start proc com.android.cellbroadcastreceiver for broadcast com.android.cellbroadcastreceiver/.CellBroadcastReceiver: pid=3190 uid=10016 gids={50016, 9997} abi=armeabi-v7a
D/BluetoothManagerService(  855): Message: 30
D/LocalBluetoothProfileManager( 2438): LocalBluetoothProfileManager construction complete
V/BluetoothPbapService( 2091): Pbap Service onBind
D/LGBluetoothUserBindClient( 2438): [BTUI] initUserBindClient
W/ContextImpl( 2438): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 2438): finishStartingService: stopping service
D/BluetoothA2dp( 2438): Proxy object connected
D/A2dpProfile( 2438): Bluetooth service connected
D/BluetoothAdapterService(1029591394)( 2091): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3eee00c8
D/BluetoothHeadset( 2438): Proxy object connected
D/HeadsetProfile( 2438): Bluetooth service connected
D/BluetoothAdapterService(1029591394)( 2091): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3eee00c8
D/BluetoothInputDevice( 2438): Proxy object connected
D/HidProfile( 2438): Bluetooth service connected
D/BluetoothAdapterService(1029591394)( 2091): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3eee00c8
D/BluetoothPan( 2438): BluetoothPAN Proxy object connected
D/PanProfile( 2438): Bluetooth service connected
D/BluetoothAdapterService(1029591394)( 2091): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3eee00c8
D/BluetoothMap( 2438): Proxy object connected
D/MapProfile( 2438): Bluetooth service connected
D/BluetoothMap( 2438): getConnectedDevices()
D/BluetoothAdapterService(1029591394)( 2091): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3eee00c8
V/BluetoothMapService( 2091): getConnectedDevices()
D/BluetoothPbap( 2438): Proxy object connected
D/PbapServerProfile( 2438): Bluetooth service connected
D/LGBluetoothUserBindClient( 2438): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 2438): onReceive
D/LGBluetoothFeatureConfig( 2438): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 2438): [BTUI] FileNotFound: readProperty
I/ActivityManager(  855): Killing 2625:com.lge.qremote/u0a106 (adj 15): empty #11
D/AndroidRuntime( 3180): 
D/AndroidRuntime( 3180): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3180): CheckJNI is OFF
D/CellBroadcastReceiverApp( 3190): CellBroadcastReceiverApp, onCreate()
D/MultiSimWrapper( 3190): [MessageUtils] isTripleSimEnabled=false
D/MultiSimWrapper( 3190): [isMultiSimEnabled] = false
D/MultiSimWrapper( 3190): [MessageUtils] isTripleSimEnabled=false
D/CellBroadcastReceiver( 3190): startInit() started. iccLoaded=false init_complete=false
D/CommonUtil( 3190): spn is empty. use default value as ""
D/CommonUtil( 3190): getRuntimeImsiCode[]
D/CommonUtil( 3190): spn is empty. use default value as ""
D/CommonUtil( 3190): getRuntimeImsiCode[]
D/CommonUtil( 3190): simOperator =
D/CommonUtil( 3190): getRuntimeMccCode[0]
D/CellBroadcastReceiver( 3190): single sim : imsiCode= MccCode=0
E/CellBroadcastReceiver( 3190): IMSI value is NOT available yet. DO NOT PROCESS NEXT STEP.
D/CellBroadcastReceiver( 3190): onReceive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.cellbroadcastreceiver/.CellBroadcastReceiver (has extras) }
D/CellBroadcastReceiver( 3190): ACTION_BOOT_COMPLETED received.
W/libprocessgroup(  855): failed to open /acct/uid_10106/pid_2625/cgroup.procs: No such file or directory
V/BluetoothOppReceiver( 2091): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
D/CellBroadcastAlertService( 3190): myUid on onStartCommand() =0
D/CellBroadcastAlertService( 3190): [MmsConfig] isSupportEmotionalLED=true
V/BluetoothOppManager( 2091): restoreApplicationData! falsefalsenullnull
I/ActivityManager(  855): Start proc com.lge.email for broadcast com.lge.email/.ui.widget.EmailWidgetProvider: pid=3228 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
V/BluetoothSapReceiver( 2091): [BTUI] checkServiceStart
D/CellBroadcastAlertService( 3190): [CB] getEmotionalLEDEffectEnabled= true
D/LGBluetoothStateChangeReceiver( 2091): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
I/CellBroadcastAlertService( 3190): startEmotionalLedService 
I/CellBroadcastAlertService( 3190): registerLEDObserver
D/AuthorizationBluetoothService( 1765): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/CellBroadcastAlertService( 3190): registerLEDObserver REGISTER
D/CellBroadcastAlertService( 3190): make mBroadcastDb
D/CellBroadcastAlertService( 3190): after ACTION_BOOT_COMPLETED cursor, Db closed!!
I/ActivityManager(  855): Killing 2926:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
D/AndroidRuntime( 3180): Calling main entry com.android.commands.am.Am
W/libprocessgroup(  855): failed to open /acct/uid_10089/pid_2926/cgroup.procs: No such file or directory
I/ActivityManager(  855): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  855): setTaskToReturnTo : TaskRecord{32119da5 #224 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  855): setTaskToReturnTo : TaskRecord{32119da5 #224 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
W/ResourcesManager( 3228): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3228): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/WindowStateEx(  855): AppWindowTokenEx init.. 
W/ResourcesManager( 3228): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/ContextHelper(  855): convertTheme. context->name=com.example.hello themeResourceId=16973833
D/InputDispatcher(  855): Focus left window: Window{370ff248 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 3180): Shutting down VM
I/[LGHome]EVENT( 1909): [Launcher.java:986:onPause()]onPause
D/SplitWindow(  855): check instance of lgWin Window{2aa08507 u0 Starting com.example.hello}
I/ActivityManager(  855): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3247 uid=10317 gids={50317, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1909): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/HotwordDetector( 1969): Closing mic
I/MicrophoneInputStream( 1969): mic_close com.google.android.apps.gsa.speech.audio.u@3c7572cf
V/AudioRecord( 1969): stop()
D/AudioRecord( 1969): AudioRecord->stop()
V/AudioFlinger(  280): RecordHandle::stop()
V/AudioFlinger(  280): RecordThread::stop
I/QCNEJ   ( 1872): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1872): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-50 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.114 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-03-01 15:33:20.006 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/AudioFlinger(  280): Record stopped OK
V/AudioPolicyManager(  280): stopInput() input 17
V/AudioPolicyService(  280): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  280): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  280): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  280): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  280): ThreadBase::setParameters() routing=0
V/AudioFlinger(  280): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  280): processConfigEvents_l() remaining events 1
V/AudioFlinger(  280): processConfigEvents_l() DONE thread 0xb3a4d000
D/audio_hw_primary(  280): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
I/[LGHome]EVENT( 1909): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  855): Starting window displayed
I/SystemUI[Framework](  855): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.example.hello
D/PhoneStatusBar( 1372): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  855): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  855): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  855): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  855): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2c57ac8e,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  855): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
V/audio_hw_primary(  280): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  280): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  280): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  280): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  280): disable_audio_route: exit
E/audio_hw_primary(  280): disable_snd_device: enter 144
D/hardware_info(  280): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  280): disable_snd_device: snd_device(144: lg-vr-handset-mic)
I/[SystemUI]NavigationThemeResource( 1372): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1372):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1372): , Keyguard show=false, IME shown=false, Panel expanded=false
V/audio_hw_primary(  280): stop_input_stream: exit: status(0)
V/audio_hw_primary(  280): in_standby: exit:  status(0)
V/AudioFlinger(  280): RecordThread: loop stopping
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioPolicyManager(  280): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  280): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  280): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  280): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioPolicyService(  280): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  280): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  280): setParameters(): io 17, keyvalue hotword_active=0, calling pid 280
V/AudioFlinger(  280): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  280): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  280): RecordThread: loop starting
V/AudioFlinger(  280): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  280): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  280): in_set_parameters: exit: status(0)
V/AudioFlinger(  280): processConfigEvents_l() DONE thread 0xb3a4d000
V/AudioFlinger(  280): RecordThread: loop stopping
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioRecord( 1969): stop()
D/BarTransitions( 1372): draw background and invalidate : color = 10000000
D/BarTransitions( 1372): draw background and invalidate : color = 13121212
V/AudioRecord( 1969): stop()
V/AudioRecord( 1969): stop()
V/AudioFlinger(  280): RecordHandle::stop()
V/AudioFlinger(  280): RecordThread::stop
V/AudioPolicyManager(  280): releaseInput() 17
V/AudioPolicyManager(  280): closeInput(17)
V/AudioFlinger(  280): closeInput() 17
V/AudioSystem(  280): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1969): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  280): ThreadBase::exit
V/AudioFlinger(  280): RecordThread: loop starting
V/AudioFlinger(  280): RecordThread 0xb3a4d000 exiting
D/audio_hw_primary(  280): adev_close_input_stream: enter:stream_handle(0xb546dd40)
D/audio_hw_primary(  280): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/audio_hw_primary(  280): in_standby: exit:  status(0)
V/AudioSystem(  855): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  280): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  280): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  280): releaseInput() exit
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioFlinger(  280): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioPolicyService(  280): AudioCommandThread() processing update audio port list
V/AudioFlinger(  280): removeClient_l() pid 1969, calling pid 280
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioSystem( 1372): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  280): releasing 16 from 1969 for -1
V/AudioFlinger(  280):  decremented refcount to 0
V/AudioFlinger(  280): purging stale effects
V/AudioSystem( 1783): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2091): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2786): ioConfigChanged() event 4, ioHandle 17
I/HotwordRecognitionRnr( 1969): Stopping hotword detection.
,I/HotwordRecognitionRnr( 1969): Hotword detection finished
D/ContextHelper( 3247): convertTheme. context->name=com.example.hello themeResourceId=16973833
,V/GLSActivity( 1765): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1765): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/WebViewFactory( 3247): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3247): Time to load native libraries: 3 ms (timestamps 4590-4593)
I/LibraryLoader( 3247): Expected native library version number "",actual native library version number ""
,I/LGEmail ( 3228): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 3228): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,V/WebViewChromiumFactoryProvider( 3247): Binding Chromium to main looper Looper (main, tid 1) {2fe52dd6}
I/LibraryLoader( 3247): Expected native library version number "",actual native library version number ""
I/chromium( 3247): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3247): Initializing chromium process, singleProcess=true
,W/art     ( 3247): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3247): ApplicationContext is null in ApplicationStatus
W/chromium( 3247): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3247): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3247): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3247): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 3247): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 3247): Build Date: 03/02/15 Mon
I/Adreno-EGL( 3247): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 3247): Remote Branch: 
I/Adreno-EGL( 3247): Local Patches: 
I/Adreno-EGL( 3247): Reconstruct Branch: 
I/WebViewFactory( 1969): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/NotificationManager( 1969): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,V/AudioPolicyService(  280): registerClient() client 0xb39b56c0, uid 10317
D/BluetoothManagerService(  855): Message: 20
D/BluetoothManagerService(  855): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2ef1cbfc:true
D/BluetoothAdapterService(1029591394)( 2091): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3eee00c8
,I/LibraryLoader( 1969): Time to load native libraries: 2 ms (timestamps 4827-4829)
,I/LibraryLoader( 1969): Expected native library version number "",actual native library version number ""
W/art     ( 1969): Attempt to remove local handle scope entry from IRT, ignoring
,I/art     ( 2037): Explicit concurrent mark sweep GC freed 2506(97KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.991ms total 37.576ms
,D/libc-netbsd( 1765): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1765): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1765): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1765): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  855): Start proc com.lge.mlt for broadcast com.lge.mlt/.MptOnBootReceiver: pid=3310 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,W/art     ( 3247): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3247): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3247): CordovaWebView is running on device made by: LGE
,W/art     ( 3247): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3247): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 1969): Attempt to remove local handle scope entry from IRT, ignoring
D/libc-netbsd( 1969): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1969): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
E/BandwidthController(  276): [LG DATA] No such appUid: 10042
D/DnsProxyListener(  276): App 10042 tries DNS query. Accept family:2 protocol:0
,D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 1765): propertyValue:false
I/Activity( 3247): Activity.onPostResume() called 
,D/OpenGLRenderer( 3247): Render dirty regions requested: true
I/OpenGLRenderer( 3247): Initialized EGL, version 1.4
D/OpenGLRenderer( 3247): Enabling debug mode 0
D/Atlas   ( 3247): Validating map...
,D/SplitWindow(  855): check instance of lgWin Window{b0550eb u0 com.example.hello/com.example.hello.MainActivity}
W/chromium( 3247): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  855): Killing 2880:android.process.media/u0a19 (adj 15): empty #11
W/libprocessgroup(  855): failed to open /acct/uid_10019/pid_2880/cgroup.procs: No such file or directory
,W/ContextImpl( 3310): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.mlt.MptOnBootReceiver.onReceive:107 android.app.ActivityThread.handleReceiver:2663 
D/InputDispatcher(  855): Focus entered window: Window{b0550eb u0 com.example.hello/com.example.hello.MainActivity}
,I/ActivityManager(  855): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=3343 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,D/libc-netbsd(  276): res_queryN name = xxxxx succeed
,W/InputMethodManagerService(  855): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
I/ActivityManager(  855): Displayed com.example.hello/.MainActivity: +1s184ms
I/Timeline(  855): Timeline: Activity_windows_visible id: ActivityRecord{226957a u0 com.example.hello/.MainActivity t224} time:45337
,D/ConnectivityService(  855): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.conn.CONNECTIVITY_CHANGE at null
I/Timeline( 3247): Timeline: Activity_idle id: android.os.BinderProxy@1261069d time:45350
,D/GpsLocationProvider(  855): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  276): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/LocSvc_java(  855): onReceive
D/LocSvc_java(  855): got connectivity action
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/LocSvc_java(  855): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  855): Sending msg: 4 arg1:1 arg2:1
E/BandwidthController(  276): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  276): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
E/MPT MptOnPowerWatcher( 3310): MptOnPowerWatcher
,D/LocSvc_java(  855): getAGpsConnectionInfo connType - 4
E/dbFlushManager( 3310): Handler is not ready.
E/dbFlushManager( 3310): It's going to sleep routine until the message handler is generated.
D/LocSvc_java(  855): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  855): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  855): Sending msg: 5 arg1:0 arg2:1
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  276): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd( 1765): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1765): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  855): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=3369 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,V/WifiInternetCheck(  855): Single check msg out of sync, ignoring.
W/BindingManager( 3247): Cannot call determinedVisibility() - never saw a connection for the pid: 3247
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out(  855): propertyValue:false
I/System.out(  855): propertyValue:false
I/System.out(  855): propertyValue:false
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  855): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=3387 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,E/MPT MptOnPowerWatcher( 3310): startListen
I/chromium( 3247): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/ActivityManager(  855): enqueue in BackgroundQueue #69 Intent=Intent { act=com.lge.qremote.action.wait_loading flg=0x14 cmp=com.lge.qremote/.appwidget.RemoteAppWidgetProvider (has extras) }
,W/ResourcesManager( 3369): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3369): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3369): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,D/GpsLocationProvider(  855): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/AlarmManagerService(  855): Setting time of day to sec=1456842794
W/AlarmManagerService(  855): Unable to set rtc to 1456842794: Invalid argument
D/LocSvc_java(  855): NTP server returned: 1456842794581 (Tue Mar 01 15:33:14 GMT+01:00 2016) reference: 45611 certainty: 63 system time offset: -3
D/LocSvc_java(  855): Sending msg: 10 arg1:0 arg2:1
,D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
D/LocSvc_java(  855): reportXtraServer 
D/LocSvc_java(  855):  server1=http://xtrapath1.izatcloud.net/xtra2.bin
D/LocSvc_java(  855):  server2=http://xtrapath2.izatcloud.net/xtra2.bin
D/LocSvc_java(  855):  server3=http://xtrapath3.izatcloud.net/xtra2.bin
D/LocSvc_java(  855): xtraDownloadRequest
D/LocSvc_java(  855): Sending msg: 6 arg1:0 arg2:1
I/[SystemUI]Clock( 1372): onReceive = android.intent.action.TIME_SET
W/ActivityManager(  855): getTasks: caller 10024 is using old GET_TASKS but privileged; allowing
,I/LgeClockWidgetControlView( 1372): time changed, timezoneChanged : false
D/WeatherService( 2780): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 15:33:14
I/[LGHome]LGDateChangeReceiver( 1909): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=1 currentDate=-1 dayofweek=3 currentDayOfWeek=-1
D/WeatherService( 2780): 2 : requestRefreshAppWidget, isUpdateStart : false
,W/ResourcesManager( 3387): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/[LGHome]LGCalendarIcon( 1909): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 1
,D/UpdateThreadPoolManager( 2780): 2 : This is isUpdating : false
D/WeatherService( 2780): 2 : requestRefreshAppWidget, isUpdating : false
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  276): App 1000 tries DNS query. Accept family:0 protocol:0
D/WeatherAncestor( 2780): 2 : buildUpdate, appWidgetId: 2
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
I/[LGHome]LGCalendarIcon( 1909): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 1
,D/JsMessageQueue( 3247): Set native->JS mode to OnlineEventsBridgeMode
I/[LGHome]Launcher( 1909): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  855): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=3414 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
E/GpsLocationProvider(  855): No APN found to select.
,E/AndroidProtocolHandler( 3247): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/WeatherTheme( 2780): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2780): 2 : Fixed theme : optimus
,D/WeatherReflect( 2780): 2 : Map key string is -2
,D/lim     ( 2780): 2 : time = 15:33
I/WeatherReflect( 2780): Model Name : LG-D722
D/WeatherTheme( 2780): 2 : exactly same view!
D/WeatherTheme( 2780): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
D/WeatherService( 2780): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 15:33:14
,D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out(  855): propertyValue:false
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/AppConfig( 3369): Total System Memory = 906309632
,I/GalleryUtils( 3369): Application Heap = 96 MB
E/ActivityThread( 2308): Failed to find provider info for com.android.contacts.metadata
I/AppConfig( 3369): App Tier : NOT_DEF
,D/SystemHelper( 3369): region [EU], country [EU], operator [OPEN], sub-operator []
,D/LgeGpsConstants(  855): Can't find 'ext_gps.conf'!!
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  276): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  276): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  855): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=3449 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ALBootInit( 3414): ====action==>android.intent.action.TIME_SET
D/SyncManager(  855): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 38134, reason: UserStart, SyncResult: databaseError: true stats []
,D/ALBootInit( 3414): Alarm ALBootInit: TIME_SET
D/Alarms  ( 3414): [setNextAlert] start
,D/Alarms  ( 3414): [setNextAlert] (1)
D/Alarms  ( 3414):  minTime  = 0
,D/Alarms  ( 3414):  -- OK multi -- 0
E/jeny.kim( 3414): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 3414): [setNextAlert]setNextAlert temp_AlarmLinkText + 
,D/SyncManager(  855): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 78851, reason: UserStart
,D/LocSvc_java(  855): calling native_inject_xtra_data
D/LocSvc_java(  855): Sending msg: 11 arg1:0 arg2:1
W/ResourcesManager( 3449): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/NotificationManager(  855): android: cancelAsUser(716319171) by android
I/ActivityManager(  855): Start proc android.process.media for content provider com.android.providers.media/.MediaProvider: pid=3468 uid=10019 gids={50019, 9997, 2001, 3003, 1028, 1015, 3007, 4002, 1024, 1023} abi=armeabi
D/libc-netbsd( 1765): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1765): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1765): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1765): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/art     (  305): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 302us total 31.135ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 296us total 22.080ms
,I/CommonUtil( 3414): BUILD Operator: OPEN
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 315us total 22.291ms
D/Alarms  ( 3414): broadcastToWidgetProvider : false
,D/Alarms  ( 3414): Enter formatDayAndTime(final Context context, long timeInMiliSec)
,I/NotificationManager(  855): android: cancelAsUser(-1597574061) by android
V/SettingsProvider(  855): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,W/BackupManagerService(  855): dataChanged but no participant pkg='com.android.providers.settings' uid=10010
I/ActivityManager(  855): Killing 2997:com.android.keychain/1000 (adj 15): empty #11
,D/GCM     ( 1765): COMPAT: Multi user not supported
D/jxcore_app_log( 3247): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1618809856
,D/JX-Cordova( 3247): jxcore cordova android initializing
D/CalendarProvider2( 3449): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@22fd0f75
,W/libprocessgroup(  855): failed to open /acct/uid_1000/pid_2997/cgroup.procs: No such file or directory
I/DigitalAppWidgetProvider( 3414): onReceive: android.intent.action.TIME_SET
V/DigitalAppWidgetProvider( 3414): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3da9f44
D/CalendarProvider2( 3449): [getOrCreateCalendarAlarmManager]
V/DigitalAppWidgetProvider( 3414): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3da9f44
I/CalendarProvider2( 3449): Created com.android.providers.calendar.CalendarAlarmManager@2fe52dd6(com.android.providers.calendar.CalendarProvider2@22fd0f75)
W/jxcore-log( 3247): Initializing JXcore engine
D/CalendarReceiver( 3449): [onReceive] intent = Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.providers.calendar/.CalendarReceiver (has extras) }
W/jxcore-log( 3247): JXcore engine is ready
D/CalendarReceiver( 3449): [onReceive] WakeLock new : CalendarReceiver_Provider, ReferenceCounted = true
D/QuickCoverProvider( 3414): onReceiver
D/CalendarReceiver( 3449): [onReceive] WakeLock acquire : CalendarReceiver_Provider
I/RlzPingService( 3343): Setting next ping for 1457447595543
I/NotificationManager(  855): android: cancelAsUser(2) by android
W/jxcore-log( 3247): Starting JXcore engine
D/CalendarReceiver( 3449): [onReceive] android.intent.action.BOOT_COMPLETED
D/CalendarProvider2( 3449): Scheduling check of next Alarm
I/NotificationManager( 1765): com.google.android.gms: cancel(0) by com.google.android.gms
I/ActivityManager(  855): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=3502 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/CalendarProvider2( 3449): SCHEDULE_ALARM_REMOVE
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  276): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/CalendarReceiver( 3449): [onReceive] WakeLock release : CalendarReceiver_Provider
W/ResourcesManager( 3502): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/SELinux ( 3468): SELinux: Loaded file_contexts from /file_contexts
E/SELinux ( 3468): SELinux:  Could not open /data/system/packages.list:  Permission denied.
W/SELinux ( 3468): SELinux:  Could not look up information for package com.android.providers.downloads, cannot restorecon cache.
E/SELinux ( 3468): SELinux: Could not set context for /data/data/com.android.providers.downloads/cache:  Permission denied
I/ActivityManager(  855): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.receiver.DmReceiver: pid=3525 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
E/LAlarm  (  855): Service started flags 0 startId 3
D/LGMediaProvider( 3468): [MediaScanner] sExternalSDPath : /storage/external_SD
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out(  855): propertyValue:false
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  276): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out(  855): propertyValue:false
V/LGMediaProvider( 3468): Attached volume: internal
W/m.example.hello( 3247): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7580]" dev="sockfs" ino=7580 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 3247): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 3247): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7737]" dev="sockfs" ino=7737 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 3247): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/m.example.hello( 3247): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/m.example.hello( 3247): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[17700]" dev="sockfs" ino=17700 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
D/CalendarApplication( 3502): CalendarApplication.onCreate()
V/WifiInternetCheck(  855): isHttpConnectionAvailable - We got a valid response : 204
D/PreferenceKeysParser( 3502): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 3502): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@1afdcf7b, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@76b0198, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@169c2df1, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@2fe52dd6, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@20fe857, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@3da9f44, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@3334b82d, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@3d5e5162, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@31c0b2f3, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@846bb0, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@b51aa29, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@385421ae, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@18a98b4f, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@36bc92dc, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@3531bfe5, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@1ec4aaba, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@b9d8d6b, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@3eee00c8, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@32437561, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@1e82b886, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@f859547, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@b466174, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@1261069d, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@1dc1d712, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@24fc3ee3, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@212220e0, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@ecc6f99, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@62525e, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@31a9e63f, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3d386b0c, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@18eb6c55, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@35fd366a, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@2360a75b, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@e872bf8, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@18c378d1, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@1cb04f36, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@28f85e37, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@33ff0fa4, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@1735d10d, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@4aa28c2, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@1ceaa6d3, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@28ef8210, lg
I/ActivityManager(  855): Killing 3021:com.android.contacts/u0a18 (adj 15): empty #11
D/GeneralPreferenceUtils( 3502): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 3502): [init]
I/Config  ( 3502): LGCalendar ver.4.40.17
I/Config  ( 3502): start check model
I/Config  ( 3502): start check native_ca
I/Config  ( 3502): Config Operator=OPEN, Country=EU
D/Config  ( 3502): [setDefaultValuesToPref]
D/Config  ( 3502): [parseProfiles]
D/ProfilesParser( 3502): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 3502): [debug_displayParseInfos] profile.operator = null
D/Config  ( 3502): [updateProfiletoCountryInfo]
D/GeneralPreference( 3502): [checkAndMigrateOldPreference]
V/LGMediaProvider( 3468): Attached volume: external
W/jxcore-log( 3247): Platform android
W/jxcore-log( 3247): 
,W/jxcore-log( 3247): Process ARCH arm
W/jxcore-log( 3247): 
W/libprocessgroup(  855): failed to open /acct/uid_10018/pid_3021/cgroup.procs: No such file or directory
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmNotiService.bootCompleted:575 com.lge.lgdmsclient.receiver.DmReceiver.onReceive:94 
,E/AgendaWidgetManager( 3502): [updateWidgets] 
V/DownloadManager( 3468): DownloadService onCreate
,E/LGDMClient( 3525): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
I/jxcore-log( 3247): JXcore Cordova bridge is ready!
I/jxcore-log( 3247): 
I/InitNotificationRingtoneService( 3502): Start InitializeAlertRingtoneService.onHandleIntent
W/jxcore-log( 3247): JXcore engine is started
I/Choreographer( 3247): Skipped 36 frames!  The application may be doing too much work on its main thread.
D/ALBootInit( 3414): ====action==>android.intent.action.BOOT_COMPLETED
D/LGDMClient( 3525): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/ALBootInit( 3414): Alarm ALBootInit: BOOT_COMPLETED
D/LGDMClient( 3525): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_BOOTUP_COMPLETE
I/AlertUtils( 3502): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,I/DownloadManager( 3468): in removeSpuriousFiles
I/ALProvider( 3414): delete where======= time <= 1456842796081  and  aindex > 0
D/LGDMClient( 3525): [DmUtil.java] [removeSilenceBootFile()] : [894] : Try to remove a Silence file
D/LGDMClient( 3525): [DmNotiService.java] [actionSystemBootComplete()] : [459] : CHECK_AUTO_UPDATE_PROCESS : 0 Call removeSilenceBootFile() 
,D/Alarms  ( 3414):  --- disableExpiredAlarms!!! isBooting : true
I/NotificationManager( 3468): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3468): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3468): created cursor android.database.sqlite.SQLiteCursor@846bb0 on behalf of 3468
,I/DownloadManager( 3468): in trimDatabase
V/DownloadManager( 3468): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3468): created cursor android.database.sqlite.SQLiteCursor@b51aa29 on behalf of 3468
D/Alarms  ( 3414): count ===>0
,E/jxcore-log( 3247): >> LGE-LG-D722
E/jxcore-log( 3247): 
I/jxcore-log( 3247): Total memory 906309632
I/jxcore-log( 3247): 
I/jxcore-log( 3247): Free memory 30613504
I/jxcore-log( 3247): 
I/jxcore-log( 3247): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3247): 
I/jxcore-log( 3247): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3247): 
D/Alarms  ( 3414): snoozeActivating scount==>0
D/Alarms  ( 3414): [setNextAlert] start
V/DownloadManager( 3468): DownloadService onStartCommand
I/LGDMClient( 3525): [DmNotiService.java] [actionSystemBootComplete()] : [467] : DM Service on boot completed
I/jxcore-log( 3247): userPath [ 'www', 'www' ]
I/jxcore-log( 3247): 
,I/jxcore-log( 3247): Size 720 1196
I/jxcore-log( 3247): 
D/Alarms  ( 3414): [setNextAlert] (1)
I/jxcore-log( 3247): Screen Brightness 255
I/jxcore-log( 3247): 
E/jxcore-log( 3247): Dummy Error Log.
E/jxcore-log( 3247): 
D/Alarms  ( 3414):  minTime  = 0
V/DownloadManager( 3468): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/LGDMClient( 3525): [DmClientController.java] [startService()] : [400] : startService(), DownloadService will be started in order to follow the start of DmClientController
W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.controller.DmClientController.startService:404 com.lge.lgdmsclient.dmclient.controller.DmClientController.getInstance:345 com.lge.lgdmsclient.service.DmNotiService.actionSystemBootComplete:474 
D/LGDMClient( 3525): [DmAgent.java] [<init>()] : [164] : DmAgent is started -> DmConstants.DMAgentState.mDmaState = 0
,D/LGDMClient( 3525): [DmClientController.java] [run()] : [178] : LooperSTART
I/LGDMClient( 3525): [DmCAConfigParser.java] [getInstance()] : [73] : DmsCAConfigParser sInstance null
E/ConnectivityChangeReceiver( 2308): Ignoring connectivity change
,D/LGDMClient( 3525): [DmPhoneSpecificInfo.java] [getPhoneSpecificInfo()] : [204] : Current MultiSimEnabled is false
,D/ConnectivityService(  855): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  855): dumpNetworkRequest
D/ConnectivityService(  855):     NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/ConnectivityService(  855):     Requests:
,D/ConnectivityService(  855):         NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  855):         NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  855):     Lingered:
D/ConnectivityService(  855): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  855): apparently satisfied.  currentScore=60
D/ConnectivityService(  855): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 2308): CM callback handler got msg 524290
D/LGDMClient( 3525): [DmPhoneSpecificInfo.java] [getPhoneSpecificInfo()] : [239] : getPhoneSpecificInfo: sim mccmnc(),spn(),gid(null),imsi(null)
I/LGDMClient( 3525): [DmCAConfigParser.java] [parse()] : [108] : parse
D/LGDMClient( 3525): [DmCAConfigParser.java] [setDefaultProfile()] : [490] : setDefaultProfile
D/LGDMClient( 3525): [DmCAConfigParser.java] [setDefaultProfile()] : [493] : filename : fota_dm_settings.xml
D/LGDMClient( 3525): [DmCAConfigParser.java] [setDefaultProfile()] : [506] : [UI4.1] Search [fota_dm_settings.xml]
D/LGDMClient( 3525): [DmCAConfigParser.java] [parse()] : [134] : [UI4.1] Search [fota_dm_settings.xml]
,D/LGDMClient( 3525): [DmAgentUtil.java] [setAutoAgentSchedule()] : [117] : IN setAutoAgentSchedule()
,I/art     (  855): Explicit concurrent mark sweep GC freed 41069(2MB) AllocSpace objects, 5(117KB) LOS objects, 33% free, 22MB/34MB, paused 3.200ms total 246.546ms
I/art     (  855): WaitForGcToComplete blocked for 175.555ms for cause Explicit
,D/MonthWidgetProvider( 3502): [onReceive]
D/CalendarWidgetProvider( 3502): [onReceive]
,D/CalendarWidgetProvider( 3502): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
W/HolidayIntentService( 3502): onHandleIntent
D/CalendarTypeController( 3502): [onUpdateAndInitCalendarTime]
D/HolidayDataLoader( 3502): readJsonAsset : holiday.json
D/WeekWidgetProvider( 3502): [onReceive]
D/CalendarWidgetProvider( 3502): [onReceive]
D/CalendarWidgetProvider( 3502): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 3502): [onUpdateAndInitCalendarTime]
D/WeatherAncestor( 2780): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 15:33:16
,D/UpdateThreadPoolManager( 2780): 2 : This is isUpdating : false
D/Weather_cast( 2780): 2 : set auto-update time : 3/1 18:33
D/WeatherAncestor( 2780): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 15:33:16
D/WeatherService( 2780): 2 : onStartCommand, intent!=null, action: android.intent.action.TIME_SET
,E/HolidayIntentService( 3502): onHandleIntent:holiday data empty
,I/ActivityManager(  855): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3568 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
W/ActivityManager(  855): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2780): 2 : Utils getTopActivity com.lge.launcher2 / true
I/art     (  855): Explicit concurrent mark sweep GC freed 2135(99KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 2.150ms total 153.251ms
,V/DownloadManager( 3468): created cursor android.database.sqlite.SQLiteCursor@3eee00c8 on behalf of 3468
D/Alarms  ( 3414):  -- OK multi -- 0
D/LGDMClient( 3525): [DmAgentUtil.java] [setAutoAgentSchedule()] : [126] :  cursor != null setAutoAgentSchedule()
D/WeatherService( 2780): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2780): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/LGDMClient( 3525): [DmAgentUtil.java] [setAutoAgentSchedule()] : [167] : SET ALARM setAutoAgentSchedule() = 20160303T212428
E/jeny.kim( 3414): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 3414): [setNextAlert]setNextAlert temp_AlarmLinkText + 
,I/CommonUtil( 3414): BUILD Operator: OPEN
D/Alarms  ( 3414): broadcastToWidgetProvider : false
D/Alarms  ( 3414): Enter formatDayAndTime(final Context context, long timeInMiliSec)
V/SettingsProvider(  855): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
D/CommonUtil( 3414): Enter deleteUnnecessaryToneItem() enter excepted tone uri value is null, preferparent value is  ALARM
,D/LGDMClient( 3525): [DmAgentUtil.java] [setAutoAgentSchedule()] : [185] : OUT setAutoAgentSchedule()
I/AlertUtils( 3502): [getCalendarNotiSoundURIFromCursor] getCount()= 21
D/LGDMClient( 3525): [DmAgent.java] [checkPostponed()] : [2062] : DMAGentState is: DmConstants.DMAgentState.mDmaState = 0
V/LGDMClient( 3525): [DmClientController.java] [handleMessage()] : [181] : DmClientController: run() - msg.what=31
D/LGDMClient( 3525): [DmAgent.java] [processRestartHandler()] : [1241] : DMAGentState is: DmConstants.DMAgentState.mDmaState = 0
D/CommonUtil( 3414): deleteUnnecessaryToneItem() -> Alarm Surviv Count is 0
D/CommonUtil( 3414): Exit deleteUnnecessaryToneItem()
I/AlertUtils( 3502): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
E/[LGE_FOTA] ( 3525): FOTA JNI_OnLoad
,E/[LGE_FOTA] ( 3525):  FOTAJNI_GetUAResult in
E/[LGE_FOTA] ( 3525): FOTAFS_Open /cache/fota/usd.dat, 0, handle : 1c
E/LGDMClient( 3525): [DmDownloadService.java] [onCreate()] : [56] : DmDownloadService.onCreate()
E/[LGE_FOTA] ( 3525): enUpdateState                : 0x00000000
E/[LGE_FOTA] ( 3525): stFWInfo.enState             : 0x00000000
E/[LGE_FOTA] ( 3525): stFWInfo.uiPkgOffset[0]     : 0x00000000
E/[LGE_FOTA] ( 3525): stFWInfo.uiPkgSize[0]       : 0x00000000
E/[LGE_FOTA] ( 3525): stFWInfo.uiPkgOffset[1]     : 0x00000000
E/[LGE_FOTA] ( 3525): stFWInfo.uiPkgSize[1]       : 0x00000000
E/[LGE_FOTA] ( 3525): stFWInfo.uiPkgOffset[2]     : 0x00000000
E/[LGE_FOTA] ( 3525): stFWInfo.uiPkgSize[2]       : 0x00000000
E/[LGE_FOTA] ( 3525): stFWInfo.uiPkgOffset[3]     : 0x00000000
E/[LGE_FOTA] ( 3525): stFWInfo.uiPkgSize[3]       : 0x00000000
E/[LGE_FOTA] ( 3525): stFWInfo.uiPkgOffset[4]     : 0x00000000
E/[LGE_FOTA] ( 3525): stFWInfo.uiPkgSize[4]       : 0x00000000
E/[LGE_FOTA] ( 3525): stFWInfo.uiPkgOffset[5]     : 0x00000000
E/[LGE_FOTA] ( 3525): stFWInfo.uiPkgSize[5]       : 0x00000000
E/[LGE_FOTA] ( 3525): stFWInfo.uiPkgOffset[6]     : 0x00000000
E/[LGE_FOTA] ( 3525): stFWInfo.uiPkgSize[6]       : 0x00000000
E/[LGE_FOTA] ( 3525): stFWInfo.uiPkgOffset[7]     : 0x00000000
E/[LGE_FOTA] ( 3525): stFWInfo.uiPkgSize[7]       : 0x00000000
E/[LGE_FOTA] ( 3525): stFWInfo.uiPkgOffset[8]     : 0x00000000
E/[LGE_FOTA] ( 3525): stFWInfo.uiPkgSize[8]       : 0x00000000
E/[LGE_FOTA] ( 3525): stFWInfo.uiPkgOffset[9]     : 0x00000000
E/[LGE_FOTA] ( 3525): stFWInfo.uiPkgSize[9]       : 0x00000000
E/[LGE_FOTA] ( 3525): stFWInfo.uiPkgOffset[10]     : 0x00000000
E/[LGE_FOTA] ( 3525): stFWInfo.uiPkgSize[10]       : 0x00000000
E/[LGE_FOTA] ( 3525): stFWInfo.uiPkgOffset[11]     : 0x00000000
E/[LGE_FOTA] ( 3525): stFWInfo.uiPkgSize[11]       : 0x00000000
E/[LGE_FOTA] ( 3525): stFWInfo.uiPkgOffset[12]     : 0x00000000
E/[LGE_FOTA] ( 3525): stFWInfo.uiPkgSize[12]       : 0x00000000
E/[LGE_FOTA] ( 3525): stFWInfo.uiPkgOffset[13]     : 0x00000000
E/[LGE_FOTA] ( 3525): stFWInfo.uiPkgSize[13]       : 0x00000000
E/[LGE_FOTA] ( 3525): stFWInfo.uiPkgOffset[14]     : 0x00000000
E/[LGE_FOTA] ( 3525): stFWInfo.uiPkgSize[14]       : 0x00000000
E/[LGE_FOTA] ( 3525): stFWInfo.uiPkgOffset[15]     : 0x00000000
E/[LGE_FOTA] ( 3525): stFWInfo.uiPkgSize[15]       : 0x00000000
E/[LGE_FOTA] ( 3525): stFWInfo.uiCurrSection       : 0x00000000
E/[LGE_FOTA] ( 3525): stFWInfo.uiResult            : 0x00000000
E/[LGE_FOTA] ( 3525): stFSInfo.enState             : 0x00000000
E/[LGE_FOTA] ( 3525): stFSInfo.uiFilePackageOffset : 0xa09907d4
E/[LGE_FOTA] ( 3525): stFSInfo.uiFilePackageSize   : 0xa09907f4
E/[LGE_FOTA] ( 3525): stFSInfo.uiResult            : 0x00000000
E/[LGE_FOTA] ( 3525): stPkgInfo.enPackageType      : 0x00000000
E/[LGE_FOTA] ( 3525): stPkgInfo.uiSize             : 0x00000000
E/[LGE_FOTA] ( 3525): stPkgInfo.uiWrittenAddr      : 0x00000000
E/[LGE_FOTA] ( 3525): stPkgInfo.uiWrittenSize      : 0x00000000
E/[LGE_FOTA] ( 3525): stPkgInfo.szPackagePath      : 
E/[LGE_FOTA] ( 3525): stCommand.enCommand	 		: 0x00000000
E/[LGE_FOTA] ( 3525): uiBackupBufferAddr			: 0x00000000
E/[LGE_FOTA] ( 3525): uiLanguage					: 0x00000000
E/[LGE_FOTA] ( 3525): stDebug.uiResetCount			: 0x00000000
E/[LGE_FOTA] ( 3525): stDebug.uiRetryCount			: 0x00000000
E/[LGE_FOTA] ( 3525): FOTAFS_Close 1c
E/[LGE_FOTA] ( 3525): FOTAJNI_GetConvertedUAResult : 450
E/[LGE_FOTA] ( 3525): FOTAJNI_GetUAResult : 450
D/LGDMClient( 3525): [SwUpdate.java] [getSwUpdateStatus()] : [244] : Software update result:450
D/LGDMClient( 3525): [DmDownloadService.java] [onStartCommand()] : [92] : DmDownloadService.onStartCommand()
D/LGDMClient( 3525): [DmDownloadService.java] [handleStart()] : [103] : DmDownloadService  intend : Intent { cmp=com.lge.lgdmsclient/.service.DmDownloadService }
I/AlertUtils( 3502): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/CommonUtil( 3414): BUILD Country: EU
D/LGDMClient( 3525): [DmAg,ent.java] [restartIdleSession()] : [1084] : skymymy is: iSwUpdateStatus = 450, isUpgradedByLGUP() = false
D/LGDMClient( 3525): [DmAgent.java] [clearContext()] : [1774] : [Enter] clearContext
I/LGDMClient( 3525): [DmAgent.java] [setState()] : [1875] : Setting Agent State and State is : DmConstants.DMAgentState.mDmaState = 0
I/TimerReceiver( 3414): onReceiveIntent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.lge.clock/.timer.TimerReceiver (has extras) }
D/TimerReceiver( 3414): onReceive() : android.intent.action.BOOT_COMPLETED
I/TimerReceiver( 3414): setTimerDone
D/TimerObj( 3414): --------------------- getTimersFromSharedPrefs
V/TimerObj( 3414): --------------------- timers list is empty
D/LGDMClient( 3525): [DmAgent.java] [clearContext()] : [1791] : [Exit] clearContext
V/LGDMClient( 3525): [DmClientController.java] [handleMessage()] : [181] : DmClientController: run() - msg.what=33
D/LGDMClient( 3525): [DmClientController.java] [stopService()] : [408] : stopDownloadService(), DownloadService will be stopped in order to follow the end of DmClientController
D/TimeService( 3568): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1456842796576
D/        ( 3568): TimeServiceNative: User Time to be set is 1456842796576
D/QC-time-services( 3568): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3568): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3568): Lib:time_genoff_operation: pargs->ts_val = 1456842796576
D/QC-time-services( 3568): Lib:time_genoff_operation: Send to server  passed!!
W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1804 android.content.ContextWrapper.stopService:520 com.lge.lgdmsclient.dmclient.controller.DmClientController.stopService:412 com.lge.lgdmsclient.dmclient.controller.DmClientController.clearController:383 com.lge.lgdmsclient.dmclient.controller.DmClientController.access$200:68 
D/QC-time-services(  320): Daemon: Connection accepted:time_genoff
D/QC-time-services(  320): Daemon:Received base = 2, unit = 1, operation = 0,value = 1456842796576
D/QC-time-services(  320): Daemon:genoff_opr: Base = 2, val = 1456842796576, operation = 0
D/QC-time-services(  320): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS6/13/70 18:34:40
D/QC-time-services(  320): Daemon:Value read from RTC seconds = 16742080000
D/QC-time-services(  320): Daemon:new time 1456842796576 
D/QC-time-services(  320): Daemon: delta 1440100716576 genoff 1440100716576 
D/QC-time-services(  320): Daemon:genoff_persistent_update: Writing genoff = 1440100716576 to memory
D/QC-time-services(  320): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  320): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  320): Updating the TOD offset
D/QC-time-services(  320): Daemon:genoff_persistent_update: Writing genoff = 1440100716576 to memory
D/QC-time-services(  320): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  320): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services( 3568): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  320): Daemon:Update to modem bit set
D/QC-time-services(  320): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  320): Daemon: Base = 2, Value being sent to MODEM = 1124135916576
E/QC-time-services(  320): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  320): Daemon: Time-services: Waiting to acceptconnection
I/AlertUtils( 3502): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 3502): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 3502): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,I/AlertUtils( 3502): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/ActivityManager(  855): Start proc com.lge.appbox.client:SingleBinaryService for broadcast com.lge.appbox.client/com.lge.appbox.singlebinary.SimChangeReceiver: pid=3589 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  855): Killing 1739:com.android.defcontainer/u0a4 (adj 15): empty #11
I/AlertUtils( 3502): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,I/AlertUtils( 3502): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 3502): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 3502): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 3502): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 3502): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 3502): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 3502): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 3502): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3502): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
,I/CalendarProvider2( 3449): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 3449): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
D/LGDMClient( 3525): [DmDownloadService.java] [onDestroy()] : [117] : DmDownloadService.onDestroy()
I/ActivityManager(  855): Killing 3130:com.lge.hiddenmenu/1000 (adj 15): empty #11
I/jxcore-log( 3247): getBuffer is called!!!!
I/jxcore-log( 3247): 
,D/AppUp4:AppBoxApplication( 3589): AppBoxApplication onCreate()
,D/AppUp4:SingleBinary( 3589): /cust/OPEN_EU/config/app-enabled-conf.json is selected!!
,D/AppUp4:SingleBinary( 3589):  Starting isFingerChanged 
I/ActivityManager(  855): Killing 3159:com.google.android.onetimeinitializer/u0a8 (adj 15): empty #11
,I/ActivityManager(  855): Killing 2438:com.android.settings/1000 (adj 15): empty #11
,V/DownloadManager( 3468): DownloadService onDestroy
,W/libprocessgroup(  855): failed to open /acct/uid_1000/pid_3130/cgroup.procs: No such file or directory
,I/ActivityManager(  855): Start proc com.lge.appbox.client for content provider com.lge.appbox.client/com.lge.appbox.databases.AppBoxContentProvider: pid=3610 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
W/libprocessgroup(  855): failed to open /acct/uid_10004/pid_1739/cgroup.procs: No such file or directory
W/libprocessgroup(  855): failed to open /acct/uid_10008/pid_3159/cgroup.procs: No such file or directory
W/libprocessgroup(  855): failed to open /acct/uid_1000/pid_2438/cgroup.procs: No such file or directory
I/AlertUtils( 3502): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 3502): End InitializeAlertRingtoneService.onHandleIntent
,I/ActivityManager(  855): Killing 3190:com.android.cellbroadcastreceiver/u0a16 (adj 15): empty #11
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,W/libprocessgroup(  855): failed to open /acct/uid_10016/pid_3190/cgroup.procs: No such file or directory
I/CheckinService( 2308): Checkin interval check for package: unspecified last checkin: 1456825786151 min interval config: 0 actual interval: 17011056
,W/DriveInitializer( 2308): Awaiting to be initialized
,W/DriveInitializer( 2308): Background init thread started
,I/AppUp4:AppBoxCP( 3610): onCreate
W/AppUp4:DB( 3610):  [AppBoxDatabaseHelper] construct
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 2308): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
I/AppUp4:DB( 3610):  setFingerPrint start
I/AppUp4:DB( 3610):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 3610):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 3610):  SDK version = 0
I/AppUp4:DB( 3610):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 3610): AppBoxApplication onCreate()
D/AppUp4:SingleBinary( 3589):  The value of isFingerChanged null
,D/AppUp4:SingleBinary( 3589): Device : jagnm
,D/AppUp4:SingleBinary( 3589): First Boot - ignore boot completed
D/AppUp4:NTCodeSingleBinary( 3589): Starting isFingerChanged 
D/AppUp4:NTCodeSingleBinary( 3589): The value of isFingerChanged lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
D/AppUp4:SingleBinary( 3589): Device : jagnm
D/AppUp4:SingleBinary( 3589): Config file is not exist - nothing
,I/ActivityManager(  855): Killing 3097:com.lge.settings.easy/1000 (adj 15): empty #11
W/libprocessgroup(  855): failed to open /acct/uid_1000/pid_3097/cgroup.procs: No such file or directory
,I/NotificationManager(  855): android: cancelAsUser(-1874035846) by android
I/AppUp4:SDKReflector( 3610): +myUserId : 0
,D/AppUp4:BootUpPollingReceiver( 3610): onReceive on user ID : 0
V/AppUp4:FotaPlusService( 3610):  isFotaPlusTriedOnce : true
D/AppUp4:BootUpPollingReceiver( 3610): Starting getSdkVersion 
D/AppUp4:BootUpPollingReceiver( 3610): SDK version is : 0
D/AppUp4:BootUpPollingReceiver( 3610): currentSdkVersion : 0
,D/AppUp4:BootUpPollingReceiver( 3610): isSdkVersionChanged : true
V/AppUp4:FotaPlusService( 3610):  setFotaPlusCompleted : false
D/AppUp4:BootUpPollingReceiver( 3610): isFotaPlusNeeded : true
D/AppUp4:BootUpPollingReceiver( 3610): Fota Plus already tried once, show notification
V/NotificationService(  855): enqueueNotificationInternal: pkg=com.lge.appbox.client id=22319582 notification=Notification(pri=0 contentView=null vibrate=default sound=default defaults=0x3 flags=0x2 color=0x00000000 vis=PRIVATE)
,D/AppUp4:BootUpPollingReceiver( 3610): isFotaPlusRunning after : true
D/AppUp4:BootUpPollingReceiver( 3610):  installPreloadedValuePackIfNeeded 
D/ZenLog  (  855): intercepted: 0|com.lge.appbox.client|22319582|null|10011,none
V/NotificationService(  855): pkg=com.lge.appbox.client canInterrupt=false intercept=true
I/NotificationServiceEx(  855): LED remove() : mLights=0|com.lge.appbox.client|22319582|null|10011
D/AppUp4:BootUpPollingReceiver( 3610):  file is : /system/apps/bootup
D/AppUp4:BootUpPollingReceiver( 3610): file false
D/AppUp4:BootUpPollingReceiver( 3610): [BootUpPollingReceiver] No preload installation.
D/NotificationServiceEx(  855): updateLightListLocked :r=0|com.lge.appbox.client|22319582|null|10011, action=2
D/NotificationServiceEx(  855): notification=Notification(pri=0 contentView=null vibrate=default sound=default defaults=0x3 flags=0x2 color=0x00000000 vis=PRIVATE)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/art     ( 2037): Explicit concurrent mark sweep GC freed 3274(132KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 479us total 44.270ms
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  855): Killing 3228:com.lge.email/u0a21 (adj 15): empty #11
,D/SmartCoverUpdateMonitor( 1332): onNotificationPosted() : StatusBarNotification(pkg=com.lge.appbox.client user=UserHandle{0} id=22319582 tag=null score=0 key=0|com.lge.appbox.client|22319582|null|10011: Notification(pri=0 contentView=com.lge.appbox.client/0x1090079 vibrate=default sound=default defaults=0x3 flags=0x2 color=0x00000000 vis=PRIVATE))
D/SmartCoverUpdateMonitor( 1332): onNotificationPosted() !qcn.isEnableToShowNotification()
D/AppUp4:dwnld( 3610): [removeAllIncompletedDownload] ... 
,V/AppUp4:BootUpPollingReceiver( 3610): [BootUpPollingReceiver] start bootup Polling.
,D/AppUp4  ( 3610): getUpdatePollingPeriod
D/AppUp4  ( 3610): getUpdatePollingPeriod
W/DriveInitializer( 2308): Background init thread ended
,I/NotificationManager(  855): android: cancelAsUser(2145784878) by android
,W/libprocessgroup(  855): failed to open /acct/uid_10021/pid_3228/cgroup.procs: No such file or directory
D/AppUp4:BackgroundPollingService ( 3610): register polling alarm when : 2016/03/03 21:37:46
D/AppUp4:LightWeightPollingService ( 3610):  [buildRemotePollingIntent]
,D/AppUp4:LightWeightPollingService ( 3610): This means remote config is N, so skip it
,I/NotificationManager( 3387): com.google.android.apps.plus: cancel(10436) by com.google.android.apps.plus
,I/[SystemUI]PhoneStatusBar( 1372): updateMediaMetaData(false): mMediaMetadata = null
,I/ActivityManager(  855): Start proc com.android.mms for broadcast com.android.mms/.transaction.SmsReceiver: pid=3660 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 3002} abi=armeabi-v7a
I/ActivityManager(  855): Killing 3369:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/libprocessgroup(  855): failed to open /acct/uid_10023/pid_3369/cgroup.procs: No such file or directory
,W/ResourcesManager( 3660): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3660): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,I/art     ( 2308): Explicit concurrent mark sweep GC freed 22218(1646KB) AllocSpace objects, 25(400KB) LOS objects, 25% free, 11MB/15MB, paused 908us total 107.852ms
,I/NotificationManager(  855): android: cancelAsUser(2145784878) by android
I/NotificationManager( 2308): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager(  855): android: cancelAsUser(353845882) by android
,I/ConversationSkinProvider( 3660): skin provider oncreate
,I/JoynPreferenceProvider( 3660): joyn preference provider oncreate
E/ActivityThread( 3660): Failed to find provider info for com.lge.ims.rcs
,I/ActivityManager(  855): Killing 3343:com.google.android.partnersetup/u0a9 (adj 15): empty #11
I/NotificationManager(  855): android: cancelAsUser(-1874035846) by android
I/art     ( 1765): Explicit concurrent mark sweep GC freed 26990(1766KB) AllocSpace objects, 19(304KB) LOS objects, 40% free, 13MB/21MB, paused 1.632ms total 142.682ms
,W/libprocessgroup(  855): failed to open /acct/uid_10009/pid_3343/cgroup.procs: No such file or directory
E/ActivityThread( 3660): Failed to find provider info for com.lge.ims.rcs
E/[MMS]   ( 3660): MmsSettings: [LGE] MmsSettings.initializeMmsSettings()
I/ActivityManager(  855): Killing 3449:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/libprocessgroup(  855): failed to open /acct/uid_10014/pid_3449/cgroup.procs: No such file or directory
E/[MMS]   ( 3660): MmsSettings: [LGE]loadXMLSettings() ++++++++++ >> Load default:false
I/[MMS]   ( 3660): MmsSettings: [LGE]loadXMLSettings() SIM(current) information
I/[MMS]   ( 3660): MmsSettings: [LGE]loadXMLSettings() Mcc:450, Mnc:00, Gid:Default
E/[MMS]   ( 3660): MmsSettings: [LGE]loadXMLSettings() [Build] Country:EU, Operator:OPEN
D/[MMS]   ( 3660): MmsSettings: find mms_config.xml data file => name = 2131034124
,I/Scheduler( 1765): Use legacy PeriodicScheduler
,I/NotificationManager(  855): android: cancelAsUser(-1548111331) by android
W/InstanceID/Rpc( 1765): Found 10006
D/MmsSettings( 3660): value of dtmf from frw noti = 80, 65, cmas = 90, 60
E/[MMS]   ( 3660): MmsSettings: [LGE]loadXMLSettings(): Check current items.
D/[MMS]   ( 3660): MmsSettings: [LGE]---------------------------------------->
,D/[MMS]   ( 3660): MmsSettings: [LGE]   sms_dr = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   cb_on = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   sms_concat = [5]
D/[MMS]   ( 3660): MmsSettings: [LGE]   sms_char = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   mms_dr_r = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   mms_dr_a = [1]
D/[MMS]   ( 3660): MmsSettings: [LGE]   mms_rr_r = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   mms_rr_a = [1]
D/[MMS]   ( 3660): MmsSettings: [LGE]   auto_retr = [1]
D/[MMS]   ( 3660): MmsSettings: [LGE]   auto_retr_r = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   mms_priority = [1]
D/[MMS]   ( 3660): MmsSettings: [LGE]   mms_validity = [6]
D/[MMS]   ( 3660): MmsSettings: [LGE]   mms_creation = [2]
D/[MMS]   ( 3660): MmsSettings: [LGE]   mms_size = [300]
D/[MMS]   ( 3660): MmsSettings: [LGE]   slide_dur = [5]
D/[MMS]   ( 3660): MmsSettings: [LGE]   recv_adv = [1]
D/[MMS]   ( 3660): MmsSettings: [LGE]   push_on = [1]
D/[MMS]   ( 3660): MmsSettings: [LGE]   del_old = [1]
D/[MMS]   ( 3660): MmsSettings: [LGE]   sms_limit = [500]
D/[MMS]   ( 3660): MmsSettings: [LGE]   mms_limit = [50]
D/[MMS]   ( 3660): MmsSettings: [LGE]   max_editor_num = [2000]
D/[MMS]   ( 3660): MmsSettings: [LGE]   mms_slide_num = [10]
D/[MMS]   ( 3660): MmsSettings: [LGE]   mms_recipient_num = [20]
D/[MMS]   ( 3660): MmsSettings: [LGE]   attachement_storage = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   send_msg_enter_key = [1]
D/[MMS]   ( 3660): MmsSettings: [LGE]   spam_setting = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   anonymous_spam_setting = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   mms_recipient_length = [64]
D/[MMS]   ( 3660): MmsSettings: [LGE]   sms_recipient_length = [20]
D/[MMS]   ( 3660): MmsSettings: [LGE]   recv_adv_invisible = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   mms_creation_invisible = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   mms_dr_r_invisible = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   mms_dr_a_invisible = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   mms_rr_r_invisible = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   mms_rr_a_invisible = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   auto_retr_r_invisible = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   mms_validity_invisible = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   mms_priority_invisible = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   sms_char_invisible = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   sms_dr_invisible = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   sms_validity_invisible = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   discard_visible = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   appointment_invisible = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   mms_pending_in_wifi_use = [1]
D/[MMS]   ( 3660): MmsSettings: [LGE]   attach_location = [1]
D/[MMS]   ( 3660): MmsSettings: [LGE]   custom_extract_ui = [1]
D/[MMS]   ( 3660): MmsSettings: [LGE]   msg_list_data_seperator = [1]
D/[MMS]   ( 3660): MmsSettings: [LGE]   animation_effect = [1]
D/[MMS]   ( 3660): MmsSettings: [LGE]   inline_msg_item = [1]
D/[MMS]   ( 3660): MmsSettings: [LGE]   display_as_slide_layout = [1]
D/[MMS]   ( 3660): MmsSettings: [LGE]   one_bubble = [1]
D/[MMS]   ( 3660): MmsSettings: [LGE]   hide_sync_header_update = [1]
D/[MMS]   ( 3660): MmsSettings: [LGE]   recipient_cc_bcc = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   ciq_on = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   mms_enabled_when_data_disabled = [1]
D/[MMS]   ( 3660): MmsSettings: [LGE]   two_finger_flick = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   kr_skt_feature_set = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   kr_kt_feature_set = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   kr_lgu_feature_set = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   docomo_message_setting = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   docomo_sim_card_set = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   docomo_nexti_phonebook_set = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   docomo_function_validity_period = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   docomo_led_button_blink = [0]
D/[MMS],   ( 3660): MmsSettings: [LGE]   docomo_dtmf_setting = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   china_feature_set = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   media_resolution_restrict_off = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   attachment_save_in_slidesheow = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   mms_max_video_resolution = [320x240]
D/[MMS]   ( 3660): MmsSettings: [LGE]   email_over_sms = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   email_over_sms_gateway_num = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   addr_len_check = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   message_poster = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   sticky_note = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   wificalling_feature_set = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   online_album = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   online_album_dest_num = [000]
D/[MMS]   ( 3660): MmsSettings: [LGE]   appointment_invisible = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   voice_mail = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   smsc_readonly = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   latin_america_fdn_check = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   sms_sent_time_mode = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   fdn_gprs_check = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   reply_to_virtual_smsc = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   save_to_draft = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   mms_signature = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   mms_callback = [0]
D/[MMS]   ( 3660): MmsSettings: [LGE]   message_counters_key = [0]
E/[MMS]   ( 3660): MmsSettings: [LGE]loadXMLSettings(): Check prefMmsConfig.
I/[MMS]   ( 3660): MmsSettings: [LGE]loadXMLSettings() Phone(saved) information
I/[MMS]   ( 3660): MmsSettings: [LGE]loadXMLSettings() Mcc:450, Mnc:00, Gid:Default
E/[MMS]   ( 3660): MmsSettings: [LGE]loadXMLSettings(): SIM is NOT changed!!!
E/[MMS]   ( 3660): MmsSettings: [LGE]loadXMLSettings(): SIM is not ready!!!
I/MmsHiddenPrefProvider( 1783): MmsHiddenConfig DB Updated
,I/MmsHiddenPrefProvider( 1783): MmsHiddenConfig DB Updated
,D/MmsConfig( 3660): [LGE] setForceSmsGsmAlphabet_SystemProperties.set: 0
I/[MMS]   ( 3660): MmsConfig: [LGE]getUaString=LG-D722 LG-Android-MMS-V4.0/1.2
,V/SettingsProvider(  855): call_put(system:android.msg.mms.useragent=LG-D722 LG-Android-MMS-V4.0/1.2) for 0 calling package = com.android.mms
,W/BackupManagerService(  855): dataChanged but no participant pkg='com.android.providers.settings' uid=10027
I/LGDrmClient( 3660): _DRM_ServiceGet() : Bind lgdrm service
,D/LGDRM   (  286): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
D/LGDRM   (  286): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
I/DrmWrapper( 3660): isDrmV1 =true
V/DrmWrapper( 3660): isDrmV2 =false
D/MmsConfig( 3660): [LGE] isSupportUAProfileRandomPath : false
,V/SettingsProvider(  855): call_put(system:android.msg.mms.uaprofile=http://gsm.lge.com/html/gsm/D722-M3-D1.xml) for 0 calling package = com.android.mms
W/BackupManagerService(  855): dataChanged but no participant pkg='com.android.providers.settings' uid=10027
V/SettingsProvider(  855): call_put(system:android.msg.mms.max.size=300) for 0 calling package = com.android.mms
W/BackupManagerService(  855): dataChanged but no participant pkg='com.android.providers.settings' uid=10027
,V/SettingsProvider(  855): call_put(system:android.msg.attachment.max.size=302080) for 0 calling package = com.android.mms
W/BackupManagerService(  855): dataChanged but no participant pkg='com.android.providers.settings' uid=10027
V/SettingsProvider(  855): call_put(system:android.msg.recipient.max.size=20) for 0 calling package = com.android.mms
W/BackupManagerService(  855): dataChanged but no participant pkg='com.android.providers.settings' uid=10027
,V/SettingsProvider(  855): call_put(system:android.msg.vobject.max.size=10) for 0 calling package = com.android.mms
W/BackupManagerService(  855): dataChanged but no participant pkg='com.android.providers.settings' uid=10027
V/SettingsProvider(  855): call_put(system:android.msg.camera.max.video.resolution=320x240) for 0 calling package = com.android.mms
W/BackupManagerService(  855): dataChanged but no participant pkg='com.android.providers.settings' uid=10027
,V/SettingsProvider(  855): call_put(system:android.msg.package.distinction=unifiedmessage) for 0 calling package = com.android.mms
W/BackupManagerService(  855): dataChanged but no participant pkg='com.android.providers.settings' uid=10027
V/SettingsProvider(  855): call_put(system:android.msg.old.message.delete=true) for 0 calling package = com.android.mms
,W/BackupManagerService(  855): dataChanged but no participant pkg='com.android.providers.settings' uid=10027
V/SettingsProvider(  855): call_put(system:android.msg.sms.max.count=500) for 0 calling package = com.android.mms
W/BackupManagerService(  855): dataChanged but no participant pkg='com.android.providers.settings' uid=10027
,V/SettingsProvider(  855): call_put(system:android.msg.mms.max.count=50) for 0 calling package = com.android.mms
W/BackupManagerService(  855): dataChanged but no participant pkg='com.android.providers.settings' uid=10027
,V/MmsConfig( 3660): [isMmsEnabledWhenDataDisabled]value=1
V/MmsConfigStaticVar( 3660): [setMmsEnabledWhenDataDisabled]enabled=true
V/MmsConfigStaticVar( 3660): [setMmsEnabledWhenDataRoamingDisabled]enabled=false
,D/CmasFeatures( 3660): [init]CMAS features are initialized for US country. Returning.
,V/Contact ( 3660): Contact init()_Create new insatnce
,V/ToneGenerator( 3660): ToneGenerator constructor: streamType=8, volume=0.133352
,V/AudioPolicyService(  280): registerClient() client 0xb39b5a00, uid 10027
V/AudioPolicyManager(  280): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  280): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  280): getOutput() returns output 2
V/AudioFlinger(  280): registerClient() client 0xb4033100, pid 3660
V/AudioFlinger(  280): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  280): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  280): thread 0xb5651000 type 0 TID 1292 waking up
V/AudioFlinger(  280): thread 0xb56eb000 type 0 TID 1296 waking up
V/AudioFlinger(  280): processConfigEvents_l() remaining events 1
V/AudioFlinger(  280): processConfigEvents_l() remaining events 1
V/AudioFlinger(  280): PlaybackThread::audioConfigChanged, thread 0xb5651000, event 0, param 0
V/AudioFlinger(  280): PlaybackThread::audioConfigChanged, thread 0xb56eb000, event 0, param 0
V/AudioSystem(  280): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  280): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1372): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1372): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 2786): ioConfigChanged() event 0, ioHandle 2
V/AudioFlinger(  280): processConfigEvents_l() DONE thread 0xb5651000
V/AudioSystem(  280): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  280): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 2786): ioConfigChanged() opening already existing output! 2
V/AudioSystem(  855): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  855): ioConfigChanged() opening already existing output! 2
V/AudioFlinger(  280): processConfigEvents_l() DONE thread 0xb56eb000
V/AudioSystem(  855): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  855): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1969): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3660): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1969): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3660): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/AudioSystem( 1969): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3660): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1969): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3660): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/AudioSystem( 2786): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 2786): ioConfigChanged() opening already existing output! 4
V/AudioFlinger(  280): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  280): thread 0xb5735000 type 0 TID 1298 waking up
V/AudioSystem( 2091): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2091): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 2091): ioConfigChanged() event 0, ioHandle 4
V/AudioFlinger(  280): processConfigEvents_l() remaining events 1
V/AudioSystem( 2091): ioConfigChanged() opening already existing output! 4
V/AudioFlinger(  280): PlaybackThread::audioConfigChanged, thread 0xb5735000, event 0, param 0
V/AudioSystem(  280): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem(  280): ioConfigChanged() opening already existing output! 6
V/AudioFlinger(  280): processConfigEvents_l() DONE thread 0xb5735000
V/AudioSystem( 2786): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 2786): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 3660): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 3660): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 1152 latency 112
V/AudioSystem(  855): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem(  855): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1783): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1783): ioConfigChanged() opening already existin,g output! 2
V/AudioSystem( 1372): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1372): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1783): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1783): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1372): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1372): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1783): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1783): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1969): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1969): ioConfigChanged() opening already existing output! 6
V/ToneGenerator( 3660): Create Track: 0xb4907180
V/AudioTrack( 3660): set(): streamType 8, sampleRate 48000, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 3660): set() streamType 8, sampleRate 48000, format 1, frameCount 0, flags 0004
V/AudioSystem( 2091): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 2091): ioConfigChanged() opening already existing output! 6
I/AudioFlinger(  280): isAudioPlaybackHookOn() false
D/AudioTrack( 3660): TrackOffload: AudioTrack Offload disabled by property, returning false
V/AudioPolicyManager(  280): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  280): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  280): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  280): getOutput() returns output 2
V/AudioSystem( 3660): getLatency() output 2, latency 50
V/AudioSystem( 3660): getFrameCount() output 2, frameCount 960
V/AudioTrack( 3660): createTrack_l() output 2 afLatency 50
V/AudioTrack( 3660): Create normal PCM 0x1 Track
V/AudioFlinger(  280): createTrack() lSessionId: 21
V/AudioFlinger(  280): AUDIO_OUTPUT_FLAG_FAST accepted: frameCount=480 mFrameCount=240
V/AudioFlinger(  280): sendConfigEvent_l() num events 1 event 1
V/AudioTrack( 3660): Flags here  0x4 
V/AudioTrack( 3660): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  280): acquiring 21 from 3660, for 3660
V/AudioFlinger(  280):  added new entry for 21
V/ToneGenerator( 3660): ToneGenerator INIT OK, time: 49628
V/ToneGenerator( 3660): ToneGenerator constructor: streamType=8, volume=0.316228
V/AudioPolicyManager(  280): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  280): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  280): getOutput() returns output 2
V/ToneGenerator( 3660): Create Track: 0xb4908580
V/AudioTrack( 3660): set(): streamType 8, sampleRate 48000, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 3660): set() streamType 8, sampleRate 48000, format 1, frameCount 0, flags 0004
I/AudioFlinger(  280): isAudioPlaybackHookOn() false
D/AudioTrack( 3660): TrackOffload: AudioTrack Offload disabled by property, returning false
V/AudioPolicyManager(  280): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  280): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  280): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  280): getOutput() returns output 2
V/AudioSystem( 3660): getLatency() output 2, latency 50
V/AudioSystem( 3660): getFrameCount() output 2, frameCount 960
V/AudioTrack( 3660): createTrack_l() output 2 afLatency 50
V/AudioTrack( 3660): Create normal PCM 0x1 Track
V/AudioFlinger(  280): createTrack() lSessionId: 22
V/AudioFlinger(  280): AUDIO_OUTPUT_FLAG_FAST accepted: frameCount=480 mFrameCount=240
V/AudioFlinger(  280): sendConfigEvent_l() num events 2 event 1
V/AudioTrack( 3660): Flags here  0x4 
V/AudioTrack( 3660): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  280): acquiring 22 from 3660, for 3660
V/AudioFlinger(  280):  added new entry for 22
V/ToneGenerator( 3660): ToneGenerator INIT OK, time: 49630
V/AudioFlinger(  280): processConfigEvents_l() remaining events 2
V/AudioFlinger(  280): processConfigEvents_l() remaining events 1
V/AudioFlinger(  280): processConfigEvents_l() DONE thread 0xb5651000
I/MessagingNotification( 3660): registerLEDObserver
I/MessagingNotification( 3660): registerLEDObserver REGISTER
,I/art     (  855): Explicit concurrent mark sweep GC freed 17861(759KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 1.891ms total 161.503ms
,I/MmsHiddenPrefProvider( 3660): MmsHiddenConfig.init()
I/MmsHiddenPrefProvider( 3660): MmsHiddenConfig.loadHiddenPrefSettings
D/CountryDetector(  855): The first listener is added
,E/ActivityThread( 3660): Failed to find provider info for com.lge.ims.provider.uc
,I/LOG_TAG ( 3660): registerContactDBChangeObserver
,D/LocationManagerService(  855): getProviders()=[passive]
I/MmsApp  ( 3660): handleBootCompleted
,D/LocationManagerService(  855): request d662435 passive Request[POWER_NONE passive fastest=0] from android(1000)
D/LocationManagerService(  855): provider request: passive ProviderRequest[ON interval=0]
I/SmsReceiverService( 3660): smsBootCompleted
D/MmsConfig( 3660): MediaScanner - scannerConnected
,D/AlertReceiver( 3502): onReceive: a=android.intent.action.BOOT_COMPLETED Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.calendar/.alerts.AlertReceiver (has extras) }
D/SwitchedService( 3660): Mms SwitchedService ACTION_USER_SWITCHED registerReceiver
D/AlertUtils( 3502): Flushing old alerts from shared prefs table
,D/AlertService( 3502): 0 Action = android.intent.action.BOOT_COMPLETED
D/AlertService( 3502): [Widget]com.android.calendar.widget.CalendarAppWidgetProvider enabled
D/Feature ( 3502): MemoryLevel - 5:NOT_DEF:Not UI4.2 LOS
D/AlertService( 3502): [Widget]com.android.calendar.widget.MonthWidgetProvider enabled
D/AlertService( 3502): [Widget]com.android.calendar.widget.WeekWidgetProvider enabled
I/ActivityManager(  855): Start proc com.android.settings for broadcast com.android.settings/.lockscreen.LockSettingsReceiver: pid=3712 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/MmsConfig( 3660): isNotAllowedSms: currentUser:0
D/MmsConfig( 3660): isNotAllowedSms: UserHandle.myUserId():0
D/MmsConfig( 3660): isUserMode:false
D/SmsReceiverService( 3660): handleMessage isUserMode:false
I/MmsSystemEventReceiver( 3660): mmsBootComplete
D/AlertService( 3502): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
W/ResourcesManager( 3660): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  855): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3734 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/SmsReceiverService( 3660): handleMessage action: android.intent.action.BOOT_COMPLETED error: 0
W/ResourcesManager( 3712): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3712): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,W/ResourcesManager( 3712): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 3712): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 3712): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/MmsConfig( 3660): getUserModeNotAllowedSms:sUserModeNotAllowedSms:false
,D/MmsConfig( 3660): isNotAllowedSms: currentUser:0
D/MmsConfig( 3660): isNotAllowedSms: UserHandle.myUserId():0
D/MmsConfig( 3660): isUserMode:false
W/ResourcesManager( 3734): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,V/LEDService( 1836): stopInternal(), pkg=com.android.mms, id=123
,D/MessagingNotification( 3660): disalbleEmotionalLED id= 123
I/NotificationManager( 3660): com.android.mms: cancel(123) by com.android.mms
V/LEDService( 1836): stopInternal(), pkg=com.android.mms, id=946
D/MessagingNotification( 3660): disalbleEmotionalLED id= 946
I/NotificationManager( 3660): com.android.mms: cancel(946) by com.android.mms
D/CalendarProvider2( 3734): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@22fd0f75
D/MessagingNotification( 3660): unread_count:0, thread_count:0, thread_id:-100
D/MessagingNotification( 3660): toLockscreenWithUnreadMsgCnt - count = 0
,D/CalendarProvider2( 3734): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 3734): Created com.android.providers.calendar.CalendarAlarmManager@2fe52dd6(com.android.providers.calendar.CalendarProvider2@22fd0f75)
,I/IndexDatabaseHelper( 3712): Using schema version: 115
,I/IndexDatabaseHelper( 3712): Index is fine
I/ActivityManager(  855): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=3753 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,D/AlarmScheduler( 3502): No events found starting within 1 week.
,I/LockScreenSettings( 3753): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,D/QuickCoverActivity( 3660): lockscreensettings ret = true
,I/MessagingNotification( 3660): repeat count :0
D/SmartCoverUpdateMonitor( 1332): received broadcast lge.intent.action.UNREAD_MESSAGES
D/KeyguardModel( 1372): mReceiver, received action: lge.intent.action.UNREAD_MESSAGES, sendingUserId:0
I/NfcP2pLinkManager( 1818): LLCP deactivated.
,D/KeyguardModel( 1372): putNotificationIntoList Number: 0 Id: 1 UserId: 0
I/NfcP2pLinkManager( 1818): Duplicate onLlcpDectivated()
I/QuickCircle( 1332): onReceive :Intent { act=lge.intent.action.UNREAD_MESSAGES flg=0x10 (has extras) }, sComponents:[com.coremobility.app.vnotes.CM_VnoteInbox, com.android.contacts.activities.DialtactsActivity, com.android.contacts.DialtactsRecentCallsEntryActivity, com.lge.vvm.authmanager.VvmAuthManagerActivity, com.lge.email.ui.setupwizard.Welcome, com.skt.prod.dialer.activities.main.MainActivity, com.android.mms.ui.ConversationList, com.lge.message.ui.ConversationList, com.lge.message.activity.MainMenuActivity, com.skt.skaf.A000Z00040.A000Z00040, com.lge.updatecenter.UpdateCenterPrfActivity]
,D/SmartCoverUpdateMonitor( 1332): MSG_BIGNOTI_XXX
D/UsbSettingsReceiver( 3712): [AUTORUN] onReceive() : action = android.intent.action.BOOT_COMPLETED
D/UsbSettingsReceiver( 3712): [AUTORUN] sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 3712): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 3712): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 3712): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 3712): [AUTORUN] setTetherStatus() : status=false
D/UsbSettingsReceiver( 3712): [AUTORUN] onReceive() : android.intent.action.BOOT_COMPLETED
D/UsbSettingsReceiver( 3712): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 3712): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 3712): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/StoreModeReceiver( 3712): intent.getAction() : android.intent.action.BOOT_COMPLETED
D/StoreModeReceiver( 3712): sim state :null
D/StoreModeReceiver( 3712): Back LED don't supported.
V/SettingsProvider(  855): call_put(system:emotional_led_back_led=0) for 0 calling package = com.android.settings
,I/QCNEJ   ( 1872): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1872): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.114 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-03-01 15:33:19.228 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
V/SettingsProvider(  855): call_put(system:emotional_led_back_incoming_call=0) for 0 calling package = com.android.settings
,V/SettingsProvider(  855): call_put(system:emotional_led_back_alarm=0) for 0 calling package = com.android.settings
,V/SettingsProvider(  855): call_put(system:emotional_led_back_missed_call=0) for 0 calling package = com.android.settings
V/SettingsProvider(  855): call_put(system:emotional_led_back_missed_messages=0) for 0 calling package = com.android.settings
,V/SettingsProvider(  855): call_put(system:emotional_led_back_missed_emails=0) for 0 calling package = com.android.settings
V/SettingsProvider(  855): call_put(system:emotional_led_back_calendar_noti=0) for 0 calling package = com.android.settings
V/SettingsProvider(  855): call_put(system:emotional_led_back_voice_recording=0) for 0 calling package = com.android.settings
,V/SettingsProvider(  855): call_put(system:emotional_led_back_camera_timer_noti=0) for 0 calling package = com.android.settings
,V/SettingsProvider(  855): call_put(system:emotional_led_back_camera_face_detecting_noti=0) for 0 calling package = com.android.settings
V/SettingsProvider(  855): call_put(system:notification_light_pulse_back=0) for 0 calling package = com.android.settings
,D/StoreModeReceiver( 3712): SystemProperty Default brightness value [0-255] : 143
D/StoreModeReceiver( 3712): Default brightness[0-255] : 143
I/LEDService( 1836): getCurrentHighestLGLedRecord() start. size = 1
V/LEDService( 1836): startInternal : pkg=batteryinfo, recordId=0 : LGLedRecord{92f8f40 flags=0 patternId=0 color=0 priority=-1 recordId=0 pkg=batteryinfo infinite=true mExceptional=false mNativeNotification=false whichLedPlay=1 patternFilePath=null}
I/LEDService( 1836): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1836): set_light_notifications: 0,0,0,0,3
I/LEDService( 1836): updateLightsLocked : turn off led
D/qdlights( 1836): set_light_notifications: 0,0,0,0,3
W/ResourcesManager( 3712): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/StoreModeReceiver( 3712): Default Screen off timeout value : 30000
D/StoreModeReceiver( 3712): SystemProperty Default brightness Mode value[true/false] : false
D/StoreModeReceiver( 3712): BRIGHTNESS_MODE - 0
D/StoreModeReceiver( 3712): Default brightness Mode [0/1] : 0
D/StoreModeReceiver( 3712): Default NIGHT_MODE : 0
D/StoreModeReceiver( 3712): Set MaxBrightness : 255
E/PhoneInterfaceManager( 1783): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/StoreModeReceiver( 3712): getPhoneNumber is empty
D/StoreModeReceiver( 3712): go to StoreModeCheck()
D/StoreModeReceiver( 3712): isStoremode not null
D/PhoneInterfaceManager( 1783): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
V/SettingsProvider(  855): call_put(system:shop_mode_check=1) for 0 calling package = com.android.settings
,D/StoreModeReceiver( 3712): product_name : jagnm_global_com
D/StoreModeReceiver( 3712): Store mode start!
V/SettingsProvider(  855): call_put(system:shop_mode=1) for 0 calling package = com.android.settings
V/SettingsProvider(  855): call_put(system:shop_mode_check=1) for 0 calling package = com.android.settings
I/PowerManagerService(  855): ALS enabled for SRE
D/PowerManagerServiceEx(  855): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x1, nextTimeout=120000 (in 69588 ms)
,D/StoreModeReceiver( 3712): setBrightness() : NoMultiALC=255
W/ContextImpl( 3712): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.StoreModeReceiver.sendBroadcast:500 com.android.settings.StoreModeReceiver.setMode:473 
V/SettingsProvider(  855): call_put(system:screen_brightness_mode=0) for 0 calling package = com.android.settings
D/SettingsProvider(  855): Set screen_off_timeout in entry value : 120000
V/SettingsProvider(  855): call_put(system:screen_off_timeout=120000) for 0 calling package = com.android.settings
V/SettingsProvider(  855): call_put(system:screen_brightness=255) for 0 calling package = com.android.settings
V/SettingsProvider(  855): call_put(system:check_night_mode=0) for 0 calling package = com.android.settings
,D/SettingBootReceiver( 3712): onReceive
D/SettingBootReceiver( 3712): Boot Completed intent received, action=android.intent.action.BOOT_COMPLETED
I/ActivityManager(  855): Killing 3525:com.lge.lgdmsclient/1000 (adj 15): empty #11
D/SettingBootReceiver( 3712): setStyle()
D/SettingBootReceiver( 3712): com.lge.appwidget.settings.powercontrol is not installed.(Successfully Removed)
D/SettingBootReceiver( 3712): com.lge.appwidget.settings.powercontrol is not installed.(Successfully Removed)
D/SettingBootReceiver( 3712): com.lge.appwidget.settings.powercontrol is not installed.(Successfully Removed)
D/SettingBootReceiver( 3712): SettingStyle=1
,D/SettingBootReceiver( 3712): setAccountMenu()
D/TAG     ( 3712): setKidsMode
D/TAG     ( 3712): mIsOwner, setKidsMode
D/SettingBootReceiver( 3712): setAccountMenu()
D/YSY     ( 3712): not support Quiet mode notification
W/libprocessgroup(  855): failed to open /acct/uid_1000/pid_3525/cgroup.procs: No such file or directory
,I/[SystemUI]LGBootReceiver( 1372): onReceive = android.intent.action.BOOT_COMPLETED
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.statusbar.bootcompleted
I/[SystemUI]PhoneStatusBar( 1372): got ACTION_STICKY_BOOT_COMPLETED
,I/BOOT    ( 1372): got ACTION_STICKY_BOOT_COMPLETED
V/SettingsProvider(  855): call_put(system:gentle_vibration_status=1) for 0 calling package = com.android.settings
,V/SettingsProvider(  855): call_put(system:smart_ringtone=0) for 0 calling package = com.android.settings
D/SettingBootReceiver( 3712): timezoneID is null
I/SettingBootReceiver( 3712): disable au
,I/ActivityManager(  855): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3777 uid=10111 gids={50111, 9997, 1028, 3003} abi=armeabi-v7a
I/TAG     ( 3712): disable WirelessSettingsActivity
I/TAG     ( 3712): disable SKTPhoneMode
,D/SettingBootReceiver( 3712): [Nightmode] Enter receiver
D/SettingBootReceiver( 3712): [Nightmode] BOOT_COMPLETED
D/NightModeInfo( 3712): [Nightmode] setNightNodeTabSettings
D/NightModeInfo( 3712): [Nightmode] getAlreadyNightModeDB() : 0
D/NightModeInfo( 3712): [Nightmode] getUserBrightnessChange() : 0
,D/NightModeInfo( 3712): [Nightmode] getUserBrightnessChangeNoNight() : 0
V/SettingsProvider(  855): call_put(system:already_night_mode=0) for 0 calling package = com.android.settings
V/SettingsProvider(  855): call_put(system:user_change_brightness=0) for 0 calling package = com.android.settings
V/SettingsProvider(  855): call_put(system:user_change_brightness_no_night=0) for 0 calling package = com.android.settings
V/SettingsProvider(  855): call_put(system:night_mode_enabled=0) for 0 calling package = com.android.settings
D/NightModeInfo( 3712): [Nightmode] setTabNightCheck : 0
V/SettingsProvider(  855): call_put(system:save_tab_night_check=0) for 0 calling package = com.android.settings
D/NightModeInfo( 3712): [Nightmode] cancelPendingIntent
,D/NightModeInfo( 3712): [Nightmode] requestPendingIntent
D/NightModeInfo( 3712): [Nightmode] setAlarmStart~!!~!!~!!
D/NightModeInfo( 3712): [Nightmode] currentHour > 6
D/NightModeInfo( 3712): [Nightmode] currentHour > 6
I/NightModeInfo( 3712): JW getStartTime201603020000
D/NightModeInfo( 3712): [Nightmode] setAlarmEnd~!!~!!~!!
D/NightModeInfo( 3712): [Nightmode] currentHour > 6
D/NightModeInfo( 3712): [Nightmode] currentHour > 6
,I/NightModeInfo( 3712): JW getEndTime201603020600
D/NightModeInfo( 3712): [Nightmode] currentHour > 6
I/NightModeInfo( 3712): getStartTime201603020000
D/NightModeInfo( 3712): [Nightmode] currentHour > 6
I/NightModeInfo( 3712): getEndTime201603020600
D/jw      ( 3712): Only VZW Supported end return
I/ActivityManager(  855): Killing 3568:com.qualcomm.timeservice/1000 (adj 15): empty #11
,W/libprocessgroup(  855): failed to open /acct/uid_1000/pid_3568/cgroup.procs: No such file or directory
,V/DownloadManager( 3468): Received broadcast intent for android.intent.action.BOOT_COMPLETED
V/DownloadManager( 3468): DownloadService onCreate
I/NotificationManager( 3468): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3468): in removeSpuriousFiles
V/DownloadManager( 3468): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3468): created cursor android.database.sqlite.SQLiteCursor@f859547 on behalf of 3468
,I/DownloadManager( 3468): in trimDatabase
V/DownloadManager( 3468): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3468): DownloadService onStartCommand
D/MediaScannerReceiver( 3468): [MediaScanner] ACTION_BOOT_COMPLETED scan INTERNAL_VOLUME, EXTERNAL_VOLUME
V/DownloadManager( 3468): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3468): created cursor android.database.sqlite.SQLiteCursor@1dc1d712 on behalf of 3468
D/MediaScannerService( 3468): [MediaScanner] start scanning volume internal: [/system/media, /oem/media, /cust/OPEN_EU/media]
V/DownloadManager( 3468): created cursor android.database.sqlite.SQLiteCursor@24fc3ee3 on behalf of 3468
,V/LGMediaProvider( 3468): insertInternal: content://media/none/media_scanner, initValues=volume=internal
D/MediaScannerService( 3468): [MediaScanner] scan() ACTION_MEDIA_SCANNER_STARTED uri : file:///system/media
,D/MtpService( 3468): updating state; isCurrentUser=true, mMtpLocked=false
D/MtpService( 3468): addStorageLocked 65537 /storage/emulated/0
E/MtpStorageEx( 3468): setAccessCapability false
D/MtpService( 3468): updating state; isCurrentUser=true, mMtpLocked=false
D/WiseScreenService( 1853): [OnBootReceiver.java:24:onReceive()] iKeepScreenOn: 0
D/WiseScreenService( 1853): [OnBootReceiver.java:28:onReceive()] iSmartVideo: 0
W/ContextImpl( 1853): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1804 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.lge.keepscreenon.OnBootReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2663 
,I/MusicBrowser( 2786): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_STARTED dat=file:///system/media flg=0x10 }}
,I/MusicBrowser( 2786): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 2786): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_STARTED
I/art     ( 3468): Thread[1,tid=3468,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31f8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
,E/MediaProfilesEx-JNI( 3468): register_com_lge_media_MediaProfilesEx
,E/MediaRecorderEx-JNI( 3468): register_com_lge_media_MediaRecorderEx
D/AudioSystemEx( 3468): register_com_lge_media_LGAudioSystem
E/SurfaceControlEx( 3468): register_com_lge_view_SurfaceControlEx
I/art     ( 3468): Thread[1,tid=3468,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31f8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
D/LGMtpDatabaseJNI( 3468): register_android_mtp_LGMtpDatabase
I/ActivityManager(  855): Start proc com.lge.voicerecorder for broadcast com.lge.voicerecorder/.bookmarkdb.BootCompletedReceiver: pid=3807 uid=10034 gids={50034, 9997, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
D/LGMtpServerJNI( 3468): register_android_mtp_LGMtpServer
I/art     ( 3468): Thread[1,tid=3468,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31f8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
E/MediaPlayerEx-jni( 3468): register_com_lge_view_MediaPlayerEx
I/art     ( 3468): Thread[1,tid=3468,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31f8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
D/        ( 3468): register_com_lge_emoji_EmojiUtil
E/LGMtpDatabaseJNI( 3468): android_mtp_LGMtpDatabase_setup
I/art     (  305): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 301us total 24.469ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 261us total 20.323ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 3.231ms total 23.297ms
,D/MediaScannerEx( 3468): [MediaScanner] scanDirectories()[0] = /system/media
D/MediaScannerEx( 3468): [MediaScanner] scanDirectories()[1] = /oem/media
D/MediaScannerEx( 3468): [MediaScanner] scanDirectories()[2] = /cust/OPEN_EU/media
D/MtpService( 3468): starting MTP server in PTP mode
D/LGMtpServer( 3468): LGMtpServer
D/LGMtpServerJNI( 3468): android_mtp_LGMtpServer_setup
D/MtpService( 3468): addStorageLocked 65537 /storage/emulated/0
E/MtpStorageEx( 3468): setAccessCapability false
D/MtpServerEx( 3468): ANR FIX - addStorage!
,V/DownloadManager( 3468): DownloadService onDestroy
D/LGMtpServerJNI( 3468): android_mtp_LGMtpServer_run
,V/MediaScannerClient( 3468): [MediaScanner]setLocale: = en_US
,E/MediaFileEx( 3468): Duplicate type = AVI
E/MediaFileEx( 3468): Duplicate type = ASF
V/MediaScannerClient( 3468): [MediaScanner]setLocale: = en_US
W/MediaScanner( 3468): Error opening directory '/oem/media/', skipping: No such file or directory.
V/MediaScannerClient( 3468): [MediaScanner]setLocale: = en_US
W/MediaScanner( 3468): Error opening directory '/cust/OPEN_EU/media/', skipping: No such file or directory.
D/LGMediaProvider( 3468): [MediaScanner] delete() uri = content://media/internal/file
,I/VRBookmarkProvider( 3807): [BookmarkProvider.java:76:<init>()-[Thread:Other] BookmarkProvider
D/LGMediaProvider( 3468): [MediaScanner] delete() completed notifyChange, uri = content://media/internal
V/MediaScannerEx( 3468): [MediaScanner] isInternalStorage : true
V/MediaScannerEx( 3468): [MediaScanner] isInternalStorage : true
V/MediaScannerEx( 3468): [MediaScanner] isInternalStorage : true
I/VRBookmarkProvider( 3807): [BookmarkProvider.java:254:onCreate()-[Thread:Other] onCreate
I/VRBookmarkProvider( 3807): [BookmarkProvider.java:504:registerObservers()-[Thread:Other] registerObservers : content://media/external/audio/media
D/MediaScanner( 3468): [MediaScanner] prescan time: 48ms
D/MediaScanner( 3468): [MediaScanner] scan time: 26ms
D/MediaScanner( 3468): [MediaScanner] postscan time: 8ms
D/MediaScanner( 3468): [MediaScanner] total time: 82ms
D/LGMediaProvider( 3468): [MediaScanner] delete() uri = content://media/none/media_scanner
D/VRBootCompletedReceiver( 3807): [BootCompletedReceiver.java:25:onReceive()-[Thread:Other] Controller has been started on Boot complete
,D/VRBootCompletedReceiver( 3807): [BootCompletedReceiver.java:47:onReceive()-[Thread:Other] Voice Recorder launcher enable(1)/disable(2) : 1
I/ActivityManager(  855): Killing 3414:com.lge.clock/u0a10 (adj 15): empty #11
D/MediaScannerService( 3468): [MediaScanner] scan() Send Intent ACTION_MEDIA_SCANNER_FINISHED uri : file:///system/media
,W/libprocessgroup(  855): failed to open /acct/uid_10010/pid_3414/cgroup.procs: No such file or directory
,I/MusicBrowser( 2786): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///system/media flg=0x10 }}
D/LGMediaProvider( 3468): [MediaScanner] mUnmountReceiver ACTION_MEDIA_SCANNER_FINISHED : uri = file:///system/media, path = /system/media
D/MediaScannerService( 3468): [MediaScanner] done scanning volume internal
D/LGBootCompleteReceiver( 1783): onReceive : android.intent.action.BOOT_COMPLETED
D/ConfigUtils( 1783): setUsimOperator() : card operator = 
D/ConfigUtils( 1783): setUsimOperator() : result = null
D/MediaScannerService( 3468): [MediaScanner] start scanning volume external: [/storage/emulated/0, /storage/external_SD]
I/MusicBrowser( 2786): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 2786): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_FINISHED
V/LGMediaProvider( 3468): insertInternal: content://media/none/media_scanner, initValues=volume=external
D/MediaScannerService( 3468): [MediaScanner] scan() ACTION_MEDIA_SCANNER_STARTED uri : file:///storage/emulated/0
D/ConfigUtils( 1783): setUsimOperator() : simOperator = 
D/ConfigUtils( 1783): setUsimOperator() : usimoperator = 0
V/LGMediaProvider( 3468): insertInternal: content://media/, initValues=name=external
D/ConfigUtils( 1783): setSupportedUsimMobilityForVoLTE() : false
I/MusicWidget( 2753): _mediaDataObserver onChange()
,D/MediaScannerEx( 3468): [MediaScanner] scanDirectories()[0] = /storage/emulated/0
D/MediaScannerEx( 3468): [MediaScanner] scanDirectories()[1] = /storage/external_SD
I/MusicBrowser( 2786): [MediaPlaybackService.java:reloadQueue()] oooooo 
D/MusicBrowser( 2786): [MediaPlaybackService.java:reloadQueue()] oooooo id=-1
D/MusicBrowser( 2786): [MediaPlaybackService.java:reloadQueue()] oooooo mCardId=-1
D/MusicBrowser( 2786): [MediaPlaybackService.java:reloadQueue()] oooooo mPreferences.id=-1
D/MusicBrowser( 2786): [MediaPlaybackService.java:reloadQueue()] oooooo q=
D/MusicBrowser( 2786): [MediaPlaybackService.java:reloadQueue()] oooooo q.length=0
W/VRBookmarkProvider( 3807): [BookmarkProvider.java:546:onChange()-[Thread:Other] Data Change!! false url : content://media/
D/MusicBrowser( 2786): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.queuechanged}
I/MusicBrowser( 2786): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
D/MusicBrowser( 2786): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
,I/MusicWidget( 2753): beingMusicWidget_4x2() result::false
D/MusicBrowser( 2786): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2786): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2786): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2786): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2786): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
D/ConfigUtils( 1783): This Model Voice Clarity Support : false
D/MusicBrowser( 2786): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2786): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
I/MusicWidget( 2753): intentReceiver onReceive() action::com.lge.music.queuechanged
I/MusicWidget( 2753): beingMusicWidget_4x2() result::false
I/MusicWidget( 2753): beingMusicWidget_Quick() result::false
I/MusicBrowser( 2786): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2786): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
I/MusicWidget( 2753): beingMusicWidget_4x1() result::true
I/MusicWidget( 2753): send mDelayedStopHandler
I/MusicWidget( 2753): performViewUpdater handleMessage() msg.what::3
I/MusicWidget( 2753): beingMusicWidget_Quick() result::false
D/LGBootCompleteReceiver( 1783): onReceive : updateCallrejectNotify rejectCallOption : 1
D/MusicBrowser( 2786): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2786): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2786): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
D/MusicBrowser( 2786): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.metachanged}
I/MusicBrowser( 2786): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
D/MusicBrowser( 2786): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
D/MusicBrowser( 2786): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2786): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2786): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2786): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2786): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2786): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2786): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
I/MusicWidget( 2753): intentReceiver onReceive() action::com.lge.music.metachanged
I/MusicBrowser( 2786): [MediaPlaybackService.java:3426:notifyChange()] oooooo mRemoteControlClient.editMetadata :: META_CHANGED 
I/MusicWidget( 2753): beingMusicWidget_4x2() result::false
I/MusicBrowser( 2786): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=false}
,I/MusicBrowser( 2786): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
,I/MusicWidget( 2753): beingMusicWidget_Quick() result::false
I/MusicWidget( 2753): beingMusicWidget_4x1() result::true
I/MusicWidget( 2753): send mDelayedStopHandler
I/MusicWidget( 2753): performViewUpdater handleMessage() msg.what::3
I/MusicWidget( 2753): beingMusicWidget_Quick() result::false
D/MusicBrowser( 2786): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2786): [MediaPlaybackService.java:updateGroupIndexData()] oooooo 
I/MusicBrowser( 2786): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2786): [MediaPlaybackService.java:9999:run()] oooooo AlbumImageUpdater() run :: Start
I/MusicBrowser( 2786): [MediaPlaybackService.java:10051:run()] oooooo AlbumImageUpdater() run :: End
D/CallRejectInfoToNotify( 1783): update : tPhoneMode : false
I/NotificationManager( 1783): com.android.phone: cancel(2131493582) by com.android.phone
I/MusicBrowser( 2786): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2786): [GroupIndexApi.java:groupingIndexDataProviderStart()] oooooo 
I/MusicBrowser( 2786): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_STARTED dat=file:///storage/emulated/0 flg=0x10 }}
I/PhoneApp( 1783): saveDefaultRingtoneUriOfOwner = content://media/internal/audio/media/55
I/MusicBrowser( 2786): [GroupingIndexDataProvider.java:101:doInBackground()] oooooo mIsMusicPickerMode = false
I/MusicBrowser( 2786): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 2786): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_STARTED
,W/MusicBrowser( 2786): - Start trace [MusicUtils.query]---------------------------------------------------------------
W/MusicBrowser( 2786): [Line 003751] MusicUtils.java, query() : MusicUtils.query
W/MusicBrowser( 2786): [Line 003761] MusicUtils.java, isMediaScannerScanning() : MusicUtils.query
W/MusicBrowser( 2786): [Line 001991] MediaPlaybackService.java, onChange() : MusicUtils.query
W/MusicBrowser( 2786): [Line 000130] ContentObserver.java, onChange() : MusicUtils.query
W/MusicBrowser( 2786): - End   trace [MusicUtils.query]---------------------------------------------------------------
V/MediaScannerClient( 3468): [MediaScanner]setLocale: = en_US
,D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out(  855): propertyValue:false
I/ActivityManager(  855): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=3838 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
D/LgeGpsLocationProvider(  855): NTP server: europe.pool.ntp.org
,D/LgeGpsLocationProvider(  855): NTP server returned: 1456842800077 (Tue Mar 01 15:33:20 GMT+01:00 2016) reference: 51111 certainty: 22 system time offset: -7
I/art     ( 3468): Explicit concurrent mark sweep GC freed 15581(997KB) AllocSpace objects, 6(96KB) LOS objects, 24% free, 8MB/10MB, paused 5.052ms total 97.817ms
,I/MusicWidget( 2753): performViewUpdater handleMessage() msg.what::0
,D/MediaScannerEx( 3468): [MediaScanner] beginFile() path = /storage/emulated/0/QuicksetLite Setup/data
I/MusicWidget( 2753): beingMusicWidget_4x1() result::true
I/MusicWidget( 2753): performUpdate()_4x1
I/MusicWidget( 2753): defaultAppWidget()_4x1
I/iu.UploadsManager( 2308): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
V/DrmBroadcastReceiver( 3838): Receive ACTION_BOOT_COMPLETED
I/MusicWidget( 2753): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2753): 4x1_currentTheme :: null
,I/MusicWidget( 2753): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2753): setDefaultViewLayoutId()_4x1
V/DrmService( 3838): Service onCreate
V/MediaScannerClient( 3468): [MediaScanner]setLocale: = en_US
W/MediaScanner( 3468): Error opening directory '/storage/external_SD/', skipping: Permission denied.
D/LGMediaProvider( 3468): [MediaScanner] delete() uri = content://media/external/file
D/DrmService( 3838): Received new request = 4
W/VRBookmarkProvider( 3807): [BookmarkProvider.java:546:onChange()-[Thread:Other] Data Change!! false url : content://media/external
W/VRBookmarkProvider( 3807): [BookmarkProvider.java:563:onChange()-[Thread:Other] EXTERNAL Change!!
W/MusicBrowser( 2786): - Start trace [MusicUtils.query]---------------------------------------------------------------
W/MusicBrowser( 2786): [Line 003751] MusicUtils.java, query() : MusicUtils.query
D/LGMediaProvider( 3468): [MediaScanner] delete() completed notifyChange, uri = content://media/external
W/MusicBrowser( 2786): [Line 003761] MusicUtils.java, isMediaScannerScanning() : MusicUtils.query
W/MusicBrowser( 2786): [Line 001991] MediaPlaybackService.java, onChange() : MusicUtils.query
W/MusicBrowser( 2786): [Line 000130] ContentObserver.java, onChange() : MusicUtils.query
W/MusicBrowser( 2786): - End   trace [MusicUtils.query]---------------------------------------------------------------
I/MusicWidget( 2753): appWidgetViewUpdate()_4x1
I/MusicWidget( 2753): linkButtons()_4x1
V/MediaScanner( 3468): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@2360a75b
,V/MediaScanner( 3468): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@2360a75b
D/MediaScanner( 3468): [MediaScanner] prescan time: 73ms
D/MediaScanner( 3468): [MediaScanner] scan time: 106ms
D/MediaScanner( 3468): [MediaScanner] postscan time: 13ms
D/MediaScanner( 3468): [MediaScanner] total time: 192ms
D/LGMediaProvider( 3468): [MediaScanner] delete() uri = content://media/none/media_scanner
D/DrmServiceHandler( 3838): updateDrmPushNotification() : No notification
D/DrmService( 3838): Completed !! request = 4
D/DrmService( 3838): Request count = 0
D/MediaScannerService( 3468): [MediaScanner] scan() Send Intent ACTION_MEDIA_SCANNER_FINISHED uri : file:///storage/emulated/0
,I/ActivityManager(  855): Start proc com.lge.cloudhub for broadcast com.lge.cloudhub/.service.CloudHubReceiver: pid=3859 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicBrowser( 2786): [MediaPlaybackService.java:1995:onChange()] oooooo 
,V/DrmService( 3838): Service onDestroy
D/MediaScannerService( 3468): [MediaScanner] done scanning volume external
D/LGMediaProvider( 3468): [MediaScanner] mUnmountReceiver ACTION_MEDIA_SCANNER_FINISHED : uri = file:///storage/emulated/0, path = /storage/emulated/0
I/MusicWidget( 2753): pushUpdate()_4x1
V/MusicBrowser( 2786): [MediaPlaybackService.java:5808:getPath()] oooooo {mFileToPlay=null}
I/MusicBrowser( 2786): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///storage/emulated/0 flg=0x10 }}
I/MusicWidget( 2753): _mediaDataObserver onChange()
I/MusicBrowser( 2786): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 2786): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_FINISHED
I/MusicWidget( 2753): beingMusicWidget_4x2() result::false
I/MusicWidget( 2753): performViewUpdater handleMessage() msg.what::1
,I/MusicWidget( 2753): beingMusicWidget_4x2() result::false
I/MusicBrowser( 2786): [MediaPlaybackService.java:reloadQueue()] oooooo 
D/MusicBrowser( 2786): [MediaPlaybackService.java:reloadQueue()] oooooo id=-1
D/MusicBrowser( 2786): [MediaPlaybackService.java:reloadQueue()] oooooo mCardId=-1
D/MusicBrowser( 2786): [MediaPlaybackService.java:reloadQueue()] oooooo mPreferences.id=-1
D/MusicBrowser( 2786): [MediaPlaybackService.java:reloadQueue()] oooooo q=
D/MusicBrowser( 2786): [MediaPlaybackService.java:reloadQueue()] oooooo q.length=0
D/MusicBrowser( 2786): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.queuechanged}
I/MusicBrowser( 2786): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
,D/MusicBrowser( 2786): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
D/MusicBrowser( 2786): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2786): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2786): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2786): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2786): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2786): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2786): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
I/MusicWidget( 2753): intentReceiver onReceive() action::com.lge.music.queuechanged
I/MusicBrowser( 2786): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2786): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
I/MusicWidget( 2753): beingMusicWidget_4x2() result::false
I/MusicWidget( 2753): beingMusicWidget_Quick() result::false
I/MusicWidget( 2753): beingMusicWidget_4x1() result::true
I/MusicWidget( 2753): send mDelayedStopHandler
I/MusicWidget( 2753): performViewUpdater handleMessage() msg.what::3
D/MusicBrowser( 2786): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
I/MusicWidget( 2753): beingMusicWidget_Quick() result::false
D/MusicBrowser( 2786): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2786): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
D/MusicBrowser( 2786): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.metachanged}
I/MusicBrowser( 2786): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
D/MusicBrowser( 2786): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
,D/MusicBrowser( 2786): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2786): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2786): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2786): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2786): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2786): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2786): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
,I/MusicWidget( 2753): intentReceiver onReceive() action::com.lge.music.metachanged
I/MusicWidget( 2753): beingMusicWidget_4x2() result::false
I/MusicWidget( 2753): beingMusicWidget_Quick() result::false
I/MusicWidget( 2753): beingMusicWidget_4x1() result::true
I/MusicWidget( 2753): send mDelayedStopHandler
I/MusicWidget( 2753): performViewUpdater handleMessage() msg.what::3
I/MusicWidget( 2753): beingMusicWidget_Quick() result::false
I/MusicBrowser( 2786): [MediaPlaybackService.java:3426:notifyChange()] oooooo mRemoteControlClient.editMetadata :: META_CHANGED 
I/MusicBrowser( 2786): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=false}
I/MusicBrowser( 2786): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
I/MusicBrowser( 2786): [MediaPlaybackService.java:9999:run()] oooooo AlbumImageUpdater() run :: Start
I/MusicBrowser( 2786): [MediaPlaybackService.java:10051:run()] oooooo AlbumImageUpdater() run :: End
D/MusicBrowser( 2786): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2786): [MediaPlaybackService.java:updateGroupIndexData()] oooooo 
I/MusicBrowser( 2786): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2786): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2786): [GroupIndexApi.java:groupingIndexDataProviderStart()] oooooo 
,I/MusicBrowser( 2786): [GroupingIndexDataProvider.java:101:doInBackground()] oooooo mIsMusicPickerMode = false
I/[LgeWidgetLib]LgeAppWidgetHostView( 1909): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/iu.UploadsManager( 2308): End new media; added: 0, uploading: 0, time: 146 ms
I/ActivityManager(  855): Killing 3589:com.lge.appbox.client:SingleBinaryService/u0a11 (adj 15): empty #11
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1909): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,W/libprocessgroup(  855): failed to open /acct/uid_10011/pid_3589/cgroup.procs: No such file or directory
V/CloudHub( 3859): [DATABASE][DBConnection|open] open database
,E/CloudHub( 3859): [DATABASE][DBConnection|getUserId] User id: 0
E/CloudHub( 3859): [DATABASE][DBConnection|getDatabasePath] Database path: /data/user/0/com.lge.cloudhub/databases/cloudhub.db
,V/CloudHub( 3859): [SERVICE][CloudHubReceiver|queryUploadCount] # of contents to upload: 0
V/DownloadManager( 3468): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,I/VRBookmarkProvider( 3807): [BookmarkProvider.java:530:handleMessage()-[Thread:Other] -- syncTable() START --
V/DownloadManager( 3468): created cursor android.database.sqlite.SQLiteCursor@e872bf8 on behalf of 3859
V/CloudHub( 3859): [SERVICE][CloudHubReceiver|queryDownloadCount] # of contents to download: 0
I/MusicWidget( 2753): performViewUpdater handleMessage() msg.what::0
I/MusicWidget( 2753): beingMusicWidget_4x1() result::true
I/MusicWidget( 2753): performUpdate()_4x1
I/MusicWidget( 2753): defaultAppWidget()_4x1
I/MusicWidget( 2753): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2753): 4x1_currentTheme :: null
I/MusicWidget( 2753): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2753): setDefaultViewLayoutId()_4x1
,I/MusicWidget( 2753): appWidgetViewUpdate()_4x1
I/MusicWidget( 2753): linkButtons()_4x1
,I/ActivityManager(  855): Start proc com.lge.gnss.airtest for broadcast com.lge.gnss.airtest/.GnssAirTestReceiver: pid=3879 uid=10054 gids={50054, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  855): Killing 3610:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/libprocessgroup(  855): failed to open /acct/uid_10011/pid_3610/cgroup.procs: No such file or directory
I/MusicWidget( 2753): pushUpdate()_4x1
,I/MusicWidget( 2753): performViewUpdater handleMessage() msg.what::1
I/MusicWidget( 2753): beingMusicWidget_4x2() result::false
I/[LgeWidgetLib]LgeAppWidgetHostView( 1909): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1909): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/art     (  855): Explicit concurrent mark sweep GC freed 15334(703KB) AllocSpace objects, 2(221KB) LOS objects, 33% free, 22MB/34MB, paused 2.222ms total 144.058ms
,V/AlarmManager(  855): ELAPSED_WAKEUP set : Alarm{ceb6c2a type 2 when 51638 com.android.providers.calendar} when 51638
I/VRBookmarkProvider( 3807): [BookmarkProvider.java:532:handleMessage()-[Thread:Other] -- syncTable() END --
D/AirTest ( 3879): Set airtest_enable to false
,I/ActivityManager(  855): Killing 3387:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  855): failed to open /acct/uid_10086/pid_3387/cgroup.procs: No such file or directory
,V/LGSC    ( 2733): [104] 401
I/ActivityManager(  855): Start proc com.lge.lgfota.permission for broadcast com.lge.lgfota.permission/.DmcTargetValidationReceiver: pid=3900 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/TARGETVALIDLATION_RECEIVER( 3900): TargetValidationReceiver_ACTION_BOOT_COMPLETETED Received
D/TARGETVALIDLATION_RECEIVER( 3900): updateFlag = new File(TARGET_FLAG_PATH)
,D/TARGETVALIDLATION_RECEIVER( 3900): Do Not display result dialog. it is not used Update Tool!!
I/ActivityManager(  855): Killing 2037:com.google.process.gapps/u0a6 (adj 15): empty #11
W/libprocessgroup(  855): failed to open /acct/uid_10006/pid_2037/cgroup.procs: No such file or directory
,V/LGSC    ( 1783): [101] 102, action=android.intent.action.BOOT_COMPLETED, iccState=null
W/ContextImpl( 2694): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.qualcomm.atfwd.AtFwdAutoboot.onReceive:24 android.app.ActivityThread.handleReceiver:2663 
E/AtFwd AutoBoot( 2694): AtFwd Auto Boot Started Successfully
,I/ActivityManager(  855): Start proc com.google.process.gapps for broadcast com.google.android.syncadapters.contacts/.ContactsSyncAdapterBroadcastReceiver: pid=3920 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/GservicesProvider( 3920): Gservices pushing to system: true; secure/global: true
,I/GoogleHttpClient( 3920): GMS http client unavailable, use old client
,D/BluetoothManagerService(  855): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  855): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@11ac20f6 mBinding = false
I/GoogleHttpClient( 3920): GMS http client unavailable, use old client
D/BluetoothManagerService(  855): Message: 2
,D/LocationManagerService(  855): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  855): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  855): JNI:system_update. Event-4
D/BluetoothAdapterService(1029591394)( 2091): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3eee00c8
D/BluetoothManagerService(  855): Sending off request.
D/WifiServiceImplEx(  855): setWifiEnabled: false pid=3247, uid=10317, package= com.example.hello, App Lable : HelloWorld
D/WifiService(  855): setWifiEnabled: false pid=3247, uid=10317
D/BluetoothAdapterService(1029591394)( 2091): disable() called...
D/BluetoothAdapterService(1029591394)( 2091): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3eee00c8
,D/BluetoothAdapterService(1029591394)( 2091): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3eee00c8
D/BluetoothAdapterState( 2091): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 2091): Setting state to 13
I/BluetoothAdapterState( 2091): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService(1029591394)( 2091): updateAdapterState() - Broadcasting state to 1 receivers.
D/LocationManagerService(  855): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  855): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  855): JNI:system_update. Event-4
,I/jxcore-log( 3247): ****TEST TOOK:  5083  ms ****
I/jxcore-log( 3247): 
I/jxcore-log( 3247): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3247): 
E/WifiStateMachine(  855): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  855): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/ActivityManager(  855): Start proc com.lge.defaultaccount for broadcast com.lge.defaultaccount/.receiver.ReceiverBootUp: pid=3944 uid=10062 gids={50062, 9997} abi=armeabi-v7a
,D/BluetoothAdapterProperties( 2091): onBluetoothDisable()
I/BluetoothAdapterState( 2091): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/LGWifiP2pService(  855): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  855): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  855): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  276): Clearing all IP addresses on wlan0
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 7
I/MusicBrowser( 2786): [MediaPlaybackService.java:2010:handleMessage()] oooooo mGroupIndexHandler msg.what : 0
I/MusicBrowser( 2786): [MediaPlaybackService.java:updateGroupIndexData()] oooooo 
I/MusicBrowser( 2786): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2786): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
,I/MusicBrowser( 2786): [GroupIndexApi.java:groupingIndexDataProviderStart()] oooooo 
I/MusicBrowser( 2786): [GroupingIndexDataProvider.java:101:doInBackground()] oooooo mIsMusicPickerMode = false
I/bt-btif ( 2091): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 2091): Scan Mode:20
,D/BluetoothAdapterState( 2091): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
I/bt-btif ( 2091): BTIF DISABLE BLUETOOTH:: current btif_core_radio_refcount: 1, btif_core_state: 2, btif_core_cb.dut_mode: 0
E/bt-btif ( 2091): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
D/bt-btif ( 2091): btsock_ctrl_hci_cleanup(L202): poll handle:4
I/bt-btif ( 2091): BTA_JvDeleteRecord
I/bt-btif ( 2091): BTA_JvRfcommStopServer
I/bt-btif ( 2091): BTA_JvDeleteRecord
I/bt-btif ( 2091): BTA_JvRfcommStopServer
D/IOP_DB_BT( 2091): db_close: nbr users 0
D/IOP_DB_BT( 2091): db_close: free database
D/BluetoothAdapterService(1029591394)( 2091): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3eee00c8
D/BluetoothManagerService(  855): Message: 60
D/BluetoothManagerService(  855): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  855): Bluetooth State Change Intent: 12 -> 13
D/btif_config_util( 2091): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/btif_config_util( 2091): enum_config(L300): in, key:Adapter, value:BluezMigrationDone
D/btif_config_util( 2091): enum_config(L302): section name:Local, key name:Adapter, value name:BluezMigrationDone, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:Adapter, value:BluezMigrationDone
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:Adapter, value:Address
D/btif_config_util( 2091): enum_config(L302): section name:Local, key name:Adapter, value name:Address, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:Adapter, value:Address
D/btif_config_util( 2091): enum_config(L344): out, value:f8:95:c7:87:85:54
D/btif_config_util( 2091): enum_config(L300): in, key:Adapter, value:Name
D/btif_config_util( 2091): enum_config(L302): section name:Local, key name:Adapter, value name:Name, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:Adapter, value:Name
D/btif_config_util( 2091): enum_config(L344): out, value:G3s-1
D/btif_config_util( 2091): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IR
D/btif_config_util( 2091): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IR, value type:binary
D/btif_config_util( 2091): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IR
D/btif_config_util( 2091): enum_config(L344): out, value:��l:4A�O���x�x�E@=-��ӑ`-'����8�\�婓��n�ScanMode
,D/btif_config_util( 2091): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IRK
D/btif_config_util( 2091): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IRK, value type:binary
D/btif_config_util( 2091): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IRK
D/btif_config_util( 2091): enum_config(L344): out, value:�E@=-��ӑ`-'����8�\�婓��n�ScanMode
D/btif_config_util( 2091): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_DHK
D/btif_config_util( 2091): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_DHK, value type:binary
D/btif_config_util( 2091): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_DHK
D/btif_config_util( 2091): enum_config(L344): out, value:��8�\�婓��n�ScanMode
D/btif_config_util( 2091): enum_config(L300): in, key:Adapter, value:ScanMode
D/btif_config_util( 2091): enum_config(L302): section name:Local, key name:Adapter, value name:ScanMode, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:Adapter, value:ScanMode
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:Adapter, value:DiscoveryTimeout
,D/btif_config_util( 2091): enum_config(L302): section name:Local, key name:Adapter, value name:DiscoveryTimeout, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:Adapter, value:DiscoveryTimeout
D/btif_config_util( 2091): enum_config(L344): out, value:x
D/btif_config_util( 2091): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_ER
D/btif_config_util( 2091): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_ER, value type:binary
D/btif_config_util( 2091): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_ER
D/btif_config_util( 2091): enum_config(L344): out, value:s!WE�(E��00:0F:F6
D/btif_config_util( 2091): enum_config(L300): in, key:AutoPairBlacklist, value:AddressBlacklist
D/btif_config_util( 2091): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:AddressBlacklist, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:AutoPairBlacklist, value:AddressBlacklist
D/btif_config_util( 2091): enum_config(L344): out, value:00:02:C7,00:16:FE,00:19:C1,00:1B:FB,00:1E:3D,00:21:4F,00:23:06,00:24:33,00:A0:79,00:0E:6D,00:13:E0,00:21:E8,00:60:57,00:0E:9F,00:12:1C,00:18:91,00:18:96,00:13:04,00:16:FD,00:22:A0,00:0B:4C,00:60:6F,00:23:3D,00:C0:59,00:0A:30,00:1E:AE,00:1C:D7,00:80:F0,00:12:8A,00:09:93,00:80:37,00:26:7E,00:06:F7,00:13:7B,00:1E:B2,00:07:04,00:13:7B,00:14:0A,00:1A:1B,00:22:4D,00:0B:24,00:1E:B2,00:0B:1F,18:6D:99,00:54:AF,18:6D:99,94:44:44,00:21:CC,04:98:F3,00:26:E8
D/btif_config_util( 2091): enum_config(L300): in, key:AutoPairBlacklist, value:ExactNameBlacklist
D/btif_config_util( 2091): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:ExactNameBlacklist, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:AutoPairBlacklist, value:ExactNameBlacklist
D/btif_config_util( 2091): enum_config(L344): out, value:Motorola IHF1000,i.TechBlueBAND,X5 Stereo v1.3,KML_CAN,Microsoft Mouse
D/btif_config_util( 2091): enum_config(L300): in, key:AutoPairBlacklist, value:PartialNameBlacklist
D/btif_config_util( 2091): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:PartialNameBlacklist, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:AutoPairBlacklist, value:PartialNameBlacklist
D/btif_config_util( 2091): enum_config(L344): out, value:BMW,Audi,Parrot,Car
D/btif_config_util( 2091): enum_config(L300): in, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
D/btif_config_util( 2091): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:FixedPinZerosKeyboardBlacklist, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
D/btif_config_util( 2091): enum_config(L344): out, value:00:0F:F6
D/btif_config_util( 2091): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Manufacturer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpVer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpVer
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpSubVer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L344): out, value:�
D/btif_config_util( 2091): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Name
D/btif_config_util( 2091): enum_co,nfig(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Name, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Name
D/btif_config_util( 2091): enum_config(L344): out, value:HTC Desire 820
D/btif_config_util( 2091): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevClass
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevClass, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevClass
D/btif_config_util( 2091): enum_config(L344): out, value:Z
D/btif_config_util( 2091): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevType
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevType, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevType
D/btif_config_util( 2091): enum_config(L344): out, value:
V/BluetoothPbapService( 2091): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/btif_config_util( 2091): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:JustWorks
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:JustWorks, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:JustWorks
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:GlobalTrust, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Service
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Service, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Service
D/btif_config_util( 2091): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2091): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Manufacturer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Manufacturer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Manufacturer
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpVer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpVer
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpSubVer
,W/bt-btif ( 2091): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpSubVer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L344): out, value:$
D/btif_config_util( 2091): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Name
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Name, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Name
D/btif_config_util( 2091): enum_config(L344): out, value:Galaxy S6-1
D/btif_config_util( 2091): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevClass
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevClass, value type:int
,D/btif_config_util( 2091): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevClass
D/btif_config_util( 2091): enum_config(L344): out, value:Z
D/btif_config_util( 2091): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevType
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevType, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevType
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:JustWorks
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:JustWorks, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:JustWorks
D/btif_config_util( 2091): enum_config(L344): out, value:
,D/btif_config_util( 2091): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:GlobalTrust
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:GlobalTrust, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:GlobalTrust
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Service
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Service, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Service
D/btif_config_util( 2091): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2091): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Manufacturer
,D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Manufacturer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Manufacturer
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpVer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpVer
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpSubVer, value type:int
,D/btif_config_util( 2091): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L344): out, value:�
D/btif_config_util( 2091): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Name
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Name, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Name
D/btif_config_util( 2091): enum_config(L344): out, value:A5-1
D/btif_config_util( 2091): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevClass
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevClass, value type:int
,D/btif_config_util( 2091): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevClass
D/btif_config_util( 2091): enum_config(L344): out, value:Z
D/btif_config_util( 2091): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevType
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevType, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevType
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:JustWorks
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:JustWorks, value type:int
,D/btif_config_util( 2091): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:JustWorks
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:GlobalTrust
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:GlobalTrust, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:GlobalTrust
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Service
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Service, value type:string
,D/btif_config_util( 2091): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Service
D/btif_config_util( 2091): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 2091): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Manufacturer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Manufacturer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Manufacturer
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpVer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpVer
,D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpSubVer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L344): out, value:#
D/btif_config_util( 2091): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Name
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Name, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Name
,D/btif_config_util( 2091): enum_config(L344): out, value:Nexus 6
D/btif_config_util( 2091): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevClass
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevClass, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevClass
D/btif_config_util( 2091): enum_config(L344): out, value:Z
D/btif_config_util( 2091): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevType
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevType, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevType
D/btif_config_util( 2091): enum_config(L344): out, value:
,D/btif_config_util( 2091): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:JustWorks
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:JustWorks, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:JustWorks
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:GlobalTrust, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
D/btif_config_util( 2091): enum_config(L344): out, value:
,D/btif_config_util( 2091): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Service
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Service, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Service
D/btif_config_util( 2091): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 2091): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Manufacturer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Manufacturer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Manufacturer,
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpVer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpVer
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpSubVer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L344): out, value:�
D/btif_config_util( 2091): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Name
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Name, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Name
D/btif_config_util( 2091): enum_config(L344): out, value:XT1072
D/btif_config_util( 2091): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevClass
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevClass, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevClass
D/btif_config_util( 2091): enum_config(L344): out, value:Z
D/btif_config_util( 2091): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevType
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevType, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevType
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:JustWorks
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:JustWorks, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:JustWorks
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:GlobalTrust,
,D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:GlobalTrust, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:GlobalTrust
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Service,
,D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Service, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Service
D/btif_config_util( 2091): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2091): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Manufacturer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Manufacturer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Manufacturer
D/btif_config_util( 2091): enum_config(L344): out, value:
,D/btif_config_util( 2091): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpVer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpVer
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpSubVer, value type:int
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 7
,D/btif_config_util( 2091): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L344): out, value:a
D/btif_config_util( 2091): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Name
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Name, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Name
D/btif_config_util( 2091): enum_config(L344): out, value:S5-1
D/btif_config_util( 2091): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevClass
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevClass, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevClass
D/btif_config_util( 2091): enum_config(L344): out, value:Z
D/btif_config_util( 2091): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevType
,D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevType, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevType
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:JustWorks
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:JustWorks, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:JustWorks
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
,D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:GlobalTrust, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Service
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Service, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Service
D/btif_config_util( 2091): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
,D/btif_config_util( 2091): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Manufacturer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Manufacturer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Manufacturer
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:LmpVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:LmpVer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:LmpVer
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:LmpSubVer, value type:int
,D/btif_config_util( 2091): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L344): out, value:	a
D/btif_config_util( 2091): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Name
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Name, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Name
D/btif_config_util( 2091): enum_config(L344): out, value:G4-1
D/btif_config_util( 2091): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:DevClass
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:DevClass, value type:int
,D/btif_config_util( 2091): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:DevClass
D/btif_config_util( 2091): enum_config(L344): out, value:Z
D/btif_config_util( 2091): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:DevType
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:DevType, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:DevType
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:JustWorks
,D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:JustWorks, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:JustWorks
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:GlobalTrust
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:GlobalTrust, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:GlobalTrust
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Service
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Service, value type:string
,D/btif_config_util( 2091): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Service
D/btif_config_util( 2091): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2091): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Manufacturer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Manufacturer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Manufacturer
,D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:LmpVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:LmpVer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:LmpVer
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:LmpSubVer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:LmpSubVer
,D/btif_config_util( 2091): enum_config(L344): out, value:a
D/btif_config_util( 2091): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Name
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Name, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Name
D/btif_config_util( 2091): enum_config(L344): out, value:Thali Test (Galaxy S5)
D/btif_config_util( 2091): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:DevClass
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:DevClass, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:DevClass
,D/btif_config_util( 2091): enum_config(L344): out, value:Z
D/btif_config_util( 2091): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:DevType
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:DevType, value type:int
,D/btif_config_util( 2091): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:DevType
D/btif_config_util( 2091): enum_config(L344): out, value:
,D/btif_config_util( 2091): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:JustWorks
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:JustWorks, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:JustWorks
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:GlobalTrust
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:GlobalTrust, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:GlobalTrust
,D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Service
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Service, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Service
D/btif_config_util( 2091): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2091): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Manufacturer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Manufacturer, value type:int
,D/btif_config_util( 2091): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Manufacturer
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:LmpVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:LmpVer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:LmpVer
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:LmpSubVer, value type:int
,D/btif_config_util( 2091): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L344): out, value:�
D/btif_config_util( 2091): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Name
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Name, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Name
D/btif_config_util( 2091): enum_config(L344): out, value:Thali Test (Galaxy A5)
D/btif_config_util( 2091): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:DevClass
,D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:DevClass, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:DevClass
D/btif_config_util( 2091): enum_config(L344): out, value:Z
D/btif_config_util( 2091): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:DevType
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:DevType, value type:int,
,D/btif_config_util( 2091): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:DevType
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:JustWorks
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:JustWorks, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:JustWorks
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:GlobalTrust
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:GlobalTrust, value type:int,
,D/btif_config_util( 2091): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:GlobalTrust
D/btif_config_util( 2091): enum_config(L344): out, value:
,D/btif_config_util( 2091): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Service
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Service, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Service
D/btif_config_util( 2091): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2091): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Manufacturer
,D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Manufacturer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Manufacturer
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpVer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpVer
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpSubVer
,D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpSubVer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L344): out, value:�
D/btif_config_util( 2091): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Name
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Name, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Name
D/btif_config_util( 2091): enum_config(L344): out, value:Thali Test (Galaxy A3)
D/btif_config_util( 2091): enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevClass
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevClass, value type:int
,D/btif_config_util( 2091): enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevClass
D/btif_config_util( 2091): enum_config(L344): out, value:Z
D/btif_config_util( 2091): enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevType
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevType, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevType
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:08:ec:a9:50:76:27, value:JustWorks
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:JustWorks, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:08:ec:a9:50:76:27, value:JustWorks
,D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:08:ec:a9:50:76:27, value:GlobalTrust
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:GlobalTrust, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:08:ec:a9:50:76:27, value:GlobalTrust
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Service
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Service, value type:string
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/btif_config_util( 2091): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Service
,D/btif_config_util( 2091): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 2091): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Manufacturer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Manufacturer, value type:int
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/btif_config_util( 2091): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Manufacturer
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:LmpVer, value type:int
,D/btif_config_util( 2091): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpVer
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:LmpSubVer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L344): out, value:A
D/btif_config_util( 2091): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Name
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Name, value type:string
,D/btif_config_util( 2091): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Name
D/btif_config_util( 2091): enum_config(L344): out, value:Thali Test's G2
D/btif_config_util( 2091): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevClass
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevClass, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevClass
D/btif_config_util( 2091): enum_config(L344): out, value:Z
D/btif_config_util( 2091): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevType
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevType, value type:int
,D/btif_config_util( 2091): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevType
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:JustWorks
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:JustWorks, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:JustWorks
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:GlobalTrust
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:GlobalTrust, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:GlobalTrust
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Service
,D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Service, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Service
D/btif_config_util( 2091): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2091): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Manufacturer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Manufacturer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Manufacturer
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:LmpVer
,D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:LmpVer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:LmpVer
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:LmpSubVer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L344): out, value:	a
D/btif_config_util( 2091): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Name
,D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Name, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Name
D/btif_config_util( 2091): enum_config(L344): out, value:Note3-1
D/ConnectivityService(  855): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/btif_config_util( 2091): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:DevClass
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:DevClass, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:DevClass
D/btif_config_util( 2091): enum_config(L344): out, value:Z
,D/btif_config_util( 2091): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:DevType
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:DevType, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:DevType
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:JustWorks
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:JustWorks, value type:int
D/ConnectivityService(  855): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
D/btif_config_util( 2091): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:JustWorks
D/btif_config_util( 2091): enum_config(L344): out, value:
,D/btif_config_util( 2091): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:GlobalTrust
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:GlobalTrust, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:GlobalTrust
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Service
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Service, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Service
D/btif_config_util( 2091): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 2091): enum_config(L300): in, key:08:ec:a9:50:75:41, value:Manufacturer
,D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Manufacturer, value type:int
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:DevClass, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:80:01:84:8a:b3:68, value:DevClass
D/btif_config_util( 2091): enum_config(L344): out, value:Z
D/btif_config_util( 2091): enum_config(L300): in, key:80:01:84:8a:b3:68, value:DevType
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:DevType, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:80:01:84:8a:b3:68, value:DevType
D/btif_config_util( 2091): enum_config(L344): out, value:
,D/btif_config_util( 2091): enum_config(L300): in, key:80:01:84:8a:b3:68, value:JustWorks
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:JustWorks, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:80:01:84:8a:b3:68, value:JustWorks
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:80:01:84:8a:b3:68, value:GlobalTrust
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:GlobalTrust, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:80:01:84:8a:b3:68, value:GlobalTrust
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:80:01:84:8a:b3:68, value:Service
,D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:Service, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:80:01:84:8a:b3:68, value:Service
D/btif_config_util( 2091): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 00006675-7475-7265-6469-616c62756d70 
D/btif_config_util( 2091): enum_config(L300): in, key:58:3f:54:73:64:c0, value:Manufacturer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:Manufacturer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:58:3f:54:73:64:c0, value:Manufacturer
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:58:3f:54:73:64:c0, value:LmpVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:LmpVer, value type:int
,D/btif_config_util( 2091): enum_config(L343): out, key:58:3f:54:73:64:c0, value:LmpVer
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:58:3f:54:73:64:c0, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:LmpSubVer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:58:3f:54:73:64:c0, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L344): out, value:�
D/btif_config_util( 2091): enum_config(L300): in, key:58:3f:54:73:64:c0, value:Name
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:Name, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:58:3f:54:73:64:c0, value:Name
D/btif_config_util( 2091): enum_config(L344): out, value:G3-1
,D/btif_config_util( 2091): enum_config(L300): in, key:58:3f:54:73:64:c0, value:DevClass
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:DevClass, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:58:3f:54:73:64:c0, value:DevClass
D/btif_config_util( 2091): enum_config(L344): out, value:Z
D/btif_config_util( 2091): enum_config(L300): in, key:58:3f:54:73:64:c0, value:DevType
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:DevType, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:58:3f:54:73:64:c0, value:DevType
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:58:3f:54:73:64:c0, value:JustWorks
,D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:JustWorks, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:58:3f:54:73:64:c0, value:JustWorks
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:58:3f:54:73:64:c0, value:GlobalTrust
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:GlobalTrust, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:58:3f:54:73:64:c0, value:GlobalTrust,
D/btif_config_util( 2091): enum_config(L344): out, value:
,D/btif_config_util( 2091): enum_config(L300): in, key:58:3f:54:73:64:c0, value:Service
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:Service, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:58:3f:54:73:64:c0, value:Service
D/btif_config_util( 2091): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 2091): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:Manufacturer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:Manufacturer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:Manufacturer
,D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:LmpVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:LmpVer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:LmpVer
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:LmpSubVer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L344): out, value:	a
D/btif_config_util( 2091): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:Name
,D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:Name, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:Name
D/btif_config_util( 2091): enum_config(L344): out, value:Nexus 5
D/btif_config_util( 2091): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:DevClass
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:DevClass, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:DevClass
D/btif_config_util( 2091): enum_config(L344): out, value:Z
D/btif_config_util( 2091): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:DevType
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:DevType, value type:int
,D/btif_config_util( 2091): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:DevType
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:JustWorks
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:JustWorks, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:JustWorks
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:GlobalTrust
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:GlobalTrust, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:GlobalTrust
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:Service
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:Service, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:Service
D/btif_config_util( 2091): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2091): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:Manufacturer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:Manufacturer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:Manufacturer
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:LmpVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:LmpVer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:LmpVer
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:LmpSubVer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L344): out, value:�
D/btif_config_util( 2091): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:Name
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:Name, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:Name
D/btif_config_util( 2091): enum_config(L344): out, value:HTC One M8s
D/btif_config_util( 2091): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:DevClass
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:DevClass, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:DevClass
D/btif_config_util( 2091): enum_config(L344): out, value:Z
D/btif_config_util( 2091): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:DevType
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:DevType, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:DevType
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:JustWorks
D/btif_config_util( 2091): enum_config(L302): section ,name:Remote, key name:90:e7:c4:f6:69:77, value name:JustWorks, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:JustWorks
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:GlobalTrust
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:GlobalTrust, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:GlobalTrust
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:Service
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:Service, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:Service
D/btif_config_util( 2091): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 00006675-7475-7265-6469-616c62756d70 
D/btif_config_util( 2091): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Manufacturer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:Manufacturer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Manufacturer
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:LmpVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:LmpVer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:LmpVer
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:LmpSubVer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L344): out, value:A
D/btif_config_util( 2091): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Name
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:Name, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Name
D/btif_config_util( 2091): enum_config(L344): out, value:S5mini-1
D/btif_config_util( 2091): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:DevClass
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:DevClass, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:DevClass
D/btif_config_util( 2091): enum_config(L344): out, value:Z
D/btif_config_util( 2091): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:DevType
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:DevType, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:DevType
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:JustWorks
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:JustWorks, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:JustWorks
D/btif_config_util( 2091): enum_config(L344): out, v,alue:
D/btif_config_util( 2091): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:GlobalTrust
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:GlobalTrust, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:GlobalTrust
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Service
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:Service, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Service
D/btif_config_util( 2091): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2091): enum_config(L300): in, key:08:00:00:00:67:f3, value:Name
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:08:00:00:00:67:f3, value name:Name, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:08:00:00:00:67:f3, value:Name
D/btif_config_util( 2091): enum_config(L344): out, value:T\���K�`�D�`�D�
D/btif_config_util( 2091): enum_config(L300): in, key:08:00:00:00:67:f3, value:DevClass
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:08:00:00:00:67:f3, value name:DevClass, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:08:00:00:00:67:f3, value:DevClass
D/btif_config_util( 2091): enum_config(L344): out, value:���
D/btif_config_util( 2091): enum_config(L300): in, key:08:00:00:00:67:f3, value:DevType
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:08:00:00:00:67:f3, value name:DevType, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:08:00:00:00:67:f3, value:DevType
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Manufacturer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:Manufacturer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Manufacturer
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:LmpVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:LmpVer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:LmpVer
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:LmpSubVer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Name
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:Name, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Name
D/btif_config_util( 2091): enum_config(L344): out, value:ALE-L21
D/btif_config_util( 2091): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:DevClass
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:DevClass, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:DevClass
D/btif_config_util( 2091): enum_config(L344): out, value:Z
D/btif_config_util( 2091): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:DevType
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:DevType, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:DevType
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:JustWorks
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:JustWorks, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:JustWorks
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:GlobalTrust
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:GlobalTrust, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:GlobalTrust
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Service
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:Service, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Service
D/btif_config_util( 2091): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 2091): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:Manufacturer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:Manufacturer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:Manufacturer
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:LmpVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:LmpVer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:LmpVer
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:LmpSubVer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L344): out, value:#
D/btif_config_util( 2091): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:Name
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:Name, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:Name
D/btif_config_util( 2091): enum_config(L344): out, value:onem9-1
D/btif_config_util( 2091): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:DevClass
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:DevClass, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:DevClass
D/btif_config_util( 2091): enum_config(L344): out, value:Z
D/btif_config_util( 2091): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:DevType
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:DevType, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:DevType
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:JustWorks
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:JustWorks, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:JustWorks
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:GlobalTrust
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:GlobalTrust, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:GlobalTrust
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:14:b4:84:21:3b:49, value:Manufacturer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:Manufacturer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:14:b4:84:21:3b:49, value:Manufacturer
D/btif_config_util( 2091): enum_config(L344): out, value:H
D/btif_config_util( 2091): enum_config(L300): in, key:14:b4:84:21:3b:49, value:LmpVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:LmpVer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:14:b4:84:21:3b:49, value:LmpVer
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:14:b4:84:21:3b:49, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:LmpSubVer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:14:b4:84:21:3b:49, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L344): out, value:?C
D/btif_config_util( 2091): enum_config(L300): in, key:14:b4:84:21:3b:49, value:Name
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:Name, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:14:b4:84:21:3b:49, value:Name
D/btif_config_util( 2091): enum_config(L344): out, value:Tab4
D/btif_config_util( 2091): enum_config(L300): in, key:14:b4:84:21:3b:49, value:DevClass
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:DevClass, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:14:b4:84:21:3b:49, value:DevClass
D/btif_config_util( 2091): enum_config(L344): out, value:Z
D/btif_config_util( 2091): enum_config(L300): in, key:14:b4:84:21:3b:49, value:DevType
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:DevType, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:14:b4:84:21:3b:49, value:DevType
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:14:b4:84:21:3b:49, value:JustWorks
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:JustWorks, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:14:b4:84:21:3b:49, value:JustWorks
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:14:b4:84:21:3b:49, value:GlobalTrust
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:GlobalTrust, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:14:b4:84:21:3b:49, value:GlobalTrust
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:14:b4:84:21:3b:49, value:Service
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:Service, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:14:b4:84:21:3b:49, value:Service
D/btif_config_util( 2091): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2091): enum_config(L300): in, key:58:1b:00:00:20:00, value:DevClass
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:58:1b:00:00:20:00, value name:DevClass, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:58:1b:00:00:20:00, value:DevClass
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:58:1b:00:00:20:00, value:DevType
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:58:1b:00:00:20:00, value name:DevType, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:58:1b:00:00:20:00, value:DevType
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:00:00:00:00:08:00, value:DevClass
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:00:00:00:00:08:00, value name:DevClass, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:00:00:00:00:08:00, value:DevClass
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:00:00:00:00:08:00, value:DevType
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:00:00:00:00:08:00, value name:DevType, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:00:00:00:00:08:00, value:DevType
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:00:00:00:00:41:0e, value:Name
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:00:00:00:00:41:0e, value name:Name, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:00:00:00:00:41:0e, value:Name
D/btif_config_util( 2091): enum_config(L344): out, value:�h�
D/btif_config_util( 2091): enum_config(L300): in, key:00:00:00:00:41:0e, value:DevClass
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:00:00:00:00:41:0e, value name:DevClass, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:00:00:00:00:41:0e, value:DevClass
D/btif_config_util( 2091): enum_config(L344): out, value:��h
D/btif_config_util( 2091): enum_config(L300): in, key:00:00:00:00:41:0e, value:DevType
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:00:00:00:00:41:0e, value name:DevType, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:00:00:00:00:41:0e, value:DevType
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:94:06:6b:a0:e3:f1, value:Name
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:94:06:6b:a0:e3:f1, value name:Name, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:94:06:6b:a0:e3:f1, value:Name
D/btif_config_util( 2091): enum_config(L344): out, value:J���J�hrD�hrD�
D/btif_config_util( 2091): enum_config(L300): in, key:94:06:6b:a0:e3:f1, value:DevClass
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:94:06:6b:a0:e3:f1, value name:DevClass, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:94:06:6b:a0:e3:f1, value:DevClass
D/btif_config_util( 2091): enum_config(L344): out, value:��P
D/btif_config_util( 2091): enum_config(L300): in, key:94:06:6b:a0:e3:f1, value:DevType
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:94:06:6b:a0:e3:f1, value name:DevType, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:94:06:6b:a0:e3:f1, value:DevType
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:08:00:00:00:67:73, value:DevClass
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:08:00:00:00:67:73, value name:DevClass, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:08:00:00:00:67:73, value:DevClass
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:08:00:00:00:67:73, value:DevType
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:08:00:00:00:67:73, value name:DevType, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:08:00:00:00:67:73, value:DevType
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:38:94:96:b5:06:dc, value:Manufacturer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:Manufacturer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:38:94:96:b5:06:dc, value:Manufacturer
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:38:94:96:b5:06:dc, value:LmpVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:LmpVer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:38:94:96:b5:06:dc, value:LmpVer
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:38:94:96:b5:06:dc, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:LmpSubVer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:38:94:96:b5:06:dc, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L344): out, value:�
D/btif_config_util( 2091): enum_config(L300): in, key:38:94:96:b5:06:dc, value:Name
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:Name, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:38:94:96:b5:06:dc, value:Name
D/btif_config_util( 2091): enum_config(L344): out, value:Galaxy S5-2
D/btif_config_util( 2091): enum_config(L300): in, key:38:94:96:b5:06:dc, value:DevClass
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:DevClass, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:38:94:96:b5:06:dc, value:DevClass
D/btif_config_util( 2091): enum_config(L344): out, value:Z
D/btif_config_util( 2091): enum_config(L300): in, key:38:94:96:b5:06:dc, value:DevType
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:DevType, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:38:94:96:b5:06:dc, value:DevType
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:38:94:96:b5:06:dc, value:JustWorks
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:JustWorks, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:38:94:96:b5:06:dc, value:JustWorks
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:38:94:96:b5:06:dc, value:GlobalTrust
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:GlobalTrust, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:38:94:96:b5:06:dc, value:GlobalTrust
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:00:00:00:00:5a:ad, value:Manufacturer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:Manufacturer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:00:00:00:00:5a:ad, value:Manufacturer
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:00:00:00:00:5a:ad, value:LmpVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:LmpVer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:00:00:00:00:5a:ad, value:LmpVer
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:00:00:00:00:5a:ad, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:LmpSubVer, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:00:00:00:00:5a:ad, value:LmpSubVer
D/btif_config_util( 2091): enum_config(L344): out, value:�
D/btif_config_util( 2091): enum_config(L300): in, key:00:00:00:00:5a:ad, value:Name
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:Name, value type:string
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/btif_config_util( 2091): enum_config(L343): out, key:00:00:00:00:5a:ad, value:Name
D/btif_config_util( 2091): enum_config(L344): out, value:A3-1
D/btif_config_util( 2091): enum_config(L300): in, key:00:00:00:00:5a:ad, value:DevClass
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:DevClass, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:00:00:00:00:5a:ad, value:DevClass
D/btif_config_util( 2091): enum_config(L344): out, value:Z
D/btif_config_util( 2091): enum_config(L300): in, key:00:00:00:00:5a:ad, value:DevType
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:DevType, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:00:00:00:00:5a:ad, value:DevType
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:00:00:00:00:5a:ad, value:JustWorks
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:JustWorks, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:00:00:00:00:5a:ad, value:JustWorks
D/WifiNetworkAgent(  855): NetworkAgent: NetworkAgent channel lost
D/LGWifiP2pService(  855): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  855): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGBluetoothAPIService( 1836): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapterService(1029591394)( 2091): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3eee00c8
D/BluetoothAdapterService(1029591394)( 2091): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3eee00c8
E/bt-btif ( 2091): btif_hf_upstreams_evt: wrong handle = 15693 
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:00:00:00:00:41:9e, value name:Name, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:00:00:00:00:41:9e, value:Name
D/btif_config_util( 2091): enum_config(L344): out, value:4g�
D/btif_config_util( 2091): enum_config(L300): in, key:00:00:00:00:41:9e, value:DevClass
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:00:00:00:00:41:9e, value name:DevClass, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:00:00:00:00:41:9e, value:DevClass
D/btif_config_util( 2091): enum_config(L344): out, value:��f
W/bt-obex ( 2091): Ignore event 10 in state 1
I/bt-btif ( 2091): HAL bt_op_callbacks->ops_state_cb
D/BluetoothOPPServiceJni( 2091): ops_state_cb(L223):  ops_state_cb state:3
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/btif_config_util( 2091): enum_config(L300): in, key:00:00:00:00:41:9e, value:DevType
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:00:00:00:00:41:9e, value name:DevType, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:00:00:00:00:41:9e, value:DevType
D/btif_config_util( 2091): enum_config(L344): out, value:
D/btif_config_util( 2091): enum_config(L300): in, key:94:c6:76:a0:e3:b1, value:Name
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:94:c6:76:a0:e3:b1, value name:Name, value type:string
D/btif_config_util( 2091): enum_config(L343): out, key:94:c6:76:a0:e3:b1, value:Name
D/btif_config_util( 2091): enum_config(L344): out, value:4g�������v��
D/btif_config_util( 2091): enum_config(L300): in, key:94:c6:76:a0:e3:b1, value:DevClass
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:94:c6:76:a0:e3:b1, value name:DevClass, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:94:c6:76:a0:e3:b1, value:DevClass
D/btif_config_util( 2091): enum_config(L344): out, value:��\
D/btif_config_util( 2091): enum_config(L300): in, key:94:c6:76:a0:e3:b1, value:DevType
D/btif_config_util( 2091): enum_config(L302): section name:Remote, key name:94:c6:76:a0:e3:b1, value name:DevType, value type:int
D/btif_config_util( 2091): enum_config(L343): out, key:94:c6:76:a0:e3:b1, value:DevType
D/btif_config_util( 2091): enum_config(L344): out, value:
D/OppService( 2091): onOpsStateChange() :3
W/bt-obex ( 2091): Ignore event 10 in state 1
D/OppService( 2091): Recieved MESSAGE_OPS_DISABLE
E/bt-btif ( 2091): bta_gattc_deregister Deregister Failedm unknown client cif
I/BluetoothMapService( 2091): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 2091): STATE_TURNING_OFF
V/BluetoothMapService( 2091): Handler(): got msg=4
D/BluetoothMapService( 2091): MAP Service closeService in
D/BluetoothMapMasInstance( 2091): MAP Service shutdown
V/BluetoothMapMasInstance( 2091): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 2091): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 2091): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 2091): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 2091): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 2091): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 2091): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 2091): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
D/LGBluetoothMapAdapter( 2091): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 2091): MAP Service closeService out
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1372): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
D/LGWifiP2pService(  855): P2pDisablingState
D/LGWifiP2pService(  855): P2pDisablingState{ when=-36ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  855): p2p socket connection lost
D/LGWifiP2pService(  855): P2pDisabledState
D/WifiHS20(  855): hidePasspointNotification off =false
D/LGWifiP2pService(  855): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  855): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  276): Clearing all IP addresses on wlan0
D/ConnectivityService(  855): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  855): disableDataServiceNotify
D/DSQN    (  855): stop dsqn bin
D/ConnectivityService(  855): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ConnectivityService(  855):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  855):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  855): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20(  855): hidePasspointNotification off =false
D/ConnectivityService(  855): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  855): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiScanningService(  855): SCAN_AVAILABLE : 1
D/RttService(  855): SCAN_AVAILABLE : 1
D/WifiScanningService(  855): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  855): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiHS20(  855): hidePasspointNotification off =false
I/QCNEJ   ( 1872): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1872): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-03-01 15:33:21.406 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1872): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1872): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1872): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-03-01 15:33:21.407 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/ConnectivityService(  855):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/QCNEJ   ( 1872): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WfdsService( 1836): WifiP2pState is changed : false
D/ConnectivityService(  855): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524292
D/Nat464Xlat(  855): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  855): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
D/WfdsService( 1836): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsJNI ( 1836): doCommand: P2P_STOP_FIND
D/CSLegacyTypeTracker(  855): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  855): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  855): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 2308): CM callback handler got msg 524292
I/QCNEJ   ( 1872): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/GoogleHttpClient( 3920): GMS http client unavailable, use old client
W/ContextImpl( 3712): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): DefaultState{ when=-14ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): Disconnected - quitting
I/WifiServerServiceExt(  855): WIFI_STATE_CHANGED_ACTION [0]
D/ConnectivityService(  855): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  855): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  855): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  855): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  855): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService(  855): Removing idletimer
V/NetworkPolicy(  855): [LG_RESTRICTED] !!!isConnected  type  :1
D/Tethering(  855): MasterInitialState.processMessage what=3
D/WIFI    (  855): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  855):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1783): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/QCNEJ   ( 1872): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-03-01 15:33:21.423 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1872): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1872): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
V/NetworkPolicy(  855): [LG_RESTRICTED] !!!isConnected  type  :1
D/TelephonyNetworkFactory-1( 1783):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/QCNEJ   ( 1872): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-03-01 15:33:21.433 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1872): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  855): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/Tethering(  855): MasterInitialState.processMessage what=3
E/ConnectivityService(  855): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/WifiServerServiceExt(  855): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  855): setSupplicantStateDISCONNECTED
D/DhcpStateMachine(  855): StoppedState
D/DhcpStateMachine(  855): StoppedState{ when=-66ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
V/BluetoothPbapReceiver( 2091): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 2091): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 2091): ***********state = 13
W/QCNEJ   ( 1872): |CORE| No family connected
W/QCNEJ   ( 1872): |CORE| No family connected
I/QCNEJ   ( 1872): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1872): |CORE| sendDefaultNwMsg: default = -1
V/BluetoothPbapReceiver( 2091): ***********Calling start service!!!! with action = null
,V/BluetoothPbapService( 2091): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 2091): state: 13
V/BluetoothPbapService( 2091): Pbap Service closeService in
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
V/BluetoothPbapService( 2091): successfully stopped pbap service
V/BluetoothPbapService( 2091): Pbap Service closeService out
V/BluetoothPbapService( 2091): Pbap Service onDestroy
V/BluetoothPbapService( 2091): Pbap Service closeService in
V/BluetoothPbapService( 2091): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 2091): [BTUI] cleanup
D/BluetoothManagerService(  855): Message: 20
D/BluetoothManagerService(  855): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@20f15682:true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.p2p.STATE_CHANGED at null
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
D/BluetoothAdapterService(1029591394)( 2091): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3eee00c8
,D/BluetoothManagerService(  855): Message: 30
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
D/BluetoothManagerService(  855): Message: 30
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/LocalBluetoothProfileManager( 3712): Adding local MAP profile
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.WIFI_STATE_CHANGED at null
D/BluetoothMap( 3712): Create BluetoothMap proxy object
D/BluetoothManagerService(  855): Message: 30
D/BluetoothManagerService(  855): Message: 30
,D/LocalBluetoothProfileManager( 3712): LocalBluetoothProfileManager construction complete
D/LGBluetoothFeatureConfig( 3712):  get() - isFeatureLoaded : false
D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
I/Netd    (  276): M: Get netlink event, ifname: p2p0 action: 4
I/Netd    (  276): M: Get netlink event, ifname: p2p0 action: 5
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/Netd    (  276): M: Get netlink event, ifname: p2p0 action: 10
I/wpa_supplicant( 2749): p2p0: CTRL-EVENT-TERMINATING 
I/Netd    (  276): M: Get netlink event, ifname: p2p0 action: 7
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/WfdsMonitor( 1836): Event [CTRL-EVENT-TERMINATING ]
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LGBluetoothUserBindClient( 3712): [BTUI] initUserBindClient
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/ContextImpl( 3712): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
I/wpa_supplicant( 2749): wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
W/wpa_supplicant( 2749): USIM:  scard_deinit function
,I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DockEventReceiver( 3712): finishStartingService: stopping service
,D/BluetoothInputDevice( 3712): Proxy object connected
D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
D/HidProfile( 3712): Bluetooth service connected
D/BluetoothAdapterService(1029591394)( 2091): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3eee00c8
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/BluetoothPan( 3712): BluetoothPAN Proxy object connected
D/PanProfile( 3712): Bluetooth service connected
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/BluetoothAdapterService(1029591394)( 2091): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3eee00c8
D/BluetoothMap( 3712): Proxy object connected
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/MapProfile( 3712): Bluetooth service connected
D/BluetoothMap( 3712): getConnectedDevices()
D/BluetoothAdapterService(1029591394)( 2091): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3eee00c8
D/BluetoothMap( 3712): Bluetooth is Not enabled
D/LGBluetoothUserBindClient( 3712): [BTUI] onServiceConnected
D/LGBluetoothAuthorization( 3712): [BTUI] cancel All Notification
I/NotificationManager( 3712): com.android.settings: cancel(17301632) by com.android.settings
I/NotificationManager( 3712): com.android.settings: cancel(-1000001) by com.android.settings
I/NotificationManager( 3712): com.android.settings: cancel(-1000011) by com.android.settings
I/NotificationManager( 3712): com.android.settings: cancel(-1000021) by com.android.settings
,I/NotificationManager( 3712): com.android.settings: cancel(-1000031) by com.android.settings
I/NotificationManager( 3712): com.android.settings: cancel(-1000041) by com.android.settings
V/AudioFlinger(  280): thread 0xb56eb000 type 0 TID 1296 going to sleep
D/BluetoothPermissionRequest( 3712): onReceive
D/LGBluetoothAuthorization( 3712): [BTUI] cancel All Notification
I/NotificationManager( 3712): com.android.settings: cancel(17301632) by com.android.settings
I/NotificationManager( 3712): com.android.settings: cancel(-1000001) by com.android.settings
I/NotificationManager( 3712): com.android.settings: cancel(-1000011) by com.android.settings
I/NotificationManager( 3712): com.android.settings: cancel(-1000021) by com.android.settings
I/NotificationManager( 3712): com.android.settings: cancel(-1000031) by com.android.settings
I/NotificationManager( 3712): com.android.settings: cancel(-1000041) by com.android.settings
V/AudioFlinger(  280): thread 0xb5651000 type 0 TID 1292 going to sleep
V/AudioFlinger(  280): thread 0xb5735000 type 0 TID 1298 going to sleep
,I/ActivityManager(  855): Killing 3734:com.android.providers.calendar/u0a14 (adj 15): empty #11
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
,D/AndroidRuntime( 3958): 
D/AndroidRuntime( 3958): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 5
I/wpa_supplicant( 2749): wlan0: CTRL-EVENT-TERMINATING 
,D/Tethering(  855): InitialState.processMessage what=4
W/libprocessgroup(  855): failed to open /acct/uid_10014/pid_3734/cgroup.procs: No such file or directory
V/BluetoothOppReceiver( 2091): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
D/BluetoothOppNotification( 2091): [BTUI] cancel opp incoming file confirm notification
I/NotificationManager( 2091): com.android.bluetooth: cancel(-1) by com.android.bluetooth
D/BluetoothOppNotification( 2091): [BTUI] cancel opp active transfer file notification
I/NotificationManager( 2091): com.android.bluetooth: cancel(-1) by com.android.bluetooth
D/Tethering(  855): sendTetherStateChangedBroadcast 0, 0, 0
D/AndroidRuntime( 3958): CheckJNI is OFF
,V/BluetoothSapReceiver( 2091): [BTUI] checkServiceStart
I/InsertAccount( 3944): The account already exists
D/WfdsService( 1836): Supplicant Connection state is changed : false
D/LGBluetoothStateChangeReceiver( 2091): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
,I/ActivityManager(  855): Start proc com.lge.hiddenmenu for broadcast com.lge.hiddenmenu/.kddi_only.sms_setting.AssistReceiver: pid=3992 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/WifiOffDelayIfNotUsed(  855): stopMonitoring
I/ActivityManager(  855): Killing 3753:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
I/ActivityManager(  855): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=4019 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,W/libprocessgroup(  855): failed to open /acct/uid_10069/pid_3753/cgroup.procs: No such file or directory
I/WifiServerServiceExt(  855): WIFI_STATE_CHANGED_ACTION [1]
I/WifiServerServiceExt(  855): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt(  855): batteryPsActivateMsgHandler : this is not treated
I/QCNEJ   ( 1872): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
I/QCNEJ   ( 1872): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-03-01 15:33:21.808 DNS addrs= 0.0.0.0, 0.0.0.0, 
,I/QCNEJ   ( 1872): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.WIFI_STATE_CHANGED at null
W/Settings( 1765): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/InsertAccount( 3944): The account info in contact DB already exists
,W/ResourcesManager( 3992): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 3992): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/ActivityManager(  855): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4036 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 4019): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/ActivityManager(  855): Killing 3777:com.android.managedprovisioning/u0a111 (adj 15): empty #11
,I/[SMS_AD]( 3992): Intent action: android.intent.action.BOOT_COMPLETED
D/AndroidRuntime( 3958): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  855): Killing 3807:com.lge.voicerecorder/u0a34 (adj 15): empty #11
D/AuthorizationBluetoothService( 1765): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
W/libprocessgroup(  855): failed to open /acct/uid_10111/pid_3777/cgroup.procs: No such file or directory
,W/PackageSettings(  855): Skipping PackageSetting{2a598b51 com.test.thalitest/10316} due to missing metadata
,W/libprocessgroup(  855): failed to open /acct/uid_10034/pid_3807/cgroup.procs: No such file or directory
I/[SMS_AD]( 3992): Intent action: android.intent.action.BOOT_COMPLETED
I/ActivityManager(  855): Force stopping com.example.hello appid=10317 user=-1: uninstall pkg
W/ResourcesManager( 4036): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/ActivityManager(  855): Killing 3247:com.example.hello/u0a317 (adj 0): stop com.example.hello
I/WindowState(  855): WIN DEATH: Window{b0550eb u0 com.example.hello/com.example.hello.MainActivity}
,D/CalendarProvider2( 4036): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@22fd0f75
D/InputDispatcher(  855): Focus left window: Window{b0550eb u0 com.example.hello/com.example.hello.MainActivity}
D/InputDispatcher(  855): Window went away: Window{b0550eb u0 com.example.hello/com.example.hello.MainActivity}
I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,W/ActivityManager(  855): Force removing ActivityRecord{226957a u0 com.example.hello/.MainActivity t224}: app died, no saved state
I/UsageStatsService(  855): User[0] Flushing usage stats to disk
I/ActivityManager(  855): Force stopping com.example.hello appid=10317 user=0: pkg removed
,D/KeyguardModel( 1372): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,W/GeofencerStateMachine( 1765): Ignoring removeGeofence because network location is disabled.
W/System.err( 3310): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
,W/System.err( 3310): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3310): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3310): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3310): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3310): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3310): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3310): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3310): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3310): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3310): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3310): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/InputReader(  855): Reconfiguring input devices.  changes=0x00000010
W/ActivityManager(  855): Spurious death for ProcessRecord{3caf5256 3247:com.example.hello/u0a317}, curProc for 3247: null
D/CalendarProvider2( 4036): [getOrCreateCalendarAlarmManager]
I/UsageStatsDatabase(  855): Moving file /data/system/usagestats/0/daily/1456531200000 to /data/system/usagestats/0/daily/1456531193198
,I/UsageStatsDatabase(  855): Moving file /data/system/usagestats/0/daily/1456790400000 to /data/system/usagestats/0/daily/1456790393198
I/UsageStatsDatabase(  855): Moving file /data/system/usagestats/0/weekly/1454543992739 to /data/system/usagestats/0/weekly/1454543985937
I/CalendarProvider2( 4036): Created com.android.providers.calendar.CalendarAlarmManager@2fe52dd6(com.android.providers.calendar.CalendarProvider2@22fd0f75)
I/UsageStatsDatabase(  855): Moving file /data/system/usagestats/0/weekly/1455148792739 to /data/system/usagestats/0/weekly/1455148785937
I/UsageStatsDatabase(  855): Moving file /data/system/usagestats/0/weekly/1456358400000 to /data/system/usagestats/0/weekly/1456358393198
I/[LGHome]EVENT( 1909): [Launcher.java:5203:onStart()]onStart
I/UsageStatsDatabase(  855): Moving file /data/system/usagestats/0/monthly/1443743972386 to /data/system/usagestats/0/monthly/1443743965584
I/UsageStatsDatabase(  855): Moving file /data/system/usagestats/0/monthly/1443743987689 to /data/system/usagestats/0/monthly/1443743980887
I/UsageStatsDatabase(  855): Moving file /data/system/usagestats/0/monthly/1446335987689 to /data/system/usagestats/0/monthly/1446335980887
I/UsageStatsDatabase(  855): Moving file /data/system/usagestats/0/monthly/1446335992739 to /data/system/usagestats/0/monthly/1446335985937
I/UsageStatsDatabase(  855): Moving file /data/system/usagestats/0/monthly/1448927992739 to /data/system/usagestats/0/monthly/1448927985937
I/UsageStatsDatabase(  855): Moving file /data/system/usagestats/0/monthly/1451519992739 to /data/system/usagestats/0/monthly/1451519985937
,I/UsageStatsDatabase(  855): Moving file /data/system/usagestats/0/monthly/1454111992739 to /data/system/usagestats/0/monthly/1454111985937
I/UsageStatsDatabase(  855): Moving file /data/system/usagestats/0/monthly/1454112000000 to /data/system/usagestats/0/monthly/1454111993198
I/UsageStatsDatabase(  855): Moving file /data/system/usagestats/0/monthly/1456704000000 to /data/system/usagestats/0/monthly/1456703993198
I/UsageStatsDatabase(  855): Moving file /data/system/usagestats/0/yearly/1419119972386 to /data/system/usagestats/0/yearly/1419119965584
I/UsageStatsDatabase(  855): Moving file /data/system/usagestats/0/yearly/1419119987689 to /data/system/usagestats/0/yearly/1419119980887
I/UsageStatsDatabase(  855): Moving file /data/system/usagestats/0/yearly/1419119992739 to /data/system/usagestats/0/yearly/1419119985937
I/UsageStatsDatabase(  855): Moving file /data/system/usagestats/0/yearly/1450655992739 to /data/system/usagestats/0/yearly/1450655985937
I/UsageStatsDatabase(  855): Moving file /data/system/usagestats/0/yearly/1450656000000 to /data/system/usagestats/0/yearly/1450655993198
,I/QCNEJ   ( 1872): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/UsageStatsService(  855): User[0] Rollover scheduled @ 2016-03-02 01:00:00(1456876800000)
I/[LGHome]EVENT( 1909): [Launcher.java:776:onResume()]onResume
D/administrator(  855): Handling package changes for user 0
,I/ActivityManager(  855): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=4057 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  855): Killing 2308:com.google.android.gms/u0a6 (adj 15): empty #11
,W/bt-l2cap( 2091): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 2091): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-btif ( 2091): ag scb idx 1 not allocated
E/bt-btif ( 2091): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 2091): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2091): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-btif ( 2091): ag scb idx 1 not allocated
E/bt-btif ( 2091): BTA AG is already disabled, ignoring ...
E/bt-btif ( 2091): bta_gattc_deregister Deregister Failedm unknown client cif
E/bt-btif ( 2091): bta_gattc_deregister Deregister Failedm unknown client cif
W/bt_userial( 2091): select_read return size <=0:0, exiting userial_read_thread
D/bt_hwcfg( 2091): hw_epilog_process
I/bt_userial_vendor( 2091): device fd = 70 close
E/bt_vendor( 2091): [BTUI] Proto is enabled. Set Proto disable!!
,D/ConnectivityService(  855): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@82dbfc7)
D/ConnectivityService(  855): dumpNetworkRequest
D/ConnectivityService(  855): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  855): sending notification RELEASED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  855): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WeatherAncestor( 2780): 2 : onReceive, action: android.intent.action.BOOT_COMPLETED, Time(hour:min:sec) 15:33:22
,W/libprocessgroup(  855): failed to open /acct/uid_10006/pid_2308/cgroup.procs: No such file or directory
I/[LGHome]EVENT( 1909): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[SystemUI]QSlideListController( 1372): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]Launcher.Model( 1909): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,I/[LGHome]LGActivityUtil( 1909): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1909): [Launcher.java:929:onResume()]onResume end
I/Activity( 1909): Activity.onPostResume() called 
I/GKI_LINUX( 2091): GKI_destroy_task(0): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
,I/GKI_LINUX( 2091): gki_task task_id=0 [BTU] terminating
W/[LGHome]LGWallpaperInfo( 1909): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1909): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
I/GKI_LINUX( 2091): GKI_destroy_task(): task [BTU] terminated
I/bt-btif ( 2091): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 2091): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterService( 2091): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2091): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService( 2091): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2091): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2091): Unable to read settings
D/BtSettings.ProfileConfig( 2091): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2091): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 2091): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 2091): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 2091): 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
D/BtSettings.ProfileConfig( 2091): 	at com.android.bluetooth.btservice.AdapterService.stopProfileServices(AdapterService.java:738)
D/BtSettings.ProfileConfig( 2091): 	at com.android.bluetooth.btservice.AdapterState$PendingCommandState.processMessage(AdapterState.java:529)
D/BtSettings.ProfileConfig( 2091): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 2091): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 2091): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 2091): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 2091): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BluetoothAdapterService( 2091): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService(1029591394)( 2091): setProfileServiceState() - Stopping service com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService( 2091): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2091): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService( 2091): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2091): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 2091): Not skipping com.android.bluetooth.a2dp.A2dpService
D/HeadsetService( 2091): Received stop request...Stopping profile...
D/BluetoothAdapterService(1029591394)( 2091): setProfileServiceState() - Stopping service com.android.bluetooth.a2dp.A2dpService
,D/BluetoothAdapterService( 2091): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2091): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
I/LGBluetoothHfpAdapter( 2091): [BTUI] LGBluetoothHfpAdapter cleanup
D/BluetoothAdapterService( 2091): getQuietmodeRadioCount = 0
W/LGBluetoothHeadsetServiceJni( 2091): Cleaning up Bluetooth Handsfree callback object
D/BtSettings.ProfileConfig( 2091): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2091): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d5e5162
W/BluetoothAdapterService( 2091): Not skipping com.android.bluetooth.hid.HidService
D/BluetoothAdapterService(1029591394)( 2091): setProfileServiceState() - Stopping service com.android.bluetooth.hid.HidService
D/HeadsetStateMachine( 2091): Exit Disconnected: -1
D/BluetoothAdapterService(1029591394)( 2091): handleMessage() - Message: 1
D/BluetoothAdapterService(1029591394)( 2091): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1029591394)( 2091): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BluetoothAdapterState( 2091): isTurningOnRadio()=false
D/BluetoothAdapterState( 2091): isTurningOffRadio()=false
D/BluetoothAdapterState( 2091): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2091): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2091): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2091): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2091): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(1029591394)( 2091): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1372): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 1372): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/A2dpService( 2091): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2091): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2091): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 2091): getQuietmodeRadioCount = 0
D/BluetoothHeadset( 1783): Proxy object disconnected
D/BtSettings.ProfileConfig( 2091): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
D/A2dpStateMachine( 2091): Exit Disconnected: -1
D/BluetoothHeadset( 1783): Proxy object disconnected
W/BluetoothAdapterService( 2091): Not skipping com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService(1029591394)( 2091): setProfileServiceState() - Stopping service com.android.bluetooth.hdp.HealthService
D/BluetoothHeadset( 1783): Proxy object disconnected
I/SystemUI[Framework](  855): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  855): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  855): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  855): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  855): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2c57ac8e,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  855): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/BluetoothAdapterService( 2091): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2091): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BluetoothAdapterService( 2091): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2091): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 2091):, Not skipping com.android.bluetooth.pan.PanService
D/BluetoothAdapterService(1029591394)( 2091): setProfileServiceState() - Stopping service com.android.bluetooth.pan.PanService
D/InputDispatcher(  855): Focus entered window: Window{370ff248 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/BluetoothAdapterService( 2091): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2091): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 2091): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2091): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 2091): Not skipping com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(1029591394)( 2091): setProfileServiceState() - Stopping service com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterService( 2091): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2091): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2091): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2091): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 2091): Not skipping com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService(1029591394)( 2091): setProfileServiceState() - Stopping service com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2091): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2091): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 2091): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2091): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 2091): Not skipping com.broadcom.bt.service.sap.SapService
D/LGBluetoothA2dpAdapter( 2091): [BTUI] LGBluetoothA2dpAdapter cleanup
D/BluetoothAdapterService(1029591394)( 2091): setProfileServiceState() - Stopping service com.broadcom.bt.service.sap.SapService
W/LGBluetoothA2dpServiceJni( 2091): Cleaning up Bluetooth Handsfree callback object
D/LGBluetoothPowerControlManager( 2091): [BTUI] terminate
D/BluetoothAdapterService( 2091): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2091): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService( 2091): getQuietmodeRadioCount = 0
D/BluetoothManagerService(  855): Message: 31
D/BtSettings.ProfileConfig( 2091): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService( 2091): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d5e5162
W/BluetoothAdapterService( 2091): Not skipping com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(1029591394)( 2091): setProfileServiceState() - Stopping service com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService( 2091): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2091): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
D/HeadsetStateMachine( 2091): Unbinding service...
D/BluetoothAdapterService( 2091): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2091): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 2091): Not skipping com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(1029591394)( 2091): setProfileServiceState() - Stopping service com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterState( 2091): Stopping profile services that were post enabled
D/UpdateThreadPoolManager( 2780): 2 : This is isUpdating : false
D/HeadsetPhoneState( 2091): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 2091): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 2091): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 2091): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 2091): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2091): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 2091): [BTUI] LGBluetoothHfpAdapter cleanup
D/HidService( 2091): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2091): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d5e5162
,D/HealthService( 2091): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2091): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d5e5162
I/[LGHome]EVENT( 1909): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/PanService( 2091): Received stop request...Stopping profile...
I/[LGHome]LGPlusHomeDBManager( 1909): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/BluetoothAdapterService( 2091): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d5e5162
I/[LGHome]LGPlusHomeDBManager( 1909): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
D/BtGatt.DebugUtils( 2091): handleDebugAction() action=null
D/BtGatt.GattService( 2091): Received stop request...Stopping profile...
D/BtGatt.GattService( 2091): stop()
D/BtGatt.AdvertiseManager( 2091): advertise clients cleared
D/LGBluetoothGattAdapter( 2091): [BTUI] LGBluetoothGattAdapter cleanup
D/BluetoothAdapterService( 2091): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d5e5162
I/InsertAccount( 3944): The account info in calendar DB already exists
D/Weather_cast( 2780): 2 : set auto-update time : 3/1 18:33
I/[LGHome]EVENT( 1909): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
D/BluetoothInputDevice( 3712): Proxy object disconnected
D/HidProfile( 3712): Bluetooth service disconnected
,I/art     ( 1818): CheckpointMarkThreadRoots callback created = 0xaaf02bc0
,D/BluetoothPan( 3712): BluetoothPAN Proxy object disconnected
D/PanProfile( 3712): Bluetooth service disconnected
I/PhoneWindow( 1909): [setNavigationBarColor] color=0x 0
D/BluetoothMapService( 2091): Received stop request...Stopping profile...
D/BluetoothMapService( 2091): stop()
D/BluetoothMapEmailAppObserver( 2091): deinitObservers()
D/BluetoothMapEmailAppObserver( 2091): removeReceiver()
W/InputMethodManagerService(  855): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
D/BluetoothAdapterService( 2091): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d5e5162
I/LockScreenSettings( 4057): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
D/SapService( 2091): Received stop request...Stopping profile...
D/SapService( 2091): Stopping Bluetooth SapService
D/LGBluetoothSapAdapter( 2091): [BTUI] LGBluetoothSapAdapter cleanup
D/LGBluetoothSapManager( 2091): [BTUI] terminateSapManager
W/InputMethodManagerService(  855): Got RemoteException sending setActive(false) notification to pid 3247 uid 10317
D/LgeBluetoothSimManager( 1783): [BTUI] SAP_DISABLE_EVT
D/BluetoothAdapterService( 2091): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d5e5162
D/BluetoothAdapterService(1029591394)( 2091): handleMessage() - Message: 1
D/BluetoothAdapterService(1029591394)( 2091): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1029591394)( 2091): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BluetoothAdapterState( 2091): isTurningOnRadio()=false
D/BluetoothAdapterState( 2091): isTurningOffRadio()=false
D/BluetoothAdapterState( 2091): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2091): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2091): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2091): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2091): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(1029591394)( 2091): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
I/Process ( 3944): Sending signal. PID: 3944 SIG: 9
I/BluetoothA2dpServiceJni( 2091): cleanupNative
I/GKI_LINUX( 2091): GKI_destroy_task(2): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 2091): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 2091): GKI_destroy_task(): task [A2DP-MEDIA] terminated
D/**BluetoothFTPService( 2091): Received stop request...Stopping profile...
D/**BluetoothFTPService( 2091): Stopping Bluetooth FTP Service
V/BluetoothFTPServiceJni( 2091): closeFtpServerNative
D/BluetoothMap( 3712): Proxy object disconnected
D/MapProfile( 3712): Bluetooth service disconnected
D/BluetoothAdapterService( 2091): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d5e5162
,D/WeatherAncestor( 2780): 2 : onReceive has processed, action: android.intent.action.BOOT_COMPLETED, Time(hour:min:sec) 15:33:22
D/WeatherService( 2780): 2 : onStartCommand, intent!=null, action: android.intent.action.BOOT_COMPLETED
D/**OppService( 2091): Received stop request...Stopping profile...
D/OppService( 2091): Stopping Bluetooth OppService
D/OppService( 2091): cleanup OPP Service
W/BluetoothOPPServiceJni( 2091): Cleaning up Bluetooth Opp Interface...
W/BluetoothOPPServiceJni( 2091): Cleaning up Bluetooth OPP callback object
D/OppService( 2091): remove callbacks and handler
D/LGBluetoothOppAdapter( 2091): [BTUI] LGBluetoothOppAdapter cleanup
D/OppService( 2091): cleanup done
D/BluetoothAdapterService( 2091): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d5e5162
I/LockScreenSettings( 4057): Received Broadcast : android.intent.action.BOOT_COMPLETED
,D/BluetoothAdapterService(1029591394)( 2091): handleMessage() - Message: 1
D/BluetoothAdapterService(1029591394)( 2091): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1029591394)( 2091): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BluetoothAdapterState( 2091): isTurningOnRadio()=false
D/BluetoothAdapterState( 2091): isTurningOffRadio()=false
D/BluetoothAdapterState( 2091): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2091): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2091): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2091): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2091): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(1029591394)( 2091): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothHidServiceJni( 2091): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 2091): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService(1029591394)( 2091): handleMessage() - Message: 1
D/BluetoothAdapterService(1029591394)( 2091): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1029591394)( 2091): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BluetoothAdapterState( 2091): isTurningOnRadio()=false
D/BluetoothAdapterState( 2091): isTurningOffRadio()=false
D/BluetoothAdapterState( 2091): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2091): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2091): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2091): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2091): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(1029591394)( 2091): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothHealthServiceJni( 2091): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2091): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 2091): Cleaning up Bluetooth Health object
D/BluetoothAdapterService(1029591394)( 2091): handleMessage() - Message: 1
D/BluetoothAdapterService(1029591394)( 2091): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1029591394)( 2091): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BluetoothAdapterState( 2091): isTurningOnRadio()=false
D/BluetoothAdapterState( 2091): isTurningOffRadio()=false
D/BluetoothAdapterState( 2091): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2091): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2091): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/KeyguardModel( 1372): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1372): createShortcutInfo...
D/BtSettings.ProfileConfig( 2091): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2091): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(1029591394)( 2091): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothPanServiceJni( 2091): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2091): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterService(1029591394)( 2091): handleMessage() - Message: ,1
D/BluetoothAdapterService(1029591394)( 2091): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1029591394)( 2091): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=true
D/BluetoothAdapterState( 2091): isTurningOnRadio()=false
D/BluetoothAdapterState( 2091): isTurningOffRadio()=false
D/BluetoothAdapterState( 2091): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2091): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2091): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2091): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2091): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(1029591394)( 2091): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
V/BluetoothMapService( 2091): Handler(): got msg=4
D/BluetoothMapService( 2091): MAP Service closeService in
D/LGBluetoothMapAdapter( 2091): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 2091): MAP Service closeService out
D/BluetoothAdapterService(1029591394)( 2091): handleMessage() - Message: 1
D/BluetoothAdapterService(1029591394)( 2091): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1029591394)( 2091): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BluetoothAdapterState( 2091): isTurningOnRadio()=false
D/BluetoothAdapterState( 2091): isTurningOffRadio()=false
D/BluetoothAdapterState( 2091): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2091): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2091): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2091): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2091): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(1029591394)( 2091): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothMapService( 2091): cleanup()
D/BluetoothMapService( 2091): MAP Service closeService in
D/LGBluetoothMapAdapter( 2091): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 2091): MAP Service closeService out
D/BluetoothAdapterService(1029591394)( 2091): handleMessage() - Message: 1
D/BluetoothAdapterService(1029591394)( 2091): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1029591394)( 2091): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
D/BluetoothAdapterState( 2091): isTurningOnRadio()=false
D/BluetoothAdapterState( 2091): isTurningOffRadio()=false
D/BluetoothAdapterState( 2091): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2091): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2091): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2091): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2091): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(1029591394)( 2091): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothSAPServiceJni( 2091): ## WARNING : cleanupNative(L223): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 2091): ## WARNING : cleanupNative(L229): Cleaning up Bluetooth SAP callback object##
D/BluetoothAdapterService(1029591394)( 2091): handleMessage() - Message: 1
D/BluetoothAdapterService(1029591394)( 2091):, handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1029591394)( 2091): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, doUpdate=true
D/BluetoothAdapterState( 2091): isTurningOnRadio()=false
D/BluetoothAdapterState( 2091): isTurningOffRadio()=false
D/BluetoothAdapterState( 2091): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2091): isQuietModeServiceTurningOff()=false
D/KeyguardModel( 1372): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/BluetoothAdapterService( 2091): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/KeyguardModel( 1372): createShortcutInfo...
D/BtSettings.ProfileConfig( 2091): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2091): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(1029591394)( 2091): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothFTPService( 2091): cleanup FTP Service
V/BluetoothFTPServiceJni( 2091): closeFtpServerNative
V/BluetoothFTPServiceJni( 2091): cleanupNative
W/BluetoothFTPServiceJni( 2091): Cleaning up Bluetooth FTP Server Interface...
W/BluetoothFTPServiceJni( 2091): Cleaning up Bluetooth FTP callback object
D/BluetoothFTPService( 2091): BluetoothFtpBinder.cleanup()
D/BluetoothFTPService( 2091): cleanup done
D/BluetoothAdapterService(1029591394)( 2091): handleMessage() - Message: 1
D/BluetoothAdapterService(1029591394)( 2091): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1029591394)( 2091): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=10, doUpdate=true
D/BluetoothAdapterState( 2091): isTurningOnRadio()=false
D/BluetoothAdapterState( 2091): isTurningOffRadio()=false
D/BluetoothAdapterState( 2091): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2091): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2091): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BluetoothAdapterService(1029591394)( 2091): onProfileServiceStateChange() - All profile services stopped...
D/OppService( 2091): cleanup OPP Service
D/OppService( 2091): remove callbacks and handler
D/LGBluetoothOppAdapter( 2091): [BTUI] LGBluetoothOppAdapter cleanup
D/OppService( 2091): cleanup done
D/BluetoothAdapterState( 2091): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2091): Setting state to 10
I/BluetoothAdapterState( 2091): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService(1029591394)( 2091): updateAdapterState() - Broadcasting state to 1 receivers.
D/BluetoothManagerService(  855): Message: 60
D/BluetoothManagerService(  855): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  855): Broadcasting onBluetoothStateChange(false) to 9 receivers.
D/BluetoothA2dp(  855): onBluetoothStateChange: up=false
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
I/BluetoothAdapterState( 2091): Entering OffState
W/PackageManager( 1372): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/art     ( 1818): CheckpointMarkThreadRoots callback created = 0xb042da70
I/ActivityManager(  855): Waited long enough for: ServiceRecord{1a2c028e u0 com.lge.sizechangable.musicwidget.widget/.service.MusicWidgetUpdater}
D/KeyguardModel( 1372): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1372): createShortcutInfo...
I/HotwordRecognitionRnr( 1969): Starting hotword detection.
I/MicrophoneInputStream( 1969): mic_starting com.google.android.apps.gsa.speech.audio.u@32393b97
,V/AudioRecord( 1969): set(): inputSource 1999, sampleRate 16000, format 0x1, channelMask 0x10, frameCount 128000, notificationFrames 0, sessionId 0, transferType 0, flags 0
V/AudioRecord( 1969): set(): mSessionId 23
V/AudioPolicyManager(  280): getInput() inputSource 1999, samplingRate 16000, format 1, channelMask 10, session 23, flags 0
V/AudioPolicyManager(  280): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  280): isPlaybackThread 0,isRecordThread 1
D/audio_hw_primary(  280): adev_open_input_stream: enter: sample_rate(16000) channel_mask(0x10) devices(0x80000004)        stream_handle(0xb546e1a0)
V/audio_hw_primary(  280): adev_open_input_stream: exit
V/AudioFlinger(  280): openInput_l() openInputStream returned input 0xb546e1a0, SamplingRate 16000, Format 0x1, Channels 10, flags 0, status 0
V/AudioFlinger(  280): openInput_l() created record thread: ID 24 thread 0xb3a4d000
V/AudioSystem(  280): ioConfigChanged() event 3, ioHandle 24
I/AudioFlinger(  280): AudioFlinger's thread 0xb3a4d000 ready to run
D/audio_hw_primary(  280): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  280): in_standby: exit:  status(0)
V/AudioSystem(  855): ioConfigChanged() event 3, ioHandle 24
V/AudioSystem( 1372): ioConfigChanged() event 3, ioHandle 24
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
V/AudioSystem( 1783): ioConfigChanged() event 3, ioHandle 24
V/AudioSystem( 1969): ioConfigChanged() event 3, ioHandle 24
V/AudioPolicyService(  280): AudioCommandThread() adding update audio port list
V/AudioSystem( 3660): ioConfigChanged() event 3, ioHandle 24
V/AudioPolicyService(  280): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
D/audio_hw_primary(  280): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  280): in_standby: exit:  status(0)
V/AudioSystem( 2091): ioConfigChanged() event 3, ioHandle 24
V/AudioFlinger(  280): RecordThread: loop stopping
V/AudioSystem( 2786): ioConfigChanged() event 3, ioHandle 24
I/[LGHome]Launcher.Model( 1909): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
I/ActivityManager(  855): Process com.lge.defaultaccount (pid 3944) has died
I/SystemUI[Framework](  855): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
V/AudioFlinger(  280): openRecord() lSessionId: 23 input 24
V/AudioFlinger(  280): getOrphanEffectChain_l session 23 index -2
D/KeyguardModel( 1372): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1372): createShortcutInfo...
V/AudioFlinger(  280): acquiring 23 from 1969, for -1
V/AudioFlinger(  280):  added new entry for 23
V/AudioRecord( 1969): start, sync event 0 trigger session 0
W/PhoneWindowManagerEx(  855): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  855): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  855): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  855): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2c57ac8e,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  855): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,I/[LGHome]EVENT( 1909): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
V/AudioRecord( 1969): mAudioRecord->start()
V/AudioFlinger(  280): RecordHandle::start()
V/AudioFlinger(  280): RecordThread::start event 0, triggerSession 0
V/AudioPolicyManager(  280): startInput() module primary->input primary(24)
V/AudioPolicyManager(  280): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  280): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  280): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  280): DeviceVector::getDevicesFromType() for type 80000004 found 0xb547b280
V/AudioPolicyService(  280): AudioCommandThread() adding create patch delay 0
V/AudioPolicyService(  280): inserting command: 7 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing create audio patch
V/AudioFlinger::PatchPanel(  280): createAudioPatch() num_sources 1 num_sinks 1 handle 0
V/AudioFlinger::PatchPanel(  280): createAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters input_source=6;routing=-2147483644
V/AudioFlinger(  280): ThreadBase::setParameters() input_source=6;routing=-2147483644
V/AudioFlinger(  280): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  280): RecordThread: loop starting
V/AudioFlinger(  280): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  280): in_set_parameters: enter: kvpairs=input_source=6;routing=-2147483644
V/audio_hw_primary(  280): in_set_parameters: exit: status(0)
V/AudioFlinger(  280): processConfigEvents_l() DONE thread 0xb3a4d000
V/AudioFlinger::PatchPanel(  280): createAudioPatch() status 0
V/AudioFlinger::PatchPanel(  280): createAudioPatch() added new patch handle 25 halHandle 0
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioPolicyManager(  280): setInputDevice() createAudioPatch returned 0 patchHandle 25
V/AudioPolicyManager(  280): addAudioPatch() handle 20 af handle 0 num_sources 1 num_sinks 1 source handle 10sink handle 19
V/AudioPolicyService(  280): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  280): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioPolicyService(  280): AudioCommandThread() adding set parameter string hotword_active=1, io 24 ,delay 0
V/AudioPolicyService(  280): inserting command: 3 at index 0, num commands 0
I/[LGHome]EVENT( 1909): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing set parameters string hotword_active=1, io 24
V/AudioFlinger(  280): setParameters(): io 24, keyvalue hotword_active=1, calling pid 280
V/AudioFlinger(  280): ThreadBase::setParameters() hotword_active=1
V/AudioFlinger(  280): sendConfigEvent_l() num events 1 event 2
D/KeyguardModel( 1372): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1372): createShortcutInfo...
W/ActivityManager(  855): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/BluetoothPan( 3712): onBluetoothStateChange on: false
I/HotwordDetector( 1969): Closing mic
D/Weather.Utils( 2780): 2 : Utils getTopActivity com.lge.launcher2 / true
I/[LGHome]EVENT( 1909): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
D/WeatherService( 2780): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2780): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/[LGHome]EVENT( 1909): [Workspace,.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
V/AudioFlinger(  280): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  280): in_set_parameters: enter: kvpairs=hotword_active=1
V/audio_hw_primary(  280): in_set_parameters: exit: status(0)
V/AudioFlinger(  280): processConfigEvents_l() DONE thread 0xb3a4d000
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioPolicyManager(  280): AudioPolicyManager::startInput() input source = 1999
I/NotificationService(  855): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  855): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
V/msm8974_platform(  280): platform_update_usecase_from_source: input source :6
,D/audio_hw_primary(  280): start_input_stream: enter: stream(0xb546e1a0)usecase(7: audio-record)
V/voice   (  280): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  280): start_input_stream: usecase(7)
E/audio_hw_primary(  280): select_devices: enter and usecase(7)
V/msm8974_platform(  280): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  280): platform_get_input_snd_device: exit: in_snd_device(voice-rec-mic)
V/msm8974_platform_lge(  280): LGE_platform_get_input_snd_device: exit: in_snd_device(lg-vr-handset-mic)
V/audio_hw_lge_primary(  280): LGE_exeption_scenario: enter and out: 0, in: 144
D/audio_hw_primary(  280): select_devices: out_snd_device(0: ) in_snd_device(144: lg-vr-handset-mic)
E/audio_hw_primary(  280): enable_snd_device: enter  144
D/hardware_info(  280): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  280): enable_snd_device: snd_device(144: lg-vr-handset-mic)
V/msm8974_platform_lge(  280): LGE_platform_send_audio_calibration: sending audio calibration for snd_Device(144) acdb_id(65)
D/ACDB-LOADER(  280): ACDB -> send_audio_cal, acdb_id = 65, path =  1
D/ACDB-LOADER(  280): ACDB -> send_adm_topology
D/ACDB-LOADER(  280): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/ACDB-LOADER(  280): ACDB -> send_asm_topology
D/ACDB-LOADER(  280): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  280): ACDB -> send_audtable
D/ACDB-LOADER(  280): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/ACDB-LOADER(  280): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  280): ACDB -> send_audvoltable
D/ACDB-LOADER(  280): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  280): Failed to fetch the lookup information of the device 00000041 
E/ACDB-LOADER(  280): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  280): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  280): ACDB -> AUDIO_SET_AFE_CAL
W/art     (  855): Suspending all threads took: 6.337ms
V/audio_hw_primary(  280): enable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  280): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  280): enable_audio_route: apply mixer and update path: audio-record
V/audio_hw_primary(  280): enable_audio_route: exit
D/audio_hw_primary(  280): select_devices: done
V/audio_hw_primary(  280): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
V/audio_hw_primary(  280): start_input_stream: exit
I/[LGHome]Launcher.Model( 1909): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/ActivityManager(  855): Start proc com.lge.springcleaning for broadcast com.lge.springcleaning/.receiver.BootCompleteReceiver: pid=4084 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/KeyguardModel( 1372): handleShortcutListChanged...
,D/JobSchedulerService(  855): Receieved: android.intent.action.PACKAGE_REMOVED
D/BluetoothHeadset(  855): Proxy object disconnected
D/AudioService(  855): onServiceDisconnected: Bluetooth profile: 1
D/TaskPersister(  855): removeObsoleteFile: deleting file=224_task.xml
,I/art     (  305): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 22.829ms
I/[LGHome]EVENT( 1909): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,I/MicrophoneInputStream( 1969): mic_started com.google.android.apps.gsa.speech.audio.u@32393b97
I/MicrophoneInputStream( 1969): mic_close com.google.android.apps.gsa.speech.audio.u@32393b97
V/AudioRecord( 1969): stop()
D/AudioRecord( 1969): AudioRecord->stop()
V/AudioFlinger(  280): RecordHandle::stop()
V/AudioFlinger(  280): RecordThread::stop
D/BluetoothHeadset( 1783): onBluetoothStateChange: up=false
D/PhoneStatusBar( 1372): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
I/[SystemUI]NavigationThemeResource( 1372): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1372):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1372): , Keyguard show=false, IME shown=false, Panel expanded=false
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 22.139ms
D/BluetoothHeadset( 1783): onBluetoothStateChange: up=false
D/BarTransitions( 1372): draw background and invalidate : color = f7000000
D/BluetoothHeadset(  855): onBluetoothStateChange: up=false
,I/[LGHome]Launcher.Model( 1909): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
D/KeyguardModel( 1372): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1372): createShortcutInfo...
D/BarTransitions( 1372): draw background and invalidate : color = f0e7e7e7
D/KeyguardModel( 1372): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
,W/PackageManager( 1372): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/BluetoothInputDevice( 3712): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1783): onBluetoothStateChange: up=false
D/BluetoothMap( 3712): onBluetoothStateChange: up=false
D/BluetoothPbap( 3712): onBluetoothStateChange: up=false
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 330us total 22.067ms
D/BluetoothAdapterService(1029591394)( 2091): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3eee00c8
D/BluetoothManagerService(  855): Calling onBluetoothServiceDown callbacks
D/KeyguardModel( 1372): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1372): createShortcutInfo...
D/BluetoothManagerService(  855): Broadcasting onBluetoothServiceDown() to 8 receivers.
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1909): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,D/KeyguardModel( 1372): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1372): createShortcutInfo...
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1909): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1372): package = com.lge.camera, class = com.lge.camera.CameraApp
,D/KeyguardModel( 1372): createShortcutInfo...
D/BluetoothManagerService(  855): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService(  855): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService(  855): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@11ac20f6 mBinding = false
V/AudioFlinger(  280): Record stopped OK
V/AudioPolicyManager(  280): stopInput() input 24
V/AudioPolicyService(  280): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  280): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  280): releaseAudioPatch handle 25
V/AudioFlinger::PatchPanel(  280): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  280): ThreadBase::setParameters() routing=0
V/AudioFlinger(  280): sendConfigEvent_l() num events 1 event 2
D/BluetoothManagerService(  855): Sending unbind request.
D/BluetoothAdapterService(1029591394)( 2091): onUnbind() - calling cleanup
D/BluetoothManagerService(  855): Bluetooth State Change Intent: 13 -> 10
D/BluetoothAdapterService(1029591394)( 2091): cleanup()
V/AudioFlinger(  280): processConfigEvents_l() remaining events 1
V/AudioFlinger(  280): processConfigEvents_l() DONE thread 0xb3a4d000
D/audio_hw_primary(  280): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
,D/LGBluetoothAPIService( 1836): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1836): Message: 2
D/LGBluetoothFeatureConfig( 3712): isPrivacyLogsEnabled : true
E/LGBluetoothEventManager( 3712): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 3712): [BTUI] clear device connection state
W/Resources( 1909): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
D/BluetoothAdapterService(1029591394)( 2091): cleanup() - Cleaning up adapter native
I/bt-btif ( 2091): btif_shutdown_bluetooth()::btif_core_cb: state: 0, is_radio_req: 0, radio_ref_count: 0, dut_mode: 0, shutdown_pending: 0
I/GKI_LINUX( 2091): GKI_destroy_task(1): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/bt-btif ( 2091): HAL bt_hal_cbacks->thread_evt_cb
I/GKI_LINUX( 2091): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 2091): GKI_destroy_task(): task [BTIF] terminated
I/GKI_LINUX( 2091): GKI_destroy_task(2): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 2091): GKI_destroy_task(1): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 2091): GKI_destroy_task(0): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 2091): GKI_exit_task 2 done
I/GKI_LINUX( 2091): GKI_exit_task 1 done
I/GKI_LINUX( 2091): GKI_exit_task 0 done
I/BluetoothServiceJni( 2091): cleanupNative: return from cleanup
W/LGBluetoothServiceJni( 2091): Cleaning up Bluetooth Service callback object
,D/LGBluetoothAPIService( 1836): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@3265ae79 mBinding = false
I/art     (  855): Explicit concurrent mark sweep GC freed 36109(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 23MB/34MB, paused 18.465ms total 480.569ms
D/LGBluetoothSettingsDBObserver( 2091): [BTUI] unregister observer for LG device name DB
D/LGBluetoothAPIService( 1836): Sending unbind request.
D/BluetoothAdapterService(1029591394)( 2091): cleanup() - Bluetooth process exited normally.
D/BluetoothAdapterService(1029591394)( 2091): cleanup() done
W/ContextImpl( 3712): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/KeyguardModel( 1372): handleShortcutListChanged...
D/BluetoothAdapter( 1372): 555751990: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1372): 555751990: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1765): 972991935: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1765): 972991935: getState() :  mService = null. Returning STATE_OFF
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1372): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
I/art     ( 2091): System.exit called, status: 0
I/AndroidRuntime( 2091): VM exiting with result code 0, cleanup skipped.
W/Resources( 1909): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1909): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1909): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
V/audio_hw_primary(  280): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  280): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  280): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  280): disable_audio_route: reset and update mixer path: audio-record
,V/audio_hw_primary(  280): disable_audio_route: exit
E/audio_hw_primary(  280): disable_snd_device: enter 144
D/hardware_info(  280): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  280): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  280): stop_input_stream: exit: status(0)
V/audio_hw_primary(  280): in_standby: exit:  status(0)
V/AudioFlinger(  280): RecordThread: loop stopping
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioPolicyManager(  280): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  280): removeAudioPatch() handle 20 af handle 25
V/AudioPolicyService(  280): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  280): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioPolicyService(  280): AudioCommandThread() adding set parameter string hotword_active=0, io 24 ,delay 0
V/AudioPolicyService(  280): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing set parameters string hotword_active=0, io 24
V/AudioFlinger(  280): setParameters(): io 24, keyvalue hotword_active=0, calling pid 280
V/AudioFlinger(  280): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  280): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  280): RecordThread: loop starting
V/AudioFlinger(  280): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  280): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  280): in_set_parameters: exit: status(0)
V/AudioFlinger(  280): processConfigEvents_l() DONE thread 0xb3a4d000
V/AudioFlinger(  280): RecordThread: loop stopping
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioRecord( 1969): stop()
V/AudioRecord( 1969): stop()
V/AudioRecord( 1969): stop()
V/AudioFlinger(  280): releasing 23 from 1969 for -1
V/AudioFlinger(  280):  decremented refcount to 0
V/AudioFlinger(  280): purging stale effects
V/AudioFlinger(  280): RecordHandle::stop()
V/AudioFlinger(  280): RecordThread::stop
V/AudioPolicyManager(  280): releaseInput() 24
V/AudioPolicyManager(  280): closeInput(24)
V/AudioFlinger(  280): closeInput() 24
V/AudioSystem(  280): ioConfigChanged() event 4, ioHandle 24
V/AudioSystem( 1783): ioConfigChanged() event 4, ioHandle 24
V/AudioFlinger(  280): ThreadBase::exit
V/AudioFlinger(  280): RecordThread: loop starting
V/AudioSystem(  855): ioConfigChanged() event 4, ioHandle 24
V/AudioFlinger(  280): RecordThread 0xb3a4d000 exiting
D/audio_hw_primary(  280): adev_close_input_stream: enter:stream_handle(0xb546e1a0)
D/audio_hw_primary(  280): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  280): in_standby: exit:  status(0)
V/AudioPolicyService(  280): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  280): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  280): releaseInput() exit
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioFlinger(  280): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioPolicyService(  280): AudioCommandThread() processing update audio port list
V/AudioFlinger(  280): removeClient_l() pid 1969, calling pid 280
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioSystem( 1969): ioConfigChanged() event 4, ioHandle 24
V/AudioSystem( 1372): ioConfigChanged() event 4, ioHandle 24
V/AudioSystem( 3660): ioConfigChanged() event 4, ioHandle 24
V/AudioSystem( 2786): ioConfigChanged() event 4, ioHandle 24
I/HotwordRecognitionRnr( 1969): Hotword detection finished
I/HotwordRecognitionRnr( 1969): Stopping hotword detection.
D/DockEventReceiver( 3712): finishSt,artingService: stopping service
W/Resources( 1909): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
V/AudioFlinger(  280): 2091 died, releasing its sessions
V/AudioFlinger(  280):  pid 1783 @ 0
V/AudioFlinger(  280):  pid 2786 @ 1
V/AudioFlinger(  280):  pid 3660 @ 2
V/AudioFlinger(  280):  pid 3660 @ 3
D/FMFRW_FmProxy( 1836): Fm Proxy object disconnected
W/Resources( 1909): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
,W/Resources( 1909): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
D/LGBluetoothUserBindClient( 3712): [BTUI] onServiceDisconnected
W/Resources( 1909): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1909): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1909): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1909): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
,W/Resources( 1909): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
,D/AndroidRuntime( 3958): Shutting down VM
,I/ActivityManager(  855): Process com.android.bluetooth (pid 2091) has died
W/ActivityManager(  855): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
W/ActivityManager(  855): Scheduling restart of crashed service com.android.bluetooth/com.broadcom.fm.fmreceiver.FmService in 11000ms
,I/Timeline(  855): Timeline: Activity_windows_visible id: ActivityRecord{3cc3b8fb u0 com.lge.launcher2/.Launcher t223} time:53981
D/BluetoothPermissionRequest( 3712): onReceive
,D/LGBluetoothUtils( 3712): [BTUI] FileNotFound: readProperty
D/BluetoothDiscoverableTimeoutReceiver( 3712): cancelDiscoverableAlarm(): Enter
D/BootCompleteReceiver( 4084): hasclipTray = true
,W/ContextImpl( 4084): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.springcleaning.receiver.BootCompleteReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2663 
I/ActivityManager(  855): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=4104 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 1035, 4002, 1023} abi=armeabi-v7a
,W/ResourcesManager(  855): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1909): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,W/ResourceType(  855): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1909): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1909): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1909): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/ActivityManager(  855): Start proc com.lge.springcleaning:AppCleanupService for service com.lge.springcleaning/.service.AppCleanupService: pid=4121 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/[LGHome]EVENT( 1909): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
,W/ResourcesManager( 4104): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 4104): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4104): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/ResourcesManager( 4104): Asset path '/system/framework/com.broadcom.fm.jar' does not exist or contains no resources.
I/ActivityManager(  855): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4140 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  855): Killing 3838:com.lge.drmservice/u0a51 (adj 15): empty #11
I/[LGHome]EVENT( 1909): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/[LGHome]EVENT( 1909): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1909): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1909): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1909): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1909): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
W/ActivityManager(  855): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
V/AlarmManager(  855): RTC_WAKEUP set : Alarm{3ae4e20 type 0 when 1456756390621 com.android.providers.contacts} when 1456756390621
D/BluetoothAdapterApp( 4104): Loading JNI Library
W/libprocessgroup(  855): failed to open /acct/uid_10051/pid_3838/cgroup.procs: No such file or directory
D/LCardEmulationManager( 1818): getHceAppCount hostAppNum : 0
,D/LCardEmulationManager( 1818): getDefaultRoute
I/HotwordRecognitionRnr( 1969): Starting hotword detection.
,I/MicrophoneInputStream( 1969): mic_starting com.google.android.apps.gsa.speech.audio.u@2e0cd25
V/AudioRecord( 1969): set(): inputSource 1999, sampleRate 16000, format 0x1, channelMask 0x10, frameCount 128000, notificationFrames 0, sessionId 0, transferType 0, flags 0
V/AudioRecord( 1969): set(): mSessionId 26
V/AudioPolicyManager(  280): getInput() inputSource 1999, samplingRate 16000, format 1, channelMask 10, session 26, flags 0
V/AudioPolicyManager(  280): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  280): isPlaybackThread 0,isRecordThread 1
D/audio_hw_primary(  280): adev_open_input_stream: enter: sample_rate(16000) channel_mask(0x10) devices(0x80000004)        stream_handle(0xb546e240)
V/audio_hw_primary(  280): adev_open_input_stream: exit
V/AudioFlinger(  280): openInput_l() openInputStream returned input 0xb546e240, SamplingRate 16000, Format 0x1, Channels 10, flags 0, status 0
V/AudioFlinger(  280): openInput_l() created record thread: ID 27 thread 0xb3a4d000
V/AudioSystem(  280): ioConfigChanged() event 3, ioHandle 27
V/AudioPolicyService(  280): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  280): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing update audio port list
I/AudioFlinger(  280): AudioFlinger's thread 0xb3a4d000 ready to run
D/audio_hw_primary(  280): in_standby: enter: stream (0xb546e240) usecase(7: audio-record)
V/audio_hw_primary(  280): in_standby: exit:  status(0)
E/BluetoothServiceJni( 4104): [BTUI] JNI_OnLoad : ### LGBT_USE_BDT : TRUE ###
,V/AudioSystem( 1969): ioConfigChanged() event 3, ioHandle 27
V/AudioSystem(  855): ioConfigChanged() event 3, ioHandle 27
D/BluetoothAdapterApp( 4104): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@22fd0f75 Instance Count = 1
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioSystem( 1372): ioConfigChanged() event 3, ioHandle 27
V/AudioSystem( 1783): ioConfigChanged() event 3, ioHandle 27
V/AudioSystem( 3660): ioConfigChanged() event 3, ioHandle 27
D/audio_hw_primary(  280): in_standby: enter: stream (0xb546e240) usecase(7: audio-record)
V/audio_hw_primary(  280): in_standby: exit:  status(0)
V/AudioFlinger(  280): RecordThread: loop stopping
V/AudioFlinger(  280): openRecord() lSessionId: 26 input 27
,V/AudioFlinger(  280): getOrphanEffectChain_l session 26 index -2
V/AudioSystem( 2786): ioConfigChanged() event 3, ioHandle 27
V/AudioFlinger(  280): acquiring 26 from 1969, for -1
V/AudioFlinger(  280):  added new entry for 26
V/AudioRecord( 1969): start, sync event 0 trigger session 0
V/AudioRecord( 1969): mAudioRecord->start()
V/AudioFlinger(  280): RecordHandle::start()
D/BluetoothAdapterApp( 4104): onCreate
V/AudioFlinger(  280): RecordThread::start event 0, triggerSession 0
V/AudioPolicyManager(  280): startInput() module primary->input primary(27)
V/AudioPolicyManager(  280): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  280): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  280): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  280): DeviceVector::getDevicesFromType() for type 80000004 found 0xb547b280
V/AudioPolicyService(  280): AudioCommandThread() adding create patch delay 0
V/AudioPolicyService(  280): inserting command: 7 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing create audio patch
V/AudioFlinger::PatchPanel(  280): createAudioPatch() num_sources 1 num_sinks 1 handle 0
V/AudioFlinger::PatchPanel(  280): createAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters input_source=6;routing=-2147483644
V/AudioFlinger(  280): ThreadBase::setParameters() input_source=6;routing=-2147483644
V/AudioFlinger(  280): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  280): RecordThread: loop starting
V/AppCleanupService( 4121): registerAlarm
V/AudioFlinger(  280): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  280): in_set_parameters: enter: kvpairs=input_source=6;routing=-2147483644
V/audio_hw_primary(  280): in_set_parameters: exit: status(0)
V/AudioFlinger(  280): processConfigEvents_l() DONE thread 0xb3a4d000
V/AudioFlinger::PatchPanel(  280): createAudioPatch() status 0
V/AudioFlinger::PatchPanel(  280): createAudioPatch() added new patch handle 28 halHandle 0
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioPolicyManager(  280): setInputDevice() createAudioPatch returned 0 patchHandle 28
V/AudioPolicyManager(  280): addAudioPatch() handle 22 af handle 0 num_sources 1 num_sinks 1 source handle 10sink handle 21
V/AudioPolicyService(  280): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  280): inserting command: 10 at index 0, num commands 0
,V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
,V/AudioPolicyService(  280): AudioCommandThread() adding set parameter string hotword_active=1, io 27 ,delay 0
V/AudioPolicyService(  280): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing set parameters string hotword_active=1, io 27
V/AudioFlinger(  280): setParameters(): io 27, keyvalue hotword_active=1, calling pid 280
V/AudioFlinger(  280): ThreadBase::setParameters() hotword_active=1
V/AudioFlinger(  280): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  280): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  280): in_set_parameters: enter: kvpairs=hotword_active=1
V/audio_hw_primary(  280): in_set_parameters: exit: status(0)
V/AudioFlinger(  280): processConfigEvents_l() DONE thread 0xb3a4d000
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioPolicyManager(  280): AudioPolicyManager::startInput() input source = 1999
I/MicrophoneInputStream( 1969): mic_started com.google.android.apps.gsa.speech.audio.u@2e0cd25
,V/msm8974_platform(  280): platform_update_usecase_from_source: input source :6
D/audio_hw_primary(  280): start_input_stream: enter: stream(0xb546e240)usecase(7: audio-record)
V/voice   (  280): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  280): start_input_stream: usecase(7)
E/audio_hw_primary(  280): select_devices: enter and usecase(7)
V/msm8974_platform(  280): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  280): platform_get_input_snd_device: exit: in_snd_device(voice-rec-mic)
V/msm8974_platform_lge(  280): LGE_platform_get_input_snd_device: exit: in_snd_device(lg-vr-handset-mic)
V/audio_hw_lge_primary(  280): LGE_exeption_scenario: enter and out: 0, in: 144
D/audio_hw_primary(  280): select_devices: out_snd_device(0: ) in_snd_device(144: lg-vr-handset-mic)
E/audio_hw_primary(  280): enable_snd_device: enter  144
D/hardware_info(  280): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  280): enable_snd_device: snd_device(144: lg-vr-handset-mic)
V/msm8974_platform_lge(  280): LGE_platform_send_audio_calibration: sending audio calibration for snd_Device(144) acdb_id(65)
D/ACDB-LOADER(  280): ACDB -> send_audio_cal, acdb_id = 65, path =  1
D/ACDB-LOADER(  280): ACDB -> send_adm_topology
D/ACDB-LOADER(  280): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/ACDB-LOADER(  280): ACDB -> send_asm_topology
D/ACDB-LOADER(  280): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  280): ACDB -> send_audtable
D/ACDB-LOADER(  280): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/ACDB-LOADER(  280): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  280): ACDB -> send_audvoltable
D/ACDB-LOADER(  280): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  280): Failed to fetch the lookup information of the device 00000041 
E/ACDB-LOADER(  280): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  280): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  280): ACDB -> AUDIO_SET_AFE_CAL
D/AppCleanupService( 4121): noticeInterval = 2674800000
D/AppCleanupService( 4121): notiDateStr = 2016-03-20 22:44:47
V/audio_hw_primary(  280): enable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  280): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  280): enable_audio_route: apply mixer and update path: audio-record
V/audio_hw_primary(  280): enable_audio_route: exit
D/audio_hw_primary(  280): select_devices: done
V/audio_hw_primary(  280): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
,I/LGBluetoothServiceJni( 4104): classInitNative: succeeds
V/audio_hw_primary(  280): start_input_stream: exit
D/BtSettings.ProfileConfig( 4104): [BTUI] HeadsetServiceis supported
D/AppCleanupService( 4121): noticeStart = 2016-03-20 22:44:47
D/BtSettings.ProfileConfig( 4104): Adding HeadsetService
D/AppCleanupService( 4121): noticeStart = 1458510287000
D/BtSettings.ProfileConfig( 4104): [BTUI] A2dpServiceis supported
D/BtSettings.ProfileConfig( 4104): Adding A2dpService
,D/BtSettings.ProfileConfig( 4104): [BTUI] HidServiceis supported
D/BtSettings.ProfileConfig( 4104): Adding HidService
D/BtSettings.ProfileConfig( 4104): [BTUI] HealthServiceis supported
D/BtSettings.ProfileConfig( 4104): Adding HealthService
D/LGBluetoothFeatureConfig( 4104): isSupportPan() :  mTargetOp=OPEN
D/sensors_hal_Time(  855): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  855): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  855): tsOffsetIs: Apps: 54433941338; DSPS: 1875204; Offset : -2808353022
E/SQLiteDatabase( 4121): Failed to open database '/data/data/com.lge.springcleaning/databases/idleapps.db'.
E/SQLiteDatabase( 4121): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4121): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4121): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/SQLiteDatabase( 4121): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/SQLiteDatabase( 4121): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/SQLiteDatabase( 4121): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/SQLiteDatabase( 4121): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 4121): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/SQLiteDatabase( 4121): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/SQLiteDatabase( 4121): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/SQLiteDatabase( 4121): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 4121): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 4121): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4121): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4121): 	at com.lge.springcleaning.db.AppUsageDbAdapter.open(AppUsageDbAdapter.java:88)
E/SQLiteDatabase( 4121): 	at com.lge.springcleaning.service.AppCleanupService.init(AppCleanupService.java:141)
E/SQLiteDatabase( 4121): 	at com.lge.springcleaning.service.AppCleanupService.onStartCommand(AppCleanupService.java:112)
E/SQLiteDatabase( 4121): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:2953)
E/SQLiteDatabase( 4121): 	at android.app.ActivityThread.access$2100(ActivityThread.java:155)
E/SQLiteDatabase( 4121): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
E/SQLiteDatabase( 4121): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4121): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4121): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/SQLiteDatabase( 4121): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 4121): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 4121): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/SQLiteDatabase( 4121): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/AndroidRuntime( 4121): Shutting down VM
--------- beginning of crash
E/AndroidRuntime( 4121): FATAL EXCEPTION: main
E/AndroidRuntime( 4121): Process: com.lge.springcleaning:AppCleanupService, PID: 4121
E/AndroidRuntime( 4121): java.lang.RuntimeException: Unable to start service com.lge.springcleaning.service.AppCleanupService@29f36b0a with Intent { cmp=com.lge.springcleaning/.service.AppCleanupService }: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4121): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:2970)
E/AndroidRuntime( 4121): 	at androi,d.app.ActivityThread.access$2100(ActivityThread.java:155)
E/AndroidRuntime( 4121): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
E/AndroidRuntime( 4121): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4121): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4121): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/AndroidRuntime( 4121): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4121): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4121): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/AndroidRuntime( 4121): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/AndroidRuntime( 4121): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4121): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4121): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/AndroidRuntime( 4121): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/AndroidRuntime( 4121): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/AndroidRuntime( 4121): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/AndroidRuntime( 4121): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 4121): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/AndroidRuntime( 4121): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/AndroidRuntime( 4121): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/AndroidRuntime( 4121): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/AndroidRuntime( 4121): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 4121): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4121): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4121): 	at com.lge.springcleaning.db.AppUsageDbAdapter.open(AppUsageDbAdapter.java:88)
E/AndroidRuntime( 4121): 	at com.lge.springcleaning.service.AppCleanupService.init(AppCleanupService.java:141)
E/AndroidRuntime( 4121): 	at com.lge.springcleaning.service.AppCleanupService.onStartCommand(AppCleanupService.java:112)
E/AndroidRuntime( 4121): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:2953)
E/AndroidRuntime( 4121): 	... 9 more
E/DropBoxManagerService(  855): Can't write: system_app_crash
E/DropBoxManagerService(  855): java.io.FileNotFoundException: /data/system/dropbox/drop119.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  855): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  855): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  855): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  855): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  855): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  855): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12621)
E/DropBoxManagerService(  855): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  855): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  855): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  855): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  855): 	... 5 more
I/[LgeWidgetLib]LgeAppWidgetHostView( 1909): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
I/PhoneWindow(  855): [generateLayout] setColorNavigationBar => color=0x ff000001
D/PhoneWindowEx(  855): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow(  855): [setNavigationBarColor2] color=0x fff5f5f5

```
