#### Test 5024228542a63d7_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/NotificationManager(  847): android: cancelAsUser(353845882) by android
--------- beginning of system
W/ContextImpl( 3630): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.mlt.MptOnBootReceiver.onReceive:107 android.app.ActivityThread.handleReceiver:2663 
E/bt-btif ( 2073): bta_dm_ctrl_features_rd_cmpl_cback Ctrl BLE feature read failed: status :1
I/GKI_LINUX( 2073): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 2073): warning : media task started media_task_refcnt 1 
E/bt-btif ( 2073): Calling BTA_HhEnable
E/bt-btif ( 2073): btif_storage_get_adapter_property service_mask:0x1201c8
I/bt-btif ( 2073): HAL bt_hal_cbacks->adapter_properties_cb
D/BT_PROF_AUDIO( 2073): created moving average (N=100)
D/BT_PROF_AUDIO( 2073): reset rate average
W/bt-btif ( 2073): overflow 0, enter 0, exit 0
D/BluetoothAdapterProperties( 2073): Address is:F8:95:C7:87:85:54
W/bt-smp  ( 2073): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 2073): Plain text(LSB ~ MSB) = 81 bd 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2073): Encrypted text(LSB ~ MSB) = 0a 90 42 ff 0c 37 67 0e 4c fd a9 ae 2e a2 1f bf 
W/bt-btm  ( 2073): Stopping oneshot timer
E/MPT MptOnPowerWatcher( 3630): MptOnPowerWatcher
,I/ActivityManager(  847): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=3679 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
D/BluetoothAdapterProperties( 2073): Name is: G3s-1
D/BluetoothManagerService(  847): Bluetooth Adapter name changed to G3s-1
E/dbFlushManager( 3630): Handler is not ready.
E/dbFlushManager( 3630): It's going to sleep routine until the message handler is generated.
D/BluetoothManagerService(  847): Stored Bluetooth name: G3s-1
D/BluetoothAdapterProperties( 2073): Scan Mode:20
D/BluetoothAdapterProperties( 2073): Discoverable Timeout:120
E/bt-btif ( 2073): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 2073): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
E/bt-btif ( 2073): btif_sock_init: !radio_req && !rfc_init
I/bt-btif ( 2073): BTA_JvEnable
E/bt-btif ( 2073): btsock_vendor_hci_init: !vhci_init
D/bt-btif ( 2073): btsock_ctrl_hci_init(L191): poll handle:6
D/bt-btif ( 2073): init_hci_slots(L136): in
D/IOP_DB_BT( 2073): db_open: file /etc/bluetooth/iop_bt.db
D/IOP_DB_BT( 2073): db_open: db_open : handle 2690635740l, read 11046 bytes onto local cache
D/IOP_DB_BT( 2073): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 2073): db_query: result 1
I/        ( 2073): iop_db_open: iop_db_open status 0
E/bt-btif ( 2073): btif_sock_init, radio_req:0, rfc_init:1, vhci_init:1
D/bt-btif ( 2073): btsock_ctrl_hci_init(L191): poll handle:6
I/bt-btif ( 2073): bta_pan_co_init
D/bte_conf( 2073): Device ID record 1 : primary
D/bte_conf( 2073):   vendorId            = 00c4
D/bte_conf( 2073):   vendorIdSource      = 0001
D/bte_conf( 2073):   product             = 13a1
D/bte_conf( 2073):   version             = 1000
D/bte_conf( 2073):   clientExecutableURL = 
D/bte_conf( 2073):   serviceDescription  = 
D/bte_conf( 2073):   documentationURL    = 
D/bte_conf( 2073): bte_load_did_conf no section named DID2.
I/bt-btif ( 2073): HAL bt_hal_cbacks->adapter_state_changed_cb
E/bt-btif ( 2073): btif_hf_upstreams_evt: wrong handle = 26465 
I/bt-btif ( 2073): HAL bt_op_callbacks->opc_state_cb
D/BluetoothOPPServiceJni( 2073): opc_state_cb(L140):  opc_state_cb state:0
D/OppService( 2073): onOpcStateChange()
I/bt-btif ( 2073): HAL bt_op_callbacks->ops_state_cb
D/BluetoothOPPServiceJni( 2073): ops_state_cb(L223):  ops_state_cb state:0
D/OppService( 2073): Recieved MESSAGE_OPC_ENABLE
D/BluetoothAdapterState( 2073): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/LGBluetoothFeatureConfig( 2073): isPrivacyLogsEnabled : true
D/BluetoothAdapterProperties( 2073): ScanMode =  20
D/BluetoothAdapterProperties( 2073): State =  11
D/BluetoothAdapterProperties( 2073): mDiscoverableTimeout = 120
D/OppService( 2073): onOpsStateChange() :0
I/bt-btif ( 2073): HAL bt_fts_callbacks->operation_cmpl_cb
D/BluetoothFTPServiceJni( 2073): operation_cmpl_callback(L192):  oper:3 status:0
I/BluetoothFTPService( 2073): onFtpServerEnabled: /storage
D/BluetoothAdapterProperties( 2073): Setting state to 12
I/BluetoothAdapterState( 2073): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService(327569342)( 2073): updateAdapterState() - Broadcasting state to 1 receivers.
D/BluetoothPanServiceJni( 2073): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
I/bt-btif ( 2073): HAL bt_hal_cbacks->adapter_properties_cb
D/OppService( 2073): Recieved MESSAGE_OPS_ENABLE
D/BluetoothManagerService(  847): Message: 60
D/BluetoothManagerService(  847): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothAdapterProperties( 2073): Scan Mode:21
I/BluetoothAdapterState( 2073): Entering On State
I/bt-btif ( 2073): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 2073): Discoverable Timeout:120
I/BluetoothAdapterState( 2073): Entering On State from state = 11
D/BluetoothManagerService(  847): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothAdapterService(327569342)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3fcae804
D/BluetoothAdapterService(327569342)( 2073): isQuetModeEnabled() - Enabled = false
D/BluetoothAdapterService(327569342)( 2073): autoConnect() - Initiate auto connection on BT on...
D/BluetoothAdapterService( 2073): [BTUI] autoConnect() : not allowed
D/BluetoothHeadset( 1785): onBluetoothStateChange: up=true
D/LGBluetoothServiceAdapter( 2073): [BTUI] OnState
D/LGBluetoothServiceAdapter( 2073): [BTUI]         global_name: G3s-1
D/BluetoothA2dp(  847): onBluetoothStateChange: up=true
D/LGBluetoothServiceAdapter( 2073): [BTUI]         local_name: G3s-1
D/BluetoothA2dp( 2073): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1785): onBluetoothStateChange: up=true
D/BluetoothAdapterService(327569342)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3fcae804
D/BluetoothHeadset(  847): onBluetoothStateChange: up=true
D/BluetoothAdapterService(327569342)( 2073): isQuetModeEnabled() - Enabled = false
D/BluetoothAdapterService(327569342)( 2073): autoConnect() - Initiate auto connection on BT on...
D/BluetoothAdapterService( 2073): [BTUI] autoConnect() : not allowed
D/BluetoothHeadset( 1785): onBluetoothStateChange: up=true
D/BluetoothManagerService(  847): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
E/BluetoothManagerService(  847): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService(  847): Bluetooth State Change Intent: 11 -> 12
D/BluetoothManagerService(  847): Message: 40
D/BluetoothManagerService(  847): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/LGBluetoothAPIService( 1838): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1838): Message: 1
D/BluetoothAdapterService(327569342)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3fcae804
D/bt_h4   ( 2073): vendor lib postload completed
D/LGBluetoothAPIService( 1838): MESSAGE_BOOT_COMPLETED
D/BluetoothAdapterService(327569342)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3fcae804
D/BluetoothAdapterService(327569342)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3fcae804
I/LGBluetoothAPIService( 1838): [BTUI] LGBluetoothAPIService Binding Success
I/[SystemUI]QuickSettingsHandler( 1388): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1388): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
W/ContextImpl( 3257): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
I/BluetoothMapService( 2073): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 2073): STATE_ON
D/BluetoothAdapterService( 2073): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13864fbe
V/BluetoothPbapService( 2073): Pbap Service onCreate
V/BluetoothPbapService( 2073): Starting PBAP service
D/BluetoothAdapterService(327569342)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3fcae804
D/LGBluetoothPbapAdapter( 2073): [BTUI] getInstance : create
V/BluetoothPbapService( 2073): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 2073): state: 12
D/LGBluetoothAPIServer( 2073): [BTUI] onCreate()
D/LGBluetoothAPIServer( 2073): [BTUI] onBind()
V/BluetoothMapService( 2073): Handler(): got msg=1
D/LGBluetoothAPIService( 1838): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/BluetoothMapMasInstance( 2073): Map Service startRfcommSocketListener
D/LGBluetoothAPIService( 1838): Message: 100
V/BluetoothPbapReceiver( 2073): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 2073): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 2073): ***********state = 12
D/BluetoothMapMasInstance( 2073): MAS initSocket()
V/BluetoothPbapService( 2073): Handler(): got msg=1
D/BluetoothMapMasInstance( 2073):   masId = 00
D/BluetoothMapMasInstance( 2073):   msgTypes = 0e
D/BluetoothMapMasInstance( 2073):   masName = SMS/MMS
D/BluetoothMapMasInstance( 2073):   SDP string = 000eSMS/MMS
D/LGBluetoothAPIService( 1838): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
V/BluetoothPbapService( 2073): Pbap Service startRfcommSocketListener
V/BluetoothOppNotification( 2073): new notify threadi!
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothOppNotification( 2073): send delay message
V/BluetoothPbapService( 2073): Pbap Service initSocket
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(327569342)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3fcae804
V/BluetoothOppProvider( 2073): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
D/LocalBluetoothProfileManager( 3257): Adding local A2DP profile
W/BluetoothAdapter( 2073): getBluetoothService() called with no BluetoothManagerCallback
W/BluetoothAdapter( 2073): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothManagerService(  847): Message: 30
I/bt-btif ( 2073): BTA_JvCreateRecordByUser
I/bt-btif ( 2073): BTA_JvRfcommStartServer
I/bt-btif ( 2073): BTA_JvCreateRecordByUser
I/bt-btif ( 2073): BTA_JvRfcommStartServer
D/LGBluetoothServiceAdapter( 2073): [BTUI] createSocketChannel FD=85 mFd=0
D/LGBluetoothServiceAdapter( 2073): [BTUI] createSocketChannel FD=83 mFd=0
V/BluetoothMapMasInstance( 2073): Succeed to create listening socket 
V/BluetoothPbapService( 2073): Succeed to create listening socket 
V/BluetoothPbapService( 2073): Accepting socket connection...
D/BluetoothMapMasInstance( 2073): Accepting socket connection...
E/MPT MptOnPowerWatcher( 3630): startListen
D/LocalBluetoothProfileManager( 3257): Adding local HEADSET profile
D/BluetoothManagerService(  847): Message: 30
D/BluetoothManagerService(  847): Message: 30
D/BluetoothManagerService(  847): Message: 30
V/BluetoothOppProvider( 2073): created cursor android.database.sqlite.SQLiteCursor@25fed171 on behalf of 
D/LocalBluetoothProfileManager( 3257): Adding local MAP profile
D/BluetoothMap( 3257): Create BluetoothMap proxy object
D/BluetoothManagerService(  847): Message: 30
V/BluetoothOppNotification( 2073): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 2073): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 2073): created cursor android.database.sqlite.SQLiteCursor@3fb5cb56 on behalf of 
V/BluetoothOppNotification( 2073): outbound: succ-0  fail-0
D/BluetoothManagerService(  847): Message: 30
I/NotificationManager( 2073): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
V/BluetoothOppNotification( 2073): outbound notification was removed.
V/BluetoothOppProvider( 2073): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 2073): created cursor android.database.sqlite.SQLiteCursor@1edff7d7 on behalf of 
V/BluetoothOppNotification( 2073): inbound: succ-0  fail-0
D/LocalBluetoothProfileManager( 3257): LocalBluetoothProfileManager construction complete
V/BluetoothPbapService( 2073): Pbap Service onBind
I/NotificationManager( 2073): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
V/BluetoothOppNotification( 2073): inbound notification was removed.
V/BluetoothOppProvider( 2073): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 2073): created cursor android.database.sqlite.SQLiteCursor@2a2a38c4 on behalf of 
D/LGBluetoothUserBindClient( 3257): [BTUI] initUserBindClient
W/ContextImpl( 3257): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 3257): finishStartingService: stopping service
D/BluetoothA2dp( 3257): Proxy object connected
D/A2dpProfile( 3257): Bluetooth service connected
D/BluetoothAdapterService(327569342)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3fcae804
D/BluetoothHeadset( 3257): Proxy object connected
D/HeadsetProfile( 3257): Bluetooth service connected
D/BluetoothAdapterService(327569342)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3fcae804
D/BluetoothInputDevice( 3257): Proxy object connected
D/HidProfile( 3257): Bluetooth service connected
D/BluetoothAdapterService(327569342)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3fcae804
D/BluetoothPan( 3257): BluetoothPAN Proxy object connected
D/PanProfile( 3257): Bluetooth service connected
D/BluetoothAdapterService(327569342)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3fcae804
D/BluetoothMap( 3257): Proxy object connected
D/MapProfile( 3257): Bluetooth service connected
D/BluetoothMap( 3257): getConnectedDevices()
D/BluetoothAdapterService(327569342)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3fcae804
V/BluetoothMapService( 2073): getConnectedDevices()
D/BluetoothPbap( 3257): Proxy object connected
D/PbapServerProfile( 3257): Bluetooth service connected
D/LGBluetoothUserBindClient( 3257): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 3257): onReceive
D/LGBluetoothFeatureConfig( 3257): isPrivacyLogsEnabled : true
V/BluetoothOppReceiver( 2073): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
V/BluetoothOppManager( 2073): restoreApplicationData! falsefalsenullnull
V/BluetoothSapReceiver( 2073): [BTUI] checkServiceStart
D/LGBluetoothStateChangeReceiver( 2073): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
D/AuthorizationBluetoothService( 1767): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager(  847): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=3725 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  298): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 316us total 22.356ms
I/art     (  298): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 2.487ms total 22.954ms
D/AndroidRuntime( 3701): 
D/AndroidRuntime( 3701): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3701): CheckJNI is OFF
I/art     (  298): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 23.162ms
W/ResourcesManager( 3725): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/Scheduler( 1767): Use legacy PeriodicScheduler
W/InstanceID/Rpc( 1767): Found 10006
I/art     ( 2092): Explicit concurrent mark sweep GC freed 2918(115KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 623us total 44.766ms
D/CalendarProvider2( 3725): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@10711041
I/RlzPingService( 3679): Setting next ping for 1452881408907
D/AndroidRuntime( 3701): Calling main entry com.android.commands.am.Am
I/ActivityManager(  847): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/art     (  847): Explicit concurrent mark sweep GC freed 12805(593KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 2.178ms total 150.331ms
D/ActivityManager(  847): setTaskToReturnTo : TaskRecord{2460de3c #220 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  847): setTaskToReturnTo : TaskRecord{2460de3c #220 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  847): AppWindowTokenEx init.. 
D/ContextHelper(  847): convertTheme. context->name=com.example.hello themeResourceId=16973833
D/InputDispatcher(  847): Focus left window: Window{29a42129 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/CalendarProvider2( 3725): [getOrCreateCalendarAlarmManager]
I/QCNEJ   ( 1874): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1874): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 19:10:09.084 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/AndroidRuntime( 3701): Shutting down VM
I/[LGHome]EVENT( 1912): [Launcher.java:986:onPause()]onPause
I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/CalendarProvider2( 3725): Created com.android.providers.calendar.CalendarAlarmManager@290ebe72(com.android.providers.calendar.CalendarProvider2@10711041)
I/ActivityManager(  847): Killing 3329:com.android.contacts/u0a18 (adj 15): empty #11
D/SplitWindow(  847): check instance of lgWin Window{3fe37a7d u0 Starting com.example.hello}
W/libprocessgroup(  847): failed to open /acct/uid_10018/pid_3329/cgroup.procs: No such file or directory
D/CalendarReceiver( 3725): [onReceive] intent = Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.providers.calendar/.CalendarReceiver (has extras) }
D/CalendarReceiver( 3725): [onReceive] WakeLock new : CalendarReceiver_Provider, ReferenceCounted = true
D/CalendarReceiver( 3725): [onReceive] WakeLock acquire : CalendarReceiver_Provider
D/CalendarReceiver( 3725): [onReceive] android.intent.action.BOOT_COMPLETED
I/ActivityManager(  847): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3760 uid=10317 gids={50317, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1912): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
D/CalendarProvider2( 3725): Scheduling check of next Alarm
D/CalendarProvider2( 3725): SCHEDULE_ALARM_REMOVE
I/HotwordDetector( 2004): Closing mic
D/CalendarReceiver( 3725): [onReceive] WakeLock release : CalendarReceiver_Provider
I/MicrophoneInputStream( 2004): mic_close com.google.android.apps.gsa.speech.audio.u@2db686bb
V/AudioRecord( 2004): stop()
D/AudioRecord( 2004): AudioRecord->stop()
V/AudioFlinger(  276): RecordHandle::stop()
V/AudioFlinger(  276): RecordThread::stop
V/AudioFlinger(  276): Record stopped OK
V/AudioPolicyManager(  276): stopInput() input 17
V/AudioPolicyService(  276): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  276): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  276): AudioCommandThread() waking up
V/AudioPolicyService(  276): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  276): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  276): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  276): ThreadBase::setParameters() routing=0
V/AudioFlinger(  276): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  276): processConfigEvents_l() remaining events 1
V/AudioFlinger(  276): processConfigEvents_l() DONE thread 0xb39ef000
D/audio_hw_primary(  276): in_standby: enter: stream (0xb546e420) usecase(7: audio-record)
I/ActivityManager(  847): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.receiver.DmReceiver: pid=3778 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
E/LAlarm  (  847): Service started flags 0 startId 3
V/audio_hw_primary(  276): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  276): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  276): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  276): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  276): disable_audio_route: exit
E/audio_hw_primary(  276): disable_snd_device: enter 144
D/hardware_info(  276): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  276): disable_snd_device: snd_device(144: lg-vr-handset-mic)
I/[LGHome]EVENT( 1912): [Launcher.java:5214:onStop()]onStop
V/audio_hw_primary(  276): stop_input_stream: exit: status(0)
V/audio_hw_primary(  276): in_standby: exit:  status(0)
V/AudioFlinger(  276): RecordThread: loop stopping
V/AudioPolicyService(  276): AudioCommandThread() going to sleep
V/AudioPolicyManager(  276): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  276): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  276): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  276): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  276): AudioCommandThread() waking up
V/AudioPolicyService(  276): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  276): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  276): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  276): AudioCommandThread() waking up
V/AudioPolicyService(  276): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  276): setParameters(): io 17, keyvalue hotword_active=0, calling pid 276
V/AudioPolicyService(  276): AudioCommandThread() going to sleep
V/AudioFlinger(  276): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  276): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  276): RecordThread: loop starting
V/AudioFlinger(  276): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  276): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  276): in_set_parameters: exit: status(0)
V/AudioFlinger(  276): processConfigEvents_l() DONE thread 0xb39ef000
V/AudioFlinger(  276): RecordThread: loop stopping
V/AudioPolicyService(  276): AudioCommandThread() going to sleep
V/AudioRecord( 2004): stop()
V/AudioRecord( 2004): stop()
V/AudioRecord( 2004): stop()
I/WindowStateAnimator(  847): Starting window displayed
V/AudioFlinger(  276): releasing 16 from 2004 for -1
V/AudioFlinger(  276):  decremented refcount to 0
V/AudioFlinger(  276): purging stale effects
V/AudioFlinger(  276): RecordHandle::stop()
V/AudioFlinger(  276): RecordThread::stop
V/AudioPolicyManager(  276): releaseInput() 17
V/AudioPolicyManager(  276): closeInput(17)
V/AudioFlinger(  276): closeInput() 17
V/AudioSystem(  276): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  276): ThreadBase::exit
V/AudioFlinger(  276): RecordThread: loop starting
V/AudioFlinger(  276): RecordThread 0xb39ef000 exiting
D/audio_hw_primary(  276): adev_close_input_stream: enter:stream_handle(0xb546e420)
D/audio_hw_primary(  276): in_standby: enter: stream (0xb546e420) usecase(7: audio-record)
V/audio_hw_primary(  276): in_standby: exit:  status(0)
V/AudioPolicyService(  276): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  276): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  276): AudioCommandThread() waking up
V/AudioPolicyService(  276): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  276): AudioCommandThread() going to sleep
V/AudioPolicyManager(  276): releaseInput() exit
V/AudioSystem(  847): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1388): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1785): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2073): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2004): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2710): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3180): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  276): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  276): removeClient_l() pid 2004, calling pid 276
I/HotwordRecognitionRnr( 2004): Hotword detection finished
I/SystemUI[Framework](  847): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.example.hello
,D/PhoneStatusBar( 1388): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  847): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  847): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  847): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  847): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3a41bd5e,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  847): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1388): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1388):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1388): , Keyguard show=false, IME shown=false, Panel expanded=false
I/HotwordRecognitionRnr( 2004): Stopping hotword detection.
D/BarTransitions( 1388): draw background and invalidate : color = 10000000
D/BarTransitions( 1388): draw background and invalidate : color = 13121212
D/ContextHelper( 3760): convertTheme. context->name=com.example.hello themeResourceId=16973833
W/ContextImpl( 3778): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmNotiService.bootCompleted:575 com.lge.lgdmsclient.receiver.DmReceiver.onReceive:94 
E/LGDMClient( 3778): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 3778): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 3778): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_BOOTUP_COMPLETE
D/LGDMClient( 3778): [DmUtil.java] [removeSilenceBootFile()] : [894] : Try to remove a Silence file
D/LGDMClient( 3778): [DmNotiService.java] [actionSystemBootComplete()] : [459] : CHECK_AUTO_UPDATE_PROCESS : 0 Call removeSilenceBootFile() 
I/WebViewFactory( 3760): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  847): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=3800 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
I/LGDMClient( 3778): [DmNotiService.java] [actionSystemBootComplete()] : [467] : DM Service on boot completed
D/LGDMClient( 3778): [DmClientController.java] [startService()] : [400] : startService(), DownloadService will be started in order to follow the start of DmClientController
W/ContextImpl( 3778): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.controller.DmClientController.startService:404 com.lge.lgdmsclient.dmclient.controller.DmClientController.getInstance:345 com.lge.lgdmsclient.service.DmNotiService.actionSystemBootComplete:474 
D/LGDMClient( 3778): [DmAgent.java] [<init>()] : [164] : DmAgent is started -> DmConstants.DMAgentState.mDmaState = 0
D/LGDMClient( 3778): [DmClientController.java] [run()] : [178] : LooperSTART
I/LGDMClient( 3778): [DmCAConfigParser.java] [getInstance()] : [73] : DmsCAConfigParser sInstance null
I/LibraryLoader( 3760): Time to load native libraries: 5 ms (timestamps 366-371)
I/LibraryLoader( 3760): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3760): Binding Chromium to main looper Looper (main, tid 1) {290ebe72}
D/LGDMClient( 3778): [DmPhoneSpecificInfo.java] [getPhoneSpecificInfo()] : [204] : Current MultiSimEnabled is false
I/LibraryLoader( 3760): Expected native library version number "",actual native library version number ""
I/chromium( 3760): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
D/LGDMClient( 3778): [DmPhoneSpecificInfo.java] [getPhoneSpecificInfo()] : [239] : getPhoneSpecificInfo: sim mccmnc(),spn(),gid(null),imsi(null)
I/LGDMClient( 3778): [DmCAConfigParser.java] [parse()] : [108] : parse
D/LGDMClient( 3778): [DmCAConfigParser.java] [setDefaultProfile()] : [490] : setDefaultProfile
D/LGDMClient( 3778): [DmCAConfigParser.java] [setDefaultProfile()] : [493] : filename : fota_dm_settings.xml
D/LGDMClient( 3778): [DmCAConfigParser.java] [setDefaultProfile()] : [506] : [UI4.1] Search [fota_dm_settings.xml]
I/BrowserStartupController( 3760): Initializing chromium process, singleProcess=true
D/ALBootInit( 3800): ====action==>android.intent.action.BOOT_COMPLETED
D/ALBootInit( 3800): Alarm ALBootInit: BOOT_COMPLETED
W/art     ( 3760): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3760): ApplicationContext is null in ApplicationStatus
I/ALProvider( 3800): delete where======= time <= 1452276609609  and  aindex > 0
D/LGDMClient( 3778): [DmCAConfigParser.java] [parse()] : [134] : [UI4.1] Search [fota_dm_settings.xml]
D/LGDMClient( 3778): [DmAgentUtil.java] [setAutoAgentSchedule()] : [117] : IN setAutoAgentSchedule()
W/chromium( 3760): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
D/Alarms  ( 3800):  --- disableExpiredAlarms!!! isBooting : true
E/libEGL  ( 3760): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3760): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3760): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 3760): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 3760): Build Date: 03/02/15 Mon
I/Adreno-EGL( 3760): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 3760): Remote Branch: 
I/Adreno-EGL( 3760): Local Patches: 
I/Adreno-EGL( 3760): Reconstruct Branch: 
I/WebViewFactory( 2004): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
D/Alarms  ( 3800): count ===>0
D/Alarms  ( 3800): snoozeActivating scount==>0
D/Alarms  ( 3800): [setNextAlert] start
D/LGDMClient( 3778): [DmAgentUtil.java] [setAutoAgentSchedule()] : [126] :  cursor != null setAutoAgentSchedule()
D/Alarms  ( 3800): [setNextAlert] (1)
D/LGDMClient( 3778): [DmAgentUtil.java] [setAutoAgentSchedule()] : [167] : SET ALARM setAutoAgentSchedule() = 20160114T212428
D/Alarms  ( 3800):  minTime  = 0
D/Alarms  ( 3800):  -- OK multi -- 0
D/LGDMClient( 3778): [DmAgentUtil.java] [setAutoAgentSchedule()] : [185] : OUT setAutoAgentSchedule()
D/LGDMClient( 3778): [DmAgent.java] [checkPostponed()] : [2062] : DMAGentState is: DmConstants.DMAgentState.mDmaState = 0
E/jeny.kim( 3800): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 3800): [setNextAlert]setNextAlert temp_AlarmLinkText + 
V/LGDMClient( 3778): [DmClientController.java] [handleMessage()] : [181] : DmClientController: run() - msg.what=31
D/LGDMClient( 3778): [DmAgent.java] [processRestartHandler()] : [1241] : DMAGentState is: DmConstants.DMAgentState.mDmaState = 0
E/LGDMClient( 3778): [DmDownloadService.java] [onCreate()] : [56] : DmDownloadService.onCreate()
D/LGDMClient( 3778): [DmDownloadService.java] [onStartCommand()] : [92] : DmDownloadService.onStartCommand()
D/LGDMClient( 3778): [DmDownloadService.java] [handleStart()] : [103] : DmDownloadService  intend : Intent { cmp=com.lge.lgdmsclient/.service.DmDownloadService }
I/CommonUtil( 3800): BUILD Operator: OPEN
I/LibraryLoader( 2004): Time to load native libraries: 2 ms (timestamps 526-528)
I/LibraryLoader( 2004): Expected native library version number "",actual native library version number ""
D/Alarms  ( 3800): broadcastToWidgetProvider : false
D/Alarms  ( 3800): Enter formatDayAndTime(final Context context, long timeInMiliSec)
V/AudioPolicyService(  276): registerClient() client 0xb381c9c0, uid 10317
D/BluetoothManagerService(  847): Message: 20
D/BluetoothManagerService(  847): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2f12836e:true
V/SettingsProvider(  847): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
D/BluetoothAdapterService(327569342)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3fcae804
E/[LGE_FOTA] ( 3778): FOTA JNI_OnLoad
E/[LGE_FOTA] ( 3778):  FOTAJNI_GetUAResult in
E/[LGE_FOTA] ( 3778): FOTAFS_Open /cache/fota/usd.dat, 0, handle : 1c
W/art     ( 2004): Attempt to remove local handle scope entry from IRT, ignoring
E/[LGE_FOTA] ( 3778): enUpdateState                : 0x00000000
E/[LGE_FOTA] ( 3778): stFWInfo.enState             : 0x00000000
E/[LGE_FOTA] ( 3778): stFWInfo.uiPkgOffset[0]     : 0x00000000
E/[LGE_FOTA] ( 3778): stFWInfo.uiPkgSize[0]       : 0x00000000
E/[LGE_FOTA] ( 3778): stFWInfo.uiPkgOffset[1]     : 0x00000000
E/[LGE_FOTA] ( 3778): stFWInfo.uiPkgSize[1]       : 0x00000000
E/[LGE_FOTA] ( 3778): stFWInfo.uiPkgOffset[2]     : 0x00000000
E/[LGE_FOTA] ( 3778): stFWInfo.uiPkgSize[2]       : 0x00000000
E/[LGE_FOTA] ( 3778): stFWInfo.uiPkgOffset[3]     : 0x00000000
E/[LGE_FOTA] ( 3778): stFWInfo.uiPkgSize[3]       : 0x00000000
E/[LGE_FOTA] ( 3778): stFWInfo.uiPkgOffset[4]     : 0x00000000
E/[LGE_FOTA] ( 3778): stFWInfo.uiPkgSize[4]       : 0x00000000
E/[LGE_FOTA] ( 3778): stFWInfo.uiPkgOffset[5]     : 0x00000000
E/[LGE_FOTA] ( 3778): stFWInfo.uiPkgSize[5]       : 0x00000000
E/[LGE_FOTA] ( 3778): stFWInfo.uiPkgOffset[6]     : 0x00000000
E/[LGE_FOTA] ( 3778): stFWInfo.uiPkgSize[6]       : 0x00000000
E/[LGE_FOTA] ( 3778): stFWInfo.uiPkgOffset[7]     : 0x00000000
E/[LGE_FOTA] ( 3778): stFWInfo.uiPkgSize[7]       : 0x00000000
E/[LGE_FOTA] ( 3778): stFWInfo.uiPkgOffset[8]     : 0x00000000
E/[LGE_FOTA] ( 3778): stFWInfo.uiPkgSize[8]       : 0x00000000
E/[LGE_FOTA] ( 3778): stFWInfo.uiPkgOffset[9]     : 0x00000000
E/[LGE_FOTA] ( 3778): stFWInfo.uiPkgSize[9]       : 0x00000000
E/[LGE_FOTA] ( 3778): stFWInfo.uiPkgOffset[10]     : 0x00000000
E/[LGE_FOTA] ( 3778): stFWInfo.uiPkgSize[10]       : 0x00000000
E/[LGE_FOTA] ( 3778): stFWInfo.uiPkgOffset[11]     : 0x00000000
E/[LGE_FOTA] ( 3778): stFWInfo.uiPkgSize[11]       : 0x00000000
E/[LGE_FOTA] ( 3778): stFWInfo.uiPkgOffset[12]     : 0x00000000
E/[LGE_FOTA] ( 3778): stFWInfo.uiPkgSize[12]       : 0x00000000
E/[LGE_FOTA] ( 3778): stFWInfo.uiPkgOffset[13]     : 0x00000000
E/[LGE_FOTA] ( 3778): stFWInfo.uiPkgSize[13]       : 0x00000000
E/[LGE_FOTA] ( 3778): stFWInfo.uiPkgOffset[14]     : 0x00000000
E/[LGE_FOTA] ( 3778): stFWInfo.uiPkgSize[14]       : 0x00000000
E/[LGE_FOTA] ( 3778): stFWInfo.uiPkgOffset[15]     : 0x00000000
E/[LGE_FOTA] ( 3778): stFWInfo.uiPkgSize[15]       : 0x00000000
E/[LGE_FOTA] ( 3778): stFWInfo.uiCurrSection       : 0x00000000
E/[LGE_FOTA] ( 3778): stFWInfo.uiResult            : 0x00000000
E/[LGE_FOTA] ( 3778): stFSInfo.enState             : 0x00000000
E/[LGE_FOTA] ( 3778): stFSInfo.uiFilePackageOffset : 0xa09ff7d4
E/[LGE_FOTA] ( 3778): stFSInfo.uiFilePackageSize   : 0xa09ff7f4
E/[LGE_FOTA] ( 3778): stFSInfo.uiResult            : 0x00000000
E/[LGE_FOTA] ( 3778): stPkgInfo.enPackageType      : 0x00000000
E/[LGE_FOTA] ( 3778): stPkgInfo.uiSize             : 0x00000000
E/[LGE_FOTA] ( 3778): stPkgInfo.uiWrittenAddr      : 0x00000000
E/[LGE_FOTA] ( 3778): stPkgInfo.uiWrittenSize      : 0x00000000
E/[LGE_FOTA] ( 3778): stPkgInfo.szPackagePath      : 
E/[LGE_FOTA] ( 3778): stCommand.enCommand	 		: 0x00000000
E/[LGE_FOTA] ( 3778): uiBackupBufferAddr			: 0x00000000
E/[LGE_FOTA] ( 3778): uiLanguage					: 0x00000000
E/[LGE_FOTA] ( 3778): stDebug.uiResetCount			: 0x00000000
E/[LGE_FOTA] ( 3778): stDebug.uiRetryCount			: 0x00000000
E/[LGE_FOTA] ( 3778): FOTAFS_Close 1c
E/[LGE_FOTA] ( 3778): FOTAJNI_GetConvertedUAResult : 450
E/[LGE_FOTA] ( 3778): FOTAJNI_GetUAResult : 450
D/LGDMClient( 3778): [SwUpdate.java] [getSwUpdateStatus()] : [244] : Software update result:450
D/LGDMClient( 3778): [DmAgent.java] [restartIdleSession()] : [1084] : skymymy is: iSwUpdateStatus = 450, isUpgradedByLGUP() = false
D/LGDMClient( 3778): [DmAgent.java] [clearContext()] : [1774] : [Enter] clearContext
D/CommonUtil( 3800): Enter deleteUnnecessaryToneItem() enter excepted tone uri value is null, preferparent value is  ALARM
D/CommonUtil( 3800): deleteUnnecessaryToneItem() -> Alarm Surviv Count is 0
D/CommonUtil( 3800): Exit deleteUnnecessaryToneItem()
I/CommonUtil( 3800): BUILD Country: EU
I/TimerReceiver( 3800): onReceiveIntent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.lge.clock/.timer.TimerReceiver (has extras) }
D/TimerReceiver( 3800): onReceive() : android.intent.action.BOOT_COMPLETED
I/TimerReceiver( 3800): setTimerDone
I/LGDMClient( 3778): [DmAgent.java] [setState()] : [1875] : Setting Agent State and State is : DmConstants.DMAgentState.mDmaState = 0
D/TimerObj( 3800): --------------------- getTimersFromSharedPrefs
D/LGDMClient( 3778): [DmAgent.java] [clearContext()] : [1791] : [Exit] clearContext
V/LGDMClient( 3778): [DmClientController.java] [handleMessage()] : [181] : DmClientController: run() - msg.what=33
V/TimerObj( 3800): --------------------- timers list is empty
D/LGDMClient( 3778): [DmClientController.java] [stopService()] : [408] : stopDownloadService(), DownloadService will be stopped in order to follow the end of DmClientController
W/ContextImpl( 3778): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1804 android.content.ContextWrapper.stopService:520 com.lge.lgdmsclient.dmclient.controller.DmClientController.stopService:412 com.lge.lgdmsclient.dmclient.controller.DmClientController.clearController:383 com.lge.lgdmsclient.dmclient.controller.DmClientController.access$200:68 
I/ActivityManager(  847): Start proc com.lge.appbox.client:SingleBinaryService for broadcast com.lge.appbox.client/com.lge.appbox.singlebinary.SimChangeReceiver: pid=3850 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/LGDMClient( 3778): [DmDownloadService.java] [onDestroy()] : [117] : DmDownloadService.onDestroy()
,I/ActivityManager(  847): Killing 3462:com.android.keychain/1000 (adj 15): empty #11
W/libprocessgroup(  847): failed to open /acct/uid_1000/pid_3462/cgroup.procs: No such file or directory
,W/art     ( 3760): Attempt to remove local handle scope entry from IRT, ignoring
,D/AppUp4:AppBoxApplication( 3850): AppBoxApplication onCreate()
W/AwContents( 3760): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3760): CordovaWebView is running on device made by: LGE
D/AppUp4:SingleBinary( 3850): /cust/OPEN_EU/config/app-enabled-conf.json is selected!!
,D/AppUp4:SingleBinary( 3850):  Starting isFingerChanged 
W/art     ( 3760): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3760): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2004): Attempt to remove local handle scope entry from IRT, ignoring
,I/ActivityManager(  847): Start proc com.lge.appbox.client for content provider com.lge.appbox.client/com.lge.appbox.databases.AppBoxContentProvider: pid=3873 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/Activity( 3760): Activity.onPostResume() called 
,D/OpenGLRenderer( 3760): Render dirty regions requested: true
I/OpenGLRenderer( 3760): Initialized EGL, version 1.4
D/OpenGLRenderer( 3760): Enabling debug mode 0
,D/Atlas   ( 3760): Validating map...
D/SplitWindow(  847): check instance of lgWin Window{2c8efb8 u0 com.example.hello/com.example.hello.MainActivity}
W/chromium( 3760): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  847): Killing 3386:com.lge.hiddenmenu/1000 (adj 15): empty #11
D/libc-netbsd( 2004): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2004): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
E/BandwidthController(  271): [LG DATA] No such appUid: 10042
D/DnsProxyListener(  271): App 10042 tries DNS query. Accept family:2 protocol:0
,D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
I/AppUp4:AppBoxCP( 3873): onCreate
,W/AppUp4:DB( 3873):  [AppBoxDatabaseHelper] construct
W/libprocessgroup(  847): failed to open /acct/uid_1000/pid_3386/cgroup.procs: No such file or directory
I/AppUp4:DB( 3873):  setFingerPrint start
I/AppUp4:DB( 3873):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 3873):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 3873):  SDK version = 0
I/AppUp4:DB( 3873):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 3873): AppBoxApplication onCreate()
,D/libc-netbsd(  271): res_queryN name = xxxxx succeed
D/AppUp4:SingleBinary( 3850):  The value of isFingerChanged null
D/AppUp4:SingleBinary( 3850): Device : jagnm
D/AppUp4:SingleBinary( 3850): First Boot - ignore boot completed
,D/InputDispatcher(  847): Focus entered window: Window{2c8efb8 u0 com.example.hello/com.example.hello.MainActivity}
D/AppUp4:NTCodeSingleBinary( 3850): Starting isFingerChanged 
I/CalendarProvider2( 3725): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,D/AppUp4:NTCodeSingleBinary( 3850): The value of isFingerChanged lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
D/AppUp4:SingleBinary( 3850): Device : jagnm
D/AppUp4:SingleBinary( 3850): Config file is not exist - nothing
W/ContentResolver( 3725): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  847): Killing 3519:com.google.android.onetimeinitializer/u0a8 (adj 15): empty #11
W/InputMethodManagerService(  847): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/Timeline( 3760): Timeline: Activity_idle id: android.os.BinderProxy@28c8ffe9 time:51118
,W/libprocessgroup(  847): failed to open /acct/uid_10008/pid_3519/cgroup.procs: No such file or directory
I/ActivityManager(  847): Displayed com.example.hello/.MainActivity: +1s162ms
I/Timeline(  847): Timeline: Activity_windows_visible id: ActivityRecord{1f5d17c5 u0 com.example.hello/.MainActivity t220} time:51127
I/ActivityManager(  847): Killing 3474:com.android.gallery3d/u0a23 (adj 15): empty #11
I/AppUp4:SDKReflector( 3873): +myUserId : 0
D/AppUp4:BootUpPollingReceiver( 3873): onReceive on user ID : 0
,V/AppUp4:FotaPlusService( 3873):  isFotaPlusTriedOnce : true
D/AppUp4:BootUpPollingReceiver( 3873): Starting getSdkVersion 
,D/AppUp4:BootUpPollingReceiver( 3873): SDK version is : 0
D/AppUp4:BootUpPollingReceiver( 3873): currentSdkVersion : 0
D/AppUp4:BootUpPollingReceiver( 3873): isSdkVersionChanged : true
V/AppUp4:FotaPlusService( 3873):  setFotaPlusCompleted : false
D/AppUp4:BootUpPollingReceiver( 3873): isFotaPlusNeeded : true
D/AppUp4:BootUpPollingReceiver( 3873): Fota Plus already tried once, show notification
W/BindingManager( 3760): Cannot call determinedVisibility() - never saw a connection for the pid: 3760
,W/libprocessgroup(  847): failed to open /acct/uid_10023/pid_3474/cgroup.procs: No such file or directory
,I/chromium( 3760): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,V/NotificationService(  847): enqueueNotificationInternal: pkg=com.lge.appbox.client id=22319582 notification=Notification(pri=0 contentView=null vibrate=default sound=default defaults=0x3 flags=0x2 color=0x00000000 vis=PRIVATE)
D/AppUp4:BootUpPollingReceiver( 3873): isFotaPlusRunning after : true
D/ZenLog  (  847): intercepted: 0|com.lge.appbox.client|22319582|null|10011,none
D/AppUp4:BootUpPollingReceiver( 3873):  installPreloadedValuePackIfNeeded 
D/AppUp4:BootUpPollingReceiver( 3873):  file is : /system/apps/bootup
V/NotificationService(  847): pkg=com.lge.appbox.client canInterrupt=false intercept=true
D/AppUp4:BootUpPollingReceiver( 3873): file false
I/NotificationServiceEx(  847): LED remove() : mLights=0|com.lge.appbox.client|22319582|null|10011
D/NotificationServiceEx(  847): updateLightListLocked :r=0|com.lge.appbox.client|22319582|null|10011, action=2
D/AppUp4:BootUpPollingReceiver( 3873): [BootUpPollingReceiver] No preload installation.
D/NotificationServiceEx(  847): notification=Notification(pri=0 contentView=null vibrate=default sound=default defaults=0x3 flags=0x2 color=0x00000000 vis=PRIVATE)
D/AppUp4:dwnld( 3873): [removeAllIncompletedDownload] ... 
,D/SmartCoverUpdateMonitor( 1330): onNotificationPosted() : StatusBarNotification(pkg=com.lge.appbox.client user=UserHandle{0} id=22319582 tag=null score=0 key=0|com.lge.appbox.client|22319582|null|10011: Notification(pri=0 contentView=com.lge.appbox.client/0x1090079 vibrate=default sound=default defaults=0x3 flags=0x2 color=0x00000000 vis=PRIVATE))
D/SmartCoverUpdateMonitor( 1330): onNotificationPosted() !qcn.isEnableToShowNotification()
V/AppUp4:BootUpPollingReceiver( 3873): [BootUpPollingReceiver] start bootup Polling.
D/AppUp4  ( 3873): getUpdatePollingPeriod
,D/AppUp4  ( 3873): getUpdatePollingPeriod
,D/AppUp4:BackgroundPollingService ( 3873): register polling alarm when : 2016/01/14 21:32:00
D/AppUp4:LightWeightPollingService ( 3873):  [buildRemotePollingIntent]
D/AppUp4:LightWeightPollingService ( 3873): This means remote config is N, so skip it
,I/[SystemUI]PhoneStatusBar( 1388): updateMediaMetaData(false): mMediaMetadata = null
I/ActivityManager(  847): Killing 3551:com.android.cellbroadcastreceiver/u0a16 (adj 15): empty #11
,D/JsMessageQueue( 3760): Set native->JS mode to OnlineEventsBridgeMode
,W/libprocessgroup(  847): failed to open /acct/uid_10016/pid_3551/cgroup.procs: No such file or directory
E/AndroidProtocolHandler( 3760): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/ActivityManager(  847): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=3912 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/MmsConfig( 3180): isNotAllowedSms: currentUser:0
D/MmsConfig( 3180): isNotAllowedSms: UserHandle.myUserId():0
D/MmsConfig( 3180): isUserMode:false
D/SmsReceiverService( 3180): handleMessage isUserMode:false
W/ResourcesManager( 3180): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/SmsReceiverService( 3180): handleMessage action: android.intent.action.BOOT_COMPLETED error: 0
,W/ResourcesManager( 3912): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 3912): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 3912): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 3912): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@2124db27, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@3ea161d4, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@147d6f7d, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@290ebe72, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@377a02c3, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@319cc740, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@3ff68679, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@13864fbe, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@2770081f, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@1427176c, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@7501135, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@653a9ca, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@b97073b, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@6243e58, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@387d8bb1, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@9ea9896, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@d64dc17, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@3fcae804, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@332e31ed, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@282fa822, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@dd122b3, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@24108070, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@28c8ffe9, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@32c4246e, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@3bb1370f, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@dd5339c, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@2028b1a5, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@2212197a, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@33d4352b, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3cfed88, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@3917c321, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@19185346, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@6def907, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@3f3a5a34, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@2b8c705d, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@19f65dd2, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@e81ea3, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@313ce5a0, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@3ea4b559, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@3738851e, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@ed401ff, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@331abbcc, l
D/GeneralP,referenceUtils( 3912): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 3912): [init]
I/Config  ( 3912): LGCalendar ver.4.40.17
I/Config  ( 3912): start check model
I/Config  ( 3912): start check native_ca
I/Config  ( 3912): Config Operator=OPEN, Country=EU
D/Config  ( 3912): [setDefaultValuesToPref]
D/Config  ( 3912): [parseProfiles]
D/ProfilesParser( 3912): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 3912): [debug_displayParseInfos] profile.operator = null
D/Config  ( 3912): [updateProfiletoCountryInfo]
D/GeneralPreference( 3912): [checkAndMigrateOldPreference]
D/AlertReceiver( 3912): onReceive: a=android.intent.action.BOOT_COMPLETED Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.calendar/.alerts.AlertReceiver (has extras) }
I/InitNotificationRingtoneService( 3912): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 3912): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,D/UsbSettingsReceiver( 3257): [AUTORUN] onReceive() : action = android.intent.action.BOOT_COMPLETED
D/UsbSettingsReceiver( 3257): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 3257): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 3257): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 3257): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 3257): [AUTORUN] setTetherStatus() : status=false
D/UsbSettingsReceiver( 3257): [AUTORUN] onReceive() : android.intent.action.BOOT_COMPLETED
D/UsbSettingsReceiver( 3257): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 3257): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 3257): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/StoreModeReceiver( 3257): intent.getAction() : android.intent.action.BOOT_COMPLETED
D/StoreModeReceiver( 3257): sim state :null
D/StoreModeReceiver( 3257): Back LED don't supported.
V/SettingsProvider(  847): call_put(system:emotional_led_back_led=0) for 0 calling package = com.android.settings
V/SettingsProvider(  847): call_put(system:emotional_led_back_incoming_call=0) for 0 calling package = com.android.settings
,V/SettingsProvider(  847): call_put(system:emotional_led_back_alarm=0) for 0 calling package = com.android.settings
V/SettingsProvider(  847): call_put(system:emotional_led_back_missed_call=0) for 0 calling package = com.android.settings
V/SettingsProvider(  847): call_put(system:emotional_led_back_missed_messages=0) for 0 calling package = com.android.settings
V/SettingsProvider(  847): call_put(system:emotional_led_back_missed_emails=0) for 0 calling package = com.android.settings
V/SettingsProvider(  847): call_put(system:emotional_led_back_calendar_noti=0) for 0 calling package = com.android.settings
V/SettingsProvider(  847): call_put(system:emotional_led_back_voice_recording=0) for 0 calling package = com.android.settings
V/SettingsProvider(  847): call_put(system:emotional_led_back_camera_timer_noti=0) for 0 calling package = com.android.settings
V/SettingsProvider(  847): call_put(system:emotional_led_back_camera_face_detecting_noti=0) for 0 calling package = com.android.settings
V/SettingsProvider(  847): call_put(system:notification_light_pulse_back=0) for 0 calling package = com.android.settings
D/StoreModeReceiver( 3257): SystemProperty Default brightness value [0-255] : 143
D/StoreModeReceiver( 3257): Default brightness[0-255] : 143
I/AlertUtils( 3912): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 3912): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
W/ResourcesManager( 3257): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/StoreModeReceiver( 3257): Default Screen off timeout value : 30000
D/StoreModeReceiver( 3257): SystemProperty Default brightness Mode value[true/false] : false
D/StoreModeReceiver( 3257): BRIGHTNESS_MODE - 0
D/StoreModeReceiver( 3257): Default brightness Mode [0/1] : 0
D/StoreModeReceiver( 3257): Default NIGHT_MODE : 0
D/StoreModeReceiver( 3257): Set MaxBrightness : 255
I/AlertUtils( 3912): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,E/PhoneInterfaceManager( 1785): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
D/StoreModeReceiver( 3257): getPhoneNumber is empty
D/StoreModeReceiver( 3257): go to StoreModeCheck()
I/AlertUtils( 3912): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
D/StoreModeReceiver( 3257): isStoremode not null
,I/AlertUtils( 3912): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 3912): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,D/PhoneInterfaceManager( 1785): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
I/AlertUtils( 3912): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 3912): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
V/SettingsProvider(  847): call_put(system:shop_mode_check=1) for 0 calling package = com.android.settings
I/AlertUtils( 3912): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 3912): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
D/StoreModeReceiver( 3257): product_name : jagnm_global_com
,D/StoreModeReceiver( 3257): Store mode start!
V/SettingsProvider(  847): call_put(system:shop_mode=1) for 0 calling package = com.android.settings
V/SettingsProvider(  847): call_put(system:shop_mode_check=1) for 0 calling package = com.android.settings
I/AlertUtils( 3912): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/PowerManagerService(  847): ALS enabled for SRE
,D/PowerManagerServiceEx(  847): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x1, nextTimeout=120000 (in 68227 ms)
I/AlertUtils( 3912): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
D/StoreModeReceiver( 3257): setBrightness() : NoMultiALC=255
I/AlertUtils( 3912): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
W/ContextImpl( 3257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.StoreModeReceiver.sendBroadcast:500 com.android.settings.StoreModeReceiver.setMode:473 
V/SettingsProvider(  847): call_put(system:screen_brightness_mode=0) for 0 calling package = com.android.settings
,D/SettingsProvider(  847): Set screen_off_timeout in entry value : 120000
V/SettingsProvider(  847): call_put(system:screen_off_timeout=120000) for 0 calling package = com.android.settings
V/SettingsProvider(  847): call_put(system:screen_brightness=255) for 0 calling package = com.android.settings
V/SettingsProvider(  847): call_put(system:check_night_mode=0) for 0 calling package = com.android.settings
I/AlertUtils( 3912): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 3912): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,D/SettingBootReceiver( 3257): onReceive
D/SettingBootReceiver( 3257): Boot Completed intent received, action=android.intent.action.BOOT_COMPLETED
I/AlertUtils( 3912): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3912): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
,D/SettingBootReceiver( 3257): setStyle()
I/AlertUtils( 3912): set default noti to content://media/internal/audio/media/38
D/SettingBootReceiver( 3257): SettingStyle=1
I/[SystemUI]LGBootReceiver( 1388): onReceive = android.intent.action.BOOT_COMPLETED
I/[SystemUI]LGPowerUI( 1388): onReceive = com.lge.statusbar.bootcompleted
,D/SettingBootReceiver( 3257): setAccountMenu()
I/[SystemUI]PhoneStatusBar( 1388): got ACTION_STICKY_BOOT_COMPLETED
I/BOOT    ( 1388): got ACTION_STICKY_BOOT_COMPLETED
D/TAG     ( 3257): setKidsMode
D/TAG     ( 3257): mIsOwner, setKidsMode
D/SettingBootReceiver( 3257): setAccountMenu()
D/SettingBootReceiver( 3257): com.lge.appwidget.settings.powercontrol is not installed.(Successfully Removed)
D/SettingBootReceiver( 3257): com.lge.appwidget.settings.powercontrol is not installed.(Successfully Removed)
D/SettingBootReceiver( 3257): com.lge.appwidget.settings.powercontrol is not installed.(Successfully Removed)
I/InitNotificationRingtoneService( 3912): End InitializeAlertRingtoneService.onHandleIntent
D/YSY     ( 3257): not support Quiet mode notification
,V/SettingsProvider(  847): call_put(system:gentle_vibration_status=1) for 0 calling package = com.android.settings
,V/SettingsProvider(  847): call_put(system:smart_ringtone=0) for 0 calling package = com.android.settings
,I/ActivityManager(  847): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3939 uid=10111 gids={50111, 9997, 1028, 3003} abi=armeabi-v7a
D/SettingBootReceiver( 3257): timezoneID is null
,W/HolidayIntentService( 3912): onHandleIntent
D/HolidayDataLoader( 3912): readJsonAsset : holiday.json
I/SettingBootReceiver( 3257): disable au
I/TAG     ( 3257): disable WirelessSettingsActivity
,D/jxcore_app_log( 3760): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426135552
D/JX-Cordova( 3760): jxcore cordova android initializing
I/TAG     ( 3257): disable SKTPhoneMode
D/AlertService( 3912): 0 Action = android.intent.action.BOOT_COMPLETED
D/AlertService( 3912): [Widget]com.android.calendar.widget.CalendarAppWidgetProvider enabled
D/Feature ( 3912): MemoryLevel - 5:NOT_DEF:Not UI4.2 LOS
,D/AlertService( 3912): [Widget]com.android.calendar.widget.MonthWidgetProvider enabled
D/AlertService( 3912): [Widget]com.android.calendar.widget.WeekWidgetProvider enabled
D/AlertService( 3912): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/SettingBootReceiver( 3257): [Nightmode] Enter receiver
D/SettingBootReceiver( 3257): [Nightmode] BOOT_COMPLETED
,D/NightModeInfo( 3257): [Nightmode] setNightNodeTabSettings
D/NightModeInfo( 3257): [Nightmode] getAlreadyNightModeDB() : 0
D/NightModeInfo( 3257): [Nightmode] getUserBrightnessChange() : 0
D/NightModeInfo( 3257): [Nightmode] getUserBrightnessChangeNoNight() : 0
V/SettingsProvider(  847): call_put(system:already_night_mode=0) for 0 calling package = com.android.settings
,V/SettingsProvider(  847): call_put(system:user_change_brightness=0) for 0 calling package = com.android.settings
V/SettingsProvider(  847): call_put(system:user_change_brightness_no_night=0) for 0 calling package = com.android.settings
V/SettingsProvider(  847): call_put(system:night_mode_enabled=0) for 0 calling package = com.android.settings
,D/NightModeInfo( 3257): [Nightmode] setTabNightCheck : 0
V/SettingsProvider(  847): call_put(system:save_tab_night_check=0) for 0 calling package = com.android.settings
D/AlarmScheduler( 3912): No events found starting within 1 week.
D/NightModeInfo( 3257): [Nightmode] cancelPendingIntent
W/jxcore-log( 3760): Initializing JXcore engine
,W/jxcore-log( 3760): JXcore engine is ready
D/NightModeInfo( 3257): [Nightmode] requestPendingIntent
D/NightModeInfo( 3257): [Nightmode] setAlarmStart~!!~!!~!!
D/NightModeInfo( 3257): [Nightmode] currentHour > 6
D/NightModeInfo( 3257): [Nightmode] currentHour > 6
I/NightModeInfo( 3257): JW getStartTime201601090000
D/NightModeInfo( 3257): [Nightmode] setAlarmEnd~!!~!!~!!
D/NightModeInfo( 3257): [Nightmode] currentHour > 6
D/NightModeInfo( 3257): [Nightmode] currentHour > 6
I/NightModeInfo( 3257): JW getEndTime201601090600
D/NightModeInfo( 3257): [Nightmode] currentHour > 6
E/HolidayIntentService( 3912): onHandleIntent:holiday data empty
I/NightModeInfo( 3257): getStartTime201601090000
D/NightModeInfo( 3257): [Nightmode] currentHour > 6
,I/NightModeInfo( 3257): getEndTime201601090600
D/jw      ( 3257): Only VZW Supported end return
V/DownloadManager( 3201): Received broadcast intent for android.intent.action.BOOT_COMPLETED
,V/DownloadManager( 3201): DownloadService onCreate
I/NotificationManager( 3201): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3201): in removeSpuriousFiles
V/DownloadManager( 3201): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3201): created cursor android.database.sqlite.SQLiteCursor@dd122b3 on behalf of 3201
I/ActivityManager(  847): Killing 3599:com.lge.email/u0a21 (adj 15): empty #11
I/DownloadManager( 3201): in trimDatabase
V/DownloadManager( 3201): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3201): created cursor android.database.sqlite.SQLiteCursor@28c8ffe9 on behalf of 3201
W/Thread-356( 3958): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7773]" dev="sockfs" ino=7773 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-356( 3958): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-356( 3958): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6345]" dev="sockfs" ino=6345 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-356( 3958): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-356( 3958): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-356( 3958): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[18839]" dev="sockfs" ino=18839 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 3760): Starting JXcore engine
,W/libprocessgroup(  847): failed to open /acct/uid_10021/pid_3599/cgroup.procs: No such file or directory
,V/DownloadManager( 3201): DownloadService onStartCommand
V/DownloadManager( 3201): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3201): created cursor android.database.sqlite.SQLiteCursor@3bb1370f on behalf of 3201
D/MediaScannerReceiver( 3201): [MediaScanner] ACTION_BOOT_COMPLETED scan INTERNAL_VOLUME, EXTERNAL_VOLUME
D/MediaScannerService( 3201): [MediaScanner] start scanning volume internal: [/system/media, /oem/media, /cust/OPEN_EU/media]
,V/LGMediaProvider( 3201): insertInternal: content://media/none/media_scanner, initValues=volume=internal
D/MediaScannerService( 3201): [MediaScanner] scan() ACTION_MEDIA_SCANNER_STARTED uri : file:///system/media
D/WiseScreenService( 1856): [OnBootReceiver.java:24:onReceive()] iKeepScreenOn: 0
,D/WiseScreenService( 1856): [OnBootReceiver.java:28:onReceive()] iSmartVideo: 0
D/MtpService( 3201): updating state; isCurrentUser=true, mMtpLocked=false
W/ContextImpl( 1856): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1804 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.lge.keepscreenon.OnBootReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2663 
D/MtpService( 3201): addStorageLocked 65537 /storage/emulated/0
,E/MtpStorageEx( 3201): setAccessCapability false
D/MtpService( 3201): updating state; isCurrentUser=true, mMtpLocked=false
I/MusicBrowser( 2710): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_STARTED dat=file:///system/media flg=0x10 }}
,D/MediaScannerEx( 3201): [MediaScanner] scanDirectories()[0] = /system/media
D/MediaScannerEx( 3201): [MediaScanner] scanDirectories()[1] = /oem/media
D/MediaScannerEx( 3201): [MediaScanner] scanDirectories()[2] = /cust/OPEN_EU/media
I/MusicBrowser( 2710): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 2710): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_STARTED
I/art     ( 3201): Thread[1,tid=3201,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31f8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
,E/MediaProfilesEx-JNI( 3201): register_com_lge_media_MediaProfilesEx
E/MediaRecorderEx-JNI( 3201): register_com_lge_media_MediaRecorderEx
D/AudioSystemEx( 3201): register_com_lge_media_LGAudioSystem
E/SurfaceControlEx( 3201): register_com_lge_view_SurfaceControlEx
I/art     ( 3201): Thread[1,tid=3201,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31f8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
D/LGMtpDatabaseJNI( 3201): register_android_mtp_LGMtpDatabase
D/LGMtpServerJNI( 3201): register_android_mtp_LGMtpServer
I/art     ( 3201): Thread[1,tid=3201,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31f8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
E/MediaPlayerEx-jni( 3201): register_com_lge_view_MediaPlayerEx
I/art     ( 3201): Thread[1,tid=3201,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31f8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
D/        ( 3201): register_com_lge_emoji_EmojiUtil
E/LGMtpDatabaseJNI( 3201): android_mtp_LGMtpDatabase_setup
I/ActivityManager(  847): Start proc com.lge.voicerecorder for broadcast com.lge.voicerecorder/.bookmarkdb.BootCompletedReceiver: pid=3967 uid=10034 gids={50034, 9997, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,W/jxcore-log( 3760): Platform android
W/jxcore-log( 3760): 
W/jxcore-log( 3760): Process ARCH arm
W/jxcore-log( 3760): 
,D/MtpService( 3201): starting MTP server in PTP mode
D/LGMtpServer( 3201): LGMtpServer
D/LGMtpServerJNI( 3201): android_mtp_LGMtpServer_setup
,D/MtpService( 3201): addStorageLocked 65537 /storage/emulated/0
E/MtpStorageEx( 3201): setAccessCapability false
D/MtpServerEx( 3201): ANR FIX - addStorage!
D/LGMtpServerJNI( 3201): android_mtp_LGMtpServer_run
V/DownloadManager( 3201): DownloadService onDestroy
,V/MediaScannerClient( 3201): [MediaScanner]setLocale: = en_US
,I/jxcore-log( 3760): JXcore Cordova bridge is ready!
I/jxcore-log( 3760): 
W/jxcore-log( 3760): JXcore engine is started
,E/MediaFileEx( 3201): Duplicate type = AVI
E/MediaFileEx( 3201): Duplicate type = ASF
V/MediaScannerClient( 3201): [MediaScanner]setLocale: = en_US
W/MediaScanner( 3201): Error opening directory '/oem/media/', skipping: No such file or directory.
V/MediaScannerClient( 3201): [MediaScanner]setLocale: = en_US
W/MediaScanner( 3201): Error opening directory '/cust/OPEN_EU/media/', skipping: No such file or directory.
D/LGMediaProvider( 3201): [MediaScanner] delete() uri = content://media/internal/file
,D/LGMediaProvider( 3201): [MediaScanner] delete() completed notifyChange, uri = content://media/internal
V/MediaScannerEx( 3201): [MediaScanner] isInternalStorage : true
V/MediaScannerEx( 3201): [MediaScanner] isInternalStorage : true
V/MediaScannerEx( 3201): [MediaScanner] isInternalStorage : true
D/MediaScanner( 3201): [MediaScanner] prescan time: 134ms
D/MediaScanner( 3201): [MediaScanner] scan time: 43ms
,D/MediaScanner( 3201): [MediaScanner] postscan time: 10ms
D/MediaScanner( 3201): [MediaScanner] total time: 187ms
D/LGMediaProvider( 3201): [MediaScanner] delete() uri = content://media/none/media_scanner
I/VRBookmarkProvider( 3967): [BookmarkProvider.java:76:<init>()-[Thread:Other] BookmarkProvider
I/VRBookmarkProvider( 3967): [BookmarkProvider.java:254:onCreate()-[Thread:Other] onCreate
I/VRBookmarkProvider( 3967): [BookmarkProvider.java:504:registerObservers()-[Thread:Other] registerObservers : content://media/external/audio/media
D/VRBootCompletedReceiver( 3967): [BootCompletedReceiver.java:25:onReceive()-[Thread:Other] Controller has been started on Boot complete
D/VRBootCompletedReceiver( 3967): [BootCompletedReceiver.java:47:onReceive()-[Thread:Other] Voice Recorder launcher enable(1)/disable(2) : 1
,I/ActivityManager(  847): Killing 3581:com.lge.settings.easy/1000 (adj 15): empty #11
E/jxcore-log( 3760): >> LGE-LG-D722
E/jxcore-log( 3760): 
,I/jxcore-log( 3760): Total memory 906309632
I/jxcore-log( 3760): 
I/jxcore-log( 3760): Free memory 22781952
I/jxcore-log( 3760): 
I/jxcore-log( 3760): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3760): 
I/jxcore-log( 3760): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3760): 
I/jxcore-log( 3760): userPath [ 'www', 'www' ]
I/jxcore-log( 3760): 
I/jxcore-log( 3760): Size 720 1196
I/jxcore-log( 3760): 
,I/jxcore-log( 3760): Screen Brightness 255
I/jxcore-log( 3760): 
E/jxcore-log( 3760): Dummy Error Log.
E/jxcore-log( 3760): 
W/libprocessgroup(  847): failed to open /acct/uid_1000/pid_3581/cgroup.procs: No such file or directory
D/MediaScannerService( 3201): [MediaScanner] scan() Send Intent ACTION_MEDIA_SCANNER_FINISHED uri : file:///system/media
,I/MusicBrowser( 2710): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///system/media flg=0x10 }}
I/ActivityManager(  847): Killing 3679:com.google.android.partnersetup/u0a9 (adj 15): empty #11
D/LGMediaProvider( 3201): [MediaScanner] mUnmountReceiver ACTION_MEDIA_SCANNER_FINISHED : uri = file:///system/media, path = /system/media
I/MusicBrowser( 2710): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
D/MediaScannerService( 3201): [MediaScanner] done scanning volume internal
D/MusicBrowser( 2710): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_FINISHED
D/LGBootCompleteReceiver( 1785): onReceive : android.intent.action.BOOT_COMPLETED
D/ConfigUtils( 1785): setUsimOperator() : card operator = 
D/ConfigUtils( 1785): setUsimOperator() : result = null
,D/ConfigUtils( 1785): setUsimOperator() : simOperator = 
D/ConfigUtils( 1785): setUsimOperator() : usimoperator = 0
D/ConfigUtils( 1785): setSupportedUsimMobilityForVoLTE() : false
W/libprocessgroup(  847): failed to open /acct/uid_10009/pid_3679/cgroup.procs: No such file or directory
D/MediaScannerService( 3201): [MediaScanner] start scanning volume external: [/storage/emulated/0, /storage/external_SD]
V/LGMediaProvider( 3201): insertInternal: content://media/none/media_scanner, initValues=volume=external
D/ConfigUtils( 1785): This Model Voice Clarity Support : false
D/MediaScannerService( 3201): [MediaScanner] scan() ACTION_MEDIA_SCANNER_STARTED uri : file:///storage/emulated/0
V/LGMediaProvider( 3201): insertInternal: content://media/, initValues=name=external
,D/LGBootCompleteReceiver( 1785): onReceive : updateCallrejectNotify rejectCallOption : 1
I/MusicWidget( 2664): _mediaDataObserver onChange()
D/MediaScannerEx( 3201): [MediaScanner] scanDirectories()[0] = /storage/emulated/0
,D/MediaScannerEx( 3201): [MediaScanner] scanDirectories()[1] = /storage/external_SD
W/VRBookmarkProvider( 3967): [BookmarkProvider.java:546:onChange()-[Thread:Other] Data Change!! false url : content://media/
I/MusicBrowser( 2710): [MediaPlaybackService.java:reloadQueue()] oooooo 
D/MusicBrowser( 2710): [MediaPlaybackService.java:reloadQueue()] oooooo id=-1
D/MusicBrowser( 2710): [MediaPlaybackService.java:reloadQueue()] oooooo mCardId=-1
D/MusicBrowser( 2710): [MediaPlaybackService.java:reloadQueue()] oooooo mPreferences.id=-1
D/MusicBrowser( 2710): [MediaPlaybackService.java:reloadQueue()] oooooo q=
D/MusicBrowser( 2710): [MediaPlaybackService.java:reloadQueue()] oooooo q.length=0
D/MusicBrowser( 2710): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.queuechanged}
I/MusicBrowser( 2710): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
D/MusicBrowser( 2710): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
D/MusicBrowser( 2710): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2710): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2710): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2710): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2710): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2710): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2710): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
I/MusicWidget( 2664): beingMusicWidget_4x2() result::false
I/MusicBrowser( 2710): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2710): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
,D/MusicBrowser( 2710): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2710): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2710): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
D/MusicBrowser( 2710): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.metachanged}
I/MusicBrowser( 2710): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
I/MusicWidget( 2664): intentReceiver onReceive() action::com.lge.music.queuechanged
,D/MusicBrowser( 2710): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
D/MusicBrowser( 2710): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2710): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2710): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2710): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2710): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2710): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2710): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
D/CallRejectInfoToNotify( 1785): update : tPhoneMode : false
I/NotificationManager( 1785): com.android.phone: cancel(2131493582) by com.android.phone
I/MusicBrowser( 2710): [MediaPlaybackService.java:3426:notifyChange()] oooooo mRemoteControlClient.editMetadata :: META_CHANGED 
I/MusicBrowser( 2710): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=false}
I/MusicBrowser( 2710): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
I/MusicWidget( 2664): beingMusicWidget_4x2() result::false
I/PhoneApp( 1785): saveDefaultRingtoneUriOfOwner = content://media/internal/audio/media/55
D/MusicBrowser( 2710): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicWidget( 2664): beingMusicWidget_Quick() result::false
I/MusicBrowser( 2710): [MediaPlaybackService.java:9999:run()] oooooo AlbumImageUpdater() run :: Start
I/MusicBrowser( 2710): [MediaPlaybackService.java:10051:run()] oooooo AlbumImageUpdater() run :: End
I/MusicBrowser( 2710): [MediaPlaybackService.java:updateGroupIndexData()] oooooo 
I/MusicBrowser( 2710): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicWidget( 2664): beingMusicWidget_4x1() result::true
I/MusicWidget( 2664): send mDelayedStopHandler
I/MusicWidget( 2664): intentReceiver onReceive() action::com.lge.music.metachanged
I/MusicWidget( 2664): beingMusicWidget_4x2() result::false
I/MusicWidget( 2664): beingMusicWidget_Quick() result::false
I/MusicWidget( 2664): beingMusicWidget_4x1() result::true
,I/MusicWidget( 2664): send mDelayedStopHandler
I/MusicWidget( 2664): performViewUpdater handleMessage() msg.what::3
I/MusicWidget( 2664): beingMusicWidget_Quick() result::false
I/MusicBrowser( 2710): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2710): [GroupIndexApi.java:groupingIndexDataProviderStart()] oooooo 
I/MusicBrowser( 2710): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_STARTED dat=file:///storage/emulated/0 flg=0x10 }}
I/MusicBrowser( 2710): [GroupingIndexDataProvider.java:101:doInBackground()] oooooo mIsMusicPickerMode = false
I/MusicBrowser( 2710): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 2710): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_STARTED
W/MusicBrowser( 2710): - Start trace [MusicUtils.query]---------------------------------------------------------------
W/MusicBrowser( 2710): [Line 003751] MusicUtils.java, query() : MusicUtils.query
W/MusicBrowser( 2710): [Line 003761] MusicUtils.java, isMediaScannerScanning() : MusicUtils.query
W/MusicBrowser( 2710): [Line 001991] MediaPlaybackService.java, onChange() : MusicUtils.query
W/MusicBrowser( 2710): [Line 000130] ContentObserver.java, onChange() : MusicUtils.query
W/MusicBrowser( 2710): - End   trace [MusicUtils.query]---------------------------------------------------------------
,I/ActivityManager(  847): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=3988 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/art     ( 3201): Explicit concurrent mark sweep GC freed 14763(794KB) AllocSpace objects, 6(96KB) LOS objects, 24% free, 8MB/10MB, paused 544us total 55.598ms
,V/MediaScannerClient( 3201): [MediaScanner]setLocale: = en_US
,V/DrmBroadcastReceiver( 3988): Receive ACTION_BOOT_COMPLETED
,V/DrmService( 3988): Service onCreate
D/DrmService( 3988): Received new request = 4
I/MusicWidget( 2664): performViewUpdater handleMessage() msg.what::0
I/MusicWidget( 2664): beingMusicWidget_4x1() result::true
I/MusicWidget( 2664): performUpdate()_4x1
I/MusicWidget( 2664): defaultAppWidget()_4x1
D/MediaScannerEx( 3201): [MediaScanner] beginFile() path = /storage/emulated/0/QuicksetLite Setup/data
,D/DrmServiceHandler( 3988): updateDrmPushNotification() : No notification
,D/DrmService( 3988): Completed !! request = 4
D/DrmService( 3988): Request count = 0
V/MediaScannerClient( 3201): [MediaScanner]setLocale: = en_US
W/MediaScanner( 3201): Error opening directory '/storage/external_SD/', skipping: Permission denied.
D/LGMediaProvider( 3201): [MediaScanner] delete() uri = content://media/external/file
D/LGMediaProvider( 3201): [MediaScanner] delete() completed notifyChange, uri = content://media/external
W/VRBookmarkProvider( 3967): [BookmarkProvider.java:546:onChange()-[Thread:Other] Data Change!! false url : content://media/external
W/VRBookmarkProvider( 3967): [BookmarkProvider.java:563:onChange()-[Thread:Other] EXTERNAL Change!!
W/MusicBrowser( 2710): - Start trace [MusicUtils.query]---------------------------------------------------------------
W/MusicBrowser( 2710): [Line 003751] MusicUtils.java, query() : MusicUtils.query
W/MusicBrowser( 2710): [Line 003761] MusicUtils.java, isMediaScannerScanning() : MusicUtils.query
W/MusicBrowser( 2710): [Line 001991] MediaPlaybackService.java, onChange() : MusicUtils.query
W/MusicBrowser( 2710): [Line 000130] ContentObserver.java, onChange() : MusicUtils.query
W/MusicBrowser( 2710): - End   trace [MusicUtils.query]---------------------------------------------------------------
I/iu.UploadsManager( 2301): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
,I/ActivityManager(  847): Start proc com.lge.cloudhub for broadcast com.lge.cloudhub/.service.CloudHubReceiver: pid=4008 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/DrmService( 3988): Service onDestroy
,I/MusicWidget( 2664): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2664): 4x1_currentTheme :: null
I/MusicWidget( 2664): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2664): setDefaultViewLayoutId()_4x1
V/MediaScanner( 3201): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@6def907
V/MediaScanner( 3201): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@6def907
I/MusicWidget( 2664): appWidgetViewUpdate()_4x1
D/MediaScanner( 3201): [MediaScanner] prescan time: 108ms
I/MusicWidget( 2664): linkButtons()_4x1
D/MediaScanner( 3201): [MediaScanner] scan time: 80ms
D/MediaScanner( 3201): [MediaScanner] postscan time: 58ms
D/MediaScanner( 3201): [MediaScanner] total time: 246ms
,D/LGMediaProvider( 3201): [MediaScanner] delete() uri = content://media/none/media_scanner
I/MusicWidget( 2664): pushUpdate()_4x1
I/MusicWidget( 2664): _mediaDataObserver onChange()
I/MusicWidget( 2664): beingMusicWidget_4x2() result::false
I/MusicWidget( 2664): performViewUpdater handleMessage() msg.what::1
I/MusicWidget( 2664): beingMusicWidget_4x2() result::false
D/MediaScannerService( 3201): [MediaScanner] scan() Send Intent ACTION_MEDIA_SCANNER_FINISHED uri : file:///storage/emulated/0
,I/MusicBrowser( 2710): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///storage/emulated/0 flg=0x10 }}
,D/LGMediaProvider( 3201): [MediaScanner] mUnmountReceiver ACTION_MEDIA_SCANNER_FINISHED : uri = file:///storage/emulated/0, path = /storage/emulated/0
I/MusicBrowser( 2710): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 2710): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_FINISHED
D/MediaScannerService( 3201): [MediaScanner] done scanning volume external
I/MusicBrowser( 2710): [MediaPlaybackService.java:reloadQueue()] oooooo 
D/MusicBrowser( 2710): [MediaPlaybackService.java:reloadQueue()] oooooo id=-1
D/MusicBrowser( 2710): [MediaPlaybackService.java:reloadQueue()] oooooo mCardId=-1
D/MusicBrowser( 2710): [MediaPlaybackService.java:reloadQueue()] oooooo mPreferences.id=-1
D/MusicBrowser( 2710): [MediaPlaybackService.java:reloadQueue()] oooooo q=
D/MusicBrowser( 2710): [MediaPlaybackService.java:reloadQueue()] oooooo q.length=0
D/MusicBrowser( 2710): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.queuechanged}
,I/MusicBrowser( 2710): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
D/MusicBrowser( 2710): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
D/MusicBrowser( 2710): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2710): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2710): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2710): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2710): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2710): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2710): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
I/MusicWidget( 2664): intentReceiver onReceive() action::com.lge.music.queuechanged
I/MusicWidget( 2664): beingMusicWidget_4x2() result::false
I/MusicWidget( 2664): beingMusicWidget_Quick() result::false
I/MusicBrowser( 2710): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicWidget( 2664): beingMusicWidget_4x1() result::true
I/MusicBrowser( 2710): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
I/MusicWidget( 2664): send mDelayedStopHandler
I/MusicWidget( 2664): performViewUpdater handleMessage() msg.what::3
I/MusicWidget( 2664): beingMusicWidget_Quick() result::false
D/MusicBrowser( 2710): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2710): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2710): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
D/MusicBrowser( 2710): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.metachanged}
I/MusicBrowser( 2710): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
D/MusicBrowser( 2710): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
D/MusicBrowser( 2710): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2710): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2710): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2710): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2710): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2710): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2710): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
,I/MusicWidget( 2664): intentReceiver onReceive() action::com.lge.music.metachanged
I/MusicBrowser( 2710): [MediaPlaybackService.java:3426:notifyChange()] oooooo mRemoteControlClient.editMetadata :: META_CHANGED 
I/MusicBrowser( 2710): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=false}
I/MusicBrowser( 2710): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
I/MusicWidget( 2664): beingMusicWidget_4x2() result::false
I/MusicWidget( 2664): beingMusicWidget_Quick() result::false
D/MusicBrowser( 2710): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicWidget( 2664): beingMusicWidget_4x1() result::true
I/MusicWidget( 2664): send mDelayedStopHandler
I/MusicWidget( 2664): performViewUpdater handleMessage() msg.what::3
I/MusicWidget( 2664): beingMusicWidget_Quick() result::false
I/MusicBrowser( 2710): [MediaPlaybackService.java:updateGroupIndexData()] oooooo 
I/MusicBrowser( 2710): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2710): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2710): [GroupIndexApi.java:groupingIndexDataProviderStart()] oooooo 
I/MusicBrowser( 2710): [MediaPlaybackService.java:9999:run()] oooooo AlbumImageUpdater() run :: Start
I/MusicBrowser( 2710): [MediaPlaybackService.java:10051:run()] oooooo AlbumImageUpdater() run :: End
I/MusicBrowser( 2710): [GroupingIndexDataProvider.java:101:doInBackground()] oooooo mIsMusicPickerMode = false
I/iu.UploadsManager( 2301): End new media; added: 0, uploading: 0, time: 107 ms
,I/ActivityManager(  847): Killing 3725:com.android.providers.calendar/u0a14 (adj 15): empty #11
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1912): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1912): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,W/libprocessgroup(  847): failed to open /acct/uid_10014/pid_3725/cgroup.procs: No such file or directory
I/QCNEJ   ( 1874): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1874): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 19:10:12.103 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/CloudHub( 4008): [DATABASE][DBConnection|open] open database
,E/CloudHub( 4008): [DATABASE][DBConnection|getUserId] User id: 0
E/CloudHub( 4008): [DATABASE][DBConnection|getDatabasePath] Database path: /data/user/0/com.lge.cloudhub/databases/cloudhub.db
V/CloudHub( 4008): [SERVICE][CloudHubReceiver|queryUploadCount] # of contents to upload: 0
,I/ActivityManager(  847): Waited long enough for: ServiceRecord{63a59f2 u0 com.lge.sizechangable.musicwidget.widget/.service.MusicWidgetUpdater}
V/DownloadManager( 3201): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3201): created cursor android.database.sqlite.SQLiteCursor@3f3a5a34 on behalf of 4008
V/CloudHub( 4008): [SERVICE][CloudHubReceiver|queryDownloadCount] # of contents to download: 0
I/VRBookmarkProvider( 3967): [BookmarkProvider.java:530:handleMessage()-[Thread:Other] -- syncTable() START --
,I/MusicWidget( 2664): performViewUpdater handleMessage() msg.what::0
I/MusicWidget( 2664): beingMusicWidget_4x1() result::true
I/MusicWidget( 2664): performUpdate()_4x1
,I/MusicWidget( 2664): defaultAppWidget()_4x1
I/MusicWidget( 2664): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2664): 4x1_currentTheme :: null
I/MusicWidget( 2664): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2664): setDefaultViewLayoutId()_4x1
I/jxcore-log( 3760): getBuffer is called!!!!
I/jxcore-log( 3760): 
I/MusicWidget( 2664): appWidgetViewUpdate()_4x1
I/MusicWidget( 2664): linkButtons()_4x1
,I/ActivityManager(  847): Start proc com.lge.gnss.airtest for broadcast com.lge.gnss.airtest/.GnssAirTestReceiver: pid=4029 uid=10054 gids={50054, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  847): Killing 3778:com.lge.lgdmsclient/1000 (adj 15): empty #11
,I/art     (  298): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 25.564ms
,I/art     (  298): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 312us total 21.295ms
,I/art     (  847): Explicit concurrent mark sweep GC freed 18866(881KB) AllocSpace objects, 2(126KB) LOS objects, 33% free, 23MB/34MB, paused 2.253ms total 181.828ms
I/art     (  298): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 297us total 21.720ms
,W/libprocessgroup(  847): failed to open /acct/uid_1000/pid_3778/cgroup.procs: No such file or directory
,I/MusicWidget( 2664): pushUpdate()_4x1
I/MusicWidget( 2664): performViewUpdater handleMessage() msg.what::1
I/VRBookmarkProvider( 3967): [BookmarkProvider.java:532:handleMessage()-[Thread:Other] -- syncTable() END --
,I/MusicWidget( 2664): beingMusicWidget_4x2() result::false
D/AirTest ( 4029): Set airtest_enable to false
,I/ActivityManager(  847): Killing 2092:com.google.process.gapps/u0a6 (adj 15): empty #11
I/[LgeWidgetLib]LgeAppWidgetHostView( 1912): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1912): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/libprocessgroup(  847): failed to open /acct/uid_10006/pid_2092/cgroup.procs: No such file or directory
,V/LGSC    ( 2763): [104] 401
I/ActivityManager(  847): Start proc com.lge.lgfota.permission for broadcast com.lge.lgfota.permission/.DmcTargetValidationReceiver: pid=4048 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/TARGETVALIDLATION_RECEIVER( 4048): TargetValidationReceiver_ACTION_BOOT_COMPLETETED Received
D/TARGETVALIDLATION_RECEIVER( 4048): updateFlag = new File(TARGET_FLAG_PATH)
,D/TARGETVALIDLATION_RECEIVER( 4048): Do Not display result dialog. it is not used Update Tool!!
I/ActivityManager(  847): Killing 3800:com.lge.clock/u0a10 (adj 15): empty #11
I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,W/libprocessgroup(  847): failed to open /acct/uid_10010/pid_3800/cgroup.procs: No such file or directory
V/LGSC    ( 1785): [101] 102, action=android.intent.action.BOOT_COMPLETED, iccState=null
,W/ContextImpl( 2819): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.qualcomm.atfwd.AtFwdAutoboot.onReceive:24 android.app.ActivityThread.handleReceiver:2663 
,E/AtFwd AutoBoot( 2819): AtFwd Auto Boot Started Successfully
I/ActivityManager(  847): Start proc com.google.process.gapps for broadcast com.google.android.syncadapters.contacts/.ContactsSyncAdapterBroadcastReceiver: pid=4068 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/GservicesProvider( 4068): Gservices pushing to system: true; secure/global: true
,I/GoogleHttpClient( 4068): GMS http client unavailable, use old client
,I/GoogleHttpClient( 4068): GMS http client unavailable, use old client
,I/GoogleHttpClient( 4068): GMS http client unavailable, use old client
,I/ActivityManager(  847): Start proc com.lge.defaultaccount for broadcast com.lge.defaultaccount/.receiver.ReceiverBootUp: pid=4091 uid=10062 gids={50062, 9997} abi=armeabi-v7a
,I/InsertAccount( 4091): The account already exists
,I/ActivityManager(  847): Start proc com.lge.hiddenmenu for broadcast com.lge.hiddenmenu/.kddi_only.sms_setting.AssistReceiver: pid=4109 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  847): Killing 3850:com.lge.appbox.client:SingleBinaryService/u0a11 (adj 15): empty #11
W/libprocessgroup(  847): failed to open /acct/uid_10011/pid_3850/cgroup.procs: No such file or directory
,I/ActivityManager(  847): Killing 3873:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/ResourcesManager( 4109): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4109): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/libprocessgroup(  847): failed to open /acct/uid_10011/pid_3873/cgroup.procs: No such file or directory
I/InsertAccount( 4091): The account info in contact DB already exists
,I/[SMS_AD]( 4109): Intent action: android.intent.action.BOOT_COMPLETED
,I/ActivityManager(  847): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4126 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/[SMS_AD]( 4109): Intent action: android.intent.action.BOOT_COMPLETED
,I/ActivityManager(  847): Killing 3257:com.android.settings/1000 (adj 15): empty #11
W/libprocessgroup(  847): failed to open /acct/uid_1000/pid_3257/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2693): 2 : onReceive, action: android.intent.action.BOOT_COMPLETED, Time(hour:min:sec) 19:10:13
I/ActivityManager(  847): Killing 3939:com.android.managedprovisioning/u0a111 (adj 15): empty #11
W/libprocessgroup(  847): failed to open /acct/uid_10111/pid_3939/cgroup.procs: No such file or directory
,D/UpdateThreadPoolManager( 2693): 2 : This is isUpdating : false
D/Weather_cast( 2693): 2 : set auto-update time : 1/8 22:10
D/WeatherAncestor( 2693): 2 : onReceive has processed, action: android.intent.action.BOOT_COMPLETED, Time(hour:min:sec) 19:10:13
D/WeatherService( 2693): 2 : onStartCommand, intent!=null, action: android.intent.action.BOOT_COMPLETED
W/ResourcesManager( 4126): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/ActivityManager(  847): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.LockSettingsReceiver: pid=4147 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  847): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2693): 2 : Utils getTopActivity com.lge.launcher2 / true
D/CalendarProvider2( 4126): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@10711041
D/WeatherService( 2693): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2693): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/CalendarProvider2( 4126): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 4126): Created com.android.providers.calendar.CalendarAlarmManager@290ebe72(com.android.providers.calendar.CalendarProvider2@10711041)
,I/InsertAccount( 4091): The account info in calendar DB already exists
I/Process ( 4091): Sending signal. PID: 4091 SIG: 9
,I/LockScreenSettings( 4147): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/ActivityManager(  847): Process com.lge.defaultaccount (pid 4091) has died
I/LockScreenSettings( 4147): Received Broadcast : android.intent.action.BOOT_COMPLETED
,I/ActivityManager(  847): Start proc com.lge.springcleaning for broadcast com.lge.springcleaning/.receiver.BootCompleteReceiver: pid=4166 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/BootCompleteReceiver( 4166): hasclipTray = true
,W/ContextImpl( 4166): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.springcleaning.receiver.BootCompleteReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2663 
I/ActivityManager(  847): Start proc com.lge.springcleaning:AppCleanupService for service com.lge.springcleaning/.service.AppCleanupService: pid=4183 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  847): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4200 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  847): Killing 3967:com.lge.voicerecorder/u0a34 (adj 15): empty #11
W/libprocessgroup(  847): failed to open /acct/uid_10034/pid_3967/cgroup.procs: No such file or directory
,V/AppCleanupService( 4183): registerAlarm
,D/AppCleanupService( 4183): noticeInterval = 2678399999
D/AppCleanupService( 4183): notiDateStr = 2016-01-20 22:41:42
,D/AppCleanupService( 4183): noticeStart = 2016-01-20 22:41:42
D/AppCleanupService( 4183): noticeStart = 1453326102000
D/AppUsageDbAdapter( 4183): initPreloadedAppToTheDB() : row count = 178
,E/UpdateRequestReceiver( 4200): ignoring update request
,E/UpdateRequestReceiver( 4200): ignoring update request
E/UpdateRequestReceiver( 4200): ignoring update request
,E/UpdateRequestReceiver( 4200): ignoring update request
E/UpdateRequestReceiver( 4200): ignoring update request
E/UpdateRequestReceiver( 4200): ignoring update request
,I/ActivityManager(  847): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseSIMObserver: pid=4235 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  847): Killing 2301:com.google.android.gms/u0a6 (adj 15): empty #11
D/ConnectivityService(  847): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@2a75caea)
,D/ConnectivityService(  847): dumpNetworkRequest
D/ConnectivityService(  847):     NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/ConnectivityService(  847):     Requests:
D/ConnectivityService(  847):         NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  847):         NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  847):         NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  847):     Lingered:
D/ConnectivityService(  847): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  847): sending notification RELEASED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  847): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/libprocessgroup(  847): failed to open /acct/uid_10006/pid_2301/cgroup.procs: No such file or directory
,D/SIMObserver( 4235): action:android.intent.action.BOOT_COMPLETED
D/SIMObserver( 4235): handle ACTION_BOOT_COMPLETED
,I/ActivityManager(  847): Killing 3988:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  847): failed to open /acct/uid_10051/pid_3988/cgroup.procs: No such file or directory
,E/QcrilMsgTunnelAutoboot( 2321): Received Intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelAutoboot (has extras) } canStartService = false
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 55034951129; DSPS: 1901372; Offset : -2994338831
V/AlarmManager(  847): ELAPSED_WAKEUP set : Alarm{16511478 type 2 when 55025 com.android.providers.calendar} when 55025
D/PhoneInterfaceManager( 1785): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
D/PhoneInterfaceManager( 1785): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
I/ActivityManager(  847): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4257 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  847): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
V/AlarmManager(  847): RTC_WAKEUP set : Alarm{1927751 type 0 when 1451930994243 com.android.providers.contacts} when 1451930994243
V/AlarmManager(  847): RTC_WAKEUP set : Alarm{37f7c0b7 type 0 when 1452276614216 com.google.android.googlequicksearchbox} when 1452276614216
,I/art     (  298): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 303us total 27.145ms
,I/art     (  298): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 21.136ms
I/art     (  298): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 21.907ms
,W/art     ( 2004): Suspending all threads took: 6.484ms
W/ResourcesManager( 4257): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/art     ( 2004): Verification of void com.google.o.a.a.a.f.a(com.google.i.a.b) took 122.178ms
,I/Babel_SMS( 4257): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 4257): MmsConfig.loadMmsSettings
,I/Babel_SMS( 4257): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 4257): MmsConfig.loadFromDatabase
,E/Babel_SMS( 4257): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4257): MmsConfig.loadFromResources
E/Babel_SMS( 4257): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 4257): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 4257): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 4257): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 4257): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
,D/SensorManager( 4257): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 4257): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 4257): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 4257): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 4257): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 4257): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 4257): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 4257): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 4257): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 4257): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 4257): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 4257): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 4257): found sensor: Motion Accel, handle=46
W/Settings( 4257): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 4257): startup - clean
I/art     ( 4257): CheckpointMarkThreadRoots callback created = 0xb042d8c0
,I/Babel   ( 4257): deleted: false for 0
,I/art     ( 4257): CheckpointMarkThreadRoots callback created = 0xb042d8a0
,W/AudioCapabilities( 4257): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 4257): Unsupported mime audio/adpcm
W/AudioCapabilities( 4257): Unsupported mime audio/g726
W/AudioCapabilities( 4257): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 4257): Unsupported mime audio/wma-voice
W/VideoCapabilities( 4257): Unsupported mime video/mjpg
,W/VideoCapabilities( 4257): Unsupported mime video/theora
W/AudioCapabilities( 4257): Unsupported mime audio/evrc
,W/AudioCapabilities( 4257): Unsupported mime audio/qcelp
W/VideoCapabilities( 4257): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 4257): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 4257): Unsupported mime audio/qcelp
W/AudioCapabilities( 4257): Unsupported mime audio/evrc
W/VideoCapabilities( 4257): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 4257): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 4257): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4257): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4257): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4257): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 4257): onServiceConnected
,W/Babel   ( 4257): Attempted to change video mute state without an active call.
I/NotificationManager( 4257): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/ActivityManager(  847): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4303 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  847): Killing 4008:com.lge.cloudhub/u0a49 (adj 15): empty #11
,W/libprocessgroup(  847): failed to open /acct/uid_10049/pid_4008/cgroup.procs: No such file or directory
,I/QCNEJ   ( 1874): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1874): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 19:10:15.143 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/ResourcesManager( 4303): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4303): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 4303): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 4303): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4303): Installed default security provider GmsCore_OpenSSL
,W/art     ( 4303): Suspending all threads took: 14.207ms
,I/art     ( 4303): CheckpointMarkThreadRoots callback created = 0xb042dba0
,W/ResourcesManager( 4303): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4303): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  847): Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=4336 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/art     ( 4303): CheckpointMarkThreadRoots callback created = 0xb042db90
W/art     ( 4303): Suspending all threads took: 25.233ms
,E/YouTube MDX( 4303): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
W/ResourcesManager( 4336): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4336): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/libc-netbsd( 4303): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4303): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4303): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,I/MultiDex( 4336): VM with version 2.1.0 has multidex support
I/MultiDex( 4336): install
I/MultiDex( 4336): VM has multidex support, MultiDex support library is disabled.
I/dex2oat ( 4354): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads1934250594.jar --oat-fd=22 --oat-location=/data/data/com.google.android.youtube/cache/ads1934250594.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 4354): dex2oat took 170.747ms (threads: 4)
,V/JNIHelp ( 4336): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/NotificationManager( 4303): com.google.android.youtube: cancel(2) by com.google.android.youtube
,W/ActivityThread( 4336): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4336): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@c2d308a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4336): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 4336): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 4336): com.google.android.gms: cancel(39789) by com.google.android.gms
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
,W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4303): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4303): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4303): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
W/InstanceID/Rpc( 4303): Found 10006
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4303): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,D/NativeLibraryUtils( 4336): Install completed successfully. count=14 extracted=0
,D/libc-netbsd( 4303): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4303): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4303): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4303): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  271): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  847): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4426 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out( 4303): propertyValue:false
D/libc-netbsd( 4303): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4303): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/NotificationManager( 4303): com.google.android.youtube: cancel(10436) by com.google.android.youtube
I/ActivityManager(  847): Killing 4048:com.lge.lgfota.permission/1000 (adj 15): empty #11
,D/libc-netbsd( 4303): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4303): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  847): Killing 4029:com.lge.gnss.airtest/u0a54 (adj 15): empty #12
,W/libprocessgroup(  847): failed to open /acct/uid_1000/pid_4048/cgroup.procs: No such file or directory
,W/libprocessgroup(  847): failed to open /acct/uid_10054/pid_4029/cgroup.procs: No such file or directory
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  847): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2d768c02 mBinding = false
,D/BluetoothManagerService(  847): Message: 2
D/BluetoothAdapterService(327569342)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3fcae804
D/BluetoothManagerService(  847): Sending off request.
D/BluetoothAdapterService(327569342)( 2073): disable() called...
D/BluetoothAdapterService(327569342)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3fcae804
D/BluetoothAdapterState( 2073): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 2073): Setting state to 13
I/BluetoothAdapterState( 2073): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService(327569342)( 2073): updateAdapterState() - Broadcasting state to 1 receivers.
D/BluetoothAdapterService(327569342)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3fcae804
D/BluetoothManagerService(  847): Message: 60
D/BluetoothManagerService(  847): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  847): Bluetooth State Change Intent: 12 -> 13
D/WifiServiceImplEx(  847): setWifiEnabled: false pid=3760, uid=10317, package= com.example.hello, App Lable : HelloWorld
D/WifiService(  847): setWifiEnabled: false pid=3760, uid=10317
D/LocationManagerService(  847): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  847): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  847): JNI:system_update. Event-4
D/LGBluetoothAPIService( 1838): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothAdapterService(327569342)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3fcae804
D/BluetoothAdapterService(327569342)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3fcae804
I/BluetoothMapService( 2073): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 2073): STATE_TURNING_OFF
I/[SystemUI]QuickSettingsHandler( 1388): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1388): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
V/BluetoothMapService( 2073): Handler(): got msg=4
D/BluetoothMapService( 2073): MAP Service closeService in
D/BluetoothMapMasInstance( 2073): MAP Service shutdown
,I/bt-btif ( 2073): BTA_JvDeleteRecord
I/bt-btif ( 2073): BTA_JvRfcommStopServer
I/jxcore-log( 3760): ****TEST TOOK:  5115  ms ****
I/jxcore-log( 3760): 
I/jxcore-log( 3760): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3760): 
D/BluetoothAdapterProperties( 2073): onBluetoothDisable()
,I/BluetoothAdapterState( 2073): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/bt-btif ( 2073): HAL bt_hal_cbacks->adapter_properties_cb
E/WifiStateMachine(  847): WifiStateMachine: Leaving Connected state
D/LocationManagerService(  847): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  847): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  847): JNI:system_update. Event-4
E/WifiConfigStore(  847): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
V/BluetoothMapMasInstance( 2073): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 2073): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 2073): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 2073): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 2073): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 2073): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 2073): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 2073): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
D/LGBluetoothMapAdapter( 2073): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 2073): MAP Service closeService out
,D/LGWifiP2pService(  847): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,I/ActivityManager(  847): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=4448 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/BluetoothAdapterProperties( 2073): Scan Mode:20
D/BluetoothAdapterState( 2073): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
I/bt-btif ( 2073): BTIF DISABLE BLUETOOTH:: current btif_core_radio_refcount: 1, btif_core_state: 2, btif_core_cb.dut_mode: 0
E/bt-btif ( 2073): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
D/bt-btif ( 2073): btsock_ctrl_hci_cleanup(L202): poll handle:4
I/bt-btif ( 2073): BTA_JvDeleteRecord
I/bt-btif ( 2073): BTA_JvRfcommStopServer
W/bt-btif ( 2073): invalid rfc slot id: 2
D/IOP_DB_BT( 2073): db_close: nbr users 0
D/IOP_DB_BT( 2073): db_close: free database
V/BluetoothPbapService( 2073): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/CommandListener(  271): Clearing all IP addresses on wlan0
D/DhcpStateMachine(  847): RunningState{ when=-2ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 7
D/btif_config_util( 2073): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/btif_config_util( 2073): enum_config(L300): in, key:Adapter, value:BluezMigrationDone
D/btif_config_util( 2073): enum_config(L302): section name:Local, key name:Adapter, value name:BluezMigrationDone, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:Adapter, value:BluezMigrationDone
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:Adapter, value:Address
D/btif_config_util( 2073): enum_config(L302): section name:Local, key name:Adapter, value name:Address, value type:string
D/btif_config_util( 2073): enum_config(L343): out, key:Adapter, value:Address
D/btif_config_util( 2073): enum_config(L344): out, value:f8:95:c7:87:85:54
D/btif_config_util( 2073): enum_config(L300): in, key:Adapter, value:Name
D/btif_config_util( 2073): enum_config(L302): section name:Local, key name:Adapter, value name:Name, value type:string
D/btif_config_util( 2073): enum_config(L343): out, key:Adapter, value:Name
D/btif_config_util( 2073): enum_config(L344): out, value:G3s-1
D/btif_config_util( 2073): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IR
D/btif_config_util( 2073): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IR, value type:binary
D/btif_config_util( 2073): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IR
D/btif_config_util( 2073): enum_config(L344): out, value:��l:4A�O���x�x�E@=-��ӑ`-'����8�\�婓��n�ScanMode
D/btif_config_util( 2073): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IRK
D/btif_config_util( 2073): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IRK, value type:binary
D/btif_config_util( 2073): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IRK
D/btif_config_util( 2073): enum_config(L344): out, value:�E@=-��ӑ`-'����8�\�婓��n�ScanMode
D/btif_config_util( 2073): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_DHK
D/btif_config_util( 2073): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_DHK, value type:binary
D/btif_config_util( 2073): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_DHK
D/btif_config_util( 2073): enum_config(L344): out, value:��8�\�婓��n�ScanMode
D/btif_config_util( 2073): enum_config(L300): in, key:Adapter, value:ScanMode
D/btif_config_util( 2073): enum_config(L302): section name:Local, key name:Adapter, value name:ScanMode, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:Adapter, value:ScanMode
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_uti,l( 2073): enum_config(L300): in, key:Adapter, value:DiscoveryTimeout
D/btif_config_util( 2073): enum_config(L302): section name:Local, key name:Adapter, value name:DiscoveryTimeout, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:Adapter, value:DiscoveryTimeout
D/btif_config_util( 2073): enum_config(L344): out, value:x
D/btif_config_util( 2073): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_ER
D/btif_config_util( 2073): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_ER, value type:binary
D/btif_config_util( 2073): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_ER
D/btif_config_util( 2073): enum_config(L344): out, value:s!WE�(E��00:0F:F6
D/btif_config_util( 2073): enum_config(L300): in, key:AutoPairBlacklist, value:AddressBlacklist
D/btif_config_util( 2073): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:AddressBlacklist, value type:string
D/btif_config_util( 2073): enum_config(L343): out, key:AutoPairBlacklist, value:AddressBlacklist
D/btif_config_util( 2073): enum_config(L344): out, value:00:02:C7,00:16:FE,00:19:C1,00:1B:FB,00:1E:3D,00:21:4F,00:23:06,00:24:33,00:A0:79,00:0E:6D,00:13:E0,00:21:E8,00:60:57,00:0E:9F,00:12:1C,00:18:91,00:18:96,00:13:04,00:16:FD,00:22:A0,00:0B:4C,00:60:6F,00:23:3D,00:C0:59,00:0A:30,00:1E:AE,00:1C:D7,00:80:F0,00:12:8A,00:09:93,00:80:37,00:26:7E,00:06:F7,00:13:7B,00:1E:B2,00:07:04,00:13:7B,00:14:0A,00:1A:1B,00:22:4D,00:0B:24,00:1E:B2,00:0B:1F,18:6D:99,00:54:AF,18:6D:99,94:44:44,00:21:CC,04:98:F3,00:26:E8
D/btif_config_util( 2073): enum_config(L300): in, key:AutoPairBlacklist, value:ExactNameBlacklist
D/btif_config_util( 2073): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:ExactNameBlacklist, value type:string
D/btif_config_util( 2073): enum_config(L343): out, key:AutoPairBlacklist, value:ExactNameBlacklist
D/btif_config_util( 2073): enum_config(L344): out, value:Motorola IHF1000,i.TechBlueBAND,X5 Stereo v1.3,KML_CAN,Microsoft Mouse
D/btif_config_util( 2073): enum_config(L300): in, key:AutoPairBlacklist, value:PartialNameBlacklist
D/btif_config_util( 2073): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:PartialNameBlacklist, value type:string
D/btif_config_util( 2073): enum_config(L343): out, key:AutoPairBlacklist, value:PartialNameBlacklist
D/btif_config_util( 2073): enum_config(L344): out, value:BMW,Audi,Parrot,Car
D/btif_config_util( 2073): enum_config(L300): in, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
D/btif_config_util( 2073): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:FixedPinZerosKeyboardBlacklist, value type:string
D/btif_config_util( 2073): enum_config(L343): out, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
D/btif_config_util( 2073): enum_config(L344): out, value:00:0F:F6
D/btif_config_util( 2073): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Manufacturer, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpVer
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpVer, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpVer
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpSubVer, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
D/btif_config_util( 2073): enum_config(L344): out, value:�
D/btif_config_util( 2073): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Name
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Name, value type:string
D/btif_config_util( 2073): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Name
D/btif_config_util( 2073): enum_config(L344): out, value:HTC Desire 820
D/btif_config_util( 2073): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevClass
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevClass, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevClass
D/btif_config_util( 2073): enum_config(L344): out, value:Z
D/btif_config_util( 2073): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevType
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevType, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevType
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:JustWorks
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:JustWorks, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:JustWorks
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:GlobalTrust, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Service
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Service, value type:string
D/btif_config_util( 2073): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Service
D/btif_config_util( 2073): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2073): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Manufacturer
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Manufacturer, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Manufacturer
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpVer
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpVer, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpVer
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpSubVer
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpSubVer, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpSubVer
D/btif_config_util( 2073): enum_config(L344): out, value:$
D/btif_config_util( 2073): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Name
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Name, value type:string
D/btif_config_util( 2073): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Name
D/btif_config_util( 2073): enum_config(L344): out, value:Galaxy S6-1
D/btif_config_util( 2073): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevClass
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevClass, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevClass
D/btif_config_util( 2073): enum_config(L344): out, value:Z
D/btif_config_util( 2073): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevType
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevType, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevType
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:JustWorks
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:JustWorks, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:JustWorks
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:GlobalTrust
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:GlobalTrust, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:GlobalTrust
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Service
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Service, value type:string
D/btif_config_util( 2073): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Service
D/btif_config_util( 2073): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2073): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Manufacturer
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Manufacturer, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Manufacturer
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpVer
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpVer, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpVer
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpSubVer
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpSubVer, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpSubVer
D/btif_config_util( 2073): enum_config(L344): out, value:�
D/btif_config_util( 2073): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Name
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Name, value type:string
D/btif_config_util( 2073): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Name
D/btif_config_util( 2073): enum_config(L344): out, value:A5-1
D/btif_config_util( 2073): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevClass
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevClass, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevClass
D/btif_config_util( 2073): enum_config(L344): out, value:Z
D/btif_config_util( 2073): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevType
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevType, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevType
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:JustWorks
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:JustWorks, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:JustWorks
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:GlobalTrust
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:GlobalTrust, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:GlobalTrust
D/btif_config_util( 2073): enum_config(L344): out, value:
W/bt-btif ( 2073): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
D/btif_config_util( 2073): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Service
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Service, value type:string
D/btif_config_util( 2073): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Service
D/btif_config_util( 2073): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 2073): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Manufacturer
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Manufacturer, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Manufacturer
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpVer
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpVer, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpVer
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpSubVer, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
D/btif_config_util( 2073): enum_config(L344): out, value:#
D/btif_config_util( 2073): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Name
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Name, value type:string
D/btif_config_util( 2073): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Name
D/btif_config_util( 2073): enum_config(L344): out, value:Nexus 6
D/btif_config_util( 2073): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevClass
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevClass, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevClass
D/btif_config_util( 2073): enum_config(L344): out, value:Z
D/btif_config_util( 2073): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevType
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevType, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevType
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:JustWorks
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:JustWorks, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:JustWorks
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:GlobalTrust, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Service
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Service, value type:string
D/btif_config_util( 2073): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Service
D/btif_config_util( 2073): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 2073): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Manufacturer
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Manufacturer, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Manufacturer
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpVer
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpVer, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpVer
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpSubVer
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpSubVer, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpSubVer
D/btif_config_util( 2073): enum_config(L344): out, value:�
D/btif_config_util( 2073): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Name
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Name, value type:string
D/btif_config_util( 2073): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Name
D/btif_config_util( 2073): enum_config(L344): out, value:XT1072
D/btif_config_util( 2073): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevClass
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevClass, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevClass
D/btif_config_util( 2073): enum_config(L344): out, value:Z
D/btif_config_util( 2073): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevType
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevType, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevType
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:JustWorks
E/bt-btif ( 2073): btif_hf_upstreams_evt: wrong handle = 18022 
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:JustWorks, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:JustWorks,
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:GlobalTrust
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:GlobalTrust, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:GlobalTrust
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Service
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Service, value type:string
D/btif_config_util( 2073): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Service
D/btif_config_util( 2073): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2073): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Manufacturer
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Manufacturer, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Manufacturer
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpVer
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpVer, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpVer
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpSubVer, value type:int
D/OppService( 2073): Recieved MESSAGE_OPS_DISABLE
D/btif_config_util( 2073): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:DevClass
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:DevClass, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:DevClass
D/btif_config_util( 2073): enum_config(L344): out, value:Z
D/btif_config_util( 2073): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:DevType
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:DevType, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:DevType
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:JustWorks
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:JustWorks, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:JustWorks
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:GlobalTrust
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:GlobalTrust, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:GlobalTrust
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Service
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Service, value type:string
D/btif_config_util( 2073): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Service
D/btif_config_util( 2073): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 2073): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:Manufacturer
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Manufacturer, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Manufacturer
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:LmpVer
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:LmpVer, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:LmpVer
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:LmpSubVer
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:LmpSubVer, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:LmpSubVer
D/btif_config_util( 2073): enum_config(L344): out, value:	a
D/btif_config_util( 2073): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:Name
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Name, value type:string
D/btif_config_util( 2073): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Name
D/btif_config_util( 2073): enum_config(L344): out, value:Nexus 5
D/btif_config_util( 2073): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:DevClass
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:DevClass, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:DevClass
D/btif_config_util( 2073): enum_config(L344): out, value:Z
D/btif_config_util( 2073): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:DevType
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:DevType, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:DevType
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:JustWorks
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:JustWorks, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:JustWorks
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:GlobalTrust
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:GlobalTrust, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:GlobalTrust
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:Service
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Service, value type:string
D/btif_config_util( 2073): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Service
D/btif_config_util( 2073): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2073): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Manufacturer
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Manufacturer, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Manufacturer
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:LmpVer
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:LmpVer, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:LmpVer
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:LmpSubVer
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:LmpSubVer, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:LmpSubVer
D/btif_config_util( 2073): enum_config(L344): out, value:�
D/btif_config_util( 2073): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Name
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Name, value type:string
D/btif_config_util( 2073): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Name
D/btif_config_util( 2073): enum_config(L344): out, value:HTC One_M8
D/btif_config_util( 2073): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:DevClass
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:DevClass, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:DevClass
D/btif_config_util( 2073): enum_config(L344): out, value:Z
D/btif_config_util( 2073): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:DevType
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:DevType, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:DevType
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Service
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Service, value type:string
D/btif_config_util( 2073): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Service
D/btif_config_util( 2073): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 00006675-7475-7265-6469-616c62756d70 fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2073): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:JustWorks
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:JustWorks, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:JustWorks
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:GlobalTrust
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:GlobalTrust, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:GlobalTrust
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Manufacturer
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:Manufacturer, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:Manufacturer
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:LmpVer
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:LmpVer, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:LmpVer
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:LmpSubVer
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:LmpSubVer, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:LmpSubVer
D/btif_config_util( 2073): enum_config(L344): out, value:"
D/btif_config_util( 2073): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Name
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:Name, value type:string
D/btif_config_util( 2073): enum_config(L300): in, key:38:94:96:b5:06:dc, value:Manufacturer
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:Manufacturer, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:38:94:96:b5:06:dc, value:Manufacturer
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:38:94:96:b5:06:dc, value:LmpVer
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:LmpVer, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:38:94:96:b5:06:dc, value:LmpVer
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:38:94:96:b5:06:dc, value:LmpSubVer
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:LmpSubVer, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:38:94:96:b5:06:dc, value:LmpSubVer
D/btif_config_util( 2073): enum_config(L344): out, value:�
D/btif_config_util( 2073): enum_config(L300): in, key:38:94:96:b5:06:dc, value:Name
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:Name, value type:string
D/btif_config_util( 2073): enum_config(L343): out, key:38:94:96:b5:06:dc, value:Name
D/btif_config_util( 2073): enum_config(L344): out, value:Galaxy S5-2
D/btif_config_util( 2073): enum_config(L300): in, key:38:94:96:b5:06:dc, value:DevClass
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:DevClass, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:38:94:96:b5:06:dc, value:DevClass
D/btif_config_util( 2073): enum_config(L344): out, value:Z
D/btif_config_util( 2073): enum_config(L300): in, key:38:94:96:b5:06:dc, value:DevType
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:DevType, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:38:94:96:b5:06:dc, value:DevType
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:38:94:96:b5:06:dc, value:JustWorks
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:JustWorks, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:38:94:96:b5:06:dc, value:JustWorks
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:38:94:96:b5:06:dc, value:GlobalTrust
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:GlobalTrust, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:38:94:96:b5:06:dc, value:GlobalTrust
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:00:00:00:00:5a:ad, value:Manufacturer
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:Manufacturer, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:00:00:00:00:5a:ad, value:Manufacturer
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:00:00:00:00:5a:ad, value:LmpVer
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:LmpVer, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:00:00:00:00:5a:ad, value:LmpVer
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:00:00:00:00:5a:ad, value:LmpSubVer
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:LmpSubVer, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:00:00:00:00:5a:ad, value:LmpSubVer
D/btif_config_util( 2073): enum_config(L344): out, value:�
D/btif_config_util( 2073): enum_config(L300): in, key:00:00:00:00:5a:ad, value:Name
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:Name, value type:string
D/btif_config_util( 2073): enum_config(L343): out, key:00:00:00:00:5a:ad, value:Name
D/btif_config_util( 2073): enum_config(L344): out, value:A3-1
D/btif_config_util( 2073): enum_config(L300): in, key:00:00:00:00:5a:ad, value:DevClass
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:DevClass, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:00:00:00:00:5a:ad, value:DevClass
D/btif_config_util( 2073): enum_config(L344): out, value:Z
D/btif_config_util( 2073): enum_config(L300): in, key:00:00:00:00:5a:ad, value:DevType
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:DevType, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:00:00:00:00:5a:ad, value:DevType
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:00:00:00:00:5a:ad, value:JustWorks
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:JustWorks, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:00:00:00:00:5a:ad, value:JustWorks
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:00:00:00:00:5a:ad, value:GlobalTrust
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:GlobalTrust, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:00:00:00:00:5a:ad, value:GlobalTrust
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:08:00:00:00:67:53, value:DevClass
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:08:00:00:00:67:53, value name:DevClass, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:08:00:00:00:67:53, value:DevClass
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:08:00:00:00:67:53, value:DevType
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:08:00:00:00:67:53, value name:DevType, value type:int
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/btif_config_util( 2073): enum_config(L343): out, key:08:00:00:00:67:53, value:DevType
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:84:24:c0:aa:ff:ff, value:Name
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:84:24:c0:aa:ff:ff, value name:Name, value type:string
D/btif_config_util( 2073): enum_config(L343): out, key:84:24:c0:aa:ff:ff, value:Name
D/btif_config_util( 2073): enum_config(L344): out, value:$��
D/btif_config_util( 2073): enum_config(L300): in, key:84:24:c0:aa:ff:ff, value:DevClass
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:84:24:c0:aa:ff:ff, value name:DevClass, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:84:24:c0:aa:ff:ff, value:DevClass
D/btif_config_util( 2073): enum_config(L344): out, value:`��
D/btif_config_util( 2073): enum_config(L300): in, key:84:24:c0:aa:ff:ff, value:DevType
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:84:24:c0:aa:ff:ff, value name:DevType, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:84:24:c0:aa:ff:ff, value:DevType
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:a0:01:c0:b4:bc:d6, value:DevClass
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:a0:01:c0:b4:bc:d6, value name:DevClass, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:a0:01:c0:b4:bc:d6, value:DevClass
D/btif_config_util( 2073): enum_config(L344): out, value:���
D/btif_config_util( 2073): enum_config(L300): in, key:a0:01:c0:b4:bc:d6, value:DevType
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:a0:01:c0:b4:bc:d6, value name:DevType, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:a0:01:c0:b4:bc:d6, value:DevType
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:94:16:79:a0:e3:01, value:DevClass
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:94:16:79:a0:e3:01, value name:DevClass, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:94:16:79:a0:e3:01, value:DevClass
D/btif_config_util( 2073): enum_config(L344): out, value:�_
D/btif_config_util( 2073): enum_config(L300): in, key:94:16:79:a0:e3:01, value:DevType
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:94:16:79:a0:e3:01, value name:DevType, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:94:16:79:a0:e3:01, value:DevType
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:00:00:00:00:41:9e, value:Name
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:00:00:00:00:41:9e, value name:Name, value type:string
D/btif_config_util( 2073): enum_config(L343): out, key:00:00:00:00:41:9e, value:Name
D/btif_config_util( 2073): enum_config(L344): out, value:4g�
D/btif_config_util( 2073): enum_config(L300): in, key:00:00:00:00:41:9e, value:DevClass
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:00:00:00:00:41:9e, value name:DevClass, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:00:00:00:00:41:9e, value:DevClass
D/btif_config_util( 2073): enum_config(L344): out, value:��f
D/btif_config_util( 2073): enum_config(L300): in, key:00:00:00:00:41:9e, value:DevType
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:00:00:00:00:41:9e, value name:DevType, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:00:00:00:00:41:9e, value:DevType
D/btif_config_util( 2073): enum_config(L344): out, value:
D/btif_config_util( 2073): enum_config(L300): in, key:94:c6:76:a0:e3:b1, value:Name
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:94:c6:76:a0:e3:b1, value name:Name, value type:string
D/btif_config_util( 2073): enum_config(L343): out, key:94:c6:76:a0:e3:b1, value:Name
D/btif_config_util( 2073): enum_config(L344): out, value:4g�������v��
D/btif_config_util( 2073): enum_config(L300): in, key:94:c6:76:a0:e3:b1, value:DevClass
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:94:c6:76:a0:e3:b1, value name:DevClass, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:94:c6:76:a0:e3:b1, value:DevClass
D/btif_config_util( 2073): enum_config(L344): out, value:��\
I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 10
D/btif_config_util( 2073): enum_config(L300): in, key:94:c6:76:a0:e3:b1, value:DevType
D/btif_config_util( 2073): enum_config(L302): section name:Remote, key name:94:c6:76:a0:e3:b1, value name:DevType, value type:int
D/btif_config_util( 2073): enum_config(L343): out, key:94:c6:76:a0:e3:b1, value:DevType
D/btif_config_util( 2073): enum_config(L344): out, value:
I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 7
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  847): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  847): ignoring duplicate network state non-change
D/ConnectivityService(  847): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/LGWifiP2pService(  847): InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiHS20(  847): hidePasspointNotification off =false
I/QCNEJ   ( 1874): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1874): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 19:10:16.815 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1874): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20(  847): hidePasspointNotification off =false
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiScanningService(  847): SCAN_AVAILABLE : 1
D/RttService(  847): SCAN_AVAILABLE : 1
D/WifiScanningService(  847): DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  847): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
I/QCNEJ   ( 1874): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1874): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 19:10:16.86 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1874): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1388): mWifiConnected = false, mWifiLevel = 0
D/LGWifiP2pService(  847): P2pDisablingState
D/LGWifiP2pService(  847): P2pDisablingState{ when=-21ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): p2p socket connection lost
D/LGWifiP2pService(  847): P2pDisabledState
D/WfdsService( 1838): WifiP2pState is changed : false
D/WfdsService( 1838): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsJNI ( 1838): doCommand: P2P_STOP_FIND
I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1388): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1388): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1388): Remote
D/WfdsService( 1838): Set the WFDS Monitor: false
I/[SystemUI]StatusBar.NetworkController( 1388): mWifiConnected = false, mWifiLevel = 0
D/WifiNetworkAgent(  847): NetworkAgent: NetworkAgent channel lost
D/WfdsMonitor( 1838): WFDS Monitor is stopped
D/CtrlSupplicant( 1838): Received on exit socket, terminate
E/CtrlSupplicant( 1838): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsMonitor( 1838): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1838): WfdsMonitorThread is received the interrupt - closing
I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1388): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1388): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1388): Remote
I/[SystemUI]QuickSettingsHandler( 1388): Got action android.net.wifi.p2p.STATE_CHANGED at null
D/WfdsService( 1838): STATE : WfdsDisabledState - enter
D/LGWifiP2pService(  847): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1838): WFDS: Scanner is paused
D/LGWifiP2pService(  847): DefaultState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsDiscoveryStore( 1838): Clear Discovery Method Map: ScanAlwaysMode false
W/WfdsSession:Controller( 1838): DefaultState - msg [9441355] is not handled
,D/CommandListener(  271): Clearing all IP addresses on wlan0
D/ConnectivityService(  847): Default network via Wi-Fi disconnect. stop DSQN
,D/DSQN    (  847): disableDataServiceNotify
D/WifiHS20(  847): hidePasspointNotification off =false
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1388): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1874): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1874): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 19:10:16.942 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1874): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/WifiServerServiceExt(  847): WIFI_STATE_CHANGED_ACTION [0]
D/DSQN    (  847): stop dsqn bin
D/WifiServerServiceExt(  847): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  847): setSupplicantStateDISCONNECTED
I/QCNEJ   ( 1874): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
I/QCNEJ   ( 1874): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 19:10:16.945 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1874): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,W/ResourcesManager( 4448): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4448): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 4448): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4448): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 4448): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1388): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1388): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1388): Remote
I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1388): Got action android.net.wifi.WIFI_STATE_CHANGED at null
D/ConnectivityService(  847): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  847):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  847):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  847): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  847): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1388): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): Disconnected - quitting
D/CSLegacyTypeTracker(  847): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }, list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  847): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  847): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy(  847): [LG_RESTRICTED] !!!isConnected  type  :1
D/Tethering(  847): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1874): |CORE| No family connected
D/ConnectivityService(  847): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  847): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  847): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  847): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  847): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  847): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  847):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkManagementService(  847): Removing idletimer
D/TelephonyNetworkFactory-1( 1785): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Tethering(  847): MasterInitialState.processMessage what=3
D/TelephonyNetworkFactory-1( 1785):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
W/QCNEJ   ( 1874): |CORE| No family connected
I/QCNEJ   ( 1874): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
V/NetworkPolicy(  847): [LG_RESTRICTED] !!!isConnected  type  :1
I/QCNEJ   ( 1874): |CORE| sendDefaultNwMsg: default = -1
,W/Settings(  847): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TelephonyIcons( 1388): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1388): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/Netd    (  271): M: Get netlink event, ifname: p2p0 action: 4
I/Netd    (  271): M: Get netlink event, ifname: p2p0 action: 5
I/Netd    (  271): M: Get netlink event, ifname: p2p0 action: 10
I/wpa_supplicant( 2762): p2p0: CTRL-EVENT-TERMINATING 
I/wpa_supplicant( 2762): monitor socket send errors count : 1
I/wpa_supplicant( 2762): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1838-2\x00 that cannot receive messages
I/Netd    (  271): M: Get netlink event, ifname: p2p0 action: 7
,D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/wpa_supplicant( 2762): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
W/wpa_supplicant( 2762): USIM:  scard_deinit function
D/TelephonyIcons( 1388): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1388): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/IndexDatabaseHelper( 4448): Using schema version: 115
I/IndexDatabaseHelper( 4448): Index is fine
I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 4
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  847): StoppedState
D/DhcpStateMachine(  847): StoppedState{ when=-189ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/AndroidRuntime( 4465): 
D/AndroidRuntime( 4465): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4465): CheckJNI is OFF
I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 4
W/ContextImpl( 4448): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,V/BluetoothPbapReceiver( 2073): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 2073): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 2073): ***********state = 13
I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 5
I/wpa_supplicant( 2762): wlan0: CTRL-EVENT-TERMINATING 
V/BluetoothPbapReceiver( 2073): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 2073): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 2073): state: 13
,V/BluetoothPbapService( 2073): Pbap Service closeService in
V/BluetoothPbapService( 2073): successfully stopped pbap service
D/Tethering(  847): InitialState.processMessage what=4
V/BluetoothPbapService( 2073): Pbap Service closeService out
V/BluetoothPbapService( 2073): Pbap Service onDestroy
V/BluetoothPbapService( 2073): Pbap Service closeService in
V/BluetoothPbapService( 2073): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 2073): [BTUI] cleanup
D/WfdsService( 1838): Supplicant Connection state is changed : false
D/WfdsService( 1838): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1838): Set the WFDS Monitor: false
D/WfdsMonitor( 1838): WFDS Monitor is stopped
D/Tethering(  847): sendTetherStateChangedBroadcast 0, 0, 0
W/Settings( 4257): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): stopMonitoring
I/WifiServerServiceExt(  847): WIFI_STATE_CHANGED_ACTION [1]
,I/WifiServerServiceExt(  847): batteryPsActivateMsgHandler : state:0 event:1
I/QCNEJ   ( 1874): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
I/QCNEJ   ( 1874): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 19:10:17.193 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1874): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/WifiServerServiceExt(  847): batteryPsActivateMsgHandler : this is not treated
D/BluetoothManagerService(  847): Message: 20
D/BluetoothManagerService(  847): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@37a09d49:true
I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1388): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1388): Got action android.net.wifi.WIFI_STATE_CHANGED at null
,W/Settings( 1767): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/art     (  847): Explicit concurrent mark sweep GC freed 34259(1677KB) AllocSpace objects, 1(110KB) LOS objects, 33% free, 23MB/34MB, paused 5.084ms total 182.471ms
,W/ActivityManager(  847): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/BluetoothAdapterService(327569342)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3fcae804
D/BluetoothManagerService(  847): Message: 30
D/BluetoothManagerService(  847): Message: 30
,D/LocalBluetoothProfileManager( 4448): Adding local MAP profile
D/BluetoothMap( 4448): Create BluetoothMap proxy object
D/BluetoothManagerService(  847): Message: 30
D/BluetoothManagerService(  847): Message: 30
,D/LocalBluetoothProfileManager( 4448): LocalBluetoothProfileManager construction complete
D/LGBluetoothFeatureConfig( 4448):  get() - isFeatureLoaded : false
D/AndroidRuntime( 4465): Calling main entry com.android.commands.pm.Pm
D/LGBluetoothUserBindClient( 4448): [BTUI] initUserBindClient
,W/ContextImpl( 4448): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 4448): finishStartingService: stopping service
,I/ActivityManager(  847): Force stopping com.example.hello appid=10317 user=-1: uninstall pkg
I/ActivityManager(  847): Killing 3760:com.example.hello/u0a317 (adj 0): stop com.example.hello
,I/WindowState(  847): WIN DEATH: Window{2c8efb8 u0 com.example.hello/com.example.hello.MainActivity}
,D/InputDispatcher(  847): Focus left window: Window{2c8efb8 u0 com.example.hello/com.example.hello.MainActivity}
D/InputDispatcher(  847): Window went away: Window{2c8efb8 u0 com.example.hello/com.example.hello.MainActivity}
,W/PackageSettings(  847): Skipping PackageSetting{369dceb4 com.test.thalitest/10316} due to missing metadata
,D/BluetoothInputDevice( 4448): Proxy object connected
D/HidProfile( 4448): Bluetooth service connected
D/BluetoothAdapterService(327569342)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3fcae804
D/BluetoothPan( 4448): BluetoothPAN Proxy object connected
D/PanProfile( 4448): Bluetooth service connected
D/BluetoothAdapterService(327569342)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3fcae804
D/BluetoothMap( 4448): Proxy object connected
D/MapProfile( 4448): Bluetooth service connected
D/BluetoothMap( 4448): getConnectedDevices()
D/BluetoothAdapterService(327569342)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3fcae804
D/BluetoothMap( 4448): Bluetooth is Not enabled
D/LGBluetoothUserBindClient( 4448): [BTUI] onServiceConnected
I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,W/ActivityManager(  847): Force removing ActivityRecord{1f5d17c5 u0 com.example.hello/.MainActivity t220}: app died, no saved state
,W/ActivityManager(  847): Spurious death for ProcessRecord{3a9c7398 3760:com.example.hello/u0a317}, curProc for 3760: null
I/ActivityManager(  847): Force stopping com.example.hello appid=10317 user=0: pkg removed
,D/LGBluetoothAuthorization( 4448): [BTUI] cancel All Notification
I/NotificationManager( 4448): com.android.settings: cancel(17301632) by com.android.settings
,I/NotificationManager( 4448): com.android.settings: cancel(-1000001) by com.android.settings
I/NotificationManager( 4448): com.android.settings: cancel(-1000011) by com.android.settings
I/[LGHome]EVENT( 1912): [Launcher.java:5203:onStart()]onStart
I/NotificationManager( 4448): com.android.settings: cancel(-1000021) by com.android.settings
I/NotificationManager( 4448): com.android.settings: cancel(-1000031) by com.android.settings
I/NotificationManager( 4448): com.android.settings: cancel(-1000041) by com.android.settings
W/bt-l2cap( 2073): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2073): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-btif ( 2073): ag scb idx 1 not allocated
E/bt-btif ( 2073): BTA AG is already disabled, ignoring ...
,W/bt_userial( 2073): select_read return size <=0:0, exiting userial_read_thread
W/bt-l2cap( 2073): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2073): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-btif ( 2073): ag scb idx 1 not allocated
E/bt-btif ( 2073): BTA AG is already disabled, ignoring ...
E/bt-btif ( 2073): bta_gattc_deregister Deregister Failedm unknown client cif
E/bt-btif ( 2073): bta_gattc_deregister Deregister Failedm unknown client cif
D/bt_hwcfg( 2073): hw_epilog_process
I/bt_userial_vendor( 2073): device fd = 70 close
I/Gmail   ( 4426): getAccountsCursor
D/BluetoothPermissionRequest( 4448): onReceive
D/KeyguardModel( 1388): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
D/LGBluetoothAuthorization( 4448): [BTUI] cancel All Notification
I/NotificationManager( 4448): com.android.settings: cancel(17301632) by com.android.settings
,E/bt_vendor( 2073): [BTUI] Proto is enabled. Set Proto disable!!
I/NotificationManager( 4448): com.android.settings: cancel(-1000001) by com.android.settings
I/NotificationManager( 4448): com.android.settings: cancel(-1000011) by com.android.settings
,I/NotificationManager( 4448): com.android.settings: cancel(-1000021) by com.android.settings
I/NotificationManager( 4448): com.android.settings: cancel(-1000031) by com.android.settings
I/NotificationManager( 4448): com.android.settings: cancel(-1000041) by com.android.settings
W/GeofencerStateMachine( 1767): Ignoring removeGeofence because network location is disabled.
I/[SystemUI]QSlideListController( 1388): onReceive = android.intent.action.PACKAGE_REMOVED
I/InputReader(  847): Reconfiguring input devices.  changes=0x00000010
I/[LGHome]EVENT( 1912): [Launcher.java:776:onResume()]onResume
,I/QCNEJ   ( 1874): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
D/KeyguardModel( 1388): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1388): createShortcutInfo...
,D/KeyguardModel( 1388): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1388): createShortcutInfo...
V/BluetoothOppReceiver( 2073): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
W/ResourceType( 1388): No package identifier when getting value for resource number 0x00000000
W/System.err( 3630): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
D/BluetoothOppNotification( 2073): [BTUI] cancel opp incoming file confirm notification
I/NotificationManager( 2073): com.android.bluetooth: cancel(-1) by com.android.bluetooth
W/System.err( 3630): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3630): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3630): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3630): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3630): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3630): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3630): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3630): 	at java.lang.reflect.Method.invoke(Native Method)
,W/System.err( 3630): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3630): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3630): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/[LGHome]LGActivityUtil( 1912): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/BluetoothOppNotification( 2073): [BTUI] cancel opp active transfer file notification
I/NotificationManager( 2073): com.android.bluetooth: cancel(-1) by com.android.bluetooth
W/PackageManager( 1388): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1388): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1388): createShortcutInfo...
I/[LGHome]EVENT( 1912): [Launcher.java:929:onResume()]onResume end
I/Activity( 1912): Activity.onPostResume() called 
W/ResourceType( 1388): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1388): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1388): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1388): createShortcutInfo...
V/BluetoothSapReceiver( 2073): [BTUI] checkServiceStart
D/LGBluetoothStateChangeReceiver( 2073): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
,W/ResourceType( 1388): No package identifier when getting value for resource number 0x00000000
,W/PackageManager( 1388): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1388): package = com.lge.camera, class = com.lge.camera.CameraApp
I/GKI_LINUX( 2073): GKI_destroy_task(0): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
D/KeyguardModel( 1388): createShortcutInfo...
I/art     ( 1820): CheckpointMarkThreadRoots callback created = 0xaaf1fb60
I/GKI_LINUX( 2073): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 2073): GKI_destroy_task(): task [BTU] terminated
I/bt-btif ( 2073): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 2073): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterService( 2073): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2073): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService( 2073): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
V/GLSActivity( 1767): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1388): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 1388): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/SystemUI[Framework](  847): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
D/InputDispatcher(  847): Focus entered window: Window{29a42129 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/PhoneWindowManagerEx(  847): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  847): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  847): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  847): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3a41bd5e,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  847): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,D/BtSettings.ProfileConfig( 2073): Unable to read settings
D/BtSettings.ProfileConfig( 2073): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2073): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 2073): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 2073): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 2073): 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
D/BtSettings.ProfileConfig( 2073): 	at com.android.bluetooth.btservice.AdapterService.stopProfileServices(AdapterService.java:738)
D/BtSettings.ProfileConfig( 2073): 	at com.android.bluetooth.btservice.AdapterState$PendingCommandState.processMessage(AdapterState.java:529)
D/BtSettings.ProfileConfig( 2073): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 2073): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 2073): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 2073): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 2073): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BluetoothAdapterService( 2073): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService(327569342)( 2073): setProfileServiceState() - Stopping service com.android.bluetooth.hfp.HeadsetService
W/[LGHome]LGWallpaperInfo( 1912): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1912): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
I/ActivityManager(  847): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=4509 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/[LGHome]EVENT( 1912): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1912): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1912): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
D/KeyguardModel( 1388): handleShortcutListChanged...
I/[LGHome]EVENT( 1912): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
D/BluetoothAdapterService( 2073): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2073): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService( 2073): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
I/art     ( 1820): CheckpointMarkThreadRoots callback created = 0xaaf4d400
D/administrator(  847): Handling package changes for user 0
,D/HeadsetService( 2073): Received stop request...Stopping profile...
,I/LGBluetoothHfpAdapter( 2073): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 2073): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 2073): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13864fbe
D/HeadsetStateMachine( 2073): Exit Disconnected: -1
W/BluetoothAdapterService( 2073): Not skipping com.android.bluetooth.a2dp.A2dpService
I/PhoneWindow( 1912): [setNavigationBarColor] color=0x 0
D/BluetoothAdapterService(327569342)( 2073): setProfileServiceState() - Stopping service com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService( 2073): getQuietmodeRadioCount = 0
,W/BluetoothAdapterService( 2073): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2073): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 2073): Not skipping com.android.bluetooth.hid.HidService
D/BluetoothAdapterService(327569342)( 2073): setProfileServiceState() - Stopping service com.android.bluetooth.hid.HidService
D/BluetoothHeadset( 1785): Proxy object disconnected
D/BluetoothHeadset( 1785): Proxy object disconnected
D/BluetoothHeadset( 1785): Proxy object disconnected
D/BluetoothAdapterService( 2073): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2073): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 2073): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 2073): Not skipping com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService(327569342)( 2073): setProfileServiceState() - Stopping service com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService(327569342)( 2073): handleMessage() - Message: 1
D/BluetoothAdapterService(327569342)( 2073): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(327569342)( 2073): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BluetoothAdapterState( 2073): isTurningOnRadio()=false
D/BluetoothAdapterState( 2073): isTurningOffRadio()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2073): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
,D/BluetoothAdapterService( 2073): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2073): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BluetoothAdapterService( 2073): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.android.bluetooth.pan.PanService
D/BluetoothAdapterService( 2073): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(327569342)( 2073): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/A2dpService( 2073): Received stop request...Stopping profile...
W/BluetoothAdapterService( 2073): Not skipping com.android.bluetooth.pan.PanService
D/BluetoothAdapterService(327569342)( 2073): setProfileServiceState() - Stopping service com.android.bluetooth.pan.PanService
D/A2dpStateMachine( 2073): Exit Disconnected: -1
D/BluetoothAdapterService( 2073): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2073): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 2073): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 2073): Not skipping com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(327569342)( 2073): setProfileServiceState() - Stopping service com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 2073): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2073): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2073): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 2073): Not skipping com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService(327569342)( 2073): setProfileServiceState() - Stopping service com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2073): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2073): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 2073): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 2073): Not skipping com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(327569342)( 2073): setProfileServiceState() - Stopping service com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 2073): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2073): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService( 2073): getQuietmodeRadioCount = 0
D/LGBluetoothA2dpAdapter( 2073): [BTUI] LGBluetoothA2dpAdapter cleanup
D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/LGBluetoothA2dpServiceJni( 2073): Cleaning up Bluetooth Handsfree callback object
D/LGBluetoothPowerControlManager( 2073): [BTUI] terminate
W/BluetoothAdapterService( 2073): Not skipping com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(327569342)( 2073): setProfileServiceState() - Stopping service com.broadcom.bt.service.ftp.FTPService
D/BluetoothManagerService(  847): Message: 31
D/BluetoothAdapterService( 2073): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2073): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2073): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 2073): Not skipping com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(327569342)( 2073): setProfileServiceState() - Stopping service com.broadcom.bt.service.opp.OppService
D/KeyguardModel( 1388): package = com.android.contacts, c,lass = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1388): createShortcutInfo...
D/BluetoothAdapterService( 2073): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13864fbe
D/BluetoothAdapterState( 2073): Stopping profile services that were post enabled
,D/HidService( 2073): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2073): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13864fbe
D/HeadsetStateMachine( 2073): Unbinding service...
D/BluetoothInputDevice( 4448): Proxy object disconnected
D/HidProfile( 4448): Bluetooth service disconnected
D/HeadsetPhoneState( 2073): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 2073): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 2073): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 2073): [BTUI] listenForMultiSimPhoneState : start = false
D/KeyguardModel( 1388): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1388): createShortcutInfo...
W/BluetoothHeadsetServiceJni( 2073): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2073): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 2073): [BTUI] LGBluetoothHfpAdapter cleanup
W/ResourceType( 1388): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1388): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1388): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1388): createShortcutInfo...
,D/HealthService( 2073): Received stop request...Stopping profile...
W/ResourceType( 1388): No package identifier when getting value for resource number 0x00000000
D/BluetoothAdapterService( 2073): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13864fbe
W/PackageManager( 1388): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/PanService( 2073): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2073): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13864fbe
D/KeyguardModel( 1388): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1388): createShortcutInfo...
D/BtGatt.DebugUtils( 2073): handleDebugAction() action=null
D/BtGatt.GattService( 2073): Received stop request...Stopping profile...
D/BtGatt.GattService( 2073): stop()
D/BtGatt.AdvertiseManager( 2073): advertise clients cleared
D/LGBluetoothGattAdapter( 2073): [BTUI] LGBluetoothGattAdapter cleanup
D/BluetoothAdapterService( 2073): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13864fbe
D/BluetoothMapService( 2073): Received stop request...Stopping profile...
D/BluetoothMapService( 2073): stop()
,W/ResourceType( 1388): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1388): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/BluetoothMapEmailAppObserver( 2073): deinitObservers()
D/BluetoothMapEmailAppObserver( 2073): removeReceiver()
D/BluetoothAdapterService( 2073): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13864fbe
D/SapService( 2073): Received stop request...Stopping profile...
D/SapService( 2073): Stopping Bluetooth SapService
D/LGBluetoothSapAdapter( 2073): [BTUI] LGBluetoothSapAdapter cleanup
D/LGBluetoothSapManager( 2073): [BTUI] terminateSapManager
,D/KeyguardModel( 1388): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1388): createShortcutInfo...
D/BluetoothPan( 4448): BluetoothPAN Proxy object disconnected
D/PanProfile( 4448): Bluetooth service disconnected
,D/BluetoothMap( 4448): Proxy object disconnected
D/MapProfile( 4448): Bluetooth service disconnected
D/BluetoothAdapterService( 2073): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13864fbe
D/**BluetoothFTPService( 2073): Received stop request...Stopping profile...
D/**BluetoothFTPService( 2073): Stopping Bluetooth FTP Service
V/BluetoothFTPServiceJni( 2073): closeFtpServerNative
D/LgeBluetoothSimManager( 1785): [BTUI] SAP_DISABLE_EVT
D/BluetoothAdapterService( 2073): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13864fbe
D/**OppService( 2073): Received stop request...Stopping profile...
D/OppService( 2073): Stopping Bluetooth OppService
D/OppService( 2073): cleanup OPP Service
W/BluetoothOPPServiceJni( 2073): Cleaning up Bluetooth Opp Interface...
W/BluetoothOPPServiceJni( 2073): Cleaning up Bluetooth OPP callback object
D/OppService( 2073): remove callbacks and handler
D/LGBluetoothOppAdapter( 2073): [BTUI] LGBluetoothOppAdapter cleanup
D/OppService( 2073): cleanup done
D/BluetoothAdapterService( 2073): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13864fbe
D/BluetoothAdapterService(327569342)( 2073): handleMessage() - Message: 1
D/BluetoothAdapterService(327569342)( 2073): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(327569342)( 2073): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BluetoothAdapterState( 2073): isTurningOnRadio()=false
D/BluetoothAdapterState( 2073): isTurningOffRadio()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2073): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2073): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(327569342)( 2073): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
I/BluetoothA2dpServiceJni( 2073): cleanupNative
I/GKI_LINUX( 2073): GKI_destroy_task(2): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 2073): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 2073): GKI_destroy_task(): task [A2DP-MEDIA] terminated
,D/KeyguardModel( 1388): handleShortcutListChanged...
D/BluetoothAdapterService(327569342)( 2073): handleMessage() - Message: 1
D/BluetoothAdapterService(327569342)( 2073): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(327569342)( 2073): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BluetoothAdapterState( 2073): isTurningOnRadio()=false
D/BluetoothAdapterState( 2073): isTurningOffRadio()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2073): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2073): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(327569342)( 2073): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothHidServiceJni( 2073): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 2073): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService(327569342)( 2073): handleMessage() - Message: 1
D/BluetoothAdapterService(327569342)( 2073): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(327569342)( 2073): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BluetoothAdapterState( 2073): isTurningOnRadio()=false
D/BluetoothAdapterState( 2073): isTurningOffRadio()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2073): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2073): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(327569342)( 2073): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothHealthServiceJni( 2073): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2073): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 2073): Cleaning up Bluetooth Health object
D/BluetoothAdapterService(327569342)( 2073): handleMessage() - Message: 1
D/BluetoothAdapterService(327569342)( 2073): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(327569342)( 2073): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BluetoothAdapterState( 2073): isTurningOnRadio()=false
D/BluetoothAdapterState( 2073): isTurningOffRadio()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2073): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2073): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(327569342)( 2073): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothPanServiceJni( 2073): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2073): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterService(327569342)( 2073): handleMessage() - Message: 1
D/BluetoothAdapterService(327569342)( 2073): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapt,erService(327569342)( 2073): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=true
D/BluetoothAdapterState( 2073): isTurningOnRadio()=false
D/BluetoothAdapterState( 2073): isTurningOffRadio()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2073): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2073): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(327569342)( 2073): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
V/BluetoothMapService( 2073): Handler(): got msg=4
D/BluetoothMapService( 2073): MAP Service closeService in
D/LGBluetoothMapAdapter( 2073): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 2073): MAP Service closeService out
D/BluetoothAdapterService(327569342)( 2073): handleMessage() - Message: 1
D/BluetoothAdapterService(327569342)( 2073): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(327569342)( 2073): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BluetoothAdapterState( 2073): isTurningOnRadio()=false
D/BluetoothAdapterState( 2073): isTurningOffRadio()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2073): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2073): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(327569342)( 2073): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothMapService( 2073): cleanup()
D/BluetoothMapService( 2073): MAP Service closeService in
D/LGBluetoothMapAdapter( 2073): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 2073): MAP Service closeService out
D/BluetoothAdapterService(327569342)( 2073): handleMessage() - Message: 1
D/BluetoothAdapterService(327569342)( 2073): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(327569342)( 2073): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
D/BluetoothAdapterState( 2073): isTurningOnRadio()=false,
D/BluetoothAdapterState( 2073): isTurningOffRadio()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2073): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2073): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(327569342)( 2073): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothSAPServiceJni( 2073): ## WARNING : cleanupNative(L223): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 2073): ## WARNING : cleanupNative(L229): Cleaning up Bluetooth SAP callback object##
D/BluetoothAdapterService(327569342)( 2073): handleMessage() - Message: 1
D/BluetoothAdapterService(327569342)( 2073): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
,D/BluetoothAdapterService(327569342)( 2073): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, doUpdate=true
D/BluetoothAdapterState( 2073): isTurningOnRadio()=false
D/BluetoothAdapterState( 2073): isTurningOffRadio()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2073): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2073): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(327569342)( 2073): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
,D/BluetoothFTPService( 2073): cleanup FTP Service
V/BluetoothFTPServiceJni( 2073): closeFtpServerNative
V/BluetoothFTPServiceJni( 2073): cleanupNative
W/BluetoothFTPServiceJni( 2073): Cleaning up Bluetooth FTP Server Interface...
W/BluetoothFTPServiceJni( 2073): Cleaning up Bluetooth FTP callback object
D/BluetoothFTPService( 2073): BluetoothFtpBinder.cleanup()
D/BluetoothFTPService( 2073): cleanup done
D/BluetoothAdapterService(327569342)( 2073): handleMessage() - Message: 1
D/BluetoothAdapterService(327569342)( 2073): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
,D/BluetoothAdapterService(327569342)( 2073): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=10, doUpdate=true
D/BluetoothAdapterState( 2073): isTurningOnRadio()=false
D/BluetoothAdapterState( 2073): isTurningOffRadio()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2073): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BluetoothAdapterService(327569342)( 2073): onProfileServiceStateChange() - All profile services stopped...
D/OppService( 2073): cleanup OPP Service
D/OppService( 2073): remove callbacks and handler
D/LGBluetoothOppAdapter( 2073): [BTUI] LGBluetoothOppAdapter cleanup
,D/OppService( 2073): cleanup done
D/BluetoothAdapterState( 2073): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2073): Setting state to 10
I/BluetoothAdapterState( 2073): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService(327569342)( 2073): updateAdapterState() - Broadcasting state to 1 receivers.
W/GAV2    ( 4426): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/BluetoothManagerService(  847): Message: 60
D/BluetoothManagerService(  847): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
,D/BluetoothManagerService(  847): Broadcasting onBluetoothStateChange(false) to 9 receivers.
I/BluetoothAdapterState( 2073): Entering OffState
D/BluetoothInputDevice( 4448): onBluetoothStateChange: up=false
D/BluetoothMap( 4448): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1785): onBluetoothStateChange: up=false
D/BluetoothPbap( 4448): onBluetoothStateChange: up=false
D/BluetoothA2dp(  847): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1785): onBluetoothStateChange: up=false
D/BluetoothPan( 4448): onBluetoothStateChange on: false
D/BluetoothHeadset(  847): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1785): onBluetoothStateChange: up=false
D/BluetoothAdapterService(327569342)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3fcae804
D/BluetoothManagerService(  847): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  847): Broadcasting onBluetoothServiceDown() to 8 receivers.
D/BluetoothManagerService(  847): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService(  847): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService(  847): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2d768c02 mBinding = false
,D/BluetoothManagerService(  847): Sending unbind request.
D/BluetoothManagerService(  847): Bluetooth State Change Intent: 13 -> 10
D/BluetoothAdapterService(327569342)( 2073): onUnbind() - calling cleanup
D/LGBluetoothAPIService( 1838): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1838): Message: 2
D/BluetoothAdapter( 1388): 1038759773: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1388): 1038759773: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapterService(327569342)( 2073): cleanup()
D/LGBluetoothAPIService( 1838): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@933e685 mBinding = false
D/LGBluetoothAPIService( 1838): Sending unbind request.
D/BluetoothAdapterService(327569342)( 2073): cleanup() - Cleaning up adapter native
,I/bt-btif ( 2073): btif_shutdown_bluetooth()::btif_core_cb: state: 0, is_radio_req: 0, radio_ref_count: 0, dut_mode: 0, shutdown_pending: 0
I/GKI_LINUX( 2073): GKI_destroy_task(1): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/bt-btif ( 2073): HAL bt_hal_cbacks->thread_evt_cb
I/GKI_LINUX( 2073): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 2073): GKI_destroy_task(): task [BTIF] terminated
I/GKI_LINUX( 2073): GKI_destroy_task(2): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 2073): GKI_destroy_task(1): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 2073): GKI_destroy_task(0): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 2073): GKI_exit_task 2 done
I/GKI_LINUX( 2073): GKI_exit_task 1 done
I/GKI_LINUX( 2073): GKI_exit_task 0 done
I/BluetoothServiceJni( 2073): cleanupNative: return from cleanup
W/LGBluetoothServiceJni( 2073): Cleaning up Bluetooth Service callback object
D/LGBluetoothSettingsDBObserver( 2073): [BTUI] unregister observer for LG device name DB
I/[SystemUI]QuickSettingsHandler( 1388): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1388): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
D/BluetoothAdapterService(327569342)( 2073): cleanup() - Bluetooth process exited normally.
D/BluetoothAdapterService(327569342)( 2073): cleanup() done
W/ActivityManager(  847): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/art     ( 2073): System.exit called, status: 0
I/AndroidRuntime( 2073): VM exiting with result code 0, cleanup skipped.
W/ResourcesManager( 4509): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/LGBluetoothFeatureConfig( 4448): isPrivacyLogsEnabled : true
,D/LGBluetoothUtils( 4448): [BTUI] resetProperty - success
W/ActivityManager(  847): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/LGBluetoothEventManager( 4448): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 4448): [BTUI] clear device connection state
V/AudioFlinger(  276): 2073 died, releasing its sessions
V/AudioFlinger(  276):  pid 1785 @ 0
V/AudioFlinger(  276):  pid 2710 @ 1
V/AudioFlinger(  276):  pid 3180 @ 2
V/AudioFlinger(  276):  pid 3180 @ 3
D/LGBluetoothUserBindClient( 4448): [BTUI] onServiceDisconnected
,I/ActivityManager(  847): Process com.android.bluetooth (pid 2073) has died
W/ActivityManager(  847): Scheduling restart of crashed service com.android.bluetooth/com.broadcom.fm.fmreceiver.FmService in 1000ms
W/ActivityManager(  847): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
D/FMFRW_FmProxy( 1838): Fm Proxy object disconnected
D/BluetoothAdapter( 1767): 387786021: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1767): 387786021: getState() :  mService = null. Returning STATE_OFF
I/Gmail   ( 4426): Observing account changes for notifications
,I/ActivityManager(  847): Killing 4109:com.lge.hiddenmenu/1000 (adj 15): empty #11
,I/art     (  847): Explicit concurrent mark sweep GC freed 14160(1002KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 3.012ms total 474.603ms
,D/AndroidRuntime( 4465): Shutting down VM
D/AuthorizationBluetoothService( 1767): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/libprocessgroup(  847): failed to open /acct/uid_1000/pid_4109/cgroup.procs: No such file or directory
W/ActivityManager(  847): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/InputMethodManagerService(  847): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/ContextImpl( 4448): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
W/InputMethodManagerService(  847): Got RemoteException sending setActive(false) notification to pid 3760 uid 10317
I/NotificationService(  847): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  847): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService(  847): Receieved: android.intent.action.PACKAGE_REMOVED
E/Gmail   ( 4426): Error finding the version of the Email provider.....
E/Gmail   ( 4426): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4426): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4426): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4426): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4426): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4426): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4426): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 4426): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 4426): We do not support migrating this version of the Email provider.
D/PhoneStatusBar( 1388): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
I/ActivityManager(  847): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=4540 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 1035, 4002, 1023} abi=armeabi-v7a
,D/DockEventReceiver( 4448): finishStartingService: stopping service
D/TaskPersister(  847): removeObsoleteFile: deleting file=220_task.xml
V/GLSActivity( 1767): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  847): Killing 4126:com.android.providers.calendar/u0a14 (adj 15): empty #11
I/Timeline( 1912): Timeline: Activity_idle id: android.os.BinderProxy@18f53da9 time:59236
,I/SystemUI[Framework](  847): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
D/PhoneStatusBar( 1388): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
W/PhoneWindowManagerEx(  847): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  847): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  847): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  847): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3a41bd5e,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  847): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1388): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1388):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1388): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1388): draw background and invalidate : color = f0000000
,D/BarTransitions( 1388): draw background and invalidate : color = eee5e5e5
I/HotwordRecognitionRnr( 2004): Starting hotword detection.
,I/MicrophoneInputStream( 2004): mic_starting com.google.android.apps.gsa.speech.audio.u@3c2b3968
V/AudioRecord( 2004): set(): inputSource 1999, sampleRate 16000, format 0x1, channelMask 0x10, frameCount 128000, notificationFrames 0, sessionId 0, transferType 0, flags 0
V/AudioRecord( 2004): set(): mSessionId 23
V/AudioPolicyManager(  276): getInput() inputSource 1999, samplingRate 16000, format 1, channelMask 10, session 23, flags 0
V/AudioPolicyManager(  276): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  276): isPlaybackThread 0,isRecordThread 1
D/audio_hw_primary(  276): adev_open_input_stream: enter: sample_rate(16000) channel_mask(0x10) devices(0x80000004)        stream_handle(0xb546e920)
V/audio_hw_primary(  276): adev_open_input_stream: exit
V/AudioFlinger(  276): openInput_l() openInputStream returned input 0xb546e920, SamplingRate 16000, Format 0x1, Channels 10, flags 0, status 0
V/AudioFlinger(  276): openInput_l() created record thread: ID 24 thread 0xb39ef000
V/AudioSystem(  276): ioConfigChanged() event 3, ioHandle 24
I/AudioFlinger(  276): AudioFlinger's thread 0xb39ef000 ready to run
D/audio_hw_primary(  276): in_standby: enter: stream (0xb546e920) usecase(7: audio-record)
V/audio_hw_primary(  276): in_standby: exit:  status(0)
V/AudioSystem( 1388): ioConfigChanged() event 3, ioHandle 24
V/AudioSystem( 1785): ioConfigChanged() event 3, ioHandle 24
V/AudioSystem(  847): ioConfigChanged() event 3, ioHandle 24
V/AudioPolicyService(  276): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  276): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  276): AudioCommandThread() waking up
V/AudioPolicyService(  276): AudioCommandThread() processing update audio port list
D/audio_hw_primary(  276): in_standby: enter: stream (0xb546e920) usecase(7: audio-record)
V/audio_hw_primary(  276): in_standby: exit:  status(0)
V/AudioFlinger(  276): RecordThread: loop stopping
V/AudioPolicyService(  276): AudioCommandThread() going to sleep
V/AudioSystem( 2710): ioConfigChanged() event 3, ioHandle 24
V/AudioSystem( 3180): ioConfigChanged() event 3, ioHandle 24
W/libprocessgroup(  847): failed to open /acct/uid_10014/pid_4126/cgroup.procs: No such file or directory
V/AudioSystem( 2004): ioConfigChanged() event 3, ioHandle 24
V/AudioFlinger(  276): openRecord() lSessionId: 23 input 24
V/AudioFlinger(  276): getOrphanEffectChain_l session 23 index -2
,D/LCardEmulationManager( 1820): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1820): getDefaultRoute
V/AudioFlinger(  276): acquiring 23 from 2004, for -1
V/AudioFlinger(  276):  added new entry for 23
V/AudioRecord( 2004): start, sync event 0 trigger session 0
V/AudioRecord( 2004): mAudioRecord->start()
V/AudioFlinger(  276): RecordHandle::start()
V/AudioFlinger(  276): RecordThread::start event 0, triggerSession 0
V/AudioPolicyManager(  276): startInput() module primary->input primary(24)
V/AudioPolicyManager(  276): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  276): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  276): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  276): DeviceVector::getDevicesFromType() for type 80000004 found 0xb547b280
,V/AudioPolicyService(  276): AudioCommandThread() adding create patch delay 0
V/AudioPolicyService(  276): inserting command: 7 at index 0, num commands 0
V/AudioPolicyService(  276): AudioCommandThread() waking up
V/AudioPolicyService(  276): AudioCommandThread() processing create audio patch
V/AudioFlinger::PatchPanel(  276): createAudioPatch() num_sources 1 num_sinks 1 handle 0
V/AudioFlinger::PatchPanel(  276): createAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters input_source=6;routing=-2147483644
V/AudioFlinger(  276): ThreadBase::setParameters() input_source=6;routing=-2147483644
V/AudioFlinger(  276): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  276): RecordThread: loop starting
V/AudioFlinger(  276): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  276): in_set_parameters: enter: kvpairs=input_source=6;routing=-2147483644
V/audio_hw_primary(  276): in_set_parameters: exit: status(0)
V/AudioFlinger(  276): processConfigEvents_l() DONE thread 0xb39ef000
V/AudioFlinger::PatchPanel(  276): createAudioPatch() status 0
V/AudioFlinger::PatchPanel(  276): createAudioPatch() added new patch handle 25 halHandle 0
V/AudioPolicyService(  276): AudioCommandThread() going to sleep
V/AudioPolicyManager(  276): setInputDevice() createAudioPatch returned 0 patchHandle 25
V/AudioPolicyManager(  276): addAudioPatch() handle 20 af handle 0 num_sources 1 num_sinks 1 source handle 10sink handle 19
V/AudioPolicyService(  276): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  276): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  276): AudioCommandThread() waking up
V/AudioPolicyService(  276): AudioCommandThread() adding set parameter string hotword_active=1, io 24 ,delay 0
V/AudioPolicyService(  276): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  276): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  276): AudioCommandThread() waking up
V/AudioPolicyService(  276): AudioCommandThread() processing set parameters string hotword_active=1, io 24
V/AudioPolicyService(  276): AudioCommandThread() going to sleep
V/AudioFlinger(  276): setParameters(): io 24, keyvalue hotword_active=1, calling pid 276
V/AudioFlinger(  276): ThreadBase::setParameters() hotword_active=1
V/AudioFlinger(  276): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  276): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  276): in_set_parameters: enter: kvpairs=hotword_active=1
V/audio_hw_primary(  276): in_set_parameters: exit: status(0)
V/AudioFlinger(  276): processConfigEvents_l() DONE thread 0xb39ef000
V/AudioPolicyService(  276): AudioCommandThread() going to sleep
V/AudioPolicyManager(  276): AudioPolicyManager::startInput() input source = 1999
I/MicrophoneInputStream( 2004): mic_started com.google.android.apps.gsa.speech.audio.u@3c2b3968
,V/msm8974_platform(  276): platform_update_usecase_from_source: input source :6
D/audio_hw_primary(  276): start_input_stream: enter: stream(0xb546e920)usecase(7: audio-record)
V/voice   (  276): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  276): start_input_stream: usecase(7)
E/audio_hw_primary(  276): select_devices: enter and usecase(7)
V/msm8974_platform(  276): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  276): platform_get_input_snd_device: exit: in_snd_device(voice-rec-mic)
V/msm8974_platform_lge(  276): LGE_platform_get_input_snd_device: exit: in_snd_device(lg-vr-handset-mic)
V/audio_hw_lge_primary(  276): LGE_exeption_scenario: enter and out: 0, in: 144
D/audio_hw_primary(  276): select_devices: out_snd_device(0: ) in_snd_device(144: lg-vr-handset-mic)
E/audio_hw_primary(  276): enable_snd_device: enter  144
D/hardware_info(  276): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  276): enable_snd_device: snd_device(144: lg-vr-handset-mic)
V/msm8974_platform_lge(  276): LGE_platform_send_audio_calibration: sending audio calibration for snd_Device(144) acdb_id(65)
D/ACDB-LOADER(  276): ACDB -> send_audio_cal, acdb_id = 65, path =  1
D/ACDB-LOADER(  276): ACDB -> send_adm_topology
D/ACDB-LOADER(  276): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/ACDB-LOADER(  276): ACDB -> send_asm_topology
D/ACDB-LOADER(  276): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  276): ACDB -> send_audtable
D/ACDB-LOADER(  276): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/ACDB-LOADER(  276): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  276): ACDB -> send_audvoltable
D/ACDB-LOADER(  276): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  276): Failed to fetch the lookup information of the device 00000041 
E/ACDB-LOADER(  276): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  276): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  276): ACDB -> AUDIO_SET_AFE_CAL
V/audio_hw_primary(  276): enable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  276): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  276): enable_audio_route: apply mixer and update path: audio-record
V/audio_hw_primary(  276): enable_audio_route: exit
D/audio_hw_primary(  276): select_devices: done
V/audio_hw_primary(  276): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
,V/audio_hw_primary(  276): start_input_stream: exit
W/ResourcesManager( 4540): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 4540): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4540): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/ResourcesManager( 4540): Asset path '/system/framework/com.broadcom.fm.jar' does not exist or contains no resources.
I/Gmail   ( 4426): getAccountsCursor
,V/GLSActivity( 1767): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/BluetoothAdapterApp( 4540): Loading JNI Library
,I/ActivityManager(  847): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=4569 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,W/ActivityManager(  847): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ResourcesManager(  847): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/BluetoothServiceJni( 4540): [BTUI] JNI_OnLoad : ### LGBT_USE_BDT : TRUE ###
,I/HotwordWorker( 2004): onReady
D/BluetoothAdapterApp( 4540): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@10711041 Instance Count = 1
V/GLSActivity( 1767): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BluetoothAdapterApp( 4540): onCreate
I/Timeline(  847): Timeline: Activity_windows_visible id: ActivityRecord{3361fca7 u0 com.lge.launcher2/.Launcher t219} time:59486
,W/ActivityManager(  847): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/LGBluetoothServiceJni( 4540): classInitNative: succeeds
,D/BtSettings.ProfileConfig( 4540): [BTUI] HeadsetServiceis supported
D/BtSettings.ProfileConfig( 4540): Adding HeadsetService
D/BtSettings.ProfileConfig( 4540): [BTUI] A2dpServiceis supported
,D/BtSettings.ProfileConfig( 4540): Adding A2dpService
E/ActivityThread( 4426): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@de3d52a that was originally bound here
E/ActivityThread( 4426): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@de3d52a that was originally bound here
E/ActivityThread( 4426): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 4426): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 4426): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 4426): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 4426): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4426): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4426): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4426): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4426): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4426): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4426): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4426): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4426): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4426): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4426): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 4426): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/BtSettings.ProfileConfig( 4540): [BTUI] HidServiceis supported
D/BtSettings.ProfileConfig( 4540): Adding HidService
W/ActivityManager(  847): Unbind failed: could not find connection for android.os.BinderProxy@14d9e3f6
D/BtSettings.ProfileConfig( 4540): [BTUI] HealthServiceis supported
D/BtSettings.ProfileConfig( 4540): Adding HealthService
D/LGBluetoothFeatureConfig( 4540): isSupportPan() :  mTargetOp=OPEN
W/FileUtils( 4426): Failed to chmod(/data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
I/Gmail   ( 4426): getAccountsCursor
,E/GmailIS ( 4426): Error handling intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gm/.GmailIntentService (has extras) }
E/GmailIS ( 4426): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/GmailIS ( 4426): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/GmailIS ( 4426): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/GmailIS ( 4426): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/GmailIS ( 4426): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/GmailIS ( 4426): 	at android.database.sqlite.SQLiteConnectionPool.tryAcquireNonPrimaryConnectionLocked(SQLiteConnectionPool.java:919)
E/GmailIS ( 4426): 	at android.database.sqlite.SQLiteConnectionPool.waitForConnection(SQLiteConnectionPool.java:610)
E/GmailIS ( 4426): 	at android.database.sqlite.SQLiteConnectionPool.acquireConnection(SQLiteConnectionPool.java:349)
E/GmailIS ( 4426): 	at android.database.sqlite.SQLiteSession.acquireConnection(SQLiteSession.java:1032)
E/GmailIS ( 4426): 	at android.database.sqlite.SQLiteSession.executeForLong(SQLiteSession.java:788)
E/GmailIS ( 4426): 	at android.database.sqlite.SQLiteStatement.simpleQueryForLong(SQLiteStatement.java:107)
E/GmailIS ( 4426): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:825)
E/GmailIS ( 4426): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:813)
E/GmailIS ( 4426): 	at android.database.sqlite.SQLiteDatabase.getVersion(SQLiteDatabase.java:974)
E/GmailIS ( 4426): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:241)
E/GmailIS ( 4426): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/GmailIS ( 4426): 	at com.google.android.gm.provider.bw.<init>(SourceFile:11950)
E/GmailIS ( 4426): 	at com.google.android.gm.provider.bw.a(SourceFile:995)
E/GmailIS ( 4426): 	at com.google.android.gm.provider.bw.b(SourceFile:1029)
E/GmailIS ( 4426): 	at com.google.android.gm.GmailIntentService.a(SourceFile:2276)
E/GmailIS ( 4426): 	at com.google.android.gm.GmailIntentService.onHandleIntent(SourceFile:73)
E/GmailIS ( 4426): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/GmailIS ( 4426): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/GmailIS ( 4426): 	at android.os.Looper.loop(Looper.java:135)
E/GmailIS ( 4426): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 4426): Failed to open database '/data/data/com.google.android.gm/databases/XX@YY'.
E/SQLiteDatabase( 4426): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4426): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4426): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/SQLiteDatabase( 4426): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/SQLiteDatabase( 4426): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/SQLiteDatabase( 4426): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/SQLiteDatabase( 4426): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 4426): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/SQLiteDatabase( 4426): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/SQLiteDatabase( 4426): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/SQLiteDatabase( 4426): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 4426): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 4426): 	at com.google.android.gm.provid,er.bw.<init>(SourceFile:10963)
E/SQLiteDatabase( 4426): 	at com.google.android.gm.provider.bw.a(SourceFile:995)
E/SQLiteDatabase( 4426): 	at com.google.android.gm.provider.cj.run(SourceFile:1053)
E/SQLiteDatabase( 4426): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 4426): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 4426): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4426): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  847): Killing 4166:com.lge.springcleaning/1000 (adj 15): empty #11
V/GLSActivity( 1767): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 4426): Thread[MailEngine creation,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of crash
E/AndroidRuntime( 4426): FATAL EXCEPTION: MailEngine creation
E/AndroidRuntime( 4426): Process: com.google.android.gm, PID: 4426
E/AndroidRuntime( 4426): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4426): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4426): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/AndroidRuntime( 4426): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/AndroidRuntime( 4426): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/AndroidRuntime( 4426): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/AndroidRuntime( 4426): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 4426): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/AndroidRuntime( 4426): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/AndroidRuntime( 4426): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/AndroidRuntime( 4426): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/AndroidRuntime( 4426): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 4426): 	at com.google.android.gm.provider.bw.<init>(SourceFile:10963)
E/AndroidRuntime( 4426): 	at com.google.android.gm.provider.bw.a(SourceFile:995)
E/AndroidRuntime( 4426): 	at com.google.android.gm.provider.cj.run(SourceFile:1053)
E/AndroidRuntime( 4426): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 4426): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4426): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4426): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
