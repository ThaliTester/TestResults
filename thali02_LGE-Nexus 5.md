#### Test 519863408c638e9_thali02_LGE-Nexus 5 Logs


```
--------- beginning of system
W/ResourcesManager( 2887): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2887): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
--------- beginning of main
D/Finsky  ( 2386): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
I/ActivityManager(  760): Killing 2121:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
,V/JNIHelp ( 2887): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
W/libprocessgroup(  760): failed to open /acct/uid_1000/pid_2121/cgroup.procs: No such file or directory
W/System  ( 2887): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2887): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 2937): 
D/AndroidRuntime( 2937): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2937): CheckJNI is OFF
D/AndroidRuntime( 2937): Calling main entry com.android.commands.am.Am
I/ActivityManager(  760): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/Icing   ( 1562): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/ActivityManager(  760): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2955 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2937): Shutting down VM
V/ActivityManager(  760): Display changed displayId=0
D/Icing   ( 1562): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1562): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/WebViewFactory( 2955): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2955): Time to load native libraries: 2 ms (timestamps 5547-5549)
I/LibraryLoader( 2955): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2955): Binding Chromium to main looper Looper (main, tid 1) {11d038de}
I/LibraryLoader( 2955): Expected native library version number "",actual native library version number ""
I/chromium( 2955): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2955): Initializing chromium process, singleProcess=true
W/art     ( 2955): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2955): ApplicationContext is null in ApplicationStatus
W/chromium( 2955): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 2955): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 2955): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2955): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 2955): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@208eac8c:true
,D/BluetoothAdapter( 2955): 702845915: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 2955): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2955): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2955): CordovaWebView is running on device made by: LGE
,W/art     ( 2955): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 2955): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2955): Render dirty regions requested: true
,D/Atlas   ( 2955): Validating map...
,W/chromium( 2955): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2955): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2955): Enabling debug mode 0
,W/IInputConnectionWrapper( 2955): showStatusIcon on inactive InputConnection
,W/BindingManager( 2955): Cannot call determinedVisibility() - never saw a connection for the pid: 2955
,I/ActivityManager(  760): Displayed com.test.thalitest/.MainActivity: +443ms (total +53s931ms)
,D/JsMessageQueue( 2955): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 2955): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
,D/JX-Cordova( 2955): jxcore cordova android initializing
,I/ActivityManager(  760): Killing 2214:com.google.android.youtube/u0a80 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10080/pid_2214/cgroup.procs: No such file or directory
,W/jxcore-log( 2955): Initializing JXcore engine
W/jxcore-log( 2955): JXcore engine is ready
W/jxcore-log( 2955): Starting JXcore engine
W/.test.thalitest( 2955): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7869]" dev="sockfs" ino=7869 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 2955): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 2955): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6641]" dev="sockfs" ino=6641 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 2955): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[17106]" dev="sockfs" ino=17106 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 2955): Platform android
W/jxcore-log( 2955): 
W/jxcore-log( 2955): Process ARCH arm
W/jxcore-log( 2955): 
I/jxcore-log( 2955): JXcore Cordova bridge is ready!
I/jxcore-log( 2955): 
W/jxcore-log( 2955): JXcore engine is started
I/chromium( 2955): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/jxcore-log( 2955): Toggling radios to true
I/jxcore-log( 2955): 
D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  760): enable():  mBluetooth =null mBinding = false
D/BluetoothManagerService(  760): Message: 1
D/BluetoothManagerService(  760): MESSAGE_ENABLE: mBluetooth = null
D/WifiService(  760): New client listening to asynchronous messages
D/WifiService(  760): setWifiEnabled: true pid=2955, uid=10270
E/WifiService(  760): Invoking mWifiStateMachine.setWifiEnabled
D/SoftapController(  179): Softap fwReload - Ok
I/jxcore-log( 2955): Radios toggled
I/jxcore-log( 2955): 
I/ActivityManager(  760): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3016 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
D/CommandListener(  179): Setting iface cfg
D/CommandListener(  179): Trying to bring down wlan0
D/CommandListener(  179): Clearing all IP addresses on wlan0
D/WifiMonitor(  760): startMonitoring(wlan0) with mConnected = false
I/ActivityManager(  760): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=3027 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
I/wpa_supplicant( 3022): Successfully initialized wpa_supplicant
W/ResourcesManager( 3016): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
I/wpa_supplicant( 3022): rfkill: Cannot open RFKILL control device
D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c8a8a43:true
D/BluetoothAdapter( 3027): 298858718: getState() :  mService = null. Returning STATE_OFF
D/BluetoothManagerService(  760): Message: 30
D/BluetoothManagerService(  760): Message: 30
D/LocalBluetoothProfileManager( 3027): Adding local MAP profile
D/BluetoothMap( 3027): Create BluetoothMap proxy object
D/BluetoothManagerService(  760): Message: 30
D/BluetoothManagerService(  760): Message: 30
D/LocalBluetoothProfileManager( 3027): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 3027): 298858718: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3027): 298858718: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager(  760): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3065 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  760): Killing 2306:com.google.android.deskclock/u0a38 (adj 15): empty #17
,D/AdapterServiceConfig( 3016): Adding HeadsetService
D/AdapterServiceConfig( 3016): Adding A2dpService
D/AdapterServiceConfig( 3016): Adding HidService
D/AdapterServiceConfig( 3016): Adding HealthService
D/AdapterServiceConfig( 3016): Adding PanService
D/AdapterServiceConfig( 3016): Adding GattService
D/AdapterServiceConfig( 3016): Adding BluetoothMapService
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@49f7369:true
,D/BluetoothAdapterState( 3016): make
,I/bluedroid( 3016): init
,I/BluetoothAdapterState( 3016): Entering OffState
,I/bte_conf( 3016): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3016): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3016): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3016): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3016): get_profile_interface socket
I/bluedroid( 3016): get_profile_interface map_client
,I/GKI_LINUX( 3016): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 3016): Address is:34:FC:EF:11:AE:67
,W/libprocessgroup(  760): failed to open /acct/uid_10038/pid_2306/cgroup.procs: No such file or directory
,D/BluetoothAdapterProperties( 3016): Name is: Nexus 5,
D/BluetoothManagerService(  760): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  760): Stored Bluetooth name: Nexus 5
D/BluetoothManagerService(  760): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  760): Message: 40
,D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 3016): config_hci_snoop_log
,D/BluetoothManagerService(  760): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  760): Broadcasting onBluetoothServiceUp() to 10 receivers.
,D/BluetoothAdapterState( 3016): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3016): Setting state to 11
,I/BluetoothAdapterState( 3016): Bluetooth adapter state changed: 10-> 11
D/BluetoothBondStateMachine( 3016): make
,D/BluetoothManagerService(  760): Message: 60
D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  760): Bluetooth State Change Intent: 10 -> 11
I/BluetoothBondStateMachine( 3016): StableState(): Entering Off State
D/BluetoothHeadset( 1192): Proxy object connected
D/BluetoothHeadset(  760): Proxy object connected
D/BluetoothHeadset( 1221): Proxy object connected
D/HeadsetService( 3016): Received start request. Starting profile...
D/BluetoothHeadset( 1192): Proxy object connected
I/BluetoothHeadsetServiceJni( 3016): classInitNative: succeeds
D/HeadsetStateMachine( 3016): make
I/BluetoothAdapterState( 3016): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/HeadsetStateMachine( 3016): max_hf_connections = 1
I/bluedroid( 3016): get_profile_interface handsfree
D/HeadsetStateMachine( 3016): Enter Disconnected: -2, size: 0
D/BluetoothAdapterService( 3016): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b00abf
D/BluetoothA2dp(  760): Proxy object connected
D/A2dpService( 3016): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3016): classInitNative: succeeds
I/bluedroid( 3016): get_profile_interface avrcp
,E/RemoteController( 3016): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3016): classInitNative: succeeds
D/A2dpStateMachine( 3016): make
,I/bluedroid( 3016): get_profile_interface a2dp
I/GKI_LINUX( 3016): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothAdapterService( 3016): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b00abf
,I/BluetoothHidServiceJni( 3016): classInitNative: succeeds
D/A2dpStateMachine( 3016): Enter Disconnected: -2
,D/HidService( 3016): Received start request. Starting profile...
D/BluetoothInputDevice( 3027): Proxy object connected
I/bluedroid( 3016): get_profile_interface hidhost
D/BluetoothAdapterService( 3016): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b00abf
,D/HidProfile( 3027): Bluetooth service connected
I/BluetoothHealthServiceJni( 3016): classInitNative: succeeds
D/HealthService( 3016): Received start request. Starting profile...
I/bluedroid( 3016): get_profile_interface health
,D/BluetoothAdapterService( 3016): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b00abf
I/BluetoothPanServiceJni( 3016): classInitNative(L105): succeeds
,D/BluetoothPan( 3027): BluetoothPAN Proxy object connected
,D/PanProfile( 3027): Bluetooth service connected
D/PanService( 3016): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3016): initializeNative(L110): pan
I/bluedroid( 3016): get_profile_interface pan
,D/BluetoothAdapterService( 3016): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b00abf
,I/BtGatt.JNI( 3016): classInitNative(L863): classInitNative: Success!
D/BtGatt.DebugUtils( 3016): handleDebugAction() action=null
D/BtGatt.GattService( 3016): Received start request. Starting profile...
D/BtGatt.GattService( 3016): start()
I/bluedroid( 3016): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 3016): advertise manager created
D/BluetoothAdapterService( 3016): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b00abf
,V/BluetoothMapService( 3016): BluetoothMapBinder()
,D/BluetoothMapService( 3016): Received start request. Starting profile...
D/BluetoothMapService( 3016): start()
,D/BluetoothMap( 3027): Proxy object connected
,D/MapProfile( 3027): Bluetooth service connected
D/BluetoothMap( 3027): getConnectedDevices()
D/BluetoothMap( 3027): Bluetooth is Not enabled
D/BluetoothMapEmailSettingsLoader( 3016): Found 0 applications
D/BluetoothMapEmailAppObserver( 3016): createReceiver()
D/BluetoothMapEmailAppObserver( 3016): initObservers()
D/BluetoothMapEmailAppObserver( 3016): getEnabledAccountItems()
,D/BluetoothAdapterService( 3016): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b00abf
,D/HeadsetStateMachine( 3016): Proxy object connected
V/BluetoothMapService( 3016): Handler(): got msg=1
D/HeadsetStateMachine( 3016): Disconnected process message: 10, size: 0
,D/HeadsetPhoneState( 3016): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/BluetoothAdapterState( 3016): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3016): enable
D/HeadsetStateMachine( 3016): Disconnected process message: 11, size: 0
,I/GKI_LINUX( 3016): gki_task_entry task_id=0 [BTU] starting
I/bt_hci_bdroid( 3016): init
I/bt-btu  ( 3016): btu_task pending for preload complete event
,I/bt_vendor( 3016): init
I/bt_vnd_conf( 3016): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3016): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3016): userial_init
,I/bt_userial_vendor( 3016): userial vendor open: opening /dev/ttyHS99
,I/bt_userial_vendor( 3016): device fd = 53 open
,D/bt_userial( 3016): Entering userial_read_thread()
,I/art     ( 1361): Explicit concurrent mark sweep GC freed 10384(610KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 19MB/32MB, paused 931us total 38.257ms
,I/bt_hwcfg( 3016): bt vendor lib: set UART baud 4000000
,D/bt_hwcfg( 3016): Chipset BCM4335C0
D/bt_hwcfg( 3016): Target name = [BCM4335C0]
I/bt_hwcfg( 3016): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,D/AuthorizationBluetoothService( 1361): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager(  760): Killing 2354:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10069/pid_2354/cgroup.procs: No such file or directory
,D/Tethering(  760): sendTetherStateChangedBroadcast 1, 0, 0
,I/bt_hwcfg( 3016): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 3016): Settlement delay -- 100 ms
I/bt_hwcfg( 3016): Setting fw settlement delay to 100 
,I/wpa_supplicant( 3022): rfkill: Cannot open RFKILL control device
,I/bt_hwcfg( 3016): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 3016): Setting local bd addr to 34:FC:EF:11:AE:67
,I/wpa_supplicant( 3022): wlan0: CTRL-EVENT-SCAN-STARTED 
,I/bt_hwcfg( 3016): vendor lib fwcfg completed
,I/bt-btu  ( 3016): btu_task received preload complete event
,D/WifiConfigStore(  760): Loading config and enabling all networks 
,E/WifiConfigStore(  760): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  760): Setting external_sim to 1
,D/WifiStateMachine(  760): Setting OUI to DA-A1-19
,I/WifiNative-HAL(  760): startHal
D/wifi    (  760): setting scan oui 0xb42172f8
D/WifiHAL (  760): Sending mac address OUI
E/WifiHAL (  760): failed to set scanning mac OUI; result = -95
,I/        ( 3016): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3016): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3016): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3016): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3016): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3016): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3016): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3016): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3016): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3016): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3016): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3016): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3016): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3016): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3016): BTE_InitTraceLevels -- TRC_BTIF
,W/Settings( 1794): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/native  (  760): do suspend true
,D/WifiService(  760): New client listening to asynchronous messages
,D/WifiScanningService(  760): SCAN_AVAILABLE : 3
,D/RttService(  760): SCAN_AVAILABLE : 3
D/WifiScanningService(  760): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  760): startHal
D/RttService(  760): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/wifi    (  760): getting scan capabilities on interface[1] = 0xb42172f8
D/WifiHAL (  760): Creating message to get scan capablities; iface = 21
D/CommandListener(  179): Setting iface cfg
D/WifiHAL (  760): In GetCapabilities::handleResponse
D/WifiHAL (  760): Id = 0, subcmd = 0, len = 28, expected len = 32
D/CommandListener(  179): Trying to bring up p2p0
D/WifiScanningService(  760): StartedState
D/WifiMonitor(  760): startMonitoring(p2p0) with mConnected = true
,I/wpa_supplicant( 3022): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,D/WifiNative-HAL(  760): p2pGetDeviceAddress
,D/WifiNative-HAL(  760): p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,I/art     (  760): Explicit concurrent mark sweep GC freed 25306(1303KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 940us total 70.255ms
,E/bt-btm  ( 3016): BTM_SecRegister:p_cb_info->p_le_callback == 0xa3ed99d5 
E/bt-btm  ( 3016): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3ed99d5 
,E/bt-btif ( 3016): Calling BTA_HhEnable
E/bt-btif ( 3016): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3016): Address is:34:FC:EF:11:AE:67
,D/BluetoothManagerService(  760): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  760): Stored Bluetooth name: Nexus 5
,D/BluetoothAdapterProperties( 3016): Name is: Nexus 5
,D/BluetoothAdapterProperties( 3016): Scan Mode:20
D/BluetoothAdapterProperties( 3016): Discoverable Timeout:120
,D/bte_conf( 3016): Device ID record 1 : primary
D/bte_conf( 3016):   vendorId            = 000f
D/bte_conf( 3016):   vendorIdSource      = 0001
D/bte_conf( 3016):   product             = 1200
D/bte_conf( 3016):   version             = 1436
D/bte_conf( 3016):   clientExecutableURL = 
D/bte_conf( 3016):   serviceDescription  = 
D/bte_conf( 3016):   documentationURL    = 
D/bte_conf( 3016): bte_load_did_conf no section named DID2.
D/BluetoothAdapterState( 3016): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3016): ScanMode =  20
D/BluetoothPanServiceJni( 3016): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,D/BluetoothAdapterProperties( 3016): State =  11
D/BluetoothAdapterProperties( 3016): Setting state to 12
I/BluetoothAdapterState( 3016): Bluetooth adapter state changed: 11-> 12
I/BluetoothAdapterState( 3016): Entering On State
D/BluetoothAdapterProperties( 3016): Scan Mode:21
D/BluetoothAdapterProperties( 3016): Discoverable Timeout:120
,D/BluetoothManagerService(  760): Message: 60
D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  760): Broadcasting onBluetoothStateChange(true) to 9 receivers.
D/BluetoothA2dp(  760): onBluetoothStateChange: up=true
D/BluetoothHeadset(  760): onBluetoothStateChange: up=true
D/BluetoothPan( 3027): onBluetoothStateChange(on) call bindService
D/BluetoothHeadset( 1192): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1192): onBluetoothStateChange: up=true
D/BluetoothInputDevice( 3027): onBluetoothStateChange: up=true
D/BluetoothPbap( 3027): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1221): onBluetoothStateChange: up=true
D/BluetoothMap( 3027): onBluetoothStateChange: up=true
W/bt-smp  ( 3016): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3016): Plain text(LSB ~ MSB) = ac 45 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3016): Encrypted text(LSB ~ MSB) = 7f 7c 37 99 23 a1 03 2e 57 07 9c 0b 24 70 46 2a 
W/bt-btm  ( 3016): Stopping oneshot timer
E/bt_h4   ( 3016): vendor lib postload completed
D/BluetoothManagerService(  760): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothManagerService(  760): Bluetooth State Change Intent: 11 -> 12
D/BluetoothMapService( 3016): onReceive
D/BluetoothMapService( 3016): STATE_ON
V/BluetoothMapService( 3016): Handler(): got msg=1
D/BluetoothMapMasInstance( 3016): Map Service startRfcommSocketListener
,W/bt-smp  ( 3016): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3016): Plain text(LSB ~ MSB) = 7b d6 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3016): Encrypted text(LSB ~ MSB) = 1e 5a 4b 27 61 07 81 7f ce e0 4a c2 1f ad 63 2a 
W/bt-btm  ( 3016): Stopping oneshot timer
W/bt-smp  ( 3016): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3016): Plain text(LSB ~ MSB) = e4 e7 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3016): Encrypted text(LSB ~ MSB) = 6b d7 d9 de 90 76 92 5b c7 75 c3 87 48 52 ab 92 
W/bt-btm  ( 3016): Stopping oneshot timer
W/bt-smp  ( 3016): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3016): Plain text(LSB ~ MSB) = 0a 48 42 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3016): Encrypted text(LSB ~ MSB) = c0 1a 9c 35 04 aa 99 34 14 94 d3 0f c5 e5 e7 85 
W/bt-btm  ( 3016): Stopping oneshot timer
,W/bt-smp  ( 3016): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3016): Plain text(LSB ~ MSB) = ae 77 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3016): Encrypted text(LSB ~ MSB) = 24 bd a3 d2 b9 e9 bc d6 82 b4 0e 52 3d 6f 76 dc 
W/bt-btm  ( 3016): Stopping oneshot timer
D/BluetoothManagerService(  760): Message: 40
D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothMapMasInstance( 3016): MAS initSocket()
D/BluetoothMapMasInstance( 3016):   masId = 00
D/BluetoothMapMasInstance( 3016):   msgTypes = 0e
D/BluetoothMapMasInstance( 3016):   masName = SMS/MMS
D/BluetoothMapMasInstance( 3016):   SDP string = 000eSMS/MMS
W/bt-smp  ( 3016): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3016): Plain text(LSB ~ MSB) = 63 c9 50 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3016): Encrypted text(LSB ~ MSB) = 8f 7a 91 1b ff 69 6c 23 35 3a 17 d3 5b c0 91 a3 
W/bt-btm  ( 3016): Stopping oneshot timer
W/bt-smp  ( 3016): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3016): Plain text(LSB ~ MSB) = e1 c9 6e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3016): Encrypted text(LSB ~ MSB) = fa 2a e8 1e e0 50 9f 95 0a 6d 49 70 61 f1 24 4c 
W/bt-btm  ( 3016): Stopping oneshot timer
I/Telecom ( 1192): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/HeadsetStateMachine( 3016): Disconnected process message: 9, size: 0
D/HeadsetStateMachine( 3016): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 3016): mNumber:  mType: 128
D/HeadsetStateMachine( 3016): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 3016): terminateScoUsingVirtualVoiceCall:No present call to terminate
W/BluetoothAdapter( 3016): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothMapMasInstance( 3016): Succeed to create listening socket 
D/BluetoothMapMasInstance( 3016): Accepting socket connection...
,D/LocalBluetoothProfileManager( 3027): Adding local A2DP profile
D/BluetoothManagerService(  760): Message: 30
D/LocalBluetoothProfileManager( 3027): Adding local HEADSET profile
D/BluetoothManagerService(  760): Message: 30
,W/ContextImpl( 3027): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/BluetoothA2dp( 3027): Proxy object connected
D/A2dpProfile( 3027): Bluetooth service connected
D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3016): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothHeadset( 3027): Proxy object connected
D/HeadsetProfile( 3027): Bluetooth service connected
D/DockEventReceiver( 3027): finishStartingService: stopping service
,D/BluetoothPbap( 3027): Proxy object connected
D/PbapServerProfile( 3027): Bluetooth service connected
,D/AuthorizationBluetoothService( 1361): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3016): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 3016): Accept thread started.
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 2955): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): my name is : LGE-Nexus 5_PT5003
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): attempting to connect to test coordinator
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): check test folder
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): found test : ./testFindPeers.js
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): found test : ./testReConnect.js
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): found test : ./testSendData.js
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): Test app app.js loaded
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/chromium( 2955): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 3022): p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  760): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiStateMachine(  760): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  760): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=1
,E/WifiConfigStore(  760): writeKnownNetworkHistory write linked 1
E/WifiConfigStore(  760): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  760): will read network variables netId=1
,E/WifiStateMachine(  760): CMD_AUTO_CONNECT did save config ->  nid=1
,E/WifiConfigStore(  760): will read network variables netId=1
,I/wpa_supplicant( 3022): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,E/WifiConfigStore(  760): setLastSelectedConfiguration -1
,E/wpa_supplicant( 3022): PNO: In assoc process
,I/wpa_supplicant( 3022): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3022): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3022): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  760): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  760): Start Dhcp Watchdog 1
,E/native  (  760): do suspend false
,E/WifiStateMachine(  760): scanCount==0 - aborting
,I/dhcpcd  ( 3197): version 5.5.6 starting
,E/dhcpcd  ( 3197): get_duid: Read-only file system
,I/dhcpcd  ( 3197): wlan0: rebinding lease of 192.168.1.114
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/dhcpcd  ( 3197): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3197): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  760): do suspend true
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  760): Adding iface wlan0 to network 100
,E/WifiStateMachine(  760): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  760): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  760): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/ConnectivityService(  760): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/ConnectivityService(  760): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService(  760): Setting Dns servers for network 100 to [/192.168.1.1]
D/Nat464Xlat(  760): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  760): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  760): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  760): rematching NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Checking http://clients3.google.com/generate_204 on "NG7005g"
D/ConnectivityService(  760):    accepting network in place of null
,D/ConnectivityService(  760): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
,D/CSLegacyTypeTracker(  760): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  760): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  760): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 01 Dec 2015 10:48:33 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1448966912907], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1448966912890]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Validated
,D/ConnectivityService(  760): Validated NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  760): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  760): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  760): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1221): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 2955): 
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  760): MasterInitialState.processMessage what=3
,D/AlarmManagerService(  760): Setting time of day to sec=1448966915
,W/AlarmManagerService(  760): Unable to set rtc to 1448966915: Invalid argument
,I/NetworkMonitor( 2474): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2474): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  760): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=3290 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/iu.SyncManager( 1562): SYNC; picasa accounts
,W/ResourcesManager( 3290): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3290): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/NetworkLogImpl( 1562): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1562): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1562): num queued entries: 0
,I/iu.UploadsManager( 1562): num updated entries: 0
,I/iu.SyncManager( 1562): NEXT; no task
,E/GpsLocationProvider(  760): No APN found to select.
,D/ChimeraCfgMgr( 1562): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1562): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/JNIHelp ( 3290): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/CheckinService( 1562): Checkin interval check for package: unspecified last checkin: 1448876855187 min interval config: 0 actual interval: 90061054
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SystemUpdateService( 1562): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SystemUpdateService( 1562): onCreate
,D/GpsLocationProvider(  760): NTP server returned: 1448966912998 (Tue Dec 01 11:48:32 GMT+01:00 2015) reference: 82685 certainty: 10 system time offset: -3262
E/LocSvc_eng(  760): E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,I/CheckinService( 1562): Checking schedule, now: 1448966916272 next: 1448919022143
,I/CheckinService( 1562): active receiver: enabled
,D/SystemUpdateService( 1562): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1562): active receiver: enabled
,W/System  ( 3290): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3290): Installed default security provider GmsCore_OpenSSL
,I/CheckinService( 1562): Preparing to send checkin request
I/EventLogService( 1562): Accumulating logs since 1448965816031
I/SystemUpdateService( 1562): showing system update notification
,I/GoogleURLConnFactory( 1562): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1562): retry (wakeup: false) in 3599961 ms
,I/ActivityManager(  760): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3335 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/SystemUpdateService( 1562): onDestroy
I/art     (  194): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 359us total 18.347ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 388us total 14.942ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 170us total 14.681ms
,E/Auth.Api.Credentials( 1562): [CredentialSyncAdapter] Unknown sync event.
,E/YouTube MDX( 3290): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/Babel   ( 1794): connection state changed from UNKNOWN to CONNECTED
,I/GCM     ( 1361): GCM config loaded
,I/GAv4    ( 3335): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3335):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3335):   adb logcat -s GAv4
,W/GAv4    ( 3335): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/ConnectivityChangeReceiver( 1562): Ignoring connectivity change
,W/GAv4    ( 3335): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3335): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/ConnectivityService(  760): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/dex2oat ( 3386): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-981007307.jar --oat-fd=37 --oat-location=/data/data/com.google.android.youtube/cache/ads-981007307.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/ConnectivityService(  760): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  760): apparently satisfied.  currentScore=60
,D/ConnectivityManager.CallbackHandler( 1562): CM callback handler got msg 524290
,I/CheckinRequestBuilder( 1562): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1562): Failed to find provider info for com.google.android.wearable.settings
D/WifiService(  760): New client listening to asynchronous messages
,W/InstanceID/Rpc( 3290): Found 10008
,I/dex2oat ( 3386): dex2oat took 63.576ms (threads: 4)
,W/ResourcesManager( 2887): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2887): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     (  760): Explicit concurrent mark sweep GC freed 40303(1981KB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 27MB/41MB, paused 1.222ms total 68.152ms
,I/art     ( 1361): Explicit concurrent mark sweep GC freed 20840(1104KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 19MB/33MB, paused 2.103ms total 81.832ms
,D/ChimeraCfgMgr( 1562): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1562): Module APK com.google.android.play.games already loaded
,D/WifiService(  760): acquireWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@2bdacd48}
,W/Flag    ( 2887): Duration spec must be at least 2 characters long
,I/WebViewFactory( 3335): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AccountUtils( 1562): 0 accounts found with uca feature
,I/GamesSyncAdapter( 1562): Starting sync for 3a3529a
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GamesSyncAdapter( 1562): User is not G+ enabled. Aborting sync
I/GamesSyncAdapter( 1562): Sync duration for 3a3529a: 14
,I/LibraryLoader( 3335): Time to load native libraries: 2 ms (timestamps 6519-6521)
I/LibraryLoader( 3335): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3335): Binding Chromium to main looper Looper (main, tid 1) {220b1020}
,I/LibraryLoader( 3335): Expected native library version number "",actual native library version number ""
I/chromium( 3335): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3335): Initializing chromium process, singleProcess=true
,W/art     ( 3335): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3335): ApplicationContext is null in ApplicationStatus
,W/DriveInitializer( 1562): Awaiting to be initialized
,W/chromium( 3335): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3335): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3335): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3335): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/DriveInitializer( 1562): Background init thread started
,D/ChimeraCfgMgr( 1562): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1562): Module APK com.google.android.play.games already loaded
,I/NSApplication( 3335): Starting up...
,W/AudioManagerAndroid( 3335): Requires BLUETOOTH permission
,D/ChimeraCfgMgr( 1562): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1562): Module APK com.google.android.play.games already loaded
,W/DriveInitializer( 1562): Background init thread ended
,I/art     ( 1562): Explicit concurrent mark sweep GC freed 25874(1738KB) AllocSpace objects, 24(407KB) LOS objects, 25% free, 22MB/30MB, paused 1.955ms total 60.131ms
,I/ActivityManager(  760): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3500 uid=10076 gids={50076, 9997} abi=armeabi-v7a
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimeService( 3500): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1448966917168
D/        ( 3500): TimeServiceNative: User Time to be set is 1448966917168
D/QC-time-services( 3500): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3500): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3500): Lib:time_genoff_operation: pargs->ts_val = 1448966917168
D/QC-time-services(  197): Daemon: Connection accepted:time_genoff
D/QC-time-services(  197): Daemon:Received base = 2, unit = 1, operation = 0,value = 1448966917168
D/QC-time-services(  197): Daemon:genoff_opr: Base = 2, val = 1448966917168, operation = 0
D/QC-time-services(  197): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/4/70 16:39:24
D/QC-time-services(  197): Daemon:Value read from RTC seconds = 8095164000
D/QC-time-services(  197): Daemon:new time 1448966917168 
D/QC-time-services(  197): Daemon: delta 1440871753168 genoff 1440871753168 
D/QC-time-services(  197): Daemon:genoff_persistent_update: Writing genoff = 1440871753168 to memory
D/QC-time-services(  197): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  197): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services( 3500): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  197): Updating the TOD offset
D/QC-time-services(  197): Daemon:genoff_persistent_update: Writing genoff = 1440871753168 to memory
D/QC-time-services(  197): Daemon:Opening File: /data/system/time/ats_1
,D/QC-time-services(  197): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  197): Daemon:Update to modem bit set
,D/QC-time-services(  197): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  197): Daemon: Base = 2, Value being sent to MODEM = 1133002117168
E/QC-time-services( 3500): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
I/ActivityManager(  760): Killing 1770:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,D/QC-time-services(  197): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,D/QC-time-services(  197): Daemon: Time-services: Waiting to acceptconnection
,W/libprocessgroup(  760): failed to open /acct/uid_10045/pid_1770/cgroup.procs: No such file or directory
,I/CheckinService( 1562): Checkin interval check for package: unspecified last checkin: 1448876855187 min interval config: 0 actual interval: 90062037
,I/ActivityManager(  760): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=3528 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager(  760): Killing 2451:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10003/pid_2451/cgroup.procs: No such file or directory
,I/ActivityManager(  760): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3545 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/GAv4    ( 3528): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3528):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3528):   adb logcat -s GAv4
,W/ResourcesManager( 3545): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3545): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/GAv4    ( 3528): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/MultiDex( 3545): VM with version 2.1.0 has multidex support
I/MultiDex( 3545): install
I/MultiDex( 3545): VM has multidex support, MultiDex support library is disabled.
,W/GAv4    ( 3528): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,V/JNIHelp ( 3545): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/GAv4    ( 3528): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/ActivityThread( 3545): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 3545): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2ae70af0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3545): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  760): Killing 2328:com.google.android.gm/u0a70 (adj 15): empty #17
,I/art     ( 3545): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,I/art     ( 3545): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,E/DefaultHttpIssuer( 2887): Attempt to consume entity of HttpIssuer when no request is executing.
,E/DefaultHttpIssuer( 2887): Attempt to close HttpIssuer when no request is executing.
E/DefaultHttpIssuer( 2887): java.io.IOException
E/DefaultHttpIssuer( 2887): 	at cjw.b(PG:159)
E/DefaultHttpIssuer( 2887): 	at cju.b(PG:5072)
E/DefaultHttpIssuer( 2887): 	at dlh.b(PG:239)
E/DefaultHttpIssuer( 2887): 	at dlh.a(PG:140)
E/DefaultHttpIssuer( 2887): 	at dqo.a(PG:224)
E/DefaultHttpIssuer( 2887): 	at dlt.run(PG:9618)
E/DefaultHttpIssuer( 2887): 	at dlr.run(PG:3031)
,E/BaseSyncManager( 2887): IOException
E/BaseSyncManager( 2887): java.io.IOException: stream was reset: PROTOCOL_ERROR
E/BaseSyncManager( 2887): 	at hzd.b(PG:145)
E/BaseSyncManager( 2887): 	at hya.b(PG:104)
E/BaseSyncManager( 2887): 	at hxn.d(PG:917)
E/BaseSyncManager( 2887): 	at hxn.a(PG:95)
E/BaseSyncManager( 2887): 	at hxn$a.a(PG:902)
E/BaseSyncManager( 2887): 	at hvz.a(PG:50089)
E/BaseSyncManager( 2887): 	at hvz$a.a(PG:230)
E/BaseSyncManager( 2887): 	at hvz.a(PG:3201)
E/BaseSyncManager( 2887): 	at clz.a(PG:127)
E/BaseSyncManager( 2887): 	at cjr.a(PG:47)
E/BaseSyncManager( 2887): 	at cjq.a(PG:22)
E/BaseSyncManager( 2887): 	at cjs.a(PG:68)
E/BaseSyncManager( 2887): 	at cjw.b(PG:92)
E/BaseSyncManager( 2887): 	at cjw.a(PG:80)
E/BaseSyncManager( 2887): 	at cju.b(PG:5140)
E/BaseSyncManager( 2887): 	at cju.a(PG:1096)
E/BaseSyncManager( 2887): 	at dlh.b(PG:14062)
E/BaseSyncManager( 2887): 	at dlh.a(PG:140)
E/BaseSyncManager( 2887): 	at dqo.a(PG:224)
E/BaseSyncManager( 2887): 	at dlt.run(PG:9618)
E/BaseSyncManager( 2887): 	at dlr.run(PG:3031)
,D/WifiService(  760): releaseWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@2bdacd48}
,D/NativeLibraryUtils( 3545): Install completed successfully. count=13 extracted=0
,W/libprocessgroup(  760): failed to open /acct/uid_10070/pid_2328/cgroup.procs: No such file or directory
,I/ActivityManager(  760): Killing 1926:com.android.providers.calendar/u0a2 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10002/pid_1926/cgroup.procs: No such file or directory
,D/WVCdm   (  183): Instantiating CDM.
,I/WVCdm   (  183): CdmEngine::OpenSession
I/WVCdm   (  183): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  183): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DrmWidevineDash(  183): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  183): Service_Initialize: starts!
D/QSEECOMAPI: (  183): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  183): App is not loaded in QSEE
,D/QSEECOMAPI: (  183): Loaded image: APP id = 3
,D/DrmWidevineDash(  183): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  183): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb47d9000
,E/DrmWidevineDash(  183): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb47d9000
,D/DrmWidevineDash(  183): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  183): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  183): hlos api version =  9
D/DrmWidevineDash(  183): tz api version =  9
,D/DrmWidevineDash(  183): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  183): OEMCrypto_IsKeyboxValid: starts!
,I/ActivityManager(  760): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3588 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/DrmWidevineDash(  183): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  183): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  183): OEMCrypto_OpenSession: starts! SID=0xbefe9500
,D/DrmWidevineDash(  183): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  183): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  183): OEMCrypto_GetRandom: starts! randomData=0xb6172268, dataLength=8
,D/DrmWidevineDash(  183): OEMCrypto_GetRandom: ends! returns 0
,I/GoogleURLConnFactory( 3545): Using platform SSLCertificateSocketFactory
,D/DrmWidevineDash(  183): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb61aa600, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  183): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  183): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  183): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  183): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  183): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  183): OEMCrypto_GetDeviceID: starts! deviceID=0xaf001440, idLength=0xaeeff710
,D/DrmWidevineDash(  183): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  183): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  183): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  183): OEMCrypto_SupportsUsageTable: wv_app_version = 21
D/DrmWidevineDash(  183): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  183): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  183): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  183): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  183): hlos api version =  9
,D/DrmWidevineDash(  183): tz api version =  9
D/DrmWidevineDash(  183): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  183): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  183): OEMCrypto_GenerateNonce: ends! returns 0
,D/WVCdm   (  183): PrepareKeyRequest: nonce=2201042665
D/DrmWidevineDash(  183): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xaf101600
,D/DrmWidevineDash(  183): message_length=1597, signature=0xb309b280, signature_length=2934961908
,W/ResourcesManager( 3588): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/VacuumService( 1361): Vacuum at: now=1448966918001 tag=VacuumService
,I/art     ( 1361): Explicit concurrent mark sweep GC freed 30507(1863KB) AllocSpace objects, 15(240KB) LOS objects, 39% free, 19MB/33MB, paused 914us total 36.854ms
,I/CalendarProvider2( 3588): Created com.android.providers.calendar.CalendarAlarmManager@243fe019(com.android.providers.calendar.CalendarProvider2@11d038de)
,D/DrmWidevineDash(  183): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  183): CdmEngine::CloseSession
D/DrmWidevineDash(  183): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  183): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  183): L3 Terminate.
,D/DrmWidevineDash(  183): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  183): Service_Uninitialize: starts!
,D/QSEECOMAPI: (  183): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  183): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  183): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  183): OEMCrypto_Terminate: ends! returns 0
,I/art     (  760): Explicit concurrent mark sweep GC freed 25718(1149KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 884us total 53.650ms
,D/WearableService( 1316): callingUid 10008, callindPid: 1316
,E/MDM     ( 1316): [135] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1562): Restart initialization of location
,D/GCM     ( 1361): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1361): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 1562): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/GCoreFlp( 1316): No location to return for getLastLocation()
,W/FusedLocationProvider( 1361): location=null
,I/dex2oat ( 3620): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=33 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 3620): dex2oat took 42.499ms (threads: 4)
,I/Adreno-EGL( 3545): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AbstractGoogleClient( 2004): Application name is not set. Call Builder#setApplicationName.
,I/AnalyticsLogBase( 2004): PlayLogger.onLoggerConnected
,I/Adreno-EGL( 3545): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/WVCdm   (  183): CdmEngine::OpenSession
I/WVCdm   (  183): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  183): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  183): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  183): Service_Initialize: starts!
D/QSEECOMAPI: (  183): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  183): App is not loaded in QSEE
,D/QSEECOMAPI: (  183): Loaded image: APP id = 3
,D/DrmWidevineDash(  183): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  183): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb47d9000
E/DrmWidevineDash(  183): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb47d9000
,D/DrmWidevineDash(  183): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  183): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  183): hlos api version =  9
D/DrmWidevineDash(  183): tz api version =  9
D/DrmWidevineDash(  183): OEMCrypto_APIVersion: ends! returns version 9
,D/DrmWidevineDash(  183): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  183): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  183): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  183): OEMCrypto_OpenSession: starts! SID=0xae7db940
,D/DrmWidevineDash(  183): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  183): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  183): OEMCrypto_GetRandom: starts! randomData=0xb6172268, dataLength=8
,D/DrmWidevineDash(  183): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  183): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb46c4000, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  183): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  183): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  183): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  183): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  183): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  183): OEMCrypto_GetDeviceID: starts! deviceID=0xaf001480, idLength=0xb4bff710
,D/DrmWidevineDash(  183): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  183): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  183): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  183): OEMCrypto_SupportsUsageTable: wv_app_version = 21
D/DrmWidevineDash(  183): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  183): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  183): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  183): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  183): hlos api version =  9
D/DrmWidevineDash(  183): tz api version =  9
,D/DrmWidevineDash(  183): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  183): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  183): OEMCrypto_GenerateNonce: ends! returns 0
,D/WVCdm   (  183): PrepareKeyRequest: nonce=1634788381
D/DrmWidevineDash(  183): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb4ac4600
D/DrmWidevineDash(  183): message_length=1632, signature=0xb4a9d280, signature_length=3032479476
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,D/DrmWidevineDash(  183): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  183): CdmEngine::CloseSession
D/DrmWidevineDash(  183): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  183): OEMCrypto_CloseSession: ends! returns 0
,I/WVCdm   (  183): L3 Terminate.
D/DrmWidevineDash(  183): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  183): Service_Uninitialize: starts!
D/QSEECOMAPI: (  183): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  183): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  183): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  183): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 3545): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/CalendarProvider2( 3588): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 3588): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/CheckinRequestBuilder( 1562): Classify the device as Phone.
,I/CheckinTask( 1562): Sending checkin request (9548 bytes)
,W/BaseAppContext( 1316): Using Auth Proxy for data requests.
,I/CalendarSyncAdapter( 2004): Found no pending settings
,I/art     ( 1316): Explicit concurrent mark sweep GC freed 17041(1154KB) AllocSpace objects, 19(304KB) LOS objects, 40% free, 19MB/32MB, paused 1.064ms total 38.010ms
,E/DataBuffer( 1316): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@23f9d25b)
,I/ActivityManager(  760): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=3661 uid=10070 gids={50070, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/CheckinResponseProcessor( 1562): From server: 1 gservices updates and 0 deletes
,I/Gmail   ( 3661): getAccountsCursor
,D/ActivityThread( 3661): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  760): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=3684 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/CertBlacklister(  760): Certificate blacklist changed, updating...
,I/CertBlacklister(  760): Certificate blacklist updated
,W/GAV2    ( 3661): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/GservicesProvider( 1361): main difference update completed
,I/CheckinRequestBuilder( 1562): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1562): Failed to find provider info for com.google.android.wearable.settings
,I/Babel_SMS( 1794): ApnsOta: OTA version -1
,I/Exchange( 3684): EasService.onCreate
,W/ActivityManager(  760): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/Gmail   ( 3661): Sync started for account: account:61035162
,I/Gmail   ( 3661): Observing account changes for notifications
,I/Exchange( 3684): RestartPingTask
,I/Exchange( 3684): RestartPingsTask did not start any pings.
I/Exchange( 3684): PSS stopIfIdle
I/Exchange( 3684): PSS has no active accounts; stopping service.
,I/Gmail   ( 3661): getAccountsCursor
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Exchange( 3684): onDestroy
I/ActivityManager(  760): Killing 1483:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,E/SQLiteLog( 3661): (283) recovered 53 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/art     (  760): Explicit concurrent mark sweep GC freed 22355(941KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.278ms total 54.972ms
,I/Gmail   ( 3661): notifyAccountChanged
,I/Gmail   ( 3661): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3661): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3661): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3661): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/libprocessgroup(  760): failed to open /acct/uid_10013/pid_1483/cgroup.procs: No such file or directory
,I/ActivityManager(  760): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=3741 uid=10013 gids={50013, 9997, 3003} abi=armeabi-v7a
,I/art     ( 1361): Explicit concurrent mark sweep GC freed 23617(1295KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 19MB/33MB, paused 697us total 23.834ms
,I/Gmail   ( 3661): notifyAccountChanged
,I/ContactAccountLoggerTas( 1374): canRun() : Opted Out
,I/ActivityManager(  760): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3770 uid=10036 gids={50036, 9997, 3003} abi=armeabi-v7a
,I/Search.GservicesUpdateTask( 1374): Updating Gservices keys
,I/Gmail   ( 3661): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 11566, normalSync: true
,E/UpdateRequestReceiver( 3770): Received malformed URL while handling Gservices.CHANGED_ACTION
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3661): getAccountsCursor
,E/UpdateRequestReceiver( 3770): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/ContactAccountLoggerTas( 1374): canRun() : Opted Out
I/ContactAccountLoggerTas( 1374): canRun() : Opted Out
,I/ContactAccountLoggerTas( 1374): canRun() : Opted Out
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/UpdateRequestReceiver( 3770): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 3770): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/Gmail   ( 3661): getAccountsCursor
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1361): Explicit concurrent mark sweep GC freed 6879(366KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 19MB/33MB, paused 898us total 24.649ms
,I/CheckinRequestBuilder( 1562): Classify the device as Phone.
,W/ResourcesManager( 3661): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3661): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  760): Killing 2853:com.android.musicfx/u0a15 (adj 15): empty #17
,V/JNIHelp ( 3661): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/libprocessgroup(  760): failed to open /acct/uid_10015/pid_2853/cgroup.procs: No such file or directory
,W/System  ( 3661): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[directory "."],nativeLibraryDirectories=[/vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3661): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1316): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,D/Finsky  ( 2386): [230] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2386): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager(  760): Killing 2767:com.google.android.gms:car/u0a8 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10008/pid_2767/cgroup.procs: No such file or directory
,I/GCoreUlr( 1316): DispatchingService.onCreate()
,I/ContactAccountLoggerTas( 1374): canRun() : Opted Out
,I/art     ( 1562): Explicit concurrent mark sweep GC freed 23953(1685KB) AllocSpace objects, 14(224KB) LOS objects, 39% free, 22MB/38MB, paused 866us total 37.276ms
,I/GCoreUlr( 1316): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,W/SQLiteConnectionPool( 1562): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/GCoreUlr( 1316): Unbound from all location providers
,I/art     ( 1361): Explicit concurrent mark sweep GC freed 5910(285KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 19MB/33MB, paused 1.081ms total 41.088ms
,I/GCoreUlr( 1316): DispatchingService.onDestroy()
I/GCoreUlr( 1316): Stopping handler for UlrDispSvcFast
,I/art     (  760): Explicit concurrent mark sweep GC freed 11707(496KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 962us total 57.007ms
,I/GCoreUlr( 1316): Unbound from all location providers
,I/CheckinTask( 1562): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1562): Checking schedule, now: 1448966921114 next: 1449009088099
I/CheckinService( 1562): active receiver: disabled
,D/CheckinService( 1562): Recording last checkin time for package unspecified as 1448966921138
,D/SystemEventReceiver( 1562): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 1562): Updating ocr activity enabled=false
,W/ActivityManager(  760): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,W/Gmail   ( 3661): MailSyncAdapterService#onSyncCanceled Thread[SyncAdapterThread-1,5,main]
W/Gmail   ( 3661): MailEngine != null account: account:61035162
,I/CheckinService( 1562): Checkin interval check for package: unspecified last checkin: 1448966921138 min interval config: 0 actual interval: 104
,I/CheckinService( 1562): Checking schedule, now: 1448966921254 next: 1449009088099
I/CheckinService( 1562): active receiver: disabled
,I/art     ( 1361): Explicit concurrent mark sweep GC freed 4519(224KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 19MB/33MB, paused 749us total 31.005ms
,I/SystemUpdateService( 1562): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 1562): onCreate
,D/SystemUpdateService( 1562): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/OcrModelManager( 1562): Updating downloaded model state (gservices changed)
,I/SystemUpdateService( 1562): active receiver: enabled
,D/GCM     ( 1361): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,I/GCoreUlr( 1316): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1316): DispatchingService.onCreate()
,I/SystemUpdateService( 1562): showing system update notification
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1562): retry (wakeup: false) in 3599935 ms
,D/SystemUpdateService( 1562): onDestroy
,E/SQLiteLog( 3588): (284) automatic index on view_events(_id)
,I/GCoreUlr( 1316): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,I/art     ( 1562): Explicit concurrent mark sweep GC freed 13854(882KB) AllocSpace objects, 9(144KB) LOS objects, 40% free, 22MB/38MB, paused 843us total 34.619ms
,D/ChimeraCfgMgr( 1562): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SyncManager(  760): failed sync operation thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 34406, reason: Periodic, SyncResult: syncAlreadyInProgress: true stats []
,D/ChimeraCfgMgr( 1562): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/GCM     ( 1361): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 1562): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1361): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1316): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1316): Unbound from all location providers
,I/GCoreUlr( 1316): DispatchingService.onDestroy()
I/GCoreUlr( 1316): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1316): Unbound from all location providers
,W/art     ( 2602): Attempt to remove local handle scope entry from IRT, ignoring
,I/ValidateNoPeople(  760): mEvictionCount: 0
,E/SQLiteLog( 1332): (284) automatic index on sqlite_sq_AF8E8100(STAT_DATA_ID)
,E/SQLiteLog( 1332): (284) automatic index on sqlite_sq_AF8264C0(STAT_DATA_ID)
,E/SQLiteLog( 1332): (284) automatic index on sqlite_sq_AF557380(STAT_DATA_ID)
,E/SQLiteLog( 1332): (284) automatic index on sqlite_sq_AF53CBA0(STAT_DATA_ID)
,I/art     ( 1316): Explicit concurrent mark sweep GC freed 21017(1246KB) AllocSpace objects, 8(128KB) LOS objects, 39% free, 19MB/32MB, paused 2.724ms total 54.371ms
,I/art     ( 3661): Explicit concurrent mark sweep GC freed 40040(2MB) AllocSpace objects, 15(263KB) LOS objects, 24% free, 18MB/25MB, paused 324us total 70.850ms
,I/art     (  760): Explicit concurrent mark sweep GC freed 21248(995KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.059ms total 67.436ms
,I/Gmail   ( 3661): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 11566, normalSync: true
,I/art     ( 1361): Explicit concurrent mark sweep GC freed 22189(1268KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 20MB/33MB, paused 558us total 33.920ms
,E/Gmail   ( 3661): Connection to search failed: 15
,I/Gmail   ( 3661): notifyAccountChanged
,I/Gmail   ( 3661): getAccountsCursor
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GHttpClientFactory( 2474): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/Gmail   ( 3661): notifyAccountChanged
,I/GoogleURLConnFactory( 2474): Using platform SSLCertificateSocketFactory
,W/Gmail   ( 3661): Sync complete for account: account:61035162
,I/Gmail   ( 3661): getAccountsCursor
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  760): handleSyncHandlerMessage: dropping since the sync is no longer active: startTime 89248, mTimeoutStartTime 89248, mHistoryRowId 11, syncOperation thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 122325, reason: Periodic
,I/MusicLifecycle( 2474): Sync started
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SyncAdapterService( 3335): Ignoring sync request for non-current account
,D/DelayedSyncController(  948): Delaying sync.
,W/BaseAppContext( 1562): Using Auth Proxy for data requests.
W/BaseAppContext( 1562): Using Auth Proxy for data requests.
,W/BaseAppContext( 1562): Using Auth Proxy for data requests.
,W/BaseAppContext( 1562): Using Auth Proxy for data requests.
,W/BaseAppContext( 1562): Using Auth Proxy for data requests.
,W/BaseAppContext( 1562): Using Auth Proxy for data requests.
,W/BaseAppContext( 1562): Using Auth Proxy for data requests.
,I/ActivityManager(  760): Start proc com.google.android.videos for service com.google.android.videos/.store.SyncService: pid=3882 uid=10077 gids={50077, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/MusicSyncAdapter( 2474): Will attempt periodic sync for account: Account {name=thalitester@gmail.com, type=com.google}
I/MusicSyncAdapter( 2474): Periodic update
,W/ResourcesManager( 3882): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,W/MusicApiClient( 2474): Activity events list is null or empty. Skip reporting.
,I/MusicLifecycle( 2474): Sync ended
,I/MusicLeanback( 2474): Conditions not met for autocaching. okToAttempt=false
,I/MusicLeanback( 2474): Stop autocaching.
,I/ActivityManager(  760): Start proc com.google.android.apps.cloudprint:sync for service com.google.android.apps.cloudprint/.printdialog.services.CloudPrintSyncService: pid=3910 uid=10035 gids={50035, 9997, 3003, 1028} abi=armeabi-v7a
,E/GmsUtils( 2474): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 2474): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/ActivityManager(  760): Killing 2724:com.android.defcontainer/u0a5 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10005/pid_2724/cgroup.procs: No such file or directory
,I/ActivityManager(  760): Start proc com.google.android.apps.cloudprint for service com.google.android.apps.cloudprint/.printdialog.services.NotificationIntentService: pid=3939 uid=10035 gids={50035, 9997, 3003, 1028} abi=armeabi-v7a
,I/art     (  194): Explicit concurrent mark sweep GC freed 705(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 174us total 8.590ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 166us total 7.323ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 167us total 8.715ms
,I/com.google.android.apps.cloudprint.printdialog.database.CloudPrintSyncAdapter( 3910): Sync request not initiated by GCP app. Dropping
,I/ActivityManager(  760): Killing 3027:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  760): Client connection lost with reason: 4
,W/libprocessgroup(  760): failed to open /acct/uid_1000/pid_3027/cgroup.procs: No such file or directory
,I/ActivityManager(  760): Killing 3500:com.qualcomm.timeservice/u0a76 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10076/pid_3500/cgroup.procs: No such file or directory
,D/PlayMovies( 3882): PersistentCache.cleanup:103 Cache is below limit, no need to shrink: [size=0, limit=5242880]
,D/PlayMovies( 3882): TransferService.onCreate:52 creating transfer service
,W/VideoCapabilities( 3882): Unrecognized profile 2130706433 for video/avc
,I/art     ( 1361): Explicit concurrent mark sweep GC freed 6428(322KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 19MB/33MB, paused 1.670ms total 46.198ms
,I/VideoCapabilities( 3882): Unsupported profile 4 for video/mp4v-es
,I/art     (  760): Explicit concurrent mark sweep GC freed 22341(874KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 954us total 72.592ms
,E/Auth.Api.Credentials( 1562): [CredentialSyncAdapter] Unknown sync event.
,W/ResourcesManager( 1562): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/CalendarSyncAdapter( 2004): Found no pending settings
,I/PlayMovies( 3882): SyncService.syncAllPurchasesAndWishlist:151 Starting sync for 515013DC511638B0584069811EF28701C0771BF5
,D/GetConfigurationSnapshotOperation( 1361): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1361): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1361): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 1361): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/ActivityManager(  760): Killing 3528:com.google.android.deskclock/u0a38 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10038/pid_3528/cgroup.procs: No such file or directory
,I/ActivityManager(  760): Killing 1794:com.google.android.talk/u0a54 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10054/pid_1794/cgroup.procs: No such file or directory
,D/GetCommittedConfigurationOperation( 1361): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/PlayMovies( 3882): SyncService.waitForCompletion:177 Sync completed for 515013DC511638B0584069811EF28701C0771BF5 purchases
,I/PlayMovies( 3882): SyncService.waitForCompletion:177 Sync completed for 515013DC511638B0584069811EF28701C0771BF5 wishlist
,I/ActivityManager(  760): Killing 2887:com.google.android.apps.docs/u0a40 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10040/pid_2887/cgroup.procs: No such file or directory
,D/GetCommittedConfigurationOperation( 1361): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/GAV2    ( 3661): Thread[GAThread,5,main]: No campaign data found.
,D/GetCommittedConfigurationOperation( 1361): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1361): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/Uploader( 1361):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1361): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1361): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1361): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1361): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1361): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1361): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1361): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1361): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1361): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,W/PackageSettings(  760): Skipping PackageSetting{1a212b06 com.example.hello/10277} due to missing metadata
,I/UpdateIcingCorporaServi( 1374): Updating corpora: APPS=com.google.android.videos, CONTACTS=MAYBE
,I/InputReader(  760): Reconfiguring input devices.  changes=0x00000010
,I/InputReader(  760): Reconfiguring input devices.  changes=0x00000010
,W/Launcher( 1290): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@20b00abf new=com.google.android.velvet.VelvetApplication@20b00abf
,D/PackageBroadcastService( 1562): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.videos
,I/UpdateIcingCorporaServi( 1374): UpdateCorporaTask done [took 65 ms] updated apps [took 65 ms] 
,D/BackupManagerService(  760): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.videos flg=0x4000010 (has extras) }
,I/ActivityManager(  760): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=4037 uid=10054 gids={50054, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/PeopleContactsSync( 1562): CP2 sync disabled
,D/BackupManagerService(  760): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  760): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  760): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  760): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  760): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@21eae189
,W/ResourcesManager( 4037): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/GmsNetworkLocationProvi( 1316): DISABLE
,I/GCoreNlp( 1316): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1290): Deferring update until onResume
,W/ResourcesManager( 1290): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1290): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1290): Deferring update until onResume
,I/Launcher( 1290): Deferring update until onResume
,I/Launcher( 1290): Deferring update until onResume
,I/Babel_SMS( 4037): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 4037): MmsConfig.loadMmsSettings
,I/Babel_SMS( 4037): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
I/Babel_SMS( 4037): MmsConfig.loadFromDatabase
,E/Babel_SMS( 4037): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 4037): MmsConfig.loadFromResources
,E/Babel_SMS( 4037): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 4037): MmsConfig.loadMmsSettings: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
,I/Babel_SMS( 4037): ApnsOta: OTA version -1
,I/Babel   ( 4037): deleted: false for 0
,W/Settings( 4037): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 4037): startup - clean
,I/UpdateIcingCorporaServi( 1374): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
W/Launcher( 1290): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@20b00abf new=com.google.android.velvet.VelvetApplication@20b00abf
,D/PackageBroadcastService( 1562): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1562): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1562): updateResources: need to parse f{com.google.android.gms}
,W/VideoCapabilities( 4037): Unrecognized profile 2130706433 for video/avc
,I/art     ( 1562): Explicit concurrent mark sweep GC freed 15553(1000KB) AllocSpace objects, 15(240KB) LOS objects, 40% free, 23MB/38MB, paused 835us total 31.338ms
,I/VideoCapabilities( 4037): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4037): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4037): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4037): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4037): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 4037): onServiceConnected
W/Babel   ( 4037): Attempted to change video mute state without an active call.
,I/UpdateIcingCorporaServi( 1374): UpdateCorporaTask done [took 217 ms] updated apps [took 217 ms] 
,W/ResourcesManager( 4037): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4037): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4037): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/System  ( 4037): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 4037): Installed default security provider GmsCore_OpenSSL
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/ActivityManager(  760): Killing 3290:com.google.android.youtube/u0a80 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10080/pid_3290/cgroup.procs: No such file or directory
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/ActivityManager(  760): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=4116 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,W/Gmail   ( 3661): Sync started for account: account:61035162
,I/Gmail   ( 3661): notifyAccountChanged
,I/Gmail   ( 3661): getAccountsCursor
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  760): Explicit concurrent mark sweep GC freed 38310(1976KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 27MB/41MB, paused 1.106ms total 61.441ms
,I/Gmail   ( 3661): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 11566, normalSync: true
,W/ResourcesManager( 3661): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3661): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GAv4    ( 4116): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4116):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4116):   adb logcat -s GAv4
,W/GAv4    ( 4116): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4116): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4116): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 4116): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
,W/ResourcesManager( 4116): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4116): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4116): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/System  ( 4116): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 4116): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3661): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 11700, normalSync: true
,I/Gmail   ( 3661): lowestBackward conversation id 0
,V/NQFileLogger( 1361): [201] e.a: about to write to file
,V/ProcessReports( 1361): [201] ProcessReportsService.a: If not already scheduled, schedule for 3600 to 14400 seconds from now (but might be processed inline after 900 seconds instead)
,I/Gmail   ( 3661): notifyAccountChanged
,I/Gmail   ( 3661): getAccountsCursor
,W/Gmail   ( 3661): Sync complete for account: account:61035162
,I/ActivityManager(  760): Killing 3065:com.google.android.keep/u0a71 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10071/pid_3065/cgroup.procs: No such file or directory
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/Icing   ( 1562): Indexing 009F7E1EAB88E81C4EB4149FAD093AD3E8757DF2 from com.google.android.gm
,I/Gmail   ( 3661): Backfilling search sequence table
,I/Icing   ( 1562): Indexing done 009F7E1EAB88E81C4EB4149FAD093AD3E8757DF2
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/ClearcutLoggerApiImpl( 1316): disconnect managed GoogleApiClient
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector connect called
I/jxcore-log( 2955): 
I/jxcore-log( 2955): Coordinator is now connected to the server!
I/jxcore-log( 2955): 
,I/chromium( 2955): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  760): Killing 3684:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10069/pid_3684/cgroup.procs: No such file or directory
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/UdcCache:FPQuery( 1562): Bootstrapping UDC settings cache for all accounts
,I/jxcore-log( 2955): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector command called
I/jxcore-log( 2955): 
I/jxcore-log( 2955): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":50000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":21,"addressList":[{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"34:FC:EF:9D:93:0B","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"7C:F9:0E:51:18:22","tryCount":0},{"address":"38:94:96:B5:06:DC","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"80:01:84:8A:B3
I/jxcore-log( 2955): Start now : testSendData.js
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":50000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 21
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): check server
I/jxcore-log( 2955): 
I/jxcore-log( 2955): serverPort is 59747
I/jxcore-log( 2955): 
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): initialize: 34:FC:EF:11:AE:67 LGE-Nexus 5_PT5003
D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 2955): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): setState: INITIALIZED
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5003","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): start: OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 2955): start: OK
I/jxcore-log( 2955): StartBroadcasting started ok
I/jxcore-log( 2955): 
I/jxcore-log( 2955): do fake peer & start
I/jxcore-log( 2955): 
I/jxcore-log( 2955): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:54:31.835Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:54:31.836Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:54:31.836Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
W/io.jxcore.node.ConnectionHelper( 2955): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to null in address 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: null 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to null in address 44:80:EB:7B:5A:05
I/jxcore-log( 2955): 2015-12-01T10:54:31.840Z SendDataTCPServer.js: TCP/IP server is bound to port: 59747
I/jxcore-log( 2955): 
I/chromium( 2955): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
I/io.jxcore.node.ConnectionHelper( 2955): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 2955): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Waiting for incoming connections...
,W/bt-btif ( 3016): info:x10
,D/        ( 3016): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 3016): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3016): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
E/bt-btif ( 3016): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3016): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3016): Entering PendingCommandState State
,I/ActivityManager(  760): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest: pid=4250 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3bb88c04:true
,I/ActivityManager(  760): Killing 3741:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10013/pid_3741/cgroup.procs: No such file or directory
,I/BluetoothBondStateMachine( 3016): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 3016): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 3016): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:1
W/bt-btif ( 3016): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3016): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Outgoing connection initialized (thread ID: 275)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 275)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 275)
,I/BluetoothBondStateMachine( 3016): StableState(): Entering Off State
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesRead: Read 81 bytes successfully (thread ID: 275)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Handshake succeeded with [44:80:EB:7B:5A:05 motorola-XT1072_PT6938 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT6938 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 275)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT6938 44:80:EB:7B:5A:05]
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing connection, peer ID: 44:80:EB:7B:5A:05, name: motorola-XT1072_PT6938, Bluetooth address: 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 2955): addNewPeerToListAndNotify: Adding peer with ID 44:80:EB:7B:5A:05
,I/io.jxcore.node.OutgoingSocketThread( 2955): Constructed
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 2955): Server socket local port: 55770
,I/io.jxcore.node.ConnectionHelper( 2955): Outgoing connection is using port 55770
I/io.jxcore.node.OutgoingSocketThread( 2955): Now accepting connections...
,I/jxcore-log( 2955): 2015-12-01T10:54:37.983Z SendDataConnector.js: CLIENT connected to 55770, error: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:54:37.984Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:54:37.985Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=0
,W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3016): dm_pm_timer expires
W/bt-btif ( 3016): dm_pm_timer expires 0
,W/bt-btif ( 3016): proc dm_pm_timer expires
,I/jxcore-log( 2955): 2015-12-01T10:54:42.987Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:54:42.988Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2955): 
,I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 44:80:EB:7B:5A:05
I/io.jxcore.node.OutgoingSocketThread( 2955): close
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 2955): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T10:54:47.995Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:54:47.995Z SendDataConnector.js: Connect (retry count 1) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:54:47.996Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:54:47.996Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to XT1072 in address 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: XT1072 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to XT1072 in address 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3016): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Outgoing connection initialized (thread ID: 278)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 278)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 278)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesRead: Read 81 bytes successfully (thread ID: 278)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Handshake succeeded with [44:80:EB:7B:5A:05 motorola-XT1072_PT6938 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT6938 44:80:EB:7B:5A:05]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT6938 44:80:EB:7B:5A:05]
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing connection, peer ID: 44:80:EB:7B:5A:05, name: motorola-XT1072_PT6938, Bluetooth address: 44:80:EB:7B:5A:05
I/io.jxcore.node.OutgoingSocketThread( 2955): Constructed
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing socket thread created successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 278)
,I/io.jxcore.node.OutgoingSocketThread( 2955): Server socket local port: 46105
I/io.jxcore.node.ConnectionHelper( 2955): Outgoing connection is using port 46105
I/io.jxcore.node.OutgoingSocketThread( 2955): Now accepting connections...
,I/jxcore-log( 2955): 2015-12-01T10:54:48.683Z SendDataConnector.js: CLIENT connected to 46105, error: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:54:48.683Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:54:48.684Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,W/bt-btif ( 3016): dm_pm_timer expires
W/bt-btif ( 3016): dm_pm_timer expires 0
W/bt-btif ( 3016): proc dm_pm_timer expires
,I/jxcore-log( 2955): 2015-12-01T10:54:53.685Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:54:53.686Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2955): 
,I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 44:80:EB:7B:5A:05
I/io.jxcore.node.OutgoingSocketThread( 2955): close
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 2955): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T10:54:58.703Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:54:58.703Z SendDataConnector.js: Connect (retry count 2) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:54:58.704Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:54:58.705Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to XT1072 in address 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: XT1072 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to XT1072 in address 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3016): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Outgoing connection initialized (thread ID: 281)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 281)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 281)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesRead: Read 81 bytes successfully (thread ID: 281)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Handshake succeeded with [44:80:EB:7B:5A:05 motorola-XT1072_PT6938 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT6938 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 281)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT6938 44:80:EB:7B:5A:05]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing connection, peer ID: 44:80:EB:7B:5A:05, name: motorola-XT1072_PT6938, Bluetooth address: 44:80:EB:7B:5A:05
I/io.jxcore.node.OutgoingSocketThread( 2955): Constructed
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 2955): Server socket local port: 37519
I/io.jxcore.node.ConnectionHelper( 2955): Outgoing connection is using port 37519
I/io.jxcore.node.OutgoingSocketThread( 2955): Now accepting connections...
,I/jxcore-log( 2955): 2015-12-01T10:54:59.272Z SendDataConnector.js: CLIENT connected to 37519, error: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:54:59.272Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:54:59.272Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,W/bt-btif ( 3016): dm_pm_timer expires
W/bt-btif ( 3016): dm_pm_timer expires 0
W/bt-btif ( 3016): proc dm_pm_timer expires
,I/jxcore-log( 2955): 2015-12-01T10:55:04.273Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:55:04.273Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2955): 
,I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 44:80:EB:7B:5A:05
I/io.jxcore.node.OutgoingSocketThread( 2955): close
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 2955): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T10:55:09.279Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:55:09.279Z SendDataConnector.js: Connect (retry count 3) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:55:09.279Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:55:09.279Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to XT1072 in address 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: XT1072 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to XT1072 in address 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3016): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,W/bt-btif ( 3016): info:x10
,D/        ( 3016): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
E/BluetoothRemoteDevices( 3016): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3016): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3016): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3016): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3016): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3016): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3016): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 3016): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3016): StableState(): Entering Off State
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:255
W/bt-btif ( 3016): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3016): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection initialized (thread ID: 284)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Waiting for incoming connections...
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 284)
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesRead: Read 76 bytes successfully (thread ID: 284)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Got valid identity from [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 284)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): removeThreadFromList: Removing thread with ID 284
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Handshake thread disposed (thread ID: 284)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onIncomingConnectionConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 284)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming connection, peer ID: F8:95:C7:87:3C:51, name: LGE-LG-H815_PT920, Bluetooth address: F8:95:C7:87:3C:51
,I/io.jxcore.node.ConnectionHelper( 2955): addNewPeerToListAndNotify: Adding peer with ID F8:95:C7:87:3C:51
,I/io.jxcore.node.IncomingSocketThread( 2955): Constructed
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming socket thread using port 0 and is now connected
,I/io.jxcore.node.IncomingSocketThread( 2955): Entering thread
,I/jxcore-log( 2955): 2015-12-01T10:55:30.766Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2955): 
,I/io.jxcore.node.IncomingSocketThread( 2955): Local host address: localhost/127.0.0.1, port: 59747
I/io.jxcore.node.IncomingSocketThread( 2955): Local streams created successfully, starting stream copying threads...
,I/io.jxcore.node.SocketThreadBase( 2955): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 2955): Exiting thread
,E/bt-btif ( 3016): DISCOVERY_COMP_EVT slot id:8, failed to find channle,                                       status:1, scn:0
E/bt-btm  ( 3016): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 3016): invalid rfc slot id: 8
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [44:80:EB:7B:5A:05 motorola-XT1072_PT6938 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): shutdown
I/jxcore-log( 2955): 2015-12-01T10:55:34.347Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:55:34.347Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:55:34.348Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,D/BluetoothMapService( 3016): onReceive
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@394fec22:true
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: XT1072
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2955): 2015-12-01T10:55:39.349Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T10:55:39.350Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2955): 
,W/bt-btif ( 3016): invalid rfc slot id: 4
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: bt socket closed, read return: -1
,E/io.jxcore.node.SocketThreadBase( 2955): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 285
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 2955): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: Socket closed
,I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,W/bt-rfcomm( 3016): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
W/bt-rfcomm( 3016): RFCOMM_DisconnectInd LCID:0x48
,I/jxcore-log( 2955): 2015-12-01T10:55:41.312Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2955): 
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:255
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection initialized (thread ID: 288)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 288)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesRead: Read 76 bytes successfully (thread ID: 288)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Got valid identity from [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 288)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): removeThreadFromList: Removing thread with ID 288
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Handshake thread disposed (thread ID: 288)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onIncomingConnectionConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming connection, peer ID: F8:95:C7:87:3C:51, name: LGE-LG-H815_PT920, Bluetooth address: F8:95:C7:87:3C:51
,I/io.jxcore.node.IncomingSocketThread( 2955): Constructed
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming socket thread using port 0 and is now connected
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 288)
,I/io.jxcore.node.IncomingSocketThread( 2955): Entering thread
,I/io.jxcore.node.IncomingSocketThread( 2955): Local host address: localhost/127.0.0.1, port: 59747
I/io.jxcore.node.IncomingSocketThread( 2955): Local streams created successfully, starting stream copying threads...
I/io.jxcore.node.SocketThreadBase( 2955): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T10:55:41.389Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T10:55:44.359Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:55:44.360Z SendDataConnector.js: Connect (retry count 4) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T10:55:44.363Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T10:55:44.364Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to XT1072 in address 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: XT1072 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to XT1072 in address 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3016): info:x10
,D/        ( 3016): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: XT1072
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:1
W/bt-btif ( 3016): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3016): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Outgoing connection initialized (thread ID: 293)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 293)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 293)
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesRead: Read 81 bytes successfully (thread ID: 293)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Handshake succeeded with [44:80:EB:7B:5A:05 motorola-XT1072_PT6938 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT6938 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 293)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT6938 44:80:EB:7B:5A:05]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing connection, peer ID: 44:80:EB:7B:5A:05, name: motorola-XT1072_PT6938, Bluetooth address: 44:80:EB:7B:5A:05
I/io.jxcore.node.OutgoingSocketThread( 2955): Constructed
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 2955): Server socket local port: 49946
I/io.jxcore.node.ConnectionHelper( 2955): Outgoing connection is using port 49946
I/io.jxcore.node.OutgoingSocketThread( 2955): Now accepting connections...
,I/jxcore-log( 2955): 2015-12-01T10:55:46.394Z SendDataConnector.js: CLIENT connected to 49946, error: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:55:46.394Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T10:55:46.397Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 44:80:EB:7B:5A:05
I/io.jxcore.node.OutgoingSocketThread( 2955): close
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 2955): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T10:55:46.401Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): ---- round done--------
I/jxcore-log( 2955): 
I/jxcore-log( 2955): ---- gotta redo : 44:80:EB:7B:5A:05, try count now: 1
I/jxcore-log( 2955): 
I/jxcore-log( 2955): do fake peer & start
I/jxcore-log( 2955): 
I/jxcore-log( 2955): Connect to fake peer: 80:01:84:8A:B3:68
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:55:46.402Z SendDataConnector.js: Start called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T10:55:46.402Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:55:46.403Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 80:01:84:8A:B3:68
W/io.jxcore.node.ConnectionHelper( 2955): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to null in address 80:01:84:8A:B3:68
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: null 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to null in address 80:01:84:8A:B3:68
I/chromium( 2955): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 44:80:EB:7B:5A:05 done with result: Listening for incoming connections", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3016): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3016): info:x10
,D/        ( 3016): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3016): aclStateChangeCallback: Device is NULL
,W/bt-btm  ( 3016): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=2
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3016): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3016): onReceive
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: XT1072
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa405124c rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3016): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 1
E/bt-btif ( 3016): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3016): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3016): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3016): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 0
,D/BluetoothAdapterProperties( 3016): Failed to remove device: 80:01:84:8A:B3:68
,I/BluetoothBondStateMachine( 3016): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3016): StableState(): Entering Off State
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: bt socket closed, read return: -1
E/io.jxcore.node.SocketThreadBase( 2955): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 289
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,W/bt-btif ( 3016): invalid rfc slot id: 9
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 2955): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: Socket closed
,I/jxcore-log( 2955): 2015-12-01T10:55:52.245Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2955): 
,W/bt-rfcomm( 3016): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
W/bt-rfcomm( 3016): RFCOMM_DisconnectInd LCID:0x4a
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection initialized (thread ID: 296)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Waiting for incoming connections...
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:255
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 296)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesRead: Read 76 bytes successfully (thread ID: 296)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Got valid identity from [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 296)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): removeThreadFromList: Removing thread with ID 296
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Handshake thread disposed (thread ID: 296)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onIncomingConnectionConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 296)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming connection, peer ID: F8:95:C7:87:3C:51, name: LGE-LG-H815_PT920, Bluetooth address: F8:95:C7:87:3C:51
,I/io.jxcore.node.IncomingSocketThread( 2955): Constructed
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming socket thread using port 0 and is now connected
,I/io.jxcore.node.IncomingSocketThread( 2955): Entering thread
,I/jxcore-log( 2955): 2015-12-01T10:55:52.455Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2955): 
,I/io.jxcore.node.IncomingSocketThread( 2955): Local host address: localhost/127.0.0.1, port: 59747
I/io.jxcore.node.IncomingSocketThread( 2955): Local streams created successfully, starting stream copying threads...
,I/io.jxcore.node.SocketThreadBase( 2955): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 2955): Exiting thread
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-rfcomm( 3016): PORT_StartCnf failed result:5
E/bt-btm  ( 3016): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 3016): invalid rfc slot id: 12
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:319)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,D/BluetoothMapService( 3016): onReceive
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [80:01:84:8A:B3:68 80:01:84:8A:B3:68 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): shutdown
I/jxcore-log( 2955): 2015-12-01T10:55:56.503Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 80:01:84:8A:B3:68 failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:55:56.504Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 80:01:84:8A:B3:68 failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:55:56.505Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 2955): 2015-12-01T10:56:01.507Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:56:01.507Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2955): 
,W/bt-btif ( 3016): invalid rfc slot id: 10
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: bt socket closed, read return: -1
E/io.jxcore.node.SocketThreadBase( 2955): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 297
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 2955): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: Socket closed
,I/jxcore-log( 2955): 2015-12-01T10:56:03.226Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2955): 
,W/bt-rfcomm( 3016): rfc_find_lcid_mcb LCID reused LCID:0x40 current:0x0
W/bt-rfcomm( 3016): RFCOMM_DisconnectInd LCID:0x40
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:255
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection initialized (thread ID: 300)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 300)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesRead: Read 76 bytes successfully (thread ID: 300)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Got valid identity from [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 300)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): removeThreadFromList: Removing thread with ID 300
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Handshake thread disposed (thread ID: 300)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onIncomingConnectionConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 300)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming connection, peer ID: F8:95:C7:87:3C:51, name: LGE-LG-H815_PT920, Bluetooth address: F8:95:C7:87:3C:51
I/io.jxcore.node.IncomingSocketThread( 2955): Constructed
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming socket thread using port 0 and is now connected
,I/io.jxcore.node.IncomingSocketThread( 2955): Entering thread
,I/jxcore-log( 2955): 2015-12-01T10:56:03.357Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2955): 
,I/io.jxcore.node.IncomingSocketThread( 2955): Local host address: localhost/127.0.0.1, port: 59747
I/io.jxcore.node.IncomingSocketThread( 2955): Local streams created successfully, starting stream copying threads...
I/io.jxcore.node.SocketThreadBase( 2955): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 2955): Exiting thread
,W/bt-btif ( 3016): info:x10
,D/        ( 3016): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3016): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3016): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 1
E/bt-btif ( 3016): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3016): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3016): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3016): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 0
,D/BluetoothAdapterProperties( 3016): Failed to remove device: 7C:F9:0E:51:18:22
,I/BluetoothBondStateMachine( 3016): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3016): StableState(): Entering Off State
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:255
W/bt-btif ( 3016): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3016): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection initialized (thread ID: 304)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 304)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesRead: Read 83 bytes successfully (thread ID: 304)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Got valid identity from [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4930 7C:F9:0E:51:18:22]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 304)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): removeThreadFromList: Removing thread with ID 304
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Handshake thread disposed (thread ID: 304)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onIncomingConnectionConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4930 7C:F9:0E:51:18:22]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4930 7C:F9:0E:51:18:22]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming connection, peer ID: 7C:F9:0E:51:18:22, name: samsung-SM-A500FU_PT4930, Bluetooth address: 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 2955): addNewPeerToListAndNotify: Adding peer with ID 7C:F9:0E:51:18:22
I/io.jxcore.node.IncomingSocketThread( 2955): Constructed
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming socket thread using port 0 and is now connected
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 304)
,I/io.jxcore.node.IncomingSocketThread( 2955): Entering thread
,I/io.jxcore.node.IncomingSocketThread( 2955): Local host address: localhost/127.0.0.1, port: 59747
I/io.jxcore.node.IncomingSocketThread( 2955): Local streams created successfully, starting stream copying threads...
,I/io.jxcore.node.SocketThreadBase( 2955): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T10:56:06.196Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T10:56:06.512Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:56:06.513Z SendDataConnector.js: Connect (retry count 1) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:56:06.513Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:56:06.514Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 80:01:84:8A:B3:68
W/io.jxcore.node.ConnectionHelper( 2955): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to HTC Desire 820 in address 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: HTC Desire 820 80:01:84:8A:B3:68
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to HTC Desire 820 in address 80:01:84:8A:B3:68
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3016): invalid rfc slot id: 13
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: bt socket closed, read return: -1
E/io.jxcore.node.SocketThreadBase( 2955): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 301
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 2955): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: Socket closed
,I/jxcore-log( 2955): 2015-12-01T10:56:14.192Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2955): 
,W/bt-rfcomm( 3016): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
W/bt-rfcomm( 3016): RFCOMM_DisconnectInd LCID:0x42
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:255
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection initialized (thread ID: 309)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 309)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesRead: Read 76 bytes successfully (thread ID: 309)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Got valid identity from [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 309)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): removeThreadFromList: Removing thread with ID 309
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Handshake thread disposed (thread ID: 309)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onIncomingConnectionConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 309)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming connection, peer ID: F8:95:C7:87:3C:51, name: LGE-LG-H815_PT920, Bluetooth address: F8:95:C7:87:3C:51
I/io.jxcore.node.IncomingSocketThread( 2955): Constructed
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming socket thread using port 0 and is now connected
,I/io.jxcore.node.IncomingSocketThread( 2955): Entering thread
,I/jxcore-log( 2955): 2015-12-01T10:56:14.376Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2955): 
,I/io.jxcore.node.IncomingSocketThread( 2955): Local host address: localhost/127.0.0.1, port: 59747
I/io.jxcore.node.IncomingSocketThread( 2955): Local streams created successfully, starting stream copying threads...
I/io.jxcore.node.SocketThreadBase( 2955): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 2955): Exiting thread
,W/bt-btif ( 3016): invalid rfc slot id: 15
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: bt socket closed, read return: -1
E/io.jxcore.node.SocketThreadBase( 2955): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 310
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 2955): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: Socket closed
,I/jxcore-log( 2955): 2015-12-01T10:56:14.725Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2955): 
,W/bt-rfcomm( 3016): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
W/bt-rfcomm( 3016): RFCOMM_DisconnectInd LCID:0x46
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3016): invalid rfc slot id: 14
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: bt socket closed, read return: -1
,E/io.jxcore.node.SocketThreadBase( 2955): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
,I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 305
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 2955): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: Socket closed
,I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,I/jxcore-log( 2955): 2015-12-01T10:56:16.861Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2955): 
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3016): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
W/bt-rfcomm( 3016): RFCOMM_DisconnectInd LCID:0x44
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:255
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection initialized (thread ID: 313)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 313)
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051414 rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesRead: Read 83 bytes successfully (thread ID: 313)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Got valid identity from [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4930 7C:F9:0E:51:18:22]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 313)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): removeThreadFromList: Removing thread with ID 313
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Handshake thread disposed (thread ID: 313)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onIncomingConnectionConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4930 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 313)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4930 7C:F9:0E:51:18:22]
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming connection, peer ID: 7C:F9:0E:51:18:22, name: samsung-SM-A500FU_PT4930, Bluetooth address: 7C:F9:0E:51:18:22
I/io.jxcore.node.IncomingSocketThread( 2955): Constructed
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming socket thread using port 0 and is now connected
,I/io.jxcore.node.IncomingSocketThread( 2955): Entering thread
,I/jxcore-log( 2955): 2015-12-01T10:56:18.157Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2955): 
,I/io.jxcore.node.IncomingSocketThread( 2955): Local host address: localhost/127.0.0.1, port: 59747
I/io.jxcore.node.IncomingSocketThread( 2955): Local streams created successfully, starting stream copying threads...
,I/io.jxcore.node.SocketThreadBase( 2955): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 2955): Exiting thread
,E/bt-btm  ( 3016): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3016): onReceive
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: G4-1
,W/bt-btif ( 3016): info:x10
,D/        ( 3016): remote version info [80:01:84:8a:b3:68]: 7, f, 6109
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: HTC Desire 820
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051414 rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa405124c rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:1
W/bt-btif ( 3016): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3016): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Outgoing connection initialized (thread ID: 317)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 317)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 317)
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa405124c rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesRead: Read 84 bytes successfully (thread ID: 317)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Handshake succeeded with [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5457 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5457 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 317)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5457 80:01:84:8A:B3:68]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing connection, peer ID: 80:01:84:8A:B3:68, name: HTC-HTC Desire 820_PT5457, Bluetooth address: 80:01:84:8A:B3:68
,I/io.jxcore.node.ConnectionHelper( 2955): addNewPeerToListAndNotify: Adding peer with ID 80:01:84:8A:B3:68
,I/io.jxcore.node.OutgoingSocketThread( 2955): Constructed
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 2955): Server socket local port: 51368
I/io.jxcore.node.ConnectionHelper( 2955): Outgoing connection is using port 51368
I/io.jxcore.node.OutgoingSocketThread( 2955): Now accepting connections...
,I/jxcore-log( 2955): 2015-12-01T10:56:22.572Z SendDataConnector.js: CLIENT connected to 51368, error: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:56:22.572Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:56:22.573Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3016): dm_pm_timer expires
W/bt-btif ( 3016): dm_pm_timer expires 1
,W/bt-btif ( 3016): proc dm_pm_timer expires
,I/jxcore-log( 2955): 2015-12-01T10:56:27.574Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:56:27.575Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2955): 
,W/bt-btif ( 3016): invalid rfc slot id: 17
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: bt socket closed, read return: -1
,E/io.jxcore.node.SocketThreadBase( 2955): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 314
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 2955): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: Socket closed
,I/jxcore-log( 2955): 2015-12-01T10:56:28.858Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2955): 
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051414 rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3016): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
W/bt-rfcomm( 3016): RFCOMM_DisconnectInd LCID:0x49
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:255
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection initialized (thread ID: 319)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 319)
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051414 rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesRead: Read 83 bytes successfully (thread ID: 319)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Got valid identity from [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4930 7C:F9:0E:51:18:22]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 319)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): removeThreadFromList: Removing thread with ID 319
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Handshake thread disposed (thread ID: 319)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onIncomingConnectionConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4930 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 319)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4930 7C:F9:0E:51:18:22]
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming connection, peer ID: 7C:F9:0E:51:18:22, name: samsung-SM-A500FU_PT4930, Bluetooth address: 7C:F9:0E:51:18:22
,I/io.jxcore.node.IncomingSocketThread( 2955): Constructed
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming socket thread using port 0 and is now connected
,I/io.jxcore.node.IncomingSocketThread( 2955): Entering thread
,I/jxcore-log( 2955): 2015-12-01T10:56:30.368Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2955): 
,I/io.jxcore.node.IncomingSocketThread( 2955): Local host address: localhost/127.0.0.1, port: 59747
I/io.jxcore.node.IncomingSocketThread( 2955): Local streams created successfully, starting stream copying threads...
I/io.jxcore.node.SocketThreadBase( 2955): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 2955): Exiting thread
,I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 80:01:84:8A:B3:68
I/io.jxcore.node.OutgoingSocketThread( 2955): close
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 2955): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T10:56:32.579Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:56:32.579Z SendDataConnector.js: Connect (retry count 2) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:56:32.579Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:56:32.579Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to HTC Desire 820 in address 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: HTC Desire 820 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to HTC Desire 820 in address 80:01:84:8A:B3:68
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3016): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051414 rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3016): invalid rfc slot id: 18
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: bt socket closed, read return: -1
,E/io.jxcore.node.SocketThreadBase( 2955): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 320
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 2955): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: Socket closed
,I/jxcore-log( 2955): 2015-12-01T10:56:41.461Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2955): 
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051414 rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3016): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
W/bt-rfcomm( 3016): RFCOMM_DisconnectInd LCID:0x4d
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:255
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection initialized (thread ID: 324)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 324)
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051414 rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesRead: Read 83 bytes successfully (thread ID: 324)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Got valid identity from [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4930 7C:F9:0E:51:18:22]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 324)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): removeThreadFromList: Removing thread with ID 324
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Handshake thread disposed (thread ID: 324)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onIncomingConnectionConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4930 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 324)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4930 7C:F9:0E:51:18:22]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming connection, peer ID: 7C:F9:0E:51:18:22, name: samsung-SM-A500FU_PT4930, Bluetooth address: 7C:F9:0E:51:18:22
I/io.jxcore.node.IncomingSocketThread( 2955): Constructed
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming socket thread using port 0 and is now connected
,I/io.jxcore.node.IncomingSocketThread( 2955): Entering thread
,I/jxcore-log( 2955): 2015-12-01T10:56:43.494Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2955): 
,I/io.jxcore.node.IncomingSocketThread( 2955): Local host address: localhost/127.0.0.1, port: 59747
I/io.jxcore.node.IncomingSocketThread( 2955): Local streams created successfully, starting stream copying threads...
,I/io.jxcore.node.SocketThreadBase( 2955): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 2955): Exiting thread
,W/bt-btif ( 3016): invalid rfc slot id: 19
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: bt socket closed, read return: -1
E/io.jxcore.node.SocketThreadBase( 2955): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: bt socket closed, read return: -1,
I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 325
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 2955): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: Socket closed
,I/jxcore-log( 2955): 2015-12-01T10:56:53.856Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2955): 
,W/bt-rfcomm( 3016): rfc_find_lcid_mcb LCID reused LCID:0x4e current:0x0
W/bt-rfcomm( 3016): RFCOMM_DisconnectInd LCID:0x4e
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:255
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection initialized (thread ID: 328)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 328)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesRead: Read 83 bytes successfully (thread ID: 328),
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Got valid identity from [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4930 7C:F9:0E:51:18:22]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 328)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): removeThreadFromList: Removing thread with ID 328
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Handshake thread disposed (thread ID: 328)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onIncomingConnectionConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4930 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 328)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4930 7C:F9:0E:51:18:22]
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming connection, peer ID: 7C:F9:0E:51:18:22, name: samsung-SM-A500FU_PT4930, Bluetooth address: 7C:F9:0E:51:18:22
I/io.jxcore.node.IncomingSocketThread( 2955): Constructed
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming socket thread using port 0 and is now connected
,I/io.jxcore.node.IncomingSocketThread( 2955): Entering thread
,I/jxcore-log( 2955): 2015-12-01T10:56:54.035Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2955): 
,I/io.jxcore.node.IncomingSocketThread( 2955): Local host address: localhost/127.0.0.1, port: 59747
I/io.jxcore.node.IncomingSocketThread( 2955): Local streams created successfully, starting stream copying threads...
I/io.jxcore.node.SocketThreadBase( 2955): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 2955): Exiting thread
,W/bt-btif ( 3016): invalid rfc slot id: 21
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: bt socket closed, read return: -1
E/io.jxcore.node.SocketThreadBase( 2955): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 329
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 2955): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: Socket closed
,I/jxcore-log( 2955): 2015-12-01T10:56:54.377Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2955): 
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051414 rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3016): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0
W/bt-rfcomm( 3016): RFCOMM_DisconnectInd LCID:0x41
,E/bt-btm  ( 3016): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3016): onReceive
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: Thali Test (Galaxy A5)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): cancel: Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3016): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:20, channel:-1
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Cancelled: Connection timeout [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5457 80:01:84:8A:B3:68]
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5457 80:01:84:8A:B3:68]
I/jxcore-log( 2955): 2015-12-01T10:57:02.607Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 80:01:84:8A:B3:68 failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:57:02.607Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 80:01:84:8A:B3:68 failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:57:02.608Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T10:57:07.609Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T10:57:07.610Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T10:57:12.617Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:57:12.618Z SendDataConnector.js: Connect (retry count 3) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:57:12.618Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:57:12.619Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
,I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to HTC Desire 820 in address 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: HTC Desire 820 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to HTC Desire 820 in address 80:01:84:8A:B3:68
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3016): DISCOVERY_COMP_EVT slot id:23, failed to find channle,                                       status:2, scn:126619823
,W/bt-btif ( 3016): invalid rfc slot id: 23
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Failed to connect to socket/initiate handshake
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5457 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): shutdown
,I/jxcore-log( 2955): 2015-12-01T10:57:12.669Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 80:01:84:8A:B3:68 failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:57:12.669Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 80:01:84:8A:B3:68 failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:57:12.669Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T10:57:17.670Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T10:57:17.674Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T10:57:22.681Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:57:22.682Z SendDataConnector.js: Connect (retry count 4) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:57:22.682Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:57:22.683Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to HTC Desire 820 in address 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: HTC Desire 820 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to HTC Desire 820 in address 80:01:84:8A:B3:68
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3016): DISCOVERY_COMP_EVT slot id:24, failed to find channle,                                       status:2, scn:126619823
,W/bt-btif ( 3016): invalid rfc slot id: 24
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Failed to connect to socket/initiate handshake
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5457 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): shutdown
,I/jxcore-log( 2955): 2015-12-01T10:57:22.733Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 80:01:84:8A:B3:68 failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:57:22.734Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 80:01:84:8A:B3:68 failed
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T10:57:22.749Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:57:22.752Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 2955): 
I/jxcore-log( 2955): ---- round done--------
I/jxcore-log( 2955): 
I/jxcore-log( 2955): ---- gotta redo : 80:01:84:8A:B3:68, try count now: 1
I/jxcore-log( 2955): 
I/jxcore-log( 2955): do fake peer & start
I/jxcore-log( 2955): 
I/jxcore-log( 2955): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:57:22.755Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:57:22.757Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:57:22.758Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
W/io.jxcore.node.ConnectionHelper( 2955): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: null 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to null in address 08:EC:A9:50:76:27
I/chromium( 2955): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 80:01:84:8A:B3:68 done with result: Connection to peer with ID 80:01:84:8A:B3:68 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3016): DISCOVERY_COMP_EVT slot id:25, failed to find channle,                                       status:2, scn:126619823
W/bt-btif ( 3016): invalid rfc slot id: 25
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:76:27 08:EC:A9:50:76:27 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): shutdown
I/jxcore-log( 2955): 2015-12-01T10:57:22.786Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 08:EC:A9:50:76:27 failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:57:22.786Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 08:EC:A9:50:76:27 failed
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T10:57:22.787Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T10:57:27.788Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:57:27.789Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2955): 
,W/bt-btif ( 3016): info:x10
,D/        ( 3016): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 3016): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa40515dc rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2955): 2015-12-01T10:57:32.793Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:57:32.794Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:57:32.795Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:57:32.795Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
W/io.jxcore.node.ConnectionHelper( 2955): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: null 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to null in address 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3016): DISCOVERY_COMP_EVT slot id:26, failed to find channle,                                       status:2, scn:126619823
,W/bt-btif ( 3016): invalid rfc slot id: 26
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Failed to connect to socket/initiate handshake
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:76:27 08:EC:A9:50:76:27 08:EC:A9:50:76:27]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): shutdown
,I/jxcore-log( 2955): 2015-12-01T10:57:32.852Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 08:EC:A9:50:76:27 failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:57:32.853Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 08:EC:A9:50:76:27 failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:57:32.853Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,I/BluetoothBondStateMachine( 3016): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
E/bt-btif ( 3016): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3016): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3016): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3016): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 3016): Failed to remove device: E0:DB:10:14:E2:C0
,I/BluetoothBondStateMachine( 3016): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3016): StableState(): Entering Off State
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:255
W/bt-btif ( 3016): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3016): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection initialized (thread ID: 336)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 336)
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa40515dc rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa40515dc rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesRead: Read 82 bytes successfully (thread ID: 336)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Got valid identity from [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5331 E0:DB:10:14:E2:C0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 336)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): removeThreadFromList: Removing thread with ID 336
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Handshake thread disposed (thread ID: 336)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onIncomingConnectionConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5331 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 336)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5331 E0:DB:10:14:E2:C0]
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming connection, peer ID: E0:DB:10:14:E2:C0, name: samsung-SM-N910C_PT5331, Bluetooth address: E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 2955): addNewPeerToListAndNotify: Adding peer with ID E0:DB:10:14:E2:C0
,I/io.jxcore.node.IncomingSocketThread( 2955): Constructed
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming socket thread using port 0 and is now connected
,I/io.jxcore.node.IncomingSocketThread( 2955): Entering thread
,I/jxcore-log( 2955): 2015-12-01T10:57:33.659Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2955): 
,I/io.jxcore.node.IncomingSocketThread( 2955): Local host address: localhost/127.0.0.1, port: 59747
I/io.jxcore.node.IncomingSocketThread( 2955): Local streams created successfully, starting stream copying threads...
,I/io.jxcore.node.SocketThreadBase( 2955): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 2955): Exiting thread
,W/bt-sdp  ( 3016): SDP - Rcvd conn cnf with error: 0xeeee  CID 0x4a
E/bt-btif ( 3016): DISCOVERY_COMP_EVT slot id:20, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3016): invalid rfc slot id: 20
,I/jxcore-log( 2955): 2015-12-01T10:57:37.855Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:57:37.855Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2955): 
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3016): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3016): onReceive
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 2955): 2015-12-01T10:57:42.859Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T10:57:42.860Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:57:42.865Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:57:42.866Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
W/io.jxcore.node.ConnectionHelper( 2955): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: null 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to null in address 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa40515dc rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3016): invalid rfc slot id: 22
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: bt socket closed, read return: -1
E/io.jxcore.node.SocketThreadBase( 2955): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 337
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 2955): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: Socket closed
,W/bt-rfcomm( 3016): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
W/bt-rfcomm( 3016): RFCOMM_DisconnectInd LCID:0x42
,I/jxcore-log( 2955): 2015-12-01T10:57:44.083Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2955): 
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:255
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection initialized (thread ID: 341)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 341)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesRead: Read 82 bytes successfully (thread ID: 341)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Got valid identity from [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5331 E0:DB:10:14:E2:C0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 341)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): removeThreadFromList: Removing thread with ID 341
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Handshake thread disposed (thread ID: 341)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onIncomingConnectionConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5331 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 341)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5331 E0:DB:10:14:E2:C0]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming connection, peer ID: E0:DB:10:14:E2:C0, name: samsung-SM-N910C_PT5331, Bluetooth address: E0:DB:10:14:E2:C0
I/io.jxcore.node.IncomingSocketThread( 2955): Constructed
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming socket thread using port 0 and is now connected
,I/io.jxcore.node.IncomingSocketThread( 2955): Entering thread
,I/io.jxcore.node.IncomingSocketThread( 2955): Local host address: localhost/127.0.0.1, port: 59747
I/io.jxcore.node.IncomingSocketThread( 2955): Local streams created successfully, starting stream copying threads...
I/io.jxcore.node.SocketThreadBase( 2955): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T10:57:44.250Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2955): 
,W/bt-btif ( 3016): invalid rfc slot id: 27
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: bt socket closed, read return: -1
,E/io.jxcore.node.SocketThreadBase( 2955): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
,I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 342
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
,I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 2955): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: Socket closed
,I/jxcore-log( 2955): 2015-12-01T10:57:54.947Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2955): 
,W/bt-rfcomm( 3016): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
W/bt-rfcomm( 3016): RFCOMM_DisconnectInd LCID:0x44
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:255
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection initialized (thread ID: 345)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 345)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesRead: Read 82 bytes successfully (thread ID: 345)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Got valid identity from [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5331 E0:DB:10:14:E2:C0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 345)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): removeThreadFromList: Removing thread with ID 345
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Handshake thread disposed (thread ID: 345)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onIncomingConnectionConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5331 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 345)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5331 E0:DB:10:14:E2:C0]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming connection, peer ID: E0:DB:10:14:E2:C0, name: samsung-SM-N910C_PT5331, Bluetooth address: E0:DB:10:14:E2:C0
I/io.jxcore.node.IncomingSocketThread( 2955): Constructed
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming socket thread using port 0 and is now connected
,I/io.jxcore.node.IncomingSocketThread( 2955): Entering thread
,I/jxcore-log( 2955): 2015-12-01T10:57:55.147Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2955): 
,I/io.jxcore.node.IncomingSocketThread( 2955): Local host address: localhost/127.0.0.1, port: 59747
I/io.jxcore.node.IncomingSocketThread( 2955): Local streams created successfully, starting stream copying threads...
,I/io.jxcore.node.SocketThreadBase( 2955): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 2955): Exiting thread
,W/bt-btif ( 3016): invalid rfc slot id: 29
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: bt socket closed, read return: -1
E/io.jxcore.node.SocketThreadBase( 2955): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 346
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 2955): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: Socket closed
,I/jxcore-log( 2955): 2015-12-01T10:58:05.912Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2955): 
,W/bt-rfcomm( 3016): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
W/bt-rfcomm( 3016): RFCOMM_DisconnectInd LCID:0x45
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:255
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection initialized (thread ID: 349)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 349)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesRead: Read 82 bytes successfully (thread ID: 349)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Got valid identity from [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5331 E0:DB:10:14:E2:C0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 349)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): removeThreadFromList: Removing thread with ID 349
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Handshake thread disposed (thread ID: 349)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onIncomingConnectionConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5331 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 349)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5331 E0:DB:10:14:E2:C0]
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming connection, peer ID: E0:DB:10:14:E2:C0, name: samsung-SM-N910C_PT5331, Bluetooth address: E0:DB:10:14:E2:C0
I/io.jxcore.node.IncomingSocketThread( 2955): Constructed
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming socket thread using port 0 and is now connected
,I/io.jxcore.node.IncomingSocketThread( 2955): Entering thread
,I/io.jxcore.node.IncomingSocketThread( 2955): Local host address: localhost/127.0.0.1, port: 59747
I/io.jxcore.node.IncomingSocketThread( 2955): Local streams created successfully, starting stream copying threads...
,I/jxcore-log( 2955): 2015-12-01T10:58:06.174Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2955): 
,I/io.jxcore.node.SocketThreadBase( 2955): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 2955): Exiting thread
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa40515dc rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3016): info:x10
,D/        ( 3016): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3016): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3016): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
E/bt-btif ( 3016): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3016): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3016): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3016): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/BluetoothAdapterProperties( 3016): Failed to remove device: 08:EC:A9:50:76:27
,I/BluetoothBondStateMachine( 3016): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3016): StableState(): Entering Off State
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:1
W/bt-btif ( 3016): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3016): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Outgoing connection initialized (thread ID: 353)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 353)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 353)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesRead: Read 83 bytes successfully (thread ID: 353)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Handshake succeeded with [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing connection, peer ID: 08:EC:A9:50:76:27, name: samsung-SM-A300FU_PT4311, Bluetooth address: 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 2955): addNewPeerToListAndNotify: Adding peer with ID 08:EC:A9:50:76:27
I/io.jxcore.node.OutgoingSocketThread( 2955): Constructed
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing socket thread created successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 353)
,I/io.jxcore.node.OutgoingSocketThread( 2955): Server socket local port: 60630
I/io.jxcore.node.ConnectionHelper( 2955): Outgoing connection is using port 60630
I/io.jxcore.node.OutgoingSocketThread( 2955): Now accepting connections...
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa40515dc rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2955): 2015-12-01T10:58:12.129Z SendDataConnector.js: CLIENT connected to 60630, error: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:58:12.130Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T10:58:12.132Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa40515dc rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3016): invalid rfc slot id: 30
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: bt socket closed, read return: -1
E/io.jxcore.node.SocketThreadBase( 2955): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 350
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 2955): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: Socket closed
,I/jxcore-log( 2955): 2015-12-01T10:58:16.758Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2955): 
,W/bt-btif ( 3016): dm_pm_timer expires
W/bt-btif ( 3016): dm_pm_timer expires 0
W/bt-btif ( 3016): proc dm_pm_timer expires
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa40515dc rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3016): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
W/bt-rfcomm( 3016): RFCOMM_DisconnectInd LCID:0x4c
,I/jxcore-log( 2955): 2015-12-01T10:58:17.137Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:58:17.139Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2955): 
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:255
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection initialized (thread ID: 355)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 355)
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa40515dc rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesRead: Read 82 bytes successfully (thread ID: 355)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Got valid identity from [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5331 E0:DB:10:14:E2:C0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 355)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): removeThreadFromList: Removing thread with ID 355
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Handshake thread disposed (thread ID: 355)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onIncomingConnectionConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5331 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 355)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5331 E0:DB:10:14:E2:C0]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming connection, peer ID: E0:DB:10:14:E2:C0, name: samsung-SM-N910C_PT5331, Bluetooth address: E0:DB:10:14:E2:C0
,I/io.jxcore.node.IncomingSocketThread( 2955): Constructed
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming socket thread using port 0 and is now connected
,I/io.jxcore.node.IncomingSocketThread( 2955): Entering thread
,I/jxcore-log( 2955): 2015-12-01T10:58:17.440Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2955): 
,I/io.jxcore.node.IncomingSocketThread( 2955): Local host address: localhost/127.0.0.1, port: 59747
I/io.jxcore.node.IncomingSocketThread( 2955): Local streams created successfully, starting stream copying threads...
,I/io.jxcore.node.SocketThreadBase( 2955): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 2955): Exiting thread
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3016): invalid rfc slot id: 31
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: bt socket closed, read return: -1
E/io.jxcore.node.SocketThreadBase( 2955): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 356
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 2955): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: Socket closed
,I/jxcore-log( 2955): 2015-12-01T10:58:17.852Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2955): 
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa40515dc rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa40515dc rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3016): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
,W/bt-rfcomm( 3016): RFCOMM_DisconnectInd LCID:0x4b
,I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 08:EC:A9:50:76:27
I/io.jxcore.node.OutgoingSocketThread( 2955): close
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 2955): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T10:58:22.166Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:58:22.167Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:58:22.168Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:58:22.168Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
,I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to Thali Test (Galaxy A3) in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: Thali Test (Galaxy A3) 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to Thali Test (Galaxy A3) in address 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa40515dc rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa40517a4 rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3016): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3016): onReceive
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: Note4-1
,W/bt-btif ( 3016): bta_jv_rfc_port_to_cb(port_handle:0x1c):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Outgoing connection initialized (thread ID: 360)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 360)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 360)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesRead: Read 83 bytes successfully (thread ID: 360)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Handshake succeeded with [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 360)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing connection, peer ID: 08:EC:A9:50:76:27, name: samsung-SM-A300FU_PT4311, Bluetooth address: 08:EC:A9:50:76:27
I/io.jxcore.node.OutgoingSocketThread( 2955): Constructed
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 2955): Server socket local port: 60461
I/io.jxcore.node.ConnectionHelper( 2955): Outgoing connection is using port 60461
I/io.jxcore.node.OutgoingSocketThread( 2955): Now accepting connections...
,I/jxcore-log( 2955): 2015-12-01T10:58:24.311Z SendDataConnector.js: CLIENT connected to 60461, error: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:58:24.312Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:58:24.313Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,W/bt-btif ( 3016): dm_pm_timer expires
W/bt-btif ( 3016): dm_pm_timer expires 0
W/bt-btif ( 3016): proc dm_pm_timer expires
,I/jxcore-log( 2955): 2015-12-01T10:58:29.314Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:58:29.315Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2955): 
,I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 08:EC:A9:50:76:27
I/io.jxcore.node.OutgoingSocketThread( 2955): close
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 2955): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T10:58:34.345Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:58:34.345Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:58:34.346Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:58:34.346Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to Thali Test (Galaxy A3) in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: Thali Test (Galaxy A3) 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to Thali Test (Galaxy A3) in address 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-btif ( 3016): bta_jv_rfc_port_to_cb(port_handle:0x1e):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Outgoing connection initialized (thread ID: 363)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 363)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 363)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesRead: Read 83 bytes successfully (thread ID: 363)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Handshake succeeded with [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 363)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing connection, peer ID: 08:EC:A9:50:76:27, name: samsung-SM-A300FU_PT4311, Bluetooth address: 08:EC:A9:50:76:27
,I/io.jxcore.node.OutgoingSocketThread( 2955): Constructed
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 2955): Server socket local port: 38174
I/io.jxcore.node.ConnectionHelper( 2955): Outgoing connection is using port 38174
I/io.jxcore.node.OutgoingSocketThread( 2955): Now accepting connections...
,I/jxcore-log( 2955): 2015-12-01T10:58:36.963Z SendDataConnector.js: CLIENT connected to 38174, error: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:58:36.964Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T10:58:36.980Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 08:EC:A9:50:76:27
I/io.jxcore.node.OutgoingSocketThread( 2955): close
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 2955): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T10:58:37.001Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2955): 
I/jxcore-log( 2955): ---- round done--------
I/jxcore-log( 2955): 
I/jxcore-log( 2955): ---- gotta redo : 08:EC:A9:50:76:27, try count now: 1
I/jxcore-log( 2955): 
I/jxcore-log( 2955): do fake peer & start
I/jxcore-log( 2955): 
I/jxcore-log( 2955): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:58:37.004Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:58:37.005Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:58:37.005Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
W/io.jxcore.node.ConnectionHelper( 2955): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to null in address 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: null 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to null in address 00:F4:6F:30:E0:6C
I/chromium( 2955): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 08:EC:A9:50:76:27 done with result: Listening for incoming connections", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3016): info:x10
,D/        ( 3016): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3016): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa405196c rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3016): bta_jv_rfc_port_to_cb(port_handle:0x1):jv handle:0x0 not FOUND
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa405196c rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3016): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 1
E/bt-btif ( 3016): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3016): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3016): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3016): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 0
,D/BluetoothAdapterProperties( 3016): Failed to remove device: 00:F4:6F:30:E0:6C
,I/BluetoothBondStateMachine( 3016): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3016): StableState(): Entering Off State
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:1
W/bt-btif ( 3016): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3016): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Outgoing connection initialized (thread ID: 366)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 366)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 366)
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa405196c rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesRead: Read 82 bytes successfully (thread ID: 366)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Handshake succeeded with [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3325 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3325 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 366)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3325 00:F4:6F:30:E0:6C]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing connection, peer ID: 00:F4:6F:30:E0:6C, name: samsung-SM-G800F_PT3325, Bluetooth address: 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 2955): addNewPeerToListAndNotify: Adding peer with ID 00:F4:6F:30:E0:6C
I/io.jxcore.node.OutgoingSocketThread( 2955): Constructed
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 2955): Server socket local port: 60588
I/io.jxcore.node.ConnectionHelper( 2955): Outgoing connection is using port 60588
I/io.jxcore.node.OutgoingSocketThread( 2955): Now accepting connections...
,I/jxcore-log( 2955): 2015-12-01T10:58:41.852Z SendDataConnector.js: CLIENT connected to 60588, error: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:58:41.853Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:58:41.854Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,E/bt-btm  ( 3016): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3016): onReceive
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: Thali Test (Galaxy A3)
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa405196c rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,D/Finsky  ( 2386): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2386): Failed write_ctrl(u 39) res=-1 errno=22
I/qtaguid ( 2386): Untagging socket 39 failed errno=-22
W/NetworkManagementSocketTagger( 2386): untagSocket(39) failed with errno -22
,D/Finsky  ( 2386): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430000] >= Server Version [-1]
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2386): Failed write_ctrl(u 39) res=-1 errno=22
I/qtaguid ( 2386): Untagging socket 39 failed errno=-22
W/NetworkManagementSocketTagger( 2386): untagSocket(39) failed with errno -22
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  760): Explicit concurrent mark sweep GC freed 24857(1082KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 943us total 53.166ms
,I/qtaguid ( 2386): Failed write_ctrl(u 39) res=-1 errno=22
I/qtaguid ( 2386): Untagging socket 39 failed errno=-22
W/NetworkManagementSocketTagger( 2386): untagSocket(39) failed with errno -22
,W/ResourcesManager( 2386): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2386): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 2386): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 2386): [1] WearSupportService.startHygiene: disabled
,D/Finsky  ( 2386): [1] DailyHygiene.access$600: Logging device features
,D/DeviceConnectionService( 1316): client connected with version: 8296000
,D/Finsky  ( 2386): [245] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2386): [1] VerifyInstalledPackagesReceiver.onReceive: Verify installed apps requested
,D/Finsky  ( 2386): [1] VerifyInstalledPackagesTask.onPreExecute: Verifying installed apps,
,W/bt-btif ( 3016): dm_pm_timer expires
W/bt-btif ( 3016): dm_pm_timer expires 0
,W/bt-btif ( 3016): proc dm_pm_timer expires
,I/jxcore-log( 2955): 2015-12-01T10:58:46.855Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:58:46.855Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2955): 
,I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 00:F4:6F:30:E0:6C
I/io.jxcore.node.OutgoingSocketThread( 2955): close
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 2955): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 2955): Exiting thread
,W/bt-btif ( 3016): bta_jv_rfc_port_to_cb(port_handle:0x7):jv handle:0x0 not FOUND
,I/jxcore-log( 2955): 2015-12-01T10:58:51.888Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:58:51.889Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:58:51.889Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T10:58:51.890Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: S5mini-1 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Outgoing connection initialized (thread ID: 369)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 369)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 369)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesRead: Read 82 bytes successfully (thread ID: 369)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Handshake succeeded with [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3325 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3325 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 369)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3325 00:F4:6F:30:E0:6C]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing connection, peer ID: 00:F4:6F:30:E0:6C, name: samsung-SM-G800F_PT3325, Bluetooth address: 00:F4:6F:30:E0:6C
I/io.jxcore.node.OutgoingSocketThread( 2955): Constructed
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 2955): Server socket local port: 54071
I/io.jxcore.node.ConnectionHelper( 2955): Outgoing connection is using port 54071
I/io.jxcore.node.OutgoingSocketThread( 2955): Now accepting connections...
,I/jxcore-log( 2955): 2015-12-01T10:58:53.012Z SendDataConnector.js: CLIENT connected to 54071, error: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:58:53.013Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:58:53.014Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,W/bt-btif ( 3016): dm_pm_timer expires
W/bt-btif ( 3016): dm_pm_timer expires 0
W/bt-btif ( 3016): proc dm_pm_timer expires
,I/jxcore-log( 2955): 2015-12-01T10:58:58.015Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:58:58.015Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2955): 
,D/Finsky  ( 2386): [230] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 2386): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 00:F4:6F:30:E0:6C
I/io.jxcore.node.OutgoingSocketThread( 2955): close
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 2955): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T10:59:03.021Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:59:03.021Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:59:03.022Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:59:03.022Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: S5mini-1 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3016): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Outgoing connection initialized (thread ID: 372)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 372)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 372)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesRead: Read 82 bytes successfully (thread ID: 372)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Handshake succeeded with [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3325 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3325 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 372)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3325 00:F4:6F:30:E0:6C]
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing connection, peer ID: 00:F4:6F:30:E0:6C, name: samsung-SM-G800F_PT3325, Bluetooth address: 00:F4:6F:30:E0:6C
I/io.jxcore.node.OutgoingSocketThread( 2955): Constructed
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 2955): Server socket local port: 39931
I/io.jxcore.node.ConnectionHelper( 2955): Outgoing connection is using port 39931
I/io.jxcore.node.OutgoingSocketThread( 2955): Now accepting connections...
,I/jxcore-log( 2955): 2015-12-01T10:59:03.867Z SendDataConnector.js: CLIENT connected to 39931, error: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:59:03.868Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:59:03.869Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,W/bt-btif ( 3016): dm_pm_timer expires
W/bt-btif ( 3016): dm_pm_timer expires 0
,W/bt-btif ( 3016): proc dm_pm_timer expires
,I/jxcore-log( 2955): 2015-12-01T10:59:08.871Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:59:08.872Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2955): 
,I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 00:F4:6F:30:E0:6C
I/io.jxcore.node.OutgoingSocketThread( 2955): close
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 2955): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T10:59:13.877Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:59:13.878Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:59:13.878Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:59:13.878Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: S5mini-1 00:F4:6F:30:E0:6C
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3016): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Outgoing connection initialized (thread ID: 375)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 375)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 375)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesRead: Read 82 bytes successfully (thread ID: 375)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Handshake succeeded with [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3325 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3325 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 375)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3325 00:F4:6F:30:E0:6C]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing connection, peer ID: 00:F4:6F:30:E0:6C, name: samsung-SM-G800F_PT3325, Bluetooth address: 00:F4:6F:30:E0:6C
I/io.jxcore.node.OutgoingSocketThread( 2955): Constructed
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 2955): Server socket local port: 44162
I/io.jxcore.node.ConnectionHelper( 2955): Outgoing connection is using port 44162
,I/io.jxcore.node.OutgoingSocketThread( 2955): Now accepting connections...
,I/jxcore-log( 2955): 2015-12-01T10:59:15.417Z SendDataConnector.js: CLIENT connected to 44162, error: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:59:15.418Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:59:15.419Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,W/bt-btif ( 3016): dm_pm_timer expires
W/bt-btif ( 3016): dm_pm_timer expires 0
W/bt-btif ( 3016): proc dm_pm_timer expires
,I/jxcore-log( 2955): 2015-12-01T10:59:20.420Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:59:20.421Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2955): 
,I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 00:F4:6F:30:E0:6C
I/io.jxcore.node.OutgoingSocketThread( 2955): close
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 2955): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T10:59:25.427Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:59:25.427Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:59:25.427Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:59:25.427Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
,I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: S5mini-1 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3016): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Outgoing connection initialized (thread ID: 378)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 378)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 378)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesRead: Read 82 bytes successfully (thread ID: 378)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Handshake succeeded with [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3325 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3325 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 378)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3325 00:F4:6F:30:E0:6C]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing connection, peer ID: 00:F4:6F:30:E0:6C, name: samsung-SM-G800F_PT3325, Bluetooth address: 00:F4:6F:30:E0:6C
I/io.jxcore.node.OutgoingSocketThread( 2955): Constructed
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 2955): Server socket local port: 37897
I/io.jxcore.node.ConnectionHelper( 2955): Outgoing connection is using port 37897
I/io.jxcore.node.OutgoingSocketThread( 2955): Now accepting connections...
,I/jxcore-log( 2955): 2015-12-01T10:59:27.600Z SendDataConnector.js: CLIENT connected to 37897, error: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:59:27.601Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T10:59:27.617Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 00:F4:6F:30:E0:6C
I/io.jxcore.node.OutgoingSocketThread( 2955): close
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 2955): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T10:59:27.642Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2955): 
I/jxcore-log( 2955): ---- round done--------
I/jxcore-log( 2955): 
I/jxcore-log( 2955): ---- gotta redo : 00:F4:6F:30:E0:6C, try count now: 1
I/jxcore-log( 2955): 
I/jxcore-log( 2955): do fake peer & start
I/jxcore-log( 2955): 
I/jxcore-log( 2955): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:59:27.647Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:59:27.648Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:59:27.648Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
,I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to Note4-1 in address E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: Note4-1 E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to Note4-1 in address E0:DB:10:14:E2:C0
I/chromium( 2955): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 00:F4:6F:30:E0:6C done with result: Listening for incoming connections", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3016): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa405196c rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa405196c rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3016): info:x10
,D/        ( 3016): remote version info [e0:db:10:14:e2:c0]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: Note4-1
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa40515dc rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:1
W/bt-btif ( 3016): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3016): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Outgoing connection initialized (thread ID: 381)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 381)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 381)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesRead: Read 82 bytes successfully (thread ID: 381)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Handshake succeeded with [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5331 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5331 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 381)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5331 E0:DB:10:14:E2:C0]
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing connection, peer ID: E0:DB:10:14:E2:C0, name: samsung-SM-N910C_PT5331, Bluetooth address: E0:DB:10:14:E2:C0
I/io.jxcore.node.OutgoingSocketThread( 2955): Constructed
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 2955): Server socket local port: 36045
I/io.jxcore.node.ConnectionHelper( 2955): Outgoing connection is using port 36045
I/io.jxcore.node.OutgoingSocketThread( 2955): Now accepting connections...
,I/jxcore-log( 2955): 2015-12-01T10:59:31.487Z SendDataConnector.js: CLIENT connected to 36045, error: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:59:31.487Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:59:31.488Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa405196c rs_disc_pending=1
E/bt-btm  ( 3016): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3016): onReceive
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: S5mini-1
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3016): dm_pm_timer expires
W/bt-btif ( 3016): dm_pm_timer expires 0
,W/bt-btif ( 3016): proc dm_pm_timer expires
,I/jxcore-log( 2955): 2015-12-01T10:59:36.489Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:59:36.490Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2955): 
,I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: E0:DB:10:14:E2:C0
I/io.jxcore.node.OutgoingSocketThread( 2955): close
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 2955): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T10:59:41.522Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:59:41.523Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:59:41.524Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:59:41.524Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to Note4-1 in address E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: Note4-1 E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to Note4-1 in address E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3016): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Outgoing connection initialized (thread ID: 384)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 384)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 384)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesRead: Read 82 bytes successfully (thread ID: 384)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Handshake succeeded with [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5331 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5331 E0:DB:10:14:E2:C0]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5331 E0:DB:10:14:E2:C0]
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing connection, peer ID: E0:DB:10:14:E2:C0, name: samsung-SM-N910C_PT5331, Bluetooth address: E0:DB:10:14:E2:C0
I/io.jxcore.node.OutgoingSocketThread( 2955): Constructed
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing socket thread created successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 384)
,I/io.jxcore.node.OutgoingSocketThread( 2955): Server socket local port: 46430
I/io.jxcore.node.ConnectionHelper( 2955): Outgoing connection is using port 46430
,I/io.jxcore.node.OutgoingSocketThread( 2955): Now accepting connections...
,I/jxcore-log( 2955): 2015-12-01T10:59:42.167Z SendDataConnector.js: CLIENT connected to 46430, error: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:59:42.168Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:59:42.168Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,W/bt-btif ( 3016): dm_pm_timer expires
W/bt-btif ( 3016): dm_pm_timer expires 0
W/bt-btif ( 3016): proc dm_pm_timer expires
,I/jxcore-log( 2955): 2015-12-01T10:59:47.169Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:59:47.169Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2955): 
,I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: E0:DB:10:14:E2:C0
I/io.jxcore.node.OutgoingSocketThread( 2955): close
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 2955): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T10:59:52.174Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:59:52.175Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:59:52.175Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:59:52.175Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to Note4-1 in address E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: Note4-1 E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to Note4-1 in address E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3016): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Outgoing connection initialized (thread ID: 387)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 387)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 387)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesRead: Read 82 bytes successfully (thread ID: 387)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Handshake succeeded with [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5331 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5331 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 387)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5331 E0:DB:10:14:E2:C0]
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing connection, peer ID: E0:DB:10:14:E2:C0, name: samsung-SM-N910C_PT5331, Bluetooth address: E0:DB:10:14:E2:C0
I/io.jxcore.node.OutgoingSocketThread( 2955): Constructed
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 2955): Server socket local port: 35162
,I/io.jxcore.node.ConnectionHelper( 2955): Outgoing connection is using port 35162
I/io.jxcore.node.OutgoingSocketThread( 2955): Now accepting connections...
,I/jxcore-log( 2955): 2015-12-01T10:59:53.535Z SendDataConnector.js: CLIENT connected to 35162, error: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:59:53.535Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:59:53.536Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,W/bt-btif ( 3016): dm_pm_timer expires
W/bt-btif ( 3016): dm_pm_timer expires 0
,W/bt-btif ( 3016): proc dm_pm_timer expires
,I/jxcore-log( 2955): 2015-12-01T10:59:58.538Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T10:59:58.538Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2955): 
,W/bt-btif ( 3016): info:x10
,D/        ( 3016): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,E/BluetoothRemoteDevices( 3016): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3016): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 1
,E/bt-btif ( 3016): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3016): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3016): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3016): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 0
,D/BluetoothAdapterProperties( 3016): Failed to remove device: F8:CF:C5:D9:E5:61
,I/BluetoothBondStateMachine( 3016): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3016): StableState(): Entering Off State
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:255
W/bt-btif ( 3016): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3016): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection initialized (thread ID: 389)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 389)
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesRead: Read 82 bytes successfully (thread ID: 389)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Got valid identity from [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3700 F8:CF:C5:D9:E5:61]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 389)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): removeThreadFromList: Removing thread with ID 389
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Handshake thread disposed (thread ID: 389)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onIncomingConnectionConnected: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3700 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 389)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3700 F8:CF:C5:D9:E5:61]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming connection, peer ID: F8:CF:C5:D9:E5:61, name: motorola-Nexus 6_PT3700, Bluetooth address: F8:CF:C5:D9:E5:61
,I/io.jxcore.node.ConnectionHelper( 2955): addNewPeerToListAndNotify: Adding peer with ID F8:CF:C5:D9:E5:61
,I/io.jxcore.node.IncomingSocketThread( 2955): Constructed
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming socket thread using port 0 and is now connected
,I/io.jxcore.node.IncomingSocketThread( 2955): Entering thread
,I/jxcore-log( 2955): 2015-12-01T11:00:00.592Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2955): 
,I/io.jxcore.node.IncomingSocketThread( 2955): Local host address: localhost/127.0.0.1, port: 59747
,I/io.jxcore.node.IncomingSocketThread( 2955): Local streams created successfully, starting stream copying threads...
,I/io.jxcore.node.SocketThreadBase( 2955): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 2955): Exiting thread
,I/ActivityManager(  760): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4451 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 4451): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4451):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4451):   adb logcat -s GAv4
,W/GAv4    ( 4451): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4451): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4451): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  760): Killing 3770:com.google.android.configupdater/u0a36 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10036/pid_3770/cgroup.procs: No such file or directory
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa40515dc rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: E0:DB:10:14:E2:C0
I/io.jxcore.node.OutgoingSocketThread( 2955): close
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 2955): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T11:00:03.543Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:00:03.543Z SendDataConnector.js: Connect (retry count 3) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:00:03.543Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:00:03.543Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
,I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to Note4-1 in address E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: Note4-1 E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to Note4-1 in address E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa40515dc rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3016): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Outgoing connection initialized (thread ID: 394)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 394)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 394)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesRead: Read 82 bytes successfully (thread ID: 394)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Handshake succeeded with [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5331 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5331 E0:DB:10:14:E2:C0]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5331 E0:DB:10:14:E2:C0]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing connection, peer ID: E0:DB:10:14:E2:C0, name: samsung-SM-N910C_PT5331, Bluetooth address: E0:DB:10:14:E2:C0
I/io.jxcore.node.OutgoingSocketThread( 2955): Constructed
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing socket thread created successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 394)
,I/io.jxcore.node.OutgoingSocketThread( 2955): Server socket local port: 48897
I/io.jxcore.node.ConnectionHelper( 2955): Outgoing connection is using port 48897
I/io.jxcore.node.OutgoingSocketThread( 2955): Now accepting connections...
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2955): 2015-12-01T11:00:04.286Z SendDataConnector.js: CLIENT connected to 48897, error: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:00:04.287Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:00:04.288Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3016): dm_pm_timer expires
W/bt-btif ( 3016): dm_pm_timer expires 1
,W/bt-btif ( 3016): proc dm_pm_timer expires
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa40515dc rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2955): 2015-12-01T11:00:09.289Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:00:09.294Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2955): 
,W/bt-btif ( 3016): invalid rfc slot id: 32
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: bt socket closed, read return: -1
E/io.jxcore.node.SocketThreadBase( 2955): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 390
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 2955): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: Socket closed
,I/jxcore-log( 2955): 2015-12-01T11:00:11.183Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2955): 
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa40515dc rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3016): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
W/bt-rfcomm( 3016): RFCOMM_DisconnectInd LCID:0x42
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:255
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection initialized (thread ID: 396)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 396)
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesRead: Read 82 bytes successfully (thread ID: 396)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Got valid identity from [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3700 F8:CF:C5:D9:E5:61]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 396)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): removeThreadFromList: Removing thread with ID 396
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Handshake thread disposed (thread ID: 396)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onIncomingConnectionConnected: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3700 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 396)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3700 F8:CF:C5:D9:E5:61]
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming connection, peer ID: F8:CF:C5:D9:E5:61, name: motorola-Nexus 6_PT3700, Bluetooth address: F8:CF:C5:D9:E5:61
I/io.jxcore.node.IncomingSocketThread( 2955): Constructed
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming socket thread using port 0 and is now connected
,I/io.jxcore.node.IncomingSocketThread( 2955): Entering thread
,I/jxcore-log( 2955): 2015-12-01T11:00:13.712Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2955): 
,I/io.jxcore.node.IncomingSocketThread( 2955): Local host address: localhost/127.0.0.1, port: 59747
I/io.jxcore.node.IncomingSocketThread( 2955): Local streams created successfully, starting stream copying threads...
I/io.jxcore.node.SocketThreadBase( 2955): startStreamCopyingThreads: OK
,I/io.jxcore.node.IncomingSocketThread( 2955): Exiting thread
,I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: E0:DB:10:14:E2:C0
I/io.jxcore.node.OutgoingSocketThread( 2955): close
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 2955): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T11:00:14.299Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:00:14.300Z SendDataConnector.js: Connect (retry count 4) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:00:14.300Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:00:14.300Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to Note4-1 in address E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: Note4-1 E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to Note4-1 in address E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3016): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa40515dc rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Outgoing connection initialized (thread ID: 401)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 401)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 401)
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa40515dc rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesRead: Read 82 bytes successfully (thread ID: 401)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Handshake succeeded with [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5331 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5331 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 401)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5331 E0:DB:10:14:E2:C0]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing connection, peer ID: E0:DB:10:14:E2:C0, name: samsung-SM-N910C_PT5331, Bluetooth address: E0:DB:10:14:E2:C0
I/io.jxcore.node.OutgoingSocketThread( 2955): Constructed
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 2955): Server socket local port: 56764
I/io.jxcore.node.ConnectionHelper( 2955): Outgoing connection is using port 56764
I/io.jxcore.node.OutgoingSocketThread( 2955): Now accepting connections...
,I/jxcore-log( 2955): 2015-12-01T11:00:15.769Z SendDataConnector.js: CLIENT connected to 56764, error: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:00:15.769Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:00:15.787Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: E0:DB:10:14:E2:C0
I/io.jxcore.node.OutgoingSocketThread( 2955): close
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 2955): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,W/bt-btif ( 3016): bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND
,I/io.jxcore.node.OutgoingSocketThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T11:00:15.814Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2955): 
I/jxcore-log( 2955): ---- round done--------
I/jxcore-log( 2955): 
I/jxcore-log( 2955): ---- gotta redo : E0:DB:10:14:E2:C0, try count now: 1
I/jxcore-log( 2955): 
I/jxcore-log( 2955): do fake peer & start
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): Connect to fake peer: 34:FC:EF:11:B1:66
,I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:00:15.817Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:00:15.818Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:00:15.818Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
W/io.jxcore.node.ConnectionHelper( 2955): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to null in address 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: null 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to null in address 34:FC:EF:11:B1:66
I/chromium( 2955): [INFO:CONSOLE(63)] "logCallback Round of send data to peer E0:DB:10:14:E2:C0 done with result: Listening for incoming connections", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa40515dc rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3016): info:x10
,D/        ( 3016): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3016): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,E/bt-btif ( 3016): DISCOVERY_COMP_EVT slot id:47, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3016): invalid rfc slot id: 47
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [34:FC:EF:11:B1:66 34:FC:EF:11:B1:66 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): shutdown
,I/jxcore-log( 2955): 2015-12-01T11:00:16.892Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:00:16.893Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:00:16.893Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa40515dc rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3016): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3016): onReceive
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: Note4-1
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3016): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3016): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2955): 2015-12-01T11:00:21.895Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:00:21.895Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2955): 
,W/bt-btif ( 3016): invalid rfc slot id: 43
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: bt socket closed, read return: -1
E/io.jxcore.node.SocketThreadBase( 2955): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 397
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 2955): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: Socket closed
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,I/jxcore-log( 2955): 2015-12-01T11:00:24.535Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2955): 
,W/bt-rfcomm( 3016): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
,W/bt-rfcomm( 3016): RFCOMM_DisconnectInd LCID:0x47
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:255
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection initialized (thread ID: 404)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 404)
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2955): 2015-12-01T11:00:26.898Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:00:26.899Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2955): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesRead: Read 82 bytes successfully (thread ID: 404)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Got valid identity from [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3700 F8:CF:C5:D9:E5:61]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 404)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): removeThreadFromList: Removing thread with ID 404
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Handshake thread disposed (thread ID: 404)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onIncomingConnectionConnected: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3700 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 404)
,I/jxcore-log( 2955): 2015-12-01T11:00:26.900Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:00:27.009Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
W/io.jxcore.node.ConnectionHelper( 2955): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to null in address 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: null 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to null in address 34:FC:EF:11:B1:66
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3700 F8:CF:C5:D9:E5:61]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming connection, peer ID: F8:CF:C5:D9:E5:61, name: motorola-Nexus 6_PT3700, Bluetooth address: F8:CF:C5:D9:E5:61
I/io.jxcore.node.IncomingSocketThread( 2955): Constructed
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming socket thread using port 0 and is now connected
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,I/io.jxcore.node.IncomingSocketThread( 2955): Entering thread
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/io.jxcore.node.IncomingSocketThread( 2955): Local host address: localhost/127.0.0.1, port: 59747
I/io.jxcore.node.IncomingSocketThread( 2955): Local streams created successfully, starting stream copying threads...
I/io.jxcore.node.SocketThreadBase( 2955): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T11:00:27.020Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2955): 
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3016): info:x10
,D/        ( 3016): remote version info [34:fc:ef:11:b1:66]: 7, f, 2205
,E/BluetoothRemoteDevices( 3016): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,E/bt-btif ( 3016): DISCOVERY_COMP_EVT slot id:49, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3016): invalid rfc slot id: 49
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [34:FC:EF:11:B1:66 34:FC:EF:11:B1:66 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): shutdown
I/jxcore-log( 2955): 2015-12-01T11:00:28.698Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:00:28.698Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:00:28.699Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3016): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3016): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2955): 2015-12-01T11:00:33.702Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:00:33.702Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2955): 
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: bt socket closed, read return: -1
E/io.jxcore.node.SocketThreadBase( 2955): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 406
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,W/bt-btif ( 3016): invalid rfc slot id: 45
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 2955): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: Socket closed
,W/bt-rfcomm( 3016): rfc_find_lcid_mcb LCID reused LCID:0x4e current:0x0
W/bt-rfcomm( 3016): RFCOMM_DisconnectInd LCID:0x4e
,I/jxcore-log( 2955): 2015-12-01T11:00:37.538Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2955): 
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:255
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection initialized (thread ID: 409)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 409)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesRead: Read 82 bytes successfully (thread ID: 409)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Got valid identity from [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3700 F8:CF:C5:D9:E5:61]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 409)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): removeThreadFromList: Removing thread with ID 409
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Handshake thread disposed (thread ID: 409)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onIncomingConnectionConnected: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3700 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 409)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3700 F8:CF:C5:D9:E5:61]
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming connection, peer ID: F8:CF:C5:D9:E5:61, name: motorola-Nexus 6_PT3700, Bluetooth address: F8:CF:C5:D9:E5:61
I/io.jxcore.node.IncomingSocketThread( 2955): Constructed
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming socket thread using port 0 and is now connected
,I/io.jxcore.node.IncomingSocketThread( 2955): Entering thread
,I/jxcore-log( 2955): 2015-12-01T11:00:37.647Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2955): 
,I/io.jxcore.node.IncomingSocketThread( 2955): Local host address: localhost/127.0.0.1, port: 59747
I/io.jxcore.node.IncomingSocketThread( 2955): Local streams created successfully, starting stream copying threads...
I/io.jxcore.node.SocketThreadBase( 2955): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 2955): Exiting thread
,W/bt-btif ( 3016): invalid rfc slot id: 48
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: bt socket closed, read return: -1
E/io.jxcore.node.SocketThreadBase( 2955): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 410
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 2955): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: Socket closed
,I/jxcore-log( 2955): 2015-12-01T11:00:37.965Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2955): 
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3016): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
,W/bt-rfcomm( 3016): RFCOMM_DisconnectInd LCID:0x43
,I/jxcore-log( 2955): 2015-12-01T11:00:38.708Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:00:38.708Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:00:38.709Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:00:38.710Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
,I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
W/io.jxcore.node.ConnectionHelper( 2955): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to null in address 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: null 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to null in address 34:FC:EF:11:B1:66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3016): info:x10
,D/        ( 3016): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3016): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051cfc rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,E/bt-btif ( 3016): DISCOVERY_COMP_EVT slot id:51, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3016): invalid rfc slot id: 51
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [34:FC:EF:11:B1:66 34:FC:EF:11:B1:66 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): shutdown
I/jxcore-log( 2955): 2015-12-01T11:00:39.814Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:00:39.815Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:00:39.815Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051cfc rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3016): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3016): onReceive
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: Nexus 6
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3016): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3016): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2955): 2015-12-01T11:00:44.817Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:00:44.818Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:00:49.822Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:00:49.823Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:00:49.823Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:00:49.824Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
W/io.jxcore.node.ConnectionHelper( 2955): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to null in address 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: null 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to null in address 34:FC:EF:11:B1:66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3016): info:x10
,D/        ( 3016): remote version info [34:fc:ef:11:b1:66]: 7, f, 230f
,E/BluetoothRemoteDevices( 3016): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,E/bt-btif ( 3016): DISCOVERY_COMP_EVT slot id:52, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3016): invalid rfc slot id: 52
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [34:FC:EF:11:B1:66 34:FC:EF:11:B1:66 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): shutdown
I/jxcore-log( 2955): 2015-12-01T11:00:51.127Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:00:51.128Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:00:51.129Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3016): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3016): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2955): 2015-12-01T11:00:56.132Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:00:56.133Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2955): 
,I/EventLogService( 1562): Aggregate from 1448966916526 (log), 1448965816031 (data)
,I/jxcore-log( 2955): 2015-12-01T11:01:01.135Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:01:01.135Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:01:01.135Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:01:01.135Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
W/io.jxcore.node.ConnectionHelper( 2955): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to null in address 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: null 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to null in address 34:FC:EF:11:B1:66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3016): info:x10
,D/        ( 3016): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 3016): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3016): info:x10
,D/        ( 3016): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3016): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3016): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 3016): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3016): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3016): Entering PendingCommandState State
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051cfc rs_disc_pending=1
,W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,E/bt-btif ( 3016): DISCOVERY_COMP_EVT slot id:53, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3016): invalid rfc slot id: 53
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [34:FC:EF:11:B1:66 34:FC:EF:11:B1:66 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): shutdown
I/jxcore-log( 2955): 2015-12-01T11:01:03.444Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:01:03.445Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:01:03.446Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:01:03.447Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2955): 
I/jxcore-log( 2955): ---- round done--------
I/jxcore-log( 2955): 
I/jxcore-log( 2955): ---- gotta redo : 34:FC:EF:11:B1:66, try count now: 1
I/jxcore-log( 2955): 
I/jxcore-log( 2955): do fake peer & start
I/jxcore-log( 2955): 
I/jxcore-log( 2955): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:01:03.447Z SendDataConnector.js: Start called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:01:03.448Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:01:03.448Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 58:2A:F7:ED:96:BE
W/io.jxcore.node.ConnectionHelper( 2955): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to null in address 58:2A:F7:ED:96:BE
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: null 58:2A:F7:ED:96:BE
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to null in address 58:2A:F7:ED:96:BE
I/chromium( 2955): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 34:FC:EF:11:B1:66 done with result: Connection to peer with ID 34:FC:EF:11:B1:66 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 3016): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3016): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 3016): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3016): StableState(): Entering Off State
,E/bt-btm  ( 3016): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3016): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-sdp  ( 3016): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
E/bt-btif ( 3016): DISCOVERY_COMP_EVT slot id:54, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3016): invalid rfc slot id: 54
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Failed to connect to socket/initiate handshake
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [58:2A:F7:ED:96:BE 58:2A:F7:ED:96:BE 58:2A:F7:ED:96:BE]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): shutdown
I/jxcore-log( 2955): 2015-12-01T11:01:08.603Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 58:2A:F7:ED:96:BE failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:01:08.603Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 58:2A:F7:ED:96:BE failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:01:08.604Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:01:13.605Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:01:13.606Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:01:18.609Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:01:18.610Z SendDataConnector.js: Connect (retry count 1) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:01:18.613Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:01:18.614Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
,I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 58:2A:F7:ED:96:BE
W/io.jxcore.node.ConnectionHelper( 2955): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to null in address 58:2A:F7:ED:96:BE
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: null 58:2A:F7:ED:96:BE
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to null in address 58:2A:F7:ED:96:BE
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3016): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
,E/bt-btif ( 3016): DISCOVERY_COMP_EVT slot id:55, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3016): invalid rfc slot id: 55
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [58:2A:F7:ED:96:BE 58:2A:F7:ED:96:BE 58:2A:F7:ED:96:BE]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): shutdown
,I/jxcore-log( 2955): 2015-12-01T11:01:23.803Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 58:2A:F7:ED:96:BE failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:01:23.804Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 58:2A:F7:ED:96:BE failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:01:23.804Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:01:28.805Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:01:28.806Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:01:33.810Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:01:33.812Z SendDataConnector.js: Connect (retry count 2) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:01:33.813Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:01:33.813Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 58:2A:F7:ED:96:BE
W/io.jxcore.node.ConnectionHelper( 2955): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to null in address 58:2A:F7:ED:96:BE
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: null 58:2A:F7:ED:96:BE
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to null in address 58:2A:F7:ED:96:BE
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051ec4 rs_disc_pending=1
E/bt-btm  ( 3016): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3016): onReceive
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: G3s-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): cancel: Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3016): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:56, channel:-1
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Cancelled: Connection timeout [58:2A:F7:ED:96:BE 58:2A:F7:ED:96:BE 58:2A:F7:ED:96:BE]
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [58:2A:F7:ED:96:BE 58:2A:F7:ED:96:BE 58:2A:F7:ED:96:BE]
I/jxcore-log( 2955): 2015-12-01T11:02:03.849Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 58:2A:F7:ED:96:BE failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:02:03.849Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 58:2A:F7:ED:96:BE failed
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:02:03.850Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:02:08.855Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:02:08.856Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:02:13.859Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:02:13.860Z SendDataConnector.js: Connect (retry count 3) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:02:13.865Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:02:13.866Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
,I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 58:2A:F7:ED:96:BE
W/io.jxcore.node.ConnectionHelper( 2955): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to null in address 58:2A:F7:ED:96:BE
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: null 58:2A:F7:ED:96:BE
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to null in address 58:2A:F7:ED:96:BE
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3016): DISCOVERY_COMP_EVT slot id:57, failed to find channle,                                       status:2, scn:126619823
,W/bt-btif ( 3016): invalid rfc slot id: 57
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Failed to connect to socket/initiate handshake
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [58:2A:F7:ED:96:BE 58:2A:F7:ED:96:BE 58:2A:F7:ED:96:BE]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): shutdown
,I/jxcore-log( 2955): 2015-12-01T11:02:13.917Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 58:2A:F7:ED:96:BE failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:02:13.917Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 58:2A:F7:ED:96:BE failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:02:13.917Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T11:02:18.918Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:02:18.919Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:02:23.923Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:02:23.924Z SendDataConnector.js: Connect (retry count 4) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:02:23.925Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:02:23.925Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 58:2A:F7:ED:96:BE
W/io.jxcore.node.ConnectionHelper( 2955): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to null in address 58:2A:F7:ED:96:BE
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: null 58:2A:F7:ED:96:BE
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to null in address 58:2A:F7:ED:96:BE
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3016): DISCOVERY_COMP_EVT slot id:58, failed to find channle,                                       status:2, scn:126619823
,W/bt-btif ( 3016): invalid rfc slot id: 58
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Failed to connect to socket/initiate handshake
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [58:2A:F7:ED:96:BE 58:2A:F7:ED:96:BE 58:2A:F7:ED:96:BE]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): shutdown
,I/jxcore-log( 2955): 2015-12-01T11:02:23.975Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 58:2A:F7:ED:96:BE failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:02:23.976Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 58:2A:F7:ED:96:BE failed
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:02:23.978Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:02:23.979Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2955): 
I/jxcore-log( 2955): ---- round done--------
I/jxcore-log( 2955): 
I/jxcore-log( 2955): ---- gotta redo : 58:2A:F7:ED:96:BE, try count now: 1
I/jxcore-log( 2955): 
I/jxcore-log( 2955): do fake peer & start
I/jxcore-log( 2955): 
I/jxcore-log( 2955): Connect to fake peer: F8:CF:C5:D9:E5:61
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:02:23.979Z SendDataConnector.js: Start called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:02:23.979Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:02:23.980Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to Nexus 6 in address F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: Nexus 6 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to Nexus 6 in address F8:CF:C5:D9:E5:61
I/chromium( 2955): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 58:2A:F7:ED:96:BE done with result: Connection to peer with ID 58:2A:F7:ED:96:BE failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3016): DISCOVERY_COMP_EVT slot id:59, failed to find channle,                                       status:2, scn:126619823
W/bt-btif ( 3016): invalid rfc slot id: 59
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3700 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): shutdown
I/jxcore-log( 2955): 2015-12-01T11:02:23.994Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:02:23.994Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:02:23.994Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T11:02:28.995Z SendDataConnector.js: re-try now : F8:CF:C5:D9:E5:61
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:02:28.996Z SendDataConnector.js: ReStart called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2955): 
,E/bt-btif ( 3016): DISCOVERY_COMP_EVT slot id:56, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3016): invalid rfc slot id: 56
,I/jxcore-log( 2955): 2015-12-01T11:02:33.999Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:02:34.000Z SendDataConnector.js: Connect (retry count 1) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:02:34.004Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:02:34.008Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
,I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to Nexus 6 in address F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: Nexus 6 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to Nexus 6 in address F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3016): info:x10
,D/        ( 3016): remote version info [f8:cf:c5:d9:e5:61]: 6, f, 410d
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: Nexus 6
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): cancel: Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:319)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3016): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:60, channel:5
,W/bt-btif ( 3016): invalid rfc slot id: 60
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Cancelled: Connection timeout [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3700 F8:CF:C5:D9:E5:61]
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3700 F8:CF:C5:D9:E5:61]
I/jxcore-log( 2955): 2015-12-01T11:03:04.047Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:03:04.048Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:03:04.050Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:03:09.055Z SendDataConnector.js: re-try now : F8:CF:C5:D9:E5:61
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:03:09.056Z SendDataConnector.js: ReStart called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2955): 
,E/bt-btm  ( 3016): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3016): onReceive
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: Nexus 6
,I/jxcore-log( 2955): 2015-12-01T11:03:14.060Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:03:14.060Z SendDataConnector.js: Connect (retry count 2) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:03:14.061Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:03:14.061Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to Nexus 6 in address F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: Nexus 6 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to Nexus 6 in address F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3016): info:x10
,D/        ( 3016): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: Nexus 6
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): cancel: Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:319)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3016): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:61, channel:5
,W/bt-btif ( 3016): invalid rfc slot id: 61
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Cancelled: Connection timeout [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3700 F8:CF:C5:D9:E5:61]
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3700 F8:CF:C5:D9:E5:61]
I/jxcore-log( 2955): 2015-12-01T11:03:44.099Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:03:44.100Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:03:44.104Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:03:49.108Z SendDataConnector.js: re-try now : F8:CF:C5:D9:E5:61
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:03:49.109Z SendDataConnector.js: ReStart called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2955): 
,E/bt-btm  ( 3016): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 3016): L2CAP got sec_comp for unknown BD_ADDR
,D/BluetoothMapService( 3016): onReceive
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: Nexus 6
,I/jxcore-log( 2955): 2015-12-01T11:03:54.113Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:03:54.114Z SendDataConnector.js: Connect (retry count 3) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:03:54.115Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:03:54.115Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to Nexus 6 in address F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: Nexus 6 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to Nexus 6 in address F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3016): info:x10
,D/        ( 3016): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: Nexus 6
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): cancel: Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:319)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3016): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:62, channel:5
,W/bt-btif ( 3016): invalid rfc slot id: 62
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Cancelled: Connection timeout [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3700 F8:CF:C5:D9:E5:61]
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3700 F8:CF:C5:D9:E5:61]
I/jxcore-log( 2955): 2015-12-01T11:04:24.153Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:04:24.153Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:04:24.154Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:04:29.156Z SendDataConnector.js: re-try now : F8:CF:C5:D9:E5:61
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:04:29.158Z SendDataConnector.js: ReStart called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2955): 
,E/bt-btm  ( 3016): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3016): onReceive
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: Nexus 6
,I/jxcore-log( 2955): 2015-12-01T11:04:34.167Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:04:34.167Z SendDataConnector.js: Connect (retry count 4) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:04:34.168Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:04:34.168Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to Nexus 6 in address F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: Nexus 6 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to Nexus 6 in address F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3016): info:x10
,D/        ( 3016): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: Nexus 6
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,W/GCM     ( 1361): Heartbeat timeout, GCM connection reset -34
,D/ConnectivityService(  760): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 01 Dec 2015 11:04:36 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1448967876821], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1448967876803]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Validated
,D/ConnectivityService(  760): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  760): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  760): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  760): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1562): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): cancel: Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:319)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3016): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:63, channel:5
,W/bt-btif ( 3016): invalid rfc slot id: 63
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Cancelled: Connection timeout [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3700 F8:CF:C5:D9:E5:61]
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3700 F8:CF:C5:D9:E5:61]
I/jxcore-log( 2955): 2015-12-01T11:05:04.206Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:05:04.207Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:05:04.224Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:05:04.227Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2955): 
I/jxcore-log( 2955): ---- round done--------
I/jxcore-log( 2955): 
I/jxcore-log( 2955): ---- gotta redo : F8:CF:C5:D9:E5:61, try count now: 1
I/jxcore-log( 2955): 
I/jxcore-log( 2955): do fake peer & start
I/jxcore-log( 2955): 
I/jxcore-log( 2955): Connect to fake peer: 7C:F9:0E:34:8A:A0
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:05:04.230Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:05:04.235Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:05:04.236Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
,I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
W/io.jxcore.node.ConnectionHelper( 2955): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to null in address 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: null 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to null in address 7C:F9:0E:34:8A:A0
I/chromium( 2955): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F8:CF:C5:D9:E5:61 done with result: Connection to peer with ID F8:CF:C5:D9:E5:61 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3016): info:x10
,D/        ( 3016): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 3016): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3016): btm_sec_disconnected - Clearing Pending flag
E/bt-btif ( 3016): Do not find the bg connection mask for the remote device
,E/bt-btif ( 3016): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3016): bondStateChangeCallback: Status: 1 Address: F8:CF:C5:D9:E5:61 newState: 0
,E/BluetoothBondStateMachine( 3016): In stable state, received invalid newState: 10
,D/BluetoothMapService( 3016): onReceive
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: Nexus 6
,I/BluetoothBondStateMachine( 3016): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
E/bt-btif ( 3016): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3016): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3016): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3016): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 3016): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 3016): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3016): StableState(): Entering Off State
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): cancel: Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:319)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3016): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:64, channel:6
,W/bt-btif ( 3016): invalid rfc slot id: 64
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Cancelled: Connection timeout [7C:F9:0E:34:8A:A0 7C:F9:0E:34:8A:A0 7C:F9:0E:34:8A:A0]
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [7C:F9:0E:34:8A:A0 7C:F9:0E:34:8A:A0 7C:F9:0E:34:8A:A0]
I/jxcore-log( 2955): 2015-12-01T11:05:34.272Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:05:34.272Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:05:34.273Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:05:39.274Z SendDataConnector.js: re-try now : 7C:F9:0E:34:8A:A0
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:05:39.275Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2955): 
,E/bt-btm  ( 3016): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 3016): L2CAP got sec_comp for unknown BD_ADDR
,D/BluetoothMapService( 3016): onReceive
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: S5-1
,I/jxcore-log( 2955): 2015-12-01T11:05:44.279Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:05:44.279Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:34:8A:A0 with availability status: true
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:05:44.280Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:05:44.285Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
,I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
W/io.jxcore.node.ConnectionHelper( 2955): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to S5-1 in address 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: S5-1 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to S5-1 in address 7C:F9:0E:34:8A:A0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3016): info:x10
,D/        ( 3016): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 230f
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: S5-1
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-l2cap( 3016): L2CAP got conn_comp for unknown BD_ADDR
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa40525e4 rs_disc_pending=0
E/bt-btm  ( 3016): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 3016): L2CAP got sec_comp for unknown BD_ADDR
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): invalid rfc slot id: 65
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:319)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [7C:F9:0E:34:8A:A0 7C:F9:0E:34:8A:A0 7C:F9:0E:34:8A:A0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): shutdown
I/jxcore-log( 2955): 2015-12-01T11:06:10.343Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:06:10.344Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:06:10.345Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,D/BluetoothMapService( 3016): onReceive
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: S5-1
,I/jxcore-log( 2955): 2015-12-01T11:06:15.346Z SendDataConnector.js: re-try now : 7C:F9:0E:34:8A:A0
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:06:15.347Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:06:20.352Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:06:20.353Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:34:8A:A0 with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:06:20.353Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:06:20.354Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
W/io.jxcore.node.ConnectionHelper( 2955): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to S5-1 in address 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: S5-1 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to S5-1 in address 7C:F9:0E:34:8A:A0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3016): info:x10
,D/        ( 3016): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: S5-1
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa40525e4 rs_disc_pending=0
E/bt-btm  ( 3016): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 3016): L2CAP got sec_comp for unknown BD_ADDR
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): invalid rfc slot id: 66
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:319)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [7C:F9:0E:34:8A:A0 7C:F9:0E:34:8A:A0 7C:F9:0E:34:8A:A0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): shutdown
I/jxcore-log( 2955): 2015-12-01T11:06:32.558Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:06:32.558Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:06:32.559Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,D/BluetoothMapService( 3016): onReceive
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: S5-1
,I/jxcore-log( 2955): 2015-12-01T11:06:37.560Z SendDataConnector.js: re-try now : 7C:F9:0E:34:8A:A0
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:06:37.561Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:06:42.565Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:06:42.566Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:34:8A:A0 with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:06:42.566Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:06:42.567Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
W/io.jxcore.node.ConnectionHelper( 2955): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to S5-1 in address 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: S5-1 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to S5-1 in address 7C:F9:0E:34:8A:A0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3016): info:x10
,D/        ( 3016): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: S5-1
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): cancel: Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:319)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3016): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:67, channel:6
,W/bt-btif ( 3016): invalid rfc slot id: 67
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Cancelled: Connection timeout [7C:F9:0E:34:8A:A0 7C:F9:0E:34:8A:A0 7C:F9:0E:34:8A:A0]
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [7C:F9:0E:34:8A:A0 7C:F9:0E:34:8A:A0 7C:F9:0E:34:8A:A0]
I/jxcore-log( 2955): 2015-12-01T11:07:12.605Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:07:12.606Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:07:12.606Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,W/bt-btif ( 3016): info:x10
,D/        ( 3016): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 3016): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa40525e4 rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3016): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 3016): L2CAP got sec_comp for unknown BD_ADDR
,D/BluetoothMapService( 3016): onReceive
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: S5-1
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2955): 2015-12-01T11:07:17.608Z SendDataConnector.js: re-try now : 7C:F9:0E:34:8A:A0
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:07:17.608Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2955): 
,I/BluetoothBondStateMachine( 3016): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 1
E/bt-btif ( 3016): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3016): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3016): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3016): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 0
,D/BluetoothAdapterProperties( 3016): Failed to remove device: E0:DB:10:1F:C9:5E
,I/BluetoothBondStateMachine( 3016): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3016): StableState(): Entering Off State
,I/jxcore-log( 2955): 2015-12-01T11:07:22.613Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:07:22.614Z SendDataConnector.js: Connect (retry count 4) to peer 7C:F9:0E:34:8A:A0 with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:07:22.614Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:07:22.615Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
W/io.jxcore.node.ConnectionHelper( 2955): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to S5-1 in address 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: S5-1 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to S5-1 in address 7C:F9:0E:34:8A:A0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btm  ( 3016): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=2
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3016): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3016): onReceive
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: Note3-1
,W/bt-btif ( 3016): info:x10
,D/        ( 3016): remote version info [08:ec:a9:50:76:27]: 7, f, 610c
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:255
W/bt-btif ( 3016): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3016): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection initialized (thread ID: 431)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 431)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesRead: Read 83 bytes successfully (thread ID: 431)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Got valid identity from [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 431)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): removeThreadFromList: Removing thread with ID 431
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Handshake thread disposed (thread ID: 431)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onIncomingConnectionConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 431)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming connection, peer ID: 08:EC:A9:50:76:27, name: samsung-SM-A300FU_PT4311, Bluetooth address: 08:EC:A9:50:76:27
,I/io.jxcore.node.IncomingSocketThread( 2955): Constructed
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming socket thread using port 0 and is now connected
,I/io.jxcore.node.IncomingSocketThread( 2955): Entering thread
,I/jxcore-log( 2955): 2015-12-01T11:07:27.416Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2955): 
,I/io.jxcore.node.IncomingSocketThread( 2955): Local host address: localhost/127.0.0.1, port: 59747
I/io.jxcore.node.IncomingSocketThread( 2955): Local streams created successfully, starting stream copying threads...
I/io.jxcore.node.SocketThreadBase( 2955): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 2955): Exiting thread
,W/bt-sdp  ( 3016): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 3016): DISCOVERY_COMP_EVT slot id:68, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3016): invalid rfc slot id: 68
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [7C:F9:0E:34:8A:A0 7C:F9:0E:34:8A:A0 7C:F9:0E:34:8A:A0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): shutdown
,I/jxcore-log( 2955): 2015-12-01T11:07:27.770Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:07:27.770Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:07:27.792Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:07:27.794Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2955): 
I/jxcore-log( 2955): ---- round done--------
I/jxcore-log( 2955): 
I/jxcore-log( 2955): ---- gotta redo : 7C:F9:0E:34:8A:A0, try count now: 1
I/jxcore-log( 2955): 
I/jxcore-log( 2955): do fake peer & start
I/jxcore-log( 2955): 
I/jxcore-log( 2955): Connect to fake peer: B4:CE:F6:AB:A4:6A
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:07:27.800Z SendDataConnector.js: Start called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:07:27.805Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:07:27.806Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
,I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID B4:CE:F6:AB:A4:6A
W/io.jxcore.node.ConnectionHelper( 2955): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to null in address B4:CE:F6:AB:A4:6A
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: null B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to null in address B4:CE:F6:AB:A4:6A
I/chromium( 2955): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 7C:F9:0E:34:8A:A0 done with result: Connection to peer with ID 7C:F9:0E:34:8A:A0 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3016): invalid rfc slot id: 50
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: bt socket closed, read return: -1
E/io.jxcore.node.SocketThreadBase( 2955): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 432
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 2955): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: Socket closed
,I/jxcore-log( 2955): 2015-12-01T11:07:28.003Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2955): 
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa40517a4 rs_disc_pending=1
,W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3016): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 3016): RFCOMM_DisconnectInd LCID:0x47
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/UsageStatsService(  760): User[0] Flushing usage stats to disk
,E/bt-btm  ( 3016): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3016): onReceive
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/bt-sdp  ( 3016): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 3016): DISCOVERY_COMP_EVT slot id:70, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3016): invalid rfc slot id: 70
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [B4:CE:F6:AB:A4:6A B4:CE:F6:AB:A4:6A B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): shutdown
I/jxcore-log( 2955): 2015-12-01T11:07:34.438Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:07:34.438Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:07:34.439Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,W/bt-btif ( 3016): info:x10
,D/        ( 3016): remote version info [e0:db:10:1f:c9:5e]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: Note3-1
,E/bt-btm  ( 3016): peer should have initiated security process by now (SM4 to SM4)
,E/bt-btm  ( 3016): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 3016): L2CAP got sec_comp for unknown BD_ADDR
,D/BluetoothMapService( 3016): onReceive
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: Note3-1
,I/jxcore-log( 2955): 2015-12-01T11:07:39.442Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:07:39.442Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2955): 
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2955): 2015-12-01T11:07:44.447Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:07:44.448Z SendDataConnector.js: Connect (retry count 1) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:07:44.448Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:07:44.449Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
,I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID B4:CE:F6:AB:A4:6A
W/io.jxcore.node.ConnectionHelper( 2955): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to null in address B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: null B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to null in address B4:CE:F6:AB:A4:6A
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3016): info:x10
,D/        ( 3016): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3016): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3016): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 1
E/bt-btif ( 3016): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3016): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3016): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3016): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 0
,D/BluetoothAdapterProperties( 3016): Failed to remove device: B4:CE:F6:AB:A4:6A
,I/BluetoothBondStateMachine( 3016): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3016): StableState(): Entering Off State
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:1
W/bt-btif ( 3016): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3016): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Outgoing connection initialized (thread ID: 437)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 437)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 437)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesRead: Read 84 bytes successfully (thread ID: 437)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Handshake succeeded with [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT6617 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnected: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT6617 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 437)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT6617 B4:CE:F6:AB:A4:6A]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing connection, peer ID: B4:CE:F6:AB:A4:6A, name: HTC-HTC Desire 820_PT6617, Bluetooth address: B4:CE:F6:AB:A4:6A
I/io.jxcore.node.ConnectionHelper( 2955): addNewPeerToListAndNotify: Adding peer with ID B4:CE:F6:AB:A4:6A
I/io.jxcore.node.OutgoingSocketThread( 2955): Constructed
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 2955): Server socket local port: 35810
I/io.jxcore.node.ConnectionHelper( 2955): Outgoing connection is using port 35810
I/io.jxcore.node.OutgoingSocketThread( 2955): Now accepting connections...
,I/jxcore-log( 2955): 2015-12-01T11:07:46.301Z SendDataConnector.js: CLIENT connected to 35810, error: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:07:46.302Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:07:46.302Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,W/bt-btif ( 3016): info:x10
,D/        ( 3016): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: Note3-1
,E/bt-btm  ( 3016): peer should have initiated security process by now (SM4 to SM4)
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa40527ac rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3016): dm_pm_timer expires
W/bt-btif ( 3016): dm_pm_timer expires 0
,W/bt-btif ( 3016): proc dm_pm_timer expires
,I/jxcore-log( 2955): 2015-12-01T11:07:51.303Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:07:51.303Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2955): 
,E/bt-btm  ( 3016): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 3016): L2CAP got sec_comp for unknown BD_ADDR
,D/BluetoothMapService( 3016): onReceive
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: Note3-1,
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa40527ac rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: B4:CE:F6:AB:A4:6A
I/io.jxcore.node.OutgoingSocketThread( 2955): close
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 2955): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T11:07:56.324Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:07:56.325Z SendDataConnector.js: Connect (retry count 2) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:07:56.326Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:07:56.326Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to HTC Desire 820 in address B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: HTC Desire 820 B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to HTC Desire 820 in address B4:CE:F6:AB:A4:6A
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3016): bta_jv_rfc_port_to_cb(port_handle:0x1e):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Outgoing connection initialized (thread ID: 440)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 440)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 440)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesRead: Read 84 bytes successfully (thread ID: 440)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Handshake succeeded with [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT6617 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnected: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT6617 B4:CE:F6:AB:A4:6A]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT6617 B4:CE:F6:AB:A4:6A]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing connection, peer ID: B4:CE:F6:AB:A4:6A, name: HTC-HTC Desire 820_PT6617, Bluetooth address: B4:CE:F6:AB:A4:6A
,I/io.jxcore.node.OutgoingSocketThread( 2955): Constructed
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing socket thread created successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 440)
,I/io.jxcore.node.OutgoingSocketThread( 2955): Server socket local port: 38928
I/io.jxcore.node.ConnectionHelper( 2955): Outgoing connection is using port 38928
I/io.jxcore.node.OutgoingSocketThread( 2955): Now accepting connections...
,I/jxcore-log( 2955): 2015-12-01T11:07:57.111Z SendDataConnector.js: CLIENT connected to 38928, error: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:07:57.112Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:07:57.112Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,W/bt-btif ( 3016): dm_pm_timer expires
W/bt-btif ( 3016): dm_pm_timer expires 0
,W/bt-btif ( 3016): proc dm_pm_timer expires
,I/jxcore-log( 2955): 2015-12-01T11:08:02.113Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:08:02.114Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2955): 
,W/bt-btif ( 3016): info:x10
,D/        ( 3016): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: Note3-1
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:255
W/bt-btif ( 3016): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3016): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection initialized (thread ID: 442)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 442)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesRead: Read 82 bytes successfully (thread ID: 442)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Got valid identity from [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT5487 E0:DB:10:1F:C9:5E]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 442)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): removeThreadFromList: Removing thread with ID 442
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Handshake thread disposed (thread ID: 442)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onIncomingConnectionConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT5487 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 442)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT5487 E0:DB:10:1F:C9:5E]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming connection, peer ID: E0:DB:10:1F:C9:5E, name: samsung-SM-N9005_PT5487, Bluetooth address: E0:DB:10:1F:C9:5E
I/io.jxcore.node.ConnectionHelper( 2955): addNewPeerToListAndNotify: Adding peer with ID E0:DB:10:1F:C9:5E
I/io.jxcore.node.IncomingSocketThread( 2955): Constructed
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming socket thread using port 0 and is now connected
,I/io.jxcore.node.IncomingSocketThread( 2955): Entering thread
,I/io.jxcore.node.IncomingSocketThread( 2955): Local host address: localhost/127.0.0.1, port: 59747
I/io.jxcore.node.IncomingSocketThread( 2955): Local streams created successfully, starting stream copying threads...
I/io.jxcore.node.SocketThreadBase( 2955): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T11:08:04.052Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2955): 
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa40527ac rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: B4:CE:F6:AB:A4:6A
I/io.jxcore.node.OutgoingSocketThread( 2955): close
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 2955): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T11:08:07.118Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:08:07.119Z SendDataConnector.js: Connect (retry count 3) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:08:07.119Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:08:07.119Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to HTC Desire 820 in address B4:CE:F6:AB:A4:6A
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: HTC Desire 820 B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to HTC Desire 820 in address B4:CE:F6:AB:A4:6A
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3016): bta_jv_rfc_port_to_cb(port_handle:0x1):jv handle:0x0 not FOUND
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa40527ac rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Outgoing connection initialized (thread ID: 447)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 447)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 447)
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa40527ac rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesRead: Read 84 bytes successfully (thread ID: 447)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Handshake succeeded with [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT6617 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnected: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT6617 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 447)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT6617 B4:CE:F6:AB:A4:6A]
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing connection, peer ID: B4:CE:F6:AB:A4:6A, name: HTC-HTC Desire 820_PT6617, Bluetooth address: B4:CE:F6:AB:A4:6A
,I/io.jxcore.node.OutgoingSocketThread( 2955): Constructed
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 2955): Server socket local port: 33286
I/io.jxcore.node.ConnectionHelper( 2955): Outgoing connection is using port 33286
,I/io.jxcore.node.OutgoingSocketThread( 2955): Now accepting connections...
,I/jxcore-log( 2955): 2015-12-01T11:08:10.332Z SendDataConnector.js: CLIENT connected to 33286, error: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:08:10.333Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:08:10.334Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3016): invalid rfc slot id: 69
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: bt socket closed, read return: -1
,E/io.jxcore.node.SocketThreadBase( 2955): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 443
,I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 2955): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: Socket closed
,I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,I/jxcore-log( 2955): 2015-12-01T11:08:14.943Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2955): 
,W/bt-btif ( 3016): dm_pm_timer expires
W/bt-btif ( 3016): dm_pm_timer expires 0
,W/bt-btif ( 3016): proc dm_pm_timer expires
,W/bt-rfcomm( 3016): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
,W/bt-rfcomm( 3016): RFCOMM_DisconnectInd LCID:0x4c
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:255
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection initialized (thread ID: 449)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 449)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesRead: Read 82 bytes successfully (thread ID: 449)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Got valid identity from [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT5487 E0:DB:10:1F:C9:5E]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 449)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): removeThreadFromList: Removing thread with ID 449
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Handshake thread disposed (thread ID: 449)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onIncomingConnectionConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT5487 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 449)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT5487 E0:DB:10:1F:C9:5E]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming connection, peer ID: E0:DB:10:1F:C9:5E, name: samsung-SM-N9005_PT5487, Bluetooth address: E0:DB:10:1F:C9:5E
,I/io.jxcore.node.IncomingSocketThread( 2955): Constructed
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming socket thread using port 0 and is now connected
,I/io.jxcore.node.IncomingSocketThread( 2955): Entering thread
,I/jxcore-log( 2955): 2015-12-01T11:08:15.263Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2955): 
,I/io.jxcore.node.IncomingSocketThread( 2955): Local host address: localhost/127.0.0.1, port: 59747
,I/io.jxcore.node.IncomingSocketThread( 2955): Local streams created successfully, starting stream copying threads...
,I/io.jxcore.node.SocketThreadBase( 2955): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T11:08:15.335Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:08:15.335Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2955): 
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa40527ac rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3016): invalid rfc slot id: 73
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: bt socket closed, read return: -1
,E/io.jxcore.node.SocketThreadBase( 2955): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 450
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 2955): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: Socket closed
,I/jxcore-log( 2955): 2015-12-01T11:08:15.825Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2955): 
,W/bt-rfcomm( 3016): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
W/bt-rfcomm( 3016): RFCOMM_DisconnectInd LCID:0x4d
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3016): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3016): onReceive
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: Note3-1
,I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: B4:CE:F6:AB:A4:6A
I/io.jxcore.node.OutgoingSocketThread( 2955): close
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 2955): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T11:08:20.362Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:08:20.363Z SendDataConnector.js: Connect (retry count 4) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:08:20.363Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:08:20.364Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to HTC Desire 820 in address B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: HTC Desire 820 B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to HTC Desire 820 in address B4:CE:F6:AB:A4:6A
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3016): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Outgoing connection initialized (thread ID: 454)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 454)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 454)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesRead: Read 84 bytes successfully (thread ID: 454)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Handshake succeeded with [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT6617 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnected: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT6617 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 454)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT6617 B4:CE:F6:AB:A4:6A]
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing connection, peer ID: B4:CE:F6:AB:A4:6A, name: HTC-HTC Desire 820_PT6617, Bluetooth address: B4:CE:F6:AB:A4:6A
I/io.jxcore.node.OutgoingSocketThread( 2955): Constructed
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 2955): Server socket local port: 53534
I/io.jxcore.node.ConnectionHelper( 2955): Outgoing connection is using port 53534
I/io.jxcore.node.OutgoingSocketThread( 2955): Now accepting connections...
,I/jxcore-log( 2955): 2015-12-01T11:08:21.856Z SendDataConnector.js: CLIENT connected to 53534, error: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:08:21.857Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:08:21.875Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: B4:CE:F6:AB:A4:6A
I/io.jxcore.node.OutgoingSocketThread( 2955): close
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 2955): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,W/bt-btif ( 3016): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,I/io.jxcore.node.OutgoingSocketThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T11:08:21.898Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2955): 
I/jxcore-log( 2955): ---- round done--------
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): ---- gotta redo : B4:CE:F6:AB:A4:6A, try count now: 1
I/jxcore-log( 2955): 
I/jxcore-log( 2955): do fake peer & start
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): Connect to fake peer: F8:95:C7:87:3C:51
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:08:21.907Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:08:21.910Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:08:21.916Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to G4-1 in address F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: G4-1 F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to G4-1 in address F8:95:C7:87:3C:51
,I/chromium( 2955): [INFO:CONSOLE(63)] "logCallback Round of send data to peer B4:CE:F6:AB:A4:6A done with result: Listening for incoming connections", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa40527ac rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3016): info:x10
,D/        ( 3016): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: G4-1
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btm  ( 3016): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa40527ac rs_disc_pending=2
E/bt-btm  ( 3016): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3016): onReceive
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: HTC Desire 820
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3016): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3016): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3016): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3016): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3016): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3016): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 3016): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3016): StableState(): Entering Off State
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:1
W/bt-btif ( 3016): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3016): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Outgoing connection initialized (thread ID: 457)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 457)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 457)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesRead: Read 76 bytes successfully (thread ID: 457)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Handshake succeeded with [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing connection, peer ID: F8:95:C7:87:3C:51, name: LGE-LG-H815_PT920, Bluetooth address: F8:95:C7:87:3C:51
,I/io.jxcore.node.OutgoingSocketThread( 2955): Constructed
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing socket thread created successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 457)
,I/io.jxcore.node.OutgoingSocketThread( 2955): Server socket local port: 46470
I/io.jxcore.node.ConnectionHelper( 2955): Outgoing connection is using port 46470
I/io.jxcore.node.OutgoingSocketThread( 2955): Now accepting connections...
,I/jxcore-log( 2955): 2015-12-01T11:08:28.774Z SendDataConnector.js: CLIENT connected to 46470, error: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:08:28.775Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:08:28.775Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3016): info:x10
,D/        ( 3016): remote version info [00:00:00:00:5a:ad]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3016): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3016): dm_pm_timer expires
W/bt-btif ( 3016): dm_pm_timer expires 0
W/bt-btif ( 3016): proc dm_pm_timer expires
,I/jxcore-log( 2955): 2015-12-01T11:08:33.776Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:08:33.776Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 2955): 
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 3016): bondStateChangeCallback: Status: 0 Address: 00:00:00:00:5A:AD newState: 1
E/bt-btif ( 3016): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3016): Bond State Change Intent:00:00:00:00:5A:AD OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3016): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3016): bondStateChangeCallback: Status: 0 Address: 00:00:00:00:5A:AD newState: 0
,D/BluetoothAdapterProperties( 3016): Failed to remove device: 00:00:00:00:5A:AD
,I/BluetoothBondStateMachine( 3016): Bond State Change Intent:00:00:00:00:5A:AD OldState: 11 NewState: 10
,W/BackupManagerService(  760): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,W/BackupManagerService(  760): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,W/BackupManagerService(  760): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/BluetoothBondStateMachine( 3016): StableState(): Entering Off State
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:255
W/bt-btif ( 3016): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3016): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection initialized (thread ID: 459)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 459)
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4052974 rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesRead: Read 83 bytes successfully (thread ID: 459)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Got valid identity from [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3175 08:EC:A9:50:75:41]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 459)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): removeThreadFromList: Removing thread with ID 459
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Handshake thread disposed (thread ID: 459)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onIncomingConnectionConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3175 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 459)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3175 08:EC:A9:50:75:41]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming connection, peer ID: 08:EC:A9:50:75:41, name: samsung-SM-A300FU_PT3175, Bluetooth address: 08:EC:A9:50:75:41
,I/io.jxcore.node.ConnectionHelper( 2955): addNewPeerToListAndNotify: Adding peer with ID 08:EC:A9:50:75:41
,I/io.jxcore.node.IncomingSocketThread( 2955): Constructed
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming socket thread using port 0 and is now connected
,I/io.jxcore.node.IncomingSocketThread( 2955): Entering thread
,I/io.jxcore.node.IncomingSocketThread( 2955): Local host address: localhost/127.0.0.1, port: 59747
I/io.jxcore.node.IncomingSocketThread( 2955): Local streams created successfully, starting stream copying threads...
,I/jxcore-log( 2955): 2015-12-01T11:08:36.445Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2955): 
,I/io.jxcore.node.SocketThreadBase( 2955): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 2955): Exiting thread
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: F8:95:C7:87:3C:51
I/io.jxcore.node.OutgoingSocketThread( 2955): close
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 2955): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T11:08:38.798Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:08:38.799Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:08:38.800Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:08:38.800Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
,I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,W/bt-btif ( 3016): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to G4-1 in address F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: G4-1 F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to G4-1 in address F8:95:C7:87:3C:51
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4052974 rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Outgoing connection initialized (thread ID: 464)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 464)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 464)
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesRead: Read 76 bytes successfully (thread ID: 464)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Handshake succeeded with [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 464)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing connection, peer ID: F8:95:C7:87:3C:51, name: LGE-LG-H815_PT920, Bluetooth address: F8:95:C7:87:3C:51
I/io.jxcore.node.OutgoingSocketThread( 2955): Constructed
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 2955): Server socket local port: 33323
,I/io.jxcore.node.ConnectionHelper( 2955): Outgoing connection is using port 33323
I/io.jxcore.node.OutgoingSocketThread( 2955): Now accepting connections...
,I/jxcore-log( 2955): 2015-12-01T11:08:40.181Z SendDataConnector.js: CLIENT connected to 33323, error: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:08:40.182Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:08:40.183Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3016): dm_pm_timer expires
W/bt-btif ( 3016): dm_pm_timer expires 0
W/bt-btif ( 3016): proc dm_pm_timer expires
,I/jxcore-log( 2955): 2015-12-01T11:08:45.184Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:08:45.184Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 2955): 
,W/bt-btif ( 3016): invalid rfc slot id: 75
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: bt socket closed, read return: -1
,E/io.jxcore.node.SocketThreadBase( 2955): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
,I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 460
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 2955): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: Socket closed
,I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,I/jxcore-log( 2955): 2015-12-01T11:08:47.311Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2955): 
,W/bt-rfcomm( 3016): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
W/bt-rfcomm( 3016): RFCOMM_DisconnectInd LCID:0x48
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:255
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection initialized (thread ID: 466)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 466)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesRead: Read 83 bytes successfully (thread ID: 466)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Got valid identity from [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3175 08:EC:A9:50:75:41]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 466)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): removeThreadFromList: Removing thread with ID 466
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Handshake thread disposed (thread ID: 466)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onIncomingConnectionConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3175 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 466)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3175 08:EC:A9:50:75:41]
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming connection, peer ID: 08:EC:A9:50:75:41, name: samsung-SM-A300FU_PT3175, Bluetooth address: 08:EC:A9:50:75:41
I/io.jxcore.node.IncomingSocketThread( 2955): Constructed
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming socket thread using port 0 and is now connected
,I/io.jxcore.node.IncomingSocketThread( 2955): Entering thread
,I/io.jxcore.node.IncomingSocketThread( 2955): Local host address: localhost/127.0.0.1, port: 59747
I/io.jxcore.node.IncomingSocketThread( 2955): Local streams created successfully, starting stream copying threads...
,I/jxcore-log( 2955): 2015-12-01T11:08:48.503Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2955): 
,I/io.jxcore.node.SocketThreadBase( 2955): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 2955): Exiting thread
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: F8:95:C7:87:3C:51
,I/io.jxcore.node.OutgoingSocketThread( 2955): close
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 2955): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T11:08:50.189Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:08:50.189Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:08:50.189Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:08:50.189Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
,I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to G4-1 in address F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: G4-1 F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to G4-1 in address F8:95:C7:87:3C:51
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3016): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Outgoing connection initialized (thread ID: 471)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 471)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 471)
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesRead: Read 76 bytes successfully (thread ID: 471)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Handshake succeeded with [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 471)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing connection, peer ID: F8:95:C7:87:3C:51, name: LGE-LG-H815_PT920, Bluetooth address: F8:95:C7:87:3C:51
I/io.jxcore.node.OutgoingSocketThread( 2955): Constructed
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 2955): Server socket local port: 40150
I/io.jxcore.node.ConnectionHelper( 2955): Outgoing connection is using port 40150
I/io.jxcore.node.OutgoingSocketThread( 2955): Now accepting connections...
,I/jxcore-log( 2955): 2015-12-01T11:08:51.306Z SendDataConnector.js: CLIENT connected to 40150, error: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:08:51.307Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:08:51.307Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,W/bt-btif ( 3016): dm_pm_timer expires
W/bt-btif ( 3016): dm_pm_timer expires 0
,W/bt-btif ( 3016): proc dm_pm_timer expires
,W/bt-btif ( 3016): info:x10
,D/        ( 3016): remote version info [80:01:84:8a:b3:68]: 6, f, 6109
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 2955): 2015-12-01T11:08:56.307Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:08:56.307Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 2955): 
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa405124c rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:255
W/bt-btif ( 3016): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3016): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection initialized (thread ID: 473)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 473)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesRead: Read 84 bytes successfully (thread ID: 473)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Got valid identity from [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5457 80:01:84:8A:B3:68]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 473)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): removeThreadFromList: Removing thread with ID 473
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Handshake thread disposed (thread ID: 473)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onIncomingConnectionConnected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5457 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 473)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5457 80:01:84:8A:B3:68]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming connection, peer ID: 80:01:84:8A:B3:68, name: HTC-HTC Desire 820_PT5457, Bluetooth address: 80:01:84:8A:B3:68
I/io.jxcore.node.IncomingSocketThread( 2955): Constructed
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming socket thread using port 0 and is now connected
,I/io.jxcore.node.IncomingSocketThread( 2955): Entering thread
,I/jxcore-log( 2955): 2015-12-01T11:08:57.867Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2955): 
,I/io.jxcore.node.IncomingSocketThread( 2955): Local host address: localhost/127.0.0.1, port: 59747
I/io.jxcore.node.IncomingSocketThread( 2955): Local streams created successfully, starting stream copying threads...
,I/io.jxcore.node.SocketThreadBase( 2955): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 2955): Exiting thread
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3016): invalid rfc slot id: 78
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: bt socket closed, read return: -1
,E/io.jxcore.node.SocketThreadBase( 2955): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
,I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 467
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping receiving thread...
,I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 2955): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: Socket closed
,I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,I/jxcore-log( 2955): 2015-12-01T11:08:59.299Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2955): 
,W/bt-rfcomm( 3016): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
W/bt-rfcomm( 3016): RFCOMM_DisconnectInd LCID:0x45
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:255
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection initialized (thread ID: 477)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 477)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesRead: Read 83 bytes successfully (thread ID: 477)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Got valid identity from [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3175 08:EC:A9:50:75:41]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 477)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): removeThreadFromList: Removing thread with ID 477
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Handshake thread disposed (thread ID: 477)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onIncomingConnectionConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3175 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 477)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3175 08:EC:A9:50:75:41]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming connection, peer ID: 08:EC:A9:50:75:41, name: samsung-SM-A300FU_PT3175, Bluetooth address: 08:EC:A9:50:75:41
I/io.jxcore.node.IncomingSocketThread( 2955): Constructed
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming socket thread using port 0 and is now connected
,I/io.jxcore.node.IncomingSocketThread( 2955): Entering thread
,I/jxcore-log( 2955): 2015-12-01T11:09:00.191Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2955): 
,I/io.jxcore.node.IncomingSocketThread( 2955): Local host address: localhost/127.0.0.1, port: 59747
,I/io.jxcore.node.IncomingSocketThread( 2955): Local streams created successfully, starting stream copying threads...
,I/io.jxcore.node.SocketThreadBase( 2955): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 2955): Exiting thread
,I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: F8:95:C7:87:3C:51
I/io.jxcore.node.OutgoingSocketThread( 2955): close
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,I/jxcore-log( 2955): 2015-12-01T11:09:01.309Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:09:01.310Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:09:01.310Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:09:01.310Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
,E/io.jxcore.node.OutgoingSocketThread( 2955): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
I/io.jxcore.node.OutgoingSocketThread( 2955): Exiting thread
,I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to G4-1 in address F8:95:C7:87:3C:51
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: G4-1 F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to G4-1 in address F8:95:C7:87:3C:51
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3016): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Outgoing connection initialized (thread ID: 482)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 482)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 482)
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesRead: Read 76 bytes successfully (thread ID: 482)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Handshake succeeded with [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 482)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing connection, peer ID: F8:95:C7:87:3C:51, name: LGE-LG-H815_PT920, Bluetooth address: F8:95:C7:87:3C:51
,I/io.jxcore.node.OutgoingSocketThread( 2955): Constructed
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 2955): Server socket local port: 48448
I/io.jxcore.node.ConnectionHelper( 2955): Outgoing connection is using port 48448
I/io.jxcore.node.OutgoingSocketThread( 2955): Now accepting connections...
,I/jxcore-log( 2955): 2015-12-01T11:09:02.725Z SendDataConnector.js: CLIENT connected to 48448, error: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:09:02.726Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:09:02.726Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,W/bt-btif ( 3016): dm_pm_timer expires
W/bt-btif ( 3016): dm_pm_timer expires 0
,W/bt-btif ( 3016): proc dm_pm_timer expires
,I/jxcore-log( 2955): 2015-12-01T11:09:07.727Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:09:07.728Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 2955): 
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3016): invalid rfc slot id: 80
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: bt socket closed, read return: -1
E/io.jxcore.node.SocketThreadBase( 2955): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 474
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 2955): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: Socket closed
,I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,I/jxcore-log( 2955): 2015-12-01T11:09:08.551Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2955): 
,W/bt-rfcomm( 3016): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 3016): RFCOMM_DisconnectInd LCID:0x47
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:255
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection initialized (thread ID: 484)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 484)
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesRead: Read 84 bytes successfully (thread ID: 484)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Got valid identity from [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5457 80:01:84:8A:B3:68]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 484)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): removeThreadFromList: Removing thread with ID 484
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Handshake thread disposed (thread ID: 484)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onIncomingConnectionConnected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5457 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 484)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5457 80:01:84:8A:B3:68]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming connection, peer ID: 80:01:84:8A:B3:68, name: HTC-HTC Desire 820_PT5457, Bluetooth address: 80:01:84:8A:B3:68
I/io.jxcore.node.IncomingSocketThread( 2955): Constructed
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming socket thread using port 0 and is now connected
,I/io.jxcore.node.IncomingSocketThread( 2955): Entering thread
,I/jxcore-log( 2955): 2015-12-01T11:09:08.854Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2955): 
,I/io.jxcore.node.IncomingSocketThread( 2955): Local host address: localhost/127.0.0.1, port: 59747
I/io.jxcore.node.IncomingSocketThread( 2955): Local streams created successfully, starting stream copying threads...
,I/io.jxcore.node.SocketThreadBase( 2955): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 2955): Exiting thread
,W/bt-btif ( 3016): invalid rfc slot id: 82
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: bt socket closed, read return: -1
E/io.jxcore.node.SocketThreadBase( 2955): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
,I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 478
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 2955): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: Socket closed
,I/jxcore-log( 2955): 2015-12-01T11:09:11.040Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2955): 
,W/bt-rfcomm( 3016): rfc_find_lcid_mcb LCID reused LCID:0x4f current:0x0
W/bt-rfcomm( 3016): RFCOMM_DisconnectInd LCID:0x4f
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:255
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection initialized (thread ID: 488)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 488)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesRead: Read 83 bytes successfully (thread ID: 488)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Got valid identity from [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3175 08:EC:A9:50:75:41]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 488)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): removeThreadFromList: Removing thread with ID 488
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Handshake thread disposed (thread ID: 488)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onIncomingConnectionConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3175 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 488)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3175 08:EC:A9:50:75:41]
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming connection, peer ID: 08:EC:A9:50:75:41, name: samsung-SM-A300FU_PT3175, Bluetooth address: 08:EC:A9:50:75:41
I/io.jxcore.node.IncomingSocketThread( 2955): Constructed
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming socket thread using port 0 and is now connected
,I/io.jxcore.node.IncomingSocketThread( 2955): Entering thread
,I/io.jxcore.node.IncomingSocketThread( 2955): Local host address: localhost/127.0.0.1, port: 59747
I/io.jxcore.node.IncomingSocketThread( 2955): Local streams created successfully, starting stream copying threads...
,I/io.jxcore.node.SocketThreadBase( 2955): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T11:09:11.900Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2955): 
,I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: F8:95:C7:87:3C:51
I/io.jxcore.node.OutgoingSocketThread( 2955): close
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 2955): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T11:09:12.749Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:09:12.749Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:09:12.750Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:09:12.753Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
,I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to G4-1 in address F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: G4-1 F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to G4-1 in address F8:95:C7:87:3C:51
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
,W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3016): bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Outgoing connection initialized (thread ID: 493)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 493)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 493)
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesRead: Read 76 bytes successfully (thread ID: 493)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Handshake succeeded with [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 493)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing connection, peer ID: F8:95:C7:87:3C:51, name: LGE-LG-H815_PT920, Bluetooth address: F8:95:C7:87:3C:51
I/io.jxcore.node.OutgoingSocketThread( 2955): Constructed
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 2955): Server socket local port: 46568
I/io.jxcore.node.ConnectionHelper( 2955): Outgoing connection is using port 46568
I/io.jxcore.node.OutgoingSocketThread( 2955): Now accepting connections...
,I/jxcore-log( 2955): 2015-12-01T11:09:14.659Z SendDataConnector.js: CLIENT connected to 46568, error: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:09:14.659Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:09:14.677Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: F8:95:C7:87:3C:51
I/io.jxcore.node.OutgoingSocketThread( 2955): close
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 2955): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 2955): Exiting thread
,W/bt-btif ( 3016): bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
,I/jxcore-log( 2955): 2015-12-01T11:09:14.700Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 2955): 
I/jxcore-log( 2955): ---- round done--------
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): ---- gotta redo : F8:95:C7:87:3C:51, try count now: 1
I/jxcore-log( 2955): 
I/jxcore-log( 2955): do fake peer & start
I/jxcore-log( 2955): 
I/jxcore-log( 2955): Connect to fake peer: E0:DB:10:1F:C9:5E
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:09:14.704Z SendDataConnector.js: Start called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:09:14.704Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:09:14.705Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to Note3-1 in address E0:DB:10:1F:C9:5E
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: Note3-1 E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to Note3-1 in address E0:DB:10:1F:C9:5E
I/chromium( 2955): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F8:95:C7:87:3C:51 done with result: Listening for incoming connections", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3016): info:x10
,D/        ( 3016): remote version info [e0:db:10:1f:c9:5e]: 0, 0, 0
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: Note3-1
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:1
W/bt-btif ( 3016): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3016): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Outgoing connection initialized (thread ID: 496)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 496)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 496)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesRead: Read 82 bytes successfully (thread ID: 496)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Handshake succeeded with [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT5487 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT5487 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 496)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT5487 E0:DB:10:1F:C9:5E]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing connection, peer ID: E0:DB:10:1F:C9:5E, name: samsung-SM-N9005_PT5487, Bluetooth address: E0:DB:10:1F:C9:5E
,I/io.jxcore.node.OutgoingSocketThread( 2955): Constructed
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 2955): Server socket local port: 50309
I/io.jxcore.node.ConnectionHelper( 2955): Outgoing connection is using port 50309
I/io.jxcore.node.OutgoingSocketThread( 2955): Now accepting connections...
,I/jxcore-log( 2955): 2015-12-01T11:09:17.455Z SendDataConnector.js: CLIENT connected to 50309, error: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:09:17.455Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:09:17.456Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,E/bt-btm  ( 3016): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3016): onReceive
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: G4-1
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: bt socket closed, read return: -1
E/io.jxcore.node.SocketThreadBase( 2955): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/bt-btif ( 3016): invalid rfc slot id: 83
,I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 485
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 2955): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: Socket closed
,I/jxcore-log( 2955): 2015-12-01T11:09:19.551Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2955): 
,W/bt-rfcomm( 3016): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
W/bt-rfcomm( 3016): RFCOMM_DisconnectInd LCID:0x44
,W/bt-btif ( 3016): dm_pm_timer expires
W/bt-btif ( 3016): dm_pm_timer expires 0
,W/bt-btif ( 3016): proc dm_pm_timer expires
,I/jxcore-log( 2955): 2015-12-01T11:09:22.457Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:09:22.458Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2955): 
,W/bt-btif ( 3016): invalid rfc slot id: 85
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: bt socket closed, read return: -1
,E/io.jxcore.node.SocketThreadBase( 2955): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 489
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 2955): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: Socket closed
,I/jxcore-log( 2955): 2015-12-01T11:09:22.554Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2955): 
,W/bt-rfcomm( 3016): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
W/bt-rfcomm( 3016): RFCOMM_DisconnectInd LCID:0x46
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:255
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Incoming connection initialized (thread ID: 498)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 498)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesRead: Read 83 bytes successfully (thread ID: 498)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Got valid identity from [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3175 08:EC:A9:50:75:41]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 498)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): removeThreadFromList: Removing thread with ID 498
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Handshake thread disposed (thread ID: 498)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onIncomingConnectionConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3175 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 498)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3175 08:EC:A9:50:75:41]
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming connection, peer ID: 08:EC:A9:50:75:41, name: samsung-SM-A300FU_PT3175, Bluetooth address: 08:EC:A9:50:75:41
,I/io.jxcore.node.IncomingSocketThread( 2955): Constructed
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Incoming socket thread using port 0 and is now connected
,I/io.jxcore.node.IncomingSocketThread( 2955): Entering thread
,I/jxcore-log( 2955): 2015-12-01T11:09:23.157Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2955): 
,I/io.jxcore.node.IncomingSocketThread( 2955): Local host address: localhost/127.0.0.1, port: 59747
I/io.jxcore.node.IncomingSocketThread( 2955): Local streams created successfully, starting stream copying threads...
I/io.jxcore.node.SocketThreadBase( 2955): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 2955): Exiting thread
,W/bt-btif ( 3016): invalid rfc slot id: 86
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: bt socket closed, read return: -1
E/io.jxcore.node.SocketThreadBase( 2955): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 499
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 2955): close: Stopping sending thread...
,I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2955): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 2955): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 2955): onDisconnected: onDisconnected: Socket closed
,I/jxcore-log( 2955): 2015-12-01T11:09:23.519Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2955): 
,W/bt-rfcomm( 3016): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
,W/bt-rfcomm( 3016): RFCOMM_DisconnectInd LCID:0x4b
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4052974 rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3016): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3016): onReceive
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: HTC Desire 820
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4052974 rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: E0:DB:10:1F:C9:5E
I/io.jxcore.node.OutgoingSocketThread( 2955): close
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 2955): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T11:09:27.474Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:09:27.475Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:09:27.476Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:09:27.476Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to Note3-1 in address E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: Note3-1 E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to Note3-1 in address E0:DB:10:1F:C9:5E
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
,W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3016): bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Outgoing connection initialized (thread ID: 503)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 503)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 503)
,E/bt-btm  ( 3016): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3016): onReceive
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:00:00:00:5A:AD, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: A3-1
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=1
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesRead: Read 82 bytes successfully (thread ID: 503)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Handshake succeeded with [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT5487 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT5487 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 503)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT5487 E0:DB:10:1F:C9:5E]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing connection, peer ID: E0:DB:10:1F:C9:5E, name: samsung-SM-N9005_PT5487, Bluetooth address: E0:DB:10:1F:C9:5E
I/io.jxcore.node.OutgoingSocketThread( 2955): Constructed
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 2955): Server socket local port: 44725
I/io.jxcore.node.ConnectionHelper( 2955): Outgoing connection is using port 44725
I/io.jxcore.node.OutgoingSocketThread( 2955): Now accepting connections...
,I/jxcore-log( 2955): 2015-12-01T11:09:28.572Z SendDataConnector.js: CLIENT connected to 44725, error: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:09:28.573Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:09:28.573Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,W/bt-btif ( 3016): dm_pm_timer expires
W/bt-btif ( 3016): dm_pm_timer expires 0
W/bt-btif ( 3016): proc dm_pm_timer expires
,I/jxcore-log( 2955): 2015-12-01T11:09:33.574Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:09:33.575Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2955): 
,I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: E0:DB:10:1F:C9:5E
I/io.jxcore.node.OutgoingSocketThread( 2955): close
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 2955): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T11:09:38.579Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:09:38.579Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:09:38.579Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:09:38.579Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to Note3-1 in address E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: Note3-1 E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to Note3-1 in address E0:DB:10:1F:C9:5E
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=0
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3016): bta_jv_rfc_port_to_cb(port_handle:0x18):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Outgoing connection initialized (thread ID: 506)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 506)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 506)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesRead: Read 82 bytes successfully (thread ID: 506)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Handshake succeeded with [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT5487 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT5487 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 506)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT5487 E0:DB:10:1F:C9:5E]
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing connection, peer ID: E0:DB:10:1F:C9:5E, name: samsung-SM-N9005_PT5487, Bluetooth address: E0:DB:10:1F:C9:5E
I/io.jxcore.node.OutgoingSocketThread( 2955): Constructed
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 2955): Server socket local port: 34371
I/io.jxcore.node.ConnectionHelper( 2955): Outgoing connection is using port 34371
I/io.jxcore.node.OutgoingSocketThread( 2955): Now accepting connections...
,I/jxcore-log( 2955): 2015-12-01T11:09:39.387Z SendDataConnector.js: CLIENT connected to 34371, error: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:09:39.387Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:09:39.388Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,W/bt-btif ( 3016): dm_pm_timer expires
W/bt-btif ( 3016): dm_pm_timer expires 0
W/bt-btif ( 3016): proc dm_pm_timer expires
,I/jxcore-log( 2955): 2015-12-01T11:09:44.389Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:09:44.390Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2955): 
,I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: E0:DB:10:1F:C9:5E
I/io.jxcore.node.OutgoingSocketThread( 2955): close
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 2955): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T11:09:49.423Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:09:49.424Z SendDataConnector.js: Connect (retry count 3) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:09:49.424Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:09:49.425Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to Note3-1 in address E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: Note3-1 E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to Note3-1 in address E0:DB:10:1F:C9:5E
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3016): bta_jv_rfc_port_to_cb(port_handle:0x19):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Outgoing connection initialized (thread ID: 509)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 509)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 509)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesRead: Read 82 bytes successfully (thread ID: 509)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Handshake succeeded with [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT5487 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT5487 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 509)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT5487 E0:DB:10:1F:C9:5E]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing connection, peer ID: E0:DB:10:1F:C9:5E, name: samsung-SM-N9005_PT5487, Bluetooth address: E0:DB:10:1F:C9:5E
,I/io.jxcore.node.OutgoingSocketThread( 2955): Constructed
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 2955): Server socket local port: 50124
I/io.jxcore.node.ConnectionHelper( 2955): Outgoing connection is using port 50124
I/io.jxcore.node.OutgoingSocketThread( 2955): Now accepting connections...
,I/jxcore-log( 2955): 2015-12-01T11:09:50.576Z SendDataConnector.js: CLIENT connected to 50124, error: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:09:50.576Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:09:50.577Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,W/bt-btif ( 3016): dm_pm_timer expires
W/bt-btif ( 3016): dm_pm_timer expires 0
W/bt-btif ( 3016): proc dm_pm_timer expires
,I/jxcore-log( 2955): 2015-12-01T11:09:55.578Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:09:55.579Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2955): 
,I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: E0:DB:10:1F:C9:5E
I/io.jxcore.node.OutgoingSocketThread( 2955): close
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 2955): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T11:10:00.585Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:10:00.585Z SendDataConnector.js: Connect (retry count 4) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:10:00.585Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:10:00.585Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to Note3-1 in address E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: Note3-1 E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to Note3-1 in address E0:DB:10:1F:C9:5E
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3016): bta_jv_rfc_port_to_cb(port_handle:0x1a):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Outgoing connection initialized (thread ID: 512)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 512)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 512)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesRead: Read 82 bytes successfully (thread ID: 512)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Handshake succeeded with [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT5487 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT5487 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 512)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT5487 E0:DB:10:1F:C9:5E]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing connection, peer ID: E0:DB:10:1F:C9:5E, name: samsung-SM-N9005_PT5487, Bluetooth address: E0:DB:10:1F:C9:5E
,I/io.jxcore.node.OutgoingSocketThread( 2955): Constructed
,I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 2955): Server socket local port: 51263
I/io.jxcore.node.ConnectionHelper( 2955): Outgoing connection is using port 51263
,I/io.jxcore.node.OutgoingSocketThread( 2955): Now accepting connections...
,I/jxcore-log( 2955): 2015-12-01T11:10:01.226Z SendDataConnector.js: CLIENT connected to 51263, error: Listening for incoming connections
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:10:01.227Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:10:01.245Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: E0:DB:10:1F:C9:5E
I/io.jxcore.node.OutgoingSocketThread( 2955): close
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 2955): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T11:10:01.264Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2955): 
I/jxcore-log( 2955): ---- round done--------
I/jxcore-log( 2955): 
I/jxcore-log( 2955): ---- gotta redo : E0:DB:10:1F:C9:5E, try count now: 1
I/jxcore-log( 2955): 
I/jxcore-log( 2955): do fake peer & start
I/jxcore-log( 2955): 
I/jxcore-log( 2955): Connect to fake peer: 38:94:96:B5:06:DC
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:10:01.267Z SendDataConnector.js: Start called with peer 38:94:96:B5:06:DC
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:10:01.268Z SendDataConnector.js: doConnect called with peer 38:94:96:B5:06:DC
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:10:01.269Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
,I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 38:94:96:B5:06:DC
W/io.jxcore.node.ConnectionHelper( 2955): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to null in address 38:94:96:B5:06:DC
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: null 38:94:96:B5:06:DC
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to null in address 38:94:96:B5:06:DC
,I/chromium( 2955): [INFO:CONSOLE(63)] "logCallback Round of send data to peer E0:DB:10:1F:C9:5E done with result: Listening for incoming connections", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3016): bta_jv_rfc_port_to_cb(port_handle:0x1b):jv handle:0x0 not FOUND
,W/bt-btm  ( 3016): btm_sec_clr_temp_auth_service() - no dev CB
E/bt-btif ( 3016): DISCOVERY_COMP_EVT slot id:94, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3016): invalid rfc slot id: 94
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [38:94:96:B5:06:DC 38:94:96:B5:06:DC 38:94:96:B5:06:DC]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): shutdown
,I/jxcore-log( 2955): 2015-12-01T11:10:10.907Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 38:94:96:B5:06:DC failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:10:10.908Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 38:94:96:B5:06:DC failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:10:10.908Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:10:15.909Z SendDataConnector.js: re-try now : 38:94:96:B5:06:DC
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:10:15.910Z SendDataConnector.js: ReStart called with peer 38:94:96:B5:06:DC
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:10:20.913Z SendDataConnector.js: Mobile.Disconnect() callback with peer 38:94:96:B5:06:DC
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:10:20.914Z SendDataConnector.js: Connect (retry count 1) to peer 38:94:96:B5:06:DC with availability status: true
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:10:20.914Z SendDataConnector.js: doConnect called with peer 38:94:96:B5:06:DC
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:10:20.915Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 38:94:96:B5:06:DC
W/io.jxcore.node.ConnectionHelper( 2955): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to null in address 38:94:96:B5:06:DC
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: null 38:94:96:B5:06:DC
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to null in address 38:94:96:B5:06:DC
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
,W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btm  ( 3016): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=2
E/bt-btm  ( 3016): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3016): onReceive
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: Note3-1
,W/bt-sdp  ( 3016): SDP - Rcvd conn cnf with error: 0x4  CID 0x44
,E/bt-btif ( 3016): DISCOVERY_COMP_EVT slot id:95, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3016): invalid rfc slot id: 95
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [38:94:96:B5:06:DC 38:94:96:B5:06:DC 38:94:96:B5:06:DC]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): shutdown
I/jxcore-log( 2955): 2015-12-01T11:10:26.107Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 38:94:96:B5:06:DC failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:10:26.108Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 38:94:96:B5:06:DC failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:10:26.109Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:10:31.110Z SendDataConnector.js: re-try now : 38:94:96:B5:06:DC
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:10:31.111Z SendDataConnector.js: ReStart called with peer 38:94:96:B5:06:DC
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:10:36.114Z SendDataConnector.js: Mobile.Disconnect() callback with peer 38:94:96:B5:06:DC
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:10:36.114Z SendDataConnector.js: Connect (retry count 2) to peer 38:94:96:B5:06:DC with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:10:36.115Z SendDataConnector.js: doConnect called with peer 38:94:96:B5:06:DC
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:10:36.115Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 38:94:96:B5:06:DC
W/io.jxcore.node.ConnectionHelper( 2955): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to null in address 38:94:96:B5:06:DC
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: null 38:94:96:B5:06:DC
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to null in address 38:94:96:B5:06:DC
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3016): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 3016): DISCOVERY_COMP_EVT slot id:96, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3016): invalid rfc slot id: 96
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [38:94:96:B5:06:DC 38:94:96:B5:06:DC 38:94:96:B5:06:DC]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): shutdown
I/jxcore-log( 2955): 2015-12-01T11:10:41.287Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 38:94:96:B5:06:DC failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:10:41.287Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 38:94:96:B5:06:DC failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:10:41.288Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:10:46.289Z SendDataConnector.js: re-try now : 38:94:96:B5:06:DC
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:10:46.289Z SendDataConnector.js: ReStart called with peer 38:94:96:B5:06:DC
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:10:51.294Z SendDataConnector.js: Mobile.Disconnect() callback with peer 38:94:96:B5:06:DC
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:10:51.295Z SendDataConnector.js: Connect (retry count 3) to peer 38:94:96:B5:06:DC with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:10:51.295Z SendDataConnector.js: doConnect called with peer 38:94:96:B5:06:DC
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:10:51.296Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 38:94:96:B5:06:DC
W/io.jxcore.node.ConnectionHelper( 2955): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to null in address 38:94:96:B5:06:DC
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: null 38:94:96:B5:06:DC
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to null in address 38:94:96:B5:06:DC
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3016): info:x10
,D/        ( 3016): remote version info [38:94:96:b5:06:dc]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3016): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3016): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3016): bondStateChangeCallback: Status: 0 Address: 38:94:96:B5:06:DC newState: 1
E/bt-btif ( 3016): check_cod: remote_cod = 0x001f00
,I/BluetoothBondStateMachine( 3016): Bond State Change Intent:38:94:96:B5:06:DC OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3016): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3016): bondStateChangeCallback: Status: 0 Address: 38:94:96:B5:06:DC newState: 0
,D/BluetoothAdapterProperties( 3016): Failed to remove device: 38:94:96:B5:06:DC
,I/BluetoothBondStateMachine( 3016): Bond State Change Intent:38:94:96:B5:06:DC OldState: 11 NewState: 10
,W/bt-btif ( 3016): new conn_srvc id:26, app_id:1
W/bt-btif ( 3016): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3016): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Outgoing connection initialized (thread ID: 518)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesWritten: 77 bytes successfully written (thread ID: 518)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Entering thread (ID: 518)
,W/BackupManagerService(  760): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): onBytesRead: Read 82 bytes successfully (thread ID: 518)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Handshake succeeded with [38:94:96:B5:06:DC samsung-SM-G800H_PT5358 38:94:96:B5:06:DC]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnected: [38:94:96:B5:06:DC samsung-SM-G800H_PT5358 38:94:96:B5:06:DC]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnected: [38:94:96:B5:06:DC samsung-SM-G800H_PT5358 38:94:96:B5:06:DC]
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing connection, peer ID: 38:94:96:B5:06:DC, name: samsung-SM-G800H_PT5358, Bluetooth address: 38:94:96:B5:06:DC
I/io.jxcore.node.ConnectionHelper( 2955): addNewPeerToListAndNotify: Adding peer with ID 38:94:96:B5:06:DC
I/io.jxcore.node.OutgoingSocketThread( 2955): Constructed
I/io.jxcore.node.ConnectionHelper( 2955): onConnected: Outgoing socket thread created successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2955): Exiting thread (ID: 518)
,I/io.jxcore.node.OutgoingSocketThread( 2955): Server socket local port: 33672
I/io.jxcore.node.ConnectionHelper( 2955): Outgoing connection is using port 33672
I/io.jxcore.node.OutgoingSocketThread( 2955): Now accepting connections...
,W/BackupManagerService(  760): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,W/BackupManagerService(  760): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/BluetoothBondStateMachine( 3016): StableState(): Entering Off State
,I/jxcore-log( 2955): 2015-12-01T11:10:56.120Z SendDataConnector.js: CLIENT connected to 33672, error: Listening for incoming connections
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:10:56.123Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:10:56.124Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2955): 
,W/bt-btif ( 3016): dm_pm_timer expires
W/bt-btif ( 3016): dm_pm_timer expires 0
,W/bt-btif ( 3016): proc dm_pm_timer expires
,I/jxcore-log( 2955): 2015-12-01T11:11:01.127Z SendDataConnector.js: re-try now : 38:94:96:B5:06:DC
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:11:01.128Z SendDataConnector.js: ReStart called with peer 38:94:96:B5:06:DC
I/jxcore-log( 2955): 
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/io.jxcore.node.ConnectionHelper( 2955): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 38:94:96:B5:06:DC
I/io.jxcore.node.OutgoingSocketThread( 2955): close
I/io.jxcore.node.SocketThreadBase( 2955): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 2955): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 2955): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 2955): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 2955): Exiting thread
,I/jxcore-log( 2955): 2015-12-01T11:11:06.148Z SendDataConnector.js: Mobile.Disconnect() callback with peer 38:94:96:B5:06:DC
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:11:06.149Z SendDataConnector.js: Connect (retry count 4) to peer 38:94:96:B5:06:DC with availability status: true
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:11:06.149Z SendDataConnector.js: doConnect called with peer 38:94:96:B5:06:DC
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:11:06.150Z SendDataConnector.js: do connect now
I/jxcore-log( 2955): 
,I/io.jxcore.node.ConnectionHelper( 2955): hasConnection: No connection with peer with ID 38:94:96:B5:06:DC
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Trying to start connecting to Galaxy S5-2 in address 38:94:96:B5:06:DC
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnecting: Galaxy S5-2 38:94:96:B5:06:DC
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): connect: Started connecting to Galaxy S5-2 in address 38:94:96:B5:06:DC
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Trying to connect...
W/BluetoothAdapter( 2955): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3016): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3016): bta_jv_rfc_port_to_cb(port_handle:0x1c):jv handle:0x0 not FOUND
,I/jxcore-log( 2955): timeout now
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): dun
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): weAreDoneNow , resultArray.length: 0
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): done, now sending data to server
I/jxcore-log( 2955): 
I/jxcore-log( 2955): DBG, CoordinatorConnector sendData called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): -- RESULT DATA {"name:":"LGE-Nexus 5_PT5003","time":1000089,"result":"TIMEOUT","sendList":[{"connections":1,"name":"38:94:96:B5:06:DC","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:9D:93:0B","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":1,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":1,"name":"80:01:84:8A:B3:68","time":0,"result":"Fail"},{"connections":1,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":1,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":1,"name
I/jxcore-log( 2955): sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
I/jxcore-log( 2955): 
I/jxcore-log( 2955): Results list does not contain any items
I/jxcore-log( 2955): 
I/jxcore-log( 2955): sendList failed peers count : 13 [100 %]
I/jxcore-log( 2955): 
I/jxcore-log( 2955): - Peer ID : 38:94:96:B5:06:DC, Tried : 1
I/jxcore-log( 2955): 
I/jxcore-log( 2955): - Peer ID : 44:80:EB:7B:5A:05, Tried : 1
I/jxcore-log( 2955): 
I/jxcore-log( 2955): - Peer ID : 80:01:84:8A:B3:68, Tried : 1
I/jxcore-log( 2955): 
I/jxcore-log( 2955): - Peer ID : 08:EC:A9:50:76:27, Tried : 1
I/jxcore-log( 2955): 
I/jxcore-log( 2955): - Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
I/jxcore-log( 2955): 
I/jxcore-log( 2955): - Peer ID : E0:DB:10:14:E2:C0, Tried : 1
I/jxcore-log( 2955): 
I/jxcore-log( 2955): - Peer ID : 34:FC:EF:11:B1:66, Tried : 1
I/jxcore-log( 2955): 
I/jxcore-log( 2955): - Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
I/jxcore-log( 2955): 
I/jxcore-log( 2955): - Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
I/jxcore-log( 2955): 
I/jxcore-log( 2955): - Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
I/jxcore-log( 2955): 
I/jxcore-log( 2955): - Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
I/jxcore-log( 2955): 
I/jxcore-log( 2955): - Peer ID : F8:95:C7:87:3C:51, Tried : 1
I/jxcore-log( 2955): 
I/jxcore-log( 2955): - Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
I/jxcore-log( 2955): 
I/jxcore-log( 2955): sendList never tried peers count : 8 [38.095238095238095 %]
I/jxcore-log( 2955): 
I/jxcore-log( 2955): - Peer ID : B0:C5:59:3F:75:69
I/jxcore-log( 2955): 
I/jxcore-log( 2955): - Peer ID : 08:EC:A9:50:75:41
I/jxcore-log( 2955): 
I/jxcore-log( 2955): - Peer ID : 7C:F9:0E:37:96:AB
I/jxcore-log( 2955): 
I/jxcore-log( 2955): - Peer ID : F8:95:C7:87:85:54
I/jxcore-log( 2955): 
I/jxcore-log( 2955): - Peer ID : 34:FC:EF:9D:93:0B
I/jxcore-log( 2955): 
I/jxcore-log( 2955): - Peer ID : F4:F1:E1:5C:3B:E2
I/jxcore-log( 2955): 
I/jxcore-log( 2955): - Peer ID : 7C:F9:0E:51:18:22
I/jxcore-log( 2955): 
I/jxcore-log( 2955): - Peer ID : 58:3F:54:73:64:C0
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:11:11.904Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:11:11.905Z SendDataConnector.js: Mobile.Disconnect() callback with peer 38:94:96:B5:06:DC
I/jxcore-log( 2955): 
,I/chromium( 2955): [INFO:CONSOLE(63)] "logCallback *** TIMEOUT ***", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 2955): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
,E/bt-btm  ( 3016): tBTM_SEC_DEV:0xa4052b3c rs_disc_pending=0
E/bt-btif ( 3016): DISCOVERY_COMP_EVT slot id:98, failed to find channle,                                       status:1, scn:0
E/bt-btm  ( 3016): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3016): bta_dm_check_av:0
,W/bt-btif ( 3016): invalid rfc slot id: 98
,W/bt-btif ( 3016): btif_dm_cback : unhandled event (14)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [38:94:96:B5:06:DC samsung-SM-G800H_PT5358 38:94:96:B5:06:DC]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2955): shutdown
I/jxcore-log( 2955): 2015-12-01T11:11:30.025Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 38:94:96:B5:06:DC failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:11:30.025Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 38:94:96:B5:06:DC failed
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:11:30.026Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2955): 
I/jxcore-log( 2955): 2015-12-01T11:11:30.029Z SendDataConnector.js: Mobile.Disconnect() callback with peer 38:94:96:B5:06:DC
I/jxcore-log( 2955): 
,D/BluetoothMapService( 3016): onReceive
,I/BTConnectionReceiver( 1374): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=38:94:96:B5:06:DC, alias=null, name=Galaxy S5-2, majorDeviceClass=7936, deviceClass=7936]
,I/BluetoothClassifier( 1374): Bluetooth Device Name: Galaxy S5-2
,W/bt-smp  ( 3016): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3016): Plain text(LSB ~ MSB) = 48 ca 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3016): Encrypted text(LSB ~ MSB) = 31 16 8a ed dd 79 91 58 1f d7 91 7b a8 8c 3c 08 
,W/bt-btm  ( 3016): Stopping oneshot timer
,I/jxcore-log( 2955): DBG, CoordinatorConnector command called
I/jxcore-log( 2955): 
I/jxcore-log( 2955): command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): stop tests now !
I/jxcore-log( 2955): 
I/jxcore-log( 2955): stop current!
I/jxcore-log( 2955): 
I/jxcore-log( 2955): testSendData stopped
I/jxcore-log( 2955): 
I/io.jxcore.node.ConnectionHelper( 2955): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Shutting down...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:91)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onIncomingConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2955): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2955): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): setState: NOT_INITIALIZED
I/jxcore-log( 2955): StopBroadcasting went ok
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): 2015-12-01T11:15:32.472Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 2955): 
I/chromium( 2955): [INFO:CONSOLE(63)] "logCallback stop", source: file:///android_asset/www/js/thali_main.js (63)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2955): onConnectionFailed: Socket is null
I/io.jxcore.node.ConnectionHelper( 2955): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 2955): onConnectionManagerStateChanged: NOT_INITIALIZED
,I/jxcore-log( 2955): DBG, CoordinatorConnector command called
I/jxcore-log( 2955): 
I/jxcore-log( 2955): command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[],\"sendError\":{\"failedPeer\":[{\"connections\":1,\"name\":\"38:94:96:B5:06:DC\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"44:80:EB:7B:5A:05\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"80:01:84:8A:B3:68\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"08:EC:A9:50:76:27\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"00:F4:6F:30:E0:6C\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"E0:DB:10:14:E2:C0\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"34:FC:EF:11:B1:66\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"58:2A:F7:ED:96:BE\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"F8:CF:C5:D9:E5:61\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"7C:F9:0E:34:8A:A0\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"B4:CE:F6:AB:A4:6A\",\"time\":0,\"result\":\"
I/jxcore-log( 2955): ****TEST TOOK:  ms ****
I/jxcore-log( 2955): 
I/jxcore-log( 2955): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2955): 
I/jxcore-log( 2955): stop tests now !
I/jxcore-log( 2955): 
I/jxcore-log( 2955): end, event received
I/jxcore-log( 2955): 
I/jxcore-log( 2955): CoordinatorConnector close called
I/jxcore-log( 2955): 
,I/jxcore-log( 2955): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 2955): 
I/jxcore-log( 2955): The Coordinator has disconnected!
I/jxcore-log( 2955): 
I/jxcore-log( 2955): The Coordinator has closed!
I/jxcore-log( 2955): 
I/jxcore-log( 2955): stop tests now !
I/jxcore-log( 2955): 
I/jxcore-log( 2955): turning Radios off
I/jxcore-log( 2955): 
I/jxcore-log( 2955): Toggling radios to false
I/jxcore-log( 2955): 
D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  760): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1e5bdcc4 mBinding = false
,D/BluetoothManagerService(  760): Message: 2
,D/BluetoothManagerService(  760): Sending off request.
,D/BluetoothAdapterState( 3016): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
,D/BluetoothAdapterProperties( 3016): Setting state to 13
I/BluetoothAdapterState( 3016): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterProperties( 3016): onBluetoothDisable()
I/BluetoothAdapterState( 3016): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 3016): Scan Mode:20
,D/BluetoothAdapterState( 3016): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,V/BluetoothMapMasInstance( 3016): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3016): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3016): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 3016): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 3016): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 3016): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3016): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3016): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,E/BtOppRfcommListener( 3016): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/btif_config_util( 3016): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3016): bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
,W/bt-l2cap( 3016): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3016): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothManagerService(  760): Message: 60
D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
,D/BluetoothManagerService(  760): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 3016): onReceive
D/BluetoothMapService( 3016): STATE_TURNING_OFF
V/BluetoothMapService( 3016): Handler(): got msg=4
D/BluetoothMapService( 3016): MAP Service closeService in
D/BluetoothMapMasInstance( 3016): MAP Service shutdown
V/BluetoothMapService( 3016): MAP Service closeService out
,I/BtOppRfcommListener( 3016): stopping Accept Thread
,I/BtOppRfcommListener( 3016): BluetoothSocket listen thread finished
,D/WifiService(  760): setWifiEnabled: false pid=2955, uid=10270
E/WifiService(  760): Invoking mWifiStateMachine.setWifiEnabled
,W/ContextImpl( 4250): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/jxcore-log( 2955): Radios toggled
I/jxcore-log( 2955): 
I/chromium( 2955): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
,E/WifiStateMachine(  760): WifiStateMachine: Leaving Connected state,
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  760): do suspend true
,D/BluetoothManagerService(  760): Message: 30
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,V/NativeCrypto( 1361): Read error: ssl=0x9df1be00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1361): SSL shutdown failed: ssl=0x9df1be00: I/O error during system call, Broken pipe
,E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/bt_userial( 3016): RX termination
W/bt_userial( 3016): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 3016): Leaving userial_read_thread()
,W/bt-btif ( 3016): ag scb idx 1 not allocated
E/bt-btif ( 3016): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3016): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3016): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3016): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3016): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3016): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3016): L2CAP - PSM: 0x0017 not found for deregistration
,D/bt_userial( 3016): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 3016): hw_epilog_process
,I/bt_userial_vendor( 3016): device fd = 53 close
,D/ConnectivityService(  760): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Checking http://clients3.google.com/generate_204 on <unknown ssid>
I/GKI_LINUX( 3016): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 3016): GKI_exit_task 0 done
I/GKI_LINUX( 3016): GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 3016): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothManagerService(  760): Message: 30
,D/HeadsetService( 3016): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3016): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b00abf
,D/HeadsetStateMachine( 3016): Exit Disconnected: -1
,D/BluetoothHeadset( 1192): Proxy object disconnected
,D/BluetoothHeadset( 1192): Proxy object disconnected
,E/WifiStateMachine(  760): scanCount==0 - aborting
,D/BluetoothAdapterState( 3016): Stopping profile services that were post enabled
D/BluetoothHeadset(  760): Proxy object disconnected
,D/BluetoothHeadset( 1221): Proxy object disconnected
,D/WifiNetworkAgent(  760): NetworkAgent: NetworkAgent channel lost
D/WifiScanningService(  760): SCAN_AVAILABLE : 1
D/RttService(  760): SCAN_AVAILABLE : 1
,D/A2dpService( 3016): Received stop request...Stopping profile...
D/WifiScanningService(  760): StartedState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  760): DefaultState
,D/A2dpStateMachine( 3016): Exit Disconnected: -1
D/RttService(  760): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/BluetoothAdapterService( 3016): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b00abf
,D/BluetoothA2dp(  760): Proxy object disconnected
,D/HidService( 3016): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3016): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b00abf
,D/HealthService( 3016): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3016): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b00abf
,D/HeadsetStateMachine( 3016): Unbinding service...
,W/BluetoothHeadsetServiceJni( 3016): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 3016): Cleaning up Bluetooth Handsfree callback object
,D/PanService( 3016): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3016): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b00abf
,D/BtGatt.DebugUtils( 3016): handleDebugAction() action=null
,D/BtGatt.GattService( 3016): Received stop request...Stopping profile...
D/BtGatt.GattService( 3016): stop()
D/BtGatt.AdvertiseManager( 3016): advertise clients cleared
E/native  (  760): do suspend true
,D/BluetoothAdapterService( 3016): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b00abf
,D/BluetoothMapService( 3016): Received stop request...Stopping profile...
D/BluetoothMapService( 3016): stop()
,D/BluetoothMapEmailAppObserver( 3016): deinitObservers()
D/BluetoothMapEmailAppObserver( 3016): removeReceiver()
,D/BluetoothAdapterService( 3016): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b00abf
,I/GKI_LINUX( 3016): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3016): GKI_exit_task 2 done
I/GKI_LINUX( 3016): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 3016): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3016): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3016): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3016): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3016): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3016): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3016): Cleaning up Bluetooth PAN callback object
V/BluetoothMapService( 3016): Handler(): got msg=4
D/BluetoothMapService( 3016): MAP Service closeService in
V/BluetoothMapService( 3016): MAP Service closeService out
D/BluetoothAdapterState( 3016): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3016): Setting state to 10
I/BluetoothAdapterState( 3016): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService(  760): Message: 60
D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  760): Broadcasting onBluetoothStateChange(false) to 7 receivers.
D/BluetoothA2dp(  760): onBluetoothStateChange: up=false
D/BluetoothHeadset(  760): onBluetoothStateChange: up=false
I/BluetoothAdapterState( 3016): Entering OffState
D/BluetoothMapService( 3016): cleanup()
D/BluetoothMapService( 3016): MAP Service closeService in
V/BluetoothMapService( 3016): MAP Service closeService out
,D/BluetoothInputDevice( 4250): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1192): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1192): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1221): onBluetoothStateChange: up=false
,E/BluetoothPan( 4250): 
E/BluetoothPan( 4250): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothPan$2@1cf4f58c
E/BluetoothPan( 4250): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1024)
E/BluetoothPan( 4250): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1802)
E/BluetoothPan( 4250): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
E/BluetoothPan( 4250): 	at android.bluetooth.BluetoothPan$1.onBluetoothStateChange(BluetoothPan.java:199)
E/BluetoothPan( 4250): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothPan( 4250): 	at android.os.Binder.execTransact(Binder.java:446)
,D/BluetoothManagerService(  760): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  760): Broadcasting onBluetoothServiceDown() to 11 receivers.
,D/BluetoothManagerService(  760): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1e5bdcc4 mBinding = false
,D/BluetoothManagerService(  760): Sending unbind request.
D/BluetoothManagerService(  760): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter(  899): 857579824: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter(  899): 857579824: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  899): 857579824: getState() :  mService = null. Returning STATE_OFF
,D/LocalBluetoothProfileManager( 4250): Adding local MAP profile
,I/GKI_LINUX( 3016): gki_task task_id=1 [BTIF] terminating
D/BluetoothMap( 4250): Create BluetoothMap proxy object
,D/BluetoothManagerService(  760): Message: 30
,I/GKI_LINUX( 3016): GKI_exit_task 1 done
I/GKI_LINUX( 3016): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3016): cleanupNative: return from cleanup
,D/CommandListener(  179): Clearing all IP addresses on wlan0
D/ConnectivityService(  760): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/Nat464Xlat(  760): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityManager.CallbackHandler( 1562): CM callback handler got msg 524292
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Disconnected - quitting
D/CSLegacyTypeTracker(  760): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/art     ( 3016): System.exit called, status: 0
I/AndroidRuntime( 3016): VM exiting with result code 0, cleanup skipped.
,D/BluetoothAdapter( 1316): 265783238: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1316): 265783238: getState() :  mService = null. Returning STATE_OFF
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524292
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  760): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1221): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  760): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/AndroidRuntime( 4679): 
D/AndroidRuntime( 4679): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4679): CheckJNI is OFF
,D/BluetoothManagerService(  760): Message: 30
,D/LocalBluetoothProfileManager( 4250): LocalBluetoothProfileManager construction complete
,D/AndroidRuntime( 4679): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  760): Process com.android.bluetooth (pid 3016) has died
,I/wpa_supplicant( 3022): p2p0: CTRL-EVENT-TERMINATING 
,I/ActivityManager(  760): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
D/DockEventReceiver( 4250): finishStartingService: stopping service
I/ActivityManager(  760): Killing 2955:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/wpa_supplicant( 3022): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,W/PackageSettings(  760): Skipping PackageSetting{1a212b06 com.example.hello/10277} due to missing metadata
,I/WindowState(  760): WIN DEATH: Window{5c50bc u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  760): Client connection lost with reason: 4
,I/wpa_supplicant( 3022): wlan0: CTRL-EVENT-TERMINATING 
,I/ActivityManager(  760):   Force finishing activity ActivityRecord{19730e1 u0 com.test.thalitest/.MainActivity t214}
,W/ActivityManager(  760): Spurious death for ProcessRecord{1e5c9a63 2955:com.test.thalitest/u0a270}, curProc for 2955: null
I/ActivityManager(  760): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/ActivityManager(  760):   Force finishing activity ActivityRecord{19730e1 u0 com.test.thalitest/.MainActivity t214 f}
W/ActivityManager(  760): Duplicate finish request for ActivityRecord{19730e1 u0 com.test.thalitest/.MainActivity t214 f}
,D/Tethering(  760): InitialState.processMessage what=4
I/InputReader(  760): Reconfiguring input devices.  changes=0x00000010
,D/Tethering(  760): sendTetherStateChangedBroadcast 0, 0, 0
,W/GeofencerStateMachine( 1316): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1081): resetDictionaries() : en_US
,W/Settings( 4037): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/art     ( 1290): Explicit concurrent mark sweep GC freed 9389(599KB) AllocSpace objects, 3(288KB) LOS objects, 37% free, 26MB/42MB, paused 821us total 39.422ms
,W/Settings( 1316): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Keyboard.Facilitator.DecoderInitializer( 1081): run()
I/Adreno-EGL(  948): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  948): Initialized EGL, version 1.4
I/art     (  760): Explicit concurrent mark sweep GC freed 41403(2MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 27MB/41MB, paused 1.344ms total 94.168ms
I/art     (  760): WaitForGcToComplete blocked for 94.517ms for cause Explicit
,D/OpenGLRenderer(  948): Enabling debug mode 0
I/art     ( 1374): Explicit concurrent mark sweep GC freed 90993(4MB) AllocSpace objects, 21(371KB) LOS objects, 24% free, 19MB/25MB, paused 344us total 104.126ms
,I/Decoder ( 1081): createOrResetDecoder
,I/ConfigService( 1361): onCreate
,W/InputMethodManagerService(  760): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@39f8fabb (uid=10034 pid=948)
,D/BackupManagerService(  760): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  760): Receieved: android.intent.action.PACKAGE_REMOVED
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1081): run()
,D/TaskPersister(  760): removeObsoleteFile: deleting file=214_task.xml
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1081): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1081): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1081): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1081): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1081): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1081): run() : Loaded File = UserHistory.en_US.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1081): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1081): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1081): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1081): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1081): run()
I/StatsUtilsManager( 1081): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1081): shouldRecordStats() = Too Soon
,I/Launcher( 1290): Deferring update until onResume
,I/art     (  760): Explicit concurrent mark sweep GC freed 10122(548KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.991ms total 176.258ms
,I/art     (  760): WaitForGcToComplete blocked for 198.938ms for cause Explicit
,W/ResourcesManager( 1290): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1290): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1290): Deferring update until onResume
,I/art     (  760): Explicit concurrent mark sweep GC freed 1838(110KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 2.096ms total 58.910ms
,D/WifiService(  760): New client listening to asynchronous messages
,I/ActivityManager(  760): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=4745 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/AndroidRuntime( 4679): Shutting down VM
,W/ResourcesManager( 4745): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/AdapterServiceConfig( 4745): Adding HeadsetService
,D/AdapterServiceConfig( 4745): Adding A2dpService
D/AdapterServiceConfig( 4745): Adding HidService
,D/AdapterServiceConfig( 4745): Adding HealthService
D/AdapterServiceConfig( 4745): Adding PanService
D/AdapterServiceConfig( 4745): Adding GattService
D/AdapterServiceConfig( 4745): Adding BluetoothMapService
,I/ActivityManager(  760): Killing 3335:com.google.android.apps.magazines/u0a61 (adj 15): empty #17
,E/libprocessgroup(  760): failed to kill 1 processes for processgroup 3335
,D/AuthorizationBluetoothService( 1361): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/ContextImpl( 4250): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver( 4250): finishStartingService: stopping service
,D/BluetoothAdapter( 4250): 15096205: getState() :  mService = null. Returning STATE_OFF
,D/AuthorizationBluetoothService( 1361): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothAdapter( 4250): 15096205: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager(  760): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=4772 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a

```
