#### Test 519863409bc5c94_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
E/SQLiteLog( 2926): (283) recovered 24 frames from WAL file /data/data/com.google.android.apps.docs/databases/DocList.db-wal
--------- beginning of system
W/ResourcesManager( 2926): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2926): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Finsky  ( 2460): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
I/ActivityManager(  756): Killing 2265:com.google.android.youtube/u0a80 (adj 15): empty #17
V/JNIHelp ( 2926): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
W/System  ( 2926): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2926): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  756): failed to open /acct/uid_10080/pid_2265/cgroup.procs: No such file or directory
V/GLSActivity( 1400): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1614): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
D/Icing   ( 1614): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1614): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
,I/ActivityManager(  756): Killing 2372:com.google.android.deskclock/u0a38 (adj 15): empty #17
W/libprocessgroup(  756): failed to open /acct/uid_10038/pid_2372/cgroup.procs: No such file or directory
D/AndroidRuntime( 2978): 
D/AndroidRuntime( 2978): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2978): CheckJNI is OFF
D/AndroidRuntime( 2978): Calling main entry com.android.commands.am.Am
I/ActivityManager(  756): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  756): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3002 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2978): Shutting down VM
V/ActivityManager(  756): Display changed displayId=0
,I/WebViewFactory( 3002): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3002): Time to load native libraries: 2 ms (timestamps 7293-7295)
I/LibraryLoader( 3002): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3002): Binding Chromium to main looper Looper (main, tid 1) {2118b849}
,I/LibraryLoader( 3002): Expected native library version number "",actual native library version number ""
,I/chromium( 3002): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3002): Initializing chromium process, singleProcess=true
,W/art     ( 3002): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3002): ApplicationContext is null in ApplicationStatus
,W/chromium( 3002): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 3002): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3002): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3002): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3002): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  756): Message: 20
D/BluetoothManagerService(  756): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@19c22914:true
,D/BluetoothAdapter( 3002): 596060811: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 3002): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3002): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3002): CordovaWebView is running on device made by: LGE
,W/art     ( 3002): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3002): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3002): Render dirty regions requested: true
,D/Atlas   ( 3002): Validating map...
,W/chromium( 3002): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3002): Initialized EGL, version 1.4
D/OpenGLRenderer( 3002): Enabling debug mode 0
,W/BindingManager( 3002): Cannot call determinedVisibility() - never saw a connection for the pid: 3002
,W/IInputConnectionWrapper( 3002): showStatusIcon on inactive InputConnection
,I/ActivityManager(  756): Displayed com.test.thalitest/.MainActivity: +416ms (total +55s862ms)
,D/JsMessageQueue( 3002): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3002): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 3002): jxcore cordova android initializing
,W/jxcore-log( 3002): Initializing JXcore engine
W/jxcore-log( 3002): JXcore engine is ready
,W/jxcore-log( 3002): Starting JXcore engine
,W/.test.thalitest( 3002): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8001]" dev="sockfs" ino=8001 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3002): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3002): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6548]" dev="sockfs" ino=6548 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3002): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19482]" dev="sockfs" ino=19482 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3002): Platform android
W/jxcore-log( 3002): 
,W/jxcore-log( 3002): Process ARCH arm
W/jxcore-log( 3002): 
,I/jxcore-log( 3002): JXcore Cordova bridge is ready!
I/jxcore-log( 3002): 
,W/jxcore-log( 3002): JXcore engine is started
I/chromium( 3002): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3002): Toggling radios to true
I/jxcore-log( 3002): 
,D/BluetoothManagerService(  756): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  756): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  756): Message: 1
D/BluetoothManagerService(  756): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  756): New client listening to asynchronous messages
,D/WifiService(  756): setWifiEnabled: true pid=3002, uid=10270
E/WifiService(  756): Invoking mWifiStateMachine.setWifiEnabled
,I/ActivityManager(  756): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3052 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/SoftapController(  179): Softap fwReload - Ok
,I/jxcore-log( 3002): Radios toggled
I/jxcore-log( 3002): 
D/CommandListener(  179): Setting iface cfg
D/CommandListener(  179): Trying to bring down wlan0
D/CommandListener(  179): Clearing all IP addresses on wlan0
,W/ResourcesManager( 3052): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/AdapterServiceConfig( 3052): Adding HeadsetService
D/AdapterServiceConfig( 3052): Adding A2dpService
D/AdapterServiceConfig( 3052): Adding HidService
D/AdapterServiceConfig( 3052): Adding HealthService
D/AdapterServiceConfig( 3052): Adding PanService
D/AdapterServiceConfig( 3052): Adding GattService
D/AdapterServiceConfig( 3052): Adding BluetoothMapService
,D/BluetoothManagerService(  756): Message: 20
,D/BluetoothManagerService(  756): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@31b10aba:true
,D/BluetoothAdapterState( 3052): make
,I/bluedroid( 3052): init
I/BluetoothAdapterState( 3052): Entering OffState
,I/bte_conf( 3052): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3052): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3052): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3052): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3052): get_profile_interface socket
I/bluedroid( 3052): get_profile_interface map_client
,I/GKI_LINUX( 3052): gki_task_entry task_id=1 [BTIF] starting
D/BluetoothManagerService(  756): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  756): Message: 40
D/BluetoothManagerService(  756): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothAdapterProperties( 3052): Address is:34:FC:EF:11:AE:67
,D/BluetoothAdapterProperties( 3052): Name is: Nexus 5
I/bluedroid( 3052): config_hci_snoop_log
D/BluetoothManagerService(  756): Bluetooth Adapter name changed to Nexus 5
,D/BluetoothManagerService(  756): Stored Bluetooth name: Nexus 5
,D/BluetoothManagerService(  756): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  756): Broadcasting onBluetoothServiceUp() to 9 receivers.
,I/wpa_supplicant( 3083): Successfully initialized wpa_supplicant
,D/BluetoothAdapterState( 3052): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3052): Setting state to 11
I/BluetoothAdapterState( 3052): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService(  756): Message: 60
D/BluetoothManagerService(  756): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  756): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 3052): make
,I/BluetoothBondStateMachine( 3052): StableState(): Entering Off State
,I/ActivityManager(  756): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=3090 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/wpa_supplicant( 3083): rfkill: Cannot open RFKILL control device
,D/WifiMonitor(  756): startMonitoring(wlan0) with mConnected = false
,D/BluetoothHeadset( 1210): Proxy object connected
,D/HeadsetService( 3052): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3052): classInitNative: succeeds
,D/BluetoothHeadset( 1174): Proxy object connected
,D/BluetoothHeadset( 1174): Proxy object connected
D/HeadsetStateMachine( 3052): make
,D/BluetoothHeadset(  756): Proxy object connected
,I/BluetoothAdapterState( 3052): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetStateMachine( 3052): max_hf_connections = 1
I/bluedroid( 3052): get_profile_interface handsfree
,D/BluetoothAdapterService( 3052): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3122e54e
,D/HeadsetStateMachine( 3052): Enter Disconnected: -2, size: 0
,D/A2dpService( 3052): Received start request. Starting profile...
D/BluetoothA2dp(  756): Proxy object connected
I/BluetoothAvrcpServiceJni( 3052): classInitNative: succeeds
I/bluedroid( 3052): get_profile_interface avrcp
,E/RemoteController( 3052): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3052): classInitNative: succeeds
D/A2dpStateMachine( 3052): make
,I/bluedroid( 3052): get_profile_interface a2dp
I/GKI_LINUX( 3052): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothAdapterService( 3052): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3122e54e
D/A2dpStateMachine( 3052): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 3052): classInitNative: succeeds
,D/HidService( 3052): Received start request. Starting profile...
I/bluedroid( 3052): get_profile_interface hidhost
D/BluetoothAdapterService( 3052): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3122e54e
I/BluetoothHealthServiceJni( 3052): classInitNative: succeeds
D/HealthService( 3052): Received start request. Starting profile...
,I/bluedroid( 3052): get_profile_interface health
D/BluetoothAdapterService( 3052): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3122e54e
,I/BluetoothPanServiceJni( 3052): classInitNative(L105): succeeds
,D/PanService( 3052): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3052): initializeNative(L110): pan
,I/bluedroid( 3052): get_profile_interface pan
,D/BluetoothAdapterService( 3052): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3122e54e
,I/BtGatt.JNI( 3052): classInitNative(L863): classInitNative: Success!
D/BtGatt.DebugUtils( 3052): handleDebugAction() action=null
D/BtGatt.GattService( 3052): Received start request. Starting profile...
D/BtGatt.GattService( 3052): start()
I/bluedroid( 3052): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 3052): advertise manager created
,D/BluetoothAdapterService( 3052): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3122e54e
,V/BluetoothMapService( 3052): BluetoothMapBinder()
D/HeadsetStateMachine( 3052): Proxy object connected
,D/BluetoothMapService( 3052): Received start request. Starting profile...
D/BluetoothMapService( 3052): start()
,D/BluetoothMapEmailSettingsLoader( 3052): Found 0 applications
D/BluetoothMapEmailAppObserver( 3052): createReceiver()
,D/BluetoothMapEmailAppObserver( 3052): initObservers()
D/BluetoothMapEmailAppObserver( 3052): getEnabledAccountItems()
D/BluetoothAdapterService( 3052): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3122e54e
D/HeadsetStateMachine( 3052): Disconnected process message: 10, size: 0
V/BluetoothMapService( 3052): Handler(): got msg=1
D/HeadsetPhoneState( 3052): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3052): Disconnected process message: 11, size: 0
D/BluetoothAdapterState( 3052): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3052): enable
,I/bt_hci_bdroid( 3052): init
I/GKI_LINUX( 3052): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3052): btu_task pending for preload complete event
,I/bt_vendor( 3052): init
I/bt_vnd_conf( 3052): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3052): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3052): userial_init
I/ActivityManager(  756): Killing 2430:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,I/bt_userial_vendor( 3052): userial vendor open: opening /dev/ttyHS99
,I/bt_userial_vendor( 3052): device fd = 53 open
,D/bt_userial( 3052): Entering userial_read_thread()
,W/libprocessgroup(  756): failed to open /acct/uid_10069/pid_2430/cgroup.procs: No such file or directory
,D/WifiService(  756): New client listening to asynchronous messages
,D/AuthorizationBluetoothService( 1400): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/bt_hwcfg( 3052): bt vendor lib: set UART baud 4000000
,I/ActivityManager(  756): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3123 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/bt_hwcfg( 3052): Chipset BCM4335C0
D/bt_hwcfg( 3052): Target name = [BCM4335C0]
I/bt_hwcfg( 3052): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,I/art     ( 1400): Explicit concurrent mark sweep GC freed 10511(615KB) AllocSpace objects, 2(32KB) LOS objects, 39% free, 19MB/32MB, paused 801us total 23.870ms
,I/bt_hwcfg( 3052): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 3052): Settlement delay -- 100 ms
I/bt_hwcfg( 3052): Setting fw settlement delay to 100 
,I/ActivityManager(  756): Killing 1823:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,I/bt_hwcfg( 3052): bt vendor lib: set UART baud 4000000
,I/bt_hwcfg( 3052): Setting local bd addr to 34:FC:EF:11:AE:67
,I/bt_hwcfg( 3052): vendor lib fwcfg completed
,I/bt-btu  ( 3052): btu_task received preload complete event
,I/        ( 3052): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3052): BTE_InitTraceLevels -- TRC_L2CAP
,I/        ( 3052): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3052): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3052): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3052): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3052): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3052): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3052): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3052): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3052): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3052): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3052): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3052): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3052): BTE_InitTraceLevels -- TRC_BTIF
,W/libprocessgroup(  756): failed to open /acct/uid_10045/pid_1823/cgroup.procs: No such file or directory
,D/Tethering(  756): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 3083): rfkill: Cannot open RFKILL control device
,I/wpa_supplicant( 3083): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiConfigStore(  756): Loading config and enabling all networks 
,E/WifiConfigStore(  756): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  756): Setting external_sim to 1
,W/Settings( 1848): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  756): Setting OUI to DA-A1-19
I/WifiNative-HAL(  756): startHal
D/wifi    (  756): setting scan oui 0xa03fbe50
D/WifiHAL (  756): Sending mac address OUI
E/WifiHAL (  756): failed to set scanning mac OUI; result = -95
,E/native  (  756): do suspend true
,D/CommandListener(  179): Setting iface cfg
D/CommandListener(  179): Trying to bring up p2p0
,D/WifiMonitor(  756): startMonitoring(p2p0) with mConnected = true
,D/WifiNative-HAL(  756): p2pGetDeviceAddress
D/WifiNative-HAL(  756): p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,D/WifiScanningService(  756): SCAN_AVAILABLE : 3
D/RttService(  756): SCAN_AVAILABLE : 3
D/WifiScanningService(  756): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  756): startHal
,D/RttService(  756): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/wifi    (  756): getting scan capabilities on interface[1] = 0xa03fbe50
D/WifiHAL (  756): Creating message to get scan capablities; iface = 21
D/WifiHAL (  756): In GetCapabilities::handleResponse
D/WifiHAL (  756): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  756): StartedState
,I/wpa_supplicant( 3083): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,E/bt-btm  ( 3052): BTM_SecRegister:p_cb_info->p_le_callback == 0xa40a09d5 
E/bt-btm  ( 3052): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa40a09d5 
,E/bt-btif ( 3052): Calling BTA_HhEnable
E/bt-btif ( 3052): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3052): Address is:34:FC:EF:11:AE:67
,D/BluetoothManagerService(  756): Bluetooth Adapter name changed to Nexus 5
,D/BluetoothAdapterProperties( 3052): Name is: Nexus 5
D/BluetoothManagerService(  756): Stored Bluetooth name: Nexus 5
,D/BluetoothAdapterProperties( 3052): Scan Mode:20
,W/bt-smp  ( 3052): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3052): Plain text(LSB ~ MSB) = 0e 89 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3052): Encrypted text(LSB ~ MSB) = 1c 96 ca 78 5e 7c 75 16 b5 c5 48 cf f3 10 be f4 
,D/BluetoothAdapterProperties( 3052): Discoverable Timeout:120
W/bt-btm  ( 3052): Stopping oneshot timer
,D/bte_conf( 3052): Device ID record 1 : primary
,D/bte_conf( 3052):   vendorId            = 000f
,D/bte_conf( 3052):   vendorIdSource      = 0001
D/bte_conf( 3052):   product             = 1200
D/bte_conf( 3052):   version             = 1436
D/bte_conf( 3052):   clientExecutableURL = 
D/bte_conf( 3052):   serviceDescription  = 
D/bte_conf( 3052):   documentationURL    = 
D/bte_conf( 3052): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 3052): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 3052): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3052): ScanMode =  20
D/BluetoothAdapterProperties( 3052): State =  11
D/BluetoothAdapterProperties( 3052): Setting state to 12
I/BluetoothAdapterState( 3052): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService(  756): Message: 60
D/BluetoothManagerService(  756): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  756): Broadcasting onBluetoothStateChange(true) to 5 receivers.
I/BluetoothAdapterState( 3052): Entering On State
D/BluetoothAdapterProperties( 3052): Scan Mode:21
D/BluetoothAdapterProperties( 3052): Discoverable Timeout:120
D/BluetoothHeadset( 1174): onBluetoothStateChange: up=true
D/BluetoothHeadset(  756): onBluetoothStateChange: up=true
D/BluetoothA2dp(  756): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1174): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1210): onBluetoothStateChange: up=true
D/BluetoothManagerService(  756): Bluetooth State Change Intent: 11 -> 12
D/BluetoothManagerService(  756): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothMapService( 3052): onReceive
D/BluetoothMapService( 3052): STATE_ON
V/BluetoothMapService( 3052): Handler(): got msg=1
,D/BluetoothMapMasInstance( 3052): Map Service startRfcommSocketListener
D/BluetoothMapMasInstance( 3052): MAS initSocket()
D/BluetoothMapMasInstance( 3052):   masId = 00
D/BluetoothMapMasInstance( 3052):   msgTypes = 0e
D/BluetoothMapMasInstance( 3052):   masName = SMS/MMS
D/BluetoothMapMasInstance( 3052):   SDP string = 000eSMS/MMS
D/BluetoothManagerService(  756): Message: 40
D/BluetoothManagerService(  756): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
E/bt_h4   ( 3052): vendor lib postload completed
D/BluetoothManagerService(  756): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3052): getBluetoothService() called with no BluetoothManagerCallback
,V/BluetoothMapMasInstance( 3052): Succeed to create listening socket 
D/BluetoothMapMasInstance( 3052): Accepting socket connection...
,W/ContextImpl( 3090): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/Telecom ( 1174): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/HeadsetStateMachine( 3052): Disconnected process message: 9, size: 0
D/HeadsetStateMachine( 3052): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 3052): mNumber:  mType: 128
D/HeadsetStateMachine( 3052): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 3052): terminateScoUsingVirtualVoiceCall:No present call to terminate
,D/BluetoothManagerService(  756): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3052): getBluetoothService() called with no BluetoothManagerCallback
,I/art     (  756): Explicit concurrent mark sweep GC freed 23845(1198KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 755us total 80.764ms
D/BluetoothManagerService(  756): Message: 20
,D/BluetoothManagerService(  756): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2ed6501f:true
,D/LocalBluetoothProfileManager( 3090): Adding local A2DP profile
,D/BluetoothManagerService(  756): Message: 30
D/LocalBluetoothProfileManager( 3090): Adding local HEADSET profile
D/BluetoothManagerService(  756): Message: 30
,D/BluetoothManagerService(  756): Message: 30
,D/BluetoothManagerService(  756): Message: 30
,D/LocalBluetoothProfileManager( 3090): Adding local MAP profile
,D/BluetoothMap( 3090): Create BluetoothMap proxy object
,D/BluetoothManagerService(  756): Message: 30
,D/BluetoothManagerService(  756): Message: 30
,D/LocalBluetoothProfileManager( 3090): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3090): finishStartingService: stopping service
,D/BluetoothA2dp( 3090): Proxy object connected
,D/A2dpProfile( 3090): Bluetooth service connected
,D/BluetoothHeadset( 3090): Proxy object connected
,D/HeadsetProfile( 3090): Bluetooth service connected
,D/BluetoothInputDevice( 3090): Proxy object connected
,D/HidProfile( 3090): Bluetooth service connected
,D/BluetoothPan( 3090): BluetoothPAN Proxy object connected
,D/PanProfile( 3090): Bluetooth service connected
,D/BluetoothMap( 3090): Proxy object connected
,D/MapProfile( 3090): Bluetooth service connected
D/BluetoothMap( 3090): getConnectedDevices()
,V/BluetoothMapService( 3052): getConnectedDevices()
,D/AuthorizationBluetoothService( 1400): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothPbap( 3090): Proxy object connected
,D/PbapServerProfile( 3090): Bluetooth service connected
,D/BluetoothManagerService(  756): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3052): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 3052): Accept thread started.
,D/BluetoothManagerService(  756): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3002): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3002): 
I/jxcore-log( 3002): my name is : LGE-Nexus 5_PT8322
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): attempting to connect to test coordinator
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): check test folder
I/jxcore-log( 3002): 
I/jxcore-log( 3002): found test : ./testFindPeers.js
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): found test : ./testReConnect.js
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): found test : ./testSendData.js
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): Test app app.js loaded
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/chromium( 3002): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/NetworkUtils( 1355): OkHttp exception
W/EventLoggerService( 1355): Unable to send logs Error code: 262146
V/GLSActivity( 1400): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1400): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Search.LoginHelper( 1355): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,V/GLSActivity( 1400): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1400): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Search.LoginHelper( 1355): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,I/wpa_supplicant( 3083): p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  756): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiStateMachine(  756): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,E/WifiConfigStore(  756): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  756): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  756): writeKnownNetworkHistory write linked 1
,E/WifiStateMachine(  756): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=1
,E/WifiConfigStore(  756): will read network variables netId=1
,E/WifiStateMachine(  756): CMD_AUTO_CONNECT did save config ->  nid=1
,E/WifiConfigStore(  756): will read network variables netId=1
,I/wpa_supplicant( 3083): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,E/WifiConfigStore(  756): setLastSelectedConfiguration -1
,E/wpa_supplicant( 3083): PNO: In assoc process
,I/wpa_supplicant( 3083): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3083): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3083): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  756): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  756): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  756): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  756): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  756): Start Dhcp Watchdog 1
,E/native  (  756): do suspend false
,E/WifiStateMachine(  756): scanCount==0 - aborting
,I/dhcpcd  ( 3186): version 5.5.6 starting
,E/dhcpcd  ( 3186): get_duid: Read-only file system
,I/dhcpcd  ( 3186): wlan0: rebinding lease of 192.168.1.114
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/dhcpcd  ( 3186): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3186): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  756): do suspend true
,D/ConnectivityService(  756): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  756): Adding iface wlan0 to network 100
,E/WifiStateMachine(  756): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  756): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  756): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  756): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  756): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  756): Setting Dns servers for network 100 to [/192.168.1.1]
,D/Nat464Xlat(  756): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  756): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  756): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  756): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  756):    accepting network in place of null
,D/ConnectivityService(  756): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
,D/CSLegacyTypeTracker(  756): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  756): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  756): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  895): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 30 Nov 2015 10:50:15 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1448880616341], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1448880616325]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Validated
,D/ConnectivityService(  756): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  756): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  756): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  756): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler(  895): CM callback handler got msg 524290
D/TelephonyNetworkFactory( 1210): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/Nat464Xlat(  756): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  756): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  895): CM callback handler got msg 524295
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  756): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2538): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2538): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/AlarmManagerService(  756): Setting time of day to sec=1448880618
,W/AlarmManagerService(  756): Unable to set rtc to 1448880618: Invalid argument
,E/GpsLocationProvider(  756): No APN found to select.
,I/iu.SyncManager( 1614): SYNC; picasa accounts
,D/GpsLocationProvider(  756): NTP server returned: 1448880618867 (Mon Nov 30 11:50:18 GMT+01:00 2015) reference: 86368 certainty: 15 system time offset: -43
E/LocSvc_eng(  756): E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,D/NetworkLogImpl( 1614): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1614): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1614): num queued entries: 0
,I/iu.UploadsManager( 1614): num updated entries: 0
,I/iu.SyncManager( 1614): NEXT; no task
,D/ChimeraCfgMgr( 1614): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1614): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/SystemUpdateService( 1614): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1614): onCreate
,D/SystemUpdateService( 1614): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1614): active receiver: enabled
,I/SystemUpdateService( 1614): showing system update notification
,V/GLSActivity( 1400): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1400): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ValidateNoPeople(  756): skipping global notification
,V/SystemUpdateService( 1614): retry (wakeup: false) in 3599979 ms
,E/Auth.Api.Credentials( 1614): [CredentialSyncAdapter] Unknown sync event.
,I/ActivityManager(  756): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3292 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Babel   ( 1848): connection state changed from DISCONNECTED to CONNECTED
,I/art     (  194): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 180us total 10.221ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 167us total 7.557ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 168us total 7.370ms
,D/SystemUpdateService( 1614): onDestroy
,V/GLSActivity( 1400): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1400): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3002): BLE advertisement not supported: Not supported
I/jxcore-log( 3002): 
,E/ConnectivityChangeReceiver( 1614): Ignoring connectivity change
,I/GCM     ( 1400): GCM config loaded
,D/ConnectivityService(  756): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  756): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  756): apparently satisfied.  currentScore=60
,D/ConnectivityManager.CallbackHandler( 1614): CM callback handler got msg 524290
,W/AbstractGoogleClient( 2078): Application name is not set. Call Builder#setApplicationName.
,I/AnalyticsLogBase( 2078): PlayLogger.onLoggerConnected
,I/GAv4    ( 3292): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3292):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3292):   adb logcat -s GAv4
,W/GAv4    ( 3292): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/art     ( 1400): Explicit concurrent mark sweep GC freed 10922(615KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 19MB/32MB, paused 807us total 32.795ms
,W/GAv4    ( 3292): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/DriveInitializer( 1614): Awaiting to be initialized
W/ResourcesManager( 2926): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2926): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/DriveInitializer( 1614): Background init thread started
,W/GAv4    ( 3292): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/WifiService(  756): acquireWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@2493ed1c}
,W/Flag    ( 2926): Duration spec must be at least 2 characters long
,W/DriveInitializer( 1614): Background init thread ended
,I/art     (  756): Explicit concurrent mark sweep GC freed 38740(1918KB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 27MB/41MB, paused 1.612ms total 60.932ms
,I/WebViewFactory( 3292): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3292): Time to load native libraries: 1 ms (timestamps 6939-6940)
I/LibraryLoader( 3292): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3292): Binding Chromium to main looper Looper (main, tid 1) {69dc3d3}
,I/LibraryLoader( 3292): Expected native library version number "",actual native library version number ""
,I/chromium( 3292): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3292): Initializing chromium process, singleProcess=true
,W/art     ( 3292): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3292): ApplicationContext is null in ApplicationStatus
,W/chromium( 3292): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3292): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3292): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3292): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/NSApplication( 3292): Starting up...
,W/AudioManagerAndroid( 3292): Requires BLUETOOTH permission
,I/ActivityManager(  756): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3381 uid=10076 gids={50076, 9997} abi=armeabi-v7a
,D/TimeService( 3381): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1448880619636
D/        ( 3381): TimeServiceNative: User Time to be set is 1448880619636
D/QC-time-services( 3381): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3381): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3381): Lib:time_genoff_operation: pargs->ts_val = 1448880619636
D/QC-time-services(  197): Daemon: Connection accepted:time_genoff
,D/QC-time-services(  197): Daemon:Received base = 2, unit = 1, operation = 0,value = 1448880619636
D/QC-time-services(  197): Daemon:genoff_opr: Base = 2, val = 1448880619636, operation = 0
D/QC-time-services(  197): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/3/70 16:41:7
D/QC-time-services(  197): Daemon:Value read from RTC seconds = 8008867000
D/QC-time-services(  197): Daemon:new time 1448880619636 
D/QC-time-services(  197): Daemon: delta 1440871752636 genoff 1440871752636 
D/QC-time-services(  197): Daemon:genoff_persistent_update: Writing genoff = 1440871752636 to memory
D/QC-time-services(  197): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  197): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services( 3381): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  197): Updating the TOD offset
D/QC-time-services(  197): Daemon:genoff_persistent_update: Writing genoff = 1440871752636 to memory
D/QC-time-services(  197): Daemon:Opening File: /data/system/time/ats_1
D/QC-time-services(  197): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  197): Daemon:Update to modem bit set
D/QC-time-services(  197): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  197): Daemon: Base = 2, Value being sent to MODEM = 1132915819636
,E/QC-time-services( 3381): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/QC-time-services(  197): Daemon: Time-services: Waiting to acceptconnection
,D/QC-time-services(  197): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,I/CheckinService( 1614): Checkin interval check for package: unspecified last checkin: 1448876855187 min interval config: 0 actual interval: 3764475
,V/GLSActivity( 1400): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  756): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=3403 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3403): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3403):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3403):   adb logcat -s GAv4
,W/GAv4    ( 3403): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/CalendarSyncAdapter( 2078): Found no pending settings
,I/ActivityManager(  756): Killing 2516:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/GAv4    ( 3403): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/DefaultHttpIssuer( 2926): Attempt to consume entity of HttpIssuer when no request is executing.
,W/GAv4    ( 3403): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/DefaultHttpIssuer( 2926): Attempt to close HttpIssuer when no request is executing.
E/DefaultHttpIssuer( 2926): java.io.IOException
E/DefaultHttpIssuer( 2926): 	at cjw.b(PG:159)
E/DefaultHttpIssuer( 2926): 	at cju.b(PG:5072)
E/DefaultHttpIssuer( 2926): 	at dlh.b(PG:239)
E/DefaultHttpIssuer( 2926): 	at dlh.a(PG:140)
E/DefaultHttpIssuer( 2926): 	at dqo.a(PG:224)
E/DefaultHttpIssuer( 2926): 	at dlt.run(PG:9618)
E/DefaultHttpIssuer( 2926): 	at dlr.run(PG:3031)
,E/BaseSyncManager( 2926): IOException
E/BaseSyncManager( 2926): java.io.IOException: stream was reset: PROTOCOL_ERROR
E/BaseSyncManager( 2926): 	at hzd.b(PG:145)
E/BaseSyncManager( 2926): 	at hya.b(PG:104)
E/BaseSyncManager( 2926): 	at hxn.d(PG:917)
E/BaseSyncManager( 2926): 	at hxn.a(PG:95)
E/BaseSyncManager( 2926): 	at hxn$a.a(PG:902)
E/BaseSyncManager( 2926): 	at hvz.a(PG:50089)
E/BaseSyncManager( 2926): 	at hvz$a.a(PG:230)
E/BaseSyncManager( 2926): 	at hvz.a(PG:3201)
E/BaseSyncManager( 2926): 	at clz.a(PG:127)
E/BaseSyncManager( 2926): 	at cjr.a(PG:47)
E/BaseSyncManager( 2926): 	at cjq.a(PG:22)
E/BaseSyncManager( 2926): 	at cjs.a(PG:68)
E/BaseSyncManager( 2926): 	at cjw.b(PG:92)
E/BaseSyncManager( 2926): 	at cjw.a(PG:80)
E/BaseSyncManager( 2926): 	at cju.b(PG:5140)
E/BaseSyncManager( 2926): 	at cju.a(PG:1096)
E/BaseSyncManager( 2926): 	at dlh.b(PG:14062)
E/BaseSyncManager( 2926): 	at dlh.a(PG:140)
E/BaseSyncManager( 2926): 	at dqo.a(PG:224)
E/BaseSyncManager( 2926): 	at dlt.run(PG:9618)
E/BaseSyncManager( 2926): 	at dlr.run(PG:3031)
,D/WifiService(  756): releaseWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@2493ed1c}
,W/libprocessgroup(  756): failed to open /acct/uid_10003/pid_2516/cgroup.procs: No such file or directory
,I/ActivityManager(  756): Killing 2401:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  756): failed to open /acct/uid_10070/pid_2401/cgroup.procs: No such file or directory
,I/CalendarSyncAdapter( 2078): Found no pending settings
,W/art     ( 1848): Attempt to remove local handle scope entry from IRT, ignoring
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/art     ( 1848): Note: end time exceeds epoch: 
,I/Babel   ( 1848): Account registration complete:1-Redacted-21
,I/Babel   ( 1848): ProcessRegisterDeviceResponse
,I/Babel   ( 1848): Perform warm sync in case there are messages missed before the device is registered for account Redacted-21
,E/Babel   ( 1848): Invalid server experiment type 3 for BabelExperiment{id='dd8c17d9', experimentType=0, defaultBoolean=null, defaultLong=null}
E/Babel   ( 1848): Invalid server experiment type 3 for BabelExperiment{id='6412be77', experimentType=0, defaultBoolean=null, defaultLong=null}
,I/art     ( 1848): Note: end time exceeds epoch: 
,D/Finsky  ( 2460): [235] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2460): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/ActivityManager(  756): Killing 2814:com.google.android.gms:car/u0a8 (adj 15): empty #17
,W/libprocessgroup(  756): failed to open /acct/uid_10008/pid_2814/cgroup.procs: No such file or directory
,V/GLSActivity( 1400): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/VacuumService( 1400): Vacuum at: now=1448880630914 tag=VacuumService
,I/art     (  756): Explicit concurrent mark sweep GC freed 25256(1087KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/41MB, paused 944us total 48.207ms
,D/GetConfigurationSnapshotOperation( 1400): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1400): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1400): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 1400): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/UdcCache:FPQuery( 1614): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 1400): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1400): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GetCommittedConfigurationOperation( 1400): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1400): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1400): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1400): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/Uploader( 1400):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1400): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1400): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1400): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1400): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1400): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1400): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1400): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1400): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/ClearcutLoggerApiImpl( 1303): disconnect managed GoogleApiClient
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector connect called
I/jxcore-log( 3002): 
I/jxcore-log( 3002): Coordinator is now connected to the server!
I/jxcore-log( 3002): 
,I/chromium( 3002): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,V/GLSActivity( 1400): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1400): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1400): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3002): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector command called
I/jxcore-log( 3002): 
I/jxcore-log( 3002): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":50000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":21,"addressList":[{"address":"B4:CE:F6:AB:A4:6A","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"50:2E:6C:AC:21:50","tryCount":0},{"address":"7C:F9:0E:51:18:22","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"34:FC:EF:9D:93:0B","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"7C:F9:0E:34:8A
I/jxcore-log( 3002): Start now : testSendData.js
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":50000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 21
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): check server
I/jxcore-log( 3002): 
I/jxcore-log( 3002): serverPort is 51687
I/jxcore-log( 3002): 
,D/BluetoothManagerService(  756): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): initialize: 34:FC:EF:11:AE:67 LGE-Nexus 5_PT8322
,D/BluetoothManagerService(  756): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3002): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): setState: INITIALIZED
,D/BluetoothManagerService(  756): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8322","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  756): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3002): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): start: OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): setState: RUNNING
I/jxcore-log( 3002): StartBroadcasting started ok
I/jxcore-log( 3002): 
I/jxcore-log( 3002): do fake peer & start
I/jxcore-log( 3002): 
I/jxcore-log( 3002): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T10:55:57.123Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T10:55:57.124Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T10:55:57.124Z SendDataConnector.js: do connect now
I/jxcore-log( 3002): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): connect: Trying to start connecting to null in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnecting: null 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): connect: Started connecting to null in address 08:EC:A9:50:75:41
I/jxcore-log( 3002): 2015-11-30T10:55:57.128Z SendDataTCPServer.js: TCP/IP server is bound to port: 51687
I/jxcore-log( 3002): 
I/chromium( 3002): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Trying to connect...
W/BluetoothAdapter( 3002): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Waiting for incoming connections...
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 1
E/bt-btif ( 3052): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3052): Entering PendingCommandState State
,W/BluetoothEventManager( 3090): CachedBluetoothDevice for device F4:F1:E1:5C:3B:E2 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3090): Got bonding state changed for F4:F1:E1:5C:3B:E2, but we have no record of that device.
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 0
,D/BluetoothAdapterProperties( 3052): Failed to remove device: F4:F1:E1:5C:3B:E2
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 11 NewState: 10
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,W/BluetoothEventManager( 3090): CachedBluetoothDevice for device F4:F1:E1:5C:3B:E2 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3090): Got bonding state changed for F4:F1:E1:5C:3B:E2, but we have no record of that device.
,I/BluetoothBondStateMachine( 3052): StableState(): Entering Off State
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Incoming connection initialized (thread ID: 279)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Entering thread (ID: 279)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): onBytesRead: Read 81 bytes successfully (thread ID: 279)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Got valid identity from [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT6879 F4:F1:E1:5C:3B:E2]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): onBytesWritten: 77 bytes successfully written (thread ID: 279)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): removeThreadFromList: Removing thread with ID 279
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Handshake thread disposed (thread ID: 279)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onIncomingConnectionConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT6879 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Exiting thread (ID: 279)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT6879 F4:F1:E1:5C:3B:E2]
I/BtConnectorHelper( 3002): Starting the connected thread incoming : true, motorola-XT1039_PT6879
,I/BtToSocketBase( 3002): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3002): Creating BTConnectedThread
I/BtConnectorHelper( 3002): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3002): --DoOneRunRound started
,I/jxcore-log( 3002): 2015-11-30T10:56:00.516Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3002): 
,I/BtToRequestSocket( 3002): LocalHost address: localhost/127.0.0.1, port: 51687
,I/BtToRequestSocket( 3002): --DoOneRunRound ended
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3002): 2015-11-30T10:56:01.552Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:01.565Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:01.597Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:01.608Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:01.640Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:01.723Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:01.764Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:01.772Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:01.806Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:01.818Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:01.850Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:01.892Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:01.929Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:01.942Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:01.981Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:02.022Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3002): 
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4217ebc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3002): 2015-11-30T10:56:02.065Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:02.072Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:02.103Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:02.150Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3002): 
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,I/jxcore-log( 3002): 2015-11-30T10:56:02.188Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:02.220Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:02.227Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:02.261Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:02.301Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:02.308Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:02.336Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:02.344Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:02.410Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:02.482Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:02.492Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:02.502Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:02.541Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:02.550Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3002): 
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
E/bt-btif ( 3052): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3052): Entering PendingCommandState State
,W/BluetoothEventManager( 3090): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,I/jxcore-log( 3002): 2015-11-30T10:56:02.654Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3002): 
,E/BluetoothEventManager( 3090): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,I/jxcore-log( 3002): 2015-11-30T10:56:02.681Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:02.688Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:02.727Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:02.803Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:02.842Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:02.854Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:02.891Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:02.949Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3002): 
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 3052): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3052): StableState(): Entering Off State
,W/BluetoothEventManager( 3090): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,I/jxcore-log( 3002): 2015-11-30T10:56:03.003Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:03.022Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3002): 
,E/BluetoothEventManager( 3090): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,I/jxcore-log( 3002): 2015-11-30T10:56:03.034Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3002): 
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Outgoing connection initialized (thread ID: 283)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): onBytesWritten: 77 bytes successfully written (thread ID: 283)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Entering thread (ID: 283)
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4217ebc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): onBytesRead: Read 83 bytes successfully (thread ID: 283)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Handshake succeeded with [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4217 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4217 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Exiting thread (ID: 283)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4217 08:EC:A9:50:75:41]
I/BtConnectorHelper( 3002): Starting the connected thread incoming : false, samsung-SM-A300FU_PT4217
,I/BtToSocketBase( 3002): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3002): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3002): mHTTPPort  set to : 32970
I/BtConnectorHelper( 3002): Request socket is using : 32970
,I/BtToRequestSocket( 3002): Now accepting connections
,I/BtConnectorHelper( 3002): Calling ConnectionStatusUpdate with port :32970
I/jxcore-log( 3002): 2015-11-30T10:56:05.304Z SendDataConnector.js: CLIENT connected to 32970, error: null
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T10:56:05.304Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3002): 
,I/BtToRequestSocket( 3002): incoming data from: /127.0.0.1, port: 32970
I/BtToRequestSocket( 3002): Set local streams
I/BtToRequestSocket( 3002): rin ended ---------------------------;
,I/jxcore-log( 3002): 2015-11-30T10:56:05.345Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3002): 
,D/        ( 3052): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3002): 2015-11-30T10:56:06.540Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:06.618Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3002): 
,D/        ( 3052): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12826
,D/        ( 3052): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8866
,I/jxcore-log( 3002): 2015-11-30T10:56:06.655Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:06.670Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:06.706Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:06.719Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:06.771Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3002): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3002): 2015-11-30T10:56:06.823Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:06.903Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3002): 
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4217ebc rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 1
W/bt-btif ( 3052): proc dm_pm_timer expires
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [f8:95:c7:87:3c:51]: 0, 0, 0
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421824c rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4217ebc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3052): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3052): Entering PendingCommandState State
,W/BluetoothEventManager( 3090): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3090): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3052): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3052): StableState(): Entering Off State
,W/BluetoothEventManager( 3090): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3090): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421824c rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Incoming connection initialized (thread ID: 287)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Entering thread (ID: 287)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): onBytesRead: Read 77 bytes successfully (thread ID: 287)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Got valid identity from [F8:95:C7:87:3C:51 LGE-LG-H815_PT6474 F8:95:C7:87:3C:51]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): onBytesWritten: 77 bytes successfully written (thread ID: 287)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): removeThreadFromList: Removing thread with ID 287
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Handshake thread disposed (thread ID: 287)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onIncomingConnectionConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT6474 F8:95:C7:87:3C:51]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Exiting thread (ID: 287)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT6474 F8:95:C7:87:3C:51]
,I/BtConnectorHelper( 3002): Starting the connected thread incoming : true, LGE-LG-H815_PT6474
,I/BtToSocketBase( 3002): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3002): Creating BTConnectedThread
I/BtConnectorHelper( 3002): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3002): --DoOneRunRound started
,I/jxcore-log( 3002): 2015-11-30T10:56:14.952Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3002): 
,I/BtToRequestSocket( 3002): LocalHost address: localhost/127.0.0.1, port: 51687
,I/BtToRequestSocket( 3002): --DoOneRunRound ended
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4217ebc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3002): 2015-11-30T10:56:15.721Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:15.765Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:15.773Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:15.788Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:15.819Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:15.854Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:15.889Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:15.920Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:15.928Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:15.960Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:15.985Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:15.993Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:16.030Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:16.043Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:16.054Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:16.059Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:16.070Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:16.106Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:16.113Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:16.121Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:16.131Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:16.172Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:16.213Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:16.235Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:16.271Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:16.305Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:16.314Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:16.322Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:16.326Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3002): 
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
W/bt-btif ( 3052): proc dm_pm_timer expires
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3052): invalid rfc slot id: 4
,I/BtToSocketBase( 3002): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3002): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3002): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT6879
I/BtToSocketBase( 3002): Stop ReceivingThread
I/BtToSocketBase( 3002): Stop SendingThread
I/BtToSocketBase( 3002): Close local in
,I/BtToSocketBase( 3002): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3002): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3002): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT6879
I/BtToSocketBase( 3002): Close LocalOutputStream
,I/BtToSocketBase( 3002): Close localHostSocket
,I/BtToSocketBase( 3002): Close bt in
,I/BtToSocketBase( 3002): Close bt in
,I/BtToSocketBase( 3002): Close bt out
I/BtToSocketBase( 3002): Close bt socket
,I/BtToSocketBase( 3002): Close bt out
I/BtToSocketBase( 3002): Close bt socket
,I/jxcore-log( 3002): 2015-11-30T10:56:53.565Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3002): 
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4217ebc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3052): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
W/bt-rfcomm( 3052): RFCOMM_DisconnectInd LCID:0x44
,I/jxcore-log( 3002): 2015-11-30T10:56:56.904Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T10:56:56.905Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T10:56:56.908Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:56.913Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:56:56.916Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3002): 
,I/BtToSocketBase( 3002): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3002): Disconnect outgoing peer: samsung-SM-A300FU_PT4217
I/BtToSocketBase( 3002): Stop ReceivingThread
I/BtToSocketBase( 3002): Stop SendingThread
I/BtToSocketBase( 3002): Close local in
I/BtToSocketBase( 3002): Close LocalOutputStream
I/BtToSocketBase( 3002): Close localHostSocket
I/BtToSocketBase( 3002): Close bt in
,I/BtToSocketBase( 3002): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3002): Close bt out
I/BtToSocketBase( 3002): Close bt socket
I/BtToRequestSocket( 3002): Close server socket
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4217ebc rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,D/BluetoothManagerService(  756): Message: 20
D/BluetoothManagerService(  756): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@28381d93:true
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: XT1039
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4217ebc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: A3-1
,I/jxcore-log( 3002): 2015-11-30T10:57:01.917Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:57:01.918Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3002): 
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421824c rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: XT1039
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Incoming connection initialized (thread ID: 291)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Waiting for incoming connections...
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Entering thread (ID: 291)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): onBytesRead: Read 81 bytes successfully (thread ID: 291)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Got valid identity from [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT6879 F4:F1:E1:5C:3B:E2]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): onBytesWritten: 77 bytes successfully written (thread ID: 291)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): removeThreadFromList: Removing thread with ID 291
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Handshake thread disposed (thread ID: 291)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onIncomingConnectionConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT6879 F4:F1:E1:5C:3B:E2]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT6879 F4:F1:E1:5C:3B:E2]
I/BtConnectorHelper( 3002): Starting the connected thread incoming : true, motorola-XT1039_PT6879
I/BtToSocketBase( 3002): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3002): Creating BTConnectedThread
I/BtConnectorHelper( 3002): Server socket is using : 0, and is now connected.
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Exiting thread (ID: 291)
,I/BtToRequestSocket( 3002): --DoOneRunRound started
,I/BtToRequestSocket( 3002): LocalHost address: localhost/127.0.0.1, port: 51687
,I/jxcore-log( 3002): 2015-11-30T10:57:04.848Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3002): 
,I/BtToRequestSocket( 3002): --DoOneRunRound ended
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421824c rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3002): 2015-11-30T10:57:05.282Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:57:05.294Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:57:05.305Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:57:05.311Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3002): 
,W/bt-btif ( 3052): invalid rfc slot id: 6
,I/BtToSocketBase( 3002): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3002): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3002): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT6474
I/BtToSocketBase( 3002): Stop ReceivingThread
,I/BtToSocketBase( 3002): Stop SendingThread
I/BtToSocketBase( 3002): Close local in
I/BtToSocketBase( 3002): Close LocalOutputStream
I/BtToSocketBase( 3002): Close localHostSocket
I/BtToSocketBase( 3002): Close bt in
,I/BtToSocketBase( 3002): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3002): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3002): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT6474
I/BtToSocketBase( 3002): Close bt in
I/BtToSocketBase( 3002): Close bt out
I/BtToSocketBase( 3002): Close bt socket
,W/bt-rfcomm( 3052): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
W/bt-rfcomm( 3052): RFCOMM_DisconnectInd LCID:0x48
,I/BtToSocketBase( 3002): Close bt out
I/BtToSocketBase( 3002): Close bt socket
,I/jxcore-log( 3002): 2015-11-30T10:57:06.327Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:57:06.929Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T10:57:06.930Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T10:57:06.930Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T10:57:06.931Z SendDataConnector.js: do connect now
I/jxcore-log( 3002): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): connect: Trying to start connecting to A3-1 in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnecting: A3-1 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): connect: Started connecting to A3-1 in address 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Trying to connect...
W/BluetoothAdapter( 3002): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: G4-1
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: A3-1
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4217ebc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Outgoing connection initialized (thread ID: 296)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): onBytesWritten: 77 bytes successfully written (thread ID: 296)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Entering thread (ID: 296)
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4217ebc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): onBytesRead: Read 83 bytes successfully (thread ID: 296)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Handshake succeeded with [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4217 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4217 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Exiting thread (ID: 296)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4217 08:EC:A9:50:75:41]
I/BtConnectorHelper( 3002): Starting the connected thread incoming : false, samsung-SM-A300FU_PT4217
I/BtToSocketBase( 3002): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3002): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3002): mHTTPPort  set to : 36819
,I/BtConnectorHelper( 3002): Request socket is using : 36819
I/BtToRequestSocket( 3002): Now accepting connections
,I/BtConnectorHelper( 3002): Calling ConnectionStatusUpdate with port :36819
I/jxcore-log( 3002): 2015-11-30T10:57:13.586Z SendDataConnector.js: CLIENT connected to 36819, error: null
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T10:57:13.586Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3002): 
,I/BtToRequestSocket( 3002): incoming data from: /127.0.0.1, port: 36819
I/BtToRequestSocket( 3002): Set local streams
I/BtToRequestSocket( 3002): rin ended ---------------------------;
,I/jxcore-log( 3002): 2015-11-30T10:57:13.613Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3002): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
W/bt-btif ( 3052): proc dm_pm_timer expires
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: G4-1
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421824c rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3052): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3052): Entering PendingCommandState State
,W/BluetoothEventManager( 3090): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3090): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3052): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3052): StableState(): Entering Off State
,W/BluetoothEventManager( 3090): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3090): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Incoming connection initialized (thread ID: 300)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Entering thread (ID: 300)
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421824c rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): onBytesRead: Read 77 bytes successfully (thread ID: 300)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Got valid identity from [F8:95:C7:87:3C:51 LGE-LG-H815_PT6474 F8:95:C7:87:3C:51]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): onBytesWritten: 77 bytes successfully written (thread ID: 300)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): removeThreadFromList: Removing thread with ID 300
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Handshake thread disposed (thread ID: 300)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onIncomingConnectionConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT6474 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Exiting thread (ID: 300)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT6474 F8:95:C7:87:3C:51]
,I/BtConnectorHelper( 3002): Starting the connected thread incoming : true, LGE-LG-H815_PT6474
,I/BtToSocketBase( 3002): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3002): Creating BTConnectedThread
,I/BtConnectorHelper( 3002): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3002): --DoOneRunRound started
,I/BtToRequestSocket( 3002): LocalHost address: localhost/127.0.0.1, port: 51687
,I/jxcore-log( 3002): 2015-11-30T10:57:19.664Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3002): 
,I/BtToRequestSocket( 3002): --DoOneRunRound ended
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4217ebc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3002): 2015-11-30T10:57:20.067Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:57:20.076Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:57:20.085Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3002): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 1
W/bt-btif ( 3052): proc dm_pm_timer expires
,W/bt-btif ( 3052): invalid rfc slot id: 7
,I/BtToSocketBase( 3002): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3002): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3002): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT6879
I/BtToSocketBase( 3002): Stop ReceivingThread
I/BtToSocketBase( 3002): Stop SendingThread
I/BtToSocketBase( 3002): Close local in
I/BtToSocketBase( 3002): Close LocalOutputStream
I/BtToSocketBase( 3002): Close localHostSocket
I/BtToSocketBase( 3002): Close bt in
I/BtToSocketBase( 3002): Close bt out
I/BtToSocketBase( 3002): Close bt socket
,I/BtToSocketBase( 3002): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3002): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3002): 2015-11-30T10:57:55.546Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3002): 
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4217ebc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3052): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
W/bt-rfcomm( 3052): RFCOMM_DisconnectInd LCID:0x4a
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
W/bt-btif ( 3052): proc dm_pm_timer expires
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: XT1039
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4217ebc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3002): 2015-11-30T10:58:03.687Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T10:58:03.688Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:58:03.694Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T10:58:03.695Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T10:58:03.696Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3002): 
,I/BtToSocketBase( 3002): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3002): Disconnect outgoing peer: samsung-SM-A300FU_PT4217
I/BtToSocketBase( 3002): Stop ReceivingThread
,I/BtToSocketBase( 3002): Stop SendingThread
I/BtToSocketBase( 3002): Close local in
I/BtToSocketBase( 3002): Close LocalOutputStream
I/BtToSocketBase( 3002): Close localHostSocket
I/BtToSocketBase( 3002): Close bt in
,I/BtToSocketBase( 3002): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3002): Close bt out
I/BtToSocketBase( 3002): Close bt socket
I/BtToRequestSocket( 3002): Close server socket
,W/bt-btif ( 3052): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421824c rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: XT1039
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421824c rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Incoming connection initialized (thread ID: 304)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Entering thread (ID: 304)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): onBytesRead: Read 81 bytes successfully (thread ID: 304)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Got valid identity from [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT6879 F4:F1:E1:5C:3B:E2]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): onBytesWritten: 77 bytes successfully written (thread ID: 304)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): removeThreadFromList: Removing thread with ID 304
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Handshake thread disposed (thread ID: 304)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onIncomingConnectionConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT6879 F4:F1:E1:5C:3B:E2]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT6879 F4:F1:E1:5C:3B:E2]
I/BtConnectorHelper( 3002): Starting the connected thread incoming : true, motorola-XT1039_PT6879
I/BtToSocketBase( 3002): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3002): Creating BTConnectedThread
I/BtConnectorHelper( 3002): Server socket is using : 0, and is now connected.
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Exiting thread (ID: 304)
,I/BtToRequestSocket( 3002): --DoOneRunRound started
,I/jxcore-log( 3002): 2015-11-30T10:58:07.036Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3002): 
,I/BtToRequestSocket( 3002): LocalHost address: localhost/127.0.0.1, port: 51687
I/BtToRequestSocket( 3002): --DoOneRunRound ended
,I/jxcore-log( 3002): 2015-11-30T10:58:07.495Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:58:07.503Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:58:07.509Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3002): 
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,I/jxcore-log( 3002): 2015-11-30T10:58:08.696Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T10:58:08.697Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3002): 
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: A3-1
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3052): invalid rfc slot id: 8
,I/BtToSocketBase( 3002): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3002): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3002): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT6474
I/BtToSocketBase( 3002): Stop ReceivingThread
I/BtToSocketBase( 3002): Stop SendingThread
I/BtToSocketBase( 3002): Close local in
I/BtToSocketBase( 3002): Close LocalOutputStream
I/BtToSocketBase( 3002): Close localHostSocket
I/BtToSocketBase( 3002): Close bt in
I/BtToSocketBase( 3002): Close bt out
I/BtToSocketBase( 3002): Close bt socket
,I/BtToSocketBase( 3002): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3002): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3002): 2015-11-30T10:58:10.333Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3002): 
,W/bt-rfcomm( 3052): rfc_find_lcid_mcb LCID reused LCID:0x4e current:0x0
W/bt-rfcomm( 3052): RFCOMM_DisconnectInd LCID:0x4e
,I/jxcore-log( 3002): 2015-11-30T10:58:13.701Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T10:58:13.702Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T10:58:13.703Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T10:58:13.703Z SendDataConnector.js: do connect now
I/jxcore-log( 3002): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): connect: Trying to start connecting to A3-1 in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnecting: A3-1 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): connect: Started connecting to A3-1 in address 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Trying to connect...
W/BluetoothAdapter( 3002): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421824c rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: G4-1
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4217ebc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,I/BluetoothClassifier( 1355): Bluetooth Device Name: A3-1
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Outgoing connection initialized (thread ID: 309)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): onBytesWritten: 77 bytes successfully written (thread ID: 309)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Entering thread (ID: 309)
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4217ebc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): onBytesRead: Read 83 bytes successfully (thread ID: 309)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Handshake succeeded with [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4217 08:EC:A9:50:75:41]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4217 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Exiting thread (ID: 309)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4217 08:EC:A9:50:75:41]
,I/BtConnectorHelper( 3002): Starting the connected thread incoming : false, samsung-SM-A300FU_PT4217
,I/BtToSocketBase( 3002): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3002): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3002): mHTTPPort  set to : 33711
I/BtConnectorHelper( 3002): Request socket is using : 33711
I/BtToRequestSocket( 3002): Now accepting connections
,I/BtConnectorHelper( 3002): Calling ConnectionStatusUpdate with port :33711
I/jxcore-log( 3002): 2015-11-30T10:58:17.016Z SendDataConnector.js: CLIENT connected to 33711, error: null
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T10:58:17.017Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3002): 
,I/BtToRequestSocket( 3002): incoming data from: /127.0.0.1, port: 33711
I/BtToRequestSocket( 3002): Set local streams
I/BtToRequestSocket( 3002): rin ended ---------------------------;
,I/jxcore-log( 3002): 2015-11-30T10:58:17.045Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3002): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: G4-1
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421824c rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4217ebc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
W/bt-btif ( 3052): proc dm_pm_timer expires
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3052): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3052): Entering PendingCommandState State
,W/BluetoothEventManager( 3090): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3090): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3052): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3052): StableState(): Entering Off State
,W/BluetoothEventManager( 3090): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3090): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Incoming connection initialized (thread ID: 313)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Entering thread (ID: 313)
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421824c rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): onBytesRead: Read 77 bytes successfully (thread ID: 313)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Got valid identity from [F8:95:C7:87:3C:51 LGE-LG-H815_PT6474 F8:95:C7:87:3C:51]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): onBytesWritten: 77 bytes successfully written (thread ID: 313)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): removeThreadFromList: Removing thread with ID 313
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Handshake thread disposed (thread ID: 313)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onIncomingConnectionConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT6474 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Exiting thread (ID: 313)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT6474 F8:95:C7:87:3C:51]
I/BtConnectorHelper( 3002): Starting the connected thread incoming : true, LGE-LG-H815_PT6474
,I/BtToSocketBase( 3002): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3002): Creating BTConnectedThread
I/BtConnectorHelper( 3002): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3002): --DoOneRunRound started
,I/jxcore-log( 3002): 2015-11-30T10:58:22.678Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3002): 
,I/BtToRequestSocket( 3002): LocalHost address: localhost/127.0.0.1, port: 51687
,I/BtToRequestSocket( 3002): --DoOneRunRound ended
,I/jxcore-log( 3002): 2015-11-30T10:58:23.075Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:58:23.083Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:58:23.111Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:58:23.120Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3002): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4217ebc rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
W/bt-btif ( 3052): proc dm_pm_timer expires
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421824c rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): invalid rfc slot id: 10
,I/BtToSocketBase( 3002): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3002): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3002): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT6879
I/BtToSocketBase( 3002): Stop ReceivingThread
I/BtToSocketBase( 3002): Stop SendingThread
I/BtToSocketBase( 3002): Close local in
,I/BtToSocketBase( 3002): Close LocalOutputStream
I/BtToSocketBase( 3002): Close localHostSocket
I/BtToSocketBase( 3002): Close bt in
I/BtToSocketBase( 3002): Close bt out
I/BtToSocketBase( 3002): Close bt socket
,I/BtToSocketBase( 3002): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3002): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3002): 2015-11-30T10:58:57.539Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3002): 
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4217ebc rs_disc_pending=1
,W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3052): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0
W/bt-rfcomm( 3052): RFCOMM_DisconnectInd LCID:0x41
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 1
W/bt-btif ( 3052): proc dm_pm_timer expires
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: XT1039
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421824c rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421824c rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3002): 2015-11-30T10:59:07.114Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T10:59:07.115Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T10:59:07.117Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:59:07.125Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T10:59:07.126Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3002): 
,I/BtToSocketBase( 3002): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3002): Disconnect outgoing peer: samsung-SM-A300FU_PT4217
,I/BtToSocketBase( 3002): Stop ReceivingThread
I/BtToSocketBase( 3002): Stop SendingThread
I/BtToSocketBase( 3002): Close local in
I/BtToSocketBase( 3002): Close LocalOutputStream
,I/BtToSocketBase( 3002): Close localHostSocket
I/BtToSocketBase( 3002): Close bt in
,I/BtToSocketBase( 3002): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3002): Close bt out
I/BtToSocketBase( 3002): Close bt socket
I/BtToRequestSocket( 3002): Close server socket
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421824c rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,D/Finsky  ( 2460): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1400): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1400): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1400): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/bt-btif ( 3052): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,W/ProcessCpuTracker(  756): Skipping unknown process pid 3600
,W/ProcessCpuTracker(  756): Skipping unknown process pid 3603
,V/GLSActivity( 1400): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2460): Failed write_ctrl(u 39) res=-1 errno=22
I/qtaguid ( 2460): Untagging socket 39 failed errno=-22
W/NetworkManagementSocketTagger( 2460): untagSocket(39) failed with errno -22
,D/Finsky  ( 2460): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430000] >= Server Version [-1]
,V/GLSActivity( 1400): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2460): Failed write_ctrl(u 39) res=-1 errno=22
I/qtaguid ( 2460): Untagging socket 39 failed errno=-22
W/NetworkManagementSocketTagger( 2460): untagSocket(39) failed with errno -22
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4217ebc rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
I/BluetoothClassifier( 1355): Bluetooth Device Name: XT1039
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Incoming connection initialized (thread ID: 317)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Waiting for incoming connections...
,V/GLSActivity( 1400): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Entering thread (ID: 317)
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4217ebc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): onBytesRead: Read 81 bytes successfully (thread ID: 317)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Got valid identity from [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT6879 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): onBytesWritten: 77 bytes successfully written (thread ID: 317)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): removeThreadFromList: Removing thread with ID 317
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Handshake thread disposed (thread ID: 317)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onIncomingConnectionConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT6879 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Exiting thread (ID: 317)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT6879 F4:F1:E1:5C:3B:E2]
I/BtConnectorHelper( 3002): Starting the connected thread incoming : true, motorola-XT1039_PT6879
I/BtToSocketBase( 3002): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3002): Creating BTConnectedThread
I/BtConnectorHelper( 3002): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3002): --DoOneRunRound started
,I/BtToRequestSocket( 3002): LocalHost address: localhost/127.0.0.1, port: 51687
I/BtToRequestSocket( 3002): --DoOneRunRound ended
,I/jxcore-log( 3002): 2015-11-30T10:59:09.605Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3002): 
,I/qtaguid ( 2460): Failed write_ctrl(u 39) res=-1 errno=22
I/qtaguid ( 2460): Untagging socket 39 failed errno=-22
W/NetworkManagementSocketTagger( 2460): untagSocket(39) failed with errno -22
,W/ResourcesManager( 2460): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 2460): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 2460): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 2460): [1] WearSupportService.startHygiene: disabled
,D/Finsky  ( 2460): [1] DailyHygiene.access$600: Logging device features
,D/DeviceConnectionService( 1303): client connected with version: 8296000
,D/Finsky  ( 2460): [250] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1400): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3002): 2015-11-30T10:59:10.025Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:59:10.029Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:59:10.033Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:59:10.041Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:59:10.042Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:59:10.049Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:59:12.126Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T10:59:12.126Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3002): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421824c rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): invalid rfc slot id: 11
,I/BtToSocketBase( 3002): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3002): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3002): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT6474
I/BtToSocketBase( 3002): Stop ReceivingThread
I/BtToSocketBase( 3002): Stop SendingThread
I/BtToSocketBase( 3002): Close local in
I/BtToSocketBase( 3002): Close LocalOutputStream
I/BtToSocketBase( 3002): Close localHostSocket
I/BtToSocketBase( 3002): Close bt in
I/BtToSocketBase( 3002): Close bt out
I/BtToSocketBase( 3002): Close bt socket
,I/BtToSocketBase( 3002): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3002): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3002): 2015-11-30T10:59:13.137Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3002): 
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421824c rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3052): rfc_find_lcid_mcb LCID reused LCID:0x40 current:0x0
W/bt-rfcomm( 3052): RFCOMM_DisconnectInd LCID:0x40
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: A3-1
,I/jxcore-log( 3002): 2015-11-30T10:59:17.132Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T10:59:17.132Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T10:59:17.133Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T10:59:17.134Z SendDataConnector.js: do connect now
I/jxcore-log( 3002): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): connect: Trying to start connecting to A3-1 in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnecting: A3-1 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): connect: Started connecting to A3-1 in address 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Trying to connect...
W/BluetoothAdapter( 3002): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: G4-1
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: A3-1
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4217ebc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Outgoing connection initialized (thread ID: 322)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): onBytesWritten: 77 bytes successfully written (thread ID: 322)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Entering thread (ID: 322)
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4217ebc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): onBytesRead: Read 83 bytes successfully (thread ID: 322)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Handshake succeeded with [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4217 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4217 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Exiting thread (ID: 322)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4217 08:EC:A9:50:75:41]
I/BtConnectorHelper( 3002): Starting the connected thread incoming : false, samsung-SM-A300FU_PT4217
I/BtToSocketBase( 3002): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3002): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3002): mHTTPPort  set to : 53235
I/BtConnectorHelper( 3002): Request socket is using : 53235
I/BtToRequestSocket( 3002): Now accepting connections
,I/BtConnectorHelper( 3002): Calling ConnectionStatusUpdate with port :53235
I/jxcore-log( 3002): 2015-11-30T10:59:20.431Z SendDataConnector.js: CLIENT connected to 53235, error: null
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T10:59:20.431Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3002): 
,I/BtToRequestSocket( 3002): incoming data from: /127.0.0.1, port: 53235
I/BtToRequestSocket( 3002): Set local streams
I/BtToRequestSocket( 3002): rin ended ---------------------------;
,I/jxcore-log( 3002): 2015-11-30T10:59:20.455Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3002): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: G4-1
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421824c rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3052): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3052): Entering PendingCommandState State
,W/BluetoothEventManager( 3090): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3090): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,D/Finsky  ( 2460): [235] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2460): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3052): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3052): StableState(): Entering Off State
,W/BluetoothEventManager( 3090): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3090): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Incoming connection initialized (thread ID: 326)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Entering thread (ID: 326)
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421824c rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): onBytesRead: Read 77 bytes successfully (thread ID: 326)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Got valid identity from [F8:95:C7:87:3C:51 LGE-LG-H815_PT6474 F8:95:C7:87:3C:51]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): onBytesWritten: 77 bytes successfully written (thread ID: 326)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): removeThreadFromList: Removing thread with ID 326
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Handshake thread disposed (thread ID: 326)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onIncomingConnectionConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT6474 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Exiting thread (ID: 326)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT6474 F8:95:C7:87:3C:51]
I/BtConnectorHelper( 3002): Starting the connected thread incoming : true, LGE-LG-H815_PT6474
I/BtToSocketBase( 3002): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3002): Creating BTConnectedThread
I/BtConnectorHelper( 3002): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3002): --DoOneRunRound started
,I/jxcore-log( 3002): 2015-11-30T10:59:25.125Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3002): 
,I/BtToRequestSocket( 3002): LocalHost address: localhost/127.0.0.1, port: 51687
,I/BtToRequestSocket( 3002): --DoOneRunRound ended
,I/jxcore-log( 3002): 2015-11-30T10:59:25.493Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:59:25.501Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3002): 
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
,W/bt-btif ( 3052): proc dm_pm_timer expires
,I/jxcore-log( 3002): 2015-11-30T10:59:25.614Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T10:59:25.644Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3002): 
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4217ebc rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/ActivityManager(  756): Killing 1331:android.process.acore/u0a4 (adj 15): empty #17
,W/libprocessgroup(  756): failed to open /acct/uid_10004/pid_1331/cgroup.procs: No such file or directory
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 1
,W/bt-btif ( 3052): proc dm_pm_timer expires
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4218084 rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421824c rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): invalid rfc slot id: 13
,I/BtToSocketBase( 3002): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3002): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3002): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT6879
I/BtToSocketBase( 3002): Stop ReceivingThread
I/BtToSocketBase( 3002): Stop SendingThread
I/BtToSocketBase( 3002): Close local in
I/BtToSocketBase( 3002): Close LocalOutputStream
I/BtToSocketBase( 3002): Close localHostSocket
I/BtToSocketBase( 3002): Close bt in
I/BtToSocketBase( 3002): Close bt out
I/BtToSocketBase( 3002): Close bt socket
,I/BtToSocketBase( 3002): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3002): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3002): 2015-11-30T11:00:00.211Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3002): 
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4218084 rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3052): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
W/bt-rfcomm( 3052): RFCOMM_DisconnectInd LCID:0x44
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: XT1039
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4217ebc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
W/bt-btif ( 3052): proc dm_pm_timer expires
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421824c rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3002): 2015-11-30T11:00:10.533Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:00:10.534Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:00:10.534Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:00:10.535Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:00:10.535Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3002): 
,I/BtToSocketBase( 3002): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3002): Disconnect outgoing peer: samsung-SM-A300FU_PT4217
I/BtToSocketBase( 3002): Stop ReceivingThread
I/BtToSocketBase( 3002): Stop SendingThread
I/BtToSocketBase( 3002): Close local in
I/BtToSocketBase( 3002): Close LocalOutputStream
I/BtToSocketBase( 3002): Close localHostSocket
I/BtToSocketBase( 3002): Close bt in
,I/BtToSocketBase( 3002): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3002): Close bt out
I/BtToSocketBase( 3002): Close bt socket
I/BtToRequestSocket( 3002): Close server socket
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: XT1039
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Incoming connection initialized (thread ID: 330)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Entering thread (ID: 330)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): onBytesRead: Read 81 bytes successfully (thread ID: 330)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Got valid identity from [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT6879 F4:F1:E1:5C:3B:E2]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): onBytesWritten: 77 bytes successfully written (thread ID: 330)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): removeThreadFromList: Removing thread with ID 330
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Handshake thread disposed (thread ID: 330)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onIncomingConnectionConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT6879 F4:F1:E1:5C:3B:E2]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT6879 F4:F1:E1:5C:3B:E2]
I/BtConnectorHelper( 3002): Starting the connected thread incoming : true, motorola-XT1039_PT6879
I/BtToSocketBase( 3002): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3002): Creating BTConnectedThread
I/BtConnectorHelper( 3002): Server socket is using : 0, and is now connected.
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Exiting thread (ID: 330)
,I/BtToRequestSocket( 3002): --DoOneRunRound started
,I/BtToRequestSocket( 3002): LocalHost address: localhost/127.0.0.1, port: 51687
,I/jxcore-log( 3002): 2015-11-30T11:00:11.341Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3002): 
,I/BtToRequestSocket( 3002): --DoOneRunRound ended
,I/jxcore-log( 3002): 2015-11-30T11:00:11.738Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:00:11.748Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data,
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:00:11.757Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:00:11.761Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:00:11.768Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3002): 
,W/bt-btif ( 3052): bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4217ebc rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3002): 2015-11-30T11:00:15.536Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:00:15.536Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3002): 
,W/bt-btif ( 3052): invalid rfc slot id: 14
,I/BtToSocketBase( 3002): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3002): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3002): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT6474
I/BtToSocketBase( 3002): Stop ReceivingThread
I/BtToSocketBase( 3002): Stop SendingThread
I/BtToSocketBase( 3002): Close local in
I/BtToSocketBase( 3002): Close LocalOutputStream
I/BtToSocketBase( 3002): Close localHostSocket
I/BtToSocketBase( 3002): Close bt in
I/BtToSocketBase( 3002): Close bt out
I/BtToSocketBase( 3002): Close bt socket
,I/BtToSocketBase( 3002): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3002): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3002): 2015-11-30T11:00:15.582Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3002): 
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4217ebc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3052): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
W/bt-rfcomm( 3052): RFCOMM_DisconnectInd LCID:0x4b
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: A3-1
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: G4-1
,I/jxcore-log( 3002): 2015-11-30T11:00:20.542Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:00:20.542Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:00:20.543Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:00:20.544Z SendDataConnector.js: do connect now
I/jxcore-log( 3002): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): connect: Trying to start connecting to A3-1 in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnecting: A3-1 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): connect: Started connecting to A3-1 in address 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Trying to connect...
W/BluetoothAdapter( 3002): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: A3-1
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4217ebc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4217ebc rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Outgoing connection initialized (thread ID: 335)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): onBytesWritten: 77 bytes successfully written (thread ID: 335)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Entering thread (ID: 335)
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4217ebc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): onBytesRead: Read 83 bytes successfully (thread ID: 335)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Handshake succeeded with [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4217 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4217 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Exiting thread (ID: 335)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4217 08:EC:A9:50:75:41]
I/BtConnectorHelper( 3002): Starting the connected thread incoming : false, samsung-SM-A300FU_PT4217
,I/BtToSocketBase( 3002): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3002): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3002): mHTTPPort  set to : 44424
I/BtConnectorHelper( 3002): Request socket is using : 44424
I/BtToRequestSocket( 3002): Now accepting connections
,I/BtConnectorHelper( 3002): Calling ConnectionStatusUpdate with port :44424
I/jxcore-log( 3002): 2015-11-30T11:00:24.364Z SendDataConnector.js: CLIENT connected to 44424, error: null
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:00:24.365Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3002): 
,I/BtToRequestSocket( 3002): incoming data from: /127.0.0.1, port: 44424
I/BtToRequestSocket( 3002): Set local streams
I/BtToRequestSocket( 3002): rin ended ---------------------------;
,I/jxcore-log( 3002): 2015-11-30T11:00:24.385Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3002): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
,W/bt-btif ( 3052): proc dm_pm_timer expires
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4217ebc rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): dm_pm_timer expires
,W/bt-btif ( 3052): dm_pm_timer expires 0
W/bt-btif ( 3052): proc dm_pm_timer expires
,W/bt-btif ( 3052): invalid rfc slot id: 16
,I/BtToSocketBase( 3002): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3002): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3002): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT6879
I/BtToSocketBase( 3002): Stop ReceivingThread
I/BtToSocketBase( 3002): Stop SendingThread
I/BtToSocketBase( 3002): Close local in
I/BtToSocketBase( 3002): Close LocalOutputStream
I/BtToSocketBase( 3002): Close localHostSocket
I/BtToSocketBase( 3002): Close bt in
I/BtToSocketBase( 3002): Close bt out
I/BtToSocketBase( 3002): Close bt socket
,I/BtToSocketBase( 3002): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3002): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3002): 2015-11-30T11:01:02.040Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3002): 
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4217ebc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3052): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
W/bt-rfcomm( 3052): RFCOMM_DisconnectInd LCID:0x4a
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
,W/bt-btif ( 3052): proc dm_pm_timer expires
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: XT1039
,I/jxcore-log( 3002): 2015-11-30T11:01:14.473Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:01:14.474Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:01:14.475Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:01:14.495Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:01:14.496Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:01:14.497Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3002): 
,I/BtConnectorHelper( 3002): Disconnect outgoing peer: 08:EC:A9:50:75:41
I/BtToSocketBase( 3002): Stop ReceivingThread
I/BtToSocketBase( 3002): Stop SendingThread
I/BtToSocketBase( 3002): Close local in
,I/BtToSocketBase( 3002): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3002): Close LocalOutputStream
I/BtToSocketBase( 3002): Close localHostSocket
,I/BtToSocketBase( 3002): Close bt in
,I/BtToSocketBase( 3002): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3002): Close bt out
I/BtToSocketBase( 3002): Close bt socket
I/BtToRequestSocket( 3002): Close server socket
I/jxcore-log( 3002): 2015-11-30T11:01:14.534Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3002): 
I/jxcore-log( 3002): ---- round done--------
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): ---- gotta redo : 08:EC:A9:50:75:41, try count now: 1
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): do fake peer & start
I/jxcore-log( 3002): 
I/jxcore-log( 3002): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:01:14.547Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:01:14.548Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:01:14.548Z SendDataConnector.js: do connect now
I/jxcore-log( 3002): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): connect: Trying to start connecting to null in address 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnecting: null 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): connect: Started connecting to null in address 44:80:EB:7B:5A:05
,I/jxcore-log( 3002): 2015-11-30T11:01:14.559Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3002): 
,I/chromium( 3002): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 08:EC:A9:50:75:41 done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Trying to connect...
W/BluetoothAdapter( 3002): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3052): bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4217ebc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: A3-1
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
E/bt-btif ( 3052): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3052): Entering PendingCommandState State
,W/BluetoothEventManager( 3090): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3090): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 3052): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3052): StableState(): Entering Off State
,W/BluetoothEventManager( 3090): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3090): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Outgoing connection initialized (thread ID: 340)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): onBytesWritten: 77 bytes successfully written (thread ID: 340)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Entering thread (ID: 340)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): onBytesRead: Read 81 bytes successfully (thread ID: 340)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Handshake succeeded with [44:80:EB:7B:5A:05 motorola-XT1072_PT6826 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT6826 44:80:EB:7B:5A:05]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT6826 44:80:EB:7B:5A:05]
,I/BtConnectorHelper( 3002): Starting the connected thread incoming : false, motorola-XT1072_PT6826
I/BtToSocketBase( 3002): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3002): Creating BtConnectedRequestSocket
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Exiting thread (ID: 340)
,I/BtToRequestSocket( 3002): mHTTPPort  set to : 51834
I/BtConnectorHelper( 3002): Request socket is using : 51834
I/BtToRequestSocket( 3002): Now accepting connections
,I/BtConnectorHelper( 3002): Calling ConnectionStatusUpdate with port :51834
I/jxcore-log( 3002): 2015-11-30T11:01:20.316Z SendDataConnector.js: CLIENT connected to 51834, error: null
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:01:20.316Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3002): 
,I/BtToRequestSocket( 3002): incoming data from: /127.0.0.1, port: 51834
I/BtToRequestSocket( 3002): Set local streams
I/BtToRequestSocket( 3002): rin ended ---------------------------;
,I/jxcore-log( 3002): 2015-11-30T11:01:20.337Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3002): 
,D/        ( 3052): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24978
,I/jxcore-log( 3002): 2015-11-30T11:01:20.915Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3002): 
,D/        ( 3052): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18048
,I/jxcore-log( 3002): 2015-11-30T11:01:20.960Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3002): 
,D/        ( 3052): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12108
,I/jxcore-log( 3002): 2015-11-30T11:01:21.013Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3002): 
,D/        ( 3052): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:5178
,I/jxcore-log( 3002): 2015-11-30T11:01:21.063Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:01:21.064Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:01:21.107Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:01:21.174Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:01:21.213Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:01:21.220Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3002): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
W/bt-btif ( 3052): proc dm_pm_timer expires
,I/jxcore-log( 3002): 2015-11-30T11:02:11.220Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:02:11.221Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:02:11.222Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:02:11.223Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:02:11.224Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3002): 
,I/BtToSocketBase( 3002): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3002): Disconnect outgoing peer: motorola-XT1072_PT6826
I/BtToSocketBase( 3002): Stop ReceivingThread
I/BtToSocketBase( 3002): Stop SendingThread
I/BtToSocketBase( 3002): Close local in
I/BtToSocketBase( 3002): Close LocalOutputStream
I/BtToSocketBase( 3002): Close localHostSocket
I/BtToSocketBase( 3002): Close bt in
,I/BtToSocketBase( 3002): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3002): Close bt out
I/BtToSocketBase( 3002): Close bt socket
I/BtToRequestSocket( 3002): Close server socket
,W/bt-btif ( 3052): bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND
,I/jxcore-log( 3002): 2015-11-30T11:02:16.223Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:02:16.224Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3002): 
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: XT1072
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 1
E/bt-btif ( 3052): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3052): Entering PendingCommandState State
,W/BluetoothEventManager( 3090): CachedBluetoothDevice for device 58:2A:F7:ED:96:BE not found, calling readPairedDevices().
,E/BluetoothEventManager( 3090): Got bonding state changed for 58:2A:F7:ED:96:BE, but we have no record of that device.
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 0
,D/BluetoothAdapterProperties( 3052): Failed to remove device: 58:2A:F7:ED:96:BE
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3052): StableState(): Entering Off State
,W/BluetoothEventManager( 3090): CachedBluetoothDevice for device 58:2A:F7:ED:96:BE not found, calling readPairedDevices().
,E/BluetoothEventManager( 3090): Got bonding state changed for 58:2A:F7:ED:96:BE, but we have no record of that device.
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Incoming connection initialized (thread ID: 344)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Entering thread (ID: 344)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): onBytesRead: Read 80 bytes successfully (thread ID: 344)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Got valid identity from [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT7478 58:2A:F7:ED:96:BE]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): onBytesWritten: 77 bytes successfully written (thread ID: 344)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): removeThreadFromList: Removing thread with ID 344
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Handshake thread disposed (thread ID: 344)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onIncomingConnectionConnected: [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT7478 58:2A:F7:ED:96:BE]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Exiting thread (ID: 344)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnected: [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT7478 58:2A:F7:ED:96:BE]
,I/BtConnectorHelper( 3002): Starting the connected thread incoming : true, HUAWEI-ALE-L21_PT7478
,I/BtToSocketBase( 3002): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3002): Creating BTConnectedThread
,I/BtConnectorHelper( 3002): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3002): --DoOneRunRound started
,I/jxcore-log( 3002): 2015-11-30T11:02:18.444Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3002): 
,I/BtToRequestSocket( 3002): LocalHost address: localhost/127.0.0.1, port: 51687
I/BtToRequestSocket( 3002): --DoOneRunRound ended
,I/jxcore-log( 3002): 2015-11-30T11:02:19.129Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:19.138Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:19.147Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:19.153Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:19.238Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:19.265Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:19.317Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:19.350Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:19.368Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:19.376Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:19.392Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:19.433Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:19.453Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:19.460Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:19.487Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:19.504Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:19.530Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:19.537Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:19.566Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:19.605Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:19.627Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:19.664Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:19.671Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:19.680Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:19.711Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:19.741Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:19.782Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:19.809Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:19.822Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:19.862Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:19.878Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:19.893Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:19.903Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:19.915Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:19.951Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:19.962Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:19.992Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:20.004Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:20.016Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:20.051Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:02:21.231Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:02:21.231Z SendDataConnector.js: Connect (retry count 1) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:02:21.232Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:02:21.232Z SendDataConnector.js: do connect now
I/jxcore-log( 3002): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): connect: Trying to start connecting to XT1072 in address 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnecting: XT1072 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): connect: Started connecting to XT1072 in address 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Trying to connect...
W/BluetoothAdapter( 3002): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa42185dc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [44:80:eb:7b:5a:05]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: XT1072
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4218414 rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Outgoing connection initialized (thread ID: 349)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): onBytesWritten: 77 bytes successfully written (thread ID: 349)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Entering thread (ID: 349)
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4218414 rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): onBytesRead: Read 81 bytes successfully (thread ID: 349)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Handshake succeeded with [44:80:EB:7B:5A:05 motorola-XT1072_PT6826 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT6826 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Exiting thread (ID: 349)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT6826 44:80:EB:7B:5A:05]
I/BtConnectorHelper( 3002): Starting the connected thread incoming : false, motorola-XT1072_PT6826
I/BtToSocketBase( 3002): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3002): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3002): mHTTPPort  set to : 48529
I/BtConnectorHelper( 3002): Request socket is using : 48529
,I/BtToRequestSocket( 3002): Now accepting connections
,I/BtConnectorHelper( 3002): Calling ConnectionStatusUpdate with port :48529
I/jxcore-log( 3002): 2015-11-30T11:02:24.794Z SendDataConnector.js: CLIENT connected to 48529, error: null
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:02:24.795Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3002): 
,I/BtToRequestSocket( 3002): incoming data from: /127.0.0.1, port: 48529
I/BtToRequestSocket( 3002): Set local streams
I/BtToRequestSocket( 3002): rin ended ---------------------------;
,I/jxcore-log( 3002): 2015-11-30T11:02:24.828Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3002): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa42185dc rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 1
W/bt-btif ( 3052): proc dm_pm_timer expires
,W/bt-btif ( 3052): invalid rfc slot id: 17
,I/BtToSocketBase( 3002): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3002): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3002): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT7478
I/BtToSocketBase( 3002): Stop ReceivingThread
I/BtToSocketBase( 3002): Stop SendingThread
,I/BtToSocketBase( 3002): Close local in
I/BtToSocketBase( 3002): Close LocalOutputStream
I/BtToSocketBase( 3002): Close localHostSocket
I/BtToSocketBase( 3002): Close bt in
I/BtToSocketBase( 3002): Close bt out
I/BtToSocketBase( 3002): Close bt socket
,I/BtToSocketBase( 3002): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3002): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3002): 2015-11-30T11:03:10.287Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:03:14.902Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:03:14.903Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:03:14.904Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:03:14.904Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:03:14.906Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3002): 
,I/BtToSocketBase( 3002): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3002): Disconnect outgoing peer: motorola-XT1072_PT6826
I/BtToSocketBase( 3002): Stop ReceivingThread
I/BtToSocketBase( 3002): Stop SendingThread
,I/BtToSocketBase( 3002): Close local in
I/BtToSocketBase( 3002): Close LocalOutputStream
I/BtToSocketBase( 3002): Close localHostSocket
I/BtToSocketBase( 3002): Close bt in
,I/BtToSocketBase( 3002): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3002): Close bt out
I/BtToSocketBase( 3002): Close bt socket
I/BtToRequestSocket( 3002): Close server socket
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4218414 rs_disc_pending=1
,W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): bta_jv_rfc_port_to_cb(port_handle:0x18):jv handle:0x0 not FOUND
,I/jxcore-log( 3002): 2015-11-30T11:03:19.906Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:03:19.907Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3002): 
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: XT1072
,I/jxcore-log( 3002): 2015-11-30T11:03:24.911Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:03:24.912Z SendDataConnector.js: Connect (retry count 2) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:03:24.912Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:03:24.913Z SendDataConnector.js: do connect now
I/jxcore-log( 3002): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): connect: Trying to start connecting to XT1072 in address 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnecting: XT1072 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): connect: Started connecting to XT1072 in address 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Trying to connect...
W/BluetoothAdapter( 3002): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: ALE-L21
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): cancel: Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3052): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:22, channel:-1
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnectionFailed: Cancelled: Connection timeout [44:80:EB:7B:5A:05 motorola-XT1072_PT6826 44:80:EB:7B:5A:05]
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [44:80:EB:7B:5A:05 motorola-XT1072_PT6826 44:80:EB:7B:5A:05]
I/jxcore-log( 3002): 2015-11-30T11:03:54.952Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:03:54.953Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:03:54.954Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3002): 
W/jxcore-log( 3002): $$jxcore_callback_20 wasn't registered
W/jxcore-log( 3002): 
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [44:80:eb:7b:5a:05]: 6, 10f, 608
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,W/bt-btif ( 3052): invalid rfc slot id: 22
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: XT1072
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: XT1072
,I/jxcore-log( 3002): 2015-11-30T11:03:59.954Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:03:59.954Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:04:04.956Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:04:04.957Z SendDataConnector.js: Connect (retry count 3) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:04:04.957Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:04:04.958Z SendDataConnector.js: do connect now
I/jxcore-log( 3002): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): connect: Trying to start connecting to XT1072 in address 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnecting: XT1072 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): connect: Started connecting to XT1072 in address 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Trying to connect...
W/BluetoothAdapter( 3002): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: XT1072
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Outgoing connection initialized (thread ID: 355)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): onBytesWritten: 77 bytes successfully written (thread ID: 355)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Entering thread (ID: 355)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): onBytesRead: Read 81 bytes successfully (thread ID: 355)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Handshake succeeded with [44:80:EB:7B:5A:05 motorola-XT1072_PT6826 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT6826 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Exiting thread (ID: 355)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT6826 44:80:EB:7B:5A:05]
I/BtConnectorHelper( 3002): Starting the connected thread incoming : false, motorola-XT1072_PT6826
I/BtToSocketBase( 3002): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3002): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3002): mHTTPPort  set to : 32923
I/BtConnectorHelper( 3002): Request socket is using : 32923
I/BtToRequestSocket( 3002): Now accepting connections
,I/BtConnectorHelper( 3002): Calling ConnectionStatusUpdate with port :32923
I/jxcore-log( 3002): 2015-11-30T11:04:07.732Z SendDataConnector.js: CLIENT connected to 32923, error: null
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:04:07.732Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:04:07.734Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,I/jxcore-log( 3002): 
,I/BtToRequestSocket( 3002): incoming data from: /127.0.0.1, port: 32923
I/BtToRequestSocket( 3002): Set local streams
I/BtToRequestSocket( 3002): rin ended ---------------------------;
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
W/bt-btif ( 3052): proc dm_pm_timer expires
,I/jxcore-log( 3002): 2015-11-30T11:04:57.819Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:04:57.820Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:04:57.821Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:04:57.822Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:04:57.823Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3002): 
,I/BtToSocketBase( 3002): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 3002): Disconnect outgoing peer: motorola-XT1072_PT6826
I/BtToSocketBase( 3002): Stop ReceivingThread
I/BtToSocketBase( 3002): Stop SendingThread
I/BtToSocketBase( 3002): Close local in
,I/BtToSocketBase( 3002): Close LocalOutputStream
I/BtToSocketBase( 3002): Close localHostSocket
I/BtToSocketBase( 3002): Close bt in
,I/BtToSocketBase( 3002): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3002): Close bt out
,I/BtToSocketBase( 3002): Close bt socket
,I/BtToRequestSocket( 3002): Close server socket
,W/bt-btif ( 3052): bta_jv_rfc_port_to_cb(port_handle:0x19):jv handle:0x0 not FOUND
,I/jxcore-log( 3002): 2015-11-30T11:05:02.823Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:05:02.824Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3002): 
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: XT1072
,I/jxcore-log( 3002): 2015-11-30T11:05:07.828Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:05:07.831Z SendDataConnector.js: Connect (retry count 4) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:05:07.831Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:05:07.832Z SendDataConnector.js: do connect now
I/jxcore-log( 3002): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): connect: Trying to start connecting to XT1072 in address 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnecting: XT1072 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): connect: Started connecting to XT1072 in address 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Trying to connect...
W/BluetoothAdapter( 3002): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: XT1072
,I/art     (  756): Explicit concurrent mark sweep GC freed 30910(1359KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.065ms total 57.137ms
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Outgoing connection initialized (thread ID: 360)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): onBytesWritten: 77 bytes successfully written (thread ID: 360)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Entering thread (ID: 360)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): onBytesRead: Read 81 bytes successfully (thread ID: 360)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Handshake succeeded with [44:80:EB:7B:5A:05 motorola-XT1072_PT6826 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT6826 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Exiting thread (ID: 360)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT6826 44:80:EB:7B:5A:05]
I/BtConnectorHelper( 3002): Starting the connected thread incoming : false, motorola-XT1072_PT6826
I/BtToSocketBase( 3002): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3002): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3002): mHTTPPort  set to : 46894
,I/BtConnectorHelper( 3002): Request socket is using : 46894
I/BtToRequestSocket( 3002): Now accepting connections
,I/BtConnectorHelper( 3002): Calling ConnectionStatusUpdate with port :46894
I/jxcore-log( 3002): 2015-11-30T11:05:10.243Z SendDataConnector.js: CLIENT connected to 46894, error: null
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:05:10.244Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3002): 
,I/BtToRequestSocket( 3002): incoming data from: /127.0.0.1, port: 46894
I/BtToRequestSocket( 3002): Set local streams
I/BtToRequestSocket( 3002): rin ended ---------------------------;
,I/jxcore-log( 3002): 2015-11-30T11:05:10.265Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3002): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
,W/bt-btif ( 3052): proc dm_pm_timer expires
,I/jxcore-log( 3002): 2015-11-30T11:06:00.360Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:06:00.360Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:06:00.361Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:06:00.380Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:06:00.380Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:06:00.381Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3002): 
I/BtConnectorHelper( 3002): Disconnect outgoing peer: 44:80:EB:7B:5A:05
I/BtToSocketBase( 3002): Stop ReceivingThread
I/BtToSocketBase( 3002): Stop SendingThread
I/BtToSocketBase( 3002): Close local in
,I/BtToSocketBase( 3002): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3002): Close LocalOutputStream
,I/BtToSocketBase( 3002): Close localHostSocket
I/BtToSocketBase( 3002): Close bt in
,I/BtToSocketBase( 3002): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3002): Close bt out
I/BtToSocketBase( 3002): Close bt socket
I/BtToRequestSocket( 3002): Close server socket
,I/jxcore-log( 3002): 2015-11-30T11:06:00.418Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3002): 
I/jxcore-log( 3002): ---- round done--------
I/jxcore-log( 3002): 
I/jxcore-log( 3002): ---- gotta redo : 44:80:EB:7B:5A:05, try count now: 1
I/jxcore-log( 3002): 
I/jxcore-log( 3002): do fake peer & start
I/jxcore-log( 3002): 
I/jxcore-log( 3002): Connect to fake peer: 80:01:84:8A:B3:68
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:06:00.426Z SendDataConnector.js: Start called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:06:00.427Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:06:00.427Z SendDataConnector.js: do connect now
I/jxcore-log( 3002): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): connect: Trying to start connecting to null in address 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnecting: null 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): connect: Started connecting to null in address 80:01:84:8A:B3:68
,I/jxcore-log( 3002): 2015-11-30T11:06:00.429Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3002): 
,I/chromium( 3002): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 44:80:EB:7B:5A:05 done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Trying to connect...
W/BluetoothAdapter( 3002): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3052): bta_jv_rfc_port_to_cb(port_handle:0x1a):jv handle:0x0 not FOUND
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4218414 rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: XT1072
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 1
E/bt-btif ( 3052): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3052): Entering PendingCommandState State
,W/BluetoothEventManager( 3090): CachedBluetoothDevice for device 80:01:84:8A:B3:68 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3090): Got bonding state changed for 80:01:84:8A:B3:68, but we have no record of that device.
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 0
,D/BluetoothAdapterProperties( 3052): Failed to remove device: 80:01:84:8A:B3:68
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3052): StableState(): Entering Off State
,W/BluetoothEventManager( 3090): CachedBluetoothDevice for device 80:01:84:8A:B3:68 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3090): Got bonding state changed for 80:01:84:8A:B3:68, but we have no record of that device.
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Outgoing connection initialized (thread ID: 365)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): onBytesWritten: 77 bytes successfully written (thread ID: 365)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Entering thread (ID: 365)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): onBytesRead: Read 84 bytes successfully (thread ID: 365)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Handshake succeeded with [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT2983 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onConnected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT2983 80:01:84:8A:B3:68]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT2983 80:01:84:8A:B3:68]
I/BtConnectorHelper( 3002): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT2983
I/BtToSocketBase( 3002): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3002): Creating BtConnectedRequestSocket
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Exiting thread (ID: 365)
,I/BtToRequestSocket( 3002): mHTTPPort  set to : 39366
I/BtConnectorHelper( 3002): Request socket is using : 39366
I/BtToRequestSocket( 3002): Now accepting connections
,I/BtConnectorHelper( 3002): Calling ConnectionStatusUpdate with port :39366
I/jxcore-log( 3002): 2015-11-30T11:06:07.288Z SendDataConnector.js: CLIENT connected to 39366, error: null
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:06:07.293Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3002): 
,I/BtToRequestSocket( 3002): incoming data from: /127.0.0.1, port: 39366
I/BtToRequestSocket( 3002): Set local streams
I/BtToRequestSocket( 3002): rin ended ---------------------------;
,I/jxcore-log( 3002): 2015-11-30T11:06:07.313Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:06:07.810Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:06:07.848Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:06:07.907Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:06:07.976Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:06:08.018Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:06:08.022Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:06:08.098Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:06:08.139Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:06:08.181Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:06:08.182Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:06:08.198Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:06:08.200Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3002): 
I/BtConnectorHelper( 3002): Disconnect outgoing peer: 80:01:84:8A:B3:68
I/BtToSocketBase( 3002): Stop ReceivingThread
I/BtToSocketBase( 3002): Stop SendingThread
I/BtToSocketBase( 3002): Close local in
,I/BtToSocketBase( 3002): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3002): Close LocalOutputStream
I/BtToSocketBase( 3002): Close localHostSocket
I/BtToSocketBase( 3002): Close bt in
,I/BtToSocketBase( 3002): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3002): Close bt out
I/BtToSocketBase( 3002): Close bt socket
I/BtToRequestSocket( 3002): Close server socket
,I/jxcore-log( 3002): 2015-11-30T11:06:08.228Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): ---- round done--------
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): do fake peer & start
I/jxcore-log( 3002): 
I/jxcore-log( 3002): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:06:08.241Z SendDataConnector.js: Start called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:06:08.243Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:06:08.244Z SendDataConnector.js: do connect now
I/jxcore-log( 3002): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): connect: 
,W/bt-btif ( 3052): bta_jv_rfc_port_to_cb(port_handle:0x1b):jv handle:0x0 not FOUND
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): connect: Trying to start connecting to ALE-L21 in address 58:2A:F7:ED:96:BE
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnecting: ALE-L21 58:2A:F7:ED:96:BE
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): connect: Started connecting to ALE-L21 in address 58:2A:F7:ED:96:BE
,I/chromium( 3002): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 80:01:84:8A:B3:68 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Trying to connect...
W/BluetoothAdapter( 3002): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa42187a4 rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [58:2a:f7:ed:96:be]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: ALE-L21
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa42185dc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 1
E/bt-btif ( 3052): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3052): Entering PendingCommandState State
,W/BluetoothEventManager( 3090): CachedBluetoothDevice for device 58:2A:F7:ED:96:BE not found, calling readPairedDevices().
,E/BluetoothEventManager( 3090): Got bonding state changed for 58:2A:F7:ED:96:BE, but we have no record of that device.
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 0
,D/BluetoothAdapterProperties( 3052): Failed to remove device: 58:2A:F7:ED:96:BE
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3052): StableState(): Entering Off State
,W/BluetoothEventManager( 3090): CachedBluetoothDevice for device 58:2A:F7:ED:96:BE not found, calling readPairedDevices().
,E/BluetoothEventManager( 3090): Got bonding state changed for 58:2A:F7:ED:96:BE, but we have no record of that device.
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa42185dc rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Outgoing connection initialized (thread ID: 370)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): onBytesWritten: 77 bytes successfully written (thread ID: 370)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Entering thread (ID: 370)
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa42185dc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): onBytesRead: Read 80 bytes successfully (thread ID: 370)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Handshake succeeded with [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT7478 58:2A:F7:ED:96:BE]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onConnected: [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT7478 58:2A:F7:ED:96:BE]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Exiting thread (ID: 370)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnected: [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT7478 58:2A:F7:ED:96:BE]
I/BtConnectorHelper( 3002): Starting the connected thread incoming : false, HUAWEI-ALE-L21_PT7478
I/BtToSocketBase( 3002): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3002): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3002): mHTTPPort  set to : 59207
I/BtConnectorHelper( 3002): Request socket is using : 59207
I/BtToRequestSocket( 3002): Now accepting connections
,I/BtConnectorHelper( 3002): Calling ConnectionStatusUpdate with port :59207
I/jxcore-log( 3002): 2015-11-30T11:06:11.166Z SendDataConnector.js: CLIENT connected to 59207, error: null
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:06:11.167Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3002): 
,I/BtToRequestSocket( 3002): incoming data from: /127.0.0.1, port: 59207
I/BtToRequestSocket( 3002): Set local streams
,I/BtToRequestSocket( 3002): rin ended ---------------------------;
,I/jxcore-log( 3002): 2015-11-30T11:06:11.190Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3002): 
,D/        ( 3052): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3002): 2015-11-30T11:06:11.701Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3002): 
,D/        ( 3052): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14806
,I/jxcore-log( 3002): 2015-11-30T11:06:11.849Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:06:11.907Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3002): 
,D/        ( 3052): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2926
,I/jxcore-log( 3002): 2015-11-30T11:06:12.001Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:06:12.025Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:06:12.063Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:06:12.104Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:06:12.107Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3002): 
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: HTC Desire 820
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
W/bt-btif ( 3052): proc dm_pm_timer expires
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
W/bt-btif ( 3052): proc dm_pm_timer expires
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa42185dc rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3002): 2015-11-30T11:07:02.108Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:07:02.112Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:07:02.118Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:07:02.119Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:07:02.120Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3002): 
,I/BtToSocketBase( 3002): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3002): Disconnect outgoing peer: HUAWEI-ALE-L21_PT7478
I/BtToSocketBase( 3002): Stop ReceivingThread
,I/BtToSocketBase( 3002): Stop SendingThread
I/BtToSocketBase( 3002): Close local in
,I/BtToSocketBase( 3002): Close LocalOutputStream
I/BtToSocketBase( 3002): Close localHostSocket
I/BtToSocketBase( 3002): Close bt in
,I/BtToSocketBase( 3002): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3002): Close bt out
I/BtToSocketBase( 3002): Close bt socket
,I/BtToRequestSocket( 3002): Close server socket
,W/bt-btif ( 3052): bta_jv_rfc_port_to_cb(port_handle:0x1c):jv handle:0x0 not FOUND
,I/jxcore-log( 3002): 2015-11-30T11:07:07.121Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:07:07.121Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3002): 
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: ALE-L21
,I/jxcore-log( 3002): 2015-11-30T11:07:12.125Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:07:12.126Z SendDataConnector.js: Connect (retry count 1) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:07:12.126Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:07:12.127Z SendDataConnector.js: do connect now
I/jxcore-log( 3002): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): connect: Trying to start connecting to ALE-L21 in address 58:2A:F7:ED:96:BE
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnecting: ALE-L21 58:2A:F7:ED:96:BE
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): connect: Started connecting to ALE-L21 in address 58:2A:F7:ED:96:BE
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Trying to connect...
W/BluetoothAdapter( 3002): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [58:2a:f7:ed:96:be]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: ALE-L21
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa42185dc rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Outgoing connection initialized (thread ID: 375)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): onBytesWritten: 77 bytes successfully written (thread ID: 375)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Entering thread (ID: 375)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): onBytesRead: Read 80 bytes successfully (thread ID: 375)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Handshake succeeded with [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT7478 58:2A:F7:ED:96:BE]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onConnected: [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT7478 58:2A:F7:ED:96:BE]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Exiting thread (ID: 375)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnected: [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT7478 58:2A:F7:ED:96:BE]
,I/BtConnectorHelper( 3002): Starting the connected thread incoming : false, HUAWEI-ALE-L21_PT7478
I/BtToSocketBase( 3002): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3002): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3002): mHTTPPort  set to : 39621
I/BtConnectorHelper( 3002): Request socket is using : 39621
I/BtToRequestSocket( 3002): Now accepting connections
,I/BtConnectorHelper( 3002): Calling ConnectionStatusUpdate with port :39621
I/jxcore-log( 3002): 2015-11-30T11:07:17.055Z SendDataConnector.js: CLIENT connected to 39621, error: null
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:07:17.056Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3002): 
,I/BtToRequestSocket( 3002): incoming data from: /127.0.0.1, port: 39621
I/BtToRequestSocket( 3002): Set local streams
,I/BtToRequestSocket( 3002): rin ended ---------------------------;
,I/jxcore-log( 3002): 2015-11-30T11:07:17.105Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3002): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
,W/bt-btif ( 3052): proc dm_pm_timer expires
,I/jxcore-log( 3002): 2015-11-30T11:08:07.141Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:08:07.142Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:08:07.144Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:08:07.144Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:08:07.145Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3002): 
,I/BtToSocketBase( 3002): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 3002): Disconnect outgoing peer: HUAWEI-ALE-L21_PT7478
I/BtToSocketBase( 3002): Stop ReceivingThread
I/BtToSocketBase( 3002): Stop SendingThread
I/BtToSocketBase( 3002): Close local in
,I/BtToSocketBase( 3002): Close LocalOutputStream
I/BtToSocketBase( 3002): Close localHostSocket
I/BtToSocketBase( 3002): Close bt in
,I/BtToSocketBase( 3002): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3002): Close bt out
I/BtToSocketBase( 3002): Close bt socket
,I/BtToRequestSocket( 3002): Close server socket
,W/bt-btif ( 3052): bta_jv_rfc_port_to_cb(port_handle:0x1d):jv handle:0x0 not FOUND
,I/jxcore-log( 3002): 2015-11-30T11:08:12.145Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:08:12.146Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3002): 
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: ALE-L21
,I/jxcore-log( 3002): 2015-11-30T11:08:17.151Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:08:17.151Z SendDataConnector.js: Connect (retry count 2) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:08:17.152Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:08:17.152Z SendDataConnector.js: do connect now
I/jxcore-log( 3002): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): connect: Trying to start connecting to ALE-L21 in address 58:2A:F7:ED:96:BE
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnecting: ALE-L21 58:2A:F7:ED:96:BE
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): connect: Started connecting to ALE-L21 in address 58:2A:F7:ED:96:BE
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Trying to connect...
W/BluetoothAdapter( 3002): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: ALE-L21
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Outgoing connection initialized (thread ID: 380)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): onBytesWritten: 77 bytes successfully written (thread ID: 380)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Entering thread (ID: 380)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): onBytesRead: Read 80 bytes successfully (thread ID: 380)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Handshake succeeded with [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT7478 58:2A:F7:ED:96:BE]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onConnected: [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT7478 58:2A:F7:ED:96:BE]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Exiting thread (ID: 380)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnected: [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT7478 58:2A:F7:ED:96:BE]
I/BtConnectorHelper( 3002): Starting the connected thread incoming : false, HUAWEI-ALE-L21_PT7478
I/BtToSocketBase( 3002): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3002): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3002): mHTTPPort  set to : 43202
I/BtConnectorHelper( 3002): Request socket is using : 43202
I/BtToRequestSocket( 3002): Now accepting connections
,I/BtConnectorHelper( 3002): Calling ConnectionStatusUpdate with port :43202
I/jxcore-log( 3002): 2015-11-30T11:08:20.244Z SendDataConnector.js: CLIENT connected to 43202, error: null
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:08:20.245Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3002): 
,I/BtToRequestSocket( 3002): incoming data from: /127.0.0.1, port: 43202
I/BtToRequestSocket( 3002): Set local streams
I/BtToRequestSocket( 3002): rin ended ---------------------------;
,I/jxcore-log( 3002): 2015-11-30T11:08:20.265Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3002): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
W/bt-btif ( 3052): proc dm_pm_timer expires
,I/jxcore-log( 3002): 2015-11-30T11:09:10.328Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:09:10.333Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:09:10.334Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:09:10.335Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:09:10.336Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3002): 
,I/BtToSocketBase( 3002): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3002): Disconnect outgoing peer: HUAWEI-ALE-L21_PT7478
I/BtToSocketBase( 3002): Stop ReceivingThread
I/BtToSocketBase( 3002): Stop SendingThread
I/BtToSocketBase( 3002): Close local in
I/BtToSocketBase( 3002): Close LocalOutputStream
I/BtToSocketBase( 3002): Close localHostSocket
I/BtToSocketBase( 3002): Close bt in
,I/BtToSocketBase( 3002): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3002): Close bt out
I/BtToSocketBase( 3002): Close bt socket
I/BtToRequestSocket( 3002): Close server socket
,W/bt-btif ( 3052): bta_jv_rfc_port_to_cb(port_handle:0x1e):jv handle:0x0 not FOUND
,I/UsageStatsService(  756): User[0] Flushing usage stats to disk
,I/jxcore-log( 3002): 2015-11-30T11:09:15.338Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:09:15.344Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3002): 
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: ALE-L21
,I/jxcore-log( 3002): 2015-11-30T11:09:20.350Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:09:20.351Z SendDataConnector.js: Connect (retry count 3) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:09:20.351Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:09:20.352Z SendDataConnector.js: do connect now
I/jxcore-log( 3002): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): connect: Trying to start connecting to ALE-L21 in address 58:2A:F7:ED:96:BE
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnecting: ALE-L21 58:2A:F7:ED:96:BE
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): connect: Started connecting to ALE-L21 in address 58:2A:F7:ED:96:BE
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Trying to connect...
W/BluetoothAdapter( 3002): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: ALE-L21
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Outgoing connection initialized (thread ID: 385)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): onBytesWritten: 77 bytes successfully written (thread ID: 385)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Entering thread (ID: 385)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): onBytesRead: Read 80 bytes successfully (thread ID: 385)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Handshake succeeded with [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT7478 58:2A:F7:ED:96:BE]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onConnected: [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT7478 58:2A:F7:ED:96:BE]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnected: [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT7478 58:2A:F7:ED:96:BE]
I/BtConnectorHelper( 3002): Starting the connected thread incoming : false, HUAWEI-ALE-L21_PT7478
I/BtToSocketBase( 3002): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3002): Creating BtConnectedRequestSocket
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Exiting thread (ID: 385)
,I/BtToRequestSocket( 3002): mHTTPPort  set to : 42394
I/BtConnectorHelper( 3002): Request socket is using : 42394
I/BtToRequestSocket( 3002): Now accepting connections
,I/BtConnectorHelper( 3002): Calling ConnectionStatusUpdate with port :42394
I/jxcore-log( 3002): 2015-11-30T11:09:21.693Z SendDataConnector.js: CLIENT connected to 42394, error: null
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:09:21.693Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3002): 
,I/BtToRequestSocket( 3002): incoming data from: /127.0.0.1, port: 42394
I/BtToRequestSocket( 3002): Set local streams
I/BtToRequestSocket( 3002): rin ended ---------------------------;
,I/jxcore-log( 3002): 2015-11-30T11:09:21.696Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3002): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
W/bt-btif ( 3052): proc dm_pm_timer expires
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421896c rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa42185dc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
W/bt-btif ( 3052): proc dm_pm_timer expires
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa42185dc rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
,W/bt-btif ( 3052): proc dm_pm_timer expires
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa42185dc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421896c rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 1
E/bt-btif ( 3052): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3052): Entering PendingCommandState State
,W/BluetoothEventManager( 3090): CachedBluetoothDevice for device 00:F4:6F:30:E0:6C not found, calling readPairedDevices().
,E/BluetoothEventManager( 3090): Got bonding state changed for 00:F4:6F:30:E0:6C, but we have no record of that device.
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 0
,D/BluetoothAdapterProperties( 3052): Failed to remove device: 00:F4:6F:30:E0:6C
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3052): StableState(): Entering Off State
,W/BluetoothEventManager( 3090): CachedBluetoothDevice for device 00:F4:6F:30:E0:6C not found, calling readPairedDevices().
,E/BluetoothEventManager( 3090): Got bonding state changed for 00:F4:6F:30:E0:6C, but we have no record of that device.
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Incoming connection initialized (thread ID: 389)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Entering thread (ID: 389)
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421896c rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): onBytesRead: Read 82 bytes successfully (thread ID: 389)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Got valid identity from [00:F4:6F:30:E0:6C samsung-SM-G800F_PT5189 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): onBytesWritten: 77 bytes successfully written (thread ID: 389)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): removeThreadFromList: Removing thread with ID 389
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Handshake thread disposed (thread ID: 389)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onIncomingConnectionConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT5189 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Exiting thread (ID: 389)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT5189 00:F4:6F:30:E0:6C]
I/BtConnectorHelper( 3002): Starting the connected thread incoming : true, samsung-SM-G800F_PT5189
I/BtToSocketBase( 3002): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3002): Creating BTConnectedThread
I/BtConnectorHelper( 3002): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3002): --DoOneRunRound started
,I/BtToRequestSocket( 3002): LocalHost address: localhost/127.0.0.1, port: 51687
I/BtToRequestSocket( 3002): --DoOneRunRound ended
,I/jxcore-log( 3002): 2015-11-30T11:10:07.035Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:08.110Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:08.140Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:08.242Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:08.251Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:08.260Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:08.272Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:08.304Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:08.316Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:08.356Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:08.361Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:08.379Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:08.413Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:08.423Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:08.463Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:08.477Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:08.511Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:08.521Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:08.561Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:08.579Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:08.615Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:10:08.616Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3002): 
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
,W/bt-btif ( 3052): proc dm_pm_timer expires
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3002): 2015-11-30T11:10:11.781Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:10:11.782Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:10:11.783Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:10:11.783Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:10:11.784Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3002): 
,I/BtToSocketBase( 3002): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3002): Disconnect outgoing peer: HUAWEI-ALE-L21_PT7478
I/BtToSocketBase( 3002): Stop ReceivingThread
I/BtToSocketBase( 3002): Stop SendingThread
,I/BtToSocketBase( 3002): Close local in
I/BtToSocketBase( 3002): Close LocalOutputStream
I/BtToSocketBase( 3002): Close localHostSocket
I/BtToSocketBase( 3002): Close bt in
,I/BtToSocketBase( 3002): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3002): Close bt out
I/BtToSocketBase( 3002): Close bt socket
I/BtToRequestSocket( 3002): Close server socket
,W/bt-btif ( 3052): bta_jv_rfc_port_to_cb(port_handle:0x1):jv handle:0x0 not FOUND
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa42185dc rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3002): 2015-11-30T11:10:16.784Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:10:16.785Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3002): 
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: ALE-L21
,I/jxcore-log( 3002): 2015-11-30T11:10:21.788Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:10:21.789Z SendDataConnector.js: Connect (retry count 4) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:10:21.789Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:10:21.790Z SendDataConnector.js: do connect now
I/jxcore-log( 3002): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): connect: Trying to start connecting to ALE-L21 in address 58:2A:F7:ED:96:BE
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnecting: ALE-L21 58:2A:F7:ED:96:BE
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): connect: Started connecting to ALE-L21 in address 58:2A:F7:ED:96:BE
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Trying to connect...
W/BluetoothAdapter( 3002): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: ALE-L21
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa42185dc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa42185dc rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Outgoing connection initialized (thread ID: 394)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): onBytesWritten: 77 bytes successfully written (thread ID: 394)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Entering thread (ID: 394)
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa42185dc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): onBytesRead: Read 80 bytes successfully (thread ID: 394)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Handshake succeeded with [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT7478 58:2A:F7:ED:96:BE]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onConnected: [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT7478 58:2A:F7:ED:96:BE]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Exiting thread (ID: 394)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnected: [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT7478 58:2A:F7:ED:96:BE]
,I/BtConnectorHelper( 3002): Starting the connected thread incoming : false, HUAWEI-ALE-L21_PT7478
I/BtToSocketBase( 3002): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3002): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3002): mHTTPPort  set to : 60787
,I/BtConnectorHelper( 3002): Request socket is using : 60787
I/BtToRequestSocket( 3002): Now accepting connections
,I/BtConnectorHelper( 3002): Calling ConnectionStatusUpdate with port :60787
,I/jxcore-log( 3002): 2015-11-30T11:10:23.418Z SendDataConnector.js: CLIENT connected to 60787, error: null
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:10:23.421Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3002): 
,I/BtToRequestSocket( 3002): incoming data from: /127.0.0.1, port: 60787
I/BtToRequestSocket( 3002): Set local streams
I/BtToRequestSocket( 3002): rin ended ---------------------------;
,I/jxcore-log( 3002): 2015-11-30T11:10:23.441Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3002): 
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4218b34 rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 3052): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3052): Entering PendingCommandState State
,W/BluetoothEventManager( 3090): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3090): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3052): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3052): StableState(): Entering Off State
,W/BluetoothEventManager( 3090): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3090): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Incoming connection initialized (thread ID: 398)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Entering thread (ID: 398)
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4218b34 rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): onBytesRead: Read 77 bytes successfully (thread ID: 398)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Got valid identity from [F8:95:C7:87:85:54 LGE-LG-D722_PT1191 F8:95:C7:87:85:54]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): onBytesWritten: 77 bytes successfully written (thread ID: 398)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): removeThreadFromList: Removing thread with ID 398
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Handshake thread disposed (thread ID: 398)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onIncomingConnectionConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT1191 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Exiting thread (ID: 398)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT1191 F8:95:C7:87:85:54]
I/BtConnectorHelper( 3002): Starting the connected thread incoming : true, LGE-LG-D722_PT1191
I/BtToSocketBase( 3002): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3002): Creating BTConnectedThread
I/BtConnectorHelper( 3002): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3002): --DoOneRunRound started
,I/BtToRequestSocket( 3002): LocalHost address: localhost/127.0.0.1, port: 51687
I/BtToRequestSocket( 3002): --DoOneRunRound ended
,I/jxcore-log( 3002): 2015-11-30T11:10:26.028Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:27.058Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:27.068Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:27.077Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:27.083Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:27.104Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data,
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:27.129Z SendDataTCPServer.js: TCP/IP server has received 28536 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:27.140Z SendDataTCPServer.js: TCP/IP server has received 30516 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:27.144Z SendDataTCPServer.js: TCP/IP server has received 32496 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:27.179Z SendDataTCPServer.js: TCP/IP server has received 48336 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:27.186Z SendDataTCPServer.js: TCP/IP server has received 50316 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:27.191Z SendDataTCPServer.js: TCP/IP server has received 52296 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:27.234Z SendDataTCPServer.js: TCP/IP server has received 68136 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:27.237Z SendDataTCPServer.js: TCP/IP server has received 70116 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:27.242Z SendDataTCPServer.js: TCP/IP server has received 72096 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:27.279Z SendDataTCPServer.js: TCP/IP server has received 87936 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:27.282Z SendDataTCPServer.js: TCP/IP server has received 89916 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:27.286Z SendDataTCPServer.js: TCP/IP server has received 91896 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:27.320Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3002): 
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
,W/bt-btif ( 3052): proc dm_pm_timer expires
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
E/bt-btif ( 3052): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3052): Entering PendingCommandState State
,W/BluetoothEventManager( 3090): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3090): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 3052): Failed to remove device: E0:DB:10:14:E2:C0
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3052): StableState(): Entering Off State
,W/BluetoothEventManager( 3090): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3090): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Incoming connection initialized (thread ID: 402)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Entering thread (ID: 402)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): onBytesRead: Read 82 bytes successfully (thread ID: 402)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Got valid identity from [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4244 E0:DB:10:14:E2:C0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): onBytesWritten: 77 bytes successfully written (thread ID: 402)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): removeThreadFromList: Removing thread with ID 402
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Handshake thread disposed (thread ID: 402)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onIncomingConnectionConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4244 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Exiting thread (ID: 402)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4244 E0:DB:10:14:E2:C0]
I/BtConnectorHelper( 3002): Starting the connected thread incoming : true, samsung-SM-N910C_PT4244
I/BtToSocketBase( 3002): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3002): Creating BTConnectedThread
I/BtConnectorHelper( 3002): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3002): --DoOneRunRound started
,I/jxcore-log( 3002): 2015-11-30T11:10:42.182Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3002): 
,I/BtToRequestSocket( 3002): LocalHost address: localhost/127.0.0.1, port: 51687
I/BtToRequestSocket( 3002): --DoOneRunRound ended
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421896c rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3002): 2015-11-30T11:10:42.965Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:42.972Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:43.024Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:43.032Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:43.104Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:43.142Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:43.192Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:43.202Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:43.242Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:43.293Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:43.321Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:43.363Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:43.401Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:43.447Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:43.481Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:43.534Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:43.570Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:43.613Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:43.620Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:43.634Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:43.671Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:43.694Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:10:43.730Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3002): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa42185dc rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
W/bt-btif ( 3052): proc dm_pm_timer expires
,W/bt-btif ( 3052): invalid rfc slot id: 20
,I/BtToSocketBase( 3002): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3002): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3002): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT5189
,I/BtToSocketBase( 3002): Stop ReceivingThread
I/BtToSocketBase( 3002): Stop SendingThread
I/BtToSocketBase( 3002): Close local in
,I/BtToSocketBase( 3002): Close LocalOutputStream
I/BtToSocketBase( 3002): Close localHostSocket
I/BtToSocketBase( 3002): Close bt in
I/BtToSocketBase( 3002): Close bt out
I/BtToSocketBase( 3002): Close bt socket
,I/BtToSocketBase( 3002): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3002): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3002): 2015-11-30T11:10:59.112Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3002): 
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421896c rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3052): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
W/bt-rfcomm( 3052): RFCOMM_DisconnectInd LCID:0x44
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: S5mini-1
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa42185dc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
W/bt-btif ( 3052): proc dm_pm_timer expires
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: S5mini-1
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421896c rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3002): 2015-11-30T11:11:13.540Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:11:13.541Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:11:13.541Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:11:13.543Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:11:13.543Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:11:13.545Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3002): 
I/BtConnectorHelper( 3002): Disconnect outgoing peer: 58:2A:F7:ED:96:BE
I/BtToSocketBase( 3002): Stop ReceivingThread
I/BtToSocketBase( 3002): Stop SendingThread
I/BtToSocketBase( 3002): Close local in
,I/BtToSocketBase( 3002): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3002): Close LocalOutputStream
I/BtToSocketBase( 3002): Close localHostSocket
I/BtToSocketBase( 3002): Close bt in
I/BtToSocketBase( 3002): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3002): Close bt out
I/BtToSocketBase( 3002): Close bt socket
I/BtToRequestSocket( 3002): Close server socket
,I/jxcore-log( 3002): 2015-11-30T11:11:13.550Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3002): 
I/jxcore-log( 3002): ---- round done--------
I/jxcore-log( 3002): 
I/jxcore-log( 3002): ---- gotta redo : 58:2A:F7:ED:96:BE, try count now: 1
I/jxcore-log( 3002): 
I/jxcore-log( 3002): do fake peer & start
I/jxcore-log( 3002): 
I/jxcore-log( 3002): Connect to fake peer: 50:2E:6C:AC:21:50
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:11:13.551Z SendDataConnector.js: Start called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:11:13.551Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:11:13.552Z SendDataConnector.js: do connect now
I/jxcore-log( 3002): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): connect: Trying to start connecting to null in address 50:2E:6C:AC:21:50
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnecting: null 50:2E:6C:AC:21:50
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): connect: Started connecting to null in address 50:2E:6C:AC:21:50
I/jxcore-log( 3002): 2015-11-30T11:11:13.554Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3002): 
,I/chromium( 3002): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 58:2A:F7:ED:96:BE done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Trying to connect...
W/BluetoothAdapter( 3002): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421896c rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Incoming connection initialized (thread ID: 407)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Entering thread (ID: 407)
,W/bt-btif ( 3052): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421896c rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): onBytesRead: Read 82 bytes successfully (thread ID: 407)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Got valid identity from [00:F4:6F:30:E0:6C samsung-SM-G800F_PT5189 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): onBytesWritten: 77 bytes successfully written (thread ID: 407)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): removeThreadFromList: Removing thread with ID 407
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Handshake thread disposed (thread ID: 407)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onIncomingConnectionConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT5189 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Exiting thread (ID: 407)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT5189 00:F4:6F:30:E0:6C]
,I/BtConnectorHelper( 3002): Starting the connected thread incoming : true, samsung-SM-G800F_PT5189
I/BtToSocketBase( 3002): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3002): Creating BTConnectedThread
,I/BtConnectorHelper( 3002): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3002): --DoOneRunRound started
,I/jxcore-log( 3002): 2015-11-30T11:11:14.569Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3002): 
,I/BtToRequestSocket( 3002): LocalHost address: localhost/127.0.0.1, port: 51687
,I/BtToRequestSocket( 3002): --DoOneRunRound ended
,I/jxcore-log( 3002): 2015-11-30T11:11:14.994Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:11:15.006Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:11:15.011Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3002): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3052): invalid rfc slot id: 30
,I/BtToSocketBase( 3002): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3002): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3002): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT1191
I/BtToSocketBase( 3002): Stop ReceivingThread
I/BtToSocketBase( 3002): Stop SendingThread
I/BtToSocketBase( 3002): Close local in
I/BtToSocketBase( 3002): Close LocalOutputStream
I/BtToSocketBase( 3002): Close localHostSocket
I/BtToSocketBase( 3002): Close bt in
I/BtToSocketBase( 3002): Close bt out
I/BtToSocketBase( 3002): Close bt socket
,I/BtToSocketBase( 3002): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3002): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3002): 2015-11-30T11:11:18.301Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3002): 
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421896c rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3052): rfc_find_lcid_mcb LCID reused LCID:0x4f current:0x0
W/bt-rfcomm( 3052): RFCOMM_DisconnectInd LCID:0x4f
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: G3s-1
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: ALE-L21
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421896c rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [f8:95:c7:87:85:54]: 6, 10f, 608
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: G3s-1
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 3052): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3052): Entering PendingCommandState State
,W/BluetoothEventManager( 3090): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3090): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3052): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3052): StableState(): Entering Off State
,W/BluetoothEventManager( 3090): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3090): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Incoming connection initialized (thread ID: 411)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Entering thread (ID: 411)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): onBytesRead: Read 77 bytes successfully (thread ID: 411)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Got valid identity from [F8:95:C7:87:85:54 LGE-LG-D722_PT1191 F8:95:C7:87:85:54]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): onBytesWritten: 77 bytes successfully written (thread ID: 411)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): removeThreadFromList: Removing thread with ID 411
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Handshake thread disposed (thread ID: 411)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onIncomingConnectionConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT1191 F8:95:C7:87:85:54]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT1191 F8:95:C7:87:85:54]
I/BtConnectorHelper( 3002): Starting the connected thread incoming : true, LGE-LG-D722_PT1191
I/BtToSocketBase( 3002): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3002): Creating BTConnectedThread
I/BtConnectorHelper( 3002): Server socket is using : 0, and is now connected.
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Exiting thread (ID: 411)
,I/BtToRequestSocket( 3002): --DoOneRunRound started
,I/BtToRequestSocket( 3002): LocalHost address: localhost/127.0.0.1, port: 51687
I/BtToRequestSocket( 3002): --DoOneRunRound ended
,I/jxcore-log( 3002): 2015-11-30T11:11:29.566Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:11:29.950Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:11:29.959Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:11:29.965Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:11:29.974Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3002): 
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
W/bt-btif ( 3052): proc dm_pm_timer expires
,W/bt-btif ( 3052): invalid rfc slot id: 32
,I/BtToSocketBase( 3002): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3002): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3002): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N910C_PT4244
I/BtToSocketBase( 3002): Stop ReceivingThread
I/BtToSocketBase( 3002): Stop SendingThread
,I/BtToSocketBase( 3002): Close local in
I/BtToSocketBase( 3002): Close LocalOutputStream
I/BtToSocketBase( 3002): Close localHostSocket
I/BtToSocketBase( 3002): Close bt in
I/BtToSocketBase( 3002): Close bt out
I/BtToSocketBase( 3002): Close bt socket
,I/BtToSocketBase( 3002): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3002): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3002): 2015-11-30T11:11:33.768Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3002): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-rfcomm( 3052): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
W/bt-rfcomm( 3052): RFCOMM_DisconnectInd LCID:0x42
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: Note4-1
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421896c rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 1
E/bt-btif ( 3052): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3052): Entering PendingCommandState State
,W/BluetoothEventManager( 3090): CachedBluetoothDevice for device 50:2E:6C:AC:21:50 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3090): Got bonding state changed for 50:2E:6C:AC:21:50, but we have no record of that device.
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 0
D/BluetoothAdapterProperties( 3052): Failed to remove device: 50:2E:6C:AC:21:50
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3052): StableState(): Entering Off State
W/BluetoothEventManager( 3090): CachedBluetoothDevice for device 50:2E:6C:AC:21:50 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3090): Got bonding state changed for 50:2E:6C:AC:21:50, but we have no record of that device.
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Outgoing connection initialized (thread ID: 415)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): onBytesWritten: 77 bytes successfully written (thread ID: 415)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Entering thread (ID: 415)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): onBytesRead: Read 80 bytes successfully (thread ID: 415)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3002): Handshake succeeded with [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT2139 50:2E:6C:AC:21:50]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onConnected: [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT2139 50:2E:6C:AC:21:50]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Exiting thread (ID: 415)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnected: [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT2139 50:2E:6C:AC:21:50]
I/BtConnectorHelper( 3002): Starting the connected thread incoming : false, HTC-HTC One_M8_PT2139
,I/BtToSocketBase( 3002): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3002): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3002): mHTTPPort  set to : 42046
I/BtConnectorHelper( 3002): Request socket is using : 42046
I/BtToRequestSocket( 3002): Now accepting connections
,I/BtConnectorHelper( 3002): Calling ConnectionStatusUpdate with port :42046
I/jxcore-log( 3002): 2015-11-30T11:11:41.942Z SendDataConnector.js: CLIENT connected to 42046, error: null
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:11:41.943Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3002): 
,I/BtToRequestSocket( 3002): incoming data from: /127.0.0.1, port: 42046
I/BtToRequestSocket( 3002): Set local streams
I/BtToRequestSocket( 3002): rin ended ---------------------------;
,I/jxcore-log( 3002): 2015-11-30T11:11:41.963Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3002): 
,D/        ( 3052): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3002): 2015-11-30T11:11:42.530Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3002): 
,D/        ( 3052): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:15796
,I/jxcore-log( 3002): 2015-11-30T11:11:42.535Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:11:42.583Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3002): 
,D/        ( 3052): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:5896
,I/jxcore-log( 3002): 2015-11-30T11:11:42.623Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:11:42.636Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:11:42.673Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:11:42.724Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:11:42.762Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:11:42.804Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3002): 
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: Note4-1
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Incoming connection initialized (thread ID: 419)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Entering thread (ID: 419)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): onBytesRead: Read 82 bytes successfully (thread ID: 419)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Got valid identity from [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4244 E0:DB:10:14:E2:C0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): onBytesWritten: 77 bytes successfully written (thread ID: 419)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): removeThreadFromList: Removing thread with ID 419
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Handshake thread disposed (thread ID: 419)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onIncomingConnectionConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4244 E0:DB:10:14:E2:C0]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4244 E0:DB:10:14:E2:C0]
I/BtConnectorHelper( 3002): Starting the connected thread incoming : true, samsung-SM-N910C_PT4244
I/BtToSocketBase( 3002): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3002): Creating BTConnectedThread
I/BtConnectorHelper( 3002): Server socket is using : 0, and is now connected.
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Exiting thread (ID: 419)
,I/BtToRequestSocket( 3002): --DoOneRunRound started
,I/BtToRequestSocket( 3002): LocalHost address: localhost/127.0.0.1, port: 51687
I/BtToRequestSocket( 3002): --DoOneRunRound ended
,I/jxcore-log( 3002): 2015-11-30T11:11:46.267Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:11:46.685Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:11:46.696Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:11:46.704Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3002): 
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
W/bt-btif ( 3052): proc dm_pm_timer expires
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4218cfc rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4218ec4 rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
W/bt-btif ( 3052): proc dm_pm_timer expires
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4218ec4 rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
E/bt-btif ( 3052): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3052): Entering PendingCommandState State
,W/BluetoothEventManager( 3090): CachedBluetoothDevice for device B0:C5:59:3F:75:69 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3090): Got bonding state changed for B0:C5:59:3F:75:69, but we have no record of that device.
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,D/BluetoothAdapterProperties( 3052): Failed to remove device: B0:C5:59:3F:75:69
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3052): StableState(): Entering Off State
,W/BluetoothEventManager( 3090): CachedBluetoothDevice for device B0:C5:59:3F:75:69 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3090): Got bonding state changed for B0:C5:59:3F:75:69, but we have no record of that device.
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421908c rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
W/bt-btif ( 3052): proc dm_pm_timer expires
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Incoming connection initialized (thread ID: 423)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Entering thread (ID: 423)
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421908c rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4218cfc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): onBytesRead: Read 82 bytes successfully (thread ID: 423)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Got valid identity from [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): onBytesWritten: 77 bytes successfully written (thread ID: 423)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): removeThreadFromList: Removing thread with ID 423
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Handshake thread disposed (thread ID: 423)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onIncomingConnectionConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Exiting thread (ID: 423)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
I/BtConnectorHelper( 3002): Starting the connected thread incoming : true, samsung-SM-G900F_PT9998
I/BtToSocketBase( 3002): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3002): Creating BTConnectedThread
I/BtConnectorHelper( 3002): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3002): --DoOneRunRound started
,I/BtToRequestSocket( 3002): LocalHost address: localhost/127.0.0.1, port: 51687
,I/jxcore-log( 3002): 2015-11-30T11:12:04.476Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3002): 
,I/BtToRequestSocket( 3002): --DoOneRunRound ended
,W/bt-btif ( 3052): invalid rfc slot id: 33
,I/BtToSocketBase( 3002): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3002): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3002): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT5189
I/BtToSocketBase( 3002): Stop ReceivingThread
I/BtToSocketBase( 3002): Stop SendingThread
I/BtToSocketBase( 3002): Close local in
I/BtToSocketBase( 3002): Close LocalOutputStream
I/BtToSocketBase( 3002): Close localHostSocket
I/BtToSocketBase( 3002): Close bt in
I/BtToSocketBase( 3002): Close bt out
I/BtToSocketBase( 3002): Close bt socket
,I/BtToSocketBase( 3002): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3002): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3002): 2015-11-30T11:12:05.280Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3002): 
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421896c rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3052): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 3052): RFCOMM_DisconnectInd LCID:0x47
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421908c rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3002): 2015-11-30T11:12:05.712Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:05.802Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:05.846Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:05.934Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:05.983Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:05.990Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:06.152Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:06.192Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:06.204Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:06.211Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:06.274Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:06.314Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:06.375Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:06.421Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:06.476Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:06.609Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:06.653Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:06.705Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:06.919Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:07.044Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:07.056Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:07.112Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:07.230Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:07.288Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:07.345Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:07.393Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:07.430Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:07.452Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:07.502Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:07.608Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:07.802Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:07.910Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:07.961Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:08.021Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:08.076Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:08.125Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:08.160Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:08.233Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:08.240Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:08.299Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:08.309Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:08.347Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:08.381Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:08.404Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:08.412Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:08.467Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:08.502Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:08.541Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:08.613Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:08.714Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3002): 
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4218ec4 rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: S5mini-1
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 2
W/bt-btif ( 3052): proc dm_pm_timer expires
,W/bt-btif ( 3052): invalid rfc slot id: 35
,I/BtToSocketBase( 3002): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3002): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3002): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT1191
,I/BtToSocketBase( 3002): Stop ReceivingThread
I/BtToSocketBase( 3002): Stop SendingThread
,I/BtToSocketBase( 3002): Close local in
I/BtToSocketBase( 3002): Close LocalOutputStream
I/BtToSocketBase( 3002): Close localHostSocket
I/BtToSocketBase( 3002): Close bt in
I/BtToSocketBase( 3002): Close bt out
,I/BtToSocketBase( 3002): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3002): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3002): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT1191
I/BtToSocketBase( 3002): Close bt in
I/BtToSocketBase( 3002): Close bt out
I/BtToSocketBase( 3002): Close bt socket
,I/BtToSocketBase( 3002): Close bt socket
,I/jxcore-log( 3002): 2015-11-30T11:12:20.184Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3002): 
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4218ec4 rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3052): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
W/bt-rfcomm( 3052): RFCOMM_DisconnectInd LCID:0x46
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: G3s-1
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421908c rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
W/bt-btif ( 3052): proc dm_pm_timer expires
,I/jxcore-log( 3002): 2015-11-30T11:12:32.809Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:12:32.810Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:12:32.811Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:12:32.812Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:12:32.813Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3002): 
,I/BtToSocketBase( 3002): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 3002): Disconnect outgoing peer: HTC-HTC One_M8_PT2139
I/BtToSocketBase( 3002): Stop ReceivingThread
I/BtToSocketBase( 3002): Stop SendingThread
I/BtToSocketBase( 3002): Close local in
,I/BtToSocketBase( 3002): Close LocalOutputStream
,I/BtToSocketBase( 3002): Close localHostSocket
I/BtToSocketBase( 3002): Close bt in
,I/BtToSocketBase( 3002): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3002): Close bt out
I/BtToSocketBase( 3002): Close bt socket
I/BtToRequestSocket( 3002): Close server socket
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: G3s-1
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4218b34 rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 3052): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3052): Entering PendingCommandState State
,W/BluetoothEventManager( 3090): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3090): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3052): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3052): StableState(): Entering Off State
,W/BluetoothEventManager( 3090): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3090): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Incoming connection initialized (thread ID: 427)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Entering thread (ID: 427)
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421908c rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4218b34 rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): onBytesRead: Read 77 bytes successfully (thread ID: 427)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Got valid identity from [F8:95:C7:87:85:54 LGE-LG-D722_PT1191 F8:95:C7:87:85:54]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): onBytesWritten: 77 bytes successfully written (thread ID: 427)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): removeThreadFromList: Removing thread with ID 427
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Handshake thread disposed (thread ID: 427)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onIncomingConnectionConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT1191 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3002): Exiting thread (ID: 427)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT1191 F8:95:C7:87:85:54]
I/BtConnectorHelper( 3002): Starting the connected thread incoming : true, LGE-LG-D722_PT1191
I/BtToSocketBase( 3002): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3002): Creating BTConnectedThread
I/BtConnectorHelper( 3002): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3002): --DoOneRunRound started
,I/jxcore-log( 3002): 2015-11-30T11:12:34.618Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3002): 
,I/BtToRequestSocket( 3002): LocalHost address: localhost/127.0.0.1, port: 51687
,I/BtToRequestSocket( 3002): --DoOneRunRound ended
,I/jxcore-log( 3002): 2015-11-30T11:12:35.024Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:35.034Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:35.056Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3002): 
,W/bt-btif ( 3052): invalid rfc slot id: 36
,I/BtToSocketBase( 3002): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3002): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3002): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N910C_PT4244
I/BtToSocketBase( 3002): Stop ReceivingThread
I/BtToSocketBase( 3002): Stop SendingThread
I/BtToSocketBase( 3002): Close local in
I/BtToSocketBase( 3002): Close LocalOutputStream
I/BtToSocketBase( 3002): Close localHostSocket
I/BtToSocketBase( 3002): Close bt in
I/BtToSocketBase( 3002): Close bt out
I/BtToSocketBase( 3002): Close bt socket
,I/BtToSocketBase( 3002): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3002): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3002): 2015-11-30T11:12:36.776Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3002): 
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4218cfc rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3052): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
W/bt-rfcomm( 3052): RFCOMM_DisconnectInd LCID:0x49
,I/jxcore-log( 3002): timeout now
I/jxcore-log( 3002): 
I/jxcore-log( 3002): dun
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): weAreDoneNow , resultArray.length: 1
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): done, now sending data to server
I/jxcore-log( 3002): 
I/jxcore-log( 3002): DBG, CoordinatorConnector sendData called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): -- RESULT DATA {"name:":"LGE-Nexus 5_PT8322","time":1000080,"result":"TIMEOUT","sendList":[{"name":"80:01:84:8A:B3:68","time":7757,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"50:2E:6C:AC:21:50","time":0,"result":"Fail"},{"connections":0,"name":"F8:CF:C5:D9:E5:61","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:9D:93:0B","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"nam
I/jxcore-log( 3002): sendList : 100% : 7757 ms, 99% : 7757 ms, 95 : 7757 ms, 90% : 7757 ms.
I/jxcore-log( 3002): 
I/jxcore-log( 3002): Result count 1, range 7757 ms to  7757 ms.
I/jxcore-log( 3002): 
I/jxcore-log( 3002): sendList failed peers count : 4 [80 %]
I/jxcore-log( 3002): 
I/jxcore-log( 3002): - Peer ID : 50:2E:6C:AC:21:50, Tried : 1
I/jxcore-log( 3002): 
I/jxcore-log( 3002): - Peer ID : 08:EC:A9:50:75:41, Tried : 1
I/jxcore-log( 3002): 
I/jxcore-log( 3002): - Peer ID : 44:80:EB:7B:5A:05, Tried : 1
I/jxcore-log( 3002): 
I/jxcore-log( 3002): - Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
I/jxcore-log( 3002): 
I/jxcore-log( 3002): sendList never tried peers count : 16 [76.19047619047619 %]
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): - Peer ID : F8:CF:C5:D9:E5:61
I/jxcore-log( 3002): 
I/jxcore-log( 3002): - Peer ID : 34:FC:EF:9D:93:0B
I/jxcore-log( 3002): 
I/jxcore-log( 3002): - Peer ID : 7C:F9:0E:51:18:22
I/jxcore-log( 3002): 
I/jxcore-log( 3002): - Peer ID : B0:C5:59:3F:75:69
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): - Peer ID : 08:EC:A9:50:76:27
I/jxcore-log( 3002): 
I/jxcore-log( 3002): - Peer ID : F8:95:C7:87:3C:51
I/jxcore-log( 3002): 
I/jxcore-log( 3002): - Peer ID : E0:DB:10:14:E2:C0
I/jxcore-log( 3002): 
I/jxcore-log( 3002): - Peer ID : 58:3F:54:73:64:C0
I/jxcore-log( 3002): 
I/jxcore-log( 3002): - Peer ID : F8:95:C7:87:85:54
I/jxcore-log( 3002): 
I/jxcore-log( 3002): - Peer ID : 00:F4:6F:30:E0:6C
I/jxcore-log( 3002): 
I/jxcore-log( 3002): - Peer ID : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3002): 
I/jxcore-log( 3002): - Peer ID : 7C:F9:0E:37:96:AB
I/jxcore-log( 3002): 
I/jxcore-log( 3002): - Peer ID : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3002): 
I/jxcore-log( 3002): - Peer ID : 7C:F9:0E:34:8A:A0
I/jxcore-log( 3002): 
I/jxcore-log( 3002): - Peer ID : 34:FC:EF:11:B1:66
I/jxcore-log( 3002): 
I/jxcore-log( 3002): - Peer ID : E0:DB:10:1F:C9:5E
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:12:37.186Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:12:37.186Z SendDataConnector.js: Stop retry timer
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:12:37.187Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3002): 
I/jxcore-log( 3002): 2015-11-30T11:12:37.187Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3002): 
,I/chromium( 3002): [INFO:CONSOLE(63)] "logCallback *** TIMEOUT ***", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3002): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4218b34 rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): invalid rfc slot id: 38
,I/BtToSocketBase( 3002): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3002): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3002): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT1191
I/BtToSocketBase( 3002): Stop ReceivingThread
I/BtToSocketBase( 3002): Stop SendingThread
I/BtToSocketBase( 3002): Close local in
I/BtToSocketBase( 3002): Close LocalOutputStream
I/BtToSocketBase( 3002): Close localHostSocket
I/BtToSocketBase( 3002): Close bt in
I/BtToSocketBase( 3002): Close bt out
I/BtToSocketBase( 3002): Close bt socket
,I/BtToSocketBase( 3002): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3002): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3002): 2015-11-30T11:12:37.783Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3002): 
,W/bt-rfcomm( 3052): rfc_find_lcid_mcb LCID reused LCID:0x4e current:0x0
W/bt-rfcomm( 3052): RFCOMM_DisconnectInd LCID:0x4e
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4218cfc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4218b34 rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: HTC One_M8
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa4218b34 rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: Note4-1
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: G3s-1
,W/bt-btif ( 3052): invalid rfc slot id: 37
,I/BtToSocketBase( 3002): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3002): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3002): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT9998
I/BtToSocketBase( 3002): Stop ReceivingThread
I/BtToSocketBase( 3002): Stop SendingThread
I/BtToSocketBase( 3002): Close local in
I/BtToSocketBase( 3002): Close LocalOutputStream
I/BtToSocketBase( 3002): Close localHostSocket
I/BtToSocketBase( 3002): Close bt in
I/BtToSocketBase( 3002): Close bt out
I/BtToSocketBase( 3002): Close bt socket
,I/BtToSocketBase( 3002): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3002): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3002): 2015-11-30T11:12:41.595Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3002): 
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa421908c rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3052): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
W/bt-rfcomm( 3052): RFCOMM_DisconnectInd LCID:0x4c
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1355): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1355): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/EventLogService( 1614): Aggregate from 1448880092326 (log), 1448880092326 (data)
,I/art     ( 1614): Explicit concurrent mark sweep GC freed 25738(1692KB) AllocSpace objects, 18(288KB) LOS objects, 24% free, 22MB/29MB, paused 469us total 32.574ms
,I/jxcore-log( 3002): DBG, CoordinatorConnector command called
I/jxcore-log( 3002): 
I/jxcore-log( 3002): command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): stop tests now !
I/jxcore-log( 3002): 
I/jxcore-log( 3002): stop current!
I/jxcore-log( 3002): 
I/jxcore-log( 3002): testSendData stopped
I/jxcore-log( 3002): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Shutting down...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:91)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Socket is null
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onIncomingConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3002): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3002): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): setState: INITIALIZED
,I/jxcore-log( 3002): StopBroadcasting went ok
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): 2015-11-30T11:15:57.286Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3002): 
I/chromium( 3002): [INFO:CONSOLE(63)] "logCallback stop", source: file:///android_asset/www/js/thali_main.js (63)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onConnectionFailed: Socket is null
,W/jxcore-log( 3002): $$jxcore_callback_38 wasn't registered
W/jxcore-log( 3002): 
,W/jxcore-log( 3002): $$jxcore_callback_38 wasn't registered
W/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector command called
I/jxcore-log( 3002): 
I/jxcore-log( 3002): command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"80:01:84:8A:B3:68\",\"time\":7757,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[{\"connections\":1,\"name\":\"50:2E:6C:AC:21:50\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"08:EC:A9:50:75:41\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"44:80:EB:7B:5A:05\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"58:2A:F7:ED:96:BE\",\"time\":0,\"result\":\"Fail\"}],\"notTriedList\":[{\"connections\":0,\"name\":\"F8:CF:C5:D9:E5:61\",\"time\":0,\"result\":\"Fail\"},{\"connections\":0,\"name\":\"34:FC:EF:9D:93:0B\",\"time\":0,\"result\":\"Fail\"},{\"connections\":0,\"name\":\"7C:F9:0E:51:18:22\",\"time\":0,\"result\":\"Fail\"},{\"connections\":0,\"name\":\"B0:C5:59:3F:75:69\",\"time\":0,\"result\":\"Fail\"},{\"connections\":0,\"name\":\"08:EC:A9:50:76:27\",\"time\":
I/jxcore-log( 3002): ****TEST TOOK:  ms ****
I/jxcore-log( 3002): 
I/jxcore-log( 3002): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3002): 
I/jxcore-log( 3002): stop tests now !
I/jxcore-log( 3002): 
I/jxcore-log( 3002): end, event received
I/jxcore-log( 3002): 
I/jxcore-log( 3002): CoordinatorConnector close called
I/jxcore-log( 3002): 
,I/jxcore-log( 3002): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3002): 
I/jxcore-log( 3002): The Coordinator has disconnected!
I/jxcore-log( 3002): 
I/jxcore-log( 3002): The Coordinator has closed!
I/jxcore-log( 3002): 
I/jxcore-log( 3002): stop tests now !
I/jxcore-log( 3002): 
I/jxcore-log( 3002): turning Radios off
I/jxcore-log( 3002): 
I/jxcore-log( 3002): Toggling radios to false
I/jxcore-log( 3002): 
D/BluetoothManagerService(  756): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  756): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@180fc5db mBinding = false
,D/BluetoothManagerService(  756): Message: 2
,D/BluetoothManagerService(  756): Sending off request.
,D/BluetoothAdapterState( 3052): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3052): Setting state to 13
I/BluetoothAdapterState( 3052): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterProperties( 3052): onBluetoothDisable()
I/BluetoothAdapterState( 3052): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 3052): Scan Mode:20
,D/BluetoothAdapterState( 3052): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,V/BluetoothMapMasInstance( 3052): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3052): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3052): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 3052): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 3052): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 3052): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3052): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3052): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/BtOppRfcommListener( 3052): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,W/bt-btif ( 3052): bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
W/bt-l2cap( 3052): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3052): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothManagerService(  756): Message: 60
D/BluetoothManagerService(  756): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  756): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 3052): onReceive
D/BluetoothMapService( 3052): STATE_TURNING_OFF
V/BluetoothMapService( 3052): Handler(): got msg=4
D/BluetoothMapService( 3052): MAP Service closeService in
D/BluetoothMapMasInstance( 3052): MAP Service shutdown
V/BluetoothMapService( 3052): MAP Service closeService out
,I/BtOppRfcommListener( 3052): stopping Accept Thread
,I/BtOppRfcommListener( 3052): BluetoothSocket listen thread finished
,D/WifiService(  756): setWifiEnabled: false pid=3002, uid=10270
E/WifiService(  756): Invoking mWifiStateMachine.setWifiEnabled
,W/ContextImpl( 3090): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver( 3090): finishStartingService: stopping service
I/jxcore-log( 3002): Radios toggled
I/jxcore-log( 3002): 
I/chromium( 3002): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onBluetoothAdapterScanModeChanged: Mode changed to 20
E/WifiStateMachine(  756): WifiStateMachine: Leaving Connected state
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onBluetoothAdapterScanModeChanged: Bluetooth disabled, stopping...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): stop: Stopping Bluetooth and peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): setState: WAITING_FOR_SERVICES_TO_BE_ENABLED
E/WifiConfigStore(  756): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  756): do suspend true
,D/AuthorizationBluetoothService( 1400): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothPbap( 3090): Proxy object disconnected
D/PbapServerProfile( 3090): Bluetooth service disconnected
W/bt-btif ( 3052): ag scb idx 1 not allocated
E/bt-btif ( 3052): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3052): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 3052): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3052): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3052): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3052): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3052): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial( 3052): RX termination
W/bt_userial( 3052): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 3052): Leaving userial_read_thread()
D/bt_userial( 3052): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 3052): hw_epilog_process
I/bt_userial_vendor( 3052): device fd = 53 close
,I/GKI_LINUX( 3052): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 3052): GKI_exit_task 0 done
I/GKI_LINUX( 3052): GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 3052): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/HeadsetService( 3052): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3052): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3122e54e
,D/HeadsetStateMachine( 3052): Exit Disconnected: -1
,D/BluetoothHeadset( 1174): Proxy object disconnected
D/BluetoothHeadset( 1174): Proxy object disconnected
D/BluetoothHeadset(  756): Proxy object disconnected
,D/BluetoothHeadset( 1210): Proxy object disconnected
,D/BluetoothAdapterState( 3052): Stopping profile services that were post enabled
,D/BluetoothHeadset( 3090): Proxy object disconnected
D/HeadsetProfile( 3090): Bluetooth service disconnected
D/A2dpService( 3052): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3052): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3122e54e
D/A2dpStateMachine( 3052): Exit Disconnected: -1
,D/BluetoothA2dp(  756): Proxy object disconnected
,D/HidService( 3052): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3052): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3122e54e
,D/HeadsetStateMachine( 3052): Unbinding service...
,W/BluetoothHeadsetServiceJni( 3052): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3052): Cleaning up Bluetooth Handsfree callback object
D/HealthService( 3052): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3052): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3122e54e
D/PanService( 3052): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3052): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3122e54e
D/BtGatt.DebugUtils( 3052): handleDebugAction() action=null
D/BtGatt.GattService( 3052): Received stop request...Stopping profile...
D/BtGatt.GattService( 3052): stop()
D/BtGatt.AdvertiseManager( 3052): advertise clients cleared
D/BluetoothAdapterService( 3052): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3122e54e
D/BluetoothMapService( 3052): Received stop request...Stopping profile...
D/BluetoothMapService( 3052): stop()
,D/BluetoothMapEmailAppObserver( 3052): deinitObservers()
D/BluetoothMapEmailAppObserver( 3052): removeReceiver()
,D/BluetoothAdapterService( 3052): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3122e54e
,I/GKI_LINUX( 3052): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 3052): GKI_exit_task 2 done
I/GKI_LINUX( 3052): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 3052): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3052): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3052): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3052): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3052): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3052): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3052): Cleaning up Bluetooth PAN callback object
,V/BluetoothMapService( 3052): Handler(): got msg=4
D/BluetoothMapService( 3052): MAP Service closeService in
V/BluetoothMapService( 3052): MAP Service closeService out
,V/NativeCrypto( 1400): Read error: ssl=0x9ca5f200: I/O error during system call, Connection timed out
,D/BluetoothAdapterState( 3052): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3052): Setting state to 10
I/BluetoothAdapterState( 3052): Bluetooth adapter state changed: 13-> 10
,D/ConnectivityService(  756): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiConfigStore(  756): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  756): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiStateMachine(  756): scanCount==0 - aborting
,D/BluetoothManagerService(  756): Message: 60
D/BluetoothManagerService(  756): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  756): Broadcasting onBluetoothStateChange(false) to 11 receivers.
D/BluetoothMapService( 3052): cleanup()
D/BluetoothMapService( 3052): MAP Service closeService in
V/BluetoothMapService( 3052): MAP Service closeService out
,D/BluetoothInputDevice( 3090): Proxy object disconnected
D/HidProfile( 3090): Bluetooth service disconnected
,I/BluetoothAdapterState( 3052): Entering OffState
,D/BluetoothHeadset( 3090): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1174): onBluetoothStateChange: up=false
,D/BluetoothHeadset(  756): onBluetoothStateChange: up=false
D/BluetoothA2dp(  756): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1174): onBluetoothStateChange: up=false
,D/BluetoothPbap( 3090): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1210): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 3090): Proxy object disconnected
D/A2dpProfile( 3090): Bluetooth service disconnected
,V/NativeCrypto( 1400): SSL shutdown failed: ssl=0x9ca5f200: I/O error during system call, Broken pipe
D/WifiNetworkAgent(  756): NetworkAgent: NetworkAgent channel lost
E/native  (  756): do suspend true
D/WifiScanningService(  756): SCAN_AVAILABLE : 1
D/RttService(  756): SCAN_AVAILABLE : 1
,D/RttService(  756): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  756): StartedState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  756): DefaultState
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3002): onWifiStateChanged: State changed to 1
,D/BluetoothA2dp( 3090): onBluetoothStateChange: up=false
,D/ConnectivityService(  756): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,D/BluetoothMap( 3090): onBluetoothStateChange: up=false
D/BluetoothMap( 3090): Proxy object disconnected
,D/MapProfile( 3090): Bluetooth service disconnected
D/BluetoothInputDevice( 3090): onBluetoothStateChange: up=false
,D/BluetoothManagerService(  756): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  756): Broadcasting onBluetoothServiceDown() to 11 receivers.
,D/BluetoothManagerService(  756): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@180fc5db mBinding = false
,D/BluetoothManagerService(  756): Sending unbind request.
,D/BluetoothManagerService(  756): Bluetooth State Change Intent: 13 -> 10
,D/AndroidRuntime( 3817): 
D/AndroidRuntime( 3817): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/BluetoothAdapter(  895): 377008931: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  895): 377008931: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  895): 377008931: getState() :  mService = null. Returning STATE_OFF
D/AndroidRuntime( 3817): CheckJNI is OFF
E/BluetoothAdapterService(824370510)( 3052): Repeated wake lock release; aborting release: bluedroid_timer
I/GKI_LINUX( 3052): gki_task task_id=1 [BTIF] terminating
E/GKI_LINUX( 3052): alarm_service_reschedule unable to release wake lock with no timers: 1
I/GKI_LINUX( 3052): GKI_exit_task 1 done
I/GKI_LINUX( 3052): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3052): cleanupNative: return from cleanup
I/art     ( 3052): System.exit called, status: 0
I/AndroidRuntime( 3052): VM exiting with result code 0, cleanup skipped.
W/ContextImpl( 3090): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/CommandListener(  179): Clearing all IP addresses on wlan0
D/ConnectivityService(  756): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/Nat464Xlat(  756): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  756): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Disconnected - quitting
D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler(  895): CM callback handler got msg 524292
D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1614): CM callback handler got msg 524292
D/BluetoothAdapter( 1303): 436503203: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1303): 436503203: getState() :  mService = null. Returning STATE_OFF
D/ConnectivityService(  756): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1210): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/AndroidRuntime( 3817): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  756): Process com.android.bluetooth (pid 3052) has died
,I/wpa_supplicant( 3083): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 3083): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,W/PackageSettings(  756): Skipping PackageSetting{38d1e411 com.example.hello/10277} due to missing metadata
,I/ActivityManager(  756): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  756): Killing 3002:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  756): WIN DEATH: Window{114bff44 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  756): Client connection lost with reason: 4
,D/Tethering(  756): InitialState.processMessage what=4
,I/wpa_supplicant( 3083): wlan0: CTRL-EVENT-TERMINATING 
,I/ActivityManager(  756):   Force finishing activity ActivityRecord{15836550 u0 com.test.thalitest/.MainActivity t214}
,I/ActivityManager(  756): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/ActivityManager(  756):   Force finishing activity ActivityRecord{15836550 u0 com.test.thalitest/.MainActivity t214 f}
,W/ActivityManager(  756): Duplicate finish request for ActivityRecord{15836550 u0 com.test.thalitest/.MainActivity t214 f}
,W/ActivityManager(  756): Spurious death for ProcessRecord{ee7fb8d 3002:com.test.thalitest/u0a270}, curProc for 3002: null
D/Tethering(  756): sendTetherStateChangedBroadcast 0, 0, 0
,I/InputReader(  756): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1303): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1066): resetDictionaries() : en_US
,W/Settings( 1848): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/DockEventReceiver( 3090): finishStartingService: stopping service
,I/Keyboard.Facilitator.DecoderInitializer( 1066): run()
I/Decoder ( 1066): createOrResetDecoder
,I/art     ( 1231): Explicit concurrent mark sweep GC freed 3952(294KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 582us total 41.856ms
,I/art     ( 1355): Explicit concurrent mark sweep GC freed 60480(2MB) AllocSpace objects, 11(176KB) LOS objects, 25% free, 19MB/25MB, paused 307us total 56.635ms
,I/LibraryLoader( 1459): Loading chrome directly from within /data/app/com.android.chrome-1/base.apk
,D/BluetoothAdapter( 3090): 1050173443: getState() :  mService = null. Returning STATE_OFF
,W/Settings( 1303): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/art     (  756): Explicit concurrent mark sweep GC freed 30223(1862KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 2.163ms total 101.063ms
,I/art     (  756): WaitForGcToComplete blocked for 95.745ms for cause Explicit
,I/ActivityManager(  756): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=3876 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/LibraryLoader( 1459): Time to load native libraries: 80 ms (timestamps 5580-5660)
I/LibraryLoader( 1459): Expected native library version number "44.0.2403.133",actual native library version number "44.0.2403.133"
,I/chromium( 1459): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,W/art     ( 1459): Attempt to remove local handle scope entry from IRT, ignoring
I/ConfigService( 1400): onCreate
W/art     ( 1459): Attempt to remove local handle scope entry from IRT, ignoring
,I/OpenGLRenderer(  943): Initialized EGL, version 1.4
,D/OpenGLRenderer(  943): Enabling debug mode 0
,D/BackupManagerService(  756): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  756): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  756): removeObsoleteFile: deleting file=214_task.xml
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1066): run()
,W/ResourcesManager( 3876): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/InputMethodManagerService(  756): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@19c43081 (uid=10034 pid=943)
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1066): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1066): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1066): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1066): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1066): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1066): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1066): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1066): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1066): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1066): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1066): run()
I/StatsUtilsManager( 1066): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1066): shouldRecordStats() = Too Soon
,I/art     (  756): Explicit concurrent mark sweep GC freed 9203(492KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 2.033ms total 151.485ms
,D/AdapterServiceConfig( 3876): Adding HeadsetService
D/AdapterServiceConfig( 3876): Adding A2dpService
D/AdapterServiceConfig( 3876): Adding HidService
D/AdapterServiceConfig( 3876): Adding HealthService
D/AdapterServiceConfig( 3876): Adding PanService
D/AdapterServiceConfig( 3876): Adding GattService
D/AdapterServiceConfig( 3876): Adding BluetoothMapService
,I/ActivityManager(  756): Killing 1491:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,I/Launcher( 1231): Deferring update until onResume
,W/ResourcesManager( 1231): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1231): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1231): Deferring update until onResume
,D/AuthorizationBluetoothService( 1400): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/libprocessgroup(  756): failed to open /acct/uid_10013/pid_1491/cgroup.procs: No such file or directory
,D/AndroidRuntime( 3817): Shutting down VM
,D/BluetoothAdapter( 3090): 1050173443: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager(  756): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=3908 uid=10004 gids={50004, 9997} abi=armeabi-v7a
,D/VoicemailCleanupService( 3908): Cleaning up data for package: com.test.thalitest
,I/UpdateIcingCorporaServi( 1355): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/Launcher( 1231): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3122e54e new=com.google.android.velvet.VelvetApplication@3122e54e
,I/ActivityManager(  756): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3932 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ContactLocale( 3908): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  756): Killing 2791:com.android.defcontainer/u0a5 (adj 15): empty #17
,W/libprocessgroup(  756): failed to open /acct/uid_10005/pid_2791/cgroup.procs: No such file or directory
,W/ContextImpl( 3932): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,I/UpdateIcingCorporaServi( 1355): UpdateCorporaTask done [took 153 ms] updated apps [took 153 ms] 
,D/PackageBroadcastService( 1614): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1614): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1614): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1614): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1614): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1614): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1614): Removing dialog suppression flag for package com.test.thalitest
,E/NetworkScheduler.SchedulerReceiver( 1400): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1400): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,E/SQLiteLog( 1614): (3850) statement aborts at 151: [DELETE FROM FileContent154 WHERE hash IN WipeoutFileContentHashView AND hash NOT IN ()] disk I/O error
,W/FileUtils( 1614): Failed to chmod(/data/data/com.google.android.gms/databases/phenotype.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,E/DocListDatabase( 1614): Failed to delete from FileContent154 table
E/DocListDatabase( 1614): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 1614): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 1614): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 1614): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 1614): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 1614): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DocListDatabase( 1614): 	at com.google.android.gms.drive.database.k.a(SourceFile:329)
E/DocListDatabase( 1614): 	at com.google.android.gms.drive.database.f.a(SourceFile:984)
E/DocListDatabase( 1614): 	at com.google.android.gms.drive.b.e.run(SourceFile:74)
E/DocListDatabase( 1614): 	at com.google.android.gms.drive.j.ag.run(SourceFile:51)
E/DocListDatabase( 1614): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DocListDatabase( 1614): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DocListDatabase( 1614): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteDatabase( 1614): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1614): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1614): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1614): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1614): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1614): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1614): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1614): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1614): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1614): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1614): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1614): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1614): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1614): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1614): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1614): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1614): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteDatabase( 1614): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1614): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1614): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1614): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1614): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1614): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1614): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1614): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1614): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1614): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1614): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1614): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1614): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1614): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1614): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1614): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1614): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1614): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteOpenHelper( 1614): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1614): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1614): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1614): 	at com.google.android.g,ms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1614): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1614): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1614): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1614): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1614): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1614): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1614): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 1614): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/SQLiteOpenHelper( 1614): Opened metrics.db in read-only mode
E/GAv4-SVC( 1614): Failed to update Analytics property: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
D/gH_CompatibleDatabase( 1614): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1614): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SharedPreferencesImpl( 1614): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteLog( 1614): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 1614): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
E/SharedPreferencesImpl( 1614): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4-SVC( 1614): Job execution failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
E/SharedPreferencesImpl( 1614): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteLog( 1614): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/GAv4-SVC( 1614): Failed to update Analytics property: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SharedPreferencesImpl( 1614): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
I/ActivityManager(  756): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3967 uid=10039 gids={50039, 9997} abi=armeabi-v7a
E/GAv4-SVC( 1614): Job execution failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
E/SharedPreferencesImpl( 1614): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/BaseAppContext( 1614): Using Auth Proxy for data requests.
,W/BaseAppContext( 1614): Using Auth Proxy for data requests.
,E/SQLiteDatabase( 1614): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 1614): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1614): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1614): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1614): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1614): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1614): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1614): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1614): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1614): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1614): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1614): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1614): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1614): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1614): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1614): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
E/SQLiteDatabase( 1614): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/SQLiteDatabase( 1614): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/SQLiteDatabase( 1614): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/SQLiteDatabase( 1614): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/SQLiteDatabase( 1614): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/SQLiteDatabase( 1614): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1614): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1614): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/SQLiteDatabase( 1614): 	at java.lang.Thread.run(Thread.java:818)
E/ClearPendingStateOp( 1614): Runtime exception while performing operation
E/ClearPendingStateOp( 1614): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 1614): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 1614): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/ClearPendingStateOp( 1614): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/ClearPendingStateOp( 1614): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 1614): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 1614): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 1614): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/ClearPendingStateOp( 1614): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/ClearPendingStateOp( 1614): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/ClearPendingStateOp( 1614): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/ClearPendingStateOp( 1614): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/ClearPendingStateOp( 1614): 	at android.database.sqlite.SQLiteOpenHel,per.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearPendingStateOp( 1614): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearPendingStateOp( 1614): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
E/ClearPendingStateOp( 1614): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/ClearPendingStateOp( 1614): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/ClearPendingStateOp( 1614): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 1614): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 1614): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/ClearPendingStateOp( 1614): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 1614): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 1614): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 1614): 	at java.lang.Thread.run(Thread.java:818)
F/ClearPendingStateOp( 1614): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1614): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 1614): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 1614): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
F/ClearPendingStateOp( 1614): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
F/ClearPendingStateOp( 1614): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 1614): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 1614): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 1614): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
F/ClearPendingStateOp( 1614): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
F/ClearPendingStateOp( 1614): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
F/ClearPendingStateOp( 1614): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
F/ClearPendingStateOp( 1614): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
F/ClearPendingStateOp( 1614): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
F/ClearPendingStateOp( 1614): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
F/ClearPendingStateOp( 1614): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
F/ClearPendingStateOp( 1614): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
F/ClearPendingStateOp( 1614): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
F/ClearPendingStateOp( 1614): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 1614): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 1614): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
F/ClearPendingStateOp( 1614): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 1614): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 1614): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 1614): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1614): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/GAv4-SVC( 1614): Sync local dispatch failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
E/SharedPreferencesImpl( 1614): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/DropBoxManagerService(  756): Can't write: system_app_wtf
E/DropBoxManagerService(  756): java.io.FileNotFoundException: /data/system/dropbox/drop95.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  756): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  756): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  756): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  756): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  756): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  756): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  756): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  756): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  756): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  756): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  756): 	... 5 more
--------- beginning of crash
E/AndroidRuntime( 1614): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 1614): Process: com.google.android.gms, PID: 1614
E/AndroidRuntime( 1614): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 1614): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1614): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1614): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1614): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1614): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1614): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 1614): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 1614): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1614): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1614): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1614): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 1614): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/GAv4-SVC( 1614): Sync local dispatch failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
E/SharedPreferencesImpl( 1614): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
I/Process ( 1614): Sending signal. PID: 1614 SIG: 9
E/DropBoxManagerService(  756): Can't write: system_app_crash
E/DropBoxManagerService(  756): java.io.FileNotFoundException: /data/system/dropbox/drop96.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  756): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  756): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  756): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  756): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  756): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  756): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  756): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  756): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  756): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  756): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  756): 	... 5 more

```
