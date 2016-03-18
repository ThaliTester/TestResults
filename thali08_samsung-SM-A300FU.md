#### Test 63377149f0d5e10_thali08_samsung-SM-A300FU Logs


```
--------- beginning of main
03-18 15:47:51.488  2660  2660 I Avrcp   :  Updating now playing list upon AVRCP Start
03-18 15:47:51.498  2660  2804 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
03-18 15:47:51.498  1019  1041 D SensorService: [SO] Reset Rotation Old [100], Init [1]
03-18 15:47:51.498  2660  2660 I BluetoothA2dpServiceJni: classInitNative: succeeds
03-18 15:47:51.498  2660  2660 D A2dpStateMachine: make
03-18 15:47:51.498  2660  2660 I bluedroid: get_profile_interface a2dp
03-18 15:47:51.498  2660  2810 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
03-18 15:47:51.498  2660  2660 E bt-btif : warning : media task started media_task_refcnt 1 
03-18 15:47:51.498  2660  2660 D A2dpService: mStartError = false
03-18 15:47:51.498  2660  2660 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@311782de
03-18 15:47:51.498  2660  2809 D A2dpStateMachine: Enter Disconnected: -2
03-18 15:47:51.498  2660  2660 I BluetoothHidServiceJni: classInitNative: succeeds
03-18 15:47:51.508  2660  2660 D HidService: Received start request. Starting profile...
03-18 15:47:51.508  2660  2660 D HidService: start()
03-18 15:47:51.508  2660  2660 I bluedroid: get_profile_interface hidhost
03-18 15:47:51.508  2660  2660 D HidService: setHidService(): set to: null
03-18 15:47:51.508  2660  2660 D HidService: mStartError = false
03-18 15:47:51.508  2660  2660 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@311782de
03-18 15:47:51.508  2660  2660 E BluetoothAdapterService(823624414): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
03-18 15:47:51.508  2660  2660 I BluetoothHealthServiceJni: classInitNative: succeeds
03-18 15:47:51.508  2660  2660 D HealthService: Received start request. Starting profile...
03-18 15:47:51.508  2660  2660 D HealthService: start()
03-18 15:47:51.508  2660  2660 I bluedroid: get_profile_interface health
03-18 15:47:51.508  2660  2660 D HealthService: mStartError = false
03-18 15:47:51.508  2660  2660 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@311782de
03-18 15:47:51.508  2660  2660 I BluetoothPanServiceJni: classInitNative(L105): succeeds
--------- beginning of system
03-18 15:47:51.508  1019  1043 W libprocessgroup: failed to open /acct/uid_10092/pid_1425/cgroup.procs: No such file or directory
03-18 15:47:51.518  2660  2804 D BluetoothMediaBrowser: no now playing list
03-18 15:47:51.518  2660  2804 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
03-18 15:47:51.518  2660  2660 D PanService: Received start request. Starting profile...
03-18 15:47:51.518  2660  2660 D PanService: start()
03-18 15:47:51.518  2660  2660 D BluetoothPanServiceJni: initializeNative(L110): pan
03-18 15:47:51.518  2660  2660 I bluedroid: get_profile_interface pan
03-18 15:47:51.518  2660  2660 D PanService: mStartError = false
03-18 15:47:51.518  2660  2660 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@311782de
03-18 15:47:51.518  2660  2660 D BluetoothMapService: Received start request. Starting profile...
03-18 15:47:51.518  2660  2660 D BluetoothMapService: start()
03-18 15:47:51.528  2660  2660 D BluetoothMapService: mStartError = false
03-18 15:47:51.528  2660  2660 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@311782de
03-18 15:47:51.528  2660  2660 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
03-18 15:47:51.538  1019  1019 D BluetoothPan: BluetoothPAN Proxy object connected
03-18 15:47:51.538  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:51.538  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:51.538  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
03-18 15:47:51.548  2660  2660 D SapService: Received start request. Starting profile...
03-18 15:47:51.548  2660  2660 D SapService: start()
03-18 15:47:51.548  2660  2660 D BluetoothSAPServiceJni: initializeNative(L209): sap
03-18 15:47:51.548  2660  2660 I bluedroid: get_profile_interface sap
03-18 15:47:51.548  2660  2660 D SapService: mStartError = false
03-18 15:47:51.548  2660  2660 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@311782de
03-18 15:47:51.548  2660  2660 D HeadsetStateMachine: Proxy object connected
03-18 15:47:51.548  2660  2660 D HeadsetStateMachine: Try to query the phonestate on bind
03-18 15:47:51.548  1019  1019 W PhoneRestrictionPolicy: Message received - msg { when=-2ms what=2 target=com.android.server.enterprise.restriction.PhoneRestrictionPolicy$SmsMmsDeliveryHandler }
03-18 15:47:51.548  1019  1019 D KnoxMUMContainerPolicy: mContainerReceiver : action - android.intent.action.BOOT_COMPLETED
03-18 15:47:51.548  1458  1468 I Telecom : BluetoothPhoneService: queryPhoneState
03-18 15:47:51.548  1458  1458 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
03-18 15:47:51.548  1458  1458 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
03-18 15:47:51.548  1458  1458 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
03-18 15:47:51.548  1458  1458 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
03-18 15:47:51.558  1019  2814 W PhoneRestrictionPolicy:  >>>> deliveryBlockedMsgs
03-18 15:47:51.558  1019  1019 I KnoxMUMContainerPolicy: MSG_REMOVE_ORPHANED_CONTAINERS received
03-18 15:47:51.558  1458  1458 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
03-18 15:47:51.568  1019  1130 D WifiP2pService: InactiveState{ what=143415 }
03-18 15:47:51.578  1019  2814 W PhoneRestrictionPolicy: cvList size 0
03-18 15:47:51.578  1019  2814 W PhoneRestrictionPolicy:  >>>> deliveryBlockedMsgs
03-18 15:47:51.578  1019  1019 D Tethering: Boot complete.
03-18 15:47:51.578  1019  2814 W PhoneRestrictionPolicy: cvList size 0
03-18 15:47:51.578  1458  1458 W BluetoothHeadset: Proxy not attached to service
03-18 15:47:51.578  1019  1019 V EnterpriseBillingEngine: ACTION_BOOT_COMPLETED
03-18 15:47:51.578  2660  2660 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
03-18 15:47:51.578  2660  2660 D HeadsetPhoneState: sendDeviceDataStateChanged
03-18 15:47:51.578  2660  2660 D HeadsetPhoneState: Signal level : previous=0 curr=0
03-18 15:47:51.578  2660  2660 E BluetoothAdapterService(823624414): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
03-18 15:47:51.578  2660  2660 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-18 15:47:51.578  2660  2660 D BluetoothA2dp: Proxy object connected
03-18 15:47:51.578  2660  2660 D BluetoothAdapterService: Bluetooth A2dp source service connected
03-18 15:47:51.578  2660  2660 E BluetoothAdapterService(823624414): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
03-18 15:47:51.578  2660  2660 E BluetoothAdapterService(823624414): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
03-18 15:47:51.578  2660  2660 E BluetoothAdapterService(823624414): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
03-18 15:47:51.578  2660  2796 D HeadsetStateMachine: Disconnected process message: 11
03-18 15:47:51.578  2660  2796 D HeadsetStateMachine: Disconnected process message: 18
03-18 15:47:51.578  2660  2796 D HeadsetStateMachine: Disconnected process message: 10
03-18 15:47:51.578  1019  1130 D WifiP2pService: P2pEnabledState{ what=143415 }
03-18 15:47:51.578  1019  1130 D WifiP2pService: DefaultState{ what=143415 }
03-18 15:47:51.578  1019  1133 D ConnectivityService: Got NetworkFactory Messenger for WIFI
,03-18 15:47:51.578  1458  1468 I Telecom : BluetoothPhoneService: Result of Message : true
03-18 15:47:51.588  1019  1131 E WifiStateMachine: Blacklist file delete
03-18 15:47:51.588  2660  2796 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
03-18 15:47:51.588  2660  2796 D HeadsetStateMachine: Disconnected process message: 11
03-18 15:47:51.588  2660  2660 E BluetoothAdapterService(823624414): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
03-18 15:47:51.598  1019  1133 D ConnectivityService: Got NetworkFactory Messenger for WIFI_P2P
03-18 15:47:51.598  1019  1130 D WIFI_P2P: got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
03-18 15:47:51.598  1019  1130 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
03-18 15:47:51.628  1019  1019 V EnterpriseBillingEngine: handleAllprofiles - start
03-18 15:47:51.628  1019  1019 V EnterpriseBillingPolicyStorage: getCurrentActiveProfiles - start - 
03-18 15:47:51.628  2003  2003 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-18 15:47:51.638  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:51.638  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:51.638  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:51.638  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:51.638   292   292 E SMD     : DCD OFF
03-18 15:47:51.648  1019  1019 V EnterpriseBillingPolicyStorage: getCurrentActiveProfiles - end - null
03-18 15:47:51.648  1019  1019 V EnterpriseBillingEngine: handleAllprofiles - end
03-18 15:47:51.648  2003  2003 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-18 15:47:51.648  2820  2820 E Zygote  : MountEmulatedStorage()
03-18 15:47:51.648  2820  2820 I libpersona: KNOX_SDCARD checking this for 10141
03-18 15:47:51.648  2820  2820 E Zygote  : v2
03-18 15:47:51.648  2820  2820 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:51.648  2820  2820 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-18 15:47:51.648  1019  1490 I ActivityManager: Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=2820 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
03-18 15:47:51.648  2820  2820 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-18 15:47:51.658  2820  2820 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-18 15:47:51.678   300   300 E USB_UICC: Timeout! No signal received. Retry num = 28
03-18 15:47:51.678  1019  1019 D UsbHostNotification: boot completed
03-18 15:47:51.688   329   329 I ServiceManager: Waiting for service AtCmdFwd...
03-18 15:47:51.688  2820  2820 D TimaKeyStoreProvider: TimaSignature is unavailable
03-18 15:47:51.688  1019  1470 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:51.688  1019  1470 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:51.688  2820  2820 D ActivityThread: Added TimaKeyStore provider
03-18 15:47:51.688  1019  1470 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
03-18 15:47:51.688  1019  1212 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:51.698  1019  1212 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:51.698  1019  1212 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
03-18 15:47:51.698  1019  1041 D SensorService: [SO] currT = 34161101000, prevT = 33691195000, diff = 469906000, [-0.460 0.211 9.883]
03-18 15:47:51.698  1019  1041 D SensorService: [SO] -0.460 0.211 9.883
03-18 15:47:51.698  1019  1041 D SensorService: [SO] [100 -> 255]
03-18 15:47:51.698  1019  1019 D UsbHostRestrictor: mBootCompletedReceiver onReceive
03-18 15:47:51.698  1019  1019 D UsbHostRestrictor: initSetUsbBlock STARTED
03-18 15:47:51.708  1019  1019 D UsbHostRestrictor: SIM was never inserted
03-18 15:47:51.708  1019  1019 D UsbHostRestrictor: writableHostSysNode[false]
03-18 15:47:51.708  1019  1019 D UsbHostRestrictor: Can NOT Write Disable Sys Node to [ON]
03-18 15:47:51.708  1019  1131 D WIFI    : got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
03-18 15:47:51.708  1019  1131 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
03-18 15:47:51.718  2820  2820 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-18 15:47:51.728  1019  1019 D PersonaManagerService: ACTION_BOOT_COMPLETED
03-18 15:47:51.728  2820  2820 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-18 15:47:51.728  2820  2820 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-18 15:47:51.728  2820  2820 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-18 15:47:51.728  1019  1063 E PersonaManagerServiceHandler:  MSG_BOOT_COMPLETE_RECEIVED : soft start personas 
03-18 15:47:51.728  1019  1019 D UsbStorageNotification: boot completed
03-18 15:47:51.728  1188  1188 D StorageNotification: boot completed
03-18 15:47:51.738  1019  1043 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.BOOT_COMPLETED
03-18 15:47:51.738  1019  1043 D GpsLocationProvider_ex: BOOT_COMPLETED native_init 
03-18 15:47:51.788  1849  1849 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
03-18 15:47:51.788  1849  1849 I dhcpcd  : wlan0: no IPv6 Routers available
03-18 15:47:51.788  2158  2761 W DriveInitializer: Awaiting to be initialized
03-18 15:47:51.788  1019  1063 D KnoxKeyguardUpdateMonitor: onBootComplete
03-18 15:47:51.788  1019  1019 I KnoxKeyguardUpdateMonitor: onTrustManagedChanged user 0, managed:false
03-18 15:47:51.788  1019  1019 I KnoxKeyguardUpdateMonitor: onTrustChanged user:0, enable:false
03-18 15:47:51.788  2158  2841 W DriveInitializer: Background init thread started
03-18 15:47:51.788  1019  1063 D PersonaManagerService: getPersonasForUser(): returning null!
03-18 15:47:51.888  1019  1467 D RCPManagerService: exchangeData() failure , invalid userId
03-18 15:47:51.898  1188  1188 D KeyguardViewMediator: onTrustChanged( Showing = false , userId = 0 )
03-18 15:47:51.898  1019  1043 D GpsLocationProvider: set_capabilities_callback: 55u
03-18 15:47:51.918  1019  2842 E LocSvc_api_v02: I/locClientOpen:2279]: Service instance id is -1
03-18 15:47:51.918  1019  1079 D RCPManagerService: exchangeData() failure , invalid userId
03-18 15:47:51.938  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:51.938  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:51.938  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-18 15:47:51.988  1019  2766 D SSRM:a  : DeviceInfo:: 000000000000
03-18 15:47:51.988  1019  2766 D SSRM:a  : SettingsAirViewInfo:: 000000000
03-18 15:47:52.028  1019  1043 E Geofence_Adapter: I/===> void GeofenceAdapter::addGfClients(GeoFencer*) line 65 
03-18 15:47:52.028  1019  1043 E Geofence_Adapter: I/===> void GeofenceAdapter::updateRegisteredEvents() line 81 
03-18 15:47:52.028  1019  1043 D GpsLocationProvider_ex: BOOT_COMPLETED native_cleanup 
03-18 15:47:52.028  1019  1563 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:52.028  1019  1563 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:52.028  1019  1563 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-18 15:47:52.048  1019  1464 D StatusBarManagerService: setIcon slot=volume index=23 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
03-18 15:47:52.048  1188  1188 D PhoneStatusBar: updateIcon slot=volume index=23 viewIndex=5 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
03-18 15:47:52.058  1019  1467 D RCPManagerService: exchangeData() failure , invalid userId
03-18 15:47:52.058   257   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
03-18 15:47:52.058   257   522 W Vold    : Returning OperationFailed - no handler for errno 0
03-18 15:47:52.058  2158  2841 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
03-18 15:47:52.058  1019  1563 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:52.058  1019  1563 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:52.058  1019  1563 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:52.058  1019  1563 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:52.078  2852  2852 E Zygote  : MountEmulatedStorage()
03-18 15:47:52.078  2852  2852 E Zygote  : v2
03-18 15:47:52.078  2852  2852 I libpersona: KNOX_SDCARD checking this for 1000
03-18 15:47:52.078  2852  2852 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:52.078  2852  2852 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-18 15:47:52.078  1019  1563 I ActivityManager: Start proc com.mobeam.barcodeService for broadcast com.mobeam.barcodeService/.system.AppBroadcastReceiver: pid=2852 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-18 15:47:52.078  2852  2852 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-18 15:47:52.078  2852  2852 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-18 15:47:52.088  1019  1490 D RCPManagerService: exchangeData() failure , invalid userId
03-18 15:47:52.108  1019  2847 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PREMIUM_SERVICES_CONFIG_REQ_V02
03-18 15:47:52.118  1019  2847 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PREMIUM_SERVICES_CONFIG_REQ_V02
03-18 15:47:52.118  1019  2842 D qmi_secgps_clnt: qmi_secgps_client_init()
03-18 15:47:52.118  2852  2852 D TimaKeyStoreProvider: TimaSignature is unavailable
03-18 15:47:52.118  2852  2852 D ActivityThread: Added TimaKeyStore provider
03-18 15:47:52.128  2660  2660 E BluetoothAdapterService(823624414): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
03-18 15:47:52.128  2660  2660 E BluetoothAdapterService(823624414): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
03-18 15:47:52.138  2660  2736 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
03-18 15:47:52.138  2660  2736 I bluedroid: enable
03-18 15:47:52.148  1019  2842 D qmi_secgps_clnt: SECGPS: qmi_client_get_service_list() returned 0 num_services = 2
03-18 15:47:52.148  1019  2842 D qmi_secgps_clnt: SECGPS: qmi_client_get_service_list() returned 0 num_entries = 0 num_services = 2
03-18 15:47:52.158  2660  2736 I bt_hci_bdroid: init
03-18 15:47:52.158  2660  2876 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
03-18 15:47:52.158  1019  2842 D qmi_secgps_clnt: SECGPS: qmi_client_get_service_list() returned 0 num_entries = 2 num_services = 2
03-18 15:47:52.178  1659  1680 I art     : Explicit concurrent mark sweep GC freed 3160(129KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 756us total 33.203ms
03-18 15:47:52.188  2660  2736 I bt_vendor: bt-vendor : init
03-18 15:47:52.188  2660  2736 I bt_vendor: bt-vendor : get_bt_soc_type
03-18 15:47:52.188  2660  2736 E bt_vendor: get_bt_soc_type: Failed to get soc type
03-18 15:47:52.188  2660  2736 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
03-18 15:47:52.188  2660  2736 D bt_userial_mct: userial_init
03-18 15:47:52.198  2660  2736 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
03-18 15:47:52.198  2660  2736 I bt_vendor: Starting hciattach daemon
03-18 15:47:52.198  2660  2736 I bt_vendor: try to set false
03-18 15:47:52.198  2660  2736 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
03-18 15:47:52.198  2660  2736 I bt_vendor: Starting hciattach daemon
03-18 15:47:52.198  2660  2736 I bt_vendor: try to set true
03-18 15:47:52.208  2852  2852 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.mobeam.barcodeService.system.AppBroadcastReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
03-18 15:47:52.208  1019  1563 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:52.208  1019  1563 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:52.208  1019  1563 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.mobeam.barcodeService, destAppInfo.processName = com.mobeam.barcodeService
03-18 15:47:52.208  1019  1509 I splitIntent: Split this intent : android.intent.action.BOOT_COMPLETED, mSplitNum[0]=87, mSplitNum[1]=126, mSplitNum[2]=164, mBgSplitQueueNum=3 divideNum= 37 r.nextReceiver= 50 receivers.size=201
03-18 15:47:52.208  1019  1509 I splitIntent: finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!
03-18 15:47:52.218  1608  1619 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
03-18 15:47:52.218  1019  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:52.218  1019  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:52.218  1019  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:52.218  1019  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:52.228  1019  1509 I ActivityManager: Start proc flipboard.boxer.app for broadcast flipboard.boxer.app/flipboard.boxer.receiver.BootCompleted: pid=2885 uid=10097 gids={50097, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-18 15:47:52.238  2885  2885 E Zygote  : MountEmulatedStorage()
03-18 15:47:52.238  2885  2885 I libpersona: KNOX_SDCARD checking this for 10097
03-18 15:47:52.238  2885  2885 E Zygote  : v2
03-18 15:47:52.238  2885  2885 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:52.238  2885  2885 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-18 15:47:52.238  2885  2885 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-18 15:47:52.238  2885  2885 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-18 15:47:52.248  2884  2884 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
03-18 15:47:52.248  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:52.248  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:52.248  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:52.248  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:52.258  1019  1561 D RCPManagerService: exchangeData() failure , invalid userId
03-18 15:47:52.268  1019  2842 E LocSvc_utils_cfg: W/loc_read_sec_gps_conf: no secgps conf file, using defaults
03-18 15:47:52.268  1019  2847 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
03-18 15:47:52.278  1019  2847 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
03-18 15:47:52.278  1019  1044 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=2904 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-18 15:47:52.278  2885  2885 D TimaKeyStoreProvider: TimaSignature is unavailable
03-18 15:47:52.278  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:52.278  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:52.288  2885  2885 D ActivityThread: Added TimaKeyStore provider
03-18 15:47:52.278  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:52.288  1019  2847 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SERVER_REQ_V02
03-18 15:47:52.278  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:52.288  2904  2904 E Zygote  : MountEmulatedStorage()
03-18 15:47:52.288  2904  2904 E Zygote  : v2
03-18 15:47:52.288  2904  2904 I libpersona: KNOX_SDCARD checking this for 10081
03-18 15:47:52.288  1019  2842 I qmi_secgps_clnt: SECGPS: Set AGPS Mode : 7
03-18 15:47:52.288  2904  2904 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:52.288  2904  2904 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-18 15:47:52.288  2904  2904 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-18 15:47:52.288  2904  2904 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-18 15:47:52.298  1019  1561 D RCPManagerService: exchangeData() failure , invalid userId
03-18 15:47:52.298  1019  2842 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-18 15:47:52.298   311   311 I art     : Explicit concurrent mark sweep GC freed 8711(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 619us total 23.541ms
03-18 15:47:52.308  1019  2847 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-18 15:47:52.308  1019  2842 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setSUPLVersion(uint32_t):1558]: supl version = 131072
03-18 15:47:52.318  1019  2847 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-18 15:47:52.318  1019  2842 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setAGLONASSProtocol(long unsigned int):1881]: aGlonassProtocolMask = 0x0
03-18 15:47:52.328  2917  2917 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
03-18 15:47:52.328   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 792us total 22.054ms
03-18 15:47:52.338  1019  2847 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-18 15:47:52.338  1019  2842 I qmi_secgps_clnt: SECGPS: Set XTRA enable : 1
03-18 15:47:52.338  2918  2918 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
03-18 15:47:52.348  2826  2826 D AndroidRuntime: 
03-18 15:47:52.348  2826  2826 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-18 15:47:52.348  2826  2826 D AndroidRuntime: CheckJNI is OFF
03-18 15:47:52.348  2826  2826 D AndroidRuntime: readGMSProperty: start
03-18 15:47:52.348  2826  2826 D AndroidRuntime: readGMSProperty: already setted!!
03-18 15:47:52.348  2826  2826 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-18 15:47:52.348  2826  2826 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-18 15:47:52.348  2826  2826 D AndroidRuntime: readGMSProperty: end
03-18 15:47:52.348  2826  2826 D AndroidRuntime: addProductProperty: start
03-18 15:47:52.348   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 673us total 20.924ms
03-18 15:47:52.358  2929  2929 E Zygote  : MountEmulatedStorage()
03-18 15:47:52.358  2929  2929 E Zygote  : v2
03-18 15:47:52.358  2929  2929 I libpersona: KNOX_SDCARD checking this for 1101
03-18 15:47:52.358  2929  2929 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:52.358  2929  2929 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-18 15:47:52.358  1019  1044 I ActivityManager: Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=2929 uid=1101 gids={41101, 9997} abi=armeabi-v7a
03-18 15:47:52.368  2929  2929 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-18 15:47:52.368  2929  2929 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-18 15:47:52.368  1019  2842 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-18 15:47:52.368  1019  2842 I qmi_secgps_clnt: SECGPS: Set GNSS RF CONFIG : 1
03-18 15:47:52.368  2158  2841 W DriveInitializer: Background init thread ended
03-18 15:47:52.368  1019  2842 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-18 15:47:52.368  1019  2842 I qmi_secgps_clnt: SECGPS: Set CERT TYPE : 15
03-18 15:47:52.368  1019  2842 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-18 15:47:52.368  1019  2842 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setLPPConfig(uint32_t):1605]: lpp profile = 0
03-18 15:47:52.378  2904  2904 D TimaKeyStoreProvider: TimaSignature is unavailable
03-18 15:47:52.378  2904  2904 D ActivityThread: Added TimaKeyStore provider
03-18 15:47:52.378  2933  2933 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
03-18 15:47:52.388  1019  1079 I ActivityManager: Killing 1571:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #31
03-18 15:47:52.388  1510  1510 D Launcher.Model: reloadBadges entered.
03-18 15:47:52.388  1608  1619 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
03-18 15:47:52.388  1608  1619 D BadgeProvider: sendNotify, [notify] : null
03-18 15:47:52.388  1608  1619 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
03-18 15:47:52.388  1608  1619 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-18 15:47:52.388  1608  1619 D BadgeProvider: update, [UpdateCount] : 1
03-18 15:47:52.398  1019  2847 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-18 15:47:52.408  1019  2842 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1644]: sensors disabled = 1
03-18 15:47:52.408  2939  2939 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
03-18 15:47:52.408  1019  2847 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
03-18 15:47:52.408  1019  2847 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
03-18 15:47:52.408  1019  2842 E LocSvc_ApiV02: E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3316]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02
03-18 15:47:52.408  2945  2945 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
03-18 15:47:52.418  2947  2947 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
03-18 15:47:52.438  2929  2929 D TimaKeyStoreProvider: TimaSignature is unavailable
03-18 15:47:52.438  2929  2929 D ActivityThread: Added TimaKeyStore provider
03-18 15:47:52.448  2904  2904 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-18 15:47:52.448  2904  2904 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-18 15:47:52.458  1188  1188 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-18 15:47:52.458  2904  2904 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-18 15:47:52.458  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-18 15:47:52.458  1188  1188 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-18 15:47:52.458  2904  2904 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-18 15:47:52.458  1188  1188 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-18 15:47:52.458  2904  2904 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
03-18 15:47:52.458  1188  1188 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-18 15:47:52.458  1188  1188 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-18 15:47:52.468  1222  1222 V DownloadManager: onReceive intent + android.intent.action.BOOT_COMPLETED
03-18 15:47:52.478  1019  1665 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:52.478  1019  1665 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:52.478  1019  1665 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-18 15:47:52.478  2929  2929 W ResourcesManager: Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
03-18 15:47:52.478  1019  1043 W libprocessgroup: failed to open /acct/uid_10052/pid_1571/cgroup.procs: No such file or directory
03-18 15:47:52.488  2929  2929 V SmartcardService: main Received broadcast
03-18 15:47:52.488  2929  2929 V SmartcardService: Starting smartcard service after boot completed
03-18 15:47:52.498  1019  1464 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
03-18 15:47:52.498  1019  1464 D SecContentProvider2: mCursor = null
03-18 15:47:52.498  1019  1212 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:52.498  1019  1212 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:52.498  1019  1212 W ActivityManager: NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
03-18 15:47:52.498  1019  1031 I ActivityManager: Killing 1986:com.sec.android.widgetapp.samsungapps/u0a134 (adj 15): empty #31
03-18 15:47:52.508  1019  1561 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:52.508  1019  1561 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:52.508  1019  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
03-18 15:47:52.518  1019  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:52.518  1019  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:52.518  1019  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:52.518  1019  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:52.518  1222  1222 D MediaScannerReceiver: action: android.intent.action.BOOT_COMPLETED
03-18 15:47:52.528  2962  2962 E Zygote  : MountEmulatedStorage()
03-18 15:47:52.528  2962  2962 E Zygote  : v2
03-18 15:47:52.528  2962  2962 I libpersona: KNOX_SDCARD checking this for 1000
03-18 15:47:52.528  2962  2962 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:52.528  2962  2962 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-18 15:47:52.528  1019  1464 I ActivityManager: Start proc com.sec.android.app.sysscope for broadcast com.sec.android.app.sysscope/.receiver.BootCompleteReceiver: pid=2962 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-18 15:47:52.528  2962  2962 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-18 15:47:52.528  2962  2962 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-18 15:47:52.558  2962  2962 D TimaKeyStoreProvider: TimaSignature is unavailable
03-18 15:47:52.558  2962  2962 D ActivityThread: Added TimaKeyStore provider
03-18 15:47:52.558  2158  2170 W art     : Suspending all threads took: 94.474ms
03-18 15:47:52.598  2962  2962 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
03-18 15:47:52.608  1019  1212 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:52.608  1019  1212 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:52.608  1019  1212 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.sysscope, destAppInfo.processName = com.sec.android.app.sysscope
03-18 15:47:52.608  1019  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:52.608  1019  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:52.608  1019  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:52.608  1019  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:52.618  2978  2978 E Zygote  : MountEmulatedStorage()
03-18 15:47:52.618  2978  2978 E Zygote  : v2
03-18 15:47:52.618  2978  2978 I libpersona: KNOX_SDCARD checking this for 10153
03-18 15:47:52.618  2978  2978 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:52.618  2978  2978 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-18 15:47:52.628  2978  2978 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-18 15:47:52.628  2978  2978 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-18 15:47:52.628  1019  1043 W libprocessgroup: failed to open /acct/uid_10134/pid_1986/cgroup.procs: No such file or directory
03-18 15:47:52.628  1019  1561 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=2978 uid=10153 gids={50153, 9997} abi=armeabi-v7a
03-18 15:47:52.658  2978  2978 D TimaKeyStoreProvider: TimaSignature is unavailable
03-18 15:47:52.658  2978  2978 D ActivityThread: Added TimaKeyStore provider
03-18 15:47:52.678   300   300 E USB_UICC: Timeout! No signal received. Retry num = 29
03-18 15:47:52.688   329   329 I ServiceManager: Waiting for service AtCmdFwd...
03-18 15:47:52.688  2978  2978 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-18 15:47:52.708  1019  1079 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
03-18 15:47:52.738  1019  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:52.738  1019  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:52.738  1019  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:52.738  1019  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:52.748  2994  2994 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
03-18 15:47:52.748  2995  2995 E Zygote  : MountEmulatedStorage()
03-18 15:47:52.748  2995  2995 E Zygote  : v2
03-18 15:47:52.748  2995  2995 I libpersona: KNOX_SDCARD checking this for 1000
03-18 15:47:52.748  2995  2995 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:52.758  2995  2995 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-18 15:47:52.758  1019  1467 I ActivityManager: Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=2995 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-18 15:47:52.758  2998  2998 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
03-18 15:47:52.758  1019  1467 I ActivityManager: Killing 1795:com.android.vending/u0a26 (adj 15): empty #31
03-18 15:47:52.758  2995  2995 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-18 15:47:52.758  2995  2995 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-18 15:47:52.798  2995  2995 D TimaKeyStoreProvider: TimaSignature is unavailable
03-18 15:47:52.798  2995  2995 D ActivityThread: Added TimaKeyStore provider
03-18 15:47:52.798  2660  2736 I bt_vendor: bluetooth satus is on
03-18 15:47:52.808  2660  2882 D bt_userial_mct: userial_open(port:0)
03-18 15:47:52.808  2660  2882 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
03-18 15:47:52.808  2660  2882 I bt_vendor: Done intiailizing UART
03-18 15:47:52.808  2660  2882 I bt_vendor: Done intiailizing UART
03-18 15:47:52.808  2660  2882 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
03-18 15:47:52.808  2660  2882 I bt_vendor: Bluetooth Firmware and transport layer are initialized
03-18 15:47:52.808  2660  3015 D bt_userial_mct: Entering userial_read_thread()
03-18 15:47:52.818  1019  1509 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:52.818  1019  1509 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:52.818  1019  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-18 15:47:52.828  1019  1470 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:52.828  1019  1470 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:52.828  1019  1470 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-18 15:47:52.858  1019  1464 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:52.858  1019  1464 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:52.858  1019  1464 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-18 15:47:52.858  1019  1212 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:52.858  1019  1212 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:52.858  1019  1212 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:52.858  1019  1212 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:52.878  1019  1212 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=3019 uid=10155 gids={50155, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
03-18 15:47:52.878  1019  1212 I ActivityManager: Killing 2217:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #31
03-18 15:47:52.888  2660  2876 I         : BTE_InitTraceLevels -- TRC_HCI
03-18 15:47:52.888  2660  2876 I         : BTE_InitTraceLevels -- TRC_L2CAP
03-18 15:47:52.888  2660  2876 I         : BTE_InitTraceLevels -- TRC_RFCOMM
03-18 15:47:52.888  2660  2876 I         : BTE_InitTraceLevels -- TRC_AVDT
03-18 15:47:52.888  2660  2876 I         : BTE_InitTraceLevels -- TRC_AVRC
03-18 15:47:52.888  2660  2876 I         : BTE_InitTraceLevels -- TRC_A2D
03-18 15:47:52.888  2660  2876 I         : BTE_InitTraceLevels -- TRC_BNEP
03-18 15:47:52.888  2660  2876 I         : BTE_InitTraceLevels -- TRC_BTM
03-18 15:47:52.888  2660  2876 I         : BTE_InitTraceLevels -- TRC_GAP
03-18 15:47:52.888  2660  2876 I         : BTE_InitTraceLevels -- TRC_PAN
03-18 15:47:52.888  2660  2876 I         : BTE_InitTraceLevels -- TRC_SAP
03-18 15:47:52.888  2660  2876 I         : BTE_InitTraceLevels -- TRC_SDP
03-18 15:47:52.888  2660  2876 I         : BTE_InitTraceLevels -- TRC_GATT
03-18 15:47:52.888  2660  2876 I         : BTE_InitTraceLevels -- TRC_SMP
03-18 15:47:52.888  2660  2876 I         : BTE_InitTraceLevels -- TRC_BTAPP
03-18 15:47:52.888  2660  2876 I         : BTE_InitTraceLevels -- TRC_BTIF
03-18 15:47:52.888  2660  2876 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
03-18 15:47:52.888  3019  3019 E Zygote  : MountEmulatedStorage()
03-18 15:47:52.888  3019  3019 I libpersona: KNOX_SDCARD checking this for 10155
03-18 15:47:52.888  3019  3019 E Zygote  : v2
03-18 15:47:52.888  3019  3019 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:52.888  3019  3019 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-18 15:47:52.888  3019  3019 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-18 15:47:52.888  1019  1043 W libprocessgroup: failed to open /acct/uid_10026/pid_1795/cgroup.procs: No such file or directory
03-18 15:47:52.888  3019  3019 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-18 15:47:52.888  1019  1490 I ActivityManager: Killing 2232:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31
03-18 15:47:52.908  1019  1044 I ActivityManager: Waited long enough for: ServiceRecord{6f6edb8 u0 com.samsung.hs20settings/.WifiHs20UtilityService}
03-18 15:47:52.918  3019  3019 D TimaKeyStoreProvider: TimaSignature is unavailable
03-18 15:47:52.918  3019  3019 D ActivityThread: Added TimaKeyStore provider
03-18 15:47:52.928  1019  1031 D SettingsProvider: name = next_alarm_formatted
03-18 15:47:52.928  1019  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-18 15:47:52.928  1019  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-18 15:47:52.928  1019  1031 D SettingsProvider: selectionArgs: false
03-18 15:47:52.928  1019  1031 D SettingsProvider: selectionArgs: 10081
03-18 15:47:52.928  1019  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-18 15:47:52.928  1019  1031 D SettingsProvider: ret = -1
03-18 15:47:52.928  1019  1467 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:52.928  1019  1467 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:52.928  1019  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-18 15:47:52.938  3019  3019 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-18 15:47:52.938  1222  3016 D MediaScannerService: !@start scanning volume internal: [/system/media, /oem/media]
03-18 15:47:52.948  1019  1470 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:52.948  1019  1470 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:52.948  1019  1470 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-18 15:47:52.948  1019  1509 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:52.948  1019  1509 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:52.948  1019  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-18 15:47:52.968  1222  1222 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
03-18 15:47:52.968  1487  1780 D TP/MmsProvider: Update uri=content://mms, match=0
03-18 15:47:52.978  1487  1780 D TP/MmsProvider: update , handleReadChangedBroadcast
03-18 15:47:52.978  1487  1780 D TP/MmsSmsProvider: need read changed broadcast:false
03-18 15:47:52.978  2660  2876 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
03-18 15:47:52.978  2420  2420 I Mms:transaction: [MmsSystemEventReceiver] restorePduNotificationStatus count=0
03-18 15:47:52.978  2420  2420 D Mms/MessagingNotification: [start]    nonBlockingUpdateMessageIndicator() consume time = 4976.959373
03-18 15:47:52.978  2420  2420 I Mms/ReservationManager: resetAfterConnected()
03-18 15:47:52.978  2660  2876 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa4540ead 
03-18 15:47:52.978  2660  2876 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa4540ead 
03-18 15:47:52.978  2885  2885 E ActivityThread: Failed to find provider info for flipboard.auth.internal.debug
03-18 15:47:52.978  2885  2885 E ActivityThread: Failed to find provider info for flipboard.auth.internal
03-18 15:47:52.978  2420  3035 D Mms/MessagingNotification: sDisableVibrateForCamera = false
03-18 15:47:52.988  1487  1502 D TP/MmsSmsProvider: query,matched:7, calling pid = 2420
03-18 15:47:52.988  1487  1502 D TP/MmsSmsProvider: match 7:Elapsed time : 3.958 ms
03-18 15:47:52.988  1019  1031 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10081
03-18 15:47:52.998  1019  1019 I DrmEventReceiver: DrmEventReceiver : onReceive
03-18 15:47:52.998  1019  1019 I DrmEventReceiver: DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
03-18 15:47:52.998  1019  1019 I DrmEventReceiver: DrmEventReceiver : beginStartingService
03-18 15:47:52.998  1019  1019 I System.out: start Service
03-18 15:47:52.998  2660  2740 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
03-18 15:47:53.008  2660  2740 E bt-btif : Calling BTA_HhEnable
03-18 15:47:53.008  2660  2740 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
03-18 15:47:53.008  2660  2740 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
03-18 15:47:53.008  2660  2740 E BluetoothServiceJni: populateRssiValuesNative
03-18 15:47:53.008  2660  2740 I bluedroid: getModelRssiValues
03-18 15:47:53.008  2660  2740 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
03-18 15:47:53.008  2660  2740 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
03-18 15:47:53.008  1019  1032 I art     : Explicit concurrent mark sweep GC freed 173918(10MB) AllocSpace objects, 82(6MB) LOS objects, 33% free, 22MB/33MB, paused 4.767ms total 418.633ms
03-18 15:47:53.008  2420  3035 D Mms/TelephonyPermission: isDefault true
03-18 15:47:53.008  2660  2740 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
03-18 15:47:53.008  1019  1019 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
03-18 15:47:53.008  2660  2740 D BluetoothAdapterProperties: Scan Mode:20
03-18 15:47:53.008  2660  2740 D BluetoothAdapterProperties: Discoverable Timeout:120
03-18 15:47:53.008  2660  2740 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
03-18 15:47:53.008  2660  2740 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
03-18 15:47:53.008  2660  2740 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
03-18 15:47:53.008  2660  2740 E bt-btif : btif_sock_init: !radio_req && !rfc_init
03-18 15:47:53.008  2660  2740 E bt-btif : btif_sock_init: !vhci_init
03-18 15:47:53.008  2660  2740 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
03-18 15:47:53.008  1188  1188 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-18 15:47:53.008  1019  1043 W libprocessgroup: failed to open /acct/uid_10064/pid_2217/cgroup.procs: No such file or directory
03-18 15:47:53.018  2660  3015 E bt_mct  : hci lib postload completed
03-18 15:47:53.018  1019  1019 D SettingsProvider: name = bluetooth_name
03-18 15:47:53.018  1019  1043 W libprocessgroup: failed to open /acct/uid_10065/pid_2232/cgroup.procs: No such file or directory
03-18 15:47:53.018  1487  1502 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2420
03-18 15:47:53.018  2420  2420 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
03-18 15:47:53.028  2660  2740 D IOP_DB_BT: db_open: db_open : handle 3028344848l, read 13894 bytes onto local cache
03-18 15:47:53.028  2660  2740 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
03-18 15:47:53.028  2660  2740 D IOP_DB_BT: db_query: result 1
03-18 15:47:53.028  2660  2740 I         : iop_db_open: iop_db_open status 0
03-18 15:47:53.028  2660  2740 D bte_conf: Device ID record 1 : primary
03-18 15:47:53.028  2660  2740 D bte_conf:   vendorId            = 0075
03-18 15:47:53.028  2660  2740 D bte_conf:   vendorIdSource      = 0001
03-18 15:47:53.028  2660  2740 D bte_conf:   product             = 0100
03-18 15:47:53.028  2660  2740 D bte_conf:   version             = 0200
03-18 15:47:53.028  2660  2740 D bte_conf:   clientExecutableURL = 
03-18 15:47:53.028  2660  2740 D bte_conf:   serviceDescription  = 
03-18 15:47:53.028  2660  2740 D bte_conf:   documentationURL    = 
03-18 15:47:53.028  2660  2740 D bte_conf: bte_load_did_conf no section named DID2.
03-18 15:47:53.028  2660  2740 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
03-18 15:47:53.028  1019  1563 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:53.028  1019  1563 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:53.028  1019  1563 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
03-18 15:47:53.038  2660  2736 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
03-18 15:47:53.038  2660  2736 D BluetoothAdapterProperties: ScanMode =  20
03-18 15:47:53.038  2660  2736 D BluetoothAdapterProperties: State =  11
03-18 15:47:53.038  1019  1509 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
03-18 15:47:53.038  2660  2736 D BluetoothAdapterProperties: Setting state to 12
03-18 15:47:53.038  2660  2736 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
03-18 15:47:53.038  1487  1780 D TP/MmsSmsProvider: query,matched:200, calling pid = 2420
03-18 15:47:53.038  1019  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.038  1487  1780 D TP/MmsSmsProvider: match 200:Elapsed time : 1.449 ms
03-18 15:47:53.038  1019  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.038  1019  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.038  1019  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.058  3042  3042 E Zygote  : MountEmulatedStorage()
03-18 15:47:53.058  3042  3042 E Zygote  : v2
03-18 15:47:53.058  3042  3042 I libpersona: KNOX_SDCARD checking this for 10043
03-18 15:47:53.058  3042  3042 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:53.058  3042  3042 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-18 15:47:53.058  3042  3042 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-18 15:47:53.058  3042  3042 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-18 15:47:53.058  1019  1569 I ActivityManager: Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=3042 uid=10043 gids={50043, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-18 15:47:53.068  2660  2740 D BluetoothAdapterProperties: Scan Mode:21
03-18 15:47:53.068  2660  2740 D BluetoothAdapterProperties: Discoverable Timeout:120
03-18 15:47:53.068  1019  1464 D SettingsProvider: name = bluetooth_a2dp_sink_mode
03-18 15:47:53.068  1019  1464 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-18 15:47:53.068  1019  1464 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-18 15:47:53.068  1019  1464 D SettingsProvider: selectionArgs: false
03-18 15:47:53.068  1019  1464 D SettingsProvider: selectionArgs: 1002
03-18 15:47:53.068  1019  1464 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-18 15:47:53.068  1019  1464 D SettingsProvider: ret = -1
03-18 15:47:53.068  2420  2420 D Mms/SmsReceiverService: onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
03-18 15:47:53.068  2420  3041 D Mms/TelephonyPermission: isDefault true
03-18 15:47:53.068  2420  3041 D Mms/SmsReceiverService: [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
03-18 15:47:53.068  2420  3041 D Mms/SmsReceiverService: [start]    handleBootCompleted() consume time = 92.671198
03-18 15:47:53.078  1487  1502 D TP/SmsProvider: query,matched:0, calling pid = 2420
03-18 15:47:53.078  1487  1502 D TP/SmsProvider: match 0:Elapsed time : 1.181 ms
03-18 15:47:53.088  1019  1464 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
03-18 15:47:53.088  2660  2736 D BluetoothAdapterService: Bluetooth PBAP supproted is true
03-18 15:47:53.088  2660  2736 D BluetoothAdapterService: updateAdapterState state is 12
03-18 15:47:53.088  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:53.088  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:53.088  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
03-18 15:47:53.098  3042  3042 D TimaKeyStoreProvider: TimaSignature is unavailable
03-18 15:47:53.098  3042  3042 D ActivityThread: Added TimaKeyStore provider
03-18 15:47:53.098  2660  2736 D BluetoothAdapterService: Autoconnection is available 
03-18 15:47:53.098  2660  2736 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
03-18 15:47:53.098  2660  2736 D BluetoothAdapterService: starting service from this receiver
03-18 15:47:53.108  1188  1188 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-18 15:47:53.108   283   514 D WVMDrmPlugIn: WVMDrmPlugin::onInitialize : 2344
03-18 15:47:53.108   283   514 D WVMDrmPlugIn: WVMDrmPlugin::onSetOnInfoListener : add 2344
03-18 15:47:53.108  1188  1211 D BluetoothAdapter: onBluetoothStateChange: up=true
03-18 15:47:53.108  1188  1211 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-18 15:47:53.108  2003  2838 D BluetoothAdapter: onBluetoothStateChange: up=true
03-18 15:47:53.108  2003  2838 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-18 15:47:53.118  1019  1048 D BluetoothA2dp: onBluetoothStateChange: up=true
03-18 15:47:53.118  1019  1561 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:53.118  1019  1561 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:53.118  1019  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
03-18 15:47:53.118  2660  2736 I BluetoothAdapterState: Entering On State from state = 11
03-18 15:47:53.118  2247  2257 D BluetoothAdapter: onBluetoothStateChange: up=true
03-18 15:47:53.118  2247  2257 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-18 15:47:53.128  1487  2029 D TP/MmsSmsProvider: getThreadUnReadCount unreadCount=0 imUnreadCount=0
03-18 15:47:53.128  1487  2029 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775806
03-18 15:47:53.128  2660  2668 D BluetoothAdapter: onBluetoothStateChange: up=true
03-18 15:47:53.128  2660  2668 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-18 15:47:53.128  2660  2660 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
03-18 15:47:53.128  1487  2029 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
03-18 15:47:53.128  1487  2029 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775806
03-18 15:47:53.128  1458  1468 D BluetoothAdapter: onBluetoothStateChange: up=true
03-18 15:47:53.128  1458  1468 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-18 15:47:53.128  2660  2668 D BluetoothA2dp: onBluetoothStateChange: up=true
03-18 15:47:53.128  1487  2029 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
03-18 15:47:53.128  1487  2029 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-18 15:47:53.128  1487  2029 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-18 15:47:53.128  1487  2029 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-18 15:47:53.128  1487  2029 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-18 15:47:53.128  1487  2029 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-18 15:47:53.128  1487  2029 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-18 15:47:53.128  1019  1048 D BluetoothAdapter: onBluetoothStateChange: up=true
03-18 15:47:53.128  1019  1048 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-18 15:47:53.128  1487  1508 D BluetoothAdapter: onBluetoothStateChange: up=true
03-18 15:47:53.128  1487  1508 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-18 15:47:53.138  1473  1495 D BluetoothAdapter: onBluetoothStateChange: up=true
03-18 15:47:53.138  1473  1495 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-18 15:47:53.138  2660  2660 I BluetoothPbapService: Handler(): got msg=1
03-18 15:47:53.138  1019  1212 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
03-18 15:47:53.148  1907  1907 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
03-18 15:47:53.148  3042  3042 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-18 15:47:53.148  3042  3042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-18 15:47:53.148  3042  3042 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-18 15:47:53.158  1188  1188 D BluetoothTile:  onBluetoothStateChange:
03-18 15:47:53.158  1188  1188 D BluetoothTile:  onBluetoothPairedDevicesChanged:
03-18 15:47:53.158  1188  1188 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
03-18 15:47:53.158  1188  1188 D BluetoothTile:  getBluetoothState : 12
03-18 15:47:53.168  1019  1561 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
03-18 15:47:53.168  1019  1490 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
03-18 15:47:53.168  1188  1188 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
03-18 15:47:53.168  1188  1617 D BluetoothTile:  handleUpdatestate:false name:null
03-18 15:47:53.168  1188  1617 D BluetoothTile:  handleUpdatestate:false name:null
03-18 15:47:53.168  1188  1617 D BluetoothTile:  handleUpdatestate:false name:null
03-18 15:47:53.188  1019  1464 D SettingsProvider: name = block_emergency_message
03-18 15:47:53.188  1019  1464 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-18 15:47:53.188  1019  1464 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-18 15:47:53.188  1019  1464 D SettingsProvider: selectionArgs: false
03-18 15:47:53.188  1019  1464 D SettingsProvider: selectionArgs: 10043
03-18 15:47:53.188  1019  1464 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-18 15:47:53.188  1019  1464 D SettingsProvider: ret = -1
03-18 15:47:53.198  1019  1470 W ActivityManager: getTasks: caller 10043 is using old GET_TASKS but privileged; allowing
03-18 15:47:53.198  3019  3019 D [0]UMC:Core: onCreate(): 
03-18 15:47:53.208  2904  2904 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 147.289ms
03-18 15:47:53.238  3019  3019 D [0]UMC:DeviceInfo: USA==US==
03-18 15:47:53.268  2744  2805 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-18 15:47:53.268  3019  3019 D USER_AGENT: UMC/1.3.23 (SM-A300FU) SAFE-5.3 KNOX-2.3 en_US
03-18 15:47:53.298  1019  3063 I DrmEventService: action event :android.intent.action.BOOT_COMPLETED
03-18 15:47:53.298  1019  1019 I TimaServiceEventReceiver: TimaServiceEventReceiver : onReceive
03-18 15:47:53.308  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
03-18 15:47:53.308  1019  1019 I InputMethodManagerService: [BT Setting State] State =12
03-18 15:47:53.308  1019  1019 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
03-18 15:47:53.308   283   283 I ANDROID_DRM_FRWORKS_DrmManager: DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
03-18 15:47:53.308  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:53.308  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:53.308  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
03-18 15:47:53.318  1339  1339 I WifiCredService: onCreate
03-18 15:47:53.328  2660  3064 V BluetoothPbapService: PBAP Service initSocket try: 0
03-18 15:47:53.328  1458  1458 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@b186631, true
03-18 15:47:53.328  1487  2029 D TP/MmsSmsProvider: delete threadId: 9223372036854775806
03-18 15:47:53.328  1487  2029 D TP/MmsSmsProvider: need read changed broadcast:false
03-18 15:47:53.328  2826  2826 E AffinityControl: AffinityControl: registerfunction enter
03-18 15:47:53.328  3019  3019 D [0]UMC:AdminManager: init - start
03-18 15:47:53.338  1222  3016 E SQLiteLog: (283) recovered 380 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
03-18 15:47:53.338  1487  1502 I art     : Explicit concurrent mark sweep GC freed 34450(2MB) AllocSpace objects, 5(80KB) LOS objects, 45% free, 4MB/8MB, paused 1.263ms total 253.543ms
03-18 15:47:53.338  1458  1458 D BluetoothHeadset: registerMessageListener
03-18 15:47:53.338  2660  3065 D BluetoothMapMasInstance: set MAP SDP message type : 1
03-18 15:47:53.348  1339  1339 D WifiTimerReceiver: action: android.intent.action.BOOT_COMPLETED
03-18 15:47:53.348  1339  1339 D WifiTimerReceiver: extra: Bundle[mParcelledData.dataSize=84]
03-18 15:47:53.348  1339  1339 D MY_TAG  : Action boot completed received
03-18 15:47:53.348  3019  3019 D [0]UMC:AdminManager: loadAdmins
03-18 15:47:53.358  2660  2668 D HeadsetService: registerMessageListener
03-18 15:47:53.358  2660  2668 D HeadsetService: registerMessageListener
03-18 15:47:53.358  2660  2796 D HeadsetStateMachine: Disconnected process message: 70
03-18 15:47:53.358  2660  2796 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@10de8bab
03-18 15:47:53.358  1458  1458 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
03-18 15:47:53.358  1458  1458 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
03-18 15:47:53.358  1458  1458 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
03-18 15:47:53.358  1458  1458 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
03-18 15:47:53.358  1458  1458 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
03-18 15:47:53.358  1487  1487 E CscReceiver: onReceive android.intent.action.BOOT_COMPLETED
03-18 15:47:53.368  1019  1569 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-18 15:47:53.368  2420  3041 D Mms/Conversation: deleteTempConversation(),deleted=0
03-18 15:47:53.368  1019  1569 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4308, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-18 15:47:53.368  1019  1569 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-18 15:47:53.368  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-18 15:47:53.368  1339  1339 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
03-18 15:47:53.368  1019  1019 I MotionRecognitionService: Plugged
03-18 15:47:53.368  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
03-18 15:47:53.368  1019  1131 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
03-18 15:47:53.368  1019 , 1131 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
03-18 15:47:53.368  1019  1131 E WifiNative-wlan0: invaild command id : 215
03-18 15:47:53.368  1188  1188 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-18 15:47:53.368  1188  1188 D KeyguardUpdateMonitor: handleBatteryUpdate
03-18 15:47:53.368  1188  1188 D PowerUI : Cable  true --> true mBootCompleted : true
03-18 15:47:53.368  1188  1188 D PowerUI : Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
03-18 15:47:53.378  1442  1442 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-18 15:47:53.378  1442  1442 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-18 15:47:53.388  2660  2660 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-18 15:47:53.388  2660  2796 D HeadsetStateMachine: Disconnected process message: 10
03-18 15:47:53.388  2660  2796 D HeadsetStateMachine: Disconnected process message: 9
03-18 15:47:53.388  2660  2796 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
03-18 15:47:53.398  1019  1509 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:53.398  1188  1188 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-18 15:47:53.398  1019  1509 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:53.398  1188  1188 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-18 15:47:53.398  1019  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
03-18 15:47:53.398  1188  1188 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-18 15:47:53.398  2660  3065 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-18 15:47:53.398  1188  1188 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-18 15:47:53.398  1188  1188 D SViewCoverView: level :100 plugged : 2
03-18 15:47:53.398  2826  2826 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-18 15:47:53.398  1487  1780 D TP/SmsProvider: query,matched:51, calling pid = 2420
03-18 15:47:53.398  1019  1470 I ActivityManager: Killing 2247:com.vlingo.midas/u0a28 (adj 15): empty #31
03-18 15:47:53.408  1487  1780 D TP/SmsProvider: match 51:Elapsed time : 3.013 ms
03-18 15:47:53.408  2660  3065 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
03-18 15:47:53.408  2660  3065 D BluetoothSocket: bindListen(), new LocalSocket 
03-18 15:47:53.408  2660  3065 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-18 15:47:53.408  2660  3065 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2e91c208
03-18 15:47:53.408  2660  3065 D BluetoothSocket: channel: 5
03-18 15:47:53.408  2660  3064 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-18 15:47:53.418  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.418  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.418  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.418  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.418  3019  3019 D [0]UMC:AdminManager: init - end
03-18 15:47:53.418  1487  1502 D SmsProvider: Update uri=content://sms/outbox, match=8
03-18 15:47:53.418  3019  3019 D GSLBManager: migrateStoredUrlFromOldPref
03-18 15:47:53.418  1487  1487 D CscUpdateService: onStart
03-18 15:47:53.418  1487  1487 E CscUpdateService: costomer file is exists : it has been preconfiged.
03-18 15:47:53.418  1487  1487 I CscUpdateService: set_CSC_version
03-18 15:47:53.418  1487  1487 E CscParser: update(): xml file exist
03-18 15:47:53.428  1019  1563 E PersonaManagerService: inState():  stateMachine is null !!
03-18 15:47:53.428  1019  1563 I PersonaManagerService: PersonaId don't exist
03-18 15:47:53.428  1019  1563 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-18 15:47:53.428  3076  3076 E Zygote  : MountEmulatedStorage()
03-18 15:47:53.428  3076  3076 I libpersona: KNOX_SDCARD checking this for 10002
03-18 15:47:53.428  3076  3076 E Zygote  : v2
03-18 15:47:53.428  3076  3076 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:53.428  1487  1502 D TP/MmsSmsProvider: need read changed broadcast:false
03-18 15:47:53.428  3019  3019 D GSLBManager: migrateStoredUrlFromOldPref : Migration Not Needed
03-18 15:47:53.428  3019  3019 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
03-18 15:47:53.428  3076  3076 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-18 15:47:53.438  3076  3076 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-18 15:47:53.438  1019  1490 I ActivityManager: Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=3076 uid=10002 gids={50002, 9997, 3002, 3003, 1028} abi=armeabi-v7a
03-18 15:47:53.438  3076  3076 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-18 15:47:53.438  1222  3016 D MediaScanner: Prescan. DB items number : 138 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
03-18 15:47:53.438  2420  3041 D Mms/SmsReceiverService: moveOutboxMessagesToFailedBox messageCount: 0
03-18 15:47:53.438  2420  3041 D Mms/SmsReceiverService: handle boot completed, sendFirstQueuedMessage()
03-18 15:47:53.438  2420  3041 D Mms/SmsReceiverService: [SIM-1]sendFirstQueuedMessage()
03-18 15:47:53.448  3019  3019 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
03-18 15:47:53.448  3019  3019 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
03-18 15:47:53.448  3019  3019 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
03-18 15:47:53.448  3019  3019 D [0]UMC:UMCAdmin: isContainer : 0
03-18 15:47:53.448  2660  3064 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
03-18 15:47:53.448  2660  3064 D BluetoothSocket: bindListen(), new LocalSocket 
03-18 15:47:53.448  2660  3064 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-18 15:47:53.448  2660  3064 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@175e3da1
03-18 15:47:53.448  2660  3064 D BluetoothSocket: channel: 19
03-18 15:47:53.448  2660  3064 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
03-18 15:47:53.448  1487  1487 I CscUtil : isWifiOnly = false
03-18 15:47:53.448  1019  1563 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-18 15:47:53.458  1487  1487 I System.out: HandDataNode = null
03-18 15:47:53.458  1487  1487 I CscUpdateService: PATH_CSCNAME =CustomerDataSet.CSCName
03-18 15:47:53.458  1487  1487 I CscUpdateService: This is normal boot : CSC not updated
03-18 15:47:53.458  1188  1188 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-18 15:47:53.458  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-18 15:47:53.458  1188  1188 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-18 15:47:53.458  1188  1188 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-18 15:47:53.458  1188  1188 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-18 15:47:53.458  1188  1188 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-18 15:47:53.458  1487  3093 E CscParser: update(): xml file exist
03-18 15:47:53.468  1019  1509 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
03-18 15:47:53.468  1019  1563 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-18 15:47:53.468  1019  1563 W ActivityManager: mDVFSHelper.acquire()
03-18 15:47:53.478  1019  1563 D FocusedStackFrame: Set to : 0
03-18 15:47:53.478  1487  3093 D CscGPS  : CSCGPS.updateParameters
03-18 15:47:53.478  1487  3093 D CscGPS  : supl host : null
03-18 15:47:53.478  1487  3093 D CscGPS  : SUPL Host is null or invalid
03-18 15:47:53.478  1487  3093 D CscGPS  : supl_ver : null
03-18 15:47:53.478  1487  3093 D CscGPS  : SUPL Ver is null or invalid
03-18 15:47:53.478  1487  3093 D CscGPS  : supl port : null
03-18 15:47:53.478  1487  3093 D CscGPS  : SUPL PORT is null or invalid
03-18 15:47:53.478  1487  3093 D CscGPS  : LPP : null
03-18 15:47:53.478  1487  3093 D CscGPS  : LPP is null or invalid
03-18 15:47:53.478  1487  3093 D CscGPS  : CSC don't have any AGPS value.
03-18 15:47:53.478  3076  3076 D TimaKeyStoreProvider: TimaSignature is unavailable
03-18 15:47:53.478  3076  3076 D ActivityThread: Added TimaKeyStore provider
03-18 15:47:53.488  1019  1563 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-18 15:47:53.488  1019  1563 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-18 15:47:53.488  1019  1563 D InputDispatcher: Focused application set to: xxxx
03-18 15:47:53.488  1487  1487 I CscUpdateService: same CSC Version
03-18 15:47:53.488  1487  1487 D CscUtil : Set Build Fingerprint to samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
03-18 15:47:53.488  1019  1563 D InputDispatcher: Focus left window: 1510
03-18 15:47:53.488  1510  1510 D Launcher.HomeView: onPause
03-18 15:47:53.488  1019  1049 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-18 15:47:53.488  1019  1049 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-18 15:47:53.488  3019  3019 E [0]UMC:UMCAdmin: No active admin owned by uid 10155
03-18 15:47:53.488  3019  3019 D [0]UMC:UMCAdmin: isContainer : 0
03-18 15:47:53.488  1510  1510 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-18 15:47:53.498  2826  2826 D AndroidRuntime: Shutting down VM
03-18 15:47:53.508  3019  3019 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
03-18 15:47:53.508   284   284 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
03-18 15:47:53.508   284   284 V voice   : voice_set_parameters: enter: A2dpSuspended=false
03-18 15:47:53.508   284   284 V voice   : voice_set_parameters: exit with code(-2)
03-18 15:47:53.508   284   284 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
03-18 15:47:53.508   284   284 V msm8974_platform: platform_set_parameters: exit with code(-2)
03-18 15:47:53.508   284   284 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
03-18 15:47:53.508   284   284 V audio_hw_primary: adev_set_parameters: exit
03-18 15:47:53.508  2660  2796 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
03-18 15:47:53.508  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-18 15:47:53.508  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
03-18 15:47:53.508  1019  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-18 15:47:53.508  1019  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-18 15:47:53.508   258   258 I SurfaceFlinger: id=10 createSurf (1x1),1 flag=404, uhalitest
03-18 15:47:53.508  1487  1780 D TP/SmsProvider: query,matched:26, calling pid = 2420
03-18 15:47:53.518  3019  3019 D [0]UMC:CoreReceiver: Intent : android.intent.action.BOOT_COMPLETED
03-18 15:47:53.518  3019  3019 D [0]UMC:CoreReceiver:  check PreETag 
03-18 15:47:53.518  1487  1780 D TP/SmsProvider: match 26:Elapsed time : 9.850 ms
03-18 15:47:53.528  1339  1339 D NearbySettings: MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
03-18 15:47:53.528  1019  1467 D SettingsProvider: name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
03-18 15:47:53.528  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.528  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.528  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.528  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.528  1019  1043 W libprocessgroup: failed to open /acct/uid_10028/pid_2247/cgroup.procs: No such file or directory
03-18 15:47:53.538  3105  3105 E Zygote  : MountEmulatedStorage()
03-18 15:47:53.538  3105  3105 I libpersona: KNOX_SDCARD checking this for 10167
03-18 15:47:53.538  3105  3105 E Zygote  : v2
03-18 15:47:53.538  3105  3105 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:53.538  3105  3105 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-18 15:47:53.548  1339  2215 V NearbySettings: MountReceiver.mPrefHandler - 7002
03-18 15:47:53.548  1019  1032 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3105 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-18 15:47:53.548  3105  3105 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-18 15:47:53.548   279  1008 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-18 15:47:53.548   279  1008 D Netd    : getNetworkForDns: using netid 502 for uid 10117
03-18 15:47:53.548  3105  3105 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-18 15:47:53.558  2420  3035 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
03-18 15:47:53.568  3019  3019 D [0]UMC:ByodSetupStarter: Container ID : 0
03-18 15:47:53.568  3019  3019 V [0]UMC:Utils: checkAppScreen() : com.test.thalitest
03-18 15:47:53.568  3019  3019 I [0]UMC:Core: shutdown
03-18 15:47:53.578  3019  3019 I art     : System.exit called, status: 0
03-18 15:47:53.578  3019  3019 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
03-18 15:47:53.578  1608  1619 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
03-18 15:47:53.588  2420  3041 D Mms/SmsReceiver: unregisterForServiceStateChanges, already unregistered
03-18 15:47:53.588  2420  3041 D Mms/MessagingNotification: sDisableVibrateForCamera = false
03-18 15:47:53.588  2420  3041 D Mms/TelephonyPermission: isDefault true
03-18 15:47:53.588  3105  3105 D TimaKeyStoreProvider: TimaSignature is unavailable
03-18 15:47:53.588  3105  3105 D ActivityThread: Added TimaKeyStore provider
03-18 15:47:53.588  1222  3016 V MediaScanner: processDirectory :  /system/media
03-18 15:47:53.608  1019  1470 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-18 15:47:53.608  1019  1470 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-18 15:47:53.608  1019  1470 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-18 15:47:53.608  1487  1508 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2420
03-18 15:47:53.608  1510  1510 V ActivityThread: updateVisibility : ActivityRecord{20bf14fa token=android.os.BinderProxy@1edcb0cd {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
03-18 15:47:53.618  1608  1625 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-18 15:47:53.618  1608  1625 D BadgeProvider: sendNotify, [notify] : null
03-18 15:47:53.618  1608  1625 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-18 15:47:53.618  1608  1625 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-18 15:47:53.618  1608  1625 D BadgeProvider: update, [UpdateCount] : 1
03-18 15:47:53.618  1510  1510 D Launcher.HomeView: onStop
03-18 15:47:53.618  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-18 15:47:53.618  1510  1510 V ActivityThread: updateVisibility : ActivityRecord{20bf14fa token=android.os.BinderProxy@1edcb0cd {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-18 15:47:53.618  1188  1188 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-18 15:47:53.618  1019  1470 D PersonaManager: isKioskContainerExistOnDevice
03-18 15:47:53.628  1510  1510 D Launcher: onTrimMemory. Level: 20
03-18 15:47:53.628  1510  1510 D Launcher.Model: reloadBadges entered.
03-18 15:47:53.628  1339  1339 I NearbySettings: MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
03-18 15:47:53.628  1339  1339 I NearbySettings: MountReceiver.onReceive - Internal Path
03-18 15:47:53.648  1019  1032 I ActivityManager: Process com.sec.enterprise.knox.cloudmdm.smdms (pid 3019)(adj 0) has died(38,660)
03-18 15:47:53.648  1222  3016 V MediaScanner:  prescan time: 501ms (DB items: 138)
03-18 15:47:53.658  1222  3016 V MediaScanner:     scan time: 125ms (Caching mode: true), (makeEntry time: 17ms ~13%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-18 15:47:53.658  1222  3016 V MediaScanner: postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-18 15:47:53.658  1222  3016 V MediaScanner:    total time: 626ms
03-18 15:47:53.658  1222  3016 V MediaScanner: checked files: 130  directories : 6  (I: 0, U: 0)
03-18 15:47:53.658  2420  3035 D Mms/MessagingNotification: setBadgeCount(), count=0
03-18 15:47:53.658  1222  3016 D MediaScanner: checkDefaultSounds
03-18 15:47:53.658  1222  3016 D MediaScanner: system alarm_alert  : Vwiurug_etwofi5wgg
03-18 15:47:53.658  1019  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.658  1019  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.658  1019  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.658  1019  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.668  2420  3035 D Mms/MessagingNotification: remove alarm
03-18 15:47:53.678  1019  1044 W ProcessCpuTracker: Skipping unknown process pid 3019
03-18 15:47:53.678   300   300 E USB_UICC: Timeout! No signal received. Retry num = 30
03-18 15:47:53.678  3126  3126 E Zygote  : MountEmulatedStorage()
03-18 15:47:53.678  3126  3126 I libpersona: KNOX_SDCARD checking this for 1000
03-18 15:47:53.678  3126  3126 E Zygote  : v2
03-18 15:47:53.678  3126  3126 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:53.678  3126  3126 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-18 15:47:53.688  1019  1044 W ProcessCpuTracker: Skipping unknown process pid 3124
03-18 15:47:53.688  3126  3126 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-18 15:47:53.688  1019  1569 I ActivityManager: Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3126 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-18 15:47:53.688   329   329 I ServiceManager: Waiting for service AtCmdFwd...
03-18 15:47:53.688  3126  3126 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-18 15:47:53.688  1019  1665 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:53.688  1019  1665 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:53.688  1019  1665 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
03-18 15:47:53.718  2826  2826 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
03-18 15:47:53.728  1019  1032 D SettingsProvider: name = personal_mode_enabled
03-18 15:47:53.728  1222  3016 D MediaScanner: OK. alarm_alert is already exist in setting DB.
03-18 15:47:53.728  1222  3016 D MediaScanner: system notification_sound  : K_Oprkltf5wgg
03-18 15:47:53.738  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-18 15:47:53.738  1019  1019 D SensorService: [SO] activate (ident=0xb7dbec58, enabled=0)
03-18 15:47:53.738  1019  1019 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
03-18 15:47:53.738  1019  1563 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:53.738  1019  1563 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:53.738  1019  1563 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,03-18 15:47:53.748  1019  1019 D SensorManager: unregisterListener ::   
,03-18 15:47:53.748  1019  1019 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
,03-18 15:47:53.748  3126  3126 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:53.748  1019  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.748  1019  1019 D SensorService: [SO] changed settle time [1]
03-18 15:47:53.748  1019  1019 D SensorService: [SO] setDelay [66000000]
03-18 15:47:53.748  1019  1019 D SensorService: [SO] activate (ident=0xb7e1eab0, enabled=1)
03-18 15:47:53.748  1019  1019 D SensorService: [SO] AR_init
03-18 15:47:53.748  1019  1019 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
03-18 15:47:53.748  3126  3126 D ActivityThread: Added TimaKeyStore provider
03-18 15:47:53.748  1828  1828 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
03-18 15:47:53.748  1828  1828 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,03-18 15:47:53.748  1828  1828 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-18 15:47:53.748  1019  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.748  1019  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.748  1019  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:53.758  1019  1019 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,03-18 15:47:53.758  1828  1828 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-18 15:47:53.758  1222  3016 D MediaScanner: OK. notification_sound is already exist in setting DB.
,03-18 15:47:53.758  1828  1828 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-18 15:47:53.758  1222  3016 D MediaScanner: system ringtone  : Wmfi_lpf_pwirywu5wgg
,03-18 15:47:53.768  3141  3141 E Zygote  : MountEmulatedStorage()
,03-18 15:47:53.768  3141  3141 E Zygote  : v2
03-18 15:47:53.768  3141  3141 I libpersona: KNOX_SDCARD checking this for 1000
03-18 15:47:53.768  3141  3141 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:53.768  1828  1828 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
,03-18 15:47:53.768  3141  3141 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-18 15:47:53.768  3141  3141 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-18 15:47:53.768  1019  1569 I ActivityManager: Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=3141 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-18 15:47:53.768  3141  3141 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-18 15:47:53.768  1188  1188 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-18 15:47:53.768  1828  1828 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-18 15:47:53.768  1828  1828 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
03-18 15:47:53.768  1828  1828 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-18 15:47:53.768  1828  1828 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-18 15:47:53.768  1828  1828 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
03-18 15:47:53.768  1828  1828 D daemonapp: [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
,03-18 15:47:53.778  1222  3016 D MediaScanner: OK. ringtone is already exist in setting DB.
,03-18 15:47:53.788   300   300 E USB_UICC: Timeout! No signal received. Reach maximum retries!
03-18 15:47:53.788   300   300 E USB_UICC: usb_uicc_init_qmi failed ! 
03-18 15:47:53.788   300   300 I USB_UICC: usb_uicc_cleanup, signal received: 0x3 
03-18 15:47:53.788   300   300 I USB_UICC: usb_uicc_cleanup, Issuing QMI deinit ... 
,03-18 15:47:53.788  1019  1032 I ActivityManager: Killing 1520:com.android.printspooler/u0a132 (adj 15): empty #31
,03-18 15:47:53.798  1222  3016 D MediaScannerService: !@done scanning volume internal
,03-18 15:47:53.808  2632  2632 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2632) action= = android.intent.action.MEDIA_SCANNER_FINISHED
03-18 15:47:53.808  2632  2632 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2632) ACTION_MEDIA_SCANNER_FINISHED = /system/media
03-18 15:47:53.808  2632  2632 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2632) ACTION_MEDIA_SCANNER_FINISHED = Ignored
,03-18 15:47:53.818   279  1008 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-18 15:47:53.818   279  1008 D Netd    : getNetworkForDns: using netid 502 for uid 10117
,03-18 15:47:53.818  1487  1508 D TP/SmsProvider: query,matched:0, calling pid = 2420
,03-18 15:47:53.818  1487  1487 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-18 15:47:53.818  1487  1487 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-18 15:47:53.818  1487  1487 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-18 15:47:53.818  1487  1487 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-18 15:47:53.818  1487  1487 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-18 15:47:53.818  1487  1487 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-18 15:47:53.818  1487  1508 D TP/SmsProvider: match 0:Elapsed time : 5.826 ms
,03-18 15:47:53.828  1222  3016 D MediaScannerService: !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,03-18 15:47:53.828  1019  1464 D SettingsProvider: name = aw_daemon_service_key_version_check
03-18 15:47:53.828  1019  1464 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-18 15:47:53.828  1019  1464 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-18 15:47:53.828  1019  1464 D SettingsProvider: selectionArgs: false
03-18 15:47:53.828  1019  1464 D SettingsProvider: selectionArgs: 10157
03-18 15:47:53.828  1019  1464 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-18 15:47:53.828  1019  1464 D SettingsProvider: ret = -1
,03-18 15:47:53.828  1019  1041 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-18 15:47:53.838  1019  1464 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10157
,03-18 15:47:53.848  1188  1188 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-18 15:47:53.848  1828  1828 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
03-18 15:47:53.848  3141  3141 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:53.848  3141  3141 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:53.848  1487  2029 D TP/MmsSmsProvider: query,matched:200, calling pid = 2420
,03-18 15:47:53.858  1339  1339 I SmartcardBootCompleteReceiver: SmartcardBootCompleteReceiver - onReceive() 
03-18 15:47:53.858  1339  1339 I SmartcardBootCompleteReceiver: Received intent with action - android.intent.action.BOOT_COMPLETED
,03-18 15:47:53.868  1487  2029 D TP/MmsSmsProvider: match 200:Elapsed time : 11.990 ms
,03-18 15:47:53.868  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:47:53.868  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:53.868  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,03-18 15:47:53.868  3126  3126 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-18 15:47:53.878  1222  3016 D MediaProvider: savePlaylistTableInBulkDeleter started
,03-18 15:47:53.878  1222  3016 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,03-18 15:47:53.878  1222  3016 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,03-18 15:47:53.878  2420  3125 D Mms/MessagingNotification: updateAllHistoryAsRead()
,03-18 15:47:53.878  2420  3035 D Mms/MessagingNotification: [end]    nonBlockingUpdateMessageIndicator() consume time = 813.029635
,03-18 15:47:53.888  1828  1828 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,03-18 15:47:53.888  1339  1339 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
,03-18 15:47:53.888  1222  3016 D MediaProvider: savePlaylistTableInBulkDeleter finished
,03-18 15:47:53.898  1222  3016 D MediaProvider: savePlaylistTableInBulkDeleter started
,03-18 15:47:53.898  1019  1041 D SensorService: [SO] -0.460 0.192 9.902
03-18 15:47:53.898  1019  1041 D SensorService: [SO] [100 -> 255]
,03-18 15:47:53.898  1339  1339 I SmartcardBootCompleteReceiver: Broadcast sent with current lockscreen type
,03-18 15:47:53.898  1828  1828 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-18 15:47:53.908  1828  1828 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-18 15:47:53.908  1828  1828 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,03-18 15:47:53.908  1019  1043 W libprocessgroup: failed to open /acct/uid_10132/pid_1520/cgroup.procs: No such file or directory
,03-18 15:47:53.908  1828  1828 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-18 15:47:53.918  1828  1828 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,03-18 15:47:53.918  1828  1828 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-18 15:47:53.918  1487  1508 D TP/SmsProvider: query,matched:0, calling pid = 2420
,03-18 15:47:53.918  1828  1828 D daemonapp: [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1458312473925
03-18 15:47:53.918  1828  1828 D daemonapp: [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1458334020000
03-18 15:47:53.918  1828  1828 D daemonapp: [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
03-18 15:47:53.918  1828  1828 D daemonapp: [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
03-18 15:47:53.918  1487  1508 D TP/SmsProvider: match 0:Elapsed time : 8.167 ms
03-18 15:47:53.928  3105  3105 I WebViewFactory: Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
03-18 15:47:53.928  1828  1828 D daemonapp: [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1458334020000
03-18 15:47:53.928  1222  3016 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
03-18 15:47:53.938  1222  3016 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
03-18 15:47:53.938  1222  3016 D MediaProvider: savePlaylistTableInBulkDeleter finished
03-18 15:47:53.938  1828  1828 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 9
03-18 15:47:53.938  1828  1828 D daemonapp: [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1458334020000
03-18 15:47:53.938  1019  1212 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.938  1019  1212 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.938  1019  1212 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.938  1019  1212 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.938  3105  3105 I LibraryLoader: Loading: webviewchromium
03-18 15:47:53.948  3105  3105 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 6407-6412)
03-18 15:47:53.948  3105  3105 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-18 15:47:53.958  3171  3171 E Zygote  : MountEmulatedStorage()
,03-18 15:47:53.958  3171  3171 E Zygote  : v2
03-18 15:47:53.958  3171  3171 I libpersona: KNOX_SDCARD checking this for 10082
03-18 15:47:53.958  3171  3171 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:53.958  1487  2029 D TP/SmsProvider: query,matched:51, calling pid = 2420
03-18 15:47:53.958  3171  3171 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-18 15:47:53.958  3171  3171 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-18 15:47:53.958  3171  3171 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-18 15:47:53.968  1019  1212 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3171 uid=10082 gids={50082, 9997, 3003} abi=armeabi-v7a
,03-18 15:47:53.968  1222  3016 D MediaScanner: Prescan. DB items number : 26 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,03-18 15:47:53.968  1019  1212 I ActivityManager: Killing 2275:com.sec.android.app.videoplayer/u0a45 (adj 15): empty #31
,03-18 15:47:53.968  1339  1339 D [SBeam] : SBeamEnabler.initPreferenceForSbeam : 0
,03-18 15:47:53.978  3141  3141 E SQLiteLog: (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
,03-18 15:47:53.978   311   311 I art     : Explicit concurrent mark sweep GC freed 8695(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 611us total 21.111ms
,03-18 15:47:53.978  1487  2029 D TP/SmsProvider: match 51:Elapsed time : 35.205 ms
,03-18 15:47:53.988  1339  1339 I SettingSearch/SearchIntentReceiver: action : android.intent.action.BOOT_COMPLETED
,03-18 15:47:53.998  1339  1339 I SettingSearch/SearchIntentReceiver: search setting db init!!
,03-18 15:47:53.998  3171  3171 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:53.998   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 598us total 16.857ms
03-18 15:47:53.998  3171  3171 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:54.008  3105  3105 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {311782de}
,03-18 15:47:54.008  3105  3105 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-18 15:47:54.008  3105  3105 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
03-18 15:47:54.008  1828  1828 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
03-18 15:47:54.008  1828  1828 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,03-18 15:47:54.018   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 664us total 16.753ms
,03-18 15:47:54.018  3141  3141 D DSM     : [Lines:107] Normal booted
03-18 15:47:54.018  3141  3141 D DSM     : [Lines:114] Boot completed
03-18 15:47:54.018  1019  1665 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:54.018  1019  1665 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:54.018  1019  1665 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:54.018  1019  1665 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:54.018  1339  1339 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
,03-18 15:47:54.028  3186  3186 E Zygote  : MountEmulatedStorage(),
03-18 15:47:54.028  3186  3186 E Zygote  : v2
03-18 15:47:54.028  3186  3186 I libpersona: KNOX_SDCARD checking this for 10161
03-18 15:47:54.028  3186  3186 I libpersona: KNOX_SDCARD not a persona,
03-18 15:47:54.028  3186  3186 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-18 15:47:54.028  1019  1665 I ActivityManager: Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3186 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-18 15:47:54.038  1019  1561 I ActivityManager: Killing 2334:com.google.android.apps.magazines/u0a110 (adj 15): empty #31
,03-18 15:47:54.038  3186  3186 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-18 15:47:54.038  1339  3192 I SettingSearch/SearchIntentReceiver: BOOT_COMPLETED call InitSerachDBThread thread start!
03-18 15:47:54.038  3186  3186 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-18 15:47:54.038  3105  3105 I BrowserStartupController: Initializing chromium process, renderers=0
03-18 15:47:54.048  3105  3105 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-18 15:47:54.068  3186  3186 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:54.068  3186  3186 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:54.068  3105  3105 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,03-18 15:47:54.068  3105  3105 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
03-18 15:47:54.068  3105  3105 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,03-18 15:47:54.078   258  1615 I SurfaceFlinger: id=9 Removed Mauncher (5/8)
,03-18 15:47:54.078   258   446 I SurfaceFlinger: id=9 Removed Mauncher (-2/8)
,03-18 15:47:54.098  3105  3105 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-18 15:47:54.098  3105  3105 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-18 15:47:54.098  3105  3105 I Adreno-EGL: Build Date: 04/06/15 Mon
03-18 15:47:54.098  3105  3105 I Adreno-EGL: Local Branch: 
03-18 15:47:54.098  3105  3105 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-18 15:47:54.098  3105  3105 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-18 15:47:54.098  3105  3105 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-18 15:47:54.188  1019  1464 I art     : Explicit concurrent mark sweep GC freed 19284(958KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/33MB, paused 2.814ms total 149.170ms
,03-18 15:47:54.198  2420  3041 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
,03-18 15:47:54.198  1019  1467 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:54.198  1019  1467 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:54.198  1019  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,03-18 15:47:54.198  1019  1043 W libprocessgroup: failed to open /acct/uid_10045/pid_2275/cgroup.procs: No such file or directory
,03-18 15:47:54.198  1019  1043 W libprocessgroup: failed to open /acct/uid_10110/pid_2334/cgroup.procs: No such file or directory
,03-18 15:47:54.198  1222  3016 V MediaScanner: processDirectory :  /storage/emulated/0
,03-18 15:47:54.208  1019  1665 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:54.208  1019  1665 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:54.208  1019  1665 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:54.208  1019  1665 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:54.218  1222  3016 D MediaScanner: Skipping:
03-18 15:47:54.218  1222  3016 D MediaScanner: 7klwibgf7fvntblfd7(75ebcf7
,03-18 15:47:54.228  3222  3222 E Zygote  : MountEmulatedStorage()
03-18 15:47:54.228  3222  3222 I libpersona: KNOX_SDCARD checking this for 1000
03-18 15:47:54.228  3222  3222 E Zygote  : v2
03-18 15:47:54.228  3222  3222 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:54.228  3222  3222 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-18 15:47:54.228  1019  1665 I ActivityManager: Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=3222 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-18 15:47:54.228  1222  3016 D MediaScanner: Skipping:
03-18 15:47:54.228  1222  3016 D MediaScanner: 7klwibgf7fvntblfd7(7Budiwrd7dblb7
03-18 15:47:54.228  1222  3016 V MediaScanner: processDirectory :  /storage/extSdCard
03-18 15:47:54.228  1222  3016 W MediaScanner: Error opening directory, reason : Permission denied.
03-18 15:47:54.228  1222  3016 W MediaScanner: 7klwibgf7fxlKdCbid7
03-18 15:47:54.228  3222  3222 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-18 15:47:54.228  3222  3222 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-18 15:47:54.238  1222  3016 V MediaScanner:  prescan time: 263ms (DB items: 26)
03-18 15:47:54.238  1222  3016 V MediaScanner:     scan time: 29ms (Caching mode: true), (makeEntry time: 20ms ~68%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-18 15:47:54.238  1222  3016 V MediaScanner: postscan time: 5ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-18 15:47:54.238  1222  3016 V MediaScanner:    total time: 297ms
03-18 15:47:54.238  1222  3016 V MediaScanner: checked files: 10  directories : 16  (I: 0, U: 0)
,03-18 15:47:54.238  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:54.238  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:54.238  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:54.238  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:54.248  3235  3235 E Zygote  : MountEmulatedStorage()
03-18 15:47:54.248  3235  3235 E Zygote  : v2
03-18 15:47:54.248  3235  3235 I libpersona: KNOX_SDCARD checking this for 10146
03-18 15:47:54.248  3235  3235 I libpersona: KNOX_SDCARD not a persona
,03-18 15:47:54.258  3235  3235 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-18 15:47:54.258  3235  3235 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-18 15:47:54.258  3222  3222 D TimaKeyStoreProvider: TimaSignature is unavailable
03-18 15:47:54.258  3235  3235 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-18 15:47:54.258  1019  1031 I ActivityManager: Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3235 uid=10146 gids={50146, 9997} abi=armeabi-v7a
,03-18 15:47:54.258  3222  3222 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:54.268  1019  1665 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:54.268  1019  1665 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:54.268  1019  1665 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:54.268  1019  1665 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:54.268  1608  1625 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,03-18 15:47:54.288  3248  3248 E Zygote  : MountEmulatedStorage(),
03-18 15:47:54.288  3248  3248 E Zygote  : v2
03-18 15:47:54.288  3248  3248 I libpersona: KNOX_SDCARD checking this for 1000
03-18 15:47:54.288  3248  3248 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:54.288  3248  3248 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-18 15:47:54.288  3248  3248 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-18 15:47:54.288  1019  1665 I ActivityManager: Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3248 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-18 15:47:54.288  3248  3248 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-18 15:47:54.298  1222  3016 D MediaScannerService: !@done scanning volume external
,03-18 15:47:54.298  2632  2632 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2632) action= = android.intent.action.MEDIA_SCANNER_FINISHED
03-18 15:47:54.298  2632  2632 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2632) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
,03-18 15:47:54.298  2632  2632 D FactoryTestApp: [DummyFtClient$sendBootCompletedAndFinish](2632) ...
03-18 15:47:54.298  2632  2632 D FactoryTestApp: [Support$Values.getString](2632) id=MODEL_COMMUNICATION_MODE, value=gsm
03-18 15:47:54.298  2632  2632 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2632) mConnectionMode = gsm
03-18 15:47:54.298  2632  2632 D FactoryTestApp: [IPCWriterToSecPhoneService$ResponseWriter](2632) Create IPCWriterToSecPhoneService
03-18 15:47:54.298  2632  2632 I FactoryTestApp: [IPCWriterToSecPhoneService$connectToSecPhoneService](2632)  
,03-18 15:47:54.298  3235  3235 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:54.308  3235  3235 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:54.318  3248  3248 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:54.318  3248  3248 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:54.318  3222  3222 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-18 15:47:54.338  3248  3248 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-18 15:47:54.348  2660  2804 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,03-18 15:47:54.358  2660  2804 D BluetoothMediaBrowser: no now playing list
03-18 15:47:54.358  2660  2804 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,03-18 15:47:54.358  2632  2632 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
,03-18 15:47:54.368  1019  1079 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:47:54.368  1019  1079 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:54.368  1019  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
,03-18 15:47:54.368  1608  1625 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
,03-18 15:47:54.368  1510  1510 D Launcher.Model: reloadBadges entered.
,03-18 15:47:54.368  1608  1625 D BadgeProvider: sendNotify, [notify] : null
,03-18 15:47:54.368  1608  1625 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
,03-18 15:47:54.378  1608  1625 D BadgeProvider: update, [BadgeCount] : badgecount=0
,03-18 15:47:54.378  1608  1625 D BadgeProvider: update, [UpdateCount] : 1
03-18 15:47:54.378  2420  3041 D Mms/MessagingNotification: setBadgeCount(), count=0
,03-18 15:47:54.388  2420  3041 D Mms/MessagingNotification: remove alarm
,03-18 15:47:54.388  3105  3213 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,03-18 15:47:54.388  2632  2632 I FactoryTestApp: [IPCWriterToSecPhoneService$onServiceConnected](2632) connected done
03-18 15:47:54.388  2632  2632 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2632) Send Response Message to SecPhone
,03-18 15:47:54.388  3105  3105 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
03-18 15:47:54.388  2632  2632 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2632) Response ��
,03-18 15:47:54.388  2420  3269 D Mms/MessagingNotification: updateAllHistoryAsRead()
,03-18 15:47:54.408  1487  1508 D TP/SmsProvider: query,matched:0, calling pid = 2420
,03-18 15:47:54.408  1487  1508 D TP/SmsProvider: match 0:Elapsed time : 1.401 ms
,03-18 15:47:54.418  2420  3041 D Mms/SmsReceiverService: [end]    handleBootCompleted() consume time = 531.33151
,03-18 15:47:54.428   322  1075 D AT_Distributor: Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>,
03-18 15:47:54.428  2632  2632 D FactoryTestApp: [IPCWriterToSecPhoneService$handleMessage](2632) Send BOOTING COMPLETED done
,03-18 15:47:54.458  3222  3222 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-18 15:47:54.458  1188  1188 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-18 15:47:54.458  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-18 15:47:54.458  1188  1188 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-18 15:47:54.458  1188  1188 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-18 15:47:54.458  1188  1188 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-18 15:47:54.458  1188  1188 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-18 15:47:54.458  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a300fu.dat
,03-18 15:47:54.458  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a3ulte.dat
,03-18 15:47:54.468  3222  3222 I LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a300fu.dat
,03-18 15:47:54.478  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
,03-18 15:47:54.528   322  1075 D AT_Distributor: SetAtdStatus(), 1_1_0,
03-18 15:47:54.528   322  1075 D AT_Distributor: Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,03-18 15:47:54.528  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
03-18 15:47:54.528  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
03-18 15:47:54.528  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
03-18 15:47:54.528  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
03-18 15:47:54.528  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
03-18 15:47:54.528  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
03-18 15:47:54.528  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
03-18 15:47:54.528  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
03-18 15:47:54.528  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
03-18 15:47:54.528  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
03-18 15:47:54.528  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
,03-18 15:47:54.528  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
03-18 15:47:54.528  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_RUN_REF
03-18 15:47:54.528  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
,03-18 15:47:54.528  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
03-18 15:47:54.528  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
,03-18 15:47:54.528  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
03-18 15:47:54.528  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
03-18 15:47:54.528  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
,03-18 15:47:54.528  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
,03-18 15:47:54.528  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
,03-18 15:47:54.538  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
,03-18 15:47:54.538  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
03-18 15:47:54.538  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
,03-18 15:47:54.538  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
03-18 15:47:54.538  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
,03-18 15:47:54.538  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
,03-18 15:47:54.538  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
03-18 15:47:54.538  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
,03-18 15:47:54.538  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
,03-18 15:47:54.538  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
03-18 15:47:54.538  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
,03-18 15:47:54.538  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
,03-18 15:47:54.538  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
03-18 15:47:54.538  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
,03-18 15:47:54.538  3222  3222 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
,03-18 15:47:54.538  3222  3222 I LcdtestApp: [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
,03-18 15:47:54.548  1019  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:54.548  1019  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:54.548  1019  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:54.548  1019  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:54.558  3278  3278 E Zygote  : MountEmulatedStorage()
03-18 15:47:54.558  3278  3278 I libpersona: KNOX_SDCARD checking this for 1000
03-18 15:47:54.558  3278  3278 E Zygote  : v2
03-18 15:47:54.558  3278  3278 I libpersona: KNOX_SDCARD not a persona
,03-18 15:47:54.558  1019  1509 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3278 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-18 15:47:54.558  3278  3278 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-18 15:47:54.558  1019  1509 I ActivityManager: Killing 1649:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,03-18 15:47:54.568  3278  3278 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-18 15:47:54.568  3278  3278 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-18 15:47:54.578  3105  3105 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-18 15:47:54.588  3278  3278 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:54.588  3278  3278 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:54.588  3105  3105 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-18 15:47:54.598  3105  3105 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-18 15:47:54.598  3105  3105 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-18 15:47:54.608  3105  3105 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-18 15:47:54.618  3105  3105 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-18 15:47:54.618  3105  3105 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-18 15:47:54.618  1019  1043 W libprocessgroup: failed to open /acct/uid_10014/pid_1649/cgroup.procs: No such file or directory
,03-18 15:47:54.628  3248  3248 I FOTA    : [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,03-18 15:47:54.648   292   292 E SMD     : DCD OFF
,03-18 15:47:54.648  3248  3248 I DBG_DM  : [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
,03-18 15:47:54.688   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,03-18 15:47:54.698  3171  3171 E UpdateRequestReceiver: ignoring update request
,03-18 15:47:54.698  3171  3171 E UpdateRequestReceiver: ignoring update request
,03-18 15:47:54.728  3105  3304 D OpenGLRenderer: Render dirty regions requested: true,
,03-18 15:47:54.728  1019  1470 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-18 15:47:54.728  1019  1470 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-18 15:47:54.728  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
,03-18 15:47:54.728  1019  1470 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-18 15:47:54.728  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-18 15:47:54.738  3105  3105 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-18 15:47:54.738  3105  3105 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-18 15:47:54.758  3171  3171 E UpdateRequestReceiver: ignoring update request
,03-18 15:47:54.788  3171  3171 E UpdateRequestReceiver: ignoring update request
,03-18 15:47:54.798  3171  3171 E UpdateRequestReceiver: ignoring update request,
,03-18 15:47:54.798  3171  3171 E UpdateRequestReceiver: ignoring update request
,03-18 15:47:54.808  1019  1563 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:54.808  1019  1563 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:54.808  1019  1563 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:54.808  1019  1563 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:54.818  3313  3313 E Zygote  : MountEmulatedStorage(),
03-18 15:47:54.818  3313  3313 E Zygote  : v2
,03-18 15:47:54.818  3313  3313 I libpersona: KNOX_SDCARD checking this for 10088
03-18 15:47:54.818  3313  3313 I libpersona: KNOX_SDCARD not a persona
,03-18 15:47:54.818  1019  1563 I ActivityManager: Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3313 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-18 15:47:54.818  3313  3313 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-18 15:47:54.828  1019  1563 I ActivityManager: Killing 2405:com.sec.modem.settings/1000 (adj 15): empty #31
,03-18 15:47:54.828  3313  3313 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-18 15:47:54.828  3313  3313 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-18 15:47:54.828  3278  3278 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,03-18 15:47:54.838  3186  3303 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-18 15:47:54.838  3186  3303 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-18 15:47:54.848  3313  3313 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:54.848  3313  3313 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:54.898  3186  3303 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-18 15:47:54.928  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2405/cgroup.procs: No such file or directory
,03-18 15:47:54.948  3186  3303 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-18 15:47:54.948  3186  3303 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1c783787: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-18 15:47:54.948  3186  3303 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-18 15:47:55.008  3248  3248 I DBG_DM  : [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
,03-18 15:47:55.008  3248  3248 I DBG_DM  : [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,03-18 15:47:55.048   258   258 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, NainActivit
,03-18 15:47:55.058  1019  1032 D InputDispatcher: Focus entered window: 3105
,03-18 15:47:55.058  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-18 15:47:55.058  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-18 15:47:55.058  3105  3105 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-18 15:47:55.058  3105  3304 I OpenGLRenderer: Initialized EGL, version 1.4
,03-18 15:47:55.068  3105  3304 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096,
03-18 15:47:55.068  3105  3304 D OpenGLRenderer: Enabling debug mode 0
,03-18 15:47:55.108  1019  1079 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-18 15:47:55.108  3248  3248 I DBG_DM  : [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,03-18 15:47:55.108  3248  3248 I DBG_DM  : [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,03-18 15:47:55.108  3248  3248 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,03-18 15:47:55.118  1019  3335 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-18 15:47:55.118  1019  1665 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:55.118  1019  1665 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:55.118  1019  1665 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-18 15:47:55.118  1188  1188 I StatusBar: Icon Only
03-18 15:47:55.118  3248  3248 I DBG_DM  : [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
03-18 15:47:55.118  1188  1188 D PanelView: There is/are notification(s) 
,03-18 15:47:55.118  3248  3248 I DBG_DM  : [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,03-18 15:47:55.128  3248  3248 I DBG_DM  : [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,03-18 15:47:55.128  3105  3105 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3dc1ff45 time:37595
,03-18 15:47:55.138  3248  3248 I DBG_DM  : [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,03-18 15:47:55.138  3248  3248 I DBG_DM  : [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
,03-18 15:47:55.138  3248  3248 I DBG_DM  : [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
,03-18 15:47:55.138  3248  3248 I DBG_DM  : [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
,03-18 15:47:55.138  1188  1188 D OverheatReceiver: onReceive() getAction : android.intent.action.BOOT_COMPLETED
,03-18 15:47:55.138  3248  3248 I DBG_DM  : [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
,03-18 15:47:55.148  3248  3248 I DBG_DM  : [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
,03-18 15:47:55.148  1019  1049 I ActivityManager: Displayed Component not be shown by security: +1s615ms
,03-18 15:47:55.148  1019  1049 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@7,
03-18 15:47:55.148  1019  1044 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@11
03-18 15:47:55.148  3248  3248 I DBG_DM  : [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
,03-18 15:47:55.148  3248  3248 I DBG_DM  : [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
,03-18 15:47:55.148  1019  1049 W ActivityManager: mDVFSHelper.release()
03-18 15:47:55.148  1019  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{4f3db13 u0 com.test.thalitest/.MainActivity t11} time:37615
,03-18 15:47:55.148  3248  3248 I DBG_DM  : [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
,03-18 15:47:55.158  3248  3248 I DBG_DM  : [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
,03-18 15:47:55.158  3248  3297 I DBG_DM  : [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,03-18 15:47:55.168  3248  3248 I DBG_DM  : [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
,03-18 15:47:55.168  3248  3248 I DBG_DM  : [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
,03-18 15:47:55.168  3248  3248 I DBG_DM  : [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
,03-18 15:47:55.168  3248  3248 I DBG_DM  : [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
,03-18 15:47:55.168  3248  3248 I DBG_DM  : [com.wssyncmldm.XDMService(155/onStartCommand)] 
,03-18 15:47:55.178  3278  3278 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,03-18 15:47:55.178  3248  3297 I DBG_DM  : [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
,03-18 15:47:55.178  3248  3248 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,03-18 15:47:55.178  3248  3297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
,03-18 15:47:55.178  1019  1079 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:47:55.178  1019  1079 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:55.178  1019  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-18 15:47:55.188  3248  3248 I DBG_DM  : [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,03-18 15:47:55.188  1188  1188 D OverheatReceiver: into the SAFE_MODE_ACTION
03-18 15:47:55.188  1188  1188 D OverheatReceiver: VZW on -> change to Global UX [safe mode]
,03-18 15:47:55.188  1188  1188 D OverheatReceiver: isSafeMode = false
,03-18 15:47:55.188  3278  3278 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,03-18 15:47:55.188  3278  3278 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
,03-18 15:47:55.188  3278  3278 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
03-18 15:47:55.188  3278  3278 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
,03-18 15:47:55.188  3278  3278 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,03-18 15:47:55.198  1487  1487 D BootupListener: intent.getAction() = android.intent.action.BOOT_COMPLETED
,03-18 15:47:55.198  1019  1561 D SettingsProvider: name = internet_call_settings_visibility
03-18 15:47:55.198  1019  1561 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-18 15:47:55.198  1019  1561 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-18 15:47:55.198  1019  1561 D SettingsProvider: selectionArgs: false
03-18 15:47:55.198  1019  1561 D SettingsProvider: selectionArgs: 1001
03-18 15:47:55.198  1019  1561 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-18 15:47:55.198  1019  1561 D SettingsProvider: ret = -1
,03-18 15:47:55.198  1487  1487 D PhoneUtilsCommon: isSupportVoLTE is false.
,03-18 15:47:55.208  1907  1907 I SamsungIME: getCurrentCandidateView
,03-18 15:47:55.218  1458  1458 I Telecom : InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,03-18 15:47:55.218  1019  1464 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:55.218  1019  1464 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:55.218  1019  1464 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-18 15:47:55.228  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:55.228  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:55.228  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-18 15:47:55.228  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:55.228  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:55.228  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:55.228  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:55.248  3338  3338 E Zygote  : MountEmulatedStorage(),
03-18 15:47:55.248  3338  3338 E Zygote  : v2
03-18 15:47:55.248  3338  3338 I libpersona: KNOX_SDCARD checking this for 10052
03-18 15:47:55.248  3338  3338 I libpersona: KNOX_SDCARD not a persona
,03-18 15:47:55.248  3338  3338 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-18 15:47:55.248  3338  3338 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-18 15:47:55.248  1019  1490 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3338 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,03-18 15:47:55.248  3338  3338 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-18 15:47:55.258  1019  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:55.258  1019  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:55.258  1019  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:55.258  1019  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,03-18 15:47:55.268  3350  3350 E Zygote  : MountEmulatedStorage()
03-18 15:47:55.268  3350  3350 E Zygote  : v2
03-18 15:47:55.268  3350  3350 I libpersona: KNOX_SDCARD checking this for 1000
03-18 15:47:55.268  3350  3350 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:55.268  3350  3350 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-18 15:47:55.278  1019  1079 I ActivityManager: Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3350 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-18 15:47:55.278  3350  3350 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-18 15:47:55.278  3350  3350 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-18 15:47:55.278  3338  3338 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:55.288  3338  3338 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:55.318  3350  3350 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:55.318  3350  3350 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:55.408   258  1403 I SurfaceFlinger: id=10 Removed uhalitest (7/8)
,03-18 15:47:55.408   258  1615 I SurfaceFlinger: id=10 Removed uhalitest (-2/8)
,03-18 15:47:55.428   257   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-18 15:47:55.428   257   522 W Vold    : Returning OperationFailed - no handler for errno 0
,03-18 15:47:55.428  3186  3186 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-18 15:47:55.428  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:47:55.438  1019  1490 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
03-18 15:47:55.438  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,03-18 15:47:55.438  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:55.438  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:55.438  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:55.438  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:55.448  1019  1019 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@11
,03-18 15:47:55.448  3248  3297 I DBG_DM  : [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,03-18 15:47:55.448  3371  3371 E Zygote  : MountEmulatedStorage()
03-18 15:47:55.448  3371  3371 I libpersona: KNOX_SDCARD checking this for 10088
03-18 15:47:55.448  3371  3371 E Zygote  : v2
03-18 15:47:55.448  3371  3371 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:55.458  3371  3371 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-18 15:47:55.458  3371  3371 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-18 15:47:55.458  3371  3371 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-18 15:47:55.468  1019  1490 I ActivityManager: Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3371 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-18 15:47:55.468  1458  1458 I Telecom : InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
,03-18 15:47:55.488  3371  3371 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:55.488  3371  3371 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:55.528  1907  1907 D SamsungIME: Dismiss ExpandCandiate
,03-18 15:47:55.588  3350  3350 I DBG_POLICYDM: [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,03-18 15:47:55.588  3350  3350 I DBG_POLICYDM: [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,03-18 15:47:55.618   284  1738 V audio_hw_primary: adev_get_parameters: enter: keys - call_forwarding
03-18 15:47:55.618   284  1738 D audio_hw_extn: audio_extn_get_parameters: returns 
03-18 15:47:55.618   284  1738 V msm8974_platform: platform_get_parameters: exit: returns - 
03-18 15:47:55.618   284  1738 V audio_hw_primary: adev_get_parameters: exit: returns - call_forwarding=false
03-18 15:47:55.618   284  1738 I str_params: key: 'call_forwarding' value: ''
,03-18 15:47:55.618  2055  2055 V InCall  : ProximitySensor -  - screenonImmediately: false
03-18 15:47:55.618  2055  2055 V InCall  : ProximitySensor -  - mFromRcsShare: false
,03-18 15:47:55.618  2055  2055 I InCall  : ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,03-18 15:47:55.618  3105  3105 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-18 15:47:55.628  2055  2055 D ScoverManager: serviceVersion : 16908288
,03-18 15:47:55.628  1019  1490 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-18 15:47:55.628  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:55.628  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:55.628  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:55.628  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:55.638  1019  3217 D LocationManagerService: getProviders()=[passive]
,03-18 15:47:55.638  3350  3350 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,03-18 15:47:55.638  3313  3313 I com.dropbox.android.service.DropboxNetworkReceiver: Setting receiver enabled: false
,03-18 15:47:55.648  3406  3406 E Zygote  : MountEmulatedStorage(),
03-18 15:47:55.648  3406  3406 E Zygote  : v2
,03-18 15:47:55.648  3350  3394 I DBG_POLICYDM: [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
03-18 15:47:55.648  3406  3406 I libpersona: KNOX_SDCARD checking this for 10014
03-18 15:47:55.648  3406  3406 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:55.648  2055  2055 D InCall  : InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
,03-18 15:47:55.648  3406  3406 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-18 15:47:55.648  1019  3217 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH,
03-18 15:47:55.648  2055  2055 D InCall  : InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
03-18 15:47:55.648  2055  2055 I InCall  : InCallPresenter -  - InCallState = NO_CALLS,
,03-18 15:47:55.648  2055  2055 I InCall  : InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
03-18 15:47:55.648  1458  1458 I Telecom : ProximitySensorManager: Proximity wake lock already released,
03-18 15:47:55.648  2055  2055 D InCall  : InCallPresenter -  - dismissCoverDialog()...
03-18 15:47:55.648  1019  1031 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3406 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
03-18 15:47:55.658  3406  3406 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-18 15:47:55.658  1019  1665 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:55.658  3350  3350 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
03-18 15:47:55.658  1019  1665 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:55.658  3406  3406 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-18 15:47:55.658  1019  1665 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:55.658  3350  3350 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
03-18 15:47:55.658  1019  1665 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:55.668  3350  3350 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
03-18 15:47:55.668  2055  2055 I InCall  : CallSContextMotion - stopPutDownListening
,03-18 15:47:55.668  3350  3350 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,03-18 15:47:55.668  2055  2055 D InCall  : StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,03-18 15:47:55.678  1019  1470 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-18 15:47:55.678  1019  1665 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3419 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-18 15:47:55.678  3350  3350 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache]
03-18 15:47:55.678  2055  2055 D InCall  : InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
,03-18 15:47:55.688  3419  3419 E Zygote  : MountEmulatedStorage()
03-18 15:47:55.688  3419  3419 I libpersona: KNOX_SDCARD checking this for 10008
03-18 15:47:55.688  3419  3419 E Zygote  : v2
03-18 15:47:55.688  3419  3419 I libpersona: KNOX_SDCARD not a persona
,03-18 15:47:55.688  3350  3350 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
03-18 15:47:55.688  3419  3419 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-18 15:47:55.688  3350  3350 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
03-18 15:47:55.688  3419  3419 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-18 15:47:55.688  3350  3350 I DBG_POLICYDM: [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
03-18 15:47:55.688   329   329 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
03-18 15:47:55.688  3419  3419 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-18 15:47:55.688  3350  3350 I DBG_POLICYDM: [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,03-18 15:47:55.698  1188  1188 D PhoneStatusBarView: setCallBackground:0
,03-18 15:47:55.698  3350  3350 I DBG_POLICYDM: [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,03-18 15:47:55.708   311   311 I art     : Explicit concurrent mark sweep GC freed 8703(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 2.627ms total 34.605ms
03-18 15:47:55.718  3105  3359 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
03-18 15:47:55.718  3105  3359 I chromium: 
,03-18 15:47:55.728  3313  3313 E ActivityThread: Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
,03-18 15:47:55.738   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 604us total 18.364ms
,03-18 15:47:55.738  3419  3419 D TimaKeyStoreProvider: TimaSignature is unavailable
03-18 15:47:55.738  3419  3419 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:55.748  3350  3394 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,03-18 15:47:55.748  3406  3406 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:55.748  3406  3406 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:55.758   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 689us total 18.690ms
,03-18 15:47:55.768  3248  3297 I DBG_DM  : [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,03-18 15:47:55.788  3350  3394 I DBG_POLICYDM: [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,03-18 15:47:55.838  3338  3442 I Velvet.VelvetFactory: checking for language pack updates
,03-18 15:47:55.858  3105  3443 D jxcore_app_log: JniHelper::setJavaVM(0xb75e5448), pthread_self() = -1210982136
,03-18 15:47:55.868  2055  2055 D VideoCallManager: Instantiating VideoCallManager
,03-18 15:47:55.868  3105  3443 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-18 15:47:55.868  3105  3443 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-18 15:47:55.868  3105  3443 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-18 15:47:55.868  3105  3443 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-18 15:47:55.868  3105  3443 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-18 15:47:55.868  3105  3443 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a4ff2d8 added. We now have 1 listener(s)
,03-18 15:47:55.878  3105  3443 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,03-18 15:47:55.878  3105  3443 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,03-18 15:47:55.888  3105  3443 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-18 15:47:55.888  3105  3443 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-18 15:47:55.898  3105  3443 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-18 15:47:55.898  3105  3443 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-18 15:47:55.898  3105  3443 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-18 15:47:55.898  3105  3443 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
03-18 15:47:55.898  3105  3443 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-18 15:47:55.898  3105  3443 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-18 15:47:55.898  3105  3443 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-18 15:47:55.898  3105  3443 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-18 15:47:55.898  3105  3443 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-18 15:47:55.898  3105  3443 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-18 15:47:55.898  3105  3443 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-18 15:47:55.898  3105  3443 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b597a97 added. We now have 1 listener(s)
,03-18 15:47:55.898  3105  3443 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-18 15:47:55.898  1907  1907 I SamsungIME: getDebugLevel  : 0x4f4c
,03-18 15:47:55.908  3313  3313 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
,03-18 15:47:55.908  3105  3443 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-18 15:47:55.908  3105  3443 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-18 15:47:55.908  3105  3443 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-18 15:47:55.908  3105  3443 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-18 15:47:55.908  3105  3443 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-18 15:47:55.918  3105  3443 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-18 15:47:55.918  3105  3443 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,03-18 15:47:55.918  3313  3313 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
,03-18 15:47:55.928  2055  2055 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-18 15:47:55.928  3248  3297 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
03-18 15:47:55.928  2055  2055 I GFX construct_block_size_descriptor_2d second part: took 2.472605ms for 0*0 texture 0
,03-18 15:47:55.928  3105  3443 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-18 15:47:55.928  3105  3443 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-18 15:47:55.928  3105  3443 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-18 15:47:55.928  3105  3443 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-18 15:47:55.928  3105  3443 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-18 15:47:55.928  3105  3443 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-18 15:47:55.928  3105  3443 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-18 15:47:55.928  3105  3443 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-18 15:47:55.928  3105  3443 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-18 15:47:55.928  3105  3443 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-18 15:47:55.928  3105  3105 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-18 15:47:55.938  3313  3313 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
,03-18 15:47:55.938  3105  3443 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-18 15:47:55.938  3248  3297 I DBG_DM  : [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
03-18 15:47:55.938  3105  3105 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-18 15:47:55.938  3248  3297 I DBG_DM  : [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,03-18 15:47:55.948  2055  2055 I GFX generate_partition_tables: took 5.291042ms for 0*0 texture 0
,03-18 15:47:55.948  2055  2055 I GFX raster: took 11.469375ms for 176*144 texture 0
03-18 15:47:55.948  2055  2055 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7990220 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb798fb50 counterpartCT=4 counterpartW=176 counterparth=144
,03-18 15:47:55.958  2055  2055 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
,03-18 15:47:55.968  2055  2055 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-18 15:47:55.968  2055  2055 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-18 15:47:55.968  2055  2055 I Adreno-EGL: Build Date: 04/06/15 Mon
03-18 15:47:55.968  2055  2055 I Adreno-EGL: Local Branch: 
03-18 15:47:55.968  2055  2055 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-18 15:47:55.968  2055  2055 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-18 15:47:55.968  2055  2055 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-18 15:47:56.008  1907  1907 I SamsungIME: getDebugLevel  : 0x4f4c
,03-18 15:47:56.008  2055  2055 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-18 15:47:56.008  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:47:56.008  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:56.008  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-18 15:47:56.008  3105  3105 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-18 15:47:56.018  2055  2055 I glCompressedTexImage2D: took 0.230052ms for 320*61440 texture 37809
,03-18 15:47:56.028  2055  2055 I draw setup: took 10.390781ms for 320*240 texture 37809
03-18 15:47:56.028  2055  2055 E GFX GPU raster: drawn
,03-18 15:47:56.028  2055  2055 I GFX GPU raster ASTC: took 39.609739ms for 320*240 texture 12
03-18 15:47:56.028  2055  2055 I GFX raster: took 39.685312ms for 320*240 texture 0
03-18 15:47:56.028  2055  2055 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb798ee10 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb798f018 counterpartCT=4 counterpartW=320 counterparth=240
,03-18 15:47:56.038  1907  1907 I SamsungIME: KeybaordView init() : load resources
,03-18 15:47:56.048  2055  2055 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-18 15:47:56.048  2055  2055 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-18 15:47:56.048  2055  2055 I glCompressedTexImage2D: took 0.341875ms for 480*122880 texture 37813
03-18 15:47:56.048  2055  2055 I draw setup: took 0.673958ms for 480*640 texture 37813
03-18 15:47:56.048  2055  2055 E GFX GPU raster: drawn
,03-18 15:47:56.058  3313  3313 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
,03-18 15:47:56.058  2055  2055 I GFX GPU raster ASTC: took 7.498540ms for 480*640 texture 12
03-18 15:47:56.058  2055  2055 I GFX raster: took 7.595936ms for 480*640 texture 0
03-18 15:47:56.058  2055  2055 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb798f018 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb7bc19d0 counterpartCT=4 counterpartW=480 counterparth=640
,03-18 15:47:56.108  2055  2055 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330,
03-18 15:47:56.108  2055  2055 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
03-18 15:47:56.108  2055  2055 I glCompressedTexImage2D: took 0.353385ms for 440*116864 texture 37809
03-18 15:47:56.108  2055  2055 I draw setup: took 0.714114ms for 440*330 texture 37809
03-18 15:47:56.108  2055  2055 E GFX GPU raster: drawn
03-18 15:47:56.108  3350  3394 I DBG_POLICYDM: [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
03-18 15:47:56.108  2055  2055 I GFX GPU raster ASTC: took 4.368697ms for 440*330 texture 12
03-18 15:47:56.108  2055  2055 I GFX raster: took 4.433594ms for 440*330 texture 0
03-18 15:47:56.108  2055  2055 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7bd1cf8 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb7bbd298 counterpartCT=4 counterpartW=440 counterparth=330
,03-18 15:47:56.118  1907  1907 I SamsungIME: getCurrentKeyboard,
,03-18 15:47:56.118  1907  1907 I SamsungIME: getTextKeyboard,
,03-18 15:47:56.118  3350  3394 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-18 15:47:56.128  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:47:56.128  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:56.128  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-18 15:47:56.138  2055  2055 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-18 15:47:56.138  2055  2055 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-18 15:47:56.138  2055  2055 I glCompressedTexImage2D: took 0.403802ms for 480*163840 texture 37811
03-18 15:47:56.138  2055  2055 I draw setup: took 0.759948ms for 480*640 texture 37811
03-18 15:47:56.138  2055  2055 E GFX GPU raster: drawn
,03-18 15:47:56.148  3313  3313 D breakpad: breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,03-18 15:47:56.148  2055  2055 I GFX GPU raster ASTC: took 6.295261ms for 480*640 texture 12
,03-18 15:47:56.148  2055  2055 I GFX raster: took 6.376822ms for 480*640 texture 0
,03-18 15:47:56.148  2055  2055 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7bba188 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb7bba318 counterpartCT=4 counterpartW=480 counterparth=640
,03-18 15:47:56.148  1019  1569 I ActivityManager: Killing 2437:com.sec.tcpdumpservice/1000 (adj 15): empty #31
,03-18 15:47:56.158  1019  2766 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,03-18 15:47:56.168  1907  1907 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-18 15:47:56.178  3350  3394 I DBG_POLICYDM: [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,03-18 15:47:56.178  3350  3394 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,03-18 15:47:56.178  3350  3394 I DBG_POLICYDM: [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,03-18 15:47:56.198  3313  3313 I com.dropbox.sync.android.a: Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,03-18 15:47:56.198  3350  3394 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,03-18 15:47:56.198  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:56.198  1019  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:56.198  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,03-18 15:47:56.208  2744  2782 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-18 15:47:56.208  2055  2055 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-18 15:47:56.208  2055  2055 I GFX construct_block_size_descriptor_2d second part: took 1.998125ms for 0*0 texture 0
,03-18 15:47:56.228  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2437/cgroup.procs: No such file or directory
,03-18 15:47:56.238  2055  2055 I GFX generate_partition_tables: took 7.598748ms for 0*0 texture 0
,03-18 15:47:56.238  2055  2055 I GFX raster: took 11.536666ms for 176*144 texture 0
03-18 15:47:56.238  2055  2055 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb798fce8 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb7bbd298 counterpartCT=4 counterpartW=176 counterparth=144
,03-18 15:47:56.238  3350  3394 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,03-18 15:47:56.248  2055  2055 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-18 15:47:56.248  2055  2055 I GFX construct_block_size_descriptor_2d second part: took 2.445312ms for 0*0 texture 0
,03-18 15:47:56.258  2055  2055 I GFX generate_partition_tables: took 6.172187ms for 0*0 texture 0
,03-18 15:47:56.258  2055  2055 I GFX raster: took 10.707969ms for 176*144 texture 0
03-18 15:47:56.258  2055  2055 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7be6270 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb7bc0790 counterpartCT=4 counterpartW=176 counterparth=144
,03-18 15:47:56.258  3350  3394 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-18 15:47:56.268  2055  2055 D ScoverManager: registerListener
,03-18 15:47:56.268  1019  1464 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-18 15:47:56.268  3350  3395 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
03-18 15:47:56.268  1019  1032 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-18 15:47:56.268  1019  1032 D CoverManager.StateNotifier: registerListenerCallback : binder = android.os.BinderProxy@1e3eb90b, pid : 2055, uid : 1001, type : 1
,03-18 15:47:56.268  1019  1212 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:56.268  1019  1212 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:56.268  1019  1212 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
03-18 15:47:56.268  3350  3394 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
,03-18 15:47:56.278  3350  3394 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,03-18 15:47:56.278  2055  2055 D InCall  : InCallPresenter -  - Finished InCallPresenter.setUp
,03-18 15:47:56.288  3350  3395 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-18 15:47:56.288  3350  3394 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/20/16:34:31,
,03-18 15:47:56.288  3350  3394 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/18/15:47:56
,03-18 15:47:56.298  3350  3394 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,03-18 15:47:56.298  3350  3394 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,03-18 15:47:56.298  3338  3442 I ContactAccountLoggerTas: canRun() : Opted Out
,03-18 15:47:56.298  3350  3395 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-18 15:47:56.298  3350  3368 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-18 15:47:56.298  3350  3395 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,03-18 15:47:56.298  3350  3368 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-18 15:47:56.298  3350  3395 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,03-18 15:47:56.298  3350  3395 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,03-18 15:47:56.298  1019  1509 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:56.308  1019  1509 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:56.308  1019  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-18 15:47:56.308  3350  3395 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,03-18 15:47:56.308  3350  3395 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
,03-18 15:47:56.308  3350  3395 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,03-18 15:47:56.318  3350  3395 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,03-18 15:47:56.318  3350  3368 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-18 15:47:56.318  3350  3370 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-18 15:47:56.318  3350  3370 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-18 15:47:56.318  3350  3370 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-18 15:47:56.358  3350  3394 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,03-18 15:47:56.358  1019  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:56.358  1019  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:56.358  1019  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:56.358  1019  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:56.368  3476  3476 E Zygote  : MountEmulatedStorage()
03-18 15:47:56.368  3476  3476 E Zygote  : v2
03-18 15:47:56.368  3476  3476 I libpersona: KNOX_SDCARD checking this for 1000
03-18 15:47:56.368  3476  3476 I libpersona: KNOX_SDCARD not a persona
,03-18 15:47:56.368  3476  3476 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-18 15:47:56.378  3476  3476 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-18 15:47:56.378  3476  3476 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-18 15:47:56.388  3105  3122 I art     : Background partial concurrent mark sweep GC freed 8679(533KB) AllocSpace objects, 3(202KB) LOS objects, 39% free, 7MB/12MB, paused 1.789ms total 170.377ms,
03-18 15:47:56.388  1019  1079 I ActivityManager: Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3476 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-18 15:47:56.388  3476  3476 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:56.398  3476  3476 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:56.398  1019  1079 I ActivityManager: Killing 2512:com.wsomacp/u0a23 (adj 15): empty #31
,03-18 15:47:56.398  1019  1079 I ActivityManager: Killing 2469:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #32
,03-18 15:47:56.398  1019  1079 I ActivityManager: Killing 2446:com.sec.android.app.sbrowser/u0a127 (adj 15): empty #33
,03-18 15:47:56.408  3350  3395 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,03-18 15:47:56.418  3186  3186 E YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,03-18 15:47:56.428  3313  3313 I com.dropbox.sync.android.ad: Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A300FU armeabi-v7a; en_US))
,03-18 15:47:56.458  1019  1490 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-18 15:47:56.458  1188  1188 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,03-18 15:47:56.458  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-18 15:47:56.458  1188  1188 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-18 15:47:56.468  1188  1188 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-18 15:47:56.468  1188  1188 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-18 15:47:56.468  1188  1188 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-18 15:47:56.518  3350  3395 I DBG_POLICYDM: [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,03-18 15:47:56.528  3350  3394 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,03-18 15:47:56.548  3350  3394 I DBG_POLICYDM: [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-18 15:47:56.568  1019  1212 I art     : Explicit concurrent mark sweep GC freed 14890(794KB) AllocSpace objects, 2(38KB) LOS objects, 33% free, 22MB/33MB, paused 2.999ms total 200.115ms
,03-18 15:47:56.578  1019  1212 E Tethering: No numeric data
,03-18 15:47:56.588  1019  1509 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:56.588  1019  1509 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:56.588  1019  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,03-18 15:47:56.588  1019  1569 E Tethering: No numeric data
,03-18 15:47:56.598  1019  2818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-18 15:47:56.598  1019  1490 E Tethering: No numeric data
,03-18 15:47:56.608  1019  1031 E Tethering: No numeric data
,03-18 15:47:56.608  1019  1569 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-18 15:47:56.608  1019  3217 I AudioService: getStreamVolume 3 index 0
,03-18 15:47:56.608  1019  1032 E Tethering: No numeric data
,03-18 15:47:56.618  3338  3338 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/mo:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,03-18 15:47:56.618  1019  1563 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-18 15:47:56.618  1019  1665 E Tethering: No numeric data
,03-18 15:47:56.628  1019  1212 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-18 15:47:56.628  3338  3338 I FavoriteContactNamesSup: get() : Execute runnable (UI thread)
,03-18 15:47:56.628  1019  1032 I AudioService: getStreamVolume 3 index 0
03-18 15:47:56.628  3338  3338 I ContactLabelSupplier: get() : Execute runnable (UI thread)
,03-18 15:47:56.628  3338  3441 I ContactLabelSupplier: get() : OptedIn = false
,03-18 15:47:56.648  3350  3395 I DBG_POLICYDM: [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,03-18 15:47:56.688  1339  3192 D [SBeam] : SBeamEnabler.isSBeamSupported : [-1]
,03-18 15:47:56.688  1339  3192 D [SBeam] : SBeamEnabler.isSBeamSupported : EXIST
,03-18 15:47:56.688  1019  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:56.688  1019  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:56.688  1019  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:56.688  1019  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:56.688  3350  3395 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-18 15:47:56.698  3506  3506 E Zygote  : MountEmulatedStorage(),
,03-18 15:47:56.698  3506  3506 E Zygote  : v2
03-18 15:47:56.698  3506  3506 I libpersona: KNOX_SDCARD checking this for 10090
03-18 15:47:56.698  3506  3506 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:56.698  3506  3506 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-18 15:47:56.708  1019  1509 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3506 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
03-18 15:47:56.708  1019  1509 I ActivityManager: Killing 2553:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,03-18 15:47:56.708  3506  3506 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-18 15:47:56.708  3506  3506 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-18 15:47:56.718  3350  3395 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,03-18 15:47:56.728  1019  1490 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
03-18 15:47:56.728  1019  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:56.728  1019  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:56.728  1019  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:56.728  1019  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:56.728  3476  3476 I DBG_FMMDM: [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,03-18 15:47:56.738  3338  3442 I Velvet.VelvetFactory: refreshing search history.,
,03-18 15:47:56.748  3506  3506 D TimaKeyStoreProvider: TimaSignature is unavailable,
03-18 15:47:56.748  3506  3506 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:56.748  1019  1467 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3525 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,03-18 15:47:56.758  3525  3525 E Zygote  : MountEmulatedStorage()
03-18 15:47:56.758  3525  3525 I libpersona: KNOX_SDCARD checking this for 10055
03-18 15:47:56.758  3525  3525 E Zygote  : v2
03-18 15:47:56.758  3525  3525 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:56.758  3525  3525 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-18 15:47:56.758  3525  3525 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-18 15:47:56.758  3525  3525 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-18 15:47:56.778  1019  1467 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:56.778  1019  1467 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:56.778  1019  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-18 15:47:56.798  3525  3525 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:56.798  3525  3525 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:56.798  1019  1569 E Tethering: No numeric data
,03-18 15:47:56.808  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:56.808  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:56.808  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-18 15:47:56.808  3476  3476 I DBG_FMMDM: [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
03-18 15:47:56.808  1019  1031 E Tethering: No numeric data
,03-18 15:47:56.808  1019  1470 E Tethering: No numeric data
03-18 15:47:56.808  3476  3476 I DBG_FMMDM: [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,03-18 15:47:56.808  3476  3476 I DBG_FMMDM: [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,03-18 15:47:56.808  1019  1043 W libprocessgroup: failed to open /acct/uid_10023/pid_2512/cgroup.procs: No such file or directory
,03-18 15:47:56.808  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2469/cgroup.procs: No such file or directory
03-18 15:47:56.808  1019  1043 W libprocessgroup: failed to open /acct/uid_10127/pid_2446/cgroup.procs: No such file or directory
,03-18 15:47:56.818  1019  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:56.818  1019  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:56.818  1019  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:56.818  1019  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:56.818   257   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-18 15:47:56.818   257   522 W Vold    : Returning OperationFailed - no handler for errno 0
03-18 15:47:56.818  3186  3186 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-18 15:47:56.828  1019  1470 E Tethering: No numeric data
,03-18 15:47:56.828   257   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-18 15:47:56.828   257   522 W Vold    : Returning OperationFailed - no handler for errno 0
,03-18 15:47:56.838  3542  3542 E Zygote  : MountEmulatedStorage()
03-18 15:47:56.838  3542  3542 I libpersona: KNOX_SDCARD checking this for 1000
03-18 15:47:56.838  3542  3542 E Zygote  : v2
03-18 15:47:56.838  3542  3542 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:56.838  3542  3542 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-18 15:47:56.838  3186  3186 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
03-18 15:47:56.838  1019  1079 I ActivityManager: Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3542 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-18 15:47:56.838  3542  3542 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-18 15:47:56.838  3542  3542 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-18 15:47:56.848   257   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-18 15:47:56.848   257   522 W Vold    : Returning OperationFailed - no handler for errno 0
,03-18 15:47:56.848  3186  3186 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-18 15:47:56.858  1019  1043 W libprocessgroup: failed to open /acct/uid_10139/pid_2553/cgroup.procs: No such file or directory
,03-18 15:47:56.868  1019  1665 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:47:56.868  1019  1665 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-18 15:47:56.868  1019  1665 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-18 15:47:56.868  1019  1467 I ActivityManager: Killing 2577:com.sec.android.app.camera/u0a135 (adj 15): empty #31
,03-18 15:47:56.888  3506  3506 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,03-18 15:47:56.888  3506  3506 D elm:15121: ELMEngine.ELMEngine( context ).
,03-18 15:47:56.888  3506  3506 D elm:15121: MDMBridge.setEnterpriseBridge()
,03-18 15:47:56.888  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:47:56.888  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-18 15:47:56.888  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-18 15:47:56.898  3506  3506 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,03-18 15:47:56.898  3542  3542 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:56.898  3506  3506 D elm:15121: ElmAgentService : onCreate()
03-18 15:47:56.898  3542  3542 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:56.908  3506  3570 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,03-18 15:47:56.918  3506  3506 D elm:15121: ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
03-18 15:47:56.918  3506  3506 D elm:15121: BootCompletedState : startBootCompleted() call
,03-18 15:47:56.918  1442  1442 V EmergencyMode: [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,03-18 15:47:56.918  3506  3506 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,03-18 15:47:56.928  3338  3441 I UpdateLanguagePacksTask: Checking for language pack updates.
,03-18 15:47:56.958  3542  3542 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,03-18 15:47:56.958  3542  3542 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
03-18 15:47:56.958  3105  3452 W jxcore-log: Initializing JXcore engine
03-18 15:47:56.958  3105  3452 W jxcore-log: JXcore engine is ready
,03-18 15:47:56.968  3542  3542 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-18 15:47:56.968  3248  3297 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,03-18 15:47:57.018  1019  1212 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:47:57.018  1019  1212 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-18 15:47:57.018  1019  1212 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-18 15:47:57.018  3506  3506 I elm:15121: Get License : 0
,03-18 15:47:57.018  3506  3506 D elm:15121: ElmAgentService : onDestroy().
,03-18 15:47:57.028  1019  1665 I ActivityManager: Killing 2390:com.sec.android.app.mt/1000 (adj 15): empty #31
,03-18 15:47:57.028  1442  1442 V EmergencyMode: [EmergencyBase] setBootTime
03-18 15:47:57.028  1442  1442 V EmergencyMode: [EmergencyFactory] No Recovery State, kill my self.
,03-18 15:47:57.028  1979  1979 E audit   : type=1400 msg=audit(1458312477.028:205): avc:  denied  { ioctl } for  pid=3452 comm="Thread-397" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,03-18 15:47:57.028  1979  1979 E audit   :  SEPF_SM-A300FU_5.0.2_0027
,03-18 15:47:57.028  1979  1979 E audit   : type=1300 msg=audit(1458312477.028:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=b a1=5451 a2=4 a3=9286f8f8 items=0 ppid=311 ppcomm=main pid=3452 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-397" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-18 15:47:57.028  1979  1979 E audit   : type=1320 msg=audit(1458312477.028:205): 
03-18 15:47:57.028  1019  1467 V VibratorService: hasVibrator - useVibetonz: true
,03-18 15:47:57.038  1019  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:57.038  1019  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:57.038  1019  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:57.038  1019  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:57.038  3525  3525 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,03-18 15:47:57.048  1019  1043 W libprocessgroup: failed to open /acct/uid_10135/pid_2577/cgroup.procs: No such file or directory
,03-18 15:47:57.048  3575  3575 E Zygote  : MountEmulatedStorage()
03-18 15:47:57.048  3575  3575 I libpersona: KNOX_SDCARD checking this for 1000
03-18 15:47:57.048  3575  3575 E Zygote  : v2
03-18 15:47:57.048  3575  3575 I libpersona: KNOX_SDCARD not a persona
,03-18 15:47:57.048  3575  3575 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-18 15:47:57.048  3105  3452 W jxcore-log: Starting JXcore engine
,03-18 15:47:57.048  1019  1561 I ActivityManager: Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3575 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-18 15:47:57.058  3575  3575 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-18 15:47:57.058  3575  3575 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-18 15:47:57.058  1019  1563 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
03-18 15:47:57.058  3542  3569 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-18 15:47:57.068  1019  1212 I ActivityManager: Killing 1715:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,03-18 15:47:57.078  3476  3476 I DBG_FMMDM: [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,03-18 15:47:57.088  3476  3476 I DBG_FMMDM: [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,03-18 15:47:57.088  3476  3476 I DBG_FMMDM: [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,03-18 15:47:57.088  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:57.088  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:57.088  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:57.088  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:57.088  3525  3525 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,03-18 15:47:57.088  3525  3525 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-18 15:47:57.088  3525  3525 D UserAnalysis: Create SecureDbHelper
,03-18 15:47:57.108  3598  3598 E Zygote  : MountEmulatedStorage()
03-18 15:47:57.108  3598  3598 I libpersona: KNOX_SDCARD checking this for 1000
03-18 15:47:57.108  3598  3598 E Zygote  : v2
03-18 15:47:57.108  3598  3598 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:57.108  3598  3598 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-18 15:47:57.108  3598  3598 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-18 15:47:57.108  3598  3598 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-18 15:47:57.118  3575  3575 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:57.118  3575  3575 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:57.128  1019  1032 I ActivityManager: Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3598 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,03-18 15:47:57.128  1019  1032 I ActivityManager: Killing 2676:com.android.keychain/1000 (adj 15): empty #31
,03-18 15:47:57.128  1019  1032 I ActivityManager: Killing 2613:com.android.calendar/u0a131 (adj 15): empty #32
,03-18 15:47:57.128  1339  3192 W NotificationAccessSettings: Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,03-18 15:47:57.138  3338  3518 I ContactAccountLoggerTas: canRun() : Opted Out
,03-18 15:47:57.138  3338  3518 I ContactAccountLoggerTas: canRun() : Opted Out
,03-18 15:47:57.138  3338  3518 I ContactAccountLoggerTas: canRun() : Opted Out
,03-18 15:47:57.138  1019  3217 V VibratorService: hasVibrator - useVibetonz: true
,03-18 15:47:57.148  1019  1509 V VibratorService: hasVibrator - useVibetonz: true
,03-18 15:47:57.158  3598  3598 D TimaKeyStoreProvider: TimaSignature is unavailable
03-18 15:47:57.158  3598  3598 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:57.178  1339  3192 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-18 15:47:57.178  3105  3452 W jxcore-log: Platform android
03-18 15:47:57.178  3105  3452 W jxcore-log: 
,03-18 15:47:57.178  3105  3452 W jxcore-log: Process ARCH arm
03-18 15:47:57.178  3105  3452 W jxcore-log: 
,03-18 15:47:57.188  1019  1563 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:47:57.188  1019  1563 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:57.188  1019  1563 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-18 15:47:57.188  3338  3356 W art     : Suspending all threads took: 16.374ms
,03-18 15:47:57.188  1019  1561 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:47:57.188  1019  1561 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:57.188  1019  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-18 15:47:57.198  1019  1467 I ActivityManager: Killing 1284:com.android.defcontainer/u0a3 (adj 15): empty #31
,03-18 15:47:57.208  3313  3502 I System.out: Thread-429(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-18 15:47:57.208  3313  3502 I System.out: Thread-429(ApacheHTTPLog):isSBSettingEnabled false
,03-18 15:47:57.208  3313  3502 I System.out: Thread-429(ApacheHTTPLog):isShipBuild true
03-18 15:47:57.208  3313  3502 I System.out: Thread-429(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-18 15:47:57.208  3313  3502 I System.out: Thread-429(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-18 15:47:57.228   279  1008 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-18 15:47:57.228   279  1008 D Netd    : getNetworkForDns: using netid 502 for uid 10088
,03-18 15:47:57.228  3575  3575 I CameraApp: CameraApp.onCreate()... mFeature : null
,03-18 15:47:57.228  3575  3575 I testFeature: Feature.Feature(context)
03-18 15:47:57.228  3575  3575 I testFeature: Feature.readInternalDefaultXml()
03-18 15:47:57.228  3575  3575 I testFeature: ResetFeatureValue
,03-18 15:47:57.238  3525  3525 D IntelligenceServiceApplication: onCreate()
,03-18 15:47:57.248  3525  3525 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,03-18 15:47:57.248  1019  3217 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:57.248  1019  3217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-18 15:47:57.248  1019  3217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-18 15:47:57.248  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:57.248  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:57.248  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:57.248  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:57.258  3575  3575 I CameraFirmware_broadcast: CameraFirmwareBroadCastReceiver...
,03-18 15:47:57.258  3575  3575 I CameraApp: CameraApp.getAppFeature()...
,03-18 15:47:57.268  3620  3620 E Zygote  : MountEmulatedStorage()
03-18 15:47:57.268  3620  3620 E Zygote  : v2
03-18 15:47:57.268  3620  3620 I libpersona: KNOX_SDCARD checking this for 10056
03-18 15:47:57.268  3620  3620 I libpersona: KNOX_SDCARD not a persona
,03-18 15:47:57.268  3620  3620 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-18 15:47:57.268  3620  3620 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-18 15:47:57.268  1019  1490 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3620 uid=10056 gids={50056, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-18 15:47:57.268  3620  3620 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-18 15:47:57.268  1019  1490 I ActivityManager: Killing 2716:com.android.chrome/u0a77 (adj 15): empty #31
,03-18 15:47:57.278  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:57.278  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:57.278  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:57.278  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:57.288  3631  3631 E Zygote  : MountEmulatedStorage(),
03-18 15:47:57.288  3631  3631 E Zygote  : v2
,03-18 15:47:57.298  3631  3631 I libpersona: KNOX_SDCARD checking this for 10095
03-18 15:47:57.298  3631  3631 I libpersona: KNOX_SDCARD not a persona
,03-18 15:47:57.298  3598  3598 I DBG_FMMDS: [50.18.150420][Line:56][onCreate] FMMDS Application Start,
,03-18 15:47:57.298  3631  3631 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-18 15:47:57.308  3620  3620 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:57.308  3620  3620 D ActivityThread: Added TimaKeyStore provider
03-18 15:47:57.308  3631  3631 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-18 15:47:57.308  3631  3631 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-18 15:47:57.308  1019  1490 I ActivityManager: Start proc com.samsung.android.provider.filterprovider for broadcast com.samsung.android.provider.filterprovider/.FilterProviderReceiver: pid=3631 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
,03-18 15:47:57.308  1019  1490 I ActivityManager: Killing 2530:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
,03-18 15:47:57.308  3598  3598 I DBG_FMMDS: [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,03-18 15:47:57.318  1019  1212 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:47:57.318  1019  1212 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:57.318  1019  1212 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
03-18 15:47:57.318  3338  3441 W GAV2    : Thread[Background Non-Blocking-0,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-18 15:47:57.328  3338  3441 W GAV2    : Thread[Background Non-Blocking-0,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,03-18 15:47:57.328  3338  3518 I ContactAccountLoggerTas: canRun() : Opted Out
,03-18 15:47:57.328  3338  3518 I ContactAccountLoggerTas: canRun() : Opted Out
,03-18 15:47:57.328  3631  3631 D TimaKeyStoreProvider: TimaSignature is unavailable
03-18 15:47:57.328  3631  3631 D ActivityThread: Added TimaKeyStore provider
03-18 15:47:57.338  3338  3518 I ContactAccountLoggerTas: canRun() : Opted Out
,03-18 15:47:57.348  3186  3595 D AndroidHttpClient: [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A300FU Build/LRX22G)
,03-18 15:47:57.348  3186  3595 D AndroidHttpClient: [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,03-18 15:47:57.348  3186  3595 I System.out: Thread-448(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-18 15:47:57.348  3186  3595 I System.out: Thread-448(ApacheHTTPLog):isSBSettingEnabled false
,03-18 15:47:57.348  3186  3595 I System.out: Thread-448(ApacheHTTPLog):isShipBuild true
03-18 15:47:57.348  3186  3595 I System.out: Thread-448(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-18 15:47:57.348  3186  3595 I System.out: Thread-448(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-18 15:47:57.348   279  1008 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-18 15:47:57.348   279  1008 D Netd    : getNetworkForDns: using netid 502 for uid 10161
,03-18 15:47:57.348  3525  3525 D IntelligenceServiceApplication: no applications having user consent for prediction
,03-18 15:47:57.358  3186  3616 W MessageQueue: Handler (android.os.Handler) {22f21a6b} sending message to a Handler on a dead thread
03-18 15:47:57.358  3186  3616 W MessageQueue: java.lang.IllegalStateException: Handler (android.os.Handler) {22f21a6b} sending message to a Handler on a dead thread
03-18 15:47:57.358  3186  3616 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:325)
03-18 15:47:57.358  3186  3616 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
03-18 15:47:57.358  3186  3616 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
03-18 15:47:57.358  3186  3616 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
03-18 15:47:57.358  3186  3616 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
03-18 15:47:57.358  3186  3616 W MessageQueue: 	at ffw.a(SourceFile:327)
03-18 15:47:57.358  3186  3616 W MessageQueue: 	at guw.a(SourceFile:120)
03-18 15:47:57.358  3186  3616 W MessageQueue: 	at guf.c(SourceFile:26)
03-18 15:47:57.358  3186  3616 W MessageQueue: 	at gui.run(SourceFile:297)
03-18 15:47:57.358  3186  3616 W MessageQueue: 	at android.os.Handler.handleCallback(Handler.java:739)
03-18 15:47:57.358  3186  3616 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-18 15:47:57.358  3186  3616 W MessageQueue: 	at android.os.Looper.loop(Looper.java:145)
03-18 15:47:57.358  3186  3616 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-18 15:47:57.378  1339  3192 D ScoverManager: serviceVersion : 16908288
,03-18 15:47:57.388  3542  3569 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-18 15:47:57.398  3598  3598 E DBG_FMMDS: Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,03-18 15:47:57.398  2632  3274 I FactoryTestApp: [IPCWriterToSecPhoneService$disConnectSecPhoneService](3274)  
,03-18 15:47:57.408  2035  2035 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,03-18 15:47:57.408  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:47:57.408  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:57.408  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,03-18 15:47:57.408  3598  3598 I DBG_FMMDS: [50.18.150420][Line:43][xdbDBInit] 
,03-18 15:47:57.418  2035  2035 D SecUISvc: Service started flags 0 startId 1
,03-18 15:47:57.418  3631  3631 D PreloadFilterInstaller: uses FILTER_DB_VER_1
,03-18 15:47:57.418  1019  1665 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:57.418  2035  3654 D SecUISvc: Thread created.
,03-18 15:47:57.418  1019  1665 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:57.418  1019  1665 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:57.418  1019  1665 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:57.438  3105  3452 I jxcore-log: JXcore Cordova bridge is ready!
03-18 15:47:57.438  3105  3452 I jxcore-log: 
,03-18 15:47:57.438  3105  3452 W jxcore-log: JXcore engine is started
,03-18 15:47:57.438  3657  3657 E Zygote  : MountEmulatedStorage()
03-18 15:47:57.438  3657  3657 E Zygote  : v2
03-18 15:47:57.438  3657  3657 I libpersona: KNOX_SDCARD checking this for 10026
03-18 15:47:57.438  3657  3657 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:57.438  3657  3657 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-18 15:47:57.448  3657  3657 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-18 15:47:57.448  3657  3657 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-18 15:47:57.448  1019  1665 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3657 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-18 15:47:57.458  3105  3443 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-18 15:47:57.458  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2390/cgroup.procs: No such file or directory
,03-18 15:47:57.458  3338  3441 E File    : fail readDirectory() errno=2
,03-18 15:47:57.458  1019  1043 W libprocessgroup: failed to open /acct/uid_10003/pid_1284/cgroup.procs: No such file or directory
,03-18 15:47:57.468  3105  3105 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-18 15:47:57.468  1188  1188 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-18 15:47:57.468  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-18 15:47:57.468  1188  1188 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-18 15:47:57.468  1188  1188 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-18 15:47:57.468  1188  1188 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-18 15:47:57.468  1188  1188 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-18 15:47:57.468  3525  3525 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,03-18 15:47:57.478  3631  3631 E SQLiteLog: (284) automatic index on titles(filter_id)
,03-18 15:47:57.488  3105  3452 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-18 15:47:57.488  3105  3452 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-18 15:47:57.498  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_1715/cgroup.procs: No such file or directory
03-18 15:47:57.498  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2676/cgroup.procs: No such file or directory
03-18 15:47:57.498  1019  1043 W libprocessgroup: failed to open /acct/uid_10131/pid_2613/cgroup.procs: No such file or directory
03-18 15:47:57.498  1019  1043 W libprocessgroup: failed to open /acct/uid_10077/pid_2716/cgroup.procs: No such file or directory
03-18 15:47:57.498  1019  1043 W libprocessgroup: failed to open /acct/uid_10039/pid_2530/cgroup.procs: No such file or directory
,03-18 15:47:57.498  3105  3105 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,03-18 15:47:57.508   257   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.googlequicksearchbox/files/download_cache/
03-18 15:47:57.508   257   522 W Vold    : Returning OperationFailed - no handler for errno 0
,03-18 15:47:57.508  3105  3105 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
03-18 15:47:57.508  3338  3441 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.googlequicksearchbox/files/download_cache
,03-18 15:47:57.508  3631  3631 I FilterProviderReceiver: onReceive in FilterProviderReceiver
03-18 15:47:57.508  3631  3631 I FilterProviderReceiver: onReceive in FilterProviderReceiver when ACTION_BOOT_COMPLETED
03-18 15:47:57.508  3657  3657 D TimaKeyStoreProvider: TimaSignature is unavailable
03-18 15:47:57.508  3657  3657 D ActivityThread: Added TimaKeyStore provider
03-18 15:47:57.508  3525  3525 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
03-18 15:47:57.508  3525  3525 D UserAnalysis.MyPlaceDbPreference: Constructor Preference
03-18 15:47:57.508  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:57.508  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:57.508  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:57.508  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:57.528  3674  3674 E Zygote  : MountEmulatedStorage()
03-18 15:47:57.528  3674  3674 I libpersona: KNOX_SDCARD checking this for 10098
03-18 15:47:57.528  3674  3674 E Zygote  : v2
03-18 15:47:57.528  3674  3674 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:57.528  3674  3674 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-18 15:47:57.528  3674  3674 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-18 15:47:57.528  3674  3674 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-18 15:47:57.538  1019  1031 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3674 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
03-18 15:47:57.538  1019  1031 I ActivityManager: Killing 2820:com.android.email/u0a141 (adj 15): empty #31
,03-18 15:47:57.538  1019  3217 D FocusedStackFrame: Set to : 0
,03-18 15:47:57.538  1019  3217 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-18 15:47:57.538  1019  3217 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-18 15:47:57.538  1019  3217 D InputDispatcher: Focused application set to: xxxx
,03-18 15:47:57.538  1019  3217 D InputDispatcher: Focus left window: 3105
,03-18 15:47:57.548  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-18 15:47:57.548  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-18 15:47:57.548   258  1403 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (616 us)
,03-18 15:47:57.568  3674  3674 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:57.568  3674  3674 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:57.578  3598  3598 I DBG_FMMDS: [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,03-18 15:47:57.578  3105  3105 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,03-18 15:47:57.578  3105  3105 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
03-18 15:47:57.578  3105  3443 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 72ms. Plugin should use CordovaInterface.getThreadPool().
,03-18 15:47:57.598  3598  3598 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
03-18 15:47:57.598  3598  3598 I DBG_FMMDS: [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
03-18 15:47:57.598  3598  3598 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-18 15:47:57.598  3598  3598 I DBG_FMMDS: [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-18 15:47:57.598  3598  3598 I DBG_FMMDS: [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
03-18 15:47:57.598  3598  3598 I DBG_FMMDS: [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,03-18 15:47:57.608  1019  1032 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@7
,03-18 15:47:57.608  1019  1032 W ActivityManager: mDVFSHelper.acquire()
,03-18 15:47:57.608  1019  1032 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-18 15:47:57.608  1019  1032 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-18 15:47:57.608  1019  1032 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,03-18 15:47:57.628  3338  3442 I WebViewFactory: Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,03-18 15:47:57.638  1019  1490 I ActivityManager: Killing 2852:com.mobeam.barcodeService/1000 (adj 15): empty #31
,03-18 15:47:57.648  1510  1510 D Launcher: onRestart, Launcher: 940895978
,03-18 15:47:57.648   292   292 E SMD     : DCD OFF
,03-18 15:47:57.648  1510  1510 D Launcher: onStart, Launcher: 940895978
03-18 15:47:57.648  1510  1510 D Launcher.HomeView: onStart
,03-18 15:47:57.648  1510  1510 D Launcher: onResume, Launcher: 940895978
,03-18 15:47:57.648  1019  1490 D SettingsProvider: name = kids_home_mode
03-18 15:47:57.648  1019  1490 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-18 15:47:57.648  1019  1490 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-18 15:47:57.648  1019  1490 D SettingsProvider: selectionArgs: false
03-18 15:47:57.648  1019  1490 D SettingsProvider: selectionArgs: 10006
03-18 15:47:57.648  1019  1490 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-18 15:47:57.648  1019  1490 D SettingsProvider: ret = -1
03-18 15:47:57.648  1510  1510 D Launcher.HomeView: onResume
,03-18 15:47:57.658  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,03-18 15:47:57.658  1019  1019 D SensorService: [SO] activate (ident=0xb7e1eab0, enabled=0)
03-18 15:47:57.658  1019  1019 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
03-18 15:47:57.658  3674  3674 D PackageIntentReceiver: ACTION_BOOT_COMPLETED
,03-18 15:47:57.668  1019  1043 W libprocessgroup: failed to open /acct/uid_10141/pid_2820/cgroup.procs: No such file or directory
,03-18 15:47:57.668  1510  1510 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-18 15:47:57.668  1019  1019 D SensorManager: unregisterListener ::   
,03-18 15:47:57.668  1019  1019 I Sensors : AccelerometerSensor(0) setDelay : 200000000(ns)
,03-18 15:47:57.668  1019  1019 D SensorService: [SO] changed settle time [0]
03-18 15:47:57.668  1019  1019 D SensorService: [SO] setDelay [200000000]
03-18 15:47:57.668  1019  1019 D SensorService: [SO] activate (ident=0xb7e1eab0, enabled=1)
03-18 15:47:57.668  1019  1019 D SensorService: [SO] AR_init
03-18 15:47:57.668  1019  1019 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-18 15:47:57.668  3419  3419 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-18 15:47:57.678  1019  1019 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,03-18 15:47:57.678  3419  3419 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,03-18 15:47:57.688  1510  1510 D MenuAppsGridFragment: onResume
,03-18 15:47:57.688  1019  1563 D ActivityManager: handle home activity for 0,
03-18 15:47:57.688  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
03-18 15:47:57.688  1019  1563 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0,
03-18 15:47:57.688  1019  1563 D KnoxTimeoutHandler: post home show event for user 0
03-18 15:47:57.688  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-18 15:47:57.688  1019  1563 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-18 15:47:57.688  1019  1563 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-18 15:47:57.688  1019  1563 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-18 15:47:57.688  1019  1019 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
03-18 15:47:57.688  1019  1019 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
03-18 15:47:57.688  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-18 15:47:57.688   258   258 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=4, Mauncher
03-18 15:47:57.688  3419  3419 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,03-18 15:47:57.698  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-18 15:47:57.708  1019  1490 D InputDispatcher: Focus entered window: 1510
,03-18 15:47:57.708  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2852/cgroup.procs: No such file or directory
,03-18 15:47:57.708  3674  3674 D PackageIntentReceiver: jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,03-18 15:47:57.708  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-18 15:47:57.708  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
03-18 15:47:57.708  1510  1510 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-18 15:47:57.718  3338  3442 I LibraryLoader: Loading: webviewchromium
,03-18 15:47:57.728  3419  3419 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-18 15:47:57.728  1019  3217 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:57.728  1019  3217 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:57.728  1019  3217 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:57.728  1019  3217 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:57.738  1510  1510 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-18 15:47:57.738  1019  1031 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-18 15:47:57.748  3701  3701 E Zygote  : MountEmulatedStorage()
03-18 15:47:57.748  3701  3701 I libpersona: KNOX_SDCARD checking this for 10099
03-18 15:47:57.748  3701  3701 E Zygote  : v2
03-18 15:47:57.748  3701  3701 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:57.748  1188  1188 I StatusBar: Icon Only
03-18 15:47:57.748  1188  1188 D PanelView: There is/are notification(s) 
03-18 15:47:57.748  3701  3701 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-18 15:47:57.748  3701  3701 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-18 15:47:57.748  3701  3701 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-18 15:47:57.758  1019  3700 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-18 15:47:57.758  3338  3442 I LibraryLoader: Time to load native libraries: 38 ms (timestamps 186-224)
03-18 15:47:57.758  3338  3442 I LibraryLoader: Expected native library version number "",actual native library version number "",
,03-18 15:47:57.758  1907  1907 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
03-18 15:47:57.758  3105  3105 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-18 15:47:57.768  1019  3217 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3701 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-18 15:47:57.768  1019  3217 I ActivityManager: Killing 2885:flipboard.boxer.app/u0a97 (adj 15): empty #31
,03-18 15:47:57.778   311   311 I art     : Explicit concurrent mark sweep GC freed 8721(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 672us total 29.926ms
,03-18 15:47:57.798  1019  3217 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:57.798  1019  3217 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:57.798  1019  3217 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:57.798  1019  3217 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:57.798   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 589us total 19.743ms
03-18 15:47:57.798  3701  3701 D TimaKeyStoreProvider: TimaSignature is unavailable
03-18 15:47:57.798  3701  3701 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:57.798  3338  3442 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,03-18 15:47:57.808  1510  1510 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1edcb0cd time:40276
,03-18 15:47:57.808  1019  1049 D PersonaManager: isKioskContainerExistOnDevice
,03-18 15:47:57.818   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 590us total 17.596ms
,03-18 15:47:57.838  3722  3722 E Zygote  : MountEmulatedStorage()
03-18 15:47:57.838  3722  3722 E Zygote  : v2
03-18 15:47:57.838  3722  3722 I libpersona: KNOX_SDCARD checking this for 10013
03-18 15:47:57.838  3722  3722 I libpersona: KNOX_SDCARD not a persona
,03-18 15:47:57.838  3722  3722 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-18 15:47:57.838  1019  3217 I ActivityManager: Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3722 uid=10013 gids={50013, 9997} abi=armeabi-v7a
,03-18 15:47:57.838  3722  3722 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-18 15:47:57.848  3722  3722 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-18 15:47:57.848  1019  1049 I ActivityManager: Displayed Component not be shown by security: +246ms
,03-18 15:47:57.868  3722  3722 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:57.868  1019  1043 W libprocessgroup: failed to open /acct/uid_10097/pid_2885/cgroup.procs: No such file or directory
,03-18 15:47:57.868  3722  3722 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:57.868  3692  3692 D AndroidRuntime: 
03-18 15:47:57.868  3692  3692 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,03-18 15:47:57.868  3692  3692 D AndroidRuntime: CheckJNI is OFF
03-18 15:47:57.868  3692  3692 D AndroidRuntime: readGMSProperty: start
03-18 15:47:57.868  3692  3692 D AndroidRuntime: readGMSProperty: already setted!!
03-18 15:47:57.868  3692  3692 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-18 15:47:57.868  3692  3692 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-18 15:47:57.868  3692  3692 D AndroidRuntime: readGMSProperty: end
03-18 15:47:57.868  3692  3692 D AndroidRuntime: addProductProperty: start
,03-18 15:47:57.878  1019  1041 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-18 15:47:57.888  3620  3620 I sCloudBackupApp: sCloudBackupApp Version Info : 4.04.7.KK_APP
,03-18 15:47:57.908  1019  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:57.908  1019  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:57.908  1019  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:57.908  1019  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:57.928  1019  1470 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3742 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
03-18 15:47:57.928  3742  3742 E Zygote  : MountEmulatedStorage()
03-18 15:47:57.928  3742  3742 I libpersona: KNOX_SDCARD checking this for 10058
03-18 15:47:57.928  3742  3742 E Zygote  : v2
03-18 15:47:57.928  3742  3742 I libpersona: KNOX_SDCARD not a persona
,03-18 15:47:57.928  3742  3742 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-18 15:47:57.928  3742  3742 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-18 15:47:57.928  3742  3742 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-18 15:47:57.928  1019  1470 I ActivityManager: Killing 1608:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
,03-18 15:47:57.948  1339  3192 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-18 15:47:57.968  3742  3742 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:57.968  3742  3742 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:57.978  3248  3297 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,03-18 15:47:57.978  3722  3722 V OneTimeInitializerReceiver: OneTimeInitializerReceiver.onReceive
,03-18 15:47:57.978  1019  1212 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:57.978  1019  1212 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:57.978  1019  1212 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,03-18 15:47:57.998  3722  3762 V OneTimeService: OneTimeService.onHandleIntent
,03-18 15:47:58.008  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:58.008  1019  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:58.008  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-18 15:47:58.018  1019  1467 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:58.018  1019  1467 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:58.018  1019  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-18 15:47:58.018  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:58.018  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-18 15:47:58.028  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-18 15:47:58.028  1019  1212 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:58.028  1019  1212 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:58.028  1019  1212 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
03-18 15:47:58.028  3692  3692 E AffinityControl: AffinityControl: registerfunction enter
,03-18 15:47:58.038  3186  3595 I System.out: Thread-448 calls detatch()
,03-18 15:47:58.048  1019  1509 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:58.048  1019  1509 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-18 15:47:58.048  1019  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-18 15:47:58.058  3692  3692 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-18 15:47:58.058  1019  1470 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:58.058  1019  1470 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:58.058  1019  1470 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-18 15:47:58.068  1630  1630 I Hs20UtilService: Starting #5
03-18 15:47:58.068  1630  1708 I Hs20UtilService: Message received 5003
,03-18 15:47:58.068  1019  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:58.068  1019  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:58.068  1019  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:58.068  1019  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:58.078  1019  1041 D SensorService: [SO] currT = 40541154000, prevT = 40071066000, diff = 470088000, [-0.479 0.211 9.883]
03-18 15:47:58.078  1019  1041 D SensorService: [SO] -0.479 0.211 9.883
03-18 15:47:58.078  1019  1041 D SensorService: [SO] [100 -> 255]
,03-18 15:47:58.078  3772  3772 E Zygote  : MountEmulatedStorage(),
03-18 15:47:58.078  3772  3772 E Zygote  : v2
03-18 15:47:58.078  3772  3772 I libpersona: KNOX_SDCARD checking this for 10018
,03-18 15:47:58.078  3772  3772 I libpersona: KNOX_SDCARD not a persona
,03-18 15:47:58.078  3772  3772 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-18 15:47:58.078  1019  1561 I ActivityManager: Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3772 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
,03-18 15:47:58.078  3772  3772 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-18 15:47:58.078  3772  3772 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-18 15:47:58.108  3772  3772 D TimaKeyStoreProvider: TimaSignature is unavailable,
03-18 15:47:58.108  1019  1044 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@7
03-18 15:47:58.108  3772  3772 D ActivityThread: Added TimaKeyStore provider
03-18 15:47:58.108  1019  1044 W ActivityManager: mDVFSHelper.release()
03-18 15:47:58.108  1019  1044 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-18 15:47:58.108  1019  1043 W libprocessgroup: failed to open /acct/uid_10068/pid_1608/cgroup.procs: No such file or directory
,03-18 15:47:58.148  3657  3657 I Finsky  : [1] com.google.android.finsky.FinskyApp.onCreate(358): Initializing network with DFE https://android.clients.google.com/fdfe/
,03-18 15:47:58.188  1339  3192 D Settings_Utils: isSupportVNFestival SM-A300FU XEO
,03-18 15:47:58.208  1019  1031 D PackageManager: START PACKAGE DELETE: observer{194151641}
03-18 15:47:58.208  1019  1031 D PackageManager: pkg{<packageName>}
03-18 15:47:58.208  1019  1031 D PackageManager: user{0}
03-18 15:47:58.208  1019  1031 D PackageManager: caller{2000}
03-18 15:47:58.208  1019  1031 D PackageManager: flags{2}
,03-18 15:47:58.218  1019  1031 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,03-18 15:47:58.218  1019  1031 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
,03-18 15:47:58.218  1019  1031 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-18 15:47:58.218  1019  1031 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-18 15:47:58.218  1019  1031 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,03-18 15:47:58.218  1019  1058 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,03-18 15:47:58.218  1019  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-18 15:47:58.218  1019  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,03-18 15:47:58.238  3772  3772 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Mar 18 15:47:58 GMT+01:00 2016
,03-18 15:47:58.238  1019  1212 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:47:58.238  1019  1212 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:58.238  1019  1212 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-18 15:47:58.248  3772  3772 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,03-18 15:47:58.248  1019  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:58.248  1019  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:58.248  1019  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:58.248  1019  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:58.258  3772  3772 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,03-18 15:47:58.258  3772  3772 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
03-18 15:47:58.258  3772  3772 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
03-18 15:47:58.258  3772  3795 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-18 15:47:58.268  3796  3796 E Zygote  : MountEmulatedStorage(),
03-18 15:47:58.268  3796  3796 I libpersona: KNOX_SDCARD checking this for 10020
03-18 15:47:58.268  3796  3796 E Zygote  : v2
03-18 15:47:58.268  3796  3796 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:58.268  3772  3795 I KLMS-2.5.123: : KLMSIntentService(): BOOT_COMPLETED
03-18 15:47:58.268  3796  3796 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-18 15:47:58.268  1019  1467 I ActivityManager: Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3796 uid=10020 gids={50020, 9997, 1028, 3003} abi=armeabi-v7a
,03-18 15:47:58.268  3796  3796 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-18 15:47:58.268  3796  3796 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-18 15:47:58.278  3742  3742 I ExternalOEMControlProvider: onCreate
,03-18 15:47:58.278  1339  3192 W ResourceType: Failure getting entry for 0x7f0202b4 (t=1 e=692) (error -75)
,03-18 15:47:58.278  1019  1058 D ApplicationPolicy: getApplicationUninstallationEnabled
,03-18 15:47:58.288  1019  1058 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,03-18 15:47:58.288  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:58.288  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:58.288  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:58.288  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:58.298  1339  3192 W ResourceType: Failure getting entry for 0x7f020510 (t=1 e=1296) (error -75)
,03-18 15:47:58.308  3812  3812 E Zygote  : MountEmulatedStorage()
03-18 15:47:58.308  3812  3812 I libpersona: KNOX_SDCARD checking this for 1000
03-18 15:47:58.308  3812  3812 E Zygote  : v2
03-18 15:47:58.308  3812  3812 I libpersona: KNOX_SDCARD not a persona
,03-18 15:47:58.308  3812  3812 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-18 15:47:58.308  3812  3812 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-18 15:47:58.308  3812  3812 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-18 15:47:58.318  1019  1031 I ActivityManager: Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3812 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
03-18 15:47:58.318  1019  1031 I ActivityManager: Killing 2929:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,03-18 15:47:58.318  3796  3796 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:58.318  3796  3796 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:58.328  1019  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3c26821f u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t10} time:40796
,03-18 15:47:58.338   258   444 I SurfaceFlinger: id=11 Removed NainActivit (7/8)
,03-18 15:47:58.338   258   446 I SurfaceFlinger: id=11 Removed NainActivit (-2/8)
,03-18 15:47:58.348  1019  1212 D SettingsProvider: name = PREVIOUS_SYS_TIME
03-18 15:47:58.348  1019  1212 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-18 15:47:58.348  1019  1212 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-18 15:47:58.348  1019  1212 D SettingsProvider: selectionArgs: false
03-18 15:47:58.348  1019  1212 D SettingsProvider: selectionArgs: 10058
03-18 15:47:58.348  1019  1212 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-18 15:47:58.348  1019  1044 I ActivityManager: Killing 2978:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #31
03-18 15:47:58.348  1019  1212 D SettingsProvider: ret = -1
,03-18 15:47:58.358  3105  3105 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
03-18 15:47:58.358  3105  3105 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
03-18 15:47:58.358  3105  3105 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
03-18 15:47:58.358  3105  3105 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
03-18 15:47:58.358  3105  3105 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
03-18 15:47:58.358  3105  3105 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-18 15:47:58.358  3105  3105 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-18 15:47:58.358  3105  3105 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
03-18 15:47:58.358  3105  3105 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a4ff2d8 removed from the list
03-18 15:47:58.358  3105  3105 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
03-18 15:47:58.358  3105  3105 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b597a97 removed from the list
03-18 15:47:58.358  3105  3105 D io.jxcore.node.ConnectivityMonitor: stop
03-18 15:47:58.358  3105  3105 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,03-18 15:47:58.358  3105  3105 I io.jxcore.node.LifeCycleMonitor: stop: OK
,03-18 15:47:58.358  3812  3812 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:58.358  1019  1212 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10058
03-18 15:47:58.358  3812  3812 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:58.368  1019  1058 D PackageManager: !@killApplicatoin: 10167, uninstall pkg
,03-18 15:47:58.368  1019  1509 D SettingsProvider: name = PREVIOUS_ELAPSED_TIME
03-18 15:47:58.368  1019  1509 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-18 15:47:58.368  1019  1509 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-18 15:47:58.368  1019  1509 D SettingsProvider: selectionArgs: false
03-18 15:47:58.368  1019  1509 D SettingsProvider: selectionArgs: 10058
03-18 15:47:58.368  1019  1509 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-18 15:47:58.368  1019  1509 D SettingsProvider: ret = -1
,03-18 15:47:58.368  3772  3772 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,03-18 15:47:58.378  1019  1509 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10058
,03-18 15:47:58.388  1019  1044 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=-1: uninstall pkg
,03-18 15:47:58.388  1019  1044 I ActivityManager: Killing 3105:com.test.thalitest/u0a167 (adj 9): stop com.test.thalitest cause uninstall pkg
,03-18 15:47:58.388   279  1008 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-18 15:47:58.388   279  1008 D Netd    : getNetworkForDns: using netid 502 for uid 10052
,03-18 15:47:58.408  1019  1019 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@11
,03-18 15:47:58.408  3812  3812 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-18 15:47:58.448  1019  1043 W libprocessgroup: failed to open /acct/uid_1101/pid_2929/cgroup.procs: No such file or directory
,03-18 15:47:58.458  3338  3442 I qtaguid : Tagging socket 39 with tag 100000000{1,0} for uid -1, pid: 3338, getuid(): 10052
,03-18 15:47:58.458  1019  1058 W PackageSettings: Skipping PackageSetting{9b87134 com.example.hello/10168} due to missing metadata
,03-18 15:47:58.488  1188  1188 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-18 15:47:58.498  1019  1079 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:58.498  1019  1079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:58.498  1019  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-18 15:47:58.508  1188  1188 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-18 15:47:58.508  1019  1467 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-18 15:47:58.528  1019  1058 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=0: pkg removed
,03-18 15:47:58.538  3812  3812 I ServiceMode: received = ACTION_BOOT_COMPLETED
03-18 15:47:58.538  3812  3812 I ServiceMode: setReferenceIsDumpState : 0
,03-18 15:47:58.558  1019  1058 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,03-18 15:47:58.568  3701  3843 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
03-18 15:47:58.568  3657  3657 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(122): No need to run daily hygiene.
,03-18 15:47:58.578  1019  1043 W libprocessgroup: failed to open /acct/uid_10153/pid_2978/cgroup.procs: No such file or directory
,03-18 15:47:58.618  1907  1907 E SamsungIME: mOCRHelper is null
,03-18 15:47:58.618  2003  2200 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-18 15:47:58.618  3657  3657 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-18 15:47:58.628  3657  3657 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-18 15:47:58.628  1487  1487 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-18 15:47:58.628  1019  1101 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-18 15:47:58.638  1019  1019 D RCPManagerService: PackageReceiver onReceive()
,03-18 15:47:58.638  1019  1019 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,03-18 15:47:58.638  1019  1470 D PowerManagerService: [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10049 pid=1188 (0x0)
,03-18 15:47:58.638  1019  1019 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,03-18 15:47:58.668  1019  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:58.668  1019  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:58.668  1019  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:58.668  1019  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:58.678  3851  3851 E Zygote  : MountEmulatedStorage(),
,03-18 15:47:58.678  3851  3851 E Zygote  : v2,
03-18 15:47:58.678  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
03-18 15:47:58.678  3851  3851 I libpersona: KNOX_SDCARD checking this for 1000
03-18 15:47:58.678  3851  3851 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-18 15:47:58.678  3851  3851 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:58.678  1019  1128 V NetworkStats: removeUidsLocked() for UIDs [10167],
03-18 15:47:58.678  1019  1128 V NetworkStats: performPollLocked(flags=0x3)
03-18 15:47:58.688  1019  1079 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3851 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-18 15:47:58.688  3851  3851 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-18 15:47:58.688  3851  3851 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-18 15:47:58.688  1019  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
03-18 15:47:58.688  1019  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,03-18 15:47:58.708  3701  3845 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,03-18 15:47:58.708  3313  3502 I System.out: pool-10-thread-1 calls detatch()
,03-18 15:47:58.718  1019  1563 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-18 15:47:58.718  1019  1128 V NetworkStats: performPollLocked() took 34ms
,03-18 15:47:58.718  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,03-18 15:47:58.718  1019  1470 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-18 15:47:58.738  1019  1467 V VibratorService: hasVibrator - useVibetonz: true
,03-18 15:47:58.738  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,03-18 15:47:58.738  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,03-18 15:47:58.748  3851  3851 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:58.748  3851  3851 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:58.758  3406  3406 I RlzPingService: Setting next ping for 1458917278750
,03-18 15:47:58.768  1019  3834 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:58.768  1019  3834 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:58.768  1019  3834 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:58.768  1019  3834 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:58.778  3871  3871 E Zygote  : MountEmulatedStorage()
03-18 15:47:58.778  3871  3871 E Zygote  : v2
03-18 15:47:58.778  3871  3871 I libpersona: KNOX_SDCARD checking this for 1000
03-18 15:47:58.778  3871  3871 I libpersona: KNOX_SDCARD not a persona
,03-18 15:47:58.778  3871  3871 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-18 15:47:58.788  3871  3871 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-18 15:47:58.788  3871  3871 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-18 15:47:58.788  1019  3834 I ActivityManager: Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3871 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,03-18 15:47:58.788  1019  3834 I ActivityManager: Killing 2995:com.sec.usbsettings/1000 (adj 15): empty #31,
,03-18 15:47:58.828  1019  1509 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
03-18 15:47:58.828  1019  1509 D SecContentProvider2: mCursor = null
,03-18 15:47:58.828  1019  1019 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-18 15:47:58.828  1019  1019 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-18 15:47:58.828  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
03-18 15:47:58.828  1019  1019 V EnterpriseBillingPolicy: uID is 10167
03-18 15:47:58.828  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
03-18 15:47:58.828  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-18 15:47:58.838  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-18 15:47:58.838  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-18 15:47:58.838  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-18 15:47:58.838  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-18 15:47:58.838  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-18 15:47:58.838  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-18 15:47:58.848  1473  1473 D RegisteredServicesCache: empty dynamic service
,03-18 15:47:58.858  3871  3871 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:58.858  3871  3871 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:58.928  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
03-18 15:47:58.928  1019  2766 D SSRM:aZ : MSG_TYPE_APP_REMOVED::
,03-18 15:47:58.928  1019  1019 V EnterpriseBillingPolicy: uID is 10167
,03-18 15:47:58.928  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
,03-18 15:47:58.928  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-18 15:47:58.928  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,03-18 15:47:58.928  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
,03-18 15:47:58.928  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-18 15:47:58.928  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-18 15:47:58.938  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-18 15:47:58.948  3851  3851 E MTPRx   : In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,03-18 15:47:58.948  1019  3835 D SecContentProvider2: uri = 14 selection = getSealedState
03-18 15:47:58.948  1019  3835 D SecContentProvider2: mCursor = null
,03-18 15:47:58.958  1019  1561 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
,03-18 15:47:58.958  1019  1561 D SecContentProvider2: mCursor = null
03-18 15:47:58.958  3338  3442 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3338, getuid(): 10052
,03-18 15:47:58.958  3338  3442 I qtaguid : Untagging socket 43
,03-18 15:47:58.958  3851  3851 V MTPRx   : sealedState: false
03-18 15:47:58.958  3851  3851 V MTPRx   : sealedUsbMassStorageState: false
,03-18 15:47:58.958  3338  3442 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3338, getuid(): 10052
,03-18 15:47:58.958  3338  3442 I qtaguid : Untagging socket 43
,03-18 15:47:58.958  3338  3442 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3338, getuid(): 10052
,03-18 15:47:58.958  3338  3442 I qtaguid : Untagging socket 43
,03-18 15:47:58.968  3338  3442 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3338, getuid(): 10052
,03-18 15:47:58.968  3338  3442 I qtaguid : Untagging socket 43
,03-18 15:47:58.968  3338  3442 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3338, getuid(): 10052
03-18 15:47:58.968  3338  3442 I qtaguid : Untagging socket 43
,03-18 15:47:58.968  3338  3442 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3338, getuid(): 10052
03-18 15:47:58.968  3657  3836 D Volley  : [501] g.b: Cache cleared.
,03-18 15:47:58.968  3338  3442 I qtaguid : Untagging socket 43
,03-18 15:47:58.968  3338  3442 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3338, getuid(): 10052
,03-18 15:47:58.968  3338  3442 I qtaguid : Untagging socket 43
,03-18 15:47:58.968  3338  3442 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3338, getuid(): 10052
,03-18 15:47:58.968  3338  3442 I qtaguid : Untagging socket 43
,03-18 15:47:58.968  3338  3442 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3338, getuid(): 10052
03-18 15:47:58.968  3338  3442 I qtaguid : Untagging socket 43
,03-18 15:47:58.968  1019  1561 D SettingsProvider: name = mtp_usb_connection_status
03-18 15:47:58.968  3338  3442 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3338, getuid(): 10052
,03-18 15:47:58.968  3338  3442 I qtaguid : Untagging socket 43
,03-18 15:47:58.968  3338  3442 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3338, getuid(): 10052
03-18 15:47:58.968  3338  3442 I qtaguid : Untagging socket 43
,03-18 15:47:58.968  3338  3442 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3338, getuid(): 10052
,03-18 15:47:58.978  3338  3442 I qtaguid : Untagging socket 43
03-18 15:47:58.978  3657  3788 D Volley  : [495] g.b: Cache cleared.
,03-18 15:47:58.978  3338  3442 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3338, getuid(): 10052
,03-18 15:47:58.978  3338  3442 I qtaguid : Untagging socket 43
,03-18 15:47:58.978  3248  3297 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,03-18 15:47:58.978  1019  1490 I ActivityManager: Killing 2292:flipboard.app/u0a96 (adj 15): empty #31
,03-18 15:47:58.988  1019  1159 D TaskPersister: removeObsoleteFile: deleting file=11_task.xml
,03-18 15:47:58.988  1019  1159 D TaskPersister: removeObsoleteFile: deleting file=11_task_thumbnail.png
,03-18 15:47:58.998  3657  3891 D Ads     : Skipping gmscore version check
,03-18 15:47:58.998  3701  3701 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-18 15:47:59.008  1019  1490 D SettingsProvider: name = media_player_mode
,03-18 15:47:59.018  1019  3835 I ActivityManager: Killing 2420:com.android.mms/u0a41 (adj 15): empty #31
,03-18 15:47:59.018  1019  3835 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:47:59.018  1019  3835 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:59.018  1019  3835 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-18 15:47:59.028  1019  1031 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-18 15:47:59.028  1019  3835 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-18 15:47:59.038  2660  2737 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-18 15:47:59.038  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:47:59.038  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:59.038  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-18 15:47:59.048  2003  2003 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-18 15:47:59.048  1019  3834 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
03-18 15:47:59.048  2003  2003 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-18 15:47:59.048  1019  3217 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:59.048  1019  3217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:59.048  1019  3217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-18 15:47:59.058  1188  1188 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-18 15:47:59.058  1019  1032 D SettingsProvider: name = mtp_usb_conditions_met
,03-18 15:47:59.068  3701  3867 I Gmail   : getAccountsCursor
,03-18 15:47:59.068  3701  3892 I Gmail   : Observing account changes for notifications
,03-18 15:47:59.108  1019  1032 D SettingsProvider: name = mtp_running_status
,03-18 15:47:59.108  1188  1188 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-18 15:47:59.118  2158  3895 D FileApkUtils: Optimizing (staging complete)
,03-18 15:47:59.118  2158  3895 D FileApkUtils: Optimizing: DynamiteModules-prod.apk [1dad65bca29c108ad7dad5d3707435ff0555d8adf974340225c102890df71a23]
,03-18 15:47:59.118  2158  3895 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000000@DynamiteModules-prod.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk': Failed to open oat filename for reading: No such file or directory
,03-18 15:47:59.118  1019  1490 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-18 15:47:59.128  1019  1561 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:59.128  1019  1561 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:59.128  1019  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,03-18 15:47:59.128  3338  3442 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3338, getuid(): 10052
,03-18 15:47:59.128  3338  3518 I ContactAccountLoggerTas: canRun() : Opted Out
,03-18 15:47:59.128  1019  1212 D CountryDetector: No listener is left
,03-18 15:47:59.138  1188  1188 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-18 15:47:59.138  3657  3657 I Finsky  : [1] com.google.android.finsky.receivers.h.a(1107): Installer kick - no action, not running yet
,03-18 15:47:59.138  3657  3657 I Finsky  : [1] com.google.android.finsky.g.j.run(208): Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-18 15:47:59.138  3657  3657 I Finsky  : [1] com.google.android.finsky.g.j.run(214): Finished loading 1 libraries.
,03-18 15:47:59.148  2158  3895 D DexOptUtils: Module /data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk is already optimized. Bailing.
,03-18 15:47:59.148  1019  3217 D SettingsProvider: name = media_mount_count
,03-18 15:47:59.158  1019  1058 I art     : Explicit concurrent mark sweep GC freed 47103(3MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 24MB/36MB, paused 33.783ms total 590.539ms
,03-18 15:47:59.158  1019  1569 I art     : WaitForGcToComplete blocked for 272.119ms for cause Explicit
,03-18 15:47:59.158  1019  1058 D PackageManager: delete codoeFile: 
,03-18 15:47:59.168  1019  1043 D EnterpriseDeviceManagerService: Package has changed for user 0,
03-18 15:47:59.168  1019  1043 W TextServicesManagerService: no available spell checker services found
03-18 15:47:59.168  1019  1043 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
03-18 15:47:59.168  1019  1058 D AASAuninstall: userId = 0, info.removedAppID = 10167, info.uid = 10167, packageName = com.test.thalitest
03-18 15:47:59.168  1019  1058 I AASA_removePackage: UID=10167 Target=com.test.thalitest
,03-18 15:47:59.168  3871  3871 D NPS_WSSNPS: [] android.intent.action.BOOT_COMPLETED
,03-18 15:47:59.168  3871  3871 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,03-18 15:47:59.168  1019  1490 D SettingsProvider: name = mtp_sync_alive
,03-18 15:47:59.168  1019  1058 D PackageManager: result of delete: 1{194151641}
,03-18 15:47:59.178  3657  3657 I Finsky  : [1] com.google.android.finsky.b.j.a(273): result=false type=4
,03-18 15:47:59.178  3692  3692 D AndroidRuntime: Shutting down VM
03-18 15:47:59.178  1188  1188 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-18 15:47:59.178  1019  1561 D SettingsProvider: name = sdcard_launch
,03-18 15:47:59.188  1019  1464 D SettingsProvider: name = boot_time_connected
,03-18 15:47:59.198  1019  1212 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-18 15:47:59.198  1019  1509 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:59.198  1019  1509 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:59.198  1019  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-18 15:47:59.198  1019  3834 D SettingsProvider: name = mtp_open_session
,03-18 15:47:59.208  3871  3871 D NPS_WSSNPS: [] Service onCreate!!
,03-18 15:47:59.218  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-18 15:47:59.218  1019  3217 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:47:59.218  1019  3217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:59.218  1188  1188 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-18 15:47:59.218  1019  3217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-18 15:47:59.218  1019  1058 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-18 15:47:59.218  1019  1058 D PackageManager: userId{-1}
03-18 15:47:59.218  1019  1058 D PackageManager: andCode{true}
,03-18 15:47:59.228  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-18 15:47:59.228  1188  1188 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-18 15:47:59.238  3871  3902 D NPS_WSSNPS: [] NpsServiceTask Start
,03-18 15:47:59.238  1188  1188 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-18 15:47:59.248  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-18 15:47:59.248  1019  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:59.248  1019  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:59.248  1019  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:59.248  1019  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:59.248  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-18 15:47:59.248  1188  1188 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-18 15:47:59.248  3542  3542 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-18 15:47:59.248  3542  3542 I PCWCLIENTTRACE_PushUtil: sales region : global
03-18 15:47:59.248  3542  3542 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-18 15:47:59.248  3542  3542 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.BOOT_COMPLETED
03-18 15:47:59.248  3542  3542 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Version: 4.82
03-18 15:47:59.248  3542  3542 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Push type: [SPP, GCM]
,03-18 15:47:59.268  3905  3905 E Zygote  : MountEmulatedStorage(),
,03-18 15:47:59.278  3905  3905 E Zygote  : v2,
,03-18 15:47:59.278  3905  3905 I libpersona: KNOX_SDCARD checking this for 10003
03-18 15:47:59.278  1019  1058 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=3905 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a,
03-18 15:47:59.278  3905  3905 I libpersona: KNOX_SDCARD not a persona
,03-18 15:47:59.278  3542  3542 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account,
03-18 15:47:59.278  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:59.278  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:59.278  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:59.278  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,03-18 15:47:59.278  3905  3905 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-18 15:47:59.288  3905  3905 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-18 15:47:59.288  3905  3905 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-18 15:47:59.308  3542  3542 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,03-18 15:47:59.318  3542  3542 I ReactiveServiceManager: Supported : 1
,03-18 15:47:59.328  1019  1212 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
03-18 15:47:59.328  1019  1212 D QSEECOMAPI: : App is not loaded in QSEE
,03-18 15:47:59.348  3920  3920 E Zygote  : MountEmulatedStorage()
03-18 15:47:59.348  3920  3920 E Zygote  : v2
03-18 15:47:59.348  3920  3920 I libpersona: KNOX_SDCARD checking this for 1000
03-18 15:47:59.348  3920  3920 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:59.348  3920  3920 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-18 15:47:59.348  3920  3920 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-18 15:47:59.348  3920  3920 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-18 15:47:59.358  1019  1490 I ActivityManager: Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3920 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-18 15:47:59.358  1019  1031 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
03-18 15:47:59.368  1019  1212 D QSEECOMAPI: : Loaded image: APP id = 9
,03-18 15:47:59.368  1019  3217 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-18 15:47:59.368  3905  3905 D TimaKeyStoreProvider: TimaSignature is unavailable
03-18 15:47:59.368  3905  3905 D ActivityThread: Added TimaKeyStore provider
03-18 15:47:59.378  1019  1509 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:59.378  1019  1509 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:59.378  1019  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-18 15:47:59.388  1019  1212 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-18 15:47:59.388  1019  1212 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 9
,03-18 15:47:59.388  1019  1212 E terrier : handleString: Failed to handle string(-4)
03-18 15:47:59.388  1019  1212 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
03-18 15:47:59.388  3871  3871 D NPS_WSSNPS: [50.150321] smlDBHelper
,03-18 15:47:59.388  3692  3692 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-18 15:47:59.398  3542  3542 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
03-18 15:47:59.398  3542  3542 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
,03-18 15:47:59.398  3542  3542 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-18 15:47:59.398  3542  3542 I PCWCLIENTTRACE_PushUtil: sales region : global
03-18 15:47:59.398  3542  3542 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-18 15:47:59.398  3542  3542 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,03-18 15:47:59.398  3920  3920 D TimaKeyStoreProvider: TimaSignature is unavailable
03-18 15:47:59.398  3920  3920 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:59.398  1019  1569 I art     : Explicit concurrent mark sweep GC freed 14323(663KB) AllocSpace objects, 1(930KB) LOS objects, 33% free, 23MB/35MB, paused 7.832ms total 245.200ms
,03-18 15:47:59.398  2632  2632 D FactoryTestApp: [DummyFtClient$onDestroy](2632) Destroy DummyFtClient service
,03-18 15:47:59.418  2632  2632 D FactoryTestApp: [Support$Values.getString](2632) id=MODEL_COMMUNICATION_MODE, value=gsm
,03-18 15:47:59.418  2632  2632 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2632) mConnectionMode = gsm
,03-18 15:47:59.418  2632  2632 I FactoryTestApp: [ModuleCommon$isRunningFtClient](2632) RUNNING_FTCLIENT : false
,03-18 15:47:59.418  2632  2632 D FactoryTestApp: [DummyFtClient$onDestroy](2632) kill process
,03-18 15:47:59.418  2632  2632 I Process : Sending signal. PID: 2632 SIG: 9
,03-18 15:47:59.428  1019  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:59.428  1019  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:59.428  1019  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:59.428  1019  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:59.448  3936  3936 E Zygote  : MountEmulatedStorage()
,03-18 15:47:59.448  3936  3936 E Zygote  : v2
03-18 15:47:59.448  3936  3936 I libpersona: KNOX_SDCARD checking this for 10028
03-18 15:47:59.448  3936  3936 I libpersona: KNOX_SDCARD not a persona
,03-18 15:47:59.448  1019  1509 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3936 uid=10028 gids={50028, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
03-18 15:47:59.448  3936  3936 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-18 15:47:59.458  1019  1470 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:59.458  1019  1470 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:59.458  1019  1470 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-18 15:47:59.458  3871  3871 I NPS_WSSNPS: [50.150321] AsyncBulkFlagCheck
03-18 15:47:59.458  3936  3936 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-18 15:47:59.458  3936  3936 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-18 15:47:59.468  3871  3942 I NPS_WSSNPS: [50.150321] IsRemain_AsyncBulkCheck
03-18 15:47:59.468  1019  1043 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
03-18 15:47:59.468  3871  3942 I NPS_WSSNPS: [50.150321] IsRemain_Asyncing nothing
,03-18 15:47:59.468  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-18 15:47:59.468  3871  3942 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,03-18 15:47:59.478  1019  3217 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:47:59.478  1019  3217 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:59.478  1019  3217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-18 15:47:59.478  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-18 15:47:59.488  1019  3835 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:59.488  1019  3835 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:59.488  1019  3835 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-18 15:47:59.488  3871  3871 D NPS_WSSNPS: [50.150321] Service onDestroy
,03-18 15:47:59.488  3701  3945 E Gmail   : Error finding the version of the Email provider.....
03-18 15:47:59.488  3701  3945 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
03-18 15:47:59.488  3701  3945 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
03-18 15:47:59.488  3701  3945 E Gmail   : 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
03-18 15:47:59.488  3701  3945 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
03-18 15:47:59.488  3701  3945 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-18 15:47:59.488  3701  3945 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-18 15:47:59.488  3701  3945 E Gmail   : 	at android.os.Looper.loop(Looper.java:145)
03-18 15:47:59.488  3701  3945 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-18 15:47:59.488  3701  3945 W EmailMigration: We do not support migrating this version of the Email provider.
,03-18 15:47:59.498  3936  3936 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:59.498  3936  3936 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:59.508  1019  1079 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:59.508  1019  1079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:59.508  1019  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
03-18 15:47:59.508  3657  3657 I Finsky  : [1] com.google.android.finsky.services.ar.a(1049): Restore complete with 0 success and 0 failed.
,03-18 15:47:59.508  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-18 15:47:59.518  1019  1043 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-18 15:47:59.518  1019  1043 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-18 15:47:59.518  1019  1043 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-18 15:47:59.518  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-18 15:47:59.518  1019  1470 I ActivityManager: Process com.sec.factory (pid 2632)(adj 0) has died(88,620)
,03-18 15:47:59.538  1019  3835 D SettingsProvider: name = access_control_enabled
,03-18 15:47:59.538  3871  3871 I NPS_WSSNPS: [50.150321] smlBRConfigurationDelete
03-18 15:47:59.538  3871  3871 I NPS_WSSNPS: [50.150321] smlBRMessageDelete
,03-18 15:47:59.538  1019  1032 I ActivityManager: Killing 3042:com.sec.android.app.safetyassurance/u0a43 (adj 15): empty #31
,03-18 15:47:59.548  1019  1212 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:59.548  1019  1212 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:59.548  1019  1212 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-18 15:47:59.548  3871  3871 I NPS_WSSNPS: [50.150321] smlBREmailDelete
,03-18 15:47:59.548  3871  3871 I NPS_WSSNPS: [50.150321] smlBRNetworkDelete
,03-18 15:47:59.558  1019  1561 I ActivityManager: Killing 2904:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #31
,03-18 15:47:59.558  3871  3871 I NPS_WSSNPS: [50.150321] smlBRCallLogDelete
,03-18 15:47:59.558  3871  3871 I NPS_WSSNPS: [50.150321] smlBRMiniDiaryDelete
,03-18 15:47:59.558  3871  3871 I NPS_WSSNPS: [50.150321] smlBRPenMemoMDelete
03-18 15:47:59.558  3871  3871 I NPS_WSSNPS: [50.150321] smlBRSMemoDelete
,03-18 15:47:59.558  3871  3871 I NPS_WSSNPS: [50.150321] cpuBooster release : false
,03-18 15:47:59.558  1510  1510 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-18 15:47:59.568  1510  1510 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-18 15:47:59.568  3871  3871 D NPS_WSSNPS: [50.150321] dsServerSocket close
,03-18 15:47:59.568  1019  1467 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:59.568  1019  1467 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:59.568  1019  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-18 15:47:59.568  1019  1509 I ActivityManager: Killing 3126:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,03-18 15:47:59.568  2003  2003 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-18 15:47:59.578  1019  3834 I ActivityManager: Killing 3141:com.sec.dsm.system/1000 (adj 15): empty #31
,03-18 15:47:59.598  1019  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:59.598  1019  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:59.598  1019  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:59.598  1019  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:59.618  3701  3867 I Gmail   : getAccountsCursor
,03-18 15:47:59.628  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-18 15:47:59.628  3961  3961 E Zygote  : MountEmulatedStorage()
,03-18 15:47:59.628  3961  3961 E Zygote  : v2
03-18 15:47:59.628  3961  3961 I libpersona: KNOX_SDCARD checking this for 10065
03-18 15:47:59.628  3961  3961 I libpersona: KNOX_SDCARD not a persona
,03-18 15:47:59.628  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-18 15:47:59.628  3961  3961 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-18 15:47:59.628  3961  3961 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-18 15:47:59.638  3961  3961 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-18 15:47:59.638  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-18 15:47:59.638  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-18 15:47:59.638  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-18 15:47:59.638  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-18 15:47:59.638  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-18 15:47:59.648  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-18 15:47:59.648  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-18 15:47:59.648  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-18 15:47:59.648  1019  1509 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3961 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-18 15:47:59.658   311   311 I art     : Explicit concurrent mark sweep GC freed 8710(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 614us total 20.637ms
,03-18 15:47:59.658  3961  3961 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:59.658  3961  3961 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:59.668  1019  1464 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:47:59.668  1019  1464 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-18 15:47:59.668  1019  1464 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-18 15:47:59.668   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 579us total 16.877ms
,03-18 15:47:59.678  1019  1032 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-18 15:47:59.688  1019  1043 D UsbSettingsManager: clearDefaults: com.test.thalitest
,03-18 15:47:59.688  1019  1043 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,03-18 15:47:59.688  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2995/cgroup.procs: No such file or directory
,03-18 15:47:59.688   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 597us total 17.129ms
,03-18 15:47:59.688  1019  1043 W libprocessgroup: failed to open /acct/uid_10096/pid_2292/cgroup.procs: No such file or directory
,03-18 15:47:59.688  1019  1043 W libprocessgroup: failed to open /acct/uid_10041/pid_2420/cgroup.procs: No such file or directory
,03-18 15:47:59.698  1019  1043 W libprocessgroup: failed to open /acct/uid_10043/pid_3042/cgroup.procs: No such file or directory
03-18 15:47:59.698  1019  1043 W libprocessgroup: failed to open /acct/uid_10081/pid_2904/cgroup.procs: No such file or directory
03-18 15:47:59.698  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3126/cgroup.procs: No such file or directory
03-18 15:47:59.698  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3141/cgroup.procs: No such file or directory
,03-18 15:47:59.708  1019  1467 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-18 15:47:59.708  3350  3394 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-18 15:47:59.708  3701  3701 E ActivityThread: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@186ebcee that was originally bound here
03-18 15:47:59.708  3701  3701 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@186ebcee that was originally bound here
03-18 15:47:59.708  3701  3701 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
03-18 15:47:59.708  3701  3701 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
03-18 15:47:59.708  3701  3701 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
03-18 15:47:59.708  3701  3701 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
03-18 15:47:59.708  3701  3701 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
03-18 15:47:59.708  3701  3701 E ActivityThread: 	at com.android.emailcommon.service.H.a(SourceFile:181)
03-18 15:47:59.708  3701  3701 E ActivityThread: 	at com.android.emailcommon.service.H.mb(SourceFile:224)
03-18 15:47:59.708  3701  3701 E ActivityThread: 	at com.android.email.service.n.j(SourceFile:160)
03-18 15:47:59.708  3701  3701 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:171)
03-18 15:47:59.708  3701  3701 E ActivityThread: 	at com.android.email.provider.b.F(SourceFile:115)
03-18 15:47:59.708  3701  3701 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.kD(SourceFile:305)
03-18 15:47:59.708  3701  3701 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:130)
03-18 15:47:59.708  3701  3701 E ActivityThread: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-18 15:47:59.708  3701  3701 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-18 15:47:59.708  3701  3701 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-18 15:47:59.708  3701  3701 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-18 15:47:59.708  1019  1561 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@209895f5
,03-18 15:47:59.728  3350  3394 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-18 15:47:59.738  3350  3394 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-18 15:47:59.738  3350  3394 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-18 15:47:59.738  3350  3394 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
03-18 15:47:59.738  3350  3394 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
03-18 15:47:59.738  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:59.738  1019  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:59.738  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,03-18 15:47:59.738  3350  3394 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-18 15:47:59.738  3350  3394 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-18 15:47:59.748  1339  3192 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-18 15:47:59.748  1019  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:59.748  1019  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:59.748  1019  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:59.748  1019  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:59.768  3978  3978 E Zygote  : MountEmulatedStorage()
03-18 15:47:59.768  3978  3978 E Zygote  : v2
03-18 15:47:59.768  3978  3978 I libpersona: KNOX_SDCARD checking this for 10102
03-18 15:47:59.768  3978  3978 I libpersona: KNOX_SDCARD not a persona
,03-18 15:47:59.768  3978  3978 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-18 15:47:59.768  3978  3978 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-18 15:47:59.768  3978  3978 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-18 15:47:59.778  1019  1464 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3978 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,03-18 15:47:59.788  1019  1563 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:59.788  1019  1563 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:47:59.788  1019  1563 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-18 15:47:59.788  3701  3957 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-18 15:47:59.788  3701  3957 E SQLiteLog: (3850) statement aborts at 1: [BEGIN IMMEDIATE;] disk I/O error
,03-18 15:47:59.788  3961  3961 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,03-18 15:47:59.788  1659  3977 I GoogleHttpClient: GMS http client unavailable, use old client
,03-18 15:47:59.798  2003  2003 D ChimeraCfgMgr: Reading stored module config
,03-18 15:47:59.798  3701  3957 E Gmail   : Error handling intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gm/.GmailIntentService (has extras) }
03-18 15:47:59.798  3701  3957 E Gmail   : android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-18 15:47:59.798  3701  3957 E Gmail   : 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-18 15:47:59.798  3701  3957 E Gmail   : 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
03-18 15:47:59.798  3701  3957 E Gmail   : 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:319)
03-18 15:47:59.798  3701  3957 E Gmail   : 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-18 15:47:59.798  3701  3957 E Gmail   : 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
03-18 15:47:59.798  3701  3957 E Gmail   : 	at android.database.sqlite.SQLiteDatabase.beginTransactionNonExclusive(SQLiteDatabase.java:445)
03-18 15:47:59.798  3701  3957 E Gmail   : 	at com.google.android.gm.provider.MailEngine.<init>(SourceFile:1257)
03-18 15:47:59.798  3701  3957 E Gmail   : 	at com.google.android.gm.provider.MailEngine.V(SourceFile:966)
03-18 15:47:59.798  3701  3957 E Gmail   : 	at com.google.android.gm.provider.MailEngine.W(SourceFile:999)
03-18 15:47:59.798  3701  3957 E Gmail   : 	at com.google.android.gm.GmailIntentService.i(SourceFile:181)
03-18 15:47:59.798  3701  3957 E Gmail   : 	at com.google.android.gm.GmailIntentService.onHandleIntent(SourceFile:70)
03-18 15:47:59.798  3701  3957 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-18 15:47:59.798  3701  3957 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-18 15:47:59.798  3701  3957 E Gmail   : 	at android.os.Looper.loop(Looper.java:145)
03-18 15:47:59.798  3701  3957 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-18 15:47:59.808  3701  3845 I Gmail   : getAccountsCursor
,03-18 15:47:59.818  3978  3978 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:59.818  3978  3978 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:59.828  3978  3978 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-18 15:47:59.968  3936  3936 I System.out: Inside onCreate() of WakeupTriggerProvide
,03-18 15:47:59.968  3936  3936 I System.out: Inside WakeupProvider
,03-18 15:47:59.978  3248  3297 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,03-18 15:47:59.988  1019  1098 V AlarmManager: waitForAlarm result :8
,03-18 15:47:59.988  1188  1188 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-18 15:47:59.988  1188  1188 D KeyguardUpdateMonitor: handleTimeUpdate
,03-18 15:47:59.998  1188  1188 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-18 15:47:59.998  1188  1188 D SecKeyguardClockView: HomeTimezone(): 1
,03-18 15:48:00.008  1188  1188 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-18 15:48:00.008  1188  1188 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,03-18 15:48:00.038  1188  1188 I KeyguardEffectViewController: *** don't update sliding image ***
,03-18 15:48:00.058  1019  1665 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:48:00.058  1019  1665 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-18 15:48:00.058  1019  1665 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-18 15:48:00.068  3936  3936 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.40139', coreVersion = '2.6.1.16800', ro.csc.sales_code=XEO
,03-18 15:48:00.078  1188  1188 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-18 15:48:00.078  1188  1188 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-18 15:48:00.088  1188  1188 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-18 15:48:00.088  1188  1188 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,03-18 15:48:00.098  1772  1772 D accuweather: [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK
,03-18 15:48:00.098  1772  1772 D accuweather: [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,03-18 15:48:00.098  1772  1772 D accuweather: [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,03-18 15:48:00.098  1772  1772 D accuweather: [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,03-18 15:48:00.098  1772  1772 D accuweather: [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,03-18 15:48:00.108  1772  1772 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
,03-18 15:48:00.108  1772  1772 D accuweather: [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 1
,03-18 15:48:00.108  1772  1772 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
03-18 15:48:00.108  1772  1772 D accuweather: [KK AccuPhone]>>> UIM:178 [0:0] get widget 4x1 view!!! wid = 2
,03-18 15:48:00.108  1772  1772 E accuweather: [KK AccuPhone]>>> UIM:1488 [0:0] bTM 15 48
,03-18 15:48:00.128  1339  1360 W art     : Suspending all threads took: 336.255ms
,03-18 15:48:00.128  1188  1188 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-18 15:48:00.138  1510  1844 W OpenGLRenderer: SFEffectCache::get: create texture(0xa1cbc724): name, size, mSize = 34, 84660, 209660
,03-18 15:48:00.158  2003  2003 D WearableService: callingUid 10011, callindPid: 2003
,03-18 15:48:00.168  3936  3936 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.1.16800, SDK: 2.0.2137, EDM:16800
,03-18 15:48:00.198  2003  2003 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-18 15:48:00.208  2003  2003 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-18 15:48:00.208  2003  2003 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-18 15:48:00.228  3701  4006 E SQLiteLog: (283) recovered 10 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-18 15:48:00.228  2158  2158 W InstanceID/Rpc: Found 10011
,03-18 15:48:00.238  2003  2003 E GmsWearableNodeHelper: GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-18 15:48:00.248  1019  1569 W ActivityManager: userId = 0, bbcId = -10000,
03-18 15:48:00.248  1019  1569 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:48:00.248  1019  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-18 15:48:00.298  1019  1464 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:48:00.298  1019  1464 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:48:00.298  1019  1464 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-18 15:48:00.328  1019  1467 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:48:00.328  1019  1467 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:48:00.328  1019  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-18 15:48:00.358  3936  3936 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,03-18 15:48:00.358  3936  3936 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,03-18 15:48:00.388  3936  3936 D DialogFlow: initQueue()
,03-18 15:48:00.408  3978  4017 I Babel   : MmsConfig: mnc/mcc: 0/0
,03-18 15:48:00.408  3978  4017 I Babel   : MmsConfig.loadMmsSettings
,03-18 15:48:00.408  3978  4017 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,03-18 15:48:00.408  3978  4017 I Babel   : MmsConfig.loadFromDatabase
,03-18 15:48:00.418  1019  1470 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:48:00.418  1019  1470 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:48:00.418  1019  1470 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-18 15:48:00.428  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:48:00.428  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:48:00.428  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:48:00.428  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:48:00.438  4019  4019 E Zygote  : MountEmulatedStorage()
03-18 15:48:00.438  4019  4019 E Zygote  : v2
03-18 15:48:00.438  4019  4019 I libpersona: KNOX_SDCARD checking this for 10029
03-18 15:48:00.438  4019  4019 I libpersona: KNOX_SDCARD not a persona
,03-18 15:48:00.438  4019  4019 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-18 15:48:00.438  1019  1031 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=4019 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,03-18 15:48:00.448  4019  4019 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-18 15:48:00.448  4019  4019 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-18 15:48:00.468  4019  4019 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:48:00.468  4019  4019 D ActivityThread: Added TimaKeyStore provider
,03-18 15:48:00.468  1019  1563 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:48:00.468  1019  1563 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:48:00.468  1019  1563 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-18 15:48:00.478  1188  1188 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-18 15:48:00.478  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-18 15:48:00.478  1188  1188 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-18 15:48:00.478  1188  1188 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-18 15:48:00.478  1188  1188 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-18 15:48:00.478  1188  1188 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-18 15:48:00.538  3978  3994 W art     : Suspending all threads took: 59.051ms
,03-18 15:48:00.538  1019  1470 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:48:00.538  1019  1470 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:48:00.548  1019  1470 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-18 15:48:00.558  2158  4015 I Icing   : Storage manager: low false usage 2.12MB avail 9.97GB capacity 11.63GB
,03-18 15:48:00.568  1019  1470 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:48:00.568  1019  1470 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:48:00.568  1019  1470 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-18 15:48:00.568  3978  3978 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-18 15:48:00.578  3978  4017 E Babel   : canonicalizeMccMnc: invalid mccmnc 
03-18 15:48:00.578  3978  4017 I Babel   : MmsConfig.loadFromResources
,03-18 15:48:00.578  3978  4017 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
03-18 15:48:00.578  3978  4017 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,03-18 15:48:00.588  3978  4016 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-18 15:48:00.598  3978  4016 W AudioCapabilities: Unsupported mime audio/evrc
,03-18 15:48:00.608  3978  4016 W AudioCapabilities: Unsupported mime audio/qcelp
,03-18 15:48:00.618  3978  4016 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,03-18 15:48:00.618  3978  4016 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,03-18 15:48:00.628  3978  4016 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,03-18 15:48:00.628  3978  4016 W AudioCapabilities: Unsupported mime audio/x-ima
,03-18 15:48:00.628  3978  4016 W AudioCapabilities: Unsupported mime audio/qcelp
,03-18 15:48:00.628  3978  4016 W AudioCapabilities: Unsupported mime audio/evrc
,03-18 15:48:00.648  1019  1467 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:48:00.648  1019  1467 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-18 15:48:00.648  1019  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,03-18 15:48:00.648   292   292 E SMD     : DCD OFF
,03-18 15:48:00.648  3235  3247 E SQLiteLog: (1034) os_unix.c:30228: (30) full_fsync(/data/user/0/com.sec.providers.settingsearch/databases/settingsearch.db) - 
,03-18 15:48:00.658  3235  3247 E SQLiteLog: (1546) os_unix.c:30272: (30) ftruncate(/data/user/0/com.sec.providers.settingsearch/databases/settingsearch.db) - 
,03-18 15:48:00.658  3235  3247 E DatabaseUtils: Writing exception to parcel
03-18 15:48:00.658  3235  3247 E DatabaseUtils: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 1034)
03-18 15:48:00.658  3235  3247 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-18 15:48:00.658  3235  3247 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
03-18 15:48:00.658  3235  3247 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
03-18 15:48:00.658  3235  3247 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
03-18 15:48:00.658  3235  3247 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:527)
03-18 15:48:00.658  3235  3247 E DatabaseUtils: 	at com.sec.providers.settingsearch.SettingSearchProvider.addSearchInfoDB(SettingSearchProvider.java:1036)
03-18 15:48:00.658  3235  3247 E DatabaseUtils: 	at com.sec.providers.settingsearch.SettingSearchProvider.call(SettingSearchProvider.java:893)
03-18 15:48:00.658  3235  3247 E DatabaseUtils: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:382)
03-18 15:48:00.658  3235  3247 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:282)
03-18 15:48:00.658  3235  3247 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:461)
,03-18 15:48:00.658  3961  3961 E SQLiteLog: (10) unixWrite() File Descriptor : 25 gets errno : 30
,03-18 15:48:00.658  3961  3961 E SQLiteLog: (10) unixWrite() File Descriptor : 25 gets errno : 30
,03-18 15:48:00.658  3961  3961 E FileShare-Server: ServerBroadcastReceiver.onReceive - exception android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
,03-18 15:48:00.668  3978  4016 W VideoCapabilities: Unsupported mime video/wvc1
,03-18 15:48:00.668  1019  1470 I ActivityManager: Killing 3222:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,03-18 15:48:00.668  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:48:00.668  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:48:00.668  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:48:00.668  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:48:00.668  3978  4016 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-18 15:48:00.688  4046  4046 E Zygote  : MountEmulatedStorage()
03-18 15:48:00.688  4046  4046 E Zygote  : v2
03-18 15:48:00.688  4046  4046 I libpersona: KNOX_SDCARD checking this for 10030
03-18 15:48:00.688  4046  4046 I libpersona: KNOX_SDCARD not a persona
,03-18 15:48:00.688  4046  4046 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-18 15:48:00.688  4046  4046 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-18 15:48:00.688  4046  4046 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-18 15:48:00.688  3978  3978 V Babel   : babel boot account: SMS
,03-18 15:48:00.698  1339  3192 E AndroidRuntime: FATAL EXCEPTION: Thread-59
03-18 15:48:00.698  1339  3192 E AndroidRuntime: Process: com.android.settings, PID: 1339
03-18 15:48:00.698  1339  3192 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 1034)
03-18 15:48:00.698  1339  3192 E AndroidRuntime: 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:179)
03-18 15:48:00.698  1339  3192 E AndroidRuntime: 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
03-18 15:48:00.698  1339  3192 E AndroidRuntime: 	at android.content.ContentProviderProxy.call(ContentProviderNative.java:643)
03-18 15:48:00.698  1339  3192 E AndroidRuntime: 	at android.content.ContentResolver.call(ContentResolver.java:1425)
03-18 15:48:00.698  1339  3192 E AndroidRuntime: 	at com.android.settings.settingssearch.SettingsSearchManager.addSearchInfoDB(SettingsSearchManager.java:181)
03-18 15:48:00.698  1339  3192 E AndroidRuntime: 	at com.android.settings.settingssearch.SettingsSearchUtils.initSearchDB(SettingsSearchUtils.java:330)
03-18 15:48:00.698  1339  3192 E AndroidRuntime: 	at com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run(SettingsSearchIntentReceiver.java:128)
,03-18 15:48:00.698  1019  1032 I ActivityManager: Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4046 uid=10030 gids={50030, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-18 15:48:00.698  1019  1032 I ActivityManager: Killing 3235:com.sec.providers.settingsearch/u0a146 (adj 15): empty #31
,03-18 15:48:00.698  3978  3978 V Babel   : babel boot account: thalitester@gmail.com
,03-18 15:48:00.708  3701  4006 E File    : fail readDirectory() errno=2
,03-18 15:48:00.708  3701  4007 I Gmail   : notifyAccountChanged
03-18 15:48:00.708  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:48:00.708  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:48:00.708  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:48:00.708  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:48:00.708  4019  4019 E SharedPreferencesImpl: Couldn't rename file /data/data/com.samsung.android.app.galaxyfinder/shared_prefs/pref_tagservice_state.xml to backup file /data/data/com.samsung.android.app.galaxyfinder/shared_prefs/pref_tagservice_state.xml.bak
,03-18 15:48:00.718  4046  4046 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:48:00.718  4046  4046 D ActivityThread: Added TimaKeyStore provider
,03-18 15:48:00.718  3701  3868 I Gmail   : getAccountsCursor
,03-18 15:48:00.728  4064  4064 E Zygote  : MountEmulatedStorage()
03-18 15:48:00.728  4064  4064 E Zygote  : v2
03-18 15:48:00.728  4064  4064 I libpersona: KNOX_SDCARD checking this for 1000
03-18 15:48:00.728  4064  4064 I libpersona: KNOX_SDCARD not a persona
,03-18 15:48:00.728  4064  4064 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-18 15:48:00.728  4064  4064 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-18 15:48:00.728  4064  4064 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-18 15:48:00.728  1019  1032 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4064 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-18 15:48:00.738  3701  4007 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
03-18 15:48:00.738  1019  1032 I ActivityManager: Killing 3278:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,03-18 15:48:00.738  1019  1032 I ActivityManager: Killing 3171:com.google.android.configupdater/u0a82 (adj 15): empty #31
,03-18 15:48:00.748  3978  4016 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,03-18 15:48:00.748  3978  4016 W VideoCapabilities: Unsupported mime video/wvc1
,03-18 15:48:00.748  4064  4064 D TimaKeyStoreProvider: TimaSignature is unavailable
03-18 15:48:00.748  3978  4016 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-18 15:48:00.748  4064  4064 D ActivityThread: Added TimaKeyStore provider
,03-18 15:48:00.748  3978  4016 W VideoCapabilities: Unsupported mime video/x-ms-wmv7,
,03-18 15:48:00.768  1019  1019 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,03-18 15:48:00.768  1019  1019 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
,03-18 15:48:00.768  2003  2003 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-18 15:48:00.778  1019  3834 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings

```
