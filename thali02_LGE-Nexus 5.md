#### Test 52971095ef317fc_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/Finsky  ( 2372): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 2814): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2814): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  761): Killing 2104:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
V/JNIHelp ( 2814): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
W/libprocessgroup(  761): failed to open /acct/uid_1000/pid_2104/cgroup.procs: No such file or directory
W/System  ( 2814): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2814): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1436): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AndroidRuntime( 2862): 
D/AndroidRuntime( 2862): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2862): CheckJNI is OFF
D/AndroidRuntime( 2862): Calling main entry com.android.commands.am.Am
I/ActivityManager(  761): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/Icing   ( 1558): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/ActivityManager(  761): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2879 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2862): Shutting down VM
V/ActivityManager(  761): Display changed displayId=0
D/Icing   ( 1558): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1558): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/WebViewFactory( 2879): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2879): Time to load native libraries: 1 ms (timestamps 5367-5368)
I/LibraryLoader( 2879): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2879): Binding Chromium to main looper Looper (main, tid 1) {32b9dd16}
I/LibraryLoader( 2879): Expected native library version number "",actual native library version number ""
I/chromium( 2879): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2879): Initializing chromium process, singleProcess=true
W/art     ( 2879): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2879): ApplicationContext is null in ApplicationStatus
W/chromium( 2879): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 2879): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 2879): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2879): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 2879): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@34f64ab6:true
D/BluetoothAdapter( 2879): 200193186: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 2879): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2879): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2879): CordovaWebView is running on device made by: LGE
,W/art     ( 2879): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2879): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2879): Render dirty regions requested: true
,D/Atlas   ( 2879): Validating map...
,W/chromium( 2879): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2879): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2879): Enabling debug mode 0
,I/Keyboard.Facilitator( 1071): onFinishInput()
,W/IInputConnectionWrapper( 2879): showStatusIcon on inactive InputConnection
,I/ActivityManager(  761): Displayed com.test.thalitest/.MainActivity: +411ms (total +53s744ms)
,W/BindingManager( 2879): Cannot call determinedVisibility() - never saw a connection for the pid: 2879
,D/JsMessageQueue( 2879): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 2879): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 2879): jxcore cordova android initializing
,I/ActivityManager(  761): Killing 2198:com.google.android.youtube/u0a80 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10080/pid_2198/cgroup.procs: No such file or directory
,W/jxcore-log( 2879): Initializing JXcore engine
W/jxcore-log( 2879): JXcore engine is ready
W/jxcore-log( 2879): Starting JXcore engine
W/.test.thalitest( 2879): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7956]" dev="sockfs" ino=7956 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 2879): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 2879): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8466]" dev="sockfs" ino=8466 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 2879): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[17406]" dev="sockfs" ino=17406 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 2879): Platform android
W/jxcore-log( 2879): 
W/jxcore-log( 2879): Process ARCH arm
W/jxcore-log( 2879): 
I/jxcore-log( 2879): JXcore Cordova bridge is ready!
I/jxcore-log( 2879): 
W/jxcore-log( 2879): JXcore engine is started
I/Choreographer( 2879): Skipped 113 frames!  The application may be doing too much work on its main thread.
I/chromium( 2879): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/jxcore-log( 2879): Toggling radios to true
I/jxcore-log( 2879): 
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  761): enable():  mBluetooth =null mBinding = false
D/BluetoothManagerService(  761): Message: 1
D/BluetoothManagerService(  761): MESSAGE_ENABLE: mBluetooth = null
D/WifiService(  761): New client listening to asynchronous messages
D/WifiService(  761): setWifiEnabled: true pid=2879, uid=10270
E/WifiService(  761): Invoking mWifiStateMachine.setWifiEnabled
D/SoftapController(  179): Softap fwReload - Ok
I/ActivityManager(  761): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=2950 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
D/CommandListener(  179): Setting iface cfg
D/CommandListener(  179): Trying to bring down wlan0
D/CommandListener(  179): Clearing all IP addresses on wlan0
I/jxcore-log( 2879): Radios toggled
I/jxcore-log( 2879): 
D/WifiMonitor(  761): startMonitoring(wlan0) with mConnected = false
,I/ActivityManager(  761): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=2958 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/wpa_supplicant( 2957): Successfully initialized wpa_supplicant
,W/ResourcesManager( 2950): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/wpa_supplicant( 2957): rfkill: Cannot open RFKILL control device
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@37f29ab5:true
,D/BluetoothAdapter( 2958): 851041558: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothManagerService(  761): Message: 30
,D/BluetoothManagerService(  761): Message: 30
,D/LocalBluetoothProfileManager( 2958): Adding local MAP profile
,D/BluetoothMap( 2958): Create BluetoothMap proxy object
,D/BluetoothManagerService(  761): Message: 30
,D/BluetoothManagerService(  761): Message: 30
,D/LocalBluetoothProfileManager( 2958): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 2958): 851041558: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2958): 851041558: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager(  761): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=2999 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  761): Killing 2292:com.google.android.deskclock/u0a38 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10038/pid_2292/cgroup.procs: No such file or directory
,D/AdapterServiceConfig( 2950): Adding HeadsetService
D/AdapterServiceConfig( 2950): Adding A2dpService
,D/AdapterServiceConfig( 2950): Adding HidService
,D/AdapterServiceConfig( 2950): Adding HealthService
,D/AdapterServiceConfig( 2950): Adding PanService
D/AdapterServiceConfig( 2950): Adding GattService
D/AdapterServiceConfig( 2950): Adding BluetoothMapService
,D/BluetoothManagerService(  761): Message: 20
,D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3c19faab:true
,D/BluetoothAdapterState( 2950): make
,I/bluedroid( 2950): init
I/BluetoothAdapterState( 2950): Entering OffState
,I/bte_conf( 2950): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 2950): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,E/bt_osi_config( 2950): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 2950): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,I/bluedroid( 2950): get_profile_interface socket
I/bluedroid( 2950): get_profile_interface map_client
,I/GKI_LINUX( 2950): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothManagerService(  761): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  761): Message: 40
,D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothAdapterProperties( 2950): Address is:34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): Bluetooth Adapter name changed to Nexus 5
D/BluetoothAdapterProperties( 2950): Name is: Nexus 5
,D/BluetoothManagerService(  761): Stored Bluetooth name: Nexus 5
,I/bluedroid( 2950): config_hci_snoop_log
,D/BluetoothManagerService(  761): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  761): Broadcasting onBluetoothServiceUp() to 10 receivers.
,D/BluetoothAdapterState( 2950): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 2950): Setting state to 11
I/BluetoothAdapterState( 2950): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService(  761): Message: 60
,D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  761): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 2950): make
,I/BluetoothBondStateMachine( 2950): StableState(): Entering Off State
,D/BluetoothHeadset(  761): Proxy object connected
D/BluetoothHeadset( 1164): Proxy object connected
D/HeadsetService( 2950): Received start request. Starting profile...
D/BluetoothHeadset( 1164): Proxy object connected
,I/BluetoothHeadsetServiceJni( 2950): classInitNative: succeeds
D/BluetoothHeadset( 1207): Proxy object connected
,D/HeadsetStateMachine( 2950): make
,I/BluetoothAdapterState( 2950): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetStateMachine( 2950): max_hf_connections = 1
I/bluedroid( 2950): get_profile_interface handsfree
,D/BluetoothAdapterService( 2950): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f840697
D/HeadsetStateMachine( 2950): Enter Disconnected: -2, size: 0
D/BluetoothA2dp(  761): Proxy object connected
,D/A2dpService( 2950): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni( 2950): classInitNative: succeeds
I/bluedroid( 2950): get_profile_interface avrcp
,E/RemoteController( 2950): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 2950): classInitNative: succeeds
D/A2dpStateMachine( 2950): make
,I/bluedroid( 2950): get_profile_interface a2dp
I/GKI_LINUX( 2950): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothAdapterService( 2950): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f840697
I/BluetoothHidServiceJni( 2950): classInitNative: succeeds
D/A2dpStateMachine( 2950): Enter Disconnected: -2
,D/BluetoothInputDevice( 2958): Proxy object connected
D/HidService( 2950): Received start request. Starting profile...
I/bluedroid( 2950): get_profile_interface hidhost
,D/BluetoothAdapterService( 2950): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f840697
D/HidProfile( 2958): Bluetooth service connected
I/BluetoothHealthServiceJni( 2950): classInitNative: succeeds
,D/HealthService( 2950): Received start request. Starting profile...
,I/bluedroid( 2950): get_profile_interface health
D/BluetoothAdapterService( 2950): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f840697
,I/BluetoothPanServiceJni( 2950): classInitNative(L105): succeeds
,D/BluetoothPan( 2958): BluetoothPAN Proxy object connected
D/PanService( 2950): Received start request. Starting profile...
D/PanProfile( 2958): Bluetooth service connected
D/BluetoothPanServiceJni( 2950): initializeNative(L110): pan
I/bluedroid( 2950): get_profile_interface pan
,D/BluetoothAdapterService( 2950): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f840697
I/BtGatt.JNI( 2950): classInitNative(L863): classInitNative: Success!
D/BtGatt.DebugUtils( 2950): handleDebugAction() action=null
,D/BtGatt.GattService( 2950): Received start request. Starting profile...
,D/BtGatt.GattService( 2950): start()
I/bluedroid( 2950): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 2950): advertise manager created
,D/BluetoothAdapterService( 2950): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f840697
,V/BluetoothMapService( 2950): BluetoothMapBinder()
,D/BluetoothMap( 2958): Proxy object connected
D/BluetoothMapService( 2950): Received start request. Starting profile...
,D/BluetoothMapService( 2950): start()
D/MapProfile( 2958): Bluetooth service connected
D/BluetoothMap( 2958): getConnectedDevices()
,D/BluetoothMap( 2958): Bluetooth is Not enabled
,D/BluetoothMapEmailSettingsLoader( 2950): Found 0 applications
D/BluetoothMapEmailAppObserver( 2950): createReceiver()
,D/BluetoothMapEmailAppObserver( 2950): initObservers()
D/BluetoothMapEmailAppObserver( 2950): getEnabledAccountItems()
D/BluetoothAdapterService( 2950): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f840697
D/HeadsetStateMachine( 2950): Proxy object connected
,V/BluetoothMapService( 2950): Handler(): got msg=1
D/HeadsetStateMachine( 2950): Disconnected process message: 10, size: 0
,D/BluetoothAdapterState( 2950): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 2950): enable
D/HeadsetPhoneState( 2950): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 2950): Disconnected process message: 11, size: 0
,I/GKI_LINUX( 2950): gki_task_entry task_id=0 [BTU] starting
,I/bt-btu  ( 2950): btu_task pending for preload complete event
I/bt_hci_bdroid( 2950): init
,I/bt_vendor( 2950): init
I/bt_vnd_conf( 2950): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 2950): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 2950): userial_init
,I/art     ( 1436): Explicit concurrent mark sweep GC freed 9266(538KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 19MB/32MB, paused 519us total 21.743ms
,I/bt_userial_vendor( 2950): userial vendor open: opening /dev/ttyHS99
,I/bt_userial_vendor( 2950): device fd = 53 open
D/bt_userial( 2950): Entering userial_read_thread()
,D/AuthorizationBluetoothService( 1436): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/bt_hwcfg( 2950): bt vendor lib: set UART baud 4000000
,I/ActivityManager(  761): Killing 2340:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,D/bt_hwcfg( 2950): Chipset BCM4335C0
D/bt_hwcfg( 2950): Target name = [BCM4335C0]
,I/bt_hwcfg( 2950): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,W/libprocessgroup(  761): failed to open /acct/uid_10069/pid_2340/cgroup.procs: No such file or directory
,D/Tethering(  761): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 2957): rfkill: Cannot open RFKILL control device
,I/bt_hwcfg( 2950): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 2950): Settlement delay -- 100 ms
I/bt_hwcfg( 2950): Setting fw settlement delay to 100 
,I/wpa_supplicant( 2957): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiConfigStore(  761): Loading config and enabling all networks 
,E/WifiConfigStore(  761): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,W/Settings( 1797): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-HAL(  761): Setting external_sim to 1
,D/WifiStateMachine(  761): Setting OUI to DA-A1-19
I/WifiNative-HAL(  761): startHal
D/wifi    (  761): setting scan oui 0x979ff1a8
D/WifiHAL (  761): Sending mac address OUI
E/WifiHAL (  761): failed to set scanning mac OUI; result = -95
,E/native  (  761): do suspend true
,D/WifiService(  761): New client listening to asynchronous messages
,D/CommandListener(  179): Setting iface cfg
D/CommandListener(  179): Trying to bring up p2p0
,D/WifiMonitor(  761): startMonitoring(p2p0) with mConnected = true
,D/WifiScanningService(  761): SCAN_AVAILABLE : 3
D/RttService(  761): SCAN_AVAILABLE : 3
D/RttService(  761): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiScanningService(  761): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  761): startHal
D/wifi    (  761): getting scan capabilities on interface[1] = 0x979ff1a8
,D/WifiHAL (  761): Creating message to get scan capablities; iface = 21
D/WifiHAL (  761): In GetCapabilities::handleResponse
D/WifiHAL (  761): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  761): StartedState
,I/bt_hwcfg( 2950): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 2950): Setting local bd addr to 34:FC:EF:11:AE:67
,I/wpa_supplicant( 2957): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,D/WifiNative-HAL(  761): p2pGetDeviceAddress
,D/WifiNative-HAL(  761): p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,I/bt_hwcfg( 2950): vendor lib fwcfg completed
,I/bt-btu  ( 2950): btu_task received preload complete event
,I/        ( 2950): BTE_InitTraceLevels -- TRC_HCI
I/        ( 2950): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 2950): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 2950): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 2950): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 2950): BTE_InitTraceLevels -- TRC_A2D
I/        ( 2950): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 2950): BTE_InitTraceLevels -- TRC_BTM
I/        ( 2950): BTE_InitTraceLevels -- TRC_GAP
I/        ( 2950): BTE_InitTraceLevels -- TRC_PAN
I/        ( 2950): BTE_InitTraceLevels -- TRC_SDP
I/        ( 2950): BTE_InitTraceLevels -- TRC_GATT
I/        ( 2950): BTE_InitTraceLevels -- TRC_SMP
I/        ( 2950): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 2950): BTE_InitTraceLevels -- TRC_BTIF
,I/ActivityManager(  761): Killing 1779:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,E/bt-btm  ( 2950): BTM_SecRegister:p_cb_info->p_le_callback == 0xa3cd99d5 
E/bt-btm  ( 2950): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3cd99d5 
,W/libprocessgroup(  761): failed to open /acct/uid_10045/pid_1779/cgroup.procs: No such file or directory
,E/bt-btif ( 2950): Calling BTA_HhEnable
E/bt-btif ( 2950): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 2950): Address is:34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  761): Stored Bluetooth name: Nexus 5
,D/BluetoothAdapterProperties( 2950): Name is: Nexus 5
,W/bt-smp  ( 2950): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2950): Plain text(LSB ~ MSB) = 4b 15 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2950): Encrypted text(LSB ~ MSB) = ae ae a9 fe 0b 7b c2 ee f7 64 18 db d4 92 3f f3 
W/bt-btm  ( 2950): Stopping oneshot timer
,D/BluetoothAdapterProperties( 2950): Scan Mode:20
D/BluetoothAdapterProperties( 2950): Discoverable Timeout:120
,D/bte_conf( 2950): Device ID record 1 : primary
D/bte_conf( 2950):   vendorId            = 000f
D/bte_conf( 2950):   vendorIdSource      = 0001
D/bte_conf( 2950):   product             = 1200
D/bte_conf( 2950):   version             = 1436
D/bte_conf( 2950):   clientExecutableURL = 
D/bte_conf( 2950):   serviceDescription  = 
D/bte_conf( 2950):   documentationURL    = 
D/bte_conf( 2950): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 2950): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 2950): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 2950): ScanMode =  20
D/BluetoothAdapterProperties( 2950): State =  11
D/BluetoothAdapterProperties( 2950): Scan Mode:21
D/BluetoothAdapterProperties( 2950): Discoverable Timeout:120
,D/BluetoothAdapterProperties( 2950): Setting state to 12
I/BluetoothAdapterState( 2950): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService(  761): Message: 60
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
I/BluetoothAdapterState( 2950): Entering On State
D/BluetoothManagerService(  761): Broadcasting onBluetoothStateChange(true) to 9 receivers.
D/BluetoothPan( 2958): onBluetoothStateChange(on) call bindService
D/BluetoothPbap( 2958): onBluetoothStateChange: up=true
D/BluetoothMap( 2958): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1207): onBluetoothStateChange: up=true
D/BluetoothInputDevice( 2958): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1164): onBluetoothStateChange: up=true
D/BluetoothA2dp(  761): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1164): onBluetoothStateChange: up=true
D/BluetoothHeadset(  761): onBluetoothStateChange: up=true
D/BluetoothManagerService(  761): Bluetooth State Change Intent: 11 -> 12
,E/bt_h4   ( 2950): vendor lib postload completed
D/BluetoothMapService( 2950): onReceive
D/BluetoothMapService( 2950): STATE_ON
,V/BluetoothMapService( 2950): Handler(): got msg=1
,D/BluetoothMapMasInstance( 2950): Map Service startRfcommSocketListener
D/BluetoothMapMasInstance( 2950): MAS initSocket()
D/BluetoothMapMasInstance( 2950):   masId = 00
D/BluetoothMapMasInstance( 2950):   msgTypes = 0e
D/BluetoothMapMasInstance( 2950):   masName = SMS/MMS
D/BluetoothMapMasInstance( 2950):   SDP string = 000eSMS/MMS
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2950): getBluetoothService() called with no BluetoothManagerCallback
,V/BluetoothMapMasInstance( 2950): Succeed to create listening socket 
D/BluetoothMapMasInstance( 2950): Accepting socket connection...
I/Telecom ( 1164): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/LocalBluetoothProfileManager( 2958): Adding local A2DP profile
D/BluetoothManagerService(  761): Message: 30
D/HeadsetStateMachine( 2950): Disconnected process message: 9, size: 0
D/HeadsetStateMachine( 2950): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 2950): mNumber:  mType: 128
D/HeadsetStateMachine( 2950): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 2950): terminateScoUsingVirtualVoiceCall:No present call to terminate
D/LocalBluetoothProfileManager( 2958): Adding local HEADSET profile
D/BluetoothManagerService(  761): Message: 30
,W/ContextImpl( 2958): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothA2dp( 2958): Proxy object connected
D/A2dpProfile( 2958): Bluetooth service connected
,I/art     (  761): Explicit concurrent mark sweep GC freed 23851(1219KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 2.257ms total 105.203ms
,D/BluetoothManagerService(  761): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothManagerService(  761): Message: 40
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 2950): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothHeadset( 2958): Proxy object connected
D/HeadsetProfile( 2958): Bluetooth service connected
,D/DockEventReceiver( 2958): finishStartingService: stopping service
,D/BluetoothPbap( 2958): Proxy object connected
,D/PbapServerProfile( 2958): Bluetooth service connected
,D/AuthorizationBluetoothService( 1436): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2950): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 2950): Accept thread started.
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 2879): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): my name is : LGE-Nexus 5_PT1108
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): attempting to connect to test coordinator
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): check test folder
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): found test : ./testFindPeers.js
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): found test : ./testReConnect.js
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): found test : ./testSendData.js
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): Test app app.js loaded
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/chromium( 2879): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  761): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiStateMachine(  761): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  761): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=1
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,E/WifiConfigStore(  761): writeKnownNetworkHistory write linked 1
E/WifiConfigStore(  761): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  761): will read network variables netId=1
,E/WifiStateMachine(  761): CMD_AUTO_CONNECT did save config ->  nid=1
,E/WifiConfigStore(  761): will read network variables netId=1
,I/wpa_supplicant( 2957): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,E/WifiConfigStore(  761): setLastSelectedConfiguration -1
,E/wpa_supplicant( 2957): PNO: In assoc process
,I/wpa_supplicant( 2957): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 2957): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2957): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  761): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  761): Start Dhcp Watchdog 1
,E/native  (  761): do suspend false
,E/WifiStateMachine(  761): scanCount==0 - aborting
,I/dhcpcd  ( 3105): version 5.5.6 starting
,E/dhcpcd  ( 3105): get_duid: Read-only file system
,I/dhcpcd  ( 3105): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3105): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3105): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  761): do suspend true
,E/WifiStateMachine(  761): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  761): Adding iface wlan0 to network 100
,V/GLSActivity( 1436): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1436): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ConnectivityService(  761): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  761): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  761): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  761): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService(  761): Setting Dns servers for network 100 to [/192.168.1.1]
D/Nat464Xlat(  761): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  761): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  761): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  761):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on "NG7005g"
D/ConnectivityService(  761): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
,D/CSLegacyTypeTracker(  761): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  761): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  916): CM callback handler got msg 524290
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 08 Dec 2015 16:08:57 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449590937408], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449590937388]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Validated
,D/ConnectivityService(  761): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  761): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/TelephonyNetworkFactory( 1207): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler(  916): CM callback handler got msg 524290
,I/jxcore-log( 2879): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,D/AlarmManagerService(  761): Setting time of day to sec=1449590940
,W/AlarmManagerService(  761): Unable to set rtc to 1449590940: Invalid argument
,I/ActivityManager(  761): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3169 uid=10076 gids={50076, 9997} abi=armeabi-v7a
,D/TimeService( 3169): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449590940524
D/        ( 3169): TimeServiceNative: User Time to be set is 1449590940524
D/QC-time-services( 3169): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3169): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3169): Lib:time_genoff_operation: pargs->ts_val = 1449590940524
D/QC-time-services( 3169): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  197): Daemon: Connection accepted:time_genoff
D/QC-time-services(  197): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449590940524
D/QC-time-services(  197): Daemon:genoff_opr: Base = 2, val = 1449590940524, operation = 0
D/QC-time-services(  197): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/11/70 21:59:45
D/QC-time-services(  197): Daemon:Value read from RTC seconds = 8719185000
D/QC-time-services(  197): Daemon:new time 1449590940524 
D/QC-time-services(  197): Daemon: delta 1440871755524 genoff 1440871755524 
D/QC-time-services(  197): Daemon:genoff_persistent_update: Writing genoff = 1440871755524 to memory
D/QC-time-services(  197): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  197): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  197): Updating the TOD offset
,D/QC-time-services(  197): Daemon:genoff_persistent_update: Writing genoff = 1440871755524 to memory
D/QC-time-services(  197): Daemon:Opening File: /data/system/time/ats_1
D/QC-time-services(  197): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  197): Daemon:Update to modem bit set
,D/QC-time-services(  197): Daemon:genoff_send_modem: Sending data to MODEM !
E/QC-time-services( 3169): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  197): Daemon: Base = 2, Value being sent to MODEM = 1133626140524
,D/QC-time-services(  197): Daemon: Time-services: Waiting to acceptconnection
,D/QC-time-services(  197): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,I/CheckinService( 1558): Checkin interval check for package: unspecified last checkin: 1449576468976 min interval config: 0 actual interval: 14471571
,I/ActivityManager(  761): Killing 2420:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10003/pid_2420/cgroup.procs: No such file or directory
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2449): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  761): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=3215 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/art     (  194): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 223us total 9.815ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 374us total 14.220ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 361us total 15.606ms
,I/ActivityManager(  761): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=3233 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  761): No APN found to select.
,D/GpsLocationProvider(  761): NTP server returned: 1449590937703 (Tue Dec 08 17:08:57 GMT+01:00 2015) reference: 82568 certainty: 13 system time offset: -3115
E/LocSvc_eng(  761): E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,I/GAv4    ( 3215): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3215):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3215):   adb logcat -s GAv4
,W/GAv4    ( 3215): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Auth.Api.Credentials( 1558): [CredentialSyncAdapter] Unknown sync event.
,W/ResourcesManager( 3233): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3233): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/GAv4    ( 3215): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3215): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/JNIHelp ( 3233): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,V/MusicLeanback( 2449): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,W/System  ( 3233): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 3233): Installed default security provider GmsCore_OpenSSL
,I/iu.SyncManager( 1558): SYNC; picasa accounts
,D/NetworkLogImpl( 1558): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1558): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1558): num queued entries: 0
,D/ChimeraCfgMgr( 1558): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/iu.UploadsManager( 1558): num updated entries: 0
,I/iu.SyncManager( 1558): NEXT; no task
,D/ChimeraCfgMgr( 1558): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/SystemUpdateService( 1558): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1558): onCreate
,D/SystemUpdateService( 1558): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1558): active receiver: enabled
,I/SystemUpdateService( 1558): showing system update notification
,V/GLSActivity( 1436): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/YouTube MDX( 3233): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,V/GLSActivity( 1436): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1558): retry (wakeup: false) in 3599969 ms
,I/ActivityManager(  761): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3297 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/dex2oat ( 3298): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-1068558210.jar --oat-fd=30 --oat-location=/data/data/com.google.android.youtube/cache/ads-1068558210.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/SystemUpdateService( 1558): onDestroy
,V/GLSActivity( 1436): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1436): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  761): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  761): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  761): apparently satisfied.  currentScore=60
,D/ConnectivityManager.CallbackHandler( 1558): CM callback handler got msg 524290
,I/dex2oat ( 3298): dex2oat took 67.327ms (threads: 4)
,I/Babel   ( 1797): connection state changed from UNKNOWN to CONNECTED
,I/GCM     ( 1436): GCM config loaded
,I/GAv4    ( 3297): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3297):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3297):   adb logcat -s GAv4
,I/art     (  761): Explicit concurrent mark sweep GC freed 40053(1959KB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 27MB/41MB, paused 1.282ms total 70.386ms
,W/InstanceID/Rpc( 3233): Found 10008
,W/GAv4    ( 3297): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/PerfProfileCollectorService( 1558): User is not opt-in to Usage & Diagnostics.
D/PerfProfileCollectorService( 1558): removeStateFiles() called
,D/PerfProfileCollectorService( 1558): User is not opt-in to Usage & Diagnostics.
,W/GAv4    ( 3297): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/art     ( 2573): Attempt to remove local handle scope entry from IRT, ignoring
,W/GAv4    ( 3297): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/art     ( 1436): Explicit concurrent mark sweep GC freed 14279(975KB) AllocSpace objects, 16(256KB) LOS objects, 39% free, 19MB/32MB, paused 1.469ms total 38.107ms
,E/Auth.Api.Credentials( 1558): [CredentialSyncAdapter] Unknown sync event.
,W/Gmail   ( 2314): Sync started for account: account:61035162
,I/Gmail   ( 2314): notifyAccountChanged
,I/Gmail   ( 2314): getAccountsCursor
,W/DriveInitializer( 1558): Awaiting to be initialized
,V/GLSActivity( 1436): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/DriveInitializer( 1558): Background init thread started
,I/WebViewFactory( 3297): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3297): Time to load native libraries: 2 ms (timestamps 6543-6545)
,I/LibraryLoader( 3297): Expected native library version number "",actual native library version number ""
,I/Gmail   ( 2314): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 12009, normalSync: true
,V/WebViewChromiumFactoryProvider( 3297): Binding Chromium to main looper Looper (main, tid 1) {fc01398}
,I/LibraryLoader( 3297): Expected native library version number "",actual native library version number ""
,I/chromium( 3297): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3297): Initializing chromium process, singleProcess=true
W/art     ( 3297): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3297): ApplicationContext is null in ApplicationStatus
,W/chromium( 3297): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3297): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3297): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3297): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/ResourcesManager( 2314): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 2314): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/AudioManagerAndroid( 3297): Requires BLUETOOTH permission
,V/JNIHelp ( 2314): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/NSApplication( 3297): Starting up...
,I/VacuumService( 1436): Vacuum at: now=1449590941759 tag=VacuumService
,W/System  ( 2314): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[directory "."],nativeLibraryDirectories=[/vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 2314): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1436): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/DriveInitializer( 1558): Background init thread ended
,I/ActivityManager(  761): Killing 1930:com.android.providers.calendar/u0a2 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10002/pid_1930/cgroup.procs: No such file or directory
,I/GoogleURLConnFactory( 1558): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1436): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1436): Explicit concurrent mark sweep GC freed 22723(1334KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 19MB/32MB, paused 816us total 27.324ms
,V/GLSActivity( 1436): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1558): Explicit concurrent mark sweep GC freed 22189(1426KB) AllocSpace objects, 23(391KB) LOS objects, 39% free, 22MB/37MB, paused 920us total 44.401ms
,V/NQFileLogger( 1436): [187] e.a: about to write to file
,V/ProcessReports( 1436): [187] ProcessReportsService.a: If not already scheduled, schedule for 3600 to 14400 seconds from now (but might be processed inline after 900 seconds instead)
,I/art     ( 2314): Explicit concurrent mark sweep GC freed 52995(1671KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 18MB/25MB, paused 317us total 26.637ms
,I/Gmail   ( 2314): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 12087, normalSync: true
,I/Gmail   ( 2314): lowestBackward conversation id 0
,I/art     (  761): Explicit concurrent mark sweep GC freed 29580(1264KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 853us total 51.172ms
,I/Gmail   ( 2314): notifyAccountChanged
,I/Gmail   ( 2314): getAccountsCursor
,V/GLSActivity( 1436): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 2314): notifyAccountChanged
,W/Gmail   ( 2314): Sync complete for account: account:61035162
I/Gmail   ( 2314): getAccountsCursor
,V/GLSActivity( 1436): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  761): Killing 1475:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10013/pid_1475/cgroup.procs: No such file or directory
,V/GLSActivity( 1436): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ValidateNoPeople(  761): mEvictionCount: 0
,E/SQLiteLog( 1361): (284) automatic index on sqlite_sq_AF82E970(STAT_DATA_ID)
,E/SQLiteLog( 1361): (284) automatic index on sqlite_sq_AF82E6A0(STAT_DATA_ID)
,E/SQLiteLog( 1361): (284) automatic index on sqlite_sq_A3B71830(STAT_DATA_ID)
,E/SQLiteLog( 1361): (284) automatic index on sqlite_sq_A3B71240(STAT_DATA_ID)
,W/AbstractGoogleClient( 2011): Application name is not set. Call Builder#setApplicationName.
,I/AnalyticsLogBase( 2011): PlayLogger.onLoggerConnected
,I/ActivityManager(  761): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3525 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 3525): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 3525): Created com.android.providers.calendar.CalendarAlarmManager@16a51231(com.android.providers.calendar.CalendarProvider2@32b9dd16)
,V/GLSActivity( 1436): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 1558): Indexing 009F7E1EAB88E81C4EB4149FAD093AD3E8757DF2 from com.google.android.gm
,I/Gmail   ( 2314): Backfilling search sequence table
,I/Icing   ( 1558): Indexing done 009F7E1EAB88E81C4EB4149FAD093AD3E8757DF2
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,D/Finsky  ( 2372): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 1 successful.
,D/Finsky  ( 2372): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/CalendarSyncAdapter( 2011): Found no pending settings
,I/RemindersSync( 1558): Found sync condition that we don't recognize, aborting. [T SyncAdapterThread-1:id=232:priority=5:group=main]
,E/SQLiteLog( 3525): (284) automatic index on view_events(_id)
,I/art     (  761): Explicit concurrent mark sweep GC freed 19126(803KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.030ms total 53.588ms
,I/art     ( 1280): Explicit concurrent mark sweep GC freed 16659(1034KB) AllocSpace objects, 19(304KB) LOS objects, 39% free, 19MB/32MB, paused 788us total 24.440ms
,E/DataBuffer( 1280): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1749ba2a)
,W/BaseAppContext( 1280): Using Auth Proxy for data requests.
,I/art     ( 1436): Explicit concurrent mark sweep GC freed 31300(1743KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 20MB/33MB, paused 1.519ms total 54.810ms
,W/BaseAppContext( 1558): Using Auth Proxy for data requests.
W/BaseAppContext( 1558): Using Auth Proxy for data requests.
,W/BaseAppContext( 1558): Using Auth Proxy for data requests.
,W/BaseAppContext( 1558): Using Auth Proxy for data requests.
,W/BaseAppContext( 1558): Using Auth Proxy for data requests.
,W/BaseAppContext( 1558): Using Auth Proxy for data requests.
,W/BaseAppContext( 1558): Using Auth Proxy for data requests.
,I/CalendarProvider2( 3525): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 3525): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/GHttpClientFactory( 2449): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 2449): Using platform SSLCertificateSocketFactory
,I/MusicLifecycle( 2449): Sync started
,V/GLSActivity( 1436): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1280): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,I/GCoreUlr( 1280): DispatchingService.onCreate()
,I/ActivityManager(  761): Start proc com.google.android.videos for service com.google.android.videos/.store.SyncService: pid=3595 uid=10077 gids={50077, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/GCoreUlr( 1280): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1280): Unbound from all location providers
,I/GCoreUlr( 1280): DispatchingService.onDestroy()
I/GCoreUlr( 1280): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1280): Unbound from all location providers
,W/ResourcesManager( 3595): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,I/MusicSyncAdapter( 2449): Skipping periodic sync. Last sync was 14475 seconds ago. Frequency: 86400
,W/MusicApiClient( 2449): Activity events list is null or empty. Skip reporting.
,I/MusicLifecycle( 2449): Sync ended
,D/WearableService( 1280): callingUid 10008, callindPid: 1280
,I/MusicLeanback( 2449): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 2449): Stop autocaching.
,E/GmsUtils( 2449): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 2449): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/ActivityManager(  761): Start proc com.google.android.apps.cloudprint:sync for service com.google.android.apps.cloudprint/.printdialog.services.CloudPrintSyncService: pid=3622 uid=10035 gids={50035, 9997, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager(  761): Start proc com.google.android.apps.cloudprint for service com.google.android.apps.cloudprint/.printdialog.services.NotificationIntentService: pid=3653 uid=10035 gids={50035, 9997, 3003, 1028} abi=armeabi-v7a
,D/PlayMovies( 3595): PersistentCache.cleanup:103 Cache is below limit, no need to shrink: [size=0, limit=5242880]
,D/PlayMovies( 3595): TransferService.onCreate:52 creating transfer service
,I/com.google.android.apps.cloudprint.printdialog.database.CloudPrintSyncAdapter( 3622): Sync request not initiated by GCP app. Dropping
,W/VideoCapabilities( 3595): Unrecognized profile 2130706433 for video/avc
,I/VideoCapabilities( 3595): Unsupported profile 4 for video/mp4v-es
,I/art     (  761): Explicit concurrent mark sweep GC freed 14627(624KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.402ms total 53.751ms
,I/ActivityManager(  761): Killing 2786:com.android.musicfx/u0a15 (adj 15): empty #17
,W/ResourcesManager( 1558): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,W/libprocessgroup(  761): failed to open /acct/uid_10015/pid_2786/cgroup.procs: No such file or directory
,I/ActivityManager(  761): Killing 2722:com.google.android.gms:car/u0a8 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10008/pid_2722/cgroup.procs: No such file or directory
,D/DelayedSyncController(  940): Delaying sync.
,I/SyncAdapterService( 3297): Ignoring sync request for non-current account
,D/UdcCache:FPQuery( 1558): Bootstrapping UDC settings cache for all accounts
,I/PlayMovies( 3595): SyncService.syncAllPurchasesAndWishlist:151 Starting sync for 515013DC511638B0584069811EF28701C0771BF5
,I/CalendarSyncAdapter( 2011): Found no pending settings
,I/PlayMovies( 3595): SyncService.waitForCompletion:177 Sync completed for 515013DC511638B0584069811EF28701C0771BF5 purchases
,I/PlayMovies( 3595): SyncService.waitForCompletion:177 Sync completed for 515013DC511638B0584069811EF28701C0771BF5 wishlist
,I/ActivityManager(  761): Killing 2814:com.google.android.apps.docs/u0a40 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10040/pid_2814/cgroup.procs: No such file or directory
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,D/GetConfigurationSnapshotOperation( 1436): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1436): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1436): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  761): Killing 2656:com.android.defcontainer/u0a5 (adj 15): empty #17
,I/art     ( 1436): Explicit concurrent mark sweep GC freed 18835(1074KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 20MB/33MB, paused 1.401ms total 32.501ms
,W/libprocessgroup(  761): failed to open /acct/uid_10005/pid_2656/cgroup.procs: No such file or directory
,D/GetCommittedConfigurationOperation( 1436): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1436): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/ActivityManager(  761): Killing 2958:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  761): Client connection lost with reason: 4
,W/libprocessgroup(  761): failed to open /acct/uid_1000/pid_2958/cgroup.procs: No such file or directory
,D/GetCommittedConfigurationOperation( 1436): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1436): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1436): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/Uploader( 1436):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1436): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1436): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1436): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1436): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1436): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1436): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1436): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1436): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/InputReader(  761): Reconfiguring input devices.  changes=0x00000010
,I/UpdateIcingCorporaServi( 1341): Updating corpora: APPS=com.google.android.videos, CONTACTS=MAYBE
,W/Launcher( 1250): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@f840697 new=com.google.android.velvet.VelvetApplication@f840697
,D/PackageBroadcastService( 1558): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.videos
,I/PeopleContactsSync( 1558): CP2 sync disabled
,D/BackupManagerService(  761): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.videos flg=0x4000010 (has extras) }
,I/UpdateIcingCorporaServi( 1341): UpdateCorporaTask done [took 54 ms] updated apps [took 54 ms] 
,I/Launcher( 1250): Deferring update until onResume
,W/ResourcesManager( 1250): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1250): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1250): Deferring update until onResume
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/Keyboard.Facilitator.LanguageModelFlusher( 1071): run()
I/Keyboard.Facilitator( 1071): flushDynamicLanguageModels()
,I/ConfigService( 1436): onCreate
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/ConfigService( 1436): onDestroy
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/ClearcutLoggerApiImpl( 1280): disconnect managed GoogleApiClient
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,E/DataBuffer( 1436): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@f24b8bc)
,E/DataBuffer( 1436): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@542045)
E/DataBuffer( 1436): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4f39a)
,E/DataBuffer( 1436): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@770d4cb)
E/DataBuffer( 1436): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2be2a4a8)
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/ClearcutLoggerApiImpl( 1436): disconnect managed GoogleApiClient
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector connect called
I/jxcore-log( 2879): 
I/jxcore-log( 2879): Coordinator is now connected to the server!
I/jxcore-log( 2879): 
,I/chromium( 2879): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,V/GLSActivity( 1436): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1436): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1436): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 2879): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector command called
I/jxcore-log( 2879): 
I/jxcore-log( 2879): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":22,"addressList":[{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"90:E7:C4:F6:69:77","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"38:94:96:B5:06:DC","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"7C:F9:0E:51:18:22","tryCount":0},{"address":"34:FC:EF:9D:93:0B","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"F8:95:C7:87:3C
I/jxcore-log( 2879): Start now : testSendData.js
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 22
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): check server
I/jxcore-log( 2879): 
I/jxcore-log( 2879): serverPort is 46178
I/jxcore-log( 2879): 
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): initialize: 34:FC:EF:11:AE:67 LGE-Nexus 5_PT1108
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 2879): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): setState: INITIALIZED
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1108","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1108","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1108","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 2879): start: OK
I/jxcore-log( 2879): StartBroadcasting started ok
I/jxcore-log( 2879): 
I/jxcore-log( 2879): do fake peer & start
I/jxcore-log( 2879): 
I/jxcore-log( 2879): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:14:44.155Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:14:44.156Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:14:44.156Z SendDataConnector.js: do connect now
I/jxcore-log( 2879): 
I/io.jxcore.node.ConnectionHelper( 2879): connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
W/io.jxcore.node.ConnectionHelper( 2879): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Trying to start connecting to null in address E0:DB:10:14:E2:C0
I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnecting: null E0:DB:10:14:E2:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Started connecting to null in address E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 2879): connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
I/jxcore-log( 2879): 2015-12-08T16:14:44.166Z SendDataTCPServer.js: TCP/IP server is bound to port: 46178
I/jxcore-log( 2879): 
I/chromium( 2879): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): startWifiPeerDiscovery: Already started
I/io.jxcore.node.ConnectionHelper( 2879): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery started successfully
I/io.jxcore.node.ConnectionHelper( 2879): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 273)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiP2pManager( 2879): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,W/bt-btif ( 2950): info:x10
,D/        ( 2950): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
E/BluetoothRemoteDevices( 2950): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2950): process_service_search_attr_rsp
,W/bt-btif ( 2950): info:x10
,D/        ( 2950): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
E/BluetoothRemoteDevices( 2950): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=1
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2950): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 2950): info:x10
,D/        ( 2950): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
E/BluetoothRemoteDevices( 2950): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 2950): info:x10
,D/        ( 2950): remote version info [58:2a:f7:ed:96:be]: 0, 0, 0
E/BluetoothRemoteDevices( 2950): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2950): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
E/bt-btif ( 2950): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2950): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2950): Entering PendingCommandState State
,I/ActivityManager(  761): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest: pid=3830 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
E/BluetoothRemoteDevices( 2950): aclStateChangeCallback: Device is NULL
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2fd3a6b1:true
,I/ActivityManager(  761): Killing 3169:com.qualcomm.timeservice/u0a76 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10076/pid_3169/cgroup.procs: No such file or directory
,E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2950): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 2950): info:x10
,D/        ( 2950): remote version info [58:2a:f7:ed:96:be]: 7, f, 610c
,E/BluetoothRemoteDevices( 2950): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2950): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 2950): info:x10
,D/        ( 2950): remote version info [b0:c5:59:3f:75:69]: 6, 10f, 608
,E/BluetoothRemoteDevices( 2950): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2950): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 2950): Failed to remove device: E0:DB:10:14:E2:C0
,I/BluetoothBondStateMachine( 2950): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2950): StableState(): Entering Off State
,E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2950): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=0
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2950): info:x10
,D/        ( 2950): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 2950): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=1
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2950): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
E/bt-btif ( 2950): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2950): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2950): Entering PendingCommandState State
,W/bt-btif ( 2950): info:x10
,D/        ( 2950): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/BluetoothRemoteDevices( 2950): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2950): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,D/BluetoothAdapterProperties( 2950): Failed to remove device: B0:C5:59:3F:75:69
,I/BluetoothBondStateMachine( 2950): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2950): StableState(): Entering Off State
,W/bt-btif ( 2950): new conn_srvc id:26, app_id:255
W/bt-btif ( 2950): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2950): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Incoming connection initialized (thread ID: 275)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Entering thread (ID: 275)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): onBytesRead: Read 82 bytes successfully (thread ID: 275)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Got valid identity from [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5421 B0:C5:59:3F:75:69]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): onBytesWritten: 77 bytes successfully written (thread ID: 275)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): removeThreadFromList: Removing thread with ID 275
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Handshake thread disposed (thread ID: 275)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onIncomingConnectionConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5421 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Exiting thread (ID: 275)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5421 B0:C5:59:3F:75:69]
,I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Incoming connection, peer ID: B0:C5:59:3F:75:69, name: samsung-SM-G900F_PT5421, Bluetooth address: B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Adding peer with ID B0:C5:59:3F:75:69
,I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Incoming socket thread, for peer with ID B0:C5:59:3F:75:69, created successfully
,D/io.jxcore.node.ConnectionHelper( 2879): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 2879): Entering thread (ID: 276)
,I/io.jxcore.node.IncomingSocketThread( 2879): Local host address: localhost/127.0.0.1, port: 46178
D/io.jxcore.node.IncomingSocketThread( 2879): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 2879): 2015-12-08T16:14:51.699Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2879): 
,I/io.jxcore.node.IncomingSocketThread( 2879): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 2879): Exiting thread (ID: 276)
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 277, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 278, name: Receiver)
,I/BluetoothBondStateMachine( 2950): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 1
E/bt-btif ( 2950): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2950): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2950): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2950): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 0
,D/BluetoothAdapterProperties( 2950): Failed to remove device: 58:2A:F7:ED:96:BE
,I/BluetoothBondStateMachine( 2950): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2950): StableState(): Entering Off State
,W/bt-btif ( 2950): new conn_srvc id:26, app_id:255
W/bt-btif ( 2950): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2950): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Incoming connection initialized (thread ID: 279)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Entering thread (ID: 279)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): onBytesRead: Read 80 bytes successfully (thread ID: 279)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Got valid identity from [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT9989 58:2A:F7:ED:96:BE]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): onBytesWritten: 77 bytes successfully written (thread ID: 279)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): removeThreadFromList: Removing thread with ID 279
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Handshake thread disposed (thread ID: 279)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onIncomingConnectionConnected: [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT9989 58:2A:F7:ED:96:BE]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnected: [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT9989 58:2A:F7:ED:96:BE]
I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Incoming connection, peer ID: 58:2A:F7:ED:96:BE, name: HUAWEI-ALE-L21_PT9989, Bluetooth address: 58:2A:F7:ED:96:BE
,D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 58:2A:F7:ED:96:BE
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Adding peer with ID 58:2A:F7:ED:96:BE
,I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Incoming socket thread, for peer with ID 58:2A:F7:ED:96:BE, created successfully
D/io.jxcore.node.ConnectionHelper( 2879): onConnected: The total number of connections is now 2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Exiting thread (ID: 279)
,D/io.jxcore.node.IncomingSocketThread( 2879): Entering thread (ID: 280)
,I/io.jxcore.node.IncomingSocketThread( 2879): Local host address: localhost/127.0.0.1, port: 46178
D/io.jxcore.node.IncomingSocketThread( 2879): Setting local streams and starting stream copying threads...
,I/jxcore-log( 2879): 2015-12-08T16:14:52.405Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2879): 
,I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 2879): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 2879): Exiting thread (ID: 280)
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 281, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 282, name: Receiver)
,W/bt-btif ( 2950): new conn_srvc id:26, app_id:1
W/bt-btif ( 2950): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2950): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onSocketConnected: Authenticating next: [E0:DB:10:14:E2:C0 E0:DB:10:14:E2:C0 E0:DB:10:14:E2:C0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 273)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): onBytesWritten: 77 bytes successfully written (thread ID: 283)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Outgoing connection initialized (*handshake* thread ID: 283)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Exiting thread (thread ID: 273)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Entering thread (ID: 283)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): onBytesRead: Read 82 bytes successfully (thread ID: 283)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Handshake succeeded with [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6099 E0:DB:10:14:E2:C0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onAuthenticated: Fully connected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6099 E0:DB:10:14:E2:C0]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6099 E0:DB:10:14:E2:C0]
,I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Outgoing connection, peer ID: E0:DB:10:14:E2:C0, name: samsung-SM-N910C_PT6099, Bluetooth address: E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Adding peer with ID E0:DB:10:14:E2:C0
,I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Outgoing socket thread, for peer with ID E0:DB:10:14:E2:C0, created successfully
D/io.jxcore.node.ConnectionHelper( 2879): onConnected: The total number of connections is now 3
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Exiting thread (ID: 283)
,I/jxcore-log( 2879): 2015-12-08T16:14:52.764Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2879): 
,D/io.jxcore.node.OutgoingSocketThread( 2879): Entering thread (ID: 284)
,D/io.jxcore.node.OutgoingSocketThread( 2879): Server socket local port: 49084
I/io.jxcore.node.OutgoingSocketThread( 2879): Now accepting connections...
,I/jxcore-log( 2879): 2015-12-08T16:14:52.875Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:53.041Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:53.051Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:53.055Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2879): 
,I/io.jxcore.node.ConnectionHelper( 2879): onListeningForIncomingConnections: Outgoing connection is using port 49084 (peer ID: E0:DB:10:14:E2:C0)
I/jxcore-log( 2879): 2015-12-08T16:14:53.085Z SendDataConnector.js: CLIENT connected to 49084, error: null
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:14:53.085Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2879): 
,I/io.jxcore.node.OutgoingSocketThread( 2879): Incoming data from address: /127.0.0.1, port: 49084
D/io.jxcore.node.OutgoingSocketThread( 2879): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread( 2879): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 2879): Exiting thread (ID: 284)
,I/jxcore-log( 2879): 2015-12-08T16:14:53.117Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2879): 
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 285, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 286, name: Receiver)
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=0
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,D/        ( 2950): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:1088
,I/jxcore-log( 2879): 2015-12-08T16:14:53.632Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:53.634Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:53.681Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:53.685Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:53.757Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:53.785Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:53.792Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:53.833Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:53.857Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:53.982Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:54.019Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:54.054Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:54.066Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:54.078Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:54.093Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:54.147Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:54.160Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:54.194Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 2879): 
,W/bt-btif ( 2950): info:x10
,D/        ( 2950): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2950): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2879): 2015-12-08T16:14:54.249Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:54.345Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:54.359Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:54.433Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:54.442Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:54.455Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:54.491Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:54.522Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:54.573Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:54.591Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:14:54.593Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:54.644Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:54.659Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:54.666Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:54.702Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:54.742Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:54.749Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 2879): 
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=1
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2879): 2015-12-08T16:14:54.836Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:54.848Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:54.913Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:54.945Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:14:54.947Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:55.053Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:55.199Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:55.258Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:55.403Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:55.413Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:55.539Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:55.546Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:55.608Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:55.626Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:14:55.628Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:55.696Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:55.794Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:55.818Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:55.834Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:55.855Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:55.863Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:56.105Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:56.118Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 2879): 
,I/BluetoothBondStateMachine( 2950): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 2950): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2950): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2950): Entering PendingCommandState State
,I/jxcore-log( 2879): 2015-12-08T16:14:56.198Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:56.217Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:56.227Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:56.231Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:56.276Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:56.298Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:56.352Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:56.362Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:56.366Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:56.369Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:56.373Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:56.457Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:56.503Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:56.534Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:56.594Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:56.607Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:56.645Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:56.753Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:56.764Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 2879): 
,I/BluetoothBondStateMachine( 2950): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2950): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2950): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2950): StableState(): Entering Off State
,I/jxcore-log( 2879): 2015-12-08T16:14:56.832Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:14:56.834Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:14:56.835Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:56.904Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:57.002Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:57.061Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:57.069Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:57.076Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:57.078Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:57.142Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 2879): 
,W/bt-btif ( 2950): invalid rfc slot id: 6
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 282, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 2879): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Incoming connection, peer with ID 58:2A:F7:ED:96:BE disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 280
,I/io.jxcore.node.OutgoingSocketThread( 2879): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 282
I/io.jxcore.node.OutgoingSocketThread( 2879): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 281
I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 281, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2879): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Incoming connection, peer with ID 58:2A:F7:ED:96:BE disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 2879): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 281, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 282, name: Receiver)
,I/jxcore-log( 2879): 2015-12-08T16:14:57.202Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:14:57.205Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:57.221Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:57.227Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:57.235Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2879): 
,W/bt-btif ( 2950): new conn_srvc id:26, app_id:255
W/bt-btif ( 2950): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2950): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Incoming connection initialized (thread ID: 287)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Entering thread (ID: 287)
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=0
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=0
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2950): invalid rfc slot id: 4
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 278, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 2879): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Incoming connection, peer with ID B0:C5:59:3F:75:69 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 276
I/io.jxcore.node.OutgoingSocketThread( 2879): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 278
I/io.jxcore.node.OutgoingSocketThread( 2879): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 277
I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing...
,I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 277, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2879): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Incoming connection, peer with ID B0:C5:59:3F:75:69 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local output stream...
,I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 2879): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 277, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 278, name: Receiver)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): onBytesRead: Read 77 bytes successfully (thread ID: 287)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Got valid identity from [F8:95:C7:87:85:54 LGE-LG-D722_PT1403 F8:95:C7:87:85:54]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): onBytesWritten: 77 bytes successfully written (thread ID: 287)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): removeThreadFromList: Removing thread with ID 287
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Handshake thread disposed (thread ID: 287)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onIncomingConnectionConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT1403 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Exiting thread (ID: 287)
,I/jxcore-log( 2879): 2015-12-08T16:14:57.786Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2879): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT1403 F8:95:C7:87:85:54]
I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Incoming connection, peer ID: F8:95:C7:87:85:54, name: LGE-LG-D722_PT1403, Bluetooth address: F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
,I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Adding peer with ID F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Incoming socket thread, for peer with ID F8:95:C7:87:85:54, created successfully
D/io.jxcore.node.ConnectionHelper( 2879): onConnected: The total number of connections is now 2
,D/io.jxcore.node.IncomingSocketThread( 2879): Entering thread (ID: 288)
,I/io.jxcore.node.IncomingSocketThread( 2879): Local host address: localhost/127.0.0.1, port: 46178
D/io.jxcore.node.IncomingSocketThread( 2879): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 2879): 2015-12-08T16:14:57.792Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2879): 
,I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 2879): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 2879): Exiting thread (ID: 288)
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 290, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 289, name: Sender)
,I/jxcore-log( 2879): 2015-12-08T16:14:57.800Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2879): 
,W/bt-rfcomm( 2950): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
W/bt-rfcomm( 2950): RFCOMM_DisconnectInd LCID:0x48
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=1
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2950): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 2950): RFCOMM_DisconnectInd LCID:0x47
,E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2950): onReceive
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@21f3ef17:true
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/jxcore-log( 2879): 2015-12-08T16:14:58.839Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:59.031Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:59.066Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:59.077Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:59.084Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:59.107Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:59.142Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:59.151Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:59.162Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:59.194Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:59.206Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:59.221Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:59.229Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:59.252Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:59.282Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:59.296Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:59.332Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:59.343Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:59.382Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:59.400Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:59.406Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:59.432Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:59.450Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:59.462Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:59.492Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:59.502Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:59.550Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:59.559Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:59.564Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2879): 
,W/bt-btif ( 2950): invalid rfc slot id: 7
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 290, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 2879): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Incoming connection, peer with ID F8:95:C7:87:85:54 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 288
I/io.jxcore.node.IncomingSocketThread( 2879): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 290
I/io.jxcore.node.IncomingSocketThread( 2879): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 289
I/io.jxcore.node.IncomingSocketThread( 2879): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 289, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 2879): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Incoming connection, peer with ID F8:95:C7:87:85:54 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.IncomingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 2879): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 2879): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 290, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 289, name: Sender)
,I/jxcore-log( 2879): 2015-12-08T16:14:59.653Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:59.663Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:14:59.797Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2879): 
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=0
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2950): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
W/bt-rfcomm( 2950): RFCOMM_DisconnectInd LCID:0x4a
,D/btif_config_util( 2950): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2950): onReceive
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: ALE-L21
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2950): onReceive
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: G3s-1
,W/bt-btif ( 2950): dm_pm_timer expires
W/bt-btif ( 2950): dm_pm_timer expires 0
W/bt-btif ( 2950): proc dm_pm_timer expires
,I/jxcore-log( 2879): 2015-12-08T16:15:09.798Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:15:09.799Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:15:09.805Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:15:09.806Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:15:09.807Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2879): 
,E/io.jxcore.node.StreamCopyingThread( 2879): Input stream got -1 on read (thread ID: 285, thread name: Sender)
,E/io.jxcore.node.IncomingSocketThread( 2879): The sending thread failed with error: Input stream got -1 on read
,W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Outgoing connection, peer with ID E0:DB:10:14:E2:C0 disconnected: Input stream got -1 on read
I/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: E0:DB:10:14:E2:C0
,I/io.jxcore.node.IncomingSocketThread( 2879): close
I/io.jxcore.node.IncomingSocketThread( 2879): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 286
I/io.jxcore.node.IncomingSocketThread( 2879): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 285
I/io.jxcore.node.IncomingSocketThread( 2879): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local input stream...
,I/io.jxcore.node.IncomingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 2879): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 2879): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 286, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 2879): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Outgoing connection, peer with ID E0:DB:10:14:E2:C0 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
,D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 286, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 285, name: Sender)
,W/bt-btif ( 2950): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,I/jxcore-log( 2879): 2015-12-08T16:15:14.808Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:15:14.810Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2879): 
,E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2950): onReceive
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524],
,I/BluetoothClassifier( 1341): Bluetooth Device Name: Note4-1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stopServiceDiscovery
,I/wpa_supplicant( 2957): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,D/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:14:E2:C0
E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Failed to disconnect (peer ID: E0:DB:10:14:E2:C0), either no such connection or failed to close the connection
I/jxcore-log( 2879): 2015-12-08T16:15:19.828Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:15:19.829Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:15:19.829Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:15:19.834Z SendDataConnector.js: do connect now
I/jxcore-log( 2879): 
,I/io.jxcore.node.ConnectionHelper( 2879): connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Trying to start connecting to Note4-1 in address E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnecting: Note4-1 E0:DB:10:14:E2:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Started connecting to Note4-1 in address E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 2879): connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 291)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2950): info:x10
,D/        ( 2950): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: Note4-1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2950): process_service_search_attr_rsp
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: Thali Test's G2 36:fc:ef:de:0a:e2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: Thali Test's G2 36:fc:ef:de:0a:e2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 2879): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,D/WifiP2pManager( 2879): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
D/WifiP2pManager( 2879): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2950): new conn_srvc id:26, app_id:1
W/bt-btif ( 2950): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2950): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onSocketConnected: Authenticating next: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6099 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 291)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): onBytesWritten: 77 bytes successfully written (thread ID: 292)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Outgoing connection initialized (*handshake* thread ID: 292)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Exiting thread (thread ID: 291)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Entering thread (ID: 292)
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): onBytesRead: Read 82 bytes successfully (thread ID: 292)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Handshake succeeded with [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6099 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onAuthenticated: Fully connected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6099 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Exiting thread (ID: 292)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6099 E0:DB:10:14:E2:C0]
I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Outgoing connection, peer ID: E0:DB:10:14:E2:C0, name: samsung-SM-N910C_PT6099, Bluetooth address: E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID E0:DB:10:14:E2:C0 already in the list
I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Outgoing socket thread, for peer with ID E0:DB:10:14:E2:C0, created successfully
D/io.jxcore.node.ConnectionHelper( 2879): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 2879): Entering thread (ID: 293)
,D/io.jxcore.node.OutgoingSocketThread( 2879): Server socket local port: 44965
I/io.jxcore.node.OutgoingSocketThread( 2879): Now accepting connections...
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2957): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2957): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Got a list of peers, but since we are currently discovering services (not peers), the new list is ignored
,I/io.jxcore.node.ConnectionHelper( 2879): onListeningForIncomingConnections: Outgoing connection is using port 44965 (peer ID: E0:DB:10:14:E2:C0)
I/jxcore-log( 2879): 2015-12-08T16:15:22.943Z SendDataConnector.js: CLIENT connected to 44965, error: null
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:15:22.944Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2879): 
,I/io.jxcore.node.OutgoingSocketThread( 2879): Incoming data from address: /127.0.0.1, port: 44965
D/io.jxcore.node.OutgoingSocketThread( 2879): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 2879): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 2879): Exiting thread (ID: 293)
,I/jxcore-log( 2879): 2015-12-08T16:15:22.948Z SendDataConnector.js: CLIENT now sending 20000 bytes of data
I/jxcore-log( 2879): 
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 294, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 295, name: Receiver)
,D/btif_config_util( 2950): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2879): 2015-12-08T16:15:25.005Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:15:25.013Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:15:25.014Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:15:25.034Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:15:25.034Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2879): 
,D/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: E0:DB:10:14:E2:C0
I/io.jxcore.node.OutgoingSocketThread( 2879): close
I/io.jxcore.node.OutgoingSocketThread( 2879): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 295
I/io.jxcore.node.OutgoingSocketThread( 2879): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 294
I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 294, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2879): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Outgoing connection, peer with ID E0:DB:10:14:E2:C0 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 2879): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 295, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 2879): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Outgoing connection, peer with ID E0:DB:10:14:E2:C0 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Successfully disconnected (peer ID: E0:DB:10:14:E2:C0
,E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 294, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 295, name: Receiver)
,I/jxcore-log( 2879): 2015-12-08T16:15:25.095Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2879): 
I/jxcore-log( 2879): ---- round done--------
I/jxcore-log( 2879): 
I/jxcore-log( 2879): do fake peer & start
I/jxcore-log( 2879): 
I/jxcore-log( 2879): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:15:25.096Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:15:25.096Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:15:25.096Z SendDataConnector.js: do connect now
I/jxcore-log( 2879): 
I/io.jxcore.node.ConnectionHelper( 2879): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
W/io.jxcore.node.ConnectionHelper( 2879): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Trying to start connecting to null in address 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnecting: null 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Started connecting to null in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 2879): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
I/chromium( 2879): [INFO:CONSOLE(63)] "logCallback Round of send data to peer E0:DB:10:14:E2:C0 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 296)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=1
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2950): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,W/bt-btif ( 2950): info:x10
,D/        ( 2950): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2950): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2950): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2950): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
E/bt-btif ( 2950): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2950): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2950): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2950): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 2950): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 2950): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2950): StableState(): Entering Off State
,W/bt-btif ( 2950): new conn_srvc id:26, app_id:1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onSocketConnected: Authenticating next: [08:EC:A9:50:75:41 08:EC:A9:50:75:41 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 296)
,W/bt-btif ( 2950): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2950): bta_dm_pm_ssr:2, lat:1200
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): onBytesWritten: 77 bytes successfully written (thread ID: 297)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Outgoing connection initialized (*handshake* thread ID: 297)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Exiting thread (thread ID: 296)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Entering thread (ID: 297)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): onBytesRead: Read 83 bytes successfully (thread ID: 297)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Handshake succeeded with [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2283 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onAuthenticated: Fully connected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2283 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Exiting thread (ID: 297)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2283 08:EC:A9:50:75:41]
I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Outgoing connection, peer ID: 08:EC:A9:50:75:41, name: samsung-SM-A300FU_PT2283, Bluetooth address: 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Adding peer with ID 08:EC:A9:50:75:41
,I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Outgoing socket thread, for peer with ID 08:EC:A9:50:75:41, created successfully
D/io.jxcore.node.ConnectionHelper( 2879): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 2879): Entering thread (ID: 298)
,D/io.jxcore.node.OutgoingSocketThread( 2879): Server socket local port: 38790
,I/io.jxcore.node.OutgoingSocketThread( 2879): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 2879): onListeningForIncomingConnections: Outgoing connection is using port 38790 (peer ID: 08:EC:A9:50:75:41)
I/jxcore-log( 2879): 2015-12-08T16:15:28.008Z SendDataConnector.js: CLIENT connected to 38790, error: null
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:15:28.009Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2879): 
,I/io.jxcore.node.OutgoingSocketThread( 2879): Incoming data from address: /127.0.0.1, port: 38790
D/io.jxcore.node.OutgoingSocketThread( 2879): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 2879): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 2879): Exiting thread (ID: 298)
,I/jxcore-log( 2879): 2015-12-08T16:15:28.046Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2879): 
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 300, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 299, name: Sender)
,D/        ( 2950): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 2879): 2015-12-08T16:15:28.851Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:15:28.951Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2879): 
,D/        ( 2950): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13816
,I/jxcore-log( 2879): 2015-12-08T16:15:29.012Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2879): 
,D/        ( 2950): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:6886
,I/jxcore-log( 2879): 2015-12-08T16:15:29.113Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:15:29.223Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:15:29.309Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:15:29.429Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2879): 
,E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2950): onReceive
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: Note4-1
,I/jxcore-log( 2879): 2015-12-08T16:15:29.511Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:15:29.603Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:15:29.603Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:15:29.605Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:15:29.606Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2879): 
D/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:75:41
I/io.jxcore.node.OutgoingSocketThread( 2879): close
I/io.jxcore.node.OutgoingSocketThread( 2879): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 300
I/io.jxcore.node.OutgoingSocketThread( 2879): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 299
I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 299, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2879): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Outgoing connection, peer with ID 08:EC:A9:50:75:41 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 2879): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 300, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 2879): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Outgoing connection, peer with ID 08:EC:A9:50:75:41 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Successfully disconnected (peer ID: 08:EC:A9:50:75:41
,E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 299, name: Sender)
E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 300, name: Receiver)
,I/jxcore-log( 2879): 2015-12-08T16:15:29.613Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 2879): 
I/jxcore-log( 2879): ---- round done--------
I/jxcore-log( 2879): 
I/jxcore-log( 2879): do fake peer & start
I/jxcore-log( 2879): 
I/jxcore-log( 2879): Connect to fake peer: F8:95:C7:87:85:54
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:15:29.613Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:15:29.613Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:15:29.613Z SendDataConnector.js: do connect now
I/jxcore-log( 2879): 
I/io.jxcore.node.ConnectionHelper( 2879): connect: Trying to connect to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): connect: 
,W/bt-btif ( 2950): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Trying to start connecting to G3s-1 in address F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnecting: G3s-1 F8:95:C7:87:85:54
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Started connecting to G3s-1 in address F8:95:C7:87:85:54
,I/io.jxcore.node.ConnectionHelper( 2879): connect: Connection process successfully started (peer ID: F8:95:C7:87:85:54)
I/chromium( 2879): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 08:EC:A9:50:75:41 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect to peer with address F8:95:C7:87:85:54 (thread ID: 301)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2950): info:x10
,D/        ( 2950): remote version info [f8:95:c7:87:85:54]: 7, f, 2205
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: G3s-1
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=0
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2950): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2950): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 2950): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2950): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2950): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2950): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2950): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2950): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2950): StableState(): Entering Off State
,W/bt-btif ( 2950): new conn_srvc id:26, app_id:1
W/bt-btif ( 2950): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2950): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onSocketConnected: Authenticating next: [F8:95:C7:87:85:54 LGE-LG-D722_PT1403 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 301)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): onBytesWritten: 77 bytes successfully written (thread ID: 302)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Outgoing connection initialized (*handshake* thread ID: 302)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Exiting thread (thread ID: 301)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Entering thread (ID: 302)
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): onBytesRead: Read 77 bytes successfully (thread ID: 302)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Handshake succeeded with [F8:95:C7:87:85:54 LGE-LG-D722_PT1403 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onAuthenticated: Fully connected: [F8:95:C7:87:85:54 LGE-LG-D722_PT1403 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Exiting thread (ID: 302)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT1403 F8:95:C7:87:85:54]
I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Outgoing connection, peer ID: F8:95:C7:87:85:54, name: LGE-LG-D722_PT1403, Bluetooth address: F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:85:54 already in the list
,I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Outgoing socket thread, for peer with ID F8:95:C7:87:85:54, created successfully
D/io.jxcore.node.ConnectionHelper( 2879): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 2879): Entering thread (ID: 303)
D/io.jxcore.node.OutgoingSocketThread( 2879): Server socket local port: 34796
I/io.jxcore.node.OutgoingSocketThread( 2879): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 2879): onListeningForIncomingConnections: Outgoing connection is using port 34796 (peer ID: F8:95:C7:87:85:54)
I/jxcore-log( 2879): 2015-12-08T16:15:32.125Z SendDataConnector.js: CLIENT connected to 34796, error: null
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:15:32.126Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2879): 
,I/io.jxcore.node.OutgoingSocketThread( 2879): Incoming data from address: /127.0.0.1, port: 34796
D/io.jxcore.node.OutgoingSocketThread( 2879): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 2879): startStreamCopyingThreads: OK
,D/io.jxcore.node.OutgoingSocketThread( 2879): Exiting thread (ID: 303)
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 304, name: Sender)
,I/jxcore-log( 2879): 2015-12-08T16:15:32.166Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2879): 
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 305, name: Receiver)
,I/jxcore-log( 2879): 2015-12-08T16:15:32.660Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:15:32.711Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:15:32.743Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:15:32.782Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:15:32.823Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2879): 
,E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2950): onReceive
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/jxcore-log( 2879): 2015-12-08T16:15:32.870Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2879): 
,I/BluetoothClassifier( 1341): Bluetooth Device Name: A3-1
,I/jxcore-log( 2879): 2015-12-08T16:15:32.939Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:15:32.976Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:15:32.980Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:15:33.028Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:15:33.028Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:15:33.031Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:15:33.031Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2879): 
D/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:85:54
I/io.jxcore.node.OutgoingSocketThread( 2879): close
I/io.jxcore.node.OutgoingSocketThread( 2879): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 305
I/io.jxcore.node.OutgoingSocketThread( 2879): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 304
I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 304, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2879): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Outgoing connection, peer with ID F8:95:C7:87:85:54 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 2879): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 305, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 2879): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Outgoing connection, peer with ID F8:95:C7:87:85:54 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:95:C7:87:85:54
,E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 304, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 305, name: Receiver)
,I/jxcore-log( 2879): 2015-12-08T16:15:33.037Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): ---- round done--------
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): do fake peer & start
I/jxcore-log( 2879): 
I/jxcore-log( 2879): Connect to fake peer: 80:01:84:8A:B3:68
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:15:33.039Z SendDataConnector.js: Start called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:15:33.039Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:15:33.039Z SendDataConnector.js: do connect now
I/jxcore-log( 2879): 
,I/io.jxcore.node.ConnectionHelper( 2879): connect: Trying to connect to peer with ID 80:01:84:8A:B3:68
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 80:01:84:8A:B3:68
W/io.jxcore.node.ConnectionHelper( 2879): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Trying to start connecting to null in address 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnecting: null 80:01:84:8A:B3:68
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Started connecting to null in address 80:01:84:8A:B3:68
I/io.jxcore.node.ConnectionHelper( 2879): connect: Connection process successfully started (peer ID: 80:01:84:8A:B3:68)
,I/chromium( 2879): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F8:95:C7:87:85:54 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 2950): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect to peer with address 80:01:84:8A:B3:68 (thread ID: 306)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 2950): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=0
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2950): onReceive
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: G3s-1
,W/bt-btif ( 2950): info:x10
,D/        ( 2950): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 2950): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
,D/btif_config_util( 2950): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x44
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:12, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 12
,E/BluetoothRemoteDevices( 2950): aclStateChangeCallback: Device is NULL
,W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): Connection timeout
,W/bt-btif ( 2950): info:x10
,D/        ( 2950): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 2950): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2950): process_service_search_attr_rsp
,D/btif_config_util( 2950): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2950): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 1
E/bt-btif ( 2950): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2950): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2950): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2950): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 0
,D/BluetoothAdapterProperties( 2950): Failed to remove device: 80:01:84:8A:B3:68
,I/BluetoothBondStateMachine( 2950): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2950): StableState(): Entering Off State
,W/bt-btif ( 2950): new conn_srvc id:26, app_id:1
W/bt-btif ( 2950): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2950): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onSocketConnected: Authenticating next: [80:01:84:8A:B3:68 80:01:84:8A:B3:68 80:01:84:8A:B3:68]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stopServiceDiscovery
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnectionFailed: Cancelled: Connection timeout [80:01:84:8A:B3:68 80:01:84:8A:B3:68 80:01:84:8A:B3:68]
,I/wpa_supplicant( 2957): P2P-FIND-STOPPED 
,W/bt-btif ( 2950): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Socket connection succeeded using system decided port, total number of attempts: 1 (thread ID: 306)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Exiting thread (thread ID: 306)
,I/jxcore-log( 2879): 2015-12-08T16:16:15.448Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 80:01:84:8A:B3:68 failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:16:15.449Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 80:01:84:8A:B3:68 failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:16:15.449Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2879): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,D/btif_config_util( 2950): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2950): onReceive
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 2879): 2015-12-08T16:16:20.449Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:16:20.452Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2879): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): start: Starting peer discovery...
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
,D/WifiP2pManager( 2879): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: Android_63cc 82:01:84:6b:e8:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 2879): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
D/WifiP2pManager( 2879): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,D/WifiP2pManager( 2879): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT26"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT26 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT26"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT26"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT26"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT26, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: S5mini-1, Wi-Fi Direct address: 02:f4:6f:30:e0:6d
,I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Adding peer with ID 00:F4:6F:30:E0:6C
,W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2283","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2283 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2283","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:75:41, peer name: samsung-SM-A300FU_PT2283, peer ID: 08:EC:A9:50:75:41, Wi-Fi Direct device name: A3-1, Wi-Fi Direct address: 0a:ec:a9:50:75:42
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:75:41 already in the list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2283","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2283","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/wpa_supplicant( 2957): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2957): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT333","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT333 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT333","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT333","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT333","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:76:27, peer name: samsung-SM-A300FU_PT333, peer ID: 08:EC:A9:50:76:27, Wi-Fi Direct device name: Thali Test (Galaxy A3), Wi-Fi Direct address: 0a:ec:a9:50:76:28
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Adding peer with ID 08:EC:A9:50:76:27
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT26"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT26 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT26"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT26"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT26"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT26, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: S5mini-1, Wi-Fi Direct address: 02:f4:6f:30:e0:6d
,I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2283","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2283 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2283","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2283","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2283","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:75:41, peer name: samsung-SM-A300FU_PT2283, peer ID: 08:EC:A9:50:75:41, Wi-Fi Direct device name: A3-1, Wi-Fi Direct address: 0a:ec:a9:50:75:42
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:75:41 already in the list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1989"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT1989 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1989"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1989"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1989"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: 80:01:84:8A:B3:68, peer name: HTC-HTC Desire 820_PT1989, peer ID: 80:01:84:8A:B3:68, Wi-Fi Direct device name: Android_63cc, Wi-Fi Direct address: 82:01:84:6b:e8:5d
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Adding peer with ID 80:01:84:8A:B3:68
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
,D/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Trying to close connection to peer with ID 80:01:84:8A:B3:68
E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 80:01:84:8A:B3:68
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Failed to disconnect (peer ID: 80:01:84:8A:B3:68), either no such connection or failed to close the connection
I/jxcore-log( 2879): 2015-12-08T16:16:25.458Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:16:25.458Z SendDataConnector.js: Connect (retry count 1) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:16:25.459Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:16:25.460Z SendDataConnector.js: do connect now
I/jxcore-log( 2879): 
,I/io.jxcore.node.ConnectionHelper( 2879): connect: Trying to connect to peer with ID 80:01:84:8A:B3:68
,D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): connect: Android_63cc
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Trying to start connecting to HTC Desire 820 in address 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnecting: HTC Desire 820 80:01:84:8A:B3:68
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Started connecting to HTC Desire 820 in address 80:01:84:8A:B3:68
I/io.jxcore.node.ConnectionHelper( 2879): connect: Connection process successfully started (peer ID: 80:01:84:8A:B3:68)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect to peer with address 80:01:84:8A:B3:68 (thread ID: 307)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x47
,E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:14, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2950): invalid rfc slot id: 14
,W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT1972"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [38:94:96:B5:06:DC samsung-SM-G800H_PT1972 38:94:96:B5:06:DC]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 5 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT1972"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT1972"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT1972"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: 38:94:96:B5:06:DC, peer name: samsung-SM-G800H_PT1972, peer ID: 38:94:96:B5:06:DC, Wi-Fi Direct device name: , Wi-Fi Direct address: 3a:94:96:b5:06:dd
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Adding peer with ID 38:94:96:B5:06:DC
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 5 peer(s), but doing nothing with that list
,W/bt-btif ( 2950): info:x10
,D/        ( 2950): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: HTC Desire 820
,W/bt-sdp  ( 2950): process_service_search_attr_rsp
,W/bt-btif ( 2950): new conn_srvc id:26, app_id:1
W/bt-btif ( 2950): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2950): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onSocketConnected: Authenticating next: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT1989 80:01:84:8A:B3:68]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Socket connection succeeded using system decided port, total number of attempts: 1 (thread ID: 307)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): onBytesWritten: 77 bytes successfully written (thread ID: 308)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Outgoing connection initialized (*handshake* thread ID: 308)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Exiting thread (thread ID: 307)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Entering thread (ID: 308)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): onBytesRead: Read 84 bytes successfully (thread ID: 308)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Handshake succeeded with [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT1989 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onAuthenticated: Fully connected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT1989 80:01:84:8A:B3:68]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Exiting thread (ID: 308)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT1989 80:01:84:8A:B3:68]
,I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Outgoing connection, peer ID: 80:01:84:8A:B3:68, name: HTC-HTC Desire 820_PT1989, Bluetooth address: 80:01:84:8A:B3:68
,D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 80:01:84:8A:B3:68
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID 80:01:84:8A:B3:68 already in the list
,I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Outgoing socket thread, for peer with ID 80:01:84:8A:B3:68, created successfully
D/io.jxcore.node.ConnectionHelper( 2879): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 2879): Entering thread (ID: 309)
,D/io.jxcore.node.OutgoingSocketThread( 2879): Server socket local port: 53433
I/io.jxcore.node.OutgoingSocketThread( 2879): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 2879): onListeningForIncomingConnections: Outgoing connection is using port 53433 (peer ID: 80:01:84:8A:B3:68)
I/jxcore-log( 2879): 2015-12-08T16:16:40.088Z SendDataConnector.js: CLIENT connected to 53433, error: null
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:16:40.089Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2879): 
,I/io.jxcore.node.OutgoingSocketThread( 2879): Incoming data from address: /127.0.0.1, port: 53433
D/io.jxcore.node.OutgoingSocketThread( 2879): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 2879): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 2879): Exiting thread (ID: 309)
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 311, name: Receiver)
,I/jxcore-log( 2879): 2015-12-08T16:16:40.121Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2879): 
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 310, name: Sender)
,I/jxcore-log( 2879): 2015-12-08T16:16:40.639Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:16:40.716Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:16:40.870Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:16:40.938Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:16:41.032Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:16:41.097Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:16:41.172Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:16:41.226Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:16:41.322Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:16:41.469Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:16:41.470Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:16:41.486Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:16:41.487Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2879): 
,D/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Trying to close connection to peer with ID 80:01:84:8A:B3:68
I/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 80:01:84:8A:B3:68
I/io.jxcore.node.OutgoingSocketThread( 2879): close
I/io.jxcore.node.OutgoingSocketThread( 2879): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 311
I/io.jxcore.node.OutgoingSocketThread( 2879): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 310
I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 310, thread name: Sender): Socket closed
,E/io.jxcore.node.OutgoingSocketThread( 2879): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Outgoing connection, peer with ID 80:01:84:8A:B3:68 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 2879): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 311, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 2879): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Outgoing connection, peer with ID 80:01:84:8A:B3:68 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Successfully disconnected (peer ID: 80:01:84:8A:B3:68
,E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 80:01:84:8A:B3:68
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 80:01:84:8A:B3:68
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 311, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 310, name: Sender)
,I/jxcore-log( 2879): 2015-12-08T16:16:41.537Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 2879): 
,W/bt-btif ( 2950): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,I/jxcore-log( 2879): ---- round done--------
I/jxcore-log( 2879): 
I/jxcore-log( 2879): do fake peer & start
I/jxcore-log( 2879): 
I/jxcore-log( 2879): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:16:41.546Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:16:41.546Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:16:41.546Z SendDataConnector.js: do connect now
I/jxcore-log( 2879): 
,I/io.jxcore.node.ConnectionHelper( 2879): connect: Trying to connect to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
W/io.jxcore.node.ConnectionHelper( 2879): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Trying to start connecting to null in address 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnecting: null 34:FC:EF:11:B1:66
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Started connecting to null in address 34:FC:EF:11:B1:66
I/io.jxcore.node.ConnectionHelper( 2879): connect: Connection process successfully started (peer ID: 34:FC:EF:11:B1:66)
I/chromium( 2879): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 80:01:84:8A:B3:68 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect to peer with address 34:FC:EF:11:B1:66 (thread ID: 312)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 2950): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=1
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2950): onReceive
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: HTC Desire 820
,W/bt-btif ( 2950): info:x10
,D/        ( 2950): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 2950): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e5196c rs_disc_pending=0
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2950): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-sdp  ( 2950): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2950): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 1
E/bt-btif ( 2950): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2950): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2950): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2950): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 0
,D/BluetoothAdapterProperties( 2950): Failed to remove device: 34:FC:EF:11:B1:66
,I/BluetoothBondStateMachine( 2950): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2950): StableState(): Entering Off State
,D/btif_config_util( 2950): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2950): new conn_srvc id:26, app_id:1
W/bt-btif ( 2950): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2950): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onSocketConnected: Authenticating next: [34:FC:EF:11:B1:66 34:FC:EF:11:B1:66 34:FC:EF:11:B1:66]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 312)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): onBytesWritten: 77 bytes successfully written (thread ID: 313)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Outgoing connection initialized (*handshake* thread ID: 313)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Exiting thread (thread ID: 312)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Entering thread (ID: 313)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): onBytesRead: Read 77 bytes successfully (thread ID: 313)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Handshake succeeded with [34:FC:EF:11:B1:66 LGE-Nexus 5_PT2378 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onAuthenticated: Fully connected: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT2378 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Exiting thread (ID: 313)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnected: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT2378 34:FC:EF:11:B1:66]
I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Outgoing connection, peer ID: 34:FC:EF:11:B1:66, name: LGE-Nexus 5_PT2378, Bluetooth address: 34:FC:EF:11:B1:66
,D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Adding peer with ID 34:FC:EF:11:B1:66
,I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Outgoing socket thread, for peer with ID 34:FC:EF:11:B1:66, created successfully
D/io.jxcore.node.ConnectionHelper( 2879): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 2879): Entering thread (ID: 314)
,D/io.jxcore.node.OutgoingSocketThread( 2879): Server socket local port: 43086
I/io.jxcore.node.OutgoingSocketThread( 2879): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 2879): onListeningForIncomingConnections: Outgoing connection is using port 43086 (peer ID: 34:FC:EF:11:B1:66)
I/jxcore-log( 2879): 2015-12-08T16:16:55.997Z SendDataConnector.js: CLIENT connected to 43086, error: null
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:16:55.998Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2879): 
,I/io.jxcore.node.OutgoingSocketThread( 2879): Incoming data from address: /127.0.0.1, port: 43086
D/io.jxcore.node.OutgoingSocketThread( 2879): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 2879): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 2879): Exiting thread (ID: 314)
,I/jxcore-log( 2879): 2015-12-08T16:16:56.027Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2879): 
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 315, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 316, name: Receiver)
,D/        ( 2950): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706
,I/jxcore-log( 2879): 2015-12-08T16:16:56.698Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2879): 
,D/        ( 2950): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:16786
,I/jxcore-log( 2879): 2015-12-08T16:16:56.757Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:16:56.764Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2879): 
,D/        ( 2950): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:9856
,I/jxcore-log( 2879): 2015-12-08T16:16:56.877Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2879): 
,D/        ( 2950): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 2879): 2015-12-08T16:16:56.926Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:16:56.980Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:16:57.055Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:16:57.132Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:16:57.177Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:16:57.385Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:16:57.386Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:16:57.401Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:16:57.402Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2879): 
D/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:B1:66
I/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 34:FC:EF:11:B1:66
I/io.jxcore.node.OutgoingSocketThread( 2879): close
I/io.jxcore.node.OutgoingSocketThread( 2879): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 316
I/io.jxcore.node.OutgoingSocketThread( 2879): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 315
I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 315, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2879): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Outgoing connection, peer with ID 34:FC:EF:11:B1:66 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local output stream...
,I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 2879): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 316, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 2879): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Outgoing connection, peer with ID 34:FC:EF:11:B1:66 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left,
I/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Successfully disconnected (peer ID: 34:FC:EF:11:B1:66
E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 315, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 316, name: Receiver)
,I/jxcore-log( 2879): 2015-12-08T16:16:57.438Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2879): 
I/jxcore-log( 2879): ---- round done--------
I/jxcore-log( 2879): 
I/jxcore-log( 2879): do fake peer & start
I/jxcore-log( 2879): 
I/jxcore-log( 2879): Connect to fake peer: 90:E7:C4:F6:69:77
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:16:57.439Z SendDataConnector.js: Start called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:16:57.439Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:16:57.439Z SendDataConnector.js: do connect now
I/jxcore-log( 2879): 
,W/bt-btif ( 2950): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
I/io.jxcore.node.ConnectionHelper( 2879): connect: Trying to connect to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
W/io.jxcore.node.ConnectionHelper( 2879): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Trying to start connecting to null in address 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnecting: null 90:E7:C4:F6:69:77
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Started connecting to null in address 90:E7:C4:F6:69:77
I/io.jxcore.node.ConnectionHelper( 2879): connect: Connection process successfully started (peer ID: 90:E7:C4:F6:69:77)
,I/chromium( 2879): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 34:FC:EF:11:B1:66 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect to peer with address 90:E7:C4:F6:69:77 (thread ID: 317)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e5196c rs_disc_pending=1
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e5196c rs_disc_pending=0
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2950): onReceive
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: Nexus 5
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:17, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 17
,W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
,E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:18, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 18
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 317)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect again in 300 ms... (thread ID: 317)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): Connection timeout
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:19, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2950): invalid rfc slot id: 19
,W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:20, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 20
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 317)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect again in 300 ms... (thread ID: 317)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnectionFailed: Cancelled: Connection timeout [90:E7:C4:F6:69:77 90:E7:C4:F6:69:77 90:E7:C4:F6:69:77]
,I/jxcore-log( 2879): 2015-12-08T16:17:18.516Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 90:E7:C4:F6:69:77 failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:17:18.517Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 90:E7:C4:F6:69:77 failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:17:18.517Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2879): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Exiting thread (thread ID: 317)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stopServiceDiscovery
,I/wpa_supplicant( 2957): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1108","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1108","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
,I/wpa_supplicant( 2957): P2P-FIND-STOPPED 
I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): restart: Restarting...
,W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): startServiceDiscovery: Invalid state, try calling restart()
,I/jxcore-log( 2879): 2015-12-08T16:17:23.520Z SendDataConnector.js: re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:17:23.522Z SendDataConnector.js: ReStart called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 2879): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): start: Starting peer discovery...
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/WifiP2pManager( 2879): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
,D/WifiP2pManager( 2879): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: P2P: Reject scan trigger since one is already pending
,D/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Trying to close connection to peer with ID 90:E7:C4:F6:69:77
E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Failed to disconnect (peer ID: 90:E7:C4:F6:69:77), either no such connection or failed to close the connection
I/jxcore-log( 2879): 2015-12-08T16:17:28.525Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:17:28.526Z SendDataConnector.js: Connect (retry count 1) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:17:28.527Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:17:28.527Z SendDataConnector.js: do connect now
I/jxcore-log( 2879): 
I/io.jxcore.node.ConnectionHelper( 2879): connect: Trying to connect to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
W/io.jxcore.node.ConnectionHelper( 2879): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Trying to start connecting to null in address 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnecting: null 90:E7:C4:F6:69:77
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Started connecting to null in address 90:E7:C4:F6:69:77
I/io.jxcore.node.ConnectionHelper( 2879): connect: Connection process successfully started (peer ID: 90:E7:C4:F6:69:77)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect to peer with address 90:E7:C4:F6:69:77 (thread ID: 318)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2957): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x44
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:21, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 21
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:22, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 22
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 318)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect again in 300 ms... (thread ID: 318)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): Connection timeout
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:23, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 23
,W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:24, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 24
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 318)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect again in 300 ms... (thread ID: 318)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnectionFailed: Cancelled: Connection timeout [90:E7:C4:F6:69:77 90:E7:C4:F6:69:77 90:E7:C4:F6:69:77]
,I/jxcore-log( 2879): 2015-12-08T16:17:49.437Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 90:E7:C4:F6:69:77 failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:17:49.438Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 90:E7:C4:F6:69:77 failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:17:49.438Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2879): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Exiting thread (thread ID: 318)
,I/jxcore-log( 2879): 2015-12-08T16:17:54.440Z SendDataConnector.js: re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:17:54.442Z SendDataConnector.js: ReStart called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 2879): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stopServiceDiscovery
,I/wpa_supplicant( 2957): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,D/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Trying to close connection to peer with ID 90:E7:C4:F6:69:77
E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Failed to disconnect (peer ID: 90:E7:C4:F6:69:77), either no such connection or failed to close the connection
I/jxcore-log( 2879): 2015-12-08T16:17:59.446Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:17:59.447Z SendDataConnector.js: Connect (retry count 2) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:17:59.447Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:17:59.448Z SendDataConnector.js: do connect now
I/jxcore-log( 2879): 
I/io.jxcore.node.ConnectionHelper( 2879): connect: Trying to connect to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
W/io.jxcore.node.ConnectionHelper( 2879): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Trying to start connecting to null in address 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnecting: null 90:E7:C4:F6:69:77
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Started connecting to null in address 90:E7:C4:F6:69:77
I/io.jxcore.node.ConnectionHelper( 2879): connect: Connection process successfully started (peer ID: 90:E7:C4:F6:69:77)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect to peer with address 90:E7:C4:F6:69:77 (thread ID: 319)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2950): info:x10
,D/        ( 2950): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 2950): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e51cfc rs_disc_pending=0
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): start: Starting peer discovery...
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/BluetoothBondStateMachine( 2950): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
E/bt-btif ( 2950): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2950): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2950): Entering PendingCommandState State
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2950): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 2950): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 2950): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2950): StableState(): Entering Off State
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:25, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 25
,W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/WifiP2pManager( 2879): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/WifiP2pManager( 2879): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e51cfc rs_disc_pending=1
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2950): new conn_srvc id:26, app_id:255
W/bt-btif ( 2950): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2950): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Incoming connection initialized (thread ID: 320)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Entering thread (ID: 320)
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e51cfc rs_disc_pending=0
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): onBytesRead: Read 81 bytes successfully (thread ID: 320)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Got valid identity from [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT291 7C:F9:0E:34:8A:A0]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): onBytesWritten: 77 bytes successfully written (thread ID: 320)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): removeThreadFromList: Removing thread with ID 320
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Handshake thread disposed (thread ID: 320)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onIncomingConnectionConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT291 7C:F9:0E:34:8A:A0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Exiting thread (ID: 320)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT291 7C:F9:0E:34:8A:A0]
,I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Incoming connection, peer ID: 7C:F9:0E:34:8A:A0, name: samsung-SM-G900F_PT291, Bluetooth address: 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
,I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Adding peer with ID 7C:F9:0E:34:8A:A0
,I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Incoming socket thread, for peer with ID 7C:F9:0E:34:8A:A0, created successfully
D/io.jxcore.node.ConnectionHelper( 2879): onConnected: The total number of connections is now 1
,I/wpa_supplicant( 2957): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 2957): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,D/io.jxcore.node.IncomingSocketThread( 2879): Entering thread (ID: 321)
,I/jxcore-log( 2879): 2015-12-08T16:18:05.896Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2879): 
,I/io.jxcore.node.IncomingSocketThread( 2879): Local host address: localhost/127.0.0.1, port: 46178
,D/io.jxcore.node.IncomingSocketThread( 2879): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 2879): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 2879): Exiting thread (ID: 321)
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 322, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 323, name: Receiver)
,I/jxcore-log( 2879): 2015-12-08T16:18:06.884Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:06.956Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:07.032Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2879): 
,D/btif_config_util( 2950): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2879): 2015-12-08T16:18:07.367Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:07.820Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:07.890Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:08.211Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:08.284Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:08.549Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:08.757Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:08.937Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:09.151Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:09.513Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:09.647Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:09.800Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:09.813Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:09.842Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:09.858Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:09.892Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:09.948Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 2879): 
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:26, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 26
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 319)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect again in 300 ms... (thread ID: 319)
,I/jxcore-log( 2879): 2015-12-08T16:18:10.090Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:10.148Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:10.185Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:10.191Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:10.215Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:10.225Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:10.263Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:10.271Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:10.283Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:10.313Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:10.325Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:10.333Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:10.363Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 2879): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 2879): 2015-12-08T16:18:10.394Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:10.412Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2879): 
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e51cfc rs_disc_pending=1
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e51cfc rs_disc_pending=0
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2950): invalid rfc slot id: 8
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 323, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 2879): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Incoming connection, peer with ID 7C:F9:0E:34:8A:A0 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 321
I/io.jxcore.node.IncomingSocketThread( 2879): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 323
I/io.jxcore.node.IncomingSocketThread( 2879): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 322
,I/io.jxcore.node.IncomingSocketThread( 2879): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 322, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 2879): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Incoming connection, peer with ID 7C:F9:0E:34:8A:A0 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.IncomingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 2879): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.IncomingSocketThread( 2879): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 322, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 323, name: Receiver)
,I/jxcore-log( 2879): 2015-12-08T16:18:11.052Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2879): 
,W/bt-rfcomm( 2950): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
W/bt-rfcomm( 2950): RFCOMM_DisconnectInd LCID:0x4a
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): Connection timeout
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2950): onReceive
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: S5-1
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:28, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 28
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:29, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 29
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 319)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect again in 300 ms... (thread ID: 319)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnectionFailed: Cancelled: Connection timeout [90:E7:C4:F6:69:77 90:E7:C4:F6:69:77 90:E7:C4:F6:69:77]
,I/jxcore-log( 2879): 2015-12-08T16:18:20.881Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 90:E7:C4:F6:69:77 failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:18:20.882Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 90:E7:C4:F6:69:77 failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:18:20.882Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2879): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Exiting thread (thread ID: 319)
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT9640","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9640 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT9640","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: E0:DB:10:1F:C9:5E, peer name: samsung-SM-N9005_PT9640, peer ID: E0:DB:10:1F:C9:5E, Wi-Fi Direct device name: , Wi-Fi Direct address: ea:50:8b:de:28:a3
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Adding peer with ID E0:DB:10:1F:C9:5E
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/jxcore-log( 2879): 2015-12-08T16:18:25.883Z SendDataConnector.js: re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:18:25.884Z SendDataConnector.js: ReStart called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 2879): 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT731","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT731 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT731","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: 44:80:EB:7B:5A:05, peer name: motorola-XT1072_PT731, peer ID: 44:80:EB:7B:5A:05, Wi-Fi Direct device name: , Wi-Fi Direct address: 44:80:eb:7b:5a:07
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Adding peer with ID 44:80:EB:7B:5A:05
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Trying to close connection to peer with ID 90:E7:C4:F6:69:77
E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Failed to disconnect (peer ID: 90:E7:C4:F6:69:77), either no such connection or failed to close the connection
I/jxcore-log( 2879): 2015-12-08T16:18:30.889Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:30.894Z SendDataConnector.js: Connect (retry count 3) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:30.895Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:30.897Z SendDataConnector.js: do connect now
I/jxcore-log( 2879): 
,I/io.jxcore.node.ConnectionHelper( 2879): connect: Trying to connect to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
W/io.jxcore.node.ConnectionHelper( 2879): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Trying to start connecting to null in address 90:E7:C4:F6:69:77
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnecting: null 90:E7:C4:F6:69:77
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Started connecting to null in address 90:E7:C4:F6:69:77
I/io.jxcore.node.ConnectionHelper( 2879): connect: Connection process successfully started (peer ID: 90:E7:C4:F6:69:77)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect to peer with address 90:E7:C4:F6:69:77 (thread ID: 324)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:30, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 30
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:31, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 31
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 324)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect again in 300 ms... (thread ID: 324)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): Connection timeout
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:32, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 32
,W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:33, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 33
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 324)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect again in 300 ms... (thread ID: 324)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): cancel: Connection timeout
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnectionFailed: Cancelled: Connection timeout [90:E7:C4:F6:69:77 90:E7:C4:F6:69:77 90:E7:C4:F6:69:77]
I/jxcore-log( 2879): 2015-12-08T16:18:51.836Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 90:E7:C4:F6:69:77 failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:18:51.837Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 90:E7:C4:F6:69:77 failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:18:51.837Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2879): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Exiting thread (thread ID: 324)
,W/bt-btif ( 2950): info:x10
,D/        ( 2950): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2950): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2950): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
E/bt-btif ( 2950): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2950): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2950): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2950): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
,D/BluetoothAdapterProperties( 2950): Failed to remove device: 58:3F:54:73:64:C0
,I/BluetoothBondStateMachine( 2950): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2950): StableState(): Entering Off State
,W/bt-btif ( 2950): new conn_srvc id:26, app_id:255
W/bt-btif ( 2950): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2950): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Incoming connection initialized (thread ID: 325)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Entering thread (ID: 325)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): onBytesRead: Read 75 bytes successfully (thread ID: 325)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Got valid identity from [58:3F:54:73:64:C0 LGE-LG-D855_PT71 58:3F:54:73:64:C0]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): onBytesWritten: 77 bytes successfully written (thread ID: 325)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): removeThreadFromList: Removing thread with ID 325
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Handshake thread disposed (thread ID: 325)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onIncomingConnectionConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT71 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Exiting thread (ID: 325)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT71 58:3F:54:73:64:C0]
I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Incoming connection, peer ID: 58:3F:54:73:64:C0, name: LGE-LG-D855_PT71, Bluetooth address: 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Adding peer with ID 58:3F:54:73:64:C0
,I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Incoming socket thread, for peer with ID 58:3F:54:73:64:C0, created successfully
D/io.jxcore.node.ConnectionHelper( 2879): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 2879): Entering thread (ID: 326)
,I/jxcore-log( 2879): 2015-12-08T16:18:55.798Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2879): 
,I/io.jxcore.node.IncomingSocketThread( 2879): Local host address: localhost/127.0.0.1, port: 46178
D/io.jxcore.node.IncomingSocketThread( 2879): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 2879): startStreamCopyingThreads: OK
,D/io.jxcore.node.IncomingSocketThread( 2879): Exiting thread (ID: 326)
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 328, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 327, name: Sender)
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2879): 2015-12-08T16:18:56.790Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:56.826Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:56.838Z SendDataConnector.js: re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:18:56.839Z SendDataConnector.js: ReStart called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:56.876Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:56.885Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:57.006Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:57.033Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:57.042Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:57.133Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:57.156Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:57.175Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:57.191Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:57.286Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:57.387Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:57.479Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:57.562Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:57.647Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:57.663Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:57.695Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:57.751Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:57.764Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:57.777Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:57.862Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:57.876Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:57.884Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:57.892Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 2879): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT9428","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9428 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT9428","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: 7C:F9:0E:51:18:22, peer name: samsung-SM-A500FU_PT9428, peer ID: 7C:F9:0E:51:18:22, Wi-Fi Direct device name: , Wi-Fi Direct address: 7e:f9:0e:51:18:23
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Adding peer with ID 7C:F9:0E:51:18:22
,W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/jxcore-log( 2879): 2015-12-08T16:18:58.049Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:58.165Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:58.244Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 2879): 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2879): 2015-12-08T16:18:58.264Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:58.339Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:58.366Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:58.382Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:58.441Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:58.479Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:58.607Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 2879): 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2879): 2015-12-08T16:18:58.936Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:58.945Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:58.970Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:58.976Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:58.983Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:58.994Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:59.001Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 2879): 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2879): 2015-12-08T16:18:59.082Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:59.098Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:59.100Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:18:59.101Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2879): 
,W/bt-btif ( 2950): invalid rfc slot id: 27
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 328, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 2879): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Incoming connection, peer with ID 58:3F:54:73:64:C0 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 326
I/io.jxcore.node.IncomingSocketThread( 2879): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 328
I/io.jxcore.node.IncomingSocketThread( 2879): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 327
I/io.jxcore.node.IncomingSocketThread( 2879): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local input stream...
I/io.jxcore.node.IncomingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 2879): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 2879): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 328, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 327, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 2879): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Incoming connection, peer with ID 58:3F:54:73:64:C0 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 327, name: Sender)
,I/jxcore-log( 2879): 2015-12-08T16:18:59.190Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2879): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7084"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:9D:93:0B LGE-LG-D802_PT7084 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7084"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: 34:FC:EF:9D:93:0B, peer name: LGE-LG-D802_PT7084, peer ID: 34:FC:EF:9D:93:0B, Wi-Fi Direct device name: Thali Test's G2, Wi-Fi Direct address: 36:fc:ef:de:0a:e2
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Adding peer with ID 34:FC:EF:9D:93:0B
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 2950): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-rfcomm( 2950): rfc_find_lcid_mcb LCID reused LCID:0x40 current:0x0
W/bt-rfcomm( 2950): RFCOMM_DisconnectInd LCID:0x40
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Trying to close connection to peer with ID 90:E7:C4:F6:69:77
E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Failed to disconnect (peer ID: 90:E7:C4:F6:69:77), either no such connection or failed to close the connection
I/jxcore-log( 2879): 2015-12-08T16:19:01.843Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:19:01.844Z SendDataConnector.js: Connect (retry count 4) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:19:01.845Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:19:01.846Z SendDataConnector.js: do connect now
I/jxcore-log( 2879): 
I/io.jxcore.node.ConnectionHelper( 2879): connect: Trying to connect to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
W/io.jxcore.node.ConnectionHelper( 2879): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Trying to start connecting to null in address 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnecting: null 90:E7:C4:F6:69:77
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Started connecting to null in address 90:E7:C4:F6:69:77
I/io.jxcore.node.ConnectionHelper( 2879): connect: Connection process successfully started (peer ID: 90:E7:C4:F6:69:77)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect to peer with address 90:E7:C4:F6:69:77 (thread ID: 329)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stopServiceDiscovery
,I/wpa_supplicant( 2957): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1108","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1108","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2957): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
,W/bt-btm  ( 2950): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e51ec4 rs_disc_pending=2
E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2950): onReceive
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: G3-1
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): start: Starting peer discovery...
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 2879): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,W/bt-btif ( 2950): info:x10
,D/        ( 2950): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2950): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2950): process_service_search_attr_rsp
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,I/BluetoothBondStateMachine( 2950): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 1
E/bt-btif ( 2950): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2950): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2950): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2950): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 0
,D/BluetoothAdapterProperties( 2950): Failed to remove device: 90:E7:C4:F6:69:77
,I/BluetoothBondStateMachine( 2950): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2950): StableState(): Entering Off State
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 2950): new conn_srvc id:26, app_id:1
W/bt-btif ( 2950): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2950): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onSocketConnected: Authenticating next: [90:E7:C4:F6:69:77 90:E7:C4:F6:69:77 90:E7:C4:F6:69:77]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 329)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): onBytesWritten: 77 bytes successfully written (thread ID: 330)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Outgoing connection initialized (*handshake* thread ID: 330)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Exiting thread (thread ID: 329)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Entering thread (ID: 330)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): onBytesRead: Read 81 bytes successfully (thread ID: 330)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Handshake succeeded with [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6293 90:E7:C4:F6:69:77]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onAuthenticated: Fully connected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6293 90:E7:C4:F6:69:77]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Exiting thread (ID: 330)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6293 90:E7:C4:F6:69:77]
I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Outgoing connection, peer ID: 90:E7:C4:F6:69:77, name: HTC-HTC One M8s_PT6293, Bluetooth address: 90:E7:C4:F6:69:77
,D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Adding peer with ID 90:E7:C4:F6:69:77
,I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Outgoing socket thread, for peer with ID 90:E7:C4:F6:69:77, created successfully
D/io.jxcore.node.ConnectionHelper( 2879): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 2879): Entering thread (ID: 331)
,D/io.jxcore.node.OutgoingSocketThread( 2879): Server socket local port: 48472
I/io.jxcore.node.OutgoingSocketThread( 2879): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 2879): onListeningForIncomingConnections: Outgoing connection is using port 48472 (peer ID: 90:E7:C4:F6:69:77)
I/jxcore-log( 2879): 2015-12-08T16:19:12.804Z SendDataConnector.js: CLIENT connected to 48472, error: null
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:19:12.805Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2879): 
,I/io.jxcore.node.OutgoingSocketThread( 2879): Incoming data from address: /127.0.0.1, port: 48472
D/io.jxcore.node.OutgoingSocketThread( 2879): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 2879): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 2879): Exiting thread (ID: 331)
,I/jxcore-log( 2879): 2015-12-08T16:19:12.835Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2879): 
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 332, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 333, name: Receiver)
,D/        ( 2950): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,D/        ( 2950): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:11836
,D/btif_config_util( 2950): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2879): 2015-12-08T16:19:23.314Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:19:23.315Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:19:23.317Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:19:23.334Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:19:23.335Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:19:23.335Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2879): 
D/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Trying to close connection to peer with ID 90:E7:C4:F6:69:77
I/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 90:E7:C4:F6:69:77
I/io.jxcore.node.OutgoingSocketThread( 2879): close
I/io.jxcore.node.OutgoingSocketThread( 2879): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 333
I/io.jxcore.node.OutgoingSocketThread( 2879): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 332
I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 332, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2879): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Outgoing connection, peer with ID 90:E7:C4:F6:69:77 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 2879): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 333, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 2879): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Outgoing connection, peer with ID 90:E7:C4:F6:69:77 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Successfully disconnected (peer ID: 90:E7:C4:F6:69:77
,E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 332, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 90:E7:C4:F6:69:77
,D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 333, name: Receiver)
,I/jxcore-log( 2879): 2015-12-08T16:19:23.387Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 2879): 
I/jxcore-log( 2879): ---- round done--------
I/jxcore-log( 2879): 
I/jxcore-log( 2879): ---- gotta redo : 90:E7:C4:F6:69:77, try count now: 1
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): do fake peer & start
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:19:23.397Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:19:23.397Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:19:23.397Z SendDataConnector.js: do connect now
I/jxcore-log( 2879): 
,I/io.jxcore.node.ConnectionHelper( 2879): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): connect: Thali Test (Galaxy A3)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnecting: null 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Started connecting to null in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 2879): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
I/jxcore-log( 2879): 2015-12-08T16:19:23.400Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2879): 
,I/chromium( 2879): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 90:E7:C4:F6:69:77 done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 334)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e51b34 rs_disc_pending=1
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2950): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2950): onReceive
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: HTC One M8s
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:36, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 36
,W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:37, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 37
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 334)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect again in 300 ms... (thread ID: 334)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): Connection timeout
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x47
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:38, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 38
,W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:39, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2950): invalid rfc slot id: 39
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 334)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect again in 300 ms... (thread ID: 334)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stopServiceDiscovery
,I/wpa_supplicant( 2957): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnectionFailed: Cancelled: Connection timeout [08:EC:A9:50:76:27 samsung-SM-A300FU_PT333 08:EC:A9:50:76:27]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): restart: Restarting...
,I/jxcore-log( 2879): 2015-12-08T16:19:45.440Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 08:EC:A9:50:76:27 failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:19:45.440Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 08:EC:A9:50:76:27 failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:19:45.440Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2879): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Exiting thread (thread ID: 334)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): start: Starting peer discovery...
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2879): 2015-12-08T16:19:50.468Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:19:50.469Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2879): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 1 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2879): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,D/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:76:27), either no such connection or failed to close the connection
,I/jxcore-log( 2879): 2015-12-08T16:19:55.479Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:19:55.484Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:19:55.487Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:19:55.488Z SendDataConnector.js: do connect now
I/jxcore-log( 2879): 
,I/io.jxcore.node.ConnectionHelper( 2879): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): connect: Thali Test (Galaxy A3)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnecting: null 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Started connecting to null in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 2879): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 335)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): Connection timeout
,W/bt-btif ( 2950): info:x10
,D/        ( 2950): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 2950): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2950): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-l2cap( 2950): L2CAP - con rsp - bad ID. Exp: 5 Got: 3
,W/bt-sdp  ( 2950): process_service_search_attr_rsp
,E/bt-btif ( 2950): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2950): No record of the device:null
I/BluetoothBondStateMachine( 2950): bondStateChangeCallback: Status: 9 Address: 08:EC:A9:50:76:27 newState: 0
,W/bt-rfcomm( 2950): PORT_StartCnf failed result:5
,W/bt-btif ( 2950): invalid rfc slot id: 40
,W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/BluetoothBondStateMachine( 2950): In stable state, received invalid newState: 10
,E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:41, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 41
,E/bt-btif ( 2950): Do not find the bg connection mask for the remote device
,E/BluetoothRemoteDevices( 2950): aclStateChangeCallback: Device is NULL
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Exiting thread (thread ID: 335)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stopServiceDiscovery
,I/wpa_supplicant( 2957): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnectionFailed: Cancelled: Connection timeout [08:EC:A9:50:76:27 samsung-SM-A300FU_PT333 08:EC:A9:50:76:27]
I/jxcore-log( 2879): 2015-12-08T16:20:31.149Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 08:EC:A9:50:76:27 failed
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:20:31.149Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 08:EC:A9:50:76:27 failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:20:31.157Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2879): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,I/jxcore-log( 2879): 2015-12-08T16:20:36.159Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:20:36.160Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2879): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery started successfully
I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pManager( 2879): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Got a list of peers, but since we are currently discovering services (not peers), the new list is ignored
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:76:27), either no such connection or failed to close the connection
I/jxcore-log( 2879): 2015-12-08T16:20:41.167Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:20:41.168Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:20:41.169Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:20:41.169Z SendDataConnector.js: do connect now
I/jxcore-log( 2879): 
,I/io.jxcore.node.ConnectionHelper( 2879): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): connect: Thali Test (Galaxy A3)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnecting: null 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Started connecting to null in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 2879): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 336)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:42, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 42
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:43, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 43
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 336)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect again in 300 ms... (thread ID: 336)
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): Connection timeout
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:44, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 44
,W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/art     (  761): Explicit concurrent mark sweep GC freed 61445(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 28MB/42MB, paused 4.857ms total 66.444ms
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:45, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2950): invalid rfc slot id: 45
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 336)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect again in 300 ms... (thread ID: 336)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnectionFailed: Cancelled: Connection timeout [08:EC:A9:50:76:27 samsung-SM-A300FU_PT333 08:EC:A9:50:76:27]
,I/jxcore-log( 2879): 2015-12-08T16:21:02.079Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 08:EC:A9:50:76:27 failed
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:21:02.082Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 08:EC:A9:50:76:27 failed
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:21:02.085Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2879): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Exiting thread (thread ID: 336)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stopServiceDiscovery
,I/wpa_supplicant( 2957): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,I/jxcore-log( 2879): 2015-12-08T16:21:07.090Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:21:07.091Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2879): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): start: Starting peer discovery...
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,D/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:76:27), either no such connection or failed to close the connection
I/jxcore-log( 2879): 2015-12-08T16:21:12.094Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:21:12.095Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:21:12.096Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:21:12.096Z SendDataConnector.js: do connect now
I/jxcore-log( 2879): 
I/io.jxcore.node.ConnectionHelper( 2879): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): connect: Thali Test (Galaxy A3)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnecting: null 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Started connecting to null in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 2879): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 337)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
,D/WifiP2pManager( 2879): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:46, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 46
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): Connection timeout
,W/bt-btif ( 2950): info:x10
,D/        ( 2950): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2950): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2950): process_service_search_attr_rsp
,D/btif_config_util( 2950): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/BluetoothBondStateMachine( 2950): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
E/bt-btif ( 2950): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2950): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2950): Entering PendingCommandState State
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2950): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/BluetoothAdapterProperties( 2950): Failed to remove device: 08:EC:A9:50:76:27
,I/BluetoothBondStateMachine( 2950): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2950): StableState(): Entering Off State
,W/bt-btif ( 2950): new conn_srvc id:26, app_id:1
W/bt-btif ( 2950): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2950): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onSocketConnected: Authenticating next: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT333 08:EC:A9:50:76:27]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Socket connection succeeded using system decided port, total number of attempts: 1 (thread ID: 337)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Exiting thread (thread ID: 337)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2283","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2283 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT2378"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT2378 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged,
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnectionFailed: Cancelled: Connection timeout [08:EC:A9:50:76:27 samsung-SM-A300FU_PT333 08:EC:A9:50:76:27]
,I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:75:41, peer name: samsung-SM-A300FU_PT2283, peer ID: 08:EC:A9:50:75:41, Wi-Fi Direct device name: A3-1, Wi-Fi Direct address: 0a:ec:a9:50:75:42
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:75:41 already in the list
,W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: 34:FC:EF:11:B1:66, peer name: LGE-Nexus 5_PT2378, peer ID: 34:FC:EF:11:B1:66, Wi-Fi Direct device name: , Wi-Fi Direct address: 52:55:27:f0:ff:f0
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID 34:FC:EF:11:B1:66 already in the list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
I/jxcore-log( 2879): 2015-12-08T16:21:40.212Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 08:EC:A9:50:76:27 failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:21:40.213Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 08:EC:A9:50:76:27 failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:21:40.215Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2879): 
,W/bt-btif ( 2950): bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/btif_config_util( 2950): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2950): onReceive
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/jxcore-log( 2879): 2015-12-08T16:21:45.217Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:21:45.218Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2879): 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1403","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT1403 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: F8:95:C7:87:85:54, peer name: LGE-LG-D722_PT1403, peer ID: F8:95:C7:87:85:54, Wi-Fi Direct device name: G3s-1, Wi-Fi Direct address: a2:39:f7:70:12:80
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:85:54 already in the list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,D/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:76:27), either no such connection or failed to close the connection
I/jxcore-log( 2879): 2015-12-08T16:21:50.224Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:21:50.224Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:21:50.225Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:21:50.225Z SendDataConnector.js: do connect now
I/jxcore-log( 2879): 
I/io.jxcore.node.ConnectionHelper( 2879): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): connect: Thali Test (Galaxy A3)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Trying to start connecting to Thali Test (Galaxy A3) in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnecting: Thali Test (Galaxy A3) 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Started connecting to Thali Test (Galaxy A3) in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 2879): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 338)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x44
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:48, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 48
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:49, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 49
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 338)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect again in 300 ms... (thread ID: 338)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): Connection timeout
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:50, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2950): invalid rfc slot id: 50
,W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:51, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2950): invalid rfc slot id: 51
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 338)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect again in 300 ms... (thread ID: 338)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnectionFailed: Cancelled: Connection timeout [08:EC:A9:50:76:27 samsung-SM-A300FU_PT333 08:EC:A9:50:76:27]
,I/jxcore-log( 2879): 2015-12-08T16:22:11.133Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 08:EC:A9:50:76:27 failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:22:11.134Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 08:EC:A9:50:76:27 failed
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:22:11.152Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2879): 
D/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:76:27), either no such connection or failed to close the connection
I/jxcore-log( 2879): 2015-12-08T16:22:11.155Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2879): 
I/jxcore-log( 2879): ---- round done--------
I/jxcore-log( 2879): 
I/jxcore-log( 2879): ---- gotta redo : 08:EC:A9:50:76:27, try count now: 1
I/jxcore-log( 2879): 
I/jxcore-log( 2879): do fake peer & start
I/jxcore-log( 2879): 
I/jxcore-log( 2879): Connect to fake peer: 58:3F:54:73:64:C0
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:22:11.158Z SendDataConnector.js: Start called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:22:11.159Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:22:11.159Z SendDataConnector.js: do connect now
I/jxcore-log( 2879): 
,I/io.jxcore.node.ConnectionHelper( 2879): connect: Trying to connect to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Trying to start connecting to G3-1 in address 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnecting: G3-1 58:3F:54:73:64:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Started connecting to G3-1 in address 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 2879): connect: Connection process successfully started (peer ID: 58:3F:54:73:64:C0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect to peer with address 58:3F:54:73:64:C0 (thread ID: 339)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
I/chromium( 2879): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 08:EC:A9:50:76:27 done with result: Connection to peer with ID 08:EC:A9:50:76:27 failed", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Exiting thread (thread ID: 338)
,W/bt-btif ( 2950): info:x10
,D/        ( 2950): remote version info [58:3f:54:73:64:c0]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: G3-1
,W/bt-sdp  ( 2950): process_service_search_attr_rsp
,W/bt-btif ( 2950): new conn_srvc id:26, app_id:1
W/bt-btif ( 2950): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2950): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onSocketConnected: Authenticating next: [58:3F:54:73:64:C0 LGE-LG-D855_PT71 58:3F:54:73:64:C0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 339)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): onBytesWritten: 77 bytes successfully written (thread ID: 340)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Outgoing connection initialized (*handshake* thread ID: 340)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Exiting thread (thread ID: 339)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Entering thread (ID: 340)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): onBytesRead: Read 75 bytes successfully (thread ID: 340)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Handshake succeeded with [58:3F:54:73:64:C0 LGE-LG-D855_PT71 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onAuthenticated: Fully connected: [58:3F:54:73:64:C0 LGE-LG-D855_PT71 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Exiting thread (ID: 340)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT71 58:3F:54:73:64:C0]
,I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Outgoing connection, peer ID: 58:3F:54:73:64:C0, name: LGE-LG-D855_PT71, Bluetooth address: 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID 58:3F:54:73:64:C0 already in the list
I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Outgoing socket thread, for peer with ID 58:3F:54:73:64:C0, created successfully
D/io.jxcore.node.ConnectionHelper( 2879): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 2879): Entering thread (ID: 341)
,D/io.jxcore.node.OutgoingSocketThread( 2879): Server socket local port: 38761
I/io.jxcore.node.OutgoingSocketThread( 2879): Now accepting connections...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stopServiceDiscovery
,I/wpa_supplicant( 2957): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1108","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1108","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
I/wpa_supplicant( 2957): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
,I/io.jxcore.node.ConnectionHelper( 2879): onListeningForIncomingConnections: Outgoing connection is using port 38761 (peer ID: 58:3F:54:73:64:C0)
I/jxcore-log( 2879): 2015-12-08T16:22:12.701Z SendDataConnector.js: CLIENT connected to 38761, error: null
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:22:12.701Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2879): 
,I/io.jxcore.node.OutgoingSocketThread( 2879): Incoming data from address: /127.0.0.1, port: 38761
D/io.jxcore.node.OutgoingSocketThread( 2879): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 2879): startStreamCopyingThreads: OK
,D/io.jxcore.node.OutgoingSocketThread( 2879): Exiting thread (ID: 341)
,I/jxcore-log( 2879): 2015-12-08T16:22:12.705Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2879): 
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 343, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 342, name: Sender)
,D/        ( 2950): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 2879): 2015-12-08T16:22:13.328Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:22:13.401Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2879): 
,D/        ( 2950): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13816
,I/jxcore-log( 2879): 2015-12-08T16:22:13.475Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:22:13.689Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2879): 
,D/        ( 2950): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 2879): 2015-12-08T16:22:13.769Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:22:13.912Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:22:14.582Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2879): 
,D/btif_config_util( 2950): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2879): 2015-12-08T16:22:14.784Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2879): 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: Galaxy S5-2 3a:94:96:b5:06:dd
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): start: Starting peer discovery...
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 2879): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2879): 2015-12-08T16:22:19.486Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2879): 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 2879): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
D/WifiP2pManager( 2879): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7084"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:9D:93:0B LGE-LG-D802_PT7084 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7084"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7084"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: 34:FC:EF:9D:93:0B, peer name: LGE-LG-D802_PT7084, peer ID: 34:FC:EF:9D:93:0B, Wi-Fi Direct device name: Thali Test's G2, Wi-Fi Direct address: 36:fc:ef:de:0a:e2
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID 34:FC:EF:9D:93:0B already in the list
,W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/jxcore-log( 2879): 2015-12-08T16:22:22.577Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:22:22.578Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:22:22.599Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:22:22.600Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2879): 
D/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Trying to close connection to peer with ID 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 58:3F:54:73:64:C0
I/io.jxcore.node.OutgoingSocketThread( 2879): close
I/io.jxcore.node.OutgoingSocketThread( 2879): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 343
I/io.jxcore.node.OutgoingSocketThread( 2879): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 342
I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 342, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2879): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Outgoing connection, peer with ID 58:3F:54:73:64:C0 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local output stream...
,I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 2879): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 343, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 2879): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Outgoing connection, peer with ID 58:3F:54:73:64:C0 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Successfully disconnected (peer ID: 58:3F:54:73:64:C0
,E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 342, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 343, name: Receiver)
,I/jxcore-log( 2879): 2015-12-08T16:22:22.639Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 2879): 
I/jxcore-log( 2879): ---- round done--------
I/jxcore-log( 2879): 
I/jxcore-log( 2879): do fake peer & start
I/jxcore-log( 2879): 
I/jxcore-log( 2879): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:22:22.640Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:22:22.640Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:22:22.640Z SendDataConnector.js: do connect now
I/jxcore-log( 2879): 
,I/io.jxcore.node.ConnectionHelper( 2879): connect: Trying to connect to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Trying to start connecting to null in address 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnecting: null 44:80:EB:7B:5A:05
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Started connecting to null in address 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 2879): connect: Connection process successfully started (peer ID: 44:80:EB:7B:5A:05)
I/chromium( 2879): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 58:3F:54:73:64:C0 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect to peer with address 44:80:EB:7B:5A:05 (thread ID: 344)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e51ec4 rs_disc_pending=1
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2950): bta_jv_rfc_port_to_cb(port_handle:0x17):jv handle:0x0 not FOUND
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: P2P: Reject scan trigger since one is already pending
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:53, failed to find channle,                                       status:1, scn:0
,W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,W/bt-btif ( 2950): invalid rfc slot id: 53
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e51ec4 rs_disc_pending=1
E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2950): onReceive
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: G3-1
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:54, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 54
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 344)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect again in 300 ms... (thread ID: 344)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): Connection timeout
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:55, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 55
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 2950): info:x10
,D/        ( 2950): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2950): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2950): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2950): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
E/bt-btif ( 2950): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2950): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2950): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2950): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 2950): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 2950): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2950): StableState(): Entering Off State
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 2950): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,W/bt-btif ( 2950): info:x10
,D/        ( 2950): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2950): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2950): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 1
,E/bt-btif ( 2950): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2950): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2950): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2950): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 0
,D/BluetoothAdapterProperties( 2950): Failed to remove device: B4:CE:F6:AB:A4:6A
,I/BluetoothBondStateMachine( 2950): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2950): StableState(): Entering Off State
,W/bt-btif ( 2950): new conn_srvc id:26, app_id:255
W/bt-btif ( 2950): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2950): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Incoming connection initialized (thread ID: 345)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Entering thread (ID: 345)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): onBytesRead: Read 84 bytes successfully (thread ID: 345)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Got valid identity from [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT5835 B4:CE:F6:AB:A4:6A]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): onBytesWritten: 77 bytes successfully written (thread ID: 345)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): removeThreadFromList: Removing thread with ID 345
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Handshake thread disposed (thread ID: 345)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onIncomingConnectionConnected: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT5835 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Exiting thread (ID: 345)
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e52254 rs_disc_pending=1
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2950): invalid rfc slot id: 56
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onConnectionFailed: Cancelled: Connection timeout
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 344)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect again in 300 ms... (thread ID: 344)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onIsDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1108","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1108","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/wpa_supplicant( 2957): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6099","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6099 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6099","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6099","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT664","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT664 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT664","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT664","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5835"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT5835 B4:CE:F6:AB:A4:6A]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5835"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5835"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5816","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT5816 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5816","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5816","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT2378"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT2378 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 5 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT2378"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66,","pn":"LGE-Nexus 5_PT2378"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1989"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT1989 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 6 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1989"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1989"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT71","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT71 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 7 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT71","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT71","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnected: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT5835 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT9640","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9640 E0:DB:10:1F:C9:5E]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 8 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT9640","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT9640","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnectionFailed: Cancelled: Connection timeout [44:80:EB:7B:5A:05 motorola-XT1072_PT731 44:80:EB:7B:5A:05]
,W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: E0:DB:10:14:E2:C0, peer name: samsung-SM-N910C_PT6099, peer ID: E0:DB:10:14:E2:C0, Wi-Fi Direct device name: Note4-1, Wi-Fi Direct address: 92:b6:86:43:73:1c
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID E0:DB:10:14:E2:C0 already in the list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 8 peer(s), but doing nothing with that list
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: F8:CF:C5:D9:E5:61, peer name: motorola-Nexus 6_PT664, peer ID: F8:CF:C5:D9:E5:61, Wi-Fi Direct device name: Android_50a5, Wi-Fi Direct address: fa:cf:c5:d9:e5:62
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Adding peer with ID F8:CF:C5:D9:E5:61
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 8 peer(s), but doing nothing with that list
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: B4:CE:F6:AB:A4:6A, peer name: HTC-HTC Desire 820_PT5835, peer ID: B4:CE:F6:AB:A4:6A, Wi-Fi Direct device name: Android_1950, Wi-Fi Direct address: b6:ce:f6:ad:a4:6b
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Adding peer with ID B4:CE:F6:AB:A4:6A
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 8 peer(s), but doing nothing with that list
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: F8:95:C7:87:3C:51, peer name: LGE-LG-H815_PT5816, peer ID: F8:95:C7:87:3C:51, Wi-Fi Direct device name: , Wi-Fi Direct address: a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Adding peer with ID F8:95:C7:87:3C:51
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 8 peer(s), but doing nothing with that list
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: 34:FC:EF:11:B1:66, peer name: LGE-Nexus 5_PT2378, peer ID: 34:FC:EF:11:B1:66, Wi-Fi Direct device name: Android_2dc2, Wi-Fi Direct address: 52:55:27:f0:ff:f0
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID 34:FC:EF:11:B1:66 already in the list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 8 peer(s), but doing nothing with that list
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: 80:01:84:8A:B3:68, peer name: HTC-HTC Desire 820_PT1989, peer ID: 80:01:84:8A:B3:68, Wi-Fi Direct device name: Android_63cc, Wi-Fi Direct address: 82:01:84:6b:e8:5d
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID 80:01:84:8A:B3:68 already in the list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 8 peer(s), but doing nothing with that list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): restart: Restarting...
,I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: 58:3F:54:73:64:C0, peer name: LGE-LG-D855_PT71, peer ID: 58:3F:54:73:64:C0, Wi-Fi Direct device name: G3-1, Wi-Fi Direct address: 02:9a:02:7b:60:ac
,I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID 58:3F:54:73:64:C0 already in the list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 8 peer(s), but doing nothing with that list
I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Incoming connection, peer ID: B4:CE:F6:AB:A4:6A, name: HTC-HTC Desire 820_PT5835, Bluetooth address: B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID B4:CE:F6:AB:A4:6A
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID B4:CE:F6:AB:A4:6A already in the list
I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Incoming socket thread, for peer with ID B4:CE:F6:AB:A4:6A, created successfully
D/io.jxcore.node.ConnectionHelper( 2879): onConnected: The total number of connections is now 1
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: E0:DB:10:1F:C9:5E, peer name: samsung-SM-N9005_PT9640, peer ID: E0:DB:10:1F:C9:5E, Wi-Fi Direct device name: Note3-1, Wi-Fi Direct address: ea:50:8b:de:28:a3
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID E0:DB:10:1F:C9:5E already in the list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 8 peer(s), but doing nothing with that list
,I/jxcore-log( 2879): 2015-12-08T16:23:48.974Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:23:48.975Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:23:48.975Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2879): 
,D/io.jxcore.node.IncomingSocketThread( 2879): Entering thread (ID: 346)
,I/io.jxcore.node.IncomingSocketThread( 2879): Local host address: localhost/127.0.0.1, port: 46178
D/io.jxcore.node.IncomingSocketThread( 2879): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 2879): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 2879): Exiting thread (ID: 346)
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 347, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 348, name: Receiver)
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2957): P2P-FIND-STOPPED 
I/jxcore-log( 2879): 2015-12-08T16:23:49.006Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2879): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/jxcore-log( 2879): 2015-12-08T16:23:49.009Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 2879): 
,W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
,W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): restart: Restarting...
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Exiting thread (thread ID: 344)
,I/jxcore-log( 2879): 2015-12-08T16:23:49.306Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:23:49.474Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:23:49.482Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:23:49.495Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:23:49.563Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:23:49.607Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:23:49.615Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:23:49.805Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:23:49.845Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:23:49.893Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:23:49.901Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:23:49.963Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2879): 
,D/btif_config_util( 2950): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e5241c rs_disc_pending=0
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2950): invalid rfc slot id: 34
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 348, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 2879): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Incoming connection, peer with ID B4:CE:F6:AB:A4:6A disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 346
,I/io.jxcore.node.IncomingSocketThread( 2879): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 348
I/io.jxcore.node.IncomingSocketThread( 2879): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 347
I/io.jxcore.node.IncomingSocketThread( 2879): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 347, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 2879): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Incoming connection, peer with ID B4:CE:F6:AB:A4:6A disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.IncomingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 2879): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 2879): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 347, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 348, name: Receiver)
,I/jxcore-log( 2879): 2015-12-08T16:23:50.514Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2879): 
,W/bt-rfcomm( 2950): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
,W/bt-rfcomm( 2950): RFCOMM_DisconnectInd LCID:0x42
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e52254 rs_disc_pending=1
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e5241c rs_disc_pending=1
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2950): onReceive
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: XT1072
,I/jxcore-log( 2879): 2015-12-08T16:23:53.977Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:23:53.979Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2879): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): start: Starting peer discovery...
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pManager( 2879): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2950): onReceive
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: HTC Desire 820
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2879): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,D/WifiP2pManager( 2879): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2879): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
D/WifiP2pManager( 2879): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,D/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Trying to close connection to peer with ID 44:80:EB:7B:5A:05
E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Failed to disconnect (peer ID: 44:80:EB:7B:5A:05), either no such connection or failed to close the connection
I/jxcore-log( 2879): 2015-12-08T16:23:58.985Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:23:58.986Z SendDataConnector.js: Connect (retry count 1) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:23:58.986Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:23:58.987Z SendDataConnector.js: do connect now
I/jxcore-log( 2879): 
I/io.jxcore.node.ConnectionHelper( 2879): connect: Trying to connect to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Trying to start connecting to XT1072 in address 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnecting: XT1072 44:80:EB:7B:5A:05
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Started connecting to XT1072 in address 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 2879): connect: Connection process successfully started (peer ID: 44:80:EB:7B:5A:05)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect to peer with address 44:80:EB:7B:5A:05 (thread ID: 349)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:58, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 58
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x44
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:59, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 59
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 349)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect again in 300 ms... (thread ID: 349)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): Connection timeout
,W/bt-btif ( 2950): info:x10
,D/        ( 2950): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: XT1072
,D/btif_config_util( 2950): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-sdp  ( 2950): process_service_search_attr_rsp
,W/bt-btif ( 2950): new conn_srvc id:26, app_id:1
W/bt-btif ( 2950): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2950): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onSocketConnected: Authenticating next: [44:80:EB:7B:5A:05 motorola-XT1072_PT731 44:80:EB:7B:5A:05]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Socket connection succeeded using port (1), total number of attempts: 2 (thread ID: 349)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Exiting thread (thread ID: 349)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stopServiceDiscovery
,I/wpa_supplicant( 2957): P2P-FIND-STOPPED 
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnectionFailed: Cancelled: Connection timeout [44:80:EB:7B:5A:05 motorola-XT1072_PT731 44:80:EB:7B:5A:05]
,I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
,I/jxcore-log( 2879): 2015-12-08T16:24:43.846Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:24:43.846Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:24:43.846Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2879): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
,W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/bt-btif ( 2950): bta_jv_rfc_port_to_cb(port_handle:0x1a):jv handle:0x0 not FOUND
,E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2950): onReceive
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: XT1072
,I/jxcore-log( 2879): 2015-12-08T16:24:48.846Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:24:48.847Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2879): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): start: Starting peer discovery...
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 2879): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 2879): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2957): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT333","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT333 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT333","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:76:27, peer name: samsung-SM-A300FU_PT333, peer ID: 08:EC:A9:50:76:27, Wi-Fi Direct device name: Thali Test (Galaxy A3), Wi-Fi Direct address: 0a:ec:a9:50:76:28
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:76:27 already in the list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT6293","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6293 90:E7:C4:F6:69:77]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT6293","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: 90:E7:C4:F6:69:77, peer name: HTC-HTC One M8s_PT6293, peer ID: 90:E7:C4:F6:69:77, Wi-Fi Direct device name: Android_608e, Wi-Fi Direct address: 92:e7:c4:e6:4c:f8
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID 90:E7:C4:F6:69:77 already in the list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT71","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT71 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT71","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: 58:3F:54:73:64:C0, peer name: LGE-LG-D855_PT71, peer ID: 58:3F:54:73:64:C0, Wi-Fi Direct device name: , Wi-Fi Direct address: 02:9a:02:7b:60:ac
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID 58:3F:54:73:64:C0 already in the list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5835"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT5835 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5835"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: B4:CE:F6:AB:A4:6A, peer name: HTC-HTC Desire 820_PT5835, peer ID: B4:CE:F6:AB:A4:6A, Wi-Fi Direct device name: , Wi-Fi Direct address: b6:ce:f6:ad:a4:6b
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID B4:CE:F6:AB:A4:6A already in the list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
,D/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Trying to close connection to peer with ID 44:80:EB:7B:5A:05
E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Failed to disconnect (peer ID: 44:80:EB:7B:5A:05), either no such connection or failed to close the connection
I/jxcore-log( 2879): 2015-12-08T16:24:53.851Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:24:53.852Z SendDataConnector.js: Connect (retry count 2) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:24:53.853Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:24:53.853Z SendDataConnector.js: do connect now
I/jxcore-log( 2879): 
I/io.jxcore.node.ConnectionHelper( 2879): connect: Trying to connect to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Trying to start connecting to XT1072 in address 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnecting: XT1072 44:80:EB:7B:5A:05
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Started connecting to XT1072 in address 44:80:EB:7B:5A:05,
I/io.jxcore.node.ConnectionHelper( 2879): connect: Connection process successfully started (peer ID: 44:80:EB:7B:5A:05)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect to peer with address 44:80:EB:7B:5A:05 (thread ID: 350)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:61, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 61
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2950): info:x10
,D/        ( 2950): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: XT1072
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 2950): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): Connection timeout
,E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:62, failed to find channle,                                       status:1, scn:0
E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 350)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect again in 300 ms... (thread ID: 350)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onConnectionFailed: Cancelled: Connection timeout
,W/bt-btif ( 2950): invalid rfc slot id: 62
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnectionFailed: Cancelled: Connection timeout [44:80:EB:7B:5A:05 motorola-XT1072_PT731 44:80:EB:7B:5A:05]
,I/jxcore-log( 2879): 2015-12-08T16:25:10.680Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:25:10.681Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:25:10.681Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2879): 
,D/BluetoothMapService( 2950): onReceive
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: XT1072
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Exiting thread (thread ID: 350)
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT291","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT291 7C:F9:0E:34:8A:A0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 5 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT291","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: 7C:F9:0E:34:8A:A0, peer name: samsung-SM-G900F_PT291, peer ID: 7C:F9:0E:34:8A:A0, Wi-Fi Direct device name: , Wi-Fi Direct address: ee:1f:72:63:11:86
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:34:8A:A0 already in the list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 5 peer(s), but doing nothing with that list
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2950): info:x10
,D/        ( 2950): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2950): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/BluetoothBondStateMachine( 2950): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 1
E/bt-btif ( 2950): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2950): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2950): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2950): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 0
D/BluetoothAdapterProperties( 2950): Failed to remove device: 7C:F9:0E:51:18:22
,I/BluetoothBondStateMachine( 2950): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2950): StableState(): Entering Off State
,I/jxcore-log( 2879): 2015-12-08T16:25:15.682Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:25:15.682Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2879): 
,W/bt-btif ( 2950): new conn_srvc id:26, app_id:255
W/bt-btif ( 2950): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2950): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Incoming connection initialized (thread ID: 351)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Entering thread (ID: 351)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): onBytesRead: Read 83 bytes successfully (thread ID: 351)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Got valid identity from [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9428 7C:F9:0E:51:18:22]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): onBytesWritten: 77 bytes successfully written (thread ID: 351)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): removeThreadFromList: Removing thread with ID 351
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Handshake thread disposed (thread ID: 351)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onIncomingConnectionConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9428 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Exiting thread (ID: 351)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9428 7C:F9:0E:51:18:22]
,I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Incoming connection, peer ID: 7C:F9:0E:51:18:22, name: samsung-SM-A500FU_PT9428, Bluetooth address: 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:51:18:22 already in the list
,I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Incoming socket thread, for peer with ID 7C:F9:0E:51:18:22, created successfully
D/io.jxcore.node.ConnectionHelper( 2879): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 2879): Entering thread (ID: 352)
,I/io.jxcore.node.IncomingSocketThread( 2879): Local host address: localhost/127.0.0.1, port: 46178
D/io.jxcore.node.IncomingSocketThread( 2879): Setting local streams and starting stream copying threads...
,I/jxcore-log( 2879): 2015-12-08T16:25:15.775Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2879): 
,I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 2879): startStreamCopyingThreads: OK
,D/io.jxcore.node.IncomingSocketThread( 2879): Exiting thread (ID: 352)
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 354, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 353, name: Sender)
,I/jxcore-log( 2879): 2015-12-08T16:25:16.550Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:16.564Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:16.572Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:16.585Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:16.595Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:16.604Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:16.704Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:16.818Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:16.835Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:16.891Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:16.969Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:17.006Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:17.042Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:17.053Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:17.127Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:17.351Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:17.401Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:17.439Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:17.501Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:17.594Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:17.623Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:17.691Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:17.703Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:17.777Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:17.877Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:17.885Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:17.948Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:17.966Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:18.046Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:18.054Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:18.125Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:18.137Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:18.227Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:18.348Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:18.355Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:18.392Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:18.407Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:18.492Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:18.635Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:18.737Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:18.885Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:18.989Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:19.152Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:19.252Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:19.338Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:19.416Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:19.491Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:19.669Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:19.702Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:19.764Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:19.835Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:19.849Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2879): 
,W/bt-btif ( 2950): invalid rfc slot id: 57
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 354, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 2879): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Incoming connection, peer with ID 7C:F9:0E:51:18:22 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 352
I/io.jxcore.node.IncomingSocketThread( 2879): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 354
I/io.jxcore.node.IncomingSocketThread( 2879): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 353
I/io.jxcore.node.IncomingSocketThread( 2879): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local input stream...
,I/io.jxcore.node.IncomingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 2879): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 2879): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 354, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 353, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 2879): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Incoming connection, peer with ID 7C:F9:0E:51:18:22 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 353, name: Sender)
,I/jxcore-log( 2879): 2015-12-08T16:25:19.970Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2879): 
,D/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Trying to close connection to peer with ID 44:80:EB:7B:5A:05
E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Failed to disconnect (peer ID: 44:80:EB:7B:5A:05), either no such connection or failed to close the connection
I/jxcore-log( 2879): 2015-12-08T16:25:20.686Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:25:20.686Z SendDataConnector.js: Connect (retry count 3) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:25:20.687Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:25:20.687Z SendDataConnector.js: do connect now
I/jxcore-log( 2879): 
I/io.jxcore.node.ConnectionHelper( 2879): connect: Trying to connect to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Trying to start connecting to XT1072 in address 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnecting: XT1072 44:80:EB:7B:5A:05
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Started connecting to XT1072 in address 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 2879): connect: Connection process successfully started (peer ID: 44:80:EB:7B:5A:05)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect to peer with address 44:80:EB:7B:5A:05 (thread ID: 355)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 2950): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e525e4 rs_disc_pending=1
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2950): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
W/bt-rfcomm( 2950): RFCOMM_DisconnectInd LCID:0x48
,E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2950): onReceive
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: Thali Test (Galaxy A5)
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:64, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 64
,W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:65, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 65
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 355)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect again in 300 ms... (thread ID: 355)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onConnectionFailed: Cancelled: Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnectionFailed: Cancelled: Connection timeout [44:80:EB:7B:5A:05 motorola-XT1072_PT731 44:80:EB:7B:5A:05]
I/jxcore-log( 2879): 2015-12-08T16:25:35.704Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:35.705Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:25:35.714Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2879): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Exiting thread (thread ID: 355)
,I/jxcore-log( 2879): 2015-12-08T16:25:40.716Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:25:40.716Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2879): 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Trying to close connection to peer with ID 44:80:EB:7B:5A:05
E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Failed to disconnect (peer ID: 44:80:EB:7B:5A:05), either no such connection or failed to close the connection
,I/jxcore-log( 2879): 2015-12-08T16:25:45.725Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:25:45.725Z SendDataConnector.js: Connect (retry count 4) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:25:45.726Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:25:45.727Z SendDataConnector.js: do connect now
I/jxcore-log( 2879): 
I/io.jxcore.node.ConnectionHelper( 2879): connect: Trying to connect to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Trying to start connecting to XT1072 in address 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnecting: XT1072 44:80:EB:7B:5A:05
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Started connecting to XT1072 in address 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 2879): connect: Connection process successfully started (peer ID: 44:80:EB:7B:5A:05)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect to peer with address 44:80:EB:7B:5A:05 (thread ID: 356)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT731","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT731 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 6 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT731","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: 44:80:EB:7B:5A:05, peer name: motorola-XT1072_PT731, peer ID: 44:80:EB:7B:5A:05, Wi-Fi Direct device name: , Wi-Fi Direct address: 44:80:eb:7b:5a:07
,I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID 44:80:EB:7B:5A:05 already in the list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 6 peer(s), but doing nothing with that list
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stopServiceDiscovery
,I/wpa_supplicant( 2957): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1108","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1108","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery started successfully
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): start: Starting peer discovery...
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2879): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: XT1039_8c05 f4:f1:e1:5c:43:c8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 2879): Ignored { when=-9ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
D/WifiP2pManager( 2879): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): Connection timeout
,W/bt-btif ( 2950): info:x10
,D/        ( 2950): remote version info [44:80:eb:7b:5a:05]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: XT1072
,W/bt-sdp  ( 2950): process_service_search_attr_rsp
,W/bt-btif ( 2950): new conn_srvc id:26, app_id:1
W/bt-btif ( 2950): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2950): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onSocketConnected: Authenticating next: [44:80:EB:7B:5A:05 motorola-XT1072_PT731 44:80:EB:7B:5A:05]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnectionFailed: Cancelled: Connection timeout [44:80:EB:7B:5A:05 motorola-XT1072_PT731 44:80:EB:7B:5A:05]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 356)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Exiting thread (thread ID: 356)
,I/jxcore-log( 2879): 2015-12-08T16:26:02.324Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:26:02.328Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2879): 
,W/bt-btif ( 2950): bta_jv_rfc_port_to_cb(port_handle:0x1c):jv handle:0x0 not FOUND
,I/jxcore-log( 2879): 2015-12-08T16:26:02.335Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2879): 
D/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Trying to close connection to peer with ID 44:80:EB:7B:5A:05
E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Failed to disconnect (peer ID: 44:80:EB:7B:5A:05), either no such connection or failed to close the connection
,I/jxcore-log( 2879): 2015-12-08T16:26:02.338Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): ---- round done--------
I/jxcore-log( 2879): 
I/jxcore-log( 2879): ---- gotta redo : 44:80:EB:7B:5A:05, try count now: 1
I/jxcore-log( 2879): 
I/jxcore-log( 2879): do fake peer & start
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:26:02.341Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:26:02.342Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:26:02.342Z SendDataConnector.js: do connect now
I/jxcore-log( 2879): 
,I/io.jxcore.node.ConnectionHelper( 2879): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): connect: S5mini-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Trying to start connecting to null in address 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnecting: null 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Started connecting to null in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 2879): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
,I/chromium( 2879): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 44:80:EB:7B:5A:05 done with result: Connection to peer with ID 44:80:EB:7B:5A:05 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 357)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2950): info:x10
,D/        ( 2950): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 2950): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e527ac rs_disc_pending=1
,W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e527ac rs_disc_pending=0
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2950): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2950): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 1
E/bt-btif ( 2950): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2950): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2950): Entering PendingCommandState State
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: P2P: Reject scan trigger since one is already pending
,E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2950): onReceive
,I/BluetoothBondStateMachine( 2950): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 0
,D/BluetoothAdapterProperties( 2950): Failed to remove device: 00:F4:6F:30:E0:6C
,I/BluetoothBondStateMachine( 2950): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2950): StableState(): Entering Off State
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: XT1072
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 2950): new conn_srvc id:26, app_id:1
W/bt-btif ( 2950): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2950): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onSocketConnected: Authenticating next: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT26 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 357)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): onBytesWritten: 77 bytes successfully written (thread ID: 358)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Outgoing connection initialized (*handshake* thread ID: 358)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Exiting thread (thread ID: 357)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Entering thread (ID: 358)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): onBytesRead: Read 80 bytes successfully (thread ID: 358)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Handshake succeeded with [00:F4:6F:30:E0:6C samsung-SM-G800F_PT26 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onAuthenticated: Fully connected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT26 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Exiting thread (ID: 358)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT26 00:F4:6F:30:E0:6C]
I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Outgoing connection, peer ID: 00:F4:6F:30:E0:6C, name: samsung-SM-G800F_PT26, Bluetooth address: 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
,I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
,I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Outgoing socket thread, for peer with ID 00:F4:6F:30:E0:6C, created successfully
D/io.jxcore.node.ConnectionHelper( 2879): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 2879): Entering thread (ID: 359)
D/io.jxcore.node.OutgoingSocketThread( 2879): Server socket local port: 42942
,I/io.jxcore.node.OutgoingSocketThread( 2879): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 2879): onListeningForIncomingConnections: Outgoing connection is using port 42942 (peer ID: 00:F4:6F:30:E0:6C)
I/jxcore-log( 2879): 2015-12-08T16:26:06.800Z SendDataConnector.js: CLIENT connected to 42942, error: null
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:26:06.801Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2879): 
,I/io.jxcore.node.OutgoingSocketThread( 2879): Incoming data from address: /127.0.0.1, port: 42942
D/io.jxcore.node.OutgoingSocketThread( 2879): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 2879): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 2879): Exiting thread (ID: 359)
,I/jxcore-log( 2879): 2015-12-08T16:26:06.833Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2879): 
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 360, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 361, name: Receiver)
,I/jxcore-log( 2879): 2015-12-08T16:26:07.923Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:26:08.277Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:26:08.867Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:26:08.985Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:26:09.452Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:26:10.171Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:26:10.747Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2879): 
,D/btif_config_util( 2950): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2879): 2015-12-08T16:26:11.087Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:26:11.645Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:26:11.940Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:26:11.941Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:26:11.957Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:26:11.958Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2879): 
,D/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:F4:6F:30:E0:6C
,I/io.jxcore.node.OutgoingSocketThread( 2879): close
I/io.jxcore.node.OutgoingSocketThread( 2879): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 361
I/io.jxcore.node.OutgoingSocketThread( 2879): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 360
I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing...
,I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 360, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2879): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Outgoing connection, peer with ID 00:F4:6F:30:E0:6C disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 2879): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 361, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 2879): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Outgoing connection, peer with ID 00:F4:6F:30:E0:6C disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:F4:6F:30:E0:6C
,E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 360, name: Sender)
E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 361, name: Receiver)
,I/jxcore-log( 2879): 2015-12-08T16:26:11.988Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2879): 
I/jxcore-log( 2879): ---- round done--------
I/jxcore-log( 2879): 
I/jxcore-log( 2879): do fake peer & start
I/jxcore-log( 2879): 
I/jxcore-log( 2879): Connect to fake peer: F4:F1:E1:5C:3B:E2
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:26:11.988Z SendDataConnector.js: Start called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:26:11.988Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:26:11.988Z SendDataConnector.js: do connect now
I/jxcore-log( 2879): 
I/io.jxcore.node.ConnectionHelper( 2879): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
W/io.jxcore.node.ConnectionHelper( 2879): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Trying to start connecting to null in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnecting: null F4:F1:E1:5C:3B:E2
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Started connecting to null in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 2879): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
I/chromium( 2879): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 00:F4:6F:30:E0:6C done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 2950): bta_jv_rfc_port_to_cb(port_handle:0x1d):jv handle:0x0 not FOUND
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 362)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e527ac rs_disc_pending=1
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e527ac rs_disc_pending=0
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2950): onReceive
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: S5mini-1
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:68, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 68
,W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x44
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:69, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 69
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 362)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect again in 300 ms... (thread ID: 362)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stopServiceDiscovery
,I/wpa_supplicant( 2957): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): Connection timeout
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
,E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:70, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2950): invalid rfc slot id: 70
,W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2950): info:x10
,D/        ( 2950): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2950): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2950): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2950): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 1
E/bt-btif ( 2950): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2950): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2950): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2950): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 0
,D/BluetoothAdapterProperties( 2950): Failed to remove device: F4:F1:E1:5C:3B:E2
,I/BluetoothBondStateMachine( 2950): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2950): StableState(): Entering Off State
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onSocketConnected: Authenticating next: [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onConnectionFailed: Cancelled: Connection timeout
,W/bt-btif ( 2950): new conn_srvc id:26, app_id:1
W/bt-btif ( 2950): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2950): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): start: Starting peer discovery...
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnectionFailed: Cancelled: Connection timeout [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
I/jxcore-log( 2879): 2015-12-08T16:26:33.273Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:26:33.273Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:26:33.273Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2879): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Socket connection succeeded using system decided port, total number of attempts: 2 (thread ID: 362)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Exiting thread (thread ID: 362)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2950): bta_jv_rfc_port_to_cb(port_handle:0x1e):jv handle:0x0 not FOUND
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e52974 rs_disc_pending=0
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 2879): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 2879): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2950): onReceive
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: XT1039
,I/jxcore-log( 2879): 2015-12-08T16:26:38.274Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:26:38.274Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2879): 
,D/btif_config_util( 2950): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,D/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
I/jxcore-log( 2879): 2015-12-08T16:26:43.278Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:26:43.279Z SendDataConnector.js: Connect (retry count 1) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:26:43.279Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:26:43.286Z SendDataConnector.js: do connect now
I/jxcore-log( 2879): 
,I/io.jxcore.node.ConnectionHelper( 2879): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
W/io.jxcore.node.ConnectionHelper( 2879): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Trying to start connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnecting: XT1039 F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Started connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 2879): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 363)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT2148"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT2148 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT2148"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: F4:F1:E1:5C:3B:E2, peer name: motorola-XT1039_PT2148, peer ID: F4:F1:E1:5C:3B:E2, Wi-Fi Direct device name: , Wi-Fi Direct address: f4:f1:e1:5c:43:c8
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Adding peer with ID F4:F1:E1:5C:3B:E2
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT664","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT664 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT664","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: F8:CF:C5:D9:E5:61, peer name: motorola-Nexus 6_PT664, peer ID: F8:CF:C5:D9:E5:61, Wi-Fi Direct device name: Android_50a5, Wi-Fi Direct address: fa:cf:c5:d9:e5:62
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID F8:CF:C5:D9:E5:61 already in the list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5816","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT5816 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5816","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: F8:95:C7:87:3C:51, peer name: LGE-LG-H815_PT5816, peer ID: F8:95:C7:87:3C:51, Wi-Fi Direct device name: , Wi-Fi Direct address: a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:3C:51 already in the list
,W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): Connection timeout
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 2950): info:x10
,D/        ( 2950): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: XT1039
,W/bt-sdp  ( 2950): process_service_search_attr_rsp
,W/bt-btif ( 2950): new conn_srvc id:26, app_id:1
W/bt-btif ( 2950): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2950): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onSocketConnected: Authenticating next: [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 363)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Exiting thread (thread ID: 363)
,W/bt-btif ( 2950): bta_jv_rfc_port_to_cb(port_handle:0x1):jv handle:0x0 not FOUND
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT2378"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT2378 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT2378"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnectionFailed: Cancelled: Connection timeout [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
,I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: 34:FC:EF:11:B1:66, peer name: LGE-Nexus 5_PT2378, peer ID: 34:FC:EF:11:B1:66, Wi-Fi Direct device name: Android_2dc2, Wi-Fi Direct address: 52:55:27:f0:ff:f0
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID 34:FC:EF:11:B1:66 already in the list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
,I/jxcore-log( 2879): 2015-12-08T16:27:05.607Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:27:05.607Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:27:05.608Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2879): 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 2950): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2950): onReceive
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: XT1039
,I/jxcore-log( 2879): 2015-12-08T16:27:10.611Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:27:10.612Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2879): 
,D/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
I/jxcore-log( 2879): 2015-12-08T16:27:15.614Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:27:15.614Z SendDataConnector.js: Connect (retry count 2) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:27:15.614Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:27:15.615Z SendDataConnector.js: do connect now
I/jxcore-log( 2879): 
I/io.jxcore.node.ConnectionHelper( 2879): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Trying to start connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnecting: XT1039 F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Started connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 2879): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 364)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:73, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 73
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:74, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 74
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 364)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect again in 300 ms... (thread ID: 364)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): Connection timeout
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:75, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 75
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onConnectionFailed: Cancelled: Connection timeout
,W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnectionFailed: Cancelled: Connection timeout [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT2148 F4:F1:E1:5C:3B:E2]
I/jxcore-log( 2879): 2015-12-08T16:27:31.386Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:27:31.399Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:27:31.399Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2879): 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): stop: Stopping services
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stopServiceDiscovery
,I/wpa_supplicant( 2957): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1108","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1108","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): Local service added successfully
,I/wpa_supplicant( 2957): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
,I/wpa_supplicant( 2957): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
,W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
,I/jxcore-log( 2879): 2015-12-08T16:27:36.400Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:27:36.400Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2879): 
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:76, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 76
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Exiting thread (thread ID: 364)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): start: Starting peer discovery...
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,D/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
I/jxcore-log( 2879): 2015-12-08T16:27:41.404Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:27:41.405Z SendDataConnector.js: Connect (retry count 3) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:27:41.405Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:27:41.406Z SendDataConnector.js: do connect now
I/jxcore-log( 2879): 
I/io.jxcore.node.ConnectionHelper( 2879): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Trying to start connecting to XT1039 in address F4:F1:E1:5C:3B:E2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnecting: XT1039 F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Started connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 2879): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 365)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 2950): info:x10
,D/        ( 2950): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 2879): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2879): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
D/WifiP2pManager( 2879): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: XT1039
,W/bt-sdp  ( 2950): process_service_search_attr_rsp
,W/bt-btif ( 2950): new conn_srvc id:26, app_id:1
W/bt-btif ( 2950): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2950): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onSocketConnected: Authenticating next: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT2148 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 365)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): onBytesWritten: 77 bytes successfully written (thread ID: 366)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Outgoing connection initialized (*handshake* thread ID: 366)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Exiting thread (thread ID: 365)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Entering thread (ID: 366)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): onBytesRead: Read 81 bytes successfully (thread ID: 366)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Handshake succeeded with [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT2148 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onAuthenticated: Fully connected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT2148 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Exiting thread (ID: 366)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT2148 F4:F1:E1:5C:3B:E2]
I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Outgoing connection, peer ID: F4:F1:E1:5C:3B:E2, name: motorola-XT1039_PT2148, Bluetooth address: F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID F4:F1:E1:5C:3B:E2 already in the list
I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Outgoing socket thread, for peer with ID F4:F1:E1:5C:3B:E2, created successfully
D/io.jxcore.node.ConnectionHelper( 2879): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 2879): Entering thread (ID: 367)
D/io.jxcore.node.OutgoingSocketThread( 2879): Server socket local port: 42375
I/io.jxcore.node.OutgoingSocketThread( 2879): Now accepting connections...
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/io.jxcore.node.ConnectionHelper( 2879): onListeningForIncomingConnections: Outgoing connection is using port 42375 (peer ID: F4:F1:E1:5C:3B:E2)
I/jxcore-log( 2879): 2015-12-08T16:27:42.752Z SendDataConnector.js: CLIENT connected to 42375, error: null
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:27:42.753Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2879): 
,I/io.jxcore.node.OutgoingSocketThread( 2879): Incoming data from address: /127.0.0.1, port: 42375
D/io.jxcore.node.OutgoingSocketThread( 2879): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 2879): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 2879): Exiting thread (ID: 367)
,I/jxcore-log( 2879): 2015-12-08T16:27:42.776Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2879): 
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 368, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 369, name: Receiver)
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,D/        ( 2950): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 2879): 2015-12-08T16:27:43.485Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2879): 
,D/        ( 2950): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:16786
,I/jxcore-log( 2879): 2015-12-08T16:27:43.518Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2879): 
,D/        ( 2950): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14806
,I/jxcore-log( 2879): 2015-12-08T16:27:43.520Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2879): 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1989"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT1989 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1989"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1989"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: 80:01:84:8A:B3:68, peer name: HTC-HTC Desire 820_PT1989, peer ID: 80:01:84:8A:B3:68, Wi-Fi Direct device name: , Wi-Fi Direct address: 82:01:84:6b:e8:5d
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID 80:01:84:8A:B3:68 already in the list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/jxcore-log( 2879): 2015-12-08T16:27:43.716Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2879): 
,I/wpa_supplicant( 2957): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,D/        ( 2950): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2926
,I/jxcore-log( 2879): 2015-12-08T16:27:43.867Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:27:44.026Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:27:44.250Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:27:44.313Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:27:44.474Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:27:44.664Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:27:44.665Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:27:44.691Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:27:44.692Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2879): 
D/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F4:F1:E1:5C:3B:E2
I/io.jxcore.node.OutgoingSocketThread( 2879): close
I/io.jxcore.node.OutgoingSocketThread( 2879): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 369
I/io.jxcore.node.OutgoingSocketThread( 2879): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 368
I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 368, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2879): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Outgoing connection, peer with ID F4:F1:E1:5C:3B:E2 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local output stream...
,I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 2879): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 369, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 2879): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Outgoing connection, peer with ID F4:F1:E1:5C:3B:E2 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Successfully disconnected (peer ID: F4:F1:E1:5C:3B:E2
,E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 368, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 369, name: Receiver)
,I/jxcore-log( 2879): 2015-12-08T16:27:44.729Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2879): 
I/jxcore-log( 2879): ---- round done--------
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): do fake peer & start
I/jxcore-log( 2879): 
I/jxcore-log( 2879): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:27:44.731Z SendDataConnector.js: Start called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:27:44.731Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:27:44.731Z SendDataConnector.js: do connect now
I/jxcore-log( 2879): 
,I/io.jxcore.node.ConnectionHelper( 2879): connect: Trying to connect to peer with ID 58:2A:F7:ED:96:BE
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 58:2A:F7:ED:96:BE
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Trying to start connecting to ALE-L21 in address 58:2A:F7:ED:96:BE
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnecting: ALE-L21 58:2A:F7:ED:96:BE
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Started connecting to ALE-L21 in address 58:2A:F7:ED:96:BE
I/io.jxcore.node.ConnectionHelper( 2879): connect: Connection process successfully started (peer ID: 58:2A:F7:ED:96:BE)
,I/chromium( 2879): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F4:F1:E1:5C:3B:E2 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 2950): bta_jv_rfc_port_to_cb(port_handle:0x7):jv handle:0x0 not FOUND
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect to peer with address 58:2A:F7:ED:96:BE (thread ID: 370)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e52974 rs_disc_pending=1
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2950): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2950): info:x10
,D/        ( 2950): remote version info [58:2a:f7:ed:96:be]: 6, f, 410d
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e52974 rs_disc_pending=0
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: ALE-L21
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=0
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2950): process_service_search_attr_rsp
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1989"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT1989 80:01:84:8A:B3:68]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1989"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1989"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: 80:01:84:8A:B3:68, peer name: HTC-HTC Desire 820_PT1989, peer ID: 80:01:84:8A:B3:68, Wi-Fi Direct device name: , Wi-Fi Direct address: 82:01:84:6b:e8:5d
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID 80:01:84:8A:B3:68 already in the list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,W/bt-btif ( 2950): new conn_srvc id:26, app_id:1
W/bt-btif ( 2950): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2950): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onSocketConnected: Authenticating next: [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT9989 58:2A:F7:ED:96:BE]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 370)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): onBytesWritten: 77 bytes successfully written (thread ID: 371)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Outgoing connection initialized (*handshake* thread ID: 371)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Exiting thread (thread ID: 370)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Entering thread (ID: 371)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): onBytesRead: Read 80 bytes successfully (thread ID: 371)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Handshake succeeded with [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT9989 58:2A:F7:ED:96:BE]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onAuthenticated: Fully connected: [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT9989 58:2A:F7:ED:96:BE]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Exiting thread (ID: 371)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnected: [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT9989 58:2A:F7:ED:96:BE]
I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Outgoing connection, peer ID: 58:2A:F7:ED:96:BE, name: HUAWEI-ALE-L21_PT9989, Bluetooth address: 58:2A:F7:ED:96:BE
,D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 58:2A:F7:ED:96:BE
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID 58:2A:F7:ED:96:BE already in the list
,I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Outgoing socket thread, for peer with ID 58:2A:F7:ED:96:BE, created successfully
D/io.jxcore.node.ConnectionHelper( 2879): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 2879): Entering thread (ID: 372)
,D/io.jxcore.node.OutgoingSocketThread( 2879): Server socket local port: 57704
I/io.jxcore.node.OutgoingSocketThread( 2879): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 2879): onListeningForIncomingConnections: Outgoing connection is using port 57704 (peer ID: 58:2A:F7:ED:96:BE)
I/jxcore-log( 2879): 2015-12-08T16:27:47.582Z SendDataConnector.js: CLIENT connected to 57704, error: null
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:27:47.582Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2879): 
,I/io.jxcore.node.OutgoingSocketThread( 2879): Incoming data from address: /127.0.0.1, port: 57704
D/io.jxcore.node.OutgoingSocketThread( 2879): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 2879): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 2879): Exiting thread (ID: 372)
,I/jxcore-log( 2879): 2015-12-08T16:27:47.586Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2879): 
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 374, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 373, name: Sender)
,D/        ( 2950): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,D/btif_config_util( 2950): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/        ( 2950): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:11836
,W/bt-btm  ( 2950): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e52974 rs_disc_pending=2
,E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2950): onReceive
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: XT1039
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=1
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,I/UsageStatsService(  761): User[0] Flushing usage stats to disk
,I/jxcore-log( 2879): 2015-12-08T16:27:58.039Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:27:58.040Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:27:58.041Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:27:58.042Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:27:58.043Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2879): 
,E/io.jxcore.node.StreamCopyingThread( 2879): Input stream got -1 on read (thread ID: 373, thread name: Sender)
E/io.jxcore.node.OutgoingSocketThread( 2879): The sending thread failed with error: Input stream got -1 on read
W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Outgoing connection, peer with ID 58:2A:F7:ED:96:BE disconnected: Input stream got -1 on read
I/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 58:2A:F7:ED:96:BE
I/io.jxcore.node.OutgoingSocketThread( 2879): close
I/io.jxcore.node.OutgoingSocketThread( 2879): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 374
I/io.jxcore.node.OutgoingSocketThread( 2879): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 373
I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local input stream...
I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 2879): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 374, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 2879): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Outgoing connection, peer with ID 58:2A:F7:ED:96:BE disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:2A:F7:ED:96:BE
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 374, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 373, name: Sender)
,W/bt-btif ( 2950): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=0
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2950): onReceive
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: ALE-L21
,I/jxcore-log( 2879): 2015-12-08T16:28:03.043Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:28:03.043Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2879): 
,D/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Trying to close connection to peer with ID 58:2A:F7:ED:96:BE
E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:2A:F7:ED:96:BE
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Failed to disconnect (peer ID: 58:2A:F7:ED:96:BE), either no such connection or failed to close the connection
I/jxcore-log( 2879): 2015-12-08T16:28:08.045Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:28:08.045Z SendDataConnector.js: Connect (retry count 1) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:28:08.046Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:28:08.046Z SendDataConnector.js: do connect now
I/jxcore-log( 2879): 
I/io.jxcore.node.ConnectionHelper( 2879): connect: Trying to connect to peer with ID 58:2A:F7:ED:96:BE
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 58:2A:F7:ED:96:BE
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Trying to start connecting to ALE-L21 in address 58:2A:F7:ED:96:BE
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnecting: ALE-L21 58:2A:F7:ED:96:BE
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Started connecting to ALE-L21 in address 58:2A:F7:ED:96:BE
I/io.jxcore.node.ConnectionHelper( 2879): connect: Connection process successfully started (peer ID: 58:2A:F7:ED:96:BE)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect to peer with address 58:2A:F7:ED:96:BE (thread ID: 375)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x4  CID 0x44
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:79, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 79
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2950): info:x10
,D/        ( 2950): remote version info [58:2a:f7:ed:96:be]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: ALE-L21
,D/btif_config_util( 2950): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): Connection timeout
,E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:80, failed to find channle,                                       status:1, scn:0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 375)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect again in 300 ms... (thread ID: 375)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onConnectionFailed: Cancelled: Connection timeout
,W/bt-btif ( 2950): invalid rfc slot id: 80
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1108","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1108","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onIsDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnectionFailed: Cancelled: Connection timeout [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT9989 58:2A:F7:ED:96:BE]
,I/wpa_supplicant( 2957): P2P-FIND-STOPPED 
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
,I/jxcore-log( 2879): 2015-12-08T16:28:48.123Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 58:2A:F7:ED:96:BE failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:28:48.123Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 58:2A:F7:ED:96:BE failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:28:48.123Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2879): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stopServiceDiscovery
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
,I/wpa_supplicant( 2957): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Exiting thread (thread ID: 375)
,E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2950): onReceive
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: ALE-L21
,I/jxcore-log( 2879): 2015-12-08T16:28:53.123Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:28:53.124Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2879): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): start: Starting peer discovery...
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: Android_63cc 82:01:84:6b:e8:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 2879): Ignored { when=-9ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
D/WifiP2pManager( 2879): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT664","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT664 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT664","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: F8:CF:C5:D9:E5:61, peer name: motorola-Nexus 6_PT664, peer ID: F8:CF:C5:D9:E5:61, Wi-Fi Direct device name: , Wi-Fi Direct address: fa:cf:c5:d9:e5:62
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID F8:CF:C5:D9:E5:61 already in the list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,D/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Trying to close connection to peer with ID 58:2A:F7:ED:96:BE
,E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:2A:F7:ED:96:BE
,D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Failed to disconnect (peer ID: 58:2A:F7:ED:96:BE), either no such connection or failed to close the connection
,I/jxcore-log( 2879): 2015-12-08T16:28:58.145Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:28:58.149Z SendDataConnector.js: Connect (retry count 2) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:28:58.150Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:28:58.153Z SendDataConnector.js: do connect now
I/jxcore-log( 2879): 
,I/io.jxcore.node.ConnectionHelper( 2879): connect: Trying to connect to peer with ID 58:2A:F7:ED:96:BE
,D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 58:2A:F7:ED:96:BE
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Trying to start connecting to ALE-L21 in address 58:2A:F7:ED:96:BE
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnecting: ALE-L21 58:2A:F7:ED:96:BE
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Started connecting to ALE-L21 in address 58:2A:F7:ED:96:BE
,I/io.jxcore.node.ConnectionHelper( 2879): connect: Connection process successfully started (peer ID: 58:2A:F7:ED:96:BE)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect to peer with address 58:2A:F7:ED:96:BE (thread ID: 376)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT9640","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9640 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT9640","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: E0:DB:10:1F:C9:5E, peer name: samsung-SM-N9005_PT9640, peer ID: E0:DB:10:1F:C9:5E, Wi-Fi Direct device name: , Wi-Fi Direct address: ea:50:8b:de:28:a3
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID E0:DB:10:1F:C9:5E already in the list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,W/bt-btif ( 2950): info:x10
,D/        ( 2950): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: ALE-L21
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT333","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT333 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT333","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:76:27, peer name: samsung-SM-A300FU_PT333, peer ID: 08:EC:A9:50:76:27, Wi-Fi Direct device name: , Wi-Fi Direct address: 0a:ec:a9:50:76:28
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:76:27 already in the list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,W/bt-sdp  ( 2950): process_service_search_attr_rsp
,W/bt-btif ( 2950): new conn_srvc id:26, app_id:1
W/bt-btif ( 2950): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2950): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onSocketConnected: Authenticating next: [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT9989 58:2A:F7:ED:96:BE]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 376)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): onBytesWritten: 77 bytes successfully written (thread ID: 377)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Outgoing connection initialized (*handshake* thread ID: 377)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Exiting thread (thread ID: 376)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Entering thread (ID: 377)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): onBytesRead: Read 80 bytes successfully (thread ID: 377)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Handshake succeeded with [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT9989 58:2A:F7:ED:96:BE]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onAuthenticated: Fully connected: [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT9989 58:2A:F7:ED:96:BE]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Exiting thread (ID: 377)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnected: [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT9989 58:2A:F7:ED:96:BE]
I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Outgoing connection, peer ID: 58:2A:F7:ED:96:BE, name: HUAWEI-ALE-L21_PT9989, Bluetooth address: 58:2A:F7:ED:96:BE
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 58:2A:F7:ED:96:BE
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID 58:2A:F7:ED:96:BE already in the list
I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Outgoing socket thread, for peer with ID 58:2A:F7:ED:96:BE, created successfully
D/io.jxcore.node.ConnectionHelper( 2879): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 2879): Entering thread (ID: 378)
,D/io.jxcore.node.OutgoingSocketThread( 2879): Server socket local port: 60218
I/io.jxcore.node.OutgoingSocketThread( 2879): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 2879): onListeningForIncomingConnections: Outgoing connection is using port 60218 (peer ID: 58:2A:F7:ED:96:BE)
I/jxcore-log( 2879): 2015-12-08T16:29:00.444Z SendDataConnector.js: CLIENT connected to 60218, error: null
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:00.445Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2879): 
,I/io.jxcore.node.OutgoingSocketThread( 2879): Incoming data from address: /127.0.0.1, port: 60218
D/io.jxcore.node.OutgoingSocketThread( 2879): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 2879): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 2879): Exiting thread (ID: 378)
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 380, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 379, name: Sender)
,I/jxcore-log( 2879): 2015-12-08T16:29:00.513Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2879): 
,D/        ( 2950): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 2879): 2015-12-08T16:29:01.161Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:01.537Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2879): 
,D/        ( 2950): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13816
,I/jxcore-log( 2879): 2015-12-08T16:29:01.815Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:01.910Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2879): 
,D/btif_config_util( 2950): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/        ( 2950): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 2879): 2015-12-08T16:29:02.239Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:02.293Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:02.329Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:02.524Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:02.724Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:02.907Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:29:02.908Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:02.929Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:29:02.930Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2879): 
D/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Trying to close connection to peer with ID 58:2A:F7:ED:96:BE
I/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 58:2A:F7:ED:96:BE
I/io.jxcore.node.OutgoingSocketThread( 2879): close
I/io.jxcore.node.OutgoingSocketThread( 2879): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 380
I/io.jxcore.node.OutgoingSocketThread( 2879): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 379
I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 379, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2879): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Outgoing connection, peer with ID 58:2A:F7:ED:96:BE disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 2879): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 2879): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 380, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 2879): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Outgoing connection, peer with ID 58:2A:F7:ED:96:BE disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Successfully disconnected (peer ID: 58:2A:F7:ED:96:BE
,E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:2A:F7:ED:96:BE
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 379, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:2A:F7:ED:96:BE
,D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 380, name: Receiver)
,W/bt-btif ( 2950): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,I/jxcore-log( 2879): 2015-12-08T16:29:02.986Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2879): 
I/jxcore-log( 2879): ---- round done--------
I/jxcore-log( 2879): 
I/jxcore-log( 2879): do fake peer & start
I/jxcore-log( 2879): 
I/jxcore-log( 2879): Connect to fake peer: 7C:F9:0E:37:96:AB
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:29:02.987Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:29:02.987Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:29:02.987Z SendDataConnector.js: do connect now
I/jxcore-log( 2879): 
I/io.jxcore.node.ConnectionHelper( 2879): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
W/io.jxcore.node.ConnectionHelper( 2879): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Trying to start connecting to null in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnecting: null 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Started connecting to null in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 2879): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/chromium( 2879): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 58:2A:F7:ED:96:BE done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 381)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=1
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=0
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2950): onReceive
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: ALE-L21
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 2950): info:x10
,D/        ( 2950): remote version info [00:f4:6f:30:e0:6c]: 6, 10f, 608
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: S5mini-1
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e527ac rs_disc_pending=0
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2950): new conn_srvc id:26, app_id:255
W/bt-btif ( 2950): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2950): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Incoming connection initialized (thread ID: 382)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Entering thread (ID: 382)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): onBytesRead: Read 80 bytes successfully (thread ID: 382)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Got valid identity from [00:F4:6F:30:E0:6C samsung-SM-G800F_PT26 00:F4:6F:30:E0:6C]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): onBytesWritten: 77 bytes successfully written (thread ID: 382)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): removeThreadFromList: Removing thread with ID 382
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Handshake thread disposed (thread ID: 382)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onIncomingConnectionConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT26 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Exiting thread (ID: 382)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT26 00:F4:6F:30:E0:6C]
,I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Incoming connection, peer ID: 00:F4:6F:30:E0:6C, name: samsung-SM-G800F_PT26, Bluetooth address: 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
,I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Incoming socket thread, for peer with ID 00:F4:6F:30:E0:6C, created successfully
,D/io.jxcore.node.ConnectionHelper( 2879): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 2879): Entering thread (ID: 383)
,I/jxcore-log( 2879): 2015-12-08T16:29:13.292Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2879): 
,I/io.jxcore.node.IncomingSocketThread( 2879): Local host address: localhost/127.0.0.1, port: 46178
D/io.jxcore.node.IncomingSocketThread( 2879): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 2879): startStreamCopyingThreads: OK
,D/io.jxcore.node.IncomingSocketThread( 2879): Exiting thread (ID: 383)
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 384, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 385, name: Receiver)
,I/jxcore-log( 2879): 2015-12-08T16:29:14.075Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:14.114Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:14.121Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:14.160Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:14.170Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:14.179Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:14.198Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:14.237Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:14.252Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:29:14.254Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:14.277Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:14.315Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:14.320Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:14.331Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:14.355Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:14.393Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:14.413Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:14.442Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:14.457Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:14.498Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:14.535Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:14.585Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:14.594Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:14.635Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:14.642Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:14.687Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:14.734Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:14.786Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:14.822Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:14.860Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:14.866Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:14.876Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:14.912Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:14.954Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:29:14.956Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:14.966Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:15.007Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:15.114Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:15.158Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:15.241Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:15.258Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 2879): 
,D/btif_config_util( 2950): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2879): 2015-12-08T16:29:15.566Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:29:15.574Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2879): 
,W/bt-btif ( 2950): invalid rfc slot id: 63
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 385, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 2879): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Incoming connection, peer with ID 00:F4:6F:30:E0:6C disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1,
I/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 383
I/io.jxcore.node.IncomingSocketThread( 2879): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 385
I/io.jxcore.node.IncomingSocketThread( 2879): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 384
I/io.jxcore.node.IncomingSocketThread( 2879): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 384, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 2879): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Incoming connection, peer with ID 00:F4:6F:30:E0:6C disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.IncomingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 2879): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.IncomingSocketThread( 2879): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 384, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 385, name: Receiver)
,I/jxcore-log( 2879): 2015-12-08T16:29:15.689Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2879): 
,W/bt-rfcomm( 2950): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
W/bt-rfcomm( 2950): RFCOMM_DisconnectInd LCID:0x48
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): Connection timeout
,E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2950): onReceive
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: S5mini-1
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/EventLogService( 1558): Aggregate from 1449590246713 (log), 1449590246713 (data)
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x8  CID 0x46
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:82, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2950): invalid rfc slot id: 82
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2950): info:x10
,D/        ( 2950): remote version info [f4:f1:e1:5c:3b:e2]: 6, f, 410d
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: XT1039
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e52974 rs_disc_pending=0
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x8  CID 0x4a
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:84, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 84
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onConnectionFailed: Cancelled: Connection timeout
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 381)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect again in 300 ms... (thread ID: 381)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onIsDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1108","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1108","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/wpa_supplicant( 2957): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2283","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2283 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2283","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnectionFailed: Cancelled: Connection timeout [7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB]
,W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:75:41, peer name: samsung-SM-A300FU_PT2283, peer ID: 08:EC:A9:50:75:41, Wi-Fi Direct device name: , Wi-Fi Direct address: 0a:ec:a9:50:75:42
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:75:41 already in the list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
I/jxcore-log( 2879): 2015-12-08T16:30:07.658Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:30:07.658Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:30:07.658Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2879): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery started successfully
,I/wpa_supplicant( 2957): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): restart: Restarting...
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Exiting thread (thread ID: 381)
,W/bt-btif ( 2950): new conn_srvc id:26, app_id:255
W/bt-btif ( 2950): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2950): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Incoming connection initialized (thread ID: 386)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Entering thread (ID: 386)
,W/bt-btif ( 2950): invalid rfc slot id: 83
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Disconnected: bt socket closed, read return: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): removeThreadFromList: Removing thread with ID 386
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Handshake failed (thread ID: 386)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Exiting thread (ID: 386)
,W/bt-rfcomm( 2950): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
W/bt-rfcomm( 2950): RFCOMM_DisconnectInd LCID:0x4c
,D/btif_config_util( 2950): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2950): onReceive
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: XT1039
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): startServiceDiscovery: Invalid state, try calling restart()
,I/jxcore-log( 2879): 2015-12-08T16:30:12.659Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:30:12.659Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2879): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2879): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2879): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully,
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,D/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:37:96:AB), either no such connection or failed to close the connection
I/jxcore-log( 2879): 2015-12-08T16:30:17.666Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:30:17.667Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:30:17.667Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:30:17.668Z SendDataConnector.js: do connect now
I/jxcore-log( 2879): 
I/io.jxcore.node.ConnectionHelper( 2879): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
W/io.jxcore.node.ConnectionHelper( 2879): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Trying to start connecting to null in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnecting: null 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Started connecting to null in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 2879): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 387)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2950): info:x10
,D/        ( 2950): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: XT1039
,E/bt-btm  ( 2950): tBTM_SEC_DEV:0xa3e52974 rs_disc_pending=0
W/bt-btif ( 2950): bta_dm_check_av:0
,W/bt-btif ( 2950): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2950): new conn_srvc id:26, app_id:255
W/bt-btif ( 2950): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2950): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Incoming connection initialized (thread ID: 388)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Entering thread (ID: 388)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): onBytesRead: Read 81 bytes successfully (thread ID: 388)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Got valid identity from [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT2148 F4:F1:E1:5C:3B:E2]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): onBytesWritten: 77 bytes successfully written (thread ID: 388)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): removeThreadFromList: Removing thread with ID 388
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Handshake thread disposed (thread ID: 388)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onIncomingConnectionConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT2148 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2879): Exiting thread (ID: 388)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT2148 F4:F1:E1:5C:3B:E2]
I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Incoming connection, peer ID: F4:F1:E1:5C:3B:E2, name: motorola-XT1039_PT2148, Bluetooth address: F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID F4:F1:E1:5C:3B:E2 already in the list
I/io.jxcore.node.ConnectionHelper( 2879): onConnected: Incoming socket thread, for peer with ID F4:F1:E1:5C:3B:E2, created successfully
D/io.jxcore.node.ConnectionHelper( 2879): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 2879): Entering thread (ID: 389)
,I/jxcore-log( 2879): 2015-12-08T16:30:20.943Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2879): 
,I/io.jxcore.node.IncomingSocketThread( 2879): Local host address: localhost/127.0.0.1, port: 46178
D/io.jxcore.node.IncomingSocketThread( 2879): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 2879): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 2879): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 2879): Exiting thread (ID: 389)
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 391, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2879): Entering thread (ID: 390, name: Sender)
,I/jxcore-log( 2879): 2015-12-08T16:30:21.941Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2879): 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 2879): 2015-12-08T16:30:22.108Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:22.183Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:22.191Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:22.254Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:22.264Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:22.275Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:22.318Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:22.345Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:22.355Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:22.388Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:22.510Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:22.619Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:22.629Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:22.636Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:22.675Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:22.687Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:22.727Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:22.736Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:22.890Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:22.897Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:22.937Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:22.948Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:22.953Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:23.076Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:23.113Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:23.142Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:23.151Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 2879): 
,D/btif_config_util( 2950): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2879): 2015-12-08T16:30:23.173Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:23.281Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:23.292Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:23.327Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:23.334Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:23.341Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:23.442Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:23.488Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:23.500Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:23.527Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:23.611Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:23.622Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:23.709Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:23.721Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:23.726Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:23.755Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:23.767Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:23.802Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:23.847Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:23.853Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:30:23.893Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2879): 
,W/bt-btif ( 2950): invalid rfc slot id: 85
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 391, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 2879): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Incoming connection, peer with ID F4:F1:E1:5C:3B:E2 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 389
I/io.jxcore.node.IncomingSocketThread( 2879): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 391
I/io.jxcore.node.IncomingSocketThread( 2879): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread( 2879): doStop: Thread ID: 390
I/io.jxcore.node.IncomingSocketThread( 2879): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 2879): Either failed to read from the output stream or write to the input stream (thread ID: 390, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 2879): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2879): onDisconnected: Incoming connection, peer with ID F4:F1:E1:5C:3B:E2 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.IncomingSocketThread( 2879): closeLocalSocketAndStreams: Closing the local output stream...
,I/io.jxcore.node.IncomingSocketThread( 2879): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 2879): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 390, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2879): Exiting thread (ID: 391, name: Receiver)
,I/jxcore-log( 2879): 2015-12-08T16:30:24.052Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2879): 
,W/bt-rfcomm( 2950): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
W/bt-rfcomm( 2950): RFCOMM_DisconnectInd LCID:0x42
,E/bt-btm  ( 2950): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2950): onReceive
,I/BTConnectionReceiver( 1341): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1341): Bluetooth Device Name: XT1039
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): Connection timeout
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x22  CID 0x4f
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:86, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 86
,W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x8  CID 0x43
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:88, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 88
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Exiting thread (thread ID: 387)
,I/jxcore-log( 2879): timeout now
I/jxcore-log( 2879): 
I/jxcore-log( 2879): dun
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): weAreDoneNow , resultArray.length: 9
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): done, now sending data to server
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector sendData called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): -- RESULT DATA {"name:":"LGE-Nexus 5_PT1108","time":1000325,"result":"TIMEOUT","sendList":[{"name":"E0:DB:10:14:E2:C0","time":40861,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":4508,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":3415,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"80:01:84:8A:B3:68","time":68432,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:B1:66","time":15840,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"58:3F:54:73:64:C0","time":11420,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"00:F4:6F:30:E0:6C","time":9600,"result":"OK","connections":1,"tryCount":1
I/jxcore-log( 2879): sendList : 100% : 92680 ms, 99% : 92680 ms, 95 : 92680 ms, 90% : 78178 ms.
I/jxcore-log( 2879): 
I/jxcore-log( 2879): Result count 9, range 3415 ms to  92680 ms.
I/jxcore-log( 2879): 
I/jxcore-log( 2879): sendList failed peers count : 4 [30.76923076923077 %]
I/jxcore-log( 2879): 
I/jxcore-log( 2879): - Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
I/jxcore-log( 2879): 
I/jxcore-log( 2879): - Peer ID : 90:E7:C4:F6:69:77, Tried : 1
I/jxcore-log( 2879): 
I/jxcore-log( 2879): - Peer ID : 08:EC:A9:50:76:27, Tried : 1
I/jxcore-log( 2879): 
I/jxcore-log( 2879): - Peer ID : 44:80:EB:7B:5A:05, Tried : 1
I/jxcore-log( 2879): 
I/jxcore-log( 2879): sendList never tried peers count : 9 [40.90909090909091 %]
I/jxcore-log( 2879): 
I/jxcore-log( 2879): - Peer ID : 7C:F9:0E:34:8A:A0
I/jxcore-log( 2879): 
I/jxcore-log( 2879): - Peer ID : B0:C5:59:3F:75:69
I/jxcore-log( 2879): 
I/jxcore-log( 2879): - Peer ID : B4:CE:F6:AB:A4:6A
I/jxcore-log( 2879): 
I/jxcore-log( 2879): - Peer ID : F8:CF:C5:D9:E5:61
I/jxcore-log( 2879): 
I/jxcore-log( 2879): - Peer ID : 7C:F9:0E:51:18:22
I/jxcore-log( 2879): 
I/jxcore-log( 2879): - Peer ID : F8:95:C7:87:3C:51
I/jxcore-log( 2879): 
I/jxcore-log( 2879): - Peer ID : 38:94:96:B5:06:DC
I/jxcore-log( 2879): 
I/jxcore-log( 2879): - Peer ID : E0:DB:10:1F:C9:5E
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): - Peer ID : 34:FC:EF:9D:93:0B
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:31:24.471Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2879): 
D/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:37:96:AB), either no such connection or failed to close the connection
I/jxcore-log( 2879): 2015-12-08T16:31:24.472Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2879): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1108","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1108","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT9428","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9428 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT9428","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT731","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT731 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT731","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnectionFailed: Cancelled: Connection timeout [7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB]
I/chromium( 2879): [INFO:CONSOLE(63)] "logCallback *** TIMEOUT ***", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 2879): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: 7C:F9:0E:51:18:22, peer name: samsung-SM-A500FU_PT9428, peer ID: 7C:F9:0E:51:18:22, Wi-Fi Direct device name: Thali Test (Galaxy A5), Wi-Fi Direct address: 7e:f9:0e:51:18:23
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:51:18:22 already in the list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: 44:80:EB:7B:5A:05, peer name: motorola-XT1072_PT731, peer ID: 44:80:EB:7B:5A:05, Wi-Fi Direct device name: XT1072_23d5, Wi-Fi Direct address: 44:80:eb:7b:5a:07
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID 44:80:EB:7B:5A:05 already in the list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
I/jxcore-log( 2879): 2015-12-08T16:31:24.485Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:31:24.485Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:31:24.485Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2879): 
,I/wpa_supplicant( 2957): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
,I/wpa_supplicant( 2957): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,I/jxcore-log( 2879): 2015-12-08T16:31:29.486Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:31:29.486Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2879): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 2879): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:37:96:AB), either no such connection or failed to close the connection
,I/jxcore-log( 2879): 2015-12-08T16:31:34.494Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:31:34.495Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:31:34.496Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:31:34.496Z SendDataConnector.js: do connect now
I/jxcore-log( 2879): 
I/io.jxcore.node.ConnectionHelper( 2879): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
W/io.jxcore.node.ConnectionHelper( 2879): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Trying to start connecting to null in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnecting: null 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Started connecting to null in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 2879): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 392)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): Connection timeout
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x8  CID 0x40
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:89, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 89
,W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,W/bt-smp  ( 2950): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2950): Plain text(LSB ~ MSB) = 98 ab 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2950): Encrypted text(LSB ~ MSB) = 3c a2 92 bd e4 7c a5 6c 73 56 9f 14 b3 98 4e 95 
W/bt-btm  ( 2950): Stopping oneshot timer
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x8  CID 0x44
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:90, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 90
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Exiting thread (thread ID: 392)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT664","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT664 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1108","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1108","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): start: Starting peer discovery...
,I/wpa_supplicant( 2957): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT333","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT333 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT2148"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT2148 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5816","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT5816 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT731","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT731 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
,I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnectionFailed: Cancelled: Connection timeout [7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB]
,I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: F8:CF:C5:D9:E5:61, peer name: motorola-Nexus 6_PT664, peer ID: F8:CF:C5:D9:E5:61, Wi-Fi Direct device name: Android_50a5, Wi-Fi Direct address: fa:cf:c5:d9:e5:62
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID F8:CF:C5:D9:E5:61 already in the list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:76:27, peer name: samsung-SM-A300FU_PT333, peer ID: 08:EC:A9:50:76:27, Wi-Fi Direct device name: Thali Test (Galaxy A3), Wi-Fi Direct address: 0a:ec:a9:50:76:28
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:76:27 already in the list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: F4:F1:E1:5C:3B:E2, peer name: motorola-XT1039_PT2148, peer ID: F4:F1:E1:5C:3B:E2, Wi-Fi Direct device name: XT1039_8c05, Wi-Fi Direct address: f4:f1:e1:5c:43:c8
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID F4:F1:E1:5C:3B:E2 already in the list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: F8:95:C7:87:3C:51, peer name: LGE-LG-H815_PT5816, peer ID: F8:95:C7:87:3C:51, Wi-Fi Direct device name: G4-1, Wi-Fi Direct address: a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:3C:51 already in the list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: 44:80:EB:7B:5A:05, peer name: motorola-XT1072_PT731, peer ID: 44:80:EB:7B:5A:05, Wi-Fi Direct device name: XT1072_23d5, Wi-Fi Direct address: 44:80:eb:7b:5a:07
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID 44:80:EB:7B:5A:05 already in the list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
I/jxcore-log( 2879): 2015-12-08T16:32:38.689Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:32:38.689Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:32:38.689Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2879): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stopServiceDiscovery
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: XT1039_8c05 f4:f1:e1:5c:43:c8
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: XT1039_8c05 f4:f1:e1:5c:43:c8
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): startServiceDiscovery: Invalid state, try calling restart()
,I/jxcore-log( 2879): 2015-12-08T16:32:43.690Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:32:43.692Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2879): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery started successfully
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 4: XT1039_8c05 f4:f1:e1:5c:43:c8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 4: XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 2879): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
D/WifiP2pManager( 2879): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 4: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 5: Android_50a5 fa:cf:c5:d9:e5:62
,D/WifiP2pManager( 2879): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 2957): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,D/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:37:96:AB), either no such connection or failed to close the connection
I/jxcore-log( 2879): 2015-12-08T16:32:48.696Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:32:48.697Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:32:48.698Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:32:48.698Z SendDataConnector.js: do connect now
I/jxcore-log( 2879): 
I/io.jxcore.node.ConnectionHelper( 2879): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
,W/io.jxcore.node.ConnectionHelper( 2879): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Trying to start connecting to null in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnecting: null 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Started connecting to null in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 2879): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 393)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): Connection timeout
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x22  CID 0x45
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:91, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 91
,W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x8  CID 0x49
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:92, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 92
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 393)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect again in 300 ms... (thread ID: 393)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stopServiceDiscovery
,I/wpa_supplicant( 2957): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1108","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1108","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onIsDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnectionFailed: Cancelled: Connection timeout [7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB]
,W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): restart: Restarting...
,I/jxcore-log( 2879): 2015-12-08T16:33:55.489Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:33:55.489Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:33:55.490Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2879): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
,I/wpa_supplicant( 2957): P2P-FIND-STOPPED 
I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): restart: Restarting...
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
,W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Exiting thread (thread ID: 393)
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: Android_63cc 82:01:84:6b:e8:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: Android_63cc 82:01:84:6b:e8:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): startServiceDiscovery: Invalid state, try calling restart()
,I/jxcore-log( 2879): 2015-12-08T16:34:00.490Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:34:00.492Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2879): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): start: Starting peer discovery...
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 2879): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 2879): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT71","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT71 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT71","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: 58:3F:54:73:64:C0, peer name: LGE-LG-D855_PT71, peer ID: 58:3F:54:73:64:C0, Wi-Fi Direct device name: G3-1, Wi-Fi Direct address: 02:9a:02:7b:60:ac
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID 58:3F:54:73:64:C0 already in the list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5816","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT5816 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5816","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: F8:95:C7:87:3C:51, peer name: LGE-LG-H815_PT5816, peer ID: F8:95:C7:87:3C:51, Wi-Fi Direct device name: , Wi-Fi Direct address: a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:3C:51 already in the list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT2148"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT2148 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT2148"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: F4:F1:E1:5C:3B:E2, peer name: motorola-XT1039_PT2148, peer ID: F4:F1:E1:5C:3B:E2, Wi-Fi Direct device name: , Wi-Fi Direct address: f4:f1:e1:5c:43:c8
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID F4:F1:E1:5C:3B:E2 already in the list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,D/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
,D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:37:96:AB), either no such connection or failed to close the connection
I/jxcore-log( 2879): 2015-12-08T16:34:05.495Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:34:05.496Z SendDataConnector.js: Connect (retry count 4) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:34:05.497Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:34:05.497Z SendDataConnector.js: do connect now
I/jxcore-log( 2879): 
I/io.jxcore.node.ConnectionHelper( 2879): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 2879): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
W/io.jxcore.node.ConnectionHelper( 2879): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Trying to start connecting to null in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnecting: null 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): connect: Started connecting to null in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 2879): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 394)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2879): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT2378"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT2378 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT2378"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: 34:FC:EF:11:B1:66, peer name: LGE-Nexus 5_PT2378, peer ID: 34:FC:EF:11:B1:66, Wi-Fi Direct device name: Android_2dc2, Wi-Fi Direct address: 52:55:27:f0:ff:f0
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID 34:FC:EF:11:B1:66 already in the list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): Connection timeout
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x22  CID 0x47
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:93, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2950): invalid rfc slot id: 93
,W/BluetoothAdapter( 2879): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2950): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2950): SDP - Rcvd conn cnf with error: 0x8  CID 0x41
E/bt-btif ( 2950): DISCOVERY_COMP_EVT slot id:94, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2950): invalid rfc slot id: 94
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): cancel: Connection timeout
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2879): Exiting thread (thread ID: 394)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): stop: Stopping services
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stopServiceDiscovery
,I/wpa_supplicant( 2957): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1108","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1108","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT333","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT333 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT333","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT9640","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9640 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT9640","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnectionFailed: Cancelled: Connection timeout [7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB]
,W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): restart: Restarting...
,I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:76:27, peer name: samsung-SM-A300FU_PT333, peer ID: 08:EC:A9:50:76:27, Wi-Fi Direct device name: Thali Test (Galaxy A3), Wi-Fi Direct address: 0a:ec:a9:50:76:28
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:76:27 already in the list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: E0:DB:10:1F:C9:5E, peer name: samsung-SM-N9005_PT9640, peer ID: E0:DB:10:1F:C9:5E, Wi-Fi Direct device name: , Wi-Fi Direct address: ea:50:8b:de:28:a3
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID E0:DB:10:1F:C9:5E already in the list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
I/jxcore-log( 2879): 2015-12-08T16:35:12.292Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:35:12.292Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2879): 
I/jxcore-log( 2879): 2015-12-08T16:35:12.292Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2879): 
D/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
E/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 2879): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2879): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:37:96:AB), either no such connection or failed to close the connection
I/jxcore-log( 2879): 2015-12-08T16:35:12.293Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2879): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
,I/wpa_supplicant( 2957): P2P-FIND-STOPPED 
I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): restart: Restarting...
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 6 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 4: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 5: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 4: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 5: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 4: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 5: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 4: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 5: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 4: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 5: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): start: Starting peer discovery...
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 8 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 4: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 7: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 8: S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2879): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 8 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 4: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 7: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 8: S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2879): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 8 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 4: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 7: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 8: S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2879): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 8 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 4: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 7: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 8: S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2879): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 8 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 4: Android_2dc2 52:55:27:f0:ff:f0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 7: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 8: S5mini-1 02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 8 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 4: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 7: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 8: S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2879): Ignored { when=-12ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
D/WifiP2pManager( 2879): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 10 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 5: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 9: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 10: S5mini-1 02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 10 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 5: Android_2dc2 52:55:27:f0:ff:f0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 9: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 10: S5mini-1 02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: 10 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 5: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 9: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onP2pDeviceListChanged: Peer 10: S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2879): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,D/WifiP2pManager( 2879): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,D/WifiP2pManager( 2879): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2957): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2957): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2957): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1989"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT1989 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: 80:01:84:8A:B3:68, peer name: HTC-HTC Desire 820_PT1989, peer ID: 80:01:84:8A:B3:68, Wi-Fi Direct device name: , Wi-Fi Direct address: 82:01:84:6b:e8:5d
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID 80:01:84:8A:B3:68 already in the list
W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1989"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1989"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1989"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1989"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1989"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1989"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1989"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1989"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/wpa_supplicant( 2957): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2957): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2957): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2957): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 2957): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1989"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Resolved peer properties: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT1989 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1989"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1989"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1989"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1989"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1989"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1989"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1989"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1989"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2879): onPeerDiscovered: Bluetooth address: 80:01:84:8A:B3:68, peer name: HTC-HTC Desire 820_PT1989, peer ID: 80:01:84:8A:B3:68, Wi-Fi Direct device name: , Wi-Fi Direct address: 82:01:84:6b:e8:5d
I/io.jxcore.node.ConnectionHelper( 2879): addNewPeerToListAndNotify: Peer with ID 80:01:84:8A:B3:68 already in the list
,W/io.jxcore.node.ConnectionHelper( 2879): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/jxcore-log( 2879): DBG, CoordinatorConnector command called
I/jxcore-log( 2879): 
I/jxcore-log( 2879): command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): stop tests now !
I/jxcore-log( 2879): 
I/jxcore-log( 2879): stop current!
I/jxcore-log( 2879): 
I/jxcore-log( 2879): testSendData stopped
I/jxcore-log( 2879): 
I/io.jxcore.node.ConnectionHelper( 2879): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2879): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2879): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2879): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): stopServiceDiscovery
,I/wpa_supplicant( 2957): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 2957): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): setState: NOT_INITIALIZED
,I/jxcore-log( 2879): StopBroadcasting went ok
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): 2015-12-08T16:35:44.458Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 2879): 
I/chromium( 2879): [INFO:CONSOLE(63)] "logCallback stop", source: file:///android_asset/www/js/thali_main.js (63)
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2879): onConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2879): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2879): Peer discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 2879): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 2879): onConnectionManagerStateChanged: NOT_INITIALIZED
,I/jxcore-log( 2879): DBG, CoordinatorConnector command called
I/jxcore-log( 2879): 
I/jxcore-log( 2879): command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"F8:95:C7:87:85:54\",\"time\":3415,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"08:EC:A9:50:75:41\",\"time\":4508,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"00:F4:6F:30:E0:6C\",\"time\":9600,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"58:3F:54:73:64:C0\",\"time\":11420,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"34:FC:EF:11:B1:66\",\"time\":15840,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"E0:DB:10:14:E2:C0\",\"time\":40861,\"result\":\"OK\",\"connections\":2,\"tryCount\":1,\"doneRounds\":1,\"dat
I/jxcore-log( 2879): ****TEST TOOK:  ms ****
I/jxcore-log( 2879): 
I/jxcore-log( 2879): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2879): 
I/jxcore-log( 2879): stop tests now !
I/jxcore-log( 2879): 
I/jxcore-log( 2879): end, event received
I/jxcore-log( 2879): 
I/jxcore-log( 2879): CoordinatorConnector close called
I/jxcore-log( 2879): 
,I/jxcore-log( 2879): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 2879): 
I/jxcore-log( 2879): The Coordinator has disconnected!
I/jxcore-log( 2879): 
I/jxcore-log( 2879): The Coordinator has closed!
I/jxcore-log( 2879): 
I/jxcore-log( 2879): stop tests now !
I/jxcore-log( 2879): 
I/jxcore-log( 2879): turning Radios off
I/jxcore-log( 2879): 
I/jxcore-log( 2879): Toggling radios to false
I/jxcore-log( 2879): 
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  761): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@5b09185 mBinding = false
,D/BluetoothManagerService(  761): Message: 2
D/BluetoothManagerService(  761): Sending off request.
,D/BluetoothAdapterState( 2950): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 2950): Setting state to 13
I/BluetoothAdapterState( 2950): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterProperties( 2950): onBluetoothDisable()
I/BluetoothAdapterState( 2950): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 2950): Scan Mode:20
,D/BluetoothAdapterState( 2950): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,V/BluetoothMapMasInstance( 2950): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 2950): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 2950): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 2950): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 2950): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 2950): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 2950): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 2950): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,E/BtOppRfcommListener( 2950): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/btif_config_util( 2950): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2950): bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
,W/bt-l2cap( 2950): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2950): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothManagerService(  761): Message: 60
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  761): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 2950): onReceive
D/BluetoothMapService( 2950): STATE_TURNING_OFF
V/BluetoothMapService( 2950): Handler(): got msg=4
D/BluetoothMapService( 2950): MAP Service closeService in
D/BluetoothMapMasInstance( 2950): MAP Service shutdown
V/BluetoothMapService( 2950): MAP Service closeService out
,I/BtOppRfcommListener( 2950): stopping Accept Thread
,I/BtOppRfcommListener( 2950): BluetoothSocket listen thread finished
,D/WifiService(  761): setWifiEnabled: false pid=2879, uid=10270
E/WifiService(  761): Invoking mWifiStateMachine.setWifiEnabled
,W/ContextImpl( 3830): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  761): Message: 30
I/jxcore-log( 2879): Radios toggled
I/jxcore-log( 2879): 
I/chromium( 2879): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
,E/WifiStateMachine(  761): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  761): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
D/BluetoothManagerService(  761): Message: 30
,D/LocalBluetoothProfileManager( 3830): Adding local MAP profile
D/BluetoothMap( 3830): Create BluetoothMap proxy object
,D/bt_userial( 2950): RX termination
W/bt_userial( 2950): select_read return size <=0:-1, exiting userial_read_thread
,D/bt_userial( 2950): Leaving userial_read_thread()
W/bt-btif ( 2950): ag scb idx 1 not allocated
E/bt-btif ( 2950): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 2950): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2950): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2950): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2950): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2950): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2950): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial( 2950): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 2950): hw_epilog_process
I/bt_userial_vendor( 2950): device fd = 53 close
D/BluetoothManagerService(  761): Message: 30
,I/GKI_LINUX( 2950): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 2950): GKI_exit_task 0 done
I/GKI_LINUX( 2950): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 2950): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,V/NativeCrypto( 1436): Read error: ssl=0x9bc09200: I/O error during system call, Connection timed out
,D/HeadsetService( 2950): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2950): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f840697
,D/HeadsetStateMachine( 2950): Exit Disconnected: -1
,D/BluetoothAdapterState( 2950): Stopping profile services that were post enabled
,D/BluetoothHeadset( 1164): Proxy object disconnected
D/BluetoothHeadset( 1164): Proxy object disconnected
D/BluetoothHeadset(  761): Proxy object disconnected
D/BluetoothHeadset( 1207): Proxy object disconnected
V/NativeCrypto( 1436): SSL shutdown failed: ssl=0x9bc09200: I/O error during system call, Broken pipe
D/A2dpService( 2950): Received stop request...Stopping profile...
,D/A2dpStateMachine( 2950): Exit Disconnected: -1
,D/BluetoothAdapterService( 2950): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f840697
,D/HidService( 2950): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2950): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f840697
,D/HealthService( 2950): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 2950): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f840697
,D/BluetoothA2dp(  761): Proxy object disconnected
,D/PanService( 2950): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2950): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f840697
,D/BtGatt.DebugUtils( 2950): handleDebugAction() action=null
,D/BtGatt.GattService( 2950): Received stop request...Stopping profile...
,D/BtGatt.GattService( 2950): stop()
D/BtGatt.AdvertiseManager( 2950): advertise clients cleared
,D/BluetoothManagerService(  761): Message: 30
,D/BluetoothAdapterService( 2950): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f840697
,D/HeadsetStateMachine( 2950): Unbinding service...
,W/BluetoothHeadsetServiceJni( 2950): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2950): Cleaning up Bluetooth Handsfree callback object
,D/BluetoothMapService( 2950): Received stop request...Stopping profile...
,D/BluetoothMapService( 2950): stop()
D/BluetoothMapEmailAppObserver( 2950): deinitObservers()
D/BluetoothMapEmailAppObserver( 2950): removeReceiver()
,D/BluetoothAdapterService( 2950): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f840697
,I/GKI_LINUX( 2950): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 2950): GKI_exit_task 2 done
I/GKI_LINUX( 2950): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 2950): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 2950): cleanup: HH disabling or disabled already, status = 0
,W/BluetoothHidServiceJni( 2950): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 2950): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2950): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 2950): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2950): Cleaning up Bluetooth PAN callback object
,V/BluetoothMapService( 2950): Handler(): got msg=4
D/BluetoothMapService( 2950): MAP Service closeService in
V/BluetoothMapService( 2950): MAP Service closeService out
D/BluetoothMapService( 2950): cleanup()
D/BluetoothMapService( 2950): MAP Service closeService in
V/BluetoothMapService( 2950): MAP Service closeService out
D/BluetoothAdapterState( 2950): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2950): Setting state to 10
,I/BluetoothAdapterState( 2950): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService(  761): Message: 60
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
,D/BluetoothManagerService(  761): Broadcasting onBluetoothStateChange(false) to 9 receivers.
E/WifiStateMachine(  761): scanCount==0 - aborting
,D/BluetoothMap( 3830): onBluetoothStateChange: up=false
,D/ConnectivityService(  761): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
I/BluetoothAdapterState( 2950): Entering OffState
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on <unknown ssid>
D/BluetoothHeadset( 1207): onBluetoothStateChange: up=false
D/BluetoothPbap( 3830): onBluetoothStateChange: up=false
D/WifiNetworkAgent(  761): NetworkAgent: NetworkAgent channel lost
D/BluetoothHeadset( 1164): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 3830): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  761): onBluetoothStateChange: up=false
D/ConnectivityService(  761): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/BluetoothHeadset( 1164): onBluetoothStateChange: up=false
D/BluetoothHeadset(  761): onBluetoothStateChange: up=false
,D/LocalBluetoothProfileManager( 3830): LocalBluetoothProfileManager construction complete
,D/ConnectivityManager.CallbackHandler(  916): CM callback handler got msg 524292
E/native  (  761): do suspend true
D/Nat464Xlat(  761): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/BluetoothManagerService(  761): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  761): Broadcasting onBluetoothServiceDown() to 11 receivers.
,D/CSLegacyTypeTracker(  761): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/BluetoothManagerService(  761): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@5b09185 mBinding = false
,D/BluetoothManagerService(  761): Sending unbind request.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Disconnected - quitting
,D/BluetoothManagerService(  761): Bluetooth State Change Intent: 13 -> 10
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/GKI_LINUX( 2950): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 2950): GKI_exit_task 1 done
I/GKI_LINUX( 2950): GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 2950): cleanupNative: return from cleanup
,D/ConnectivityService(  761): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1207): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CommandListener(  179): Clearing all IP addresses on wlan0
D/WifiScanningService(  761): SCAN_AVAILABLE : 1
D/RttService(  761): SCAN_AVAILABLE : 1
D/WifiScanningService(  761): StartedState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  761): DefaultState
D/RttService(  761): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
I/art     ( 2950): System.exit called, status: 0
,I/AndroidRuntime( 2950): VM exiting with result code 0, cleanup skipped.
D/BluetoothAdapter( 1280): 551825804: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1280): 551825804: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter(  916): 676396712: getState() :  mService = null. Returning STATE_OFF
,D/ConnectivityManager.CallbackHandler( 1558): CM callback handler got msg 524292
D/BluetoothAdapter(  916): 676396712: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  916): 676396712: getState() :  mService = null. Returning STATE_OFF
,D/AndroidRuntime( 4171): 
D/AndroidRuntime( 4171): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4171): CheckJNI is OFF
,I/ActivityManager(  761): Process com.android.bluetooth (pid 2950) has died
,D/DockEventReceiver( 3830): finishStartingService: stopping service
,D/WifiService(  761): New client listening to asynchronous messages
,I/wpa_supplicant( 2957): p2p0: CTRL-EVENT-TERMINATING 
,I/ActivityManager(  761): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=4217 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/wpa_supplicant( 2957): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,D/AndroidRuntime( 4171): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  761): Killing 2879:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,W/PackageSettings(  761): Skipping PackageSetting{19ede03e com.example.hello/10277} due to missing metadata
,I/WindowState(  761): WIN DEATH: Window{e04cd66 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  761): Client connection lost with reason: 4
,D/Tethering(  761): InitialState.processMessage what=4
,I/wpa_supplicant( 2957): wlan0: CTRL-EVENT-TERMINATING 
,I/ActivityManager(  761):   Force finishing activity ActivityRecord{3366cc63 u0 com.test.thalitest/.MainActivity t214}
,W/ActivityManager(  761): Spurious death for ProcessRecord{1d2caa18 2879:com.test.thalitest/u0a270}, curProc for 2879: null
I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/ActivityManager(  761):   Force finishing activity ActivityRecord{3366cc63 u0 com.test.thalitest/.MainActivity t214 f}
W/ActivityManager(  761): Duplicate finish request for ActivityRecord{3366cc63 u0 com.test.thalitest/.MainActivity t214 f}
,D/Tethering(  761): sendTetherStateChangedBroadcast 0, 0, 0
W/ResourcesManager( 4217): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator( 1071): resetDictionaries() : en_US
,W/GeofencerStateMachine( 1280): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  761): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 1250): Explicit concurrent mark sweep GC freed 7209(469KB) AllocSpace objects, 2(207KB) LOS objects, 38% free, 26MB/42MB, paused 4.170ms total 38.390ms
W/Settings( 1797): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1280): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Adreno-EGL(  940): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  940): Initialized EGL, version 1.4
I/Keyboard.Facilitator.DecoderInitializer( 1071): run()
,I/Decoder ( 1071): createOrResetDecoder
,D/OpenGLRenderer(  940): Enabling debug mode 0
,I/art     ( 1341): Explicit concurrent mark sweep GC freed 87838(4MB) AllocSpace objects, 18(311KB) LOS objects, 25% free, 19MB/25MB, paused 650us total 108.264ms
,I/ConfigService( 1436): onCreate
,D/AdapterServiceConfig( 4217): Adding HeadsetService
D/AdapterServiceConfig( 4217): Adding A2dpService
,D/AdapterServiceConfig( 4217): Adding HidService
D/AdapterServiceConfig( 4217): Adding HealthService
D/AdapterServiceConfig( 4217): Adding PanService
D/AdapterServiceConfig( 4217): Adding GattService
D/AdapterServiceConfig( 4217): Adding BluetoothMapService
,I/ActivityManager(  761): Killing 1797:com.google.android.talk/u0a54 (adj 15): empty #17
,I/art     (  761): Explicit concurrent mark sweep GC freed 114627(5MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 29MB/43MB, paused 1.355ms total 133.736ms
W/InputMethodManagerService(  761): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@3aa57dcf (uid=10034 pid=940)
,I/art     (  761): WaitForGcToComplete blocked for 121.139ms for cause Explicit
,W/libprocessgroup(  761): failed to open /acct/uid_10054/pid_1797/cgroup.procs: No such file or directory
D/AuthorizationBluetoothService( 1436): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BackupManagerService(  761): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  761): Receieved: android.intent.action.PACKAGE_REMOVED
,W/ContextImpl( 3830): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver( 3830): finishStartingService: stopping service
,D/BluetoothAdapter( 3830): 443641893: getState() :  mService = null. Returning STATE_OFF
,W/InputMethodManagerService(  761): Got RemoteException sending setActive(false) notification to pid 2879 uid 10270
,I/Keyboard.Facilitator( 1071): onFinishInput()
,D/AuthorizationBluetoothService( 1436): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/TaskPersister(  761): removeObsoleteFile: deleting file=214_task.xml
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1071): run()
,D/BluetoothAdapter( 3830): 443641893: getState() :  mService = null. Returning STATE_OFF
,I/Launcher( 1250): Deferring update until onResume
,I/art     (  761): Explicit concurrent mark sweep GC freed 25808(1280KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 28MB/42MB, paused 1.634ms total 156.154ms
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1071): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1071): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1071): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1071): run()
I/StatsUtilsManager( 1071): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1071): shouldRecordStats() = Too Soon
,W/ResourcesManager( 1250): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1250): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  761): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=4245 uid=10054 gids={50054, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/Launcher( 1250): Deferring update until onResume
,D/AndroidRuntime( 4171): Shutting down VM
,W/ResourcesManager( 4245): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 4245): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 4245): MmsConfig.loadMmsSettings
,I/Babel_SMS( 4245): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
,I/Babel_SMS( 4245): MmsConfig.loadFromDatabase
,E/Babel_SMS( 4245): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4245): MmsConfig.loadFromResources
,E/Babel_SMS( 4245): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 4245): MmsConfig.loadMmsSettings: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
,I/Babel_SMS( 4245): ApnsOta: OTA version -1
,I/Babel   ( 4245): deleted: false for 0
,W/Settings( 4245): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 4245): startup - clean
,D/VoicemailCleanupService( 1361): Cleaning up data for package: com.test.thalitest
,W/VideoCapabilities( 4245): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  761): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=4279 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,E/SQLiteLog( 1361): (3850) statement aborts at 16: [DELETE FROM voicemail_status WHERE (((source_package = 'com.test.thalitest')))] disk I/O error
--------- beginning of crash
E/AndroidRuntime( 1361): FATAL EXCEPTION: IntentService[VoicemailCleanupService]
E/AndroidRuntime( 1361): Process: android.process.acore, PID: 1361
E/AndroidRuntime( 1361): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1361): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1361): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1361): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1361): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1361): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1361): 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:156)
E/AndroidRuntime( 1361): 	at com.android.providers.contacts.VoicemailStatusTable.delete(VoicemailStatusTable.java:80)
E/AndroidRuntime( 1361): 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:130)
E/AndroidRuntime( 1361): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/AndroidRuntime( 1361): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/AndroidRuntime( 1361): 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:52)
E/AndroidRuntime( 1361): 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
E/AndroidRuntime( 1361): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1361): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1361): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1361): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 1361): Sending signal. PID: 1361 SIG: 9
E/DropBoxManagerService(  761): Can't write: system_app_crash
E/DropBoxManagerService(  761): java.io.FileNotFoundException: /data/system/dropbox/drop99.tmp: open failed: EROFS (Read-only file system)
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
,I/VideoCapabilities( 4245): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4245): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4245): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4245): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4245): Unrecognized profile 2130706433 for video/avc

```
