#### Test 55634150e857e16_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/bte_conf( 2202): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 2202): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 2202): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 2202): get_profile_interface socket
I/bluedroid( 2202): get_profile_interface map_client
D/SyncManager(  761): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 26912, reason: UserStart, SyncResult: databaseError: true stats []
D/BluetoothManagerService(  761): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  761): Message: 40
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/SyncManager(  761): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 65689, reason: UserStart
I/bluedroid( 2202): config_hci_snoop_log
D/BluetoothManagerService(  761): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  761): Broadcasting onBluetoothServiceUp() to 7 receivers.
I/GKI_LINUX( 2202): gki_task_entry task_id=1 [BTIF] starting
D/BluetoothAdapterProperties( 2202): Address is:34:FC:EF:11:AE:67
D/BluetoothManagerService(  761): Bluetooth Adapter name changed to Nexus 5
D/BluetoothAdapterProperties( 2202): Name is: Nexus 5
D/BluetoothManagerService(  761): Stored Bluetooth name: Nexus 5
D/BluetoothAdapterState( 2202): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 2202): Setting state to 11
I/BluetoothAdapterState( 2202): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  761): Message: 60
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  761): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 2202): make
I/BluetoothBondStateMachine( 2202): StableState(): Entering Off State
D/BluetoothHeadset(  761): Proxy object connected
D/BluetoothHeadset( 1163): Proxy object connected
D/BluetoothHeadset( 1163): Proxy object connected
D/HeadsetService( 2202): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 2202): classInitNative: succeeds
I/BluetoothAdapterState( 2202): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/HeadsetStateMachine( 2202): make
D/HeadsetStateMachine( 2202): max_hf_connections = 1
I/bluedroid( 2202): get_profile_interface handsfree
D/HeadsetStateMachine( 2202): Enter Disconnected: -2, size: 0
D/BluetoothAdapterService( 2202): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a52278d
D/BluetoothA2dp(  761): Proxy object connected
D/A2dpService( 2202): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 2202): classInitNative: succeeds
I/bluedroid( 2202): get_profile_interface avrcp
E/RemoteController( 2202): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 2202): classInitNative: succeeds
D/A2dpStateMachine( 2202): make
I/bluedroid( 2202): get_profile_interface a2dp
I/GKI_LINUX( 2202): gki_task_entry task_id=2 [A2DP-MEDIA] starting
D/BluetoothAdapterService( 2202): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a52278d
I/BluetoothHidServiceJni( 2202): classInitNative: succeeds
D/A2dpStateMachine( 2202): Enter Disconnected: -2
D/BluetoothInputDevice( 1321): Proxy object connected
D/HidService( 2202): Received start request. Starting profile...
I/bluedroid( 2202): get_profile_interface hidhost
D/BluetoothAdapterService( 2202): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a52278d
D/HidProfile( 1321): Bluetooth service connected
I/BluetoothHealthServiceJni( 2202): classInitNative: succeeds
D/HealthService( 2202): Received start request. Starting profile...
I/bluedroid( 2202): get_profile_interface health
D/BluetoothAdapterService( 2202): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a52278d
I/BluetoothPanServiceJni( 2202): classInitNative(L105): succeeds
D/BluetoothPan( 1321): BluetoothPAN Proxy object connected
D/PanService( 2202): Received start request. Starting profile...
D/BluetoothPanServiceJni( 2202): initializeNative(L110): pan
I/bluedroid( 2202): get_profile_interface pan
D/PanProfile( 1321): Bluetooth service connected
D/BluetoothAdapterService( 2202): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a52278d
I/BtGatt.JNI( 2202): classInitNative(L863): classInitNative: Success!
D/BtGatt.DebugUtils( 2202): handleDebugAction() action=null
D/BtGatt.GattService( 2202): Received start request. Starting profile...
D/BtGatt.GattService( 2202): start()
I/bluedroid( 2202): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 2202): advertise manager created
D/BluetoothAdapterService( 2202): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a52278d
V/BluetoothMapService( 2202): BluetoothMapBinder()
D/BluetoothMapService( 2202): Received start request. Starting profile...
D/BluetoothMapService( 2202): start()
D/BluetoothMap( 1321): Proxy object connected
D/MapProfile( 1321): Bluetooth service connected
D/BluetoothMap( 1321): getConnectedDevices()
D/BluetoothMapEmailSettingsLoader( 2202): Found 0 applications
D/BluetoothMapEmailAppObserver( 2202): createReceiver()
D/BluetoothMapEmailAppObserver( 2202): initObservers()
D/BluetoothMapEmailAppObserver( 2202): getEnabledAccountItems()
D/BluetoothMap( 1321): Bluetooth is Not enabled
D/BluetoothAdapterService( 2202): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a52278d
D/HeadsetStateMachine( 2202): Proxy object connected
V/BluetoothMapService( 2202): Handler(): got msg=1
D/HeadsetStateMachine( 2202): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 2202): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/BluetoothAdapterState( 2202): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
D/HeadsetStateMachine( 2202): Disconnected process message: 11, size: 0
I/bluedroid( 2202): enable
I/GKI_LINUX( 2202): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 2202): btu_task pending for preload complete event
I/bt_hci_bdroid( 2202): init
I/bt_vendor( 2202): init
I/bt_vnd_conf( 2202): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 2202): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 2202): userial_init
I/bt_userial_vendor( 2202): userial vendor open: opening /dev/ttyHS99
I/bt_userial_vendor( 2202): device fd = 53 open
D/bt_userial( 2202): Entering userial_read_thread()
E/ConnectivityChangeReceiver( 1623): Ignoring connectivity change
--------- beginning of system
D/ConnectivityService(  761): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  761): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  761): apparently satisfied.  currentScore=60
D/ConnectivityManager.CallbackHandler( 1623): CM callback handler got msg 524290
D/ConnectivityService(  761): Got NetworkFactory Messenger for Telephony
W/DriveInitializer( 1623): Awaiting to be initialized
W/DriveInitializer( 1623): Background init thread started
I/bt_hwcfg( 2202): bt vendor lib: set UART baud 4000000
D/GpsLocationProvider(  761): received SIM realted action: android.intent.action.SIM_STATE_CHANGED
D/GpsLocationProvider(  761): SIM MCC/MNC is still not available
D/DcSwitchState( 1204): [DcSwitchState-0] DcSwitchState constructor E
D/DcSwitchState( 1204): [DcSwitchState-0] DcSwitchState constructor X
D/bt_hwcfg( 2202): Chipset BCM4335C0
D/bt_hwcfg( 2202): Target name = [BCM4335C0]
I/bt_hwcfg( 2202): Found patchfile: /vendor/firmware//bcm4335c0.hcd
D/DctController( 1204): [DctController] DctController(phones): Connect success: 0
W/ResourcesManager( 1204): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@284908d6:true
D/BluetoothManagerService(  761): Message: 30
D/ConnectivityService(  761): Got NetworkFactory Messenger for WIFI
D/WIFI    (  761): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
I/CalendarProvider2( 2126): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 2126): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
W/DriveInitializer( 1623): Background init thread ended
I/ActivityManager(  761): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=2344 uid=10012 gids={50012, 9997} abi=armeabi-v7a
V/OneTimeInitializerReceiver( 2344): OneTimeInitializerReceiver.onReceive
I/art     (  761): Explicit concurrent mark sweep GC freed 26644(1382KB) AllocSpace objects, 23(2MB) LOS objects, 33% free, 27MB/41MB, paused 1.087ms total 50.867ms
V/OneTimeService( 2344): OneTimeService.onHandleIntent
I/ActivityManager(  761): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=2371 uid=10014 gids={50014, 9997, 1028, 3003} abi=armeabi-v7a
D/TelephonyNetworkFactory( 1204): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
D/DctController( 1204): [DctController] EVENT_PHONE1_RADIO_OFF.
D/TelephonyDebugService( 1204): TelephonyDebugService()
D/WifiService(  761): New client listening to asynchronous messages
D/BluetoothHeadset( 1204): Proxy object connected
D/DctController( 1204): [DctController] DataStateReceiver: phoneId= 0
D/DctController( 1204): [DctController] DataStateReceiver: ignore invalid subId=-1
I/ActivityManager(  761): Killing 1321:com.android.settings/1000 (adj 15): empty #17
I/bt_hwcfg( 2202): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 2202): Settlement delay -- 100 ms
I/bt_hwcfg( 2202): Setting fw settlement delay to 100 
D/WifiService(  761): Client connection lost with reason: 4
W/libprocessgroup(  761): failed to open /acct/uid_1000/pid_1321/cgroup.procs: No such file or directory
D/GpsLocationProvider(  761): received SIM realted action: android.intent.action.SIM_STATE_CHANGED
D/GpsLocationProvider(  761): SIM MCC/MNC is still not available
D/GpsLocationProvider(  761): received SIM realted action: android.intent.action.ACTION_SUBINFO_RECORD_UPDATED
I/MmsService( 1204): mReceiver action: android.intent.action.ACTION_SUBINFO_RECORD_UPDATED
I/Telephony( 1204): : SUBINFO_RECORD_UPDATED : 4.
I/MmsService( 1204): MmsConfigManager.loadInBackground(): mcc/mnc: 0/0
D/GpsLocationProvider(  761): SIM MCC/MNC is still not available
I/RlzPingService( 1441): Setting next ping for 1453133390020
E/MmsService( 1204): MmsConfigManager.load -- empty getActiveSubInfoList
E/PhoneInterfaceManager( 1204): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
I/Telephony( 1204): PstnIncomingCallNotifier: Registering: Handler (com.android.internal.telephony.gsm.GSMPhone) {29c32e76}
I/bt_hwcfg( 2202): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 2202): Setting local bd addr to 34:FC:EF:11:AE:67
I/ActivityManager(  761): Killing 1848:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
I/bt_hwcfg( 2202): vendor lib fwcfg completed
I/bt-btu  ( 2202): btu_task received preload complete event
I/        ( 2202): BTE_InitTraceLevels -- TRC_HCI
I/        ( 2202): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 2202): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 2202): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 2202): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 2202): BTE_InitTraceLevels -- TRC_A2D
I/        ( 2202): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 2202): BTE_InitTraceLevels -- TRC_BTM
I/        ( 2202): BTE_InitTraceLevels -- TRC_GAP
I/        ( 2202): BTE_InitTraceLevels -- TRC_PAN
I/        ( 2202): BTE_InitTraceLevels -- TRC_SDP
I/        ( 2202): BTE_InitTraceLevels -- TRC_GATT
I/        ( 2202): BTE_InitTraceLevels -- TRC_SMP
I/        ( 2202): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 2202): BTE_InitTraceLevels -- TRC_BTIF
W/libprocessgroup(  761): failed to open /acct/uid_10045/pid_1848/cgroup.procs: No such file or directory
I/ActivityManager(  761): Killing 1221:com.android.printspooler/u0a72 (adj 15): empty #17
D/MtpService(  913): updating state; isCurrentUser=true, mMtpLocked=false
I/ContactAccountLoggerTas( 1349): canRun() : Opted Out
W/libprocessgroup(  761): failed to open /acct/uid_10072/pid_1221/cgroup.procs: No such file or directory
E/SQLiteLog(  913): (283) recovered 49 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
I/ActivityManager(  761): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=2406 uid=10036 gids={50036, 9997, 3003} abi=armeabi-v7a
W/MediaScanner(  913): Error opening directory '/oem/media/', skipping: No such file or directory.
,E/bt-btm  ( 2202): BTM_SecRegister:p_cb_info->p_le_callback == 0xa3dd99d5 
E/bt-btm  ( 2202): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3dd99d5 
I/iu.UploadsManager( 1623): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
E/UpdateRequestReceiver( 2406): ignoring update request
I/iu.UploadsManager( 1623): End new media; added: 0, uploading: 0, time: 38 ms
E/UpdateRequestReceiver( 2406): ignoring update request
W/art     ( 2406): No such thread id for suspend: 14
V/MediaScanner(  913): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@2ec0ffb5
V/MediaScanner(  913): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@2ec0ffb5
E/UpdateRequestReceiver( 2406): ignoring update request
E/UpdateRequestReceiver( 2406): ignoring update request
E/UpdateRequestReceiver( 2406): ignoring update request
E/UpdateRequestReceiver( 2406): ignoring update request
W/BroadcastQueue(  761): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to com.google.android.gallery3d/com.android.camera.DisableCameraReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
I/GoogleHttpClient( 1462): GMS http client unavailable, use old client
I/ActivityManager(  761): Start proc com.lge.SprintHiddenMenu for broadcast com.lge.SprintHiddenMenu/.sprintspec.data.UaproflieSettingReceiver: pid=2446 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
I/art     ( 1462): Explicit concurrent mark sweep GC freed 3391(145KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/21MB, paused 265us total 11.904ms
D/AndroidRuntime( 2430): 
D/AndroidRuntime( 2430): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2430): CheckJNI is OFF
E/bt-btif ( 2202): Calling BTA_HhEnable
E/bt-btif ( 2202): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 2202): Address is:34:FC:EF:11:AE:67
D/BluetoothAdapterProperties( 2202): Name is: Nexus 5
D/BluetoothManagerService(  761): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  761): Stored Bluetooth name: Nexus 5
D/BluetoothAdapterProperties( 2202): Scan Mode:20
D/BluetoothAdapterProperties( 2202): Discoverable Timeout:120
W/bt-smp  ( 2202): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2202): Plain text(LSB ~ MSB) = 91 58 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2202): Encrypted text(LSB ~ MSB) = 2b ed 3b 5a 45 52 16 aa 18 dd 82 8e 51 06 59 61 
W/bt-btm  ( 2202): Stopping oneshot timer
W/ResourcesManager( 2446): Asset path '/system/framework/serviceitems.jar' does not exist or contains no resources.
W/ResourcesManager( 2446): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/bte_conf( 2202): Device ID record 1 : primary
D/bte_conf( 2202):   vendorId            = 000f
D/bte_conf( 2202):   vendorIdSource      = 0001
D/bte_conf( 2202):   product             = 1200
D/bte_conf( 2202):   version             = 1436
D/bte_conf( 2202):   clientExecutableURL = 
D/bte_conf( 2202):   serviceDescription  = 
D/bte_conf( 2202):   documentationURL    = 
D/bte_conf( 2202): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 2202): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 2202): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 2202): ScanMode =  20
D/BluetoothAdapterProperties( 2202): State =  11
D/BluetoothAdapterProperties( 2202): Setting state to 12
I/BluetoothAdapterState( 2202): Bluetooth adapter state changed: 11-> 12
I/BluetoothAdapterState( 2202): Entering On State
D/BluetoothManagerService(  761): Message: 60
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  761): Broadcasting onBluetoothStateChange(true) to 5 receivers.
D/BluetoothAdapterProperties( 2202): Scan Mode:21
D/BluetoothHeadset( 1163): onBluetoothStateChange: up=true
D/BluetoothAdapterProperties( 2202): Discoverable Timeout:120
D/BluetoothA2dp(  761): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1204): onBluetoothStateChange: up=true
D/BluetoothHeadset(  761): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1163): onBluetoothStateChange: up=true
D/BluetoothManagerService(  761): Bluetooth State Change Intent: 11 -> 12
D/BluetoothManagerService(  761): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  761): Message: 40
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothMapService( 2202): onReceive
D/BluetoothMapService( 2202): STATE_ON
V/BluetoothMapService( 2202): Handler(): got msg=1
D/BluetoothMapMasInstance( 2202): Map Service startRfcommSocketListener
I/Telecom ( 1163): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
D/BluetoothMapMasInstance( 2202): MAS initSocket()
D/BluetoothMapMasInstance( 2202):   masId = 00
D/BluetoothMapMasInstance( 2202):   msgTypes = 0e
D/BluetoothMapMasInstance( 2202):   masName = SMS/MMS
D/BluetoothMapMasInstance( 2202):   SDP string = 000eSMS/MMS
D/HeadsetStateMachine( 2202): Disconnected process message: 9, size: 0
D/HeadsetStateMachine( 2202): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 2202): mNumber:  mType: 128
E/bt_h4   ( 2202): vendor lib postload completed
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/HeadsetStateMachine( 2202): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 2202): terminateScoUsingVirtualVoiceCall:No present call to terminate
W/BluetoothAdapter( 2202): getBluetoothService() called with no BluetoothManagerCallback
I/ActivityManager(  761): Start proc com.qualcomm.qcrilmsgtunnel for broadcast com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelAutoboot: pid=2479 uid=1001 gids={41001, 9997, 3003, 2001, 1028, 1015, 3002, 3001} abi=armeabi-v7a
V/BluetoothMapMasInstance( 2202): Succeed to create listening socket 
D/BluetoothMapMasInstance( 2202): Accepting socket connection...
I/art     (  194): Explicit concurrent mark sweep GC freed 703(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 191us total 9.429ms
I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 165us total 7.464ms
I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 193us total 8.426ms
D/AndroidRuntime( 2430): Calling main entry com.android.commands.am.Am
I/ActivityManager(  761): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/AndroidRuntime( 2430): Shutting down VM
I/ActivityManager(  761): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2505 uid=10278 gids={50278, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/MicrophoneInputStream( 1349): mic_close gfk@259b7140
I/ActivityManager(  761): Killing 1899:com.google.android.music:main/u0a60 (adj 15): empty #17
D/audio_hw_primary(  183): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  183): disable_snd_device: snd_device(55: voice-rec-mic)
I/HotwordRecognitionRnr( 1349): Hotword detection finished
I/HotwordRecognitionRnr( 1349): Stopping hotword detection.
W/libprocessgroup(  761): failed to open /acct/uid_10060/pid_1899/cgroup.procs: No such file or directory
D/QcrilMsgTunnelAutoboot( 2479): ComponentInfo{com.qualcomm.qcrilmsgtunnel/com.qualcomm.qcrilmsgtunnel.QcrilMsgTunnelService} started successfully
D/QcrilMsgTunnelService( 2479): onCreate method
D/QcrilMsgTunnelIfaceManager( 2479): : Instantiated
V/QcrilMsgTunnelSocket( 2479): Starting QcRil Sender & Receiver threads
I/QcrilMsgTunnelSocket( 2479): Connected to 'qmux_radio/rild_oem0' socket
D/QcrilMsgTunnelIfaceManager( 2479):  Registered for UNSOL OEM HOOK Responses to deliver external apps
I/WebViewFactory( 2505): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2505): Time to load native libraries: 3 ms (timestamps 4963-4966)
I/LibraryLoader( 2505): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 2505): Binding Chromium to main looper Looper (main, tid 1) {414b024}
I/LibraryLoader( 2505): Expected native library version number "",actual native library version number ""
I/chromium( 2505): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 2505): Initializing chromium process, singleProcess=true
,W/art     ( 2505): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 2505): ApplicationContext is null in ApplicationStatus
,W/chromium( 2505): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 2505): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2505): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 2505): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@393ea958:true
,D/FileApkUtils( 1623): Spent 28ms computing apk sha1.
,D/FileApkUtils( 1623): Module already staged or being staged:chimera-modules/MapsModule.apk
,I/art     ( 1623): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-71c764a6f3cb92bdc5525a965b589e7c5ed304f3@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-71c764a6f3cb92bdc5525a965b589e7c5ed304f3/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,W/art     ( 2505): Attempt to remove local handle scope entry from IRT, ignoring
,D/DexOptUtils( 1623): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-71c764a6f3cb92bdc5525a965b589e7c5ed304f3/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 1623): Keeping up-to-date module: module-71c764a6f3cb92bdc5525a965b589e7c5ed304f3
,D/ChimeraCfgMgr( 1623): Reading stored module config
,W/InstanceID/Rpc( 1623): Found 10008
,W/AwContents( 2505): onDetachedFromWindow called when already detached. Ignoring
,D/GmsModuleFndr( 1623): Beginning GMS chimera module scan
,D/SystemWebViewEngine( 2505): CordovaWebView is running on device made by: LGE
,W/art     ( 2505): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2505): Attempt to remove local handle scope entry from IRT, ignoring
,D/GmsModuleFndr( 1623): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
,D/ChimeraCfgMgr( 1623): Beginning module configuration check
,D/ChimeraCfgMgr( 1623): Module APKs unchanged, check complete
,I/art     (  761): Explicit concurrent mark sweep GC freed 12397(553KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 981us total 53.881ms
,D/OpenGLRenderer( 2505): Render dirty regions requested: true
,D/Atlas   ( 2505): Validating map...
,W/chromium( 2505): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/GCM     ( 1623): COMPAT: Multi user ser=0 current=0
,D/GCM     ( 1653): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,I/GCoreUlr( 1623): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/GCoreUlr( 1653): DispatchingService.onCreate()
,I/CheckinService( 1623): Checkin interval check for package: unspecified last checkin: 1452516304580 min interval config: 0 actual interval: 12286598
I/CheckinService( 1623): Disabling old GoogleServicesFramework version
D/SystemUpdateService( 1623): onCreate
D/SystemUpdateService( 1623): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1623): active receiver: enabled
,I/SystemUpdateService( 1623): showing system update notification
,V/AuthZen ( 1623): Handling intent: android.intent.action.BOOT_COMPLETED
,D/ChimeraCfgMgr( 1623): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/BootCompletedReceiver( 1623): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
D/BootCompletedReceiver( 1623): Got an BootCompleted event.
,D/AuthZenEventHandler( 1623): Handling event: android.intent.action.BOOT_COMPLETED
,D/BootCompletedReceiver( 1623): Will NOT schedule AdAttestation signal task because it's disabled.
,V/GLSActivity( 1653): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1653): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinService( 1623): Checking schedule, now: 1452528591241 next: 1452558471542
,I/ValidateNoPeople(  761): skipping global notification
I/CheckinService( 1623): active receiver: disabled
,I/GCoreUlr( 1653): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,D/SurfaceFlinger(  171): shader cache generated - 24 shaders in 143.316467 ms
,I/ActivityManager(  761): Delay finish: com.google.android.gms/.tron.AlarmReceiver
,I/ActivityManager(  761): Resuming delayed broadcast
,V/SystemUpdateService( 1623): retry (wakeup: false) in 3599935 ms
,I/OpenGLRenderer( 2505): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2505): Enabling debug mode 0
,I/GCoreUlr( 1653): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/art     ( 1623): Explicit concurrent mark sweep GC freed 19697(1410KB) AllocSpace objects, 17(272KB) LOS objects, 25% free, 20MB/27MB, paused 568us total 51.648ms
,W/BaseAppContext( 1623): Using Auth Proxy for data requests.
,W/SQLiteConnectionPool( 1623): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,E/BaseAppContext( 1623): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,I/ActivityManager(  761): Displayed com.example.hello/.MainActivity: +694ms (total +12s490ms)
,W/BindingManager( 2505): Cannot call determinedVisibility() - never saw a connection for the pid: 2505
,I/chromium( 2505): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,I/Keyboard.Facilitator( 1062): onFinishInput()
,V/GLSActivity( 1653): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1653): Unbound from all location providers
I/GCoreUlr( 1653): Place inference reporting - stopped
,I/AuthZen ( 1623): Fetching signing key...
,D/SystemUpdateService( 1623): onDestroy
,I/GCoreUlr( 1653): DispatchingService.onDestroy()
,I/GCoreUlr( 1653): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1653): Unbound from all location providers
I/GCoreUlr( 1653): Place inference reporting - stopped
,W/Auth    ( 1653): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,D/JsMessageQueue( 2505): Set native->JS mode to OnlineEventsBridgeMode
,I/AuthZen ( 1623): Signing key fetched successfully!
,V/GLSActivity( 1653): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1653): No location to return for getLastLocation()
W/FusedLocationProvider( 1653): location=null
,W/BaseAppContext( 1623): Using Auth Proxy for data requests.
E/AndroidProtocolHandler( 2505): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/a       ( 1623): Opening database auth.proximity.permit_store...
,W/GCoreFlp( 1653): No location to return for getLastLocation()
,W/FusedLocationProvider( 1653): location=null
,D/AuthZenTransactionCache( 1623): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 1623): Clearing transaction cache
,D/PersistentNotificationBroadcastReceiver( 1653): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,D/jxcore_app_log( 2505): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 2505): jxcore cordova android initializing
,I/ActivityManager(  761): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=2597 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/jxcore-log( 2505): Initializing JXcore engine
,W/jxcore-log( 2505): JXcore engine is ready
,W/jxcore-log( 2505): Starting JXcore engine
,W/m.example.hello( 2505): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8348]" dev="sockfs" ino=8348 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/m.example.hello( 2505): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/m.example.hello( 2505): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9584]" dev="sockfs" ino=9584 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 2505): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[16297]" dev="sockfs" ino=16297 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 2505): Platform android
W/jxcore-log( 2505): 
W/jxcore-log( 2505): Process ARCH arm
W/jxcore-log( 2505): 
,I/jxcore-log( 2505): JXcore Cordova bridge is ready!
I/jxcore-log( 2505): 
,W/jxcore-log( 2505): JXcore engine is started
,E/jxcore-log( 2505): >> LGE-Nexus 5
E/jxcore-log( 2505): 
,I/jxcore-log( 2505): Total memory 1946181632
I/jxcore-log( 2505): 
,I/jxcore-log( 2505): Free memory 409755648
I/jxcore-log( 2505): 
I/jxcore-log( 2505): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2505): 
,I/jxcore-log( 2505): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2505): 
,I/jxcore-log( 2505): userPath [ 'www', 'www' ]
I/jxcore-log( 2505): 
,I/jxcore-log( 2505): Size 1080 1776
I/jxcore-log( 2505): 
,I/jxcore-log( 2505): Screen Brightness 82
I/jxcore-log( 2505): 
,E/jxcore-log( 2505): Dummy Error Log.
E/jxcore-log( 2505): 
,W/ResourcesManager( 2597): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 2597): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 2597): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 2597): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 2597): Installed default security provider GmsCore_OpenSSL
,I/dex2oat ( 2634): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads237113945.jar --oat-fd=21 --oat-location=/data/data/com.google.android.youtube/cache/ads237113945.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/YouTube MDX( 2597): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/dex2oat ( 2634): dex2oat took 34.292ms (threads: 4)
,W/InstanceID/Rpc( 2597): Found 10008
,I/jxcore-log( 2505): getBuffer is called!!!!
I/jxcore-log( 2505): 
,W/GmsClient( 2597): mServiceBroker is null, client disconnected
,V/Babel   ( 1945): babel boot account: thalitester@gmail.com
,I/ActivityManager(  761): Start proc com.google.android.apps.fitness for broadcast com.google.android.apps.fitness/.FitnessBootReceiver: pid=2696 uid=10045 gids={50045, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,E/SQLiteLog( 1945): (284) automatic index on conversation_participants_view(conversation_id)
,W/VideoCapabilities( 1945): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 1945): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 1945): Unrecognized profile 2130706433 for video/avc
,E/SQLiteLog( 1945): (284) automatic index on conversation_participants_view(conversation_id)
,E/SQLiteLog( 1945): (284) automatic index on conversation_participants_view(conversation_id)
,I/ActivityManager(  761): Killing 1769:com.google.android.apps.magazines/u0a61 (adj 15): empty #17
,I/FitnessApp( 2696): Initializers took 1 milliseconds
,W/libprocessgroup(  761): failed to open /acct/uid_10061/pid_1769/cgroup.procs: No such file or directory
,I/ActivityManager(  761): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=2716 uid=10070 gids={50070, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  761): Killing 2045:com.google.android.apps.plus/u0a67 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10067/pid_2045/cgroup.procs: No such file or directory
,I/Gmail   ( 2716): getAccountsCursor
,D/ActivityThread( 2716): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,V/GLSActivity( 1653): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  761): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=2742 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GAV2    ( 2716): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  761): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 2716): Observing account changes for notifications
,I/art     (  761): Explicit concurrent mark sweep GC freed 18373(880KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 27MB/41MB, paused 835us total 48.529ms
,I/Exchange( 2742): EasService.onCreate
,I/Exchange( 2742): RestartPingTask
,I/Exchange( 2742): RestartPingsTask did not start any pings.
,I/Exchange( 2742): PSS stopIfIdle
I/Exchange( 2742): PSS has no active accounts; stopping service.
,I/Gmail   ( 2716): getAccountsCursor
,I/ActivityManager(  761): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=2775 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 1653): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl( 2086): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/GAV2    ( 2086): Thread[GAThread,5,main]: No campaign data found.
,I/GAv4-SVC( 1623): Google Analytics 8.4.89 is starting up.
,E/SQLiteLog( 2716): (283) recovered 47 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/Gmail   ( 2716): notifyAccountChanged
,I/Gmail   ( 2716): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/art     ( 1462): Explicit concurrent mark sweep GC freed 3384(133KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 15MB/21MB, paused 249us total 11.953ms
,I/Gmail   ( 2716): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 2716): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 2716): calculateUnknownSyncRationalesAndPurgeInBackground: running
,V/GLSActivity( 1653): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 2716): getAccountsCursor
,D/Finsky  ( 2775): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,V/GLSActivity( 1653): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 2716): getAccountsCursor
,V/GLSActivity( 1653): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2775): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 2775): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 2775): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Volley  ( 2775): [263] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 2775): [256] DiskBasedCache.clear: Cache cleared.
,I/ActivityManager(  761): Killing 2221:com.android.keychain/1000 (adj 15): empty #17
,D/Ads     ( 2775): Skipping gmscore version check
,I/ActivityManager(  761): Killing 2147:com.qualcomm.timeservice/u0a76 (adj 15): empty #18
,I/SystemBroadcastReceiver( 1062): Boot has been completed
I/SystemBroadcastReceiver( 1062): toggleAppIcon() : FLAG_SYSTEM = true
,W/libprocessgroup(  761): failed to open /acct/uid_1000/pid_2221/cgroup.procs: No such file or directory
,W/libprocessgroup(  761): failed to open /acct/uid_10076/pid_2147/cgroup.procs: No such file or directory
,D/Finsky  ( 2775): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 2775): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 2775): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 2775): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  761): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=2839 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1349): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/PackageBroadcastService( 1623): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,D/ChimeraCfgMgr( 1623): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1623): Loading module APK com.google.android.play.games
,I/ActivityManager(  761): Killing 2251:com.google.android.dialer/u0a10 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10010/pid_2251/cgroup.procs: No such file or directory
,I/ActivityManager(  761): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
,I/ActivityManager(  761): Resuming delayed broadcast
,D/ChimeraCfgMgr( 1623): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1623): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1623): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1623): Submit a task: k
,D/ChimeraCfgMgr( 1623): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 1623): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 1623): Processing package: com.example.hello
,D/GassUtils( 1623): Found app info for package com.example.hello:18. Hash: 68ddfd019b48f789223df845f1e49bbdc6edef025bd9dbaddc0e41222bbc602e
D/k       ( 1623): Found info for package com.example.hello in db.
,I/ActivityManager(  761): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=2875 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,W/BaseAppContext( 1623): Using Auth Proxy for data requests.
W/BaseAppContext( 1623): Using Auth Proxy for data requests.
,I/PeopleDatabaseHelper( 1623): cleanUpNonGplusAccounts done.
,W/BaseAppContext( 1623): Using Auth Proxy for data requests.
,W/BaseAppContext( 1623): Using Auth Proxy for data requests.
,W/BaseAppContext( 1623): Using Auth Proxy for data requests.
,W/BaseAppContext( 1623): Using Auth Proxy for data requests.
,W/BaseAppContext( 1623): Using Auth Proxy for data requests.
,I/UpdateIcingCorporaServi( 1349): UpdateCorporaTask done [took 500 ms] updated apps [took 500 ms] 
,D/ChimeraCfgMgr( 1623): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1623): Module APK com.google.android.play.games already loaded
,I/GAv4    ( 2875): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2875):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2875):   adb logcat -s GAv4
,W/GAv4    ( 2875): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2875): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2875): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 2875): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
,D/Finsky  ( 2775): [1] ExternalReferrer.access$200: Package state data is missing for com.example.hello
,W/ResourcesManager( 2875): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2875): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  761): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=2911 uid=10067 gids={50067, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  761): Killing 2344:com.google.android.onetimeinitializer/u0a12 (adj 15): empty #17
,V/JNIHelp ( 2875): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/libprocessgroup(  761): failed to open /acct/uid_10012/pid_2344/cgroup.procs: No such file or directory
,W/System  ( 2875): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2875): Installed default security provider GmsCore_OpenSSL
W/ResourcesManager( 2911): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/GLSActivity( 1653): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/UserPresentBroadcastReceiver( 1653): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,I/ActivityManager(  761): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=2942 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  761): Killing 2371:com.android.managedprovisioning/u0a14 (adj 15): empty #17
,I/ActivityManager(  761): Killing 2126:com.android.providers.calendar/u0a2 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10014/pid_2371/cgroup.procs: No such file or directory
W/libprocessgroup(  761): failed to open /acct/uid_10002/pid_2126/cgroup.procs: No such file or directory
,D/WifiService(  761): New client listening to asynchronous messages
,D/AuthorizationBluetoothService( 1653): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/Icing   ( 1623): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
,I/ActivityManager(  761): Start proc com.android.cellbroadcastreceiver for broadcast com.android.cellbroadcastreceiver/.CellBroadcastReceiver: pid=2960 uid=10003 gids={50003, 9997} abi=armeabi-v7a
,I/art     (  194): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 189us total 7.946ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 168us total 8.608ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 173us total 7.811ms
,D/Icing   ( 1623): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1623): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,I/art     (  761): Explicit concurrent mark sweep GC freed 12223(630KB) AllocSpace objects, 3(52KB) LOS objects, 33% free, 27MB/41MB, paused 806us total 51.396ms
,D/CellBroadcastReceiver( 2960): onReceive Intent { act=android.intent.action.SERVICE_STATE flg=0x10 cmp=com.android.cellbroadcastreceiver/.CellBroadcastReceiver (has extras) }
D/CellBroadcastReceiver( 2960): Intent ACTION_SERVICE_STATE_CHANGED
,D/CellBroadcastReceiver( 2960): Service state changed! 3 Full: 3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=false Current state=-1
,I/ActivityManager(  761): Killing 2406:com.google.android.configupdater/u0a36 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10036/pid_2406/cgroup.procs: No such file or directory
,D/SIP     ( 1204): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,I/ActivityManager(  761): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=2982 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Icing   ( 1623): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
,I/Icing   ( 1623): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
,I/MusicStore( 2982): Database version: 120
,W/ResourcesManager( 2982): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2982): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 2982): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 2982): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 2982): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@f8f29b2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 2982): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 2982): GMSCore installation verified
,I/ConfigStore( 2982): Config Database version: 1
,I/MediaRouter( 2982): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=11, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/NetworkMonitor( 2982): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 2982): type=WIFI subType= reason=null isConnected=true
,I/GHttpClientFactory( 2982): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 2982): Using platform SSLCertificateSocketFactory
,W/ContextImpl( 2942): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  761): Message: 20
,D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@12ce3d3b:true
,D/LocalBluetoothProfileManager( 2942): Adding local A2DP profile
,D/BluetoothManagerService(  761): Message: 30
,D/LocalBluetoothProfileManager( 2942): Adding local HEADSET profile
,D/BluetoothManagerService(  761): Message: 30
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2202): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothManagerService(  761): Message: 30
,D/BluetoothManagerService(  761): Message: 30
,D/LocalBluetoothProfileManager( 2942): Adding local MAP profile
,D/BluetoothMap( 2942): Create BluetoothMap proxy object
D/BluetoothManagerService(  761): Message: 30
,D/BluetoothManagerService(  761): Message: 30
,D/LocalBluetoothProfileManager( 2942): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 2942): finishStartingService: stopping service
,D/BluetoothA2dp( 2942): Proxy object connected
,D/A2dpProfile( 2942): Bluetooth service connected
,D/BluetoothHeadset( 2942): Proxy object connected
,D/HeadsetProfile( 2942): Bluetooth service connected
,D/BluetoothInputDevice( 2942): Proxy object connected
D/HidProfile( 2942): Bluetooth service connected
,D/BluetoothPan( 2942): BluetoothPAN Proxy object connected
,D/PanProfile( 2942): Bluetooth service connected
D/BluetoothMap( 2942): Proxy object connected
,D/MapProfile( 2942): Bluetooth service connected
D/BluetoothMap( 2942): getConnectedDevices()
,V/BluetoothMapService( 2202): getConnectedDevices()
,D/BluetoothPbap( 2942): Proxy object connected
,D/PbapServerProfile( 2942): Bluetooth service connected
,D/AuthorizationBluetoothService( 1653): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2202): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 2202): Accept thread started.
,D/GCM     ( 1653): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/GCoreFlp( 1653): No location to return for getLastLocation()
W/FusedLocationProvider( 1653): location=null
,I/MediaStoreImporter( 2982): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager(  761): Killing 1522:com.google.android.keep/u0a71 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10071/pid_1522/cgroup.procs: No such file or directory
,E/WifiStateMachine(  761): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=12.62 rxSuccessRate=10.38 targetRoamBSSID=c0:ff:d4:d3:aa:4a RSSI=-51
,E/WifiStateMachine(  761): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/wpa_supplicant( 1051): wlan0: CTRL-EVENT-SCAN-STARTED 
,I/ActivityManager(  761): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=3053 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 1945): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1945): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 1945): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ResourcesManager( 3053): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/System  ( 1945): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 1945): Installed default security provider GmsCore_OpenSSL
,I/CalendarProvider2( 3053): Created com.android.providers.calendar.CalendarAlarmManager@185630b7(com.android.providers.calendar.CalendarProvider2@414b024)
,E/PhoneInterfaceManager( 1204): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,E/SQLiteLog( 3053): (284) automatic index on view_events(_id)
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  761): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1c243a39 mBinding = false
,D/BluetoothManagerService(  761): Message: 2
D/BluetoothManagerService(  761): Sending off request.
D/BluetoothAdapterState( 2202): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 2202): Setting state to 13
I/BluetoothAdapterState( 2202): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 2202): onBluetoothDisable()
I/BluetoothAdapterState( 2202): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothAdapterProperties( 2202): Scan Mode:20
D/BluetoothAdapterState( 2202): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
D/btif_config_util( 2202): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/BtOppRfcommListener( 2202): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,W/bt-btif ( 2202): bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
,V/BluetoothMapMasInstance( 2202): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 2202): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 2202): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 2202): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 2202): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 2202): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 2202): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 2202): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,W/bt-l2cap( 2202): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2202): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothManagerService(  761): Message: 60
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  761): Bluetooth State Change Intent: 12 -> 13
,D/WifiService(  761): setWifiEnabled: false pid=2505, uid=10278
E/WifiService(  761): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothMapService( 2202): onReceive
D/BluetoothMapService( 2202): STATE_TURNING_OFF
V/BluetoothMapService( 2202): Handler(): got msg=4
D/BluetoothMapService( 2202): MAP Service closeService in
,D/BluetoothMapMasInstance( 2202): MAP Service shutdown
V/BluetoothMapService( 2202): MAP Service closeService out
D/WifiService(  761): New client listening to asynchronous messages
,I/BtOppRfcommListener( 2202): stopping Accept Thread
,I/BtOppRfcommListener( 2202): BluetoothSocket listen thread finished
,W/ContextImpl( 2942): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver( 2942): finishStartingService: stopping service
,E/WifiStateMachine(  761): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
I/jxcore-log( 2505): ****TEST TOOK:  5062  ms ****
I/jxcore-log( 2505): 
I/jxcore-log( 2505): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2505): 
,D/CommandListener(  179): Clearing all IP addresses on wlan0
D/AuthorizationBluetoothService( 1653): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothPbap( 2942): Proxy object disconnected
D/PbapServerProfile( 2942): Bluetooth service disconnected
V/NativeCrypto( 1653): Read error: ssl=0xb4178e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1653): Read error: ssl=0x9ac5de00: I/O error during system call, Connection timed out
V/NativeCrypto( 1653): SSL shutdown failed: ssl=0xb4178e00: I/O error during system call, Broken pipe
,E/Auth    ( 1653): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.talk, Service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
E/Auth    ( 1653): com.google.android.gms.auth.be.account.b.d: Error when calling server.
E/Auth    ( 1653): 	at com.google.android.gms.auth.be.account.b.e.a(SourceFile:117)
E/Auth    ( 1653): 	at com.google.android.gms.auth.be.p.a(SourceFile:355)
E/Auth    ( 1653): 	at com.google.android.gms.auth.be.o.a(SourceFile:260)
E/Auth    ( 1653): 	at com.google.android.gms.auth.firstparty.dataservice.y.a(SourceFile:197)
E/Auth    ( 1653): 	at com.google.android.gms.auth.firstparty.dataservice.x.a(SourceFile:558)
E/Auth    ( 1653): 	at com.google.android.gms.auth.firstparty.dataservice.x.a(SourceFile:196)
E/Auth    ( 1653): 	at com.google.android.gms.auth.o.a(SourceFile:276)
E/Auth    ( 1653): 	at com.google.android.gms.auth.o.a(SourceFile:196)
E/Auth    ( 1653): 	at com.google.android.b.b.onTransact(SourceFile:137)
E/Auth    ( 1653): 	at android.os.Binder.execTransact(Binder.java:446)
E/Auth    ( 1653): Caused by: javax.net.ssl.SSLException: Read error: ssl=0x9ac5de00: I/O error during system call, Connection timed out
E/Auth    ( 1653): 	at com.google.android.gms.org.conscrypt.NativeCrypto.SSL_read(Native Method)
E/Auth    ( 1653): 	at com.google.android.gms.org.conscrypt.s.read(SourceFile:714)
E/Auth    ( 1653): 	at com.android.okio.Okio$2.read(Okio.java:113)
E/Auth    ( 1653): 	at com.android.okio.RealBufferedSource.indexOf(RealBufferedSource.java:147)
E/Auth    ( 1653): 	at com.android.okio.RealBufferedSource.readUtf8LineStrict(RealBufferedSource.java:94)
E/Auth    ( 1653): 	at com.android.okhttp.internal.http.HttpConnection.readResponse(HttpConnection.java:175)
E/Auth    ( 1653): 	at com.android.okhttp.internal.http.HttpTransport.readResponseHeaders(HttpTransport.java:101)
E/Auth    ( 1653): 	at com.android.okhttp.internal.http.HttpEngine.readResponse(HttpEngine.java:616)
E/Auth    ( 1653): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:379)
E/Auth    ( 1653): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:323)
E/Auth    ( 1653): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.getResponseCode(HttpURLConnectionImpl.java:491)
E/Auth    ( 1653): 	at com.android.okhttp.internal.http.DelegatingHttpsURLConnection.getResponseCode(DelegatingHttpsURLConnection.java:105)
E/Auth    ( 1653): 	at com.android.okhttp.internal.http.HttpsURLConnectionImpl.getResponseCode(HttpsURLConnectionImpl.java:25)
E/Auth    ( 1653): 	at com.google.android.gms.http.GoogleHttpClient.a(SourceFile:802)
E/Auth    ( 1653): 	at com.google.android.gms.http.GoogleHttpClient.a(SourceFile:767)
E/Auth    ( 1653): 	at com.google.android.gms.http.GoogleHttpClient.execute(SourceFile:665)
E/Auth    ( 1653): 	at com.google.android.gms.auth.j.a.a(SourceFile:77)
E/Auth    ( 1653): 	at com.google.android.gms.auth.j.a.a(SourceFile:114)
E/Auth    ( 1653): 	at com.google.android.gms.auth.be.account.b.e.a(SourceFile:115)
E/Auth    ( 1653): 	... 9 more
,D/ConnectivityService(  761): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): ValidatedState{ when=-7ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=-7ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  761): scanCount==0 - aborting
,D/WifiNetworkAgent(  761): NetworkAgent: NetworkAgent channel lost
,D/WifiScanningService(  761): SCAN_AVAILABLE : 1
,D/RttService(  761): SCAN_AVAILABLE : 1
D/RttService(  761): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiScanningService(  761): StartedState got{ when=-2ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  761): DefaultState
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  761): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  761): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  761): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Disconnected - quitting
,W/bt-btif ( 2202): ag scb idx 1 not allocated
E/bt-btif ( 2202): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 2202): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2202): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2202): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2202): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2202): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2202): L2CAP - PSM: 0x0017 not found for deregistration
,D/bt_userial( 2202): RX termination
W/bt_userial( 2202): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 2202): Leaving userial_read_thread()
D/bt_userial( 2202): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 2202): hw_epilog_process
I/bt_userial_vendor( 2202): device fd = 53 close
D/ConnectivityService(  761): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524292
,I/GKI_LINUX( 2202): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 2202): GKI_exit_task 0 done
I/GKI_LINUX( 2202): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 2202): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/ConnectivityManager.CallbackHandler( 1623): CM callback handler got msg 524292
,E/ConnectivityService(  761): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/HeadsetService( 2202): Received stop request...Stopping profile...
D/TelephonyNetworkFactory( 1204): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/BluetoothAdapterService( 2202): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a52278d
,D/HeadsetStateMachine( 2202): Exit Disconnected: -1
,D/BluetoothHeadset( 1163): Proxy object disconnected
,D/BluetoothHeadset(  761): Proxy object disconnected
,D/BluetoothHeadset( 1163): Proxy object disconnected
D/BluetoothHeadset( 2942): Proxy object disconnected
,D/HeadsetProfile( 2942): Bluetooth service disconnected
D/BluetoothAdapterState( 2202): Stopping profile services that were post enabled
,D/A2dpService( 2202): Received stop request...Stopping profile...
D/A2dpStateMachine( 2202): Exit Disconnected: -1
,D/BluetoothAdapterService( 2202): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a52278d
,D/BluetoothA2dp(  761): Proxy object disconnected
,D/HidService( 2202): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2202): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a52278d
,D/HealthService( 2202): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2202): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a52278d
,D/HeadsetStateMachine( 2202): Unbinding service...
,W/BluetoothHeadsetServiceJni( 2202): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2202): Cleaning up Bluetooth Handsfree callback object
,D/PanService( 2202): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 2202): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a52278d
,D/BtGatt.DebugUtils( 2202): handleDebugAction() action=null
,D/BtGatt.GattService( 2202): Received stop request...Stopping profile...
D/BtGatt.GattService( 2202): stop()
D/BtGatt.AdvertiseManager( 2202): advertise clients cleared
,D/BluetoothAdapterService( 2202): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a52278d
,D/BluetoothMapService( 2202): Received stop request...Stopping profile...
D/BluetoothMapService( 2202): stop()
,D/BluetoothMapEmailAppObserver( 2202): deinitObservers()
D/BluetoothMapEmailAppObserver( 2202): removeReceiver()
D/BluetoothAdapterService( 2202): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a52278d
,I/GKI_LINUX( 2202): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 2202): GKI_exit_task 2 done
I/GKI_LINUX( 2202): GKI_shutdown(): task [A2DP-MEDIA] terminated
,W/BluetoothHidServiceJni( 2202): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 2202): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2202): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 2202): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2202): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 2202): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2202): Cleaning up Bluetooth PAN callback object
,V/BluetoothMapService( 2202): Handler(): got msg=4
D/BluetoothMapService( 2202): MAP Service closeService in
V/BluetoothMapService( 2202): MAP Service closeService out
D/BluetoothMapService( 2202): cleanup()
D/BluetoothMapService( 2202): MAP Service closeService in
,V/BluetoothMapService( 2202): MAP Service closeService out
,D/BluetoothAdapterState( 2202): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
,D/BluetoothAdapterProperties( 2202): Setting state to 10
I/BluetoothAdapterState( 2202): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService(  761): Message: 60
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  761): Broadcasting onBluetoothStateChange(false) to 11 receivers.
I/BluetoothAdapterState( 2202): Entering OffState
D/BluetoothPbap( 2942): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1163): onBluetoothStateChange: up=false
D/BluetoothA2dp(  761): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1204): onBluetoothStateChange: up=false
D/BluetoothHeadset(  761): onBluetoothStateChange: up=false
D/BluetoothMap( 2942): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1163): onBluetoothStateChange: up=false
D/BluetoothA2dp( 2942): onBluetoothStateChange: up=false
D/BluetoothHeadset( 2942): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 2942): onBluetoothStateChange: up=false
D/BluetoothManagerService(  761): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  761): Broadcasting onBluetoothServiceDown() to 9 receivers.
,D/BluetoothManagerService(  761): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1c243a39 mBinding = false
,D/BluetoothManagerService(  761): Sending unbind request.
,I/ActivityManager(  761): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3104 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  761): Explicit concurrent mark sweep GC freed 21976(1104KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/41MB, paused 1.476ms total 122.164ms
,D/BluetoothManagerService(  761): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter(  899): 728182790: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter(  899): 728182790: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  899): 728182790: getState() :  mService = null. Returning STATE_OFF
,I/wpa_supplicant( 1051): p2p0: CTRL-EVENT-TERMINATING 
,I/GKI_LINUX( 2202): gki_task task_id=1 [BTIF] terminating
E/Babel   ( 1945): Network error while getting auth token
I/wpa_supplicant( 1051): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
I/GKI_LINUX( 2202): GKI_exit_task 1 done
I/GKI_LINUX( 2202): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 2202): cleanupNative: return from cleanup
,E/Babel   ( 1945): cal: Cannot get auth token
E/Babel   ( 1945): 	at g.a(Unknown Source)
E/Babel   ( 1945): 	at cae.a(SourceFile:3089)
E/Babel   ( 1945): 	at cae.a(SourceFile:1131)
E/Babel   ( 1945): 	at cws.a(SourceFile:4333)
E/Babel   ( 1945): 	at cws.a(SourceFile:1419)
E/Babel   ( 1945): 	at crl.a(SourceFile:492)
E/Babel   ( 1945): 	at crl.a(SourceFile:1468)
E/Babel   ( 1945): 	at cqu.a(SourceFile:4416)
E/Babel   ( 1945): 	at cas.b(SourceFile:106)
E/Babel   ( 1945): 	at cap.d(SourceFile:335)
E/Babel   ( 1945): 	at caq.run(SourceFile:81)
E/Babel   ( 1945): Caused by: java.io.IOException: NetworkError
E/Babel   ( 1945): 	at eeg.a(Unknown Source)
E/Babel   ( 1945): 	at eeg.a(Unknown Source)
E/Babel   ( 1945): 	at eeg.a(Unknown Source)
E/Babel   ( 1945): 	at g.a(Unknown Source)
E/Babel   ( 1945): 	... 10 more
,D/BluetoothAdapter( 1653): 828387491: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1653): 828387491: getState() :  mService = null. Returning STATE_OFF
,I/Babel   ( 1945): connection state changed from CONNECTED to DISCONNECTED
,I/art     ( 2202): System.exit called, status: 0
I/AndroidRuntime( 2202): VM exiting with result code 0, cleanup skipped.
,D/AndroidRuntime( 3098): 
D/AndroidRuntime( 3098): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3098): CheckJNI is OFF
,I/ActivityManager(  761): Process com.android.bluetooth (pid 2202) has died
,D/AndroidRuntime( 3098): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  761): Force stopping com.example.hello appid=10278 user=-1: uninstall pkg
I/ActivityManager(  761): Killing 2505:com.example.hello/u0a278 (adj 0): stop com.example.hello
,I/WindowState(  761): WIN DEATH: Window{3d4daf5d u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  761): Client connection lost with reason: 4
,W/PackageSettings(  761): Skipping PackageSetting{25313351 com.test.thalitest/10270} due to missing metadata
,D/Tethering(  761): InitialState.processMessage what=4
,I/wpa_supplicant( 1051): wlan0: CTRL-EVENT-TERMINATING 
,W/ActivityManager(  761): Force removing ActivityRecord{30d3ca0e u0 com.example.hello/.MainActivity t214}: app died, no saved state
,W/ActivityManager(  761): Spurious death for ProcessRecord{35211cfb 2505:com.example.hello/u0a278}, curProc for 2505: null
,I/ActivityManager(  761): Force stopping com.example.hello appid=10278 user=0: pkg removed
,D/Tethering(  761): sendTetherStateChangedBroadcast 0, 0, 0
,I/Keyboard.Facilitator( 1062): resetDictionaries() : en_US
,W/Settings( 1945): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/GeofencerStateMachine( 1653): Ignoring removeGeofence because network location is disabled.
,W/Settings( 1653): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Keyboard.Facilitator.DecoderInitializer( 1062): run()
,I/Decoder ( 1062): createOrResetDecoder
,I/InputReader(  761): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 1462): Explicit concurrent mark sweep GC freed 2953(118KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/21MB, paused 1.202ms total 15.343ms
,I/ConfigService( 1653): onCreate
,W/SQLiteConnectionPool( 1462): A SQLiteConnection object for database '/data/user/0/com.google.android.gsf/databases/gservices.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/CalendarProvider2( 3053): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 3053): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,W/SQLiteConnectionPool( 1462): A SQLiteConnection object for database '/data/user/0/com.google.android.gsf/databases/gservices.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1062): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1062): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1062): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1062): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1062): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1062): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1062): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1062): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1062): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1062): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1062): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1062): run()
I/StatsUtilsManager( 1062): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1062): shouldRecordStats() = Too Soon
,W/InputMethodManagerService(  761): Got RemoteException sending setActive(false) notification to pid 2505 uid 10278
,I/Keyboard.Facilitator( 1062): onFinishInput()
,I/MicrophoneInputStream( 1349): mic_starting gfk@1e045891
,I/HotwordRecognitionRnr( 1349): Starting hotword detection.
D/BackupManagerService(  761): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  761): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  761): removeObsoleteFile: deleting file=214_task.xml
,I/AudioFlinger(  183): AudioFlinger's thread 0xb31bd000 ready to run
,I/MicrophoneInputStream( 1349): mic_started gfk@1e045891
,D/audio_hw_primary(  183): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  183): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
D/        (  183): Failed to fetch the lookup information of the device 0000003E 
E/ACDB-LOADER(  183): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  183): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  183): enable_audio_route: apply and update mixer path: audio-record
,I/art     (  761): Explicit concurrent mark sweep GC freed 15917(1047KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.561ms total 216.007ms
,D/AndroidRuntime( 3098): Shutting down VM
,I/ActivityManager(  761): Killing 2446:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
,I/HotwordWorker( 1349): onReady
,W/libprocessgroup(  761): failed to open /acct/uid_1000/pid_2446/cgroup.procs: No such file or directory
,I/ActivityManager(  761): Killing 2597:com.google.android.youtube/u0a80 (adj 15): empty #17
,W/ResourcesManager( 1250): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1250): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/libprocessgroup(  761): failed to open /acct/uid_10080/pid_2597/cgroup.procs: No such file or directory
,W/ContextImpl( 2942): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/ActivityManager(  761): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=3171 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/DockEventReceiver( 2942): finishStartingService: stopping service
,W/ResourcesManager( 3171): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/AdapterServiceConfig( 3171): Adding HeadsetService
D/AdapterServiceConfig( 3171): Adding A2dpService
D/AdapterServiceConfig( 3171): Adding HidService
,D/AdapterServiceConfig( 3171): Adding HealthService
,D/AdapterServiceConfig( 3171): Adding PanService
,D/AdapterServiceConfig( 3171): Adding GattService
D/AdapterServiceConfig( 3171): Adding BluetoothMapService
,D/BluetoothAdapter( 2942): 847552102: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager(  761): Killing 2171:com.google.android.deskclock/u0a38 (adj 15): empty #17
,D/AuthorizationBluetoothService( 1653): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/libprocessgroup(  761): failed to open /acct/uid_10038/pid_2171/cgroup.procs: No such file or directory
,W/OpenGLRenderer( 1250): Incorrectly called buildLayer on View: adg, destroying layer...
W/OpenGLRenderer( 1250): Incorrectly called buildLayer on View: adg, destroying layer...
,E/SQLiteLog( 1290): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,--------- beginning of crash
E/AndroidRuntime( 1290): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 1290): Process: android.process.acore, PID: 1290
E/AndroidRuntime( 1290): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1290): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1290): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1290): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1290): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1290): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1290): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1290): 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:381)
E/AndroidRuntime( 1290): 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:350)
E/AndroidRuntime( 1290): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1706)
E/AndroidRuntime( 1290): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/AndroidRuntime( 1290): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1290): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1290): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService(  761): Can't write: system_app_crash
E/DropBoxManagerService(  761): java.io.FileNotFoundException: /data/system/dropbox/drop94.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  761): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  761): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  761): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  761): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  761): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  761): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  761): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  761): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  761): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  761): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  761): 	... 5 more
,D/VoicemailCleanupService( 1290): Cleaning up data for package: com.example.hello
,E/SQLiteLog( 1290): (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.example.hello'))) AND ((type = 4))] disk I/O error
,I/Process ( 1290): Sending signal. PID: 1290 SIG: 9
,D/OpenGLRenderer(  761): Render dirty regions requested: true
,D/Atlas   (  761): Validating map...
,I/UpdateIcingCorporaServi( 1349): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/ActivityManager(  761): Process android.process.acore (pid 1290) has died
E/SQLiteLog( 1349): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/ActivityManager(  761): Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,E/AndroidRuntime( 1349): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 1349): Process: com.google.android.googlequicksearchbox:search, PID: 1349
E/AndroidRuntime( 1349): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1349): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1349): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1349): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1349): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1349): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1349): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1349): 	at csx.d(PG:186)
E/AndroidRuntime( 1349): 	at cun.g(PG:594)
E/AndroidRuntime( 1349): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 1349): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:325)
E/AndroidRuntime( 1349): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AndroidRuntime( 1349): 	at cuw.Tg(PG:368)
E/AndroidRuntime( 1349): 	at cuy.ub(PG:301)
E/AndroidRuntime( 1349): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
E/AndroidRuntime( 1349): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
E/AndroidRuntime( 1349): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1349): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1349): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1349): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService(  761): Can't write: system_app_crash
E/DropBoxManagerService(  761): java.io.FileNotFoundException: /data/system/dropbox/drop96.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  761): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  761): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  761): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  761): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  761): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  761): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  761): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  761): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  761): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  761): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  761): 	... 5 more
,I/Adreno-EGL(  761): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  761): Initialized EGL, version 1.4
,D/OpenGLRenderer(  761): Enabling debug mode 0
,E/qdoverlay(  171): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
,E/qdoverlay(  171): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  171): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
E/qdoverlay(  171): src msmfb_img w=3200 h=1920 format=5 MDP_RGB_888
E/qdoverlay(  171): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  171): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  171): == Last good known OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
E/qdoverlay(  171): src msmfb_img w=3200 h=1920 format=5 MDP_RGB_888
E/qdoverlay(  171): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  171): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  171): Ctrl commit failed set overlay
E/qdhwcomposer(  171): configureLowRes: commit failed for low res panel
E/qdoverlay(  171): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  171): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  171): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  171): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  171): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  171): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,E/qdoverlay(  171): == Last good known OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x60000 id=8
E/qdoverlay(  171): src msmfb_img w=1152 h=96 format=13 MDP_RGBA_8888
E/qdoverlay(  171): src_rect mdp_rect x=0 y=0 w=1080 h=75
E/qdoverlay(  171): dst_rect mdp_rect x=0 y=0 w=1080 h=75
E/qdoverlay(  171): Ctrl commit failed set overlay
E/qdhwcomposer(  171): configure: commit fails
E/qdoverlay(  171): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  171): MdpCtrl close error in unset
,W/InputMethodManagerService(  761): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@79cd8b2 attribute=null, token = android.os.BinderProxy@2706666e

```
