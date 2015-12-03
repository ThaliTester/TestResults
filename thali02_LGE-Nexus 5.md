#### Test 5253548629578ed_thali02_LGE-Nexus 5 Logs


```
--------- beginning of system
W/ResourcesManager( 2918): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 2918): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
--------- beginning of main
D/Finsky  ( 2432): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
I/ActivityManager(  733): Killing 2132:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
I/art     ( 1381): Explicit concurrent mark sweep GC freed 10166(584KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 19MB/32MB, paused 696us total 20.874ms
W/libprocessgroup(  733): failed to open /acct/uid_1000/pid_2132/cgroup.procs: No such file or directory
V/JNIHelp ( 2918): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
W/System  ( 2918): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2918): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 2975): 
D/AndroidRuntime( 2975): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2975): CheckJNI is OFF
D/AndroidRuntime( 2975): Calling main entry com.android.commands.am.Am
I/ActivityManager(  733): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/Icing   ( 1561): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/ActivityManager(  733): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2996 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2975): Shutting down VM
D/Icing   ( 1561): Loaded CLD2 Version V2.0 - 20141016
V/ActivityManager(  733): Display changed displayId=0
I/Icing   ( 1561): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/WebViewFactory( 2996): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2996): Time to load native libraries: 2 ms (timestamps 839-841)
I/LibraryLoader( 2996): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2996): Binding Chromium to main looper Looper (main, tid 1) {1e6db3e4}
I/LibraryLoader( 2996): Expected native library version number "",actual native library version number ""
I/chromium( 2996): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2996): Initializing chromium process, singleProcess=true
W/art     ( 2996): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2996): ApplicationContext is null in ApplicationStatus
W/chromium( 2996): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 2996): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 2996): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2996): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 2996): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  733): Message: 20
D/BluetoothManagerService(  733): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a5cc56f:true
,D/BluetoothAdapter( 2996): 844681839: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 2996): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2996): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2996): CordovaWebView is running on device made by: LGE
,W/art     ( 2996): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2996): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2996): Render dirty regions requested: true
,D/Atlas   ( 2996): Validating map...
,W/chromium( 2996): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2996): Initialized EGL, version 1.4
D/OpenGLRenderer( 2996): Enabling debug mode 0
,I/ActivityManager(  733): Displayed com.test.thalitest/.MainActivity: +428ms (total +56s183ms)
,W/IInputConnectionWrapper( 2996): showStatusIcon on inactive InputConnection
,W/BindingManager( 2996): Cannot call determinedVisibility() - never saw a connection for the pid: 2996
,D/JsMessageQueue( 2996): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 2996): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
,D/JX-Cordova( 2996): jxcore cordova android initializing
,I/ActivityManager(  733): Killing 2226:com.google.android.youtube/u0a80 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10080/pid_2226/cgroup.procs: No such file or directory
,W/jxcore-log( 2996): Initializing JXcore engine
W/jxcore-log( 2996): JXcore engine is ready
W/jxcore-log( 2996): Starting JXcore engine
W/.test.thalitest( 2996): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8024]" dev="sockfs" ino=8024 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 2996): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 2996): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[10250]" dev="sockfs" ino=10250 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 2996): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18681]" dev="sockfs" ino=18681 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 2996): Platform android
W/jxcore-log( 2996): 
W/jxcore-log( 2996): Process ARCH arm
W/jxcore-log( 2996): 
,I/jxcore-log( 2996): JXcore Cordova bridge is ready!
I/jxcore-log( 2996): 
W/jxcore-log( 2996): JXcore engine is started
,I/Choreographer( 2996): Skipped 114 frames!  The application may be doing too much work on its main thread.
,I/chromium( 2996): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 2996): Toggling radios to true
I/jxcore-log( 2996): 
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  733): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  733): Message: 1
D/BluetoothManagerService(  733): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  733): setWifiEnabled: true pid=2996, uid=10270
,E/WifiService(  733): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  733): New client listening to asynchronous messages
,D/SoftapController(  181): Softap fwReload - Ok
,I/jxcore-log( 2996): Radios toggled
I/jxcore-log( 2996): 
,I/ActivityManager(  733): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3056 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/CommandListener(  181): Setting iface cfg
D/CommandListener(  181): Trying to bring down wlan0
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,W/ResourcesManager( 3056): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/AdapterServiceConfig( 3056): Adding HeadsetService
D/AdapterServiceConfig( 3056): Adding A2dpService
D/AdapterServiceConfig( 3056): Adding HidService
D/AdapterServiceConfig( 3056): Adding HealthService
D/AdapterServiceConfig( 3056): Adding PanService
D/AdapterServiceConfig( 3056): Adding GattService
D/AdapterServiceConfig( 3056): Adding BluetoothMapService
,D/BluetoothManagerService(  733): Message: 20
D/BluetoothManagerService(  733): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@38249d62:true
,I/wpa_supplicant( 3073): Successfully initialized wpa_supplicant
,D/BluetoothAdapterState( 3056): make
,I/bluedroid( 3056): init
,I/BluetoothAdapterState( 3056): Entering OffState
,I/bte_conf( 3056): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3056): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,E/bt_osi_config( 3056): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3056): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3056): get_profile_interface socket
,I/bluedroid( 3056): get_profile_interface map_client
,I/GKI_LINUX( 3056): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothManagerService(  733): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  733): Message: 40
D/BluetoothManagerService(  733): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 3056): config_hci_snoop_log
,D/BluetoothManagerService(  733): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  733): Broadcasting onBluetoothServiceUp() to 9 receivers.
,D/BluetoothAdapterState( 3056): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3056): Setting state to 11
I/BluetoothAdapterState( 3056): Bluetooth adapter state changed: 10-> 11
,D/BluetoothBondStateMachine( 3056): make
,D/BluetoothManagerService(  733): Message: 60
D/BluetoothManagerService(  733): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  733): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothAdapterProperties( 3056): Address is:34:FC:EF:11:AE:67
,I/BluetoothBondStateMachine( 3056): StableState(): Entering Off State
,I/wpa_supplicant( 3073): rfkill: Cannot open RFKILL control device
,I/ActivityManager(  733): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=3080 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/BluetoothAdapterProperties( 3056): Name is: Nexus 5
,D/WifiMonitor(  733): startMonitoring(wlan0) with mConnected = false
,D/BluetoothManagerService(  733): Bluetooth Adapter name changed to Nexus 5
,D/BluetoothManagerService(  733): Stored Bluetooth name: Nexus 5
,D/BluetoothHeadset(  733): Proxy object connected
,D/BluetoothHeadset( 1186): Proxy object connected
,D/BluetoothHeadset( 1226): Proxy object connected
,D/BluetoothHeadset( 1186): Proxy object connected
,D/HeadsetService( 3056): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3056): classInitNative: succeeds
,D/HeadsetStateMachine( 3056): make
,I/BluetoothAdapterState( 3056): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetStateMachine( 3056): max_hf_connections = 1
,I/bluedroid( 3056): get_profile_interface handsfree
D/HeadsetStateMachine( 3056): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 3056): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27dd404d
,D/BluetoothA2dp(  733): Proxy object connected
D/A2dpService( 3056): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni( 3056): classInitNative: succeeds
I/bluedroid( 3056): get_profile_interface avrcp
,E/RemoteController( 3056): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3056): classInitNative: succeeds
,D/A2dpStateMachine( 3056): make
,I/bluedroid( 3056): get_profile_interface a2dp
,I/GKI_LINUX( 3056): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothAdapterService( 3056): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27dd404d
I/BluetoothHidServiceJni( 3056): classInitNative: succeeds
D/A2dpStateMachine( 3056): Enter Disconnected: -2
,D/HidService( 3056): Received start request. Starting profile...
I/bluedroid( 3056): get_profile_interface hidhost
D/BluetoothAdapterService( 3056): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27dd404d
I/BluetoothHealthServiceJni( 3056): classInitNative: succeeds
,D/HealthService( 3056): Received start request. Starting profile...
,I/bluedroid( 3056): get_profile_interface health
D/BluetoothAdapterService( 3056): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27dd404d
,I/BluetoothPanServiceJni( 3056): classInitNative(L105): succeeds
,I/ActivityManager(  733): Killing 2338:com.google.android.deskclock/u0a38 (adj 15): empty #17
,D/PanService( 3056): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3056): initializeNative(L110): pan
I/bluedroid( 3056): get_profile_interface pan
,D/BluetoothAdapterService( 3056): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27dd404d
I/BtGatt.JNI( 3056): classInitNative(L863): classInitNative: Success!
D/BtGatt.DebugUtils( 3056): handleDebugAction() action=null
,D/BtGatt.GattService( 3056): Received start request. Starting profile...
D/BtGatt.GattService( 3056): start()
I/bluedroid( 3056): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 3056): advertise manager created
,W/libprocessgroup(  733): failed to open /acct/uid_10038/pid_2338/cgroup.procs: No such file or directory
,D/BluetoothAdapterService( 3056): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27dd404d
,V/BluetoothMapService( 3056): BluetoothMapBinder()
,D/BluetoothMapService( 3056): Received start request. Starting profile...
,D/BluetoothMapService( 3056): start()
,D/BluetoothMapEmailSettingsLoader( 3056): Found 0 applications
,D/BluetoothMapEmailAppObserver( 3056): createReceiver()
D/BluetoothMapEmailAppObserver( 3056): initObservers()
D/BluetoothMapEmailAppObserver( 3056): getEnabledAccountItems()
D/BluetoothAdapterService( 3056): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27dd404d
D/HeadsetStateMachine( 3056): Proxy object connected
V/BluetoothMapService( 3056): Handler(): got msg=1
D/HeadsetStateMachine( 3056): Disconnected process message: 10, size: 0
,D/HeadsetPhoneState( 3056): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/BluetoothAdapterState( 3056): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3056): enable
D/HeadsetStateMachine( 3056): Disconnected process message: 11, size: 0
I/bt_hci_bdroid( 3056): init
I/bt_vendor( 3056): init
I/bt_vnd_conf( 3056): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3056): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3056): userial_init
I/GKI_LINUX( 3056): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3056): btu_task pending for preload complete event
,D/WifiService(  733): New client listening to asynchronous messages
,D/AuthorizationBluetoothService( 1381): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/bt_userial_vendor( 3056): userial vendor open: opening /dev/ttyHS99
,I/ActivityManager(  733): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3129 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/bt_userial_vendor( 3056): device fd = 53 open
D/bt_userial( 3056): Entering userial_read_thread()
,I/bt_hwcfg( 3056): bt vendor lib: set UART baud 4000000
,D/bt_hwcfg( 3056): Chipset BCM4335C0
D/bt_hwcfg( 3056): Target name = [BCM4335C0]
I/bt_hwcfg( 3056): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,D/Tethering(  733): sendTetherStateChangedBroadcast 1, 0, 0
,I/ActivityManager(  733): Killing 2389:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,I/wpa_supplicant( 3073): rfkill: Cannot open RFKILL control device
,W/libprocessgroup(  733): failed to open /acct/uid_10069/pid_2389/cgroup.procs: No such file or directory
,I/wpa_supplicant( 3073): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiConfigStore(  733): Loading config and enabling all networks 
,E/WifiConfigStore(  733): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  733): Setting external_sim to 1
,D/WifiStateMachine(  733): Setting OUI to DA-A1-19
I/WifiNative-HAL(  733): startHal
,D/wifi    (  733): setting scan oui 0xa02f39b8
D/WifiHAL (  733): Sending mac address OUI
E/WifiHAL (  733): failed to set scanning mac OUI; result = -95
,W/Settings( 1797): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/native  (  733): do suspend true
,D/CommandListener(  181): Setting iface cfg
D/CommandListener(  181): Trying to bring up p2p0
,D/WifiMonitor(  733): startMonitoring(p2p0) with mConnected = true
D/WifiScanningService(  733): SCAN_AVAILABLE : 3
D/RttService(  733): SCAN_AVAILABLE : 3
D/WifiScanningService(  733): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  733): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  733): startHal
,D/wifi    (  733): getting scan capabilities on interface[1] = 0xa02f39b8
D/WifiHAL (  733): Creating message to get scan capablities; iface = 21
D/WifiHAL (  733): In GetCapabilities::handleResponse
D/WifiHAL (  733): Id = 0, subcmd = 0, len = 28, expected len = 32
,D/WifiScanningService(  733): StartedState
,I/wpa_supplicant( 3073): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,D/WifiNative-HAL(  733): p2pGetDeviceAddress
D/WifiNative-HAL(  733): p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,I/bt_hwcfg( 3056): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 3056): Settlement delay -- 100 ms
,I/bt_hwcfg( 3056): Setting fw settlement delay to 100 
,I/bt_hwcfg( 3056): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 3056): Setting local bd addr to 34:FC:EF:11:AE:67
,I/bt_hwcfg( 3056): vendor lib fwcfg completed
,I/bt-btu  ( 3056): btu_task received preload complete event
,I/        ( 3056): BTE_InitTraceLevels -- TRC_HCI
,I/        ( 3056): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3056): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3056): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3056): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3056): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3056): BTE_InitTraceLevels -- TRC_BNEP
,I/        ( 3056): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3056): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3056): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3056): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3056): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3056): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3056): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3056): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 3056): BTM_SecRegister:p_cb_info->p_le_callback == 0xa40639d5 
E/bt-btm  ( 3056): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa40639d5 
,E/bt-btif ( 3056): Calling BTA_HhEnable
E/bt-btif ( 3056): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3056): Address is:34:FC:EF:11:AE:67
,D/BluetoothManagerService(  733): Bluetooth Adapter name changed to Nexus 5
,D/BluetoothAdapterProperties( 3056): Name is: Nexus 5
,D/BluetoothAdapterProperties( 3056): Scan Mode:20
D/BluetoothAdapterProperties( 3056): Discoverable Timeout:120
,D/BluetoothManagerService(  733): Stored Bluetooth name: Nexus 5
,D/bte_conf( 3056): Device ID record 1 : primary
D/bte_conf( 3056):   vendorId            = 000f
D/bte_conf( 3056):   vendorIdSource      = 0001
D/bte_conf( 3056):   product             = 1200
D/bte_conf( 3056):   version             = 1436
D/bte_conf( 3056):   clientExecutableURL = 
D/bte_conf( 3056):   serviceDescription  = 
D/bte_conf( 3056):   documentationURL    = 
D/bte_conf( 3056): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 3056): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 3056): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3056): ScanMode =  20
D/BluetoothAdapterProperties( 3056): State =  11
,D/BluetoothAdapterProperties( 3056): Scan Mode:21
D/BluetoothAdapterProperties( 3056): Discoverable Timeout:120
,D/BluetoothAdapterProperties( 3056): Setting state to 12
,I/BluetoothAdapterState( 3056): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService(  733): Message: 60
D/BluetoothManagerService(  733): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
,I/BluetoothAdapterState( 3056): Entering On State
,D/BluetoothManagerService(  733): Broadcasting onBluetoothStateChange(true) to 5 receivers.
D/BluetoothHeadset(  733): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1186): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1186): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1226): onBluetoothStateChange: up=true
D/BluetoothA2dp(  733): onBluetoothStateChange: up=true
D/BluetoothManagerService(  733): Bluetooth State Change Intent: 11 -> 12
D/BluetoothManagerService(  733): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothMapService( 3056): onReceive
D/BluetoothMapService( 3056): STATE_ON
V/BluetoothMapService( 3056): Handler(): got msg=1
,D/BluetoothMapMasInstance( 3056): Map Service startRfcommSocketListener
,E/bt_h4   ( 3056): vendor lib postload completed
,D/BluetoothMapMasInstance( 3056): MAS initSocket()
D/BluetoothMapMasInstance( 3056):   masId = 00
D/BluetoothMapMasInstance( 3056):   msgTypes = 0e
D/BluetoothMapMasInstance( 3056):   masName = SMS/MMS
D/BluetoothMapMasInstance( 3056):   SDP string = 000eSMS/MMS
W/bt-smp  ( 3056): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3056): Plain text(LSB ~ MSB) = b1 c1 6e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3056): Encrypted text(LSB ~ MSB) = dd 12 1c f6 45 a3 17 f7 29 e1 3a 9f c1 e6 91 5e 
W/bt-btm  ( 3056): Stopping oneshot timer
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  733): Message: 40
D/BluetoothManagerService(  733): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
W/BluetoothAdapter( 3056): getBluetoothService() called with no BluetoothManagerCallback
I/Telecom ( 1186): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
V/BluetoothMapMasInstance( 3056): Succeed to create listening socket 
D/BluetoothMapMasInstance( 3056): Accepting socket connection...
W/bt-smp  ( 3056): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3056): Plain text(LSB ~ MSB) = fa f6 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3056): Encrypted text(LSB ~ MSB) = c1 60 92 de 0b 4f be 9c bb 8e a6 03 c5 14 ad 46 
W/bt-btm  ( 3056): Stopping oneshot timer
D/HeadsetStateMachine( 3056): Disconnected process message: 9, size: 0
D/HeadsetStateMachine( 3056): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 3056): mNumber:  mType: 128
D/HeadsetStateMachine( 3056): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 3056): terminateScoUsingVirtualVoiceCall:No present call to terminate
,W/bt-smp  ( 3056): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3056): Plain text(LSB ~ MSB) = 30 3f 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3056): Encrypted text(LSB ~ MSB) = 84 04 07 59 de f0 c8 93 64 4a a4 a9 15 a5 30 2f 
W/bt-btm  ( 3056): Stopping oneshot timer
,W/bt-smp  ( 3056): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3056): Plain text(LSB ~ MSB) = 66 6d 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3056): Encrypted text(LSB ~ MSB) = d7 01 30 09 9f 58 9c 3d 13 6b d2 b4 06 11 8c b8 
W/bt-btm  ( 3056): Stopping oneshot timer
,W/ContextImpl( 3080): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,W/bt-smp  ( 3056): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3056): Plain text(LSB ~ MSB) = 00 b8 67 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3056): Encrypted text(LSB ~ MSB) = 28 2b 9a c0 d4 17 63 f7 48 e7 ec db 4f 88 c5 5f 
,W/bt-btm  ( 3056): Stopping oneshot timer
,W/bt-smp  ( 3056): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3056): Plain text(LSB ~ MSB) = ae b8 5d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3056): Encrypted text(LSB ~ MSB) = 6e 8e 4f f7 02 a9 77 2a 36 7e 65 d5 4f b5 63 31 
W/bt-btm  ( 3056): Stopping oneshot timer
,W/bt-smp  ( 3056): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3056): Plain text(LSB ~ MSB) = fd 45 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3056): Encrypted text(LSB ~ MSB) = 9b d1 35 cb 70 72 d7 2e 13 4d ac 7d 88 b6 f5 a9 
W/bt-btm  ( 3056): Stopping oneshot timer
,I/art     (  733): Explicit concurrent mark sweep GC freed 24078(1199KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 1.204ms total 85.588ms
,D/BluetoothManagerService(  733): Message: 20
D/BluetoothManagerService(  733): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@34ecdf27:true
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3056): getBluetoothService() called with no BluetoothManagerCallback
,D/LocalBluetoothProfileManager( 3080): Adding local A2DP profile
,D/BluetoothManagerService(  733): Message: 30
,D/LocalBluetoothProfileManager( 3080): Adding local HEADSET profile
,D/BluetoothManagerService(  733): Message: 30
,D/BluetoothManagerService(  733): Message: 30
,D/BluetoothManagerService(  733): Message: 30
,D/LocalBluetoothProfileManager( 3080): Adding local MAP profile
,D/BluetoothMap( 3080): Create BluetoothMap proxy object
,D/BluetoothManagerService(  733): Message: 30
,D/BluetoothManagerService(  733): Message: 30
,D/LocalBluetoothProfileManager( 3080): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3080): finishStartingService: stopping service
,D/BluetoothA2dp( 3080): Proxy object connected
,D/A2dpProfile( 3080): Bluetooth service connected
,D/BluetoothHeadset( 3080): Proxy object connected
D/HeadsetProfile( 3080): Bluetooth service connected
,D/AuthorizationBluetoothService( 1381): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothInputDevice( 3080): Proxy object connected
D/HidProfile( 3080): Bluetooth service connected
,D/BluetoothPan( 3080): BluetoothPAN Proxy object connected
D/PanProfile( 3080): Bluetooth service connected
,D/BluetoothMap( 3080): Proxy object connected
D/MapProfile( 3080): Bluetooth service connected
D/BluetoothMap( 3080): getConnectedDevices()
,V/BluetoothMapService( 3056): getConnectedDevices()
,D/BluetoothPbap( 3080): Proxy object connected
D/PbapServerProfile( 3080): Bluetooth service connected
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3056): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 3056): Accept thread started.
,W/NetworkUtils( 1423): OkHttp exception
W/EventLoggerService( 1423): Unable to send logs Error code: 262146
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Search.LoginHelper( 1423): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Search.LoginHelper( 1423): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 2996): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): my name is : LGE-Nexus 5_PT1117
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): attempting to connect to test coordinator
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): check test folder
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): found test : ./testFindPeers.js
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): found test : ./testReConnect.js
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): found test : ./testSendData.js
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): Test app app.js loaded
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/chromium( 2996): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  733): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiStateMachine(  733): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
E/WifiConfigStore(  733): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  733): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=1
,E/WifiConfigStore(  733): writeKnownNetworkHistory write linked 1
E/WifiConfigStore(  733): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  733): will read network variables netId=1
,E/WifiStateMachine(  733): CMD_AUTO_CONNECT did save config ->  nid=1
,E/WifiConfigStore(  733): will read network variables netId=1
,I/wpa_supplicant( 3073): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,E/WifiConfigStore(  733): setLastSelectedConfiguration -1
,E/wpa_supplicant( 3073): PNO: In assoc process
,I/wpa_supplicant( 3073): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3073): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3073): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  733): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  733): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  733): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  733): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  181): Setting iface cfg
,E/WifiStateMachine(  733): Start Dhcp Watchdog 1
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,E/native  (  733): do suspend false
,E/WifiStateMachine(  733): scanCount==0 - aborting
,I/dhcpcd  ( 3238): version 5.5.6 starting
,E/dhcpcd  ( 3238): get_duid: Read-only file system
,I/dhcpcd  ( 3238): wlan0: rebinding lease of 192.168.1.114
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/dhcpcd  ( 3238): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3238): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  733): do suspend true
,D/ConnectivityService(  733): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  733): Adding iface wlan0 to network 100
,E/WifiStateMachine(  733): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  733): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  733): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  733): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  733): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  733): Setting Dns servers for network 100 to [/192.168.1.1]
,D/Nat464Xlat(  733): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  733): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  733): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  733): rematching NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  733):    accepting network in place of null
D/ConnectivityService(  733): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
,D/CSLegacyTypeTracker(  733): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  733): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  733): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 03 Dec 2015 13:59:29 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449151169573], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449151169561]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Validated
D/ConnectivityService(  733): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  733): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  733): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
,D/ConnectivityService(  733): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
,D/TelephonyNetworkFactory( 1226): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/jxcore-log( 2996): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 2996): 
,D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  733): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2518): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2518): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/AlarmManagerService(  733): Setting time of day to sec=1449151172
,W/AlarmManagerService(  733): Unable to set rtc to 1449151172: Invalid argument
,I/ActivityManager(  733): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=3285 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 3285): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3285): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 3285): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/iu.SyncManager( 1561): SYNC; picasa accounts
,D/NetworkLogImpl( 1561): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1561): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1561): num queued entries: 0
,I/iu.UploadsManager( 1561): num updated entries: 0
I/iu.SyncManager( 1561): NEXT; no task
,W/System  ( 3285): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3285): Installed default security provider GmsCore_OpenSSL
,D/ChimeraCfgMgr( 1561): Loading module com.google.android.gms.kids from APK com.google.android.gms
,E/GpsLocationProvider(  733): No APN found to select.
,D/ChimeraCfgMgr( 1561): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/CheckinService( 1561): Checkin interval check for package: unspecified last checkin: 1449052176483 min interval config: 0 actual interval: 98996589
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/SystemUpdateService( 1561): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GpsLocationProvider(  733): NTP server returned: 1449151172859 (Thu Dec 03 14:59:32 GMT+01:00 2015) reference: 91406 certainty: 16 system time offset: -220
E/LocSvc_eng(  733): E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,D/SystemUpdateService( 1561): onCreate
,D/SystemUpdateService( 1561): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/SystemUpdateService( 1561): active receiver: enabled
,I/SystemUpdateService( 1561): showing system update notification
,I/GoogleURLConnFactory( 1561): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ValidateNoPeople(  733): skipping global notification
,I/CheckinService( 1561): Checking schedule, now: 1449151173116 next: 1449094343454
I/CheckinService( 1561): active receiver: enabled
,V/SystemUpdateService( 1561): retry (wakeup: false) in 3599975 ms
,D/SystemUpdateService( 1561): onDestroy
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinService( 1561): Preparing to send checkin request
,I/EventLogService( 1561): Accumulating logs since 1449149632735
,E/Auth.Api.Credentials( 1561): [CredentialSyncAdapter] Unknown sync event.
,I/ActivityManager(  733): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3349 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  196): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 187us total 9.116ms
,I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 169us total 7.354ms
,I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 182us total 7.911ms
,E/YouTube MDX( 3285): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/dex2oat ( 3359): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-1507777136.jar --oat-fd=24 --oat-location=/data/data/com.google.android.youtube/cache/ads-1507777136.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/Babel   ( 1797): connection state changed from UNKNOWN to CONNECTED
,I/dex2oat ( 3359): dex2oat took 47.078ms (threads: 4)
,E/ConnectivityChangeReceiver( 1561): Ignoring connectivity change
,D/ConnectivityService(  733): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  733): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  733): apparently satisfied.  currentScore=60
,D/ConnectivityManager.CallbackHandler( 1561): CM callback handler got msg 524290
,I/GAv4    ( 3349): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3349):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3349):   adb logcat -s GAv4
,I/art     ( 1381): Explicit concurrent mark sweep GC freed 13410(740KB) AllocSpace objects, 2(32KB) LOS objects, 39% free, 19MB/33MB, paused 4.648ms total 104.187ms
,W/GAv4    ( 3349): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/GCM     ( 1381): GCM config loaded
,W/GAv4    ( 3349): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3349): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/InstanceID/Rpc( 3285): Found 10008
,I/art     (  733): Explicit concurrent mark sweep GC freed 40657(1989KB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 27MB/41MB, paused 1.025ms total 71.058ms
,D/ChimeraCfgMgr( 1561): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1561): Module APK com.google.android.play.games already loaded
,I/CheckinRequestBuilder( 1561): Checkin reason type: 12 attempt count: 1
,D/WifiService(  733): New client listening to asynchronous messages
,E/ActivityThread( 1561): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AccountUtils( 1561): 0 accounts found with uca feature
,I/GamesSyncAdapter( 1561): Starting sync for 3a3529a
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GamesSyncAdapter( 1561): User is not G+ enabled. Aborting sync
,I/GamesSyncAdapter( 1561): Sync duration for 3a3529a: 25
,I/WebViewFactory( 3349): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3349): Time to load native libraries: 1 ms (timestamps 2239-2240)
I/LibraryLoader( 3349): Expected native library version number "",actual native library version number ""
,W/DriveInitializer( 1561): Awaiting to be initialized
,V/WebViewChromiumFactoryProvider( 3349): Binding Chromium to main looper Looper (main, tid 1) {36e9dc36}
I/LibraryLoader( 3349): Expected native library version number "",actual native library version number ""
I/chromium( 3349): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,W/DriveInitializer( 1561): Background init thread started
,D/ChimeraCfgMgr( 1561): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1561): Module APK com.google.android.play.games already loaded
,I/BrowserStartupController( 3349): Initializing chromium process, singleProcess=true
W/art     ( 3349): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3349): ApplicationContext is null in ApplicationStatus
,W/chromium( 3349): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3349): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3349): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3349): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3349): Requires BLUETOOTH permission
,I/NSApplication( 3349): Starting up...
,D/ChimeraCfgMgr( 1561): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1561): Module APK com.google.android.play.games already loaded
,I/art     ( 1561): Explicit concurrent mark sweep GC freed 25668(1732KB) AllocSpace objects, 24(407KB) LOS objects, 25% free, 22MB/30MB, paused 6.718ms total 58.873ms
,I/ActivityManager(  733): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3513 uid=10076 gids={50076, 9997} abi=armeabi-v7a
,W/DriveInitializer( 1561): Background init thread ended
,I/ActivityManager(  733): Killing 1779:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10045/pid_1779/cgroup.procs: No such file or directory
,D/TimeService( 3513): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449151173995
D/        ( 3513): TimeServiceNative: User Time to be set is 1449151173996
D/QC-time-services( 3513): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3513): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3513): Lib:time_genoff_operation: pargs->ts_val = 1449151173996
D/QC-time-services(  199): Daemon: Connection accepted:time_genoff
D/QC-time-services( 3513): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  199): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449151173996
D/QC-time-services(  199): Daemon:genoff_opr: Base = 2, val = 1449151173996, operation = 0
,D/QC-time-services(  199): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/6/70 19:50:20
D/QC-time-services(  199): Daemon:Value read from RTC seconds = 8279420000
D/QC-time-services(  199): Daemon:new time 1449151173996 
D/QC-time-services(  199): Daemon: delta 1440871753996 genoff 1440871753996 
D/QC-time-services(  199): Daemon:genoff_persistent_update: Writing genoff = 1440871753996 to memory
D/QC-time-services(  199): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  199): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  199): Updating the TOD offset
D/QC-time-services(  199): Daemon:genoff_persistent_update: Writing genoff = 1440871753996 to memory
D/QC-time-services(  199): Daemon:Opening File: /data/system/time/ats_1
D/QC-time-services(  199): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  199): Daemon:Update to modem bit set
D/QC-time-services(  199): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  199): Daemon: Base = 2, Value being sent to MODEM = 1133186373996
,E/QC-time-services( 3513): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
I/ActivityManager(  733): Killing 2490:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,D/QC-time-services(  199): Daemon: Time-services: Waiting to acceptconnection
,D/QC-time-services(  199): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,W/libprocessgroup(  733): failed to open /acct/uid_10003/pid_2490/cgroup.procs: No such file or directory
,I/CheckinService( 1561): Checkin interval check for package: unspecified last checkin: 1449052176483 min interval config: 0 actual interval: 98997576
,I/ActivityManager(  733): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=3547 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3547): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3547):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3547):   adb logcat -s GAv4
,I/ActivityManager(  733): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3565 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/GAv4    ( 3547): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3547): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/ResourcesManager( 3565): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3565): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/GAv4    ( 3547): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/MultiDex( 3565): VM with version 2.1.0 has multidex support
I/MultiDex( 3565): install
,I/MultiDex( 3565): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  733): Killing 2360:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10070/pid_2360/cgroup.procs: No such file or directory
,I/art     ( 1381): Explicit concurrent mark sweep GC freed 24817(1430KB) AllocSpace objects, 12(192KB) LOS objects, 39% free, 19MB/33MB, paused 1.303ms total 58.142ms
,V/JNIHelp ( 3565): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 3565): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3565): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@128f0586: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3565): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1320): callingUid 10008, callindPid: 1320
,E/MDM     ( 1320): [135] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1561): Restart initialization of location
,I/art     ( 3565): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,I/art     ( 3565): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/art     ( 2640): Attempt to remove local handle scope entry from IRT, ignoring
,D/WVCdm   (  185): Instantiating CDM.
,I/WVCdm   (  185): CdmEngine::OpenSession
I/WVCdm   (  185): Level3 Library Sep 25 2014 17:10:03
,D/NativeLibraryUtils( 3565): Install completed successfully. count=13 extracted=0
,W/WVCdm   (  185): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/GCM     ( 1381): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1381): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/GoogleURLConnFactory( 3565): Using platform SSLCertificateSocketFactory
,D/DrmWidevineDash(  185): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  185): Service_Initialize: starts!
D/QSEECOMAPI: (  185): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  185): App is not loaded in QSEE
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1320): No location to return for getLastLocation()
,W/FusedLocationProvider( 1381): location=null
D/QSEECOMAPI: (  185): Loaded image: APP id = 3
V/GmsCoreStatsServiceLauncher( 1561): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/DrmWidevineDash(  185): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  185): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb47e6000
E/DrmWidevineDash(  185): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb47e6000
,D/DrmWidevineDash(  185): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  185): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  185): hlos api version =  9
D/DrmWidevineDash(  185): tz api version =  9
D/DrmWidevineDash(  185): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  185): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  185): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  185): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  185): OEMCrypto_OpenSession: starts! SID=0xb49ff940
,D/DrmWidevineDash(  185): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  185): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  185): OEMCrypto_GetRandom: starts! randomData=0xb6172268, dataLength=8
,D/DrmWidevineDash(  185): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  185): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb48dd000, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  185): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  185): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  185): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  185): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  185): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  185): OEMCrypto_GetDeviceID: starts! deviceID=0xb31ba440, idLength=0xaee01710
,D/DrmWidevineDash(  185): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  185): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  185): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  185): OEMCrypto_SupportsUsageTable: wv_app_version = 21
D/DrmWidevineDash(  185): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  185): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  185): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  185): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  185): hlos api version =  9
D/DrmWidevineDash(  185): tz api version =  9
D/DrmWidevineDash(  185): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  185): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  185): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  185): PrepareKeyRequest: nonce=2823725292
D/DrmWidevineDash(  185): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb1f16600
,D/DrmWidevineDash(  185): message_length=1597, signature=0xb51b1280, signature_length=2933921524
,D/DrmWidevineDash(  185): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  185): CdmEngine::CloseSession
D/DrmWidevineDash(  185): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  185): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  185): L3 Terminate.
D/DrmWidevineDash(  185): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  185): Service_Uninitialize: starts!
D/QSEECOMAPI: (  185): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  185): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  185): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  185): OEMCrypto_Terminate: ends! returns 0
,I/art     (  733): Explicit concurrent mark sweep GC freed 20645(953KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 1.105ms total 68.359ms
,I/dex2oat ( 3632): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/cache/ads-1378209762.jar --oat-fd=112 --oat-location=/data/data/com.google.android.gms/cache/ads-1378209762.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 3632): dex2oat took 35.613ms (threads: 4)
,I/dex2oat ( 3637): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=35 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 3637): dex2oat took 55.269ms (threads: 4)
,I/Adreno-EGL( 3565): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/WVCdm   (  185): CdmEngine::OpenSession
I/WVCdm   (  185): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  185): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  185): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
,D/DrmWidevineDash(  185): Service_Initialize: starts!
D/QSEECOMAPI: (  185): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  185): App is not loaded in QSEE
,D/QSEECOMAPI: (  185): Loaded image: APP id = 3
,D/DrmWidevineDash(  185): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  185): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb47e6000
E/DrmWidevineDash(  185): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb47e6000
,D/DrmWidevineDash(  185): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  185): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  185): hlos api version =  9
D/DrmWidevineDash(  185): tz api version =  9
D/DrmWidevineDash(  185): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  185): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  185): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  185): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  185): OEMCrypto_OpenSession: starts! SID=0xaeeff940
,D/DrmWidevineDash(  185): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  185): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  185): OEMCrypto_GetRandom: starts! randomData=0xb31100e0, dataLength=8
,D/DrmWidevineDash(  185): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  185): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb31cb600, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  185): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  185): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  185): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  185): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,I/WVCdm   (  185): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  185): OEMCrypto_GetDeviceID: starts! deviceID=0xb31ba480, idLength=0xaee01710
,D/DrmWidevineDash(  185): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  185): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  185): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  185): OEMCrypto_SupportsUsageTable: wv_app_version = 21
D/DrmWidevineDash(  185): OEMCrypto_SupportsUsageTable: ends! returns 0x0
,D/DrmWidevineDash(  185): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  185): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  185): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  185): hlos api version =  9
D/DrmWidevineDash(  185): tz api version =  9
D/DrmWidevineDash(  185): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  185): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  185): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  185): PrepareKeyRequest: nonce=1504314599
D/DrmWidevineDash(  185): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb1f16600
D/DrmWidevineDash(  185): message_length=1632, signature=0xb51b1280, signature_length=2933921524
,D/DrmWidevineDash(  185): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  185): CdmEngine::CloseSession
D/DrmWidevineDash(  185): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  185): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  185): L3 Terminate.
,D/DrmWidevineDash(  185): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  185): Service_Uninitialize: starts!
D/QSEECOMAPI: (  185): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  185): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  185): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  185): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 3565): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/Adreno-EGL( 3565): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/CheckinRequestBuilder( 1561): Classify the device as Phone.
,W/AbstractGoogleClient( 2015): Application name is not set. Call Builder#setApplicationName.
,I/AnalyticsLogBase( 2015): PlayLogger.onLoggerConnected
,I/CheckinTask( 1561): Sending checkin request (9788 bytes)
,I/VacuumService( 1381): Vacuum at: now=1449151176255 tag=VacuumService
,I/CheckinResponseProcessor( 1561): From server: 2 gservices updates and 0 deletes
,D/Finsky  ( 2432): [230] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2432): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/CertBlacklister(  733): Certificate blacklist changed, updating...
,I/CertBlacklister(  733): Certificate blacklist updated
,I/GservicesProvider( 1381): main difference update completed
,I/CheckinRequestBuilder( 1561): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1561): Failed to find provider info for com.google.android.wearable.settings
,I/Babel_SMS( 1797): ApnsOta: OTA version -1
,I/ContactAccountLoggerTas( 1423): canRun() : Opted Out
,I/art     ( 1381): Explicit concurrent mark sweep GC freed 38242(2MB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 19MB/33MB, paused 936us total 28.471ms
,I/ActivityManager(  733): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3694 uid=10036 gids={50036, 9997, 3003} abi=armeabi-v7a
,I/Search.GservicesUpdateTask( 1423): Updating Gservices keys
,E/UpdateRequestReceiver( 3694): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 3694): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/ContactAccountLoggerTas( 1423): canRun() : Opted Out
,E/UpdateRequestReceiver( 3694): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/ContactAccountLoggerTas( 1423): canRun() : Opted Out
I/ContactAccountLoggerTas( 1423): canRun() : Opted Out
,E/UpdateRequestReceiver( 3694): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/art     (  733): Explicit concurrent mark sweep GC freed 24632(1028KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 860us total 50.705ms
,I/art     ( 1381): Explicit concurrent mark sweep GC freed 8246(413KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 19MB/33MB, paused 1.360ms total 57.836ms
,I/CalendarSyncAdapter( 2015): Found no pending settings
,I/ActivityManager(  733): Killing 2796:com.google.android.gms:car/u0a8 (adj 15): empty #17
,I/art     ( 1561): Explicit concurrent mark sweep GC freed 33893(2MB) AllocSpace objects, 18(288KB) LOS objects, 40% free, 23MB/38MB, paused 912us total 45.035ms
,W/SQLiteConnectionPool( 1561): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,W/libprocessgroup(  733): failed to open /acct/uid_10008/pid_2796/cgroup.procs: No such file or directory
,I/ActivityManager(  733): Killing 2891:com.android.musicfx/u0a15 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10015/pid_2891/cgroup.procs: No such file or directory
,W/BaseAppContext( 1320): Using Auth Proxy for data requests.
,I/CheckinRequestBuilder( 1561): Classify the device as Phone.
,I/art     ( 1381): Explicit concurrent mark sweep GC freed 4502(207KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 19MB/33MB, paused 865us total 36.939ms
,I/ActivityManager(  733): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=3744 uid=10070 gids={50070, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SystemEventReceiver( 1561): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 1561): Updating ocr activity enabled=false
,I/CheckinTask( 1561): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1561): Checking schedule, now: 1449151177441 next: 1449193344430
I/CheckinService( 1561): active receiver: disabled
,D/CheckinService( 1561): Recording last checkin time for package unspecified as 1449151177473
,W/ActivityManager(  733): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,I/CheckinService( 1561): Checkin interval check for package: unspecified last checkin: 1449151177473 min interval config: 0 actual interval: 58
,I/CheckinService( 1561): Checking schedule, now: 1449151177551 next: 1449193344430
I/CheckinService( 1561): active receiver: disabled
,I/SystemUpdateService( 1561): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 1561): onCreate
,D/SystemUpdateService( 1561): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/OcrModelManager( 1561): Updating downloaded model state (gservices changed)
,I/SystemUpdateService( 1561): active receiver: enabled
,I/Gmail   ( 3744): getAccountsCursor
D/ActivityThread( 3744): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,D/GCM     ( 1381): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1320): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1320): DispatchingService.onCreate()
,I/SystemUpdateService( 1561): showing system update notification
,I/ValidateNoPeople(  733): skipping global notification
,V/SystemUpdateService( 1561): retry (wakeup: false) in 3599935 ms
,D/SystemUpdateService( 1561): onDestroy
,I/art     ( 1320): Explicit concurrent mark sweep GC freed 17561(1152KB) AllocSpace objects, 14(224KB) LOS objects, 39% free, 19MB/32MB, paused 812us total 30ms
,I/art     ( 1561): Explicit concurrent mark sweep GC freed 14587(888KB) AllocSpace objects, 8(128KB) LOS objects, 39% free, 23MB/38MB, paused 1.402ms total 47.627ms
,E/DataBuffer( 1320): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@96b8c92)
,I/ContactAccountLoggerTas( 1423): canRun() : Opted Out
,I/ActivityManager(  733): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=3790 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GCoreUlr( 1320): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,W/GAV2    ( 3744): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/SyncManager(  733): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 37341, reason: Periodic, SyncResult: syncAlreadyInProgress: true stats []
,D/ChimeraCfgMgr( 1561): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/Gmail   ( 3744): getAccountsCursor
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 1561): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager(  733): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Exchange( 3790): EasService.onCreate
,W/Gmail   ( 3744): Sync started for account: account:61035162
D/GetConfigurationSnapshotOperation( 1381): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/Exchange( 3790): RestartPingTask
,I/Gmail   ( 3744): Observing account changes for notifications
,E/SQLiteLog( 3744): (283) recovered 39 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,D/GCM     ( 1381): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  733): Explicit concurrent mark sweep GC freed 29582(1281KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.262ms total 71.837ms
,D/ChimeraCfgMgr( 1561): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Exchange( 3790): RestartPingsTask did not start any pings.
I/Exchange( 3790): PSS stopIfIdle
I/Exchange( 3790): PSS has no active accounts; stopping service.
W/AppCertServiceClient( 1320): Interrupted when getting service: java.lang.InterruptedException
,I/Exchange( 3790): onDestroy
I/PhenotypeFlagCommitter( 1381): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1381): Using platform SSLCertificateSocketFactory
,W/AbstractServer( 1320): GoogleAuthException while getting app cert is being ignored.
W/AbstractServer( 1320): com.google.android.gms.auth.o: Interrupted
W/AbstractServer( 1320): 	at com.google.android.gms.auth.b.a.a(SourceFile:123)
W/AbstractServer( 1320): 	at com.google.android.gms.auth.b.a.a(SourceFile:90)
W/AbstractServer( 1320): 	at com.google.android.gms.common.server.c.d(SourceFile:74)
W/AbstractServer( 1320): 	at com.google.android.gms.common.server.o.d(SourceFile:31)
W/AbstractServer( 1320): 	at com.google.android.gms.common.server.o.b(SourceFile:379)
W/AbstractServer( 1320): 	at com.google.android.gms.common.server.o.a(SourceFile:348)
W/AbstractServer( 1320): 	at com.google.android.gms.common.server.o.a(SourceFile:327)
W/AbstractServer( 1320): 	at com.google.android.location.reporting.d.c.a(SourceFile:164)
W/AbstractServer( 1320): 	at com.google.android.location.reporting.d.g.a(SourceFile:94)
W/AbstractServer( 1320): 	at com.google.android.location.reporting.service.u.b(SourceFile:220)
W/AbstractServer( 1320): 	at com.google.android.location.reporting.service.u.a(SourceFile:173)
W/AbstractServer( 1320): 	at com.google.android.location.reporting.service.t.a(SourceFile:151)
W/AbstractServer( 1320): 	at com.google.android.gms.common.j.a.onPerformSync(SourceFile:98)
W/AbstractServer( 1320): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/art     ( 1381): Explicit concurrent mark sweep GC freed 19676(1113KB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 20MB/33MB, paused 757us total 28.351ms
,D/GCM     ( 1381): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GetCommittedConfigurationOperation( 1381): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/GCoreUlr( 1320): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/Gmail   ( 3744): notifyAccountChanged
,I/GCoreUlr( 1320): Unbound from all location providers
,I/ActivityManager(  733): Killing 2918:com.google.android.apps.docs/u0a40 (adj 15): empty #17
,I/Gmail   ( 3744): getAccountsCursor
,I/Gmail   ( 3744): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3744): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3744): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3744): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/libprocessgroup(  733): failed to open /acct/uid_10040/pid_2918/cgroup.procs: No such file or directory
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3744): notifyAccountChanged
,I/GCoreUlr( 1320): DispatchingService.onDestroy()
I/GCoreUlr( 1320): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1320): Unbound from all location providers
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3744): getAccountsCursor
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3744): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 11793, normalSync: true
,W/ResourcesManager( 3744): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3744): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 3744): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/GetCommittedConfigurationOperation( 1381): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/System  ( 3744): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[directory "."],nativeLibraryDirectories=[/vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3744): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1320): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,I/GCoreUlr( 1320): DispatchingService.onCreate()
,D/SyncManager(  733): handleSyncHandlerMessage: dropping since the sync is no longer active: startTime 95612, mTimeoutStartTime 95612, mHistoryRowId 10, syncOperation thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 126645, reason: Periodic
,I/ValidateNoPeople(  733): mEvictionCount: 0
,I/GCoreUlr( 1320): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1320): Unbound from all location providers
,I/GCoreUlr( 1320): DispatchingService.onDestroy()
I/GCoreUlr( 1320): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1320): Unbound from all location providers
,E/SQLiteLog( 1336): (284) automatic index on sqlite_sq_AFB3C970(STAT_DATA_ID)
,E/SQLiteLog( 1336): (284) automatic index on sqlite_sq_AFB66060(STAT_DATA_ID)
,E/SQLiteLog( 1336): (284) automatic index on sqlite_sq_AF530290(STAT_DATA_ID)
,E/SQLiteLog( 1336): (284) automatic index on sqlite_sq_AF518A10(STAT_DATA_ID)
,I/art     ( 1381): Explicit concurrent mark sweep GC freed 28499(1568KB) AllocSpace objects, 7(135KB) LOS objects, 39% free, 20MB/34MB, paused 742us total 27.136ms
,I/art     (  733): Explicit concurrent mark sweep GC freed 17792(760KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.004ms total 95.080ms
,D/GetCommittedConfigurationOperation( 1381): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/GHttpClientFactory( 2518): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 2518): Using platform SSLCertificateSocketFactory
,I/MusicLifecycle( 2518): Sync started
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GetCommittedConfigurationOperation( 1381): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/Uploader( 1381):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1381): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1381): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/MusicSyncAdapter( 2518): Will attempt periodic sync for account: Account {name=thalitester@gmail.com, type=com.google}
I/MusicSyncAdapter( 2518): Periodic update
,W/MusicApiClient( 2518): Activity events list is null or empty. Skip reporting.
,I/MusicLifecycle( 2518): Sync ended
,I/MusicLeanback( 2518): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 2518): Stop autocaching.
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WearableService( 1320): callingUid 10008, callindPid: 1320
,E/GmsUtils( 2518): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 2518): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/SyncAdapterService( 3349): Ignoring sync request for non-current account
,V/NQFileLogger( 1381): [201] e.a: about to write to file
,V/ProcessReports( 1381): [201] ProcessReportsService.a: If not already scheduled, schedule for 3600 to 14400 seconds from now (but might be processed inline after 900 seconds instead)
,D/DelayedSyncController(  945): Delaying sync.
,D/GetCommittedConfigurationOperation( 1381): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/BaseAppContext( 1561): Using Auth Proxy for data requests.
,W/BaseAppContext( 1561): Using Auth Proxy for data requests.
,W/BaseAppContext( 1561): Using Auth Proxy for data requests.
,W/BaseAppContext( 1561): Using Auth Proxy for data requests.
,W/BaseAppContext( 1561): Using Auth Proxy for data requests.
,W/BaseAppContext( 1561): Using Auth Proxy for data requests.
,I/art     ( 1381): Explicit concurrent mark sweep GC freed 40114(2MB) AllocSpace objects, 7(112KB) LOS objects, 40% free, 21MB/35MB, paused 10.986ms total 43.604ms
,W/BaseAppContext( 1561): Using Auth Proxy for data requests.
,D/GetCommittedConfigurationOperation( 1381): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/ActivityManager(  733): Start proc com.google.android.videos for service com.google.android.videos/.store.SyncService: pid=3899 uid=10077 gids={50077, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/GetCommittedConfigurationOperation( 1381): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/art     ( 3744): Explicit concurrent mark sweep GC freed 149390(5MB) AllocSpace objects, 15(263KB) LOS objects, 24% free, 18MB/25MB, paused 458us total 57.393ms
,I/Gmail   ( 3744): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 11857, normalSync: true
,I/Gmail   ( 3744): lowestBackward conversation id 0
,W/ResourcesManager( 3899): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,I/Gmail   ( 3744): notifyAccountChanged
,I/Gmail   ( 3744): getAccountsCursor
,D/GetCommittedConfigurationOperation( 1381): no corresponding serverToken: com.google.android.gms.playlog.uploader
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3744): notifyAccountChanged
,W/Gmail   ( 3744): Sync complete for account: account:61035162
,I/Gmail   ( 3744): getAccountsCursor
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  733): Killing 2772:com.android.defcontainer/u0a5 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10005/pid_2772/cgroup.procs: No such file or directory
,I/ActivityManager(  733): Start proc com.google.android.apps.cloudprint:sync for service com.google.android.apps.cloudprint/.printdialog.services.CloudPrintSyncService: pid=3919 uid=10035 gids={50035, 9997, 3003, 1028} abi=armeabi-v7a
,D/GetCommittedConfigurationOperation( 1381): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1381): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/ActivityManager(  733): Start proc com.google.android.apps.cloudprint for service com.google.android.apps.cloudprint/.printdialog.services.NotificationIntentService: pid=3950 uid=10035 gids={50035, 9997, 3003, 1028} abi=armeabi-v7a
,D/PlayMovies( 3899): PersistentCache.cleanup:103 Cache is below limit, no need to shrink: [size=0, limit=5242880]
,D/PlayMovies( 3899): TransferService.onCreate:52 creating transfer service
,W/VideoCapabilities( 3899): Unrecognized profile 2130706433 for video/avc
,I/VideoCapabilities( 3899): Unsupported profile 4 for video/mp4v-es
,I/art     (  733): Explicit concurrent mark sweep GC freed 23354(895KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 967us total 53.280ms
,I/com.google.android.apps.cloudprint.printdialog.database.CloudPrintSyncAdapter( 3919): Sync request not initiated by GCP app. Dropping
,W/ResourcesManager( 1561): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,I/ActivityManager(  733): Killing 3080:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  733): Client connection lost with reason: 4
,W/libprocessgroup(  733): failed to open /acct/uid_1000/pid_3080/cgroup.procs: No such file or directory
,I/ActivityManager(  733): Killing 3513:com.qualcomm.timeservice/u0a76 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10076/pid_3513/cgroup.procs: No such file or directory
,E/Auth.Api.Credentials( 1561): [CredentialSyncAdapter] Unknown sync event.
,I/CalendarSyncAdapter( 2015): Found no pending settings
,I/ActivityManager(  733): Killing 3547:com.google.android.deskclock/u0a38 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10038/pid_3547/cgroup.procs: No such file or directory
,I/PlayMovies( 3899): SyncService.syncAllPurchasesAndWishlist:151 Starting sync for 515013DC511638B0584069811EF28701C0771BF5
,I/Icing   ( 1561): Indexing 009F7E1EAB88E81C4EB4149FAD093AD3E8757DF2 from com.google.android.gm
,I/art     ( 1561): Explicit concurrent mark sweep GC freed 11449(820KB) AllocSpace objects, 16(256KB) LOS objects, 40% free, 23MB/38MB, paused 886us total 31.146ms
,I/Gmail   ( 3744): Backfilling search sequence table
,I/Icing   ( 1561): Indexing done 009F7E1EAB88E81C4EB4149FAD093AD3E8757DF2
,I/PlayMovies( 3899): SyncService.waitForCompletion:177 Sync completed for 515013DC511638B0584069811EF28701C0771BF5 purchases
,I/PlayMovies( 3899): SyncService.waitForCompletion:177 Sync completed for 515013DC511638B0584069811EF28701C0771BF5 wishlist
,I/ActivityManager(  733): Killing 1797:com.google.android.talk/u0a54 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10054/pid_1797/cgroup.procs: No such file or directory
,I/GAV2    ( 3744): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,W/PackageSettings(  733): Skipping PackageSetting{16a5834c com.example.hello/10277} due to missing metadata
,I/InputReader(  733): Reconfiguring input devices.  changes=0x00000010
,I/InputReader(  733): Reconfiguring input devices.  changes=0x00000010
,I/UpdateIcingCorporaServi( 1423): Updating corpora: APPS=com.google.android.videos, CONTACTS=MAYBE
W/Launcher( 1287): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@27dd404d new=com.google.android.velvet.VelvetApplication@27dd404d
,D/PackageBroadcastService( 1561): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.videos
,I/PeopleContactsSync( 1561): CP2 sync disabled
,I/UpdateIcingCorporaServi( 1423): UpdateCorporaTask done [took 56 ms] updated apps [took 56 ms] 
,D/BackupManagerService(  733): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.videos flg=0x4000010 (has extras) }
,I/ActivityManager(  733): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=4037 uid=10054 gids={50054, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/BackupManagerService(  733): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  733): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  733): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  733): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  733): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@f1d9ad6
,W/ResourcesManager( 4037): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/GmsNetworkLocationProvi( 1320): DISABLE
,I/GCoreNlp( 1320): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1287): Deferring update until onResume
,W/ResourcesManager( 1287): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1287): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Babel_SMS( 4037): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 4037): MmsConfig.loadMmsSettings
,I/Babel_SMS( 4037): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
I/Babel_SMS( 4037): MmsConfig.loadFromDatabase
,I/Launcher( 1287): Deferring update until onResume
,E/Babel_SMS( 4037): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4037): MmsConfig.loadFromResources
,E/Babel_SMS( 4037): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 4037): MmsConfig.loadMmsSettings: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
,I/Babel_SMS( 4037): ApnsOta: OTA version -1
,I/Babel   ( 4037): deleted: false for 0
,W/Settings( 4037): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Launcher( 1287): Deferring update until onResume
,I/Babel_Crash( 4037): startup - clean
,I/Launcher( 1287): Deferring update until onResume
,I/UpdateIcingCorporaServi( 1423): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
W/Launcher( 1287): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@27dd404d new=com.google.android.velvet.VelvetApplication@27dd404d
,D/PackageBroadcastService( 1561): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1561): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1561): updateResources: need to parse f{com.google.android.gms}
,W/VideoCapabilities( 4037): Unrecognized profile 2130706433 for video/avc
,I/VideoCapabilities( 4037): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4037): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4037): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4037): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4037): Unrecognized profile 2130706433 for video/avc
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/vclib   ( 4037): onServiceConnected
,W/Babel   ( 4037): Attempted to change video mute state without an active call.
,W/ResourcesManager( 4037): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4037): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4037): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/UpdateIcingCorporaServi( 1423): UpdateCorporaTask done [took 213 ms] updated apps [took 213 ms] 
,W/System  ( 4037): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4037): Installed default security provider GmsCore_OpenSSL
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/ActivityManager(  733): Killing 3285:com.google.android.youtube/u0a80 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10080/pid_3285/cgroup.procs: No such file or directory
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/ActivityManager(  733): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4091 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/art     (  196): Explicit concurrent mark sweep GC freed 703(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 179us total 7.748ms
,I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 165us total 7.325ms
,I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 174us total 11.909ms
,I/GAv4    ( 4091): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4091):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4091):   adb logcat -s GAv4
,W/GAv4    ( 4091): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4091): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4091): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  733): Killing 1492:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10013/pid_1492/cgroup.procs: No such file or directory
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/art     ( 1320): Explicit concurrent mark sweep GC freed 19409(1132KB) AllocSpace objects, 9(144KB) LOS objects, 39% free, 19MB/32MB, paused 960us total 26.672ms
,W/BaseAppContext( 1320): Using Auth Proxy for data requests.
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/UdcCache:FPQuery( 1561): Bootstrapping UDC settings cache for all accounts
,I/art     (  733): Explicit concurrent mark sweep GC freed 35234(1843KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 27MB/41MB, paused 898us total 92.005ms
,I/GCoreUlr( 1320): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,I/GCoreUlr( 1320): DispatchingService.onCreate()
,I/GCoreUlr( 1320): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1320): Unbound from all location providers
,I/GCoreUlr( 1320): DispatchingService.onDestroy()
I/GCoreUlr( 1320): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1320): Unbound from all location providers
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/ClearcutLoggerApiImpl( 1320): disconnect managed GoogleApiClient
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/ClearcutLoggerApiImpl( 1381): disconnect managed GoogleApiClient
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): DBG, CoordinatorConnector connect called
I/jxcore-log( 2996): 
I/jxcore-log( 2996): Coordinator is now connected to the server!
I/jxcore-log( 2996): 
,I/chromium( 2996): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  733): Killing 3694:com.google.android.configupdater/u0a36 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10036/pid_3694/cgroup.procs: No such file or directory
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  733): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=4187 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 4187): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4187): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4187): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/System  ( 4187): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 4187): Installed default security provider GmsCore_OpenSSL
,E/YouTube MDX( 4187): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/dex2oat ( 4237): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-1507777136.jar --oat-fd=22 --oat-location=/data/data/com.google.android.youtube/cache/ads-1507777136.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 4237): dex2oat took 31.135ms (threads: 4)
,W/InstanceID/Rpc( 4187): Found 10008
,I/ActivityManager(  733): Killing 3129:com.google.android.keep/u0a71 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10071/pid_3129/cgroup.procs: No such file or directory
,I/jxcore-log( 2996): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): DBG, CoordinatorConnector command called
I/jxcore-log( 2996): 
I/jxcore-log( 2996): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":17,"addressList":[{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"B4:CE:F6:AB:A4:6A","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"34:FC:EF:9D:93:0B","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"00:F4:6F:30:E0:6C","tryCount":0},{"address":"F4:F1:E1:5C:3B:E2","tryCount":0}]}
I/jxcore-log( 2996): 
I/jxcore-log( 2996): Start now : testSendData.js
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 17
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): check server
I/jxcore-log( 2996): 
I/jxcore-log( 2996): serverPort is 46930
I/jxcore-log( 2996): 
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 2996): Stoping All
I/        ( 2996): Stopping services
I/        ( 2996): Stop Bluetooth
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 2996): Start-My BT: 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 2996):  mInstanceString : {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1117","ra":"34:FC:EF:11:AE:67"}
,I/        ( 2996): All stuff available and enabled
I/        ( 2996): Stoping All
I/        ( 2996): Stopping services
I/        ( 2996): Stop Bluetooth
I/        ( 2996): Starting All
I/        ( 2996): Stopping services
I/        ( 2996): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1117","ra":"34:FC:EF:11:AE:67"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@17118440
I/        ( 2996): Stopping services
I/        ( 2996): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1117","ra":"34:FC:EF:11:AE:67"}
I/        ( 2996): Add local service :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1117","ra":"34:FC:EF:11:AE:67"}, length : 77
,I/        ( 2996): peerDiscoveryTimer timeout value:9854
,I/        ( 2996): Stop Bluetooth
I/        ( 2996): StartBluetooth listener
I/        ( 2996): StartBluetooth listener
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2996): StartBroadcasting started ok
I/jxcore-log( 2996): 
I/jxcore-log( 2996): do fake peer & start
I/jxcore-log( 2996): 
I/jxcore-log( 2996): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:05:03.360Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:05:03.361Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:05:03.361Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 2996): Connecting to null, at 44:80:EB:7B:5A:05
,I/jxcore-log( 2996): 2015-12-03T14:05:03.366Z SendDataTCPServer.js: TCP/IP server is bound to port: 46930
I/jxcore-log( 2996): 
I/chromium( 2996): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/WB      ( 2996): We already were running, thus doing nothing
I/        ( 2996): Added local service
I/        ( 2996): Cleared service requests
I/        ( 2996): Stopped peer discovery
I/        ( 2996): Started peer discovery
I/        ( 2996): Discovery state changed to Started.
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,I/BTListenerThread( 2996): starting to listen
I/BTListenerThread( 2996): waiting to accept incoming Connection
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3056): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,W/bt-rfcomm( 3056): PORT_StartCnf failed result:5
,W/bt-btif ( 3056): invalid rfc slot id: 5
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BTConnectToThread( 2996): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3056): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 3056): No record of the device:null
I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 9 Address: 44:80:EB:7B:5A:05 newState: 0
,E/BluetoothBondStateMachine( 3056): In stable state, received invalid newState: 10
,I/CONNEC  ( 2996): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2996): 2015-12-03T14:05:06.227Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:05:06.228Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:05:06.230Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
E/bt-btif ( 3056): Do not find the bg connection mask for the remote device
,E/BluetoothRemoteDevices( 3056): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2996): Found 1 peers.
I/SS      ( 2996): Peer(1): Android_2dc2 52:55:27:f0:ff:f0
,D/WifiP2pManager( 2996): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2996): Added service request
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2996): Started service discovery
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2996): 2015-12-03T14:05:11.237Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:05:11.239Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:05:16.244Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:05:16.244Z SendDataConnector.js: Connect (retry count 1) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:05:16.246Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:05:16.246Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 2996): Connecting to null, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 3056): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41daebc rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btif ( 3056): DISCOVERY_COMP_EVT slot id:6, failed to find channle,                                       status:1, scn:0
E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 3056): invalid rfc slot id: 6
,I/BTConnectToThread( 2996): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/BluetoothRemoteDevices( 3056): aclStateChangeCallback: Device is NULL
,I/CONNEC  ( 2996): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2996): 2015-12-03T14:05:39.083Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:05:39.084Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:05:39.084Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:05:44.086Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:05:44.086Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:05:49.092Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:05:49.093Z SendDataConnector.js: Connect (retry count 2) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:05:49.093Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:05:49.094Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 2996): Connecting to null, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3056): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
E/bt-btif ( 3056): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3056): Entering PendingCommandState State
,I/ActivityManager(  733): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest: pid=4314 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
D/BluetoothAdapterProperties( 3056): Failed to remove device: 44:80:EB:7B:5A:05
I/BluetoothBondStateMachine( 3056): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,D/BluetoothManagerService(  733): Message: 20
D/BluetoothManagerService(  733): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3e3b8d89:true
,I/ActivityManager(  733): Killing 3790:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 2996): Starting to Handshake
,I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
I/BTConnectToThread( 2996): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,W/libprocessgroup(  733): failed to open /acct/uid_10069/pid_3790/cgroup.procs: No such file or directory
,I/BTConnectToThread( 2996): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 2996): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4866","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2996): HandshakeOk : motorola-XT1072_PT4866
I/HS      ( 2996): Hand Shake finished outgoing for : motorola-XT1072_PT4866
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 2996): Starting the connected thread incoming : false, motorola-XT1072_PT4866
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 2996): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2996): mHTTPPort  set to : 45014
I/BtConnectorHelper( 2996): Request socket is using : 45014
,I/BtToRequestSocket( 2996): Now accepting connections
,I/BluetoothBondStateMachine( 3056): StableState(): Entering Off State
,I/BtConnectorHelper( 2996): Calling ConnectionStatusUpdate with port :45014
I/jxcore-log( 2996): 2015-12-03T14:05:52.979Z SendDataConnector.js: CLIENT connected to 45014, error: null
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:05:52.980Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): incoming data from: /127.0.0.1, port: 45014
,I/BtToRequestSocket( 2996): Set local streams
,I/BtToRequestSocket( 2996): rin ended ---------------------------;
,I/jxcore-log( 2996): 2015-12-03T14:05:53.019Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2996): 
,D/        ( 3056): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 2996): 2015-12-03T14:05:53.552Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2996): 
,D/        ( 3056): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:16786
,I/jxcore-log( 2996): 2015-12-03T14:05:53.598Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2996): 
,D/        ( 3056): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8866
,I/jxcore-log( 2996): 2015-12-03T14:05:53.675Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:05:53.678Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:05:53.724Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:05:53.770Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:05:53.846Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:05:53.883Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:05:54.028Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:05:54.043Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:05:54.048Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:05:54.076Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:05:54.076Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/BtConnectorHelper( 2996): Disconnect outgoing peer: 44:80:EB:7B:5A:05
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
I/BtToRequestSocket( 2996): Close server socket
I/jxcore-log( 2996): 2015-12-03T14:05:54.082Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): ---- round done--------
I/jxcore-log( 2996): 
I/jxcore-log( 2996): do fake peer & start
I/jxcore-log( 2996): 
I/jxcore-log( 2996): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:05:54.083Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:05:54.083Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:05:54.083Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 2996): Connecting to null, at E0:DB:10:14:E2:C0
,I/chromium( 2996): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 44:80:EB:7B:5A:05 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41daebc rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3056): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
E/BluetoothRemoteDevices( 3056): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db084 rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
E/bt-btif ( 3056): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3056): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 3056): Failed to remove device: E0:DB:10:14:E2:C0
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3056): StableState(): Entering Off State
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2996): Starting to Handshake
I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2996): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/BTConnectToThread( 2996): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 2996): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT7904","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2996): HandshakeOk : samsung-SM-N910C_PT7904
I/HS      ( 2996): Hand Shake finished outgoing for : samsung-SM-N910C_PT7904
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : false, samsung-SM-N910C_PT7904
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2996): mHTTPPort  set to : 42699
I/BtConnectorHelper( 2996): Request socket is using : 42699
I/BtToRequestSocket( 2996): Now accepting connections
,I/BtConnectorHelper( 2996): Calling ConnectionStatusUpdate with port :42699
I/jxcore-log( 2996): 2015-12-03T14:05:57.417Z SendDataConnector.js: CLIENT connected to 42699, error: null
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:05:57.418Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): incoming data from: /127.0.0.1, port: 42699
I/BtToRequestSocket( 2996): Set local streams
I/BtToRequestSocket( 2996): rin ended ---------------------------;
,I/jxcore-log( 2996): 2015-12-03T14:05:57.450Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:05:58.118Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:05:58.184Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:05:58.253Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:05:58.769Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:05:58.874Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/jxcore-log( 2996): 2015-12-03T14:05:59.114Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2996): 
,D/BluetoothManagerService(  733): Message: 20
D/BluetoothManagerService(  733): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@101f8daf:true
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: XT1072
,I/jxcore-log( 2996): 2015-12-03T14:05:59.557Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:05:59.808Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:06:00.192Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:06:00.193Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:06:00.209Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:06:00.210Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
,I/BtConnectorHelper( 2996): Disconnect outgoing peer: E0:DB:10:14:E2:C0
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2996): Close LocalOutputStream
,I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2996): Close bt out
,I/BtToSocketBase( 2996): Close bt socket
I/BtToRequestSocket( 2996): Close server socket
,W/bt-btif ( 3056): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,I/jxcore-log( 2996): 2015-12-03T14:06:00.254Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): ---- round done--------
I/jxcore-log( 2996): 
I/jxcore-log( 2996): do fake peer & start
I/jxcore-log( 2996): 
I/jxcore-log( 2996): Connect to fake peer: B0:C5:59:3F:75:69
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:06:00.262Z SendDataConnector.js: Start called with peer B0:C5:59:3F:75:69
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:06:00.263Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:06:00.263Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: B0:C5:59:3F:75:69, name: null
,I/        ( 2996): Connecting to null, at B0:C5:59:3F:75:69
I/chromium( 2996): [INFO:CONSOLE(63)] "logCallback Round of send data to peer E0:DB:10:14:E2:C0 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 3056): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db24c rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
E/bt-btif ( 3056): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3056): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,D/BluetoothAdapterProperties( 3056): Failed to remove device: B0:C5:59:3F:75:69
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3056): StableState(): Entering Off State
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db24c rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2996): Starting to Handshake
,I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2996): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db24c rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 2996): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 2996): Got JSON from encryption:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT411","ra":"B0:C5:59:3F:75:69"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2996): HandshakeOk : samsung-SM-G900F_PT411
I/HS      ( 2996): Hand Shake finished outgoing for : samsung-SM-G900F_PT411
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : false, samsung-SM-G900F_PT411
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2996): mHTTPPort  set to : 57935
I/BtConnectorHelper( 2996): Request socket is using : 57935
I/BtToRequestSocket( 2996): Now accepting connections
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: Note4-1
,I/BtConnectorHelper( 2996): Calling ConnectionStatusUpdate with port :57935
I/jxcore-log( 2996): 2015-12-03T14:06:04.467Z SendDataConnector.js: CLIENT connected to 57935, error: null
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:06:04.467Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): incoming data from: /127.0.0.1, port: 57935
I/BtToRequestSocket( 2996): Set local streams
I/BtToRequestSocket( 2996): rin ended ---------------------------;
,I/jxcore-log( 2996): 2015-12-03T14:06:04.474Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:06:04.932Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:06:04.981Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:06:05.027Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:06:05.076Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:06:05.143Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:06:05.174Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:06:05.252Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:06:05.258Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2996): 
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 2996): Cleared service requests
I/        ( 2996): Started peer discovery
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2996): Found 3 peers.
I/SS      ( 2996): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2996): Peer(2): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2996): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
,D/WifiP2pManager( 2996): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2996): Added service request
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2996): Started service discovery
,W/bt-btif ( 3056): dm_pm_timer expires
W/bt-btif ( 3056): dm_pm_timer expires 0
W/bt-btif ( 3056): proc dm_pm_timer expires
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2996): 2015-12-03T14:06:15.259Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:06:15.259Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:06:15.266Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:06:15.267Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:06:15.268Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2996): 
,I/BtToSocketBase( 2996): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2996): Disconnect outgoing peer: samsung-SM-G900F_PT411
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
I/BtToRequestSocket( 2996): Close server socket
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db24c rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3056): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/jxcore-log( 2996): 2015-12-03T14:06:20.273Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:06:20.274Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:06:25.279Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:06:25.279Z SendDataConnector.js: Connect (retry count 1) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:06:25.280Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:06:25.283Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: B0:C5:59:3F:75:69, name: Thali Test (Galaxy S5)
,I/        ( 2996): Connecting to Thali Test (Galaxy S5), at B0:C5:59:3F:75:69
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: Thali Test (Galaxy S5)
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2996): Starting to Handshake
,I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2996): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/BTConnectToThread( 2996): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 2996): Got JSON from encryption:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT411","ra":"B0:C5:59:3F:75:69"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2996): HandshakeOk : samsung-SM-G900F_PT411
I/HS      ( 2996): Hand Shake finished outgoing for : samsung-SM-G900F_PT411
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : false, samsung-SM-G900F_PT411
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2996): mHTTPPort  set to : 33523
I/BtConnectorHelper( 2996): Request socket is using : 33523
I/BtToRequestSocket( 2996): Now accepting connections
,I/BtConnectorHelper( 2996): Calling ConnectionStatusUpdate with port :33523
,I/jxcore-log( 2996): 2015-12-03T14:06:27.248Z SendDataConnector.js: CLIENT connected to 33523, error: null
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:06:27.249Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): incoming data from: /127.0.0.1, port: 33523
I/BtToRequestSocket( 2996): Set local streams
I/BtToRequestSocket( 2996): rin ended ---------------------------;
,I/jxcore-log( 2996): 2015-12-03T14:06:27.272Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2996): 
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3056): dm_pm_timer expires
W/bt-btif ( 3056): dm_pm_timer expires 0
W/bt-btif ( 3056): proc dm_pm_timer expires
,I/jxcore-log( 2996): 2015-12-03T14:06:37.327Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:06:37.328Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:06:37.330Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:06:37.337Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:06:37.338Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2996): 
,I/BtToSocketBase( 2996): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2996): Disconnect outgoing peer: samsung-SM-G900F_PT411
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
I/BtToRequestSocket( 2996): Close server socket
,W/bt-btif ( 3056): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,I/jxcore-log( 2996): 2015-12-03T14:06:42.339Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:06:42.342Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/jxcore-log( 2996): 2015-12-03T14:06:47.348Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:06:47.348Z SendDataConnector.js: Connect (retry count 2) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:06:47.349Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:06:47.349Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: B0:C5:59:3F:75:69, name: Thali Test (Galaxy S5)
,I/        ( 2996): Connecting to Thali Test (Galaxy S5), at B0:C5:59:3F:75:69
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: Thali Test (Galaxy S5)
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2996): Starting to Handshake
I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2996): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/BTConnectToThread( 2996): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 2996): Got JSON from encryption:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT411","ra":"B0:C5:59:3F:75:69"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2996): HandshakeOk : samsung-SM-G900F_PT411
I/HS      ( 2996): Hand Shake finished outgoing for : samsung-SM-G900F_PT411
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : false, samsung-SM-G900F_PT411
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2996): mHTTPPort  set to : 54173
I/BtConnectorHelper( 2996): Request socket is using : 54173
I/BtToRequestSocket( 2996): Now accepting connections
,I/BtConnectorHelper( 2996): Calling ConnectionStatusUpdate with port :54173
I/jxcore-log( 2996): 2015-12-03T14:06:48.546Z SendDataConnector.js: CLIENT connected to 54173, error: null
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:06:48.546Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): incoming data from: /127.0.0.1, port: 54173
I/BtToRequestSocket( 2996): Set local streams
I/BtToRequestSocket( 2996): rin ended ---------------------------;
,I/jxcore-log( 2996): 2015-12-03T14:06:48.567Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2996): 
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3056): dm_pm_timer expires
W/bt-btif ( 3056): dm_pm_timer expires 0
W/bt-btif ( 3056): proc dm_pm_timer expires
,I/jxcore-log( 2996): 2015-12-03T14:06:58.637Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:06:58.638Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:06:58.639Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:06:58.645Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:06:58.648Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2996): 
,I/BtToSocketBase( 2996): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2996): Disconnect outgoing peer: samsung-SM-G900F_PT411
,I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
,I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
I/BtToRequestSocket( 2996): Close server socket
,W/bt-btif ( 3056): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,I/jxcore-log( 2996): 2015-12-03T14:07:03.649Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:07:03.650Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/jxcore-log( 2996): 2015-12-03T14:07:08.662Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:07:08.663Z SendDataConnector.js: Connect (retry count 3) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:07:08.663Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:07:08.664Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: B0:C5:59:3F:75:69, name: Thali Test (Galaxy S5)
,I/        ( 2996): Connecting to Thali Test (Galaxy S5), at B0:C5:59:3F:75:69
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/        ( 2996): Cleared service requests
I/        ( 2996): Started peer discovery
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2996): Found 6 peers.
I/SS      ( 2996): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2996): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2996): Peer(3): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 2996): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2996): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2996): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2996): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2996): Added service request
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2996): Starting to Handshake
I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2996): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/BTConnectToThread( 2996): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 2996): Got JSON from encryption:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT411","ra":"B0:C5:59:3F:75:69"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 2996): HandshakeOk : samsung-SM-G900F_PT411
I/HS      ( 2996): Hand Shake finished outgoing for : samsung-SM-G900F_PT411
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : false, samsung-SM-G900F_PT411
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2996): mHTTPPort  set to : 54915
I/BtConnectorHelper( 2996): Request socket is using : 54915
I/BtToRequestSocket( 2996): Now accepting connections
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BtConnectorHelper( 2996): Calling ConnectionStatusUpdate with port :54915
,I/jxcore-log( 2996): 2015-12-03T14:07:10.503Z SendDataConnector.js: CLIENT connected to 54915, error: null
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:07:10.504Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): incoming data from: /127.0.0.1, port: 54915
I/BtToRequestSocket( 2996): Set local streams
I/BtToRequestSocket( 2996): rin ended ---------------------------;
,I/jxcore-log( 2996): 2015-12-03T14:07:10.525Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2996): 
,I/wpa_supplicant( 3073): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2996): Started service discovery
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2996): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7616"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7616"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT7616, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT7616, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 2996): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6183","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6183","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6183, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6183, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 2996): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2326"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2326"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2326, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2326, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,W/bt-btif ( 3056): dm_pm_timer expires
W/bt-btif ( 3056): dm_pm_timer expires 0
W/bt-btif ( 3056): proc dm_pm_timer expires
,I/jxcore-log( 2996): 2015-12-03T14:07:20.613Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:07:20.614Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:07:20.615Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:07:20.616Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:07:20.617Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2996): 
,I/BtToSocketBase( 2996): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 2996): Disconnect outgoing peer: samsung-SM-G900F_PT411
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
,I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
,I/BtToSocketBase( 2996): Close bt in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
I/BtToRequestSocket( 2996): Close server socket
,W/bt-btif ( 3056): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,I/        ( 2996): Cleared service requests
I/        ( 2996): Started peer discovery
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2996): Found 9 peers.
I/SS      ( 2996): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2996): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2996): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2996): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2996): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2996): Peer(6): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2996): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2996): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2996): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2996): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2996): Added service request
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2996): Started service discovery
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2996): 2015-12-03T14:07:25.617Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:07:25.624Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/jxcore-log( 2996): 2015-12-03T14:07:30.632Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:07:30.633Z SendDataConnector.js: Connect (retry count 4) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:07:30.633Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:07:30.634Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: B0:C5:59:3F:75:69, name: Thali Test (Galaxy S5)
,I/        ( 2996): Connecting to Thali Test (Galaxy S5), at B0:C5:59:3F:75:69
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: Thali Test (Galaxy S5)
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2996): Starting to Handshake
I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2996): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/BTConnectToThread( 2996): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 2996): Got JSON from encryption:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT411","ra":"B0:C5:59:3F:75:69"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2996): HandshakeOk : samsung-SM-G900F_PT411
I/HS      ( 2996): Hand Shake finished outgoing for : samsung-SM-G900F_PT411
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : false, samsung-SM-G900F_PT411
,I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2996): mHTTPPort  set to : 59406
I/BtConnectorHelper( 2996): Request socket is using : 59406
I/BtToRequestSocket( 2996): Now accepting connections
,I/BtConnectorHelper( 2996): Calling ConnectionStatusUpdate with port :59406
I/jxcore-log( 2996): 2015-12-03T14:07:33.523Z SendDataConnector.js: CLIENT connected to 59406, error: null
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:07:33.524Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): incoming data from: /127.0.0.1, port: 59406
I/BtToRequestSocket( 2996): Set local streams
I/BtToRequestSocket( 2996): rin ended ---------------------------;
,I/jxcore-log( 2996): 2015-12-03T14:07:33.553Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2996): 
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3056): dm_pm_timer expires
W/bt-btif ( 3056): dm_pm_timer expires 0
W/bt-btif ( 3056): proc dm_pm_timer expires
,I/jxcore-log( 2996): 2015-12-03T14:07:43.617Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:07:43.618Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:07:43.627Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:07:43.642Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:07:43.643Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:07:43.643Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/BtConnectorHelper( 2996): Disconnect outgoing peer: B0:C5:59:3F:75:69
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
,I/BtToSocketBase( 2996): Close bt in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
I/BtToRequestSocket( 2996): Close server socket
I/jxcore-log( 2996): 2015-12-03T14:07:43.679Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 2996): 
I/jxcore-log( 2996): ---- round done--------
I/jxcore-log( 2996): 
I/jxcore-log( 2996): ---- gotta redo : B0:C5:59:3F:75:69, try count now: 1
I/jxcore-log( 2996): 
I/jxcore-log( 2996): do fake peer & start
I/jxcore-log( 2996): 
I/jxcore-log( 2996): Connect to fake peer: 80:01:84:8A:B3:68
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:07:43.680Z SendDataConnector.js: Start called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:07:43.680Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:07:43.680Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: 80:01:84:8A:B3:68, name: null
,I/        ( 2996): Connecting to null, at 80:01:84:8A:B3:68
I/jxcore-log( 2996): 2015-12-03T14:07:43.683Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2996): 
,I/chromium( 2996): [INFO:CONSOLE(63)] "logCallback Round of send data to peer B0:C5:59:3F:75:69 done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db24c rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3056): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3056): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db24c rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db414 rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 1
E/bt-btif ( 3056): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3056): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 0
,D/BluetoothAdapterProperties( 3056): Failed to remove device: 80:01:84:8A:B3:68
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3056): StableState(): Entering Off State
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2996): Starting to Handshake
,I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2996): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/BTConnectToThread( 2996): got MESSAGE_READ 84 bytes.
I/BTConnectToThread( 2996): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9389"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2996): HandshakeOk : HTC-HTC Desire 820_PT9389
I/HS      ( 2996): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT9389
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT9389
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2996): mHTTPPort  set to : 49127
I/BtConnectorHelper( 2996): Request socket is using : 49127
I/BtToRequestSocket( 2996): Now accepting connections
,I/BtConnectorHelper( 2996): Calling ConnectionStatusUpdate with port :49127
I/jxcore-log( 2996): 2015-12-03T14:07:47.934Z SendDataConnector.js: CLIENT connected to 49127, error: null
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:07:47.935Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): incoming data from: /127.0.0.1, port: 49127
I/BtToRequestSocket( 2996): Set local streams
I/BtToRequestSocket( 2996): rin ended ---------------------------;
,I/jxcore-log( 2996): 2015-12-03T14:07:47.956Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: Thali Test (Galaxy S5)
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db414 rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,D/        ( 3056): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:402
,I/jxcore-log( 2996): 2015-12-03T14:07:49.154Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:07:49.225Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:07:49.253Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:07:49.312Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:07:49.436Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:07:49.499Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:07:49.579Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:07:49.686Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:07:49.748Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2996): 
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3056): dm_pm_timer expires
W/bt-btif ( 3056): dm_pm_timer expires 0
,W/bt-btif ( 3056): proc dm_pm_timer expires
,I/jxcore-log( 2996): 2015-12-03T14:07:59.748Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:07:59.749Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:07:59.750Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:07:59.754Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:07:59.759Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2996): 
,I/BtToSocketBase( 2996): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2996): Disconnect outgoing peer: HTC-HTC Desire 820_PT9389
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
I/BtToRequestSocket( 2996): Close server socket
,W/bt-btif ( 3056): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 2996): 2015-12-03T14:08:04.757Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:08:04.758Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:08:09.761Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:08:09.762Z SendDataConnector.js: Connect (retry count 1) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:08:09.763Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:08:09.763Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820
,I/        ( 2996): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [80:01:84:8a:b3:68]: 7, f, 610c
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: HTC Desire 820
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2996): Starting to Handshake
,I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2996): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/BTConnectToThread( 2996): got MESSAGE_READ 84 bytes.
I/BTConnectToThread( 2996): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9389"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2996): HandshakeOk : HTC-HTC Desire 820_PT9389
I/HS      ( 2996): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT9389
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT9389
,I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2996): mHTTPPort  set to : 55674
I/BtConnectorHelper( 2996): Request socket is using : 55674
I/BtToRequestSocket( 2996): Now accepting connections
,I/BtConnectorHelper( 2996): Calling ConnectionStatusUpdate with port :55674
I/jxcore-log( 2996): 2015-12-03T14:08:13.756Z SendDataConnector.js: CLIENT connected to 55674, error: null
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:08:13.757Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): incoming data from: /127.0.0.1, port: 55674
I/BtToRequestSocket( 2996): Set local streams
,I/BtToRequestSocket( 2996): rin ended ---------------------------;
,I/jxcore-log( 2996): 2015-12-03T14:08:13.785Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2996): 
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3056): dm_pm_timer expires
W/bt-btif ( 3056): dm_pm_timer expires 0
W/bt-btif ( 3056): proc dm_pm_timer expires
,I/        ( 2996): Cleared service requests
I/        ( 2996): Started peer discovery
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2996): Found 10 peers.
I/SS      ( 2996): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2996): Peer(2): Note4-1 92:b6:86:43:73:1c
,I/SS      ( 2996): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 2996): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2996): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2996): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2996): Peer(7): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2996): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2996): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2996): Peer(10): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2996): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2996): Added service request
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2996): 2015-12-03T14:08:23.847Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:08:23.847Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:08:23.849Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:08:23.850Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:08:23.854Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2996): 
,I/BtToSocketBase( 2996): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2996): Disconnect outgoing peer: HTC-HTC Desire 820_PT9389
I/BtToSocketBase( 2996): Stop ReceivingThread
,I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
,I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
I/BtToRequestSocket( 2996): Close server socket
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2996): Started service discovery
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 3056): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
,I/jxcore-log( 2996): 2015-12-03T14:08:28.854Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:08:28.855Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:08:33.858Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:08:33.859Z SendDataConnector.js: Connect (retry count 2) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:08:33.859Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:08:33.865Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820
,I/        ( 2996): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db414 rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,E/BluetoothRemoteDevices( 3056): aclStateChangeCallback: Device is NULL
W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db5dc rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 1
E/bt-btif ( 3056): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3056): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 0
,D/BluetoothAdapterProperties( 3056): Failed to remove device: 58:2A:F7:ED:96:BE
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3056): StableState(): Entering Off State
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db414 rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2996): we got incoming connection
,I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
I/BTListenerThread( 2996): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db5dc rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2996): got MESSAGE_READ 80 bytes.
I/BTListenerThread( 2996): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT7421","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2996): MESSAGE_WRITE 77 bytes.
I/HS      ( 2996): Incoming connection Hand Shake finished for : HUAWEI-ALE-L21_PT7421
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : true, HUAWEI-ALE-L21_PT7421
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BTConnectedThread
I/BtConnectorHelper( 2996): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2996): --DoOneRunRound started
,I/jxcore-log( 2996): 2015-12-03T14:08:38.065Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): LocalHost address: localhost/127.0.0.1, port: 46930
I/BtToRequestSocket( 2996): --DoOneRunRound ended
,I/jxcore-log( 2996): 2015-12-03T14:08:38.746Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:08:38.760Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:08:38.766Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:08:38.790Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:08:38.798Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:08:38.810Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:08:38.859Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:08:38.892Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:08:38.905Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:08:38.944Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:08:38.982Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:08:39.029Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:08:39.053Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:08:39.092Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:08:39.107Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:08:39.114Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:08:39.130Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:08:39.162Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:08:39.243Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:08:39.296Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:08:39.325Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:08:39.374Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:08:39.409Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:08:39.437Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:08:39.475Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:08:39.494Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:08:39.509Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:08:39.543Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:08:39.549Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2996): 
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btif ( 3056): DISCOVERY_COMP_EVT slot id:16, failed to find channle,                                       status:1, scn:0
E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 3056): invalid rfc slot id: 16
,I/BTConnectToThread( 2996): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2996): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2996): 2015-12-03T14:08:47.284Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:08:47.285Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:08:47.286Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2996): 
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: HTC Desire 820
,W/bt-btif ( 3056): invalid rfc slot id: 4
,I/BtToSocketBase( 2996): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT7421
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT7421
I/BtToSocketBase( 2996): Close LocalOutputStream
,I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
,I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/BtToSocketBase( 2996): Close bt in
I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/jxcore-log( 2996): 2015-12-03T14:08:49.902Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2996): 
,W/bt-rfcomm( 3056): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
,W/bt-rfcomm( 3056): RFCOMM_DisconnectInd LCID:0x49
,I/jxcore-log( 2996): 2015-12-03T14:08:52.287Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:08:52.288Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: ALE-L21
,I/jxcore-log( 2996): 2015-12-03T14:08:57.293Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:08:57.294Z SendDataConnector.js: Connect (retry count 3) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:08:57.295Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:08:57.295Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820
,I/        ( 2996): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [58:2a:f7:ed:96:be]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: ALE-L21
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2996): we got incoming connection
I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
I/BTListenerThread( 2996): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/BTListenerThread( 2996): got MESSAGE_READ 80 bytes.
I/BTListenerThread( 2996): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT7421","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2996): MESSAGE_WRITE 77 bytes.
I/HS      ( 2996): Incoming connection Hand Shake finished for : HUAWEI-ALE-L21_PT7421
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : true, HUAWEI-ALE-L21_PT7421
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BTConnectedThread
I/BtConnectorHelper( 2996): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2996): --DoOneRunRound started
,I/jxcore-log( 2996): 2015-12-03T14:09:00.777Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): LocalHost address: localhost/127.0.0.1, port: 46930
I/BtToRequestSocket( 2996): --DoOneRunRound ended
,I/jxcore-log( 2996): 2015-12-03T14:09:01.352Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:01.764Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:02.994Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:03.344Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2996): 
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2996): 2015-12-03T14:09:04.639Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:04.707Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2996): 
,W/bt-btif ( 3056): invalid rfc slot id: 17
,I/BtToSocketBase( 2996): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT7421
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2996): 2015-12-03T14:09:11.635Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2996): 
,W/bt-rfcomm( 3056): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
W/bt-rfcomm( 3056): RFCOMM_DisconnectInd LCID:0x4c
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: ALE-L21
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: ALE-L21
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2996): we got incoming connection
I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
I/BTListenerThread( 2996): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/BTListenerThread( 2996): got MESSAGE_READ 80 bytes.
I/BTListenerThread( 2996): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT7421","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2996): MESSAGE_WRITE 77 bytes.
I/HS      ( 2996): Incoming connection Hand Shake finished for : HUAWEI-ALE-L21_PT7421
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : true, HUAWEI-ALE-L21_PT7421
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BTConnectedThread
I/BtConnectorHelper( 2996): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2996): --DoOneRunRound started
,I/BtToRequestSocket( 2996): LocalHost address: localhost/127.0.0.1, port: 46930
,I/jxcore-log( 2996): 2015-12-03T14:09:23.352Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): --DoOneRunRound ended
,I/        ( 2996): Cleared service requests
I/        ( 2996): Started peer discovery
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2996): 2015-12-03T14:09:23.813Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:23.818Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:23.838Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:23.846Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2996): 
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2996): Found 6 peers.
I/SS      ( 2996): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2996): Peer(2): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2996): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2996): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2996): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2996): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2996): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2996): Added service request
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [80:01:84:8a:b3:68]: 6, 10f, 608
,I/wpa_supplicant( 3073): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2996): Started service discovery
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: HTC Desire 820
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2996): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4866","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4866","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT4866, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT4866, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db414 rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-l2cap( 3056): L2CAP - con rsp - bad ID. Exp: 5 Got: 3
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2996): Starting to Handshake
I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/BTConnectToThread( 2996): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db414 rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 2996): got MESSAGE_READ 84 bytes.
I/BTConnectToThread( 2996): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9389"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2996): HandshakeOk : HTC-HTC Desire 820_PT9389
I/HS      ( 2996): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT9389
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT9389
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2996): mHTTPPort  set to : 59065
,I/BtConnectorHelper( 2996): Request socket is using : 59065
I/BtToRequestSocket( 2996): Now accepting connections
,I/BtConnectorHelper( 2996): Calling ConnectionStatusUpdate with port :59065
I/jxcore-log( 2996): 2015-12-03T14:09:31.042Z SendDataConnector.js: CLIENT connected to 59065, error: null
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:09:31.043Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): incoming data from: /127.0.0.1, port: 59065
I/BtToRequestSocket( 2996): Set local streams
I/BtToRequestSocket( 2996): rin ended ---------------------------;
,I/jxcore-log( 2996): 2015-12-03T14:09:31.070Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db5dc rs_disc_pending=0
,W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3056): invalid rfc slot id: 19
,I/BtToSocketBase( 2996): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT7421
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2996): 2015-12-03T14:09:33.745Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db5dc rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3056): rfc_find_lcid_mcb LCID reused LCID:0x4e current:0x0
W/bt-rfcomm( 3056): RFCOMM_DisconnectInd LCID:0x4e
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db414 rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 3056): dm_pm_timer expires
W/bt-btif ( 3056): dm_pm_timer expires 0
W/bt-btif ( 3056): proc dm_pm_timer expires
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: ALE-L21
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
E/BluetoothRemoteDevices( 3056): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db7a4 rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/        ( 2996): Cleared service requests
I/        ( 2996): Started peer discovery
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db414 rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
E/bt-btif ( 3056): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3056): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 3056): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3056): StableState(): Entering Off State
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2996): we got incoming connection
,I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2996): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db7a4 rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2996): 2015-12-03T14:09:41.145Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:09:41.146Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:09:41.147Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:09:41.148Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:09:41.149Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2996): 
,I/BtToSocketBase( 2996): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2996): Disconnect outgoing peer: HTC-HTC Desire 820_PT9389
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
I/BtToRequestSocket( 2996): Close server socket
,W/bt-btif ( 3056): bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db7a4 rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2996): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 2996): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5769","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2996): MESSAGE_WRITE 77 bytes.
I/HS      ( 2996): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT5769
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : true, samsung-SM-G900F_PT5769
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BTConnectedThread
I/BtConnectorHelper( 2996): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2996): --DoOneRunRound started
,I/jxcore-log( 2996): 2015-12-03T14:09:41.578Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): LocalHost address: localhost/127.0.0.1, port: 46930
,I/BtToRequestSocket( 2996): --DoOneRunRound ended
,I/jxcore-log( 2996): 2015-12-03T14:09:42.749Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:42.918Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:42.948Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:42.989Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:43.053Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:43.084Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:43.090Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:43.095Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:43.104Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:43.178Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:43.308Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:43.357Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:43.468Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:43.553Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:43.626Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:43.686Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:43.722Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:43.765Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:43.786Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:43.802Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:43.833Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:43.838Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:43.873Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:43.917Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:43.941Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:43.982Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:43.990Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:44.117Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 2996): 
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: P2P: Reject scan trigger since one is already pending
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2996): 2015-12-03T14:09:44.559Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 2996): 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2996): Found 4 peers.
I/SS      ( 2996): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2996): Peer(2): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2996): Peer(3): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2996): Peer(4): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2996): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2996): Added service request
,I/jxcore-log( 2996): 2015-12-03T14:09:44.861Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:44.873Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:44.918Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:44.925Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:44.965Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:44.975Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:45.014Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:45.021Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:45.026Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:45.065Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:45.079Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 2996): 
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [58:2a:f7:ed:96:be]: 0, 0, 0
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2996): 2015-12-03T14:09:45.135Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:45.147Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 2996): 
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: ALE-L21
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db7a4 rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2996): 2015-12-03T14:09:45.481Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/jxcore-log( 2996): 2015-12-03T14:09:45.545Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 2996): 
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: HTC Desire 820
,I/wpa_supplicant( 3073): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2996): Started service discovery
,I/jxcore-log( 2996): 2015-12-03T14:09:45.646Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:45.727Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 2996): 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2996): we got incoming connection
I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2996): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/jxcore-log( 2996): 2015-12-03T14:09:45.961Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:45.995Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:46.149Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:09:46.150Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db5dc rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2996): got MESSAGE_READ 80 bytes.
I/BTListenerThread( 2996): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT7421","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2996): MESSAGE_WRITE 77 bytes.
I/HS      ( 2996): Incoming connection Hand Shake finished for : HUAWEI-ALE-L21_PT7421
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : true, HUAWEI-ALE-L21_PT7421
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BTConnectedThread
I/BtConnectorHelper( 2996): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2996): --DoOneRunRound started
,I/jxcore-log( 2996): 2015-12-03T14:09:46.314Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): LocalHost address: localhost/127.0.0.1, port: 46930
,I/BtToRequestSocket( 2996): --DoOneRunRound ended
,I/        ( 2996): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5769","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5769","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5769, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5769, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/jxcore-log( 2996): 2015-12-03T14:09:46.753Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:46.788Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:46.795Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:46.802Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:09:46.828Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2996): 
,I/        ( 2996): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7616"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7616"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT7616, peerAddress: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT7616, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 2996): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6183","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6183","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6183, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6183, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 2996): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2226","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2226","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT2226, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT2226, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db7a4 rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2996): 2015-12-03T14:09:51.153Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:09:51.154Z SendDataConnector.js: Connect (retry count 4) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:09:51.156Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:09:51.156Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820
,I/        ( 2996): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db5dc rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: HTC Desire 820
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db414 rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db7a4 rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2996): Starting to Handshake
,I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2996): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db414 rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 2996): got MESSAGE_READ 84 bytes.
I/BTConnectToThread( 2996): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9389"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2996): HandshakeOk : HTC-HTC Desire 820_PT9389
I/HS      ( 2996): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT9389
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT9389
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2996): mHTTPPort  set to : 51170
I/BtConnectorHelper( 2996): Request socket is using : 51170
I/BtToRequestSocket( 2996): Now accepting connections
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BtToSocketBase( 2996): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT5769
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,W/bt-btif ( 3056): invalid rfc slot id: 20
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2996): 2015-12-03T14:09:55.623Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2996): 
,W/bt-rfcomm( 3056): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0
W/bt-rfcomm( 3056): RFCOMM_DisconnectInd LCID:0x41
,I/BtConnectorHelper( 2996): Calling ConnectionStatusUpdate with port :51170
I/jxcore-log( 2996): 2015-12-03T14:09:55.868Z SendDataConnector.js: CLIENT connected to 51170, error: null
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:09:55.868Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): incoming data from: /127.0.0.1, port: 51170
I/BtToRequestSocket( 2996): Set local streams
,I/BtToRequestSocket( 2996): rin ended ---------------------------;
,I/jxcore-log( 2996): 2015-12-03T14:09:55.883Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db414 rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3056): invalid rfc slot id: 21
,I/BtToSocketBase( 2996): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT7421
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2996): 2015-12-03T14:09:57.089Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2996): 
,W/bt-rfcomm( 3056): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
W/bt-rfcomm( 3056): RFCOMM_DisconnectInd LCID:0x44
,I/        ( 2996): Cleared service requests
I/        ( 2996): Started peer discovery
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: S5-1
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: P2P: Reject scan trigger since one is already pending
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,W/bt-btif ( 3056): dm_pm_timer expires
W/bt-btif ( 3056): dm_pm_timer expires 1
W/bt-btif ( 3056): proc dm_pm_timer expires
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 2996): Found 5 peers.
I/SS      ( 2996): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2996): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2996): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2996): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2996): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2996): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2996): Added service request
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: ALE-L21
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2996): Started service discovery
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db414 rs_disc_pending=1
,W/bt-btif ( 3056): invalid rfc slot id: 23
,I/BtToSocketBase( 2996): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): Disconnect outgoing peer: HTC-HTC Desire 820_PT9389
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
I/BtToRequestSocket( 2996): Close server socket
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: HTC Desire 820
,I/        ( 2996): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2326"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2326"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2326, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2326, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 2996): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5769","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5769","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5769, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5769, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 2996): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7616"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7616"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT7616, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT7616, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 2996): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6183","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6183","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6183, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6183, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/jxcore-log( 2996): 2015-12-03T14:10:05.955Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:10:05.956Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:10:05.957Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:10:05.974Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:10:05.974Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:10:05.975Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:10:05.978Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 2996): 
I/jxcore-log( 2996): ---- round done--------
I/jxcore-log( 2996): 
I/jxcore-log( 2996): ---- gotta redo : 80:01:84:8A:B3:68, try count now: 1
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): do fake peer & start
I/jxcore-log( 2996): 
I/jxcore-log( 2996): Connect to fake peer: F8:95:C7:87:85:54
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:10:05.988Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:10:05.993Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:10:05.994Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 2996): Connecting to null, at F8:95:C7:87:85:54
I/jxcore-log( 2996): 2015-12-03T14:10:06.010Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2996): 
I/chromium( 2996): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 80:01:84:8A:B3:68 done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 3056): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [7c:f9:0e:34:8a:a0]: 7, 1d, 7d3
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: S5-1
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db7a4 rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 3056): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3056): Entering PendingCommandState State
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: ALE-L21
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db7a4 rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2996): we got incoming connection
I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
I/BTListenerThread( 2996): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3056): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3056): StableState(): Entering Off State
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db5dc rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2996): got MESSAGE_READ 80 bytes.
I/BTListenerThread( 2996): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT7421","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2996): MESSAGE_WRITE 77 bytes.
I/HS      ( 2996): Incoming connection Hand Shake finished for : HUAWEI-ALE-L21_PT7421
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : true, HUAWEI-ALE-L21_PT7421
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BTConnectedThread
,I/BtConnectorHelper( 2996): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2996): --DoOneRunRound started
,I/jxcore-log( 2996): 2015-12-03T14:10:09.368Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): LocalHost address: localhost/127.0.0.1, port: 46930
,I/BtToRequestSocket( 2996): --DoOneRunRound ended
,I/jxcore-log( 2996): 2015-12-03T14:10:09.791Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:10:09.853Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:10:09.904Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:10:09.971Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:10:10.039Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2996): 
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2996): we got incoming connection
,I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
I/BTListenerThread( 2996): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db5dc rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db96c rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db7a4 rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2996): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 2996): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5769","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2996): MESSAGE_WRITE 77 bytes.
I/HS      ( 2996): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT5769
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : true, samsung-SM-G900F_PT5769
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BTConnectedThread
I/BtConnectorHelper( 2996): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2996): --DoOneRunRound started
,I/BtToRequestSocket( 2996): LocalHost address: localhost/127.0.0.1, port: 46930
I/BtToRequestSocket( 2996): --DoOneRunRound ended
,I/jxcore-log( 2996): 2015-12-03T14:10:11.010Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2996): 
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2996): Starting to Handshake
I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2996): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/jxcore-log( 2996): 2015-12-03T14:10:11.717Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:10:11.763Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:10:11.769Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:10:11.909Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:10:11.919Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db96c rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db7a4 rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 2996): got MESSAGE_READ 77 bytes.
,I/BTConnectToThread( 2996): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2226","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2996): HandshakeOk : LGE-LG-D722_PT2226
I/HS      ( 2996): Hand Shake finished outgoing for : LGE-LG-D722_PT2226
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : false, LGE-LG-D722_PT2226
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 2996): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2996): mHTTPPort  set to : 34731
,I/BtConnectorHelper( 2996): Request socket is using : 34731
I/BtToRequestSocket( 2996): Now accepting connections
,I/BtConnectorHelper( 2996): Calling ConnectionStatusUpdate with port :34731
I/jxcore-log( 2996): 2015-12-03T14:10:13.822Z SendDataConnector.js: CLIENT connected to 34731, error: null
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:10:13.822Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): incoming data from: /127.0.0.1, port: 34731
I/BtToRequestSocket( 2996): Set local streams
I/BtToRequestSocket( 2996): rin ended ---------------------------;
,I/jxcore-log( 2996): 2015-12-03T14:10:13.879Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:10:15.106Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:10:15.507Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:10:15.824Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:10:15.985Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2996): 
,I/        ( 2996): Cleared service requests
I/        ( 2996): Started peer discovery
,I/jxcore-log( 2996): 2015-12-03T14:10:16.707Z SendDataConnector.js: CLIENT is data received : 50000,
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:10:16.884Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:10:17.048Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:10:17.190Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:10:17.510Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db5dc rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3056): invalid rfc slot id: 22
,I/BtToSocketBase( 2996): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT7421
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2996): 2015-12-03T14:10:19.804Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db5dc rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3056): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
W/bt-rfcomm( 3056): RFCOMM_DisconnectInd LCID:0x4b
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2996): Found 7 peers.
I/SS      ( 2996): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2996): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2996): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2996): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2996): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
,W/bt-btif ( 3056): invalid rfc slot id: 25
,I/BtToSocketBase( 2996): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT5769
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
,I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/SS      ( 2996): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2996): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,I/jxcore-log( 2996): 2015-12-03T14:10:21.963Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2996): 
D/WifiP2pManager( 2996): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2996): Added service request
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db5dc rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3056): dm_pm_timer expires
W/bt-btif ( 3056): dm_pm_timer expires 0
,W/bt-btif ( 3056): proc dm_pm_timer expires
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2996): Started service discovery
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-rfcomm( 3056): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
W/bt-rfcomm( 3056): RFCOMM_DisconnectInd LCID:0x4c
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: ALE-L21
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db7a4 rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: S5-1
,I/jxcore-log( 2996): 2015-12-03T14:10:27.511Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:10:27.511Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:10:27.514Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:10:27.515Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:10:27.516Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2996): 
,I/BtToSocketBase( 2996): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2996): Disconnect outgoing peer: LGE-LG-D722_PT2226
I/BtToSocketBase( 2996): Stop ReceivingThread
,I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
,I/BtToSocketBase( 2996): Close bt in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
I/BtToRequestSocket( 2996): Close server socket
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db96c rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3056): bta_jv_rfc_port_to_cb(port_handle:0x19):jv handle:0x0 not FOUND
,I/jxcore-log( 2996): 2015-12-03T14:10:32.516Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:10:32.517Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 2996): 
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: S5-1
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db7a4 rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-btm  ( 3056): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db96c rs_disc_pending=2
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: G3s-1
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2996): we got incoming connection
I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2996): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/BTListenerThread( 2996): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 2996): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5769","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 2996): MESSAGE_WRITE 77 bytes.
I/HS      ( 2996): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT5769
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : true, samsung-SM-G900F_PT5769
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BTConnectedThread
I/BtConnectorHelper( 2996): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2996): --DoOneRunRound started
,I/BtToRequestSocket( 2996): LocalHost address: localhost/127.0.0.1, port: 46930
I/BtToRequestSocket( 2996): --DoOneRunRound ended
,I/jxcore-log( 2996): 2015-12-03T14:10:33.520Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:10:34.025Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:10:34.035Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:10:34.043Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2996): 
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2996): 2015-12-03T14:10:37.526Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:10:37.526Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:10:37.527Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:10:37.527Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 2996): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db7a4 rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: G3s-1
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db96c rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db96c rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 3056): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3056): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3056): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3056): StableState(): Entering Off State
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2996): Starting to Handshake
I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2996): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db96c rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 2996): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 2996): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2226","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2996): HandshakeOk : LGE-LG-D722_PT2226
I/HS      ( 2996): Hand Shake finished outgoing for : LGE-LG-D722_PT2226
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : false, LGE-LG-D722_PT2226
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2996): mHTTPPort  set to : 60907
I/BtConnectorHelper( 2996): Request socket is using : 60907
I/BtToRequestSocket( 2996): Now accepting connections
,I/BtConnectorHelper( 2996): Calling ConnectionStatusUpdate with port :60907
,I/jxcore-log( 2996): 2015-12-03T14:10:43.405Z SendDataConnector.js: CLIENT connected to 60907, error: null
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:10:43.406Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): incoming data from: /127.0.0.1, port: 60907
I/BtToRequestSocket( 2996): Set local streams
I/BtToRequestSocket( 2996): rin ended ---------------------------;
,I/jxcore-log( 2996): 2015-12-03T14:10:43.426Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2996): 
,W/bt-btif ( 3056): invalid rfc slot id: 26
,I/BtToSocketBase( 2996): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT5769
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2996): 2015-12-03T14:10:44.412Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2996): 
,W/bt-rfcomm( 3056): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
W/bt-rfcomm( 3056): RFCOMM_DisconnectInd LCID:0x4a
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3056): dm_pm_timer expires
W/bt-btif ( 3056): dm_pm_timer expires 0
W/bt-btif ( 3056): proc dm_pm_timer expires
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: S5-1
,I/jxcore-log( 2996): 2015-12-03T14:10:53.489Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:10:53.489Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:10:53.496Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:10:53.497Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:10:53.498Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2996): 
,I/BtToSocketBase( 2996): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2996): Disconnect outgoing peer: LGE-LG-D722_PT2226
,I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
,I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
I/BtToRequestSocket( 2996): Close server socket
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db96c rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3056): bta_jv_rfc_port_to_cb(port_handle:0x1d):jv handle:0x0 not FOUND
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: S5-1
,I/art     (  733): Explicit concurrent mark sweep GC freed 34762(1596KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/42MB, paused 1.060ms total 72.601ms
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db96c rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2996): we got incoming connection
I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
I/BTListenerThread( 2996): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/BTListenerThread( 2996): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 2996): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5769","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2996): MESSAGE_WRITE 77 bytes.
I/HS      ( 2996): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT5769
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : true, samsung-SM-G900F_PT5769
,I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BTConnectedThread
,I/BtConnectorHelper( 2996): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2996): --DoOneRunRound started
,I/jxcore-log( 2996): 2015-12-03T14:10:55.698Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): LocalHost address: localhost/127.0.0.1, port: 46930
,I/BtToRequestSocket( 2996): --DoOneRunRound ended
,I/jxcore-log( 2996): 2015-12-03T14:10:56.205Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:10:56.217Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:10:56.227Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db96c rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: G3s-1
,I/jxcore-log( 2996): 2015-12-03T14:10:58.498Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:10:58.498Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:11:03.504Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:11:03.505Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:11:03.505Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:11:03.506Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 2996): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: G3s-1
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db96c rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db96c rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 3056): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3056): Entering PendingCommandState State
,W/bt-btif ( 3056): invalid rfc slot id: 27
,I/BtToSocketBase( 2996): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT5769
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2996): 2015-12-03T14:11:06.335Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2996): 
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3056): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3056): StableState(): Entering Off State
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db96c rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2996): Starting to Handshake
I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2996): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db96c rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 2996): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 2996): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2226","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2996): HandshakeOk : LGE-LG-D722_PT2226
,I/HS      ( 2996): Hand Shake finished outgoing for : LGE-LG-D722_PT2226
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : false, LGE-LG-D722_PT2226
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2996): mHTTPPort  set to : 39876
I/BtConnectorHelper( 2996): Request socket is using : 39876
,I/BtToRequestSocket( 2996): Now accepting connections
,I/BtConnectorHelper( 2996): Calling ConnectionStatusUpdate with port :39876
I/jxcore-log( 2996): 2015-12-03T14:11:07.267Z SendDataConnector.js: CLIENT connected to 39876, error: null
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:11:07.267Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): incoming data from: /127.0.0.1, port: 39876
I/BtToRequestSocket( 2996): Set local streams
,I/BtToRequestSocket( 2996): rin ended ---------------------------;
,I/jxcore-log( 2996): 2015-12-03T14:11:07.291Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2996): 
,W/bt-rfcomm( 3056): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
W/bt-rfcomm( 3056): RFCOMM_DisconnectInd LCID:0x43
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: S5-1
,W/bt-btif ( 3056): dm_pm_timer expires
W/bt-btif ( 3056): dm_pm_timer expires 0
W/bt-btif ( 3056): proc dm_pm_timer expires
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: S5-1
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2996): we got incoming connection
I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
I/BTListenerThread( 2996): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/BTListenerThread( 2996): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 2996): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5769","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2996): MESSAGE_WRITE 77 bytes.
I/HS      ( 2996): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT5769
I/BtConnectorHelper( 2996): Starting the connected thread incoming : true, samsung-SM-G900F_PT5769
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BTConnectedThread
I/BtConnectorHelper( 2996): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2996): --DoOneRunRound started
,I/BtToRequestSocket( 2996): LocalHost address: localhost/127.0.0.1, port: 46930
I/BtToRequestSocket( 2996): --DoOneRunRound ended
,I/jxcore-log( 2996): 2015-12-03T14:11:16.979Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:11:17.357Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:11:17.358Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:11:17.359Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:11:17.360Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:11:17.368Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2996): 
,I/BtToSocketBase( 2996): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2996): Disconnect outgoing peer: LGE-LG-D722_PT2226
,I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
I/BtToRequestSocket( 2996): Close server socket
,I/jxcore-log( 2996): 2015-12-03T14:11:17.496Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:11:17.505Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db96c rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2996): 2015-12-03T14:11:17.698Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:11:17.758Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:11:17.765Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db96c rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3056): bta_jv_rfc_port_to_cb(port_handle:0x1):jv handle:0x0 not FOUND
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 2996): Cleared service requests
I/        ( 2996): Started peer discovery
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2996): 2015-12-03T14:11:22.367Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:11:22.369Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: G3s-1
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2996): Found 7 peers.
I/SS      ( 2996): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2996): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2996): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2996): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2996): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2996): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2996): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2996): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2996): Added service request
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2996): Started service discovery
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2996): 2015-12-03T14:11:27.374Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:11:27.375Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:11:27.376Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:11:27.376Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 2996): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3056): invalid rfc slot id: 29
,I/BtToSocketBase( 2996): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT5769
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2996): 2015-12-03T14:11:27.830Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2996): 
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: G3s-1
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db7a4 rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3056): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
W/bt-rfcomm( 3056): RFCOMM_DisconnectInd LCID:0x45
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db96c rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 3056): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3056): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3056): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3056): StableState(): Entering Off State
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2996): Starting to Handshake
I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2996): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/BTConnectToThread( 2996): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 2996): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2226","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2996): HandshakeOk : LGE-LG-D722_PT2226
,I/HS      ( 2996): Hand Shake finished outgoing for : LGE-LG-D722_PT2226
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : false, LGE-LG-D722_PT2226
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BtConnectedRequestSocket
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2996): mHTTPPort  set to : 38102
I/BtConnectorHelper( 2996): Request socket is using : 38102
I/BtToRequestSocket( 2996): Now accepting connections
,I/BtConnectorHelper( 2996): Calling ConnectionStatusUpdate with port :38102
,I/jxcore-log( 2996): 2015-12-03T14:11:31.395Z SendDataConnector.js: CLIENT connected to 38102, error: null
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:11:31.396Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): incoming data from: /127.0.0.1, port: 38102
I/BtToRequestSocket( 2996): Set local streams
I/BtToRequestSocket( 2996): rin ended ---------------------------;
,I/jxcore-log( 2996): 2015-12-03T14:11:31.415Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db7a4 rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db96c rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: S5-1
,I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db96c rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3056): dm_pm_timer expires
W/bt-btif ( 3056): dm_pm_timer expires 0
W/bt-btif ( 3056): proc dm_pm_timer expires
,I/jxcore-log( 2996): 2015-12-03T14:11:41.482Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:11:41.482Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:11:41.484Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:11:41.484Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:11:41.485Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2996): 
,I/BtToSocketBase( 2996): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2996): Disconnect outgoing peer: LGE-LG-D722_PT2226
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
,I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
I/BtToRequestSocket( 2996): Close server socket
,W/bt-btif ( 3056): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,I/jxcore-log( 2996): 2015-12-03T14:11:46.485Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:11:46.486Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: G3s-1
,I/jxcore-log( 2996): 2015-12-03T14:11:51.490Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:11:51.492Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:11:51.492Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:11:51.493Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 2996): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: G3s-1
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: Thali Test (Galaxy S5)
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db24c rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/        ( 2996): Cleared service requests
I/        ( 2996): Started peer discovery
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2996): Found 9 peers.
I/SS      ( 2996): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2996): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2996): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2996): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2996): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 2996): Peer(6): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2996): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2996): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2996): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2996): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2996): Added service request
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2996): we got incoming connection
,I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2996): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2996): Started service discovery
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db24c rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db24c rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2996): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 2996): Got JSON from encryption:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT411","ra":"B0:C5:59:3F:75:69"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2996): MESSAGE_WRITE 77 bytes.
I/HS      ( 2996): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT411
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : true, samsung-SM-G900F_PT411
,I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BTConnectedThread
,I/BtConnectorHelper( 2996): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2996): --DoOneRunRound started
,I/jxcore-log( 2996): 2015-12-03T14:12:25.538Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): LocalHost address: localhost/127.0.0.1, port: 46930
,I/BtToRequestSocket( 2996): --DoOneRunRound ended
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 2996): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3634","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3634","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT3634, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT3634, WifiDirectName: , WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/jxcore-log( 2996): 2015-12-03T14:12:26.534Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:26.542Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:26.568Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:26.577Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:26.587Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:26.622Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:26.660Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:26.666Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:26.700Z SendDataTCPServer.js: TCP/IP server has received 18092 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:26.772Z SendDataTCPServer.js: TCP/IP server has received 20072 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:26.911Z SendDataTCPServer.js: TCP/IP server has received 22052 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:27.135Z SendDataTCPServer.js: TCP/IP server has received 24032 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:27.236Z SendDataTCPServer.js: TCP/IP server has received 26012 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:27.244Z SendDataTCPServer.js: TCP/IP server has received 29972 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:27.303Z SendDataTCPServer.js: TCP/IP server has received 31952 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:27.333Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:27.365Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:27.378Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:27.420Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:27.432Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:27.462Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:27.486Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:27.524Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:27.533Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:27.539Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:27.558Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:27.579Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:27.613Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:27.622Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:27.629Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:27.639Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:27.675Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:27.679Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:27.712Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:27.747Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 2996): 
,I/        ( 2996): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5769","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5769","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5769, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5769, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/jxcore-log( 2996): 2015-12-03T14:12:27.797Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:27.801Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:27.808Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:27.855Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:27.859Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:28.177Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 2996): 
I/        ( 2996): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT411","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT411","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT411, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT411, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/jxcore-log( 2996): 2015-12-03T14:12:28.217Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:28.222Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2996): 
,I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/        ( 2996): Cleared service requests
I/        ( 2996): Started peer discovery
,W/bt-btif ( 3056): invalid rfc slot id: 31
,I/BtToSocketBase( 2996): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT411
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
,I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT411
I/BtToSocketBase( 2996): Close bt in
I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/jxcore-log( 2996): 2015-12-03T14:12:38.252Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db24c rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3056): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
W/bt-rfcomm( 3056): RFCOMM_DisconnectInd LCID:0x46
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db24c rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2996): Found 5 peers.
I/SS      ( 2996): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2996): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2996): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2996): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2996): Peer(5): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2996): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2996): Added service request
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/wpa_supplicant( 3073): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2996): Started service discovery
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: Thali Test (Galaxy S5)
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db24c rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2996): we got incoming connection
,I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
I/BTListenerThread( 2996): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/BTListenerThread( 2996): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 2996): Got JSON from encryption:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT411","ra":"B0:C5:59:3F:75:69"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2996): MESSAGE_WRITE 77 bytes.
I/HS      ( 2996): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT411
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : true, samsung-SM-G900F_PT411
,I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BTConnectedThread
,I/BtConnectorHelper( 2996): Server socket is using : 0, and is now connected.
,I/BtConnection( 2996): connectionTimeoutTimer
,I/BTConnectToThread( 2996): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3056): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:33, channel:8
,W/bt-btif ( 3056): invalid rfc slot id: 33
,I/CONNEC  ( 2996): Error: Cancelled
I/CONNEC  ( 2996): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2996): 2015-12-03T14:12:51.526Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:12:51.526Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:51.540Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:12:51.541Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:12:51.541Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2996): 
I/jxcore-log( 2996): ---- round done--------
I/jxcore-log( 2996): 
I/jxcore-log( 2996): ---- gotta redo : F8:95:C7:87:85:54, try count now: 1
I/jxcore-log( 2996): 
I/jxcore-log( 2996): do fake peer & start
I/jxcore-log( 2996): 
I/jxcore-log( 2996): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:12:51.542Z SendDataConnector.js: Start called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:12:51.542Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:12:51.542Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): --DoOneRunRound started
,I/        ( 2996): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 2996): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
I/jxcore-log( 2996): 2015-12-03T14:12:51.546Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:51.546Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:12:51.547Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2996): 
I/chromium( 2996): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F8:95:C7:87:85:54 done with result: Connection to F8:95:C7:87:85:54 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BtToRequestSocket( 2996): LocalHost address: localhost/127.0.0.1, port: 46930
I/BtToRequestSocket( 2996): --DoOneRunRound ended
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 2996): 2015-12-03T14:12:51.553Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2996): 
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db24c rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2996): 2015-12-03T14:12:53.293Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:53.364Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:53.431Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:53.504Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:53.578Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:12:53.853Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2996): 
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: ALE-L21
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db24c rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2996): 2015-12-03T14:12:56.548Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:12:56.549Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2996): 
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db5dc rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-l2cap( 3056): L2CAP - con rsp - bad ID. Exp: 5 Got: 3
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db5dc rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2996): Starting to Handshake
,I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2996): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/jxcore-log( 2996): 2015-12-03T14:13:01.553Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:13:01.554Z SendDataConnector.js: Connect (retry count 1) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:13:01.555Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:13:01.555Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread disconnected: java.io.IOException: bt socket closed, read return: -1
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/        ( 2996): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 2996): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db5dc rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3056): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,W/bt-btif ( 3056): invalid rfc slot id: 34
,I/BtToSocketBase( 2996): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT411
,I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT411
I/BtToSocketBase( 2996): Close bt in
I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/BtToSocketBase( 2996): Close bt in
,I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/jxcore-log( 2996): 2015-12-03T14:13:03.051Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db5dc rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2996): Starting to Handshake
,I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2996): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/BTConnectToThread( 2996): got MESSAGE_READ 80 bytes.
I/BTConnectToThread( 2996): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT7421","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2996): HandshakeOk : HUAWEI-ALE-L21_PT7421
I/HS      ( 2996): Hand Shake finished outgoing for : HUAWEI-ALE-L21_PT7421
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : false, HUAWEI-ALE-L21_PT7421
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2996): mHTTPPort  set to : 55206
I/BtConnectorHelper( 2996): Request socket is using : 55206
I/BtToRequestSocket( 2996): Now accepting connections
,I/BtConnectorHelper( 2996): Calling ConnectionStatusUpdate with port :55206
I/jxcore-log( 2996): 2015-12-03T14:13:04.208Z SendDataConnector.js: CLIENT connected to 55206, error: null
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:13:04.208Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): incoming data from: /127.0.0.1, port: 55206
I/BtToRequestSocket( 2996): Set local streams
I/BtToRequestSocket( 2996): rin ended ---------------------------;
,I/jxcore-log( 2996): 2015-12-03T14:13:04.234Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2996): 
,D/        ( 3056): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24978
,I/jxcore-log( 2996): 2015-12-03T14:13:05.076Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db24c rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3056): rfc_find_lcid_mcb LCID reused LCID:0x4e current:0x0
,W/bt-rfcomm( 3056): RFCOMM_DisconnectInd LCID:0x4e
,I/jxcore-log( 2996): 2015-12-03T14:13:05.602Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2996): 
,D/        ( 3056): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14088
,I/jxcore-log( 2996): 2015-12-03T14:13:05.654Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:13:06.022Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2996): 
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
D/        ( 3056): cod is 0, set as unclassified
,I/BluetoothBondStateMachine( 3056): sspRequestCallback: [B@6385e47 name: [B@4a3f674 cod: 7936 pairingVariant 0 passkey: 431927
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3056): Entering PendingCommandState State
,D/        ( 3056): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4188
,I/jxcore-log( 2996): 2015-12-03T14:13:08.302Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:13:08.754Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:13:08.772Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:13:09.110Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/jxcore-log( 2996): 2015-12-03T14:13:09.273Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2996): 
,I/BluetoothClassifier( 1423): Bluetooth Device Name: Thali Test (Galaxy S5)
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: Thali Test (Galaxy S5)
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db24c rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3056): dm_pm_timer expires
W/bt-btif ( 3056): dm_pm_timer expires 0
W/bt-btif ( 3056): proc dm_pm_timer expires
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2996): we got incoming connection
,I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2996): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db24c rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db24c rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2996): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 2996): Got JSON from encryption:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT411","ra":"B0:C5:59:3F:75:69"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2996): MESSAGE_WRITE 77 bytes.
I/HS      ( 2996): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT411
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : true, samsung-SM-G900F_PT411
,I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BTConnectedThread
,I/BtConnectorHelper( 2996): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2996): --DoOneRunRound started
,I/jxcore-log( 2996): 2015-12-03T14:13:16.873Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): LocalHost address: localhost/127.0.0.1, port: 46930
,I/BtToRequestSocket( 2996): --DoOneRunRound ended
,I/jxcore-log( 2996): 2015-12-03T14:13:17.436Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:13:17.445Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:13:17.484Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:13:17.507Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:13:17.546Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:13:19.273Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:13:19.274Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:13:19.275Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:13:19.276Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:13:19.277Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2996): 
,I/BtToSocketBase( 2996): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2996): Disconnect outgoing peer: HUAWEI-ALE-L21_PT7421
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
,I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
I/BtToRequestSocket( 2996): Close server socket
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db24c rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3056): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,I/jxcore-log( 2996): 2015-12-03T14:13:24.276Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:13:24.277Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: ALE-L21
,W/bt-btif ( 3056): invalid rfc slot id: 35
,I/BtToSocketBase( 2996): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT411
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2996): 2015-12-03T14:13:27.481Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2996): 
,W/bt-rfcomm( 3056): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
W/bt-rfcomm( 3056): RFCOMM_DisconnectInd LCID:0x44
,I/jxcore-log( 2996): 2015-12-03T14:13:29.282Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:13:29.283Z SendDataConnector.js: Connect (retry count 2) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:13:29.284Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:13:29.284Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 2996): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: ALE-L21
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: Thali Test (Galaxy S5)
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db5dc rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-l2cap( 3056): L2CAP - con rsp - bad ID. Exp: 5 Got: 3
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 3056): invalid rfc slot id: 39
,I/BTConnectToThread( 2996): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2996): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2996): 2015-12-03T14:13:37.043Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:13:37.044Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:13:37.045Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2996): 
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: ALE-L21
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: Thali Test (Galaxy S5)
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2996): we got incoming connection
,I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
I/BTListenerThread( 2996): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/BTListenerThread( 2996): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 2996): Got JSON from encryption:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT411","ra":"B0:C5:59:3F:75:69"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2996): MESSAGE_WRITE 77 bytes.
I/HS      ( 2996): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT411
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : true, samsung-SM-G900F_PT411
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BTConnectedThread
I/BtConnectorHelper( 2996): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2996): --DoOneRunRound started
,I/BtToRequestSocket( 2996): LocalHost address: localhost/127.0.0.1, port: 46930
,I/jxcore-log( 2996): 2015-12-03T14:13:39.578Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): --DoOneRunRound ended
,I/jxcore-log( 2996): 2015-12-03T14:13:40.173Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:13:40.180Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:13:40.187Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:13:40.208Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:13:40.218Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2996): 
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 2996): Cleared service requests
I/        ( 2996): Started peer discovery
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2996): 2015-12-03T14:13:42.046Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:13:42.047Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2996): 
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btif ( 3056): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 9 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3056): Failed to remove device: F8:95:C7:87:85:54
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3056): StableState(): Entering Off State
,I/SS      ( 2996): Found 4 peers.
I/SS      ( 2996): Peer(1): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2996): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2996): Peer(3): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 2996): Peer(4): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2996): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2996): Added service request
,W/bt-btm  ( 3056): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db96c rs_disc_pending=2
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
E/bt-btif ( 3056): Do not find the bg connection mask for the remote device
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: G3s-1
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2996): Started service discovery
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2996): 2015-12-03T14:13:47.050Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:13:47.052Z SendDataConnector.js: Connect (retry count 3) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:13:47.053Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:13:47.053Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 2996): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [58:2a:f7:ed:96:be]: 6, f, 410d
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: ALE-L21
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db5dc rs_disc_pending=1
,W/bt-btif ( 3056): bta_dm_check_av:0
W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,I/        ( 2996): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3634","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3634","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT3634, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT3634, WifiDirectName: , WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,W/bt-btif ( 3056): invalid rfc slot id: 38
,I/BtToSocketBase( 2996): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT411
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2996): 2015-12-03T14:13:50.402Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2996): 
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2996): Starting to Handshake
I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2996): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/BTConnectToThread( 2996): got MESSAGE_READ 80 bytes.
I/BTConnectToThread( 2996): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT7421","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2996): HandshakeOk : HUAWEI-ALE-L21_PT7421
,I/HS      ( 2996): Hand Shake finished outgoing for : HUAWEI-ALE-L21_PT7421
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : false, HUAWEI-ALE-L21_PT7421
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2996): mHTTPPort  set to : 56409
I/BtConnectorHelper( 2996): Request socket is using : 56409
,I/BtToRequestSocket( 2996): Now accepting connections
,I/BtConnectorHelper( 2996): Calling ConnectionStatusUpdate with port :56409
,I/jxcore-log( 2996): 2015-12-03T14:13:50.970Z SendDataConnector.js: CLIENT connected to 56409, error: null
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:13:50.974Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): incoming data from: /127.0.0.1, port: 56409
I/BtToRequestSocket( 2996): Set local streams
I/BtToRequestSocket( 2996): rin ended ---------------------------;
,I/jxcore-log( 2996): 2015-12-03T14:13:51.008Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2996): 
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db5dc rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3056): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 3056): RFCOMM_DisconnectInd LCID:0x47
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: Thali Test (Galaxy S5)
,W/bt-btif ( 3056): dm_pm_timer expires
W/bt-btif ( 3056): dm_pm_timer expires 0
W/bt-btif ( 3056): proc dm_pm_timer expires
,I/        ( 2996): Cleared service requests
I/        ( 2996): Started peer discovery
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2996): 2015-12-03T14:14:01.068Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:14:01.068Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:14:01.069Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:01.080Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:14:01.081Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2996): 
,I/BtToSocketBase( 2996): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2996): Disconnect outgoing peer: HUAWEI-ALE-L21_PT7421
I/BtToSocketBase( 2996): Stop ReceivingThread
,I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
,I/BtToSocketBase( 2996): Close bt in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
I/BtToRequestSocket( 2996): Close server socket
,I/SS      ( 2996): Found 7 peers.
I/SS      ( 2996): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2996): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2996): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2996): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2996): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2996): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2996): Peer(7): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2996): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2996): Added service request
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,W/bt-btif ( 3056): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,I/BluetoothClassifier( 1423): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db24c rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/        ( 2996): Started service discovery
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db5dc rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/        ( 2996): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4866","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4866","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT4866, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT4866, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2996): we got incoming connection
I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2996): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db24c rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db24c rs_disc_pending=0
,W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2996): got MESSAGE_READ 81 bytes.
,I/BTListenerThread( 2996): Got JSON from encryption:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT411","ra":"B0:C5:59:3F:75:69"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2996): MESSAGE_WRITE 77 bytes.
I/HS      ( 2996): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT411
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : true, samsung-SM-G900F_PT411
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BTConnectedThread
I/BtConnectorHelper( 2996): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2996): --DoOneRunRound started
,I/jxcore-log( 2996): 2015-12-03T14:14:04.491Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): LocalHost address: localhost/127.0.0.1, port: 46930
,I/BtToRequestSocket( 2996): --DoOneRunRound ended
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2996): 2015-12-03T14:14:05.095Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:05.290Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:05.301Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:05.366Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:05.428Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:05.512Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:06.082Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:14:06.083Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2996): 
,I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: ALE-L21
,I/jxcore-log( 2996): 2015-12-03T14:14:11.087Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:14:11.088Z SendDataConnector.js: Connect (retry count 4) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:14:11.088Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:14:11.089Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 2996): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db24c rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/        ( 2996): Cleared service requests
I/        ( 2996): Started peer discovery
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: ALE-L21
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 2996): Found 6 peers.
I/SS      ( 2996): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2996): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2996): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2996): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2996): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2996): Peer(6): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2996): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2996): Added service request
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2996): Started service discovery
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 2996): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4866","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4866","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT4866, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT4866, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,W/bt-btif ( 3056): dm_pm_timer expires
W/bt-btif ( 3056): dm_pm_timer expires 0
W/bt-btif ( 3056): proc dm_pm_timer expires
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db5dc rs_disc_pending=1
W/bt-rfcomm( 3056): PORT_StartCnf failed result:5
E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): invalid rfc slot id: 43
,I/BTConnectToThread( 2996): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3056): onReceive
,I/CONNEC  ( 2996): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2996): 2015-12-03T14:14:21.512Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:14:21.513Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:21.542Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:14:21.543Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:14:21.546Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): ---- round done--------
I/jxcore-log( 2996): 
I/jxcore-log( 2996): ---- gotta redo : 58:2A:F7:ED:96:BE, try count now: 1
I/jxcore-log( 2996): 
I/jxcore-log( 2996): do fake peer & start
I/jxcore-log( 2996): 
I/jxcore-log( 2996): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:14:21.549Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:14:21.549Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:21.550Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 2996): Connecting to null, at 08:EC:A9:50:75:41
I/chromium( 2996): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 58:2A:F7:ED:96:BE done with result: Connection to 58:2A:F7:ED:96:BE failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: ALE-L21
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db24c rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/BtToSocketBase( 2996): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,W/bt-btif ( 3056): invalid rfc slot id: 40
,I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT411
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2996): 2015-12-03T14:14:22.478Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2996): 
,W/bt-rfcomm( 3056): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
,W/bt-rfcomm( 3056): RFCOMM_DisconnectInd LCID:0x4d
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/        ( 2996): Cleared service requests
I/        ( 2996): Started peer discovery
,W/bt-sdp  ( 3056): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 3056): DISCOVERY_COMP_EVT slot id:44, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3056): invalid rfc slot id: 44
,I/BTConnectToThread( 2996): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2996): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2996): 2015-12-03T14:14:26.787Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:14:26.788Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:14:26.788Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2996): 
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 2996): Found 7 peers.
I/SS      ( 2996): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2996): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2996): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2996): Peer(4): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2996): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2996): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2996): Peer(7): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2996): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2996): Added service request
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 2996): 2015-12-03T14:14:31.788Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:14:31.788Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2996): 
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2996): Started service discovery
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2996): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1913","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 2996): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1913","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT1913, peerAddress: 08:EC:A9:50:75:41
,I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT1913, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 2996): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4866","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4866","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT4866, peerAddress: 44:80:EB:7B:5A:05
,I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT4866, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/EventLogService( 1561): Aggregate from 1449151173440 (log), 1449149632735 (data)
,I/        ( 2996): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT7904","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 2996): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT7904","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT7904, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT7904, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/        ( 2996): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7616"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7616"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT7616, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT7616, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 2996): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5769","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5769","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5769, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5769, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 2996): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3634","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 2996): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3634","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT3634, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT3634, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 2996): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9389"}, typeCordovap2p._tcp.local.:
,I/        ( 2996): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9389"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9389, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9389, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/jxcore-log( 2996): 2015-12-03T14:14:36.793Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:36.794Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:14:36.801Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:14:36.801Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 2996): Connecting to null, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3056): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
E/bt-btif ( 3056): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3056): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 3056): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3056): StableState(): Entering Off State
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2996): Starting to Handshake
I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2996): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/BTConnectToThread( 2996): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 2996): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1913","ra":"08:EC:A9:50:75:41"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2996): HandshakeOk : samsung-SM-A300FU_PT1913
I/HS      ( 2996): Hand Shake finished outgoing for : samsung-SM-A300FU_PT1913
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : false, samsung-SM-A300FU_PT1913
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2996): mHTTPPort  set to : 43059
I/BtConnectorHelper( 2996): Request socket is using : 43059
I/BtToRequestSocket( 2996): Now accepting connections
,I/BtConnectorHelper( 2996): Calling ConnectionStatusUpdate with port :43059
,I/jxcore-log( 2996): 2015-12-03T14:14:42.293Z SendDataConnector.js: CLIENT connected to 43059, error: null
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:14:42.295Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): incoming data from: /127.0.0.1, port: 43059
I/BtToRequestSocket( 2996): Set local streams
I/BtToRequestSocket( 2996): rin ended ---------------------------;
,I/jxcore-log( 2996): 2015-12-03T14:14:42.314Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2996): 
,D/        ( 3056): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24978
,I/jxcore-log( 2996): 2015-12-03T14:14:43.050Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2996): 
,D/        ( 3056): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:16068
,I/jxcore-log( 2996): 2015-12-03T14:14:43.114Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:43.155Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2996): 
,D/        ( 3056): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:10128
,I/jxcore-log( 2996): 2015-12-03T14:14:43.171Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:43.206Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:43.266Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:43.428Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:43.573Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:43.603Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:14:43.604Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:43.620Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:14:43.621Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/BtConnectorHelper( 2996): Disconnect outgoing peer: 08:EC:A9:50:75:41
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
I/BtToRequestSocket( 2996): Close server socket
I/jxcore-log( 2996): 2015-12-03T14:14:43.655Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 2996): 
I/jxcore-log( 2996): ---- round done--------
I/jxcore-log( 2996): 
I/jxcore-log( 2996): do fake peer & start
I/jxcore-log( 2996): 
I/jxcore-log( 2996): Connect to fake peer: F4:F1:E1:5C:3B:E2
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:14:43.658Z SendDataConnector.js: Start called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:14:43.659Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:14:43.659Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,W/bt-btif ( 3056): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,I/        ( 2996): Selected device address: F4:F1:E1:5C:3B:E2, name: null
,I/        ( 2996): Connecting to null, at F4:F1:E1:5C:3B:E2
I/chromium( 2996): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 08:EC:A9:50:75:41 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db96c rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3056): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dbb34 rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 1
E/bt-btif ( 3056): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3056): Entering PendingCommandState State
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db96c rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 0
,D/BluetoothAdapterProperties( 3056): Failed to remove device: F4:F1:E1:5C:3B:E2
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3056): StableState(): Entering Off State
,I/        ( 2996): Cleared service requests
I/        ( 2996): Started peer discovery
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: A3-1
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2996): Found 9 peers.
I/SS      ( 2996): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2996): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2996): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2996): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2996): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2996): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 2996): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2996): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2996): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2996): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2996): Added service request
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2996): Started service discovery
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-l2cap( 3056): L2CAP - no CCB for conn rsp, LCID: 66 RCID: 64
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2996): Starting to Handshake
,I/BTListenerThread( 2996): we got incoming connection
I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
I/BTListenerThread( 2996): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2996): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
I/BTListenerThread( 2996): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 2996): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7616"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
I/BTConnectToThread( 2996): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 2996): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7616"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2996): HandshakeOk : motorola-XT1039_PT7616
I/HS      ( 2996): Hand Shake finished outgoing for : motorola-XT1039_PT7616
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : false, motorola-XT1039_PT7616
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BtConnectedRequestSocket
,I/BTListenerThread( 2996): MESSAGE_WRITE 77 bytes.
I/HS      ( 2996): Incoming connection Hand Shake finished for : motorola-XT1039_PT7616
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : true, motorola-XT1039_PT7616
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BTConnectedThread
I/BtConnectorHelper( 2996): Server socket is using : 0, and is now connected.
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2996): mHTTPPort  set to : 56950
I/BtConnectorHelper( 2996): Request socket is using : 56950
I/BtToRequestSocket( 2996): Now accepting connections
I/BtToRequestSocket( 2996): --DoOneRunRound started
,I/BtToRequestSocket( 2996): LocalHost address: localhost/127.0.0.1, port: 46930
I/BtToRequestSocket( 2996): --DoOneRunRound ended
,I/jxcore-log( 2996): 2015-12-03T14:14:52.097Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2996): 
,I/BtConnectorHelper( 2996): Calling ConnectionStatusUpdate with port :56950
I/jxcore-log( 2996): 2015-12-03T14:14:52.392Z SendDataConnector.js: CLIENT connected to 56950, error: null
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:14:52.392Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): incoming data from: /127.0.0.1, port: 56950
I/BtToRequestSocket( 2996): Set local streams
I/BtToRequestSocket( 2996): rin ended ---------------------------;
,I/jxcore-log( 2996): 2015-12-03T14:14:52.413Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:52.964Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:53.003Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:53.022Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:53.030Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:53.034Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:53.040Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
,I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:53.046Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 2996): 
,D/        ( 3056): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 2996): 2015-12-03T14:14:53.073Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:53.081Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:53.112Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:53.124Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:53.162Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:53.180Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:53.278Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:53.288Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:53.296Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:53.305Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:53.373Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:53.480Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:53.599Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 2996): 
,D/        ( 3056): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8866
,I/jxcore-log( 2996): 2015-12-03T14:14:53.634Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:53.645Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:53.651Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:53.696Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:53.749Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:53.771Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:53.844Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:53.922Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:53.967Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:53.985Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:54.018Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:54.091Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:54.100Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:54.118Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:54.150Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:54.154Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:14:54.154Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:54.164Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:54.175Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:54.212Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:54.219Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:54.231Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:14:54.233Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:54.263Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:54.339Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:54.361Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:54.375Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:54.380Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:14:54.404Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2996): 
,W/bt-btif ( 3056): dm_pm_timer expires
W/bt-btif ( 3056): dm_pm_timer expires 0
W/bt-btif ( 3056): proc dm_pm_timer expires
,E/bt-btif ( 3056): bta_dm_pm_btm_status  hci_status=35
,I/jxcore-log( 2996): 2015-12-03T14:15:04.375Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:15:04.376Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:15:04.377Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:15:04.378Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:15:04.379Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2996): 
,I/BtToSocketBase( 2996): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2996): Disconnect outgoing peer: motorola-XT1039_PT7616
I/BtToSocketBase( 2996): Stop ReceivingThread
,I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
I/BtToRequestSocket( 2996): Close server socket
,W/bt-btif ( 3056): invalid rfc slot id: 42
,I/BtToSocketBase( 2996): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,W/bt-btif ( 3056): bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
,I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT7616
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT7616
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close bt in
I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/jxcore-log( 2996): 2015-12-03T14:15:04.651Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2996): 
,I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,I/jxcore-log( 2996): 2015-12-03T14:15:09.379Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:15:09.384Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: XT1039
,I/jxcore-log( 2996): 2015-12-03T14:15:14.388Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:15:14.389Z SendDataConnector.js: Connect (retry count 1) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:15:14.390Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:15:14.393Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: F4:F1:E1:5C:3B:E2, name: XT1039
,I/        ( 2996): Connecting to XT1039, at F4:F1:E1:5C:3B:E2
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3056): No ag scb for peer addr
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [f4:f1:e1:5c:3b:e2]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: XT1039,
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-l2cap( 3056): L2CAP - no CCB for conn rsp, LCID: 70 RCID: 74
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2996): Starting to Handshake
,I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2996): we got incoming connection
,I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
I/BTListenerThread( 2996): waiting to accept incoming Connection
,I/BTConnectToThread( 2996): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/BTConnectToThread( 2996): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 2996): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7616"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2996): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 2996): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7616"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 2996): HandshakeOk : motorola-XT1039_PT7616
I/HS      ( 2996): Hand Shake finished outgoing for : motorola-XT1039_PT7616
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BTListenerThread( 2996): MESSAGE_WRITE 77 bytes.
I/HS      ( 2996): Incoming connection Hand Shake finished for : motorola-XT1039_PT7616
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : false, motorola-XT1039_PT7616
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BtConnectedRequestSocket
I/BtConnectorHelper( 2996): Starting the connected thread incoming : true, motorola-XT1039_PT7616
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BTConnectedThread
I/BtConnectorHelper( 2996): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2996): mHTTPPort  set to : 59981
I/BtConnectorHelper( 2996): Request socket is using : 59981
I/BtToRequestSocket( 2996): Now accepting connections
,I/BtToRequestSocket( 2996): --DoOneRunRound started
,I/BtToRequestSocket( 2996): LocalHost address: localhost/127.0.0.1, port: 46930
I/BtToRequestSocket( 2996): --DoOneRunRound ended
,I/jxcore-log( 2996): 2015-12-03T14:15:21.806Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2996): 
,I/BtConnectorHelper( 2996): Calling ConnectionStatusUpdate with port :59981
I/jxcore-log( 2996): 2015-12-03T14:15:22.085Z SendDataConnector.js: CLIENT connected to 59981, error: null
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:15:22.085Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): incoming data from: /127.0.0.1, port: 59981
I/BtToRequestSocket( 2996): Set local streams
I/BtToRequestSocket( 2996): rin ended ---------------------------;
,I/jxcore-log( 2996): 2015-12-03T14:15:22.106Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:15:22.205Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:15:22.214Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:15:22.230Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2996): 
,W/bt-btif ( 3056): dm_pm_timer expires
W/bt-btif ( 3056): dm_pm_timer expires 0,
W/bt-btif ( 3056): proc dm_pm_timer expires
,I/jxcore-log( 2996): 2015-12-03T14:15:32.202Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:15:32.203Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:15:32.204Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:15:32.205Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:15:32.206Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2996): 
,I/BtToSocketBase( 2996): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2996): Disconnect outgoing peer: motorola-XT1039_PT7616
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
I/BtToRequestSocket( 2996): Close server socket
,W/bt-btif ( 3056): invalid rfc slot id: 47
,I/BtToSocketBase( 2996): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,W/bt-btif ( 3056): bta_jv_rfc_port_to_cb(port_handle:0x17):jv handle:0x0 not FOUND
,I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT7616
I/BtToSocketBase( 2996): Stop ReceivingThread
,I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT7616
I/BtToSocketBase( 2996): Close bt in
I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/jxcore-log( 2996): 2015-12-03T14:15:32.651Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2996): 
,I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,I/jxcore-log( 2996): 2015-12-03T14:15:37.206Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:15:37.207Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: XT1039
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [08:ec:a9:50:75:41]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: A3-1
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2996): we got incoming connection
I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
I/BTListenerThread( 2996): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/BTListenerThread( 2996): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 2996): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1913","ra":"08:EC:A9:50:75:41"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2996): MESSAGE_WRITE 77 bytes.
I/HS      ( 2996): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT1913
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : true, samsung-SM-A300FU_PT1913
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BTConnectedThread
I/BtConnectorHelper( 2996): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2996): --DoOneRunRound started
,I/jxcore-log( 2996): 2015-12-03T14:15:40.606Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): LocalHost address: localhost/127.0.0.1, port: 46930
I/BtToRequestSocket( 2996): --DoOneRunRound ended
,I/jxcore-log( 2996): 2015-12-03T14:15:41.435Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:15:41.443Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:15:41.450Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:15:41.457Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:15:41.467Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:15:41.511Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:15:41.544Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:15:41.558Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:15:41.595Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:15:41.615Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:15:41.653Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:15:41.666Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:15:41.711Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:15:41.724Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:15:41.736Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:15:41.762Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:15:41.774Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:15:41.810Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:15:41.842Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:15:41.857Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:15:41.893Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:15:42.210Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:15:42.211Z SendDataConnector.js: Connect (retry count 2) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:15:42.212Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:15:42.212Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: F4:F1:E1:5C:3B:E2, name: XT1039
,I/        ( 2996): Connecting to XT1039, at F4:F1:E1:5C:3B:E2
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db96c rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3056): No ag scb for peer addr
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: XT1039
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dbb34 rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 2996): Cleared service requests
I/        ( 2996): Started peer discovery
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2996): Found 6 peers.
I/SS      ( 2996): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2996): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2996): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2996): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2996): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2996): Peer(6): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 2996): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2996): Added service request
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2996): Started service discovery
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2996): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT7904","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT7904","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT7904, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT7904, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,W/bt-btif ( 3056): invalid rfc slot id: 49
,I/BtToSocketBase( 2996): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT1913
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2996): 2015-12-03T14:15:52.059Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2996): 
,W/bt-rfcomm( 3056): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
W/bt-rfcomm( 3056): RFCOMM_DisconnectInd LCID:0x4a
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: A3-1
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2996): Cleared service requests
I/        ( 2996): Started peer discovery
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2996): Found 7 peers.
I/SS      ( 2996): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2996): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2996): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2996): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2996): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2996): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2996): Peer(7): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 2996): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2996): Added service request
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2996): Started service discovery
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: A3-1
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2996): we got incoming connection
I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
I/BTListenerThread( 2996): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db96c rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2996): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 2996): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1913","ra":"08:EC:A9:50:75:41"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2996): MESSAGE_WRITE 77 bytes.
I/HS      ( 2996): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT1913
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : true, samsung-SM-A300FU_PT1913
,I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BTConnectedThread
,I/BtConnectorHelper( 2996): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2996): --DoOneRunRound started
,I/BtToRequestSocket( 2996): LocalHost address: localhost/127.0.0.1, port: 46930
,I/jxcore-log( 2996): 2015-12-03T14:16:03.687Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): --DoOneRunRound ended
,I/jxcore-log( 2996): 2015-12-03T14:16:04.119Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:16:04.128Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:16:04.162Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:16:04.176Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2996): 
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,W/bt-btif ( 3056): invalid rfc slot id: 50
,I/BtToSocketBase( 2996): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT1913
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2996): 2015-12-03T14:16:14.142Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2996): 
,W/bt-rfcomm( 3056): PORT_StartCnf failed result:5
E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 3056): invalid rfc slot id: 51
,I/BTConnectToThread( 2996): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2996): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2996): 2015-12-03T14:16:14.192Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:16:14.192Z SendDataConnector.js: CLIENT Can not Connect: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:16:14.193Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2996): 
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: XT1039
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db96c rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3056): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
W/bt-rfcomm( 3056): RFCOMM_DisconnectInd LCID:0x44
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: A3-1
,I/jxcore-log( 2996): 2015-12-03T14:16:19.195Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:16:19.195Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:16:24.199Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:16:24.203Z SendDataConnector.js: Connect (retry count 3) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:16:24.204Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:16:24.207Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: F4:F1:E1:5C:3B:E2, name: XT1039
,I/        ( 2996): Connecting to XT1039, at F4:F1:E1:5C:3B:E2
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3056): No ag scb for peer addr
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [f4:f1:e1:5c:3b:e2]: 7, 1d, 7d3
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: XT1039
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [08:ec:a9:50:75:41]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: A3-1
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2996): we got incoming connection
I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
I/BTListenerThread( 2996): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/BTListenerThread( 2996): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 2996): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1913","ra":"08:EC:A9:50:75:41"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2996): MESSAGE_WRITE 77 bytes.
I/HS      ( 2996): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT1913
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : true, samsung-SM-A300FU_PT1913
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BTConnectedThread
I/BtConnectorHelper( 2996): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2996): --DoOneRunRound started
,I/jxcore-log( 2996): 2015-12-03T14:16:26.765Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): LocalHost address: localhost/127.0.0.1, port: 46930
,I/BtToRequestSocket( 2996): --DoOneRunRound ended
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dbb34 rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2996): 2015-12-03T14:16:27.143Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:16:27.148Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:16:27.225Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:16:27.230Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2996): ,
,I/jxcore-log( 2996): 2015-12-03T14:16:27.240Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:16:27.261Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2996): 
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2996): we got incoming connection
I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
I/BTListenerThread( 2996): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2996): Starting to Handshake
,I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2996): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dbb34 rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2996): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 2996): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7616"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2996): MESSAGE_WRITE 77 bytes.
I/HS      ( 2996): Incoming connection Hand Shake finished for : motorola-XT1039_PT7616
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : true, motorola-XT1039_PT7616
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BTConnectedThread
,I/BTConnectToThread( 2996): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 2996): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7616"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2996): HandshakeOk : motorola-XT1039_PT7616
I/HS      ( 2996): Hand Shake finished outgoing for : motorola-XT1039_PT7616
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Server socket is using : 0, and is now connected.
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : false, motorola-XT1039_PT7616
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2996): mHTTPPort  set to : 57006
I/BtConnectorHelper( 2996): Request socket is using : 57006
I/BtToRequestSocket( 2996): Now accepting connections
,I/BtToRequestSocket( 2996): --DoOneRunRound started
,I/jxcore-log( 2996): 2015-12-03T14:16:29.069Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): LocalHost address: localhost/127.0.0.1, port: 46930
,I/BtToRequestSocket( 2996): --DoOneRunRound ended
,I/BtConnectorHelper( 2996): Calling ConnectionStatusUpdate with port :57006
I/jxcore-log( 2996): 2015-12-03T14:16:29.348Z SendDataConnector.js: CLIENT connected to 57006, error: null
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:16:29.348Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): incoming data from: /127.0.0.1, port: 57006
I/BtToRequestSocket( 2996): Set local streams
,I/BtToRequestSocket( 2996): rin ended ---------------------------;
,I/jxcore-log( 2996): 2015-12-03T14:16:29.360Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:16:29.552Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:16:29.559Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:16:29.590Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:16:29.596Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:16:29.602Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:16:29.620Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2996): 
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db96c rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3056): dm_pm_timer expires
W/bt-btif ( 3056): dm_pm_timer expires 1
W/bt-btif ( 3056): proc dm_pm_timer expires
,W/bt-btif ( 3056): invalid rfc slot id: 52,
,I/BtToSocketBase( 2996): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT1913
,I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT1913
I/BtToSocketBase( 2996): Close bt in
I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/jxcore-log( 2996): 2015-12-03T14:16:37.165Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db96c rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3056): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
W/bt-rfcomm( 3056): RFCOMM_DisconnectInd LCID:0x49
,I/jxcore-log( 2996): 2015-12-03T14:16:39.431Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:16:39.432Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:16:39.433Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:16:39.433Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:16:39.434Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2996): 
,I/BtToSocketBase( 2996): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2996): Disconnect outgoing peer: motorola-XT1039_PT7616
,I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
,I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
I/BtToRequestSocket( 2996): Close server socket
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: A3-1
,W/bt-btif ( 3056): bta_jv_rfc_port_to_cb(port_handle:0x1c):jv handle:0x0 not FOUND
,I/jxcore-log( 2996): 2015-12-03T14:16:44.433Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:16:44.434Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2996): 
,W/bt-btif ( 3056): dm_pm_timer expires
W/bt-btif ( 3056): dm_pm_timer expires 0
W/bt-btif ( 3056): proc dm_pm_timer expires
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: A3-1
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db96c rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2996): we got incoming connection
,I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2996): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db96c rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2996): 2015-12-03T14:16:49.437Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:16:49.438Z SendDataConnector.js: Connect (retry count 4) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:16:49.438Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:16:49.439Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: F4:F1:E1:5C:3B:E2, name: XT1039
,I/        ( 2996): Connecting to XT1039, at F4:F1:E1:5C:3B:E2
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/BTListenerThread( 2996): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 2996): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1913","ra":"08:EC:A9:50:75:41"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2996): MESSAGE_WRITE 77 bytes.
I/HS      ( 2996): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT1913
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : true, samsung-SM-A300FU_PT1913
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BTConnectedThread
I/BtConnectorHelper( 2996): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2996): --DoOneRunRound started
,I/BtToRequestSocket( 2996): LocalHost address: localhost/127.0.0.1, port: 46930
I/BtToRequestSocket( 2996): --DoOneRunRound ended
,I/jxcore-log( 2996): 2015-12-03T14:16:49.506Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:16:49.909Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:16:49.921Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:16:49.928Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2996): 
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3056): invalid rfc slot id: 54
,I/BtToSocketBase( 2996): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT7616
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2996): 2015-12-03T14:16:53.556Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2996): 
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,W/bt-btif ( 3056): invalid rfc slot id: 55
,I/BtToSocketBase( 2996): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT1913
,I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2996): 2015-12-03T14:17:00.371Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2996): 
,W/bt-rfcomm( 3056): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
W/bt-rfcomm( 3056): RFCOMM_DisconnectInd LCID:0x4c
,I/        ( 2996): Cleared service requests
I/        ( 2996): Started peer discovery
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-l2cap( 3056): L2CAP - con rsp - bad ID. Exp: 16 Got: 15
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: A3-1
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2996): Found 4 peers.
I/SS      ( 2996): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2996): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2996): Peer(3): S5-1 ee:1f:72:63:11:86
I/SS      ( 2996): Peer(4): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2996): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2996): Added service request
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2996): Started service discovery
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:255
,I/BTListenerThread( 2996): we got incoming connection
,I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
I/BTListenerThread( 2996): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:1
,I/BTConnectToThread( 2996): Starting to Handshake
,I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2996): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/BTListenerThread( 2996): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 2996): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7616"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2996): MESSAGE_WRITE 77 bytes.
I/HS      ( 2996): Incoming connection Hand Shake finished for : motorola-XT1039_PT7616
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : true, motorola-XT1039_PT7616
,I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BTConnectedThread
,I/BtConnectorHelper( 2996): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2996): --DoOneRunRound started
,I/jxcore-log( 2996): 2015-12-03T14:17:10.900Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): LocalHost address: localhost/127.0.0.1, port: 46930
,I/BtToRequestSocket( 2996): --DoOneRunRound ended
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: A3-1
,I/BTConnectToThread( 2996): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 2996): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7616"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2996): HandshakeOk : motorola-XT1039_PT7616
I/HS      ( 2996): Hand Shake finished outgoing for : motorola-XT1039_PT7616
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : false, motorola-XT1039_PT7616
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2996): mHTTPPort  set to : 39270
I/BtConnectorHelper( 2996): Request socket is using : 39270
I/BtToRequestSocket( 2996): Now accepting connections
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db96c rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/BtConnectorHelper( 2996): Calling ConnectionStatusUpdate with port :39270
I/jxcore-log( 2996): 2015-12-03T14:17:12.097Z SendDataConnector.js: CLIENT connected to 39270, error: null
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:17:12.097Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): incoming data from: /127.0.0.1, port: 39270
I/BtToRequestSocket( 2996): Set local streams
,I/BtToRequestSocket( 2996): rin ended ---------------------------;
,I/jxcore-log( 2996): 2015-12-03T14:17:12.122Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2996): 
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2996): we got incoming connection
I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
I/BTListenerThread( 2996): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db96c rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2996): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 2996): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1913","ra":"08:EC:A9:50:75:41"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2996): MESSAGE_WRITE 77 bytes.
I/HS      ( 2996): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT1913
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : true, samsung-SM-A300FU_PT1913
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BTConnectedThread
I/BtConnectorHelper( 2996): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2996): --DoOneRunRound started
,I/jxcore-log( 2996): 2015-12-03T14:17:13.711Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): LocalHost address: localhost/127.0.0.1, port: 46930
I/BtToRequestSocket( 2996): --DoOneRunRound ended
,I/jxcore-log( 2996): 2015-12-03T14:17:14.282Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:14.292Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:14.362Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:14.463Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:14.477Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:14.488Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2996): 
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2996): 2015-12-03T14:17:15.405Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:19.050Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:19.058Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:19.966Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:22.190Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:17:22.191Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:17:22.192Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:22.209Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:17:22.209Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:22.213Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
,I/BtConnectorHelper( 2996): Disconnect outgoing peer: F4:F1:E1:5C:3B:E2
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2996): Close LocalOutputStream
,I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
I/BtToRequestSocket( 2996): Close server socket
I/jxcore-log( 2996): 2015-12-03T14:17:22.245Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2996): 
I/jxcore-log( 2996): ---- round done--------
I/jxcore-log( 2996): 
I/jxcore-log( 2996): ---- gotta redo : F4:F1:E1:5C:3B:E2, try count now: 1
I/jxcore-log( 2996): 
I/jxcore-log( 2996): do fake peer & start
I/jxcore-log( 2996): 
I/jxcore-log( 2996): Connect to fake peer: F8:95:C7:87:3C:51
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:17:22.248Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:17:22.249Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:17:22.249Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: F8:95:C7:87:3C:51, name: null
,I/        ( 2996): Connecting to null, at F8:95:C7:87:3C:51
I/jxcore-log( 2996): 2015-12-03T14:17:22.273Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2996): 
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/chromium( 2996): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F4:F1:E1:5C:3B:E2 done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db96c rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 3056): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3056): invalid rfc slot id: 58
,I/BtToSocketBase( 2996): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT1913
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2996): 2015-12-03T14:17:24.292Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2996): 
,W/bt-rfcomm( 3056): rfc_find_lcid_mcb LCID reused LCID:0x4f current:0x0
W/bt-rfcomm( 3056): RFCOMM_DisconnectInd LCID:0x4f
E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dbcfc rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3056): bta_jv_rfc_port_to_cb(port_handle:0x7):jv handle:0x0 not FOUND
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41db96c rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3056): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3056): Entering PendingCommandState State
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: A3-1
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3056): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3056): StableState(): Entering Off State
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2996): Starting to Handshake
,I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2996): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/BTConnectToThread( 2996): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 2996): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3634","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2996): HandshakeOk : LGE-LG-H815_PT3634
I/HS      ( 2996): Hand Shake finished outgoing for : LGE-LG-H815_PT3634
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : false, LGE-LG-H815_PT3634
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2996): mHTTPPort  set to : 47455
I/BtConnectorHelper( 2996): Request socket is using : 47455
I/BtToRequestSocket( 2996): Now accepting connections
,I/BtConnectorHelper( 2996): Calling ConnectionStatusUpdate with port :47455
I/jxcore-log( 2996): 2015-12-03T14:17:30.492Z SendDataConnector.js: CLIENT connected to 47455, error: null
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:17:30.492Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): incoming data from: /127.0.0.1, port: 47455
I/BtToRequestSocket( 2996): Set local streams
I/BtToRequestSocket( 2996): rin ended ---------------------------;
,I/jxcore-log( 2996): 2015-12-03T14:17:30.514Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2996): 
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3056): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
E/bt-btif ( 3056): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3056): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/BluetoothAdapterProperties( 3056): Failed to remove device: 08:EC:A9:50:76:27
,I/jxcore-log( 2996): 2015-12-03T14:17:31.450Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2996): 
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3056): StableState(): Entering Off State
,I/jxcore-log( 2996): 2015-12-03T14:17:31.602Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2996): 
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2996): we got incoming connection
I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
I/BTListenerThread( 2996): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/BTListenerThread( 2996): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 2996): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2951","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2996): MESSAGE_WRITE 77 bytes.
I/HS      ( 2996): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT2951
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : true, samsung-SM-A300FU_PT2951
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BTConnectedThread
I/BtConnectorHelper( 2996): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2996): --DoOneRunRound started
,I/jxcore-log( 2996): 2015-12-03T14:17:31.790Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): LocalHost address: localhost/127.0.0.1, port: 46930
,I/BtToRequestSocket( 2996): --DoOneRunRound ended
,I/jxcore-log( 2996): 2015-12-03T14:17:32.129Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:32.496Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:32.508Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:32.518Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:32.560Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:32.592Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:32.615Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:32.642Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:32.672Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:32.707Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:32.742Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:32.773Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:32.782Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:32.794Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:32.823Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:32.918Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:32.925Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:32.931Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:33.079Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:33.112Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:33.166Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:33.279Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:33.354Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:33.365Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:33.410Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:33.417Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:33.426Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:33.517Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:33.544Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:33.551Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:33.665Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 2996): 
,W/bt-btif ( 3056): invalid rfc slot id: 56
,I/BtToSocketBase( 2996): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT7616
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2996): 2015-12-03T14:17:33.689Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:33.704Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:17:33.706Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:33.731Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:33.792Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:33.797Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2996): 
,W/bt-rfcomm( 3056): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
W/bt-rfcomm( 3056): RFCOMM_DisconnectInd LCID:0x4a
,I/jxcore-log( 2996): 2015-12-03T14:17:34.051Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:34.379Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:34.972Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:35.447Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2996): 
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: XT1039
,W/bt-btif ( 3056): dm_pm_timer expires
W/bt-btif ( 3056): dm_pm_timer expires 0
W/bt-btif ( 3056): proc dm_pm_timer expires
,I/jxcore-log( 2996): 2015-12-03T14:17:45.446Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:17:45.447Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:17:45.448Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:17:45.449Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:45.450Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2996): 
,I/BtToSocketBase( 2996): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2996): Disconnect outgoing peer: LGE-LG-H815_PT3634
,I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
,I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
I/BtToRequestSocket( 2996): Close server socket
,W/bt-btif ( 3056): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,W/bt-btif ( 3056): dm_pm_timer expires
W/bt-btif ( 3056): dm_pm_timer expires 1
W/bt-btif ( 3056): proc dm_pm_timer expires
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dbcfc rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: G4-1
,I/jxcore-log( 2996): 2015-12-03T14:17:50.449Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:50.449Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:55.450Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:17:55.450Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:17:55.451Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:17:55.451Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,I/        ( 2996): Connecting to G4-1, at F8:95:C7:87:3C:51
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [f8:95:c7:87:3c:51]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: G4-1
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dbcfc rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3056): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3056): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3056): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3056): StableState(): Entering Off State
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2996): Starting to Handshake
I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2996): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dbcfc rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 2996): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 2996): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3634","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 2996): HandshakeOk : LGE-LG-H815_PT3634
I/HS      ( 2996): Hand Shake finished outgoing for : LGE-LG-H815_PT3634
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : false, LGE-LG-H815_PT3634
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2996): mHTTPPort  set to : 56119
I/BtConnectorHelper( 2996): Request socket is using : 56119
I/BtToRequestSocket( 2996): Now accepting connections
,I/BtConnectorHelper( 2996): Calling ConnectionStatusUpdate with port :56119
,I/jxcore-log( 2996): 2015-12-03T14:17:57.505Z SendDataConnector.js: CLIENT connected to 56119, error: null
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:17:57.506Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): incoming data from: /127.0.0.1, port: 56119
I/BtToRequestSocket( 2996): Set local streams
I/BtToRequestSocket( 2996): rin ended ---------------------------;
,I/jxcore-log( 2996): 2015-12-03T14:17:57.526Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 3056): invalid rfc slot id: 59
,I/BtToSocketBase( 2996): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT2951
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2996): 2015-12-03T14:17:59.939Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2996): 
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: Thali Test (Galaxy A3)
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dbcfc rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3056): dm_pm_timer expires
W/bt-btif ( 3056): dm_pm_timer expires 0
,W/bt-btif ( 3056): proc dm_pm_timer expires
,I/        ( 2996): Cleared service requests
I/        ( 2996): Started peer discovery
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 2996): Found 3 peers.
I/SS      ( 2996): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2996): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2996): Peer(3): S5-1 ee:1f:72:63:11:86
,D/WifiP2pManager( 2996): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2996): Added service request
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2996): Started service discovery
,I/        ( 2996): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2951","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2951","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT2951, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT2951, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/jxcore-log( 2996): 2015-12-03T14:18:07.589Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:18:07.596Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:18:07.599Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:18:07.599Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:18:07.604Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2996): 
,I/BtToSocketBase( 2996): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2996): Disconnect outgoing peer: LGE-LG-H815_PT3634
,I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
,I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
I/BtToRequestSocket( 2996): Close server socket
,W/bt-btif ( 3056): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dbcfc rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: G4-1
,I/jxcore-log( 2996): 2015-12-03T14:18:12.603Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:18:12.604Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 2996): 
,I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,I/        ( 2996): Cleared service requests
I/        ( 2996): Started peer discovery
,I/jxcore-log( 2996): 2015-12-03T14:18:17.608Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:18:17.608Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:18:17.609Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:18:17.609Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,I/        ( 2996): Connecting to G4-1, at F8:95:C7:87:3C:51
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2996): Found 4 peers.
I/SS      ( 2996): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2996): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2996): Peer(3): S5-1 ee:1f:72:63:11:86
I/SS      ( 2996): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 2996): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2996): Added service request
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: G4-1
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,I/        ( 2996): Started service discovery
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3056): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3056): Entering PendingCommandState State
,I/        ( 2996): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT411","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT411","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT411, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT411, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3056): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3056): StableState(): Entering Off State
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2996): Starting to Handshake
,I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2996): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/BTConnectToThread( 2996): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 2996): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3634","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2996): HandshakeOk : LGE-LG-H815_PT3634
I/HS      ( 2996): Hand Shake finished outgoing for : LGE-LG-H815_PT3634
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : false, LGE-LG-H815_PT3634
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2996): mHTTPPort  set to : 57463
I/BtConnectorHelper( 2996): Request socket is using : 57463
I/BtToRequestSocket( 2996): Now accepting connections
,I/BtConnectorHelper( 2996): Calling ConnectionStatusUpdate with port :57463
I/jxcore-log( 2996): 2015-12-03T14:18:21.288Z SendDataConnector.js: CLIENT connected to 57463, error: null
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:18:21.288Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): incoming data from: /127.0.0.1, port: 57463
I/BtToRequestSocket( 2996): Set local streams
,I/BtToRequestSocket( 2996): rin ended ---------------------------;
,I/jxcore-log( 2996): 2015-12-03T14:18:21.313Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2996): 
,I/        ( 2996): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7616"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7616"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT7616, peerAddress: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT7616, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 2996): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3634","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3634","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT3634, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT3634, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 2996): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2951","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2951","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT2951, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT2951, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/UsageStatsService(  733): User[0] Flushing usage stats to disk
,W/bt-btif ( 3056): dm_pm_timer expires
W/bt-btif ( 3056): dm_pm_timer expires 0
W/bt-btif ( 3056): proc dm_pm_timer expires
,I/jxcore-log( 2996): 2015-12-03T14:18:31.389Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:18:31.390Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:18:31.391Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:18:31.392Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:18:31.393Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2996): 
,I/BtToSocketBase( 2996): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2996): Disconnect outgoing peer: LGE-LG-H815_PT3634
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
,I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
I/BtToRequestSocket( 2996): Close server socket
,W/bt-btif ( 3056): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2996): Cleared service requests
I/        ( 2996): Started peer discovery
,I/jxcore-log( 2996): 2015-12-03T14:18:36.392Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:18:36.393Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: G4-1
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2996): Found 8 peers.
I/SS      ( 2996): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2996): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2996): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2996): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2996): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2996): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2996): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2996): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2996): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2996): Added service request
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2996): Started service discovery
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2996): 2015-12-03T14:18:41.396Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:18:41.396Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:18:41.397Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:18:41.397Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,I/        ( 2996): Connecting to G4-1, at F8:95:C7:87:3C:51
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: G4-1
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: Thali Test (Galaxy A3)
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dbec4 rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2996): we got incoming connection
,I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2996): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dbec4 rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2996): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 2996): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2951","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2996): MESSAGE_WRITE 77 bytes.
I/HS      ( 2996): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT2951
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : true, samsung-SM-A300FU_PT2951
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BTConnectedThread
I/BtConnectorHelper( 2996): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2996): --DoOneRunRound started
,I/jxcore-log( 2996): 2015-12-03T14:19:07.995Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): LocalHost address: localhost/127.0.0.1, port: 46930
,I/BtToRequestSocket( 2996): --DoOneRunRound ended
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2996): 2015-12-03T14:19:08.407Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:08.419Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:08.558Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:08.574Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:08.601Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:08.725Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2996): 
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3056): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3056): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3056): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3056): StableState(): Entering Off State
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dbcfc rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2996): Starting to Handshake
,I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2996): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/BTConnectToThread( 2996): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 2996): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3634","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2996): HandshakeOk : LGE-LG-H815_PT3634
,I/HS      ( 2996): Hand Shake finished outgoing for : LGE-LG-H815_PT3634
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : false, LGE-LG-H815_PT3634
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2996): mHTTPPort  set to : 50859
I/BtConnectorHelper( 2996): Request socket is using : 50859
I/BtToRequestSocket( 2996): Now accepting connections
,I/BtConnectorHelper( 2996): Calling ConnectionStatusUpdate with port :50859
I/jxcore-log( 2996): 2015-12-03T14:19:10.242Z SendDataConnector.js: CLIENT connected to 50859, error: null
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:19:10.242Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): incoming data from: /127.0.0.1, port: 50859
I/BtToRequestSocket( 2996): Set local streams
I/BtToRequestSocket( 2996): rin ended ---------------------------;
,I/jxcore-log( 2996): 2015-12-03T14:19:10.264Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2996): 
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3056): dm_pm_timer expires
W/bt-btif ( 3056): dm_pm_timer expires 1
W/bt-btif ( 3056): proc dm_pm_timer expires
,W/bt-btif ( 3056): invalid rfc slot id: 61
,I/BtToSocketBase( 2996): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT2951
,I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2996): 2015-12-03T14:19:18.560Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:20.349Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:19:20.350Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:19:20.351Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:19:20.351Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:19:20.352Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2996): 
,I/BtToSocketBase( 2996): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2996): Disconnect outgoing peer: LGE-LG-H815_PT3634
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
,I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
I/BtToRequestSocket( 2996): Close server socket
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dbcfc rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3056): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: G4-1
,I/jxcore-log( 2996): 2015-12-03T14:19:25.352Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:19:25.353Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [08:ec:a9:50:76:27]: 7, f, 6109
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2996): we got incoming connection
I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
I/BTListenerThread( 2996): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/BTListenerThread( 2996): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 2996): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2951","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2996): MESSAGE_WRITE 77 bytes.
I/HS      ( 2996): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT2951
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : true, samsung-SM-A300FU_PT2951
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BTConnectedThread
I/BtConnectorHelper( 2996): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2996): --DoOneRunRound started
,I/jxcore-log( 2996): 2015-12-03T14:19:29.529Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): LocalHost address: localhost/127.0.0.1, port: 46930
,I/BtToRequestSocket( 2996): --DoOneRunRound ended
,I/jxcore-log( 2996): 2015-12-03T14:19:29.934Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:29.939Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:29.943Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:29.999Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:30.003Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:30.005Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:30.357Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:19:30.358Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:19:30.358Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:19:30.359Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,I/        ( 2996): Connecting to G4-1, at F8:95:C7:87:3C:51
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dbec4 rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [f8:95:c7:87:3c:51]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: G4-1
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3056): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3056): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3056): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3056): StableState(): Entering Off State
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2996): Starting to Handshake
I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2996): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/BTConnectToThread( 2996): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 2996): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3634","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2996): HandshakeOk : LGE-LG-H815_PT3634
I/HS      ( 2996): Hand Shake finished outgoing for : LGE-LG-H815_PT3634
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : false, LGE-LG-H815_PT3634
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2996): mHTTPPort  set to : 43306
I/BtConnectorHelper( 2996): Request socket is using : 43306
I/BtToRequestSocket( 2996): Now accepting connections
,I/BtConnectorHelper( 2996): Calling ConnectionStatusUpdate with port :43306
I/jxcore-log( 2996): 2015-12-03T14:19:35.049Z SendDataConnector.js: CLIENT connected to 43306, error: null
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:35.050Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): incoming data from: /127.0.0.1, port: 43306
I/BtToRequestSocket( 2996): Set local streams
I/BtToRequestSocket( 2996): rin ended ---------------------------;
,I/jxcore-log( 2996): 2015-12-03T14:19:35.074Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dbcfc rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 2996): Cleared service requests
I/        ( 2996): Started peer discovery
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3056): invalid rfc slot id: 65
,I/BtToSocketBase( 2996): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT2951
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2996): 2015-12-03T14:19:40.051Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2996): 
,W/bt-btif ( 3056): dm_pm_timer expires
W/bt-btif ( 3056): dm_pm_timer expires 0
W/bt-btif ( 3056): proc dm_pm_timer expires
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 2996): Found 8 peers.
I/SS      ( 2996): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2996): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2996): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2996): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2996): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2996): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2996): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2996): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2996): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2996): Added service request
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dbcfc rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3056): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
,W/bt-rfcomm( 3056): RFCOMM_DisconnectInd LCID:0x4d
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: G3s-1
,I/wpa_supplicant( 3073): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2996): Started service discovery
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dc08c rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 3056): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3056): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3056): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3056): StableState(): Entering Off State
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2996): we got incoming connection
I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
I/BTListenerThread( 2996): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dc08c rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2996): got MESSAGE_READ 77 bytes.
,I/BTListenerThread( 2996): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2226","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2996): MESSAGE_WRITE 77 bytes.
I/HS      ( 2996): Incoming connection Hand Shake finished for : LGE-LG-D722_PT2226
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : true, LGE-LG-D722_PT2226
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BTConnectedThread
I/BtConnectorHelper( 2996): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2996): --DoOneRunRound started
,I/jxcore-log( 2996): 2015-12-03T14:19:43.308Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): LocalHost address: localhost/127.0.0.1, port: 46930
,I/BtToRequestSocket( 2996): --DoOneRunRound ended
,I/jxcore-log( 2996): 2015-12-03T14:19:44.433Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:44.481Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:44.489Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:44.499Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:44.514Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:44.520Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:44.555Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:44.574Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:44.612Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dbcfc rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2996): 2015-12-03T14:19:44.678Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:44.713Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:44.797Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:44.808Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:44.852Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:44.938Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:44.997Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:45.054Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:45.147Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:19:45.148Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:19:45.149Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/jxcore-log( 2996): 2015-12-03T14:19:45.195Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:19:45.196Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:19:45.197Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/BtConnectorHelper( 2996): Disconnect outgoing peer: F8:95:C7:87:3C:51
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
I/BtToRequestSocket( 2996): Close server socket
I/jxcore-log( 2996): 2015-12-03T14:19:45.208Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): ---- round done--------
I/jxcore-log( 2996): 
I/jxcore-log( 2996): ---- gotta redo : F8:95:C7:87:3C:51, try count now: 1
I/jxcore-log( 2996): 
I/jxcore-log( 2996): do fake peer & start
I/jxcore-log( 2996): 
I/jxcore-log( 2996): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:19:45.209Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:19:45.209Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:19:45.209Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2996): Connecting to null, at 34:FC:EF:11:B1:66
I/jxcore-log( 2996): 2015-12-03T14:19:45.216Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:45.216Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 2996): 
,I/chromium( 2996): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F8:95:C7:87:3C:51 done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/jxcore-log( 2996): 2015-12-03T14:19:45.224Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 2996): 
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/jxcore-log( 2996): 2015-12-03T14:19:45.230Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 2996): 
,I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dbcfc rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2996): 2015-12-03T14:19:46.226Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:46.231Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:46.271Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:46.294Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:46.297Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:46.333Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dbcfc rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2996): 2015-12-03T14:19:46.373Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:46.428Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 2996): 
,W/bt-btif ( 3056): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3056): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2996): 2015-12-03T14:19:46.574Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:46.611Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 2996): 
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,E/bt-btif ( 3056): DISCOVERY_COMP_EVT slot id:69, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3056): invalid rfc slot id: 69
,I/BTConnectToThread( 2996): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2996): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2996): 2015-12-03T14:19:46.705Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:19:46.706Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:19:46.706Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:46.752Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:46.805Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dbcfc rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dc254 rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3056): aclStateChangeCallback: Device is NULL
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: G4-1
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [08:ec:a9:50:76:27]: 6, f, 6109
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2996): we got incoming connection
I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
I/BTListenerThread( 2996): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/        ( 2996): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9389"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9389"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9389, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9389, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/BTListenerThread( 2996): got MESSAGE_READ 83 bytes.
,I/BTListenerThread( 2996): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2951","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2996): MESSAGE_WRITE 77 bytes.
I/HS      ( 2996): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT2951
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : true, samsung-SM-A300FU_PT2951
,I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BTConnectedThread
,I/BtConnectorHelper( 2996): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2996): --DoOneRunRound started
,I/BtToRequestSocket( 2996): LocalHost address: localhost/127.0.0.1, port: 46930
I/BtToRequestSocket( 2996): --DoOneRunRound ended
,I/jxcore-log( 2996): 2015-12-03T14:19:50.947Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2996): 
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2996): 2015-12-03T14:19:51.530Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:51.537Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:51.655Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:51.707Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:19:51.708Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2996): 
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3056): invalid rfc slot id: 66
,I/BtToSocketBase( 2996): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT2226
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2996): 2015-12-03T14:19:56.482Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:19:56.712Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:19:56.713Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:19:56.713Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:19:56.714Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2996): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [34:fc:ef:11:b1:66]: 7, f, 6109
,E/BluetoothRemoteDevices( 3056): aclStateChangeCallback: Device is NULL
,W/bt-rfcomm( 3056): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
W/bt-rfcomm( 3056): RFCOMM_DisconnectInd LCID:0x44
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,E/bt-btif ( 3056): DISCOVERY_COMP_EVT slot id:71, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3056): invalid rfc slot id: 71
,I/BTConnectToThread( 2996): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2996): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2996): 2015-12-03T14:19:58.281Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:19:58.282Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:19:58.282Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dc254 rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/        ( 2996): Cleared service requests
I/        ( 2996): Started peer discovery
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3056): invalid rfc slot id: 68
,I/BtToSocketBase( 2996): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT2951
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2996): 2015-12-03T14:20:01.528Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3056): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: G3s-1
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dbec4 rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3056): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
W/bt-rfcomm( 3056): RFCOMM_DisconnectInd LCID:0x49
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2996): 2015-12-03T14:20:03.283Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:20:03.284Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2996): 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2996): Found 6 peers.
I/SS      ( 2996): Peer(1): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2996): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2996): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2996): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2996): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2996): Peer(6): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 2996): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2996): Added service request
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2996): Started service discovery
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2996): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3634","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3634","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT3634, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT3634, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 2996): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT9133"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT9133"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT9133, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT9133, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [f8:95:c7:87:85:54]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: G3s-1
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 3056): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3056): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3056): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 2996): we got incoming connection
I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
I/BTListenerThread( 2996): waiting to accept incoming Connection
,I/BluetoothBondStateMachine( 3056): StableState(): Entering Off State
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/BTListenerThread( 2996): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 2996): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2226","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2996): MESSAGE_WRITE 77 bytes.
I/HS      ( 2996): Incoming connection Hand Shake finished for : LGE-LG-D722_PT2226
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : true, LGE-LG-D722_PT2226
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BTConnectedThread
I/BtConnectorHelper( 2996): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2996): --DoOneRunRound started
,I/jxcore-log( 2996): 2015-12-03T14:20:07.907Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): LocalHost address: localhost/127.0.0.1, port: 46930
,I/BtToRequestSocket( 2996): --DoOneRunRound ended
,I/jxcore-log( 2996): 2015-12-03T14:20:08.290Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:20:08.291Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:20:08.291Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:20:08.292Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2996): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2996): Starting to connect
,I/jxcore-log( 2996): 2015-12-03T14:20:08.316Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:20:08.338Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2996): 
,W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/jxcore-log( 2996): 2015-12-03T14:20:08.348Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:20:08.358Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dc08c rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3056): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,E/bt-btif ( 3056): DISCOVERY_COMP_EVT slot id:73, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3056): invalid rfc slot id: 73
,I/BTConnectToThread( 2996): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2996): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2996): 2015-12-03T14:20:09.298Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:20:09.298Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:20:09.299Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3056): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2996): 2015-12-03T14:20:14.300Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:20:14.301Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2996): 
,I/        ( 2996): Cleared service requests
I/        ( 2996): Started peer discovery
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2996): Found 8 peers.
I/SS      ( 2996): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2996): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2996): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2996): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2996): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2996): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2996): Peer(7): A3-1 0a:ec:a9:50:75:42
I/SS      ( 2996): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2996): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2996): Added service request
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2996): Started service discovery
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/BtToSocketBase( 2996): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT2226
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
W/bt-btif ( 3056): invalid rfc slot id: 70
,I/jxcore-log( 2996): 2015-12-03T14:20:18.392Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:20:19.304Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:20:19.305Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:20:19.305Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:20:19.306Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2996): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3056): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,E/bt-btif ( 3056): DISCOVERY_COMP_EVT slot id:74, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3056): invalid rfc slot id: 74
,I/BTConnectToThread( 2996): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2996): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2996): 2015-12-03T14:20:20.405Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:20:20.406Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:20:20.406Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2996): 
,W/bt-rfcomm( 3056): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
W/bt-rfcomm( 3056): RFCOMM_DisconnectInd LCID:0x4b
,I/        ( 2996): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT9133"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT9133"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT9133, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT9133, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 2996): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1913","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1913","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT1913, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT1913, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3056): aclStateChangeCallback: Device is NULL
,I/        ( 2996): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5769","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5769","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5769, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5769, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 2996): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9389"}, typeCordovap2p._tcp.local.:
,I/        ( 2996): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9389"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9389, peerAddress: 80:01:84:8A:B3:68
,I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9389, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: G3s-1
,I/jxcore-log( 2996): 2015-12-03T14:20:25.416Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:20:25.417Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2996): 
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: G3s-1
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 3056): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3056): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3056): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3056): StableState(): Entering Off State
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2996): we got incoming connection
I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
I/BTListenerThread( 2996): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/BTListenerThread( 2996): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 2996): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2226","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2996): MESSAGE_WRITE 77 bytes.
I/HS      ( 2996): Incoming connection Hand Shake finished for : LGE-LG-D722_PT2226
I/BtConnectorHelper( 2996): Starting the connected thread incoming : true, LGE-LG-D722_PT2226
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BTConnectedThread
I/BtConnectorHelper( 2996): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2996): --DoOneRunRound started
,I/BtToRequestSocket( 2996): LocalHost address: localhost/127.0.0.1, port: 46930
I/BtToRequestSocket( 2996): --DoOneRunRound ended
,I/jxcore-log( 2996): 2015-12-03T14:20:30.236Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:20:30.420Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:20:30.421Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:20:30.421Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:20:30.422Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2996): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dc08c rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2996): 2015-12-03T14:20:31.074Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:20:31.306Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:20:31.374Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:20:31.417Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:20:31.424Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2996): 
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3056): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,E/bt-btif ( 3056): DISCOVERY_COMP_EVT slot id:76, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3056): invalid rfc slot id: 76
,I/BTConnectToThread( 2996): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2996): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2996): 2015-12-03T14:20:31.538Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:20:31.539Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:20:31.562Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:20:31.578Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2996): 
I/jxcore-log( 2996): ---- round done--------
I/jxcore-log( 2996): 
I/jxcore-log( 2996): ---- gotta redo : 34:FC:EF:11:B1:66, try count now: 1
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): do fake peer & start
I/jxcore-log( 2996): 
I/jxcore-log( 2996): Connect to fake peer: 7C:F9:0E:37:96:AB
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:20:31.581Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:20:31.581Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:20:31.581Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/        ( 2996): Connecting to null, at 7C:F9:0E:37:96:AB
I/chromium( 2996): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 34:FC:EF:11:B1:66 done with result: Connection to 34:FC:EF:11:B1:66 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3056): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
E/bt-btif ( 3056): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3056): Entering PendingCommandState State
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothAdapterProperties( 3056): Failed to remove device: 7C:F9:0E:37:96:AB
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3056): StableState(): Entering Off State
,I/wpa_supplicant( 3073): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2996): Cleared service requests
I/        ( 2996): Started peer discovery
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2996): Found 8 peers.
I/SS      ( 2996): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2996): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2996): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2996): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2996): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2996): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2996): Peer(7): A3-1 0a:ec:a9:50:75:42
I/SS      ( 2996): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2996): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2996): Added service request
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2996): Starting to Handshake
,I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2996): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BTConnectToThread( 2996): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 2996): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT7439","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2996): HandshakeOk : samsung-SM-A500FU_PT7439
I/HS      ( 2996): Hand Shake finished outgoing for : samsung-SM-A500FU_PT7439
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : false, samsung-SM-A500FU_PT7439
,I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2996): mHTTPPort  set to : 55384
I/BtConnectorHelper( 2996): Request socket is using : 55384
I/BtToRequestSocket( 2996): Now accepting connections
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BtConnectorHelper( 2996): Calling ConnectionStatusUpdate with port :55384
I/jxcore-log( 2996): 2015-12-03T14:20:34.937Z SendDataConnector.js: CLIENT connected to 55384, error: null
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:20:34.938Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): incoming data from: /127.0.0.1, port: 55384
I/BtToRequestSocket( 2996): Set local streams
I/BtToRequestSocket( 2996): rin ended ---------------------------;
,I/jxcore-log( 2996): 2015-12-03T14:20:34.965Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2996): 
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2996): Started service discovery
,D/        ( 3056): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24978
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3056): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2996): 2015-12-03T14:20:35.535Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2996): 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2996): 2015-12-03T14:20:35.782Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2996): 
,D/        ( 3056): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13098
,I/jxcore-log( 2996): 2015-12-03T14:20:35.818Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2996): 
,D/        ( 3056): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:9138
,I/jxcore-log( 2996): 2015-12-03T14:20:35.957Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:20:36.118Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:20:36.193Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2996): 
,I/        ( 2996): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7616"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7616"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT7616, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT7616, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/jxcore-log( 2996): 2015-12-03T14:20:36.388Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:20:36.470Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:20:36.558Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2996): 
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dc41c rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/        ( 2996): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT9133"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT9133"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT9133, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT9133, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,W/bt-btif ( 3056): invalid rfc slot id: 72
,I/BtToSocketBase( 2996): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT2226
,I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT2226
I/BtToSocketBase( 2996): Close bt in
I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/BtToSocketBase( 2996): Close bt in
I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/jxcore-log( 2996): 2015-12-03T14:20:40.866Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2996): 
,W/bt-btif ( 3056): dm_pm_timer expires
W/bt-btif ( 3056): dm_pm_timer expires 0
W/bt-btif ( 3056): proc dm_pm_timer expires
,W/bt-rfcomm( 3056): rfc_find_lcid_mcb LCID reused LCID:0x4f current:0x0
,W/bt-rfcomm( 3056): RFCOMM_DisconnectInd LCID:0x4f
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dc41c rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2996): 2015-12-03T14:20:46.557Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:20:46.558Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:20:46.559Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:20:46.560Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:20:46.565Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2996): 
,I/BtToSocketBase( 2996): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2996): Disconnect outgoing peer: samsung-SM-A500FU_PT7439
,I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
,I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
I/BtToRequestSocket( 2996): Close server socket
,W/bt-btif ( 3056): bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: G3s-1
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dc41c rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/        ( 2996): Cleared service requests
I/        ( 2996): Started peer discovery
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: A5-1
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: G3s-1
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 3056): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3056): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3056): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3056): StableState(): Entering Off State
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2996): we got incoming connection
I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
I/BTListenerThread( 2996): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/BTListenerThread( 2996): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 2996): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2226","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2996): MESSAGE_WRITE 77 bytes.
I/HS      ( 2996): Incoming connection Hand Shake finished for : LGE-LG-D722_PT2226
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : true, LGE-LG-D722_PT2226
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BTConnectedThread
I/BtConnectorHelper( 2996): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2996): --DoOneRunRound started
,I/BtToRequestSocket( 2996): LocalHost address: localhost/127.0.0.1, port: 46930
,I/jxcore-log( 2996): 2015-12-03T14:20:51.312Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): --DoOneRunRound ended
,I/jxcore-log( 2996): 2015-12-03T14:20:51.564Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:20:51.565Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:20:51.693Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:20:51.700Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:20:51.714Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:20:51.721Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2996): 
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2996): Found 7 peers.
I/SS      ( 2996): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2996): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2996): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2996): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2996): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2996): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2996): Peer(7): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 2996): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2996): Added service request
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2996): Started service discovery
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2996): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT411","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT411","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT411, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT411, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/jxcore-log( 2996): 2015-12-03T14:20:56.568Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:20:56.569Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:20:56.569Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:20:56.570Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 2996): Connecting to A5-1, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dc08c rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [7c:f9:0e:37:96:ab]: 6, f, 6109
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: A5-1
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dc41c rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3056): dm_pm_timer expires
W/bt-btif ( 3056): dm_pm_timer expires 0
,W/bt-btif ( 3056): proc dm_pm_timer expires
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dc41c rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2996): Starting to Handshake
,I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2996): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dc41c rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3056): invalid rfc slot id: 75
,I/BtToSocketBase( 2996): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT2226
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
,I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT2226
I/BtToSocketBase( 2996): Close bt in
I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/jxcore-log( 2996): 2015-12-03T14:21:01.812Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dc41c rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 2996): got MESSAGE_READ 83 bytes.
,I/BTConnectToThread( 2996): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT7439","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2996): HandshakeOk : samsung-SM-A500FU_PT7439
,I/HS      ( 2996): Hand Shake finished outgoing for : samsung-SM-A500FU_PT7439
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : false, samsung-SM-A500FU_PT7439
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2996): mHTTPPort  set to : 44314
I/BtConnectorHelper( 2996): Request socket is using : 44314
,I/BtToRequestSocket( 2996): Now accepting connections
,I/BtConnectorHelper( 2996): Calling ConnectionStatusUpdate with port :44314
I/jxcore-log( 2996): 2015-12-03T14:21:02.363Z SendDataConnector.js: CLIENT connected to 44314, error: null
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:21:02.364Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): incoming data from: /127.0.0.1, port: 44314
I/BtToRequestSocket( 2996): Set local streams
,I/BtToRequestSocket( 2996): rin ended ---------------------------;
,I/jxcore-log( 2996): 2015-12-03T14:21:02.392Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2996): 
,W/bt-rfcomm( 3056): rfc_find_lcid_mcb LCID reused LCID:0x4e current:0x0
W/bt-rfcomm( 3056): RFCOMM_DisconnectInd LCID:0x4e
,I/        ( 2996): Cleared service requests
I/        ( 2996): Started peer discovery
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2996): Found 8 peers.
I/SS      ( 2996): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2996): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2996): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2996): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2996): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 2996): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 2996): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2996): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2996): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2996): Added service request
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: G3s-1
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2996): Started service discovery
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dc41c rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3056): dm_pm_timer expires
W/bt-btif ( 3056): dm_pm_timer expires 0
W/bt-btif ( 3056): proc dm_pm_timer expires
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: G3s-1
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 3056): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3056): Entering PendingCommandState State
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dc41c rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2996): 2015-12-03T14:21:12.456Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:21:12.456Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:21:12.456Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:21:12.456Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:21:12.457Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2996): 
,I/BtToSocketBase( 2996): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2996): Disconnect outgoing peer: samsung-SM-A500FU_PT7439
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/BtToRequestSocket( 2996): Close server socket
,I/BluetoothBondStateMachine( 3056): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3056): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 3056): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3056): StableState(): Entering Off State
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2996): we got incoming connection
,I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
I/BTListenerThread( 2996): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/BTListenerThread( 2996): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 2996): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2226","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2996): MESSAGE_WRITE 77 bytes.
I/HS      ( 2996): Incoming connection Hand Shake finished for : LGE-LG-D722_PT2226
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : true, LGE-LG-D722_PT2226
,I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BTConnectedThread
I/BtConnectorHelper( 2996): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2996): --DoOneRunRound started
,I/BtToRequestSocket( 2996): LocalHost address: localhost/127.0.0.1, port: 46930
,I/jxcore-log( 2996): 2015-12-03T14:21:12.697Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): --DoOneRunRound ended
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dc41c rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2996): 2015-12-03T14:21:13.098Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:21:13.130Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:21:13.138Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data,
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:21:13.165Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2996): 
,W/bt-btif ( 3056): bta_jv_rfc_port_to_cb(port_handle:0x18):jv handle:0x0 not FOUND
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: A5-1
,I/jxcore-log( 2996): 2015-12-03T14:21:17.456Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:21:17.456Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2996): 
,I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2996): 2015-12-03T14:21:22.457Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:21:22.458Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:21:22.458Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:21:22.458Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 2996): Connecting to A5-1, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 2996): Starting to connect
,W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3056): invalid rfc slot id: 78
,I/BtToSocketBase( 2996): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2996): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT2226
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2996): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2996): 2015-12-03T14:21:23.255Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2996): 
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: A5-1
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dc08c rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3056): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
W/bt-rfcomm( 3056): RFCOMM_DisconnectInd LCID:0x46
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dc41c rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2996): Starting to Handshake
I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2996): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dc08c rs_disc_pending=1
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BTConnectToThread( 2996): got MESSAGE_READ 83 bytes.
,I/BTConnectToThread( 2996): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT7439","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2996): HandshakeOk : samsung-SM-A500FU_PT7439
I/HS      ( 2996): Hand Shake finished outgoing for : samsung-SM-A500FU_PT7439
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : false, samsung-SM-A500FU_PT7439
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2996): mHTTPPort  set to : 46673
I/BtConnectorHelper( 2996): Request socket is using : 46673
I/BtToRequestSocket( 2996): Now accepting connections
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: G3s-1
,I/BtConnectorHelper( 2996): Calling ConnectionStatusUpdate with port :46673
I/jxcore-log( 2996): 2015-12-03T14:21:27.427Z SendDataConnector.js: CLIENT connected to 46673, error: null
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:21:27.428Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): incoming data from: /127.0.0.1, port: 46673
I/BtToRequestSocket( 2996): Set local streams
,I/BtToRequestSocket( 2996): rin ended ---------------------------;
,I/jxcore-log( 2996): 2015-12-03T14:21:27.432Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2996): 
,W/bt-btif ( 3056): dm_pm_timer expires
W/bt-btif ( 3056): dm_pm_timer expires 0
W/bt-btif ( 3056): proc dm_pm_timer expires
,E/bt-btm  ( 3056): tBTM_SEC_DEV:0xa41dc41c rs_disc_pending=0
W/bt-btif ( 3056): bta_dm_check_av:0
,W/bt-btif ( 3056): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2996): 2015-12-03T14:21:37.479Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:21:37.479Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:21:37.485Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:21:37.488Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:21:37.491Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2996): 
,I/BtToSocketBase( 2996): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2996): Disconnect outgoing peer: samsung-SM-A500FU_PT7439
,I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
,I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
I/BtToRequestSocket( 2996): Close server socket
,W/bt-btif ( 3056): bta_jv_rfc_port_to_cb(port_handle:0x1a):jv handle:0x0 not FOUND
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: A5-1
,I/jxcore-log( 2996): 2015-12-03T14:21:42.492Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:21:42.493Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): timeout now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): dun
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): weAreDoneNow , resultArray.length: 3
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): done, now sending data to server
I/jxcore-log( 2996): 
I/jxcore-log( 2996): DBG, CoordinatorConnector sendData called
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): -- RESULT DATA {"name:":"LGE-Nexus 5_PT1117","time":1000100,"result":"TIMEOUT","sendList":[{"name":"44:80:EB:7B:5A:05","time":50697,"result":"OK","connections":3,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":6111,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":22056,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:9D:93:0B","time":0,"result":"Fail"},{"connections":0,"name":"B4:CE:F6:AB:A4:6A","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":1,
I/jxcore-log( 2996): sendList : 100% : 50697 ms, 99% : 50697 ms, 95 : 50697 ms, 90% : 50697 ms.
I/jxcore-log( 2996): 
I/jxcore-log( 2996): Result count 3, range 6111 ms to  50697 ms.
I/jxcore-log( 2996): 
I/jxcore-log( 2996): sendList failed peers count : 8 [72.72727272727273 %]
I/jxcore-log( 2996): 
I/jxcore-log( 2996): - Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
I/jxcore-log( 2996): 
I/jxcore-log( 2996): - Peer ID : B0:C5:59:3F:75:69, Tried : 1
I/jxcore-log( 2996): 
I/jxcore-log( 2996): - Peer ID : 80:01:84:8A:B3:68, Tried : 1
I/jxcore-log( 2996): 
I/jxcore-log( 2996): - Peer ID : F8:95:C7:87:85:54, Tried : 1
I/jxcore-log( 2996): 
I/jxcore-log( 2996): - Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
I/jxcore-log( 2996): 
I/jxcore-log( 2996): - Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
I/jxcore-log( 2996): 
I/jxcore-log( 2996): - Peer ID : F8:95:C7:87:3C:51, Tried : 1
I/jxcore-log( 2996): 
I/jxcore-log( 2996): - Peer ID : 34:FC:EF:11:B1:66, Tried : 1
I/jxcore-log( 2996): 
I/jxcore-log( 2996): sendList never tried peers count : 6 [35.294117647058826 %]
I/jxcore-log( 2996): 
I/jxcore-log( 2996): - Peer ID : 08:EC:A9:50:76:27
I/jxcore-log( 2996): 
I/jxcore-log( 2996): - Peer ID : 00:F4:6F:30:E0:6C
I/jxcore-log( 2996): 
I/jxcore-log( 2996): - Peer ID : 7C:F9:0E:34:8A:A0
I/jxcore-log( 2996): 
I/jxcore-log( 2996): - Peer ID : 34:FC:EF:9D:93:0B
I/jxcore-log( 2996): 
I/jxcore-log( 2996): - Peer ID : B4:CE:F6:AB:A4:6A
I/jxcore-log( 2996): 
I/jxcore-log( 2996): - Peer ID : 58:3F:54:73:64:C0
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:21:43.433Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:21:43.433Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:21:43.434Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2996): 
,I/chromium( 2996): [INFO:CONSOLE(63)] "logCallback *** TIMEOUT ***", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 2996): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2996): 2015-12-03T14:21:47.496Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:21:47.497Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:21:47.497Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:21:47.498Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 2996): Connecting to A5-1, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [7c:f9:0e:37:96:ab]: 6, f, 410d
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: A5-1
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2996): Starting to Handshake
,I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2996): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/BTConnectToThread( 2996): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 2996): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT7439","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2996): HandshakeOk : samsung-SM-A500FU_PT7439
,I/HS      ( 2996): Hand Shake finished outgoing for : samsung-SM-A500FU_PT7439
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : false, samsung-SM-A500FU_PT7439
,I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 2996): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2996): mHTTPPort  set to : 59460
I/BtConnectorHelper( 2996): Request socket is using : 59460
I/BtToRequestSocket( 2996): Now accepting connections
,I/BtConnectorHelper( 2996): Calling ConnectionStatusUpdate with port :59460
I/jxcore-log( 2996): 2015-12-03T14:21:49.818Z SendDataConnector.js: CLIENT connected to 59460, error: null
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:21:49.819Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): incoming data from: /127.0.0.1, port: 59460
I/BtToRequestSocket( 2996): Set local streams
I/BtToRequestSocket( 2996): rin ended ---------------------------;
,I/jxcore-log( 2996): 2015-12-03T14:21:49.841Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2996): 
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3056): dm_pm_timer expires
W/bt-btif ( 3056): dm_pm_timer expires 0
W/bt-btif ( 3056): proc dm_pm_timer expires
,I/jxcore-log( 2996): 2015-12-03T14:21:59.907Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:21:59.908Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:21:59.909Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:21:59.909Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:21:59.914Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2996): 
,I/BtToSocketBase( 2996): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2996): Disconnect outgoing peer: samsung-SM-A500FU_PT7439
I/BtToSocketBase( 2996): Stop ReceivingThread
,I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
I/BtToSocketBase( 2996): Close LocalOutputStream
,I/BtToSocketBase( 2996): Close localHostSocket
I/BtToSocketBase( 2996): Close bt in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
I/BtToRequestSocket( 2996): Close server socket
,W/bt-btif ( 3056): bta_jv_rfc_port_to_cb(port_handle:0x1b):jv handle:0x0 not FOUND
,I/jxcore-log( 2996): 2015-12-03T14:22:04.914Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:22:04.915Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2996): 
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: A5-1
,I/        ( 2996): Cleared service requests
I/        ( 2996): Started peer discovery
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 2996): Found 9 peers.
I/SS      ( 2996): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2996): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2996): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2996): Peer(4): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2996): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2996): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2996): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2996): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2996): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2996): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2996): Added service request
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2996): Started service discovery
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 2996): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9389"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9389"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9389, peerAddress: 80:01:84:8A:B3:68
,I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9389, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/jxcore-log( 2996): 2015-12-03T14:22:09.919Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:22:09.919Z SendDataConnector.js: Connect (retry count 4) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:22:09.920Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:22:09.923Z SendDataConnector.js: do connect now
I/jxcore-log( 2996): 
,I/        ( 2996): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 2996): Connecting to A5-1, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 2996): Starting to connect
W/BluetoothAdapter( 2996): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3056): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3056): info:x10
,D/        ( 3056): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: A5-1
,W/bt-sdp  ( 3056): process_service_search_attr_rsp
,W/bt-btif ( 3056): new conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3056): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2996): Starting to Handshake
,I/BTHandshakeSocketThread( 2996): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2996): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread started
,I/BTConnectToThread( 2996): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 2996): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT7439","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2996): HandshakeOk : samsung-SM-A500FU_PT7439
I/HS      ( 2996): Hand Shake finished outgoing for : samsung-SM-A500FU_PT7439
I/BTHandshakeSocketThread( 2996): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2996): Starting the connected thread incoming : false, samsung-SM-A500FU_PT7439
I/BtToSocketBase( 2996): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2996): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2996): mHTTPPort  set to : 39686
I/BtConnectorHelper( 2996): Request socket is using : 39686
,I/BtToRequestSocket( 2996): Now accepting connections
,I/BtConnectorHelper( 2996): Calling ConnectionStatusUpdate with port :39686
I/jxcore-log( 2996): 2015-12-03T14:22:11.689Z SendDataConnector.js: CLIENT connected to 39686, error: null
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:22:11.690Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2996): 
,I/BtToRequestSocket( 2996): incoming data from: /127.0.0.1, port: 39686
I/BtToRequestSocket( 2996): Set local streams
I/BtToRequestSocket( 2996): rin ended ---------------------------;
,I/jxcore-log( 2996): 2015-12-03T14:22:11.714Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2996): 
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3056): dm_pm_timer expires
W/bt-btif ( 3056): dm_pm_timer expires 0
W/bt-btif ( 3056): proc dm_pm_timer expires
,I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,I/        ( 2996): Cleared service requests
I/        ( 2996): Started peer discovery
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2996): 2015-12-03T14:22:21.777Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:22:21.778Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:22:21.779Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:22:21.788Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:22:21.788Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 2996): 
I/jxcore-log( 2996): 2015-12-03T14:22:21.789Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2996): 
,I/BtConnectorHelper( 2996): Disconnect outgoing peer: 7C:F9:0E:37:96:AB
I/BtToSocketBase( 2996): Stop ReceivingThread
I/BtToSocketBase( 2996): Stop SendingThread
I/BtToSocketBase( 2996): Close local in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2996): Close LocalOutputStream
I/BtToSocketBase( 2996): Close localHostSocket
,I/BtToSocketBase( 2996): Close bt in
,I/BtToSocketBase( 2996): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2996): Close bt out
I/BtToSocketBase( 2996): Close bt socket
,I/BtToRequestSocket( 2996): Close server socket
I/jxcore-log( 2996): 2015-12-03T14:22:21.837Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:22:21.838Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2996): 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2996): Found 8 peers.
I/SS      ( 2996): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2996): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2996): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2996): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2996): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2996): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2996): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2996): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2996): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2996): Added service request
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3056): bta_jv_rfc_port_to_cb(port_handle:0x1c):jv handle:0x0 not FOUND
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2996): Started service discovery
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2996): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9389"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9389"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9389, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9389, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 2996): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2951","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2951","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT2951, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT2951, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 2996): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT7904","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
I/        ( 2996): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT7904","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT7904, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT7904, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,E/bt-btm  ( 3056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3056): onReceive
,I/BTConnectionReceiver( 1423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1423): Bluetooth Device Name: A5-1
,I/        ( 2996): Cleared service requests
I/        ( 2996): Started peer discovery
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2996): Found 8 peers.
I/SS      ( 2996): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2996): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2996): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2996): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2996): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2996): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2996): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2996): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2996): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2996): Added service request
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2996): Started service discovery
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2996): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT7439","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 2996): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT7439","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT7439, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 2996): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT7439, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 2996): Cleared service requests
I/        ( 2996): Started peer discovery
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2996): Found 12 peers.
I/SS      ( 2996): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2996): Peer(2): S5-1 ee:1f:72:63:11:86
,I/SS      ( 2996): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2996): Peer(4): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2996): Peer(5): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2996): Peer(6): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 2996): Peer(7): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2996): Peer(8): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2996): Peer(9): A3-1 0a:ec:a9:50:75:42
I/SS      ( 2996): Peer(10): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2996): Peer(11): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2996): Peer(12): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2996): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2996): Added service request
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2996): Started service discovery
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/        ( 2996): Cleared service requests
I/        ( 2996): Started peer discovery
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2996): Found 8 peers.
I/SS      ( 2996): Peer(1): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2996): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2996): Peer(3): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2996): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2996): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2996): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 2996): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2996): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2996): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2996): Added service request
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2996): Started service discovery
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,W/bt-smp  ( 3056): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3056): Plain text(LSB ~ MSB) = 0d f9 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3056): Encrypted text(LSB ~ MSB) = 0a 92 00 34 8c b2 e2 01 67 e2 25 6d c7 2d a1 f0 
,W/bt-btm  ( 3056): Stopping oneshot timer
,I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/        ( 2996): Cleared service requests
I/        ( 2996): Started peer discovery
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2996): Found 6 peers.
I/SS      ( 2996): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2996): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2996): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2996): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2996): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2996): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2996): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2996): Added service request
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2996): Started service discovery
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,I/        ( 2996): Cleared service requests
I/        ( 2996): Started peer discovery
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2996): Found 8 peers.
I/SS      ( 2996): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2996): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2996): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2996): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2996): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2996): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2996): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2996): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2996): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2996): Added service request
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2996): Started service discovery
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3073): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2996): DBG, CoordinatorConnector command called
I/jxcore-log( 2996): 
I/jxcore-log( 2996): command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): stop tests now !
I/jxcore-log( 2996): 
I/jxcore-log( 2996): stop current!
I/jxcore-log( 2996): 
I/jxcore-log( 2996): testSendData stopped
I/jxcore-log( 2996): 
I/        ( 2996): Stoping All
I/        ( 2996): Stopping services
I/        ( 2996): Stopping services
,I/wpa_supplicant( 3073): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 3073): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/        ( 2996): Stop Bluetooth
I/        ( 2996): Stop Bluetooth
I/BTListenerThread( 2996): Stopped
,I/jxcore-log( 2996): StopBroadcasting went ok
I/jxcore-log( 2996): 
,I/jxcore-log( 2996): 2015-12-03T14:26:02.925Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 2996): 
I/chromium( 2996): [INFO:CONSOLE(63)] "logCallback stop", source: file:///android_asset/www/js/thali_main.js (63)
I/        ( 2996): Cleared local services
I/        ( 2996): Cleared service requests
I/        ( 2996): Stopped peer discovery
,I/jxcore-log( 2996): DBG, CoordinatorConnector command called
I/jxcore-log( 2996): 
I/jxcore-log( 2996): command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"E0:DB:10:14:E2:C0\",\"time\":6111,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"08:EC:A9:50:75:41\",\"time\":22056,\"result\":\"OK\",\"connections\":2,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"44:80:EB:7B:5A:05\",\"time\":50697,\"result\":\"OK\",\"connections\":3,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[{\"connections\":1,\"name\":\"7C:F9:0E:37:96:AB\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"B0:C5:59:3F:75:69\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"80:01:84:8A:B3:68\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"F8:95:C7:87:85:54\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"58:2A:F7:ED:96:BE\",\"time\":0,\"result\":\"Fail\"},
I/jxcore-log( 2996): ****TEST TOOK:  ms ****
I/jxcore-log( 2996): 
I/jxcore-log( 2996): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2996): 
I/jxcore-log( 2996): stop tests now !
I/jxcore-log( 2996): 
I/jxcore-log( 2996): end, event received
I/jxcore-log( 2996): 
I/jxcore-log( 2996): CoordinatorConnector close called
I/jxcore-log( 2996): 
I/jxcore-log( 2996): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 2996): 
I/jxcore-log( 2996): The Coordinator has disconnected!
I/jxcore-log( 2996): 
I/jxcore-log( 2996): The Coordinator has closed!
I/jxcore-log( 2996): 
I/jxcore-log( 2996): stop tests now !
I/jxcore-log( 2996): 
I/jxcore-log( 2996): turning Radios off
I/jxcore-log( 2996): 
I/jxcore-log( 2996): Toggling radios to false
I/jxcore-log( 2996): 
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  733): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@12f725ec mBinding = false
,D/BluetoothManagerService(  733): Message: 2
D/BluetoothManagerService(  733): Sending off request.
,D/BluetoothAdapterState( 3056): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3056): Setting state to 13
I/BluetoothAdapterState( 3056): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterProperties( 3056): onBluetoothDisable()
I/BluetoothAdapterState( 3056): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 3056): Scan Mode:20
,D/BluetoothAdapterState( 3056): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,V/BluetoothMapMasInstance( 3056): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3056): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3056): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 3056): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 3056): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 3056): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3056): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3056): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,E/BtOppRfcommListener( 3056): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/btif_config_util( 3056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3056): bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
W/bt-l2cap( 3056): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3056): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothManagerService(  733): Message: 60
D/BluetoothManagerService(  733): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  733): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 3056): onReceive
D/BluetoothMapService( 3056): STATE_TURNING_OFF
V/BluetoothMapService( 3056): Handler(): got msg=4
D/BluetoothMapService( 3056): MAP Service closeService in
D/BluetoothMapMasInstance( 3056): MAP Service shutdown
V/BluetoothMapService( 3056): MAP Service closeService out
,I/BtOppRfcommListener( 3056): stopping Accept Thread
,I/BtOppRfcommListener( 3056): BluetoothSocket listen thread finished
,D/WifiService(  733): setWifiEnabled: false pid=2996, uid=10270
E/WifiService(  733): Invoking mWifiStateMachine.setWifiEnabled
,E/WifiStateMachine(  733): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  733): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  733): do suspend true
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,I/jxcore-log( 2996): Radios toggled
I/jxcore-log( 2996): 
I/chromium( 2996): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
,V/NativeCrypto( 1381): Read error: ssl=0xaf9e6400: I/O error during system call, Connection timed out
,D/bt_userial( 3056): RX termination
W/bt_userial( 3056): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 3056): Leaving userial_read_thread()
D/bt_userial( 3056): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 3056): hw_epilog_process
W/bt-btif ( 3056): ag scb idx 1 not allocated
E/bt-btif ( 3056): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3056): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3056): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3056): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3056): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3056): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3056): L2CAP - PSM: 0x0017 not found for deregistration
I/bt_userial_vendor( 3056): device fd = 53 close
,I/GKI_LINUX( 3056): gki_task task_id=0 [BTU] terminating
,E/WifiConfigStore(  733): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  733): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  733): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
I/GKI_LINUX( 3056): GKI_exit_task 0 done
I/GKI_LINUX( 3056): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 3056): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,E/WifiStateMachine(  733): scanCount==0 - aborting
,D/WifiNetworkAgent(  733): NetworkAgent: NetworkAgent channel lost
,D/WifiScanningService(  733): SCAN_AVAILABLE : 1
D/RttService(  733): SCAN_AVAILABLE : 1
,D/WifiScanningService(  733): StartedState got{ when=-3ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  733): DefaultState
E/native  (  733): do suspend true
,D/RttService(  733): EnabledState got{ when=-5ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,D/ConnectivityService(  733): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  733): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  733): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Disconnected - quitting
,D/ConnectivityManager.CallbackHandler( 1561): CM callback handler got msg 524292
D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524292
,D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  733): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1226): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/art     (  733): Explicit concurrent mark sweep GC freed 70045(3MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 28MB/42MB, paused 2.615ms total 152.822ms
,D/HeadsetService( 3056): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3056): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27dd404d
,D/HeadsetStateMachine( 3056): Exit Disconnected: -1
,V/NativeCrypto( 1381): SSL shutdown failed: ssl=0xaf9e6400: I/O error during system call, Broken pipe
,D/BluetoothHeadset( 1186): Proxy object disconnected
,D/BluetoothHeadset( 1186): Proxy object disconnected
D/BluetoothHeadset(  733): Proxy object disconnected
,D/A2dpService( 3056): Received stop request...Stopping profile...
W/ContextImpl( 4314): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/A2dpStateMachine( 3056): Exit Disconnected: -1
,D/BluetoothAdapterService( 3056): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27dd404d
,D/BluetoothA2dp(  733): Proxy object disconnected
,D/BluetoothAdapterState( 3056): Stopping profile services that were post enabled
D/HidService( 3056): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3056): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27dd404d
,D/HeadsetStateMachine( 3056): Unbinding service...
,W/BluetoothHeadsetServiceJni( 3056): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3056): Cleaning up Bluetooth Handsfree callback object
,D/HealthService( 3056): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3056): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27dd404d
D/PanService( 3056): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3056): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27dd404d
,D/BtGatt.DebugUtils( 3056): handleDebugAction() action=null
D/BtGatt.GattService( 3056): Received stop request...Stopping profile...
,D/BtGatt.GattService( 3056): stop()
D/BtGatt.AdvertiseManager( 3056): advertise clients cleared
D/BluetoothAdapterService( 3056): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27dd404d
,I/GKI_LINUX( 3056): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 3056): GKI_exit_task 2 done
I/GKI_LINUX( 3056): GKI_shutdown(): task [A2DP-MEDIA] terminated
,D/BluetoothMapService( 3056): Received stop request...Stopping profile...
D/BluetoothMapService( 3056): stop()
,D/BluetoothMapEmailAppObserver( 3056): deinitObservers()
,D/BluetoothMapEmailAppObserver( 3056): removeReceiver()
,D/BluetoothAdapterService( 3056): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27dd404d
,W/BluetoothHidServiceJni( 3056): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3056): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3056): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3056): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3056): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3056): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3056): Cleaning up Bluetooth PAN callback object
,V/BluetoothMapService( 3056): Handler(): got msg=4
D/BluetoothMapService( 3056): MAP Service closeService in
V/BluetoothMapService( 3056): MAP Service closeService out
D/BluetoothMapService( 3056): cleanup()
D/BluetoothMapService( 3056): MAP Service closeService in
,V/BluetoothMapService( 3056): MAP Service closeService out
D/BluetoothAdapterState( 3056): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
,D/BluetoothAdapterProperties( 3056): Setting state to 10
I/BluetoothAdapterState( 3056): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService(  733): Message: 60
D/BluetoothManagerService(  733): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  733): Broadcasting onBluetoothStateChange(false) to 5 receivers.
D/BluetoothHeadset(  733): onBluetoothStateChange: up=false
,I/BluetoothAdapterState( 3056): Entering OffState
,D/BluetoothHeadset( 1186): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1186): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1226): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  733): onBluetoothStateChange: up=false
,D/BluetoothManagerService(  733): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  733): Broadcasting onBluetoothServiceDown() to 11 receivers.
,D/BluetoothManagerService(  733): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@12f725ec mBinding = false
D/BluetoothManagerService(  733): Sending unbind request.
,D/BluetoothManagerService(  733): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothManagerService(  733): Message: 30
,D/BluetoothAdapter(  898): 536751558: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  898): 536751558: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter(  898): 536751558: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 3056): gki_task task_id=1 [BTIF] terminating
,D/BluetoothManagerService(  733): Message: 30
,D/BluetoothAdapter( 1320): 312379399: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1320): 312379399: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 3056): GKI_exit_task 1 done
,I/GKI_LINUX( 3056): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3056): cleanupNative: return from cleanup
D/LocalBluetoothProfileManager( 4314): Adding local MAP profile
,D/BluetoothMap( 4314): Create BluetoothMap proxy object
I/art     ( 3056): System.exit called, status: 0
I/AndroidRuntime( 3056): VM exiting with result code 0, cleanup skipped.
,D/BluetoothManagerService(  733): Message: 30
,D/BluetoothManagerService(  733): Message: 30
,D/LocalBluetoothProfileManager( 4314): LocalBluetoothProfileManager construction complete
,I/wpa_supplicant( 3073): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 3073): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,D/AndroidRuntime( 4840): 
D/AndroidRuntime( 4840): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4840): CheckJNI is OFF
,I/ActivityManager(  733): Process com.android.bluetooth (pid 3056) has died
,D/DockEventReceiver( 4314): finishStartingService: stopping service
,D/WifiService(  733): New client listening to asynchronous messages
,I/ActivityManager(  733): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=4877 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/AndroidRuntime( 4840): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  733): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  733): Killing 2996:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/wpa_supplicant( 3073): wlan0: CTRL-EVENT-TERMINATING 
D/Tethering(  733): InitialState.processMessage what=4
,W/PackageSettings(  733): Skipping PackageSetting{16a5834c com.example.hello/10277} due to missing metadata
,I/WindowState(  733): WIN DEATH: Window{1a2fe85f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  733): Client connection lost with reason: 4
,I/ActivityManager(  733):   Force finishing activity ActivityRecord{38593338 u0 com.test.thalitest/.MainActivity t214}
,D/Tethering(  733): sendTetherStateChangedBroadcast 0, 0, 0
,W/ActivityManager(  733): Spurious death for ProcessRecord{3802abfa 2996:com.test.thalitest/u0a270}, curProc for 2996: null
,I/ActivityManager(  733): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,W/Settings( 4037): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1320): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Adreno-EGL(  945): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/ResourcesManager( 4877): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/OpenGLRenderer(  945): Initialized EGL, version 1.4
,D/OpenGLRenderer(  945): Enabling debug mode 0
,W/InputMethodManagerService(  733): Got RemoteException sending setActive(false) notification to pid 2996 uid 10270
,I/Keyboard.Facilitator( 1084): onFinishInput()
,I/art     ( 1423): Explicit concurrent mark sweep GC freed 84313(4MB) AllocSpace objects, 17(284KB) LOS objects, 25% free, 19MB/25MB, paused 337us total 59.581ms
,I/art     ( 1287): Explicit concurrent mark sweep GC freed 9395(599KB) AllocSpace objects, 3(288KB) LOS objects, 37% free, 26MB/42MB, paused 1.896ms total 34.701ms
,W/GeofencerStateMachine( 1320): Ignoring removeGeofence because network location is disabled.
I/InputReader(  733): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator( 1084): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1084): run()
,I/Decoder ( 1084): createOrResetDecoder
,D/AdapterServiceConfig( 4877): Adding HeadsetService
D/AdapterServiceConfig( 4877): Adding A2dpService
D/AdapterServiceConfig( 4877): Adding HidService
D/AdapterServiceConfig( 4877): Adding HealthService
D/AdapterServiceConfig( 4877): Adding PanService
D/AdapterServiceConfig( 4877): Adding GattService
D/AdapterServiceConfig( 4877): Adding BluetoothMapService
,I/ActivityManager(  733): Killing 2518:com.google.android.music:main/u0a60 (adj 15): empty #17
,D/BackupManagerService(  733): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  733): Receieved: android.intent.action.PACKAGE_REMOVED
,D/AuthorizationBluetoothService( 1381): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/art     (  733): Explicit concurrent mark sweep GC freed 26074(1562KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 28MB/42MB, paused 1.588ms total 87.549ms
I/ConfigService( 1381): onCreate
W/libprocessgroup(  733): failed to open /acct/uid_10060/pid_2518/cgroup.procs: No such file or directory
,D/AndroidRuntime( 4840): Shutting down VM
,I/Launcher( 1287): Deferring update until onResume
D/TaskPersister(  733): removeObsoleteFile: deleting file=214_task.xml
,W/ResourcesManager( 1287): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/Keyboard.Facilitator.MainLanguageModelLoader( 1084): run()
,W/ResourcesManager( 1287): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1084): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/ActivityManager(  733): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=4942 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1084): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1084): run() : Loading LM = contacts
,I/Launcher( 1287): Deferring update until onResume
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1084): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1084): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1084): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1084): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1084): run() : Missing File = Personal.en_US.dict
,I/Keyboard.Facilitator.PersonalDictionaryLoader( 1084): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1084): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1084): run()
I/StatsUtilsManager( 1084): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1084): shouldRecordStats() = Too Soon
,W/ContextImpl( 4314): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver( 4314): finishStartingService: stopping service
,D/BluetoothAdapter( 4314): 80933736: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager(  733): Killing 3349:com.google.android.apps.magazines/u0a61 (adj 15): empty #17

```
