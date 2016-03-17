#### Test 625090941eef958_thali01_samsung-SM-A500FU Logs


```
--------- beginning of system
03-17 08:35:44.004  1018  1018 D UsbHostNotification: boot completed
03-17 08:35:44.014  1018  1018 D UsbHostRestrictor: mBootCompletedReceiver onReceive
03-17 08:35:44.014  1018  1018 D UsbHostRestrictor: initSetUsbBlock STARTED
--------- beginning of main
03-17 08:35:44.034  2632  2774 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
03-17 08:35:44.034  2632  2774 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa3f246e9 
03-17 08:35:44.034  2632  2774 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3f246e9 
03-17 08:35:44.034  1018  1058 D PackageManager: [MSG] MCS_UNBIND
03-17 08:35:44.054  1018  1133 D WIFI    : got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
03-17 08:35:44.054  1018  1133 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
03-17 08:35:44.054  1018  1018 D UsbHostRestrictor: SIM was never inserted
03-17 08:35:44.054  1018  1018 D UsbHostRestrictor: writableHostSysNode[false]
03-17 08:35:44.054  1018  1018 D UsbHostRestrictor: Can NOT Write Disable Sys Node to [ON]
03-17 08:35:44.054  1018  1257 I ActivityManager: Killing 1559:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
03-17 08:35:44.084  2632  2707 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
03-17 08:35:44.084  2632  2707 E bt-btif : Calling BTA_HhEnable
03-17 08:35:44.084  2632  2707 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
03-17 08:35:44.084  2632  2707 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
03-17 08:35:44.084  2632  2707 E BluetoothServiceJni: populateRssiValuesNative
03-17 08:35:44.084  2632  2707 I bluedroid: getModelRssiValues
03-17 08:35:44.084  2632  2707 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
03-17 08:35:44.094  2632  2707 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
03-17 08:35:44.094  2059  2703 W DriveInitializer: Awaiting to be initialized
03-17 08:35:44.094  2632  2707 D BluetoothAdapterProperties: Name is: A5-1
03-17 08:35:44.094  2059  2840 W DriveInitializer: Background init thread started
03-17 08:35:44.094  2632  2707 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-17 08:35:44.094  2632  2707 D BluetoothAdapterProperties: Scan Mode:20
03-17 08:35:44.094  2632  2707 D BluetoothAdapterProperties: Discoverable Timeout:120
03-17 08:35:44.094  2632  2707 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
03-17 08:35:44.094  2632  2707 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
03-17 08:35:44.094  2632  2707 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
03-17 08:35:44.094  2632  2707 E bt-btif : btif_sock_init: !radio_req && !rfc_init
03-17 08:35:44.094  2632  2707 E bt-btif : btif_sock_init: !vhci_init
03-17 08:35:44.094  2632  2707 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,03-17 08:35:44.104  2632  2828 E bt_mct  : hci lib postload completed
03-17 08:35:44.104  1018  1018 D PersonaManagerService: ACTION_BOOT_COMPLETED
03-17 08:35:44.114  1018  1062 E PersonaManagerServiceHandler:  MSG_BOOT_COMPLETE_RECEIVED : soft start personas 
03-17 08:35:44.114  1018  1018 D SettingsProvider: name = bluetooth_name
03-17 08:35:44.114  1018  1062 D KnoxKeyguardUpdateMonitor: onBootComplete
03-17 08:35:44.114  1018  1018 D UsbStorageNotification: boot completed
03-17 08:35:44.124  1018  1018 I KnoxKeyguardUpdateMonitor: onTrustManagedChanged user 0, managed:false
03-17 08:35:44.124  1192  1192 D KeyguardViewMediator: onTrustChanged( Showing = false , userId = 0 )
03-17 08:35:44.124  2632  2707 D IOP_DB_BT: db_open: db_open : handle 3023323152l, read 13894 bytes onto local cache
03-17 08:35:44.124  2632  2707 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
03-17 08:35:44.124  2632  2707 D IOP_DB_BT: db_query: result 1
03-17 08:35:44.124  2632  2707 I         : iop_db_open: iop_db_open status 0
03-17 08:35:44.124  1018  1018 I KnoxKeyguardUpdateMonitor: onTrustChanged user:0, enable:false
03-17 08:35:44.124  1018  1062 D PersonaManagerService: getPersonasForUser(): returning null!
03-17 08:35:44.134  1018  1040 D SensorService: [SO] currT = 35210191807, prevT = 34730074880, diff = 480116927, [0.115 0.402 10.113]
03-17 08:35:44.134  1018  1040 D SensorService: [SO] 0.115 0.402 10.113
03-17 08:35:44.134  1018  1040 D SensorService: [SO] [100 -> 255]
03-17 08:35:44.134  1018  1558 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
03-17 08:35:44.134  1018  1558 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
03-17 08:35:44.134  1018  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
03-17 08:35:44.144  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
03-17 08:35:44.224  2632  2707 D bte_conf: Device ID record 1 : primary
03-17 08:35:44.224  2632  2707 D bte_conf:   vendorId            = 0075
03-17 08:35:44.224  2632  2707 D bte_conf:   vendorIdSource      = 0001
03-17 08:35:44.224  2632  2707 D bte_conf:   product             = 0100
03-17 08:35:44.224  2632  2707 D bte_conf:   version             = 0200
03-17 08:35:44.224  2632  2707 D bte_conf:   clientExecutableURL = 
03-17 08:35:44.224  2632  2707 D bte_conf:   serviceDescription  = 
03-17 08:35:44.224  2632  2707 D bte_conf:   documentationURL    = 
03-17 08:35:44.224  2632  2707 D bte_conf: bte_load_did_conf no section named DID2.
03-17 08:35:44.224  2632  2707 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
03-17 08:35:44.224  2632  2702 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
03-17 08:35:44.224  2632  2702 D BluetoothAdapterProperties: ScanMode =  20
03-17 08:35:44.224  2632  2702 D BluetoothAdapterProperties: State =  11
03-17 08:35:44.224  1018  1734 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
03-17 08:35:44.234  2632  2702 D BluetoothAdapterProperties: Setting state to 12
03-17 08:35:44.234  2632  2702 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
03-17 08:35:44.234  2632  2707 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-17 08:35:44.234  2632  2707 D BluetoothAdapterProperties: Scan Mode:21
03-17 08:35:44.234  2632  2707 D BluetoothAdapterProperties: Discoverable Timeout:120
03-17 08:35:44.234  1018  1558 D SettingsProvider: name = bluetooth_a2dp_sink_mode
03-17 08:35:44.234  1018  1558 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 08:35:44.234  1018  1558 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 08:35:44.234  1018  1558 D SettingsProvider: selectionArgs: false
03-17 08:35:44.234  1018  1558 D SettingsProvider: selectionArgs: 1002
03-17 08:35:44.234  1018  1558 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 08:35:44.234  1018  1558 D SettingsProvider: ret = -1
03-17 08:35:44.244  1018  1558 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
03-17 08:35:44.244  2632  2702 D BluetoothAdapterService: Bluetooth PBAP supproted is true
03-17 08:35:44.244  2632  2702 D BluetoothAdapterService: updateAdapterState state is 12
03-17 08:35:44.244  1018  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
03-17 08:35:44.244  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
03-17 08:35:44.244  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:44.244  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:35:44.244  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
03-17 08:35:44.254  2632  2702 D BluetoothAdapterService: Autoconnection is available 
03-17 08:35:44.254  2632  2702 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
03-17 08:35:44.254  2632  2702 D BluetoothAdapterService: starting service from this receiver
03-17 08:35:44.254  1018  1487 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
03-17 08:35:44.254  1018  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
03-17 08:35:44.254  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:44.254  1018  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:35:44.254  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
03-17 08:35:44.254  2632  2702 I BluetoothAdapterState: Entering On State from state = 11
03-17 08:35:44.264  1192  1203 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 08:35:44.264  1192  1203 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 08:35:44.264  1453  1468 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 08:35:44.264  1453  1468 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 08:35:44.264  2632  2712 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 08:35:44.264  2632  2712 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 08:35:44.264  1443  1459 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 08:35:44.264  1443  1459 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 08:35:44.264  1192  1192 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 08:35:44.264  1018  1047 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 08:35:44.264  1018  1047 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 08:35:44.264  1869  1877 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 08:35:44.264  1869  1877 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 08:35:44.264  1689  1700 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 08:35:44.264  1689  1700 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 08:35:44.264  2632  2645 D BluetoothA2dp: onBluetoothStateChange: up=true
03-17 08:35:44.264  1018  1047 D BluetoothA2dp: onBluetoothStateChange: up=true
03-17 08:35:44.264  1464  1683 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 08:35:44.264  1464  1683 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 08:35:44.274  2130  2146 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 08:35:44.274  2130  2146 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 08:35:44.274  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
03-17 08:35:44.274  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
03-17 08:35:44.274  2632  2632 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
03-17 08:35:44.274  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
03-17 08:35:44.274  1018  1018 I InputMethodManagerService: [BT Setting State] State =12
03-17 08:35:44.274  1018  1018 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
03-17 08:35:44.284  1192  1192 D BluetoothTile:  onBluetoothStateChange:
03-17 08:35:44.284  1443  1443 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3d6423e9, true
03-17 08:35:44.284  1443  1443 D BluetoothHeadset: registerMessageListener
03-17 08:35:44.284  1018  1042 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.BOOT_COMPLETED
03-17 08:35:44.284  1018  1042 W libprocessgroup: failed to open /acct/uid_10057/pid_1559/cgroup.procs: No such file or directory
03-17 08:35:44.284  1018  1042 D GpsLocationProvider_ex: BOOT_COMPLETED native_init 
03-17 08:35:44.284  1018  1042 D GpsLocationProvider: set_capabilities_callback: 55u
03-17 08:35:44.284  1192  1192 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
03-17 08:35:44.284  1192  1192 D BluetoothTile:  onBluetoothPairedDevicesChanged:
03-17 08:35:44.284  1192  1192 D BluetoothTile:  getBluetoothState : 12
03-17 08:35:44.284  2632  2712 D HeadsetService: registerMessageListener
03-17 08:35:44.294  2632  2712 D HeadsetService: registerMessageListener
03-17 08:35:44.294  2632  2711 D HeadsetStateMachine: Disconnected process message: 70
03-17 08:35:44.294  2632  2711 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1ffe545d
03-17 08:35:44.294  1443  1443 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
03-17 08:35:44.294  1443  1443 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
03-17 08:35:44.294  1018  1549 D qmi_secgps_clnt: qmi_secgps_client_init()
03-17 08:35:44.294  2632  2632 I BluetoothPbapService: Handler(): got msg=1
03-17 08:35:44.294  1906  1906 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
03-17 08:35:44.294  1018  1042 I libmdmdetect: ESOC framework not supported
03-17 08:35:44.304  1018  1030 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
03-17 08:35:44.304  1018  1042 I libmdmdetect: Found internal modem: modem
03-17 08:35:44.304  1018  1042 E PerMgrLib: Peripheral manager is not supported on this device
03-17 08:35:44.304  1018  1042 E Geofence_Adapter: I/===> void GeofenceAdapter::addGfClients(GeoFencer*) line 65 
03-17 08:35:44.304  1018  1042 E Geofence_Adapter: I/===> void GeofenceAdapter::updateRegisteredEvents() line 81 
03-17 08:35:44.304  1018  1042 D GpsLocationProvider_ex: BOOT_COMPLETED native_cleanup 
03-17 08:35:44.304  1443  1443 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
03-17 08:35:44.304  1443  1443 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
03-17 08:35:44.304  1443  1443 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
03-17 08:35:44.304  1018  1031 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
03-17 08:35:44.304  1018  1257 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
03-17 08:35:44.314  2632  2711 D HeadsetStateMachine: Disconnected process message: 9
03-17 08:35:44.314  2632  2711 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
03-17 08:35:44.314  1018  1549 D qmi_secgps_clnt: SECGPS: qmi_client_get_service_list() returned 0 num_services = 2
03-17 08:35:44.314  1018  1549 D qmi_secgps_clnt: SECGPS: qmi_client_get_service_list() returned 0 num_entries = 0 num_services = 2
03-17 08:35:44.314  1192  1732 D BluetoothTile:  handleUpdatestate:false name:null
03-17 08:35:44.314  1192  1192 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
03-17 08:35:44.324  1192  1192 D StorageNotification: boot completed
03-17 08:35:44.324  1018  1549 D qmi_secgps_clnt: SECGPS: qmi_client_get_service_list() returned 0 num_entries = 2 num_services = 2
03-17 08:35:44.324  2632  2852 V BluetoothPbapService: PBAP Service initSocket try: 0
03-17 08:35:44.324  2632  2853 D BluetoothMapMasInstance: set MAP SDP message type : 1
03-17 08:35:44.324  1192  1732 D BluetoothTile:  handleUpdatestate:false name:null
03-17 08:35:44.324   286   744 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
03-17 08:35:44.324   286   744 V voice   : voice_set_parameters: enter: A2dpSuspended=false
03-17 08:35:44.324   286   744 V voice   : voice_set_parameters: exit with code(-2)
03-17 08:35:44.324   286   744 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
03-17 08:35:44.324   286   744 V msm8974_platform: platform_set_parameters: exit with code(-2)
03-17 08:35:44.324   286   744 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
03-17 08:35:44.324   286   744 V audio_hw_primary: adev_set_parameters: exit
03-17 08:35:44.334  2632  2711 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
03-17 08:35:44.334  1192  1732 D BluetoothTile:  handleUpdatestate:false name:null
03-17 08:35:44.334  2632  2852 D BluetoothSocket: bindListen(): myUserId = 0
03-17 08:35:44.334  2632  2852 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-17 08:35:44.334  1018  2715 D SSRM:a  : DeviceInfo:: 000000000000
03-17 08:35:44.334  1018  2715 D SSRM:a  : SettingsAirViewInfo:: 000000000
03-17 08:35:44.334  2632  2852 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
03-17 08:35:44.334  2632  2852 D BluetoothSocket: bindListen(), new LocalSocket 
03-17 08:35:44.334  2632  2852 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-17 08:35:44.334  2632  2852 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d3319a0
03-17 08:35:44.334  2632  2852 D BluetoothSocket: channel: 19
03-17 08:35:44.334  2632  2852 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
03-17 08:35:44.334  2632  2853 D BluetoothSocket: bindListen(): myUserId = 0
03-17 08:35:44.334  2632  2853 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-17 08:35:44.334  2632  2853 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
03-17 08:35:44.334  2632  2853 D BluetoothSocket: bindListen(), new LocalSocket 
03-17 08:35:44.334  2632  2853 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-17 08:35:44.334  2632  2853 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1250d959
03-17 08:35:44.334  2632  2853 D BluetoothSocket: channel: 5
03-17 08:35:44.334   256   540 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
03-17 08:35:44.334   256   540 W Vold    : Returning OperationFailed - no handler for errno 0
03-17 08:35:44.344  2059  2840 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
03-17 08:35:44.364  1192  1192 D PhoneStatusBar: updateIcon slot=volume index=23 viewIndex=5 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
03-17 08:35:44.364  1018  1731 D StatusBarManagerService: setIcon slot=volume index=23 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
03-17 08:35:44.374  1018  1487 D ActivityManager: startProcessLocked calleePkgName: flipboard.boxer.app, hostingType: broadcast
03-17 08:35:44.374  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:44.374  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:44.374  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:44.374  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:44.384  2858  2858 E Zygote  : MountEmulatedStorage()
03-17 08:35:44.384  2858  2858 E Zygote  : v2
03-17 08:35:44.384  2858  2858 I libpersona: KNOX_SDCARD checking this for 10099
03-17 08:35:44.384  2844  2844 D AndroidRuntime: 
03-17 08:35:44.384  2844  2844 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-17 08:35:44.384  2858  2858 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:44.384  2858  2858 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 08:35:44.384  1018  1487 I ActivityManager: Start proc flipboard.boxer.app for broadcast flipboard.boxer.app/flipboard.boxer.receiver.BootCompleted: pid=2858 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 08:35:44.384  2844  2844 D AndroidRuntime: CheckJNI is OFF
03-17 08:35:44.394  2844  2844 D AndroidRuntime: readGMSProperty: start
03-17 08:35:44.394  2844  2844 D AndroidRuntime: readGMSProperty: already setted!!
03-17 08:35:44.394  2844  2844 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-17 08:35:44.394  2844  2844 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-17 08:35:44.394  2844  2844 D AndroidRuntime: readGMSProperty: end
03-17 08:35:44.394  2844  2844 D AndroidRuntime: addProductProperty: start
03-17 08:35:44.394  2858  2858 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 08:35:44.394  2858  2858 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 08:35:44.394  1018  1143 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.cache.DataUpdateListenerCacheService; callingUser = 0; userId(target) = 0
03-17 08:35:44.444  2858  2858 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 08:35:44.444  2858  2858 D ActivityThread: Added TimaKeyStore provider
03-17 08:35:44.444  1018  1549 E LocSvc_utils_cfg: W/loc_read_sec_gps_conf: no secgps conf file, using defaults
03-17 08:35:44.444  1018  1556 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
03-17 08:35:44.454  1018  1556 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
03-17 08:35:44.464  1018  1556 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SERVER_REQ_V02
03-17 08:35:44.464  1018  1549 I qmi_secgps_clnt: SECGPS: Set AGPS Mode : 7
03-17 08:35:44.464  1018  1549 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-17 08:35:44.464  1018  1556 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-17 08:35:44.464  1018  1549 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setSUPLVersion(uint32_t):1558]: supl version = 131072
03-17 08:35:44.474  1018  1556 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-17 08:35:44.474  1018  1549 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setAGLONASSProtocol(long unsigned int):1881]: aGlonassProtocolMask = 0x0
03-17 08:35:44.494  1018  1556 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-17 08:35:44.494  1018  1549 I qmi_secgps_clnt: SECGPS: Set XTRA enable : 1
03-17 08:35:44.494  1018  1549 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-17 08:35:44.494  1018  1549 I qmi_secgps_clnt: SECGPS: Set GNSS RF CONFIG : 1
03-17 08:35:44.494  1018  1549 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-17 08:35:44.494  1018  1549 I qmi_secgps_clnt: SECGPS: Set CERT TYPE : 15
03-17 08:35:44.494  1018  1549 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-17 08:35:44.494  1018  1549 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setLPPConfig(uint32_t):1605]: lpp profile = 0
03-17 08:35:44.544  2844  2844 E AffinityControl: AffinityControl: registerfunction enter
03-17 08:35:44.544  1018  1556 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-17 08:35:44.544  1018  1549 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1644]: sensors disabled = 1
03-17 08:35:44.544  1018  1556 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
03-17 08:35:44.544  1018  1556 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
03-17 08:35:44.554  1018  1549 E LocSvc_ApiV02: E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3316]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02
03-17 08:35:44.564  2844  2844 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-17 08:35:44.584  1018  1731 E PersonaManagerService: inState():  stateMachine is null !!
03-17 08:35:44.584  1018  1731 I PersonaManagerService: PersonaId don't exist
03-17 08:35:44.584  1018  1731 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-17 08:35:44.584   331   331 I ServiceManager: Waiting for service AtCmdFwd...
03-17 08:35:44.594  2059  2840 W DriveInitializer: Background init thread ended
03-17 08:35:44.594  1018  1731 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 08:35:44.604   302   302 E USB_UICC: Timeout! No signal received. Retry num = 29
03-17 08:35:44.614  1018  1731 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-17 08:35:44.614  1018  1731 W ActivityManager: mDVFSHelper.acquire()
03-17 08:35:44.614  1018  1731 D FocusedStackFrame: Set to : 0
03-17 08:35:44.624  1018  1731 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 08:35:44.624  1018  1731 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 08:35:44.624  1018  1731 D InputDispatcher: Focused application set to: xxxx
03-17 08:35:44.624  1018  1731 D InputDispatcher: Focus left window: 1491
03-17 08:35:44.624  1018  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 08:35:44.624  1018  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-17 08:35:44.624  1491  1491 D Launcher.HomeView: onPause
03-17 08:35:44.624  2844  2844 D AndroidRuntime: Shutting down VM
03-17 08:35:44.624  1491  1491 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-17 08:35:44.634  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-17 08:35:44.634  1018  1030 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
03-17 08:35:44.634  1018  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
03-17 08:35:44.634  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-17 08:35:44.634  1018  1018 I MotionRecognitionService: Plugged
03-17 08:35:44.634  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
03-17 08:35:44.634  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 08:35:44.634  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 08:35:44.634  1192  1192 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 08:35:44.634  1192  1192 D KeyguardUpdateMonitor: handleBatteryUpdate
03-17 08:35:44.634  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 08:35:44.634  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-17 08:35:44.644   257   257 I SurfaceFlinger: id=10 createSurf (1x1),1 flag=404, uhalitest
03-17 08:35:44.644  1428  1428 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 08:35:44.644  1192  1192 D PowerUI : Cable  true --> true mBootCompleted : true
03-17 08:35:44.644  1192  1192 D PowerUI : Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
03-17 08:35:44.644  1428  1428 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-17 08:35:44.654  2632  2632 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-17 08:35:44.654  2632  2711 D HeadsetStateMachine: Disconnected process message: 10
03-17 08:35:44.664  1660  1672 I art     : Explicit concurrent mark sweep GC freed 7249(359KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 743us total 26.542ms
03-17 08:35:44.664  1018  1731 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:44.664  1018  1731 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:44.664  1018  1731 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:44.664  1018  1731 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:44.684  2896  2896 E Zygote  : MountEmulatedStorage()
03-17 08:35:44.684  2896  2896 E Zygote  : v2
03-17 08:35:44.684  2896  2896 I libpersona: KNOX_SDCARD checking this for 10155
03-17 08:35:44.684  2896  2896 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:44.684  2896  2896 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 08:35:44.684  2896  2896 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 08:35:44.684  1018  1731 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2896 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-17 08:35:44.684  2896  2896 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 08:35:44.694  1192  1192 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 08:35:44.694  1192  1192 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 08:35:44.694  1192  1192 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 08:35:44.714  1491  1491 V ActivityThread: updateVisibility : ActivityRecord{3d541059 token=android.os.BinderProxy@35fc6267 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
03-17 08:35:44.724  2896  2896 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 08:35:44.734  2896  2896 D ActivityThread: Added TimaKeyStore provider
03-17 08:35:44.734  1018  1257 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 08:35:44.734  1018  1257 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-17 08:35:44.734  1018  1257 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 08:35:44.744  1491  1491 D Launcher.HomeView: onStop
03-17 08:35:44.744  1491  1491 V ActivityThread: updateVisibility : ActivityRecord{3d541059 token=android.os.BinderProxy@35fc6267 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-17 08:35:44.744  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-17 08:35:44.754  1018  1257 D PersonaManager: isKioskContainerExistOnDevice
03-17 08:35:44.774  1018  1490 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 08:35:44.774  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:44.774  1018  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 08:35:44.774  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 08:35:44.784  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-17 08:35:44.784  1018  1018 D SensorService: [SO] activate (ident=0xb96032c0, enabled=0)
03-17 08:35:44.784  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
03-17 08:35:44.794  1018  1018 D SensorManager: unregisterListener ::   
03-17 08:35:44.794  1018  1018 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
03-17 08:35:44.804  1018  1018 D SensorService: [SO] changed settle time [1]
03-17 08:35:44.804  1018  1018 D SensorService: [SO] setDelay [66000000]
03-17 08:35:44.804  1018  1018 D SensorService: [SO] activate (ident=0xb96032c0, enabled=1)
03-17 08:35:44.804  1018  1018 D SensorService: [SO] AR_init
03-17 08:35:44.804  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
03-17 08:35:44.804  1491  1491 D Launcher: onTrimMemory. Level: 20
03-17 08:35:44.804  1018  1018 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
03-17 08:35:44.814  1018  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
03-17 08:35:44.814  1018  1042 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.metadata.sync.syncadapter.SyncAdapterService; callingUser = 0; userId(target) = 0
03-17 08:35:44.844  2844  2844 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-17 08:35:44.854  1018  1257 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 08:35:44.854  1018  1257 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:35:44.854  1018  1257 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 08:35:44.854  1018  1257 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 08:35:44.854  1018  1734 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 08:35:44.854  1018  1734 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:44.854  1018  1734 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 08:35:44.854  1018  1734 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 08:35:44.874  1018  1040 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-17 08:35:44.884  2858  2858 E ActivityThread: Failed to find provider info for flipboard.auth.internal.debug
,03-17 08:35:44.884  2858  2858 E ActivityThread: Failed to find provider info for flipboard.auth.internal
,03-17 08:35:44.894  1018  1031 I splitIntent: Split this intent : android.intent.action.BOOT_COMPLETED, mSplitNum[0]=91, mSplitNum[1]=131, mSplitNum[2]=170, mBgSplitQueueNum=3 divideNum= 38 r.nextReceiver= 53 receivers.size=208
,03-17 08:35:44.894  1018  1031 I splitIntent: finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!
,03-17 08:35:44.894  1018  1018 I DrmEventReceiver: DrmEventReceiver : onReceive
,03-17 08:35:44.894  1018  1018 I DrmEventReceiver: DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
,03-17 08:35:44.904  1018  1018 I DrmEventReceiver: DrmEventReceiver : beginStartingService
,03-17 08:35:44.904  1018  1018 I System.out: start Service
,03-17 08:35:44.904  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.bluetoothtest, hostingType: broadcast
,03-17 08:35:44.904  1018  1018 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
03-17 08:35:44.904  2896  2896 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,03-17 08:35:44.904  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:44.914  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:44.914  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:44.914  1243  1243 V DownloadManager: onReceive intent + android.intent.action.BOOT_COMPLETED
03-17 08:35:44.914  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:44.924  2925  2925 E Zygote  : MountEmulatedStorage()
03-17 08:35:44.924  2925  2925 E Zygote  : v2
03-17 08:35:44.924  2925  2925 I libpersona: KNOX_SDCARD checking this for 1000
03-17 08:35:44.924  2925  2925 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:44.924  2925  2925 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 08:35:44.924  1018  1043 I ActivityManager: Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=2925 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 08:35:44.924  2925  2925 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 08:35:44.924  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
03-17 08:35:44.924  2925  2925 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 08:35:44.934  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:44.934  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:44.934  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:44.934  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,03-17 08:35:44.944  1018  1040 D SensorService: [SO] 0.134 0.421 10.132,
03-17 08:35:44.944  1018  1040 D SensorService: [SO] [100 -> 255]
,03-17 08:35:44.954  2936  2936 E Zygote  : MountEmulatedStorage()
03-17 08:35:44.954  2936  2936 E Zygote  : v2
03-17 08:35:44.954  2936  2936 I libpersona: KNOX_SDCARD checking this for 10152
03-17 08:35:44.954  2936  2936 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:44.954  2936  2936 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 08:35:44.954  2936  2936 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-17 08:35:44.954  2936  2936 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 08:35:44.954  1018  1043 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=2936 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
,03-17 08:35:44.964  1018  1143 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
03-17 08:35:44.964  1018  1143 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,03-17 08:35:44.964  1018  1143 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:44.964  1018  1143 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:35:44.964  1018  1143 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-17 08:35:44.964  2925  2925 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 08:35:44.964  2925  2925 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:44.974  1018  1018 D ActivityManager: startService callerProcessName:android, calleePkgName: android
03-17 08:35:44.974  1018  1018 D ActivityManager: retrieveServiceLocked(): component = android/com.android.server.DrmEventService; callingUser = 0; userId(target) = 0
,03-17 08:35:44.984   321   321 I art     : Explicit concurrent mark sweep GC freed 8738(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 632us total 28.011ms
,03-17 08:35:44.994  2936  2936 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:44.994  2936  2936 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:45.014   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 657us total 23.773ms
,03-17 08:35:45.014  2896  2896 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 6088-6093)
,03-17 08:35:45.014  2896  2896 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 08:35:45.024  2197  2197 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,03-17 08:35:45.024  1018  1731 I ActivityManager: Killing 1789:com.sec.android.widgetapp.samsungapps/u0a138 (adj 15): empty #31
03-17 08:35:45.024   285   524 D WVMDrmPlugIn: WVMDrmPlugin::onInitialize : 1920
03-17 08:35:45.024   285   524 D WVMDrmPlugIn: WVMDrmPlugin::onSetOnInfoListener : add 1920
,03-17 08:35:45.034   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 687us total 19.941ms
,03-17 08:35:45.034  1018  1031 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
03-17 08:35:45.034  1018  1031 D SecContentProvider2: mCursor = null
,03-17 08:35:45.034  1243  1243 D MediaScannerReceiver: action: android.intent.action.BOOT_COMPLETED
,03-17 08:35:45.044  1018  1734 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
,03-17 08:35:45.044  1018  1734 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,03-17 08:35:45.044  1018  1734 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:45.044  1018  1734 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:35:45.044  1018  1734 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-17 08:35:45.054  2925  2925 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 08:35:45.054  1018  1558 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
03-17 08:35:45.054  1018  1558 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,03-17 08:35:45.054  1018  1558 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:45.054  1018  1558 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:35:45.054  1018  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-17 08:35:45.054  1018  1018 I TimaServiceEventReceiver: TimaServiceEventReceiver : onReceive
,03-17 08:35:45.054  1018  2962 I DrmEventService: action event :android.intent.action.BOOT_COMPLETED
,03-17 08:35:45.064  2896  2896 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4bd1b36}
03-17 08:35:45.064  2896  2896 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-17 08:35:45.064  2896  2896 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
03-17 08:35:45.064   285   285 I ANDROID_DRM_FRWORKS_DrmManager: DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
03-17 08:35:45.064  2925  2925 D BluetoothBDAdrressReceiver: onReceive(), action: android.intent.action.BOOT_COMPLETED
03-17 08:35:45.074  1018  1042 W libprocessgroup: failed to open /acct/uid_10138/pid_1789/cgroup.procs: No such file or directory
03-17 08:35:45.074  2925  2925 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,03-17 08:35:45.084  1018  1558 D ActivityManager: startService callerProcessName:com.sec.android.app.bluetoothtest, calleePkgName: com.sec.android.app.bluetoothtest
,03-17 08:35:45.084  1018  1558 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.bluetoothtest/com.sec.android.app.bluetoothtest.BluetoothBDTestService; callingUser = 0; userId(target) = 0
,03-17 08:35:45.084  1018  1558 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:35:45.084  1018  1558 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 08:35:45.084  1018  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,03-17 08:35:45.094  1464  1464 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 08:35:45.104  2896  2896 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-17 08:35:45.114  1464  1464 D BluetoothBDTestService: onCreate()
,03-17 08:35:45.114  1464  1464 E BluetoothBDTestService: onStart(), extra_type: BOOT_COMPLETED
03-17 08:35:45.114  1464  1464 E BluetoothBDTestService: bd_address_path: /efs/bluetooth/bt_addr
,03-17 08:35:45.114  2896  2896 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 08:35:45.114  1464  1464 E BluetoothBDTestService: already exist!( /efs/bluetooth/bt_addr ), file length: 17
,03-17 08:35:45.114  2896  2896 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-17 08:35:45.114  1464  1464 E CscReceiver: onReceive android.intent.action.BOOT_COMPLETED
,03-17 08:35:45.114  1018  1734 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,03-17 08:35:45.114  1018  1734 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.114  1018  1734 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.114  1018  1734 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.114  1018  1734 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:45.134  2966  2966 E Zygote  : MountEmulatedStorage(),
03-17 08:35:45.134  2966  2966 I libpersona: KNOX_SDCARD checking this for 1000
03-17 08:35:45.134  2966  2966 E Zygote  : v2
03-17 08:35:45.134  2966  2966 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:45.134  2966  2966 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 08:35:45.144  2966  2966 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 08:35:45.144  2966  2966 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-17 08:35:45.144  1018  1734 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=2966 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 08:35:45.144  1018  1734 I ActivityManager: Killing 1507:com.android.printspooler/u0a136 (adj 15): empty #31,
,03-17 08:35:45.154  2936  2936 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,03-17 08:35:45.174  1018  1490 D ActivityManager: startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
03-17 08:35:45.174  1018  1490 D ActivityManager: retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,03-17 08:35:45.174  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:45.174  1018  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:35:45.174  1243  2963 D MediaScannerService: !@start scanning volume internal: [/system/media, /oem/media]
03-17 08:35:45.174  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,03-17 08:35:45.184  2896  2896 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
03-17 08:35:45.184  2896  2896 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
03-17 08:35:45.184  2896  2896 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,03-17 08:35:45.184  1018  1734 I ActivityManager: Killing 1689:com.google.android.apps.maps/u0a107 (adj 15): empty #31
,03-17 08:35:45.184  2896  2896 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 08:35:45.184  2896  2896 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 08:35:45.184  2896  2896 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 08:35:45.184  2896  2896 I Adreno-EGL: Local Branch: 
03-17 08:35:45.184  2896  2896 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 08:35:45.184  2896  2896 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 08:35:45.184  2896  2896 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 08:35:45.194  2966  2966 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:45.194  2966  2966 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:45.194  1018  1734 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.providers.context, hostingType: broadcast
,03-17 08:35:45.194  1018  1734 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:45.194  1018  1734 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:45.194  1018  1734 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.194  1018  1734 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:45.204  1464  1464 D CscUpdateService: onStart
,03-17 08:35:45.204  1464  1464 E CscUpdateService: costomer file is exists : it has been preconfiged.
,03-17 08:35:45.204  1464  1464 I CscUpdateService: set_CSC_version
,03-17 08:35:45.204  1464  1464 E CscParser: update(): xml file exist
,03-17 08:35:45.214  2983  2983 E Zygote  : MountEmulatedStorage()
03-17 08:35:45.214  2983  2983 I libpersona: KNOX_SDCARD checking this for 10003
03-17 08:35:45.214  2983  2983 E Zygote  : v2
03-17 08:35:45.214  2983  2983 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:45.214   257   449 I SurfaceFlinger: id=9 Removed Mauncher (5/8)
,03-17 08:35:45.224   257   444 I SurfaceFlinger: id=9 Removed Mauncher (-2/8)
,03-17 08:35:45.224  2983  2983 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 08:35:45.224  2983  2983 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 08:35:45.224  2983  2983 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 08:35:45.234  1018  1734 I ActivityManager: Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=2983 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,03-17 08:35:45.244  1018  1731 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
03-17 08:35:45.244  1018  1731 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,03-17 08:35:45.254  1018  1731 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:45.254  1018  1731 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:35:45.254  1018  1731 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,03-17 08:35:45.254  1018  1506 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
03-17 08:35:45.254  1018  1506 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,03-17 08:35:45.254  1018  1506 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:45.254  1018  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:35:45.254  1018  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-17 08:35:45.254  1464  1464 I CscUtil : isWifiOnly = false
,03-17 08:35:45.264  1464  1464 I System.out: HandDataNode = null
,03-17 08:35:45.264  1464  1464 I CscUpdateService: PATH_CSCNAME =CustomerDataSet.CSCName
,03-17 08:35:45.264  1464  1464 I CscUpdateService: This is normal boot : CSC not updated
,03-17 08:35:45.274  1018  1734 D ActivityManager: startProcessLocked calleePkgName: org.simalliance.openmobileapi.service, hostingType: broadcast
,03-17 08:35:45.274  1018  1734 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:45.284  1243  1243 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
03-17 08:35:45.284  1018  1734 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.284  1018  1734 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:45.284  1018  1734 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:45.284  2966  2966 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 08:35:45.294  2983  2983 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:45.294  2983  2983 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:45.294  3014  3014 E Zygote  : MountEmulatedStorage(),
03-17 08:35:45.294  3014  3014 E Zygote  : v2
03-17 08:35:45.294  3014  3014 I libpersona: KNOX_SDCARD checking this for 1101
03-17 08:35:45.294  3014  3014 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:45.294  3014  3014 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 08:35:45.304  3014  3014 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 08:35:45.304  3014  3014 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 08:35:45.304  1018  1734 I ActivityManager: Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=3014 uid=1101 gids={41101, 9997} abi=armeabi-v7a
,03-17 08:35:45.314  1464  3009 E CscParser: update(): xml file exist
,03-17 08:35:45.314  1464  3009 D CscGPS  : CSCGPS.updateParameters
03-17 08:35:45.314  1464  3009 D CscGPS  : supl host : null
03-17 08:35:45.314  1464  3009 D CscGPS  : SUPL Host is null or invalid
03-17 08:35:45.314  1464  3009 D CscGPS  : supl_ver : null
03-17 08:35:45.314  1464  3009 D CscGPS  : SUPL Ver is null or invalid
03-17 08:35:45.314  1464  3009 D CscGPS  : supl port : null
03-17 08:35:45.314  1464  3009 D CscGPS  : SUPL PORT is null or invalid
03-17 08:35:45.314  1464  3009 D CscGPS  : LPP : null
03-17 08:35:45.314  1464  3009 D CscGPS  : LPP is null or invalid
03-17 08:35:45.314  1464  3009 D CscGPS  : CSC don't have any AGPS value.
,03-17 08:35:45.334  3014  3014 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:45.334  3014  3014 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:45.344  1464  1683 D TP/MmsProvider: Update uri=content://mms, match=0
,03-17 08:35:45.344  1018  1042 W libprocessgroup: failed to open /acct/uid_10136/pid_1507/cgroup.procs: No such file or directory
03-17 08:35:45.344  1018  1042 W libprocessgroup: failed to open /acct/uid_10107/pid_1689/cgroup.procs: No such file or directory
,03-17 08:35:45.344  1464  1683 D TP/MmsProvider: update , handleReadChangedBroadcast
03-17 08:35:45.344  1464  1683 D TP/MmsSmsProvider: need read changed broadcast:false
,03-17 08:35:45.354  2342  2342 I Mms:transaction: [MmsSystemEventReceiver] restorePduNotificationStatus count=0
,03-17 08:35:45.354  2342  2342 D Mms/MessagingNotification: [start]    nonBlockingUpdateMessageIndicator() consume time = 3811.753697
03-17 08:35:45.354  1464  1464 I CscUpdateService: same CSC Version
03-17 08:35:45.354  1464  1464 D CscUtil : Set Build Fingerprint to samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
,03-17 08:35:45.354  2342  2342 I Mms/ReservationManager: resetAfterConnected()
,03-17 08:35:45.364  3014  3014 W ResourcesManager: Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
,03-17 08:35:45.364  1464  1481 D TP/MmsSmsProvider: query,matched:7, calling pid = 2342
,03-17 08:35:45.364  1464  1481 D TP/MmsSmsProvider: match 7:Elapsed time : 6.030 ms
,03-17 08:35:45.364  1018  1731 D PersonaManagerService: getPersonasForUser(): returning null!
,03-17 08:35:45.374  3014  3014 V SmartcardService: main Received broadcast
03-17 08:35:45.374  3014  3014 V SmartcardService: Starting smartcard service after boot completed
,03-17 08:35:45.374  1018  1487 D ActivityManager: startService callerProcessName:org.simalliance.openmobileapi.service, calleePkgName: org.simalliance.openmobileapi.service
,03-17 08:35:45.374  1018  1487 D ActivityManager: retrieveServiceLocked(): component = org.simalliance.openmobileapi.service/org.simalliance.openmobileapi.service.SmartcardService; callingUser = 0; userId(target) = 0
,03-17 08:35:45.374  2342  3031 D Mms/MessagingNotification: sDisableVibrateForCamera = false
03-17 08:35:45.374  2342  3031 D Mms/TelephonyPermission: isDefault true
03-17 08:35:45.374  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:45.374  1018  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:35:45.374  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
,03-17 08:35:45.384  1243  2963 E SQLiteLog: (283) recovered 298 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
,03-17 08:35:45.384  2342  2342 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,03-17 08:35:45.384  1464  1740 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2342
,03-17 08:35:45.424  2966  2966 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,03-17 08:35:45.424  2966  3034 I KnoxUsageLogPro: savePreference: key = previous_sys_time value = 1458200145429
,03-17 08:35:45.454  2966  3034 I KnoxUsageLogPro: savePreference: key = previous_elapsed_time value = 36504
,03-17 08:35:45.484  2896  3002 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,03-17 08:35:45.564  1018  1490 I art     : Explicit concurrent mark sweep GC freed 164326(9MB) AllocSpace objects, 38(3MB) LOS objects, 33% free, 26MB/39MB, paused 2.506ms total 181.479ms
03-17 08:35:45.564  1018  1490 D ActivityManager: bindService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.gms, action: null
03-17 08:35:45.564  1018  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,03-17 08:35:45.564  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:45.564  1018  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 08:35:45.564  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,03-17 08:35:45.574  1018  1734 D ActivityManager: startService callerProcessName:com.android.phone, calleePkgName: com.android.stk
,03-17 08:35:45.574  1018  1734 D ActivityManager: retrieveServiceLocked(): component = com.android.stk/com.android.stk.StkAppService; callingUser = 0; userId(target) = 0
,03-17 08:35:45.574  1243  2963 D MediaScanner: Prescan. DB items number : 141 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,03-17 08:35:45.574  2966  2966 I KnoxUsageLogPro: premStatus:2
,03-17 08:35:45.574  1018  1734 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:45.574  1018  1734 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:35:45.574  1018  1734 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,03-17 08:35:45.584  1018  1346 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,03-17 08:35:45.584  2966  2966 I KnoxUsageLogPro: isEulaShown : false
03-17 08:35:45.584  2966  2966 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,03-17 08:35:45.584  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:45.584  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.584  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.584  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:45.594   331   331 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 08:35:45.604  3040  3040 E Zygote  : MountEmulatedStorage(),
03-17 08:35:45.604  3040  3040 I libpersona: KNOX_SDCARD checking this for 10157
,03-17 08:35:45.604  3040  3040 E Zygote  : v2
03-17 08:35:45.604  3040  3040 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:45.604   302   302 E USB_UICC: Timeout! No signal received. Retry num = 30
03-17 08:35:45.604  3040  3040 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 08:35:45.604  3040  3040 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 08:35:45.604  1018  1346 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=3040 uid=10157 gids={50157, 9997} abi=armeabi-v7a
03-17 08:35:45.604  3040  3040 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 08:35:45.604  1018  1257 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
03-17 08:35:45.604  1018  1257 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
,03-17 08:35:45.604  1018  1257 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:45.604  1018  1257 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:35:45.604  1018  1257 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,03-17 08:35:45.614  1018  1490 D ActivityManager: startService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.samsung.android.providers.context
03-17 08:35:45.614  1018  1490 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
,03-17 08:35:45.614  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:45.614  1018  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:35:45.614  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,03-17 08:35:45.614  1018  1490 I ActivityManager: Killing 2130:com.vlingo.midas/u0a31 (adj 15): empty #31
,03-17 08:35:45.624  1018  1346 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,03-17 08:35:45.624  2983  3042 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,03-17 08:35:45.634  3040  3040 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:45.634  3040  3040 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:45.634  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.634  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:45.634  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,03-17 08:35:45.634  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:45.644  2983  3042 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,03-17 08:35:45.644   399   399 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 10003, gid 10003, pid 2983
03-17 08:35:45.644   399   399 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
03-17 08:35:45.644  2983  3042 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running,
03-17 08:35:45.644  2983  3042 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
03-17 08:35:45.654   399   399 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 10003, gid 10003, pid 2983
03-17 08:35:45.654   399   399 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,03-17 08:35:45.654  1243  2963 V MediaScanner: processDirectory :  /system/media
,03-17 08:35:45.654  2896  2896 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 08:35:45.654  3058  3058 E Zygote  : MountEmulatedStorage()
03-17 08:35:45.654  3058  3058 E Zygote  : v2
,03-17 08:35:45.654  3058  3058 I libpersona: KNOX_SDCARD checking this for 10085
,03-17 08:35:45.654  3058  3058 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:45.654  3058  3058 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 08:35:45.654  1018  1346 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=3058 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 08:35:45.664  3058  3058 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-17 08:35:45.664  1018  1031 D ActivityManager: startService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.samsung.android.providers.context
03-17 08:35:45.664  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
03-17 08:35:45.664  3058  3058 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 08:35:45.664  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:45.664  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:35:45.664  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,03-17 08:35:45.674  1018  1346 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.safetyassurance, hostingType: broadcast
,03-17 08:35:45.674  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.674  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.674  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.674  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:45.674  1464  1481 D TP/MmsSmsProvider: query,matched:200, calling pid = 2342
,03-17 08:35:45.674  1464  1481 D TP/MmsSmsProvider: match 200:Elapsed time : 3.175 ms
,03-17 08:35:45.684  2896  2896 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-17 08:35:45.694  3075  3075 E Zygote  : MountEmulatedStorage()
,03-17 08:35:45.694  3075  3075 E Zygote  : v2
03-17 08:35:45.694  3075  3075 I libpersona: KNOX_SDCARD checking this for 10048
03-17 08:35:45.694  3075  3075 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:45.694  3075  3075 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 08:35:45.694  3075  3075 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 08:35:45.694  1018  1346 I ActivityManager: Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=3075 uid=10048 gids={50048, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-17 08:35:45.694  3075  3075 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 08:35:45.704  3058  3058 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 08:35:45.704  3058  3058 D ActivityThread: Added TimaKeyStore provider
03-17 08:35:45.704  1243  2963 V MediaScanner:  prescan time: 362ms (DB items: 141)
03-17 08:35:45.704  1243  2963 V MediaScanner:     scan time: 66ms (Caching mode: true), (makeEntry time: 26ms ~39%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-17 08:35:45.704  1243  2963 V MediaScanner: postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-17 08:35:45.704  1243  2963 V MediaScanner:    total time: 428ms
03-17 08:35:45.704   302   302 E USB_UICC: Timeout! No signal received. Reach maximum retries!
03-17 08:35:45.704  1243  2963 V MediaScanner: checked files: 133  directories : 6  (I: 0, U: 0)
03-17 08:35:45.704   302   302 E USB_UICC: usb_uicc_init_qmi failed ! 
03-17 08:35:45.704   302   302 I USB_UICC: usb_uicc_cleanup, signal received: 0x3 
03-17 08:35:45.704   302   302 I USB_UICC: usb_uicc_cleanup, Issuing QMI deinit ... 
,03-17 08:35:45.704  1243  2963 D MediaScanner: checkDefaultSounds
03-17 08:35:45.704  1243  2963 D MediaScanner: system alarm_alert  : Vwiurug_etwofi5wgg
,03-17 08:35:45.704  2896  2896 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 08:35:45.704  2896  2896 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-17 08:35:45.704  1243  2963 D MediaScanner: OK. alarm_alert is already exist in setting DB.,
,03-17 08:35:45.714  1243  2963 D MediaScanner: system notification_sound  : K_Oprkltf5wgg
03-17 08:35:45.714  3040  3040 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 08:35:45.714  1018  1346 D ActivityManager: startProcessLocked calleePkgName: com.sec.dsm.system, hostingType: broadcast
,03-17 08:35:45.714  2896  2896 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-17 08:35:45.724  2342  2342 D Mms/SmsReceiverService: onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
,03-17 08:35:45.724  2342  3064 D Mms/TelephonyPermission: isDefault true
03-17 08:35:45.724  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.724  2342  3064 D Mms/SmsReceiverService: [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
03-17 08:35:45.724  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.724  2342  3064 D Mms/SmsReceiverService: [start]    handleBootCompleted() consume time = 372.240052
03-17 08:35:45.724  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.724  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:45.724  1243  2963 D MediaScanner: OK. notification_sound is already exist in setting DB.
,03-17 08:35:45.734  1243  2963 D MediaScanner: system ringtone  : Wmfi_lpf_pwirywu5wgg
,03-17 08:35:45.734  1243  2963 D MediaScanner: OK. ringtone is already exist in setting DB.
,03-17 08:35:45.744  3075  3075 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:45.744  3075  3075 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:45.744  3095  3095 E Zygote  : MountEmulatedStorage()
03-17 08:35:45.744  3095  3095 I libpersona: KNOX_SDCARD checking this for 1000
03-17 08:35:45.744  3095  3095 E Zygote  : v2
03-17 08:35:45.744  3095  3095 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:45.754  3095  3095 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 08:35:45.754  1018  1346 I ActivityManager: Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=3095 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 08:35:45.764  3095  3095 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 08:35:45.764  1018  1042 W libprocessgroup: failed to open /acct/uid_10031/pid_2130/cgroup.procs: No such file or directory
,03-17 08:35:45.764  3095  3095 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 08:35:45.764  2896  2896 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 08:35:45.764  2896  2896 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 08:35:45.764  3058  3058 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 08:35:45.764  3058  3058 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 08:35:45.764  3058  3058 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 08:35:45.764  3058  3058 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 08:35:45.764  3058  3058 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 08:35:45.764  3058  3058 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,03-17 08:35:45.774  1018  1346 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,03-17 08:35:45.774  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.774  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.774  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.774  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:45.784  1464  1484 D TP/MmsSmsProvider: getThreadUnReadCount unreadCount=0 imUnreadCount=0
,03-17 08:35:45.794  1243  2963 D MediaScannerService: !@done scanning volume internal
,03-17 08:35:45.794  1464  1484 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775806
,03-17 08:35:45.794  3095  3095 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 08:35:45.794  1464  1484 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
03-17 08:35:45.794  1464  1484 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775806
,03-17 08:35:45.804  1464  1484 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,03-17 08:35:45.804  1464  1484 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 08:35:45.804  1464  1484 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 08:35:45.804  1464  1484 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 08:35:45.804  1464  1484 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 08:35:45.804  1464  1484 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 08:35:45.804  1464  1484 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-17 08:35:45.804  3095  3095 D ActivityThread: Added TimaKeyStore provider
03-17 08:35:45.804  3114  3114 I libpersona: KNOX_SDCARD checking this for 10159
03-17 08:35:45.804  3114  3114 E Zygote  : MountEmulatedStorage()
03-17 08:35:45.804  3114  3114 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:45.804  3114  3114 E Zygote  : v2
03-17 08:35:45.804  1018  1346 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=3114 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 08:35:45.804  3114  3114 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 08:35:45.814  1018  1346 I ActivityManager: Killing 2159:com.sec.android.app.videoplayer/u0a50 (adj 15): empty #31,
,03-17 08:35:45.814  3114  3114 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 08:35:45.814  3114  3114 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
03-17 08:35:45.814  1464  1484 D TP/MmsSmsProvider: delete threadId: 9223372036854775806
03-17 08:35:45.814  1464  1484 D TP/MmsSmsProvider: need read changed broadcast:false
,03-17 08:35:45.824  1192  1192 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 08:35:45.824  1192  1192 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 08:35:45.824  1192  1192 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 08:35:45.824  1192  1192 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 08:35:45.824  1192  1192 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 08:35:45.824  1192  1192 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 08:35:45.824  1243  2963 D MediaScannerService: !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,03-17 08:35:45.834  3075  3075 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-17 08:35:45.834  3075  3075 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 08:35:45.834  3075  3075 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,03-17 08:35:45.844  3114  3114 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:45.844  2595  2595 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2595) action= = android.intent.action.MEDIA_SCANNER_FINISHED
03-17 08:35:45.844  2595  2595 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2595) ACTION_MEDIA_SCANNER_FINISHED = /system/media
03-17 08:35:45.844  2595  2595 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2595) ACTION_MEDIA_SCANNER_FINISHED = Ignored
03-17 08:35:45.844  3114  3114 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:45.844  2342  3064 D Mms/Conversation: deleteTempConversation(),deleted=0
,03-17 08:35:45.864  1464  1683 D TP/SmsProvider: query,matched:0, calling pid = 2342
,03-17 08:35:45.864  1464  1683 D TP/SmsProvider: match 0:Elapsed time : 1.581 ms
,03-17 08:35:45.874  2896  3130 D OpenGLRenderer: Render dirty regions requested: true
,03-17 08:35:45.874  1243  2963 D MediaProvider: savePlaylistTableInBulkDeleter started
,03-17 08:35:45.874  1464  1481 D SmsProvider: Update uri=content://sms/outbox, match=8
,03-17 08:35:45.884  1464  1484 D TP/SmsProvider: query,matched:51, calling pid = 2342
,03-17 08:35:45.884  1018  1558 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,03-17 08:35:45.884  1018  1558 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 08:35:45.884  1018  1558 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-17 08:35:45.884  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-17 08:35:45.884  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,03-17 08:35:45.884  1243  2963 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,03-17 08:35:45.884  1464  1481 D TP/MmsSmsProvider: need read changed broadcast:false
,03-17 08:35:45.894  1018  1042 W libprocessgroup: failed to open /acct/uid_10050/pid_2159/cgroup.procs: No such file or directory
,03-17 08:35:45.894  2896  2896 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 08:35:45.894  2896  2896 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-17 08:35:45.894  2342  3064 D Mms/SmsReceiverService: moveOutboxMessagesToFailedBox messageCount: 0
,03-17 08:35:45.894  2342  3064 D Mms/SmsReceiverService: handle boot completed, sendFirstQueuedMessage()
03-17 08:35:45.894  2342  3064 D Mms/SmsReceiverService: [SIM-1]sendFirstQueuedMessage()
,03-17 08:35:45.904   257   257 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, NainActivit
,03-17 08:35:45.904  1464  1484 D TP/SmsProvider: match 51:Elapsed time : 21.418 ms
,03-17 08:35:45.914  1464  1683 D TP/SmsProvider: query,matched:26, calling pid = 2342
,03-17 08:35:45.914  1018  1257 I ActivityManager: Killing 2249:com.google.android.apps.magazines/u0a113 (adj 15): empty #31
,03-17 08:35:45.914  1464  1683 D TP/SmsProvider: match 26:Elapsed time : 4.783 ms
,03-17 08:35:45.924  2342  3031 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
,03-17 08:35:45.924  1018  1143 D InputDispatcher: Focus entered window: 2896
,03-17 08:35:45.924  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 08:35:45.924  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 08:35:45.924  2896  2896 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-17 08:35:45.924  2896  3130 I OpenGLRenderer: Initialized EGL, version 1.4
,03-17 08:35:45.934  2896  3130 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-17 08:35:45.934  2896  3130 D OpenGLRenderer: Enabling debug mode 0
,03-17 08:35:45.934  3114  3114 I Intent to TravelDirActivity: inside TravelBroadcastReceiver
,03-17 08:35:45.944  1576  1584 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,03-17 08:35:45.954  1018  1490 D ActivityManager: startProcessLocked calleePkgName: com.sec.usbsettings, hostingType: broadcast
,03-17 08:35:45.954  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.954  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.954  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:45.954  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:45.954  2342  3064 D Mms/SmsReceiver: unregisterForServiceStateChanges, already unregistered
03-17 08:35:45.954  2342  3064 D Mms/MessagingNotification: sDisableVibrateForCamera = false
03-17 08:35:45.954  2342  3064 D Mms/TelephonyPermission: isDefault true
,03-17 08:35:45.964  3134  3134 E Zygote  : MountEmulatedStorage()
03-17 08:35:45.964  3134  3134 E Zygote  : v2
03-17 08:35:45.964  3134  3134 I libpersona: KNOX_SDCARD checking this for 1000
03-17 08:35:45.964  3134  3134 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:45.974  3134  3134 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 08:35:45.974  1018  1490 I ActivityManager: Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=3134 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 08:35:45.974  3134  3134 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 08:35:45.974  3134  3134 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 08:35:45.974  1018  1734 D SettingsProvider: name = block_emergency_message
03-17 08:35:45.974  1018  1734 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 08:35:45.974  1018  1734 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 08:35:45.974  1018  1734 D SettingsProvider: selectionArgs: false
03-17 08:35:45.974  1018  1734 D SettingsProvider: selectionArgs: 10048
03-17 08:35:45.974  1018  1734 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 08:35:45.974  1018  1734 D SettingsProvider: ret = -1
,03-17 08:35:45.984  1018  1030 W ActivityManager: getTasks: caller 10048 is using old GET_TASKS but privileged; allowing
,03-17 08:35:45.984  1018  1346 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 08:35:45.984  1018  1031 I ActivityManager: Killing 1643:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,03-17 08:35:45.994  1018  3148 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 08:35:46.004  1192  1192 I StatusBar: Icon Only
,03-17 08:35:46.004  1192  1192 D PanelView: There is/are notification(s) 
,03-17 08:35:46.004  3134  3134 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:46.004  3134  3134 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:46.014  1018  1048 I ActivityManager: Displayed Component not be shown by security: +1s353ms
,03-17 08:35:46.014  2896  2896 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2cc686c3 time:37095
,03-17 08:35:46.014  1464  1740 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2342
,03-17 08:35:46.014  1906  1906 I SamsungIME: getCurrentCandidateView
,03-17 08:35:46.024  1018  1048 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,03-17 08:35:46.024  1018  1048 W ActivityManager: mDVFSHelper.release()
03-17 08:35:46.024  1018  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{26b1821c u0 com.test.thalitest/.MainActivity t12} time:37104
03-17 08:35:46.024  1018  1043 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-17 08:35:46.034  3095  3095 E SQLiteLog: (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
,03-17 08:35:46.034  1576  1584 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-17 08:35:46.034  1576  1584 D BadgeProvider: sendNotify, [notify] : null
03-17 08:35:46.034  1576  1584 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-17 08:35:46.034  1576  1584 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 08:35:46.034  1576  1584 D BadgeProvider: update, [UpdateCount] : 1
03-17 08:35:46.034  1491  1491 D Launcher.Model: reloadBadges entered.
,03-17 08:35:46.044  2342  3031 D Mms/MessagingNotification: setBadgeCount(), count=0
,03-17 08:35:46.054  2342  3031 D Mms/MessagingNotification: remove alarm
,03-17 08:35:46.054  1018  1042 W libprocessgroup: failed to open /acct/uid_10113/pid_2249/cgroup.procs: No such file or directory
03-17 08:35:46.054  1018  1042 W libprocessgroup: failed to open /acct/uid_10015/pid_1643/cgroup.procs: No such file or directory
,03-17 08:35:46.054  1018  1346 D ActivityManager: startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
,03-17 08:35:46.064  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.064  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.064  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.064  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:46.064  1464  1770 D TP/SmsProvider: query,matched:0, calling pid = 2342
,03-17 08:35:46.074  1464  1770 D TP/SmsProvider: match 0:Elapsed time : 8.753 ms
,03-17 08:35:46.074  3156  3156 E Zygote  : MountEmulatedStorage()
03-17 08:35:46.074  3156  3156 E Zygote  : v2
03-17 08:35:46.074  3156  3156 I libpersona: KNOX_SDCARD checking this for 10160
03-17 08:35:46.074  3156  3156 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:46.074  3156  3156 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 08:35:46.084  1243  2963 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty,
03-17 08:35:46.084  1243  2963 D MediaProvider: savePlaylistTableInBulkDeleter finished
03-17 08:35:46.084  1018  1346 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=3156 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
03-17 08:35:46.084  1243  2963 D MediaProvider: savePlaylistTableInBulkDeleter started
,03-17 08:35:46.084  1018  1490 I ActivityManager: Killing 2327:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
03-17 08:35:46.084  1243  2963 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
03-17 08:35:46.084  1243  2963 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
03-17 08:35:46.084  1243  2963 D MediaProvider: savePlaylistTableInBulkDeleter finished
,03-17 08:35:46.084  3156  3156 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 08:35:46.084  3156  3156 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 08:35:46.094  2342  3153 D Mms/MessagingNotification: updateAllHistoryAsRead()
,03-17 08:35:46.094  1243  2963 D MediaScanner: Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,03-17 08:35:46.094  2342  3031 D Mms/MessagingNotification: [end]    nonBlockingUpdateMessageIndicator() consume time = 373.805052
,03-17 08:35:46.104  3156  3156 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:46.114  3156  3156 D ActivityThread: Added TimaKeyStore provider
03-17 08:35:46.124  1018  1490 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,03-17 08:35:46.124  1018  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.wifi.WifiCredService; callingUser = 0; userId(target) = -2
,03-17 08:35:46.124  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:46.124  1018  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:35:46.124  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,03-17 08:35:46.124  1243  2963 V MediaScanner: processDirectory :  /storage/emulated/0
,03-17 08:35:46.134  1338  1338 I WifiCredService: onCreate
,03-17 08:35:46.134  1243  2963 D MediaScanner: Skipping:
03-17 08:35:46.134  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_2327/cgroup.procs: No such file or directory
03-17 08:35:46.134  1243  2963 D MediaScanner: 7klwibgf7fvntblfd7(75ebcf7
,03-17 08:35:46.134  1243  2963 D MediaScanner: Skipping:
03-17 08:35:46.134  1243  2963 D MediaScanner: 7klwibgf7fvntblfd7(7Budiwrd7dblb7
03-17 08:35:46.134  3156  3156 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 08:35:46.144  1243  2963 V MediaScanner: processDirectory :  /storage/extSdCard
03-17 08:35:46.144  1243  2963 W MediaScanner: Error opening directory, reason : Permission denied.
03-17 08:35:46.144  1243  2963 W MediaScanner: 7klwibgf7fxlKdCbid7
,03-17 08:35:46.144  1243  2963 V MediaScanner:  prescan time: 38ms (DB items: 27)
03-17 08:35:46.144  1243  2963 V MediaScanner:     scan time: 21ms (Caching mode: true), (makeEntry time: 17ms ~80%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-17 08:35:46.144  1243  2963 V MediaScanner: postscan time: 2ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-17 08:35:46.144  1243  2963 V MediaScanner:    total time: 61ms
03-17 08:35:46.144  1243  2963 V MediaScanner: checked files: 10  directories : 17  (I: 0, U: 0)
,03-17 08:35:46.154  2595  2595 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2595) action= = android.intent.action.MEDIA_SCANNER_FINISHED
03-17 08:35:46.154  1243  2963 D MediaScannerService: !@done scanning volume external
03-17 08:35:46.154  2595  2595 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2595) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
03-17 08:35:46.154  2595  2595 D FactoryTestApp: [DummyFtClient$sendBootCompletedAndFinish](2595) ...
03-17 08:35:46.154  2595  2595 D FactoryTestApp: [Support$Values.getString](2595) id=MODEL_COMMUNICATION_MODE, value=gsm
03-17 08:35:46.154  2595  2595 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2595) mConnectionMode = gsm
,03-17 08:35:46.164  2595  2595 D FactoryTestApp: [IPCWriterToSecPhoneService$ResponseWriter](2595) Create IPCWriterToSecPhoneService
03-17 08:35:46.164  2595  2595 I FactoryTestApp: [IPCWriterToSecPhoneService$connectToSecPhoneService](2595)  
,03-17 08:35:46.164  2595  2595 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
,03-17 08:35:46.164  1018  1490 D ActivityManager: bindService callerProcessName:com.sec.factory, calleePkgName: com.sec.phone, action: null
03-17 08:35:46.164  1338  1338 D WifiTimerReceiver: action: android.intent.action.BOOT_COMPLETED
03-17 08:35:46.164  1018  1490 D ActivityManager: retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
03-17 08:35:46.164  1338  1338 D WifiTimerReceiver: extra: Bundle[mParcelledData.dataSize=84]
03-17 08:35:46.164  1338  1338 D MY_TAG  : Action boot completed received
03-17 08:35:46.164  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:46.164  1018  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:35:46.164  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
03-17 08:35:46.164  1338  1338 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,03-17 08:35:46.174  1018  1133 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
03-17 08:35:46.174  1018  1133 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
03-17 08:35:46.174  1018  1133 E WifiNative-wlan0: invaild command id : 215
,03-17 08:35:46.184  1018  1096 V AlarmManager: waitForAlarm result :8
,03-17 08:35:46.184  1018  1096 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 08:35:46.184  1464  1683 I art     : Explicit concurrent mark sweep GC freed 40306(2MB) AllocSpace objects, 11(176KB) LOS objects, 40% free, 7MB/13MB, paused 936us total 85.815ms
,03-17 08:35:46.194  1464  1683 D TP/MmsSmsProvider: query,matched:200, calling pid = 2342
,03-17 08:35:46.194  2595  2595 I FactoryTestApp: [IPCWriterToSecPhoneService$onServiceConnected](2595) connected done
03-17 08:35:46.194  2595  2595 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2595) Send Response Message to SecPhone
03-17 08:35:46.194  2595  2595 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2595) Response ��
,03-17 08:35:46.194  3095  3095 D DSM     : [Lines:107] Normal booted
,03-17 08:35:46.194  3095  3095 D DSM     : [Lines:114] Boot completed
,03-17 08:35:46.204  1464  1683 D TP/MmsSmsProvider: match 200:Elapsed time : 9.024 ms
,03-17 08:35:46.204  1018  1257 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.factorykeystring, hostingType: broadcast
,03-17 08:35:46.204  1018  1257 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.204  1018  1257 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.204  1018  1257 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.204  1018  1257 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:46.224  3178  3178 E Zygote  : MountEmulatedStorage(),
03-17 08:35:46.224  3178  3178 E Zygote  : v2
,03-17 08:35:46.224   325  1075 D AT_Distributor: Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
03-17 08:35:46.224  1018  1257 I ActivityManager: Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=3178 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 08:35:46.224  3178  3178 I libpersona: KNOX_SDCARD checking this for 1000
03-17 08:35:46.224  3178  3178 I libpersona: KNOX_SDCARD not a persona,
03-17 08:35:46.224  3178  3178 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 08:35:46.224  2595  2595 D FactoryTestApp: [IPCWriterToSecPhoneService$handleMessage](2595) Send BOOTING COMPLETED done
,03-17 08:35:46.234  3178  3178 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 08:35:46.234  3178  3178 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 08:35:46.234  2813  2917 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 08:35:46.234   257  1868 I SurfaceFlinger: id=10 Removed uhalitest (7/8),
,03-17 08:35:46.254  1338  1338 D NearbySettings: MountReceiver.onReceive - Create HandlerThread
03-17 08:35:46.254  1338  1338 D NearbySettings: MountReceiver.onReceive - Start HandlerThread
03-17 08:35:46.254  1338  1338 D NearbySettings: MountReceiver.onReceive - Create mPrefHandler
,03-17 08:35:46.254   321   321 I art     : Explicit concurrent mark sweep GC freed 8746(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 639us total 30.034ms
,03-17 08:35:46.264  3178  3178 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:46.264  3178  3178 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:46.274  1338  1338 D NearbySettings: MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
,03-17 08:35:46.274  1338  3193 V NearbySettings: MountReceiver.mPrefHandler - 7002
03-17 08:35:46.274  1018  1731 D SettingsProvider: name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
,03-17 08:35:46.274  1464  1770 D TP/SmsProvider: query,matched:0, calling pid = 2342
,03-17 08:35:46.284   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 711us total 18.480ms
,03-17 08:35:46.294  1464  1770 D TP/SmsProvider: match 0:Elapsed time : 15.227 ms
,03-17 08:35:46.294   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 614us total 17.204ms
,03-17 08:35:46.304  3178  3178 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 08:35:46.314  1464  1740 D TP/SmsProvider: query,matched:51, calling pid = 2342
,03-17 08:35:46.324  1464  1740 D TP/SmsProvider: match 51:Elapsed time : 4.225 ms
,03-17 08:35:46.324  1018  1018 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
,03-17 08:35:46.324   325  1075 D AT_Distributor: SetAtdStatus(), 1_1_0
03-17 08:35:46.324   325  1075 D AT_Distributor: Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,03-17 08:35:46.334  2342  3064 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
,03-17 08:35:46.334  1576  3154 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,03-17 08:35:46.344  3178  3178 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-17 08:35:46.344  3178  3178 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a500fu.dat
,03-17 08:35:46.344  3178  3178 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a5ulte.dat
,03-17 08:35:46.354  3178  3178 I LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a500fu.dat
,03-17 08:35:46.364  2632  2713 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,03-17 08:35:46.374  1906  1906 D SamsungIME: Dismiss ExpandCandiate
,03-17 08:35:46.384  2632  2713 D BluetoothMediaBrowser: no now playing list
,03-17 08:35:46.384  2632  2713 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,03-17 08:35:46.384  1338  1338 I NearbySettings: MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
03-17 08:35:46.384  1338  1338 I NearbySettings: MountReceiver.onReceive - Internal Path
,03-17 08:35:46.384  1576  1584 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-17 08:35:46.384  1576  1584 D BadgeProvider: sendNotify, [notify] : null
03-17 08:35:46.384  1576  1584 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-17 08:35:46.384  1576  1584 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 08:35:46.384  1576  1584 D BadgeProvider: update, [UpdateCount] : 1
,03-17 08:35:46.394  2342  3064 D Mms/MessagingNotification: setBadgeCount(), count=0
,03-17 08:35:46.394  1192  1192 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 08:35:46.404  1491  1491 D Launcher.Model: reloadBadges entered.
,03-17 08:35:46.404  2342  3064 D Mms/MessagingNotification: remove alarm
,03-17 08:35:46.404  1018  1346 D SettingsProvider: name = personal_mode_enabled
,03-17 08:35:46.404  1464  1770 D TP/SmsProvider: query,matched:0, calling pid = 2342
,03-17 08:35:46.414  1464  1770 D TP/SmsProvider: match 0:Elapsed time : 7.211 ms
,03-17 08:35:46.414  3178  3178 D LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
,03-17 08:35:46.424  2342  3199 D Mms/MessagingNotification: updateAllHistoryAsRead()
,03-17 08:35:46.434  3156  3156 D [0]UMC:UMCContentProvider: @onCreate
,03-17 08:35:46.434  1464  1464 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-17 08:35:46.434  1464  1464 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 08:35:46.434  1464  1464 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 08:35:46.434  1464  1464 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 08:35:46.434  1464  1464 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 08:35:46.434  1464  1464 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
03-17 08:35:46.434  3178  3178 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
03-17 08:35:46.434  3178  3178 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
03-17 08:35:46.434  3178  3178 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
03-17 08:35:46.434  3178  3178 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
03-17 08:35:46.434  3178  3178 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
03-17 08:35:46.434  3178  3178 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
,03-17 08:35:46.434  3178  3178 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
03-17 08:35:46.434  3178  3178 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
03-17 08:35:46.434  3178  3178 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
03-17 08:35:46.434  3178  3178 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
,03-17 08:35:46.444  3178  3178 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
03-17 08:35:46.444  3178  3178 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
03-17 08:35:46.444  3178  3178 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
03-17 08:35:46.444  3178  3178 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
03-17 08:35:46.444  3178  3178 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
03-17 08:35:46.444  3178  3178 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
03-17 08:35:46.444  3178  3178 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
03-17 08:35:46.444  2342  3064 D Mms/SmsReceiverService: [end]    handleBootCompleted() consume time = 346.552499
03-17 08:35:46.444  3178  3178 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
03-17 08:35:46.444  3178  3178 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
,03-17 08:35:46.444  3178  3178 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
,03-17 08:35:46.444  3178  3178 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
03-17 08:35:46.444  3178  3178 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
03-17 08:35:46.444  3178  3178 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
03-17 08:35:46.444  1018  1506 I ActivityManager: Killing 2359:com.sec.android.omc/1000 (adj 15): empty #31
03-17 08:35:46.444  3156  3156 D [0]UMC:Core: onCreate(): 
,03-17 08:35:46.454  3156  3156 D [0]UMC:Core: @isManagedProfileUser
03-17 08:35:46.454  3156  3156 D [0]UMC:Core: userId: 0
03-17 08:35:46.454  3178  3178 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
03-17 08:35:46.454  3178  3178 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
03-17 08:35:46.454  3178  3178 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
03-17 08:35:46.454  3156  3156 D [0]UMC:Core: userInfo: UserInfo{0:Thali Test:13}
03-17 08:35:46.454  3156  3156 D [0]UMC:Core: userInfo.isManagedProfile() : false
03-17 08:35:46.454  3178  3178 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
03-17 08:35:46.454  3178  3178 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
03-17 08:35:46.454  3178  3178 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
03-17 08:35:46.454  3178  3178 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
03-17 08:35:46.454  3178  3178 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
03-17 08:35:46.454  3178  3178 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
03-17 08:35:46.454  3178  3178 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
03-17 08:35:46.454  3178  3178 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
03-17 08:35:46.454  3178  3178 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
03-17 08:35:46.454  3178  3178 I LcdtestApp: [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
03-17 08:35:46.454  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
03-17 08:35:46.464  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.464  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.464  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.464  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.474  3156  3156 D [0]UMC:DeviceInfo: USA==US==
03-17 08:35:46.474  3206  3206 E Zygote  : MountEmulatedStorage()
03-17 08:35:46.474  3206  3206 I libpersona: KNOX_SDCARD checking this for 1000
03-17 08:35:46.474  3206  3206 E Zygote  : v2
03-17 08:35:46.474  3206  3206 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:46.474  3206  3206 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 08:35:46.474  3206  3206 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 08:35:46.484  1018  1031 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3206 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 08:35:46.484  1018  1031 I ActivityManager: Killing 2390:com.sec.tcpdumpservice/1000 (adj 15): empty #31
03-17 08:35:46.484  3206  3206 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 08:35:46.484  1338  1338 I SmartcardBootCompleteReceiver: SmartcardBootCompleteReceiver - onReceive() 
03-17 08:35:46.484  1338  1338 I SmartcardBootCompleteReceiver: Received intent with action - android.intent.action.BOOT_COMPLETED
,03-17 08:35:46.504  3206  3206 D TimaKeyStoreProvider: TimaSignature is unavailable,
03-17 08:35:46.504  3206  3206 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:46.524  1338  1338 I SmartcardBootCompleteReceiver: Broadcast sent with current lockscreen type
03-17 08:35:46.524  1338  1338 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
,03-17 08:35:46.534  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_2359/cgroup.procs: No such file or directory
03-17 08:35:46.534  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_2390/cgroup.procs: No such file or directory
,03-17 08:35:46.584  1018  1558 D SettingsProvider: name = next_alarm_formatted,
,03-17 08:35:46.584  1018  1558 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 08:35:46.584  1018  1558 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 08:35:46.584  1018  1558 D SettingsProvider: selectionArgs: false
03-17 08:35:46.584  1018  1558 D SettingsProvider: selectionArgs: 10085
03-17 08:35:46.584  1018  1558 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 08:35:46.584  1018  1558 D SettingsProvider: ret = -1
03-17 08:35:46.584   293   293 E SMD     : DCD OFF
,03-17 08:35:46.594   331   331 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 08:35:46.604   277   964 D EnterpriseController: uids 10120
03-17 08:35:46.604   277   964 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 08:35:46.604   277   964 D Netd    : getNetworkForDns: using netid 502 for uid 10120
,03-17 08:35:46.614  3206  3206 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] ,
,03-17 08:35:46.664  1338  1338 D [SBeam] : SBeamEnabler.initPreferenceForSbeam : 0
,03-17 08:35:46.664  1018  1558 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10085
,03-17 08:35:46.674  1906  1906 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 08:35:46.674  1192  1192 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 08:35:46.724  1338  1338 I SettingSearch/SearchIntentReceiver: action : android.intent.action.BOOT_COMPLETED
,03-17 08:35:46.724  1338  1338 I SettingSearch/SearchIntentReceiver: search setting db init!!
,03-17 08:35:46.724   399   399 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,03-17 08:35:46.724  1338  1338 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
,03-17 08:35:46.734  1338  3226 I SettingSearch/SearchIntentReceiver: BOOT_COMPLETED call InitSerachDBThread thread start!
,03-17 08:35:46.764  2896  2896 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 2896
,03-17 08:35:46.764  1018  1257 D ActivityManager: startProcessLocked calleePkgName: com.wssyncmldm, hostingType: broadcast
,03-17 08:35:46.764  1018  1257 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.764  1018  1257 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.764  1018  1257 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.764  1018  1257 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:46.774  2983  3042 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed,
03-17 08:35:46.774  2983  3042 I SecureStorage: [INFO]: SPID(0x00000002)Skip using SecureStorageExceptionJNI
,03-17 08:35:46.784  3228  3228 E Zygote  : MountEmulatedStorage()
,03-17 08:35:46.784  3228  3228 E Zygote  : v2
03-17 08:35:46.784  3228  3228 I libpersona: KNOX_SDCARD checking this for 1000
03-17 08:35:46.784  3228  3228 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:46.784  1018  1257 I ActivityManager: Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3228 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-17 08:35:46.794  3228  3228 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 08:35:46.794  3228  3228 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 08:35:46.794  3228  3228 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 08:35:46.814  1018  1731 D ActivityManager: getContentProviderImpl callerProcessName:com.android.settings, calleePkgName: com.sec.providers.settingsearch
,03-17 08:35:46.824  3058  3058 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 142.254ms
,03-17 08:35:46.824  1192  1192 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 08:35:46.824  1192  1192 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 08:35:46.824  1192  1192 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 08:35:46.824  1018  1731 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.824  1018  1731 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.824  1018  1731 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:46.824  1018  1731 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:46.824  1192  1192 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 08:35:46.824  1192  1192 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 08:35:46.824  1192  1192 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 08:35:46.834  3228  3228 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:46.844  3238  3238 E Zygote  : MountEmulatedStorage(),
03-17 08:35:46.844  3238  3238 E Zygote  : v2
,03-17 08:35:46.844  3238  3238 I libpersona: KNOX_SDCARD checking this for 10150
03-17 08:35:46.844  3238  3238 I libpersona: KNOX_SDCARD not a persona,
03-17 08:35:46.844  1018  1731 I ActivityManager: Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3238 uid=10150 gids={50150, 9997} abi=armeabi-v7a
,03-17 08:35:46.844  3238  3238 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 08:35:46.854  3238  3238 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-17 08:35:46.854  3228  3228 D ActivityThread: Added TimaKeyStore provider,
03-17 08:35:46.854  3238  3238 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 08:35:46.864  2896  2896 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-17 08:35:46.894  3238  3238 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:46.894  3238  3238 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:46.914  1906  1906 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 08:35:46.924  3228  3228 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 08:35:46.964  3156  3156 D USER_AGENT: UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
,03-17 08:35:46.994  1906  1906 I SamsungIME: KeybaordView init() : load resources
,03-17 08:35:47.014  3156  3156 D [0]UMC:AdminManager: init - start
,03-17 08:35:47.024  3206  3206 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,03-17 08:35:47.044  3206  3206 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,03-17 08:35:47.054  3156  3156 D [0]UMC:AdminManager: loadAdmins
,03-17 08:35:47.074  3206  3206 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
,03-17 08:35:47.084  3206  3206 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
,03-17 08:35:47.084  3206  3206 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
,03-17 08:35:47.084  3206  3206 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,03-17 08:35:47.084  3156  3156 D [0]UMC:AdminManager: init - end
,03-17 08:35:47.094  3156  3156 D GSLBManager: migrateStoredUrlFromOldPref
,03-17 08:35:47.124  2896  3171 D jxcore_app_log: JniHelper::setJavaVM(0xb8e04450), pthread_self() = -1187584984
,03-17 08:35:47.134  3156  3156 D GSLBManager: migrateStoredUrlFromOldPref : Migration Not Needed
,03-17 08:35:47.134  3156  3156 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
,03-17 08:35:47.134  3156  3156 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,03-17 08:35:47.134  3156  3156 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
03-17 08:35:47.134  3156  3156 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
03-17 08:35:47.134  3156  3156 D [0]UMC:UMCAdmin: isContainer : 0
,03-17 08:35:47.144  2896  3171 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-17 08:35:47.144  2896  3171 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-17 08:35:47.144  2896  3171 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-17 08:35:47.144  2896  3171 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-17 08:35:47.144  2896  3171 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-17 08:35:47.144  2896  3171 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15ca786e added. We now have 1 listener(s)
,03-17 08:35:47.144  2896  3171 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,03-17 08:35:47.144  1018  1506 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
,03-17 08:35:47.154  2896  3171 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"7C:F9:0E:37:96:AB"}
,03-17 08:35:47.154  2896  3171 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"7C:F9:0E:37:96:AB"}
03-17 08:35:47.154  2896  3171 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-17 08:35:47.154  2896  3171 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-17 08:35:47.154  3156  3156 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
03-17 08:35:47.154  3156  3156 D [0]UMC:UMCAdmin: isContainer : 0
,03-17 08:35:47.164  2896  3171 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-17 08:35:47.164  2896  3171 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-17 08:35:47.164  2896  3171 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-17 08:35:47.164  2896  3171 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
03-17 08:35:47.164  2896  3171 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-17 08:35:47.164  2896  3171 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-17 08:35:47.164  2896  3171 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-17 08:35:47.164  2896  3171 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-17 08:35:47.164  2896  3171 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-17 08:35:47.164  2896  3171 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-17 08:35:47.164  2896  3171 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d5215a5 added. We now have 1 listener(s)
,03-17 08:35:47.164  2896  3171 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-17 08:35:47.174  1906  1906 I SamsungIME: getCurrentKeyboard
03-17 08:35:47.174  1906  1906 I SamsungIME: getTextKeyboard
,03-17 08:35:47.184  2896  3171 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-17 08:35:47.184  2896  3171 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-17 08:35:47.184  2896  3171 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,03-17 08:35:47.184  2896  3171 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-17 08:35:47.184  2896  3171 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-17 08:35:47.184  3228  3228 I FOTA    : [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,03-17 08:35:47.184  2896  3171 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-17 08:35:47.194  2896  3171 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,03-17 08:35:47.214  2896  3171 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-17 08:35:47.214  2896  3171 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-17 08:35:47.214  2896  3171 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-17 08:35:47.214  2896  3171 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-17 08:35:47.214  2896  3171 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-17 08:35:47.214  2896  3171 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-17 08:35:47.214  2896  3171 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-17 08:35:47.214  2896  3171 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-17 08:35:47.214  2896  3171 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-17 08:35:47.214  2896  3171 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-17 08:35:47.224  1018  1257 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.colorblind, hostingType: broadcast
,03-17 08:35:47.234  3156  3156 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
,03-17 08:35:47.234  1018  1257 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:47.234  1018  1257 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:47.234  1018  1257 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:47.234  1018  1257 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:47.244  1018  1257 I ActivityManager: Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3266 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-17 08:35:47.254  1018  1257 I ActivityManager: Killing 2405:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31,
,03-17 08:35:47.254  3266  3266 E Zygote  : MountEmulatedStorage(),
03-17 08:35:47.254  3266  3266 E Zygote  : v2,
03-17 08:35:47.254  1018  1031 D ActivityManager: startService callerProcessName:com.sec.enterprise.knox.cloudmdm.smdms, calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms
03-17 08:35:47.254  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,03-17 08:35:47.254  3266  3266 I libpersona: KNOX_SDCARD checking this for 1000
03-17 08:35:47.254  3266  3266 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:47.254  3266  3266 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 08:35:47.264  1018  1031 W ActivityManager: userId = 0, bbcId = -10000,
03-17 08:35:47.264  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:35:47.264  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,03-17 08:35:47.264  3266  3266 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 08:35:47.264  3156  3156 D [0]UMC:GuardService: @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
,03-17 08:35:47.274  3266  3266 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 08:35:47.274  3156  3156 D [0]UMC:CoreReceiver: Intent : android.intent.action.BOOT_COMPLETED
03-17 08:35:47.274  3156  3156 D [0]UMC:CoreReceiver:  check PreETag 
,03-17 08:35:47.294  1906  1906 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
03-17 08:35:47.294  1018  1490 I ActivityManager: Killing 2312:com.sec.android.app.mt/1000 (adj 15): empty #31
,03-17 08:35:47.324  3266  3266 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:47.324  3266  3266 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:47.334  3228  3228 I DBG_DM  : [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
,03-17 08:35:47.364  3156  3156 D [0]UMC:CoreReceiver: bulk enrolled package: null
,03-17 08:35:47.374  3228  3228 I DBG_DM  : [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
,03-17 08:35:47.374  3156  3156 V [0]UMC:ProfileStorage: Enter loadList
,03-17 08:35:47.374  3228  3228 I DBG_DM  : [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,03-17 08:35:47.374  3156  3156 D [0]UMC:CoreReceiver: handleAutoEnrollmentAndUMCAdminDeactivation
,03-17 08:35:47.374  3156  3156 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
,03-17 08:35:47.384  3156  3156 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,03-17 08:35:47.404  3156  3156 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
03-17 08:35:47.404  3156  3156 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
03-17 08:35:47.404  3156  3156 D [0]UMC:UMCAdmin: isContainer : 0
,03-17 08:35:47.414  1018  1031 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
,03-17 08:35:47.414  2896  2896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-17 08:35:47.414  3156  3156 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
03-17 08:35:47.414  3156  3156 D [0]UMC:UMCAdmin: isContainer : 0
,03-17 08:35:47.414  3266  3266 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 08:35:47.414  3156  3156 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
,03-17 08:35:47.424  2896  2896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 08:35:47.424  2896  2896 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-17 08:35:47.434  1018  1487 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.policydm
,03-17 08:35:47.434  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:47.434  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:47.434  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:47.434  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:47.454  3290  3290 E Zygote  : MountEmulatedStorage()
,03-17 08:35:47.454  3290  3290 E Zygote  : v2
,03-17 08:35:47.454  3290  3290 I libpersona: KNOX_SDCARD checking this for 1000
03-17 08:35:47.454  3290  3290 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:47.454  3156  3156 D [0]UMC:ByodSetupStarter: Container ID : 0
03-17 08:35:47.454  3290  3290 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 08:35:47.464  3290  3290 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-17 08:35:47.464  1018  1487 I ActivityManager: Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3290 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 08:35:47.464  3290  3290 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 08:35:47.474  3156  3156 V [0]UMC:Utils: checkAppScreen() : com.test.thalitest
,03-17 08:35:47.474  3156  3156 I [0]UMC:Core: shutdown
,03-17 08:35:47.474  1018  1346 D ActivityManager: retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,03-17 08:35:47.484  1018  1346 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:47.484  1018  1346 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:35:47.484  1018  1346 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,03-17 08:35:47.484  3156  3156 D [0]UMC:GuardService: @GuardService - stopService Result = true
,03-17 08:35:47.484  1018  1346 E Tethering: No numeric data
,03-17 08:35:47.494  3156  3156 I art     : System.exit called, status: 0
03-17 08:35:47.494  3156  3156 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,03-17 08:35:47.494  1018  1490 E Tethering: No numeric data
,03-17 08:35:47.494  1018  1506 E Tethering: No numeric data
,03-17 08:35:47.504  1018  1031 E Tethering: No numeric data
,03-17 08:35:47.504  1018  1734 E Tethering: No numeric data
,03-17 08:35:47.514  1018  1030 E Tethering: No numeric data
,03-17 08:35:47.514  1018  1346 D ActivityManager: startProcessLocked calleePkgName: com.google.android.configupdater, hostingType: broadcast
,03-17 08:35:47.514  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:47.514  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:47.514  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:47.514  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:47.534  3306  3306 E Zygote  : MountEmulatedStorage()
03-17 08:35:47.534  3306  3306 I libpersona: KNOX_SDCARD checking this for 10086
03-17 08:35:47.534  3306  3306 E Zygote  : v2
03-17 08:35:47.534  3306  3306 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:47.534  3306  3306 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 08:35:47.534  1018  1346 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3306 uid=10086 gids={50086, 9997, 3003} abi=armeabi-v7a
03-17 08:35:47.534  1018  1346 I ActivityManager: Killing 2450:com.wsomacp/u0a25 (adj 15): empty #31
,03-17 08:35:47.534  3290  3290 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 08:35:47.534  3290  3290 D ActivityThread: Added TimaKeyStore provider
03-17 08:35:47.534  3306  3306 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 08:35:47.544  3306  3306 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 08:35:47.564  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_2312/cgroup.procs: No such file or directory
,03-17 08:35:47.564  1018  1042 W libprocessgroup: failed to open /acct/uid_10131/pid_2405/cgroup.procs: No such file or directory
,03-17 08:35:47.584  3306  3306 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:47.584  3306  3306 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:47.594   331   331 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-17 08:35:47.614  1338  3226 D [SBeam] : SBeamEnabler.isSBeamSupported : [-1]
,03-17 08:35:47.614  1338  3226 D [SBeam] : SBeamEnabler.isSBeamSupported : EXIST
,03-17 08:35:47.634  1018  1558 I ActivityManager: Process com.sec.enterprise.knox.cloudmdm.smdms (pid 3156)(adj 0) has died(208,1059)
,03-17 08:35:47.644  1018  1042 W libprocessgroup: failed to open /acct/uid_10025/pid_2450/cgroup.procs: No such file or directory
,03-17 08:35:47.654  1018  1346 E Tethering: No numeric data
,03-17 08:35:47.654  1018  1731 E Tethering: No numeric data
,03-17 08:35:47.654  1018  1257 E Tethering: No numeric data
,03-17 08:35:47.654  1317  1317 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
03-17 08:35:47.654  1317  1317 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,03-17 08:35:47.654  1317  1317 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 08:35:47.674  1317  1317 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 08:35:47.674  1018  1490 E Tethering: No numeric data
,03-17 08:35:47.674  1317  1317 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-17 08:35:47.674  1317  1317 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
,03-17 08:35:47.684  1317  1317 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-17 08:35:47.684  1317  1317 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
03-17 08:35:47.684  1317  1317 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-17 08:35:47.684  1317  1317 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,03-17 08:35:47.684  3228  3228 I DBG_DM  : [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
03-17 08:35:47.684  1317  1317 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
03-17 08:35:47.684  1317  1317 D daemonapp: [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
,03-17 08:35:47.684  3228  3228 I DBG_DM  : [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,03-17 08:35:47.684  3228  3228 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,03-17 08:35:47.684  1018  1734 D ActivityManager: startService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm
,03-17 08:35:47.694  1018  1734 D ActivityManager: retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,03-17 08:35:47.694  1018  1734 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:47.694  1018  1734 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:35:47.694  1018  1734 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-17 08:35:47.694  1018  1558 D SettingsProvider: name = aw_daemon_service_key_version_check
,03-17 08:35:47.694  1018  1558 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,03-17 08:35:47.694  1018  1558 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,03-17 08:35:47.694  1018  1558 D SettingsProvider: selectionArgs: false
,03-17 08:35:47.704  1018  1558 D SettingsProvider: selectionArgs: 10162
,03-17 08:35:47.704  3228  3228 I DBG_DM  : [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,03-17 08:35:47.704  1018  1558 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,03-17 08:35:47.704  3228  3228 I DBG_DM  : [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,03-17 08:35:47.704  3228  3228 I DBG_DM  : [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,03-17 08:35:47.704  1018  1558 D SettingsProvider: ret = -1
,03-17 08:35:47.714  1192  1192 D OverheatReceiver: onReceive() getAction : android.intent.action.BOOT_COMPLETED
,03-17 08:35:47.714  1192  1192 D OverheatReceiver: into the SAFE_MODE_ACTION
,03-17 08:35:47.714  1192  1192 D OverheatReceiver: VZW on -> change to Global UX [safe mode]
,03-17 08:35:47.714  1192  1192 D OverheatReceiver: isSafeMode = false
,03-17 08:35:47.724  1464  1464 D BootupListener: intent.getAction() = android.intent.action.BOOT_COMPLETED
,03-17 08:35:47.724  1018  1143 D SettingsProvider: name = internet_call_settings_visibility
,03-17 08:35:47.724  1018  1143 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,03-17 08:35:47.724  1018  1143 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,03-17 08:35:47.724  1018  1143 D SettingsProvider: selectionArgs: false
03-17 08:35:47.724  1018  1143 D SettingsProvider: selectionArgs: 1001
,03-17 08:35:47.724  1018  1143 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,03-17 08:35:47.724  1018  1143 D SettingsProvider: ret = -1
,03-17 08:35:47.734  1464  1464 D PhoneUtilsCommon: isSupportVoLTE is false.
,03-17 08:35:47.744  1443  1443 I Telecom : InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,03-17 08:35:47.744  1018  1506 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: android.telecom.InCallService
,03-17 08:35:47.744  1018  1506 D ActivityManager: retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.InCallServiceImpl; callingUser = 0; userId(target) = -2
,03-17 08:35:47.744  1018  1506 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:35:47.744  1018  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 08:35:47.744  1018  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-17 08:35:47.754  3306  3306 E UpdateRequestReceiver: ignoring update request
,03-17 08:35:47.754  1018  1031 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: com.samsung.incallui.SEC_IN_CALL_SERVICE
,03-17 08:35:47.754  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.SecInCallService; callingUser = 0; userId(target) = -2
,03-17 08:35:47.754  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:35:47.764  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 08:35:47.764  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-17 08:35:47.764  1018  1731 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,03-17 08:35:47.764  1018  1731 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:47.764  1018  1731 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:47.764  1018  1731 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:47.764  1018  1731 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:47.774  1018  1558 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10162
,03-17 08:35:47.784  3306  3306 E UpdateRequestReceiver: ignoring update request,
,03-17 08:35:47.784  3326  3326 E Zygote  : MountEmulatedStorage(),
03-17 08:35:47.784  3326  3326 E Zygote  : v2
03-17 08:35:47.784  3326  3326 I libpersona: KNOX_SDCARD checking this for 10057,
03-17 08:35:47.784  3326  3326 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-17 08:35:47.784  3326  3326 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:47.784  3326  3326 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 08:35:47.784  3326  3326 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,03-17 08:35:47.794  1018  1731 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3326 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a,
03-17 08:35:47.794  1317  1317 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-17 08:35:47.794  1018  1346 V VibratorService: hasVibrator - useVibetonz: true
,03-17 08:35:47.804  1192  1192 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 08:35:47.804  1443  1443 I Telecom : InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
,03-17 08:35:47.814  3326  3326 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 08:35:47.814  3306  3306 E UpdateRequestReceiver: ignoring update request
,03-17 08:35:47.814  3326  3326 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:47.824  1338  3226 W NotificationAccessSettings: Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,03-17 08:35:47.824  1018  1346 V VibratorService: hasVibrator - useVibetonz: true
,03-17 08:35:47.834  1317  1317 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,03-17 08:35:47.844  1018  1506 V VibratorService: hasVibrator - useVibetonz: true
,03-17 08:35:47.844  2983  2983 E BluetoothHeadset: BTStateChangeCB is registed
,03-17 08:35:47.844  2983  2983 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,03-17 08:35:47.854  1317  1317 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-17 08:35:47.854  1317  1317 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-17 08:35:47.854  1317  1317 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,03-17 08:35:47.854  1018  1731 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
03-17 08:35:47.854  1018  1731 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,03-17 08:35:47.864  1018  1731 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:35:47.864  1018  1731 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 08:35:47.864  1018  1731 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,03-17 08:35:47.864  2983  2983 E BluetoothHeadset: BluetoothHeadset service is binded
,03-17 08:35:47.874  3306  3306 E UpdateRequestReceiver: ignoring update request
,03-17 08:35:47.874  1338  3226 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 08:35:47.874  2983  2983 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,03-17 08:35:47.874  1317  1317 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-17 08:35:47.884  1018  1506 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,03-17 08:35:47.884  1018  1506 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,03-17 08:35:47.884  1018  1506 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:35:47.884  1018  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 08:35:47.884  1018  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,03-17 08:35:47.904  1317  1317 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,03-17 08:35:47.904  1317  1317 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 08:35:47.904   286   744 V audio_hw_primary: adev_get_parameters: enter: keys - call_forwarding
03-17 08:35:47.904   286   744 D audio_hw_extn: audio_extn_get_parameters: returns 
03-17 08:35:47.904   286   744 V msm8974_platform: platform_get_parameters: exit: returns - 
03-17 08:35:47.904   286   744 V audio_hw_primary: adev_get_parameters: exit: returns - call_forwarding=false
03-17 08:35:47.904   286   744 I str_params: key: 'call_forwarding' value: ''
03-17 08:35:47.914  1959  1959 V InCall  : ProximitySensor -  - screenonImmediately: false
03-17 08:35:47.914  1959  1959 V InCall  : ProximitySensor -  - mFromRcsShare: false
,03-17 08:35:47.914  1959  1959 I InCall  : ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,03-17 08:35:47.914  1317  1317 D daemonapp: [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1458200147908
,03-17 08:35:47.914  1317  1317 D daemonapp: [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1458221700000
03-17 08:35:47.914  1317  1317 D daemonapp: [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
,03-17 08:35:47.914  1317  1317 D daemonapp: [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
,03-17 08:35:47.914  3306  3306 E UpdateRequestReceiver: ignoring update request
,03-17 08:35:47.914  3228  3228 I DBG_DM  : [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,03-17 08:35:47.924  1317  1317 D daemonapp: [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1458221700000
,03-17 08:35:47.924  1317  1317 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
,03-17 08:35:47.934  1317  1317 D daemonapp: [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1458221700000
,03-17 08:35:47.934  1959  1959 D ScoverManager: serviceVersion : 16908288
,03-17 08:35:47.934  1018  1143 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 08:35:47.934  1959  1959 D InCall  : InCallUtils - isCoverClosed false
,03-17 08:35:47.934  1443  1443 I Telecom : ProximitySensorManager: Proximity wake lock already released
,03-17 08:35:47.934  1018  1346 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 08:35:47.934  1959  1959 D InCall  : InCallUtils - isCoverClosed false
,03-17 08:35:47.934  1959  1959 I InCall  : InCallPresenter -  - InCallState = NO_CALLS
,03-17 08:35:47.944  1959  1959 I InCall  : InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
,03-17 08:35:47.944  1959  1959 D InCall  : InCallPresenter -  - dismissCoverDialog()...
,03-17 08:35:47.944  3228  3228 I DBG_DM  : [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
,03-17 08:35:47.944  3228  3228 I DBG_DM  : [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
,03-17 08:35:47.944  3228  3228 I DBG_DM  : [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
,03-17 08:35:47.944  3228  3228 I DBG_DM  : [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
,03-17 08:35:47.944  1959  1959 I InCall  : CallSContextMotion - stopPutDownListening
,03-17 08:35:47.944  3228  3228 I DBG_DM  : [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
,03-17 08:35:47.944  1959  1959 D InCall  : StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,03-17 08:35:47.944  3228  3228 I DBG_DM  : [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
,03-17 08:35:47.944  3228  3228 I DBG_DM  : [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
,03-17 08:35:47.954  3306  3306 E UpdateRequestReceiver: ignoring update request
,03-17 08:35:47.954  1317  1317 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
,03-17 08:35:47.954  1317  1317 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,03-17 08:35:47.954  1192  1192 D PhoneStatusBarView: setCallBackground:0
,03-17 08:35:47.954  1018  1346 D ActivityManager: startProcessLocked calleePkgName: com.google.android.youtube, hostingType: broadcast
,03-17 08:35:47.964  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:47.964  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:47.964  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:47.964  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:47.964  3228  3228 I DBG_DM  : [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
03-17 08:35:47.964  3228  3268 I DBG_DM  : [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,03-17 08:35:47.964  1018  1490 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 08:35:47.974  1959  1959 D InCall  : InCallUtils - isCoverClosed false
,03-17 08:35:47.974  3350  3350 E Zygote  : MountEmulatedStorage()
03-17 08:35:47.974  3350  3350 I libpersona: KNOX_SDCARD checking this for 10166
03-17 08:35:47.974  3350  3350 E Zygote  : v2
03-17 08:35:47.974  3350  3350 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:47.984  3350  3350 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-17 08:35:47.984  1018  1346 I ActivityManager: Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3350 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,03-17 08:35:47.984  3350  3350 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 08:35:47.994  1018  1346 D ActivityManager: startProcessLocked calleePkgName: com.dropbox.android, hostingType: broadcast
,03-17 08:35:47.994  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:47.994  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:47.994  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:47.994  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:48.014  3357  3357 E Zygote  : MountEmulatedStorage(),
03-17 08:35:48.014  3357  3357 I libpersona: KNOX_SDCARD checking this for 10092
03-17 08:35:48.014  3357  3357 E Zygote  : v2,
03-17 08:35:48.014  3357  3357 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:48.014  3357  3357 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 08:35:48.014  3357  3357 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 08:35:48.014  1018  1346 I ActivityManager: Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3357 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
03-17 08:35:48.014  3350  3350 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
03-17 08:35:48.014  1018  1346 I ActivityManager: Killing 2484:com.sec.android.widgetapp.digitalclock/u0a88 (adj 15): empty #31
03-17 08:35:48.014  3357  3357 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL,
,03-17 08:35:48.044  3228  3228 I DBG_DM  : [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
,03-17 08:35:48.054  3357  3357 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:48.054  3357  3357 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:48.054  1338  3226 D ScoverManager: serviceVersion : 16908288
,03-17 08:35:48.064  3350  3350 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:48.064  3350  3350 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:48.074  3228  3228 I DBG_DM  : [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
,03-17 08:35:48.074  1018  1030 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,03-17 08:35:48.074  3228  3228 I DBG_DM  : [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
03-17 08:35:48.074  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:48.074  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:48.074  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:48.074  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:48.094  3384  3384 E Zygote  : MountEmulatedStorage(),
03-17 08:35:48.094  3384  3384 E Zygote  : v2
03-17 08:35:48.094  3384  3384 I libpersona: KNOX_SDCARD checking this for 10009,
03-17 08:35:48.094  3384  3384 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 08:35:48.094  3384  3384 I libpersona: KNOX_SDCARD not a persona,
,03-17 08:35:48.094  3384  3384 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-17 08:35:48.094  1018  1030 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3384 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
03-17 08:35:48.094  3384  3384 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 08:35:48.114  3384  3384 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:48.114  3384  3384 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:48.124  3228  3268 I DBG_DM  : [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
,03-17 08:35:48.124  1959  1959 D VideoCallManager: Instantiating VideoCallManager
,03-17 08:35:48.124  1959  1959 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-17 08:35:48.124  1959  1959 I GFX construct_block_size_descriptor_2d second part: took 2.131510ms for 0*0 texture 0
,03-17 08:35:48.134  1959  1959 I GFX generate_partition_tables: took 5.210937ms for 0*0 texture 0
,03-17 08:35:48.134  3228  3228 I DBG_DM  : [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
,03-17 08:35:48.134  1959  1959 I GFX raster: took 11.085938ms for 176*144 texture 0
03-17 08:35:48.134  1959  1959 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb91cf6f0 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb91e7900 counterpartCT=4 counterpartW=176 counterparth=144
03-17 08:35:48.134  3228  3228 I DBG_DM  : [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
,03-17 08:35:48.144  1959  1959 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
,03-17 08:35:48.144  1959  1959 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 08:35:48.144  1959  1959 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 08:35:48.144  1959  1959 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 08:35:48.144  1959  1959 I Adreno-EGL: Local Branch: 
03-17 08:35:48.144  1959  1959 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 08:35:48.144  1959  1959 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 08:35:48.144  1959  1959 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 08:35:48.164  1959  1959 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 08:35:48.174  3290  3290 I DBG_POLICYDM: [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,03-17 08:35:48.174  2896  3264 W jxcore-log: Initializing JXcore engine
03-17 08:35:48.174  2896  3264 W jxcore-log: JXcore engine is ready
03-17 08:35:48.174  3290  3290 I DBG_POLICYDM: [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
03-17 08:35:48.174  1959  1959 I glCompressedTexImage2D: took 0.325573ms for 320*61440 texture 37809
,03-17 08:35:48.184  1959  1959 I draw setup: took 10.221094ms for 320*240 texture 37809
03-17 08:35:48.184  1959  1959 E GFX GPU raster: drawn
,03-17 08:35:48.184  1959  1959 I GFX GPU raster ASTC: took 40.073177ms for 320*240 texture 12
03-17 08:35:48.184  1959  1959 I GFX raster: took 40.169792ms for 320*240 texture 0
03-17 08:35:48.184  1959  1959 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb91e7900 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb91e9c40 counterpartCT=4 counterpartW=320 counterparth=240
,03-17 08:35:48.204  1959  1959 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-17 08:35:48.204  1959  1959 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 08:35:48.204  1959  1959 I glCompressedTexImage2D: took 0.336928ms for 480*122880 texture 37813
03-17 08:35:48.204  1959  1959 I draw setup: took 0.704271ms for 480*640 texture 37813
03-17 08:35:48.204  1959  1959 E GFX GPU raster: drawn
,03-17 08:35:48.204  3228  3268 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
,03-17 08:35:48.214  1959  1959 I GFX GPU raster ASTC: took 6.929532ms for 480*640 texture 12
03-17 08:35:48.214  1959  1959 I GFX raster: took 7.011666ms for 480*640 texture 0
03-17 08:35:48.214  1959  1959 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb91e9c40 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb94180d0 counterpartCT=4 counterpartW=480 counterparth=640
,03-17 08:35:48.224  1018  1346 D ActivityManager: bindService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm, action: null
03-17 08:35:48.224  1018  1346 D ActivityManager: retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,03-17 08:35:48.224  1018  1346 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:48.224  1018  1346 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:35:48.224  1018  1346 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-17 08:35:48.244  1905  1905 E audit   : type=1400 msg=audit(1458200148.244:205): avc:  denied  { ioctl } for  pid=3264 comm="Thread-349" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-17 08:35:48.244  1905  1905 E audit   :  SEPF_SM-A500FU_5.0.2-1_0038
03-17 08:35:48.244  1905  1905 E audit   : type=1300 msg=audit(1458200148.244:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=9c84f8f8 items=0 ppid=321 ppcomm=main pid=3264 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-349" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-17 08:35:48.244  1905  1905 E audit   : type=1320 msg=audit(1458200148.244:205): 
,03-17 08:35:48.254  1018  1042 W libprocessgroup: failed to open /acct/uid_10088/pid_2484/cgroup.procs: No such file or directory
,03-17 08:35:48.254  1959  1959 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,03-17 08:35:48.254  2896  3264 W jxcore-log: Starting JXcore engine
,03-17 08:35:48.264  1959  1959 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 08:35:48.264  1959  1959 I glCompressedTexImage2D: took 0.352136ms for 440*116864 texture 37809
03-17 08:35:48.264  1959  1959 I draw setup: took 0.748646ms for 440*330 texture 37809
03-17 08:35:48.264  1959  1959 E GFX GPU raster: drawn
,03-17 08:35:48.274  1959  1959 I GFX GPU raster ASTC: took 5.012343ms for 440*330 texture 12
,03-17 08:35:48.274  1959  1959 I GFX raster: took 5.100937ms for 440*330 texture 0
03-17 08:35:48.274  1959  1959 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb94180d0 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb942c4c0 counterpartCT=4 counterpartW=440 counterparth=330
,03-17 08:35:48.284  3228  3228 I DBG_DM  : [com.wssyncmldm.XDMService(155/onStartCommand)] 
,03-17 08:35:48.304  1959  1959 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-17 08:35:48.304  1959  1959 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 08:35:48.314  1959  1959 I glCompressedTexImage2D: took 0.575312ms for 480*163840 texture 37811
03-17 08:35:48.314  1959  1959 I draw setup: took 0.948073ms for 480*640 texture 37811
03-17 08:35:48.314  1959  1959 E GFX GPU raster: drawn,
,03-17 08:35:48.314  1959  1959 I GFX GPU raster ASTC: took 5.850208ms for 480*640 texture 12
03-17 08:35:48.314  1959  1959 I GFX raster: took 5.944896ms for 480*640 texture 0
03-17 08:35:48.314  1959  1959 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb941c2d0 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb942bff8 counterpartCT=4 counterpartW=480 counterparth=640
,03-17 08:35:48.314  3228  3228 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,03-17 08:35:48.324  3228  3228 I DBG_DM  : [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,03-17 08:35:48.334  3290  3290 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,03-17 08:35:48.344  3290  3377 I DBG_POLICYDM: [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,03-17 08:35:48.354  3290  3290 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,03-17 08:35:48.364  1018  1487 I art     : Explicit concurrent mark sweep GC freed 23625(1226KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 26MB/39MB, paused 2.829ms total 226.749ms
,03-17 08:35:48.374  1959  1959 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-17 08:35:48.374  1959  1959 I GFX construct_block_size_descriptor_2d second part: took 2.012031ms for 0*0 texture 0
,03-17 08:35:48.384  1959  1959 I GFX generate_partition_tables: took 7.423490ms for 0*0 texture 0
,03-17 08:35:48.384  1959  1959 I GFX raster: took 11.428281ms for 176*144 texture 0
03-17 08:35:48.384  1959  1959 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb9415990 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb9415ab0 counterpartCT=4 counterpartW=176 counterparth=144
,03-17 08:35:48.394  1959  1959 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-17 08:35:48.394  1959  1959 I GFX construct_block_size_descriptor_2d second part: took 2.047656ms for 0*0 texture 0
,03-17 08:35:48.404  1959  1959 I GFX generate_partition_tables: took 6.166249ms for 0*0 texture 0
,03-17 08:35:48.404  1959  1959 I GFX raster: took 10.355103ms for 176*144 texture 0
03-17 08:35:48.404  1959  1959 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb9415cd0 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb9415c70 counterpartCT=4 counterpartW=176 counterparth=144
,03-17 08:35:48.414  1959  1959 D ScoverManager: registerListener
,03-17 08:35:48.414  1018  1731 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 08:35:48.414  1018  1558 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 08:35:48.414  1018  1558 D CoverManager.StateNotifier: registerListenerCallback : binder = android.os.BinderProxy@b858d32, pid : 1959, uid : 1001, type : 1
,03-17 08:35:48.414  3290  3290 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,03-17 08:35:48.424  3290  3290 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,03-17 08:35:48.424  1959  1959 D InCall  : InCallPresenter -  - Finished InCallPresenter.setUp
,03-17 08:35:48.424  3290  3290 I DBG_POLICYDM: [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,03-17 08:35:48.424  3290  3290 I DBG_POLICYDM: [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,03-17 08:35:48.424  3290  3377 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,03-17 08:35:48.424  1018  2715 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.cB:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,03-17 08:35:48.434  3290  3290 I DBG_POLICYDM: [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,03-17 08:35:48.444  2896  3264 W jxcore-log: Platform android
03-17 08:35:48.444  2896  3264 W jxcore-log: 
,03-17 08:35:48.444  2896  3264 W jxcore-log: Process ARCH arm
03-17 08:35:48.444  2896  3264 W jxcore-log: 
,03-17 08:35:48.454  2983  2983 D BluetoothA2dp: Proxy object connected
,03-17 08:35:48.464  3228  3268 I DBG_DM  : [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,03-17 08:35:48.594  1338  3226 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-17 08:35:48.604  1906  3280 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-17 08:35:48.614  1338  3226 D Settings_Utils: isSupportVNFestival SM-A500FU XEO
,03-17 08:35:48.684  1018  1031 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,03-17 08:35:48.684  2896  3264 I jxcore-log: JXcore Cordova bridge is ready!
03-17 08:35:48.684  2896  3264 I jxcore-log: 
,03-17 08:35:48.684  2896  3264 W jxcore-log: JXcore engine is started
,03-17 08:35:48.684  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:48.684  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:48.684  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:48.684  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:48.684  3290  3377 I DBG_POLICYDM: [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,03-17 08:35:48.694  2896  3171 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION,
,03-17 08:35:48.694  2896  2896 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-17 08:35:48.694  3413  3413 E Zygote  : MountEmulatedStorage()
,03-17 08:35:48.694  3413  3413 E Zygote  : v2
03-17 08:35:48.694  3413  3413 I libpersona: KNOX_SDCARD checking this for 10015
03-17 08:35:48.694  3413  3413 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:48.704  3413  3413 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 08:35:48.704  3413  3413 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 08:35:48.704  3413  3413 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 08:35:48.714  1018  1030 D LocationManagerService: getProviders()=[passive]
03-17 08:35:48.714  1018  1031 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3413 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,03-17 08:35:48.714  2896  3264 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-17 08:35:48.714  2896  3264 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-17 08:35:48.714  3413  3413 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:48.724  3413  3413 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:48.724  2896  2896 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,03-17 08:35:48.724  2896  2896 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,03-17 08:35:48.724   321   321 I art     : Explicit concurrent mark sweep GC freed 8750(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 644us total 23.858ms
03-17 08:35:48.724  1018  1487 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 08:35:48.724  1018  1487 D FocusedStackFrame: Set to : 0
03-17 08:35:48.724  1018  1487 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 08:35:48.724  1018  1487 D InputDispatcher: Focused application set to: xxxx
03-17 08:35:48.724  1018  1487 D InputDispatcher: Focus left window: 2896
03-17 08:35:48.734  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 08:35:48.734  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 08:35:48.744   257   444 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (155 us)
03-17 08:35:48.754   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 612us total 22.092ms
,03-17 08:35:48.774   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 680us total 19.060ms
,03-17 08:35:48.804  2896  3171 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 75ms. Plugin should use CordovaInterface.getThreadPool().
03-17 08:35:48.804  1018  1490 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-17 08:35:48.804  1018  1490 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 08:35:48.804  1018  1490 W ActivityManager: mDVFSHelper.acquire()
03-17 08:35:48.804  1018  1490 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 08:35:48.804  1018  1490 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,03-17 08:35:48.844  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
03-17 08:35:48.844  1018  1018 D SensorService: [SO] activate (ident=0xb96032c0, enabled=0)
03-17 08:35:48.844  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-17 08:35:48.854  1018  1018 D SensorManager: unregisterListener ::   ,
03-17 08:35:48.854  1018  1018 I Sensors : AccelerometerSensor(0) setDelay : 200000000(ns)
,03-17 08:35:48.854  1018  1018 D SensorService: [SO] changed settle time [0]
,03-17 08:35:48.854  1018  1018 D SensorService: [SO] setDelay [200000000]
03-17 08:35:48.854  1018  1018 D SensorService: [SO] activate (ident=0xb96032c0, enabled=1)
03-17 08:35:48.854  1018  1018 D SensorService: [SO] AR_init
03-17 08:35:48.854  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-17 08:35:48.854  1491  1491 D Launcher: onRestart, Launcher: 246920386
,03-17 08:35:48.854  1491  1491 D Launcher: onStart, Launcher: 246920386
03-17 08:35:48.854  1491  1491 D Launcher.HomeView: onStart
03-17 08:35:48.854  1491  1491 D Launcher: onResume, Launcher: 246920386
,03-17 08:35:48.854  1018  1487 D SettingsProvider: name = kids_home_mode
03-17 08:35:48.854  1018  1487 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 08:35:48.854  1018  1487 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 08:35:48.854  1018  1487 D SettingsProvider: selectionArgs: false
03-17 08:35:48.854  1018  1487 D SettingsProvider: selectionArgs: 10007
,03-17 08:35:48.854  1018  1487 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 08:35:48.854  1018  1487 D SettingsProvider: ret = -1
03-17 08:35:48.854  1491  1491 D Launcher.HomeView: onResume
,03-17 08:35:48.864  1018  1018 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  ,
,03-17 08:35:48.864  1491  1491 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-17 08:35:48.874  1491  1491 D MenuAppsGridFragment: onResume
,03-17 08:35:48.904  1018  1731 D ActivityManager: handle home activity for 0,
03-17 08:35:48.904  1018  1731 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
03-17 08:35:48.904  1018  1731 D KnoxTimeoutHandler: post home show event for user 0
03-17 08:35:48.904  1018  1731 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-17 08:35:48.904  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,03-17 08:35:48.904  1018  1731 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 08:35:48.904  1018  1731 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-17 08:35:48.904  1018  1018 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
03-17 08:35:48.904  1018  1018 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
03-17 08:35:48.904  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-17 08:35:48.914   257   257 I SurfaceFlinger: id=12 createSurf (720x1280),1 flag=4, Mauncher
,03-17 08:35:48.914  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 08:35:48.934  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 08:35:48.934  1018  1030 D InputDispatcher: Focus entered window: 1491
,03-17 08:35:48.944  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-17 08:35:48.954  2813  2826 W art     : Suspending all threads took: 7.293ms
,03-17 08:35:48.954  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 08:35:48.954  1491  1491 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-17 08:35:48.964  1018  2832 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 08:35:48.984  1491  1491 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-17 08:35:48.984  1018  1731 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,03-17 08:35:48.984  1018  1731 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.service.BroadcastListenerService; callingUser = 0; userId(target) = 0
,03-17 08:35:48.984  1018  1558 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 08:35:48.994  1018  1731 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:35:48.994  1192  1192 I StatusBar: Icon Only
03-17 08:35:48.994  2896  2896 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-17 08:35:48.994  1192  1192 D PanelView: There is/are notification(s) 
03-17 08:35:48.994  1018  1731 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 08:35:48.994  1018  1731 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
03-17 08:35:48.994  1906  1906 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-17 08:35:49.004  1018  3444 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 08:35:49.024  3228  3268 I DBG_DM  : [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,03-17 08:35:49.034  2197  2197 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,03-17 08:35:49.034  2197  2197 I dhcpcd  : wlan0: no IPv6 Routers available
,03-17 08:35:49.034  1018  1490 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,03-17 08:35:49.034  1018  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.velvet.VelvetBackgroundTasksImpl$Service; callingUser = 0; userId(target) = 0
,03-17 08:35:49.034  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:35:49.034  1018  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 08:35:49.034  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-17 08:35:49.054  3433  3433 D AndroidRuntime: 
03-17 08:35:49.054  3433  3433 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,03-17 08:35:49.054  3433  3433 D AndroidRuntime: CheckJNI is OFF
,03-17 08:35:49.054  3433  3433 D AndroidRuntime: readGMSProperty: start
03-17 08:35:49.054  3433  3433 D AndroidRuntime: readGMSProperty: already setted!!
03-17 08:35:49.054  3433  3433 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-17 08:35:49.054  3433  3433 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-17 08:35:49.054  3433  3433 D AndroidRuntime: readGMSProperty: end
03-17 08:35:49.054  3433  3433 D AndroidRuntime: addProductProperty: start
,03-17 08:35:49.064  1018  1040 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-17 08:35:49.074  1491  1491 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@35fc6267 time:40159
,03-17 08:35:49.084  1018  1048 D PersonaManager: isKioskContainerExistOnDevice
,03-17 08:35:49.094  3350  3432 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 08:35:49.094  3350  3432 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 08:35:49.104  1018  1731 D ActivityManager: startService callerProcessName:com.dropbox.android, calleePkgName: com.dropbox.android
,03-17 08:35:49.104  1018  1731 D ActivityManager: retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.android.exception.CrashUploaderService; callingUser = 0; userId(target) = 0
,03-17 08:35:49.114  3326  3449 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[refresh_search_history]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-17 08:35:49.124  3326  3457 I SearchServiceFactory: refreshing search history.
,03-17 08:35:49.134  1018  1731 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:35:49.134  1018  1731 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
03-17 08:35:49.134  1018  1731 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,03-17 08:35:49.134  1018  1731 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:49.134  1018  1731 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:49.134  1018  1731 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:49.134  1018  1731 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:49.154  3290  3377 I DBG_POLICYDM: [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
03-17 08:35:49.154  3458  3458 I libpersona: KNOX_SDCARD checking this for 10092
03-17 08:35:49.154  3458  3458 E Zygote  : MountEmulatedStorage()
03-17 08:35:49.154  3458  3458 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:49.154  3458  3458 E Zygote  : v2
,03-17 08:35:49.154  3458  3458 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 08:35:49.154  3458  3458 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 08:35:49.164  3458  3458 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL,
,03-17 08:35:49.164  3290  3377 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
03-17 08:35:49.164  1018  1731 I ActivityManager: Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3458 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 08:35:49.164  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,03-17 08:35:49.164  3228  3268 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-17 08:35:49.164  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:49.164  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:49.164  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:49.164  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:49.184  3469  3469 E Zygote  : MountEmulatedStorage()
03-17 08:35:49.184  3469  3469 E Zygote  : v2
03-17 08:35:49.184  3469  3469 I libpersona: KNOX_SDCARD checking this for 10003
03-17 08:35:49.184  3469  3469 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:49.184  3469  3469 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 08:35:49.184  3469  3469 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 08:35:49.194  1018  1018 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3469 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
03-17 08:35:49.194  3458  3458 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 08:35:49.194  3458  3458 D ActivityThread: Added TimaKeyStore provider,
03-17 08:35:49.194  2595  3177 I FactoryTestApp: [IPCWriterToSecPhoneService$disConnectSecPhoneService](3177)  
03-17 08:35:49.194  3469  3469 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 08:35:49.194  1018  1257 I ActivityManager: Killing 2496:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,03-17 08:35:49.204  1018  1048 I ActivityManager: Displayed Component not be shown by security: +405ms
,03-17 08:35:49.214  3228  3268 I DBG_DM  : [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
03-17 08:35:49.214  1018  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 08:35:49.214  3228  3268 I DBG_DM  : [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
03-17 08:35:49.214  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:49.214  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 08:35:49.214  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,03-17 08:35:49.224  3433  3433 E AffinityControl: AffinityControl: registerfunction enter
,03-17 08:35:49.234  1018  1257 I ActivityManager: Killing 2530:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,03-17 08:35:49.244  1018  1731 D ActivityManager: startProcessLocked calleePkgName: com.fmm.dm, hostingType: broadcast
,03-17 08:35:49.244  1018  1731 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:49.244  1018  1731 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:49.244  1018  1731 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:49.244  1018  1731 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:49.254  3433  3433 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,03-17 08:35:49.254  3290  3377 I DBG_POLICYDM: [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
03-17 08:35:49.254  3290  3377 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
03-17 08:35:49.264  1018  1040 D SensorService: [SO] currT = 40340110659, prevT = 39870101336, diff = 470009323, [0.134 0.421 10.132]
03-17 08:35:49.264  1018  1040 D SensorService: [SO] 0.134 0.421 10.132
03-17 08:35:49.264  1018  1040 D SensorService: [SO] [100 -> 255]
03-17 08:35:49.264  3290  3377 I DBG_POLICYDM: [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
,03-17 08:35:49.274  1018  1143 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-17 08:35:49.274  1018  1143 D PackageManager: START PACKAGE DELETE: observer{76434808}
03-17 08:35:49.274  1018  1143 D PackageManager: pkg{<packageName>}
03-17 08:35:49.274  1018  1143 D PackageManager: user{0}
03-17 08:35:49.274  1018  1143 D PackageManager: caller{2000}
03-17 08:35:49.274  1018  1143 D PackageManager: flags{2}
03-17 08:35:49.274  1018  1143 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-17 08:35:49.274  1018  1143 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-17 08:35:49.274  1018  1143 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-17 08:35:49.274  1018  1143 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,03-17 08:35:49.274  3493  3493 E Zygote  : MountEmulatedStorage()
03-17 08:35:49.274  3493  3493 I libpersona: KNOX_SDCARD checking this for 1000
03-17 08:35:49.274  3493  3493 E Zygote  : v2
03-17 08:35:49.274  3493  3493 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:49.284  3493  3493 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 08:35:49.284  3493  3493 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-17 08:35:49.284  1018  1731 I ActivityManager: Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3493 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 08:35:49.284  3469  3469 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 08:35:49.284  1018  1058 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
03-17 08:35:49.284  1018  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-17 08:35:49.284  1018  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,03-17 08:35:49.284  1018  1058 D ApplicationPolicy: getApplicationUninstallationEnabled
03-17 08:35:49.284  1018  1058 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
03-17 08:35:49.284  3493  3493 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 08:35:49.284  3469  3469 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:49.294  1018  1731 I ActivityManager: Killing 2656:com.android.keychain/1000 (adj 15): empty #31
,03-17 08:35:49.294  1018  1731 I ActivityManager: Killing 2610:com.android.calendar/u0a135 (adj 15): empty #32
,03-17 08:35:49.294  1018  1731 I ActivityManager: Killing 2558:com.samsung.android.securitylogagent/1000 (adj 15): empty #33
,03-17 08:35:49.304  1018  1043 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,03-17 08:35:49.304  1018  1043 W ActivityManager: mDVFSHelper.release()
03-17 08:35:49.304  1018  1043 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-17 08:35:49.314  3493  3493 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:49.314  3493  3493 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:49.334  3350  3432 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-17 08:35:49.344  1018  1058 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
,03-17 08:35:49.354  1018  1043 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
,03-17 08:35:49.354  1018  1043 I ActivityManager: Killing 2896:com.test.thalitest/u0a155 (adj 1): stop com.test.thalitest cause uninstall pkg
,03-17 08:35:49.394  3290  3377 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
,03-17 08:35:49.424  3290  3377 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,03-17 08:35:49.434  3290  3377 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-17 08:35:49.434  3290  3399 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
03-17 08:35:49.434  3290  3377 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
,03-17 08:35:49.434  3357  3357 I com.dropbox.android.service.DropboxNetworkReceiver: Setting receiver enabled: false
,03-17 08:35:49.444  3350  3432 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-17 08:35:49.444  3350  3432 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3616c5ff: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 08:35:49.444  3350  3432 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-17 08:35:49.444  3290  3399 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 08:35:49.444  3290  3377 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
,03-17 08:35:49.454  3290  3399 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-17 08:35:49.464  3290  3377 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/03/18/16:12:11
,03-17 08:35:49.464  3290  3399 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,03-17 08:35:49.464  1018  3512 I WindowState: WIN DEATH: Window{1af6830c u0 com.test.thalitest/com.test.thalitest.MainActivity EXITING}
,03-17 08:35:49.474  3290  3399 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,03-17 08:35:49.474  3290  3377 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/03/17/08:35:49
,03-17 08:35:49.474  3290  3399 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,03-17 08:35:49.474  3290  3377 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
,03-17 08:35:49.474  3290  3399 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,03-17 08:35:49.474  3290  3377 I DBG_POLICYDM: [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
,03-17 08:35:49.474  3290  3399 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
,03-17 08:35:49.484  3290  3399 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,03-17 08:35:49.484  3290  3399 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,03-17 08:35:49.504  3290  3399 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
,03-17 08:35:49.514  3290  3399 I DBG_POLICYDM: [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
,03-17 08:35:49.544  1018  1506 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 08:35:49.554  1018  1506 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:35:49.554  1018  1506 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 08:35:49.554  1018  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 08:35:49.564  1018  1042 W libprocessgroup: failed to open /acct/uid_10142/pid_2496/cgroup.procs: No such file or directory
03-17 08:35:49.564  1018  1042 W libprocessgroup: failed to open /acct/uid_10139/pid_2530/cgroup.procs: No such file or directory
,03-17 08:35:49.564  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_2558/cgroup.procs: No such file or directory
03-17 08:35:49.564  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_2656/cgroup.procs: No such file or directory
,03-17 08:35:49.564  1018  3513 W ActivityManager: Spurious death for ProcessRecord{341d0db7 2896:com.test.thalitest/u0a155}, curProc for 2896: null
,03-17 08:35:49.564  1018  1042 W libprocessgroup: failed to open /acct/uid_10135/pid_2610/cgroup.procs: No such file or directory
,03-17 08:35:49.574  1018  1058 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,03-17 08:35:49.584   293   293 E SMD     : DCD OFF,
,03-17 08:35:49.604  1018  1058 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,03-17 08:35:49.604  3290  3377 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
,03-17 08:35:49.604  1018  1018 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
03-17 08:35:49.604  3493  3493 I DBG_FMMDM: [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,03-17 08:35:49.624   257   983 I SurfaceFlinger: id=11 Removed NainActivit (7/8)
,03-17 08:35:49.624   257   449 I SurfaceFlinger: id=11 Removed NainActivit (-2/8)
,03-17 08:35:49.624  3493  3493 I DBG_FMMDM: [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,03-17 08:35:49.624  3493  3493 I DBG_FMMDM: [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,03-17 08:35:49.624  3493  3493 I DBG_FMMDM: [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,03-17 08:35:49.634  3469  3469 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,03-17 08:35:49.694  1869  2099 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-17 08:35:49.694  3469  3469 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,03-17 08:35:49.694  1906  1906 E SamsungIME: mOCRHelper is null
,03-17 08:35:49.694  3469  3469 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-17 08:35:49.694  3469  3469 D UserAnalysis: Create SecureDbHelper
,03-17 08:35:49.704  1464  1464 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 08:35:49.734  1018  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1272c526 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t11} time:40814
,03-17 08:35:49.734  1018  1130 V NetworkStats: removeUidsLocked() for UIDs [10155]
03-17 08:35:49.734  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
03-17 08:35:49.734  1018  1130 V NetworkStats: performPollLocked(flags=0x3)
,03-17 08:35:49.734  3357  3357 E ActivityThread: Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
,03-17 08:35:49.734  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
03-17 08:35:49.734  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,03-17 08:35:49.744  3469  3469 D IntelligenceServiceApplication: onCreate()
,03-17 08:35:49.744  1018  1130 V NetworkStats: performPollLocked() took 9ms
03-17 08:35:49.744  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 08:35:49.744  1018  1558 D ActivityManager: getContentProviderImpl callerProcessName:com.fmm.dm, calleePkgName: com.sec.pcw.device
,03-17 08:35:49.754  3469  3469 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,03-17 08:35:49.754  1018  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:49.754  1018  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:49.754  1018  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:49.754  1018  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:49.774  3469  3469 D IntelligenceServiceApplication: no applications having user consent for prediction,
,03-17 08:35:49.784  3522  3522 E Zygote  : MountEmulatedStorage()
03-17 08:35:49.784  3522  3522 E Zygote  : v2
03-17 08:35:49.784  3522  3522 I libpersona: KNOX_SDCARD checking this for 1000
03-17 08:35:49.784  3522  3522 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:49.784  3522  3522 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 08:35:49.794  1018  1558 I ActivityManager: Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3522 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 08:35:49.794  3522  3522 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 08:35:49.794  3522  3522 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-17 08:35:49.794  3357  3357 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
,03-17 08:35:49.804  1018  1731 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,03-17 08:35:49.804  3326  3457 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,03-17 08:35:49.814  3469  3469 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,03-17 08:35:49.814  3357  3357 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
,03-17 08:35:49.814  1018  1734 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.backup, hostingType: broadcast
,03-17 08:35:49.814  3357  3357 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
,03-17 08:35:49.824  1018  1734 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:49.824  1018  1734 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:49.824  1018  1734 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:49.824  1018  1734 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:49.834  3357  3357 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
,03-17 08:35:49.834  3522  3522 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:49.834  3522  3522 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:49.844  3290  3377 I DBG_POLICYDM: [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
03-17 08:35:49.844  3538  3538 I libpersona: KNOX_SDCARD checking this for 10060
03-17 08:35:49.844  3538  3538 E Zygote  : MountEmulatedStorage()
03-17 08:35:49.844  3538  3538 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:49.844  3538  3538 E Zygote  : v2
03-17 08:35:49.854  1018  1734 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3538 uid=10060 gids={50060, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-17 08:35:49.854  3538  3538 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 08:35:49.854  3357  3357 D breakpad: breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,03-17 08:35:49.854  3538  3538 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 08:35:49.854  3538  3538 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 08:35:49.874  3469  3469 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,03-17 08:35:49.874  3469  3469 D UserAnalysis.MyPlaceDbPreference: Constructor Preference
,03-17 08:35:49.884  3538  3538 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:49.884  3538  3538 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:49.884  1018  1734 I ActivityManager: Killing 2740:com.android.email/u0a145 (adj 15): empty #31
,03-17 08:35:49.884  1018  1101 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-17 08:35:49.884  1453  1453 D RegisteredComponentCache: Collect Tech packages for Knox
,03-17 08:35:49.894  1018  1131 D NtpTrustedTime: currentTimeMillis() cache hit
03-17 08:35:49.894  1018  1131 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 08:35:49.894  1453  1453 D PersonaManager: isKioskContainerExistOnDevice
,03-17 08:35:49.924  3290  3377 I DBG_POLICYDM: [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-17 08:35:49.934  3290  3399 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-17 08:35:49.954  3290  3399 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,03-17 08:35:49.964  1453  1453 D PersonaManager: isKioskContainerExistOnDevice,
,03-17 08:35:49.964  1018  1030 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
03-17 08:35:49.964  1018  1030 D SecContentProvider2: mCursor = null
03-17 08:35:49.964  1453  1453 D RegisteredServicesCache: empty dynamic service
,03-17 08:35:49.964  3326  3457 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 1048-1049)
,03-17 08:35:49.974  3326  3457 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 08:35:49.974  3522  3522 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
03-17 08:35:49.974  3522  3522 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,03-17 08:35:49.984  3522  3522 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-17 08:35:49.984  3357  3357 I com.dropbox.sync.android.a: Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,03-17 08:35:50.014  3522  3534 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-17 08:35:50.034  1018  1018 D RCPManagerService: PackageReceiver onReceive()
,03-17 08:35:50.034  1018  1018 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,03-17 08:35:50.034  1018  1018 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
03-17 08:35:50.034  1018  1018 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,03-17 08:35:50.034  1018  1018 D OTPFW   : OtpDbHelper::getInstance New instance created
,03-17 08:35:50.044  1018  1018 D OTPFW   : DBIntegrity::getInstance - New instance created
,03-17 08:35:50.044  3493  3493 I DBG_FMMDM: [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,03-17 08:35:50.044  3493  3493 I DBG_FMMDM: [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,03-17 08:35:50.044  3326  3457 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 08:35:50.054  3493  3493 I DBG_FMMDM: [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,03-17 08:35:50.054  1018  1143 D ActivityManager: startProcessLocked calleePkgName: com.fmm.ds, hostingType: broadcast
,03-17 08:35:50.054  1018  1143 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:50.054  1018  1143 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:50.054  1018  1143 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:50.054  1018  1143 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:50.054  1018  1018 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
,03-17 08:35:50.054  1018  1018 I OTPFW   : ProvisionData::getAllEntries Enter
,03-17 08:35:50.054  1018  1018 E OTPFW   : ProvisionData::getAllEntries Table is empty
,03-17 08:35:50.054  1018  1018 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-17 08:35:50.054  1018  1018 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-17 08:35:50.054  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
03-17 08:35:50.054  1018  1018 V EnterpriseBillingPolicy: uID is 10155
03-17 08:35:50.054  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
03-17 08:35:50.054  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-17 08:35:50.064  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-17 08:35:50.064  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-17 08:35:50.064  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-17 08:35:50.064  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-17 08:35:50.064  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-17 08:35:50.064  3326  3457 W TRThreadPoolExecutor: Task "b[Get cookie call]" is a o. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-17 08:35:50.064  1018  1042 D EnterpriseDeviceManagerService: Package has changed for user 0
03-17 08:35:50.064  1018  1042 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
03-17 08:35:50.064  1018  1042 W TextServicesManagerService: no available spell checker services found
,03-17 08:35:50.074  3561  3561 E Zygote  : MountEmulatedStorage()
,03-17 08:35:50.074  3561  3561 E Zygote  : v2
03-17 08:35:50.074  3561  3561 I libpersona: KNOX_SDCARD checking this for 1000
03-17 08:35:50.074  3561  3561 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:50.074  1018  1143 I ActivityManager: Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3561 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-17 08:35:50.074  3561  3561 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 08:35:50.074  1018  1143 I ActivityManager: Killing 1576:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,03-17 08:35:50.074  3561  3561 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 08:35:50.074  1018  1143 I ActivityManager: Killing 2469:com.sec.android.gallery3d/u0a44 (adj 15): empty #32
,03-17 08:35:50.084  3561  3561 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 08:35:50.084  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-17 08:35:50.094  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
03-17 08:35:50.094  1018  1018 V EnterpriseBillingPolicy: uID is 10155
03-17 08:35:50.094  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
03-17 08:35:50.094  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-17 08:35:50.094  1018  2715 D SSRM:aZ : MSG_TYPE_APP_REMOVED::
,03-17 08:35:50.094  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,03-17 08:35:50.104  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-17 08:35:50.104  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-17 08:35:50.104  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-17 08:35:50.104  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-17 08:35:50.104  1018  1018 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
,03-17 08:35:50.144  3561  3561 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:50.154  3561  3561 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:50.194  3538  3538 I sCloudBackupApp: sCloudBackupApp Version Info : 4.04.8.KK_APP
,03-17 08:35:50.194  3357  3357 I com.dropbox.sync.android.ad: Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A500FU armeabi-v7a; en_US))
,03-17 08:35:50.234  2632  2705 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-17 08:35:50.254  1338  3226 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-17 08:35:50.274  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 08:35:50.274  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 08:35:50.274  3561  3561 I DBG_FMMDS: [50.18.150420][Line:56][onCreate] FMMDS Application Start
,03-17 08:35:50.274  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 08:35:50.304  1018  3513 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,03-17 08:35:50.304  1018  3513 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:50.304  1018  3513 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:50.304  1018  3513 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:50.304  1018  3513 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:50.304  3561  3561 I DBG_FMMDS: [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,03-17 08:35:50.314  3582  3582 E Zygote  : MountEmulatedStorage(),
03-17 08:35:50.314  3582  3582 E Zygote  : v2
03-17 08:35:50.314  3582  3582 I libpersona: KNOX_SDCARD checking this for 10062
03-17 08:35:50.314  3582  3582 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:50.314  3582  3582 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 08:35:50.324  3582  3582 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 08:35:50.324  1018  3513 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3582 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 08:35:50.324  3582  3582 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 08:35:50.324  1018  3513 I ActivityManager: Killing 1923:com.android.defcontainer/u0a4 (adj 15): empty #31
,03-17 08:35:50.334  3228  3268 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,03-17 08:35:50.364  1018  1174 D TaskPersister: removeObsoleteFile: deleting file=12_task.xml
,03-17 08:35:50.364  1018  1174 D TaskPersister: removeObsoleteFile: deleting file=12_task_thumbnail.png
,03-17 08:35:50.374  1491  1491 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-17 08:35:50.374  1491  1491 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-17 08:35:50.374  1491  1491 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-17 08:35:50.394  3522  3534 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-17 08:35:50.394  3582  3582 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:50.394  3582  3582 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:50.414  1018  1487 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,03-17 08:35:50.424  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:50.424  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:50.424  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:50.424  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:50.444  1018  1487 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3601 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,03-17 08:35:50.444  3601  3601 E Zygote  : MountEmulatedStorage()
03-17 08:35:50.444  3601  3601 I libpersona: KNOX_SDCARD checking this for 10094
03-17 08:35:50.444  3601  3601 E Zygote  : v2
03-17 08:35:50.444  3601  3601 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:50.444  3601  3601 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 08:35:50.454  3601  3601 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 08:35:50.454  3601  3601 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 08:35:50.474  3601  3601 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:50.474  3601  3601 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:50.474  3561  3561 E DBG_FMMDS: Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,03-17 08:35:50.474  3357  3600 I System.out: Thread-444(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-17 08:35:50.484  3357  3600 I System.out: Thread-444(ApacheHTTPLog):isSBSettingEnabled false
03-17 08:35:50.484  3357  3600 I System.out: Thread-444(ApacheHTTPLog):isShipBuild true
03-17 08:35:50.484  3357  3600 I System.out: Thread-444(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-17 08:35:50.484  3357  3600 I System.out: Thread-444(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-17 08:35:50.484   277   964 D EnterpriseController: uids 10092
03-17 08:35:50.484   277   964 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 08:35:50.484   277   964 D Netd    : getNetworkForDns: using netid 502 for uid 10092
,03-17 08:35:50.494  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 08:35:50.494  3561  3561 I DBG_FMMDS: [50.18.150420][Line:43][xdbDBInit] 
,03-17 08:35:50.514  3350  3511 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 08:35:50.514  3350  3511 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 08:35:50.544  3582  3582 I ExternalOEMControlProvider: onCreate
,03-17 08:35:50.544  3601  3601 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,03-17 08:35:50.544  3601  3601 D elm:15183: ELMEngine.ELMEngine( context ).
,03-17 08:35:50.564  1018  3512 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.servicemodeapp, hostingType: broadcast
,03-17 08:35:50.564  1018  3512 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:50.564  1018  3512 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:50.564  1018  3512 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:50.564  1018  3512 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:50.564  3601  3601 D elm:15183: MDMBridge.setEnterpriseBridge()
,03-17 08:35:50.574  3624  3624 E Zygote  : MountEmulatedStorage()
03-17 08:35:50.574  3624  3624 E Zygote  : v2
,03-17 08:35:50.574  3624  3624 I libpersona: KNOX_SDCARD checking this for 1000
03-17 08:35:50.574  3624  3624 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:50.574  3624  3624 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-17 08:35:50.574  1018  3512 I ActivityManager: Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3624 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 08:35:50.584  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:50.574  1018  1487 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
03-17 08:35:50.584  1018  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:35:50.574  1018  1487 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
03-17 08:35:50.584  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
03-17 08:35:50.584  3624  3624 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 08:35:50.584  3624  3624 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 08:35:50.584  3601  3601 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,03-17 08:35:50.594  1428  1428 V EmergencyMode: [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,03-17 08:35:50.604  3601  3601 D elm:15183: ElmAgentService : onCreate()
,03-17 08:35:50.604  3601  3632 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,03-17 08:35:50.604  3601  3601 D elm:15183: ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
,03-17 08:35:50.604  3601  3601 D elm:15183: BootCompletedState : startBootCompleted() call
,03-17 08:35:50.604  3601  3601 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,03-17 08:35:50.614  1018  1346 D SettingsProvider: name = PREVIOUS_SYS_TIME
,03-17 08:35:50.614  3624  3624 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:50.614  1018  1346 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,03-17 08:35:50.614  1018  1346 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,03-17 08:35:50.614  1018  1346 D SettingsProvider: selectionArgs: false
03-17 08:35:50.614  1018  1346 D SettingsProvider: selectionArgs: 10062
03-17 08:35:50.614  1018  1346 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 08:35:50.614  1018  1346 D SettingsProvider: ret = -1
,03-17 08:35:50.624  3624  3624 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:50.624  3621  3621 I dex2oat : ----------------------------------------------------
03-17 08:35:50.624  3621  3621 I dex2oat : <SS>: S T A R T I N G . . .
03-17 08:35:50.624  3621  3621 I dex2oat : <SS>: Zip is absent. Canceled.
,03-17 08:35:50.624  3621  3621 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-1875001386.jar --oat-fd=31 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads-1875001386.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,03-17 08:35:50.624  3601  3601 I elm:15183: Get License : 0
03-17 08:35:50.624  3601  3601 D elm:15183: ElmAgentService : onDestroy().
,03-17 08:35:50.634  1018  1487 I ActivityManager: Killing 2726:com.samsung.android.sm/1000 (adj 15): empty #31
,03-17 08:35:50.634  1018  1346 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,03-17 08:35:50.644  1018  3515 D SettingsProvider: name = PREVIOUS_ELAPSED_TIME
03-17 08:35:50.644  1018  3515 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 08:35:50.644  1018  3515 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 08:35:50.644  1018  3515 D SettingsProvider: selectionArgs: false
03-17 08:35:50.644  1018  3515 D SettingsProvider: selectionArgs: 10062
03-17 08:35:50.644  1018  3515 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 08:35:50.644  1018  3515 D SettingsProvider: ret = -1
,03-17 08:35:50.654  1192  1192 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 08:35:50.654  1018  3515 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,03-17 08:35:50.664  3624  3624 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 08:35:50.664  1018  1058 I art     : Explicit concurrent mark sweep GC freed 45648(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 30MB/45MB, paused 12.132ms total 1.041s
,03-17 08:35:50.664  1192  1192 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 08:35:50.684  3624  3624 I ServiceMode: received = ACTION_BOOT_COMPLETED
,03-17 08:35:50.684  3624  3624 I ServiceMode: setReferenceIsDumpState : 0
,03-17 08:35:50.704  1018  1731 D ActivityManager: startProcessLocked calleePkgName: com.wssnps, hostingType: broadcast
,03-17 08:35:50.704  1018  1731 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:50.704  1018  1731 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:50.704  1018  1731 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:50.704  1018  1731 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:50.704  1018  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75),
,03-17 08:35:50.714  3350  3350 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,03-17 08:35:50.714  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 08:35:50.724  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 08:35:50.724  3648  3648 E Zygote  : MountEmulatedStorage()
03-17 08:35:50.724  3648  3648 I libpersona: KNOX_SDCARD checking this for 1000
03-17 08:35:50.724  3648  3648 E Zygote  : v2
03-17 08:35:50.724  3648  3648 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:50.724  1018  1731 I ActivityManager: Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3648 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 08:35:50.724  3648  3648 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 08:35:50.724  1018  1731 I ActivityManager: Killing 2858:flipboard.boxer.app/u0a99 (adj 15): empty #31
,03-17 08:35:50.724  3648  3648 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 08:35:50.724  3648  3648 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 08:35:50.734  1428  1428 V EmergencyMode: [EmergencyBase] setBootTime
03-17 08:35:50.734  1428  1428 V EmergencyMode: [EmergencyFactory] No Recovery State, kill my self.
,03-17 08:35:50.734  1018  1487 D ActivityManager: startProcessLocked calleePkgName: com.sec.factory.camera, hostingType: broadcast
,03-17 08:35:50.734  3621  3621 I dex2oat : dex2oat took 113.946ms (threads: 4)
,03-17 08:35:50.744  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:50.744  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:50.744  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:50.744  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:50.754  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 08:35:50.754  3648  3648 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:50.754  3648  3648 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:50.764  3666  3666 E Zygote  : MountEmulatedStorage(),
03-17 08:35:50.764  3666  3666 I libpersona: KNOX_SDCARD checking this for 1000
03-17 08:35:50.764  3666  3666 E Zygote  : v2
03-17 08:35:50.764  3666  3666 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:50.764  3666  3666 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 08:35:50.764  1018  1058 D PackageManager: delete codoeFile: ,
,03-17 08:35:50.764  3666  3666 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 08:35:50.764  1018  1487 I ActivityManager: Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3666 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 08:35:50.764  1018  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 08:35:50.764  1018  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 08:35:50.764  1018  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 08:35:50.774  3666  3666 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 08:35:50.774  1338  3226 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,03-17 08:35:50.784  1338  3226 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
03-17 08:35:50.784  1018  3513 I ActivityManager: Killing 2179:flipboard.app/u0a98 (adj 15): empty #31
,03-17 08:35:50.784  1338  3226 I SettingSearch/SearchIntentReceiver: InitSerachDBThread thread end!
,03-17 08:35:50.794  3666  3666 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 08:35:50.794  3666  3666 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:50.794  3326  3457 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 08:35:50.804   321   321 I art     : Explicit concurrent mark sweep GC freed 8764(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.075ms total 34.794ms
,03-17 08:35:50.824  1018  1058 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
,03-17 08:35:50.824   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 901us total 20.471ms
03-17 08:35:50.824  1018  1058 I AASA_removePackage: UID=10155 Target=com.test.thalitest
,03-17 08:35:50.824  1018  1058 D PackageManager: result of delete: 1{76434808}
,03-17 08:35:50.834  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 08:35:50.844  3561  3561 I DBG_FMMDS: [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,03-17 08:35:50.844   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 866us total 22.932ms
,03-17 08:35:50.854  3350  3350 I System.out: YouTube MDX: MDX video stage moved to NEW
03-17 08:35:50.854  3350  3350 I System.out: YouTube MDX: MDX video player state moved to UNSTARTED
03-17 08:35:50.854  3350  3350 I System.out: YouTube MDX: MDX ad player state moved to UNSTARTED
,03-17 08:35:50.854  3433  3433 D AndroidRuntime: Shutting down VM
,03-17 08:35:50.864  1018  1058 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-17 08:35:50.864  1018  1058 D PackageManager: userId{-1}
03-17 08:35:50.864  1018  1058 D PackageManager: andCode{true}
,03-17 08:35:50.864  1018  1058 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,03-17 08:35:50.874  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:50.874  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:50.874  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:50.874  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:50.884  3561  3561 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W,
03-17 08:35:50.894  3561  3561 I DBG_FMMDS: [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=,
,03-17 08:35:50.894  3693  3693 E Zygote  : MountEmulatedStorage(),
03-17 08:35:50.894  3693  3693 E Zygote  : v2
03-17 08:35:50.894  3693  3693 I libpersona: KNOX_SDCARD checking this for 10004,
,03-17 08:35:50.904  3561  3561 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
03-17 08:35:50.904  3693  3693 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:50.904  3561  3561 I DBG_FMMDS: [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
03-17 08:35:50.904  1018  1058 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=3693 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
03-17 08:35:50.904  3693  3693 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 08:35:50.904  3666  3666 I CameraApp: CameraApp.onCreate()... mFeature : null
03-17 08:35:50.904  3561  3561 I DBG_FMMDS: [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
03-17 08:35:50.904  3666  3666 I testFeature: Feature.Feature(context)
03-17 08:35:50.904  3666  3666 I testFeature: Feature.readInternalDefaultXml()
03-17 08:35:50.904  3561  3561 I DBG_FMMDS: [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
03-17 08:35:50.904  3666  3666 I testFeature: ResetFeatureValue
,03-17 08:35:50.904  3693  3693 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 08:35:50.904  3666  3666 I CameraFirmware_broadcast: CameraFirmwareBroadCastReceiver...
03-17 08:35:50.904  1018  1558 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
03-17 08:35:50.904  3693  3693 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 08:35:50.904  1018  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:50.904  3666  3666 I CameraApp: CameraApp.getAppFeature()...
03-17 08:35:50.904  1018  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:50.904  1018  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:50.904  1018  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:50.934  3709  3709 E Zygote  : MountEmulatedStorage()
03-17 08:35:50.934  3709  3709 E Zygote  : v2
03-17 08:35:50.934  3709  3709 I libpersona: KNOX_SDCARD checking this for 10100
03-17 08:35:50.934  3709  3709 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:50.934  3709  3709 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 08:35:50.934  3709  3709 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 08:35:50.934  3709  3709 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 08:35:50.944  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 08:35:50.944  1018  1558 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3709 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,03-17 08:35:50.944  3693  3693 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:50.944  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 08:35:50.944  3693  3693 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:50.944  1018  1558 I ActivityManager: Killing 2925:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #31
,03-17 08:35:50.954  1018  1558 I ActivityManager: Killing 2059:com.google.android.gms/u0a12 (adj 15): empty #31
,03-17 08:35:50.964  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 08:35:50.964  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 08:35:50.964  1018  1257 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 08:35:50.974  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 08:35:50.974  1018  1257 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:50.974  1018  1257 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 08:35:50.974  1018  1257 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-17 08:35:50.974  1018  1257 W ActivityManager: ProcessRecord{aaec780 2059:com.google.android.gms/u0a12} is already killed
03-17 08:35:50.974  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 08:35:50.974  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
03-17 08:35:50.974   254   254 E lowmemorykiller: Error writing /proc/2059/oom_score_adj; errno=22
,03-17 08:35:50.974  1018  1490 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 08:35:50.974  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 08:35:50.974  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 08:35:50.974  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:35:50.984  1018  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 08:35:50.984  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-17 08:35:50.984  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 08:35:50.984  1018  1042 D UsbSettingsManager: clearDefaults: com.test.thalitest
03-17 08:35:50.984  1018  1042 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,03-17 08:35:50.984  3709  3709 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:50.984  3709  3709 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:50.984  3384  3384 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-17 08:35:50.994  1018  3516 D PowerManagerService: [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1192 (0x0)
,03-17 08:35:51.004  3648  3648 D NPS_WSSNPS: [] android.intent.action.BOOT_COMPLETED
,03-17 08:35:51.004  3648  3648 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,03-17 08:35:51.004  3384  3384 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,03-17 08:35:51.004  3384  3384 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,03-17 08:35:51.004  1018  3515 D ActivityManager: startService callerProcessName:com.wssnps, calleePkgName: com.wssnps
,03-17 08:35:51.004  1018  3515 D ActivityManager: retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,03-17 08:35:51.014  1018  3515 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:51.014  1018  3515 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:35:51.014  1018  3515 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-17 08:35:51.014  3648  3648 D NPS_WSSNPS: [] Service onCreate!!
03-17 08:35:51.014  1018  1506 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,03-17 08:35:51.014  1018  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:51.014  1018  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:51.014  1018  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:51.014  1018  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:51.034  3731  3731 E Zygote  : MountEmulatedStorage()
03-17 08:35:51.034  3731  3731 E Zygote  : v2
03-17 08:35:51.034  3731  3731 I libpersona: KNOX_SDCARD checking this for 1000
03-17 08:35:51.034  3731  3731 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:51.034  3731  3731 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 08:35:51.034  3731  3731 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 08:35:51.034  3731  3731 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 08:35:51.034  1018  1506 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=3731 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 08:35:51.044  1018  1506 I ActivityManager: Killing 2936:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,03-17 08:35:51.054  1018  3516 I ActivityManager: Killing 2375:com.sec.modem.settings/1000 (adj 15): empty #31
03-17 08:35:51.054  3648  3742 D NPS_WSSNPS: [] NpsServiceTask Start
,03-17 08:35:51.054  3731  3731 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:51.054  3731  3731 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:51.064  3433  3433 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-17 08:35:51.074  1018  1042 W libprocessgroup: failed to open /acct/uid_10145/pid_2740/cgroup.procs: No such file or directory
,03-17 08:35:51.074  1018  1042 W libprocessgroup: failed to open /acct/uid_10044/pid_2469/cgroup.procs: No such file or directory
03-17 08:35:51.074  1018  1042 W libprocessgroup: failed to open /acct/uid_10072/pid_1576/cgroup.procs: No such file or directory
,03-17 08:35:51.074  1018  1042 W libprocessgroup: failed to open /acct/uid_10004/pid_1923/cgroup.procs: No such file or directory
,03-17 08:35:51.074  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_2726/cgroup.procs: No such file or directory
03-17 08:35:51.074  1018  1042 W libprocessgroup: failed to open /acct/uid_10099/pid_2858/cgroup.procs: No such file or directory
03-17 08:35:51.074  1018  1042 W libprocessgroup: failed to open /acct/uid_10098/pid_2179/cgroup.procs: No such file or directory
03-17 08:35:51.074  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_2925/cgroup.procs: No such file or directory
03-17 08:35:51.074  1018  1257 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@2e45967d)
03-17 08:35:51.074  1018  1731 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.ads.identifier.service.AdvertisingIdService in 1000ms
03-17 08:35:51.084  1018  1137 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
03-17 08:35:51.084  1018  1137 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-17 08:35:51.084  3709  3709 D PackageIntentReceiver: ACTION_BOOT_COMPLETED
,03-17 08:35:51.084  3648  3648 D NPS_WSSNPS: [50.150621] smlDBHelper
,03-17 08:35:51.084   277   964 D EnterpriseController: uids 10057
03-17 08:35:51.084   277   964 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 08:35:51.084   277   964 D Netd    : getNetworkForDns: using netid 502 for uid 10057
,03-17 08:35:51.084  3731  3731 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 08:35:51.084  3384  3384 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-17 08:35:51.084  1018  1490 D ActivityManager: startProcessLocked calleePkgName: com.google.android.onetimeinitializer, hostingType: broadcast
,03-17 08:35:51.094  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:51.094  3709  3709 D PackageIntentReceiver: jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
03-17 08:35:51.094  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:51.094  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:51.094  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:51.114  3754  3754 E Zygote  : MountEmulatedStorage()
03-17 08:35:51.114  3754  3754 E Zygote  : v2
03-17 08:35:51.114  3754  3754 I libpersona: KNOX_SDCARD checking this for 10014
03-17 08:35:51.114  3754  3754 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:51.114  3754  3754 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 08:35:51.114  1018  1490 I ActivityManager: Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3754 uid=10014 gids={50014, 9997} abi=armeabi-v7a
,03-17 08:35:51.114  1018  1490 I ActivityManager: Killing 3014:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31,
03-17 08:35:51.114  3754  3754 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 08:35:51.124  3754  3754 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 08:35:51.124  1018  1490 D ActivityManager: startProcessLocked calleePkgName: com.google.android.gm, hostingType: broadcast
,03-17 08:35:51.134  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:51.134  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:51.134  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:51.134  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:51.134  1018  1042 W libprocessgroup: failed to open /acct/uid_10012/pid_2059/cgroup.procs: No such file or directory
,03-17 08:35:51.144  3754  3754 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:51.144  3754  3754 D ActivityThread: Added TimaKeyStore provider
03-17 08:35:51.144  3648  3648 I NPS_WSSNPS: [50.150621] AsyncBulkFlagCheck
,03-17 08:35:51.154  3770  3770 E Zygote  : MountEmulatedStorage(),
03-17 08:35:51.154  3770  3770 E Zygote  : v2
,03-17 08:35:51.154  3770  3770 I libpersona: KNOX_SDCARD checking this for 10101
03-17 08:35:51.154  3770  3770 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 08:35:51.154  3770  3770 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:51.154  3770  3770 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 08:35:51.154  3770  3770 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 08:35:51.154  1018  1490 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3770 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 08:35:51.154  1018  1490 I ActivityManager: Killing 2966:com.sec.knox.bridge/1000 (adj 15): empty #31
,03-17 08:35:51.164  3648  3771 I NPS_WSSNPS: [50.150621] IsRemain_AsyncBulkCheck
03-17 08:35:51.164  1018  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 08:35:51.164  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:51.164  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 08:35:51.164  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms,
03-17 08:35:51.164  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:51.164  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:51.164  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:51.164  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:51.184  3770  3770 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:51.184  3770  3770 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:51.184  1018  1042 W libprocessgroup: failed to open /acct/uid_10152/pid_2936/cgroup.procs: No such file or directory,
,03-17 08:35:51.194  3787  3787 E Zygote  : MountEmulatedStorage(),
03-17 08:35:51.194  3787  3787 E Zygote  : v2
03-17 08:35:51.194  3787  3787 I libpersona: KNOX_SDCARD checking this for 10012
03-17 08:35:51.194  3787  3787 I libpersona: KNOX_SDCARD not a persona
03-17 08:35:51.194  3787  3787 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 08:35:51.194  3787  3787 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 08:35:51.194  1018  1031 I ActivityManager: Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=3787 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,03-17 08:35:51.204  3787  3787 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 08:35:51.204  3648  3771 I NPS_WSSNPS: [50.150621] IsRemain_Asyncing nothing
03-17 08:35:51.204  3648  3771 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
03-17 08:35:51.204  2595  2595 D FactoryTestApp: [DummyFtClient$onDestroy](2595) Destroy DummyFtClient service
,03-17 08:35:51.214  1018  1487 D ActivityManager: retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
03-17 08:35:51.214  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:51.214  1018  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:35:51.214  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-17 08:35:51.224  2595  2595 D FactoryTestApp: [Support$Values.getString](2595) id=MODEL_COMMUNICATION_MODE, value=gsm
,03-17 08:35:51.224  2595  2595 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2595) mConnectionMode = gsm
03-17 08:35:51.224  2595  2595 I FactoryTestApp: [ModuleCommon$isRunningFtClient](2595) RUNNING_FTCLIENT : false
,03-17 08:35:51.224  2595  2595 D FactoryTestApp: [DummyFtClient$onDestroy](2595) kill process
03-17 08:35:51.224  2595  2595 I Process : Sending signal. PID: 2595 SIG: 9
,03-17 08:35:51.224  3787  3787 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:51.224  3787  3787 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:51.224  3648  3648 D NPS_WSSNPS: [50.150621] Service onDestroy
,03-17 08:35:51.254  3787  3787 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-17 08:35:51.254  3787  3787 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 08:35:51.264  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_2375/cgroup.procs: No such file or directory
03-17 08:35:51.264  1018  1042 W libprocessgroup: failed to open /acct/uid_1101/pid_3014/cgroup.procs: No such file or directory
03-17 08:35:51.264  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_2966/cgroup.procs: No such file or directory
,03-17 08:35:51.284  1018  3516 I ActivityManager: Process com.sec.factory (pid 2595)(adj 0) has died(157,1101)
,03-17 08:35:51.294  3754  3754 V OneTimeInitializerReceiver: OneTimeInitializerReceiver.onReceive
,03-17 08:35:51.294  1018  1506 D ActivityManager: startService callerProcessName:com.google.android.onetimeinitializer, calleePkgName: com.google.android.onetimeinitializer
,03-17 08:35:51.294  1018  1506 D ActivityManager: retrieveServiceLocked(): component = com.google.android.onetimeinitializer/com.google.android.onetimeinitializer.OneTimeService; callingUser = 0; userId(target) = 0
,03-17 08:35:51.304  1018  1506 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:51.304  1018  1506 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 08:35:51.304  1018  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,03-17 08:35:51.304  3787  3787 I MultiDex: VM with version 2.1.0 has multidex support
03-17 08:35:51.304  3787  3787 I MultiDex: install
03-17 08:35:51.304  3787  3787 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-17 08:35:51.314  3648  3648 I NPS_WSSNPS: [50.150621] smlBRConfigurationDelete
,03-17 08:35:51.314  3648  3648 I NPS_WSSNPS: [50.150621] smlBRMessageDelete
,03-17 08:35:51.314  3648  3648 I NPS_WSSNPS: [50.150621] smlBREmailDelete
,03-17 08:35:51.314  3648  3648 I NPS_WSSNPS: [50.150621] smlBRNetworkDelete
03-17 08:35:51.314  3648  3648 I NPS_WSSNPS: [50.150621] smlBRCallLogDelete
,03-17 08:35:51.314  3648  3648 I NPS_WSSNPS: [50.150621] smlBRMiniDiaryDelete
,03-17 08:35:51.314  3648  3648 I NPS_WSSNPS: [50.150621] smlBRPenMemoMDelete
03-17 08:35:51.314  3648  3648 I NPS_WSSNPS: [50.150621] smlBRSMemoDelete
,03-17 08:35:51.314  3648  3648 I NPS_WSSNPS: [50.150621] verifier installed? false
03-17 08:35:51.314  3648  3648 I NPS_WSSNPS: [50.150621] cpuBooster release : false
,03-17 08:35:51.314  3754  3802 V OneTimeService: OneTimeService.onHandleIntent
,03-17 08:35:51.324  3648  3648 D NPS_WSSNPS: [50.150621] dsServerSocket close
,03-17 08:35:51.324  1018  1257 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,03-17 08:35:51.324  1018  1257 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.ClientIdService; callingUser = 0; userId(target) = 0
,03-17 08:35:51.324  1018  1257 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:51.324  1018  1257 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 08:35:51.324  1018  1257 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 08:35:51.334  1018  1558 I ActivityManager: Killing 2342:com.android.mms/u0a46 (adj 15): empty #31
,03-17 08:35:51.334  1018  1143 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
03-17 08:35:51.334  1018  1143 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppHiderService; callingUser = 0; userId(target) = 0
,03-17 08:35:51.334  1018  1143 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:35:51.334  1018  1143 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 08:35:51.334  1018  1143 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 08:35:51.344  1018  3515 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
03-17 08:35:51.344  1018  3515 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccFallbackService; callingUser = 0; userId(target) = 0
,03-17 08:35:51.344  3228  3268 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
03-17 08:35:51.344  1018  3515 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:51.344  1018  3515 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 08:35:51.344  1018  3515 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 08:35:51.344  1018  1734 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,03-17 08:35:51.344  1018  1734 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccOverrideService; callingUser = 0; userId(target) = 0
,03-17 08:35:51.344  1018  1734 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:35:51.344  1018  1734 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 08:35:51.344  1018  1734 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 08:35:51.344  1018  1030 D ActivityManager: bindService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube, action: null
,03-17 08:35:51.344  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,03-17 08:35:51.354  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:51.354  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 08:35:51.354  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 08:35:51.374  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,03-17 08:35:51.374  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,03-17 08:35:51.374  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 08:35:51.374  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 08:35:51.374  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 08:35:51.374  1018  3513 D ActivityManager: startProcessLocked calleePkgName: com.samsung.hs20settings, hostingType: broadcast
,03-17 08:35:51.374  1018  3513 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:51.374  1018  3513 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-17 08:35:51.374  1018  3513 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:51.374  1018  3513 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:51.394  3811  3811 E Zygote  : MountEmulatedStorage()
03-17 08:35:51.394  3811  3811 E Zygote  : v2
03-17 08:35:51.394  3811  3811 I libpersona: KNOX_SDCARD checking this for 1000
03-17 08:35:51.394  3811  3811 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:51.394  1018  1346 D CountryDetector: No listener is left
,03-17 08:35:51.394  1018  3513 I ActivityManager: Start proc com.samsung.hs20settings for broadcast com.samsung.hs20settings/.WifiHs20BroadcastReceiver: pid=3811 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 08:35:51.404  1018  1042 W libprocessgroup: failed to open /acct/uid_10046/pid_2342/cgroup.procs: No such file or directory
,03-17 08:35:51.464  3811  3811 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 08:35:51.464  3811  3811 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 08:35:51.464  3811  3811 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 08:35:51.464   256   540 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-17 08:35:51.464   256   540 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 08:35:51.474  3350  3350 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-17 08:35:51.484  3787  3787 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-17 08:35:51.494  3811  3811 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:51.494  3811  3811 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:51.564  1018  1346 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
03-17 08:35:51.564  1018  1346 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-17 08:35:51.564  1018  1346 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:51.564  1018  1346 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 08:35:51.564  1018  1346 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
03-17 08:35:51.564  3787  3787 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-17 08:35:51.564  3787  3787 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@9a1453d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 08:35:51.564  3787  3787 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-17 08:35:51.574  3811  3811 I Hs20UtilService: onCreate
,03-17 08:35:51.584  1018  1257 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
03-17 08:35:51.584  1018  1257 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingService; callingUser = 0; userId(target) = 0
,03-17 08:35:51.584  1018  1257 W ActivityManager: userId = 0, bbcId = -10000
03-17 08:35:51.584  1018  1257 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 08:35:51.584  1018  1257 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 08:35:51.584  1018  3510 D ActivityManager: startProcessLocked calleePkgName: com.samsung.klmsagent, hostingType: broadcast
,03-17 08:35:51.584  1018  3510 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:51.584  1018  3510 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:51.584  1018  3510 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 08:35:51.584  1018  3510 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 08:35:51.594  3811  3811 I Hs20UtilService: Starting #1
,03-17 08:35:51.594  3811  3835 I Hs20UtilService: Message received 5003
,03-17 08:35:51.604  3840  3840 E Zygote  : MountEmulatedStorage()
03-17 08:35:51.604  3840  3840 E Zygote  : v2
03-17 08:35:51.604  3840  3840 I libpersona: KNOX_SDCARD checking this for 10019
03-17 08:35:51.604  3840  3840 I libpersona: KNOX_SDCARD not a persona
,03-17 08:35:51.604  3840  3840 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 08:35:51.604  1018  3510 I ActivityManager: Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3840 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-17 08:35:51.614  3840  3840 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 08:35:51.614  3840  3840 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 08:35:51.634  3413  3413 I RlzPingService: Setting next ping for 1458804951635
,03-17 08:35:51.644  3840  3840 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 08:35:51.644  3840  3840 D ActivityThread: Added TimaKeyStore provider
,03-17 08:35:51.674  3413  3857 W FileUtils: Failed to chmod(/data/user/0/com.google.android.partnersetup/shared_prefs/RLZ.xml): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,03-17 08:35:51.684  1018  3512 I ActivityManager: Killing 3040:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
,03-17 08:35:51.694  2578  3204 W FileUtils: Failed to chmod(/data/data/com.sec.android.app.sysscope/databases/SysScope.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,03-17 08:35:51.694  2578  3204 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,03-17 08:35:51.694  2578  3204 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-17 08:35:51.694  2578  3204 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 08:35:51.694  2578  3204 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-17 08:35:51.704  3787  3860 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/reminders.db" with flag (131138) and mode_t (0) due to error (30)
,03-17 08:35:51.704  2578  3204 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,03-17 08:35:51.704  2578  3204 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-17 08:35:51.704  2578  3204 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 08:35:51.704  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 08:35:51.704  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 08:35:51.704  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 08:35:51.704  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 08:35:51.704  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 08:35:51.704  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 08:35:51.704  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 08:35:51.704  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 08:35:51.704  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 08:35:51.704  2578  3204 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 08:35:51.704  2578  3204 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 08:35:51.704  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 08:35:51.704  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 08:35:51.704  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-17 08:35:51.704  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-17 08:35:51.704  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-17 08:35:51.704  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 08:35:51.704  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 08:35:51.704  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-17 08:35:51.704  2578  3204 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 08:35:51.704  2578  3204 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 08:35:51.704  2578  3204 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 08:35:51.704  2578  3204 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-17 08:35:51.714  3787  3860 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/reminders.db'.
03-17 08:35:51.714  3787  3860 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 08:35:51.714  3787  3860 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 08:35:51.714  3787  3860 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 08:35:51.714  3787  3860 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 08:35:51.714  3787  3860 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 08:35:51.714  3787  3860 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 08:35:51.714  3787  3860 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 08:35:51.714  3787  3860 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 08:35:51.714  3787  3860 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 08:35:51.714  3787  3860 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 08:35:51.714  3787  3860 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 08:35:51.714  3787  3860 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 08:35:51.714  3787  3860 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 08:35:51.714  3787  3860 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-17 08:35:51.714  3787  3860 E SQLiteDatabase: 	at com.google.android.gms.reminders.provider.RemindersProvider.query(:com.google.android.gms:422)
03-17 08:35:51.714  3787  3860 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:993)
03-17 08:35:51.714  3787  3860 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
03-17 08:35:51.714  3787  3860 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:489)
03-17 08:35:51.714  3787  3860 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:433)
03-17 08:35:51.714  3787  3860 E SQLiteDatabase: 	at com.google.android.gms.reminders.a.a.a(:com.google.android.gms:66)
03-17 08:35:51.714  3787  3860 E SQLiteDatabase: 	at com.google.android.gms.reminders.a.c.doInBackground(:com.google.android.gms:45)
03-17 08:35:51.714  3787  3860 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
03-17 08:35:51.714  3787  3860 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 08:35:51.714  3787  3860 E SQLiteDatabase: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-17 08:35:51.714  3787  3860 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 08:35:51.714  3787  3860 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 08:35:51.714  3787  3860 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-17 08:35:51.714  3787  3860 E SQLiteOpenHelper: Couldn't open reminders.db for writing (will try read-only):
03-17 08:35:51.714  3787  3860 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 08:35:51.714  3787  3860 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 08:35:51.714  3787  3860 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 08:35:51.714  3787  3860 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 08:35:51.714  3787  3860 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 08:35:51.714  3787  3860 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 08:35:51.714  3787  3860 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 08:35:51.714  3787  3860 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 08:35:51.714  3787  3860 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 08:35:51.714  3787  3860 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 08:35:51.714  3787  3860 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 08:35:51.714  3787  3860 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 08:35:51.714  3787  3860 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 08:35:51.714  3787  3860 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-17 08:35:51.714  3787  3860 E SQLiteOpenHelper: 	at com.google.android.gms.reminders.provider.RemindersProvider.query(:com.google.android.gms:422)
03-17 08:35:51.714  3787  3860 E SQLiteOpenHelper: 	at android.content.ContentProvider.query(ContentProvider.java:993)
03-17 08:35:51.714  3787  3860 E SQLiteOpenHelper: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
03-17 08:35:51.714  3787  3860 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:489)
03-17 08:35:51.714  3787  3860 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:433)
03-17 08:35:51.714  3787  3860 E SQLiteOpenHelper: 	at com.google.android.gms.reminders.a.a.a(:com.google.android.gms:66)
03-17 08:35:51.714  3787  3860 E SQLiteOpenHelper: 	at com.google.android.gms.reminders.a.c.doInBackground(:com.google.android.gms:45)
03-17 08:35:51.714  3787  3860 E SQLiteOpenHelper: 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
03-17 08:35:51.714  3787  3860 E SQLiteOpenHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 08:35:51.714  3787  3860 E SQLiteOpenHelper: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-17 08:35:51.714  3787  3860 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 08:35:51.714  3787  3860 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 08:35:51.714  3787  3860 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
03-17 08:35:51.714  3787  3860 W SQLiteOpenHelper: Opened reminders.db in read-only mode
03-17 08:35:51.734  2578  3204 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-17 08:35:51.734  2578  3204 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 08:35:51.734  2578  3204 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-17 08:35:51.744  2578  3204 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-17 08:35:51.744  2578  3204 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,03-17 08:35:51.744  3787  3862 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/plus.db" with flag (131138) and mode_t (0) due to error (30)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 08:35:51.744  2578  3204 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-17 08:35:51.754  3357  3600 I System.out: pool-10-thread-1 calls detatch()
03-17 08:35:51.764  2578  3204 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-17 08:35:51.764  2578  3204 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-17 08:35:51.764  3840  3840 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 17 08:35:51 GMT+01:00 2016
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 08:35:51.764  2578  3204 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-17 08:35:51.764  1018  1487 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
03-17 08:35:51.764  1018  1487 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0

```
