#### Test 61703351926082e_thali01_LGE-LG-H815 Logs


```
--------- beginning of main
D/LGBluetoothPowerControlManager( 4553): [BTUI] init : getProfileProxy
D/BluetoothManagerService( 1282): Message: 30
D/TasksReceiver( 7406): [onReceive] intent = Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.lge.task/.database.TasksReceiver (has extras) }
D/TasksReceiver( 7406): [onReceive] WakeLock new : TasksReceiver, ReferenceCounted = true
D/TasksReceiver( 7406): [onReceive] WakeLock acquire : TasksReceiver
D/TasksReceiver( 7406): [onReceive] android.intent.action.BOOT_COMPLETED
D/AsyncAlarmTask( 7406): [AsyncAlarmTask]
D/BluetoothAdapterService( 4553): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d037118
D/LGBluetoothDeviceModeControllManager( 4553): onServiceStarted - isSink : false mWaitingForService : false
D/A2dpStateMachine( 4553): Enter Disconnected: -2
D/BluetoothAdapterService( 4553): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d037118
I/BluetoothHidServiceJni( 4553): classInitNative: succeeds
D/TasksReceiver( 7406): [onReceive] WakeLock release : TasksReceiver_Provider
--------- beginning of system
I/ActivityManager( 1282): Killing 6708:com.lge.hiddenmenu/1000 (adj 15): empty #22
D/HidService( 4553): Received start request. Starting profile...
I/bluedroid( 4553): get_profile_interface hidhost
I/bt-btif ( 4553): btif_hh_get_interface
I/bt-btif ( 4553): init
D/bt-btif ( 4553): btif_enable_service: current services:0xde4da348
D/BluetoothAdapterService( 4553): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d037118
D/BluetoothAdapterService(218329368)( 4553): handleMessage() - Message: 1
D/BluetoothAdapterService(218329368)( 4553): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(218329368)( 4553): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
D/BluetoothAdapterState( 4553): isTurningOnRadio()=false
D/BluetoothAdapterState( 4553): isTurningOffRadio()=false
D/BluetoothAdapterState( 4553): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 4553): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 4553): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 4553): Profile still not running:com.broadcom.bt.service.opp.OppService
D/HeadsetStateMachine( 4553): Proxy object connected
D/HeadsetStateMachine( 4553): Disconnected process message: 10, size: 0
D/AsyncAlarmTask( 7406): [doInBackground] cursor.getCount() = 0
D/LGBluetoothHfpAdapter( 4553): [BTUI] queryPhoneState
D/HeadsetPhoneState( 4553): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
I/BluetoothHealthServiceJni( 4553): classInitNative: succeeds
D/HeadsetStateMachine( 4553): Disconnected process message: 11, size: 0
D/HealthService( 4553): Received start request. Starting profile...
V/LIA_AppRecommendContentProvider( 7443): MrGContentProvider onCreate()
I/bluedroid( 4553): get_profile_interface health
I/bt-btif ( 4553): btif_hl_get_interface
I/bt-btif ( 4553): init
D/bt-btif ( 4553): Process name (droid.bluetooth)
D/bt-btif ( 4553): btif_hl_soc_thread_init
D/bt-btif ( 4553): create_thread: entered
D/bt-btif ( 4553): create_thread: thread created successfully
D/bt-btif ( 4553): entered btif_hl_select_thread
D/bt-btif ( 4553): btif_hl_select_wakeup_init
I/LGBluetoothHealthServiceJni( 4553): classInitNative: succeeds
D/BluetoothAdapterService( 4553): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d037118
D/bt-btif ( 4553): btif_hl_select_wakeup_init signal_fds[0]=58 signal_fds[1]=59
D/bt-btif ( 4553): max_s=58 
D/bt-btif ( 4553): set curr_set = org_set 
I/BluetoothPanServiceJni( 4553): classInitNative(L105): succeeds
D/PanService( 4553): Received start request. Starting profile...
D/BluetoothPanServiceJni( 4553): initializeNative(L110): pan
I/bluedroid( 4553): get_profile_interface pan
D/bt-btif ( 4553): stack_initialized = 0, btpan_cb.enabled:0
W/OpenGLRenderer( 4393): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
W/OpenGLRenderer( 4393): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,I/MSM-irqbalance(  595): Decided to move IRQ163 from CPU0 to CPU2
I/ActivityManager( 1282): Killing 6920:com.lge.cic.eden.service/u0a7 (adj 15): empty #22
D/AndroidRuntime( 7480): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 7480): CheckJNI is OFF
I/LGBluetoothPanAdapter( 4553): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 4553): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d037118
I/BtGatt.JNI( 4553): classInitNative(L901): classInitNative: Success!
D/BtGatt.DebugUtils( 4553): handleDebugAction() action=null
D/BtGatt.GattService( 4553): Received start request. Starting profile...
D/BtGatt.GattService( 4553): start()
I/bluedroid( 4553): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 4553): advertise manager created
I/LIA_SmartSetting(4.50.6)_LogCore( 7443): LIA Log setTagPrefix - prefix : LIA_SmartSetting(4.50.6)_
V/LIA_SmartSetting(4.50.6)_ContextDetector( 7443): onReceive action android.bluetooth.adapter.action.STATE_CHANGED
D/LIA_SmartSetting(4.50.6)_BTContextDetector( 7443): onReceive state= 11
W/LIA_SmartSetting(4.50.6)_ContextDetector( 7443): setting value is undefined.
I/LGBluetoothGattAdapter( 4553): [BTUI] getInstance : create [LGBluetoothGattAdapter]
D/LGBluetoothGattAdapter( 4553): setGattService:  set to: null
D/BluetoothAdapterService( 4553): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d037118
I/LGNetworkSettings( 4225): onCreate: 
D/BluetoothAdapterService( 4553): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d037118
I/LGBluetoothMapAdapter( 4553): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 4553): BluetoothMapBinder()
D/BluetoothMapService( 4553): Received start request. Starting profile...
D/BluetoothMapService( 4553): start()
D/BluetoothMapEmailSettingsLoader( 4553): Found 0 applications
D/BluetoothMapEmailAppObserver( 4553): createReceiver()
D/BluetoothMapEmailAppObserver( 4553): initObservers()
D/BluetoothMapEmailAppObserver( 4553): getEnabledAccountItems()
D/PhoneGlobalsNet( 4225): networksettings : PhoneGlobals.java[157] : onCreate()...
D/LGBluetoothProfileConnectionReceiver_LGSettingsAPK( 7382): onReceive(), ConnectedDeviceName : null , Num : 0
D/LGBluetoothProfileConnectionReceiver_LGSettingsAPK( 7382): [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information - BluetoothSettings
D/BluetoothAdapterService( 4553): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d037118
D/ConfigUtils( 4225): COUNTRY : EU
I/BluetoothSAPServiceJni( 4553): classInitNative(L170): succeeds
D/SapService( 4553): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 4553): initializeNative(L175): sap
I/bluedroid( 4553): get_profile_interface sap
I/bt-btif ( 4553): btif_sc_get_interface
I/bt-btif ( 4553): init
D/bt-btif ( 4553): btif_enable_service: current services:0xde4da348
I/LGBluetoothSapAdapter( 4553): [BTUI] getInstance : create [LGBluetoothSapAdapter]
I/LGBluetoothSapAdapter( 4553): [BTUI] Create LGBluetoothSapManager Instance
D/LGBluetoothSapManager( 4553): [BTUI] initSapManager
D/ConfigUtils( 4225): OPERATOR : 1
D/ConfigUtils( 4225): ALTERNATIVE CARRIER : OPEN
D/ConfigUtils( 4225): MODEL NAME : LG-H815
D/ConfigUtils( 4225): REGION : EU
D/ConfigUtils( 4225): TARGET PLATFORM : msm8992
D/ConfigUtils( 4225): DEVICE_UNKNOWN : p1
D/ConfigUtils( 4225): MODEL NAME : LG-H815
I/LGNetworkSettings( 4225): setUse4gNetwork
I/networksettings : ( 4225): LGNetworkSettings.java[68] : disable LteGsmUmtsSettings
D/BluetoothAdapterService( 4553): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d037118
D/LGBluetoothFeatureConfig( 4553): isPrivacyLogsEnabled : true
E/BluetoothOPPServiceJni( 4553): classInitNative
I/BluetoothOPPServiceJni( 4553): classInitNative(L373): succeeds
D/LgeBluetoothSimManager( 4225): [BTUI] SAP_ENABLE_EVT
V/PhoneGlobalsNet( 4225): Action intent recieved:android.intent.action.SIM_STATE_CHANGED
V/PhoneGlobalsNet( 4225): Action intent recieved:android.intent.action.SERVICE_STATE
I/ActivityManager( 1282): Start proc 7487:com.lge.lpd/1000 for broadcast com.lge.lpd/.receiver.LPDBootCompletedReceiver
D/NotificationMgrNet( 4225): updateNetworkSelection()...state = 2 new network 
D/NotificationMgrNet( 4225): cancelNetworkSelection()...
I/NotificationManager( 4225): com.lge.networksettings: cancel(6) by com.lge.networksettings
V/OppService( 4553): Opp initBinder
D/**OppService( 4553): Received start request. Starting profile...
D/OppService( 4553): Starting OppService 
D/LGBluetoothOppAdapter( 4553): [BTUI] getInstance : create [LGBluetoothOppAdapter]
I/NotificationManager( 4553): com.android.bluetooth: cancelAll by com.android.bluetooth
V/BluetoothOppNotification( 4553): send message
D/BluetoothOppPreference( 4553): Dumping Names:  
D/BluetoothOppPreference( 4553): {}
D/BluetoothOppPreference( 4553): Dumping Channels:  
D/BluetoothOppPreference( 4553): {}
D/OppService( 4553): Start()
W/BluetoothOPPServiceJni( 4553): initOppNative
D/BluetoothOPPServiceJni( 4553): initOppNative(L383): OPP
I/bluedroid( 4553): get_profile_interface opp
I/bt-btif ( 4553): btif_op_get_interface
D/BluetoothOPPServiceJni( 4553): initOppNative(L411): mOppCallbacksObj 2100202
D/BluetoothOPPServiceJni( 4553): initOppNative(L413): calling OPP init
I/bt-btif ( 4553): btif_opp_init
D/bt-btif ( 4553): btif_enable_service: current services:0xde4da348
D/BluetoothOPPServiceJni( 4553): initOppNative(L429): OPC and OPS init Succesful
D/BluetoothOPPServiceJni( 4553): initOppNative(L430): mOppCallbacksObj 2100202
V/OppService( 4553): setOppService(): set to: com.broadcom.bt.service.opp.OppService@3acbf7f9
D/BluetoothAdapterService( 4553): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d037118
D/BluetoothA2dp( 4553): Proxy object connected
D/LGBluetoothPowerControlManager( 4553): [BTUI] onServiceConnected : Got BluetoothA2dp: android.bluetooth.BluetoothA2dp@31fca33e
D/BluetoothAdapterService(218329368)( 4553): handleMessage() - Message: 1
D/BluetoothAdapterService(218329368)( 4553): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
V/OppService( 4553): pendingUpdate is :  true
D/BluetoothAdapterService(218329368)( 4553): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
D/BluetoothAdapterState( 4553): isTurningOnRadio()=false
D/BluetoothAdapterState( 4553): isTurningOffRadio()=false
D/BluetoothAdapterState( 4553): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 4553): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 4553): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
W/ContextImpl( 7487): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1804 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.lge.lpd.receiver.LPDBootCompletedReceiver.onReceive:42 android.app.ActivityThread.handleReceiver:2701 
D/BluetoothAdapterService( 4553): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(218329368)( 4553): handleMessage() - Message: 1
D/BluetoothAdapterService(218329368)( 4553): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(218329368)( 4553): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
D/BluetoothAdapterState( 4553): isTurningOnRadio()=false
D/BluetoothAdapterState( 4553): isTurningOffRadio()=false
D/BluetoothAdapterState( 4553): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 4553): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 4553): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/BluetoothOppProvider( 4553): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/OppService( 4553): Deleted complete outbound shares, number =  0
D/BluetoothAdapterService( 4553): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(218329368)( 4553): handleMessage() - Message: 1
D/BluetoothAdapterService(218329368)( 4553): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(218329368)( 4553): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
D/BluetoothAdapterState( 4553): isTurningOnRadio()=false
D/BluetoothAdapterState( 4553): isTurningOffRadio()=false
D/BluetoothAdapterState( 4553): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 4553): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 4553): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/BluetoothOppProvider( 4553): created cursor android.database.sqlite.SQLiteCursor@3bcb1ab5 on behalf of 
V/OppService( 4553): Deleted complete inbound failed shares, number = 0
V/BluetoothOppProvider( 4553): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
D/BluetoothAdapterService( 4553): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothOppNotification( 4553): update too frequent, put in queue
D/BluetoothAdapterService(218329368)( 4553): handleMessage() - Message: 1
D/BluetoothAdapterService(218329368)( 4553): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(218329368)( 4553): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
D/BluetoothAdapterState( 4553): isTurningOnRadio()=false
D/BluetoothAdapterState( 4553): isTurningOffRadio()=false
D/BluetoothAdapterState( 4553): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 4553): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 4553): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/BluetoothOppProvider( 4553): created cursor android.database.sqlite.SQLiteCursor@349bb54a on behalf of 
V/OppService( 4553): pendingUpdate is :  false
E/OppService( 4553): UpdateThread is Completed
D/BluetoothAdapterService( 4553): Profile still not running:com.broadcom.bt.service.opp.OppService
V/PanService( 4553): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService(218329368)( 4553): handleMessage() - Message: 1
D/BluetoothAdapterService(218329368)( 4553): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(218329368)( 4553): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=true
D/BluetoothAdapterState( 4553): isTurningOnRadio()=false
D/BluetoothAdapterState( 4553): isTurningOffRadio()=false
D/BluetoothAdapterState( 4553): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 4553): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 4553): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 4553): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothMapService( 4553): Handler(): got msg=1
D/BluetoothAdapterService(218329368)( 4553): handleMessage() - Message: 1
D/BluetoothAdapterService(218329368)( 4553): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(218329368)( 4553): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
D/BluetoothAdapterState( 4553): isTurningOnRadio()=false
D/BluetoothAdapterState( 4553): isTurningOffRadio()=false
D/BluetoothAdapterState( 4553): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 4553): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 4553): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 4553): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(218329368)( 4553): handleMessage() - Message: 1
D/BluetoothAdapterService(218329368)( 4553): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(218329368)( 4553): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
D/BluetoothAdapterState( 4553): isTurningOnRadio()=false
D/BluetoothAdapterState( 4553): isTurningOffRadio()=false
D/BluetoothAdapterState( 4553): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 4553): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 4553): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 4553): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothOppNotification( 4553): new notify threadi!
V/BluetoothOppNotification( 4553): send delay message
D/BluetoothAdapterService(218329368)( 4553): handleMessage() - Message: 1
D/BluetoothAdapterService(218329368)( 4553): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(218329368)( 4553): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=12, doUpdate=true
D/BluetoothAdapterState( 4553): isTurningOnRadio()=false
D/BluetoothAdapterState( 4553): isTurningOffRadio()=false
D/BluetoothAdapterState( 4553): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 4553): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 4553): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService(218329368)( 4553): onProfileServiceStateChange() - All profile services started.
V/OppService( 4553): ContentObserver received notification
D/BluetoothAdapterState( 4553): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 4553): enable
I/bt-btif ( 4553): BTIF ENABLE BLUETOOTH :: current btif_core_radio_refcount: 0, btif_core_state: 0, btif_core_cb.dut_mode: 0
E/bt-btu  ( 4553): VERSION AFBT-LREL-30_00.06 (BTE: BTE0322_00.20.00)
V/OppService( 4553): ContentObserver received notification
V/OppService( 4553): pendingUpdate is :  true
V/BluetoothOppProvider( 4553): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 4553): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 4553): created cursor android.database.sqlite.SQLiteCursor@18c4ecbb on behalf of 
V/BluetoothSapReceiver( 4553): [BTUI] checkServiceStart
V/BluetoothOppProvider( 4553): created cursor android.database.sqlite.SQLiteCursor@1f9bf5d8 on behalf of 
V/BluetoothOppNotification( 4553): mUpdateCompleteNotification = true
V/OppService( 4553): pendingUpdate is :  false
E/OppService( 4553): UpdateThread is Completed
V/BluetoothOppProvider( 4553): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 4553): created cursor android.database.sqlite.SQLiteCursor@375fad31 on behalf of 
V/BluetoothOppNotification( 4553): outbound: succ-0  fail-0
I/NotificationManager( 4553): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
V/BluetoothOppNotification( 4553): outbound notification was removed.
V/BluetoothOppProvider( 4553): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
I/GKI_LINUX( 4553): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 4553): btu_task pending for preload complete event
I/bt_hci_bdroid( 4553): init
I/bt_vendor( 4553): init
I/bt_vnd_conf( 4553): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 4553): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_vendor( 4553): op for 5
V/BluetoothOppProvider( 4553): created cursor android.database.sqlite.SQLiteCursor@1f67dc16 on behalf of 
I/bt-btif ( 4553): libbt-hci init returns 0
D/bt_vendor( 4553): op for 0
D/bt_vendor( 4553): op for 0
V/BluetoothOppNotification( 4553): inbound: succ-0  fail-0
I/NotificationManager( 4553): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
V/BluetoothOppNotification( 4553): inbound notification was removed.
V/BluetoothOppProvider( 4553): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 4553): created cursor android.database.sqlite.SQLiteCursor@134b9997 on behalf of 
D/LIA_NativeEventReceiver( 4350): onReceive action : android.intent.action.BOOT_COMPLETED = null
I/ActivityManager( 1282): Start proc 7529:com.lge.settings.easy/1000 for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver
I/LIA_PlatformUtil( 4350): startLIAService() : Trying to start LIA service ...
I/LIA_Service_LogCore( 4350): LIA Log Open() - prefix : LIA_Service_
D/StoreModeReceiver( 7382): intent.getAction() : android.intent.action.BOOT_COMPLETED
D/StoreModeReceiver( 7382): sim state :null
D/StoreModeReceiver( 7382): Back LED don't supported.
V/SettingsProvider( 1282): call_put(system:emotional_led_back_led=0) for 0 calling package = com.android.settings
E/NetlinkEvent(  415): NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
E/NetlinkEvent(  463): NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
V/SettingsProvider( 1282): call_put(system:emotional_led_back_incoming_call=0) for 0 calling package = com.android.settings
V/SettingsProvider( 1282): call_put(system:emotional_led_back_alarm=0) for 0 calling package = com.android.settings
V/SettingsProvider( 1282): call_put(system:emotional_led_back_missed_call=0) for 0 calling package = com.android.settings
V/SettingsProvider( 1282): call_put(system:emotional_led_back_missed_messages=0) for 0 calling package = com.android.settings
V/SettingsProvider( 1282): call_put(system:emotional_led_back_missed_emails=0) for 0 calling package = com.android.settings
V/SettingsProvider( 1282): call_put(system:emotional_led_back_calendar_noti=0) for 0 calling package = com.android.settings
V/SettingsProvider( 1282): call_put(system:emotional_led_back_voice_recording=0) for 0 calling package = com.android.settings
V/SettingsProvider( 1282): call_put(system:emotional_led_back_camera_timer_noti=0) for 0 calling package = com.android.settings
V/SettingsProvider( 1282): call_put(system:emotional_led_back_camera_face_detecting_noti=0) for 0 calling package = com.android.settings
V/SettingsProvider( 1282): call_put(system:notification_light_pulse_back=0) for 0 calling package = com.android.settings
D/StoreModeReceiver( 7382): SystemProperty Default brightness value [0-255] : 145
D/StoreModeReceiver( 7382): Default brightness[0-255] : 145
W/ResourcesManager( 7382): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/StoreModeReceiver( 7382): Default Screen off timeout value : 30000
D/StoreModeReceiver( 7382): SystemProperty Default brightness Mode value[true/false] : false
D/StoreModeReceiver( 7382): Default brightness Mode [0/1] : 0
D/StoreModeReceiver( 7382): Set MaxBrightness : 255
W/ResourcesManager( 7529): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/LIA_Service_LIAService( 4350): [LIA Service Info] -------------------------------
I/LIA_Service_LIAService( 4350):  - LIA Service Version Name : 0.8.20.2
I/LIA_Service_LIAService( 4350):  - LIA Service Release Date : 2014.10.27
I/LIA_Service_LIAService( 4350): --------------------------------------------------
D/LIA_Service_LIAService( 4350): onCreate()
E/PhoneInterfaceManager( 4225): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
D/AndroidRuntime( 7480): Calling main entry com.android.commands.am.Am
D/StoreModeReceiver( 7382): getPhoneNumber is empty
I/ActivityManager( 1282): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/StoreModeReceiver( 7382): go to StoreModeCheck()
D/StoreModeReceiver( 7382): isStoremode not null
V/SplitWindowPolicy( 4163): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1282): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0x0/ state=NATIVE]
D/PhoneInterfaceManager( 4225): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: 2147483643, result: false
D/ActivityManager( 1282): setTaskToReturnTo : TaskRecord{20a53661 #53 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ContextHelper( 1282): convertTheme. context->name=com.example.hello themeResourceId=16973833
D/ActivityManager( 1282): setTaskToReturnTo : TaskRecord{20a53661 #53 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
I/[LGHome]EVENT( 4393): onPause
D/WindowStateEx( 1282): AppWindowTokenEx init.. 
V/WindowManager( 1282): addAppToken: AppWindowToken{1d1fd674 token=Token{5b7be47 ActivityRecord{2cefe586 u0 com.example.hello/.MainActivity t53}}} to stack=1 task=53 at 0
D/InputDispatcher( 1282): Focus left window: Window{3aac7212 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/SplitWindowPolicy( 4163): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 4163): topRunningActivity=ActivityInfo{16c6cfac co.....Launcher}, taskId=51, activityType=1, bIsSplit=false
V/SettingsProvider( 1282): call_put(system:shop_mode_check=1) for 0 calling package = com.android.settings
D/AndroidRuntime( 7480): Shutting down VM
D/bt_vendor( 4553): op for 3
I/bt_userial_vendor( 4553): userial vendor open: opening /dev/ttyHS0
I/bt_userial_vendor( 4553): device fd = 73 open
D/bt_vendor( 4553): set_bluetooth_preproto set on
D/bt_vendor( 4553): op for 1
D/bt_vendor( 4553): op for 10
D/SplitWindow( 1282): check instance of lgWin Window{382b800c u0 Starting com.example.hello}
V/WindowManager( 1282): Adding window Window{382b800c u0 Starting com.example.hello} at 2 of 9 (after Window{3aac7212 u0 com.lge.launcher2/com.lge.launcher2.Launcher})
D/StoreModeReceiver( 7382): product_name : p1_global_com
D/StoreModeReceiver( 7382): Store mode start!
V/SettingsProvider( 1282): call_put(system:shop_mode=1) for 0 calling package = com.android.settings
V/SettingsProvider( 1282): call_put(system:shop_mode_check=1) for 0 calling package = com.android.settings
D/PowerManagerServiceEx( 1282): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x1, nextTimeout=147848 (in 107093 ms)
D/StoreModeReceiver( 7382): setBrightness() : NoMultiALC=255
W/ContextImpl( 7382): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1439 android.content.ContextWrapper.sendBroadcast:377 android.content.ContextWrapper.sendBroadcast:377 com.android.settings.StoreModeReceiver.sendBroadcast:480 com.android.settings.StoreModeReceiver.setMode:452 
I/ActivityManager( 1282): Start proc 7557:com.example.hello/u0a361 for activity com.example.hello/.MainActivity
I/[LGHome]EVENT( 4393): [Launcher.java:5453:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[LGHome]EVENT( 4393): [Launcher.java:5479:setEnableShakeHandlers()]disableShakeHandlers
V/SettingsProvider( 1282): call_put(system:screen_brightness_mode=0) for 0 calling package = com.android.settings
D/SettingsProvider( 1282): Set screen_off_timeout in entry value : 120000
V/SettingsProvider( 1282): call_put(system:screen_off_timeout=120000) for 0 calling package = com.android.settings
V/SettingsProvider( 1282): call_put(system:screen_brightness=255) for 0 calling package = com.android.settings
V/SettingsProvider( 1282): call_put(system:Retail_Mode=1) for 0 calling package = com.android.settings
D/bt_hwcfg( 4553): hw_config_cback opcode:0x0c03
D/bt_hwcfg( 4553): hw_config_cback state=1
D/LGBluetoothProfileConnectionReceiver_EasySetting( 7529): [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information EasySettings
D/PowerManagerService( 1282): updateBatteryLowStatus : lowPowerModeEnabled = false, autoLowPowerModeConfigured = false
D/PowerManagerServiceEx( 1282): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x1, nextTimeout=147848 (in 107072 ms)
I/PowerManagerServiceEx( 1282): [WiseScreen] mWiseScreenEnable = 0
D/SettingBootReceiver( 7382): onReceive
D/SettingBootReceiver( 7382): Boot Completed intent received, action=android.intent.action.BOOT_COMPLETED
I/PowerManagerServiceEx( 1282): [WiseScreen] mWirelessChargingEnable = 0
D/SettingBootReceiver( 7382): boot completed process end time=0
D/LPWGController( 1282): [updateSettings] mKnockOnSetting = true, mKnockCodeSetting = false, tapcount = 0, mIsSame1st2ndTap =false
D/PowerManagerServiceEx( 1282): setRetailMode, Mode : 1
D/SettingBootReceiver( 7382): setStyle()
D/PowerManagerServiceEx( 1282): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x1, nextTimeout=147848 (in 107068 ms)
D/SettingBootReceiver( 7382): SettingStyle=1
D/SettingBootReceiver( 7382): setAccountMenu()
D/TAG     ( 7382): setKidsMode
D/TAG     ( 7382): mIsOwner, setKidsMode
D/SettingBootReceiver( 7382): setAccountMenu()
D/SettingBootReceiver( 7382): timezoneID is null
D/bt_hwcfg( 4553): hw_config_cback opcode:0x0c14
D/bt_hwcfg( 4553): hw_config_cback state=4
D/bt_hwcfg( 4553): Chipset Name: BCM4335C0
D/bt_hwcfg( 4553): Change chipset Name: BCM4339
D/bt_hwcfg( 4553): Chipset BCM4339
D/bt_hwcfg( 4553): Target name = [BCM4339]
I/bt_hwcfg( 4553): Found patchfile: /system/bin//BCM4339_003.001.009.0108.0501_LGE_P1-EU_FM_ORC.hcd
I/[LGHome]EVENT( 4393): onStop
D/LIA_Service_RemotePackageHandler( 4350): LIA task pacakge added(Using PackageManager) : com.lge.ia.task.incalagent
D/LIA_Service_RemoteSessionManager( 4350): onAdded() : com.lge.ia.task.incalagent
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc45
D/bt_hwcfg( 4553): hw_config_cback state=2
D/LIA_Service_RemoteProxy( 4350): connectToRemoteService() : sleep for 100(msec) and start to connect to com.lge.ia.task.incalagent
D/ActionManagerService( 4287): notifyUserLog: 1000004
I/WindowStateAnimator( 1282): Starting window displayed
I/SettingBootReceiver( 7382): disable au
D/SplitWindowPolicy( 4163): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 4163): topRunningActivity=ActivityInfo{10f50475 co.....MainActivity}, taskId=53, activityType=0, bIsSplit=false
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc18
D/bt_hwcfg( 4553): hw_config_cback state=3
I/bt_hwcfg( 4553): bt vendor lib: set UART baud 4000000
I/TAG     ( 7382): disable WirelessSettingsActivity
I/TAG     ( 7382): disable SKTPhoneMode
I/SystemUI[Framework]( 1282): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.example.hello
W/PhoneWindowManagerEx( 1282): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1282): setLGSystemUiVisibility(0x0)
I/SystemUI[Framework]( 1282): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2db55615,  pkg=Window{382b800c u0 Starting com.example.hello}
D/StatusBarManagerServiceEx( 1282): manageNaviBtnDisableList userId=0 what=0x0 pkg=Window{382b800c u0 Starting com.example.hello}
D/PhoneStatusBar( 3410): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
I/SystemUI[Framework]( 1282): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 3410): NavigationKey Color is changed(WHITE_WITH_SHADOW -> WHITE)
I/[SystemUI]NavigationThemeResource( 3410):  BarMode=0, Theme=BLACK, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 3410): , Keyguard show=false, IME shown=false, Panel expanded=false
I/Utils   ( 7382): Exception config_folder_phone
D/BarTransitions( 3410): draw background and invalidate : color = 7000000
D/BarTransitions( 3410): draw background and invalidate : color = 7000000
D/UsbSettingsControl( 7382): [AUTORUN] setTetherStatus() : status=false
D/SettingBootReceiver( 7382): [AUTORUN] onReceive() : android.intent.action.BOOT_COMPLETED
D/SettingBootReceiver( 7382): [AUTORUN] sys.usb.config = ptp_only,adb
D/SettingBootReceiver( 7382): [AUTORUN] sys.usb.state = ptp_only,adb
D/SettingBootReceiver( 7382): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/SettingBootReceiver( 7382): [Nightmode] Enter receiver
D/BluetoothPermissionRequest( 7382): onReceive
D/LGBluetoothFeatureConfig( 7382):  get() - isFeatureLoaded : false
D/AppInfoDao( 7487): topacitivyt exist app = com.example.hello
D/ContextHelper( 7557): convertTheme. context->name=com.example.hello themeResourceId=16973833
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc2e
D/bt_hwcfg( 4553): hw_config_cback state=5
D/AppInfoDao( 7487): topacitivyt update app = com.example.hello time = 2016-03-08 08:58 date = 20160308
I/mission ( 7382): isglobe in receiver false
I/ApnSelectReceiver( 7382): ApnSelectReceiver onReceive : android.intent.action.BOOT_COMPLETED
I/ApnSelectReceiver( 7382): persist.sys.cupss.changed is : 0
I/mission ( 7382):  current numeric is 
D/BluetoothManagerService( 1282): Message: 20
D/BluetoothManagerService( 1282): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1769fd3:true
I/NotificationManager( 6942): com.google.android.apps.plus: cancel(10436) by com.google.android.apps.plus
I/WebViewFactory( 7557): Loading com.google.android.webview version 44.0.2403.90 (code 240309050)
I/ActivityManager( 1282): Start proc 7582:com.google.android.configupdater/u0a64 for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/LGBluetoothStateChangeReceiver( 7382): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/LIA_Service_RemoteProxy( 4350): connectToRemoteService() : start service - com.lge.ia.task.incalagent
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
I/LibraryLoader( 7557): Time to load native libraries: 1 ms (timestamps 911-912)
I/LibraryLoader( 7557): Expected native library version number "",actual native library version number ""
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
I/ActivityManager( 1282): Start proc 7606:com.lge.lockscreensettings/1000 for broadcast com.lge.lockscreensettings/.lockscreen.QuickUnlockReceiver
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
,V/WebViewChromiumFactoryProvider( 7557): Binding Chromium to main looper Looper (main, tid 1) {1d49e2c}
I/ActivityManager( 1282): Killing 6891:com.android.gallery3d/u0a55 (adj 15): empty #22
I/LibraryLoader( 7557): Expected native library version number "",actual native library version number ""
I/chromium( 7557): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
I/BrowserStartupController( 7557): Initializing chromium process, singleProcess=true
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
W/art     ( 7557): Attempt to remove local handle scope entry from IRT, ignoring
I/art     (  497): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 53% free, 28MB/60MB, paused 231us total 22.454ms
E/SysUtils( 7557): ApplicationContext is null in ApplicationStatus
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
W/chromium( 7557): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
I/art     (  497): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 53% free, 28MB/60MB, paused 142us total 14.111ms
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
E/libEGL  ( 7557): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7557): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 7557): QUALCOMM build                   : 7fcf94b, Ib2e715f795
I/Adreno  ( 7557): Build Date                       : 07/03/15
I/Adreno  ( 7557): OpenGL ES Shader Compiler Version: E031.25.03.09
I/Adreno  ( 7557): Local Branch                     : 
I/Adreno  ( 7557): Remote Branch                    : refs/tags/AU_LINUX_ANDROID_LA.BF64.1.2.1_RB2.05.01.01.081.049
I/Adreno  ( 7557): Remote Branch                    : NONE
I/Adreno  ( 7557): Reconstruct Branch               : NOTHING
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
I/art     (  497): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 53% free, 28MB/60MB, paused 120us total 12.182ms
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
V/AudioPolicyService(  468): registerClient() client 0xf1d55e00, uid 10361
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/BluetoothManagerService( 1282): Message: 20
D/BluetoothManagerService( 1282): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3181662f:true
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/BluetoothAdapterService(218329368)( 4553): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@176790cf
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
E/LIA_Service_RemoteProxy( 4350): connectToRemoteService() : startService() failed! - com.lge.ia.task.incalagent
W/ActivityManager( 1282): Unable to start service Intent { act=com.lge.ia.task.incalagent pkg=com.lge.ia.task.incalagent (has extras) } U=0: not found
D/LIA_Service_RemoteProxy( 4350): connectToRemoteService() : bind service - com.lge.ia.task.incalagent
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
W/ActivityManager( 1282): Unable to start service Intent { act=com.lge.ia.task.incalagent pkg=com.lge.ia.task.incalagent (has extras) } U=0: not found
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
E/LIA_Service_RemoteProxy( 4350): connectToRemoteService() : bindService() failed! - com.lge.ia.task.incalagent
D/LIA_Service_RemotePackageHandler( 4350): LIA task pacakge added(Using PackageManager) : com.lge.ia.task.smartsetting
D/LIA_Service_RemoteSessionManager( 4350): onAdded() : com.lge.ia.task.smartsetting
D/LIA_Service_RemoteProxy( 4350): connectToRemoteService() : sleep for 100(msec) and start to connect to com.lge.ia.task.smartsetting
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
I/NotificationManager( 1282): android: cancelAsUser(2145784878) by android
W/ResourcesManager( 7606): Asset path '/system/framework/com.lge.locksettings.jar' does not exist or contains no resources.
W/ResourcesManager( 7606): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
I/ActivityManager( 1282): Killing 6968:com.google.android.onetimeinitializer/u0a13 (adj 15): empty #22
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 4553): hw_config_cback state=6
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc4e
D/bt_hwcfg( 4553): hw_config_cback state=6
D/LIA_Service_RemoteProxy( 4350): connectToRemoteService() : start service - com.lge.ia.task.smartsetting
E/LIA_Service_RemoteProxy( 4350): connectToRemoteService() : startService() failed! - com.lge.ia.task.smartsetting
W/ActivityManager( 1282): Unable to start service Intent { act=com.lge.ia.task.smartsetting pkg=com.lge.ia.task.smartsetting (has extras) } U=0: not found
D/LIA_Service_RemoteProxy( 4350): connectToRemoteService() : bind service - com.lge.ia.task.smartsetting
W/ActivityManager( 1282): Unable to start service Intent { act=com.lge.ia.task.smartsetting pkg=com.lge.ia.task.smartsetting (has extras) } U=0: not found
E/LIA_Service_RemoteProxy( 4350): connectToRemoteService() : bindService() failed! - com.lge.ia.task.smartsetting
D/LIA_Service_RemotePackageHandler( 4350): LIA task pacakge added(Using PackageManager) : com.lge.ia.task.s4urecommender
D/LIA_Service_RemoteSessionManager( 4350): onAdded() : com.lge.ia.task.s4urecommender
D/LIA_Service_RemoteProxy( 4350): connectToRemoteService() : sleep for 100(msec) and start to connect to com.lge.ia.task.s4urecommender
E/UpdateRequestReceiver( 7582): ignoring update request
I/bt_hwcfg( 4553): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 4553): Settlement delay -- 100 ms
I/bt_hwcfg( 4553): Setting fw settlement delay to 100 
I/ActivityManager( 1282): Start proc 7645:com.google.android.apps.maps/u0a119 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
W/art     ( 7557): Attempt to remove local handle scope entry from IRT, ignoring
E/UpdateRequestReceiver( 7582): ignoring update request
W/AwContents( 7557): onDetachedFromWindow called when already detached. Ignoring
E/UpdateRequestReceiver( 7582): ignoring update request
D/SystemWebViewEngine( 7557): CordovaWebView is running on device made by: LGE
W/art     ( 7557): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7557): Attempt to remove local handle scope entry from IRT, ignoring
E/UpdateRequestReceiver( 7582): ignoring update request
E/UpdateRequestReceiver( 7582): ignoring update request
E/UpdateRequestReceiver( 7582): ignoring update request
D/LIA_Service_RemoteProxy( 4350): connectToRemoteService() : start service - com.lge.ia.task.s4urecommender
I/ActivityManager( 1282): Start proc 7682:com.lge.drmservice/u0a68 for broadcast com.lge.drmservice/.DrmBroadcastReceiver
I/ActivityManager( 1282): Killing 6810:com.lge.eodengine/1000 (adj 15): empty #22
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc45
D/bt_hwcfg( 4553): hw_config_cback state=2
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc18
D/bt_hwcfg( 4553): hw_config_cback state=7
I/bt_hwcfg( 4553): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 4553): Setting local bd addr to F8:95:C7:87:3C:51
D/bt_hwcfg( 4553): hw_config_cback opcode:0xfc01
D/bt_hwcfg( 4553): hw_config_cback state=8
I/bt_hwcfg( 4553): vendor lib fwcfg completed
I/bt-btif ( 4553): HC preload_cb 0 [0:SUCCESS 1:FAIL]
I/bt-btu  ( 4553): btu_task received preload complete event
I/        ( 4553): BTE_InitTraceLevels -- TRC_HCI,2
I/        ( 4553): BTE_InitTraceLevels -- TRC_L2CAP,2
I/        ( 4553): BTE_InitTraceLevels -- TRC_RFCOMM,2
I/        ( 4553): BTE_InitTraceLevels -- TRC_OBEX,2
I/        ( 4553): BTE_InitTraceLevels -- TRC_AVCT,2
I/        ( 4553): BTE_InitTraceLevels -- TRC_AVDT,2
I/        ( 4553): BTE_InitTraceLevels -- TRC_AVRC,2
I/        ( 4553): BTE_InitTraceLevels -- TRC_AVDT_SCB,2
I/        ( 4553): BTE_InitTraceLevels -- TRC_A2D,2
I/        ( 4553): BTE_InitTraceLevels -- TRC_BNEP,2
I/        ( 4553): BTE_InitTraceLevels -- TRC_BTM,2
I/        ( 4553): BTE_InitTraceLevels -- TRC_GAP,2
I/        ( 4553): BTE_InitTraceLevels -- TRC_PAN,2
I/        ( 4553): BTE_InitTraceLevels -- TRC_SAP,2
I/        ( 4553): BTE_InitTraceLevels -- TRC_SDP,2
I/        ( 4553): BTE_InitTraceLevels -- TRC_GATT,2
I/        ( 4553): BTE_InitTraceLevels -- TRC_SMP,2
I/        ( 4553): BTE_InitTraceLevels -- TRC_BTAPP,3
I/        ( 4553): BTE_InitTraceLevels -- TRC_BTIF,3
I/        ( 4553): BTE_InitTraceLevels -- TRC_PROTOCOL,0
I/TasksProvider( 7406): Sending task notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.lge.task/ }
W/ContentResolver( 7406): Failed to get type for: content://com.lge.task/ (Unknown URI content://com.lge.task/)
D/LIA_Service_RemoteProxy( 4350): connectToRemoteService() : startService() succeeded. - com.lge.ia.task.s4urecommender
D/LIA_Service_RemoteProxy( 4350): connectToRemoteService() : bind service - com.lge.ia.task.s4urecommender
I/Activity( 7557): Activity.onPostResume() called 
D/LIA_Service_RemoteProxy( 4350): connectToRemoteService() : bindService() succeeded - waiting for onServiceConnected() for com.lge.ia.task.s4urecommender ...
D/LIA_Service_RemotePackageHandler( 4350): LIA task pacakge added(Using PackageManager) : com.lge.ia.task.informant
D/LIA_Service_RemoteSessionManager( 4350): onAdded() : com.lge.ia.task.informant
D/LIA_Service_RemoteProxy( 4350): connectToRemoteService() : sleep for 100(msec) and start to connect to com.lge.ia.task.informant
D/OpenGLRenderer( 7557): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/SplitWindow( 1282): check instance of lgWin Window{1ca3ed22 u0 com.example.hello/com.example.hello.MainActivity}
V/WindowManager( 1282): Adding window Window{1ca3ed22 u0 com.example.hello/com.example.hello.MainActivity} at 2 of 10 (before Window{382b800c u0 Starting com.example.hello})
I/LIA_S4URecommender_LogCore( 7154): LIA Log Open() - prefix : LIA_S4URecommender_
I/LIA_S4URecommender_LogTracer( 7154): [Log Tracer - Service State Transition] onCreate()...... 
W/chromium( 7557): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/ActivityManager( 1282): Killing 6255:com.lge.appbox.client:SingleBinaryService/u0a9 (adj 15): empty #22
V/BluetoothOppNotification( 4553): new notify threadi!
V/BluetoothOppNotification( 4553): send delay message
V/BluetoothOppProvider( 4553): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 4553): created cursor android.database.sqlite.SQLiteCursor@21c69784 on behalf of 
V/BluetoothOppNotification( 4553): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 4553): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/DrmBroadcastReceiver( 7682): Receive ACTION_BOOT_COMPLETED
V/BluetoothOppProvider( 4553): created cursor android.database.sqlite.SQLiteCursor@17d0eb6d on behalf of 
V/BluetoothOppNotification( 4553): outbound: succ-0  fail-0
I/NotificationManager( 4553): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
V/BluetoothOppNotification( 4553): outbound notification was removed.
V/BluetoothOppProvider( 4553): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 4553): created cursor android.database.sqlite.SQLiteCursor@efda3a2 on behalf of 
V/BluetoothOppNotification( 4553): inbound: succ-0  fail-0
I/NotificationManager( 4553): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
V/BluetoothOppNotification( 4553): inbound notification was removed.
V/BluetoothOppProvider( 4553): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 4553): created cursor android.database.sqlite.SQLiteCursor@1b263833 on behalf of 
I/LIA_S4URecommender_LIARemoteService( 7154): [LIA Remote Service Info] ------------------------
I/LIA_S4URecommender_LIARemoteService( 7154):  - UID : 10031
I/LIA_S4URecommender_LIARemoteService( 7154):  - LIA Core Version Name : 0.8.24
I/LIA_S4URecommender_LIARemoteService( 7154):  - LIA Core Release Date : 2014.12.16
I/LIA_S4URecommender_LIARemoteService( 7154):  - LIA S4URecommender Task Version Name : 4.22.15
I/LIA_S4URecommender_LIARemoteService( 7154):  - LIA Service Version Name : 0.8.20.2
I/LIA_S4URecommender_LIARemoteService( 7154): --------------------------------------------------
D/LIA_S4URecommender_LIARemoteService( 7154): onCreate()
I/LIA_S4URecommender_S4URecommenderService( 7154): getTaskPropertiesAtFirstStarting()
I/LIA_S4URecommender_S4URecommenderService( 7154): isNowInActivationCondition()
I/LIA_S4URecommender_BoardStateUtil( 7154): defaultHomePackage : com.lge.launcher2
I/LIA_S4URecommender_ActivationConditionHandler( 7154): ActivationConditionHandler : LGHome condition is true
D/StrictMode( 7645): StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 7645): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 7645): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 7645): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 7645): 	at java.io.File.exists(File.java:363)
D/StrictMode( 7645): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1107)
D/StrictMode( 7645): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1130)
D/StrictMode( 7645): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1072)
D/StrictMode( 7645): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
D/StrictMode( 7645): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 7645): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4700)
D/StrictMode( 7645): 	at android.app.ActivityThread.access$1500(ActivityThread.java:162)
D/StrictMode( 7645): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1410)
D/StrictMode( 7645): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 7645): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 7645): 	at android.app.ActivityThread.main(ActivityThread.java:5430)
D/StrictMode( 7645): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 7645): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 7645): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:913)
D/StrictMode( 7645): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:706)
D/StrictMode( 7645): StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 7645): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 7645): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 7645): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 7645): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 7645): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1073)
D/StrictMode( 7645): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
D/StrictMode( 7645): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 7645): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4700)
D/StrictMode( 7645): 	at android.app.ActivityThread.access$1500(ActivityThread.java:162)
D/StrictMode( 7645): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1410)
D/StrictMode( 7645): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 7645): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 7645): 	at android.app.ActivityThread.main(ActivityThread.java:5430)
D/StrictMode( 7645): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 7645): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 7645): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:913)
D/StrictMode( 7645): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:706)
D/StrictMode( 7645): StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 7645): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 7645): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 7645): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 7645): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 7645): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1073)
D/StrictMode( 7645): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
D/StrictMode( 7645): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 7645): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4700)
D/StrictMode( 7645): 	at android.app.ActivityThread.access$1500(ActivityThread.java:162)
D/StrictMode( 7645): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1410)
D/StrictMode( 7645): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 7645): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 7645): 	at android.app.ActivityThread.main(ActivityThread.java:5430)
D/StrictMode( 7645): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 7645): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 7645): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:913)
D/StrictMode( 7645): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:706)
D/StrictMode( 7645): StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 7645): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 7645): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 7645): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 7645): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 7645): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 7645): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 7645): 	at com.google.r.k.d(PG:1187)
D/StrictMode( 7645): 	at com.google.r.k.a(PG:2107)
D/StrictMode( 7645): 	at com.google.w.a.a.do.<init>(PG:23)
D/StrictMode( 7645): 	at com.google.w.a.a.do.a(PG:405)
D/StrictMode( 7645): 	at com.google.r.v.a(PG:1161)
D/StrictMode( 7645): 	at com.google.r.y.a(PG:2188)
D/StrictMode( 7645): 	at com.google.r.e.b(PG:170)
D/StrictMode( 7645): 	at com.google.r.e.b(PG:15188)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
D/StrictMode( 7645): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 7645): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4700)
D/StrictMode( 7645): 	at android.app.ActivityThread.access$1500(ActivityThread.java:162)
D/StrictMode( 7645): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1410)
D/StrictMode( 7645): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 7645): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 7645): 	at android.app.ActivityThread.main(ActivityThread.java:5430)
D/StrictMode( 7645): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 7645): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 7645): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:913)
D/StrictMode( 7645): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:706)
D/StrictMode( 7645): StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 7645): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 7645): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 7645): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 7645): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 7645): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 7645): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 7645): 	at com.google.r.k.d(PG:1187)
D/StrictMode( 7645): 	at com.google.r.k.c(PG:18147)
D/StrictMode( 7645): 	at com.google.r.k.d(PG:583)
D/StrictMode( 7645): 	at com.google.w.a.a.do.<init>(PG:40)
D/StrictMode( 7645): 	at com.google.w.a.a.do.a(PG:405)
D/StrictMode( 7645): 	at com.google.r.v.a(PG:1161)
D/StrictMode( 7645): 	at com.google.r.y.a(PG:2188)
D/StrictMode( 7645): 	at com.google.r.e.b(PG:170)
D/StrictMode( 7645): 	at com.google.r.e.b(PG:15188)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
D/StrictMode( 7645): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 7645): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4700)
D/StrictMode( 7645): 	at android.app.ActivityThread.access$1500(ActivityThread.java:162)
D/StrictMode( 7645): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1410)
D/StrictMode( 7645): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 7645): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 7645): 	at android.app.ActivityThread.main(ActivityThread.java:5430)
D/StrictMode( 7645): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 7645): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 7645): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:913)
D/StrictMode( 7645): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:706)
D/StrictMode( 7645): StrictMode policy violation; ~duration=63 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 7645): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 7645): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 7645): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 7645): 	at java.io.File.exists(File.java:363)
D/StrictMode( 7645): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1107)
D/StrictMode( 7645): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1130)
D/StrictMode( 7645): 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1238)
D/StrictMode( 7645): 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:192)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
D/StrictMode( 7645): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 7645): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4700)
D/StrictMode( 7645): 	at android.app.ActivityThread.access$1500(ActivityThread.java:162)
D/StrictMode( 7645): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1410)
D/StrictMode( 7645): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 7645): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 7645): 	at android.app.ActivityThread.main(ActivityThread.java:5430)
D/StrictMode( 7645): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 7645): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 7645): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:913)
D/StrictMode( 7645): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:706)
D/StrictMode( 7645): StrictMode policy violation; ~duration=62 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 7645): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 7645): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 7645): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 7645): 	at java.io.File.exists(File.java:363)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
D/StrictMode( 7645): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 7645): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4700)
D/StrictMode( 7645): 	at android.app.ActivityThread.access$1500(ActivityThread.java:162)
D/StrictMode( 7645): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1410)
D/StrictMode( 7645): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 7645): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 7645): 	at android.app.ActivityThread.main(ActivityThread.java:5430)
D/StrictMode( 7645): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 7645): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 7645): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:913)
D/StrictMode( 7645): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:706)
D/StrictMode( 7645): StrictMode policy violation; ~duration=62 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 7645): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 7645): 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
D/StrictMode( 7645): 	at java.io.File.lastModified(File.java:571)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
D/StrictMode( 7645): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
D/StrictMode( 7645): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 7645): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4700)
D/StrictMode( 7645): 	at android.app.ActivityThread.access$1500(ActivityThread.java:162)
D/StrictMode( 7645): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1410)
D/StrictMode( 7645): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 7645): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 7645): 	at android.app.ActivityThread.main(ActivityThread.java:5430)
D/StrictMode( 7645): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 7645): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 7645): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:913)
D/StrictMode( 7645): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:706)
,D/LIA_Service_RemoteProxy( 4350): connectToRemoteService() : start service - com.lge.ia.task.informant
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 4393): [LGUnreadLgeEmailsBadge.java:86:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 4393): [LGUnreadLgeEmailsBadge.java:87:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]NumberBadge.LGBroadCastBadge( 4393): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 4393): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 4393): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
,V/DrmService( 7682): Service onCreate
,D/DrmService( 7682): Received new request = 4
I/ActivityManager( 1282): Killing 6396:com.android.cellbroadcastreceiver/u0a14 (adj 15): empty #22
,I/OpenGLRenderer( 7557): Initialized EGL, version 1.4
W/ActivityThread( 7645): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/DrmServiceHandler( 7682): updateDrmPushNotification() : No notification
D/DrmService( 7682): Completed !! request = 4
D/DrmService( 7682): Request count = 0
,D/InputDispatcher( 1282): Focus entered window: Window{1ca3ed22 u0 com.example.hello/com.example.hello.MainActivity},
,D/libc-netbsd( 7645): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7645): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7645): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7645): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  463): [LG DATA] No such appUid: 10119
D/DnsProxyListener(  463): App 10119 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  463): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  463): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd(  463): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  463): res_queryN name = xxxxx, class = 1, type = 1
,D/OpenGLRenderer( 7557): Enabling debug mode 0
,W/com.google.a.a.b.d.a( 7645): Application name is not set. Call Builder#setApplicationName.
,D/BluetoothManagerService( 1282): Message: 20
D/BluetoothManagerService( 1282): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fc6b62b:true
,I/bt-btif ( 4553): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 4553): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
,W/bt-smp  ( 4553): Key(LSB ~ MSB) = e8 a9 6d f5 8a 0a a8 5d ae 6a 38 6f 56 7c 5c 21 
W/bt-smp  ( 4553): Plain text(LSB ~ MSB) = 55 09 71 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 4553): Encrypted text(LSB ~ MSB) = 78 a0 1e cf 38 ed 30 58 03 e2 8e 39 ae 47 ec cb 
W/bt-btm  ( 4553): Stopping oneshot timer
,I/GKI_LINUX( 4553): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,W/bt-smp  ( 4553): Key(LSB ~ MSB) = e8 a9 6d f5 8a 0a a8 5d ae 6a 38 6f 56 7c 5c 21 
W/bt-smp  ( 4553): Plain text(LSB ~ MSB) = 74 78 7a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 4553): Encrypted text(LSB ~ MSB) = 16 58 e2 1e 9b d2 52 83 ed 8b 32 4b 29 16 cb f1 
E/bt-btif ( 4553): warning : media task started media_task_refcnt 1 
E/bt-btif ( 4553): Calling BTA_HhEnable
E/bt-btif ( 4553): btif_storage_get_adapter_property service_mask:0x1200c8
I/bt-btif ( 4553): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 4553): Address is:F8:95:C7:87:3C:51
W/bt-smp  ( 4553): Key(LSB ~ MSB) = e8 a9 6d f5 8a 0a a8 5d ae 6a 38 6f 56 7c 5c 21 
W/bt-smp  ( 4553): Plain text(LSB ~ MSB) = 6d 50 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 4553): Encrypted text(LSB ~ MSB) = f0 7c 04 55 2e 6c 12 08 ef 5f be 92 9a a5 bc a1 
,D/BT_PROF_AUDIO( 4553): created moving average (N=100)
D/BT_PROF_AUDIO( 4553): reset rate average
W/bt-btif ( 4553): overflow 0, enter 0, exit 0
,W/bt-smp  ( 4553): Key(LSB ~ MSB) = e8 a9 6d f5 8a 0a a8 5d ae 6a 38 6f 56 7c 5c 21 
W/bt-smp  ( 4553): Plain text(LSB ~ MSB) = 4f 4f 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 4553): Encrypted text(LSB ~ MSB) = 4a 6f a0 b4 0e c0 d9 c6 fe 20 f1 0f 24 03 51 04 
,W/bt-smp  ( 4553): Key(LSB ~ MSB) = e8 a9 6d f5 8a 0a a8 5d ae 6a 38 6f 56 7c 5c 21 
W/bt-smp  ( 4553): Plain text(LSB ~ MSB) = fd 8d 6b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 4553): Encrypted text(LSB ~ MSB) = a2 3c 28 84 8e c1 4f f2 32 1a 8a b4 52 80 db 97 
,I/Timeline( 7557): Timeline: Activity_idle id: android.os.BinderProxy@6f54ee1 time:41897
,W/BindingManager( 7557): Cannot call determinedVisibility() - never saw a connection for the pid: 7557
,I/chromium( 7557): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/libc-netbsd(  463): res_queryN name = xxxxx succeed
I/System.out( 7645): propertyValue:false
,D/AuthorizationBluetoothService( 5096): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager( 1282): Displayed com.example.hello/.MainActivity: +1s214ms (total +3s779ms)
I/Timeline( 1282): Timeline: Activity_windows_visible id: ActivityRecord{2cefe586 u0 com.example.hello/.MainActivity t53} time:41938
,D/BluetoothAdapterProperties( 4553): Name is: G4-1
,D/BluetoothManagerService( 1282): Bluetooth Adapter name changed to G4-1
D/BluetoothManagerService( 1282): store name and address
V/DrmService( 7682): Service onDestroy
D/BluetoothManagerService( 1282): Stored Bluetooth name: G4-1
,D/JsMessageQueue( 7557): Set native->JS mode to OnlineEventsBridgeMode
,D/libc-netbsd( 7645): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7645): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,E/AndroidProtocolHandler( 7557): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/ActivityManager( 1282): Start proc 7731:com.lge.gcuv/1000 for broadcast com.lge.gcuv/.GcuvReceiver
,D/LIA_Service_RemoteProxy( 4350): connectToRemoteService() : startService() succeeded. - com.lge.ia.task.informant
D/LIA_Service_RemoteProxy( 4350): connectToRemoteService() : bind service - com.lge.ia.task.informant
I/LIA_S4URecommender_BoardStateUtil( 7154): isEnabledConciergeBoard() : count > 0 - true
I/LIA_S4URecommender_ActivationConditionHandler( 7154): ActivationConditionHandler : ConciergeBoard condition is true
I/LIA_S4URecommender_ActivationConditionHandler( 7154): isAllConditionsSatisfied() : LGHome ConciergeBoard is true
,D/LIA_Service_RemoteProxy( 4350): connectToRemoteService() : bindService() succeeded - waiting for onServiceConnected() for com.lge.ia.task.informant ...
D/LIA_Service_LIAManager( 4350): LIAManager instance created.
D/LIA_Service_LIAService( 4350): onStartCommand() : LIAService started! - id :1, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
,D/BluetoothAdapterProperties( 4553): Scan Mode:20
D/BluetoothAdapterProperties( 4553): Discoverable Timeout:120
I/ActivityManager( 1282): Killing 6334:com.google.android.partnersetup/u0a5 (adj 15): empty #22
D/BluetoothAdapterProperties( 4553): Adding bonded device:10:D3:8A:FB:85:D4
,I/bt-btif ( 4553): HAL bt_hal_cbacks->remote_device_properties_cb
,I/NotificationManager( 7645): com.google.android.apps.maps: cancel(10436) by com.google.android.apps.maps
,I/LIA_S4URecommender_MrGServiceBase( 7154): Version Update Check : CASE2 - This is not the first task launching after installing the first version APK or updated version APK
I/LIA_S4URecommender_LIARemoteService( 7154): checkTaskInitialization() : needResetTaskPropertyInSharedPreference() is false, so maintain SharedPreference
D/LIA_S4URecommender_LIARemoteService( 7154): getTaskPreparation()
I/LIA_S4URecommender_S4URecommenderService( 7154): getTaskPropertiesAtFirstStarting()
I/LIA_S4URecommender_S4URecommenderService( 7154): isNowInActivationCondition()
,I/LIA_S4URecommender_BoardStateUtil( 7154): defaultHomePackage : com.lge.launcher2
I/LIA_S4URecommender_ActivationConditionHandler( 7154): ActivationConditionHandler : LGHome condition is true
,E/BluetoothRemoteDevices( 4553): devicePropertyChangedCallback: bdDevice: 10:D3:8A:FB:85:D4, value is empty for type: 10
,I/LIA_S4URecommender_BoardStateUtil( 7154): isEnabledConciergeBoard() : count > 0 - true
I/LIA_S4URecommender_ActivationConditionHandler( 7154): ActivationConditionHandler : ConciergeBoard condition is true
I/LIA_S4URecommender_ActivationConditionHandler( 7154): isAllConditionsSatisfied() : LGHome ConciergeBoard is true
D/LIA_S4URecommender_LIARemoteService( 7154): updateTaskProperties()
,D/LIA_S4URecommender_LIARemoteService( 7154): --> Getting task property of activation from Shared preferences ...
D/LIA_S4URecommender_LIARemoteService( 7154): --> Task property for activation for S4URecommender is true
D/LIA_S4URecommender_LIARemoteService( 7154): --> Getting activation properties done!
,D/LIA_S4URecommender_LIARemoteManager( 7154): init()
,D/LIA_S4URecommender_LIARemoteService( 7154): prepare() : Tasks are registering ...
D/LIA_S4URecommender_LIARemoteService( 7154): --> Task name : S4URecommender
,D/LIA_S4URecommender_TaskLauncher( 7154): register() - main launcher : false
D/LIA_S4URecommender_LIARemoteService( 7154): prepare() : Tasks have been registered.
I/LIA_S4URecommender_LogCore( 7154): LIA Log setTagPrefix - prefix : LIA_S4URecommender_
D/LIA_S4URecommender_LIARemoteService( 7154): onStartCommand() : LIARemoteService started! - (Id :1), Intent { act=com.lge.ia.task.s4urecommender pkg=com.lge.ia.task.s4urecommender (has extras) }
D/LIA_S4URecommender_LIARemoteService( 7154): onBind()
D/LIA_S4URecommender_LIARemoteManager( 7154): getBinder()
,D/BluetoothAdapterService(218329368)( 4553): handleMessage() - Message: 40
D/BluetoothAdapterService(218329368)( 4553): handleMessage() - MESSAGE_PROFILE_INIT_PRIORITIES
I/LGRemoteDevicePropertySetting( 4553): [BTUI] remoteDeviceSetProperties
I/LGRemoteDevicePropertySetting( 4553): [BTUI] Get AOSP HeadsetService
,E/BluetoothRemoteDevices( 4553): devicePropertyChangedCallback: mDeviceTrust: false
E/bt-btif ( 4553): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
D/bt_vendor( 4553): op for 2
E/bt-btif ( 4553): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
D/bt_vendor( 4553): op for 6
,E/bt-btif ( 4553): btif_sock_init: !radio_req && !rfc_init
I/bt-btif ( 4553): BTA_JvEnable
E/bt-btif ( 4553): btsock_vendor_hci_init: !vhci_init
D/bt-btif ( 4553): btsock_ctrl_hci_init(L191): poll handle:6
D/bt-btif ( 4553): init_hci_slots(L136): in
,D/IOP_DB_BT( 4553): db_open: file /etc/bluetooth/iop_bt.db
D/jxcore_app_log( 7557): JniHelper::setJavaVM(0xf509d200), pthread_self() = -425530624
,D/LIA_Service_RemoteProxy( 4350): onServiceConnected() : com.lge.ia.task.s4urecommender
,D/IOP_DB_BT( 4553): db_open: db_open : handle 3729672248l, read 11677 bytes onto local cache
D/IOP_DB_BT( 4553): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/LIA_S4URecommender_LIARemoteManager( 7154): getProperties()
D/LIA_S4URecommender_TaskLauncher( 7154): getTaskPropertyList() - main launcher : false
D/IOP_DB_BT( 4553): db_query: result 1
I/        ( 4553): iop_db_open: iop_db_open status 0
E/bt-btif ( 4553): btif_sock_init, radio_req:0, rfc_init:1, vhci_init:1
D/bt-btif ( 4553): btsock_ctrl_hci_init(L191): poll handle:6
I/bt-btif ( 4553): bta_pan_co_init
,D/bte_conf( 4553): Device ID record 1 : primary
D/bte_conf( 4553):   vendorId            = 00c4
D/bte_conf( 4553):   vendorIdSource      = 0001
D/bte_conf( 4553):   product             = 13a1,
,D/bte_conf( 4553):   version             = 1000
D/bte_conf( 4553):   clientExecutableURL = 
D/bte_conf( 4553):   serviceDescription  = 
D/bte_conf( 4553):   documentationURL    = 
D/bte_conf( 4553): bte_load_did_conf no section named DID2.
I/bt-btif ( 4553): HAL bt_hal_cbacks->adapter_state_changed_cb
E/bt-btif ( 4553): btif_hf_upstreams_evt: wrong handle = 1021 
D/BluetoothAdapterState( 4553): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
I/bt-btif ( 4553): HAL bt_op_callbacks->opc_state_cb
D/BluetoothOPPServiceJni( 4553): opc_state_cb(L140):  opc_state_cb state:0
D/BluetoothAdapterProperties( 4553): ScanMode =  20
D/BluetoothAdapterProperties( 4553): State =  11
D/BluetoothAdapterProperties( 4553): mDiscoverableTimeout = 120
D/BluetoothAdapterProperties( 4553): Setting state to 12
I/BluetoothAdapterState( 4553): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService(218329368)( 4553): updateAdapterState() - Broadcasting state to 1 receivers.
V/LIA_Service_RemoteProxy( 4350): onServiceConnected() : Task Property for S4URecommender - Activation:true, AutoExecution:true
D/BluetoothManagerService( 1282): Message: 60
D/BluetoothManagerService( 1282): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService( 1282): Broadcasting onBluetoothStateChange(true) to 8 receivers.
I/BluetoothAdapterState( 4553): Entering On State
I/BluetoothAdapterState( 4553): Entering On State from state = 11
,D/BluetoothAdapterService(218329368)( 4553): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@176790cf
D/BluetoothAdapterService(218329368)( 4553): isQuetModeEnabled() - Enabled = false
D/BluetoothAdapterService(218329368)( 4553): autoConnect() - Initiate auto connection on BT on...
D/BluetoothAdapterService( 4553): [BTUI] autoConnect() : not allowed
D/LGBluetoothServiceAdapter( 4553): [BTUI] OnState
D/LGBluetoothServiceAdapter( 4553): [BTUI]         global_name: G4-1
D/LGBluetoothServiceAdapter( 4553): [BTUI]         local_name: G4-1
,D/BluetoothHeadset( 4225): onBluetoothStateChange: up=true
D/BluetoothAdapterService(218329368)( 4553): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@176790cf
D/BluetoothAdapterService(218329368)( 4553): isQuetModeEnabled() - Enabled = false
D/BluetoothAdapterService(218329368)( 4553): autoConnect() - Initiate auto connection on BT on...
D/BluetoothAdapterService( 4553): [BTUI] autoConnect() : not allowed
D/BluetoothManagerService( 1282): Creating new ProfileServiceConnections object for profile: 1
D/LIA_Service_RemoteSessionManager( 4350): New RemoteProxy received and try to update proxy map ...
D/BluetoothAdapterService(218329368)( 4553): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@176790cf
,I/LIA_Service_RemoteSessionManager( 4350): Added task & RemoteProxy: S4URecommender, com.lge.ia.manager.remote.RemoteProxy@2b0f6e8a
V/LIA_Service_RemoteSessionManager( 4350): Trying to register task(s) to LIACore ...
D/LIA_Service_TaskLauncher( 4350): register() - main launcher : true
D/LIA_Service_TaskLauncher( 4350): --> S4URecommender is registered on LIACores
,D/LIA_Service_TaskLauncher( 4350): --> S4URecommender is auto execution task. Try to run ...
D/LIA_Service_TaskLauncher( 4350): runTask - main launcher : true
D/LIA_Service_RemoteSessionManager( 4350): runTask() : S4URecommender
D/LIA_Service_RemoteProxy( 4350): runTask() : Task name & RemoteProxy - S4URecommender, com.lge.ia.manager.remote.RemoteProxy@2b0f6e8a
D/bt_h4   ( 4553): vendor lib postload completed
D/BluetoothHeadset( 1282): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 1282): onBluetoothStateChange: up=true
D/BluetoothHeadset( 4225): onBluetoothStateChange: up=true
I/LIA_Service_LogTracer( 4350): [Log Tracer - Task State Transition] runTask(S4URecommender)...... 
D/OppService( 4553): onOpcStateChange()
I/bt-btif ( 4553): HAL bt_op_callbacks->ops_state_cb
D/BluetoothOPPServiceJni( 4553): ops_state_cb(L223):  ops_state_cb state:0
D/LIA_S4URecommender_LIARemoteManager( 7154): runTask() : S4URecommender
D/OppService( 4553): Recieved MESSAGE_OPC_ENABLE
D/OppService( 4553): onOpsStateChange() :0
D/LIA_S4URecommender_TaskLauncher( 7154): runTask - main launcher : false
V/LIA_S4URecommender_TaskContext( 7154): runSession() : S4URecommender
D/LIA_S4URecommender_LIARemoteService( 7154): getTask()
D/LGBluetoothFeatureConfig( 4553): isPrivacyLogsEnabled : true
D/OppService( 4553): Recieved MESSAGE_OPS_ENABLE
D/BluetoothPanServiceJni( 4553): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
I/bt-btif ( 4553): HAL bt_hal_cbacks->adapter_properties_cb
D/LIA_S4URecommender_TaskSession( 7154): TaskSession.of() - thread id : 251, thread name : Binder_2
D/BluetoothAdapterService(218329368)( 4553): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@176790cf
D/BluetoothA2dp( 4722): onBluetoothStateChange: up=true
I/LIA_Informant_LogCore( 7154): LIA Log Open() - prefix : LIA_Informant_
D/BluetoothHeadset( 4225): onBluetoothStateChange: up=true
,D/BluetoothAdapterProperties( 4553): Scan Mode:21
,D/BluetoothHeadset( 4722): onBluetoothStateChange: up=true
I/bt-btif ( 4553): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 4553): Discoverable Timeout:120
D/LGBluetoothDeviceModeControllManager( 4553): adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,D/BluetoothA2dp( 4553): onBluetoothStateChange: up=true
I/LIA_Informant_LogTracer( 7154): [Log Tracer - Service State Transition] onCreate()...... 
,E/BluetoothManagerService( 1282): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService( 1282): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService( 1282): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService( 1282): Message: 40
D/BluetoothManagerService( 1282): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/LGBluetoothAPIService( 4163): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/BleQmManagerService( 4163): [BleQmManagerService]  onReceive:  android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapterService(218329368)( 4553): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@176790cf
D/LGBluetoothAPIService( 4163): Message: 1
D/LGBluetoothAPIService( 4163): MESSAGE_BOOT_COMPLETED
D/BluetoothAdapterService(218329368)( 4553): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@176790cf
,D/BluetoothAdapterService(218329368)( 4553): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@176790cf
,D/BluetoothAdapterService(218329368)( 4553): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@176790cf
W/jxcore-log( 7557): Initializing JXcore engine
W/jxcore-log( 7557): JXcore engine is ready
,D/BluetoothAdapterService(218329368)( 4553): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@176790cf
I/LGBluetoothAPIService( 4163): [BTUI] LGBluetoothAPIService Binding Success
,I/BluetoothMapService( 4553): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 4553): STATE_ON
V/BluetoothPbapReceiver( 4553): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 4553): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 4553): ***********state = 12
,I/[SystemUI]QuickSettingsHandler( 3410): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 3410): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,W/ContextImpl( 7382): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1804 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.lge.bluetoothsetting.DockEventReceiver.beginStartingService:138 com.lge.bluetoothsetting.DockEventReceiver.onReceive:119 
,D/LGBluetoothAPIServer( 4553): [BTUI] onCreate()
D/LGBluetoothAPIServer( 4553): [BTUI] onBind()
,D/LGBluetoothAPIService( 4163): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 4163): Message: 100
D/LGBluetoothAPIService( 4163): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,I/LIA_SmartSetting(4.50.6)_LogCore( 7443): LIA Log setTagPrefix - prefix : LIA_SmartSetting(4.50.6)_
V/LIA_SmartSetting(4.50.6)_ContextDetector( 7443): onReceive action android.bluetooth.adapter.action.STATE_CHANGED
D/LIA_SmartSetting(4.50.6)_BTContextDetector( 7443): onReceive state= 12
,D/LIA_SmartSetting(4.50.6)_LGIFTTT( 7443): recipeSlug= arrive_home_bluetooth
D/LIA_SmartSetting(4.50.6)_LGIFTTT( 7443): RECIPE_URI= content://com.lge.iftttmanager.provider/recipe
D/LIA_SmartSetting(4.50.6)_LGIFTTT( 7443): selection= recipe_slug = "arrive_home_bluetooth"
,D/BluetoothAdapterService( 4553): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d037118
V/BluetoothPbapService( 4553): Pbap Service onCreate
V/BluetoothPbapService( 4553): Starting PBAP service
I/LIA_S4URecommender_LogTracer( 7154): [Log Tracer - Task State Transition] create(S4URecommender)...... Request
D/BluetoothAdapterService(218329368)( 4553): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@176790cf
D/LGBluetoothPbapAdapter( 4553): [BTUI] getInstance : create
,V/BluetoothMapService( 4553): Handler(): got msg=1
,D/BluetoothMapMasInstance( 4553): Map Service startRfcommSocketListener
V/BluetoothPbapService( 4553): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 4553): state: 12
D/LGBluetoothDeviceModeControllManager( 4553): [BTUI] checkDeviceModeAndSet, sinkMode : false
V/BluetoothPbapService( 4553): Handler(): got msg=1
V/BluetoothPbapService( 4553): Pbap Service startRfcommSocketListener
D/BluetoothMapMasInstance( 4553): MAS initSocket()
,D/BluetoothMapMasInstance( 4553):   masId = 00
D/BluetoothMapMasInstance( 4553):   msgTypes = 0e
D/BluetoothMapMasInstance( 4553):   masName = SMS/MMS
D/BluetoothMapMasInstance( 4553):   SDP string = 000eSMS/MMS
D/BluetoothAdapterService(218329368)( 4553): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@176790cf
,V/BluetoothPbapService( 4553): Pbap Service initSocket
D/BluetoothManagerService( 1282): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService( 1282): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 4553): getBluetoothService() called with no BluetoothManagerCallback
D/LIA_SmartSetting(4.50.6)_LGIFTTT( 7443): status= 0
D/LIA_SmartSetting(4.50.6)_ContextDetector( 7443): onUpdate Bluetooth on
W/jxcore-log( 7557): Starting JXcore engine
,D/LIA_S4URecommender_AsyncChannel( 7154): Send Order (17)
D/LIA_S4URecommender_S4URecommenderTask( 7154): registerRunBatchStarterAlarm entered
W/LIA_S4URecommender_S4URecommenderTask( 7154): unregisterRunBatchStarterAlarm
I/bt-btif ( 4553): BTA_JvCreateRecordByUser
D/LIA_S4URecommender_S4URecommenderTask( 7154): registerRunBatch start alarm time : Wed Mar 09 00:00:00 CET 2016
I/bt-btif ( 4553): BTA_JvRfcommStartServer
,D/LGBluetoothServiceAdapter( 4553): [BTUI] createSocketChannel FD=86 mFd=0
D/LIA_S4URecommender_CommunicationRankCallLogCollector( 7154): CommunicationRankCallLogCollector Creator
D/LIA_S4URecommender_S4URecommenderTask( 7154): registerListener
W/BluetoothAdapter( 4553): getBluetoothService() called with no BluetoothManagerCallback
,D/LocalBluetoothProfileManager( 7382): Adding local A2DP profile
V/BluetoothPbapService( 4553): Succeed to create listening socket ,
V/BluetoothPbapService( 4553): Accepting socket connection...
I/bt-btif ( 4553): BTA_JvCreateRecordByUser
I/bt-btif ( 4553): BTA_JvRfcommStartServer
D/LGBluetoothServiceAdapter( 4553): [BTUI] createSocketChannel FD=88 mFd=86
V/BluetoothMapMasInstance( 4553): Succeed to create listening socket 
D/BluetoothMapMasInstance( 4553): Accepting socket connection...
,D/BluetoothManagerService( 1282): Message: 30
D/LIA_SmartSetting(4.50.6)_Recommender( 7443): onStatusChanged value= Bluetooth on
,V/LIA_SmartSetting(4.50.6)_SenseLocation( 7443): getCurrentPlaceId 
,D/LIA_SmartSetting(4.50.6)_Recommender( 7443): not entered home
V/LIA_SmartSetting(4.50.6)_DeviceLogger( 7443): DeviceLogger.log: DeviceSettingProfile [profileId=-1, timestamp=1457423883162, , settingStatus=Bluetooth on, deviceTypeOrdinal=1]
,D/BluetoothAdapterService(218329368)( 4553): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@176790cf
,I/LIA_S4URecommender_LogTracer( 7154): [Log Tracer - Task State Transition] create(S4URecommender)...... Success
I/LIA_S4URecommender_TaskSession( 7154): S4URecommender task is created !!
I/LIA_S4URecommender_TaskSession( 7154): S4URecommender create() process time = 29 msec
D/LIA_S4URecommender_TaskSession( 7154): enable() - enable state : false, thread id : 251, thread name : Binder_2
,I/LIA_S4URecommender_LogTracer( 7154): [Log Tracer - Task State Transition] start(S4URecommender)...... Request
D/BluetoothAdapterService(218329368)( 4553): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@176790cf
,D/LIA_SmartSetting(4.50.6)_LocationDBManagerDBAdapter( 7443): insert start
,D/LocalBluetoothProfileManager( 7382): Adding local HEADSET profile
,I/LIA_Informant_LIARemoteService( 7154): [LIA Remote Service Info] ------------------------
I/LIA_Informant_LIARemoteService( 7154):  - UID : 10031
I/LIA_Informant_LIARemoteService( 7154):  - LIA Core Version Name : 0.8.25
I/LIA_Informant_LIARemoteService( 7154):  - LIA Core Release Date : 2015.05.12
I/LIA_Informant_LIARemoteService( 7154):  - LIA Informant Task Version Name : 4.22.22
I/LIA_Informant_LIARemoteService( 7154):  - LIA Service Version Name : 0.8.20.2
I/LIA_Informant_LIARemoteService( 7154): --------------------------------------------------
D/LIA_Informant_LIARemoteService( 7154): onCreate()
D/BluetoothManagerService( 1282): Message: 30
,I/LIA_Informant_InformantService( 7154): [main] getTaskPropertiesAtFirstStarting()
I/LIA_Informant_InformantService( 7154): [main] isNowInActivationCondition()
,I/LIA_S4URecommender_TaskSession( 7154): S4URecommender start() result: true, process time = 0 msec
I/LIA_S4URecommender_LogTracer( 7154): [Log Tracer - Task State Transition] start(S4URecommender)...... Success
I/LIA_S4URecommender_TaskSession( 7154): enable() - enable state : true
D/LIA_S4URecommender_TaskContext( 7154): runSeesion() succeeded.
D/LIA_S4URecommender_TaskLauncher( 7154): runTask - succeeded.
,D/BluetoothManagerService( 1282): Message: 30
I/LIA_Informant_BoardStateUtil( 7154): defaultHomePackage : com.lge.launcher2
,D/LIA_S4URecommender_AndroidDBHelper( 7154): /data/data/com.lge.ia.task.s4urecommender/
I/LIA_Service_RemoteSessionManager( 4350): RemoteProxyMap Size : 1
I/LIA_Service_RemoteSessionManager( 4350): RemoteProxyMap : com.lge.ia.task.s4urecommender [key: S4URecommender]
,D/LIA_S4URecommender_AndroidDBHelper( 7154): /data/data/com.lge.ia.task.s4urecommender/
D/LIA_S4URecommender_AndroidDBHelper( 7154): /data/data/com.lge.ia.task.s4urecommender/
,D/LIA_S4URecommender_AsyncChannel( 7154): Receive Order (17)
D/LIA_S4URecommender_S4URecommenderTask( 7154): Prepare Done Callback ~~~ !!!!!!!!!!!
,D/ActionManager( 7154): connecting to ActionManagerService...
I/LGBluetoothContextForResources( 7382): [BTUI] create LGBluetoothContextForResources new Instance
D/LGBluetoothContextForResources( 7382): context.getPackageName : com.lge.bluetoothsetting
D/LGBluetoothContextForResources( 7382): mBluetoothContext.getPackageName : com.lge.bluetoothsetting
D/PanProfile( 7382): mainContext : com.lge.bluetoothsetting
,I/LIA_Informant_ActivationConditionHandler( 7154): ActivationConditionHandler : LGHome condition is true
,D/LIA_SmartSetting(4.50.6)_LocationDBManager( 7443): insertSettingInfo ID = 5474
V/GCUV:GcuvReceiver( 7731): onReceive from Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.lge.gcuv/.GcuvReceiver (has extras) }
,D/BluetoothManagerService( 1282): Message: 30
,I/GCUV:SDKReflector( 7731): +isLinkedUser : false
,I/LIA_Informant_BoardStateUtil( 7154): isEnabledConciergeBoard() : count > 0 - true
I/LIA_Informant_ActivationConditionHandler( 7154): ActivationConditionHandler : ConciergeBoard condition is true
I/LIA_Informant_ActivationConditionHandler( 7154): isAllConditionsSatisfied() : LGHome ConciergeBoard is true
D/LocalBluetoothProfileManager( 7382): Adding local MAP profile
,D/BluetoothMap( 7382): Create BluetoothMap proxy object
I/LIA_Informant_BoardStateUtil( 7154): defaultHomePackage : com.lge.launcher2
I/LIA_Informant_ActivationConditionHandler( 7154): ActivationConditionHandler : LGHome condition is true
D/BluetoothManagerService( 1282): Message: 30
,V/GCUV:JsonUtils( 7731): getJsonFile {"sequence":"00000000000000000000000003000002952842","gcuv_completed":false}
,I/GCUV:JsonUtils( 7731): readCompleted + false
D/BluetoothManagerService( 1282): Message: 400
D/BluetoothHeadset( 4225): Proxy object connected
,D/BluetoothManagerService( 1282): Message: 400
D/BluetoothHeadset( 1282): Proxy object connected
,D/BluetoothManagerService( 1282): Message: 30
D/BluetoothManagerService( 1282): Message: 400
D/BluetoothHeadset( 4225): Proxy object connected
V/GCUV:Utils( 7731): startService will start at 03/08 10:58:03
,V/BluetoothPbapService( 4553): Pbap Service onBind
D/LocalBluetoothProfileManager( 7382): LocalBluetoothProfileManager construction complete
,D/BluetoothManagerService( 1282): Message: 400
D/BluetoothAdapterService(218329368)( 4553): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@176790cf
D/BluetoothHeadset( 4225): Proxy object connected
,D/BluetoothManagerService( 1282): Message: 400
,D/BluetoothHeadset( 4722): Proxy object connected
,W/jxcore-log( 7557): Platform android
W/jxcore-log( 7557): 
W/jxcore-log( 7557): Process ARCH arm
W/jxcore-log( 7557): 
,I/ActivityManager( 1282): Start proc 7768:com.lge.drive.activator/u0a65 for broadcast com.lge.drive.activator/com.lge.drive.oem.BootReceiver
,I/LIA_Informant_BoardStateUtil( 7154): isEnabledConciergeBoard() : count > 0 - true
I/LIA_Informant_ActivationConditionHandler( 7154): ActivationConditionHandler : ConciergeBoard condition is true
I/LIA_Informant_ActivationConditionHandler( 7154): isAllConditionsSatisfied() : LGHome ConciergeBoard is true
D/LGBluetoothUserBindClient( 7382): [BTUI] initUserBindClient
,W/ContextImpl( 7382): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1870 android.content.ContextWrapper.bindService:539 com.lge.bluetoothsetting.LGBluetoothUserBindClient.initUserBindClient:98 com.lge.bluetoothsetting.LGBluetoothUserBindClient.<init>:57 com.lge.bluetoothsetting.LGBluetoothUserBindClient.getInstance:47 
,I/LIA_Informant_MrGServiceBase( 7154): Version Update Check : CASE2 - This is not the first task launching after installing the first version APK or updated version APK
I/LIA_Informant_LIARemoteService( 7154): checkTaskInitialization() : needResetTaskPropertyInSharedPreference() is false, so maintain SharedPreference
D/LIA_Informant_LIARemoteService( 7154): getTaskPreparation()
I/LIA_Informant_InformantService( 7154): [main] getTaskPropertiesAtFirstStarting()
I/LIA_Informant_InformantService( 7154): [main] isNowInActivationCondition()
,I/jxcore-log( 7557): JXcore Cordova bridge is ready!
I/jxcore-log( 7557): 
W/jxcore-log( 7557): JXcore engine is started
D/DockEventReceiver( 7382): finishStartingService: stopping service
,I/LIA_Informant_BoardStateUtil( 7154): defaultHomePackage : com.lge.launcher2
I/LIA_Informant_ActivationConditionHandler( 7154): ActivationConditionHandler : LGHome condition is true
,D/BluetoothA2dp( 7382): Proxy object connected
,D/A2dpProfile( 7382): Bluetooth service connected
,D/BluetoothAdapterService(218329368)( 4553): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@176790cf
,D/BluetoothInputDevice( 7382): Proxy object connected
,D/HidProfile( 7382): Bluetooth service connected
D/BluetoothAdapterService(218329368)( 4553): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@176790cf
,D/LGBluetoothProfileConnectionReceiver_LGSettingsAPK( 7382): onReceive(), ConnectedDeviceName : null , Num : 0
,D/BluetoothPan( 7382): BluetoothPAN Proxy object connected
,D/PanProfile( 7382): Bluetooth service connected
,D/BluetoothAdapterService(218329368)( 4553): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@176790cf
V/BluetoothOppReceiver( 4553): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,I/LIA_Informant_BoardStateUtil( 7154): isEnabledConciergeBoard() : count > 0 - true
I/LIA_Informant_ActivationConditionHandler( 7154): ActivationConditionHandler : ConciergeBoard condition is true
I/LIA_Informant_ActivationConditionHandler( 7154): isAllConditionsSatisfied() : LGHome ConciergeBoard is true
,D/BluetoothMap( 7382): Proxy object connected
D/MapProfile( 7382): Bluetooth service connected
D/BluetoothMap( 7382): getConnectedDevices()
,D/BluetoothAdapterService(218329368)( 4553): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@176790cf
I/LIA_Informant_BoardStateUtil( 7154): defaultHomePackage : com.lge.launcher2
I/LIA_Informant_ActivationConditionHandler( 7154): ActivationConditionHandler : LGHome condition is true
,V/BluetoothMapService( 4553): getConnectedDevices()
,D/BluetoothPbap( 7382): Proxy object connected
,D/PbapServerProfile( 7382): Bluetooth service connected
V/BluetoothOppManager( 4553): restoreApplicationData! falsefalsenullnull
,D/LGBluetoothUserBindClient( 7382): [BTUI] onServiceConnected
,I/ActivityManager( 1282): Killing 7002:com.android.providers.calendar/u0a19 (adj 15): empty #22
,D/BluetoothManagerService( 1282): Message: 400
,D/BluetoothHeadset( 7382): Proxy object connected
,D/HeadsetProfile( 7382): Bluetooth service connected
,D/BluetoothAdapterService(218329368)( 4553): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@176790cf
,E/jxcore-log( 7557): >> LGE-LG-H815
E/jxcore-log( 7557): 
,I/jxcore-log( 7557): Total memory 2968948736
I/jxcore-log( 7557): 
,I/jxcore-log( 7557): Free memory 87416832
I/jxcore-log( 7557): 
I/jxcore-log( 7557): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 7557): 
I/jxcore-log( 7557): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 7557): 
,I/jxcore-log( 7557): userPath [ 'www', 'www' ]
I/jxcore-log( 7557): 
,I/jxcore-log( 7557): Size 1440 2392
I/jxcore-log( 7557): 
,I/jxcore-log( 7557): Screen Brightness 255
I/jxcore-log( 7557): 
,E/jxcore-log( 7557): Dummy Error Log.
E/jxcore-log( 7557): 
,V/BluetoothSapReceiver( 4553): [BTUI] checkServiceStart
,I/LIA_Informant_BoardStateUtil( 7154): isEnabledConciergeBoard() : count > 0 - true
I/LIA_Informant_ActivationConditionHandler( 7154): ActivationConditionHandler : ConciergeBoard condition is true
I/LIA_Informant_ActivationConditionHandler( 7154): isAllConditionsSatisfied() : LGHome ConciergeBoard is true
D/LIA_Informant_LIARemoteService( 7154): updateTaskProperties()
D/LIA_Informant_LIARemoteService( 7154): --> Getting task property of activation from Shared preferences ...
D/LIA_Informant_LIARemoteService( 7154): --> Task property for activation for Informant is true
D/LIA_Informant_LIARemoteService( 7154): --> Task property for activation for SmartMoment is true
D/LIA_Informant_LIARemoteService( 7154): --> Task property for activation for TermExtraction is true
D/LIA_Informant_LIARemoteService( 7154): --> Task property for activation for UIMAgent is true
D/LIA_Informant_LIARemoteService( 7154): --> Getting activation properties done!
,D/LIA_Informant_LIARemoteManager( 7154): init()
D/BluetoothPermissionRequest( 7382): onReceive
,D/LGBluetoothFeatureConfig( 7382): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 7382): [BTUI] FileNotFound: readProperty
D/LIA_Informant_LIARemoteService( 7154): prepare() : Tasks are registering ...
D/LIA_Informant_LIARemoteService( 7154): --> Task name : Informant
,D/LGBluetoothStateChangeReceiver( 7382): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
,D/LIA_Informant_TaskLauncher( 7154): register() - main launcher : false
D/LIA_Informant_LIARemoteService( 7154): --> Task name : SmartMoment
D/LIA_Informant_TaskLauncher( 7154): register() - main launcher : false
D/LIA_Informant_LIARemoteService( 7154): --> Task name : TermExtraction
D/LIA_Informant_TaskLauncher( 7154): register() - main launcher : false
D/LIA_Informant_LIARemoteService( 7154): --> Task name : UIMAgent
D/LIA_Informant_TaskLauncher( 7154): register() - main launcher : false
D/LIA_Informant_LIARemoteService( 7154): prepare() : Tasks have been registered.
I/LIA_Informant_LogCore( 7154): LIA Log setTagPrefix - prefix : LIA_Informant_
,I/LIA_Informant_Tips_ModelReleaseConfig( 7154): isSupportModel() : SmartTips App Installed - true
,I/LIA_Informant_Tips_ModelReleaseConfig( 7154): isSupportModel() : SmartTips App Installed - true
,I/LIA_Informant_Tips_ModelReleaseConfig( 7154): isSupportModel() : SmartTips App Installed - true
,I/ActivityManager( 1282): Start proc 7798:com.lge.cloudhub/u0a73 for broadcast com.lge.cloudhub/.service.CloudHubReceiver
,D/LIA_Informant_TimeAlarmHandler( 7154): setRepeating() : 2016-03-08 08:58:33
,D/LIA_Informant_LIARemoteService( 7154): onStartCommand() : LIARemoteService started! - (Id :1), Intent { act=com.lge.ia.task.informant pkg=com.lge.ia.task.informant (has extras) }
D/LIA_Informant_LIARemoteService( 7154): onBind()
D/LIA_Informant_LIARemoteManager( 7154): getBinder()
,I/ActivityManager( 1282): Killing 7036:com.lge.clock/u0a16 (adj 15): empty #22
,D/AuthorizationBluetoothService( 5096): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/LIA_Service_RemoteProxy( 4350): onServiceConnected() : com.lge.ia.task.informant
V/AlarmManager( 1282): ELAPSED_WAKEUP set : Alarm{1b0517f4 type 2 when 42532 com.android.providers.calendar} when 42532
,D/ActionManager( 7154): connected to ActionManagerService.
,D/LIA_Informant_LIARemoteManager( 7154): getProperties()
D/LIA_Informant_TaskLauncher( 7154): getTaskPropertyList() - main launcher : false
,V/LIA_Service_RemoteProxy( 4350): onServiceConnected() : Task Property for TermExtraction - Activation:true, AutoExecution:false
V/LIA_Service_RemoteProxy( 4350): onServiceConnected() : Task Property for UIMAgent - Activation:true, AutoExecution:false
V/LIA_Service_RemoteProxy( 4350): onServiceConnected() : Task Property for Informant - Activation:true, AutoExecution:true
V/LIA_Service_RemoteProxy( 4350): onServiceConnected() : Task Property for SmartMoment - Activation:true, AutoExecution:true
D/LIA_Service_RemoteSessionManager( 4350): New RemoteProxy received and try to update proxy map ...
I/LIA_Service_RemoteSessionManager( 4350): Added task & RemoteProxy: TermExtraction, com.lge.ia.manager.remote.RemoteProxy@11fc4cfb
I/LIA_Service_RemoteSessionManager( 4350): Added task & RemoteProxy: UIMAgent, com.lge.ia.manager.remote.RemoteProxy@11fc4cfb
I/LIA_Service_RemoteSessionManager( 4350): Added task & RemoteProxy: Informant, com.lge.ia.manager.remote.RemoteProxy@11fc4cfb
I/LIA_Service_RemoteSessionManager( 4350): Added task & RemoteProxy: SmartMoment, com.lge.ia.manager.remote.RemoteProxy@11fc4cfb
V/LIA_Service_RemoteSessionManager( 4350): Trying to register task(s) to LIACore ...
D/LIA_Service_TaskLauncher( 4350): register() - main launcher : true
D/LIA_Service_TaskLauncher( 4350): --> TermExtraction is registered on LIACores
D/LIA_Service_TaskLauncher( 4350): register() - main launcher : true
D/LIA_Service_TaskLauncher( 4350): --> UIMAgent is registered on LIACores
D/LIA_Service_TaskLauncher( 4350): register() - main launcher : true
D/LIA_Service_TaskLauncher( 4350): --> Informant is registered on LIACores
D/LIA_Service_TaskLauncher( 4350): --> Informant is auto execution task. Try to run ...
D/LIA_Service_TaskLauncher( 4350): runTask - main launcher : true
D/LIA_Service_RemoteSessionManager( 4350): runTask() : Informant
D/LIA_Service_RemoteProxy( 4350): runTask() : Task name & RemoteProxy - Informant, com.lge.ia.manager.remote.RemoteProxy@11fc4cfb
I/LIA_Service_LogTracer( 4350): [Log Tracer - Task State Transition] runTask(Informant)...... 
,D/LIA_Informant_LIARemoteManager( 7154): runTask() : Informant
D/LIA_Informant_TaskLauncher( 7154): runTask - main launcher : false
,V/LIA_Informant_TaskContext( 7154): runSession() : Informant
D/LIA_Informant_LIARemoteService( 7154): getTask()
D/LIA_Informant_TaskSession( 7154): TaskSession.of() - thread id : 250, thread name : Binder_1
,D/LIA_S4URecommender_S4URecommenderTask( 7154): handleMessage : 1002
D/LIA_S4URecommender_S4URecommenderTask( 7154): Connected to ActionManager Service
,D/ActionManagerService( 4287): Messenger is registered - action id mask=0x43e00
I/LIA_Informant_LogTracer( 7154): [Log Tracer - Task State Transition] create(Informant)...... Request
I/LIA_Informant_InformantTask( 7154): [Binder_1] create!!!!!!
,I/LIA_Informant_LogTracer( 7154): [Log Tracer - Task State Transition] create(Informant)...... Success
I/LIA_Informant_TaskSession( 7154): Informant task is created !!
I/LIA_Informant_TaskSession( 7154): Informant create() process time = 2 msec
D/LIA_Informant_TaskSession( 7154): enable() - enable state : false, thread id : 250, thread name : Binder_1
,I/LIA_Informant_LogTracer( 7154): [Log Tracer - Task State Transition] start(Informant)...... Request
,I/LIA_Informant_InformantTask( 7154): [pool-3-thread-1] task start!!!!
D/LIA_Informant_InformantManager( 7154): [pool-3-thread-1] start
,D/LIA_Informant_ActionManagerMessageHandler( 7154): [pool-3-thread-1] start
,D/LIA_Informant_ActionManagerMessageHandler( 7154): [pool-3-thread-1] new actionCategoryID = 17053184
D/LIA_Informant_ActionManagerMessageHandler( 7154): [pool-3-thread-1] connectActionManager
,I/LIA_Informant_ActionManagerMessageHandler( 7154): [ActionManagerHandler] connect ActionManager: action id mask = 0x1043600
,D/a       ( 5096): Opening database auth.proximity.permit_store...
,D/ActionManager( 7154): connecting to ActionManagerService...
,D/ActionManager( 7154): connected to ActionManagerService.
,D/LIA_Informant_ActionManagerMessageHandler( 7154): [ActionManagerHandler] handleMessage: what(1002) actionID(0x0)
D/LIA_Informant_ActionManagerMessageHandler( 7154): [ActionManagerHandler] ActionManager connected!!!!
D/LIA_Informant_InformantManager( 7154): [ActionManagerHandler] ActionManager onConnected
I/LIA_Informant_ConciergeCardManager( 7154): [ActionManagerHandler] start
I/LIA_Informant_ConciergeCardManager( 7154): [ActionManagerHandler] setState = 0
I/LIA_Informant_TaskSession( 7154): Informant start() result: true, process time = 11 msec
I/LIA_Informant_LogTracer( 7154): [Log Tracer - Task State Transition] start(Informant)...... Success
I/LIA_Informant_TaskSession( 7154): enable() - enable state : true
D/LIA_Informant_ConciergeCardManager( 7154): [ActionManagerHandler] registerActionEventListener
I/LIA_Informant_ActionManagerMessageHandler( 7154): [ActionManagerHandler] registerListener = concierge_card
I/LIA_Informant_ActionManagerMessageHandler( 7154): [ActionManagerHandler] after add numListener = 1
D/LIA_Informant_TaskContext( 7154): runSeesion() succeeded.
D/LIA_Informant_TaskLauncher( 7154): runTask - succeeded.
D/LIA_Service_TaskLauncher( 4350): register() - main launcher : true
D/LIA_Service_TaskLauncher( 4350): --> SmartMoment is registered on LIACores
D/LIA_Service_TaskLauncher( 4350): --> SmartMoment is auto execution task. Try to run ...
D/LIA_Service_TaskLauncher( 4350): runTask - main launcher : true
D/LIA_Service_RemoteSessionManager( 4350): runTask() : SmartMoment
D/LIA_Service_RemoteProxy( 4350): runTask() : Task name & RemoteProxy - SmartMoment, com.lge.ia.manager.remote.RemoteProxy@11fc4cfb
I/LIA_Service_LogTracer( 4350): [Log Tracer - Task State Transition] runTask(SmartMoment)...... 
,D/ActionManagerService( 4287): Messenger is registered - action id mask=0x1043600
D/LIA_Informant_LIARemoteManager( 7154): runTask() : SmartMoment
D/LIA_Informant_TaskLauncher( 7154): runTask - main launcher : false
V/LIA_Informant_TaskContext( 7154): runSession() : SmartMoment
D/LIA_Informant_LIARemoteService( 7154): getTask()
,D/LIA_Informant_TaskSession( 7154): TaskSession.of() - thread id : 251, thread name : Binder_2
I/LIA_Informant_LogTracer( 7154): [Log Tracer - Task State Transition] create(SmartMoment)...... Request
D/LIA_Informant_SmartMomentTask( 7154): create
,I/LIA_Informant_LogTracer( 7154): [Log Tracer - Task State Transition] create(SmartMoment)...... Success
I/LIA_Informant_TaskSession( 7154): SmartMoment task is created !!
I/LIA_Informant_TaskSession( 7154): SmartMoment create() process time = 1 msec
D/LIA_Informant_TaskSession( 7154): enable() - enable state : false, thread id : 251, thread name : Binder_2
I/LIA_Informant_LogTracer( 7154): [Log Tracer - Task State Transition] start(SmartMoment)...... Request
,D/LIA_Informant_SmartMomentTask( 7154): start
,I/LIA_Informant_BoardStateUtil( 7154): isEnabledConciergeBoard() : count > 0 - true
I/LIA_Informant_ConciergeCardManager( 7154): [ActionManagerHandler] ConciergeBoard On!!!
I/LIA_Informant_ConciergeCardManager( 7154): [ActionManagerHandler] getState = 0
I/LIA_Informant_ConciergeCardManager( 7154): [ActionManagerHandler] setState = 1
D/LIA_Informant_ConciergeCardManager( 7154): [ActionManagerHandler] startFlowManager key = concierge_weather_briefing
D/LIA_Informant_FlowManagerPlant( 7154): [ActionManagerHandler] WEATHER_BRIEFING
,D/LIA_Informant_SmartMoment_Entropy_AppEntropyFlowManager( 7154):  AppEntropyFlowManager -> SmartMomentEngineType : TYPE_SMARTTIPS
,I/LIA_Informant_FlowManagerPlant( 7154): [ActionManagerHandler] ConciergeScript serverMode = OP_SERVER
,D/LIA_Informant_SmartMoment_Entropy_AppEntropyFlowManager( 7154): [SMARTTIPS] start() - 0.1.8, 2015.03.26
D/LIA_Informant_SmartMoment_Entropy_AppEntropyFlowManager( 7154): [SMARTTIPS] start (period : 4)
D/LIA_Informant_LDBAccessManager( 7154): LDBAccessManager
D/LIA_Informant_ArchiveManager( 7154): ArchiveManager
D/LIA_Informant_SmartMoment_Entropy_MonitoringTimeScheduler( 7154): [SMARTTIPS] start() : type_smarttips
,D/LIA_Informant_SmartMoment_Entropy_AppEntropyFlowManager( 7154): [SMARTTIPS]  start() : period >= AppEntropyUtil.ANALYSIS_PERIOD_MIN
,D/LIA_Informant_SmartMoment_Entropy_AppEntropyFlowManager( 7154): [SMARTTIPS] already have analyzed result the same time.
D/LIA_Informant_SmartMoment_Entropy_AppEntropyFlowManager( 7154): [SMARTTIPS] analyzedResult = com.lge.ia.task.smartmoment.entropy.item.AnalyzedResultItem@1451ea5c
D/LIA_Informant_SmartMoment_Entropy_AppEntropyFlowManager( 7154): [SMARTTIPS] Alanlyzed result already exists.
D/LIA_Informant_SmartMoment_Entropy_MonitoringTimeScheduler( 7154): [SMARTTIPS] setAlarm() : AlarmType = START_MONITORING, monitoringType = AFTERNOON
,D/LIA_Informant_SmartMoment_Entropy_MonitoringTimeScheduler( 7154): [SMARTTIPS]  alarmManager.set() : alarmTime = 1457434800582
I/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : without handler
,D/LIA_Informant_BirthdayTimeNoticeFlowManager( 7154): BirthdayTimeNoticeFlowManager
D/LIA_Informant_LDBAccessManager( 7154): LDBAccessManager
,D/LIA_Informant_BirthdayDBManager( 7154): BirthdayDBManager
D/LIA_Informant_BirthdayDBHelper( 7154): BirthdayDBHelper
D/LIA_Informant_CTP_DBConnectionManagerAndroid( 7154):  setAndroidResource:  null
D/LIA_Informant_CTP_CallbackTimePredictorCoreAndroid( 7154): CallbackTimePredictorCore Engine start
D/LIA_Informant_CTP_CallbackTimePredictorCoreAndroid( 7154): mode: 0, null
D/LIA_Informant_CTP_DBConnectionManagerAndroid( 7154):  setAndroidResource:  null
,D/LIA_Informant_CTP_PredictorThread( 7154):  creator!!
D/LIA_Informant_CTP_CallbackTimePredictorCoreAndroid( 7154): startPredictorThread enters!!!!
D/LIA_Informant_CTP_CallbackTimePredictorAndroidDBHelper( 7154): /data/data/com.lge.ia.task.informant/  is created!!!
D/LIA_Informant_CTP_CallbackTimePredictorAndroidDBHelper( 7154): /data/data/com.lge.ia.task.informant/  is created!!!
D/LIA_Informant_CTP_CallbackTimePredictorAndroidDBHelper( 7154): /data/data/com.lge.ia.task.informant/SmartMoment/CallbackTiming.db
D/LIA_Informant_CTP_PredictorThread( 7154): init() enters!!
E/NetlinkEvent(  415): NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
E/NetlinkEvent(  463): NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
E/NetlinkEvent(  415): NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
E/NetlinkEvent(  463): NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
D/LIA_Informant_CTP_NaiveBayes( 7154): CallbackTimePredictorDBAccess: com.lge.s4u.DB.Android.CallbackTimePredictorDBAccessAndroid@19415048
D/LIA_Informant_CTP_MaxTimeConstraintReceiver( 7154): MaxTimeConstraintReceiver creator!!
D/LIA_Informant_CTP_PredictorThread( 7154): initPrefereces start!!
D/KeyguardUpdateMonitor( 3410): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 3410): onReceive = com.lge.android.intent.action.BATTERYEX
D/PowerService( 4163): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 3410): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 3410): On Skip Timer : true
D/LIA_Informant_CTP_PredictorThread( 7154): initPrefereces end
D/LIA_Informant_CTP_PredictorThread( 7154): threshold: 0.7
D/LIA_Informant_CTP_PredictorThread( 7154): trackingIdArray:
D/LIA_Informant_CTP_MultipleSensorDetector( 7154): MultipleSensorDetector Start!!! OK~
D/LIA_Informant_CTP_PredictorThread( 7154):  run() enters!!!! Looper.prepare() is done 
D/LIA_Informant_CTP_PredictorThread( 7154): run()  - startCallStateReceiver is instantiated!!
D/SensorManager( 7154): found sensor: LGE Accelerometer, handle=0
D/SensorManager( 7154): found sensor: LGE Magnetometer, handle=10
D/SensorManager( 7154): found sensor: LGE Magnetometer Uncalibrated, handle=11
D/SensorManager( 7154): found sensor: LGE Gyroscope, handle=2
D/SensorManager( 7154): found sensor: LGE Gyroscope Uncalibrated, handle=8
D/SensorManager( 7154): found sensor: LGE Proximity, handle=48
D/SensorManager( 7154): found sensor: LGE Knock-on Proximity Sensor, handle=74
D/SensorManager( 7154): found sensor: LGE Virtual Proximity Sensor, handle=75
D/SensorManager( 7154): found sensor: LGE Light, handle=1
D/SensorManager( 7154): found sensor: LGE Pressure, handle=3
D/SensorManager( 7154): found sensor: LGE Accelerometer -Wakeup Secondary, handle=17
D/SensorManager( 7154): found sensor: LGE Magnetometer -Wakeup Secondary, handle=26
D/SensorManager( 7154): found sensor: LGE Magnetometer Uncalibrated -Wakeup Secondary, handle=27
D/SensorManager( 7154): found sensor: LGE Gyroscope -Wakeup Secondary, handle=19
D/SensorManager( 7154): found sensor: LGE Gyroscope Uncalibrated -Wakeup Secondary, handle=24
D/SensorManager( 7154): found sensor: LGE Proximity -Non Wakeup Secondary, handle=67
D/SensorManager( 7154): found sensor: LGE Light -Wakeup Secondary, handle=18
D/SensorManager( 7154): found sensor: LGE Pressure -Wakeup Secondary, handle=20
D/SensorManager( 7154): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7154): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7154): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7154): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7154): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7154): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7154): found sensor: LGE Game Rotation Vector Sensor, handle=50
D/SensorManager( 7154): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7154): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7154): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7154): found sensor: Gravity -Wakeup Secondary, handle=60
D/SensorManager( 7154): found sensor: Linear Acceleration -Wakeup Secondary, handle=61
D/SensorManager( 7154): found sensor: Rotation Vector -Wakeup Secondary, handle=62
D/SensorManager( 7154): found sensor: Step Detector -Wakeup Secondary, handle=65
D/SensorManager( 7154): found sensor: Step Counter -Wakeup Secondary, handle=66
D/SensorManager( 7154): found sensor: Game Rotation Vector -Wakeup Secondary, handle=63
D/SensorManager( 7154): found sensor: GeoMagnetic Rotation Vector -Wakeup Secondary, handle=64
D/SensorManager( 7154): found sensor: Orientation -Wakeup Secondary, handle=59
D/SensorManager( 7154): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7154): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7154): found sensor: Motion Accel, handle=46
I/SensorManager( 7154): registerListenerImpl() [Sensor: LGE Step Counter Sensor, Rate: 30000000, SensorEventListener: com.lge.s4u.core.algorithm.detector.sensor.android.StepCounterDetected@2c4ecac7] by com.lge.s4u.core.algorithm.detector.sensor.android.StepCounterDetected.start():84
D/sensors_hal_SAM( 1282): batch:sensor(android.sensor.step_counter) handle:44 freq:1.000000 report_rate_f:0.003333                        report_rate_Q16:218 batch_rate:218 max:1.000000 min:0.000275
D/sensors_hal_StepCounter( 1282): enable: handle=44, freq=1.000000 report_rate=65536 batch_rate=218                     batched=1 wakeup 0
I/sensors_hal_SAM( 1282): sendEnableReq:sensor(android.sensor.step_counter) Sending enable to svc no:37
D/sensors_hal_Util( 1282): waitForResponse: timeout=1000
D/sensors_hal_StepCounter( 1282): processResp: Received SNS_SAM_PED_ENABLE_RESP_V01
D/sensors_hal_StepCounter( 1282): enable: Received Response: 0
I/sensors_hal_StepCounter( 1282): sendGetReportReq: handle:44
I/LIA_Informant_CTP_StepCounterDetected( 7154): StepCounter sensor available! ==> true and isBatchModeSupported ==> true
D/LIA_Informant_LDBAccessManager( 7154): LDBAccessManager
D/sensors_hal_StepCounter( 1282): processResp: Received SNS_SAM_PED_GET_REPORT_RESP_V01
D/sensors_hal_StepCounter( 1282): processInd: SNS_SAM_PED_GET_REPORT_RESP_V01
I/sensors_hal_StepCounter( 1282): processInd: STEP COUNTER: step is 0, running_total 0 TS:42621939565
D/sensors_hal_Ctx( 1282): poll:polldata:1, sensor:44, type:19, x:0.000000 y:0.000000 z:0.000000
D/sensors_hal_Util( 1282): waitForResponse: timeout=0
D/LIA_Informant_CTP_StepCounterDetected( 7154): currentStep: 0.0
D/LIA_Informant_CTP_StepCounterDetected( 7154): currentStep: 0.0
D/LIA_Informant_CTP_PredictorThread( 7154): createSensorConditionDetector()  - MultipleSensorDetector.start() is called!!
I/LIA_Informant_TaskSession( 7154): SmartMoment start() result: true, process time = 54 msec
I/LIA_Informant_LogTracer( 7154): [Log Tracer - Task State Transition] start(SmartMoment)...... Success
I/LIA_Informant_TaskSession( 7154): enable() - enable state : true
D/LIA_Informant_TaskContext( 7154): runSeesion() succeeded.
D/LIA_Informant_TaskLauncher( 7154): runTask - succeeded.
I/LIA_Service_RemoteSessionManager( 4350): RemoteProxyMap Size : 5
I/LIA_Service_RemoteSessionManager( 4350): RemoteProxyMap : com.lge.ia.task.informant [key: TermExtraction]
I/LIA_Service_RemoteSessionManager( 4350): RemoteProxyMap : com.lge.ia.task.s4urecommender [key: S4URecommender]
I/LIA_Service_RemoteSessionManager( 4350): RemoteProxyMap : com.lge.ia.task.informant [key: UIMAgent]
I/LIA_Service_RemoteSessionManager( 4350): RemoteProxyMap : com.lge.ia.task.informant [key: Informant]
I/LIA_Service_RemoteSessionManager( 4350): RemoteProxyMap : com.lge.ia.task.informant [key: SmartMoment]
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - b1009337-1c5e-41c7-b3be-dd08f876b9ad
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - b1009337-1c5e-41c7-b3be-dd08f876b9ad / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - f258fb14-5c4a-4724-a87f-42e177b4cb27
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - f258fb14-5c4a-4724-a87f-42e177b4cb27 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 27740ffc-92e1-444b-b834-7b48aa475f14
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 27740ffc-92e1-444b-b834-7b48aa475f14 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 52ec428d-7393-4001-afb9-0ba5819a88c6
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 52ec428d-7393-4001-afb9-0ba5819a88c6 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 32799bcb-e93d-4f84-bdd1-ebb2c0c28d2b
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 32799bcb-e93d-4f84-bdd1-ebb2c0c28d2b / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 64141475-5e7b-4eb6-a8c8-b4680e8ae087
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 64141475-5e7b-4eb6-a8c8-b4680e8ae087 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 3bc70a07-f049-40ba-9a79-d76bd725487e
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 3bc70a07-f049-40ba-9a79-d76bd725487e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,V/sensors_hal_Light( 1282): processReportInd: 60000 6.000000
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 57119a5b-8761-41b6-bb70-94581d8a6581
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 57119a5b-8761-41b6-bb70-94581d8a6581 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,E/CloudHub( 7798): [DATABASE][DBConnection|getUserId] User id: 0
,E/CloudHub( 7798): [DATABASE][DBConnection|getDatabasePath] Database path: /data/user/0/com.lge.cloudhub/databases/cloudhub.db
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - a549f1df-1fe2-40b4-8635-2c81bd3cac8d
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - a549f1df-1fe2-40b4-8635-2c81bd3cac8d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 2e22a147-f7a8-4b2b-a14e-bea09727a0ae
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 2e22a147-f7a8-4b2b-a14e-bea09727a0ae / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - f6271f92-ed41-4c69-84f5-606c892300d1
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - f6271f92-ed41-4c69-84f5-606c892300d1 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - c542ba5a-0592-4bfd-8bf5-cfac37a860d7
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - c542ba5a-0592-4bfd-8bf5-cfac37a860d7 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
V/DownloadManager( 6539): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
V/DownloadManager( 6539): created cursor android.database.sqlite.SQLiteCursor@1aceaa92 on behalf of 7798
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 1ff642a8-b124-4df5-b3c1-33d817a4e60e
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 1ff642a8-b124-4df5-b3c1-33d817a4e60e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - d4a43d35-4df8-45ad-b61c-eda0af248a43
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - d4a43d35-4df8-45ad-b61c-eda0af248a43 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - b8208147-f5ec-4164-8055-a2468ab10f20
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - b8208147-f5ec-4164-8055-a2468ab10f20 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,I/GoogleHttpClient( 4748): GMS http client unavailable, use old client
,V/AudioFlinger(  468): thread 0xf1c47000 type 0 TID 3227 going to sleep
,V/AudioFlinger(  468): thread 0xf1c91000 type 0 TID 3229 going to sleep
,V/AudioFlinger(  468): thread 0xf57ab000 type 0 TID 3226 going to sleep
,I/ActivityManager( 1282): Start proc 7836:com.lge.lgfota.permission/1000 for broadcast com.lge.lgfota.permission/.DmcTargetValidationReceiver
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - bd4db121-0001-4931-89ef-88b98a345bd6
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - bd4db121-0001-4931-89ef-88b98a345bd6 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - ec633e7c-a5f5-44af-8f55-576dc760628f
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - ec633e7c-a5f5-44af-8f55-576dc760628f / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 0f9b97a4-1484-4249-974c-965230f18910
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 0f9b97a4-1484-4249-974c-965230f18910 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 41f56ba5-fe4e-4635-92f8-e32f4b1dcc33
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 41f56ba5-fe4e-4635-92f8-e32f4b1dcc33 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 5904f973-cb93-457e-ace8-f5c17155a91b
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 5904f973-cb93-457e-ace8-f5c17155a91b / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - e1cce721-867f-4e81-bb7b-0da00da8de38
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - e1cce721-867f-4e81-bb7b-0da00da8de38 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 1a58bab3-b209-4d0d-b3cc-fd9746b13604
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 1a58bab3-b209-4d0d-b3cc-fd9746b13604 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 23e25e28-2482-444d-a297-1e28d403844e
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 23e25e28-2482-444d-a297-1e28d403844e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/TARGETVALIDLATION_RECEIVER( 7836): TargetValidationReceiver_ACTION_BOOT_COMPLETETED Received
,I/ActivityManager( 1282): Killing 7075:com.lge.formmanager/u0a49 (adj 15): empty #22
,D/TARGETVALIDLATION_RECEIVER( 7836): updateFlag = new File(TARGET_FLAG_PATH)
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - a3134ff3-9cdf-48e0-ad40-d6f420a5ce40
D/TARGETVALIDLATION_RECEIVER( 7836): Do Not display result dialog. it is not used Update Tool!!
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - a3134ff3-9cdf-48e0-ad40-d6f420a5ce40 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,I/jxcore-log( 7557): getBuffer is called!!!!
I/jxcore-log( 7557): 
,V/sensors_hal_Light( 1282): processReportInd: 60000 6.000000
,I/ActivityManager( 1282): Start proc 7856:com.lge.hiddenmenu/1000 for broadcast com.lge.hiddenmenu/.ModemProtocol.L5000LoggingReceiver
,I/ActivityManager( 1282): Killing 5151:com.google.android.gms/u0a6 (adj 15): empty #22
,D/ConnectivityService( 1282): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@fb90daf)
D/ConnectivityService( 1282): dumpNetworkRequest
,D/ConnectivityService( 1282):     NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,fe80::a239:f7ff:fe6f:c95d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60}  everValidated{true}  lastValidated{true}  created{true}  explicitlySelected{false} }
D/ConnectivityService( 1282):     Requests:
D/ConnectivityService( 1282):         NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1282):         NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1282):         NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1282):     Lingered:
D/ConnectivityService( 1282): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1282): sending notification RELEASED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService( 1282): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 3132b7ca-fa19-4d73-9705-2cb57fbec8df
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 3132b7ca-fa19-4d73-9705-2cb57fbec8df / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,W/ResourcesManager( 7856): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7856): Asset path '/system/framework/lgsvcitems.jar' does not exist or contains no resources.
W/ResourcesManager( 7856): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 673d67a7-2d43-4961-b400-d3ed5b8e61e8
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 673d67a7-2d43-4961-b400-d3ed5b8e61e8 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 8fbc4b27-668a-45d0-b0d4-fe7617f7a9a0
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 8fbc4b27-668a-45d0-b0d4-fe7617f7a9a0 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 1182da2f-bc57-43c4-910b-613712644e30
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 1182da2f-bc57-43c4-910b-613712644e30 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/SMSNvReceiver( 7856): onReceive
,V/sensors_hal_Light( 1282): processReportInd: 60000 6.000000
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 0de30ba8-3b34-491e-86a1-f1c530b51d64
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 0de30ba8-3b34-491e-86a1-f1c530b51d64 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
I/[SMS_AD]( 7856): Intent action: android.intent.action.BOOT_COMPLETED
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
I/ActivityManager( 1282): Killing 7238:com.android.managedprovisioning/u0a43 (adj 15): empty #22
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 48df9194-53e8-4edc-954b-96b4e091b2fc
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 48df9194-53e8-4edc-954b-96b4e091b2fc / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,V/LGSC    ( 5446): [104] 401
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
I/ActivityManager( 1282): Waited long enough for: ServiceRecord{2fec18cb u0 com.lge.sizechangable.musicwidget.widget/.service.MusicWidgetUpdater}
V/LGSC    ( 4225): [101] 102, action=android.intent.action.BOOT_COMPLETED, iccState=null
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - d19c611a-6540-426e-9814-f39d7cbf3168
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - d19c611a-6540-426e-9814-f39d7cbf3168 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,I/ActivityManager( 1282): Start proc 7877:com.lge.sizechangable.weather.platform/u0a96 for broadcast com.lge.sizechangable.weather.platform/.receiver.WeatherPlatformCommonReceiver
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - c56e0e67-3470-499c-9b17-142622005681
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - c56e0e67-3470-499c-9b17-142622005681 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - a61d74fd-f974-4b1b-b660-4ada594333e2
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - a61d74fd-f974-4b1b-b660-4ada594333e2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - b9bec2d5-cc2b-4662-a72c-2711fe638f2b
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - b9bec2d5-cc2b-4662-a72c-2711fe638f2b / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - a608db5e-bafe-4ae9-909e-afed114d9b9e
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - a608db5e-bafe-4ae9-909e-afed114d9b9e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 08c542e6-6376-481f-be62-611270405932
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 08c542e6-6376-481f-be62-611270405932 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 2b91e03f-7dbf-4be9-888c-dc0f20376a68
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 2b91e03f-7dbf-4be9-888c-dc0f20376a68 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 8a3a7f6c-76a5-4731-ba75-430b3844617f
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 8a3a7f6c-76a5-4731-ba75-430b3844617f / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - b8d79fa1-9a6c-4130-9053-79db6eb1747d
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - b8d79fa1-9a6c-4130-9053-79db6eb1747d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 5afde72d-f0d8-468e-8ea1-b1a9c2e76738
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 5afde72d-f0d8-468e-8ea1-b1a9c2e76738 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 65bb3c86-a9db-4604-a1c9-d9fe50ef6790
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 65bb3c86-a9db-4604-a1c9-d9fe50ef6790 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - ddc94ad9-b03a-476f-9dfe-e5807eb53531
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - ddc94ad9-b03a-476f-9dfe-e5807eb53531 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 664cfe23-0b15-46f7-bb60-7cb96f1bd038
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 664cfe23-0b15-46f7-bb60-7cb96f1bd038 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,I/art     ( 7877): Almond Protected OAT
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - ce6e3e2a-4afe-4b30-b4a8-a3e3d19a896e
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - ce6e3e2a-4afe-4b30-b4a8-a3e3d19a896e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - c1d2622f-b7fc-4ee5-8ba9-f25cce3faf02
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - c1d2622f-b7fc-4ee5-8ba9-f25cce3faf02 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - d6ac4177-228c-4ca3-96fe-aa24c4bfc4a2
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - d6ac4177-228c-4ca3-96fe-aa24c4bfc4a2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 1a792a83-e47d-4c90-a2a2-4937c8dfcafb
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 1a792a83-e47d-4c90-a2a2-4937c8dfcafb / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/WeatherPlatformReceiver( 7877): start action : android.intent.action.BOOT_COMPLETED
D/WeatherPlatformReceiver( 7877): setNextUpdate
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/WeatherPlatform_Alarm( 7877): CurrentTime = 3/8 8:58:4
D/WeatherPlatform_Alarm( 7877): lastUpdatedTime = 1/1 1:0:0
D/WeatherPlatform_Alarm( 7877): RemainedTime = -404836:-58:-4
,D/WeatherPlatform_Alarm( 7877): Update is Canceled by com.lge.sizechangable.weather.action.autoupdate
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - c74543a1-23ee-4138-851d-816543e2f882
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - c74543a1-23ee-4138-851d-816543e2f882 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/WeatherPlatform_Alarm( 7877): Update is Canceled by com.lge.sizechangable.weather.action.update.currentonly
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/WeatherPlatform_Alarm( 7877): set auto-update time : 1/1 4:0:0
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 4190378c-4811-410a-bbf1-4c014a1380f0
D/WeatherPlatformReceiver( 7877): end action : android.intent.action.BOOT_COMPLETED : 10ms
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 4190378c-4811-410a-bbf1-4c014a1380f0 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,I/ActivityManager( 1282): Start proc 7899:com.lge.springcleaning/1000 for broadcast com.lge.springcleaning/.receiver.BootCompleteReceiver
,I/ActivityManager( 1282): Killing 7260:com.lge.appbox.client:AppBoxCommonService/u0a9 (adj 15): empty #22
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 287b97d5-2c50-4bee-bf54-890c05d714f3
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 287b97d5-2c50-4bee-bf54-890c05d714f3 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - a0ff4247-5118-4d66-90eb-7df8baa0f1fe
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - a0ff4247-5118-4d66-90eb-7df8baa0f1fe / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - c858f754-bfc3-44f5-8d8e-5794e530e624
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - c858f754-bfc3-44f5-8d8e-5794e530e624 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/BootCompleteReceiver( 7899): hasclipTray = true
,W/ContextImpl( 7899): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1804 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.lge.springcleaning.receiver.BootCompleteReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2701 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 8f8092b3-c00f-4529-9fa0-ccee6a777255
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 8f8092b3-c00f-4529-9fa0-ccee6a777255 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,I/ActivityManager( 1282): Start proc 7919:com.lge.springcleaning:AppCleanupService/1000 for service com.lge.springcleaning/.service.AppCleanupService
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,I/ActivityManager( 1282): Killing 7284:com.lge.voicerecorder/u0a41 (adj 15): empty #22
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - c1750b9a-5a54-4cc3-944a-fad793c4c259
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - c1750b9a-5a54-4cc3-944a-fad793c4c259 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,W/ContextImpl( 6451): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1804 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.qualcomm.atfwd.AtFwdAutoboot.onReceive:24 android.app.ActivityThread.handleReceiver:2701 
E/AtFwd AutoBoot( 6451): AtFwd Auto Boot Started Successfully
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 1af933bf-8670-451c-87e8-7c1b7ae9486a
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 1af933bf-8670-451c-87e8-7c1b7ae9486a / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,I/ActivityManager( 1282): Start proc 7939:com.lge.gnss.airtest/u0a80 for broadcast com.lge.gnss.airtest/.GnssAirTestReceiver
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
V/AppCleanupService( 7919): registerAlarm
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - a275957e-facb-4980-a59f-1e9453f4cafa
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - a275957e-facb-4980-a59f-1e9453f4cafa / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - a6a5fcb3-8518-4985-8a0c-7ad44e963154
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - a6a5fcb3-8518-4985-8a0c-7ad44e963154 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/AppCleanupService( 7919): noticeInterval = 2674800000
D/AppCleanupService( 7919): notiDateStr = 2016-03-27 17:35:59
,D/AppCleanupService( 7919): noticeStart = 2016-03-27 17:35:59
,D/AppCleanupService( 7919): noticeStart = 1459092959000
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 55d6b5cf-0708-4575-8ef0-65a5f6e1ff0d
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 55d6b5cf-0708-4575-8ef0-65a5f6e1ff0d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - e74ed1c1-8ac9-40ce-88c2-d6a654574c60
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - e74ed1c1-8ac9-40ce-88c2-d6a654574c60 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 5a73105e-90d9-4e0b-93a4-2d5eb53d45bb
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 5a73105e-90d9-4e0b-93a4-2d5eb53d45bb / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/AppUsageDbAdapter( 7919): initPreloadedAppToTheDB() : row count = 258
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
,D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 5e812aab-280e-4435-b506-ed5a3f9f9580
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 5e812aab-280e-4435-b506-ed5a3f9f9580 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/AirTest ( 7939): Set airtest_enable to false
,I/ActivityManager( 1282): Killing 6278:com.lge.appbox.client/u0a9 (adj 15): empty #22
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 99c097ff-6324-4404-8a7b-36ad2e9099ba
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 99c097ff-6324-4404-8a7b-36ad2e9099ba / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,I/art     ( 1282): Explicit concurrent mark sweep GC freed 67103(3MB) AllocSpace objects, 3(276KB) LOS objects, 33% free, 62MB/94MB, paused 1.650ms total 171.672ms
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - cf6e9aa1-8414-4f1f-9735-4f1ed185f03b
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - cf6e9aa1-8414-4f1f-9735-4f1ed185f03b / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 44ac4a1b-f7df-434f-9acb-340a4c8bf53a
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 44ac4a1b-f7df-434f-9acb-340a4c8bf53a / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - bc6cabce-23cf-44cf-be8c-8e683e2a6511
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - bc6cabce-23cf-44cf-be8c-8e683e2a6511 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 1f14cdd0-97be-4b45-9914-f08fc4b3c8d2
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 1f14cdd0-97be-4b45-9914-f08fc4b3c8d2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/PhoneInterfaceManager( 4225): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: 2147483643, result: false
,I/LockScreenSettings( 7606): Received Broadcast : android.intent.action.BOOT_COMPLETED
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 2e924b26-5222-4f81-a202-762c1e34be4c
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 2e924b26-5222-4f81-a202-762c1e34be4c / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
I/LockScreenSettings( 7606): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/PhoneInterfaceManager( 4225): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: 2147483643, result: false
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - ef3f3e5c-b8d3-4cad-b358-1b2cb4884687
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - ef3f3e5c-b8d3-4cad-b358-1b2cb4884687 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - dfd63267-835a-4eda-a321-3bee2c8b0b88
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - dfd63267-835a-4eda-a321-3bee2c8b0b88 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - a94f9dab-0d80-46d2-b5ff-7278318a3d4b
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - a94f9dab-0d80-46d2-b5ff-7278318a3d4b / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,V/XDivert ( 4225): Action intent recieved:Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.qti.xdivert/.XDivert (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 4dee7d54-b854-40ef-b8b5-907c814bc96b
D/QcrilMsgTunnelAutoboot( 4867): ComponentInfo{com.qualcomm.qcrilmsgtunnel/com.qualcomm.qcrilmsgtunnel.QcrilMsgTunnelService} started successfully
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 4dee7d54-b854-40ef-b8b5-907c814bc96b / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,I/ActivityManager( 1282): Start proc 7963:com.lge.bnr/1000 for broadcast com.lge.bnr/.service.BNRBootReceiver
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 98226e59-5a46-4292-a127-573e15c4338c
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 98226e59-5a46-4292-a127-573e15c4338c / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 87b243b2-e8d3-455c-868c-bd0320642af1
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 87b243b2-e8d3-455c-868c-bd0320642af1 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 31ad7790-e021-4968-87de-a06f51f364de
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 31ad7790-e021-4968-87de-a06f51f364de / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 81cddcee-bbfd-4ad8-97bd-faa0b5301fef
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 81cddcee-bbfd-4ad8-97bd-faa0b5301fef / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - b03ef931-562d-405f-b5d0-ae590e52163b
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - b03ef931-562d-405f-b5d0-ae590e52163b / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - a201ffd3-d058-4684-8e23-9745806819de
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - a201ffd3-d058-4684-8e23-9745806819de / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 4eb008ee-9019-49cc-b88a-fb85c90f6601
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 4eb008ee-9019-49cc-b88a-fb85c90f6601 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 09cedf75-8e65-47d2-b65c-8e4a21bed284
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 09cedf75-8e65-47d2-b65c-8e4a21bed284 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,V/[BNRBootReceiver]( 7963): boot receiver action = android.intent.action.BOOT_COMPLETED
,V/[BNRBootReceiver]( 7963): set property sys.lge.bnrd = 1
V/[BNRBootReceiver]( 7963): End of BootComplted IF
V/[BNRBootReceiver]( 7963): Boot Receiver Return
V/[BNRBootCompletedThread]( 7963): run
W/MainApplication( 7963): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 927d41e6-ace1-435a-b6a1-b1430777d4dc
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 927d41e6-ace1-435a-b6a1-b1430777d4dc / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,W/linker  ( 7983): /system/bin/bnrd has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/bnrd    ( 7983): BNRD > wait starting [7983-4136038528] <
,E/bnrd    ( 7983): /data/data/.bnr_fifo_req
,V/[BNRBootCompletedThread]( 7963): End of BNRProcess
,V/[BNRBootCompletedThread]( 7963): End of BNRViaWifiProcess
,V/[BNRBootCompletedThread]( 7963): End of SpriteProcess
,V/[BNRBootCompletedThread]( 7963): exit
,I/ActivityManager( 1282): Start proc 7991:com.google.android.youtube/u0a124 for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver
,I/ActivityManager( 1282): Killing 7313:com.lge.smartconfig/1000 (adj 15): empty #22
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 6f350c72-efc6-4e61-8ca9-128590ada4c3
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 6f350c72-efc6-4e61-8ca9-128590ada4c3 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 2bc2feae-76de-41b3-96cb-29aef1d82d46
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 2bc2feae-76de-41b3-96cb-29aef1d82d46 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
,D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - d025c2dc-2403-4c58-8afb-b7044c47e6f0
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - d025c2dc-2403-4c58-8afb-b7044c47e6f0 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
,D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 7e755399-2d1e-46f7-b555-ac5717c782a5
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 7e755399-2d1e-46f7-b555-ac5717c782a5 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 62861828-0857-4aee-9bca-b3c50b3ba7db
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 62861828-0857-4aee-9bca-b3c50b3ba7db / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - ed6f533b-2544-4fa4-9f59-0d7e78288932
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - ed6f533b-2544-4fa4-9f59-0d7e78288932 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 7d167cc1-4e1f-4731-ad6d-34da062cbd9b
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 7d167cc1-4e1f-4731-ad6d-34da062cbd9b / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 596750fc-8a2c-4df2-aedf-9bbdbd307a46
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 596750fc-8a2c-4df2-aedf-9bbdbd307a46 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 94f48549-6edc-479c-bbdd-8817250b778f
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 94f48549-6edc-479c-bbdd-8817250b778f / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 278a99db-4070-4289-8a8f-698f63a66bda
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 278a99db-4070-4289-8a8f-698f63a66bda / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 31b72c81-9a22-4b2b-a6aa-a47b47514c93
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 31b72c81-9a22-4b2b-a6aa-a47b47514c93 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 0c7ef734-9d1d-4d30-b555-5185e961d058,
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 0c7ef734-9d1d-4d30-b555-5185e961d058 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm,
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 004e7126-d828-45f2-8db7-87cc51833ec6
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 004e7126-d828-45f2-8db7-87cc51833ec6 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 84bb5c65-45fe-43b8-a2d4-f796ea2c0556
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 84bb5c65-45fe-43b8-a2d4-f796ea2c0556 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 611782dd-1b85-4ad4-a0a7-65ea50c18137
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 611782dd-1b85-4ad4-a0a7-65ea50c18137 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - eeeca687-17ba-4496-8dfd-f9de2ddbfcbf
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - eeeca687-17ba-4496-8dfd-f9de2ddbfcbf / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 5186bb4b-0567-4d4e-a673-4e6d4c0999be
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 5186bb4b-0567-4d4e-a673-4e6d4c0999be / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 04f36d3f-c48d-45d5-8f07-10212d056e69
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 04f36d3f-c48d-45d5-8f07-10212d056e69 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - e22589bd-a788-4404-b626-cf8fc4aaee80
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - e22589bd-a788-4404-b626-cf8fc4aaee80 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 4092a9bd-3a85-4262-aa6c-aa824a29c1c2
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 4092a9bd-3a85-4262-aa6c-aa824a29c1c2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
,D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - bba919cd-b828-4cf9-a1fe-d11eeeb473a2
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - bba919cd-b828-4cf9-a1fe-d11eeeb473a2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - a44054ce-270b-4e36-93cc-84c22e4a9bca
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - a44054ce-270b-4e36-93cc-84c22e4a9bca / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 80e3e563-c2ae-468e-b3c5-304d3025b210
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 80e3e563-c2ae-468e-b3c5-304d3025b210 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - d8e78793-325e-4aa5-ac8d-228a603d0367
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - d8e78793-325e-4aa5-ac8d-228a603d0367 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - ceca4459-dae0-48ce-b519-53c970b9ec00
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - ceca4459-dae0-48ce-b519-53c970b9ec00 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - a0af8b25-cbbc-4a59-8051-507fc0e9b60d
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - a0af8b25-cbbc-4a59-8051-507fc0e9b60d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 171a03a2-d0ff-44e9-8246-c5698b0f7138
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 171a03a2-d0ff-44e9-8246-c5698b0f7138 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 03e83af4-0e5e-4d33-bda4-5775ac44f0c9
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 03e83af4-0e5e-4d33-bda4-5775ac44f0c9 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 73215c5a-3c90-46b8-a8d4-073b59c16f4c
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 73215c5a-3c90-46b8-a8d4-073b59c16f4c / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - b518486e-38d7-4c62-9ae6-103ebfc299c0
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - b518486e-38d7-4c62-9ae6-103ebfc299c0 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 595f748f-dd66-47e3-9b72-878813e08b17
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 595f748f-dd66-47e3-9b72-878813e08b17 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - ffb88a65-3c60-4fb8-a6e3-107504236874
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - ffb88a65-3c60-4fb8-a6e3-107504236874 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - e64a047e-c72b-42c0-8d3b-49c998d3dcd7
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - e64a047e-c72b-42c0-8d3b-49c998d3dcd7 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 457cc45a-d90a-4a2f-a84e-17a5a040e54d
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 457cc45a-d90a-4a2f-a84e-17a5a040e54d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,W/ActivityManager( 1282): getRunningAppProcesses: caller 10124 does not hold REAL_GET_TASKS; limiting output
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - b123c05d-baca-400e-a81f-1b9e03c3c0c0
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - b123c05d-baca-400e-a81f-1b9e03c3c0c0 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 0811f9de-123c-47d0-a96d-a5a378aa7346
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 0811f9de-123c-47d0-a96d-a5a378aa7346 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - deb9f079-8f54-4a32-820d-cbe1e7b8a2ab
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - deb9f079-8f54-4a32-820d-cbe1e7b8a2ab / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 869808e7-7467-4d4d-8ef3-38a11bdc7aa8
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 869808e7-7467-4d4d-8ef3-38a11bdc7aa8 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - b222fdb0-13b6-4364-8b77-0fe3d9b131b7
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - b222fdb0-13b6-4364-8b77-0fe3d9b131b7 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 151e475f-becf-4d00-8f48-d7dad0c500a6
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 151e475f-becf-4d00-8f48-d7dad0c500a6 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - c38523a3-5c05-4551-8d5c-60002cbdd666
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - c38523a3-5c05-4551-8d5c-60002cbdd666 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
W/ResourcesManager( 7991): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7991): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 7b05957e-dea2-43bc-9f10-e82b187b4825
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 7b05957e-dea2-43bc-9f10-e82b187b4825 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 37e24a4b-05bc-4cef-bccf-7048ddf00a8f
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 37e24a4b-05bc-4cef-bccf-7048ddf00a8f / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - b2f2840c-0331-482b-8a8c-275c5c7f7241
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - b2f2840c-0331-482b-8a8c-275c5c7f7241 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - debc2b4b-df02-4fc0-b223-3623910576d6
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - debc2b4b-df02-4fc0-b223-3623910576d6 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,V/JNIHelp ( 7991): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 9bc52120-dc53-4abf-8e05-3d8c591935eb
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 9bc52120-dc53-4abf-8e05-3d8c591935eb / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 2f2d55ad-71cf-47e5-b47f-a4026eff375d
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 2f2d55ad-71cf-47e5-b47f-a4026eff375d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - d29a559d-5c21-44ea-8e56-54907674eab8
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - d29a559d-5c21-44ea-8e56-54907674eab8 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 20361834-0923-49e2-bddf-83bd3f273a59
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 20361834-0923-49e2-bddf-83bd3f273a59 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - aafe78f8-e04e-42e6-ac74-a8d774918607
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - aafe78f8-e04e-42e6-ac74-a8d774918607 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - cb58d621-d69c-48fc-a189-313570a50797
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - cb58d621-d69c-48fc-a189-313570a50797 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 4829edec-e062-41e7-bc40-f2cf942a1bc6
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 4829edec-e062-41e7-bc40-f2cf942a1bc6 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 8e1331e3-0612-4a99-981d-ae79a3a483e3
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 8e1331e3-0612-4a99-981d-ae79a3a483e3 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,I/ProviderInstaller( 7991): Installed default security provider GmsCore_OpenSSL
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 88305298-5d49-42bb-b379-f58bfb74237e
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 88305298-5d49-42bb-b379-f58bfb74237e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 3431e8fb-688d-42d8-b044-4a0b31e09c2d
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 3431e8fb-688d-42d8-b044-4a0b31e09c2d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - bc6989b3-d9af-4f66-ad25-48f8feef1fac
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - bc6989b3-d9af-4f66-ad25-48f8feef1fac / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 4c6fc8e1-64b0-43bb-a8e6-31a5a8a3ccbd
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 4c6fc8e1-64b0-43bb-a8e6-31a5a8a3ccbd / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 834a078b-bbc3-433b-ad24-7374720abbca
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 834a078b-bbc3-433b-ad24-7374720abbca / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - b6035a83-4f7d-469d-ab0e-2c1b758f3cbb
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - b6035a83-4f7d-469d-ab0e-2c1b758f3cbb / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 57681a41-7b11-4000-bfc0-e4685d64f616
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 57681a41-7b11-4000-bfc0-e4685d64f616 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 518b673e-37b1-4fe5-a41e-bf6bd96bc45a
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 518b673e-37b1-4fe5-a41e-bf6bd96bc45a / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 493930b0-fba2-4e71-bbeb-980d846513c7
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 493930b0-fba2-4e71-bbeb-980d846513c7 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,V/AlarmManager( 1282): RTC_WAKEUP set : Alarm{3173a054 type 0 when 1457423885772 com.lge.myplace} when 1457423885772
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - bf9f7fb1-e1b0-4244-874f-e6e55488f0dd
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - bf9f7fb1-e1b0-4244-874f-e6e55488f0dd / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 1588a9c1-7816-486b-b709-ad4687ed104a
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 1588a9c1-7816-486b-b709-ad4687ed104a / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 2c9d6b36-f196-4d27-9cf9-1a05eacae44f
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 2c9d6b36-f196-4d27-9cf9-1a05eacae44f / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 7da46135-f30a-4cc7-a48e-7ed2469965fd
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 7da46135-f30a-4cc7-a48e-7ed2469965fd / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - ebc6f3d2-8e9b-4d52-a73a-26666c21bedb
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - ebc6f3d2-8e9b-4d52-a73a-26666c21bedb / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - de444991-6fae-41cf-88df-6ea89ae595f2
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - de444991-6fae-41cf-88df-6ea89ae595f2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 3544525f-7a46-43f3-b821-f5f925c91364
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 3544525f-7a46-43f3-b821-f5f925c91364 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - e66c4f6a-c6b2-49c4-9e5b-aa919a6d402e
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - e66c4f6a-c6b2-49c4-9e5b-aa919a6d402e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 01cecfcb-ca84-4a50-b919-65bc5b8b08d8
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 01cecfcb-ca84-4a50-b919-65bc5b8b08d8 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 763e4172-cd32-4e68-8bda-9b12a569ae07
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 763e4172-cd32-4e68-8bda-9b12a569ae07 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 2ae13f22-ce07-4e54-b9f2-e196e2e6aea1
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 2ae13f22-ce07-4e54-b9f2-e196e2e6aea1 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 1bc38bb4-707f-43e8-95e4-8357b03eb6bc
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 1bc38bb4-707f-43e8-95e4-8357b03eb6bc / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 74a589a7-7ae1-443d-a71c-3012a7490cf2
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 74a589a7-7ae1-443d-a71c-3012a7490cf2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 5dfcd78d-dca1-448b-a5e9-621d41a6911a
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 5dfcd78d-dca1-448b-a5e9-621d41a6911a / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 089b8ef7-36c5-48e2-a905-bc5678be5979
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 089b8ef7-36c5-48e2-a905-bc5678be5979 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 5f863214-316c-42c3-8398-856ba55e0382
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 5f863214-316c-42c3-8398-856ba55e0382 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 82b9a205-4fa0-4794-918b-a593bd4f33a9
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 82b9a205-4fa0-4794-918b-a593bd4f33a9 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 6eadfa52-9425-4717-99e8-1d4e907b2fee
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 6eadfa52-9425-4717-99e8-1d4e907b2fee / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - bdffc995-fc23-483a-8303-4600254e1a4e
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - bdffc995-fc23-483a-8303-4600254e1a4e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 2f501d59-657b-4647-87a9-d40b8df84ab7
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 2f501d59-657b-4647-87a9-d40b8df84ab7 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 91362f08-3471-4796-8261-4102ba5e06b6
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 91362f08-3471-4796-8261-4102ba5e06b6 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
,D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - d17bd42a-b0d6-4413-8657-613dedf877c1
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - d17bd42a-b0d6-4413-8657-613dedf877c1 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 3e01f7be-98e3-46aa-a43d-3ee68546da04
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 3e01f7be-98e3-46aa-a43d-3ee68546da04 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 2d313401-5b56-4def-81e9-af630f55c065
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 2d313401-5b56-4def-81e9-af630f55c065 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 9802f6c9-7e76-46b1-91a5-b9bf890bea1a
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 9802f6c9-7e76-46b1-91a5-b9bf890bea1a / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - a84e3c6d-b477-476b-b68e-456f670ccbcb
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - a84e3c6d-b477-476b-b68e-456f670ccbcb / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 741faada-69bc-45ee-b9c2-2accb6aed8f2
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 741faada-69bc-45ee-b9c2-2accb6aed8f2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
I/dex2oat ( 8022): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads1981932281.jar --oat-fd=32 --oat-location=/data/data/com.google.android.youtube/cache/ads1981932281.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 07dd7864-f444-40fe-8fdc-bf699e71c648
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 07dd7864-f444-40fe-8fdc-bf699e71c648 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - e172e70b-487f-42d2-9fd5-fa2e8bbeb957
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - e172e70b-487f-42d2-9fd5-fa2e8bbeb957 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
,D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 9377b7e6-9a10-4a39-bf14-0e18c9b9b223
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 9377b7e6-9a10-4a39-bf14-0e18c9b9b223 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,E/YouTube MDX( 7991): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 98424e47-20e8-4f6c-a819-b6a0bc4e9e0d
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 98424e47-20e8-4f6c-a819-b6a0bc4e9e0d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/libc-netbsd( 7991): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7991): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/dex2oat ( 8022): dex2oat took 38.522ms (threads: 6) arena alloc=300KB java alloc=12KB native alloc=1741KB free=6MB
,I/ActivityManager( 1282): Start proc 8039:com.google.android.gms/u0a6 for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 65e2d64b-6123-4b23-b870-87e398004426
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 65e2d64b-6123-4b23-b870-87e398004426 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 0c9220f3-5315-4dcc-a872-515bdb9047ca
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 0c9220f3-5315-4dcc-a872-515bdb9047ca / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - c8921f61-d72f-40f8-90da-5485d520eb11
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - c8921f61-d72f-40f8-90da-5485d520eb11 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - a101f2ed-29b3-437e-a70b-486a40e9fd71
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - a101f2ed-29b3-437e-a70b-486a40e9fd71 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - acdf2dd6-72d3-415a-9aee-eb0f72bd0470
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - acdf2dd6-72d3-415a-9aee-eb0f72bd0470 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 29f8335f-ebeb-4bc2-921f-8da2aecf36b2
W/ResourcesManager( 8039): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 29f8335f-ebeb-4bc2-921f-8da2aecf36b2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
W/ResourcesManager( 8039): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 6e72c836-d97d-495e-8423-9a7bc240e01a
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 6e72c836-d97d-495e-8423-9a7bc240e01a / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 54652804-c445-4d93-af00-b504c7632281
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 54652804-c445-4d93-af00-b504c7632281 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - f0c17726-3516-42b1-99a7-c068941871a2
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - f0c17726-3516-42b1-99a7-c068941871a2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - afdf2484-a5b0-449a-9d83-469c0cadbb48
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - afdf2484-a5b0-449a-9d83-469c0cadbb48 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/GmsApplication( 8039): Forcing legacy multidex for PROD_LMP build.
,I/MultiDex( 8039): VM with version 2.1.0 has multidex support
I/MultiDex( 8039): install
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - e55ed73c-2afa-4b73-bcc9-ac7cdd13350e
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - e55ed73c-2afa-4b73-bcc9-ac7cdd13350e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
I/MultiDex( 8039): MultiDexExtractor.load(/data/app/com.google.android.gms-1/base.apk, false)
,I/MultiDex( 8039): loading existing secondary dex files
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - cb5a2383-3379-4bcc-b551-4536e4b5b2c2
I/MultiDex( 8039): load found 3 secondary dex files
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - cb5a2383-3379-4bcc-b551-4536e4b5b2c2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - a8b46284-cbf4-44bd-ac5b-4e81473520bd
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - a8b46284-cbf4-44bd-ac5b-4e81473520bd / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 396123ce-dbf7-4cc0-ab2e-d8f533b3c9b3
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 396123ce-dbf7-4cc0-ab2e-d8f533b3c9b3 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,I/MultiDex( 8039): install done
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - f1333028-d927-43ed-9c9e-e2b702673fa9
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - f1333028-d927-43ed-9c9e-e2b702673fa9 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,W/ActivityManager( 1282): getRunningAppProcesses: caller 10124 does not hold REAL_GET_TASKS; limiting output
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 1b71813e-78ba-44f6-81bb-ba108c400456
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 1b71813e-78ba-44f6-81bb-ba108c400456 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - d85031a6-3afb-4890-9152-9a157c738d35
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - d85031a6-3afb-4890-9152-9a157c738d35 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 8e52cffe-8cdb-449d-b707-9663d0796ec9
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 8e52cffe-8cdb-449d-b707-9663d0796ec9 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 269419bd-8393-4a13-bc0f-00657cd015d5
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 269419bd-8393-4a13-bc0f-00657cd015d5 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 9f130368-95f1-44ae-8366-1fa6fce0498b
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 9f130368-95f1-44ae-8366-1fa6fce0498b / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 78bbbf3c-373f-4771-ae86-0ba66933d381
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 78bbbf3c-373f-4771-ae86-0ba66933d381 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 2aa4c3f6-93fb-4d41-868c-12322edfc4a6
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 2aa4c3f6-93fb-4d41-868c-12322edfc4a6 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - ef259041-18f9-4c0f-9e07-1d395e4f60d7
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - ef259041-18f9-4c0f-9e07-1d395e4f60d7 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 6da5e912-3d51-48dc-90ca-c86cc01cb687
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 6da5e912-3d51-48dc-90ca-c86cc01cb687 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 03e01b19-0c10-45ed-b89d-f3c0c5f751aa
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 03e01b19-0c10-45ed-b89d-f3c0c5f751aa / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - b7800d3a-015f-4cde-8d6b-1f5ef3687991
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - b7800d3a-015f-4cde-8d6b-1f5ef3687991 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 3edc9206-7a1b-4640-9209-30108ef8c2e0
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 3edc9206-7a1b-4640-9209-30108ef8c2e0 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - ea97011e-ea1f-4943-b4e4-83e855f851e5
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - ea97011e-ea1f-4943-b4e4-83e855f851e5 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 264fc4a9-7da2-4057-9f66-6e3edf523ad2
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 264fc4a9-7da2-4057-9f66-6e3edf523ad2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 773b6064-318b-4264-bd4e-23a7f09331d0
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 773b6064-318b-4264-bd4e-23a7f09331d0 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - c7ed03f4-d69e-4b71-ba70-3bccad2c2ea4
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - c7ed03f4-d69e-4b71-ba70-3bccad2c2ea4 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm,
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 3aa655f7-13e4-4005-a013-ef85ee744b8a
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 3aa655f7-13e4-4005-a013-ef85ee744b8a / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,I/NotificationManager( 7991): com.google.android.youtube: cancel(2) by com.google.android.youtube
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 5118ed51-6564-45ef-bd2f-1696d323e2d5
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 5118ed51-6564-45ef-bd2f-1696d323e2d5 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 6ba37268-3437-42b6-a7da-8c901e186926
W/ActivityManager( 1282): getRunningAppProcesses: caller 10124 does not hold REAL_GET_TASKS; limiting output
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 6ba37268-3437-42b6-a7da-8c901e186926 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - f4faa060-5d7c-40e7-b14c-50029e3d8754
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - f4faa060-5d7c-40e7-b14c-50029e3d8754 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 3b02990c-c8c8-4007-a836-162cf43d3892
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 3b02990c-c8c8-4007-a836-162cf43d3892 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 28d50d8d-b6e1-4cc7-9f1c-bb92d23fb6b9
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 28d50d8d-b6e1-4cc7-9f1c-bb92d23fb6b9 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,W/InstanceID/Rpc( 7991): Found 10006
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 32cce78b-0af3-4e75-b148-dad19d3f6399
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 32cce78b-0af3-4e75-b148-dad19d3f6399 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - a352c52f-7ebf-4e52-97b7-58d23a32e3d3
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - a352c52f-7ebf-4e52-97b7-58d23a32e3d3 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 91edf82a-547b-4dca-b08a-c56b752cbdfe
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 91edf82a-547b-4dca-b08a-c56b752cbdfe / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 5a7bbf3c-75b2-4c4e-87c6-70f4af4d2ce4
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 5a7bbf3c-75b2-4c4e-87c6-70f4af4d2ce4 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 96b00bf1-76ac-420b-9772-9614970555c7
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 96b00bf1-76ac-420b-9772-9614970555c7 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - e6426277-aa80-4168-9b22-23feff97b8fb
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - e6426277-aa80-4168-9b22-23feff97b8fb / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 6a79f1d5-9b76-4db7-a10e-433a023ea36c
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 6a79f1d5-9b76-4db7-a10e-433a023ea36c / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 50b8b9d1-491c-4f73-8aff-5d3a8f795783
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 50b8b9d1-491c-4f73-8aff-5d3a8f795783 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,I/art     ( 4748): Explicit concurrent mark sweep GC freed 3582(158KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 28MB/44MB, paused 555us total 32.217ms
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 56670f89-0720-427c-a99e-d830f924a7c8
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 56670f89-0720-427c-a99e-d830f924a7c8 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 00082803-a5c5-418a-92e8-131fc1e22894
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 00082803-a5c5-418a-92e8-131fc1e22894 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
,D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 12b975bc-2b41-44ed-8b43-4741895d7da8
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 12b975bc-2b41-44ed-8b43-4741895d7da8 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
V/JNIHelp ( 8039): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/SQLiteConnectionPool( 4748): A SQLiteConnection object for database '/data/user/0/com.google.android.gsf/databases/gservices.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 5b7161b2-44b6-477e-a060-ad697b76921c
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 5b7161b2-44b6-477e-a060-ad697b76921c / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - af9f85c4-81dd-43b9-a262-fb2d49677423
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - af9f85c4-81dd-43b9-a262-fb2d49677423 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 562db7fb-5b34-426c-a7b7-fbcbdd84a4dc
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 562db7fb-5b34-426c-a7b7-fbcbdd84a4dc / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 2b9e11ee-4b0f-4afa-b6dc-0c5a455b1447
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 2b9e11ee-4b0f-4afa-b6dc-0c5a455b1447 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 1aa4e30b-74b0-4f43-8193-98f1d34a5482
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 1aa4e30b-74b0-4f43-8193-98f1d34a5482 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
I/ProviderInstaller( 8039): Installed default security provider GmsCore_OpenSSL
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,I/NotificationManager( 8039): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 8039): com.google.android.gms: cancel(39789) by com.google.android.gms
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 7b46cc46-899a-47cb-bc10-ba0e32c44a7a
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 7b46cc46-899a-47cb-bc10-ba0e32c44a7a / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 3183faee-4fcc-47e1-b1db-c3e6ee9ba8e4
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 3183faee-4fcc-47e1-b1db-c3e6ee9ba8e4 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 1b02046b-ebef-41fd-bb2e-743c213625b1
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 1b02046b-ebef-41fd-bb2e-743c213625b1 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
I/MSM-irqbalance(  595): Discovered a new IRQ: 146
I/MSM-irqbalance(  595): Decided to move IRQ271 from CPU2 to CPU3
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 6d8ca6f4-87c5-4188-9958-7ad7a5ee8632
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 6d8ca6f4-87c5-4188-9958-7ad7a5ee8632 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 2e04197a-166d-45c8-93f4-fe6b17dccf2c
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 2e04197a-166d-45c8-93f4-fe6b17dccf2c / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 51d374e6-993f-4b00-9341-17734525412e
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 51d374e6-993f-4b00-9341-17734525412e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - b2b18ab5-9dfe-4143-a022-b790cb612382
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - b2b18ab5-9dfe-4143-a022-b790cb612382 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - cb642665-f1ff-4d6d-8c23-1fff43d18c07
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - cb642665-f1ff-4d6d-8c23-1fff43d18c07 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - f80b4dff-7116-463f-83dc-6216cb0f7774
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - f80b4dff-7116-463f-83dc-6216cb0f7774 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - f47bf020-8f59-48bb-b451-418965586113
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - f47bf020-8f59-48bb-b451-418965586113 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 13097e5e-5a19-4b6e-8aa0-cc0c941da455
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 13097e5e-5a19-4b6e-8aa0-cc0c941da455 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 89b446a7-f264-4f2f-b33d-772690c8dff2
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 89b446a7-f264-4f2f-b33d-772690c8dff2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 4cd36e79-f3fd-4953-b9bf-e7afa7ae8b94
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 4cd36e79-f3fd-4953-b9bf-e7afa7ae8b94 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 791cef21-e04b-4002-b449-00d8a902c417
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 791cef21-e04b-4002-b449-00d8a902c417 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/libc-netbsd( 7991): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7991): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7991): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7991): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  463): [LG DATA] No such appUid: 10124
D/DnsProxyListener(  463): App 10124 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  463): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  463): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  463): default dns: query_ipv6=0, query_ipv4=1, netid=100
,D/libc-netbsd(  463): res_queryN name = xxxxx, class = 1, type = 1
,I/ActivityManager( 1282): Start proc 8115:com.lge.ia.task.incalagent/u0a8 for broadcast com.lge.ia.task.incalagent/.BootReceiver
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
W/ActivityManager( 1282): getRunningAppProcesses: caller 10124 does not hold REAL_GET_TASKS; limiting output
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 51ca12f5-ab79-47ba-9abe-008c71e0a91e
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 51ca12f5-ab79-47ba-9abe-008c71e0a91e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - db2893c4-2092-4a11-a687-eb437ac9b21b
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - db2893c4-2092-4a11-a687-eb437ac9b21b / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - e38485cb-3da2-49c4-ace3-40fa306627ea
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - e38485cb-3da2-49c4-ace3-40fa306627ea / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 8a89f1ff-8ff1-471b-86e4-833314171b9e
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 8a89f1ff-8ff1-471b-86e4-833314171b9e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,I/ActivityManager( 1282): Killing 6080:com.android.defcontainer/u0a3 (adj 15): empty #22
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 1bd7c750-f371-47f1-bb4e-af35a88aa5b0
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 1bd7c750-f371-47f1-bb4e-af35a88aa5b0 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/NativeLibraryUtils( 8039): Install completed successfully. count=19 extracted=0
,D/InCalContentProvider( 8115): [ContentProvider] onCreate called
,E/DBConnectionManagerAndroid( 8115): Same database already exists
,D/libc-netbsd(  463): res_queryN name = xxxxx succeed
,I/System.out( 7991): propertyValue:false
,D/libc-netbsd( 7991): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7991): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager( 1282): Killing 7355:com.lge.myplace/u0a30 (adj 15): empty #23
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/InCalAgent( 8115): InCalAgent Alarm: android.intent.action.BOOT_COMPLETED
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 31189bf4-5545-429d-a50e-377de73fc965
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 31189bf4-5545-429d-a50e-377de73fc965 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,E/DBConnectionManagerAndroid( 8115): Same database already exists
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/InCalAgentAndroidDBHelper( 8115): /data/data/com.lge.ia.task.incalagent/
D/InCalAgentAndroidDBHelper( 8115): /data/data/com.lge.ia.task.incalagent/
D/InCalAgentAndroidDBHelper( 8115): /data/data/com.lge.ia.task.incalagent/
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 289f8e57-548f-4619-b95d-c3d6b525dced
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 289f8e57-548f-4619-b95d-c3d6b525dced / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - b493e08a-0831-47ee-8f46-dd0fc9f82cb7
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - b493e08a-0831-47ee-8f46-dd0fc9f82cb7 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/InCalAgent( 8115): Deleted old venue_detail info
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - f2898a16-488c-4c01-bdab-93ac801aca29
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - f2898a16-488c-4c01-bdab-93ac801aca29 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,I/ActivityManager( 1282): Start proc 8138:com.android.providers.calendar/u0a19 for content provider com.android.providers.calendar/.CalendarProvider2
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 3c2b9169-addf-4a0f-8263-56e010616005
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 3c2b9169-addf-4a0f-8263-56e010616005 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 8b49a803-634a-48f5-baf2-d75366b43837
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 8b49a803-634a-48f5-baf2-d75366b43837 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - ba8b3b9d-6a68-43c7-8a85-1a463041fccc
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - ba8b3b9d-6a68-43c7-8a85-1a463041fccc / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
I/art     (  498): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 53% free, 28MB/60MB, paused 426us total 20.824ms
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - e4775662-575e-4d3a-b353-8e8669e1974b
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - e4775662-575e-4d3a-b353-8e8669e1974b / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 2cd8d5cb-7395-4a48-96c7-2d9468597cb2
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 2cd8d5cb-7395-4a48-96c7-2d9468597cb2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - d3de462b-25ec-485a-a5c5-b0176ff108ca
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - d3de462b-25ec-485a-a5c5-b0176ff108ca / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
W/ResourcesManager( 8138): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - edc3b145-01e3-4651-b55c-529363ae9c9a
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - edc3b145-01e3-4651-b55c-529363ae9c9a / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
I/art     (  498): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 53% free, 28MB/60MB, paused 384us total 17.875ms
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 890d5493-8caf-4e84-ac03-4a9425825369
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 890d5493-8caf-4e84-ac03-4a9425825369 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 0173bc1a-d097-4d28-a0c9-5c281cd3e009
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 0173bc1a-d097-4d28-a0c9-5c281cd3e009 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - bc1d6f22-43e3-4ae1-82b7-a6b0c4d01587
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - bc1d6f22-43e3-4ae1-82b7-a6b0c4d01587 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/CalendarProvider2( 8138): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@81b6200
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
I/art     (  498): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 53% free, 28MB/60MB, paused 565us total 18.157ms
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 83509d54-ae3a-48a6-987b-28ad775956c9
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 83509d54-ae3a-48a6-987b-28ad775956c9 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
,D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - c6b9ce0e-0bf6-4395-8276-24d2a6431005
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - c6b9ce0e-0bf6-4395-8276-24d2a6431005 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/CalendarProvider2( 8138): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 8138): Created com.android.providers.calendar.CalendarAlarmManager@11c0f0f5(com.android.providers.calendar.CalendarProvider2@81b6200)
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - f1475e52-243d-4144-8435-202c684b1255
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - f1475e52-243d-4144-8435-202c684b1255 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 0eaba406-8682-490f-9924-bb7c808954df
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 0eaba406-8682-490f-9924-bb7c808954df / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/InCalAgent( 8115): Data retrieved from content://com.android.calendar/event_pocket_preference
D/InCalAgent( 8115): Data retrieved  Visible Checked: 0
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - ee6b751b-3f3d-4e7e-87f1-8a6277bff917
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - ee6b751b-3f3d-4e7e-87f1-8a6277bff917 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/libc-netbsd( 7991): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7991): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/InCalAgent( 8115): Data retrieved from content://com.android.calendar/event_pocket_preference
D/InCalAgent( 8115): Data retrieved  Visible Checked: 0
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 93531771-b572-4406-9c77-af2d1e644c41
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 93531771-b572-4406-9c77-af2d1e644c41 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/InCalAgent( 8115): Visible Unchecked Not Start InCalService
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - fbb8a6df-fe6d-43de-bd0d-ecf46325d80f
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - fbb8a6df-fe6d-43de-bd0d-ecf46325d80f / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,I/ActivityManager( 1282): Start proc 8159:com.google.android.talk/u0a121 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver
,I/ActivityManager( 1282): Killing 6942:com.google.android.apps.plus/u0a122 (adj 15): empty #22
,I/ActivityManager( 1282): Killing 7406:com.lge.task/u0a20 (adj 15): empty #23
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
I/ActivityManager( 1282): Waited long enough for: ServiceRecord{3935be3c u0 com.lge.splitwindow/.SplitService}
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 0b50dead-7338-42e1-a3be-5d69a95ae21d
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 0b50dead-7338-42e1-a3be-5d69a95ae21d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,W/ResourcesManager( 8159): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 6043a4f0-2d5f-4486-bfb4-823dc35c3505
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 6043a4f0-2d5f-4486-bfb4-823dc35c3505 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 862ed339-641f-4c84-b358-577d9fb98ad9
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 862ed339-641f-4c84-b358-577d9fb98ad9 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 27122fb5-fd7e-4c45-8dd0-770d0b506dd7,
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 27122fb5-fd7e-4c45-8dd0-770d0b506dd7 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
,D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - ea6d03af-023d-4bbc-a40c-dc7d05890c8b,
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - ea6d03af-023d-4bbc-a40c-dc7d05890c8b / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 92181860-a943-42e2-a155-d4a0e735852f
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 92181860-a943-42e2-a155-d4a0e735852f / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 08c1cae8-2fca-4848-b332-91dd33d52943
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 08c1cae8-2fca-4848-b332-91dd33d52943 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 706751e4-df06-4c0b-a9bd-cf05cc1b5933
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 706751e4-df06-4c0b-a9bd-cf05cc1b5933 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 65f680e3-9f2b-492d-9d65-777207824fb2
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 65f680e3-9f2b-492d-9d65-777207824fb2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
,D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 29e1e57b-84d4-4c9d-ac79-db148cb0d4e9
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 29e1e57b-84d4-4c9d-ac79-db148cb0d4e9 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
,D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 1f0183e5-83e3-46b5-a44e-d0cfee8f7bc2
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 1f0183e5-83e3-46b5-a44e-d0cfee8f7bc2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 1389325a-4c9c-406f-b8fb-5047b265794b
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 1389325a-4c9c-406f-b8fb-5047b265794b / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 3681ea27-72d0-4150-aa2f-ceb5f95299fd
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 3681ea27-72d0-4150-aa2f-ceb5f95299fd / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - bb9de6fe-8f41-4419-b8a8-ad29c5cc37e3
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - bb9de6fe-8f41-4419-b8a8-ad29c5cc37e3 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 6ee5456f-9456-46b8-8981-4c04ecff2cf2
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 6ee5456f-9456-46b8-8981-4c04ecff2cf2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 98f0874d-b6fe-48e5-aad9-6bf37eaa2c59
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 98f0874d-b6fe-48e5-aad9-6bf37eaa2c59 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - cfbe8b72-8e3a-4998-b463-3edb97a83a82
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - cfbe8b72-8e3a-4998-b463-3edb97a83a82 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 25e1b2ab-b32f-426e-91ec-ac2ebec08d66
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 25e1b2ab-b32f-426e-91ec-ac2ebec08d66 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - ef230305-4cf3-469d-9c08-aa3fd1eafe85
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - ef230305-4cf3-469d-9c08-aa3fd1eafe85 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - ea0e2806-7922-4f2f-b42c-f03f4d0bb32f
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - ea0e2806-7922-4f2f-b42c-f03f4d0bb32f / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 6d52451c-3ff9-414b-8cec-677d8da8f540
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 6d52451c-3ff9-414b-8cec-677d8da8f540 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - b10104d1-e4e9-4fba-b05a-38316754e591
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - b10104d1-e4e9-4fba-b05a-38316754e591 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 16772382-6d07-43e6-bb1c-6aa089f375cd
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 16772382-6d07-43e6-bb1c-6aa089f375cd / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 2db1372b-686b-43eb-ab9f-6e7d0a3ae7ff
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 2db1372b-686b-43eb-ab9f-6e7d0a3ae7ff / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - d1bf7a09-33bd-4731-805b-b4e9eeaec6ee
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - d1bf7a09-33bd-4731-805b-b4e9eeaec6ee / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - d80f77b0-13b6-4c62-bcdf-d481014590d3
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - d80f77b0-13b6-4c62-bcdf-d481014590d3 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 6ce07274-cdcd-4ce2-814c-4b259fe619a9
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 6ce07274-cdcd-4ce2-814c-4b259fe619a9 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 38e33f3f-4773-48d0-806f-13174903b491
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 38e33f3f-4773-48d0-806f-13174903b491 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 5fabf0b0-fb7f-479c-910f-0309b2dd0bf7
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 5fabf0b0-fb7f-479c-910f-0309b2dd0bf7 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - ab141f47-5e67-4525-b200-f3be7d04013a
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - ab141f47-5e67-4525-b200-f3be7d04013a / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - a9520a93-0796-4360-ac68-0b1cc385201e
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - a9520a93-0796-4360-ac68-0b1cc385201e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 4bb10986-e8ec-4dcc-8ae2-ca0a448864cb
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 4bb10986-e8ec-4dcc-8ae2-ca0a448864cb / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - ef60bd9b-4b37-46db-a1ba-404941422741
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - ef60bd9b-4b37-46db-a1ba-404941422741 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - a249ba1a-4ed1-45c6-b299-e7ca14ff60f0
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - a249ba1a-4ed1-45c6-b299-e7ca14ff60f0 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - fa3ec0e5-a36a-4116-b749-3574d36a6c69
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - fa3ec0e5-a36a-4116-b749-3574d36a6c69 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - a693e746-222f-40a6-b6a6-2dbac9a7cc05
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - a693e746-222f-40a6-b6a6-2dbac9a7cc05 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - f90cd638-7f1f-44e7-8b5c-f715a5018587
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - f90cd638-7f1f-44e7-8b5c-f715a5018587 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - f4d27d96-14f4-4ac7-a025-4b2d52255a43
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - f4d27d96-14f4-4ac7-a025-4b2d52255a43 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 9c66dce2-ec8d-4b2a-b078-32fd35a28ae0
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 9c66dce2-ec8d-4b2a-b078-32fd35a28ae0 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 886be952-2de9-4927-b34e-39ed969a5588
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 886be952-2de9-4927-b34e-39ed969a5588 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 2d76dd0f-0098-4b73-abaf-f028667221b9
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 2d76dd0f-0098-4b73-abaf-f028667221b9 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 8fcc5e8c-c8fe-4888-85ab-12aa489431cd
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 8fcc5e8c-c8fe-4888-85ab-12aa489431cd / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 803125a0-c64c-44b7-b6fd-d35b7ca1b725
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 803125a0-c64c-44b7-b6fd-d35b7ca1b725 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 24e437fc-3494-40c3-972f-b9c2f82ef89e
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 24e437fc-3494-40c3-972f-b9c2f82ef89e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 94a5beeb-2fb2-4ad8-88d6-ccd78991edba
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 94a5beeb-2fb2-4ad8-88d6-ccd78991edba / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 894925e2-e51a-4291-9bc1-792ae15c4b12
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 894925e2-e51a-4291-9bc1-792ae15c4b12 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 63cb7ad3-9b21-4bc9-99a0-8f14f42e0959
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 63cb7ad3-9b21-4bc9-99a0-8f14f42e0959 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 65185bd2-75cd-4dcc-89b5-69883bd5a900
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 65185bd2-75cd-4dcc-89b5-69883bd5a900 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - d9be372b-8066-436d-81b5-d990aeeda02c
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - d9be372b-8066-436d-81b5-d990aeeda02c / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 829b4156-1341-4270-8ab3-13b5eaf56794
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 829b4156-1341-4270-8ab3-13b5eaf56794 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 30435cfc-d93b-471d-b56e-fd2526705744
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 30435cfc-d93b-471d-b56e-fd2526705744 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 9a931799-16f8-406a-82f1-2f98d6e6ea04
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 9a931799-16f8-406a-82f1-2f98d6e6ea04 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - a8f25c9a-f492-487e-9f29-ef20a347f630
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - a8f25c9a-f492-487e-9f29-ef20a347f630 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 84352142-8431-4722-ac6d-c375fe7041b3
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 84352142-8431-4722-ac6d-c375fe7041b3 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 865b4daf-072f-4f31-8b58-cec9534baa97
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 865b4daf-072f-4f31-8b58-cec9534baa97 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 4b794654-155f-421b-b272-24c223b7b48a
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 4b794654-155f-421b-b272-24c223b7b48a / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 44ca9b81-fa77-4713-9972-dc5361e9dbd5
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 44ca9b81-fa77-4713-9972-dc5361e9dbd5 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - fc128c02-c630-4662-9981-70da16e8cf99
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - fc128c02-c630-4662-9981-70da16e8cf99 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,I/Babel_SMS( 8159): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8159): MmsConfig.loadMmsSettings
,I/Babel_SMS( 8159): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-H815 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/YSdHbanpHC5h2R_E/H815-M3-D1.xml
,I/Babel_SMS( 8159): MmsConfig.loadFromDatabase
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - c08e9922-0204-4981-bb90-6d9d9cdfe5ac
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - c08e9922-0204-4981-bb90-6d9d9cdfe5ac / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 6dfef9fc-b361-45a9-9998-edc5899487b0
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 6dfef9fc-b361-45a9-9998-edc5899487b0 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 27f38297-b70b-40e3-94a8-3227e45002d5
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 27f38297-b70b-40e3-94a8-3227e45002d5 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - ebcfd271-c361-4f20-94aa-4c0c5cd24811
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - ebcfd271-c361-4f20-94aa-4c0c5cd24811 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 6ef657a4-a755-44ec-89a5-dc6178314e49
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 6ef657a4-a755-44ec-89a5-dc6178314e49 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
E/Babel_SMS( 8159): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 8159): MmsConfig.loadFromResources
,E/Babel_SMS( 8159): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 8159): MmsConfig.loadMmsSettings: mUserAgent=LG-H815 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/YSdHbanpHC5h2R_E/H815-M3-D1.xml
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 81c8c749-54c7-4053-9ad1-0a4e1b9e1141
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 81c8c749-54c7-4053-9ad1-0a4e1b9e1141 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 7050ff3f-2cd7-4006-ac9d-3ef4e6a07b98
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 7050ff3f-2cd7-4006-ac9d-3ef4e6a07b98 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 26d7ccb8-6238-425e-a914-52f7941108bd
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 26d7ccb8-6238-425e-a914-52f7941108bd / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/SensorManager( 8159): found sensor: LGE Accelerometer, handle=0
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - a70bd083-4c69-4a1e-8b19-3187f5168b43
D/SensorManager( 8159): found sensor: LGE Magnetometer, handle=10
D/SensorManager( 8159): found sensor: LGE Magnetometer Uncalibrated, handle=11
D/SensorManager( 8159): found sensor: LGE Gyroscope, handle=2
D/SensorManager( 8159): found sensor: LGE Gyroscope Uncalibrated, handle=8
D/SensorManager( 8159): found sensor: LGE Proximity, handle=48
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - a70bd083-4c69-4a1e-8b19-3187f5168b43 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/SensorManager( 8159): found sensor: LGE Knock-on Proximity Sensor, handle=74
D/SensorManager( 8159): found sensor: LGE Virtual Proximity Sensor, handle=75
D/SensorManager( 8159): found sensor: LGE Light, handle=1
D/SensorManager( 8159): found sensor: LGE Pressure, handle=3
D/SensorManager( 8159): found sensor: LGE Accelerometer -Wakeup Secondary, handle=17
D/SensorManager( 8159): found sensor: LGE Magnetometer -Wakeup Secondary, handle=26
D/SensorManager( 8159): found sensor: LGE Magnetometer Uncalibrated -Wakeup Secondary, handle=27
D/SensorManager( 8159): found sensor: LGE Gyroscope -Wakeup Secondary, handle=19
D/SensorManager( 8159): found sensor: LGE Gyroscope Uncalibrated -Wakeup Secondary, handle=24
D/SensorManager( 8159): found sensor: LGE Proximity -Non Wakeup Secondary, handle=67
D/SensorManager( 8159): found sensor: LGE Light -Wakeup Secondary, handle=18
D/SensorManager( 8159): found sensor: LGE Pressure -Wakeup Secondary, handle=20
D/SensorManager( 8159): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 8159): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 8159): found sensor: LGE Rotation Vector Sensor, handle=36
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/SensorManager( 8159): found sensor: LGE Step Detector Sensor, handle=43
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/SensorManager( 8159): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 8159): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 8159): found sensor: LGE Game Rotation Vector Sensor, handle=50
D/SensorManager( 8159): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 8159): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 8159): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 8159): found sensor: Gravity -Wakeup Secondary, handle=60
D/SensorManager( 8159): found sensor: Linear Acceleration -Wakeup Secondary, handle=61
D/SensorManager( 8159): found sensor: Rotation Vector -Wakeup Secondary, handle=62
D/SensorManager( 8159): found sensor: Step Detector -Wakeup Secondary, handle=65
D/SensorManager( 8159): found sensor: Step Counter -Wakeup Secondary, handle=66
D/SensorManager( 8159): found sensor: Game Rotation Vector -Wakeup Secondary, handle=63
D/SensorManager( 8159): found sensor: GeoMagnetic Rotation Vector -Wakeup Secondary, handle=64
D/SensorManager( 8159): found sensor: Orientation -Wakeup Secondary, handle=59
D/SensorManager( 8159): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 8159): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 8159): found sensor: Motion Accel, handle=46
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - fa5c3172-db16-47a5-933a-b9a0d67b1eb3
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - fa5c3172-db16-47a5-933a-b9a0d67b1eb3 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
,D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - b835f487-a783-486f-a42e-a9f3c802b38a
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - b835f487-a783-486f-a42e-a9f3c802b38a / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
,D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 40fd4fba-cefb-46af-b577-6e61ac94842c
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 40fd4fba-cefb-46af-b577-6e61ac94842c / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
W/Settings( 8159): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 8159): startup - clean
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 4ca2f31f-88b4-4df6-9f47-83970a61b60f
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 4ca2f31f-88b4-4df6-9f47-83970a61b60f / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - bd1e7c72-5562-4ff0-9c1b-835dd21f0567
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - bd1e7c72-5562-4ff0-9c1b-835dd21f0567 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - b66e5d5d-b14d-4acc-bda2-0f819c17bad0
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - b66e5d5d-b14d-4acc-bda2-0f819c17bad0 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
I/Babel   ( 8159): deleted: false for 0
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 40946a72-4ec0-4c8d-8d2f-a0d9905e6106
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 40946a72-4ec0-4c8d-8d2f-a0d9905e6106 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 4e829150-125e-4886-86ea-9ccde1c985d5
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 4e829150-125e-4886-86ea-9ccde1c985d5 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 55abf039-0499-433f-9f0d-3aa3bdfb1cd5
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 55abf039-0499-433f-9f0d-3aa3bdfb1cd5 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 19033ee3-e37d-4335-9815-c4160abd8747
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 19033ee3-e37d-4335-9815-c4160abd8747 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - e1639432-8c5f-48a0-8649-e45b9abe721e
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - e1639432-8c5f-48a0-8649-e45b9abe721e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 537c5b87-9f67-415d-81f4-84d83f25deb8
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 537c5b87-9f67-415d-81f4-84d83f25deb8 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 5e249c61-e345-42a3-a78b-e2bb95936113
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 5e249c61-e345-42a3-a78b-e2bb95936113 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,I/Babel_telephony( 8159): TeleModule.launchCompleted
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 970b9fe0-824b-4e9d-b0ba-d8346aabb205
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 970b9fe0-824b-4e9d-b0ba-d8346aabb205 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - bba95c60-e778-4b10-af5c-f615bfac03d6
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - bba95c60-e778-4b10-af5c-f615bfac03d6 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 74aff581-351d-4be1-89c6-2c4529d06455
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 74aff581-351d-4be1-89c6-2c4529d06455 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/PhoneAccountRegistrar( 4225): createAccounts: [[PhoneAccount: ComponentInfo{com.android.phone/com.android.services.telephony.TelephonyConnectionService}, [4208433e9abcef6d04057081ae5a7fc2b23515a1], UserHandle{0} Capabilities: 22 Schemes: tel voicemail ]]
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 0218dba6-3b8f-4dd6-aa68-65b0bddedbb1
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 0218dba6-3b8f-4dd6-aa68-65b0bddedbb1 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,I/Babel_telephony( 8159): TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 57e5e86c-0721-4786-a65e-b3b7886de815
W/Babel   ( 8159): BAM#gBA: invalid account id: -1
W/Babel   ( 8159): BAM#gBA: invalid account id: -1
I/Babel_telephony( 8159): TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 57e5e86c-0721-4786-a65e-b3b7886de815 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 0244ab51-5b33-450e-a0ae-f7003ad4bc64
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 0244ab51-5b33-450e-a0ae-f7003ad4bc64 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 23c52ef1-4bea-4648-abc7-e20327a28f4f
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 23c52ef1-4bea-4648-abc7-e20327a28f4f / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 4922fff3-1d9f-4647-a8de-2b186920a32e
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 4922fff3-1d9f-4647-a8de-2b186920a32e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 5870cbdc-47ad-4b06-b8fd-214d3666860e
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 5870cbdc-47ad-4b06-b8fd-214d3666860e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 116fae68-b15d-4ad5-b2ce-d36d616351ea
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 116fae68-b15d-4ad5-b2ce-d36d616351ea / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
W/AudioCapabilities( 8159): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 8159): Unsupported mime audio/adpcm
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 34ed90bb-ea48-4655-9406-ca237996b5ab
W/AudioCapabilities( 8159): Unsupported mime audio/g726
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 34ed90bb-ea48-4655-9406-ca237996b5ab / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
W/AudioCapabilities( 8159): Unsupported mime audio/eac3
W/AudioCapabilities( 8159): Unsupported mime audio/ac3
,W/AudioCapabilities( 8159): Unsupported mime audio/wma-voice
W/AudioCapabilities( 8159): Unsupported mime audio/x-ms-wma
,W/VideoCapabilities( 8159): Unsupported mime video/theora
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 98e370a8-dc72-438d-acc4-14756bab1cee
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 98e370a8-dc72-438d-acc4-14756bab1cee / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,W/VideoCapabilities( 8159): Unsupported mime video/mjpg
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - c8df21d1-5658-42f3-80ba-8170ab81ec73
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - c8df21d1-5658-42f3-80ba-8170ab81ec73 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 78f338c7-4684-4764-bcaa-064186026361
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 78f338c7-4684-4764-bcaa-064186026361 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 409f36ac-2a0a-40e5-b1b3-1d5d8b74fd9a
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 409f36ac-2a0a-40e5-b1b3-1d5d8b74fd9a / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 81535909-e940-40b0-b588-a88c8f90b4ca
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 81535909-e940-40b0-b588-a88c8f90b4ca / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - dc651e19-46e8-4831-abb0-0d8cb228d035
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - dc651e19-46e8-4831-abb0-0d8cb228d035 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,W/AudioCapabilities( 8159): Unsupported mime audio/evrc
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,W/VideoCapabilities( 8159): Unrecognized profile 2130706433 for video/avc
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 814bf556-8011-42d7-a000-99d240d75e00
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 814bf556-8011-42d7-a000-99d240d75e00 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 682f2ce4-b1ad-4e2d-8a0d-d2028980af56
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 682f2ce4-b1ad-4e2d-8a0d-d2028980af56 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
W/AudioCapabilities( 8159): Unsupported mime audio/evrc
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 6202a83b-e18c-49f7-83b9-37dda8d37934
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 6202a83b-e18c-49f7-83b9-37dda8d37934 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
W/VideoCapabilities( 8159): Unsupported mime video/x-ms-wmv
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 680cb9ec-7b04-42ac-9056-73993ecc808c
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 680cb9ec-7b04-42ac-9056-73993ecc808c / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
W/VideoCapabilities( 8159): Unsupported mime video/x-ms-wmv
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 1d5c7421-6381-4abc-b782-7c3adc677e7d
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 1d5c7421-6381-4abc-b782-7c3adc677e7d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
W/VideoCapabilities( 8159): Unsupported mime video/divx
,W/VideoCapabilities( 8159): Unsupported mime video/divx4
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - ce57ba62-cb76-4220-a487-2114dcb6092c
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - ce57ba62-cb76-4220-a487-2114dcb6092c / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - fbd8ec31-807f-4a7c-9ea6-2016bb7c1cf6
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - fbd8ec31-807f-4a7c-9ea6-2016bb7c1cf6 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
W/VideoCapabilities( 8159): Unsupported mime video/mp4v-esdp
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 70590970-02bd-4905-a7c0-e2d2bb42eb62
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 70590970-02bd-4905-a7c0-e2d2bb42eb62 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 7236aae1-e996-463a-8031-4cc362fde6b3
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 7236aae1-e996-463a-8031-4cc362fde6b3 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,I/VideoCapabilities( 8159): Unsupported profile 4 for video/mp4v-es
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 926ebf23-406f-4438-8f59-9a37c2271c8f
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 926ebf23-406f-4438-8f59-9a37c2271c8f / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 5520c849-42d8-45c3-9a64-d3b94b7251d3
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 5520c849-42d8-45c3-9a64-d3b94b7251d3 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
W/VideoCapabilities( 8159): Unrecognized profile 2130706433 for video/avc
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
W/VideoCapabilities( 8159): Unrecognized profile 2130706433 for video/avc
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - dc0f9d35-d277-4d02-b51e-52a6cd9e0b76
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - dc0f9d35-d277-4d02-b51e-52a6cd9e0b76 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
W/VideoCapabilities( 8159): Unrecognized profile 2130706433 for video/avc
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,W/VideoCapabilities( 8159): Unrecognized profile 2130706433 for video/avc,
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 63ded62a-9750-4e49-9ece-0961f83f42ed
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 63ded62a-9750-4e49-9ece-0961f83f42ed / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm,
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 8a86d4bd-d371-4086-818c-88debab7e023
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 8a86d4bd-d371-4086-818c-88debab7e023 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - cb77b773-c909-4cde-ac38-a34efc68150c
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - cb77b773-c909-4cde-ac38-a34efc68150c / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
I/vclib   ( 8159): onServiceConnected
W/Babel   ( 8159): Attempted to change video mute state without an active call.
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 8e5af302-3dba-48f5-87ac-53e03d539d04
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 8e5af302-3dba-48f5-87ac-53e03d539d04 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,I/NotificationManager( 8159): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/ActivityManager( 1282): Start proc 8191:com.google.android.gm/u0a113 for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver
,I/ActivityManager( 1282): Killing 7582:com.google.android.configupdater/u0a64 (adj 15): empty #22
,I/art     (  497): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 53% free, 28MB/60MB, paused 255us total 23.157ms
,I/art     (  497): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 53% free, 28MB/60MB, paused 214us total 21.074ms
,I/art     (  497): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 53% free, 28MB/60MB, paused 215us total 20.752ms
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - eee7b05c-fa50-49d6-88ed-a2a759a27f15
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - eee7b05c-fa50-49d6-88ed-a2a759a27f15 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 6a69f98d-6575-45d5-9e91-d68e7dee4da2
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 6a69f98d-6575-45d5-9e91-d68e7dee4da2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - ea14854e-3f9f-4ee7-a201-11a1631fdeca
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - ea14854e-3f9f-4ee7-a201-11a1631fdeca / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 464ddc3e-1680-4c53-b3f2-e72dc8758016
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 464ddc3e-1680-4c53-b3f2-e72dc8758016 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 1f907072-f094-4959-9ab0-0f79ee5a6480
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 1f907072-f094-4959-9ab0-0f79ee5a6480 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - d7baeb28-d03c-454b-acd6-ffcd88610a03
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - d7baeb28-d03c-454b-acd6-ffcd88610a03 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 9e0154e7-1b18-47e7-a1a9-3a12cedf27c8
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 9e0154e7-1b18-47e7-a1a9-3a12cedf27c8 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - f6037b05-fc58-4492-a50b-18c18fe64951
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - f6037b05-fc58-4492-a50b-18c18fe64951 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - b7ff929f-b6a7-4c54-9365-aaa04bf418dd
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - b7ff929f-b6a7-4c54-9365-aaa04bf418dd / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 976de724-cfbb-47c8-8567-ef68177fc50d
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 976de724-cfbb-47c8-8567-ef68177fc50d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 68c06519-cd8d-46be-a2e6-636edda9d7d6
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 68c06519-cd8d-46be-a2e6-636edda9d7d6 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 62075146-fc0f-4a97-97a2-3ecf30b1334a
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 62075146-fc0f-4a97-97a2-3ecf30b1334a / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - bff89f91-99d5-4412-a336-672911ba88a8
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - bff89f91-99d5-4412-a336-672911ba88a8 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - d380f950-c87c-4f1b-a483-2a63f49bf1fd
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - d380f950-c87c-4f1b-a483-2a63f49bf1fd / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
,D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - bcfbc285-dc7e-439a-9ea8-cc1b145ac79f
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - bcfbc285-dc7e-439a-9ea8-cc1b145ac79f / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
,D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 6553dabf-f63d-4062-b8c3-d84fb2c4f8b9
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 6553dabf-f63d-4062-b8c3-d84fb2c4f8b9 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 865ed0fa-2f5b-465c-9ced-4ac0880cd16e
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 865ed0fa-2f5b-465c-9ced-4ac0880cd16e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 4fe0fa81-7eca-4486-82ba-e2da3e7b55be
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 4fe0fa81-7eca-4486-82ba-e2da3e7b55be / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 2e6bb707-df3a-46c8-8b91-5c4b0ae4a55d
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 2e6bb707-df3a-46c8-8b91-5c4b0ae4a55d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 937d70d6-6e5b-4091-a795-2ded79d5d42d
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 937d70d6-6e5b-4091-a795-2ded79d5d42d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - e3587bbb-8cc3-4db6-86f1-de8c12a29067
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - e3587bbb-8cc3-4db6-86f1-de8c12a29067 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - fb13061c-fcd4-4752-bd33-9c1d341e1e61
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - fb13061c-fcd4-4752-bd33-9c1d341e1e61 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 2d9a8638-ed23-4470-9d49-8dca99785057
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 2d9a8638-ed23-4470-9d49-8dca99785057 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - d1a03ad5-d246-4d36-a9ee-f61055fb6c9a
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - d1a03ad5-d246-4d36-a9ee-f61055fb6c9a / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - a0015d8e-db79-4411-94bb-e51aa8329482
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - a0015d8e-db79-4411-94bb-e51aa8329482 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 6dbeaf37-3466-42cc-ba47-af0d1d41888a
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 6dbeaf37-3466-42cc-ba47-af0d1d41888a / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,I/Gmail   ( 8191): getAccountsCursor
D/ActivityThread( 8191): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 0c2f9104-796b-4205-ae33-4b0d070111fd
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 0c2f9104-796b-4205-ae33-4b0d070111fd / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - ffae94f7-8d51-41a7-b23e-841c1d3d03d9
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - ffae94f7-8d51-41a7-b23e-841c1d3d03d9 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - ecb6ccf5-4c8e-45fc-9d8f-93084aec3df2
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - ecb6ccf5-4c8e-45fc-9d8f-93084aec3df2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 3496b1b5-8354-47d3-a32d-b65fbd5ca47b
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 3496b1b5-8354-47d3-a32d-b65fbd5ca47b / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - db8034f2-ccf8-4976-adf8-93bd0e42a1ad
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - db8034f2-ccf8-4976-adf8-93bd0e42a1ad / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,V/GLSActivity( 5096): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 0f181be5-e6ba-4a18-aedb-e1356e782077
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 0f181be5-e6ba-4a18-aedb-e1356e782077 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 304f965d-5d0b-4c64-92fd-e8bec5275e84
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 304f965d-5d0b-4c64-92fd-e8bec5275e84 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 57c30edb-3a2a-4ed0-98ec-7ed94f879838
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 57c30edb-3a2a-4ed0-98ec-7ed94f879838 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - bafe996d-e0aa-41fe-b4b1-381133107c2e
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - bafe996d-e0aa-41fe-b4b1-381133107c2e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 9b9fc9bc-089e-4a7b-a2f4-a039d608bcb2
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 9b9fc9bc-089e-4a7b-a2f4-a039d608bcb2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
W/ActivityManager( 1282): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
W/ActivityManager( 1282): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 99cac81d-2123-46ce-a4d3-fe28654d55cb
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 99cac81d-2123-46ce-a4d3-fe28654d55cb / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 012f0558-9752-4ee3-a667-bbb57ada0109
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 012f0558-9752-4ee3-a667-bbb57ada0109 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 1ce831ee-f8dc-4bb2-b9fd-5b1f1f1866e8
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 1ce831ee-f8dc-4bb2-b9fd-5b1f1f1866e8 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 6dd19686-49ad-470b-89ad-4dfa598a7d40
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 6dd19686-49ad-470b-89ad-4dfa598a7d40 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 473e3a23-945a-42ae-8215-1f818169a959
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 473e3a23-945a-42ae-8215-1f818169a959 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 7eca0968-92ed-4e46-b7ed-2fe7c22bf1fe
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 7eca0968-92ed-4e46-b7ed-2fe7c22bf1fe / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 06ab7a24-8eeb-4874-aec4-d19f138546ef
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 06ab7a24-8eeb-4874-aec4-d19f138546ef / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 3b9905d6-e5ed-486c-8f80-f2fcb8ca514d
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 3b9905d6-e5ed-486c-8f80-f2fcb8ca514d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 2390de7e-2f9d-489d-bbff-8d75cbbd4ed9
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 2390de7e-2f9d-489d-bbff-8d75cbbd4ed9 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,W/ActivityManager( 1282): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - d64deca9-23d2-477d-b6dd-915f31af1672
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - d64deca9-23d2-477d-b6dd-915f31af1672 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 6885fdd2-6a7c-4898-9d55-21a337014781
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 6885fdd2-6a7c-4898-9d55-21a337014781 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
I/Gmail   ( 8191): Observing account changes for notifications
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - adb18da9-114c-44cf-a58f-2150dca28a1e
W/ActivityManager( 1282): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - adb18da9-114c-44cf-a58f-2150dca28a1e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - fd34b0e0-6de5-4fa7-bd7a-9d8d78ba0aeb
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - fd34b0e0-6de5-4fa7-bd7a-9d8d78ba0aeb / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
W/GAV2    ( 8191): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 46f38f3b-4098-43e6-a630-44be5a7eda4c
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 46f38f3b-4098-43e6-a630-44be5a7eda4c / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - f012d2aa-2add-422e-ac27-ab5f560931d7
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - f012d2aa-2add-422e-ac27-ab5f560931d7 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 7796bb58-49b3-49d2-8eb8-7999f2a8ba70
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 7796bb58-49b3-49d2-8eb8-7999f2a8ba70 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 8fee0203-fdde-4b7d-8163-3b46c63af0df
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 8fee0203-fdde-4b7d-8163-3b46c63af0df / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,W/ActivityManager( 1282): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 61c1ea30-78eb-4cf3-860b-e7f1662ba055
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 61c1ea30-78eb-4cf3-860b-e7f1662ba055 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - faea5ea3-bd8d-4da9-9206-770ff342d5c4
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - faea5ea3-bd8d-4da9-9206-770ff342d5c4 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 9bc0f51e-5189-480b-b9d1-6d1e3d1a7615
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 9bc0f51e-5189-480b-b9d1-6d1e3d1a7615 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
E/Gmail   ( 8191): Error finding the version of the Email provider.....
E/Gmail   ( 8191): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 8191): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 8191): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 8191): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 8191): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 8191): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 8191): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 8191): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 8191): We do not support migrating this version of the Email provider.
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,I/Gmail   ( 8191): getAccountsCursor
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - c639a728-339e-4545-8390-c9536453654c
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - c639a728-339e-4545-8390-c9536453654c / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - b6805ff3-2c52-4320-8c53-596c952f6e8f
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - b6805ff3-2c52-4320-8c53-596c952f6e8f / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
V/GLSActivity( 5096): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - fc9a8edd-207d-427e-a5e4-75f090ba05f0
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - fc9a8edd-207d-427e-a5e4-75f090ba05f0 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - b20adf61-a0b1-4a82-bc8e-cb885de2fec5
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - b20adf61-a0b1-4a82-bc8e-cb885de2fec5 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,W/ActivityManager( 1282): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 4f08a1e3-0da4-4551-b49b-77bf8f81b275
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 4f08a1e3-0da4-4551-b49b-77bf8f81b275 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,W/ActivityManager( 1282): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 39db361c-7fd9-4b33-b2eb-867d986a4563
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 39db361c-7fd9-4b33-b2eb-867d986a4563 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - ea50bff7-8fc8-4420-b3b5-f675cf05da43
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - ea50bff7-8fc8-4420-b3b5-f675cf05da43 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 2ad01bce-48f3-4847-ba33-00a73832084d
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 2ad01bce-48f3-4847-ba33-00a73832084d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 755c7cc2-1bee-458b-a6ce-3e5783a8494d
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 755c7cc2-1bee-458b-a6ce-3e5783a8494d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - e24e4e4c-1531-4561-80c9-e1e46dd8734c
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - e24e4e4c-1531-4561-80c9-e1e46dd8734c / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,E/ActivityThread( 8191): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@164ccab6 that was originally bound here
E/ActivityThread( 8191): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@164ccab6 that was originally bound here
E/ActivityThread( 8191): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1259)
E/ActivityThread( 8191): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1153)
E/ActivityThread( 8191): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1888)
E/ActivityThread( 8191): 	at android.app.ContextImpl.bindService(ContextImpl.java:1871)
E/ActivityThread( 8191): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
E/ActivityThread( 8191): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 8191): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 8191): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 8191): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 8191): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 8191): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 8191): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 8191): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 8191): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 8191): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 8191): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager( 1282): Unbind failed: could not find connection for android.os.BinderProxy@1b256d47
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - d073ef55-ec51-4487-a7ad-57fc9a9bac98
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - d073ef55-ec51-4487-a7ad-57fc9a9bac98 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - e6706500-5974-40a4-9412-3c889951aad5
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - e6706500-5974-40a4-9412-3c889951aad5 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 282d3e17-345f-453d-9a06-0acf4fc6a925
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 282d3e17-345f-453d-9a06-0acf4fc6a925 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 6313603d-3b9f-44fa-9602-eefcf2aeae06
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 6313603d-3b9f-44fa-9602-eefcf2aeae06 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - f461309b-5114-40b1-811c-a1d958c2cdd5
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - f461309b-5114-40b1-811c-a1d958c2cdd5 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 9e9d2d55-39f8-4b01-a1c1-c18e9a35e893
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 9e9d2d55-39f8-4b01-a1c1-c18e9a35e893 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - c98f3939-3834-4d49-9d43-d5750a416c37
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - c98f3939-3834-4d49-9d43-d5750a416c37 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/BluetoothManagerService( 1282): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService( 1282): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2255974 mBinding = false
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - f31e07a7-2cb2-4be9-b0ea-94e2cdef2998
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - f31e07a7-2cb2-4be9-b0ea-94e2cdef2998 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/FileApkUtils( 8039): Spent 21ms computing apk sha1.
D/FileApkUtils( 8039): Module already staged or being staged:chimera-modules/MapsModule.apk
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 73bfab76-3ff3-4db4-a38d-106418180f7c
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 73bfab76-3ff3-4db4-a38d-106418180f7c / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/BluetoothManagerService( 1282): Message: 2
D/BluetoothAdapterService(218329368)( 4553): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@176790cf
,D/BluetoothManagerService( 1282): Sending off request.
D/BluetoothAdapterService(218329368)( 4553): disable() called...
D/LGBluetoothServiceAdapter( 4553): [BTUI] Precleanup
D/LGBluetoothDeviceModeControllManager( 4553): getDeviceMode  deviceMode 0
D/LocationManagerService( 1282): getAllProviders()=[passive, gps, network]
,D/Ulp_jni ( 1282): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1282): JNI:system_update. Event-4
D/BluetoothAdapterService(218329368)( 4553): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@176790cf
D/BluetoothAdapterState( 4553): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 4553): Setting state to 13
I/BluetoothAdapterState( 4553): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService(218329368)( 4553): updateAdapterState() - Broadcasting state to 1 receivers.
,D/DexOptUtils( 8039): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-eadf3a03a14c8741cdcafd8c1812c44afdd347da/MapsModule.apk is already optimized. Bailing.
D/FileApkUtils( 8039): Keeping up-to-date module: module-eadf3a03a14c8741cdcafd8c1812c44afdd347da
D/ChimeraCfgMgr( 8039): Reading stored module config
D/BluetoothAdapterProperties( 4553): onBluetoothDisable()
I/BluetoothAdapterState( 4553): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterService(218329368)( 4553): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@176790cf
,I/bt-btif ( 4553): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothManagerService( 1282): Message: 60
D/BluetoothManagerService( 1282): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1282): Bluetooth State Change Intent: 12 -> 13
D/BluetoothAdapterProperties( 4553): Scan Mode:20
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 5ad1145f-ef5f-4219-b387-543ca4782e0b
D/BluetoothAdapterState( 4553): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
I/bt-btif ( 4553): BTIF DISABLE BLUETOOTH:: current btif_core_radio_refcount: 1, btif_core_state: 2, btif_core_cb.dut_mode: 0
E/bt-btif ( 4553): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,D/bt-btif ( 4553): btsock_ctrl_hci_cleanup(L202): poll handle:4
W/ActivityManager( 1282): getRunningAppProcesses: caller 10361 does not hold REAL_GET_TASKS; limiting output
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 5ad1145f-ef5f-4219-b387-543ca4782e0b / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/WifiServiceImplEx( 1282): setWifiEnabled: false pid=7557, uid=10361, package= com.example.hello, App Lable : HelloWorld
I/bt-btif ( 4553): BTA_JvDeleteRecord
D/WifiService( 1282): setWifiEnabled: false pid=7557, uid=10361
I/bt-btif ( 4553): BTA_JvRfcommStopServer
I/bt-btif ( 4553): BTA_JvDeleteRecord
I/bt-btif ( 4553): BTA_JvRfcommStopServer
V/BluetoothPbapService( 4553): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-btif ( 4553): invalid rfc slot id: 1
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/GmsModuleFndr( 8039): Beginning GMS chimera module scan
,D/IOP_DB_BT( 4553): db_close: nbr users 0
D/IOP_DB_BT( 4553): db_close: free database
W/bt-btif ( 4553): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
D/btif_config_util( 4553): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/btif_config_util( 4553): enum_config(L300): in, key:Adapter, value:BluezMigrationDone
D/btif_config_util( 4553): enum_config(L302): section name:Local, key name:Adapter, value name:BluezMigrationDone, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:Adapter, value:BluezMigrationDone
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:Adapter, value:Address
D/btif_config_util( 4553): enum_config(L302): section name:Local, key name:Adapter, value name:Address, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:Adapter, value:Address
D/btif_config_util( 4553): enum_config(L344): out, value:f8:95:c7:87:3c:51
D/btif_config_util( 4553): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IR
D/btif_config_util( 4553): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IR, value type:binary
D/btif_config_util( 4553): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IR
D/btif_config_util( 4553): enum_config(L344): out, value:����:r4W�J�c��^���m��
D/btif_config_util( 4553): �]�j8oV|\!�2�d��	t�y����LE_LOCAL_KEY_ER
D/btif_config_util( 4553): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IRK
D/btif_config_util( 4553): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IRK, value type:binary
E/bt-btif ( 4553): Ignore event 10ms_evt: wrong handle = 1280 
D/btif_config_util( 4553): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IRK
W/bt-obex ( 4553): Ignore event 10 in state 1
D/btif_config_util( 4553): enum_config(L344): out, value:��m��
D/btif_config_util( 4553): �]�j8oV|\!�2�d��	t�y����LE_LOCAL_KEY_ER
D/btif_config_util( 4553): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_DHK
D/btif_config_util( 4553): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_DHK, value type:binary
D/btif_config_util( 4553): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_DHK
D/btif_config_util( 4553): enum_config(L344): out, value:�2�d��	t�y����LE_LOCAL_KEY_ER
I/bt-btif ( 4553): HAL bt_op_callbacks->ops_state_cb
D/btif_config_util( 4553): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_ER
D/BluetoothOPPServiceJni( 4553): ops_state_cb(L223):  ops_state_cb state:3
D/btif_config_util( 4553): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_ER, value type:binary
E/        ( 4553): ### ASSERT : vendor/lge/external/bluetooth/bluedroid_brcm/main/../iop_hooks/iop_db_hooks.c line 96 no handle (0) ###
D/btif_config_util( 4553): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_ER
D/btif_config_util( 4553): enum_config(L344): out, value:�<#��%9T�u�-x�`ScanMode
D/btif_config_util( 4553): enum_config(L300): in, key:Adapter, value:ScanMode
D/btif_config_util( 4553): enum_config(L302): section name:Local, key name:Adapter, value name:ScanMode, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:Adapter, value:ScanMode
D/OppService( 4553): onOpsStateChange() :3
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:Adapter, value:DiscoveryTimeout
D/btif_config_util( 4553): enum_config(L302): section name:Local, key name:Adapter, value name:DiscoveryTimeout, value type:int
E/bt-btif ( 4553): bta_gattc_deregister Deregister Failedm unknown client cif
D/btif_config_util( 4553): enum_config(L343): out, key:Adapter, value:DiscoveryTimeout
D/btif_config_util( 4553): enum_config(L344): out, value:x
D/btif_config_util( 4553): enum_config(L300): in, key:Adapter, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Local, key name:Adapter, value name:Name, value type:string
D/btif_config_util( 4553): enum,_config(L343): out, key:Adapter, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:G4-1
D/btif_config_util( 4553): enum_config(L300): in, key:AutoPairBlacklist, value:AddressBlacklist
D/btif_config_util( 4553): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:AddressBlacklist, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:AutoPairBlacklist, value:AddressBlacklist
D/btif_config_util( 4553): enum_config(L344): out, value:00:02:C7,00:16:FE,00:19:C1,00:1B:FB,00:1E:3D,00:21:4F,00:23:06,00:24:33,00:A0:79,00:0E:6D,00:13:E0,00:21:E8,00:60:57,00:0E:9F,00:12:1C,00:18:91,00:18:96,00:13:04,00:16:FD,00:22:A0,00:0B:4C,00:60:6F,00:23:3D,00:C0:59,00:0A:30,00:1E:AE,00:1C:D7,00:80:F0,00:12:8A,00:09:93,00:80:37,00:26:7E,00:06:F7,00:13:7B,00:1E:B2,00:07:04,00:13:7B,00:14:0A,00:1A:1B,00:22:4D,00:0B:24,00:1E:B2,00:0B:1F,18:6D:99,00:54:AF,18:6D:99,94:44:44,00:21:CC,04:98:F3,00:26:E8
D/btif_config_util( 4553): enum_config(L300): in, key:AutoPairBlacklist, value:ExactNameBlacklist
D/btif_config_util( 4553): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:ExactNameBlacklist, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:AutoPairBlacklist, value:ExactNameBlacklist
D/btif_config_util( 4553): enum_config(L344): out, value:Motorola IHF1000,i.TechBlueBAND,X5 Stereo v1.3,KML_CAN,Microsoft Mouse
D/btif_config_util( 4553): enum_config(L300): in, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
D/btif_config_util( 4553): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:FixedPinZerosKeyboardBlacklist, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
D/btif_config_util( 4553): enum_config(L344): out, value:00:0F:F6
D/OppService( 4553): Recieved MESSAGE_OPS_DISABLE
D/btif_config_util( 4553): enum_config(L300): in, key:AutoPairBlacklist, value:PartialNameBlacklist
D/btif_config_util( 4553): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:PartialNameBlacklist, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:AutoPairBlacklist, value:PartialNameBlacklist
D/btif_config_util( 4553): enum_config(L344): out, value:BMW,Audi,Parrot,Car
D/btif_config_util( 4553): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Manufacturer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Manufacturer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Manufacturer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:LmpVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:LmpVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:LmpVer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:LmpSubVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L344): out, value:	a
D/btif_config_util( 4553): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:Note3-1
D/btif_config_util( 4553): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_con,fig(L343): out, key:e0:db:10:1f:c9:5e, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:Z
D/btif_config_util( 4553): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:JustWorks
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:JustWorks, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:JustWorks
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:GlobalTrust, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Service
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Service, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Service
D/btif_config_util( 4553): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 4553): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Manufacturer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Manufacturer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Manufacturer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:LmpVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpVer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:LmpSubVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L344): out, value:A
D/btif_config_util( 4553): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:Thali Test's G2
D/btif_config_util( 4553): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:Z
D/btif_config_util( 4553): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:JustWorks
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:JustWorks, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:JustWorks
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:GlobalTrust, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Service
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Service, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Service
D/btif_config_util( 4553): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 4553): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Manufacturer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Manufacturer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Manufacturer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpVer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpSubVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L344): out, value:�
D/FastDownloadService( 1282): [FastDN][FDS] handleMessage: EVENT_WIFI_SETTING_CHANGED
D/btif_config_util( 4553): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Name
D/FastDownloadService( 1282): [FastDN][FDS] wifi setting is changed to false
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:Thali Test (Galaxy A3)
D/btif_config_util( 4553): enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:Z
D/btif_config_util( 4553): enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:08:ec:a9:50:76:27, value:JustWorks
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:JustWorks, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:08:ec:a9:50:76:27, value:JustWorks
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:08:ec:a9:50:76:27, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:GlobalTrust, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:08:ec:a9:50:76:27, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Service
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Service, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Service
D/btif_config_util( 4553): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 4553): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Manufacturer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:Manufacturer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Manufacturer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:LmpVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:LmpVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:LmpVer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:LmpSubVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L344): out, value:A
D/btif_config_util( 4553): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:S5mini-1
D/btif_config_util( 4553): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:Z
D/btif_config_util( 4553): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:JustWorks
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:JustWorks, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:JustWorks
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:GlobalTrust, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Service
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:Service, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Service
D/btif_config_util( 4553): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 4553): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Manufacturer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Manufacturer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Manufacturer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpVer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpSubVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L344): out, value:#
D/btif_config_util( 4553): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:Nexus 6
D/btif_config_util( 4553): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:Z
D/btif_config_util( 4553): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:JustWorks
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:JustWorks, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:JustWorks
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:GlobalTrust, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Service
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Service, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Service
D/btif_config_util( 4553): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 4553): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Manufacturer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Manufacturer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Manufacturer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:LmpVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:LmpVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:LmpVer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:LmpSubVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L344): out, value:�
D/btif_config_util( 4553): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:HTC One_M8
D/btif_config_util( 4553): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:Z
D/btif_config_util( 4553): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:JustWorks
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:JustWorks, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:JustWorks
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:GlobalTrust, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Service
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Service, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Service
D/btif_config_util( 4553): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 00006675-7475-7265-6469-616c62756d70 fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 4553): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Manufacturer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpVer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpSubVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L344): out, value:�
D/btif_config_util( 4553): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:HTC Desire 820
D/btif_config_util( 4553): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:Z
D/btif_config_util( 4553): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:JustWorks
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:JustWorks, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:JustWorks
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:GlobalTrust, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Service
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Service, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Service
D/btif_config_util( 4553): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 00006675-7475-7265-6469-616c62756d70 
D/btif_config_util( 4553): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Manufacturer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Manufacturer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Manufacturer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpVer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpSubVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L344): out, value:�
D/btif_config_util( 4553): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:Galaxy S6-1
D/btif_config_util( 4553): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:Z
D/btif_config_util( 4553): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:JustWorks
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:JustWorks, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:JustWorks
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:GlobalTrust, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LinkKeyType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LinkKeyType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LinkKeyType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:PinLength
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:PinLength, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:PinLength
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LinkKey
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LinkKey, value type:binary
D/btif_config_util( 4553): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LinkKey
D/btif_config_util( 4553): enum_config(L344): out, value:�tR��w���𦜻'Manufacturer
D/btif_config_util( 4553): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Service
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Service, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Service
D/btif_config_util( 4553): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 4553): enum_config(L300): in, key:14:b4:84:21:3b:49, value:Manufacturer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:Manufacturer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:14:b4:84:21:3b:49, value:Manufacturer
D/btif_config_util( 4553): enum_config(L344): out, value:H
D/btif_config_util( 4553): enum_config(L300): in, key:14:b4:84:21:3b:49, value:LmpVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:LmpVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:14:b4:84:21:3b:49, value:LmpVer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:14:b4:84:21:3b:49, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:LmpSubVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:14:b4:84:21:3b:49, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L344): out, value:?C
D/btif_config_util( 4553): enum_config(L300): in, key:14:b4:84:21:3b:49, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:14:b4:84:21:3b:49, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:Tab4
D/btif_config_util( 4553): enum_config(L300): in, key:14:b4:84:21:3b:49, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:14:b4:84:21:3b:49, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:Z
D/btif_config_util( 4553): enum_config(L300): in, key:14:b4:84:21:3b:49, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:14:b4:84:21:3b:49, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:14:b4:84:21:3b:49, value:JustWorks
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:JustWorks, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:14:b4:84:21:3b:49, value:JustWorks
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:14:b4:84:21:3b:49, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:GlobalTrust, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:14:b4:84:21:3b:49, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:14:b4:84:21:3b:49, value:Service
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:Service, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:14:b4:84:21:3b:49, value:Service
D/btif_config_util( 4553): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 4553): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Manufacturer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Manufacturer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Manufacturer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:LmpVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:LmpVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:LmpVer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:LmpSubVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L344): out, value:a
D/btif_config_util( 4553): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:Thali Test (Galaxy S5)
D/btif_config_util( 4553): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:Z
D/btif_config_util( 4553): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:JustWorks
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:JustWorks, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:JustWorks
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:GlobalTrust, value type:int
D/btif_config_util( 4553): enum_confi,g(L343): out, key:b0:c5:59:3f:75:69, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Service
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Service, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Service
D/btif_config_util( 4553): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 4553): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Manufacturer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Manufacturer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Manufacturer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:LmpVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:LmpVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:LmpVer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:LmpSubVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L344): out, value:�
D/btif_config_util( 4553): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:Thali Test (Galaxy A5)
D/btif_config_util( 4553): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:Z
D/btif_config_util( 4553): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:DevType
D/btif_config_util( 4553): enum_co,nfig(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:JustWorks
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:JustWorks, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:JustWorks
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:GlobalTrust, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Service
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Service, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Service
D/btif_config_util( 4553): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 4553): enum_config(L300): in, key:80:01:84:8a:b3:68, value:Manufacturer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:Manufacturer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:80:01:84:8a:b3:68, value:Manufacturer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:80:01:84:8a:b3:68, value:LmpVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:LmpVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:80:01:84:8a:b3:68, value:LmpVer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:80:01:84:8a:b3:68, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:LmpSubVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:80:01:84:8a:b3:68, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L344): out, value:�
D/btif_config_util( 4553): enum_config(L300): in, key:80:01:84:8a:b3:68, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:80:01:84:8a:b3:68, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:HTC Desire 820
D/btif_config_util( 4553): enum_config(L300): in, key:80:01:84:8a:b3:68, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:80:01:84:8a:b3:68, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:Z
D/btif_config_util( 4553): enum_config(L300): in, key:80:01:84:8a:b3:68, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:80:01:84:8a:b3:68, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:80:01:84:8a:b3:68, value:JustWorks
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:JustWorks, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:80:01:84:8a:b3:68, value:JustWorks
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:80:01:84:8a:b3:68, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:GlobalTrust, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:80:01:84:8a:b3:68, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:80:01:84:8a:b3:68, value:Service
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:Service, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:80:01:84:8a:b3:68, value:Service
D/btif_config_util( 4553): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 00006675-7475-7265-6469-616c62756d70 
D/btif_config_util( 4553): enum_config(L300): in, key:08:ec:a9:50:75:41, value:Manufacturer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Manufacturer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:08:ec:a9:50:75:41, value:Manufacturer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:08:ec:a9:50:75:41, value:LmpVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:LmpVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:08:ec:a9:50:75:41, value:LmpVer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:08:ec:a9:50:75:41, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:LmpSubVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:08:ec:a9:50:75:41, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L344): out, value:�
D/btif_config_util( 4553): enum_config(L300): in, key:08:ec:a9:50:75:41, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:08:ec:a9:50:75:41, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:A3-1
D/btif_config_util( 4553): enum_config(L300): in, key:08:ec:a9:50:75:41, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:08:ec:a9:50:75:41, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:Z
D/btif_config_util( 4553): enum_config(L300): in, key:08:ec:a9:50:75:41, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:08:ec:a9:50:75:41, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:08:ec:a9:50:75:41, value:JustWorks
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:JustWorks, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:08:ec:a9:50:75:41, value:JustWorks
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:08:ec:a9:50:75:41, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:GlobalTrust, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:08:ec:a9:50:75:41, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:08:ec:a9:50:75:41, value:Service
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Service, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:08:ec:a9:50:75:41, value:Service
D/btif_config_util( 4553): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 4553): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Manufacturer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Manufacturer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Manufacturer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpVer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpSubVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L344): out, value:a
D/btif_config_util( 4553): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:S5-1
D/btif_config_util( 4553): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:Z
D/btif_config_util( 4553): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:JustWorks
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:JustWorks, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:JustWorks
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:GlobalTrust, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Service
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Service, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Service
D/btif_config_util( 4553): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 4553): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Manufacturer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Manufacturer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Manufacturer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpVer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpSubVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L344): out, value:�
D/btif_config_util( 4553): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:XT1072
D/btif_config_util( 4553): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:Z
D/btif_config_util( 4553): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:JustWorks
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:JustWorks, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:JustWorks
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:GlobalTrust, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Service
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Service, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Service
D/btif_config_util( 4553): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 4553): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:AddrType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:AddrType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:AddrType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DMTSupported
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DMTSupported, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DMTSupported
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Manufacturer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Manufacturer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Manufacturer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpVer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpSubVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L344): out, value:�
D/btif_config_util( 4553): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:A5-1
D/btif_config_util( 4553): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:Z
D/btif_config_util( 4553): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:JustWorks
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:JustWorks, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:JustWorks
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:GlobalTrust, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Service
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Service, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Service
D/btif_config_util( 4553): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 4553): enum_config(L300): in, key:f8:95:c7:87:85:54, value:Manufacturer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:f8:95:c7:87:85:54, value name:Manufacturer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:f8:95:c7:87:85:54, value:Manufacturer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:f8:95:c7:87:85:54, value:LmpVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:f8:95:c7:87:85:54, value name:LmpVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:f8:95:c7:87:85:54, value:LmpVer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:f8:95:c7:87:85:54, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:f8:95:c7:87:85:54, value name:LmpSubVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:f8:95:c7:87:85:54, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L344): out, value:A
D/btif_config_util( 4553): enum_config(L300): in, key:f8:95:c7:87:85:54, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:f8:95:c7:87:85:54, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:f8:95:c7:87:85:54, value:Name
D/LGBluetoothAPIService( 4163): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/BleQmManagerService( 4163): [BleQmManagerService]  onReceive:  android.bluetooth.adapter.action.STATE_CHANGED
I/BluetoothMapService( 4553): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 4553): STATE_TURNING_OFF
V/BluetoothMapService( 4553): Handler(): got msg=4
D/BluetoothMapService( 4553): MAP Service closeService in
D/BluetoothMapMasInstance( 4553): MAP Service shutdown
D/btif_config_util( 4553): enum_config(L344): out, value:G3s-1
D/btif_config_util( 4553): enum_config(L300): in, key:f8:95:c7:87:85:54, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:f8:95:c7:87:85:54, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:f8:95:c7:87:85:54, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:Z
D/btif_config_util( 4553): enum_config(L300): in, key:f8:95:c7:87:85:54, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:f8:95:c7:87:85:54, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:f8:95:c7:87:85:54, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:f8:95:c7:87:85:54, value:JustWorks
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:f8:95:c7:87:85:54, value name:JustWorks, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:f8:95:c7:87:85:54, value:JustWorks
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:f8:95:c7:87:85:54, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:f8:95:c7:87:85:54, value name:GlobalTrust, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:f8:95:c7:87:85:54, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:f8:95:c7:87:85:54, value:Service
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:f8:95:c7:87:85:54, value name:Service, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:f8:95:c7:87:85:54, value:Service
D/btif_config_util( 4553): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 4553): enum_config(L300): in, key:00:00:00:00:6d:82, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:00:00:00:00:6d:82, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:00:00:00:00:6d:82, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:�
D/btif_config_util( 4553): enum_config(L300): in, key:00:00:00:00:6d:82, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:00:00:00:00:6d:82, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:00:00:00:00:6d:82, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:��
D/btif_config_util( 4553): enum_config(L300): in, key:00:00:00:00:6d:82, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:00:00:00:00:6d:82, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:00:00:00:00:6d:82, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Manufacturer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Manufacturer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Manufacturer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:LmpVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:LmpVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:LmpVer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:LmpSubVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L344): out, value:�
D/btif_config_util( 4553): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:XT1039
D/btif_config_util( 4553): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:DevClass
D/btif_config_util( 4553): enum_,config(L344): out, value:Z
D/btif_config_util( 4553): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:JustWorks
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:JustWorks, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:JustWorks
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:GlobalTrust, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Service
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Service, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Service
D/btif_config_util( 4553): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/BluetoothAdapterService(218329368)( 4553): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@176790cf
D/btif_config_util( 4553): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Manufacturer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:Manufacturer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:Manufacturer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:LmpVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:LmpVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:LmpVer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:LmpSubVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L344): out, value:"
D/btif_config_util( 4553): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:Note4-1
D/btif_config_util( 4553): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:Z
D/btif_config_util( 4553): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:JustWorks
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:JustWorks, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:JustWorks
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:GlobalTrust, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Service
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:Service, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:Service
D/btif_config_util( 4553): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 4553): enum_config(L300): in, key:00:00:00:00:08:00, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:00:00:00:00:08:00, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:00:00:00:00:08:00, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:00:00:00:00:08:00, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:00:00:00:00:08:00, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:00:00:00:00:08:00, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:Manufacturer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Manufacturer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Manufacturer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:LmpVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:LmpVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:LmpVer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:LmpSubVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L344): out, value:	a
D/btif_config_util( 4553): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:Nexus 5
D/btif_config_util( 4553): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:Z
D/btif_config_util( 4553): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:JustWorks
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67,, value name:JustWorks, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:JustWorks
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:GlobalTrust, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:Service
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Service, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Service
D/btif_config_util( 4553): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 4553): enum_config(L300): in, key:58:3f:54:73:64:c0, value:Manufacturer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:Manufacturer, value type:int
D/BluetoothAdapterService(218329368)( 4553): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@176790cf
D/btif_config_util( 4553): enum_config(L343): out, key:58:3f:54:73:64:c0, value:Manufacturer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:58:3f:54:73:64:c0, value:LmpVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:LmpVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:58:3f:54:73:64:c0, value:LmpVer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:58:3f:54:73:64:c0, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:LmpSubVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:58:3f:54:73:64:c0, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L344): out, value:�
D/btif_config_util( 4553): enum_config(L300): in, key:58:3f:54:73:64:c0, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:58:3f:54:73:64:c0, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:G3-1
D/btif_config_util( 4553): enum_config(L300): in, key:58:3f:54:73:64:c0, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:58:3f:54:73:64:c0, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:Z
D/btif_config_util( 4553): enum_config(L300): in, key:58:3f:54:73:64:c0, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:58:3f:54:73:64:c0, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:58:3f:54:73:64:c0, value:JustWorks
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:JustWorks, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:58:3f:54:73:64:c0, value:JustWorks
D/btif_config_util( 4553): enum_,config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:58:3f:54:73:64:c0, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:GlobalTrust, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:58:3f:54:73:64:c0, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:58:3f:54:73:64:c0, value:Service
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:Service, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:58:3f:54:73:64:c0, value:Service
D/btif_config_util( 4553): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 4553): enum_config(L300): in, key:08:00:00:00:9b:6e, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:08:00:00:00:9b:6e, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:08:00:00:00:9b:6e, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:�
D/btif_config_util( 4553): enum_config(L300): in, key:08:00:00:00:9b:6e, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:08:00:00:00:9b:6e, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:08:00:00:00:9b:6e, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:��
D/btif_config_util( 4553): enum_config(L300): in, key:08:00:00:00:9b:6e, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:08:00:00:00:9b:6e, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:08:00:00:00:9b:6e, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:Manufacturer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:Manufacturer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:Manufacturer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:LmpVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:LmpVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:LmpVer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:LmpSubVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L344): out, value:	a
D/btif_config_util( 4553): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:Nexus 5
D/btif_config_util( 4553): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:34:,fc:ef:11:b1:66, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:Z
D/btif_config_util( 4553): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:JustWorks
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:JustWorks, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:JustWorks
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:GlobalTrust, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:Service
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:Service, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:Service
D/btif_config_util( 4553): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 4553): enum_config(L300): in, key:0c:a8:1b:de:a9:a9, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:0c:a8:1b:de:a9:a9, value name:Name, value type:string
D/ConnectivityService( 1282): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/btif_config_util( 4553): enum_config(L343): out, key:0c:a8:1b:de:a9:a9, value:Name
D/ConnectivityService( 1282): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/btif_config_util( 4553): enum_config(L344): out, value:����
D/WifiHS20( 1282): hidePasspointNotification off =false
D/btif_config_util( 4553): enum_config(L300): in, key:0c:a8:1b:de:a9:a9, value:DevClass
D/WifiHS20( 1282): hidePasspointNotification off =false
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:0c:a8:1b:de:a9:a9, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:0c:a8:1b:de:a9:a9, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:��
D/btif_config_util( 4553): enum_config(L300): in, key:0c:a8:1b:de:a9:a9, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:0c:a8:1b:de:a9:a9, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:0c:a8:1b:de:a9:a9, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:03:00:00:00:a9:81, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:03:00:00:00:a9:81, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:03:00:00:00:a9:81, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:��
D/btif_config_util( 4553): enum_config(L300): in, key:03:00:00:00:a9:81, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:03:00:00:00:a9:81, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:03:00:00:00:a9:81, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:L�
D/btif_config_util( 4553): enum_config(L300): in, key:03:00:00:00:a9:81, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:03:00:00:00:a9:81, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:03:00:00:00:a9:81, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:Manufacturer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:Manufacturer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:Manufacturer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:LmpVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:LmpVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:LmpVer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:LmpSubVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L344): out, value:#
D/btif_config_util( 4553): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:onem9-1
D/btif_config_util( 4553): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:Z
D/btif_config_util( 4553): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:JustWorks
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:JustWorks, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:JustWorks
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:GlobalTrust, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:Service
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:Service, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:Service
D/btif_config_util( 4553): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 4553): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:Manufacturer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:Manufacturer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:Manufacturer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:LmpVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:LmpVer, value type:int
I/[SystemUI]QuickSettingsHandler( 3410): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
D/btif_config_util( 4553): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:LmpVer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:LmpSubVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:LmpSubVer
I/[SystemUI]BluetoothHandler( 3410): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
D/btif_config_util( 4553): enum_config(L344): out, value:�
D/btif_config_util( 4553): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:HTC One M8s
D/btif_config_util( 4553): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:Z
D/btif_config_util( 4553): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:JustWorks
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:JustWorks, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:JustWorks
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:GlobalTrust, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:Service
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:Service, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:Service
D/btif_config_util( 4553): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 00006675-7475-7265-6469-616c62756d70 
D/btif_config_util( 4553): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Manufacturer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:Manufacturer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Manufacturer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:LmpVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:LmpVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:LmpVer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:LmpSubVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:ALE-L21
D/btif_config_util( 4553): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:Z
D/btif_config_util( 4553): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:JustWorks
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:JustWorks, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:JustWorks
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:GlobalTrust, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Service
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:Service, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Service
D/btif_config_util( 4553): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 4553): enum_config(L300): in, key:24:59:5c:de:a9:59, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:24:59:5c:de:a9:59, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:24:59:5c:de:a9:59, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:�Lި���,a\ޛ
D/btif_config_util( 4553): enum_config(L300): in, key:24:59:5c:de:a9:59, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:24:59:5c:de:a9:59, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:24:59:5c:de:a9:59, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:��B
D/btif_config_util( 4553): enum_config(L300): in, key:24:59:5c:de:a9:59, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:24:59:5c:de:a9:59, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:24:59:5c:de:a9:59, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:94:0e:40:e6:ff:ff, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:94:0e:40:e6:ff:ff, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:94:0e:40:e6:ff:ff, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): @�
D/btif_config_util( 4553): enum_config(L300): in, key:94:0e:40:e6:ff:ff, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:94:0e:40:e6:ff:ff, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:94:0e:40:e6:ff:ff, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:D��
D/btif_config_util( 4553): enum_config(L300): in, key:94:0e:40:e6:ff:ff, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:94:0e:40:e6:ff:ff, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:94:0e:40:e6:ff:ff, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:30:0f:80:e6:ff:ff, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:30:0f:80:e6:ff:ff, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:30:0f:80:e6:ff:ff, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:��
D/btif_config_util( 4553): enum_config(L300): in, key:30:0f:80:e6:ff:ff, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:30:0f:80:e6:ff:ff, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:30:0f:80:e6:ff:ff, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:���
D/btif_config_util( 4553): enum_config(L300): in, key:30:0f:80:e6:ff:ff, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:30:0f:80:e6:ff:ff, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:30:0f:80:e6:ff:ff, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:f4:16:19:de:a9:19, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:f4:16:19:de:a9:19, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:f4:16:19:de:a9:19, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:�	ޠ���B��B�
D/btif_config_util( 4553): enum_config(L300): in, key:f4:16:19:de:a9:19, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:f4:16:19:de:a9:19, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:f4:16:19:de:a9:19, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:���
D/btif_config_util( 4553): enum_config(L300): in, key:f4:16:19:de:a9:19, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:f4:16:19:de:a9:19, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:f4:16:19:de:a9:19, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:08:00:00:00:9b:ae, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:08:00:00:00:9b:ae, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:08:00:00:00:9b:ae, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:i������p��p��
D/btif_config_util( 4553): enum_config(L300): in, key:08:00:00:00:9b:ae, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:08:00:00:00:9b:ae, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:08:00:00:00:9b:ae, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:���
D/btif_config_util( 4553): enum_config(L300): in, key:08:00:00:00:9b:ae, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:08:00:00:00:9b:ae, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:08:00:00:00:9b:ae, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:24:99:f6:dd:a9:99, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:24:99:f6:dd:a9:99, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:24:99:f6:dd:a9:99, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:	�ݨ�4���ݛ
D/btif_config_util( 4553): enum_config(L300): in, key:24:99:f6:dd:a9:99, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:24:99:f6:dd:a9:99, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:24:99:f6:dd:a9:99, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:���
D/btif_config_util( 4553): enum_config(L300): in, key:24:99:f6:dd:a9:99, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:24:99:f6:dd:a9:99, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:24:99:f6:dd:a9:99, value:DevType
V/BluetoothMapMasInstance( 4553): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 4553): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 4553): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 4553): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 4553): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 4553): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 4553): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 4553): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
D/LGBluetoothMapAdapter( 4553): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 4553): MAP Service closeService out
V/BluetoothPbapReceiver( 4553): PbapReceiver onReceive 
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:f4:96:f6:dd:a9:99, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:f4:96:f6:dd:a9:99, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:f4:96:f6:dd:a9:99, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:	�ݠ�����P���P�
D/btif_config_util( 4553): enum_config(L300): in, key:f4:96:f6:dd:a9:99, value:DevClass
V/BluetoothPbapReceiver( 4553): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:f4:96:f6:dd:a9:99, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:f4:96:f6:dd:a9:99, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:���
D/btif_config_util( 4553): enum_config(L300): in, key:f4:96:f6:dd:a9:99, value:DevType
V/BluetoothPbapReceiver( 4553): ***********state = 13
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:f4:96:f6:dd:a9:99, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:f4:96:f6:dd:a9:99, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:00:00:00:00:6d:f2, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:00:00:00:00:6d:f2, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:00:00:00:00:6d:f2, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:���
D/btif_config_util( 4553): enum_config(L300): in, key:00:00:00:00:6d:f2, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:00:00:00:00:6d:f2, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:00:00:00:00:6d:f2, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:���
D/btif_config_util( 4553): enum_config(L300): in, key:00:00:00:00:6d:f2, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:00:00:00:00:6d:f2, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:00:00:00:00:6d:f2, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:08:00:00:00:9b:4e, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:08:00:00:00:9b:4e, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:08:00:00:00:9b:4e, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:	'ް�B��E��E�
D/btif_config_util( 4553): enum_config(L300): in, key:08:00:00:00:9b:4e, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:08:00:00:00:9b:4e, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:08:00:00:00:9b:4e, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:��I
D/btif_config_util( 4553): enum_config(L300): in, key:08:00:00:00:9b:4e, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:08:00:00:00:9b:4e, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:08:00:00:00:9b:4e, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:38:94:96:b5:06:dc, value:Manufacturer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:Manufacturer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:38:94:96:b5:06:dc, value:Manufacturer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:38:94:96:b5:06:dc, value:LmpVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:LmpVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:38:94:96:b5:06:dc, value:LmpVer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:38:94:96:b5:06:dc, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:LmpSubVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:38:94:96:b5:06:dc, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L344): out, value:�
D/btif_config_util( 4553): enum_config(L300): in, key:38:94:96:b5:06:dc, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:38:94:96:b5:06:dc, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:Galaxy S5-2
D/btif_config_util( 4553): enum_config(L300): in, key:38:94:96:b5:06:dc, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:38:94:96:b5:06:dc, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:Z
D/btif_config_util( 4553): enum_config(L300): in, key:38:94:96:b5:06:dc, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:38:94:96:b5:06:dc, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:38:94:96:b5:06:dc, value:JustWorks
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:JustWorks, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:38:94:96:b5:06:dc, value:JustWorks
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:38:94:96:b5:06:dc, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:GlobalTrust, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:38:94:96:b5:06:dc, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:38:94:96:b5:06:dc, value:Service
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:Service, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:38:94:96:b5:06:dc, value:Service
D/btif_config_util( 4553): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 4553): enum_config(L300): in, key:00:00:00:00:5a:ad, value:Manufacturer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:Manufacturer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:00:00:00:00:5a:ad, value:Manufacturer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:00:00:00:00:5a:ad, value:LmpVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:LmpVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:00:00:00:00:5a:ad, value:LmpVer
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:00:00:00:00:5a:ad, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:LmpSubVer, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:00:00:00:00:5a:ad, value:LmpSubVer
D/btif_config_util( 4553): enum_config(L344): out, value:�
D/btif_config_util( 4553): enum_config(L300): in, key:00:00:00:00:5a:ad, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:00:00:00:00:5a:ad, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:A3-1
D/btif_config_util( 4553): enum_config(L300): in, key:00:00:00:00:5a:ad, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:00:00:00:00:5a:ad, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:Z
D/btif_config_util( 4553): enum_config(L300): in, key:00:00:00:00:5a:ad, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:00:00:00:00:5a:ad, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:00:00:00:00:5a:ad, value:JustWorks
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:JustWorks, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:00:00:00:00:5a:ad, value:JustWorks
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:00:00:00:00:5a:ad, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:GlobalTrust, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:00:00:00:00:5a:ad, value:GlobalTrust
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:24:0f:40:e6:ff:ff, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:24:0f:40:e6:ff:ff, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:24:0f:40:e6:ff:ff, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:@�
D/btif_config_util( 4553): enum_config(L300): in, key:24:0f:40:e6:ff:ff, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:24:0f:40:e6:ff:ff, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:24:0f:40:e6:ff:ff, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:���
D/btif_config_util( 4553): enum_config(L300): in, key:24:0f:40:e6:ff:ff, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:24:0f:40:e6:ff:ff, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:24:0f:40:e6:ff:ff, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:24:d9:2f:de:a9:d9, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:24:d9:2f:de:a9:d9, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:24:d9:2f:de:a9:d9, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:24:d9:2f:de:a9:d9, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:24:d9:2f:de:a9:d9, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:24:d9:2f:de:a9:d9, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:00:00:00:00:6d:12, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:00:00:00:00:6d:12, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:00:00:00:00:6d:12, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:��
D/btif_config_util( 4553): enum_config(L300): in, key:00:00:00:00:6d:12, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:00:00:00:00:6d:12, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:00:00:00:00:6d:12, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:��
D/btif_config_util( 4553): enum_config(L300): in, key:00:00:00:00:6d:12, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:00:00:00:00:6d:12, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:00:00:00:00:6d:12, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:88:0e:80:e6:ff:ff, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:88:0e:80:e6:ff:ff, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:88:0e:80:e6:ff:ff, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:��
D/btif_config_util( 4553): enum_config(L300): in, key:88:0e:80:e6:ff:ff, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:88:0e:80:e6:ff:ff, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:88:0e:80:e6:ff:ff, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:H��
D/btif_config_util( 4553): enum_config(L300): in, key:88:0e:80:e6:ff:ff, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:88:0e:80:e6:ff:ff, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:88:0e:80:e6:ff:ff, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:0c:18:0c:de:a9:19, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:0c:18:0c:de:a9:19, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:0c:18:0c:de:a9:19, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:�������hr�hr�
D/btif_config_util( 4553): enum_config(L300): in, key:0c:18:0c:de:a9:19, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:0c:18:0c:de:a9:19, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:0c:18:0c:de:a9:19, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:���
D/btif_config_util( 4553): enum_config(L300): in, key:0c:18:0c:de:a9:19, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:0c:18:0c:de:a9:19, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:0c:18:0c:de:a9:19, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:20:00:00:00:00:00, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:20:00:00:00:00:00, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:20:00:00:00:00:00, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:t��8��� 
D/btif_config_util( 4553): enum_config(L300): in, key:20:00:00:00:00:00, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:20:00:00:00:00:00, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:20:00:00:00:00:00, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:�
D/btif_config_util( 4553): enum_config(L300): in, key:20:00:00:00:00:00, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:20:00:00:00:00:00, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:20:00:00:00:00:00, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:88:c6:26:19:97:dc, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:88:c6:26:19:97:dc, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:88:c6:26:19:97:dc, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:88:c6:26:19:97:dc, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:88:c6:26:19:97:dc, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:88:c6:26:19:97:dc, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:88:c6:26:19:97:dc, value:AddrType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:88:c6:26:19:97:dc, value name:AddrType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:88:c6:26:19:97:dc, value:AddrType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:fc:f3:1c:6e:2d:57, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:fc:f3:1c:6e:2d:57, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:fc:f3:1c:6e:2d:57, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:fc:f3:1c:68:15:41, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:fc:f3:1c:68:15:41, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:fc:f3:1c:68:15:41, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:c8:d9:53:a0:ea:82, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:c8:d9:53:a0:ea:82, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:c8:d9:53:a0:ea:82, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:c8:d9:53:a0:ec:4e, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:c8:d9:53:a0:ec:4e, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:c8:d9:53:a0:ec:4e, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:e0:b7:20:28:c5:81, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:e0:b7:20:28:c5:81, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:e0:b7:20:28:c5:81, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:54:be:8a:2a:e1:73, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:54:be:8a:2a:e1:73, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:54:be:8a:2a:e1:73, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:f0:8b:b2:7e:ea:d2, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:f0:8b:b2:7e:ea:d2, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:f0:8b:b2:7e:ea:d2, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:58:be:ea:0c:ac:d5, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:58:be:ea:0c:ac:d5, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:58:be:ea:0c:ac:d5, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:HTC One M8s
D/btif_config_util( 4553): enum_config(L300): in, key:58:be:ea:0c:ac:d5, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:58:be:ea:0c:ac:d5, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:58:be:ea:0c:ac:d5, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300):, in, key:58:be:ea:0c:ac:d5, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:58:be:ea:0c:ac:d5, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:58:be:ea:0c:ac:d5, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:58:be:ea:0c:ac:d5, value:AddrType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:58:be:ea:0c:ac:d5, value name:AddrType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:58:be:ea:0c:ac:d5, value:AddrType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:66:72:3c:79:d2:ed, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:66:72:3c:79:d2:ed, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:66:72:3c:79:d2:ed, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:79:5c:ac:41:e2:ce, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:79:5c:ac:41:e2:ce, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:79:5c:ac:41:e2:ce, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:0c:98:f6:dd:a9:99, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:0c:98:f6:dd:a9:99, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:0c:98:f6:dd:a9:99, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:	��p���C��C�
D/btif_config_util( 4553): enum_config(L300): in, key:0c:98:f6:dd:a9:99, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:0c:98:f6:dd:a9:99, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:0c:98:f6:dd:a9:99, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:���
D/btif_config_util( 4553): enum_config(L300): in, key:0c:98:f6:dd:a9:99, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:0c:98:f6:dd:a9:99, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:0c:98:f6:dd:a9:99, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:fc:f3:1c:a2:30:44, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:fc:f3:1c:a2:30:44, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:fc:f3:1c:a2:30:44, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:55:ce:01:ef:8c:a5, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:55:ce:01:ef:8c:a5, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:55:ce:01:ef:8c:a5, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:6e:88:dc:7c:fd:26, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:6e:88:dc:7c:fd:26, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:6e:88:dc:7c:fd:26, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:6e:ee:f8:11:8b:a4, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:6e:ee:f8:11:8b:a4, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:6e:ee:f8:11:8b:a4, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:HTC One M8s
D/btif_config_util( 4553): enum_config(L300): in, key:6e:ee:f8:11:8b:a4, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:6e:ee:f8:11:8b:a4, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:6e:ee:f8:11:8b:a4, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:6e:ee:f8:11:8b:a4, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:6e:ee:f8:11:8b:a4, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:6e:ee:f8:11:8b:a4, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:6e:ee:f8:11:8b:a4, value:AddrType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:6e:ee:f8:11:8b:a4, value name:AddrType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:6e:ee:f8:11:8b:a4, value:AddrType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:7c:ab:09:40:44:f7, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:7c:ab:09:40:44:f7, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:7c:ab:09:40:44:f7, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:HTC One M8s
D/btif_config_util( 4553): enum_config(L300): in, key:7c:ab:09:40:44:f7, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:7c:ab:09:40:44:f7, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:7c:ab:09:40:44:f7, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:7c:ab:09:40:44:f7, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:7c:ab:09:40:44:f7, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:7c:ab:09:40:44:f7, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:7c:ab:09:40:44:f7, value:AddrType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:7c:ab:09:40:44:f7, value name:AddrType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:7c:ab:09:40:44:f7, value:AddrType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:70:dc:09:f2:8c:9f, value:Name
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:70:dc:09:f2:8c:9f, value name:Name, value type:string
D/btif_config_util( 4553): enum_config(L343): out, key:70:dc:09:f2:8c:9f, value:Name
D/btif_config_util( 4553): enum_config(L344): out, value:HTC One M8s
D/btif_config_util( 4553): enum_config(L300): in, key:70:dc:09:f2:8c:9f, value:DevClass
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:70:dc:09:f2:8c:9f, value name:DevClass, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:70:dc:09:f2:8c:9f, value:DevClass
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:70:dc:09:f2:8c:9f, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:70:dc:09:f2:8c:9f, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:70:dc:09:f2:8c:9f, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:70:dc:09:f2:8c:9f, value:AddrType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:70:dc:09:f2:8c:9f, value name:AddrType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:70:dc:09:f2:8c:9f, value:AddrType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:54:36:60:05:36:7a, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:54:36:60:05:36:7a, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:54:36:60:05:36:7a, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:58:f5:d4:66:00:e7, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:58:f5:d4:66:00:e7, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:58:f5:d4:66:00:e7, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:7c:ca:90:58:e4:df, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:7c:ca:90:58:e4:df, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:7c:ca:90:58:e4:df, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:51:9c:b5:21:65:57, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:51:9c:b5:21:65:57, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:51:9c:b5:21:65:57, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:53:8f:03:8e:00:3c, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:53:8f:03:8e:00:3c, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:53:8f:03:8e:00:3c, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:53:f4:70:85:14:64, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:53:f4:70:85:14:64, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:53:f4:70:85:14:64, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:6d:1c:64:a9:88:80, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:6d:1c:64:a9:88:80, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:6d:1c:64:a9:88:80, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:49:c5:64:5c:74:8c, value:DevType
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 4a3f534f-67b0-42d7-90d4-82287072acc9
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:49:c5:64:5c:74:8c, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:49:c5:64:5c:74:8c, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
D/btif_config_util( 4553): enum_config(L300): in, key:4b:a1:34:a9:32:1d, value:DevType
D/btif_config_util( 4553): enum_config(L302): section name:Remote, key name:4b:a1:34:a9:32:1d, value name:DevType, value type:int
D/btif_config_util( 4553): enum_config(L343): out, key:4b:a1:34:a9:32:1d, value:DevType
D/btif_config_util( 4553): enum_config(L344): out, value:
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 4a3f534f-67b0-42d7-90d4-82287072acc9 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LocationManagerService( 1282): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1282): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1282): JNI:system_update. Event-4
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
I/jxcore-log( 7557): ****TEST TOOK:  5065  ms ****
I/jxcore-log( 7557): 
I/jxcore-log( 7557): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7557): 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 60259dd3-530d-4b02-a588-32a83785d4e7
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 60259dd3-530d-4b02-a588-32a83785d4e7 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
E/WifiStateMachine( 1282): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1282): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 0e104402-cca0-4d90-a975-45cced602f6d
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 0e104402-cca0-4d90-a975-45cced602f6d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/GmsModuleFndr( 8039): Module pkg com.google.android.apps.kids.familylink not installed, skipping
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - a53bfb02-0d5b-4b75-bd74-930b138e9929
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - a53bfb02-0d5b-4b75-bd74-930b138e9929 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/ChimeraCfgMgr( 8039): Beginning module configuration check
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/ChimeraCfgMgr( 8039): Module APKs unchanged, check complete
I/Gmail   ( 8191): notifyAccountChanged
V/BluetoothPbapReceiver( 4553): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 4553): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 4553): state: 13
V/BluetoothPbapService( 4553): Pbap Service closeService in
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 6796770b-5fb6-4726-a0e8-78553dc068c2
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 6796770b-5fb6-4726-a0e8-78553dc068c2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
I/Gmail   ( 8191): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/BluetoothPbapService( 4553): successfully stopped pbap service
V/BluetoothPbapService( 4553): Pbap Service closeService out
V/BluetoothPbapService( 4553): Pbap Service onDestroy
,V/BluetoothPbapService( 4553): Pbap Service closeService in
V/BluetoothPbapService( 4553): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 4553): [BTUI] cleanup
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 766bfdf6-64a9-4048-9134-1b8b1aabd6d0
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 766bfdf6-64a9-4048-9134-1b8b1aabd6d0 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 0048bf62-4366-4a74-907b-ce3b06c110bd
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 0048bf62-4366-4a74-907b-ce3b06c110bd / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
E/LGBluetoothEventManager( 7382): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - f8d7d334-b7f8-4cf1-abd3-dc9816b57553
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - f8d7d334-b7f8-4cf1-abd3-dc9816b57553 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
I/Gmail   ( 8191): getAccountsCursor
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/CommandListener(  463): Clearing all IP addresses on wlan0
I/Netd    (  463): M: Get netlink event, ifname: wlan0 action: 7
D/DhcpStateMachine( 1282): RunningState{ when=-2ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 3315adda-1603-4fed-94f4-cc4f279135a8
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 3315adda-1603-4fed-94f4-cc4f279135a8 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/libc-netbsd( 1282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Netd    (  463): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  463): M: Get netlink event, ifname: wlan0 action: 7
D/libc-netbsd( 1282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]NetworkController( 3410): onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 (has extras) }
I/Gmail   ( 8191): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/WfdStateTracker( 4163): handleWifiStateChangedEvent: 0
E/WifiStateMachine( 1282): scanCount==0 - aborting
D/LgWifiTrafficPoller( 1282): ENABLE_TRAFFIC_STATS_POLL, mTriggeringTput = 100Mbits
D/WifiOffDelayIfNotUsed( 1282): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - ba25acd0-62b0-47e8-a927-eee5b33e7ca7
D/WifiOffDelayIfNotUsed( 1282): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LgWifiTrafficPoller( 1282): ENABLE_TRAFFIC_STATS_POLL, mTriggeringTput = 100Mbits
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - ba25acd0-62b0-47e8-a927-eee5b33e7ca7 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
V/WfdStateTracker( 4163): WfdStateTracker handleDirectStateChangedEvent: 0
D/WfdsService( 4163): WifiP2pState is changed : false
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/WfdsService( 4163): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WifiScanningService( 1282): SCAN_AVAILABLE : 1
I/Gmail   ( 8191): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/RttService( 1282): SCAN_AVAILABLE : 1
D/WifiScanningService( 1282): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService( 1282): DefaultState
D/RttService( 1282): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]QuickSettingsHandler( 3410): Got action android.net.wifi.STATE_CHANGE at null
I/Gmail   ( 8191): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/WfdsService( 4163): Set the WFDS Monitor: false
D/WfdsMonitor( 4163): WFDS Monitor is stopped
D/WfdsService( 4163): STATE : WfdsDisabledState - enter
D/WfdsService( 4163): WFDS: Scanner is paused
D/CtrlSupplicant( 4163): Received on exit socket, terminate
E/CtrlSupplicant( 4163): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsDiscoveryStore( 4163): Clear Discovery Method Map: ScanAlwaysMode false
D/WfdsMonitor( 4163): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 4163): WfdsMonitorThread is received the interrupt - closing
D/WifiNetworkAgent( 1282): NetworkAgent: NetworkAgent channel lost
W/WfdsSession:Controller( 4163): DefaultState - msg [9441355] is not handled
I/[SystemUI]QuickSettingsHandler( 3410): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 3410): Remote
I/[SystemUI]NetworkController( 3410): onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 (has extras) }
I/[SystemUI]QuickSettingsHandler( 3410): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 3410): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 3410): Remote
I/[SystemUI]QuickSettingsHandler( 3410): Got action android.net.wifi.p2p.STATE_CHANGED at null
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - d4993ef2-3ed9-4c07-980c-97875d8b93da
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - d4993ef2-3ed9-4c07-980c-97875d8b93da / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/libc-netbsd( 1282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 25be324e-8988-406d-848c-db6b87187ea0
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 25be324e-8988-406d-848c-db6b87187ea0 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 1da2a246-22d1-4f91-a862-4e7a90cd52eb
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 1da2a246-22d1-4f91-a862-4e7a90cd52eb / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 41c53c33-50d8-49ac-98b2-eabba89498e6
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 41c53c33-50d8-49ac-98b2-eabba89498e6 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 4019f137-59a3-4201-9f09-3519bb9ac520
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 4019f137-59a3-4201-9f09-3519bb9ac520 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 4c5d7f71-8d54-49a4-9e27-dd68168afda6
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 4c5d7f71-8d54-49a4-9e27-dd68168afda6 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 6c991d0f-6693-471e-bb41-d5d13b1472eb
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 6c991d0f-6693-471e-bb41-d5d13b1472eb / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 4f948d0f-e5bd-4a2f-bc7b-b9736bb93386
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 4f948d0f-e5bd-4a2f-bc7b-b9736bb93386 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - e77c7fbe-1bbd-422b-9d53-596833e396cd
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - e77c7fbe-1bbd-422b-9d53-596833e396cd / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - cb10dc0e-4956-4101-9dcd-07d616009e00
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - cb10dc0e-4956-4101-9dcd-07d616009e00 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/CommandListener(  463): Clearing all IP addresses on wlan0
D/ConnectivityService( 1282): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1282): disableDataServiceNotify
D/DSQN    ( 1282): stop dsqn bin
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 99d66707-1bc4-42a7-a719-ea82a245eaba
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 99d66707-1bc4-42a7-a719-ea82a245eaba / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
E/WifiStateMachine( 1282): SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
D/WifiHS20( 1282): hidePasspointNotification off =false
D/LgWifiTrafficPoller( 1282): ENABLE_TRAFFIC_STATS_POLL, mTriggeringTput = 100Mbits
I/[SystemUI]NetworkController( 3410): onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 (has extras) }
D/WifiOffDelayIfNotUsed( 1282): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
I/[SystemUI]QuickSettingsHandler( 3410): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 3410): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 3410): Remote
V/WfdStateTracker( 4163): WfdStateTracker handleDirectStateChanged,Event: 6
I/[SystemUI]NetworkController( 3410): onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 70ec249a-13ac-4ded-85e9-c71f134273c7
I/[SystemUI]QuickSettingsHandler( 3410): Got action android.net.wifi.WIFI_STATE_CHANGED at null
I/WifiServerServiceExt( 1282): WIFI_STATE_CHANGED_ACTION [0]
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 70ec249a-13ac-4ded-85e9-c71f134273c7 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/WifiServerServiceExt( 1282): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1282): setSupplicantStateDISCONNECTED
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - afa80763-76f5-49dd-bcd6-f8618d033b2e
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - afa80763-76f5-49dd-bcd6-f8618d033b2e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/NetworkManagementService( 1282): hardware tether stats:NetworkStats: elapsedRealtime=47490
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/NetworkManagementService( 1282): getNetworkStatsSummaryXt:NetworkStats: elapsedRealtime=47491
D/NetworkManagementService( 1282):   [0] iface=wlan0 uid=-1 set=ALL tag=0x0 rxBytes=66782 rxPackets=132 txBytes=15688 txPackets=126 operations=0
D/NetworkManagementService( 1282):   [1] iface=lo uid=-1 set=ALL tag=0x0 rxBytes=0 rxPackets=0 txBytes=0 txPackets=0 operations=0
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/ConnectivityManager.CallbackHandler( 3410): CM callback handler got msg 524292
D/NetworkManagementService( 1282): hardware tether stats:NetworkStats: elapsedRealtime=47492
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100]( 1282): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkManagementService( 1282): getNetworkStatsSummaryDev:NetworkStats: elapsedRealtime=47493
D/NetworkManagementService( 1282):   [0] iface=wlan0 uid=-1 set=ALL tag=0x0 rxBytes=67110 rxPackets=136 txBytes=17966 txPackets=128 operations=0
D/NetworkManagementService( 1282):   [1] iface=lo uid=-1 set=ALL tag=0x0 rxBytes=0 rxPackets=0 txBytes=0 txPackets=0 operations=0
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100]( 1282): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1282): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100]( 1282): Disconnected - quitting
D/ConnectivityService( 1282):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/GpsLocationProvider( 1282): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1282):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Tethering( 1282): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/ConnectivityService( 1282): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Tethering( 1282): MasterInitialState.processMessage what=3
D/Nat464Xlat( 1282): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
W/QCNEJ   ( 4183): |CORE| No family connected
D/CSLegacyTypeTracker( 1282): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,fe80::a239:f7ff:fe6f:c95d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60}  everValidated{true}  lastValidated{true}  created{true}  explicitlySelected{false} } list []  wasFirstNetwork :true
D/LocSvc_java( 1282): onReceive
,D/CSLegacyTypeTracker( 1282): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/LocSvc_java( 1282): got connectivity action
D/ConnectivityService( 1282): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/[LGE_DATA][PayPopUp_ko] ( 4225): intent received :android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1282): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java( 1282): broadcast - no network connections
D/FastDownloadService( 1282): [FastDN][FDS] received CONNECTIVITY_ACTION_IMMEDIATE for WIFI detailedState: DISCONNECTED
D/LocSvc_java( 1282): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/FastDownloadService( 1282): [FastDN][FDS] WIFI is disconnected
D/LocSvc_java( 1282): Sending msg: 4 arg1:0 arg2:1
V/NetworkPolicy( 1282): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1282): getAGpsConnectionInfo connType - 4
D/ConnectivityService( 1282): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/LocSvc_java( 1282): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/FastDownloadService( 1282): [FastDN][FDS] received CONNECTIVITY_ACTION for WIFI detailedState: DISCONNECTED
,D/LocSvc_java( 1282): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1282): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 0a200fd7-7bf9-441f-95a6-862fda1b7095
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 0a200fd7-7bf9-441f-95a6-862fda1b7095 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,V/NetworkPolicy( 1282): [LG_RESTRICTED] !!!isConnected  type  :1
,D/[LGE_DATA][PayPopUp_ko] ( 4225): intent received :android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering( 1282): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
W/QCNEJ   ( 4183): |CORE| No family connected
,D/LocSvc_java( 1282): onReceive
D/FastDownloadService( 1282): [FastDN][FDS] received CONNECTIVITY_ACTION_IMMEDIATE for WIFI detailedState: DISCONNECTED
D/LocSvc_java( 1282): got connectivity action
D/FastDownloadService( 1282): [FastDN][FDS] WIFI is disconnected
D/LocSvc_java( 1282): broadcast - no network connections
D/ConnectivityService( 1282): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/LocSvc_java( 1282): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/ConnectivityService( 1282): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/LocSvc_java( 1282): Sending msg: 4 arg1:0 arg2:1
D/Tethering( 1282): MasterInitialState.processMessage what=3
D/WIFI    ( 1282): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1282):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    ( 1282): evalRequest
D/WIFI    ( 1282):   done
D/WIFI_UT ( 1282): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI_UT ( 1282):   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI_UT ( 1282): evalRequest
D/WIFI_UT ( 1282):   done
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/NetworkManagementService( 1282): Removing idletimer
D/GpsLocationProvider( 1282): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/FastDownloadService( 1282): [FastDN][FDS] received CONNECTIVITY_ACTION for WIFI detailedState: DISCONNECTED
D/LocSvc_java( 1282): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1282): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1282): ignore wifi update if we are not in OPENING or CLOSING
,E/ConnectivityService( 1282): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/GpsLocationProvider( 1282): updateNetworkState unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1282): updateNetworkState unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/[SystemUI]NetworkController( 3410): onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - a564c8fd-212f-490f-9063-1f4ad32350ba
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - a564c8fd-212f-490f-9063-1f4ad32350ba / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,I/art     ( 1282): Explicit concurrent mark sweep GC freed 142613(7MB) AllocSpace objects, 3(5MB) LOS objects, 33% free, 57MB/85MB, paused 2.424ms total 142.242ms
,W/ContextImpl( 7382): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1804 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.lge.bluetoothsetting.DockEventReceiver.beginStartingService:138 com.lge.bluetoothsetting.DockEventReceiver.onReceive:119 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - e91d5fa6-391f-43de-bc3f-33cf15f8dcd5
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - e91d5fa6-391f-43de-bc3f-33cf15f8dcd5 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
V/GLSActivity( 5096): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - d48d39d3-d509-46a5-9b72-582b00769d42
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - d48d39d3-d509-46a5-9b72-582b00769d42 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/BluetoothPbap( 7382): Proxy object disconnected
D/PbapServerProfile( 7382): Bluetooth service disconnected
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,I/LIA_SmartSetting(4.50.6)_LogCore( 7443): LIA Log setTagPrefix - prefix : LIA_SmartSetting(4.50.6)_
V/LIA_SmartSetting(4.50.6)_ContextDetector( 7443): onReceive action android.bluetooth.adapter.action.STATE_CHANGED
D/LIA_SmartSetting(4.50.6)_BTContextDetector( 7443): onReceive state= 13
D/LIA_SmartSetting(4.50.6)_LGIFTTT( 7443): recipeSlug= arrive_home_bluetooth
D/LIA_SmartSetting(4.50.6)_LGIFTTT( 7443): RECIPE_URI= content://com.lge.iftttmanager.provider/recipe
D/LIA_SmartSetting(4.50.6)_LGIFTTT( 7443): selection= recipe_slug = "arrive_home_bluetooth"
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - ac2b7434-fc15-4c57-9bd3-20742fc15016
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - ac2b7434-fc15-4c57-9bd3-20742fc15016 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/DockEventReceiver( 7382): finishStartingService: stopping service
,D/LIA_SmartSetting(4.50.6)_LGIFTTT( 7443): status= 0
D/LIA_SmartSetting(4.50.6)_ContextDetector( 7443): onUpdate Bluetooth off
I/[SystemUI]QuickSettingsHandler( 3410): Got action android.net.conn.CONNECTIVITY_CHANGE at null
I/[SystemUI]NetworkController( 3410): onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - a3d8ad2a-dd4e-4665-a504-1b02b76494d7
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - a3d8ad2a-dd4e-4665-a504-1b02b76494d7 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_SmartSetting(4.50.6)_Recommender( 7443): onStatusChanged value= Bluetooth off
V/LIA_SmartSetting(4.50.6)_SenseLocation( 7443): getCurrentPlaceId 
D/LIA_SmartSetting(4.50.6)_Recommender( 7443): not entered home
V/LIA_SmartSetting(4.50.6)_DeviceLogger( 7443): DeviceLogger.log: DeviceSettingProfile [profileId=-1, timestamp=1457423888559, , settingStatus=Bluetooth off, deviceTypeOrdinal=1]
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - f2dae507-9697-4a0d-9686-edc6dc22b7c7
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - f2dae507-9697-4a0d-9686-edc6dc22b7c7 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - fb6ada1e-f37a-490f-aec1-261f400ed972
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - fb6ada1e-f37a-490f-aec1-261f400ed972 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LIA_SmartSetting(4.50.6)_LocationDBManagerDBAdapter( 7443): insert start
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 6247073c-0906-4b9c-a57b-6c37ec675bc4
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 6247073c-0906-4b9c-a57b-6c37ec675bc4 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,W/CursorWrapperInner( 7798): Cursor finalized without prior close()
,D/LIA_SmartSetting(4.50.6)_LocationDBManager( 7443): insertSettingInfo ID = 5475
,I/wpa_supplicant( 3275): p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
I/wpa_supplicant( 3275): monitor socket send errors count : 1
I/wpa_supplicant( 3275): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_4163-2\x00 that cannot receive messages
D/LGBluetoothProfileConnectionReceiver_LGSettingsAPK( 7382): onReceive(), ConnectedDeviceName : null , Num : 0
,I/wpa_supplicant( 3275): wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
E/NetlinkEvent(  463): NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
V/BluetoothOppReceiver( 4553): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
E/NetlinkEvent(  415): NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
W/wpa_supplicant( 3275): USIM:  scard_deinit function
D/BluetoothOppNotification( 4553): [BTUI] cancel opp incoming file confirm notification
I/NotificationManager( 4553): com.android.bluetooth: cancel(-1) by com.android.bluetooth
I/Netd    (  463): M: Get netlink event, ifname: wlan0 action: 4
D/Tethering( 1282): interfaceLinkStateChanged wlan0, true
D/Tethering( 1282): interfaceStatusChanged wlan0, true
D/BluetoothOppNotification( 4553): [BTUI] cancel opp active transfer file notification
I/NotificationManager( 4553): com.android.bluetooth: cancel(-1) by com.android.bluetooth
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 02c6aca9-debb-4e8a-9c17-f60b979d6767
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 02c6aca9-debb-4e8a-9c17-f60b979d6767 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
V/BluetoothSapReceiver( 4553): [BTUI] checkServiceStart
,I/[SystemUI]QuickSettingsHandler( 3410): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 3ee7652f-fb0f-427d-84a0-69fe4ccb027c
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 3ee7652f-fb0f-427d-84a0-69fe4ccb027c / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LGBluetoothAuthorization( 7382): [BTUI] cancel All Notification
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
I/NotificationManager( 7382): com.lge.bluetoothsetting: cancel(17301632) by com.lge.bluetoothsetting
,I/NotificationManager( 7382): com.lge.bluetoothsetting: cancel(-1000001) by com.lge.bluetoothsetting
,I/NotificationManager( 7382): com.lge.bluetoothsetting: cancel(-1000011) by com.lge.bluetoothsetting
I/NotificationManager( 7382): com.lge.bluetoothsetting: cancel(-1000021) by com.lge.bluetoothsetting
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 6487316c-3534-4364-8bf1-05cddb3e9b3c
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 6487316c-3534-4364-8bf1-05cddb3e9b3c / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,I/NotificationManager( 7382): com.lge.bluetoothsetting: cancel(-1000031) by com.lge.bluetoothsetting
D/DhcpStateMachine( 1282): StoppedState
D/DhcpStateMachine( 1282): StoppedState{ when=-188ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,I/NotificationManager( 7382): com.lge.bluetoothsetting: cancel(-1000041) by com.lge.bluetoothsetting
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/BluetoothPermissionRequest( 7382): onReceive
D/LGBluetoothAuthorization( 7382): [BTUI] cancel All Notification
I/NotificationManager( 7382): com.lge.bluetoothsetting: cancel(17301632) by com.lge.bluetoothsetting
,I/NotificationManager( 7382): com.lge.bluetoothsetting: cancel(-1000001) by com.lge.bluetoothsetting
I/NotificationManager( 7382): com.lge.bluetoothsetting: cancel(-1000011) by com.lge.bluetoothsetting
I/NotificationManager( 7382): com.lge.bluetoothsetting: cancel(-1000021) by com.lge.bluetoothsetting
I/NotificationManager( 7382): com.lge.bluetoothsetting: cancel(-1000031) by com.lge.bluetoothsetting
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - cbca895e-ca9e-4903-b67a-9cc2edd32dc9
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - cbca895e-ca9e-4903-b67a-9cc2edd32dc9 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_CTP_StepCounterDetected( 7154): currentStep : 0.0 - standardStep : 0.0 = storedStep: 0.0
I/NotificationManager( 7382): com.lge.bluetoothsetting: cancel(-1000041) by com.lge.bluetoothsetting
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LGBluetoothStateChangeReceiver( 7382): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 60d28021-dbf7-4656-90a2-0d6609ba3eb2
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 60d28021-dbf7-4656-90a2-0d6609ba3eb2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,V/GLSActivity( 5096): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,V/GLSActivity( 5096): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WearableService( 5096): callingUid 10006, callindPid: 5096
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - f2c1d123-fc55-47ae-99cf-67bf7ea8756b
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - f2c1d123-fc55-47ae-99cf-67bf7ea8756b / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/AndroidRuntime( 8249): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/AndroidRuntime( 8249): CheckJNI is OFF
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 2076ebb9-3f26-428b-8cbb-cc4910151db2
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 2076ebb9-3f26-428b-8cbb-cc4910151db2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/AuthorizationBluetoothService( 5096): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 6199e5e5-f3c3-4baa-b712-d6794259c10c
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 6199e5e5-f3c3-4baa-b712-d6794259c10c / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
E/GmsWearableNodeHelper( 5096): GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 455b0263-7ab8-4ef5-8010-52546ffafc19
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 455b0263-7ab8-4ef5-8010-52546ffafc19 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,W/InstanceID/Rpc( 8039): Found 10006
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 49900ceb-e9ee-43be-8fad-90889fb94f93
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 49900ceb-e9ee-43be-8fad-90889fb94f93 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 23c66c4d-0695-4b7e-b03d-edc360b1728f
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 23c66c4d-0695-4b7e-b03d-edc360b1728f / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 2d9751e6-c2ab-4e34-94d3-d8a758192626
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 2d9751e6-c2ab-4e34-94d3-d8a758192626 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 624ee395-c38a-465c-8646-f216591604eb
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 624ee395-c38a-465c-8646-f216591604eb / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 4465d555-2e2b-4e85-988e-22358accdbbf
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 4465d555-2e2b-4e85-988e-22358accdbbf / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - a4c1aa9e-3e0d-4ea4-81a2-42547e5a6757
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - a4c1aa9e-3e0d-4ea4-81a2-42547e5a6757 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 0fc460f0-d36e-4b0e-809a-e3ed8552e137
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 0fc460f0-d36e-4b0e-809a-e3ed8552e137 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - f0852760-a915-4c2a-a799-fcceac3f8a27
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - f0852760-a915-4c2a-a799-fcceac3f8a27 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 7d02cecd-1fa8-4c1b-9c16-2c5350b87c89
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 7d02cecd-1fa8-4c1b-9c16-2c5350b87c89 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 5bffde62-9582-4892-9615-f5301c750644
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 5bffde62-9582-4892-9615-f5301c750644 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,I/Netd    (  463): M: Get netlink event, ifname: wlan0 action: 4
,D/Tethering( 1282): interfaceLinkStateChanged wlan0, true
D/Tethering( 1282): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3275): wlan0: CTRL-EVENT-TERMINATING 
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 3d83a00d-ae09-4b26-9035-a2456720ebd0
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 3d83a00d-ae09-4b26-9035-a2456720ebd0 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
I/Netd    (  463): M: Get netlink event, ifname: wlan0 action: 5
,D/Tethering( 1282): interfaceLinkStateChanged wlan0, false
D/Tethering( 1282): interfaceStatusChanged wlan0, false
,D/Tethering( 1282): InitialState.processMessage what=4
D/WifiOffDelayIfNotUsed( 1282): stopMonitoring
D/Tethering( 1282): upstreamIface add type 0
D/Tethering( 1282): upstreamIface add type 1
D/Tethering( 1282): upstreamIface add type 4
D/Tethering( 1282): upstreamIface add type 5
D/Tethering( 1282): upstreamIface add type 7
D/Tethering( 1282): upstreamIface add type 9
D/Tethering( 1282): upstreamIface add type 18
D/Tethering( 1282): checkDunRequired: secureSetting is 2
W/Settings( 8159): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/Tethering( 1282): sendTetherStateChangedBroadcast 0, 0, 0
D/WfdsService( 4163): Supplicant Connection state is changed : false
D/WfdsService( 4163): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 4163): Set the WFDS Monitor: false
D/WfdsMonitor( 4163): WFDS Monitor is stopped
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - bbc3915f-633e-4881-8ede-c76197fdcf6f
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - bbc3915f-633e-4881-8ede-c76197fdcf6f / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 88114078-8626-4753-8e49-3233951f3c53
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 88114078-8626-4753-8e49-3233951f3c53 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
V/WfdStateTracker( 4163): WfdStateTracker handleDirectStateChangedEvent: 0
,I/[SystemUI]NetworkController( 3410): onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 (has extras) }
I/[SystemUI]QuickSettingsHandler( 3410): Got action android.net.wifi.WIFI_STATE_CHANGED at null
,D/NetworkManagementService( 1282): hardware tether stats:NetworkStats: elapsedRealtime=47757
,D/NetworkManagementService( 1282): getNetworkStatsSummaryXt:NetworkStats: elapsedRealtime=47759
D/NetworkManagementService( 1282):   [0] iface=wlan0 uid=-1 set=ALL tag=0x0 rxBytes=66782 rxPackets=132 txBytes=15688 txPackets=126 operations=0
D/NetworkManagementService( 1282):   [1] iface=lo uid=-1 set=ALL tag=0x0 rxBytes=0 rxPackets=0 txBytes=0 txPackets=0 operations=0
I/WifiServerServiceExt( 1282): WIFI_STATE_CHANGED_ACTION [1]
I/WifiServerServiceExt( 1282): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt( 1282): batteryPsActivateMsgHandler : this is not treated
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 15b7c3d1-441d-447b-85f9-0b2040507bbd
D/NetworkManagementService( 1282): hardware tether stats:NetworkStats: elapsedRealtime=47760
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 15b7c3d1-441d-447b-85f9-0b2040507bbd / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/NetworkManagementService( 1282): getNetworkStatsSummaryDev:NetworkStats: elapsedRealtime=47766
D/NetworkManagementService( 1282):   [0] iface=wlan0 uid=-1 set=ALL tag=0x0 rxBytes=67110 rxPackets=137 txBytes=17966 txPackets=128 operations=0
D/NetworkManagementService( 1282):   [1] iface=lo uid=-1 set=ALL tag=0x0 rxBytes=0 rxPackets=0 txBytes=0 txPackets=0 operations=0
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,I/Gmail   ( 8191): getAccountsCursor
,W/Settings( 5096): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 673ef126-a86d-4f55-9ab8-3640ec5e2909
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 673ef126-a86d-4f55-9ab8-3640ec5e2909 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
V/GLSActivity( 5096): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 352163c7-894c-4980-8d53-a08bbc2fea6d
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 352163c7-894c-4980-8d53-a08bbc2fea6d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 9f8adb48-f58e-4694-b159-a448f62c935e
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 9f8adb48-f58e-4694-b159-a448f62c935e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - fd0ec790-0cb0-4395-ba71-1358bc9e791a
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - fd0ec790-0cb0-4395-ba71-1358bc9e791a / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - a96fcf37-0e34-4a7d-8dd2-cc0824ddc518
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - a96fcf37-0e34-4a7d-8dd2-cc0824ddc518 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - f88f483a-1c88-4d7e-9a56-a5424effafe0
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - f88f483a-1c88-4d7e-9a56-a5424effafe0 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - aca1b635-c030-4b38-9b41-74b1f64a132c
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - aca1b635-c030-4b38-9b41-74b1f64a132c / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 079d68a3-2e0e-4f02-baaf-50e6ee98affe
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 079d68a3-2e0e-4f02-baaf-50e6ee98affe / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 38ae858b-d24c-4c00-8ffa-844f5572bbb7
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 38ae858b-d24c-4c00-8ffa-844f5572bbb7 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/GCM     ( 8039): COMPAT: Multi user ser=0 current=0
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 499b7c7d-8e72-4202-b859-afbf7ae6b83b
I/CheckinService( 8039): Checkin interval check for package: unspecified last checkin: 1457400913955 min interval config: 0 actual interval: 22974883
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 499b7c7d-8e72-4202-b859-afbf7ae6b83b / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/AndroidRuntime( 8249): Calling main entry com.android.commands.pm.Pm
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 5311871e-855e-4e4d-9877-1ad818717977
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 5311871e-855e-4e4d-9877-1ad818717977 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
,D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 6a45442b-b305-46ba-a303-c3e4b0025606
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 6a45442b-b305-46ba-a303-c3e4b0025606 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
I/CheckinService( 8039): Disabling old GoogleServicesFramework version
,I/ActivityManager( 1282): Force stopping com.example.hello appid=10361 user=-1: uninstall pkg
I/ActivityManager( 1282): Killing 7557:com.example.hello/u0a361 (adj 0): stop com.example.hello
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 1dce3de8-1551-469d-9001-bf5b8e0ea298
I/GCoreUlr( 8039): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 1dce3de8-1551-469d-9001-bf5b8e0ea298 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,W/PackageSettings( 1282): Skipping PackageSetting{5eb74d com.test.thalitest/10353} due to missing metadata
,D/ChimeraCfgMgr( 8039): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/BootCompletedReceiver( 8039): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,D/BootCompletedReceiver( 8039): Got an BootCompleted event.
V/CheckinService( 8039): No Subscriptions found on the device
W/InputDispatcher( 1282): channel '1ca3ed22 com.example.hello/com.example.hello.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher( 1282): channel '1ca3ed22 com.example.hello/com.example.hello.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher( 1282): Attempted to unregister already unregistered input channel '1ca3ed22 com.example.hello/com.example.hello.MainActivity (server)'
I/WindowState( 1282): WIN DEATH: Window{1ca3ed22 u0 com.example.hello/com.example.hello.MainActivity}
,D/InputDispatcher( 1282): Focus left window: Window{1ca3ed22 u0 com.example.hello/com.example.hello.MainActivity}
D/InputDispatcher( 1282): Window went away: Window{1ca3ed22 u0 com.example.hello/com.example.hello.MainActivity}
,W/ActivityManager( 1282): Force removing ActivityRecord{2cefe586 u0 com.example.hello/.MainActivity t53}: app died, no saved state
,D/SplitWindowPolicy( 4163): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 4163): topRunningActivity=ActivityInfo{249e72f1 co.....MainActivity}, taskId=53, activityType=0, bIsSplit=false
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
I/ActivityManager( 1282): Force stopping com.example.hello appid=10361 user=0: pkg removed
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 86d44507-007a-4f8a-92ea-1e3a59e07241
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 86d44507-007a-4f8a-92ea-1e3a59e07241 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,W/ActivityManager( 1282): Spurious death for ProcessRecord{3581cbb1 7557:com.example.hello/u0a361}, curProc for 7557: null
,I/[LGHome]EVENT( 4393): onStart
I/[LGHome]EVENT( 4393): onResume
D/SplitWindowPolicy( 4163): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/TaskPersister( 1282): removeObsoleteFile: deleting file=53_task.xml
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/SplitWindowPolicy( 4163): topRunningActivity=ActivityInfo{35e28ed6 co.....Launcher}, taskId=51, activityType=1, bIsSplit=false
,I/[LGHome]LGActivityUtil( 4393): [LGActivityUtil.java:204:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,D/AppInfoDao( 7487): topacitivyt exist app = com.lge.launcher2
,I/[LGHome]EVENT( 4393): onResume end
I/Activity( 4393): Activity.onPostResume() called 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - cfd51b72-d24d-4073-8000-6b100b6628d7
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - cfd51b72-d24d-4073-8000-6b100b6628d7 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
I/LGCover ( 5209): PackageIntentReceiver: PackageIntentReceiver Received Broadcast : android.intent.action.PACKAGE_REMOVED
D/LIA_Service_RemotePackageHandler( 4350): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.example.hello
,W/System.err( 4371): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
,W/System.err( 4371): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4371): 	at com.lge.mlt.watcher.LDBOnAppWatcher$2.onReceive(LDBOnAppWatcher.java:69)
W/System.err( 4371): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1038)
W/System.err( 4371): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4371): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4371): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4371): 	at android.app.ActivityThread.main(ActivityThread.java:5430)
W/System.err( 4371): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4371): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4371): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:913)
W/System.err( 4371): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:706)
,D/AppInfoDao( 7487): topacitivyt update app = com.lge.launcher2 time = 2016-03-08 08:58 date = 20160308
,W/ResourcesManager( 4225): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ActionManagerService( 4287): notifyUserLog: 1000004
I/InputReader( 1282): Reconfiguring input devices.  changes=0x00000010
,D/LGCover ( 5209): QuickCoverSettingsProvider: QuickCover getClass()
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LGCover ( 5209): QuickCoverSettingsProvider: QuickCover getClass() cursor.getString()com.lge.camera.app.QuickWindowCameraActivity
D/LGCover ( 5209): QuickCoverSettingsProvider: QuickCover getClass() cursor.getString()com.android.mms.quickcover.QuickCoverActivity
D/LGCover ( 5209): QuickCoverSettingsProvider: QuickCover getClass() cursor.getString()com.android.contacts.activities.QuickCircleActivity
D/LGCover ( 5209): QuickCoverSettingsProvider: QuickCover getClass() cursor.getString()com.lge.music.MusicQuickCircle
D/LGCover ( 5209): QuickCoverSettingsProvider: QuickCover getClass() cursor.getString()com.lge.lifetracker.QuickCover
D/LGCover ( 5209): QuickCoverSettingsProvider: QuickCover getClass() cursor.getString()com.lge.smartcover.quickcircle.apps.AppMarketCoverCloseActivity
D/LGCover ( 5209): QuickCoverSettingsProvider: QuickCover getClass() cursor.getString()com.lge.smartcover.quickcircle.apps.SettingCoverCloseActivity
D/BootCompletedReceiver( 8039): Will NOT schedule AdAttestation signal task because it's disabled.
I/ActivityManager( 1282): Waited long enough for: ServiceRecord{2a3c7ede u0 com.android.mms/.service.SwitchedService}
I/art     ( 4478): Explicit concurrent mark sweep GC freed 115259(5MB) AllocSpace objects, 17(2MB) LOS objects, 35% free, 29MB/45MB, paused 307us total 42.959ms
I/MirrorLink_UPnP( 4478): pkgReceiver : ACTION_PACKAGE_REMOVED:com.example.hello [TmAppListManager.java:380:onReceive()]
D/MirrorLink_UPnP( 4478): removeApp : com.example.hello [TmAppListManager.java:1503:removeApp()]
D/SystemUpdateService( 8039): onCreate
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - d2f43ea9-9b6e-402a-b7e4-34738fff4425
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - d2f43ea9-9b6e-402a-b7e4-34738fff4425 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LGCover ( 5209): QuickCoverSettingsUtil.java:215 isSupportsQuickCircle(): cover_type : 3
D/LGCover ( 5209): QuickCoverSettingsUtil.java:226 isSupportsYGCover(): cover_type : 3
,D/WallpaperManager( 4393): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,I/art     ( 3410): Explicit concurrent mark sweep GC freed 8771(393KB) AllocSpace objects, 157(21MB) LOS objects, 26% free, 87MB/119MB, paused 1.872ms total 48.108ms
D/KeyguardModel( 3410): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/SystemUI[Framework]( 1282): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
,D/InputDispatcher( 1282): Focus entered window: Window{3aac7212 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/PhoneWindowManagerEx( 1282): Call!!!getLGSystemUiVisibility. =0x0
I/SystemUI[Framework]( 1282): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2db55615,  pkg=Window{3aac7212 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/StatusBarManagerServiceEx( 1282): setLGSystemUiVisibility(0x0)
I/SystemUI[Framework]( 1282): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/StatusBarManagerServiceEx( 1282): manageNaviBtnDisableList userId=0 what=0x0 pkg=Window{3aac7212 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,E/NetlinkEvent(  415): NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,E/NetlinkEvent(  463): NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,D/LGCover ( 5209): PackageIntentReceiver: Quick cover app present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LGCover ( 5209): PackageIntentReceiver: Quick cover app present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LGCover ( 5209): PackageIntentReceiver: Quick cover app present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LGCover ( 5209): PackageIntentReceiver: Quick cover app present in DB = com.lge.music.MusicQuickCircle  true
D/LGCover ( 5209): PackageIntentReceiver: Quick cover app present in DB = com.lge.lifetracker.QuickCover  true
D/LGCover ( 5209): PackageIntentReceiver: Quick cover app present in DB = com.lge.smartcover.quickcircle.apps.AppMarketCoverCloseActivity  true
D/LGCover ( 5209): PackageIntentReceiver: Quick cover app present in DB = com.lge.smartcover.quickcircle.apps.SettingCoverCloseActivity  true
I/LGCover ( 5209): PackageIntentReceiver: PackageIntentReceiver Received Broadcast : android.intent.action.PACKAGE_FULLY_REMOVED
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 8f5d9005-0028-4e5a-9bc4-bcf5246595c7
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 8f5d9005-0028-4e5a-9bc4-bcf5246595c7 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
I/[SystemUI]QSlideListController( 3410): onReceive = android.intent.action.PACKAGE_REMOVED
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - a6616c8f-7af8-47c6-8542-dc938c53ade6
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - a6616c8f-7af8-47c6-8542-dc938c53ade6 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/SystemUpdateService( 8039): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/[LGHome]EVENT( 4393): [Launcher.java:5453:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/[LGHome]EVENT( 4393): [Launcher.java:5476:setEnableShakeHandlers()]enableShakeHandlers
,D/[Concierge][ConciergeWidgetLayout]( 4393): notifyExtViewAvailable
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,V/AuthZen ( 8039): Handling intent: android.intent.action.BOOT_COMPLETED
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - f734dcf0-0bd3-4085-80f6-c570a8cf5f4f
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - f734dcf0-0bd3-4085-80f6-c570a8cf5f4f / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,I/CheckinService( 8039): Checking schedule, now: 1457423889090 next: 1457969009926
I/CheckinService( 8039): active receiver: disabled
,W/ResourceType( 1282): ResTable_typeSpec entry count inconsistent: given 1, previously 483
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 8a6c9bf6-3881-4037-852f-1e97edf82b53
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 8a6c9bf6-3881-4037-852f-1e97edf82b53 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 3410): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 3410): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - e2453fdd-5eac-479f-8be3-58128e0015cd
D/administrator( 1282): Handling package changes for user 0
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - e2453fdd-5eac-479f-8be3-58128e0015cd / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,W/InputMethodManagerService( 1282): Got RemoteException sending setActive(false) notification to pid 7557 uid 10361
,I/Timeline( 4393): Timeline: Activity_idle id: android.os.BinderProxy@37ded9f2 time:48149
,V/SplitUIManager( 6226): split_name #14 / not available #0
,D/SplitUIService( 6226): removed split : 
,I/SystemUI[Framework]( 1282): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
,I/SystemUI[Framework]( 1282): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2db55615,  pkg=Window{3aac7212 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/PhoneWindowManagerEx( 1282): Call!!!getLGSystemUiVisibility. =0x0
I/SystemUI[Framework]( 1282): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/StatusBarManagerServiceEx( 1282): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1282): manageNaviBtnDisableList userId=0 what=0x0 pkg=Window{3aac7212 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
,I/ActivityManager( 1282): Start proc 8294:com.lge.provider.lockscreensettings/u0a84 for content provider com.lge.provider.lockscreensettings/.LockSettingsDBProvider
D/AuthZenEventHandler( 8039): Handling event: android.intent.action.BOOT_COMPLETED
I/ActivityManager( 1282): Displayed com.lge.launcher2/.Launcher: +194ms (total +8s464ms)
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 88e08cb5-78fc-41a3-96ba-2bd2c1874f9e
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 88e08cb5-78fc-41a3-96ba-2bd2c1874f9e / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 3dcf2c66-e774-4e19-b20a-1487126aa342
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 3dcf2c66-e774-4e19-b20a-1487126aa342 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,E/xt9input_alpha( 3730): alpha_data::getExactType() failed. status(0x4)
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 0834ce33-faa5-4134-9756-d447a844c844
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 0834ce33-faa5-4134-9756-d447a844c844 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
I/SystemUpdateService( 8039): cancelUpdate (empty URL)
,I/SystemUpdateService( 8039): active receiver: disabled
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - e3b05f88-02c5-42ea-a6f1-581a25258d91
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - e3b05f88-02c5-42ea-a6f1-581a25258d91 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,I/NotificationManager( 8039): com.google.android.gms: cancel(2130838165) by com.google.android.gms
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,I/NotificationManager( 8039): com.google.android.gms: cancel(2130838166) by com.google.android.gms
,D/JobSchedulerService( 1282): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService( 1282): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/PhoneStatusBar( 3410): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
W/ResourcesManager( 8294): Asset path '/system/framework/com.lge.locksettings.jar' does not exist or contains no resources.
D/PhoneStatusBar( 3410): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 3410): NavigationKey Color is changed(WHITE -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 3410):  BarMode=4, Theme=BLACK, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 3410): , Keyguard show=false, IME shown=false, Panel expanded=false
,I/art     ( 1282): Explicit concurrent mark sweep GC freed 49381(2MB) AllocSpace objects, 5(100KB) LOS objects, 33% free, 57MB/85MB, paused 2.707ms total 231.626ms
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - c1a49fb2-932e-42e7-b4ae-51ab222065a4
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - c1a49fb2-932e-42e7-b4ae-51ab222065a4 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 45017bdd-df72-4dcd-b9cb-38c4a2736d73
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 45017bdd-df72-4dcd-b9cb-38c4a2736d73 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/BarTransitions( 3410): draw background and invalidate : color = e2000000
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/BarTransitions( 3410): draw background and invalidate : color = e1000000
I/art     ( 8249): System.exit called, status: 0
I/AndroidRuntime( 8249): VM exiting with result code 0.
,W/BaseAppContext( 8039): Using Auth Proxy for data requests.
W/ResourcesManager( 1282): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/SplitUIManager( 6226): split_name #14 / not available #0
I/SplitUIService( 6226): split app #14
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - f3a7a560-d274-4fc8-b384-61dcfd24bcd2
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - f3a7a560-d274-4fc8-b384-61dcfd24bcd2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 614641c7-d9a9-446b-85c9-1155132a4154
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 614641c7-d9a9-446b-85c9-1155132a4154 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/KeyguardModel( 3410): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 3410): createShortcutInfo...
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - dfbd449a-d536-47d9-af79-d4512bc4fd3d
D/KeyguardModel( 3410): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 3410): createShortcutInfo...
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - dfbd449a-d536-47d9-af79-d4512bc4fd3d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 9fd10f62-84c7-4b8f-8ece-309b847103da
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 9fd10f62-84c7-4b8f-8ece-309b847103da / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
W/ResourcesManager( 3410): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/asset   ( 3410): Asset path /system/framework/com.lge.telephony.sms.jar is neither a directory nor file (type=1).
W/ResourcesManager( 3410): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 3410): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,W/ResourceType( 3410): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 3410): Failure retrieving resources for com.android.mms: Resource ID #0x0
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 66855880-858c-4418-8002-20f11ff1923b
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 66855880-858c-4418-8002-20f11ff1923b / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/KeyguardModel( 3410): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 3410): createShortcutInfo...
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 4dd65ea2-89d0-4435-b32b-fba24a41366d
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 4dd65ea2-89d0-4435-b32b-fba24a41366d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,W/ResourceType( 3410): No package identifier when getting value for resource number 0x00000000
W/ResourcesManager( 3410): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/PackageManager( 3410): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 33f82974-65df-4d07-94af-da014e3ea9d2
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 33f82974-65df-4d07-94af-da014e3ea9d2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 7039789e-ac11-496f-b020-ea718c68996c
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 7039789e-ac11-496f-b020-ea718c68996c / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/KeyguardModel( 3410): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 3410): createShortcutInfo...
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 64005afa-8973-4a58-bcfd-dbd0d671ddff
W/ResourcesManager( 3410): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 64005afa-8973-4a58-bcfd-dbd0d671ddff / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
W/ResourcesManager( 3410): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3410): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 3410): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,W/ResourceType( 3410): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 3410): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/KeyguardModel( 3410): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 3410): createShortcutInfo...
E/BaseAppContext( 8039): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
I/art     ( 4748): Explicit concurrent mark sweep GC freed 3155(124KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 28MB/60MB, paused 3.383ms total 31.555ms
,D/bt_vendor( 4553): op for 6
W/bt-l2cap( 4553): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 4553): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-btif ( 4553): ag scb idx 1 not allocated
W/bt-btif ( 4553): ag scb idx 2 not allocated
E/bt-btif ( 4553): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 4553): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 4553): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-btif ( 4553): ag scb idx 1 not allocated
W/bt-btif ( 4553): ag scb idx 2 not allocated
E/bt-btif ( 4553): BTA AG is already disabled, ignoring ...
E/bt-btif ( 4553): bta_gattc_deregister Deregister Failedm unknown client cif
E/bt-btif ( 4553): bta_gattc_deregister Deregister Failedm unknown client cif
W/bt_userial( 4553): select_read return size <=0:0, exiting userial_read_thread
,D/bt_vendor( 4553): op for 9
D/bt_hwcfg( 4553): hw_epilog_process
,D/bt_vendor( 4553): op for 4
I/bt_userial_vendor( 4553): device fd = 73 close
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 2ee02827-4995-46aa-b16d-5133ff9fde7b
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 2ee02827-4995-46aa-b16d-5133ff9fde7b / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/KeyguardModel( 3410): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 3410): createShortcutInfo...
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/KeyguardModel( 3410): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 3410): createShortcutInfo...
,W/ResourceType( 3410): No package identifier when getting value for resource number 0x00000000
D/bt_vendor( 4553): op for 0
W/PackageManager( 3410): Failure retrieving resources for com.android.mms: Resource ID #0x0
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - dbbdce1f-3167-463a-a610-b6e6df9f7fa6
D/bt_vendor( 4553): cleanup
E/NetlinkEvent(  463): NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
I/GKI_LINUX( 4553): GKI_destroy_task(0): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
E/NetlinkEvent(  415): NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
I/GKI_LINUX( 4553): gki_task task_id=0 [BTU] terminating
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - dbbdce1f-3167-463a-a610-b6e6df9f7fa6 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
I/GKI_LINUX( 4553): GKI_destroy_task(): task [BTU] terminated
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/KeyguardModel( 3410): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 3410): createShortcutInfo...
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
I/bt-btif ( 4553): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 4553): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/BluetoothAdapterService( 4553): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 4553): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService( 4553): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 4553): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 4553): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService(218329368)( 4553): setProfileServiceState() - Stopping service com.android.bluetooth.hfp.HeadsetService
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 2e178e37-4d35-47da-b071-cd73e4a0ee5a
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 2e178e37-4d35-47da-b071-cd73e4a0ee5a / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/KeyguardModel( 3410): handleShortcutListChanged...
,D/BluetoothAdapterService( 4553): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 4553): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService( 4553): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 4553): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
D/HeadsetService( 4553): Received stop request...Stopping profile...
W/BluetoothAdapterService( 4553): Not skipping com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService(218329368)( 4553): setProfileServiceState() - Stopping service com.android.bluetooth.a2dp.A2dpService
,I/LGBluetoothHfpAdapter( 4553): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 4553): Cleaning up Bluetooth Handsfree callback object
W/ResourceType( 3410): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 3410): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/BluetoothAdapterService( 4553): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 4553): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 4553): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 4553): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,D/HeadsetStateMachine( 4553): Exit Disconnected: -1
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/KeyguardModel( 3410): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 3410): createShortcutInfo...
,W/ResourceType( 3410): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 3410): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,D/KeyguardModel( 3410): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 3410): createShortcutInfo...
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 273f1900-cd5c-4949-8b09-9d55f9a02907
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 273f1900-cd5c-4949-8b09-9d55f9a02907 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,W/BluetoothAdapterService( 4553): Not skipping com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 4553): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d037118
D/BluetoothAdapterService(218329368)( 4553): setProfileServiceState() - Stopping service com.android.bluetooth.hid.HidService
D/A2dpService( 4553): Received stop request...Stopping profile...
D/A2dpStateMachine( 4553): Exit Disconnected: -1
D/BluetoothHeadset( 4225): Proxy object disconnected
D/BluetoothHeadset( 1282): Proxy object disconnected
D/BluetoothHeadset( 4225): Proxy object disconnected
,D/BluetoothAdapterService( 4553): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 4553): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 4553): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 4553): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/ActivityManager( 1282): Unable to start service Intent { act=com.lge.ime.intent.ANDROID_CONTACT_DB_UPDATED pkg=com.lge.ime } U=0: not found
D/BluetoothHeadset( 4225): Proxy object disconnected
,W/BluetoothAdapterService( 4553): Not skipping com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService(218329368)( 4553): setProfileServiceState() - Stopping service com.android.bluetooth.hdp.HealthService
,D/BluetoothHeadset( 7382): Proxy object disconnected
D/BluetoothAdapterService( 4553): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 4553): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BluetoothAdapterService( 4553): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 4553): getProfileSaveSetting: com.android.bluetooth.pan.PanService
D/LGBluetoothA2dpAdapter( 4553): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 4553): Cleaning up Bluetooth Handsfree callback object
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 1fe6f2a5-9027-48f0-9819-a369e0bc9a6c
D/LGBluetoothPowerControlManager( 4553): [BTUI] terminate
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 1fe6f2a5-9027-48f0-9819-a369e0bc9a6c / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/HeadsetProfile( 7382): Bluetooth service disconnected
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/BluetoothManagerService( 1282): Message: 31
,D/BluetoothAdapterService( 4553): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d037118
,D/BluetoothHeadset( 4722): Proxy object disconnected
D/BluetoothAdapterService(218329368)( 4553): handleMessage() - Message: 1
D/BluetoothAdapterService(218329368)( 4553): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(218329368)( 4553): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BluetoothAdapterState( 4553): isTurningOnRadio()=false
D/BluetoothAdapterState( 4553): isTurningOffRadio()=false
D/BluetoothAdapterState( 4553): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 4553): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 4553): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 4553): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/AudioService( 1282): onServiceDisconnected: Bluetooth profile: 1
D/BluetoothA2dp( 1282): Proxy object disconnected
D/AudioService( 1282): onServiceDisconnected: Bluetooth profile: 2
W/BluetoothAdapterService( 4553): Not skipping com.android.bluetooth.pan.PanService
D/BluetoothAdapterService( 4553): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(218329368)( 4553): setProfileServiceState() - Stopping service com.android.bluetooth.pan.PanService
D/BluetoothAdapterService(218329368)( 4553): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
,D/HeadsetStateMachine( 4553): Unbinding service...
D/BluetoothA2dp( 7382): Proxy object disconnected
D/A2dpProfile( 7382): Bluetooth service disconnected
D/BluetoothAdapterService( 4553): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 4553): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 4553): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 4553): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,D/BluetoothA2dp( 4722): Proxy object disconnected
,W/BluetoothAdapterService( 4553): Not skipping com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(218329368)( 4553): setProfileServiceState() - Stopping service com.android.bluetooth.gatt.GattService
D/HeadsetPhoneState( 4553): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 4553): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 4553): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 4553): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 4553): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 4553): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 4553): [BTUI] LGBluetoothHfpAdapter cleanup
D/BluetoothAdapterService( 4553): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 4553): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 4553): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 4553): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 4553): Not skipping com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService(218329368)( 4553): setProfileServiceState() - Stopping service com.android.bluetooth.map.BluetoothMapService
D/HidService( 4553): Received stop request...Stopping profile...
D/BluetoothAdapterService( 4553): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d037118
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - fe005924-4345-4bdc-a001-5cb541a6b7c2
D/BluetoothInputDevice( 7382): Proxy object disconnected
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - fe005924-4345-4bdc-a001-5cb541a6b7c2 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/BluetoothAdapterService( 4553): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 4553): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 4553): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 4553): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/HealthService( 4553): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 4553): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d037118
D/HidProfile( 7382): Bluetooth service disconnected
,I/[LGHome]EVENT( 4393): [LauncherModel.java:199:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
W/BluetoothAdapterService( 4553): Not skipping com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(218329368)( 4553): setProfileServiceState() - Stopping service com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService(218329368)( 4553): handleMessage() - Message: 1
D/BluetoothAdapterService(218329368)( 4553): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(218329368)( 4553): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BluetoothAdapterState( 4553): isTurningOnRadio()=false
D/BluetoothAdapterState( 4553): isTurningOffRadio()=false
D/BluetoothAdapterState( 4553): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 4553): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 4553): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 4553): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 4553): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(218329368)( 4553): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
,I/BluetoothA2dpServiceJni( 4553): cleanupNative
I/GKI_LINUX( 4553): GKI_destroy_task(2): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 4553): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 4553): GKI_destroy_task(): task [A2DP-MEDIA] terminated
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - b71b09a4-72cf-4bc3-99f1-52070af913ab
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - b71b09a4-72cf-4bc3-99f1-52070af913ab / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/PanService( 4553): Received stop request...Stopping profile...
D/BluetoothAdapterService( 4553): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d037118
D/BluetoothPan( 7382): BluetoothPAN Proxy object disconnected
D/PanProfile( 7382): Bluetooth service disconnected
D/BtGatt.DebugUtils( 4553): handleDebugAction() action=null
,D/BtGatt.GattService( 4553): Received stop request...Stopping profile...
D/BtGatt.GattService( 4553): stop()
D/BtGatt.AdvertiseManager( 4553): advertise clients cleared
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 5b23d196-dbd8-43cc-a052-03c21b8a213c
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 5b23d196-dbd8-43cc-a052-03c21b8a213c / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LGBluetoothGattAdapter( 4553): [BTUI] LGBluetoothGattAdapter cleanup
D/BluetoothAdapterService( 4553): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d037118
,D/BluetoothAdapterService( 4553): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 4553): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 4553): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 4553): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 4553): Not skipping com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(218329368)( 4553): setProfileServiceState() - Stopping service com.broadcom.bt.service.opp.OppService
,D/KeyguardModel( 3410): handleShortcutListChanged...
D/BluetoothAdapterService(218329368)( 4553): handleMessage() - Message: 1
D/BluetoothAdapterService(218329368)( 4553): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(218329368)( 4553): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BluetoothAdapterState( 4553): isTurningOnRadio()=false
D/BluetoothAdapterState( 4553): isTurningOffRadio()=false
D/BluetoothAdapterState( 4553): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 4553): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 4553): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 4553): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 4553): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(218329368)( 4553): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothHidServiceJni( 4553): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 4553): Cleaning up Bluetooth GID callback object
I/[LGHome]Launcher.Model( 4393): onPackageRemoved=com.example.hello for UserHandle{0}
D/BluetoothAdapterState( 4553): Stopping profile services that were post enabled
D/BluetoothMapService( 4553): Received stop request...Stopping profile...
D/BluetoothMapService( 4553): stop()
,D/BluetoothMapEmailAppObserver( 4553): deinitObservers()
D/BluetoothMapEmailAppObserver( 4553): removeReceiver()
,D/BluetoothAdapterService( 4553): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d037118
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/BluetoothAdapterService(218329368)( 4553): handleMessage() - Message: 1
D/BluetoothAdapterService(218329368)( 4553): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(218329368)( 4553): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BluetoothAdapterState( 4553): isTurningOnRadio()=false
D/BluetoothAdapterState( 4553): isTurningOffRadio()=false
D/BluetoothAdapterState( 4553): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 4553): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 4553): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 4553): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 4553): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(218329368)( 4553): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothHealthServiceJni( 4553): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 4553): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 4553): Cleaning up Bluetooth Health object
,D/SapService( 4553): Received stop request...Stopping profile...
D/SapService( 4553): Stopping Bluetooth SapService
D/LGBluetoothSapAdapter( 4553): [BTUI] LGBluetoothSapAdapter cleanup
D/LGBluetoothSapManager( 4553): [BTUI] terminateSapManager
,D/BluetoothAdapterService( 4553): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d037118
,D/LgeBluetoothSimManager( 4225): [BTUI] SAP_DISABLE_EVT
D/BluetoothMap( 7382): Proxy object disconnected
D/MapProfile( 7382): Bluetooth service disconnected
D/BluetoothAdapterService(218329368)( 4553): handleMessage() - Message: 1
D/BluetoothAdapterService(218329368)( 4553): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(218329368)( 4553): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BluetoothAdapterState( 4553): isTurningOnRadio()=false
D/BluetoothAdapterState( 4553): isTurningOffRadio()=false
D/BluetoothAdapterState( 4553): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 4553): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 4553): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 4553): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 4553): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(218329368)( 4553): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothPanServiceJni( 4553): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 4553): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterService(218329368)( 4553): handleMessage() - Message: 1
D/BluetoothAdapterService(218329368)( 4553): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(218329368)( 4553): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=true
D/BluetoothAdapterState( 4553): isTurningOnRadio()=false
D/BluetoothAdapterState( 4553): isTurningOffRadio()=false
D/BluetoothAdapterState( 4553): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 4553): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 4553): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 4553): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 4553): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(218329368)( 4553): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/**OppService( 4553): Received stop request...Stopping profile...
D/OppService( 4553): Stopping Bluetooth OppService
D/OppService( 4553): cleanup OPP Service
W/BluetoothOPPServiceJni( 4553): Cleaning up Bluetooth Opp Interface...
W/BluetoothOPPServiceJni( 4553): Cleaning up Bluetooth OPP callback object
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 92b8c69d-a760-47ae-9753-7094e1d0d6f7
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 92b8c69d-a760-47ae-9753-7094e1d0d6f7 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/OppService( 4553): remove callbacks and handler
D/LGBluetoothOppAdapter( 4553): [BTUI] LGBluetoothOppAdapter cleanup
D/OppService( 4553): cleanup done
D/BluetoothAdapterService( 4553): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d037118
,I/AuthZen ( 8039): Fetching signing key...
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,V/BluetoothMapService( 4553): Handler(): got msg=4
D/BluetoothMapService( 4553): MAP Service closeService in
D/LGBluetoothMapAdapter( 4553): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 4553): MAP Service closeService out
D/BluetoothAdapterService(218329368)( 4553): handleMessage() - Message: 1
D/BluetoothAdapterService(218329368)( 4553): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(218329368)( 4553): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BluetoothAdapterState( 4553): isTurningOnRadio()=false
D/BluetoothAdapterState( 4553): isTurningOffRadio()=false
D/BluetoothAdapterState( 4553): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 4553): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 4553): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 4553): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 4553): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(218329368)( 4553): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(218329368)( 4553): handleMessage() - Message: 1
D/BluetoothAdapterService(218329368)( 4553): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(218329368)( 4553): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
D/BluetoothAdapterState( 4553): isTurningOnRadio()=false
D/BluetoothAdapterState( 4553): isTurningOffRadio()=false
D/BluetoothAdapterState( 4553): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 4553): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 4553): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 4553): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 4553): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(218329368)( 4553): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothMapService( 4553): cleanup()
D/BluetoothMapService( 4553): MAP Service closeService in
D/LGBluetoothMapAdapter( 4553): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 4553): MAP Service closeService out
W/BluetoothSAPServiceJni( 4553): ## WARNING : cleanupNative(L223): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 4553): ## WARNING : cleanupNative(L229): Cleaning up Bluetooth SAP callback object##
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 280a6176-f06f-4e3f-b331-bf2f88440d70
D/BluetoothAdapterService(218329368)( 4553): handleMessage() - Message: 1
D/BluetoothAdapterService(218329368)( 4553): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(218329368)( 4553): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=10, doUpdate=true
D/BluetoothAdapterState( 4553): isTurningOnRadio()=false
D/BluetoothAdapterState( 4553): isTurningOffRadio()=false
D/BluetoothAdapterState( 4553): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 4553): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 4553): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BluetoothAdapterService(218329368)( 4553): onProfileServiceStateChange() - All profile services stopped...
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 280a6176-f06f-4e3f-b331-bf2f88440d70 / Intent { act=com.lge.ia.conciergescript.P,olling.Date (has extras) }
D/OppService( 4553): cleanup OPP Service
D/OppService( 4553): remove callbacks and handler
D/LGBluetoothOppAdapter( 4553): [BTUI] LGBluetoothOppAdapter cleanup
D/OppService( 4553): cleanup done
D/BluetoothAdapterState( 4553): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 4553): Setting state to 10
I/BluetoothAdapterState( 4553): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService(218329368)( 4553): updateAdapterState() - Broadcasting state to 1 receivers.
D/BluetoothManagerService( 1282): Message: 60
D/BluetoothManagerService( 1282): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1282): Broadcasting onBluetoothStateChange(false) to 13 receivers.
D/BluetoothMap( 7382): onBluetoothStateChange: up=false
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LGBluetoothDeviceModeControllManager( 4553): LGAdapterState - setDeviceMode : 0
D/LGBluetoothDeviceModeControllManager( 4553): LGAdapterState - setDeviceMode : 0
I/BluetoothAdapterState( 4553): Entering OffState
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 18211945-076a-4e8f-8798-5163c3fa5765
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 18211945-076a-4e8f-8798-5163c3fa5765 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/BluetoothHeadset( 4225): onBluetoothStateChange: up=false
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/BluetoothHeadset( 1282): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1282): onBluetoothStateChange: up=false
D/BluetoothHeadset( 4225): onBluetoothStateChange: up=false
D/BluetoothA2dp( 4722): onBluetoothStateChange: up=false
D/BluetoothHeadset( 4225): onBluetoothStateChange: up=false
D/BluetoothHeadset( 4722): onBluetoothStateChange: up=false
,D/BluetoothPan( 7382): onBluetoothStateChange on: false
,D/BluetoothHeadset( 7382): onBluetoothStateChange: up=false
D/BluetoothPbap( 7382): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 7382): onBluetoothStateChange: up=false
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 3dee9de4-a979-4d6a-9995-bd703a559487
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 3dee9de4-a979-4d6a-9995-bd703a559487 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/BluetoothA2dp( 7382): onBluetoothStateChange: up=false
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/BluetoothAdapterService(218329368)( 4553): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@176790cf
,D/BluetoothManagerService( 1282): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1282): Broadcasting onBluetoothServiceDown() to 10 receivers.
,I/art     ( 8039): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 39bf9284-3761-470f-8555-0c010de8a638
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 39bf9284-3761-470f-8555-0c010de8a638 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/BluetoothManagerService( 1282): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService( 1282): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService( 1282): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2255974 mBinding = false
,D/BluetoothManagerService( 1282): Sending unbind request.
,I/art     ( 8039): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/BluetoothManagerService( 1282): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapterService(218329368)( 4553): onUnbind() - calling cleanup
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - bf794050-11b5-42d3-8058-e468c1867048
D/LGBluetoothAPIService( 4163): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/BleQmManagerService( 4163): [BleQmManagerService]  onReceive:  android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 4163): Message: 2
D/LGBluetoothAPIService( 4163): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@8803557 mBinding = false
D/LGBluetoothAPIService( 4163): Sending unbind request.
D/BluetoothAdapterService(218329368)( 4553): cleanup()
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - bf794050-11b5-42d3-8058-e468c1867048 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
E/LGBluetoothEventManager( 7382): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/BluetoothAdapter( 3410): 28134830: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3410): 28134830: getState() :  mService = null. Returning STATE_OFF
D/LGBluetoothEventManager( 7382): [BTUI] clear device connection state
D/SystemUpdateService( 8039): onDestroy
,I/[SystemUI]QuickSettingsHandler( 3410): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 3410): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
D/BluetoothAdapter( 5096): 847028910: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 5096): 847028910: getState() :  mService = null. Returning STATE_OFF
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,I/AuthZen ( 8039): Signing key fetched successfully!
,D/BluetoothAdapterService(218329368)( 4553): cleanup() - Cleaning up adapter native
I/bt-btif ( 4553): btif_shutdown_bluetooth()::btif_core_cb: state: 0, is_radio_req: 0, radio_ref_count: 0, dut_mode: 0, shutdown_pending: 0
I/GKI_LINUX( 4553): GKI_destroy_task(1): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/bt-btif ( 4553): HAL bt_hal_cbacks->thread_evt_cb
,I/GKI_LINUX( 4553): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 4553): GKI_destroy_task(): task [BTIF] terminated
I/GKI_LINUX( 4553): GKI_destroy_task(2): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 4553): GKI_destroy_task(1): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 4553): GKI_destroy_task(0): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 4553): GKI_exit_task 2 done
I/GKI_LINUX( 4553): GKI_exit_task 1 done
I/GKI_LINUX( 4553): GKI_exit_task 0 done
I/BluetoothServiceJni( 4553): cleanupNative: return from cleanup
W/LGBluetoothServiceJni( 4553): Cleaning up Bluetooth Service callback object
,D/LGBluetoothSettingsDBObserver( 4553): [BTUI] unregister observer for LG device name DB
,D/BluetoothAdapterService(218329368)( 4553): cleanup() - Bluetooth process exited normally.
D/BluetoothAdapterService(218329368)( 4553): cleanup() done
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - d9264cbe-86b3-463e-bdcd-fe2418ba62a3
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - d9264cbe-86b3-463e-bdcd-fe2418ba62a3 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,I/art     ( 4553): System.exit called, status: 0
I/AndroidRuntime( 4553): VM exiting with result code 0, cleanup skipped.
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 1ec4f568-fe8f-4a31-844c-08adfb7ae53b
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 1ec4f568-fe8f-4a31-844c-08adfb7ae53b / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 35bf9ac4-c6cc-4f5d-873a-1da8e1122770
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 35bf9ac4-c6cc-4f5d-873a-1da8e1122770 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
I/Timeline( 1282): Timeline: Activity_windows_visible id: ActivityRecord{284f8278 u0 com.lge.launcher2/.Launcher t51} time:48466
E/SharedPreferencesImpl( 8039): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/sizeCache.xml to backup file /data/data/com.google.android.gms/shared_prefs/sizeCache.xml.bak
W/BaseAppContext( 8039): Using Auth Proxy for data requests.
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 6879bbfb-e581-4afc-9dd2-cfaeb66c46f4
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 6879bbfb-e581-4afc-9dd2-cfaeb66c46f4 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - cbfc1c04-b902-4d63-b1c5-ea767808d511
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - cbfc1c04-b902-4d63-b1c5-ea767808d511 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 7016f303-84a0-41d6-a307-d2d56acd51e0
,E/SQLiteDatabase( 8039): Failed to open database '/data/data/com.google.android.gms/databases/keys.db'.
E/SQLiteDatabase( 8039): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8039): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8039): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/SQLiteDatabase( 8039): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/SQLiteDatabase( 8039): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/SQLiteDatabase( 8039): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/SQLiteDatabase( 8039): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8039): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/SQLiteDatabase( 8039): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/SQLiteDatabase( 8039): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/SQLiteDatabase( 8039): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1260)
E/SQLiteDatabase( 8039): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8039): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8039): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8039): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 8039): 	at com.google.android.gms.auth.authzen.keyservice.j.c(SourceFile:228)
E/SQLiteDatabase( 8039): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:186)
E/SQLiteDatabase( 8039): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/SQLiteDatabase( 8039): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/SQLiteDatabase( 8039): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:258)
E/SQLiteDatabase( 8039): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:209)
E/SQLiteDatabase( 8039): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:202)
E/SQLiteDatabase( 8039): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:148)
E/SQLiteDatabase( 8039): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/SQLiteDatabase( 8039): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 8039): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8039): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 8039): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 7016f303-84a0-41d6-a307-d2d56acd51e0 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
E/SQLiteOpenHelper( 8039): Couldn't open keys.db for writing (will try read-only):
E/SQLiteOpenHelper( 8039): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 8039): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 8039): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/SQLiteOpenHelper( 8039): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/SQLiteOpenHelper( 8039): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/SQLiteOpenHelper( 8039): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/SQLiteOpenHelper( 8039): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 8039): 	at android.database.sqlite.SQLiteDatabase.openInner(S,QLiteDatabase.java:916)
E/SQLiteOpenHelper( 8039): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/SQLiteOpenHelper( 8039): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/SQLiteOpenHelper( 8039): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1260)
E/SQLiteOpenHelper( 8039): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 8039): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 8039): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 8039): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 8039): 	at com.google.android.gms.auth.authzen.keyservice.j.c(SourceFile:228)
E/SQLiteOpenHelper( 8039): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:186)
E/SQLiteOpenHelper( 8039): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/SQLiteOpenHelper( 8039): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/SQLiteOpenHelper( 8039): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:258)
E/SQLiteOpenHelper( 8039): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:209)
E/SQLiteOpenHelper( 8039): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:202)
E/SQLiteOpenHelper( 8039): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:148)
E/SQLiteOpenHelper( 8039): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/SQLiteOpenHelper( 8039): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 8039): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 8039): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 8039): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,E/NetlinkEvent(  463): NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
W/SQLiteOpenHelper( 8039): Opened keys.db in read-only mode
,E/NetlinkEvent(  463): NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 687dc7e0-726d-4e28-9b3b-d1dc19973944
E/NetlinkEvent(  415): NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 687dc7e0-726d-4e28-9b3b-d1dc19973944 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
E/NetlinkEvent(  415): NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
D/KeyguardUpdateMonitor( 3410): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 4163): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 3410): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 3410): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 3410): On Skip Timer : true
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/KeyguardUpdateMonitor( 3410): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 4163): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 3410): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 3410): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 3410): On Skip Timer : true
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 793b5435-ea5a-4a9b-9a45-d47ebd938d75
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 793b5435-ea5a-4a9b-9a45-d47ebd938d75 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,E/SQLiteDatabase( 8039): Failed to open database '/data/data/com.google.android.gms/databases/auth.proximity.permit_store'.
E/SQLiteDatabase( 8039): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8039): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8039): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/SQLiteDatabase( 8039): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/SQLiteDatabase( 8039): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/SQLiteDatabase( 8039): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/SQLiteDatabase( 8039): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8039): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/SQLiteDatabase( 8039): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/SQLiteDatabase( 8039): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/SQLiteDatabase( 8039): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1260)
E/SQLiteDatabase( 8039): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8039): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8039): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 8039): 	at com.google.android.gms.auth.be.proximity.b.a.a(SourceFile:43)
E/SQLiteDatabase( 8039): 	at com.google.android.gms.auth.be.proximity.b.c.b(SourceFile:148)
E/SQLiteDatabase( 8039): 	at com.google.android.gms.auth.be.proximity.f.a(SourceFile:32)
E/SQLiteDatabase( 8039): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:261)
E/SQLiteDatabase( 8039): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:209)
E/SQLiteDatabase( 8039): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:202)
E/SQLiteDatabase( 8039): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:148)
E/SQLiteDatabase( 8039): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/SQLiteDatabase( 8039): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 8039): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8039): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 8039): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 683a437d-8eab-40ea-9f65-66479ca4c210
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 683a437d-8eab-40ea-9f65-66479ca4c210 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - e7262b6f-c9ce-4f9a-9ccb-c06d78952a2c
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - e7262b6f-c9ce-4f9a-9ccb-c06d78952a2c / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,E/AuthZen ( 8039): Error
E/AuthZen ( 8039): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AuthZen ( 8039): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AuthZen ( 8039): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/AuthZen ( 8039): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/AuthZen ( 8039): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/AuthZen ( 8039): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/AuthZen ( 8039): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AuthZen ( 8039): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/AuthZen ( 8039): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/AuthZen ( 8039): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/AuthZen ( 8039): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1260)
E/AuthZen ( 8039): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AuthZen ( 8039): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AuthZen ( 8039): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AuthZen ( 8039): 	at com.google.android.gms.auth.be.proximity.b.a.a(SourceFile:43)
E/AuthZen ( 8039): 	at com.google.android.gms.auth.be.proximity.b.c.b(SourceFile:148)
E/AuthZen ( 8039): 	at com.google.android.gms.auth.be.proximity.f.a(SourceFile:32)
E/AuthZen ( 8039): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:261)
E/AuthZen ( 8039): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:209)
E/AuthZen ( 8039): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:202)
E/AuthZen ( 8039): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:148)
E/AuthZen ( 8039): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 8039): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 8039): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 8039): 	at android.os.Looper.loop(Looper.java:135)
E/AuthZen ( 8039): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 321f23d9-d8a0-4a8e-8fcb-c9879dab813a
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 321f23d9-d8a0-4a8e-8fcb-c9879dab813a / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - ea73a07f-1fcf-419e-900a-35f7dd6540d4
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - ea73a07f-1fcf-419e-900a-35f7dd6540d4 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 7ba6a590-9860-43f6-989f-5118b26940ee
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 7ba6a590-9860-43f6-989f-5118b26940ee / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 27b15818-2aa2-4703-905d-9ac068881322
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 27b15818-2aa2-4703-905d-9ac068881322 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 921e4d5d-b49e-4189-affc-1a2b3a1f3567
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 921e4d5d-b49e-4189-affc-1a2b3a1f3567 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,I/qdhwcomposer(  416): handle_blank_event: dpy:1 panel power state: 0
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 43776899-9dae-4448-abf7-7d0704c1ed64
E/qdoverlay(  416): validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
E/qdoverlay(  416): Bad ov dump:  mdp_overlay z=0 alpha=255 mask=-1 flags=0x0 id=32
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 43776899-9dae-4448-abf7-7d0704c1ed64 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
E/qdoverlay(  416): src msmfb_img w=2944 h=2560 format=5 MDP_RGB_888
E/qdoverlay(  416): src_rect mdp_rect x=720 y=0 w=1440 h=2560
E/qdoverlay(  416): dst_rect mdp_rect x=0 y=0 w=1440 h=2560
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,E/qdoverlay(  416): validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
E/qdoverlay(  416): Bad ov dump:  mdp_overlay z=0 alpha=255 mask=-1 flags=0x0 id=32
E/qdoverlay(  416): src msmfb_img w=2944 h=2560 format=5 MDP_RGB_888
E/qdoverlay(  416): src_rect mdp_rect x=720 y=100 w=1440 h=2292
E/qdoverlay(  416): dst_rect mdp_rect x=0 y=100 w=1440 h=2292
E/qdoverlay(  416): validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
E/qdoverlay(  416): Bad ov dump:  mdp_overlay z=0 alpha=255 mask=-1 flags=0x220000 id=32
E/qdoverlay(  416): src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
E/qdoverlay(  416): src_rect mdp_rect x=0 y=0 w=1440 h=2560
E/qdoverlay(  416): dst_rect mdp_rect x=0 y=0 w=1440 h=2560
E/qdoverlay(  416): validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
E/qdoverlay(  416): Bad ov dump:  mdp_overlay z=2 alpha=255 mask=-1 flags=0x220000 id=32
E/qdoverlay(  416): src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
E/qdoverlay(  416): src_rect mdp_rect x=0 y=0 w=1440 h=2560
E/qdoverlay(  416): dst_rect mdp_rect x=0 y=0 w=1440 h=2560
E/qdoverlay(  416): validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
E/qdoverlay(  416): Bad ov dump:  mdp_overlay z=1 alpha=255 mask=-1 flags=0x220000 id=32
E/qdoverlay(  416): src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
E/qdoverlay(  416): src_rect mdp_rect x=0 y=0 w=1440 h=2560
E/qdoverlay(  416): dst_rect mdp_rect x=0 y=0 w=1440 h=2560
E/qdoverlay(  416): validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
E/qdoverlay(  416): Bad ov dump:  mdp_overlay z=0 alpha=255 mask=-1 flags=0x220000 id=32
E/qdoverlay(  416): src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
E/qdoverlay(  416): src_rect mdp_rect x=0 y=0 w=1440 h=2560
E/qdoverlay(  416): dst_rect mdp_rect x=0 y=0 w=1440 h=2560
E/qdoverlay(  416): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Cannot send after transport endpoint shutdown
E/qdoverlay(  416): MdpCtrl close error in unset
,V/AudioFlinger(  468): 4553 died, releasing its sessions,
W/ActivityManager( 1282): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
V/AudioFlinger(  468):  pid 4225 @ 0
W/ActivityManager( 1282): Scheduling restart of crashed service com.android.bluetooth/com.broadcom.fm.fmreceiver.FmService in 11000ms
V/AudioFlinger(  468):  pid 4650 @ 1
D/FMFRW_FmProxy( 4163): Fm Proxy object disconnected
D/LGBluetoothUserBindClient( 7382): [BTUI] onServiceDisconnected
,W/ContextImpl( 7382): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1804 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.lge.bluetoothsetting.DockEventReceiver.beginStartingService:138 com.lge.bluetoothsetting.DockEventReceiver.onReceive:119 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - e6c430d1-5ebb-421f-8fea-f1bbad86c21b
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - e6c430d1-5ebb-421f-8fea-f1bbad86c21b / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/DockEventReceiver( 7382): finishStartingService: stopping service
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
I/LIA_SmartSetting(4.50.6)_LogCore( 7443): LIA Log setTagPrefix - prefix : LIA_SmartSetting(4.50.6)_
V/LIA_SmartSetting(4.50.6)_ContextDetector( 7443): onReceive action android.bluetooth.adapter.action.STATE_CHANGED
D/LIA_SmartSetting(4.50.6)_BTContextDetector( 7443): onReceive state= 10
D/LIA_SmartSetting(4.50.6)_LGIFTTT( 7443): recipeSlug= arrive_home_bluetooth
D/LIA_SmartSetting(4.50.6)_LGIFTTT( 7443): RECIPE_URI= content://com.lge.iftttmanager.provider/recipe
D/LIA_SmartSetting(4.50.6)_LGIFTTT( 7443): selection= recipe_slug = "arrive_home_bluetooth"
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - f3683dcb-92e8-4d74-af2c-2ccf61f5c790
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - f3683dcb-92e8-4d74-af2c-2ccf61f5c790 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 614b9e62-fee3-4dd0-808b-3e73c3d369fa
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 614b9e62-fee3-4dd0-808b-3e73c3d369fa / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 7fde553f-6947-4311-bfcc-e267ae7bf4fb
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 7fde553f-6947-4311-bfcc-e267ae7bf4fb / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 95f63e9f-cb7c-4cc2-8ba0-79afbe56e346
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 95f63e9f-cb7c-4cc2-8ba0-79afbe56e346 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 1d964a43-a344-465b-97f4-8c055e23a634
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 1d964a43-a344-465b-97f4-8c055e23a634 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - e9a0e8d8-19df-4473-9d4a-f96276843909
I/art     ( 8039): Explicit concurrent mark sweep GC freed 55293(3MB) AllocSpace objects, 27(540KB) LOS objects, 31% free, 34MB/50MB, paused 906us total 93.074ms
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - e9a0e8d8-19df-4473-9d4a-f96276843909 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - f7656190-e63e-4baf-b412-1adf5e717638
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - f7656190-e63e-4baf-b412-1adf5e717638 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - f2e5a6be-21b0-4c83-8c95-9f4527acf1f3
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - f2e5a6be-21b0-4c83-8c95-9f4527acf1f3 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 0fd34556-443c-4b2c-9c95-330844dadf40
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 0fd34556-443c-4b2c-9c95-330844dadf40 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - bbbb3b10-6d85-4f1c-801f-78d16e766f7d
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - bbbb3b10-6d85-4f1c-801f-78d16e766f7d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - f98da9d0-8a69-4b27-b656-7fbac46acb8b
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - f98da9d0-8a69-4b27-b656-7fbac46acb8b / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,I/art     ( 5096): Explicit concurrent mark sweep GC freed 24820(1541KB) AllocSpace objects, 10(200KB) LOS objects, 47% free, 35MB/67MB, paused 1.308ms total 89.670ms
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 2da5d858-0dde-43ba-8dc0-867f839e37a5
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 2da5d858-0dde-43ba-8dc0-867f839e37a5 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 3fed1e3a-be86-4454-a871-5169aee39571
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 3fed1e3a-be86-4454-a871-5169aee39571 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
D/LCardEmulationManager( 4266): setRequireHCEConfirmvalue : true
D/LCardEmulationManager( 4266): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 4266): getDefaultRoute
D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - f8f9e2e2-cb1f-41e4-a260-2eaf65862693
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - f8f9e2e2-cb1f-41e4-a260-2eaf65862693 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - c8b48e5b-120a-4223-b361-7ac6fbca4dfc
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - c8b48e5b-120a-4223-b361-7ac6fbca4dfc / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 1d4ff91e-c205-460e-80a6-c62965515bab
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 1d4ff91e-c205-460e-80a6-c62965515bab / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - dfee499a-a254-405b-83ba-8c16505d0974
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - dfee499a-a254-405b-83ba-8c16505d0974 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 67a8b6c4-9bfa-45c8-943e-84e5d6007e9a
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 67a8b6c4-9bfa-45c8-943e-84e5d6007e9a / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - a70fe673-0ff5-4067-a5e6-16a2a199beaa
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - a70fe673-0ff5-4067-a5e6-16a2a199beaa / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 7b96fdec-8ca9-4d84-add8-3726425d49b9
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 7b96fdec-8ca9-4d84-add8-3726425d49b9 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 1d2b8664-8bf3-4d55-b08c-df2c8249f28f
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 1d2b8664-8bf3-4d55-b08c-df2c8249f28f / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 6634b432-8b5b-48d2-b89d-55763c7abfcb
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 6634b432-8b5b-48d2-b89d-55763c7abfcb / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - e689dfc0-304b-458c-8831-01ef971a6383
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - e689dfc0-304b-458c-8831-01ef971a6383 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 9c8f0505-f42c-4b17-b94c-b7cc25410f2d
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 9c8f0505-f42c-4b17-b94c-b7cc25410f2d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
,D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 94af0833-a7c4-4c55-b812-ddd81d19287d
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 94af0833-a7c4-4c55-b812-ddd81d19287d / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 5195d9be-d72c-4bf3-8156-6f794ae92962
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 5195d9be-d72c-4bf3-8156-6f794ae92962 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - d1115d65-5e01-445e-af71-e8e5cdbfc4ce
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - d1115d65-5e01-445e-af71-e8e5cdbfc4ce / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - b10b827c-27d7-4fad-9db2-35396c0f2ee6
,I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - b10b827c-27d7-4fad-9db2-35396c0f2ee6 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - 3222ae3c-d401-49c3-a625-22aa1f828a48
,I/qdhwcomposer(  416): handle_blank_event: dpy:0 panel power state: 0
I/LIA_Informant_RecoverableAlarmManager( 7154): getPendingIntent() : key - 3222ae3c-d401-49c3-a625-22aa1f828a48 / Intent { act=com.lge.ia.conciergescript.Polling.Date (has extras) }
E/qdoverlay(  416): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Cannot send after transport endpoint shutdown
,E/qdoverlay(  416): MdpCtrl close error in unset
E/qdoverlay(  416): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Cannot send after transport endpoint shutdown
E/qdoverlay(  416): MdpCtrl close error in unset
E/qdoverlay(  416): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Cannot send after transport endpoint shutdown
E/qdoverlay(  416): MdpCtrl close error in unset
,D/LIA_Informant_RecoverableAlarmManager( 7154): re setRepeating Alarm
,D/LIA_Informant_RecoverableAlarmManager( 7154): setRepeating 
,D/LIA_Informant_RecoverableAlarmManager( 7154): restoreAllAlarm() : sharedPreferences key - eef47b08-77b1-4037-9567-9d9916d00bfb
```
