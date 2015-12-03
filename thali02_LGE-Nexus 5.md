#### Test 52383621712b264_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
W/AnalyticsTrackerProxyImpl( 2864): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
,--------- beginning of system
W/ResourcesManager( 2864): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2864): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 2864): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
D/Finsky  ( 2368): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
I/ActivityManager(  761): Killing 2101:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
W/System  ( 2864): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2864): Installed default security provider GmsCore_OpenSSL
D/AndroidRuntime( 2910): 
D/AndroidRuntime( 2910): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2910): CheckJNI is OFF
W/libprocessgroup(  761): failed to open /acct/uid_1000/pid_2101/cgroup.procs: No such file or directory
V/GLSActivity( 1412): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 2910): Calling main entry com.android.commands.am.Am
I/ActivityManager(  761): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  761): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2931 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2910): Shutting down VM
I/Icing   ( 1557): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
V/ActivityManager(  761): Display changed displayId=0
D/Icing   ( 1557): Loaded CLD2 Version V2.0 - 20141016
I/WebViewFactory( 2931): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2931): Time to load native libraries: 2 ms (timestamps 5659-5661)
I/LibraryLoader( 2931): Expected native library version number "",actual native library version number ""
I/Icing   ( 1557): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
V/WebViewChromiumFactoryProvider( 2931): Binding Chromium to main looper Looper (main, tid 1) {1efba657}
I/LibraryLoader( 2931): Expected native library version number "",actual native library version number ""
I/chromium( 2931): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 2931): Initializing chromium process, singleProcess=true
W/art     ( 2931): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2931): ApplicationContext is null in ApplicationStatus
W/chromium( 2931): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 2931): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 2931): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2931): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 2931): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d9a7c11:true
D/BluetoothAdapter( 2931): 227071918: getState() :  mService = null. Returning STATE_OFF
W/art     ( 2931): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 2931): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 2931): CordovaWebView is running on device made by: LGE
W/art     ( 2931): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2931): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 2931): Render dirty regions requested: true
D/Atlas   ( 2931): Validating map...
W/chromium( 2931): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 2931): Initialized EGL, version 1.4
D/OpenGLRenderer( 2931): Enabling debug mode 0
W/IInputConnectionWrapper( 2931): showStatusIcon on inactive InputConnection
W/BindingManager( 2931): Cannot call determinedVisibility() - never saw a connection for the pid: 2931
I/ActivityManager(  761): Displayed com.test.thalitest/.MainActivity: +451ms (total +53s854ms)
D/JsMessageQueue( 2931): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 2931): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 2931): jxcore cordova android initializing
I/ActivityManager(  761): Killing 2194:com.google.android.youtube/u0a80 (adj 15): empty #17
W/libprocessgroup(  761): failed to open /acct/uid_10080/pid_2194/cgroup.procs: No such file or directory
,W/jxcore-log( 2931): Initializing JXcore engine
W/jxcore-log( 2931): JXcore engine is ready
,W/jxcore-log( 2931): Starting JXcore engine
,W/.test.thalitest( 2931): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7606]" dev="sockfs" ino=7606 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 2931): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 2931): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6720]" dev="sockfs" ino=6720 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 2931): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18959]" dev="sockfs" ino=18959 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 2931): Platform android
W/jxcore-log( 2931): 
W/jxcore-log( 2931): Process ARCH arm
W/jxcore-log( 2931): 
,I/jxcore-log( 2931): JXcore Cordova bridge is ready!
I/jxcore-log( 2931): 
W/jxcore-log( 2931): JXcore engine is started
,I/chromium( 2931): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 2931): Toggling radios to true
I/jxcore-log( 2931): 
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  761): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  761): Message: 1
D/BluetoothManagerService(  761): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  761): setWifiEnabled: true pid=2931, uid=10270
E/WifiService(  761): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiService(  761): New client listening to asynchronous messages
,D/SoftapController(  179): Softap fwReload - Ok
,I/ActivityManager(  761): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3006 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/CommandListener(  179): Setting iface cfg
D/CommandListener(  179): Trying to bring down wlan0
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,I/jxcore-log( 2931): Radios toggled
I/jxcore-log( 2931): 
,W/ResourcesManager( 3006): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/AdapterServiceConfig( 3006): Adding HeadsetService
D/AdapterServiceConfig( 3006): Adding A2dpService
D/AdapterServiceConfig( 3006): Adding HidService
D/AdapterServiceConfig( 3006): Adding HealthService
D/AdapterServiceConfig( 3006): Adding PanService
D/AdapterServiceConfig( 3006): Adding GattService
D/AdapterServiceConfig( 3006): Adding BluetoothMapService
,I/wpa_supplicant( 3030): Successfully initialized wpa_supplicant
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b2983ac:true
D/BluetoothAdapterState( 3006): make
I/bluedroid( 3006): init
I/BluetoothAdapterState( 3006): Entering OffState
,I/bte_conf( 3006): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3006): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3006): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3006): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3006): get_profile_interface socket
I/bluedroid( 3006): get_profile_interface map_client
,D/BluetoothManagerService(  761): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  761): Message: 40
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 3006): config_hci_snoop_log
D/BluetoothManagerService(  761): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  761): Broadcasting onBluetoothServiceUp() to 9 receivers.
,I/GKI_LINUX( 3006): gki_task_entry task_id=1 [BTIF] starting
D/BluetoothAdapterProperties( 3006): Address is:34:FC:EF:11:AE:67
,D/BluetoothAdapterProperties( 3006): Name is: Nexus 5
,D/BluetoothManagerService(  761): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  761): Stored Bluetooth name: Nexus 5
D/BluetoothAdapterState( 3006): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3006): Setting state to 11
I/BluetoothAdapterState( 3006): Bluetooth adapter state changed: 10-> 11
,D/BluetoothBondStateMachine( 3006): make
D/BluetoothManagerService(  761): Message: 60
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  761): Bluetooth State Change Intent: 10 -> 11
I/BluetoothBondStateMachine( 3006): StableState(): Entering Off State
,I/wpa_supplicant( 3030): rfkill: Cannot open RFKILL control device
,I/ActivityManager(  761): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=3038 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
D/WifiMonitor(  761): startMonitoring(wlan0) with mConnected = false
,D/BluetoothHeadset( 1194): Proxy object connected
D/BluetoothHeadset( 1194): Proxy object connected
,D/BluetoothHeadset(  761): Proxy object connected
D/HeadsetService( 3006): Received start request. Starting profile...
,D/BluetoothHeadset( 1227): Proxy object connected
I/BluetoothHeadsetServiceJni( 3006): classInitNative: succeeds
,D/HeadsetStateMachine( 3006): make
,I/BluetoothAdapterState( 3006): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetStateMachine( 3006): max_hf_connections = 1
I/bluedroid( 3006): get_profile_interface handsfree
D/HeadsetStateMachine( 3006): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 3006): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1e8544
,D/BluetoothA2dp(  761): Proxy object connected
,D/A2dpService( 3006): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3006): classInitNative: succeeds
I/bluedroid( 3006): get_profile_interface avrcp
,E/RemoteController( 3006): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3006): classInitNative: succeeds
D/A2dpStateMachine( 3006): make
,I/bluedroid( 3006): get_profile_interface a2dp
,I/GKI_LINUX( 3006): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothAdapterService( 3006): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1e8544
I/BluetoothHidServiceJni( 3006): classInitNative: succeeds
,D/HidService( 3006): Received start request. Starting profile...
D/A2dpStateMachine( 3006): Enter Disconnected: -2
I/bluedroid( 3006): get_profile_interface hidhost
D/BluetoothAdapterService( 3006): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1e8544
I/BluetoothHealthServiceJni( 3006): classInitNative: succeeds
,D/HealthService( 3006): Received start request. Starting profile...
,I/bluedroid( 3006): get_profile_interface health
D/BluetoothAdapterService( 3006): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1e8544
,I/BluetoothPanServiceJni( 3006): classInitNative(L105): succeeds
,D/PanService( 3006): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3006): initializeNative(L110): pan
I/bluedroid( 3006): get_profile_interface pan
,D/BluetoothAdapterService( 3006): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1e8544
,I/BtGatt.JNI( 3006): classInitNative(L863): classInitNative: Success!
,D/BtGatt.DebugUtils( 3006): handleDebugAction() action=null
,D/BtGatt.GattService( 3006): Received start request. Starting profile...
,D/BtGatt.GattService( 3006): start()
I/bluedroid( 3006): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 3006): advertise manager created
,D/BluetoothAdapterService( 3006): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1e8544
,V/BluetoothMapService( 3006): BluetoothMapBinder()
,D/BluetoothMapService( 3006): Received start request. Starting profile...
D/BluetoothMapService( 3006): start()
,D/BluetoothMapEmailSettingsLoader( 3006): Found 0 applications
,D/BluetoothMapEmailAppObserver( 3006): createReceiver()
D/BluetoothMapEmailAppObserver( 3006): initObservers()
D/BluetoothMapEmailAppObserver( 3006): getEnabledAccountItems()
,D/BluetoothAdapterService( 3006): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1e8544
D/HeadsetStateMachine( 3006): Proxy object connected
D/HeadsetStateMachine( 3006): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3006): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3006): Disconnected process message: 11, size: 0
,V/BluetoothMapService( 3006): Handler(): got msg=1
D/BluetoothAdapterState( 3006): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3006): enable
,I/GKI_LINUX( 3006): gki_task_entry task_id=0 [BTU] starting
I/bt_hci_bdroid( 3006): init
,I/bt-btu  ( 3006): btu_task pending for preload complete event
,I/bt_vendor( 3006): init
I/bt_vnd_conf( 3006): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3006): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3006): userial_init
,I/ActivityManager(  761): Killing 2287:com.google.android.deskclock/u0a38 (adj 15): empty #17
,I/bt_userial_vendor( 3006): userial vendor open: opening /dev/ttyHS99
,I/bt_userial_vendor( 3006): device fd = 53 open
D/bt_userial( 3006): Entering userial_read_thread()
,W/libprocessgroup(  761): failed to open /acct/uid_10038/pid_2287/cgroup.procs: No such file or directory
,D/WifiService(  761): New client listening to asynchronous messages
,D/AuthorizationBluetoothService( 1412): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager(  761): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3076 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/bt_hwcfg( 3006): bt vendor lib: set UART baud 4000000
,D/bt_hwcfg( 3006): Chipset BCM4335C0
D/bt_hwcfg( 3006): Target name = [BCM4335C0]
,I/bt_hwcfg( 3006): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,I/art     ( 1412): Explicit concurrent mark sweep GC freed 9274(544KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 19MB/32MB, paused 962us total 28.568ms
,I/ActivityManager(  761): Killing 2337:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,I/bt_hwcfg( 3006): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 3006): Settlement delay -- 100 ms
,I/bt_hwcfg( 3006): Setting fw settlement delay to 100 
,W/libprocessgroup(  761): failed to open /acct/uid_10069/pid_2337/cgroup.procs: No such file or directory
,I/bt_hwcfg( 3006): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 3006): Setting local bd addr to 34:FC:EF:11:AE:67
,D/Tethering(  761): sendTetherStateChangedBroadcast 1, 0, 0
,I/bt_hwcfg( 3006): vendor lib fwcfg completed
,I/bt-btu  ( 3006): btu_task received preload complete event
,I/        ( 3006): BTE_InitTraceLevels -- TRC_HCI
,I/        ( 3006): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3006): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3006): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3006): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3006): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3006): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3006): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3006): BTE_InitTraceLevels -- TRC_GAP
,I/        ( 3006): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3006): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3006): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3006): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3006): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3006): BTE_InitTraceLevels -- TRC_BTIF
,I/wpa_supplicant( 3030): rfkill: Cannot open RFKILL control device
,I/wpa_supplicant( 3030): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiConfigStore(  761): Loading config and enabling all networks 
,E/WifiConfigStore(  761): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  761): Setting external_sim to 1
,D/WifiStateMachine(  761): Setting OUI to DA-A1-19
I/WifiNative-HAL(  761): startHal
D/wifi    (  761): setting scan oui 0xaf2626b8
D/WifiHAL (  761): Sending mac address OUI
E/WifiHAL (  761): failed to set scanning mac OUI; result = -95
,W/Settings( 1796): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/native  (  761): do suspend true
,D/WifiScanningService(  761): SCAN_AVAILABLE : 3
D/RttService(  761): SCAN_AVAILABLE : 3
D/WifiScanningService(  761): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  761): startHal
,D/RttService(  761): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/wifi    (  761): getting scan capabilities on interface[1] = 0xaf2626b8
D/WifiHAL (  761): Creating message to get scan capablities; iface = 21
D/WifiHAL (  761): In GetCapabilities::handleResponse
D/WifiHAL (  761): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  761): StartedState
,D/CommandListener(  179): Setting iface cfg
D/CommandListener(  179): Trying to bring up p2p0
,D/WifiMonitor(  761): startMonitoring(p2p0) with mConnected = true
,D/WifiNative-HAL(  761): p2pGetDeviceAddress
,D/WifiNative-HAL(  761): p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,E/bt-btm  ( 3006): BTM_SecRegister:p_cb_info->p_le_callback == 0xa400d9d5 
E/bt-btm  ( 3006): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa400d9d5 
,I/wpa_supplicant( 3030): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,I/ActivityManager(  761): Killing 1778:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,E/bt-btif ( 3006): Calling BTA_HhEnable
E/bt-btif ( 3006): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3006): Address is:34:FC:EF:11:AE:67
,W/bt-smp  ( 3006): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3006): Plain text(LSB ~ MSB) = 92 a3 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3006): Encrypted text(LSB ~ MSB) = f8 3e ee 8d 7a 63 0d e5 c4 e0 20 7d fd de 09 0a 
W/bt-btm  ( 3006): Stopping oneshot timer
,W/libprocessgroup(  761): failed to open /acct/uid_10045/pid_1778/cgroup.procs: No such file or directory
,D/BluetoothManagerService(  761): Bluetooth Adapter name changed to Nexus 5
,D/BluetoothAdapterProperties( 3006): Name is: Nexus 5
D/BluetoothManagerService(  761): Stored Bluetooth name: Nexus 5
,D/BluetoothAdapterProperties( 3006): Scan Mode:20
D/BluetoothAdapterProperties( 3006): Discoverable Timeout:120
,D/bte_conf( 3006): Device ID record 1 : primary
D/bte_conf( 3006):   vendorId            = 000f
D/bte_conf( 3006):   vendorIdSource      = 0001
D/bte_conf( 3006):   product             = 1200
D/bte_conf( 3006):   version             = 1436
D/bte_conf( 3006):   clientExecutableURL = 
D/bte_conf( 3006):   serviceDescription  = 
D/bte_conf( 3006):   documentationURL    = 
D/bte_conf( 3006): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 3006): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 3006): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3006): ScanMode =  20
D/BluetoothAdapterProperties( 3006): State =  11
D/BluetoothAdapterProperties( 3006): Setting state to 12
I/BluetoothAdapterState( 3006): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService(  761): Message: 60
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  761): Broadcasting onBluetoothStateChange(true) to 5 receivers.
D/BluetoothHeadset(  761): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 3006): Entering On State
,D/BluetoothHeadset( 1227): onBluetoothStateChange: up=true
D/BluetoothAdapterProperties( 3006): Scan Mode:21
D/BluetoothAdapterProperties( 3006): Discoverable Timeout:120
,D/BluetoothHeadset( 1194): onBluetoothStateChange: up=true
,D/BluetoothA2dp(  761): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1194): onBluetoothStateChange: up=true
,E/bt_h4   ( 3006): vendor lib postload completed
,D/BluetoothManagerService(  761): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothManagerService(  761): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothMapService( 3006): onReceive
D/BluetoothMapService( 3006): STATE_ON
V/BluetoothMapService( 3006): Handler(): got msg=1
,D/BluetoothMapMasInstance( 3006): Map Service startRfcommSocketListener
,D/BluetoothManagerService(  761): Message: 40
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothMapMasInstance( 3006): MAS initSocket()
D/BluetoothMapMasInstance( 3006):   masId = 00
D/BluetoothMapMasInstance( 3006):   msgTypes = 0e
D/BluetoothMapMasInstance( 3006):   masName = SMS/MMS
D/BluetoothMapMasInstance( 3006):   SDP string = 000eSMS/MMS
,I/Telecom ( 1194): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3006): getBluetoothService() called with no BluetoothManagerCallback
,V/BluetoothMapMasInstance( 3006): Succeed to create listening socket 
D/BluetoothMapMasInstance( 3006): Accepting socket connection...
,D/HeadsetStateMachine( 3006): Disconnected process message: 9, size: 0
D/HeadsetStateMachine( 3006): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 3006): mNumber:  mType: 128
D/HeadsetStateMachine( 3006): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 3006): terminateScoUsingVirtualVoiceCall:No present call to terminate
,W/ContextImpl( 3038): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@18173a09:true
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3006): getBluetoothService() called with no BluetoothManagerCallback
,D/LocalBluetoothProfileManager( 3038): Adding local A2DP profile
D/BluetoothManagerService(  761): Message: 30
D/LocalBluetoothProfileManager( 3038): Adding local HEADSET profile
D/BluetoothManagerService(  761): Message: 30
,I/art     (  761): Explicit concurrent mark sweep GC freed 25292(1316KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 896us total 60.189ms
,D/BluetoothManagerService(  761): Message: 30
D/BluetoothManagerService(  761): Message: 30
,D/LocalBluetoothProfileManager( 3038): Adding local MAP profile
,D/BluetoothMap( 3038): Create BluetoothMap proxy object
D/BluetoothManagerService(  761): Message: 30
,D/BluetoothManagerService(  761): Message: 30
,D/LocalBluetoothProfileManager( 3038): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3038): finishStartingService: stopping service
,D/BluetoothA2dp( 3038): Proxy object connected
,D/A2dpProfile( 3038): Bluetooth service connected
,D/BluetoothHeadset( 3038): Proxy object connected
D/HeadsetProfile( 3038): Bluetooth service connected
,D/BluetoothInputDevice( 3038): Proxy object connected
D/HidProfile( 3038): Bluetooth service connected
,D/BluetoothPan( 3038): BluetoothPAN Proxy object connected
,D/PanProfile( 3038): Bluetooth service connected
,D/AuthorizationBluetoothService( 1412): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothMap( 3038): Proxy object connected
D/MapProfile( 3038): Bluetooth service connected
D/BluetoothMap( 3038): getConnectedDevices()
V/BluetoothMapService( 3006): getConnectedDevices()
,D/BluetoothPbap( 3038): Proxy object connected
D/PbapServerProfile( 3038): Bluetooth service connected
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3006): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 3006): Accept thread started.
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 2931): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): my name is : LGE-Nexus 5_PT3779
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): attempting to connect to test coordinator
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): check test folder
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): found test : ./testFindPeers.js
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): found test : ./testReConnect.js
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): found test : ./testSendData.js
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): Test app app.js loaded
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/chromium( 2931): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  761): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiStateMachine(  761): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  761): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=1
,E/WifiConfigStore(  761): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  761): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  761): will read network variables netId=1
,E/WifiStateMachine(  761): CMD_AUTO_CONNECT did save config ->  nid=1
,E/WifiConfigStore(  761): will read network variables netId=1
,I/wpa_supplicant( 3030): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,E/WifiConfigStore(  761): setLastSelectedConfiguration -1
,E/wpa_supplicant( 3030): PNO: In assoc process
,I/wpa_supplicant( 3030): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3030): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3030): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  761): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  761): Start Dhcp Watchdog 1
,E/native  (  761): do suspend false
,E/WifiStateMachine(  761): scanCount==0 - aborting
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/dhcpcd  ( 3166): version 5.5.6 starting
,E/dhcpcd  ( 3166): get_duid: Read-only file system
,I/dhcpcd  ( 3166): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3166): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3166): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  761): do suspend true
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  761): Adding iface wlan0 to network 100
,E/ConnectivityService(  761): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  761): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/ConnectivityService(  761): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  761): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  761): Setting Dns servers for network 100 to [/192.168.1.1]
,D/Nat464Xlat(  761): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  761): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  761): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  761):    accepting network in place of null
D/ConnectivityService(  761): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
,D/CSLegacyTypeTracker(  761): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  761): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 03 Dec 2015 14:40:12 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449153613503], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449153613486]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Validated
,D/ConnectivityService(  761): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  761): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/TelephonyNetworkFactory( 1227): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/Nat464Xlat(  761): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  761): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524295
,V/GLSActivity( 1412): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1412): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2468): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2468): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/AlarmManagerService(  761): Setting time of day to sec=1449153615
,W/AlarmManagerService(  761): Unable to set rtc to 1449153615: Invalid argument
,I/iu.SyncManager( 1557): SYNC; picasa accounts
,E/GpsLocationProvider(  761): No APN found to select.
,D/NetworkLogImpl( 1557): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1557): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1557): num queued entries: 0
,D/GpsLocationProvider(  761): NTP server returned: 1449153615722 (Thu Dec 03 15:40:15 GMT+01:00 2015) reference: 84858 certainty: 6 system time offset: -98
E/LocSvc_eng(  761): E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,I/iu.UploadsManager( 1557): num updated entries: 0
,I/iu.SyncManager( 1557): NEXT; no task
,D/ChimeraCfgMgr( 1557): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1557): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/SystemUpdateService( 1557): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1557): onCreate
,D/SystemUpdateService( 1557): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,V/GLSActivity( 1412): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SystemUpdateService( 1557): active receiver: enabled
,V/GLSActivity( 1412): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SystemUpdateService( 1557): showing system update notification
,E/Auth.Api.Credentials( 1557): [CredentialSyncAdapter] Unknown sync event.
,I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1557): retry (wakeup: false) in 3599977 ms
,I/ActivityManager(  761): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3264 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SystemUpdateService( 1557): onDestroy
,V/GLSActivity( 1412): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1412): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 2931): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 2931): 
,I/Babel   ( 1796): connection state changed from UNKNOWN to CONNECTED
,I/GCM     ( 1412): GCM config loaded
,E/ConnectivityChangeReceiver( 1557): Ignoring connectivity change
,D/ConnectivityService(  761): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  761): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  761): apparently satisfied.  currentScore=60
D/ConnectivityManager.CallbackHandler( 1557): CM callback handler got msg 524290
,I/GAv4    ( 3264): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3264):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3264):   adb logcat -s GAv4
,W/GAv4    ( 3264): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3264): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3264): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/Auth.Api.Credentials( 1557): [CredentialSyncAdapter] Unknown sync event.
,W/DriveInitializer( 1557): Awaiting to be initialized
W/DriveInitializer( 1557): Background init thread started
,W/AbstractGoogleClient( 2015): Application name is not set. Call Builder#setApplicationName.
,I/AnalyticsLogBase( 2015): PlayLogger.onLoggerConnected
,I/art     ( 1412): Explicit concurrent mark sweep GC freed 8638(494KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 19MB/32MB, paused 690us total 30.434ms
,I/WebViewFactory( 3264): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3264): Time to load native libraries: 1 ms (timestamps 5467-5468)
I/LibraryLoader( 3264): Expected native library version number "",actual native library version number ""
,W/art     ( 2622): Attempt to remove local handle scope entry from IRT, ignoring
,V/WebViewChromiumFactoryProvider( 3264): Binding Chromium to main looper Looper (main, tid 1) {35d1c1b1}
I/LibraryLoader( 3264): Expected native library version number "",actual native library version number ""
I/chromium( 3264): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3264): Initializing chromium process, singleProcess=true
,W/art     ( 3264): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3264): ApplicationContext is null in ApplicationStatus
,W/DriveInitializer( 1557): Background init thread ended
,W/chromium( 3264): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3264): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3264): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3264): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/art     (  761): Explicit concurrent mark sweep GC freed 38422(1899KB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 27MB/41MB, paused 919us total 56.338ms
,W/AudioManagerAndroid( 3264): Requires BLUETOOTH permission
,I/NSApplication( 3264): Starting up...
,I/ActivityManager(  761): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3364 uid=10076 gids={50076, 9997} abi=armeabi-v7a
,I/art     (  194): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 185us total 7.831ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 167us total 7.357ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 168us total 7.306ms
,D/TimeService( 3364): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449153616615
,D/        ( 3364): TimeServiceNative: User Time to be set is 1449153616616
D/QC-time-services( 3364): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3364): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3364): Lib:time_genoff_operation: pargs->ts_val = 1449153616616
D/QC-time-services(  197): Daemon: Connection accepted:time_genoff
D/QC-time-services( 3364): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  197): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449153616616
D/QC-time-services(  197): Daemon:genoff_opr: Base = 2, val = 1449153616616, operation = 0
D/QC-time-services(  197): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/6/70 20:31:3
D/QC-time-services(  197): Daemon:Value read from RTC seconds = 8281863000
D/QC-time-services(  197): Daemon:new time 1449153616616 
D/QC-time-services(  197): Daemon: delta 1440871753616 genoff 1440871753616 
D/QC-time-services(  197): Daemon:genoff_persistent_update: Writing genoff = 1440871753616 to memory
D/QC-time-services(  197): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  197): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  197): Updating the TOD offset
D/QC-time-services(  197): Daemon:genoff_persistent_update: Writing genoff = 1440871753616 to memory
,D/QC-time-services(  197): Daemon:Opening File: /data/system/time/ats_1
D/QC-time-services(  197): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  197): Daemon:Update to modem bit set
,D/QC-time-services(  197): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  197): Daemon: Base = 2, Value being sent to MODEM = 1133188816616
E/QC-time-services( 3364): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/QC-time-services(  197): Daemon: Time-services: Waiting to acceptconnection
,D/QC-time-services(  197): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,I/CheckinService( 1557): Checkin interval check for package: unspecified last checkin: 1449151177473 min interval config: 0 actual interval: 2439171
,I/ActivityManager(  761): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=3383 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3383): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3383):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3383):   adb logcat -s GAv4
,W/GAv4    ( 3383): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3383): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3383): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/CalendarSyncAdapter( 2015): Found no pending settings
,I/ActivityManager(  761): Killing 2311:com.google.android.gm/u0a70 (adj 15): empty #17
,I/ActivityManager(  761): Killing 2426:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #18
,W/libprocessgroup(  761): failed to open /acct/uid_10070/pid_2311/cgroup.procs: No such file or directory
,W/libprocessgroup(  761): failed to open /acct/uid_10003/pid_2426/cgroup.procs: No such file or directory
,I/ActivityManager(  761): Start proc com.google.android.apps.cloudprint:sync for service com.google.android.apps.cloudprint/.printdialog.services.CloudPrintSyncService: pid=3415 uid=10035 gids={50035, 9997, 3003, 1028} abi=armeabi-v7a
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/ActivityManager(  761): Start proc com.google.android.apps.cloudprint for service com.google.android.apps.cloudprint/.printdialog.services.NotificationIntentService: pid=3434 uid=10035 gids={50035, 9997, 3003, 1028} abi=armeabi-v7a
,I/com.google.android.apps.cloudprint.printdialog.database.CloudPrintSyncAdapter( 3415): Sync request not initiated by GCP app. Dropping
,I/ActivityManager(  761): Killing 1459:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10013/pid_1459/cgroup.procs: No such file or directory
,I/ActivityManager(  761): Killing 2836:com.android.musicfx/u0a15 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10015/pid_2836/cgroup.procs: No such file or directory
,W/BaseAppContext( 1316): Using Auth Proxy for data requests.
,I/CalendarSyncAdapter( 2015): Found no pending settings
,I/art     ( 1316): Explicit concurrent mark sweep GC freed 21783(1318KB) AllocSpace objects, 15(240KB) LOS objects, 39% free, 19MB/32MB, paused 1.556ms total 53.304ms
,E/DataBuffer( 1316): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@d3bbfcf)
,I/GCoreUlr( 1316): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,I/GCoreUlr( 1316): DispatchingService.onCreate()
,I/GCoreUlr( 1316): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1316): Unbound from all location providers
,I/art     ( 1557): Explicit concurrent mark sweep GC freed 13386(969KB) AllocSpace objects, 18(288KB) LOS objects, 40% free, 21MB/36MB, paused 849us total 56.163ms
,I/GCoreUlr( 1316): DispatchingService.onDestroy()
,I/GCoreUlr( 1316): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1316): Unbound from all location providers
,I/art     (  761): Explicit concurrent mark sweep GC freed 19156(821KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.073ms total 90.152ms
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,D/Finsky  ( 2368): [230] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2368): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager(  761): Killing 2864:com.google.android.apps.docs/u0a40 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10040/pid_2864/cgroup.procs: No such file or directory
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,V/GLSActivity( 1412): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1412): Vacuum at: now=1449153633696 tag=VacuumService
,D/UdcCache:FPQuery( 1557): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 1412): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1412): Explicit concurrent mark sweep GC freed 24154(1559KB) AllocSpace objects, 12(192KB) LOS objects, 39% free, 19MB/32MB, paused 596us total 24.365ms
,V/GLSActivity( 1412): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GetConfigurationSnapshotOperation( 1412): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1412): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1412): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 1412): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1412): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1412): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/Uploader( 1412):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1412): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1412): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1412): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1412): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1412): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1412): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,D/HeadsetStateMachine( 3006): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3006): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/HeadsetStateMachine( 3006): Disconnected process message: 11, size: 0
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/ClearcutLoggerApiImpl( 1316): disconnect managed GoogleApiClient
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector connect called
I/jxcore-log( 2931): 
I/jxcore-log( 2931): Coordinator is now connected to the server!
I/jxcore-log( 2931): 
,I/chromium( 2931): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,V/GLSActivity( 1412): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1412): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1412): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 1557): Aggregate from 1449152073585 (log), 1449152073585 (data)
,I/jxcore-log( 2931): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector command called
I/jxcore-log( 2931): 
I/jxcore-log( 2931): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":17,"addressList":[{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"B4:CE:F6:AB:A4:6A","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"34:FC:EF:9D:93:0B","tryCount":0},{"address":"00:F4:6F:30:E0:6C","tryCount":0},{"address":"F4:F1:E1:5C:3B:E2","tryCount":0}]}
I/jxcore-log( 2931): 
I/jxcore-log( 2931): Start now : testSendData.js
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 17
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): check server
I/jxcore-log( 2931): 
I/jxcore-log( 2931): serverPort is 60555
I/jxcore-log( 2931): 
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 2931): Stoping All
I/        ( 2931): Stopping services
I/        ( 2931): Stop Bluetooth
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 2931): Start-My BT: 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 2931):  mInstanceString : {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT3779","ra":"34:FC:EF:11:AE:67"}
,I/        ( 2931): All stuff available and enabled
I/        ( 2931): Stoping All
I/        ( 2931): Stopping services
I/        ( 2931): Stop Bluetooth
I/        ( 2931): Starting All
I/        ( 2931): Stopping services
I/        ( 2931): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT3779","ra":"34:FC:EF:11:AE:67"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@1d7dcbd2
I/        ( 2931): Stopping services
I/        ( 2931): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT3779","ra":"34:FC:EF:11:AE:67"}
I/        ( 2931): Add local service :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT3779","ra":"34:FC:EF:11:AE:67"}, length : 77
,I/        ( 2931): peerDiscoveryTimer timeout value:8994
,I/        ( 2931): Stop Bluetooth
I/        ( 2931): StartBluetooth listener
I/        ( 2931): StartBluetooth listener
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2931): StartBroadcasting started ok
I/jxcore-log( 2931): 
I/jxcore-log( 2931): do fake peer & start
I/jxcore-log( 2931): 
I/jxcore-log( 2931): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:45:46.608Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:45:46.609Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:45:46.609Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2931): Connecting to null, at 00:F4:6F:30:E0:6C
,I/jxcore-log( 2931): 2015-12-03T14:45:46.615Z SendDataTCPServer.js: TCP/IP server is bound to port: 60555
I/jxcore-log( 2931): 
I/chromium( 2931): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/WB      ( 2931): We already were running, thus doing nothing
I/        ( 2931): Added local service
I/        ( 2931): Cleared service requests
I/        ( 2931): Stopped peer discovery
I/        ( 2931): Started peer discovery
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 2931): Discovery state changed to Started.
,I/BTListenerThread( 2931): starting to listen
I/BTListenerThread( 2931): waiting to accept incoming Connection
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3006): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3006): process_service_search_attr_rsp
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 2931): Found 2 peers.
I/SS      ( 2931): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2931): Peer(2): G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 2931): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2931): Added service request
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 1
E/bt-btif ( 3006): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3006): Entering PendingCommandState State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device 00:F4:6F:30:E0:6C not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for 00:F4:6F:30:E0:6C, but we have no record of that device.
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 0
,D/BluetoothAdapterProperties( 3006): Failed to remove device: 00:F4:6F:30:E0:6C
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 11 NewState: 10
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device 00:F4:6F:30:E0:6C not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for 00:F4:6F:30:E0:6C, but we have no record of that device.
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 3006): StableState(): Entering Off State
,I/wpa_supplicant( 3030): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2931): Started service discovery
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2931): Starting to Handshake
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2931): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4184ebc rs_disc_pending=0
,W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BTConnectToThread( 2931): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 2931): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9166"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2931): HandshakeOk : samsung-SM-G800F_PT9166
I/HS      ( 2931): Hand Shake finished outgoing for : samsung-SM-G800F_PT9166
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : false, samsung-SM-G800F_PT9166
,I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2931): mHTTPPort  set to : 54670
,I/BtConnectorHelper( 2931): Request socket is using : 54670
,I/BtToRequestSocket( 2931): Now accepting connections
,I/BtConnectorHelper( 2931): Calling ConnectionStatusUpdate with port :54670
I/jxcore-log( 2931): 2015-12-03T14:45:54.490Z SendDataConnector.js: CLIENT connected to 54670, error: null
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:45:54.491Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): incoming data from: /127.0.0.1, port: 54670
I/BtToRequestSocket( 2931): Set local streams
I/BtToRequestSocket( 2931): rin ended ---------------------------;
,I/jxcore-log( 2931): 2015-12-03T14:45:54.534Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:45:55.860Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:45:56.168Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:45:56.559Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:45:56.772Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:45:57.008Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:45:57.213Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:45:57.506Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:45:57.993Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:45:58.181Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): dm_pm_timer expires
W/bt-btif ( 3006): dm_pm_timer expires 0
W/bt-btif ( 3006): proc dm_pm_timer expires
,I/jxcore-log( 2931): 2015-12-03T14:46:08.182Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:46:08.188Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:46:08.198Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:46:08.199Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:46:08.210Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2931): 
,I/BtToSocketBase( 2931): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2931): Disconnect outgoing peer: samsung-SM-G800F_PT9166
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
I/BtToRequestSocket( 2931): Close server socket
,W/bt-btif ( 3006): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@171eaf3b:true
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: S5mini-1
,I/jxcore-log( 2931): 2015-12-03T14:46:13.209Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:46:13.209Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:46:18.210Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:46:18.210Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:46:18.210Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:46:18.210Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 2931): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: S5mini-1
,W/bt-sdp  ( 3006): process_service_search_attr_rsp
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2931): Starting to Handshake
,I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2931): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTConnectToThread( 2931): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 2931): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9166"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2931): HandshakeOk : samsung-SM-G800F_PT9166
I/HS      ( 2931): Hand Shake finished outgoing for : samsung-SM-G800F_PT9166
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : false, samsung-SM-G800F_PT9166
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 2931): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2931): mHTTPPort  set to : 40792
I/BtConnectorHelper( 2931): Request socket is using : 40792
I/BtToRequestSocket( 2931): Now accepting connections
,I/BtConnectorHelper( 2931): Calling ConnectionStatusUpdate with port :40792
I/jxcore-log( 2931): 2015-12-03T14:46:20.511Z SendDataConnector.js: CLIENT connected to 40792, error: null
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:46:20.511Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): incoming data from: /127.0.0.1, port: 40792
I/BtToRequestSocket( 2931): Set local streams
I/BtToRequestSocket( 2931): rin ended ---------------------------;
,I/jxcore-log( 2931): 2015-12-03T14:46:20.538Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2931): 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3006): dm_pm_timer expires
W/bt-btif ( 3006): dm_pm_timer expires 0
W/bt-btif ( 3006): proc dm_pm_timer expires
,I/jxcore-log( 2931): 2015-12-03T14:46:30.611Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:46:30.612Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:46:30.613Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:46:30.618Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:46:30.623Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2931): 
,I/BtToSocketBase( 2931): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2931): Disconnect outgoing peer: samsung-SM-G800F_PT9166
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
I/BtToRequestSocket( 2931): Close server socket
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3006): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185084 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4184ebc rs_disc_pending=1
,W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
E/bt-btif ( 3006): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3006): Entering PendingCommandState State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 3006): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3006): StableState(): Entering Off State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185084 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185084 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2931): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2317","ra":"08:EC:A9:50:75:41"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT2317
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, samsung-SM-A300FU_PT2317
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/jxcore-log( 2931): 2015-12-03T14:46:34.579Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
I/BtToRequestSocket( 2931): --DoOneRunRound ended
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4184ebc rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: S5mini-1
,I/jxcore-log( 2931): 2015-12-03T14:46:35.459Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:46:35.463Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:46:35.471Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:46:35.478Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:46:35.484Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:46:35.491Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:46:35.529Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:46:35.567Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:46:35.581Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:46:35.619Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:46:35.645Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:46:35.645Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:46:35.649Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:46:35.676Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:46:35.715Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:46:35.730Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:46:35.768Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:46:35.778Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:46:35.816Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:46:35.829Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:46:35.867Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:46:35.878Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:46:35.898Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:46:35.981Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:46:36.016Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:46:36.031Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): invalid rfc slot id: 4
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT2317
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT2317
I/BtToSocketBase( 2931): Close LocalOutputStream
,I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
,I/BtToSocketBase( 2931): Close bt socket
,I/jxcore-log( 2931): 2015-12-03T14:46:36.124Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x47
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: A3-1
,I/jxcore-log( 2931): 2015-12-03T14:46:40.647Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:46:40.647Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:46:40.647Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:46:40.648Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 2931): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: S5mini-1
,W/bt-sdp  ( 3006): process_service_search_attr_rsp
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2931): Starting to Handshake
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTConnectToThread( 2931): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTConnectToThread( 2931): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 2931): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9166"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 2931): HandshakeOk : samsung-SM-G800F_PT9166
I/HS      ( 2931): Hand Shake finished outgoing for : samsung-SM-G800F_PT9166
I/BtConnectorHelper( 2931): Starting the connected thread incoming : false, samsung-SM-G800F_PT9166
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2931): mHTTPPort  set to : 57679
I/BtConnectorHelper( 2931): Request socket is using : 57679
I/BtToRequestSocket( 2931): Now accepting connections
,I/BtConnectorHelper( 2931): Calling ConnectionStatusUpdate with port :57679
I/jxcore-log( 2931): 2015-12-03T14:46:42.497Z SendDataConnector.js: CLIENT connected to 57679, error: null
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:46:42.497Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:46:42.499Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): incoming data from: /127.0.0.1, port: 57679
I/BtToRequestSocket( 2931): Set local streams
I/BtToRequestSocket( 2931): rin ended ---------------------------;
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3006): dm_pm_timer expires
W/bt-btif ( 3006): dm_pm_timer expires 0
W/bt-btif ( 3006): proc dm_pm_timer expires
,I/        ( 2931): Cleared service requests
I/        ( 2931): Started peer discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2931): Found 5 peers.
I/SS      ( 2931): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2931): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2931): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2931): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2931): Peer(5): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 2931): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2931): Added service request
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2931): Started service discovery
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 2931): 2015-12-03T14:46:52.580Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:46:52.580Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:46:52.582Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:46:52.582Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:46:52.587Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2931): 
,I/BtToSocketBase( 2931): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2931): Disconnect outgoing peer: samsung-SM-G800F_PT9166
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
I/BtToRequestSocket( 2931): Close server socket
,W/bt-btif ( 3006): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: S5mini-1
,I/jxcore-log( 2931): 2015-12-03T14:46:57.584Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:46:57.584Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:02.587Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:47:02.588Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:47:02.589Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:47:02.589Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 2931): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: S5mini-1
,W/bt-sdp  ( 3006): process_service_search_attr_rsp
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2931): Starting to Handshake
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2931): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTConnectToThread( 2931): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 2931): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9166"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2931): HandshakeOk : samsung-SM-G800F_PT9166
I/HS      ( 2931): Hand Shake finished outgoing for : samsung-SM-G800F_PT9166
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : false, samsung-SM-G800F_PT9166
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2931): mHTTPPort  set to : 57209
I/BtConnectorHelper( 2931): Request socket is using : 57209
,I/BtToRequestSocket( 2931): Now accepting connections
,I/BtConnectorHelper( 2931): Calling ConnectionStatusUpdate with port :57209
I/jxcore-log( 2931): 2015-12-03T14:47:04.023Z SendDataConnector.js: CLIENT connected to 57209, error: null
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:04.023Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): incoming data from: /127.0.0.1, port: 57209
I/BtToRequestSocket( 2931): Set local streams
I/BtToRequestSocket( 2931): rin ended ---------------------------;
,I/jxcore-log( 2931): 2015-12-03T14:47:04.051Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2931): 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3006): dm_pm_timer expires
W/bt-btif ( 3006): dm_pm_timer expires 0
W/bt-btif ( 3006): proc dm_pm_timer expires
,I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,I/jxcore-log( 2931): 2015-12-03T14:47:14.110Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:47:14.110Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:47:14.112Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:47:14.112Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:14.118Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2931): 
,I/BtToSocketBase( 2931): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2931): Disconnect outgoing peer: samsung-SM-G800F_PT9166
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
I/BtToRequestSocket( 2931): Close server socket
,W/bt-btif ( 3006): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/jxcore-log( 2931): 2015-12-03T14:47:19.113Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:47:19.114Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2931): 
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: S5mini-1
,I/jxcore-log( 2931): 2015-12-03T14:47:24.127Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:47:24.128Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:47:24.128Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:47:24.129Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 2931): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,W/bt-sdp  ( 3006): process_service_search_attr_rsp
,E/bt-btif ( 3006): DISCOVERY_COMP_EVT slot id:10, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3006): invalid rfc slot id: 10
,I/BTConnectToThread( 2931): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2931): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2931): 2015-12-03T14:47:25.629Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:47:25.629Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:25.631Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:47:25.631Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:47:25.632Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2931): 
I/jxcore-log( 2931): ---- round done--------
I/jxcore-log( 2931): 
I/jxcore-log( 2931): ---- gotta redo : 00:F4:6F:30:E0:6C, try count now: 1
I/jxcore-log( 2931): 
I/jxcore-log( 2931): do fake peer & start
I/jxcore-log( 2931): 
I/jxcore-log( 2931): Connect to fake peer: B0:C5:59:3F:75:69
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:47:25.633Z SendDataConnector.js: Start called with peer B0:C5:59:3F:75:69
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:47:25.633Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:47:25.633Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: B0:C5:59:3F:75:69, name: null
,I/        ( 2931): Connecting to null, at B0:C5:59:3F:75:69
,I/chromium( 2931): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 00:F4:6F:30:E0:6C done with result: Connection to 00:F4:6F:30:E0:6C failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: S5mini-1
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4184ebc rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4184ebc rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4184ebc rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,E/BluetoothRemoteDevices( 3006): aclStateChangeCallback: Device is NULL
W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: S5mini-1
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418524c rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3006): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
E/bt-btif ( 3006): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3006): Entering PendingCommandState State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device B0:C5:59:3F:75:69 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for B0:C5:59:3F:75:69, but we have no record of that device.
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,D/BluetoothAdapterProperties( 3006): Failed to remove device: B0:C5:59:3F:75:69
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3006): StableState(): Entering Off State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device B0:C5:59:3F:75:69 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for B0:C5:59:3F:75:69, but we have no record of that device.
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2931): Starting to Handshake
,I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2931): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTConnectToThread( 2931): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 2931): Got JSON from encryption:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8216","ra":"B0:C5:59:3F:75:69"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2931): HandshakeOk : samsung-SM-G900F_PT8216
I/HS      ( 2931): Hand Shake finished outgoing for : samsung-SM-G900F_PT8216
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : false, samsung-SM-G900F_PT8216
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2931): mHTTPPort  set to : 57489
I/BtConnectorHelper( 2931): Request socket is using : 57489
I/BtToRequestSocket( 2931): Now accepting connections
,I/BtConnectorHelper( 2931): Calling ConnectionStatusUpdate with port :57489
I/jxcore-log( 2931): 2015-12-03T14:47:32.914Z SendDataConnector.js: CLIENT connected to 57489, error: null
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:47:32.915Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): incoming data from: /127.0.0.1, port: 57489
I/BtToRequestSocket( 2931): Set local streams
I/BtToRequestSocket( 2931): rin ended ---------------------------;
,I/jxcore-log( 2931): 2015-12-03T14:47:32.945Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418524c rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,D/        ( 3006): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:402
,I/jxcore-log( 2931): 2015-12-03T14:47:33.844Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:33.951Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:34.161Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:34.239Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:34.295Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:34.346Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:34.374Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:34.416Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:34.725Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2931): 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3006): dm_pm_timer expires
W/bt-btif ( 3006): dm_pm_timer expires 0
,W/bt-btif ( 3006): proc dm_pm_timer expires
,I/jxcore-log( 2931): 2015-12-03T14:47:44.725Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:47:44.725Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:47:44.727Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:47:44.730Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:47:44.731Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2931): 
,I/BtToSocketBase( 2931): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 2931): Disconnect outgoing peer: samsung-SM-G900F_PT8216
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
,I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
,I/BtToSocketBase( 2931): Close bt in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
I/BtToRequestSocket( 2931): Close server socket
,W/bt-btif ( 3006): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,I/        ( 2931): Cleared service requests
I/        ( 2931): Started peer discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3006): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2931): 2015-12-03T14:47:49.731Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:47:49.732Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 2931): 
,W/bt-btm  ( 3006): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418524c rs_disc_pending=2
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2931): Found 6 peers.
I/SS      ( 2931): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2931): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2931): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2931): Peer(4): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 2931): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2931): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2931): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2931): Added service request
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
E/bt-btif ( 3006): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3006): Entering PendingCommandState State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device 58:3F:54:73:64:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for 58:3F:54:73:64:C0, but we have no record of that device.
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
,D/BluetoothAdapterProperties( 3006): Failed to remove device: 58:3F:54:73:64:C0
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3006): StableState(): Entering Off State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device 58:3F:54:73:64:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for 58:3F:54:73:64:C0, but we have no record of that device.
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 2931): Started service discovery
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185414 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2931): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT7284","ra":"58:3F:54:73:64:C0"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : LGE-LG-D855_PT7284
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, LGE-LG-D855_PT7284
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
,I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/jxcore-log( 2931): 2015-12-03T14:47:51.648Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
,I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 2931): 2015-12-03T14:47:52.658Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:52.671Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:52.685Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:52.694Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:52.710Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:52.723Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:52.757Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:52.830Z SendDataTCPServer.js: TCP/IP server has received 18092 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:52.852Z SendDataTCPServer.js: TCP/IP server has received 20072 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:52.863Z SendDataTCPServer.js: TCP/IP server has received 22052 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:52.896Z SendDataTCPServer.js: TCP/IP server has received 27992 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:52.930Z SendDataTCPServer.js: TCP/IP server has received 29972 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:52.966Z SendDataTCPServer.js: TCP/IP server has received 31952 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:52.983Z SendDataTCPServer.js: TCP/IP server has received 33932 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:53.017Z SendDataTCPServer.js: TCP/IP server has received 41852 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:53.029Z SendDataTCPServer.js: TCP/IP server has received 43832 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:53.067Z SendDataTCPServer.js: TCP/IP server has received 49772 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:53.080Z SendDataTCPServer.js: TCP/IP server has received 51752 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:53.097Z SendDataTCPServer.js: TCP/IP server has received 55712 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:53.126Z SendDataTCPServer.js: TCP/IP server has received 57692 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:53.141Z SendDataTCPServer.js: TCP/IP server has received 59672 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:53.227Z SendDataTCPServer.js: TCP/IP server has received 61652 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:53.237Z SendDataTCPServer.js: TCP/IP server has received 63632 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:53.276Z SendDataTCPServer.js: TCP/IP server has received 71552 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:53.291Z SendDataTCPServer.js: TCP/IP server has received 73532 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:53.347Z SendDataTCPServer.js: TCP/IP server has received 75512 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:53.409Z SendDataTCPServer.js: TCP/IP server has received 77492 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:53.434Z SendDataTCPServer.js: TCP/IP server has received 79472 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:53.463Z SendDataTCPServer.js: TCP/IP server has received 81452 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:53.486Z SendDataTCPServer.js: TCP/IP server has received 83432 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:53.526Z SendDataTCPServer.js: TCP/IP server has received 85412 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:53.535Z SendDataTCPServer.js: TCP/IP server has received 87392 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:53.541Z SendDataTCPServer.js: TCP/IP server has received 89372 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:53.547Z SendDataTCPServer.js: TCP/IP server has received 91352 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:53.559Z SendDataTCPServer.js: TCP/IP server has received 93332 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:53.595Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:47:54.738Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:47:54.739Z SendDataConnector.js: Connect (retry count 1) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:47:54.739Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:47:54.740Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: B0:C5:59:3F:75:69, name: Thali Test (Galaxy S5)
,I/        ( 2931): Connecting to Thali Test (Galaxy S5), at B0:C5:59:3F:75:69
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185414 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-sdp  ( 3006): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
E/bt-btif ( 3006): DISCOVERY_COMP_EVT slot id:13, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3006): invalid rfc slot id: 13
,I/BTConnectToThread( 2931): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2931): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2931): 2015-12-03T14:48:00.108Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B0:C5:59:3F:75:69 failed
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:48:00.109Z SendDataConnector.js: CLIENT Can not Connect: Connection to B0:C5:59:3F:75:69 failed
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:48:00.109Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185414 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): invalid rfc slot id: 7
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D855_PT7284
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2931): 2015-12-03T14:48:03.704Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x40 current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x40
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3006): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185414 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2931): 2015-12-03T14:48:05.110Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:48:05.111Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 2931): 
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 1
E/bt-btif ( 3006): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3006): Entering PendingCommandState State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device B4:CE:F6:AB:A4:6A not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for B4:CE:F6:AB:A4:6A, but we have no record of that device.
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 0
,D/BluetoothAdapterProperties( 3006): Failed to remove device: B4:CE:F6:AB:A4:6A
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3006): StableState(): Entering Off State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device B4:CE:F6:AB:A4:6A not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for B4:CE:F6:AB:A4:6A, but we have no record of that device.
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTListenerThread( 2931): got MESSAGE_READ 84 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT4731"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT4731
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT4731
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/jxcore-log( 2931): 2015-12-03T14:48:06.305Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
,I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/jxcore-log( 2931): 2015-12-03T14:48:07.172Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:07.181Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:07.190Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:07.195Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:07.206Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:07.237Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:07.250Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:07.286Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:07.311Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:07.317Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:07.330Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:07.342Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:07.377Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:07.391Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:07.453Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:07.487Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:07.503Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:07.539Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:07.549Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:07.587Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:07.626Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:07.671Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:07.684Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:07.717Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:07.760Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:07.776Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:07.805Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:07.812Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:07.820Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: G3-1
,I/jxcore-log( 2931): 2015-12-03T14:48:10.116Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:48:10.117Z SendDataConnector.js: Connect (retry count 2) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:48:10.117Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:48:10.118Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: B0:C5:59:3F:75:69, name: Thali Test (Galaxy S5)
,I/        ( 2931): Connecting to Thali Test (Galaxy S5), at B0:C5:59:3F:75:69
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [b0:c5:59:3f:75:69]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Thali Test (Galaxy S5)
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418524c rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3006): process_service_search_attr_rsp
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418524c rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2931): Starting to Handshake
,I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2931): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418524c rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 2931): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 2931): Got JSON from encryption:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8216","ra":"B0:C5:59:3F:75:69"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2931): HandshakeOk : samsung-SM-G900F_PT8216
I/HS      ( 2931): Hand Shake finished outgoing for : samsung-SM-G900F_PT8216
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : false, samsung-SM-G900F_PT8216
,I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2931): mHTTPPort  set to : 50613
I/BtConnectorHelper( 2931): Request socket is using : 50613
I/BtToRequestSocket( 2931): Now accepting connections
,I/BtConnectorHelper( 2931): Calling ConnectionStatusUpdate with port :50613
I/jxcore-log( 2931): 2015-12-03T14:48:13.018Z SendDataConnector.js: CLIENT connected to 50613, error: null
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:48:13.018Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): incoming data from: /127.0.0.1, port: 50613
I/BtToRequestSocket( 2931): Set local streams
I/BtToRequestSocket( 2931): rin ended ---------------------------;
,I/jxcore-log( 2931): 2015-12-03T14:48:13.042Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2931): 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [58:3f:54:73:64:c0]: 0, 0, 0
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: G3-1
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185414 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185414 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3006): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa41857a4 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
,I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa41857a4 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2931): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT7284","ra":"58:3F:54:73:64:C0"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : LGE-LG-D855_PT7284
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, LGE-LG-D855_PT7284
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/jxcore-log( 2931): 2015-12-03T14:48:17.224Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/jxcore-log( 2931): 2015-12-03T14:48:17.664Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:17.668Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:17.681Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:17.685Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:17.717Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:17.787Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): invalid rfc slot id: 12
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT4731
,I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
,I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT4731
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/jxcore-log( 2931): 2015-12-03T14:48:17.877Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa41857a4 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): dm_pm_timer expires
W/bt-btif ( 3006): dm_pm_timer expires 0
,W/bt-btif ( 3006): proc dm_pm_timer expires
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x44
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 1,
I/BluetoothBondStateMachine( 3006): sspRequestCallback: [B@34d167e6 name: [B@cb58127 cod: 5898764 pairingVariant 0 passkey: 953335
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3006): Entering PendingCommandState State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device 80:01:84:8A:B3:68 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for 80:01:84:8A:B3:68, but we have no record of that device.
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418524c rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: HTC Desire 820
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418524c rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2931): 2015-12-03T14:48:23.110Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:48:23.110Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:48:23.111Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:48:23.112Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:48:23.113Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2931): 
,I/BtToSocketBase( 2931): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2931): Disconnect outgoing peer: samsung-SM-G900F_PT8216
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
,I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
I/BtToRequestSocket( 2931): Close server socket
,W/bt-btif ( 3006): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418524c rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Thali Test (Galaxy S5)
,W/bt-btif ( 3006): invalid rfc slot id: 14
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D855_PT7284
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2931): 2015-12-03T14:48:27.853Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:28.112Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:48:28.112Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [b4:ce:f6:ab:a4:6a]: 7, f, 610c
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: HTC Desire 820
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTListenerThread( 2931): got MESSAGE_READ 84 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT4731"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT4731
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT4731
,I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
,I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/jxcore-log( 2931): 2015-12-03T14:48:28.929Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:29.399Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:29.407Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:29.416Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:29.455Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:29.459Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x49
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2931): 2015-12-03T14:48:33.115Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:48:33.116Z SendDataConnector.js: Connect (retry count 3) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:48:33.117Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:48:33.117Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: B0:C5:59:3F:75:69, name: Thali Test (Galaxy S5)
,I/        ( 2931): Connecting to Thali Test (Galaxy S5), at B0:C5:59:3F:75:69
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: G3-1
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [b0:c5:59:3f:75:69]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Thali Test (Galaxy S5)
,W/bt-sdp  ( 3006): process_service_search_attr_rsp
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418524c rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa41855dc rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 3006): invalid rfc slot id: 18
,I/BTConnectToThread( 2931): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2931): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2931): 2015-12-03T14:48:37.992Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B0:C5:59:3F:75:69 failed
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:37.993Z SendDataConnector.js: CLIENT Can not Connect: Connection to B0:C5:59:3F:75:69 failed
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:37.997Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Thali Test (Galaxy S5)
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa41855dc rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [58:3f:54:73:64:c0]: 7, f, 610c
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: G3-1
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTListenerThread( 2931): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT7284","ra":"58:3F:54:73:64:C0"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : LGE-LG-D855_PT7284
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, LGE-LG-D855_PT7284
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
,I/jxcore-log( 2931): 2015-12-03T14:48:38.916Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/jxcore-log( 2931): 2015-12-03T14:48:39.338Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:39.341Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:39.345Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:39.381Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:39.388Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa41855dc rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): invalid rfc slot id: 16
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT4731
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2931): 2015-12-03T14:48:39.752Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa41855dc rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x4c
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2931): 2015-12-03T14:48:43.001Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:48:43.002Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: HTC Desire 820
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185414 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2931): 2015-12-03T14:48:48.005Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:48:48.006Z SendDataConnector.js: Connect (retry count 4) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:48:48.006Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:48:48.007Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: B0:C5:59:3F:75:69, name: Thali Test (Galaxy S5)
,I/        ( 2931): Connecting to Thali Test (Galaxy S5), at B0:C5:59:3F:75:69
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185414 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btm  ( 3006): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa41857a4 rs_disc_pending=2
E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3006): bta_dm_check_av:0
E/bt-btif ( 3006): Do not find the bg connection mask for the remote device
,E/bt-btif ( 3006): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 9 Address: 80:01:84:8A:B3:68 newState: 0
,D/BluetoothAdapterProperties( 3006): Failed to remove device: 80:01:84:8A:B3:68
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3006): onReceive
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3006): StableState(): Entering Off State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device 80:01:84:8A:B3:68 not found, calling readPairedDevices().
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,E/BluetoothEventManager( 3038): Got bonding state changed for 80:01:84:8A:B3:68, but we have no record of that device.
,I/BluetoothClassifier( 1352): Bluetooth Device Name: HTC Desire 820
,W/bt-btif ( 3006): invalid rfc slot id: 17
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D855_PT7284
,I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D855_PT7284
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/jxcore-log( 2931): 2015-12-03T14:48:50.130Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x42
,I/        ( 2931): Cleared service requests
I/        ( 2931): Started peer discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: HTC Desire 820
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa41855dc rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [b0:c5:59:3f:75:69]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2931): Found 6 peers.
I/SS      ( 2931): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2931): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2931): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2931): Peer(4): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 2931): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2931): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2931): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2931): Added service request
,W/bt-sdp  ( 3006): process_service_search_attr_rsp
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa41855dc rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418524c rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa41855dc rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2931): got MESSAGE_READ 84 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT4731"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT4731
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT4731
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
,I/jxcore-log( 2931): 2015-12-03T14:48:52.431Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/        ( 2931): Started service discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2931): 2015-12-03T14:48:52.948Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:52.992Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:53.117Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418524c rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2931): 2015-12-03T14:48:53.295Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:48:53.352Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: G3-1
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418524c rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2931): Starting to Handshake
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2931): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa41855dc rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418524c rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 2931): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 2931): Got JSON from encryption:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8216","ra":"B0:C5:59:3F:75:69"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2931): HandshakeOk : samsung-SM-G900F_PT8216
I/HS      ( 2931): Hand Shake finished outgoing for : samsung-SM-G900F_PT8216
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : false, samsung-SM-G900F_PT8216
,I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2931): mHTTPPort  set to : 37364
I/BtConnectorHelper( 2931): Request socket is using : 37364
I/BtToRequestSocket( 2931): Now accepting connections
,I/BtConnectorHelper( 2931): Calling ConnectionStatusUpdate with port :37364
I/jxcore-log( 2931): 2015-12-03T14:48:55.759Z SendDataConnector.js: CLIENT connected to 37364, error: null
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:48:55.760Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): incoming data from: /127.0.0.1, port: 37364
I/BtToRequestSocket( 2931): Set local streams
I/BtToRequestSocket( 2931): rin ended ---------------------------;
,I/jxcore-log( 2931): 2015-12-03T14:48:55.782Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2931): 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418524c rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: HTC Desire 820
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [58:3f:54:73:64:c0]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: G3-1
,W/bt-btif ( 3006): dm_pm_timer expires
W/bt-btif ( 3006): dm_pm_timer expires 1
,W/bt-btif ( 3006): proc dm_pm_timer expires
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 1
E/bt-btif ( 3006): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3006): Entering PendingCommandState State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device 80:01:84:8A:B3:68 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for 80:01:84:8A:B3:68, but we have no record of that device.
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 0
,D/BluetoothAdapterProperties( 3006): Failed to remove device: 80:01:84:8A:B3:68
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 11 NewState: 10
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device 80:01:84:8A:B3:68 not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 3006): StableState(): Entering Off State
,E/BluetoothEventManager( 3038): Got bonding state changed for 80:01:84:8A:B3:68, but we have no record of that device.
,I/BTListenerThread( 2931): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT7284","ra":"58:3F:54:73:64:C0"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : LGE-LG-D855_PT7284
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, LGE-LG-D855_PT7284
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
,I/jxcore-log( 2931): 2015-12-03T14:49:01.376Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): --DoOneRunRound ended
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418524c rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
,I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTListenerThread( 2931): got MESSAGE_READ 84 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT2572"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT2572
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT2572
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa41855dc rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2931): 2015-12-03T14:49:01.728Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
,I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/jxcore-log( 2931): 2015-12-03T14:49:01.941Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:01.944Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:02.003Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:02.013Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:02.392Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:02.403Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:02.413Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:02.435Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:02.466Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:02.507Z SendDataTCPServer.js: TCP/IP server has received 24576 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:02.546Z SendDataTCPServer.js: TCP/IP server has received 26556 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:02.589Z SendDataTCPServer.js: TCP/IP server has received 34476 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:02.601Z SendDataTCPServer.js: TCP/IP server has received 38436 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:02.637Z SendDataTCPServer.js: TCP/IP server has received 44376 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:02.647Z SendDataTCPServer.js: TCP/IP server has received 46356 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:02.693Z SendDataTCPServer.js: TCP/IP server has received 48336 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:02.702Z SendDataTCPServer.js: TCP/IP server has received 50316 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:02.759Z SendDataTCPServer.js: TCP/IP server has received 52296 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:02.796Z SendDataTCPServer.js: TCP/IP server has received 60216 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:02.868Z SendDataTCPServer.js: TCP/IP server has received 62196 bytes of data
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): invalid rfc slot id: 19
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT4731
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2931): 2015-12-03T14:49:02.923Z SendDataTCPServer.js: TCP/IP server has received 70116 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:02.935Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:02.941Z SendDataTCPServer.js: TCP/IP server has received 72096 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:02.998Z SendDataTCPServer.js: TCP/IP server has received 74076 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:03.007Z SendDataTCPServer.js: TCP/IP server has received 76056 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:03.011Z SendDataTCPServer.js: TCP/IP server has received 78036 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:03.072Z SendDataTCPServer.js: TCP/IP server has received 80016 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:03.083Z SendDataTCPServer.js: TCP/IP server has received 81996 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:03.117Z SendDataTCPServer.js: TCP/IP server has received 85956 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:03.146Z SendDataTCPServer.js: TCP/IP server has received 87936 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:03.185Z SendDataTCPServer.js: TCP/IP server has received 89916 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:03.192Z SendDataTCPServer.js: TCP/IP server has received 91896 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:03.204Z SendDataTCPServer.js: TCP/IP server has received 93876 bytes of data
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa41855dc rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x45
,I/jxcore-log( 2931): 2015-12-03T14:49:03.245Z SendDataTCPServer.js: TCP/IP server has received 95856 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:03.258Z SendDataTCPServer.js: TCP/IP server has received 99816 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:03.292Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa41855dc rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2931): 2015-12-03T14:49:05.875Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:49:05.876Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:49:05.877Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:05.894Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:49:05.894Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:49:05.895Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/BtConnectorHelper( 2931): Disconnect outgoing peer: B0:C5:59:3F:75:69
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
,I/BtToSocketBase( 2931): Close bt in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
I/BtToRequestSocket( 2931): Close server socket
,I/jxcore-log( 2931): 2015-12-03T14:49:05.931Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 2931): 
I/jxcore-log( 2931): ---- round done--------
I/jxcore-log( 2931): 
I/jxcore-log( 2931): ---- gotta redo : B0:C5:59:3F:75:69, try count now: 1
I/jxcore-log( 2931): 
I/jxcore-log( 2931): do fake peer & start
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:05.938Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:05.940Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:49:05.945Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: 08:EC:A9:50:75:41, name: A3-1
,I/        ( 2931): Connecting to A3-1, at 08:EC:A9:50:75:41
,I/jxcore-log( 2931): 2015-12-03T14:49:05.968Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2931): 
,I/chromium( 2931): [INFO:CONSOLE(63)] "logCallback Round of send data to peer B0:C5:59:3F:75:69 done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3006): bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [08:ec:a9:50:75:41]: 0, 0, 0
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: A3-1
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa41855dc rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3006): process_service_search_attr_rsp
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa41855dc rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: HTC Desire 820
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2931): Starting to Handshake
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2931): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTConnectToThread( 2931): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 2931): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2317","ra":"08:EC:A9:50:75:41"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2931): HandshakeOk : samsung-SM-A300FU_PT2317
I/HS      ( 2931): Hand Shake finished outgoing for : samsung-SM-A300FU_PT2317
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : false, samsung-SM-A300FU_PT2317
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2931): mHTTPPort  set to : 54776
I/BtConnectorHelper( 2931): Request socket is using : 54776
I/BtToRequestSocket( 2931): Now accepting connections
,I/BtConnectorHelper( 2931): Calling ConnectionStatusUpdate with port :54776
I/jxcore-log( 2931): 2015-12-03T14:49:07.770Z SendDataConnector.js: CLIENT connected to 54776, error: null
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:49:07.770Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): incoming data from: /127.0.0.1, port: 54776
I/BtToRequestSocket( 2931): Set local streams
,I/BtToRequestSocket( 2931): rin ended ---------------------------;
,I/jxcore-log( 2931): 2015-12-03T14:49:07.795Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185084 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,D/        ( 3006): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 2931): 2015-12-03T14:49:08.515Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418524c rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2931): 2015-12-03T14:49:08.682Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2931): 
,D/        ( 3006): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13816
,I/jxcore-log( 2931): 2015-12-03T14:49:09.029Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:09.106Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2931): 
,D/        ( 3006): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 2931): 2015-12-03T14:49:09.201Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:09.454Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2931): 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2931): 2015-12-03T14:49:09.707Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2931): 
,I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/jxcore-log( 2931): 2015-12-03T14:49:10.244Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:10.774Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Thali Test (Galaxy S5)
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185084 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): invalid rfc slot id: 21
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D855_PT7284
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2931): 2015-12-03T14:49:12.370Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185084 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): invalid rfc slot id: 22
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT2572
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2931): 2015-12-03T14:49:13.367Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x47
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185084 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: HTC Desire 820
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x4a
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTListenerThread( 2931): got MESSAGE_READ 84 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT4731"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT4731
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT4731
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/jxcore-log( 2931): 2015-12-03T14:49:15.491Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
,I/BtToRequestSocket( 2931): --DoOneRunRound ended
,W/bt-btif ( 3006): dm_pm_timer expires
W/bt-btif ( 3006): dm_pm_timer expires 0
W/bt-btif ( 3006): proc dm_pm_timer expires
,I/jxcore-log( 2931): 2015-12-03T14:49:15.929Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:15.936Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185084 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2931): 2015-12-03T14:49:16.003Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:16.011Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:16.019Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:16.081Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data,
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa41857a4 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: HTC Desire 820
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: G3-1
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185084 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2931): 2015-12-03T14:49:20.773Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:49:20.774Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:49:20.777Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:49:20.778Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:49:20.779Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2931): 
,I/BtToSocketBase( 2931): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2931): Disconnect outgoing peer: samsung-SM-A300FU_PT2317
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
,I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToRequestSocket( 2931): Close server socket
,W/bt-btif ( 3006): bta_jv_rfc_port_to_cb(port_handle:0x19):jv handle:0x0 not FOUND
,I/jxcore-log( 2931): 2015-12-03T14:49:25.778Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:49:25.779Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): invalid rfc slot id: 23
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT4731
,I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT4731
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/jxcore-log( 2931): 2015-12-03T14:49:26.375Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x4f current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x4f
,I/jxcore-log( 2931): 2015-12-03T14:49:30.783Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:49:30.786Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:49:30.787Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:49:30.788Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: 08:EC:A9:50:75:41, name: A3-1
,I/        ( 2931): Connecting to A3-1, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185084 rs_disc_pending=1
E/bt-btif ( 3006): DISCOVERY_COMP_EVT slot id:26, failed to find channle,                                       status:1, scn:0
E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): invalid rfc slot id: 26
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 2931): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2931): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2931): 2015-12-03T14:49:31.486Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:49:31.487Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:49:31.488Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: A3-1
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 2931): 2015-12-03T14:49:36.489Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:49:36.490Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: HTC Desire 820
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa41855dc rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTListenerThread( 2931): got MESSAGE_READ 84 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT4731"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT4731
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT4731
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/jxcore-log( 2931): 2015-12-03T14:49:37.801Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/jxcore-log( 2931): 2015-12-03T14:49:38.307Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:38.323Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:38.329Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:38.336Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:38.343Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:38.367Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2931): 2015-12-03T14:49:41.495Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:49:41.495Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:49:41.496Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:49:41.496Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: 08:EC:A9:50:75:41, name: A3-1
,I/        ( 2931): Connecting to A3-1, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa41855dc rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3006): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 3006): DISCOVERY_COMP_EVT slot id:28, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3006): invalid rfc slot id: 28
,I/BTConnectToThread( 2931): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2931): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2931): 2015-12-03T14:49:46.864Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:49:46.865Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:49:46.866Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): invalid rfc slot id: 25
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT4731
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2931): 2015-12-03T14:49:48.378Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x40 current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x40
,I/        ( 2931): Cleared service requests
I/        ( 2931): Started peer discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2931): 2015-12-03T14:49:51.867Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:49:51.892Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2931): 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524],
I/BluetoothClassifier( 1352): Bluetooth Device Name: HTC Desire 820
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2931): Found 4 peers.
I/SS      ( 2931): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2931): Peer(2): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2931): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2931): Peer(4): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 2931): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2931): Added service request
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2931): Started service discovery
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2931): 2015-12-03T14:49:56.897Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:49:56.898Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:49:56.899Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:49:56.899Z SendDataConnector.js: do connect now,
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: 08:EC:A9:50:75:41, name: A3-1
,I/        ( 2931): Connecting to A3-1, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-sdp  ( 3006): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 3006): DISCOVERY_COMP_EVT slot id:29, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3006): invalid rfc slot id: 29
,I/BTConnectToThread( 2931): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2931): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2931): 2015-12-03T14:50:02.074Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:50:02.075Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:50:02.076Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:07.077Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:50:07.077Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2931): 
,I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,I/jxcore-log( 2931): 2015-12-03T14:50:12.080Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:50:12.081Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:50:12.082Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:50:12.082Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: 08:EC:A9:50:75:41, name: A3-1
,I/        ( 2931): Connecting to A3-1, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: HTC Desire 820
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa41857a4 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTListenerThread( 2931): got MESSAGE_READ 84 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT2572"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT2572
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT2572
,I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
,I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/jxcore-log( 2931): 2015-12-03T14:50:13.528Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
,I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/jxcore-log( 2931): 2015-12-03T14:50:13.901Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:14.056Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:14.203Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:14.290Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:14.438Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:14.506Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-sdp  ( 3006): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
E/bt-btif ( 3006): DISCOVERY_COMP_EVT slot id:30, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3006): invalid rfc slot id: 30
I/BTConnectToThread( 2931): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2931): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2931): 2015-12-03T14:50:17.255Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:50:17.255Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:17.257Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:50:17.257Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:50:17.258Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 2931): 
I/jxcore-log( 2931): ---- round done--------
I/jxcore-log( 2931): 
I/jxcore-log( 2931): ---- gotta redo : 08:EC:A9:50:75:41, try count now: 1
I/jxcore-log( 2931): 
I/jxcore-log( 2931): do fake peer & start
I/jxcore-log( 2931): 
I/jxcore-log( 2931): Connect to fake peer: 7C:F9:0E:37:96:AB
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:50:17.258Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:50:17.258Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:50:17.258Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/        ( 2931): Connecting to null, at 7C:F9:0E:37:96:AB
,I/chromium( 2931): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 08:EC:A9:50:75:41 done with result: Connection to 08:EC:A9:50:75:41 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa41857a4 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3006): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418596c rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3006): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
E/bt-btif ( 3006): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3006): Entering PendingCommandState State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothAdapterProperties( 3006): Failed to remove device: 7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3006): StableState(): Entering Off State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2931): Starting to Handshake
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2931): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTConnectToThread( 2931): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 2931): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2273","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2931): HandshakeOk : samsung-SM-A500FU_PT2273
I/HS      ( 2931): Hand Shake finished outgoing for : samsung-SM-A500FU_PT2273
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : false, samsung-SM-A500FU_PT2273
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2931): mHTTPPort  set to : 46728
I/BtConnectorHelper( 2931): Request socket is using : 46728
I/BtToRequestSocket( 2931): Now accepting connections
,I/BtConnectorHelper( 2931): Calling ConnectionStatusUpdate with port :46728
,I/jxcore-log( 2931): 2015-12-03T14:50:24.197Z SendDataConnector.js: CLIENT connected to 46728, error: null
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:50:24.198Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): incoming data from: /127.0.0.1, port: 46728
I/BtToRequestSocket( 2931): Set local streams
I/BtToRequestSocket( 2931): rin ended ---------------------------;
,I/jxcore-log( 2931): 2015-12-03T14:50:24.222Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): invalid rfc slot id: 27
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT2572
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2931): 2015-12-03T14:50:24.640Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,D/        ( 3006): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 2931): 2015-12-03T14:50:24.804Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:24.887Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2931): 
,D/        ( 3006): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12826
,I/jxcore-log( 2931): 2015-12-03T14:50:24.972Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:25.050Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2931): 
,D/        ( 3006): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 2931): 2015-12-03T14:50:25.061Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:25.133Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:25.222Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:25.328Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:25.331Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2931): 
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x4b
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: HTC Desire 820
,W/bt-btif ( 3006): dm_pm_timer expires
W/bt-btif ( 3006): dm_pm_timer expires 0
W/bt-btif ( 3006): proc dm_pm_timer expires
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 2931): 2015-12-03T14:50:35.330Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:50:35.330Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:50:35.330Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:50:35.331Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:50:35.331Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2931): 
,I/BtToSocketBase( 2931): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2931): Disconnect outgoing peer: samsung-SM-A500FU_PT2273
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
I/BtToRequestSocket( 2931): Close server socket
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa41857a4 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): bta_jv_rfc_port_to_cb(port_handle:0x1d):jv handle:0x0 not FOUND
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa41857a4 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2931): got MESSAGE_READ 84 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT2572"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT2572
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT2572
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
,I/jxcore-log( 2931): 2015-12-03T14:50:35.868Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/jxcore-log( 2931): 2015-12-03T14:50:36.248Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:36.258Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:36.270Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 3006): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa41857a4 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185b34 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
E/bt-btif ( 3006): check_cod: remote_cod = 0x5a020c
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418596c rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3006): Entering PendingCommandState State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 3006): Failed to remove device: E0:DB:10:14:E2:C0
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3006): StableState(): Entering Off State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.
,I/jxcore-log( 2931): 2015-12-03T14:50:40.332Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:50:40.332Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418596c rs_disc_pending=1
,W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: A5-1
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185b34 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2931): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1345","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : samsung-SM-N910C_PT1345
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, samsung-SM-N910C_PT1345
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/jxcore-log( 2931): 2015-12-03T14:50:41.453Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:42.169Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:42.225Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:42.278Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:42.376Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:42.493Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:42.508Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:42.690Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:42.727Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:42.787Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:42.889Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:42.995Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:43.148Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:43.489Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:43.497Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:43.517Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:43.525Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:43.539Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:43.584Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:43.664Z SendDataTCPServer.js: TCP/IP server has received 40960 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:43.670Z SendDataTCPServer.js: TCP/IP server has received 42940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:43.704Z SendDataTCPServer.js: TCP/IP server has received 48880 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:43.713Z SendDataTCPServer.js: TCP/IP server has received 50860 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:43.720Z SendDataTCPServer.js: TCP/IP server has received 52840 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:43.754Z SendDataTCPServer.js: TCP/IP server has received 54820 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:43.802Z SendDataTCPServer.js: TCP/IP server has received 56800 bytes of data
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185b34 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2931): 2015-12-03T14:50:44.538Z SendDataTCPServer.js: TCP/IP server has received 58780 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:44.543Z SendDataTCPServer.js: TCP/IP server has received 60760 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:44.594Z SendDataTCPServer.js: TCP/IP server has received 62740 bytes of data
I/jxcore-log( 2931): 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2931): 2015-12-03T14:50:44.650Z SendDataTCPServer.js: TCP/IP server has received 64720 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:44.664Z SendDataTCPServer.js: TCP/IP server has received 72640 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:44.679Z SendDataTCPServer.js: TCP/IP server has received 74620 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:44.714Z SendDataTCPServer.js: TCP/IP server has received 88480 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:44.717Z SendDataTCPServer.js: TCP/IP server has received 90460 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:44.718Z SendDataTCPServer.js: TCP/IP server has received 92440 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:44.722Z SendDataTCPServer.js: TCP/IP server has received 94420 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:44.755Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:50:45.337Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:50:45.338Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:50:45.339Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:50:45.339Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 2931): Connecting to A5-1, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185b34 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): invalid rfc slot id: 31
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT2572
,I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT2572
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/jxcore-log( 2931): 2015-12-03T14:50:46.809Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa41857a4 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x47
,W/bt-sdp  ( 3006): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 3006): DISCOVERY_COMP_EVT slot id:35, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3006): invalid rfc slot id: 35
,I/BTConnectToThread( 2931): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2931): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2931): 2015-12-03T14:50:50.896Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:50:50.896Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:50:50.897Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: HTC Desire 820
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185b34 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/        ( 2931): Cleared service requests
I/        ( 2931): Started peer discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2931): Found 7 peers.
,I/SS      ( 2931): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2931): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2931): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2931): Peer(4): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 2931): Peer(5): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 2931): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2931): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2931): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2931): Added service request
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,W/bt-btif ( 3006): invalid rfc slot id: 33
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N910C_PT1345
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x4e current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x4e
,I/jxcore-log( 2931): 2015-12-03T14:50:54.834Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,I/        ( 2931): Started service discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2931): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT6494"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT6494"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT6494, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT6494, WifiDirectName: , WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/jxcore-log( 2931): 2015-12-03T14:50:55.899Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:50:55.899Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Note4-1
,I/jxcore-log( 2931): 2015-12-03T14:51:00.903Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:00.906Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:00.909Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:00.910Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 2931): Connecting to A5-1, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 3006): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185cfc rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: A5-1
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185cfc rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418596c rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3006): process_service_search_attr_rsp
,I/        ( 2931): Cleared service requests
I/        ( 2931): Started peer discovery
,I/BTConnectToThread( 2931): Starting to Handshake
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2931): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTConnectToThread( 2931): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 2931): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2273","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2931): HandshakeOk : samsung-SM-A500FU_PT2273
I/HS      ( 2931): Hand Shake finished outgoing for : samsung-SM-A500FU_PT2273
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : false, samsung-SM-A500FU_PT2273
,I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2931): mHTTPPort  set to : 59919
I/BtConnectorHelper( 2931): Request socket is using : 59919
I/BtToRequestSocket( 2931): Now accepting connections
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BtConnectorHelper( 2931): Calling ConnectionStatusUpdate with port :59919
,I/jxcore-log( 2931): 2015-12-03T14:51:05.006Z SendDataConnector.js: CLIENT connected to 59919, error: null
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:51:05.007Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): incoming data from: /127.0.0.1, port: 59919
I/BtToRequestSocket( 2931): Set local streams
I/BtToRequestSocket( 2931): rin ended ---------------------------;
,I/jxcore-log( 2931): 2015-12-03T14:51:05.029Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2931): 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2931): Found 9 peers.
I/SS      ( 2931): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2931): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2931): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2931): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2931): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2931): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2931): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2931): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2931): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2931): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2931): Added service request
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 3006): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3006): Entering PendingCommandState State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3006): Failed to remove device: F8:95:C7:87:85:54
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3006): StableState(): Entering Off State
,E/BluetoothEventManager( 3038): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/BTListenerThread( 2931): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6666","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : LGE-LG-D722_PT6666
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, LGE-LG-D722_PT6666
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
,I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/jxcore-log( 2931): 2015-12-03T14:51:06.162Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/        ( 2931): Started service discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/jxcore-log( 2931): 2015-12-03T14:51:07.075Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:07.463Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:07.521Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:07.659Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:07.728Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:07.737Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:07.790Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:07.966Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:08.016Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:08.059Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:08.069Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:08.113Z SendDataTCPServer.js: TCP/IP server has received 24576 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:08.145Z SendDataTCPServer.js: TCP/IP server has received 26556 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:08.248Z SendDataTCPServer.js: TCP/IP server has received 28536 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:08.281Z SendDataTCPServer.js: TCP/IP server has received 30516 bytes of data
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,I/jxcore-log( 2931): 2015-12-03T14:51:08.375Z SendDataTCPServer.js: TCP/IP server has received 32496 bytes of data
I/jxcore-log( 2931): 
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Note4-1
,I/jxcore-log( 2931): 2015-12-03T14:51:08.506Z SendDataTCPServer.js: TCP/IP server has received 34476 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:08.509Z SendDataTCPServer.js: TCP/IP server has received 36456 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:08.512Z SendDataTCPServer.js: TCP/IP server has received 38436 bytes of data
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185b34 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2931): 2015-12-03T14:51:08.548Z SendDataTCPServer.js: TCP/IP server has received 40416 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:08.551Z SendDataTCPServer.js: TCP/IP server has received 42396 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:08.607Z SendDataTCPServer.js: TCP/IP server has received 44376 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:08.672Z SendDataTCPServer.js: TCP/IP server has received 46356 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:08.682Z SendDataTCPServer.js: TCP/IP server has received 50316 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:08.696Z SendDataTCPServer.js: TCP/IP server has received 52296 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:08.748Z SendDataTCPServer.js: TCP/IP server has received 54276 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:08.803Z SendDataTCPServer.js: TCP/IP server has received 56256 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:08.882Z SendDataTCPServer.js: TCP/IP server has received 58236 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:09.132Z SendDataTCPServer.js: TCP/IP server has received 60216 bytes of data
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
,I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/jxcore-log( 2931): 2015-12-03T14:51:09.306Z SendDataTCPServer.js: TCP/IP server has received 62196 bytes of data
I/jxcore-log( 2931): 
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/jxcore-log( 2931): 2015-12-03T14:51:09.358Z SendDataTCPServer.js: TCP/IP server has received 64176 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:09.365Z SendDataTCPServer.js: TCP/IP server has received 66156 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:09.371Z SendDataTCPServer.js: TCP/IP server has received 68136 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:09.427Z SendDataTCPServer.js: TCP/IP server has received 70116 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:09.439Z SendDataTCPServer.js: TCP/IP server has received 72096 bytes of data
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185b34 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2931): 2015-12-03T14:51:09.487Z SendDataTCPServer.js: TCP/IP server has received 74076 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:09.502Z SendDataTCPServer.js: TCP/IP server has received 80016 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:09.535Z SendDataTCPServer.js: TCP/IP server has received 81996 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:09.566Z SendDataTCPServer.js: TCP/IP server has received 83976 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:09.587Z SendDataTCPServer.js: TCP/IP server has received 85956 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:09.602Z SendDataTCPServer.js: TCP/IP server has received 91896 bytes of data
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185b34 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2931): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1345","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : samsung-SM-N910C_PT1345
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/jxcore-log( 2931): 2015-12-03T14:51:09.799Z SendDataTCPServer.js: TCP/IP server has received 93876 bytes of data
I/jxcore-log( 2931): 
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, samsung-SM-N910C_PT1345
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/jxcore-log( 2931): 2015-12-03T14:51:09.804Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
,I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/jxcore-log( 2931): 2015-12-03T14:51:09.807Z SendDataTCPServer.js: TCP/IP server has received 95856 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:09.891Z SendDataTCPServer.js: TCP/IP server has received 97836 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:09.952Z SendDataTCPServer.js: TCP/IP server has received 99816 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:09.953Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): dm_pm_timer expires
W/bt-btif ( 3006): dm_pm_timer expires 0
W/bt-btif ( 3006): proc dm_pm_timer expires
,I/jxcore-log( 2931): 2015-12-03T14:51:10.427Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:10.449Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:10.505Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:10.755Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:10.803Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:10.873Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2931): 2015-12-03T14:51:15.108Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:51:15.108Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:51:15.110Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:51:15.110Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:51:15.111Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2931): 
,I/BtToSocketBase( 2931): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2931): Disconnect outgoing peer: samsung-SM-A500FU_PT2273
I/BtToSocketBase( 2931): Stop ReceivingThread
,I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
,I/BtToSocketBase( 2931): Close bt in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2931): Close bt out
,I/BtToSocketBase( 2931): Close bt socket
,I/BtToRequestSocket( 2931): Close server socket
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185b34 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185cfc rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418596c rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): bta_jv_rfc_port_to_cb(port_handle:0x7):jv handle:0x0 not FOUND
,W/bt-btif ( 3006): invalid rfc slot id: 34
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT6666
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2931): 2015-12-03T14:51:19.921Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:20.111Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:51:20.112Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: A5-1
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185b34 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): invalid rfc slot id: 37
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N910C_PT1345
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2931): 2015-12-03T14:51:21.799Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x48
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185cfc rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2931): 2015-12-03T14:51:25.116Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:51:25.116Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:51:25.117Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:51:25.118Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 2931): Connecting to A5-1, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Note4-1
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: G3s-1
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [7c:f9:0e:37:96:ab]: 6, f, 410d
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: A5-1
,W/bt-sdp  ( 3006): process_service_search_attr_rsp
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2931): Starting to Handshake
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2931): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTConnectToThread( 2931): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 2931): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2273","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2931): HandshakeOk : samsung-SM-A500FU_PT2273
I/HS      ( 2931): Hand Shake finished outgoing for : samsung-SM-A500FU_PT2273
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : false, samsung-SM-A500FU_PT2273
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2931): mHTTPPort  set to : 53141
I/BtConnectorHelper( 2931): Request socket is using : 53141
I/BtToRequestSocket( 2931): Now accepting connections
,I/BtConnectorHelper( 2931): Calling ConnectionStatusUpdate with port :53141
I/jxcore-log( 2931): 2015-12-03T14:51:28.956Z SendDataConnector.js: CLIENT connected to 53141, error: null
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:51:28.957Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): incoming data from: /127.0.0.1, port: 53141
I/BtToRequestSocket( 2931): Set local streams
I/BtToRequestSocket( 2931): rin ended ---------------------------;
,I/jxcore-log( 2931): 2015-12-03T14:51:28.979Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [f8:95:c7:87:85:54]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: G3s-1
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418596c rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Note4-1
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418596c rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTListenerThread( 2931): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1345","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : samsung-SM-N910C_PT1345
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, samsung-SM-N910C_PT1345
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
,I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/jxcore-log( 2931): 2015-12-03T14:51:32.519Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
,I/BtToRequestSocket( 2931): --DoOneRunRound ended
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185cfc rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2931): 2015-12-03T14:51:32.955Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:32.963Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:33.020Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:33.032Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:33.093Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:33.102Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): dm_pm_timer expires
W/bt-btif ( 3006): dm_pm_timer expires 0
W/bt-btif ( 3006): proc dm_pm_timer expires
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 3006): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3006): Entering PendingCommandState State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3006): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3006): StableState(): Entering Off State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185cfc rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2931): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6666","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : LGE-LG-D722_PT6666
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, LGE-LG-D722_PT6666
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/jxcore-log( 2931): 2015-12-03T14:51:35.477Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
,I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/jxcore-log( 2931): 2015-12-03T14:51:35.905Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:35.941Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:35.952Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:51:35.955Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:39.051Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:51:39.052Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:51:39.053Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:39.053Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:39.062Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2931): 
,I/BtToSocketBase( 2931): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2931): Disconnect outgoing peer: samsung-SM-A500FU_PT2273
,I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
,I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
I/BtToRequestSocket( 2931): Close server socket
,W/bt-btif ( 3006): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3006): invalid rfc slot id: 38
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N910C_PT1345
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N910C_PT1345
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/jxcore-log( 2931): 2015-12-03T14:51:43.056Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:44.060Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:51:44.060Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2931): 
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x4a
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: A5-1
,W/bt-btif ( 3006): invalid rfc slot id: 40
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT6666
I/BtToSocketBase( 2931): Stop ReceivingThread
,I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT6666
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/jxcore-log( 2931): 2015-12-03T14:51:46.056Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x47
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Note4-1
,I/jxcore-log( 2931): 2015-12-03T14:51:49.063Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:51:49.066Z SendDataConnector.js: Connect (retry count 4) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:51:49.066Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:51:49.067Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 2931): Connecting to A5-1, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,W/bt-sdp  ( 3006): process_service_search_attr_rsp
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: A5-1
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2931): Starting to Handshake
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2931): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTConnectToThread( 2931): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 2931): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2273","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2931): HandshakeOk : samsung-SM-A500FU_PT2273
I/HS      ( 2931): Hand Shake finished outgoing for : samsung-SM-A500FU_PT2273
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : false, samsung-SM-A500FU_PT2273
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2931): mHTTPPort  set to : 52543
I/BtConnectorHelper( 2931): Request socket is using : 52543
I/BtToRequestSocket( 2931): Now accepting connections
,I/BtConnectorHelper( 2931): Calling ConnectionStatusUpdate with port :52543
I/jxcore-log( 2931): 2015-12-03T14:51:49.802Z SendDataConnector.js: CLIENT connected to 52543, error: null
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:51:49.803Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): incoming data from: /127.0.0.1, port: 52543
I/BtToRequestSocket( 2931): Set local streams
I/BtToRequestSocket( 2931): rin ended ---------------------------;
,I/jxcore-log( 2931): 2015-12-03T14:51:49.815Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418596c rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: G3s-1
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [e0:db:10:14:e2:c0]: 6, f, 410d
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Note4-1
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418596c rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTListenerThread( 2931): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1345","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : samsung-SM-N910C_PT1345
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, samsung-SM-N910C_PT1345
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
,I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/jxcore-log( 2931): 2015-12-03T14:51:54.747Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
,I/BtToRequestSocket( 2931): --DoOneRunRound ended
,W/bt-btif ( 3006): dm_pm_timer expires
W/bt-btif ( 3006): dm_pm_timer expires 0
W/bt-btif ( 3006): proc dm_pm_timer expires
,I/jxcore-log( 2931): 2015-12-03T14:51:55.179Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:55.182Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:55.186Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:55.190Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:55.191Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:55.196Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [f8:95:c7:87:85:54]: 7, f, 2205
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: G3s-1
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185cfc rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 3006): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3006): Entering PendingCommandState State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3006): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3006): StableState(): Entering Off State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/jxcore-log( 2931): 2015-12-03T14:51:59.850Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:51:59.850Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:51:59.850Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:59.853Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:59.853Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:51:59.853Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
,I/BtConnectorHelper( 2931): Disconnect outgoing peer: 7C:F9:0E:37:96:AB
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2931): Close LocalOutputStream
,I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
I/BtToRequestSocket( 2931): Close server socket
I/jxcore-log( 2931): 2015-12-03T14:51:59.884Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2931): 
I/jxcore-log( 2931): ---- round done--------
I/jxcore-log( 2931): 
I/jxcore-log( 2931): ---- gotta redo : 7C:F9:0E:37:96:AB, try count now: 1
I/jxcore-log( 2931): 
I/jxcore-log( 2931): do fake peer & start
I/jxcore-log( 2931): 
I/jxcore-log( 2931): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:51:59.890Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:51:59.896Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:51:59.898Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 2931): Connecting to Note4-1, at E0:DB:10:14:E2:C0
I/jxcore-log( 2931): 2015-12-03T14:51:59.911Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2931): 
,I/chromium( 2931): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 7C:F9:0E:37:96:AB done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185cfc rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2931): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6666","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : LGE-LG-D722_PT6666
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, LGE-LG-D722_PT6666
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/jxcore-log( 2931): 2015-12-03T14:51:59.986Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3006): process_service_search_attr_rsp
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2931): Starting to Handshake
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2931): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTConnectToThread( 2931): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 2931): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1345","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2931): HandshakeOk : samsung-SM-N910C_PT1345
I/HS      ( 2931): Hand Shake finished outgoing for : samsung-SM-N910C_PT1345
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : false, samsung-SM-N910C_PT1345
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2931): mHTTPPort  set to : 59075
I/BtConnectorHelper( 2931): Request socket is using : 59075
I/BtToRequestSocket( 2931): Now accepting connections
,I/BtConnectorHelper( 2931): Calling ConnectionStatusUpdate with port :59075
I/jxcore-log( 2931): 2015-12-03T14:52:00.408Z SendDataConnector.js: CLIENT connected to 59075, error: null
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:52:00.408Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): incoming data from: /127.0.0.1, port: 59075
I/BtToRequestSocket( 2931): Set local streams
I/BtToRequestSocket( 2931): rin ended ---------------------------;
,I/jxcore-log( 2931): 2015-12-03T14:52:00.411Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418596c rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2931): 2015-12-03T14:52:00.868Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:00.954Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:01.056Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:01.063Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:01.152Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:01.235Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:01.319Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:01.399Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:01.470Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:01.593Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:01.656Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:01.777Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:01.789Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2931): 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185cfc rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: A5-1
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185cfc rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): invalid rfc slot id: 41
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N910C_PT1345
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2931): 2015-12-03T14:52:05.195Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,I/        ( 2931): Cleared service requests
I/        ( 2931): Started peer discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2931): Found 11 peers.
I/SS      ( 2931): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2931): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2931): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2931): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2931): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2931): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2931): Peer(7): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2931): Peer(8): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2931): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2931): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2931): Peer(11): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2931): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2931): Added service request
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 2931): Started service discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 2931): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6802","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6802","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT6802, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT6802, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,W/bt-btif ( 3006): dm_pm_timer expires
W/bt-btif ( 3006): dm_pm_timer expires 1
W/bt-btif ( 3006): proc dm_pm_timer expires
,I/        ( 2931): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1345","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1345","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT1345, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT1345, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,W/bt-btif ( 3006): invalid rfc slot id: 43
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT6666
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
,I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/art     (  761): Explicit concurrent mark sweep GC freed 38939(1745KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 991us total 91.052ms
,I/jxcore-log( 2931): 2015-12-03T14:52:11.075Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:11.789Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:52:11.790Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:52:11.791Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:52:11.791Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:52:11.792Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2931): 
,I/BtToSocketBase( 2931): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2931): Disconnect outgoing peer: samsung-SM-N910C_PT1345
I/BtToSocketBase( 2931): Stop ReceivingThread
,I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
,I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
I/BtToRequestSocket( 2931): Close server socket
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x46
,W/bt-btif ( 3006): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185cfc rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: G3s-1
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTListenerThread( 2931): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1345","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : samsung-SM-N910C_PT1345
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, samsung-SM-N910C_PT1345
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
,I/jxcore-log( 2931): 2015-12-03T14:52:15.899Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,I/jxcore-log( 2931): 2015-12-03T14:52:16.328Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:16.332Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:16.339Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:16.427Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:16.435Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:16.792Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:52:16.793Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2931): 
,I/        ( 2931): Cleared service requests
,I/        ( 2931): Started peer discovery
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [f8:95:c7:87:85:54]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: G3s-1,
,I/jxcore-log( 2931): 2015-12-03T14:52:21.794Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:52:21.794Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:52:21.794Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:52:21.794Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 2931): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185cfc rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 3006): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3006): Entering PendingCommandState State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3006): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3006): StableState(): Entering Off State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185cfc rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2931): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6666","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : LGE-LG-D722_PT6666
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, LGE-LG-D722_PT6666
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/jxcore-log( 2931): 2015-12-03T14:52:22.616Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
,I/BtToRequestSocket( 2931): --DoOneRunRound ended
,W/bt-sdp  ( 3006): process_service_search_attr_rsp
,I/jxcore-log( 2931): 2015-12-03T14:52:23.050Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:23.065Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:1
,I/BTConnectToThread( 2931): Starting to Handshake
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2931): MESSAGE_WRITE 77 bytes.
,I/jxcore-log( 2931): 2015-12-03T14:52:23.092Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BTConnectToThread( 2931): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 2931): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1345","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2931): HandshakeOk : samsung-SM-N910C_PT1345
I/HS      ( 2931): Hand Shake finished outgoing for : samsung-SM-N910C_PT1345
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : false, samsung-SM-N910C_PT1345
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2931): mHTTPPort  set to : 41785
I/BtConnectorHelper( 2931): Request socket is using : 41785
I/BtToRequestSocket( 2931): Now accepting connections
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 2931): Found 6 peers.
I/SS      ( 2931): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2931): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2931): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2931): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2931): Peer(5): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 2931): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2931): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2931): Added service request
,I/BtConnectorHelper( 2931): Calling ConnectionStatusUpdate with port :41785
I/jxcore-log( 2931): 2015-12-03T14:52:23.699Z SendDataConnector.js: CLIENT connected to 41785, error: null
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:52:23.700Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): incoming data from: /127.0.0.1, port: 41785
I/BtToRequestSocket( 2931): Set local streams
I/BtToRequestSocket( 2931): rin ended ---------------------------;
,I/jxcore-log( 2931): 2015-12-03T14:52:23.720Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2931): 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2931): Started service discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3006): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185ec4 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): invalid rfc slot id: 44
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N910C_PT1345
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2931): 2015-12-03T14:52:26.417Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185cfc rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
E/bt-btif ( 3006): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3006): Entering PendingCommandState State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185b34 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 3006): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3006): StableState(): Entering Off State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
,I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTListenerThread( 2931): got MESSAGE_READ 81 bytes.
,I/BTListenerThread( 2931): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8266","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : motorola-XT1072_PT8266
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, motorola-XT1072_PT8266
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/jxcore-log( 2931): 2015-12-03T14:52:27.677Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
,I/BtToRequestSocket( 2931): --DoOneRunRound ended
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185b34 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185ec4 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2931): 2015-12-03T14:52:28.642Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:28.709Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:29.297Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:29.305Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:29.312Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:29.368Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:29.371Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:29.477Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:29.478Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:29.485Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:29.643Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:29.771Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:29.806Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:29.856Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:29.870Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:29.908Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:29.919Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:29.926Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:30.027Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:30.068Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:30.089Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:30.157Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:30.543Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:30.550Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 2931): 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2931): 2015-12-03T14:52:30.695Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): dm_pm_timer expires
W/bt-btif ( 3006): dm_pm_timer expires 1
,W/bt-btif ( 3006): proc dm_pm_timer expires
,I/jxcore-log( 2931): 2015-12-03T14:52:30.785Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:30.842Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:30.896Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:30.937Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:31.006Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:31.016Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:31.026Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185b34 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2931): 2015-12-03T14:52:31.147Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:31.156Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:31.164Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:31.182Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:31.198Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:31.236Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:31.310Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:31.373Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:31.422Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:31.459Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185cfc rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): invalid rfc slot id: 46
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT6666
,I/BtToSocketBase( 2931): Stop ReceivingThread
,I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT6666
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/jxcore-log( 2931): 2015-12-03T14:52:33.087Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x49
,I/jxcore-log( 2931): 2015-12-03T14:52:33.786Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:52:33.787Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:52:33.788Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:52:33.788Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:52:33.789Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2931): 
,I/BtToSocketBase( 2931): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2931): Disconnect outgoing peer: samsung-SM-N910C_PT1345
I/BtToSocketBase( 2931): Stop ReceivingThread
,I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
,I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
I/BtToRequestSocket( 2931): Close server socket
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185b34 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185cfc rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185b34 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: G3s-1
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185b34 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2931): 2015-12-03T14:52:38.789Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:52:38.790Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Note4-1
,W/bt-btif ( 3006): dm_pm_timer expires
W/bt-btif ( 3006): dm_pm_timer expires 1
W/bt-btif ( 3006): proc dm_pm_timer expires
,W/bt-btif ( 3006): invalid rfc slot id: 48
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT8266
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2931): 2015-12-03T14:52:42.301Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x4b
,I/jxcore-log( 2931): 2015-12-03T14:52:43.796Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:52:43.796Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:43.815Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:52:43.816Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 2931): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: G3s-1
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185cfc rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 3006): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3006): Entering PendingCommandState State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3006): Failed to remove device: F8:95:C7:87:85:54,
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3006): StableState(): Entering Off State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTListenerThread( 2931): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6666","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : LGE-LG-D722_PT6666
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, LGE-LG-D722_PT6666
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/jxcore-log( 2931): 2015-12-03T14:52:45.495Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
I/BtToRequestSocket( 2931): --DoOneRunRound ended
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Note4-1
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185cfc rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2931): 2015-12-03T14:52:46.099Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:46.106Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:46.180Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:52:46.185Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185b34 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3006): process_service_search_attr_rsp
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 2931): Starting to Handshake
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTConnectToThread( 2931): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BluetoothClassifier( 1352): Bluetooth Device Name: XT1072
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185b34 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185cfc rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 2931): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 2931): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1345","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2931): HandshakeOk : samsung-SM-N910C_PT1345
I/HS      ( 2931): Hand Shake finished outgoing for : samsung-SM-N910C_PT1345
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : false, samsung-SM-N910C_PT1345
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2931): mHTTPPort  set to : 41440
I/BtConnectorHelper( 2931): Request socket is using : 41440
I/BtToRequestSocket( 2931): Now accepting connections
,I/BtConnectorHelper( 2931): Calling ConnectionStatusUpdate with port :41440
I/jxcore-log( 2931): 2015-12-03T14:52:48.406Z SendDataConnector.js: CLIENT connected to 41440, error: null
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:52:48.406Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): incoming data from: /127.0.0.1, port: 41440
I/BtToRequestSocket( 2931): Set local streams
I/BtToRequestSocket( 2931): rin ended ---------------------------;
,I/jxcore-log( 2931): 2015-12-03T14:52:48.410Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2931): 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3006): dm_pm_timer expires
W/bt-btif ( 3006): dm_pm_timer expires 1
W/bt-btif ( 3006): proc dm_pm_timer expires
,W/bt-btif ( 3006): invalid rfc slot id: 49
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT6666
,I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
,I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT6666
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Close bt socket
,I/jxcore-log( 2931): 2015-12-03T14:52:56.427Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185cfc rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x4f current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x4f
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185cfc rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2931): 2015-12-03T14:52:58.445Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:52:58.446Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:52:58.447Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:52:58.448Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:52:58.449Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2931): 
,I/BtToSocketBase( 2931): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2931): Disconnect outgoing peer: samsung-SM-N910C_PT1345
I/BtToSocketBase( 2931): Stop ReceivingThread
,I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
,I/BtToSocketBase( 2931): Close bt in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2931): Close bt out
,I/BtToSocketBase( 2931): Close bt socket
I/BtToRequestSocket( 2931): Close server socket
,W/bt-btif ( 3006): bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185b34 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185cfc rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: G3s-1
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Note4-1
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [7c:f9:0e:37:96:ab]: 6, f, 410d
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: A5-1
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
,I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTListenerThread( 2931): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2273","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : samsung-SM-A500FU_PT2273
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, samsung-SM-A500FU_PT2273
,I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
,I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/jxcore-log( 2931): 2015-12-03T14:53:02.928Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
,I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/jxcore-log( 2931): 2015-12-03T14:53:03.448Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:53:03.448Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:03.700Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:03.707Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:03.747Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:03.780Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:03.785Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:03.792Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:03.805Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:03.837Z SendDataTCPServer.js: TCP/IP server has received 22052 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:03.850Z SendDataTCPServer.js: TCP/IP server has received 24032 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:03.886Z SendDataTCPServer.js: TCP/IP server has received 27992 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:03.897Z SendDataTCPServer.js: TCP/IP server has received 29972 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:03.907Z SendDataTCPServer.js: TCP/IP server has received 31952 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:03.918Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:03.957Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:03.979Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:04.016Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:04.052Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:04.088Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:04.099Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:04.136Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:04.143Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:04.150Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:04.162Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:04.201Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:04.207Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:04.213Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:04.223Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:04.256Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:04.283Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:04.288Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:04.305Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:04.349Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:04.356Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:04.362Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:04.369Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): dm_pm_timer expires
W/bt-btif ( 3006): dm_pm_timer expires 0
W/bt-btif ( 3006): proc dm_pm_timer expires
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2931): 2015-12-03T14:53:08.451Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:53:08.452Z SendDataConnector.js: Connect (retry count 3) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:53:08.452Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:53:08.453Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 2931): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Note4-1
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185b34 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3006): process_service_search_attr_rsp
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2931): Starting to Handshake
,I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2931): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTConnectToThread( 2931): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 2931): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1345","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2931): HandshakeOk : samsung-SM-N910C_PT1345
I/HS      ( 2931): Hand Shake finished outgoing for : samsung-SM-N910C_PT1345
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : false, samsung-SM-N910C_PT1345
,I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2931): mHTTPPort  set to : 60175
,I/BtConnectorHelper( 2931): Request socket is using : 60175
I/BtToRequestSocket( 2931): Now accepting connections
,I/BtConnectorHelper( 2931): Calling ConnectionStatusUpdate with port :60175
I/jxcore-log( 2931): 2015-12-03T14:53:11.790Z SendDataConnector.js: CLIENT connected to 60175, error: null
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:53:11.791Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): incoming data from: /127.0.0.1, port: 60175
I/BtToRequestSocket( 2931): Set local streams
I/BtToRequestSocket( 2931): rin ended ---------------------------;
,I/jxcore-log( 2931): 2015-12-03T14:53:11.810Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2931): 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3006): invalid rfc slot id: 51
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT2273
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT2273
I/BtToSocketBase( 2931): Close LocalOutputStream
,I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/jxcore-log( 2931): 2015-12-03T14:53:14.802Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x44
,I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,W/bt-btif ( 3006): dm_pm_timer expires
W/bt-btif ( 3006): dm_pm_timer expires 0
W/bt-btif ( 3006): proc dm_pm_timer expires
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: A5-1
,I/jxcore-log( 2931): 2015-12-03T14:53:21.870Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:53:21.871Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:53:21.872Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:53:21.872Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:21.873Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2931): 
,I/BtToSocketBase( 2931): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2931): Disconnect outgoing peer: samsung-SM-N910C_PT1345
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
,I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
I/BtToRequestSocket( 2931): Close server socket
,W/bt-btif ( 3006): bta_jv_rfc_port_to_cb(port_handle:0x18):jv handle:0x0 not FOUND
,I/        ( 2931): Cleared service requests
,I/        ( 2931): Started peer discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 2931): Found 6 peers.
I/SS      ( 2931): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2931): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2931): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2931): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2931): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2931): Peer(6): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2931): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2931): Added service request
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2931): Started service discovery
,I/        ( 2931): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT2572"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT2572"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT2572, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT2572, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Note4-1
,I/        ( 2931): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9611","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9611","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT9611, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT9611, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: A5-1
,I/jxcore-log( 2931): 2015-12-03T14:53:26.873Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:26.874Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTListenerThread( 2931): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2273","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : samsung-SM-A500FU_PT2273
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, samsung-SM-A500FU_PT2273
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
,I/jxcore-log( 2931): 2015-12-03T14:53:26.931Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/jxcore-log( 2931): 2015-12-03T14:53:27.311Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:27.326Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:27.334Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:27.348Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 2931): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6584"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6584"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT6584, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT6584, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,W/bt-btif ( 3006): dm_pm_timer expires
W/bt-btif ( 3006): dm_pm_timer expires 0
W/bt-btif ( 3006): proc dm_pm_timer expires
,I/jxcore-log( 2931): 2015-12-03T14:53:31.877Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:53:31.878Z SendDataConnector.js: Connect (retry count 4) to peer E0:DB:10:14:E2:C0 with availability status: true,
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:53:31.879Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:53:31.879Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 2931): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418596c rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Note4-1
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: XT1072
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTListenerThread( 2931): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8266","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : motorola-XT1072_PT8266
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, motorola-XT1072_PT8266
,I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
,I/jxcore-log( 2931): 2015-12-03T14:53:34.881Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/jxcore-log( 2931): 2015-12-03T14:53:35.369Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:35.380Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:35.393Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:35.398Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): invalid rfc slot id: 52
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT2273
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2931): 2015-12-03T14:53:37.793Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x42
,I/        ( 2931): Cleared service requests
I/        ( 2931): Started peer discovery
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: A5-1
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2931): Found 6 peers.
I/SS      ( 2931): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2931): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2931): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2931): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2931): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2931): Peer(6): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2931): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2931): Added service request
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185b34 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2931): Started service discovery
,W/bt-btif ( 3006): invalid rfc slot id: 54
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT8266
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
,I/BtToSocketBase( 2931): Close local in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT8266
I/BtToSocketBase( 2931): Close LocalOutputStream
,I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Close bt in
,I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/jxcore-log( 2931): 2015-12-03T14:53:45.805Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,I/        ( 2931): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT2572"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT2572"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT2572, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT2572, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185b34 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: A5-1
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x41
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTListenerThread( 2931): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2273","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : samsung-SM-A500FU_PT2273
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, samsung-SM-A500FU_PT2273
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
,I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
I/        ( 2931): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6584"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6584"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT6584, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT6584, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
,I/jxcore-log( 2931): 2015-12-03T14:53:49.474Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/jxcore-log( 2931): 2015-12-03T14:53:49.839Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:49.925Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:50.049Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:53:50.216Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: XT1072
,I/        ( 2931): Cleared service requests
I/        ( 2931): Started peer discovery
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185b34 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): invalid rfc slot id: 56
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT2273
,I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
,I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT2273
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/jxcore-log( 2931): 2015-12-03T14:54:00.300Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: XT1072
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185b34 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x48
,I/BTListenerThread( 2931): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8266","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : motorola-XT1072_PT8266
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, motorola-XT1072_PT8266
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/jxcore-log( 2931): 2015-12-03T14:54:01.426Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
,I/BtToRequestSocket( 2931): --DoOneRunRound ended
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 3006): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2931): 2015-12-03T14:54:01.803Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418608c rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2931): 2015-12-03T14:54:01.846Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:01.930Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:01.941Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:01.995Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
E/bt-btif ( 3006): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3006): Entering PendingCommandState State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device 7C:F9:0E:34:8A:A0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for 7C:F9:0E:34:8A:A0, but we have no record of that device.
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 3006): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3006): StableState(): Entering Off State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device 7C:F9:0E:34:8A:A0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for 7C:F9:0E:34:8A:A0, but we have no record of that device.
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2931): Found 7 peers.
I/SS      ( 2931): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2931): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2931): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2931): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2931): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2931): Peer(6): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 2931): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2931): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2931): Added service request
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
,I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418608c rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418608c rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2931): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9611","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT9611
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, samsung-SM-G900F_PT9611
,I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
,I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/        ( 2931): Started service discovery
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/jxcore-log( 2931): 2015-12-03T14:54:03.959Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: A5-1
,I/        ( 2931): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2273","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2273","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT2273, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT2273, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418608c rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2931): 2015-12-03T14:54:05.182Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:05.191Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:05.199Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:05.226Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:05.266Z SendDataTCPServer.js: TCP/IP server has received 22052 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:05.280Z SendDataTCPServer.js: TCP/IP server has received 24032 bytes of data
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418608c rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2931): 2015-12-03T14:54:05.667Z SendDataTCPServer.js: TCP/IP server has received 26012 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:05.670Z SendDataTCPServer.js: TCP/IP server has received 27992 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:05.724Z SendDataTCPServer.js: TCP/IP server has received 29972 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:05.803Z SendDataTCPServer.js: TCP/IP server has received 31952 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:05.931Z SendDataTCPServer.js: TCP/IP server has received 33932 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:05.966Z SendDataTCPServer.js: TCP/IP server has received 39872 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:05.988Z SendDataTCPServer.js: TCP/IP server has received 41852 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:06.001Z SendDataTCPServer.js: TCP/IP server has received 45812 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:06.066Z SendDataTCPServer.js: TCP/IP server has received 47792 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:06.106Z SendDataTCPServer.js: TCP/IP server has received 51752 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:06.150Z SendDataTCPServer.js: TCP/IP server has received 53732 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:06.212Z SendDataTCPServer.js: TCP/IP server has received 55712 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:06.478Z SendDataTCPServer.js: TCP/IP server has received 57692 bytes of data
I/jxcore-log( 2931): 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2931): 2015-12-03T14:54:06.723Z SendDataTCPServer.js: TCP/IP server has received 59672 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:07.091Z SendDataTCPServer.js: TCP/IP server has received 61652 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:07.508Z SendDataTCPServer.js: TCP/IP server has received 63632 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:07.554Z SendDataTCPServer.js: TCP/IP server has received 65612 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:07.562Z SendDataTCPServer.js: TCP/IP server has received 69572 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:07.568Z SendDataTCPServer.js: TCP/IP server has received 71552 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:07.581Z SendDataTCPServer.js: TCP/IP server has received 73532 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:07.617Z SendDataTCPServer.js: TCP/IP server has received 81452 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:07.667Z SendDataTCPServer.js: TCP/IP server has received 83432 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:07.706Z SendDataTCPServer.js: TCP/IP server has received 85412 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:07.854Z SendDataTCPServer.js: TCP/IP server has received 87392 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:07.997Z SendDataTCPServer.js: TCP/IP server has received 89372 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:08.095Z SendDataTCPServer.js: TCP/IP server has received 91352 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:08.301Z SendDataTCPServer.js: TCP/IP server has received 93332 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:08.335Z SendDataTCPServer.js: TCP/IP server has received 97292 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:08.458Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: A5-1
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTListenerThread( 2931): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2273","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : samsung-SM-A500FU_PT2273
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, samsung-SM-A500FU_PT2273
,I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
,I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/jxcore-log( 2931): 2015-12-03T14:54:12.000Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
,I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/jxcore-log( 2931): 2015-12-03T14:54:12.551Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:12.618Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:12.628Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:12.636Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): invalid rfc slot id: 57
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT8266
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2931): 2015-12-03T14:54:12.791Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 2931): Cleared service requests
,I/        ( 2931): Started peer discovery
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x47
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2931): Found 9 peers.
I/SS      ( 2931): Peer(1): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2931): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2931): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2931): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2931): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2931): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2931): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2931): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2931): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2931): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2931): Added service request
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3006): dm_pm_timer expires
W/bt-btif ( 3006): dm_pm_timer expires 0
,W/bt-btif ( 3006): proc dm_pm_timer expires
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418608c rs_disc_pending=1
E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3006): bta_dm_check_av:0
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT9611
I/BtToSocketBase( 2931): Stop ReceivingThread
,I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): invalid rfc slot id: 58
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2931): 2015-12-03T14:54:15.805Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: S5-1
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185b34 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/        ( 2931): Started service discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: XT1072
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185b34 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): invalid rfc slot id: 59
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT2273
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2931): 2015-12-03T14:54:22.443Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: XT1072
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
,W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x43
,I/BTListenerThread( 2931): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8266","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : motorola-XT1072_PT8266
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, motorola-XT1072_PT8266
,I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/jxcore-log( 2931): 2015-12-03T14:54:23.140Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/jxcore-log( 2931): 2015-12-03T14:54:23.594Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:23.644Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:23.650Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:23.659Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:23.682Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:23.690Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185b34 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: A5-1
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185b34 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [7c:f9:0e:34:8a:a0]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: S5-1
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418608c rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BtConnection( 2931): connectionTimeoutTimer
,I/BTConnectToThread( 2931): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3006): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:55, channel:-1
,I/CONNEC  ( 2931): Error: Cancelled
I/CONNEC  ( 2931): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2931): 2015-12-03T14:54:31.907Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:54:31.907Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:31.924Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:54:31.925Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:54:31.928Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2931): 
I/jxcore-log( 2931): ---- round done--------
I/jxcore-log( 2931): 
I/jxcore-log( 2931): ---- gotta redo : E0:DB:10:14:E2:C0, try count now: 1
I/jxcore-log( 2931): 
I/jxcore-log( 2931): do fake peer & start
I/jxcore-log( 2931): 
I/jxcore-log( 2931): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:54:31.931Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:54:31.931Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:54:31.932Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2931): Connecting to null, at 34:FC:EF:11:B1:66
,I/jxcore-log( 2931): 2015-12-03T14:54:31.952Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:54:31.952Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:54:31.952Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
,I/chromium( 2931): [INFO:CONSOLE(63)] "logCallback Round of send data to peer E0:DB:10:14:E2:C0 done with result: Connection to E0:DB:10:14:E2:C0 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btif ( 3006): DISCOVERY_COMP_EVT slot id:63, failed to find channle,                                       status:2, scn:449581235
W/bt-btif ( 3006): invalid rfc slot id: 63
,I/BTConnectToThread( 2931): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2931): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/jxcore-log( 2931): $$jxcore_callback_56 wasn't registered
W/jxcore-log( 2931): 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418608c rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BTListenerThread( 2931): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 2931): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9611","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT9611
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, samsung-SM-G900F_PT9611
,I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
,I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/jxcore-log( 2931): 2015-12-03T14:54:32.579Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
,I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/jxcore-log( 2931): 2015-12-03T14:54:33.130Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:33.152Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:33.162Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:33.171Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:33.175Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:33.223Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [7c:f9:0e:37:96:ab]: 7, f, 610c
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: A5-1
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418608c rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2931): 2015-12-03T14:54:36.954Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:54:36.954Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2931): 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418608c rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3006): SDP - Rcvd conn cnf with error: 0xf  CID 0x40
E/bt-btif ( 3006): DISCOVERY_COMP_EVT slot id:55, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3006): invalid rfc slot id: 55
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Note4-1
,W/bt-btif ( 3006): dm_pm_timer expires
W/bt-btif ( 3006): dm_pm_timer expires 1
W/bt-btif ( 3006): proc dm_pm_timer expires
,I/jxcore-log( 2931): 2015-12-03T14:54:41.957Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:54:41.958Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:54:41.959Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:41.959Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2931): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2931): Starting to connect
,W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418608c rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418608c rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3006): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3006): invalid rfc slot id: 61
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT9611
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2931): 2015-12-03T14:54:43.983Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,W/bt-sdp  ( 3006): process_service_search_attr_rsp
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418608c rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x4c
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 1
E/bt-btif ( 3006): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3006): Entering PendingCommandState State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device 34:FC:EF:11:B1:66 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for 34:FC:EF:11:B1:66, but we have no record of that device.
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 0
,D/BluetoothAdapterProperties( 3006): Failed to remove device: 34:FC:EF:11:B1:66
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3006): StableState(): Entering Off State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device 34:FC:EF:11:B1:66 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for 34:FC:EF:11:B1:66, but we have no record of that device.
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4186254 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2931): Starting to Handshake
,I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2931): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418608c rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4186254 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 2931): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 2931): Got JSON from encryption:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT4785"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2931): HandshakeOk : LGE-Nexus 5_PT4785
,I/HS      ( 2931): Hand Shake finished outgoing for : LGE-Nexus 5_PT4785
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : false, LGE-Nexus 5_PT4785
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2931): mHTTPPort  set to : 42014
I/BtConnectorHelper( 2931): Request socket is using : 42014
,I/BtToRequestSocket( 2931): Now accepting connections
,I/BtConnectorHelper( 2931): Calling ConnectionStatusUpdate with port :42014
I/jxcore-log( 2931): 2015-12-03T14:54:47.477Z SendDataConnector.js: CLIENT connected to 42014, error: null
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:54:47.478Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): incoming data from: /127.0.0.1, port: 42014
I/BtToRequestSocket( 2931): Set local streams
I/BtToRequestSocket( 2931): rin ended ---------------------------;
,I/jxcore-log( 2931): 2015-12-03T14:54:47.499Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,D/        ( 3006): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: S5-1
,I/jxcore-log( 2931): 2015-12-03T14:54:48.815Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:48.968Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2931): 
,D/        ( 3006): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13816
,I/jxcore-log( 2931): 2015-12-03T14:54:49.169Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:49.470Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2931): 
,D/        ( 3006): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 2931): 2015-12-03T14:54:49.666Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2931): 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2931): 2015-12-03T14:54:49.911Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:50.297Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): dm_pm_timer expires
W/bt-btif ( 3006): dm_pm_timer expires 1
,W/bt-btif ( 3006): proc dm_pm_timer expires
,I/jxcore-log( 2931): 2015-12-03T14:54:50.548Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:54:50.779Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2931): 
,I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4186254 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: A5-1
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,W/bt-btif ( 3006): dm_pm_timer expires
W/bt-btif ( 3006): dm_pm_timer expires 0
,W/bt-btif ( 3006): proc dm_pm_timer expires
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: S5-1
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4186254 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418608c rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418608c rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418608c rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2931): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9611","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT9611
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, samsung-SM-G900F_PT9611
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/jxcore-log( 2931): 2015-12-03T14:54:59.497Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
,I/BtToRequestSocket( 2931): --DoOneRunRound ended
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 3006): invalid rfc slot id: 60
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT8266
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2931): 2015-12-03T14:55:00.078Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:55:00.086Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: XT1072
,I/jxcore-log( 2931): 2015-12-03T14:55:00.116Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418608c rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2931): 2015-12-03T14:55:00.456Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:55:00.461Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:55:00.496Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:55:00.504Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:55:00.777Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:55:00.777Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:55:00.778Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:55:00.778Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:55:00.778Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2931): 
,I/BtToSocketBase( 2931): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2931): Disconnect outgoing peer: LGE-Nexus 5_PT4785
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
I/BtToRequestSocket( 2931): Close server socket
,W/bt-btif ( 3006): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418608c rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4186254 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2931): 2015-12-03T14:55:05.778Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:55:05.779Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Nexus 5
,W/bt-btif ( 3006): invalid rfc slot id: 62
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT9611
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2931): 2015-12-03T14:55:10.328Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:55:10.781Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:55:10.782Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:55:10.782Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:55:10.783Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: 34:FC:EF:11:B1:66, name: Nexus 5
,I/        ( 2931): Connecting to Nexus 5, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418608c rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x48
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Nexus 5
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4186254 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3006): process_service_search_attr_rsp
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4186254 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2931): Starting to Handshake
,I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2931): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4186254 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/        ( 2931): Cleared service requests
I/        ( 2931): Started peer discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4186254 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): invalid rfc slot id: 66
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread disconnected: java.io.IOException: bt socket closed, read return: -1
I/BTConnectToThread( 2931): HandshakeFailed : SOCKET_DISCONNECTED
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/CONNEC  ( 2931): Error: handshake: SOCKET_DISCONNECTED
,I/jxcore-log( 2931): 2015-12-03T14:55:15.499Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:55:15.499Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:55:15.500Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2931): Found 9 peers.
I/SS      ( 2931): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2931): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2931): Peer(3): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2931): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2931): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2931): Peer(6): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2931): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2931): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2931): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2931): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2931): Added service request
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: S5-1
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4186254 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2931): Started service discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4186254 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Nexus 5
,I/jxcore-log( 2931): 2015-12-03T14:55:20.502Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:55:20.503Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2931): 
,I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,I/        ( 2931): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3573","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3573","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT3573, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT3573, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 2931): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8216","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8216","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT8216, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT8216, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: S5-1
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTListenerThread( 2931): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9611","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
,I/HS      ( 2931): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT9611
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, samsung-SM-G900F_PT9611
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
,I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/jxcore-log( 2931): 2015-12-03T14:55:21.933Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
,I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/jxcore-log( 2931): 2015-12-03T14:55:22.472Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:55:22.589Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:55:22.699Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:55:22.707Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:55:22.765Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:55:22.817Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,I/        ( 2931): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT2572"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT2572"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT2572, peerAddress: 80:01:84:8A:B3:68
,I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT2572, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 2931): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6584"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6584"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT6584, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT6584, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2931): 2015-12-03T14:55:25.506Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:55:25.507Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:55:25.508Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:55:25.508Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: 34:FC:EF:11:B1:66, name: Nexus 5
,I/        ( 2931): Connecting to Nexus 5, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2931): Starting to connect
,W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418608c rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/        ( 2931): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT7284","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT7284","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT7284, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT7284, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Nexus 5
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4186254 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418608c rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14),
,W/bt-sdp  ( 3006): process_service_search_attr_rsp
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4186254 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2931): Starting to Handshake
,I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2931): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTConnectToThread( 2931): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 2931): Got JSON from encryption:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT4785"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2931): HandshakeOk : LGE-Nexus 5_PT4785
I/HS      ( 2931): Hand Shake finished outgoing for : LGE-Nexus 5_PT4785
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : false, LGE-Nexus 5_PT4785
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2931): mHTTPPort  set to : 40528
I/BtConnectorHelper( 2931): Request socket is using : 40528
I/BtToRequestSocket( 2931): Now accepting connections
,I/BtConnectorHelper( 2931): Calling ConnectionStatusUpdate with port :40528
I/jxcore-log( 2931): 2015-12-03T14:55:31.537Z SendDataConnector.js: CLIENT connected to 40528, error: null
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:55:31.538Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): incoming data from: /127.0.0.1, port: 40528
I/BtToRequestSocket( 2931): Set local streams
I/BtToRequestSocket( 2931): rin ended ---------------------------;
,I/jxcore-log( 2931): 2015-12-03T14:55:31.572Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2931): 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418608c rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4186254 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): invalid rfc slot id: 65
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT9611
,I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT9611
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/jxcore-log( 2931): 2015-12-03T14:55:33.041Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x4f current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x4f
,I/        ( 2931): Cleared service requests
I/        ( 2931): Started peer discovery
,W/bt-btif ( 3006): dm_pm_timer expires
,W/bt-btif ( 3006): dm_pm_timer expires 1
W/bt-btif ( 3006): proc dm_pm_timer expires
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418608c rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: S5-1
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4186254 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2931): Found 5 peers.
I/SS      ( 2931): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2931): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 2931): Peer(3): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 2931): Peer(4): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 2931): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2931): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2931): Added service request
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2931): Started service discovery
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2931): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT4731"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT4731"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT4731, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT4731, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 2931): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT7284","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT7284","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT7284, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT7284, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 2931): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT2572"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT2572"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT2572, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT2572, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/jxcore-log( 2931): 2015-12-03T14:55:41.640Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:55:41.641Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:55:41.642Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:55:41.643Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:55:41.647Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2931): 
,I/BtToSocketBase( 2931): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2931): Disconnect outgoing peer: LGE-Nexus 5_PT4785
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToRequestSocket( 2931): Close server socket
,W/bt-btif ( 3006): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: S5-1
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4186254 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418608c rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
,I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4186254 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2931): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9611","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT9611
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, samsung-SM-G900F_PT9611
,I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
,I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/jxcore-log( 2931): 2015-12-03T14:55:45.311Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
,I/BtToRequestSocket( 2931): --DoOneRunRound ended
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418608c rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Nexus 5
,I/jxcore-log( 2931): 2015-12-03T14:55:46.040Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:55:46.092Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
,I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:55:46.222Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:55:46.293Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:55:46.305Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:55:46.645Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:55:46.646Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2931): 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 2931): Cleared service requests
I/        ( 2931): Started peer discovery
,I/jxcore-log( 2931): 2015-12-03T14:55:51.650Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:55:51.651Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:55:51.651Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:55:51.652Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: 34:FC:EF:11:B1:66, name: Nexus 5
,I/        ( 2931): Connecting to Nexus 5, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Nexus 5
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4186254 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3006): process_service_search_attr_rsp
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2931): Found 5 peers.
I/SS      ( 2931): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2931): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2931): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2931): Peer(4): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 2931): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2931): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2931): Added service request
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418608c rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4186254 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/        ( 2931): Started service discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2931): Starting to Handshake
,I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2931): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/BTConnectToThread( 2931): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 2931): Got JSON from encryption:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT4785"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2931): HandshakeOk : LGE-Nexus 5_PT4785
I/HS      ( 2931): Hand Shake finished outgoing for : LGE-Nexus 5_PT4785
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : false, LGE-Nexus 5_PT4785
,I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2931): mHTTPPort  set to : 47347
I/BtConnectorHelper( 2931): Request socket is using : 47347
I/BtToRequestSocket( 2931): Now accepting connections
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418608c rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/BtConnectorHelper( 2931): Calling ConnectionStatusUpdate with port :47347
I/jxcore-log( 2931): 2015-12-03T14:55:55.826Z SendDataConnector.js: CLIENT connected to 47347, error: null
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:55:55.826Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): incoming data from: /127.0.0.1, port: 47347
I/BtToRequestSocket( 2931): Set local streams
,I/BtToRequestSocket( 2931): rin ended ---------------------------;
,I/jxcore-log( 2931): 2015-12-03T14:55:55.830Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4186254 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/        ( 2931): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9611","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9611","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT9611, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT9611, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418608c rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): invalid rfc slot id: 67
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT9611
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2931): 2015-12-03T14:55:56.462Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418608c rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/        ( 2931): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT4731"}, typeCordovap2p._tcp.local.:
,I/        ( 2931): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT4731"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT4731, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT4731, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x40 current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x40
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4186254 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418608c rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: S5-1
,W/bt-btif ( 3006): dm_pm_timer expires
W/bt-btif ( 3006): dm_pm_timer expires 1
W/bt-btif ( 3006): proc dm_pm_timer expires
,I/jxcore-log( 2931): 2015-12-03T14:56:05.869Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:56:05.869Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:56:05.870Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:56:05.872Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:56:05.872Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:56:05.872Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
,I/BtConnectorHelper( 2931): Disconnect outgoing peer: 34:FC:EF:11:B1:66
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
I/BtToRequestSocket( 2931): Close server socket
,I/jxcore-log( 2931): 2015-12-03T14:56:05.881Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2931): 
I/jxcore-log( 2931): ---- round done--------
I/jxcore-log( 2931): 
I/jxcore-log( 2931): ---- gotta redo : 34:FC:EF:11:B1:66, try count now: 1
I/jxcore-log( 2931): 
I/jxcore-log( 2931): do fake peer & start
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:56:05.882Z SendDataConnector.js: Start called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:56:05.882Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:56:05.882Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/        ( 2931): Connecting to null, at 58:2A:F7:ED:96:BE
I/jxcore-log( 2931): 2015-12-03T14:56:05.886Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2931): 
,I/chromium( 2931): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 34:FC:EF:11:B1:66 done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/        ( 2931): Cleared service requests
I/        ( 2931): Started peer discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3006): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4186254 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2931): Found 7 peers.
I/SS      ( 2931): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2931): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2931): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2931): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2931): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2931): Peer(6): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 2931): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2931): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2931): Added service request
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2931): Started service discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4186254 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Nexus 5
,W/bt-sdp  ( 3006): SDP - Rcvd conn cnf with error: 0x10  CID 0x49
E/bt-btif ( 3006): DISCOVERY_COMP_EVT slot id:71, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3006): invalid rfc slot id: 71
,I/BTConnectToThread( 2931): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2931): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2931): 2015-12-03T14:56:13.922Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:56:13.922Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:56:13.923Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:56:18.924Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:56:18.925Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2931): 
,I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,I/jxcore-log( 2931): 2015-12-03T14:56:23.928Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:56:23.928Z SendDataConnector.js: Connect (retry count 1) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:56:23.929Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:56:23.929Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/        ( 2931): Connecting to null, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/BluetoothRemoteDevices( 3006): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3006): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 1
E/bt-btif ( 3006): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3006): Entering PendingCommandState State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device 58:2A:F7:ED:96:BE not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for 58:2A:F7:ED:96:BE, but we have no record of that device.
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 0
,D/BluetoothAdapterProperties( 3006): Failed to remove device: 58:2A:F7:ED:96:BE
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3006): StableState(): Entering Off State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device 58:2A:F7:ED:96:BE not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for 58:2A:F7:ED:96:BE, but we have no record of that device.
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2931): Starting to Handshake
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2931): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTConnectToThread( 2931): got MESSAGE_READ 80 bytes.
I/BTConnectToThread( 2931): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2479","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2931): HandshakeOk : HUAWEI-ALE-L21_PT2479
I/HS      ( 2931): Hand Shake finished outgoing for : HUAWEI-ALE-L21_PT2479
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : false, HUAWEI-ALE-L21_PT2479
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2931): mHTTPPort  set to : 43518
I/BtConnectorHelper( 2931): Request socket is using : 43518
I/BtToRequestSocket( 2931): Now accepting connections
,I/BtConnectorHelper( 2931): Calling ConnectionStatusUpdate with port :43518
I/jxcore-log( 2931): 2015-12-03T14:56:25.701Z SendDataConnector.js: CLIENT connected to 43518, error: null
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:56:25.701Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): incoming data from: /127.0.0.1, port: 43518
I/BtToRequestSocket( 2931): Set local streams
I/BtToRequestSocket( 2931): rin ended ---------------------------;
,I/jxcore-log( 2931): 2015-12-03T14:56:25.723Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2931): 
,D/        ( 3006): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 2931): 2015-12-03T14:56:26.227Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2931): 
,D/        ( 3006): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:15796
,I/jxcore-log( 2931): 2015-12-03T14:56:26.271Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:56:26.276Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2931): 
,D/        ( 3006): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:7876
,I/jxcore-log( 2931): 2015-12-03T14:56:26.338Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:56:26.408Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:56:26.443Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:56:26.460Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:56:26.571Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:56:26.670Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:56:26.720Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:56:26.721Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:56:26.724Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:56:26.724Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/BtConnectorHelper( 2931): Disconnect outgoing peer: 58:2A:F7:ED:96:BE
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
,I/BtToSocketBase( 2931): Close bt socket
I/BtToRequestSocket( 2931): Close server socket
I/jxcore-log( 2931): 2015-12-03T14:56:26.726Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2931): 
I/jxcore-log( 2931): ---- round done--------
I/jxcore-log( 2931): 
I/jxcore-log( 2931): do fake peer & start
I/jxcore-log( 2931): 
I/jxcore-log( 2931): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:56:26.726Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:56:26.726Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:56:26.726Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/        ( 2931): Selected device address: 08:EC:A9:50:76:27, name: null
I/        ( 2931): Connecting to null, at 08:EC:A9:50:76:27
,I/chromium( 2931): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 58:2A:F7:ED:96:BE done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418641c rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418641c rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3006): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3006): process_service_search_attr_rsp
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418641c rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
E/bt-btif ( 3006): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3006): Entering PendingCommandState State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device 08:EC:A9:50:76:27 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for 08:EC:A9:50:76:27, but we have no record of that device.
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/BluetoothAdapterProperties( 3006): Failed to remove device: 08:EC:A9:50:76:27
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3006): StableState(): Entering Off State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device 08:EC:A9:50:76:27 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for 08:EC:A9:50:76:27, but we have no record of that device.
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2931): Starting to Handshake
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2931): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTConnectToThread( 2931): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 2931): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6802","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2931): HandshakeOk : samsung-SM-A300FU_PT6802
I/HS      ( 2931): Hand Shake finished outgoing for : samsung-SM-A300FU_PT6802
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : false, samsung-SM-A300FU_PT6802
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BtConnectedRequestSocket
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2931): mHTTPPort  set to : 44949
I/BtConnectorHelper( 2931): Request socket is using : 44949
I/BtToRequestSocket( 2931): Now accepting connections
,I/BtConnectorHelper( 2931): Calling ConnectionStatusUpdate with port :44949
,I/jxcore-log( 2931): 2015-12-03T14:56:29.133Z SendDataConnector.js: CLIENT connected to 44949, error: null
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:56:29.139Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): incoming data from: /127.0.0.1, port: 44949
I/BtToRequestSocket( 2931): Set local streams
I/BtToRequestSocket( 2931): rin ended ---------------------------;
,I/jxcore-log( 2931): 2015-12-03T14:56:29.161Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2931): 
,D/        ( 3006): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 2931): 2015-12-03T14:56:29.645Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:56:29.720Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2931): 
,D/        ( 3006): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13816
,I/jxcore-log( 2931): 2015-12-03T14:56:29.777Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2931): 
,D/        ( 3006): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:6886
,I/jxcore-log( 2931): 2015-12-03T14:56:29.819Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:56:29.858Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:56:29.869Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:56:29.932Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:56:29.938Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:56:29.980Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa41865e4 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: ALE-L21
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3006): dm_pm_timer expires
W/bt-btif ( 3006): dm_pm_timer expires 0
,W/bt-btif ( 3006): proc dm_pm_timer expires
,I/jxcore-log( 2931): 2015-12-03T14:56:39.980Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:56:39.981Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:56:39.982Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:56:39.983Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:56:39.990Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2931): 
,I/BtToSocketBase( 2931): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2931): Disconnect outgoing peer: samsung-SM-A300FU_PT6802
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
I/BtToRequestSocket( 2931): Close server socket
,W/bt-btif ( 3006): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,I/jxcore-log( 2931): 2015-12-03T14:56:44.984Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:56:44.985Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/jxcore-log( 2931): 2015-12-03T14:56:49.988Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:56:49.989Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:56:49.990Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:56:49.990Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: 08:EC:A9:50:76:27, name: Thali Test (Galaxy A3)
,I/        ( 2931): Connecting to Thali Test (Galaxy A3), at 08:EC:A9:50:76:27
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [08:ec:a9:50:76:27]: 6, 10f, 608
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,W/bt-sdp  ( 3006): process_service_search_attr_rsp
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2931): Starting to Handshake
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2931): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTConnectToThread( 2931): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 2931): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6802","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 2931): HandshakeOk : samsung-SM-A300FU_PT6802
I/HS      ( 2931): Hand Shake finished outgoing for : samsung-SM-A300FU_PT6802
I/BtConnectorHelper( 2931): Starting the connected thread incoming : false, samsung-SM-A300FU_PT6802
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
I/BtToRequestSocket( 2931): mHTTPPort  set to : 41640
I/BtConnectorHelper( 2931): Request socket is using : 41640
I/BtToRequestSocket( 2931): Now accepting connections
,I/BtConnectorHelper( 2931): Calling ConnectionStatusUpdate with port :41640
,I/jxcore-log( 2931): 2015-12-03T14:56:51.538Z SendDataConnector.js: CLIENT connected to 41640, error: null
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:56:51.539Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): incoming data from: /127.0.0.1, port: 41640
I/BtToRequestSocket( 2931): Set local streams
I/BtToRequestSocket( 2931): rin ended ---------------------------;
,I/jxcore-log( 2931): 2015-12-03T14:56:51.558Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2931): 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3006): dm_pm_timer expires
W/bt-btif ( 3006): dm_pm_timer expires 0
W/bt-btif ( 3006): proc dm_pm_timer expires
,I/jxcore-log( 2931): 2015-12-03T14:57:01.620Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:57:01.621Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:57:01.622Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:57:01.622Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:57:01.623Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2931): 
,I/BtToSocketBase( 2931): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2931): Disconnect outgoing peer: samsung-SM-A300FU_PT6802
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
I/BtToRequestSocket( 2931): Close server socket
,W/bt-btif ( 3006): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/jxcore-log( 2931): 2015-12-03T14:57:06.625Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:57:06.626Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [b0:c5:59:3f:75:69]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/        ( 2931): Cleared service requests
,I/        ( 2931): Started peer discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTListenerThread( 2931): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8216","ra":"B0:C5:59:3F:75:69"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT8216
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, samsung-SM-G900F_PT8216
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/jxcore-log( 2931): 2015-12-03T14:57:07.616Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2931): Found 6 peers.
I/SS      ( 2931): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2931): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2931): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2931): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2931): Peer(5): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 2931): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2931): Ignored { when=-6ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2931): Added service request
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2931): 2015-12-03T14:57:08.621Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:08.635Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:08.681Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:08.689Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:08.695Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:08.707Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:08.721Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:08.728Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:08.768Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:08.774Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:08.803Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:08.820Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:08.844Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:08.860Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:08.894Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 2931): 
,I/        ( 2931): Started service discovery
I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
I/jxcore-log( 2931): 2015-12-03T14:57:08.940Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:08.974Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:09.031Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:09.051Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:09.121Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:09.267Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:09.305Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:09.327Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:09.334Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 2931): 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2931): 2015-12-03T14:57:09.381Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:09.405Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:09.424Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:09.437Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:09.478Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:09.522Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:09.529Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:09.541Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:09.575Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:09.599Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:09.641Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:09.695Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:09.735Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:09.745Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:09.756Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:09.785Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:09.796Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:09.820Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:09.855Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2931): 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2931): 2015-12-03T14:57:11.629Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:57:11.630Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:57:11.630Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:57:11.631Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: 08:EC:A9:50:76:27, name: Thali Test (Galaxy A3)
,I/        ( 2931): Connecting to Thali Test (Galaxy A3), at 08:EC:A9:50:76:27
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418524c rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Thali Test (Galaxy A3)
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa41865e4 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3006): process_service_search_attr_rsp
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2931): Starting to Handshake
,I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2931): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTConnectToThread( 2931): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 2931): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6802","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2931): HandshakeOk : samsung-SM-A300FU_PT6802
I/HS      ( 2931): Hand Shake finished outgoing for : samsung-SM-A300FU_PT6802
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : false, samsung-SM-A300FU_PT6802
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2931): mHTTPPort  set to : 50960
I/BtConnectorHelper( 2931): Request socket is using : 50960
I/BtToRequestSocket( 2931): Now accepting connections
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418524c rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/BtConnectorHelper( 2931): Calling ConnectionStatusUpdate with port :50960
I/jxcore-log( 2931): 2015-12-03T14:57:17.000Z SendDataConnector.js: CLIENT connected to 50960, error: null
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:57:17.001Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): incoming data from: /127.0.0.1, port: 50960
I/BtToRequestSocket( 2931): Set local streams
I/BtToRequestSocket( 2931): rin ended ---------------------------;
,I/jxcore-log( 2931): 2015-12-03T14:57:17.021Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2931): 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3006): invalid rfc slot id: 69
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT8216
,I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT8216
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/jxcore-log( 2931): 2015-12-03T14:57:19.963Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418524c rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x47
,I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,W/bt-btif ( 3006): dm_pm_timer expires
W/bt-btif ( 3006): dm_pm_timer expires 1
,W/bt-btif ( 3006): proc dm_pm_timer expires
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/jxcore-log( 2931): 2015-12-03T14:57:27.107Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:57:27.107Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:57:27.108Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:57:27.109Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:57:27.110Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2931): 
,I/BtToSocketBase( 2931): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2931): Disconnect outgoing peer: samsung-SM-A300FU_PT6802
,I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
,I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
,I/BtToSocketBase( 2931): Close bt in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
I/BtToRequestSocket( 2931): Close server socket
,W/bt-btif ( 3006): bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Thali Test (Galaxy S5)
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
,I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/jxcore-log( 2931): 2015-12-03T14:57:32.109Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:57:32.110Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2931): 
,I/BTListenerThread( 2931): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8216","ra":"B0:C5:59:3F:75:69"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT8216
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, samsung-SM-G900F_PT8216
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/jxcore-log( 2931): 2015-12-03T14:57:32.218Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
,I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/jxcore-log( 2931): 2015-12-03T14:57:32.839Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:32.896Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:32.903Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:33.005Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:33.052Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:33.105Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2931): 2015-12-03T14:57:37.113Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:57:37.114Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:57:37.114Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:57:37.115Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: 08:EC:A9:50:76:27, name: Thali Test (Galaxy A3)
,I/        ( 2931): Connecting to Thali Test (Galaxy A3), at 08:EC:A9:50:76:27
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418524c rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Thali Test (Galaxy A3)
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa41865e4 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3006): process_service_search_attr_rsp
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2931): Starting to Handshake
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2931): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa41865e4 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418524c rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 2931): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 2931): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6802","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2931): HandshakeOk : samsung-SM-A300FU_PT6802
I/HS      ( 2931): Hand Shake finished outgoing for : samsung-SM-A300FU_PT6802
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : false, samsung-SM-A300FU_PT6802
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2931): mHTTPPort  set to : 37001
I/BtConnectorHelper( 2931): Request socket is using : 37001
I/BtToRequestSocket( 2931): Now accepting connections
,I/BtConnectorHelper( 2931): Calling ConnectionStatusUpdate with port :37001
I/jxcore-log( 2931): 2015-12-03T14:57:41.611Z SendDataConnector.js: CLIENT connected to 37001, error: null
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:57:41.612Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): incoming data from: /127.0.0.1, port: 37001
I/BtToRequestSocket( 2931): Set local streams
I/BtToRequestSocket( 2931): rin ended ---------------------------;
,I/jxcore-log( 2931): 2015-12-03T14:57:41.633Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): invalid rfc slot id: 75
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT8216
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2931): 2015-12-03T14:57:42.818Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418524c rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x46
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa41865e4 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Thali Test (Galaxy S5)
,W/bt-btif ( 3006): dm_pm_timer expires
W/bt-btif ( 3006): dm_pm_timer expires 1
W/bt-btif ( 3006): proc dm_pm_timer expires
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa41865e4 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2931): 2015-12-03T14:57:51.708Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:57:51.708Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:57:51.708Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:57:51.708Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:57:51.709Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2931): 
,I/BtToSocketBase( 2931): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2931): Disconnect outgoing peer: samsung-SM-A300FU_PT6802
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
I/BtToRequestSocket( 2931): Close server socket
,W/bt-btif ( 3006): bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Thali Test (Galaxy S5)
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa41865e4 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418524c rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/jxcore-log( 2931): 2015-12-03T14:57:56.709Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:57:56.709Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2931): 
,I/BTListenerThread( 2931): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8216","ra":"B0:C5:59:3F:75:69"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT8216
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, samsung-SM-G900F_PT8216
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
,I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/jxcore-log( 2931): 2015-12-03T14:57:56.785Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
,I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/jxcore-log( 2931): 2015-12-03T14:57:57.240Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:57.253Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:57.261Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:57.272Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:57:57.291Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2931): 2015-12-03T14:58:01.713Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:01.714Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:01.719Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:58:01.720Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: 08:EC:A9:50:76:27, name: Thali Test (Galaxy A3)
,I/        ( 2931): Connecting to Thali Test (Galaxy A3), at 08:EC:A9:50:76:27
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418524c rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418524c rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): invalid rfc slot id: 77
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT8216
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
,I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2931): 2015-12-03T14:58:07.399Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,W/bt-sdp  ( 3006): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 3006): DISCOVERY_COMP_EVT slot id:80, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3006): invalid rfc slot id: 80
,I/BTConnectToThread( 2931): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2931): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2931): 2015-12-03T14:58:07.446Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:58:07.447Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:07.463Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:58:07.463Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:58:07.466Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2931): 
I/jxcore-log( 2931): ---- round done--------
I/jxcore-log( 2931): 
I/jxcore-log( 2931): ---- gotta redo : 08:EC:A9:50:76:27, try count now: 1
I/jxcore-log( 2931): 
I/jxcore-log( 2931): do fake peer & start
I/jxcore-log( 2931): 
I/jxcore-log( 2931): Connect to fake peer: B4:CE:F6:AB:A4:6A
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:58:07.468Z SendDataConnector.js: Start called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:58:07.469Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:58:07.469Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: B4:CE:F6:AB:A4:6A, name: HTC Desire 820
,I/        ( 2931): Connecting to HTC Desire 820, at B4:CE:F6:AB:A4:6A
,I/chromium( 2931): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 08:EC:A9:50:76:27 done with result: Connection to 08:EC:A9:50:76:27 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/        ( 2931): Cleared service requests
I/        ( 2931): Started peer discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418524c rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x49
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2931): Found 5 peers.
I/SS      ( 2931): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 2931): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2931): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2931): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2931): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2931): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2931): Added service request
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: HTC Desire 820
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa41855dc rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/        ( 2931): Started service discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 3006): process_service_search_attr_rsp
,I/        ( 2931): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6802","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6802","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT6802, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT6802, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Thali Test (Galaxy S5)
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2931): Starting to Handshake
,I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2931): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTConnectToThread( 2931): got MESSAGE_READ 84 bytes.
I/BTConnectToThread( 2931): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT4731"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2931): HandshakeOk : HTC-HTC Desire 820_PT4731
I/HS      ( 2931): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT4731
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT4731
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2931): mHTTPPort  set to : 39861
I/BtConnectorHelper( 2931): Request socket is using : 39861
I/BtToRequestSocket( 2931): Now accepting connections
,I/BtConnectorHelper( 2931): Calling ConnectionStatusUpdate with port :39861
I/jxcore-log( 2931): 2015-12-03T14:58:17.103Z SendDataConnector.js: CLIENT connected to 39861, error: null
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:17.103Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): incoming data from: /127.0.0.1, port: 39861
I/BtToRequestSocket( 2931): Set local streams
I/BtToRequestSocket( 2931): rin ended ---------------------------;
,I/jxcore-log( 2931): 2015-12-03T14:58:17.131Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:18.361Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/        ( 2931): Cleared service requests
I/        ( 2931): Started peer discovery
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2931): Found 5 peers.
I/SS      ( 2931): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2931): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2931): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2931): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2931): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2931): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2931): Added service request
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa41855dc rs_disc_pending=1
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/BtConnectorHelper( 2931): Disconnect outgoing peer: HTC-HTC Desire 820_PT4731
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
I/BtToRequestSocket( 2931): Close server socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: HTC Desire 820
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2931): Started service discovery
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2931): 2015-12-03T14:58:28.362Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:58:28.363Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:28.363Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:58:28.367Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:28.371Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:33.371Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:58:33.371Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:33.372Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Thali Test (Galaxy S5)
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTListenerThread( 2931): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8216","ra":"B0:C5:59:3F:75:69"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT8216
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, samsung-SM-G900F_PT8216
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
,I/jxcore-log( 2931): 2015-12-03T14:58:35.159Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/jxcore-log( 2931): 2015-12-03T14:58:35.646Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:35.665Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:35.686Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:35.691Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:35.707Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:35.730Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2931): 2015-12-03T14:58:38.377Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:58:38.378Z SendDataConnector.js: Connect (retry count 1) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:58:38.378Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:58:38.379Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: B4:CE:F6:AB:A4:6A, name: HTC Desire 820
,I/        ( 2931): Connecting to HTC Desire 820, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418524c rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: HTC Desire 820
,W/bt-sdp  ( 3006): process_service_search_attr_rsp
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2931): Starting to Handshake
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTConnectToThread( 2931): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTConnectToThread( 2931): got MESSAGE_READ 84 bytes.
I/BTConnectToThread( 2931): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT4731"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2931): HandshakeOk : HTC-HTC Desire 820_PT4731
I/HS      ( 2931): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT4731
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT4731
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2931): mHTTPPort  set to : 42075
I/BtConnectorHelper( 2931): Request socket is using : 42075
I/BtToRequestSocket( 2931): Now accepting connections
,I/BtConnectorHelper( 2931): Calling ConnectionStatusUpdate with port :42075
I/jxcore-log( 2931): 2015-12-03T14:58:43.500Z SendDataConnector.js: CLIENT connected to 42075, error: null
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:58:43.500Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): incoming data from: /127.0.0.1, port: 42075
I/BtToRequestSocket( 2931): Set local streams
I/BtToRequestSocket( 2931): rin ended ---------------------------;
,I/jxcore-log( 2931): 2015-12-03T14:58:43.503Z SendDataConnector.js: CLIENT now sending 90000 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:44.476Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:44.785Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2931): 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2931): 2015-12-03T14:58:45.399Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:45.689Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): invalid rfc slot id: 79
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT8216
,I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT8216
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/jxcore-log( 2931): 2015-12-03T14:58:46.523Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:46.699Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa418524c rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x4a
,I/jxcore-log( 2931): 2015-12-03T14:58:50.016Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/jxcore-log( 2931): 2015-12-03T14:58:51.217Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:51.519Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): dm_pm_timer expires
W/bt-btif ( 3006): dm_pm_timer expires 0
W/bt-btif ( 3006): proc dm_pm_timer expires
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 3006): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3006): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3006): Entering PendingCommandState State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3006): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3006): StableState(): Entering Off State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTListenerThread( 2931): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3573","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : LGE-LG-H815_PT3573
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, LGE-LG-H815_PT3573
,I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
,I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
,I/jxcore-log( 2931): 2015-12-03T14:58:58.668Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/jxcore-log( 2931): 2015-12-03T14:58:59.348Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:59.356Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:59.362Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:59.369Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:59.377Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:59.390Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:59.396Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:59.428Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:59.452Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:59.465Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:59.495Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:59.529Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:59.555Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:59.601Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:59.635Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:59.671Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:59.684Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:59.717Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:59.731Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:59.770Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:59.807Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:59.858Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:59.897Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:59.907Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:58:59.968Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:59:00.016Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:59:00.079Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:59:00.090Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:59:00.094Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:59:00.142Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:59:01.519Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:59:01.520Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:59:01.521Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:59:01.521Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:59:01.522Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2931): 
,I/BtToSocketBase( 2931): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2931): Disconnect outgoing peer: HTC-HTC Desire 820_PT4731
,I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
I/BtToRequestSocket( 2931): Close server socket
,W/bt-btif ( 3006): bta_jv_rfc_port_to_cb(port_handle:0x19):jv handle:0x0 not FOUND
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2931): 2015-12-03T14:59:06.523Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:59:06.528Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: HTC Desire 820
,W/bt-btif ( 3006): invalid rfc slot id: 82
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT3573
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2931): 2015-12-03T14:59:10.401Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:59:11.536Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:59:11.537Z SendDataConnector.js: Connect (retry count 2) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:59:11.537Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:59:11.537Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: B4:CE:F6:AB:A4:6A, name: HTC Desire 820
,I/        ( 2931): Connecting to HTC Desire 820, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/UsageStatsService(  761): User[0] Flushing usage stats to disk
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x4f current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x4f
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: G4-1
,W/bt-sdp  ( 3006): SDP - Rcvd conn cnf with error: 0x1f  CID 0x43
E/bt-btif ( 3006): DISCOVERY_COMP_EVT slot id:85, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3006): invalid rfc slot id: 85
,I/BTConnectToThread( 2931): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2931): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2931): 2015-12-03T14:59:17.929Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:59:17.930Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:59:17.930Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: G4-1
,I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3006): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3006): Entering PendingCommandState State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3006): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 3006): StableState(): Entering Off State
,E/BluetoothEventManager( 3038): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTListenerThread( 2931): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3573","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : LGE-LG-H815_PT3573
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, LGE-LG-H815_PT3573
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/jxcore-log( 2931): 2015-12-03T14:59:22.351Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
,I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/jxcore-log( 2931): 2015-12-03T14:59:22.773Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:59:22.787Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:59:22.794Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:59:22.931Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:59:22.932Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2931): 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2931): Cleared service requests
I/        ( 2931): Started peer discovery
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2931): Found 4 peers.
I/SS      ( 2931): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2931): Peer(2): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2931): Peer(3): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2931): Peer(4): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 2931): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2931): Added service request
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2931): Started service discovery
,I/        ( 2931): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8216","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8216","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT8216, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT8216, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 2931): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3573","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3573","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT3573, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT3573, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2931): 2015-12-03T14:59:27.935Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:59:27.936Z SendDataConnector.js: Connect (retry count 3) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:59:27.937Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:59:27.937Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: B4:CE:F6:AB:A4:6A, name: HTC Desire 820
,I/        ( 2931): Connecting to HTC Desire 820, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa41867ac rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: HTC Desire 820
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa41855dc rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3006): process_service_search_attr_rsp
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2931): Starting to Handshake
,I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2931): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTConnectToThread( 2931): got MESSAGE_READ 84 bytes.
I/BTConnectToThread( 2931): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT4731"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2931): HandshakeOk : HTC-HTC Desire 820_PT4731
I/HS      ( 2931): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT4731
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT4731
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2931): mHTTPPort  set to : 51650
I/BtConnectorHelper( 2931): Request socket is using : 51650
I/BtToRequestSocket( 2931): Now accepting connections
,I/BtConnectorHelper( 2931): Calling ConnectionStatusUpdate with port :51650
,I/jxcore-log( 2931): 2015-12-03T14:59:31.009Z SendDataConnector.js: CLIENT connected to 51650, error: null
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:59:31.009Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): incoming data from: /127.0.0.1, port: 51650
I/BtToRequestSocket( 2931): Set local streams
I/BtToRequestSocket( 2931): rin ended ---------------------------;
,I/jxcore-log( 2931): 2015-12-03T14:59:31.029Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2931): 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3006): invalid rfc slot id: 84
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT3573
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2931): 2015-12-03T14:59:32.773Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x46
,I/        ( 2931): Cleared service requests
I/        ( 2931): Started peer discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2931): Found 6 peers.
I/SS      ( 2931): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2931): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2931): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2931): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2931): Peer(5): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 2931): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2931): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2931): Added service request
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3006): dm_pm_timer expires
W/bt-btif ( 3006): dm_pm_timer expires 1
,W/bt-btif ( 3006): proc dm_pm_timer expires
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: G4-1
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2931): Started service discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2931): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9611","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 2931): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9611","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT9611, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT9611, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 2931): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8216","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8216","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT8216, peerAddress: B0:C5:59:3F:75:69
,I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT8216, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 2931): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3573","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 2931): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3573","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT3573, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT3573, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 2931): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6802","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6802","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT6802, peerAddress: 08:EC:A9:50:76:27
,I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT6802, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 2931): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6584"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6584"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT6584, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT6584, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/jxcore-log( 2931): 2015-12-03T14:59:41.090Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:59:41.091Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:59:41.091Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:59:41.092Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:59:41.093Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2931): 
,I/BtToSocketBase( 2931): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2931): Disconnect outgoing peer: HTC-HTC Desire 820_PT4731
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
I/BtToRequestSocket( 2931): Close server socket
,W/bt-btif ( 3006): bta_jv_rfc_port_to_cb(port_handle:0x1c):jv handle:0x0 not FOUND
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: G4-1
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3006): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3006): Entering PendingCommandState State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3006): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3006): StableState(): Entering Off State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTListenerThread( 2931): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3573","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : LGE-LG-H815_PT3573
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, LGE-LG-H815_PT3573
,I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
,I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
,I/jxcore-log( 2931): 2015-12-03T14:59:46.032Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/jxcore-log( 2931): 2015-12-03T14:59:46.093Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:59:46.093Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:59:46.418Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/jxcore-log( 2931): 2015-12-03T14:59:46.527Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 2931): 2015-12-03T14:59:46.627Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:59:46.680Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T14:59:46.683Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,I/        ( 2931): Cleared service requests
I/        ( 2931): Started peer discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2931): Found 7 peers.
I/SS      ( 2931): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2931): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2931): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2931): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2931): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2931): Peer(6): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 2931): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2931): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2931): Added service request
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2931): 2015-12-03T14:59:51.096Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:59:51.096Z SendDataConnector.js: Connect (retry count 4) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:59:51.097Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T14:59:51.097Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: B4:CE:F6:AB:A4:6A, name: HTC Desire 820
,I/        ( 2931): Connecting to HTC Desire 820, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
,I/        ( 2931): Started service discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2931): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9611","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9611","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT9611, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT9611, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 2931): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8216","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8216","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT8216, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT8216, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 2931): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3573","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3573","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT3573, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT3573, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 2931): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6584"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6584"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT6584, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT6584, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,W/bt-btif ( 3006): invalid rfc slot id: 86
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT3573
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2931): 2015-12-03T14:59:56.777Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x49
,I/        ( 2931): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT4731"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT4731"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT4731, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT4731, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 2931): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1345","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1345","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT1345, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT1345, WifiDirectName: , WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: G4-1
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [b4:ce:f6:ab:a4:6a]: 7, f, 6109
,W/bt-sdp  ( 3006): process_service_search_attr_rsp
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: HTC Desire 820
,E/bt-btif ( 3006): DISCOVERY_COMP_EVT slot id:89, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3006): invalid rfc slot id: 89
,I/BTConnectToThread( 2931): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2931): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2931): 2015-12-03T15:00:04.937Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:00:04.937Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:04.938Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:00:04.939Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:04.941Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2931): 
I/jxcore-log( 2931): ---- round done--------
I/jxcore-log( 2931): 
I/jxcore-log( 2931): ---- gotta redo : B4:CE:F6:AB:A4:6A, try count now: 1
I/jxcore-log( 2931): 
I/jxcore-log( 2931): do fake peer & start
I/jxcore-log( 2931): 
I/jxcore-log( 2931): Connect to fake peer: F4:F1:E1:5C:3B:E2
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:00:04.942Z SendDataConnector.js: Start called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:00:04.942Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:00:04.942Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: F4:F1:E1:5C:3B:E2, name: null
,I/        ( 2931): Connecting to null, at F4:F1:E1:5C:3B:E2
I/chromium( 2931): [INFO:CONSOLE(63)] "logCallback Round of send data to peer B4:CE:F6:AB:A4:6A done with result: Connection to B4:CE:F6:AB:A4:6A failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3006): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4186974 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3006): process_service_search_attr_rsp
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2931): Cleared service requests
I/        ( 2931): Started peer discovery
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 1
E/bt-btif ( 3006): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3006): Entering PendingCommandState State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device F4:F1:E1:5C:3B:E2 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for F4:F1:E1:5C:3B:E2, but we have no record of that device.
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [f8:95:c7:87:3c:51]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: G4-1
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 0
,D/BluetoothAdapterProperties( 3006): Failed to remove device: F4:F1:E1:5C:3B:E2
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3006): StableState(): Entering Off State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device F4:F1:E1:5C:3B:E2 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for F4:F1:E1:5C:3B:E2, but we have no record of that device.
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: HTC Desire 820
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4186974 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2931): Found 9 peers.
I/SS      ( 2931): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2931): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2931): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2931): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2931): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2931): Peer(6): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2931): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2931): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2931): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2931): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler },
I/        ( 2931): Added service request
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2931): Starting to Handshake
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2931): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4186974 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 2931): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 2931): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6584"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2931): HandshakeOk : motorola-XT1039_PT6584
I/HS      ( 2931): Hand Shake finished outgoing for : motorola-XT1039_PT6584
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : false, motorola-XT1039_PT6584
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2931): mHTTPPort  set to : 60118
I/BtConnectorHelper( 2931): Request socket is using : 60118
I/BtToRequestSocket( 2931): Now accepting connections
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/BtConnectorHelper( 2931): Calling ConnectionStatusUpdate with port :60118
I/jxcore-log( 2931): 2015-12-03T15:00:09.562Z SendDataConnector.js: CLIENT connected to 60118, error: null
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:00:09.563Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): incoming data from: /127.0.0.1, port: 60118
I/BtToRequestSocket( 2931): Set local streams
I/BtToRequestSocket( 2931): rin ended ---------------------------;
,I/jxcore-log( 2931): 2015-12-03T15:00:09.583Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2931): 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3006): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3006): Entering PendingCommandState State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3006): Failed to remove device: F8:95:C7:87:3C:51
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3006): StableState(): Entering Off State
,E/BluetoothEventManager( 3038): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/        ( 2931): Started service discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,D/        ( 3006): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24978
,I/jxcore-log( 2931): 2015-12-03T15:00:10.597Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2931): 
,I/BTListenerThread( 2931): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3573","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : LGE-LG-H815_PT3573
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, LGE-LG-H815_PT3573
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/jxcore-log( 2931): 2015-12-03T15:00:11.346Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
,I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/jxcore-log( 2931): 2015-12-03T15:00:11.581Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2931): 
,D/        ( 3006): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14088
,I/jxcore-log( 2931): 2015-12-03T15:00:11.589Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:12.009Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:12.068Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:12.077Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:12.160Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:12.498Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,D/        ( 3006): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4188
,I/jxcore-log( 2931): 2015-12-03T15:00:13.041Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:13.425Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2931): 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2931): 2015-12-03T15:00:13.952Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:14.320Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): dm_pm_timer expires
W/bt-btif ( 3006): dm_pm_timer expires 0
W/bt-btif ( 3006): proc dm_pm_timer expires
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4186974 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4186974 rs_disc_pending=1
,W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2931): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6584"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : motorola-XT1039_PT6584
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, motorola-XT1039_PT6584
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/jxcore-log( 2931): 2015-12-03T15:00:22.126Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
I/BtToRequestSocket( 2931): --DoOneRunRound ended
,W/bt-btif ( 3006): invalid rfc slot id: 88
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT3573
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2931): 2015-12-03T15:00:22.190Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:22.981Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:22.997Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:00:22.999Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:23.007Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:23.060Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:23.070Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:23.143Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:23.154Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:23.163Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:23.173Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:23.183Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:23.217Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:23.223Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:23.327Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:23.334Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:23.346Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:23.385Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:23.529Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:23.536Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:23.546Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:23.579Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:23.586Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:23.598Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:23.628Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:23.665Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:23.678Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:23.688Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:23.696Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:23.718Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 2931): 
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x47
,I/jxcore-log( 2931): 2015-12-03T15:00:23.756Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:23.771Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:23.785Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:23.818Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:23.833Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:23.907Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:23.917Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:23.955Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:24.319Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:00:24.320Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:00:24.321Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:00:24.321Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:00:24.322Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2931): 
,I/BtToSocketBase( 2931): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2931): Disconnect outgoing peer: motorola-XT1039_PT6584
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
,I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
I/BtToRequestSocket( 2931): Close server socket
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4186974 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): bta_jv_rfc_port_to_cb(port_handle:0x1e):jv handle:0x0 not FOUND
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: G4-1
,I/jxcore-log( 2931): 2015-12-03T15:00:29.322Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:00:29.323Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [f8:95:c7:87:3c:51]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: G4-1
,W/bt-btif ( 3006): invalid rfc slot id: 91
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT6584
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2931): 2015-12-03T15:00:34.028Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:34.330Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:00:34.331Z SendDataConnector.js: Connect (retry count 1) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:00:34.332Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:00:34.332Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: F4:F1:E1:5C:3B:E2, name: XT1039
,I/        ( 2931): Connecting to XT1039, at F4:F1:E1:5C:3B:E2
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4186974 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3006): process_service_search_attr_rsp
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:1
,I/BTConnectToThread( 2931): Starting to Handshake
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2931): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTConnectToThread( 2931): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 2931): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6584"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2931): HandshakeOk : motorola-XT1039_PT6584
I/HS      ( 2931): Hand Shake finished outgoing for : motorola-XT1039_PT6584
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : false, motorola-XT1039_PT6584
,I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2931): mHTTPPort  set to : 52545
I/BtConnectorHelper( 2931): Request socket is using : 52545
I/BtToRequestSocket( 2931): Now accepting connections
,I/BtConnectorHelper( 2931): Calling ConnectionStatusUpdate with port :52545
I/jxcore-log( 2931): 2015-12-03T15:00:35.362Z SendDataConnector.js: CLIENT connected to 52545, error: null
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:00:35.363Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): incoming data from: /127.0.0.1, port: 52545
I/BtToRequestSocket( 2931): Set local streams
I/BtToRequestSocket( 2931): rin ended ---------------------------;
,I/jxcore-log( 2931): 2015-12-03T15:00:35.384Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2931): 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa41867ac rs_disc_pending=1
,W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): dm_pm_timer expires
W/bt-btif ( 3006): dm_pm_timer expires 0
,W/bt-btif ( 3006): proc dm_pm_timer expires
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3006): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3006): Entering PendingCommandState State
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3038): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/BluetoothBondStateMachine( 3006): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3006): Failed to remove device: F8:95:C7:87:3C:51
,W/BluetoothEventManager( 3038): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 3006): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3006): StableState(): Entering Off State
,E/BluetoothEventManager( 3038): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTListenerThread( 2931): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3573","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : LGE-LG-H815_PT3573
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, LGE-LG-H815_PT3573
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/jxcore-log( 2931): 2015-12-03T15:00:41.977Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
,I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/jxcore-log( 2931): 2015-12-03T15:00:42.446Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:42.566Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:42.666Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:42.892Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:42.900Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:43.118Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTListenerThread( 2931): got MESSAGE_READ 81 bytes.
,I/BTListenerThread( 2931): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6584"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : motorola-XT1039_PT6584
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, motorola-XT1039_PT6584
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/jxcore-log( 2931): 2015-12-03T15:00:44.787Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
,I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/jxcore-log( 2931): 2015-12-03T15:00:45.281Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:45.290Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:45.311Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2931): ,
,I/jxcore-log( 2931): 2015-12-03T15:00:45.320Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:45.450Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:00:45.451Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:00:45.452Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:00:45.452Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:00:45.453Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2931): 
,I/BtToSocketBase( 2931): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2931): Disconnect outgoing peer: motorola-XT1039_PT6584
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
I/BtToRequestSocket( 2931): Close server socket
,W/bt-btif ( 3006): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,I/jxcore-log( 2931): 2015-12-03T15:00:50.453Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:00:50.454Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): invalid rfc slot id: 92
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT3573
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2931): 2015-12-03T15:00:53.231Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x40 current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x40
,W/bt-btif ( 3006): invalid rfc slot id: 94
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1,
,I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT6584
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2931): 2015-12-03T15:00:55.255Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:00:55.458Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:00:55.459Z SendDataConnector.js: Connect (retry count 2) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:00:55.459Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:00:55.460Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: F4:F1:E1:5C:3B:E2, name: XT1039
,I/        ( 2931): Connecting to XT1039, at F4:F1:E1:5C:3B:E2
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-sdp  ( 3006): process_service_search_attr_rsp
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:1
,I/BTConnectToThread( 2931): Starting to Handshake
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2931): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTConnectToThread( 2931): got MESSAGE_READ 81 bytes.
,I/BTConnectToThread( 2931): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6584"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2931): HandshakeOk : motorola-XT1039_PT6584
I/HS      ( 2931): Hand Shake finished outgoing for : motorola-XT1039_PT6584
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : false, motorola-XT1039_PT6584
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2931): mHTTPPort  set to : 35077
I/BtConnectorHelper( 2931): Request socket is using : 35077
I/BtToRequestSocket( 2931): Now accepting connections
,I/BtConnectorHelper( 2931): Calling ConnectionStatusUpdate with port :35077
I/jxcore-log( 2931): 2015-12-03T15:00:56.209Z SendDataConnector.js: CLIENT connected to 35077, error: null
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:00:56.210Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): incoming data from: /127.0.0.1, port: 35077
I/BtToRequestSocket( 2931): Set local streams
I/BtToRequestSocket( 2931): rin ended ---------------------------;
,I/jxcore-log( 2931): 2015-12-03T15:00:56.232Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: G4-1
,W/bt-btif ( 3006): dm_pm_timer expires
W/bt-btif ( 3006): dm_pm_timer expires 0
,W/bt-btif ( 3006): proc dm_pm_timer expires
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTListenerThread( 2931): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6584"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : motorola-XT1039_PT6584
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, motorola-XT1039_PT6584
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/jxcore-log( 2931): 2015-12-03T15:01:06.229Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/jxcore-log( 2931): 2015-12-03T15:01:06.299Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:01:06.299Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:01:06.299Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:01:06.299Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:01:06.299Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2931): 
,I/BtToSocketBase( 2931): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2931): Disconnect outgoing peer: motorola-XT1039_PT6584
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
I/BtToRequestSocket( 2931): Close server socket
,W/bt-btif ( 3006): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,I/jxcore-log( 2931): 2015-12-03T15:01:06.614Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:06.621Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:06.627Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:06.633Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:06.640Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,I/        ( 2931): Cleared service requests
I/        ( 2931): Started peer discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2931): Found 11 peers.
I/SS      ( 2931): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2931): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2931): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2931): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2931): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2931): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2931): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2931): Peer(8): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2931): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2931): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2931): Peer(11): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2931): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2931): Added service request
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2931): Started service discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2931): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT4785"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT4785"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT4785, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT4785, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,I/jxcore-log( 2931): 2015-12-03T15:01:11.300Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:01:11.300Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:16.306Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:01:16.307Z SendDataConnector.js: Connect (retry count 3) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:01:16.307Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:01:16.308Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: F4:F1:E1:5C:3B:E2, name: XT1039
,I/        ( 2931): Connecting to XT1039, at F4:F1:E1:5C:3B:E2
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3006): invalid rfc slot id: 95
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT6584
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2931): 2015-12-03T15:01:16.747Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,W/bt-sdp  ( 3006): process_service_search_attr_rsp
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:1
,I/BTConnectToThread( 2931): Starting to Handshake
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2931): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTConnectToThread( 2931): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 2931): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6584"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2931): HandshakeOk : motorola-XT1039_PT6584
I/HS      ( 2931): Hand Shake finished outgoing for : motorola-XT1039_PT6584
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : false, motorola-XT1039_PT6584
,I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2931): mHTTPPort  set to : 55453
,I/BtConnectorHelper( 2931): Request socket is using : 55453
I/BtToRequestSocket( 2931): Now accepting connections
,I/BtConnectorHelper( 2931): Calling ConnectionStatusUpdate with port :55453
I/jxcore-log( 2931): 2015-12-03T15:01:17.217Z SendDataConnector.js: CLIENT connected to 55453, error: null
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:01:17.218Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): incoming data from: /127.0.0.1, port: 55453
I/BtToRequestSocket( 2931): Set local streams
I/BtToRequestSocket( 2931): rin ended ---------------------------;
,I/jxcore-log( 2931): 2015-12-03T15:01:17.237Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2931): 
,I/        ( 2931): Cleared service requests
I/        ( 2931): Started peer discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2931): Found 12 peers.
I/SS      ( 2931): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2931): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2931): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2931): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2931): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2931): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2931): Peer(7): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2931): Peer(8): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2931): Peer(9): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2931): Peer(10): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2931): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2931): Peer(12): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2931): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2931): Added service request
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2931): Started service discovery
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 3006): dm_pm_timer expires
W/bt-btif ( 3006): dm_pm_timer expires 0
W/bt-btif ( 3006): proc dm_pm_timer expires
,I/jxcore-log( 2931): 2015-12-03T15:01:27.334Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:01:27.335Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:01:27.335Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:01:27.336Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:01:27.337Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2931): 
,I/BtToSocketBase( 2931): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 2931): Disconnect outgoing peer: motorola-XT1039_PT6584
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
,I/BtToSocketBase( 2931): Close local in
,I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
I/BtToRequestSocket( 2931): Close server socket
,W/bt-btif ( 3006): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
I/BTListenerThread( 2931): got MESSAGE_READ 81 bytes.
,I/BTListenerThread( 2931): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6584"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : motorola-XT1039_PT6584
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, motorola-XT1039_PT6584
,I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/jxcore-log( 2931): 2015-12-03T15:01:27.820Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/jxcore-log( 2931): 2015-12-03T15:01:28.228Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:28.237Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:28.243Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [34:fc:ef:11:b1:66]: 7, f, 6109
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Nexus 5
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4186254 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/jxcore-log( 2931): 2015-12-03T15:01:32.337Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:01:32.338Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4186254 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4186254 rs_disc_pending=0
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2931): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT4785"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : LGE-Nexus 5_PT4785
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, LGE-Nexus 5_PT4785
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/jxcore-log( 2931): 2015-12-03T15:01:32.769Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
,I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/jxcore-log( 2931): 2015-12-03T15:01:33.782Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:33.818Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:33.855Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:33.863Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:33.871Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:33.882Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:33.915Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:33.940Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:33.992Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:34.062Z SendDataTCPServer.js: TCP/IP server has received 24576 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:34.121Z SendDataTCPServer.js: TCP/IP server has received 26556 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:34.130Z SendDataTCPServer.js: TCP/IP server has received 30516 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:34.142Z SendDataTCPServer.js: TCP/IP server has received 34476 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:34.176Z SendDataTCPServer.js: TCP/IP server has received 36456 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:34.182Z SendDataTCPServer.js: TCP/IP server has received 38436 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:34.225Z SendDataTCPServer.js: TCP/IP server has received 40416 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:34.278Z SendDataTCPServer.js: TCP/IP server has received 42396 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:34.330Z SendDataTCPServer.js: TCP/IP server has received 44376 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:34.371Z SendDataTCPServer.js: TCP/IP server has received 46356 bytes of data
I/jxcore-log( 2931): 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2931): 2015-12-03T15:01:34.410Z SendDataTCPServer.js: TCP/IP server has received 48336 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:34.418Z SendDataTCPServer.js: TCP/IP server has received 52296 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:34.452Z SendDataTCPServer.js: TCP/IP server has received 54276 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:34.607Z SendDataTCPServer.js: TCP/IP server has received 56256 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:34.612Z SendDataTCPServer.js: TCP/IP server has received 58236 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:34.620Z SendDataTCPServer.js: TCP/IP server has received 60216 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:34.623Z SendDataTCPServer.js: TCP/IP server has received 62196 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:34.655Z SendDataTCPServer.js: TCP/IP server has received 68136 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:34.662Z SendDataTCPServer.js: TCP/IP server has received 70116 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:34.713Z SendDataTCPServer.js: TCP/IP server has received 72096 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:34.841Z SendDataTCPServer.js: TCP/IP server has received 74076 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:34.851Z SendDataTCPServer.js: TCP/IP server has received 76056 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:34.855Z SendDataTCPServer.js: TCP/IP server has received 78036 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:34.898Z SendDataTCPServer.js: TCP/IP server has received 80016 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:34.969Z SendDataTCPServer.js: TCP/IP server has received 81996 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:35.007Z SendDataTCPServer.js: TCP/IP server has received 83976 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:35.014Z SendDataTCPServer.js: TCP/IP server has received 85956 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:35.050Z SendDataTCPServer.js: TCP/IP server has received 87936 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:35.061Z SendDataTCPServer.js: TCP/IP server has received 89916 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:35.159Z SendDataTCPServer.js: TCP/IP server has received 91896 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:35.171Z SendDataTCPServer.js: TCP/IP server has received 93876 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:35.256Z SendDataTCPServer.js: TCP/IP server has received 95856 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:35.371Z SendDataTCPServer.js: TCP/IP server has received 97836 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:35.449Z SendDataTCPServer.js: TCP/IP server has received 99816 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:35.461Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:37.341Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:01:37.342Z SendDataConnector.js: Connect (retry count 4) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:01:37.342Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:01:37.343Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: F4:F1:E1:5C:3B:E2, name: XT1039
,I/        ( 2931): Connecting to XT1039, at F4:F1:E1:5C:3B:E2
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-sdp  ( 3006): process_service_search_attr_rsp
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:1
,I/BTConnectToThread( 2931): Starting to Handshake
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2931): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTConnectToThread( 2931): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 2931): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6584"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2931): HandshakeOk : motorola-XT1039_PT6584
I/HS      ( 2931): Hand Shake finished outgoing for : motorola-XT1039_PT6584
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : false, motorola-XT1039_PT6584
,I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2931): mHTTPPort  set to : 57270
I/BtConnectorHelper( 2931): Request socket is using : 57270
,I/BtToRequestSocket( 2931): Now accepting connections
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4186254 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/BtConnectorHelper( 2931): Calling ConnectionStatusUpdate with port :57270
I/jxcore-log( 2931): 2015-12-03T15:01:38.214Z SendDataConnector.js: CLIENT connected to 57270, error: null
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:01:38.215Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): incoming data from: /127.0.0.1, port: 57270
I/BtToRequestSocket( 2931): Set local streams
I/BtToRequestSocket( 2931): rin ended ---------------------------;
,I/jxcore-log( 2931): 2015-12-03T15:01:38.234Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): invalid rfc slot id: 97
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT6584
,I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2931): 2015-12-03T15:01:38.330Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): dm_pm_timer expires
W/bt-btif ( 3006): dm_pm_timer expires 1
,W/bt-btif ( 3006): proc dm_pm_timer expires
,W/bt-btif ( 3006): invalid rfc slot id: 99
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT4785
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2931): 2015-12-03T15:01:45.508Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x4e current:0x0
,W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x4e
,I/jxcore-log( 2931): 2015-12-03T15:01:48.327Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:01:48.328Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:01:48.329Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:48.347Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:01:48.347Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:01:48.348Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
I/BtConnectorHelper( 2931): Disconnect outgoing peer: F4:F1:E1:5C:3B:E2
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2931): Close LocalOutputStream
,I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
I/BtToRequestSocket( 2931): Close server socket
I/jxcore-log( 2931): 2015-12-03T15:01:48.382Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2931): 
I/jxcore-log( 2931): ---- round done--------
I/jxcore-log( 2931): 
I/jxcore-log( 2931): ---- gotta redo : F4:F1:E1:5C:3B:E2, try count now: 1
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): do fake peer & start
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:48.391Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:01:48.398Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:01:48.398Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: 44:80:EB:7B:5A:05, name: XT1072
,I/        ( 2931): Connecting to XT1072, at 44:80:EB:7B:5A:05
I/jxcore-log( 2931): 2015-12-03T15:01:48.401Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2931): 
,I/chromium( 2931): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F4:F1:E1:5C:3B:E2 done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3006): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTListenerThread( 2931): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6584"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : motorola-XT1039_PT6584
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, motorola-XT1039_PT6584
,I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
,I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/jxcore-log( 2931): 2015-12-03T15:01:50.010Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
,I/BtToRequestSocket( 2931): --DoOneRunRound ended
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Nexus 5
,I/jxcore-log( 2931): 2015-12-03T15:01:51.325Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:51.478Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:51.615Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:51.750Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:51.816Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:52.121Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,W/bt-sdp  ( 3006): SDP - Rcvd conn cnf with error: 0x4  CID 0x44
E/bt-btif ( 3006): DISCOVERY_COMP_EVT slot id:102, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3006): invalid rfc slot id: 102
,I/BTConnectToThread( 2931): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2931): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2931): 2015-12-03T15:01:53.546Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:01:53.547Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:01:53.547Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Nexus 5
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTListenerThread( 2931): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT4785"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : LGE-Nexus 5_PT4785
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, LGE-Nexus 5_PT4785
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
,I/jxcore-log( 2931): 2015-12-03T15:01:55.913Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/jxcore-log( 2931): 2015-12-03T15:01:56.287Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:56.291Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:56.300Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:56.375Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:56.387Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:56.424Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:01:58.548Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:01:58.548Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2931): 
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3006): invalid rfc slot id: 100
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT6584
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2931): 2015-12-03T15:02:00.750Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x45
,I/jxcore-log( 2931): 2015-12-03T15:02:03.552Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:02:03.552Z SendDataConnector.js: Connect (retry count 1) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:02:03.553Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:02:03.553Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: 44:80:EB:7B:5A:05, name: XT1072
,I/        ( 2931): Connecting to XT1072, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: XT1039
,W/bt-btif ( 3006): invalid rfc slot id: 103
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT4785
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
,I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2931): 2015-12-03T15:02:06.451Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x40 current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x40
,W/bt-sdp  ( 3006): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 3006): DISCOVERY_COMP_EVT slot id:105, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3006): invalid rfc slot id: 105
,I/BTConnectToThread( 2931): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2931): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2931): 2015-12-03T15:02:08.729Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:02:08.730Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:02:08.730Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2931): 
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Nexus 5
,I/jxcore-log( 2931): 2015-12-03T15:02:13.731Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:02:13.732Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Nexus 5
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2931): we got incoming connection
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
I/BTListenerThread( 2931): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTListenerThread( 2931): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 2931): Got JSON from encryption:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT4785"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2931): MESSAGE_WRITE 77 bytes.
I/HS      ( 2931): Incoming connection Hand Shake finished for : LGE-Nexus 5_PT4785
I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : true, LGE-Nexus 5_PT4785
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BTConnectedThread
I/BtConnectorHelper( 2931): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2931): --DoOneRunRound started
,I/BtToRequestSocket( 2931): LocalHost address: localhost/127.0.0.1, port: 60555
I/BtToRequestSocket( 2931): --DoOneRunRound ended
,I/jxcore-log( 2931): 2015-12-03T15:02:17.242Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:02:17.676Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:02:17.703Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:02:17.732Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:02:17.760Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:02:17.790Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:02:17.813Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:02:18.734Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:02:18.735Z SendDataConnector.js: Connect (retry count 2) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:02:18.735Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:02:18.736Z SendDataConnector.js: do connect now
I/jxcore-log( 2931): 
,I/        ( 2931): Selected device address: 44:80:EB:7B:5A:05, name: XT1072
,I/        ( 2931): Connecting to XT1072, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 2931): Starting to connect
W/BluetoothAdapter( 2931): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3006): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4186254 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): info:x10
,D/        ( 3006): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: XT1072
,W/bt-sdp  ( 3006): process_service_search_attr_rsp
,W/bt-btif ( 3006): new conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3006): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2931): Starting to Handshake
I/BTHandshakeSocketThread( 2931): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2931): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread started
,I/BTConnectToThread( 2931): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 2931): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8266","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2931): HandshakeOk : motorola-XT1072_PT8266
I/HS      ( 2931): Hand Shake finished outgoing for : motorola-XT1072_PT8266
,I/BtConnectorHelper( 2931): Starting the connected thread incoming : false, motorola-XT1072_PT8266
I/BtToSocketBase( 2931): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2931): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 2931): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2931): mHTTPPort  set to : 43530
I/BtConnectorHelper( 2931): Request socket is using : 43530
I/BtToRequestSocket( 2931): Now accepting connections
,I/BtConnectorHelper( 2931): Calling ConnectionStatusUpdate with port :43530
I/jxcore-log( 2931): 2015-12-03T15:02:20.171Z SendDataConnector.js: CLIENT connected to 43530, error: null
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:02:20.171Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2931): 
,I/BtToRequestSocket( 2931): incoming data from: /127.0.0.1, port: 43530
I/BtToRequestSocket( 2931): Set local streams
I/BtToRequestSocket( 2931): rin ended ---------------------------;
,I/jxcore-log( 2931): 2015-12-03T15:02:20.191Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2931): 
,D/        ( 3006): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 2931): 2015-12-03T15:02:20.692Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2931): 
,D/        ( 3006): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:16786
,I/jxcore-log( 2931): 2015-12-03T15:02:20.748Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:02:20.750Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2931): 
,D/        ( 3006): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:9856
,I/jxcore-log( 2931): 2015-12-03T15:02:20.775Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2931): 
,D/        ( 3006): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2926
,I/jxcore-log( 2931): 2015-12-03T15:02:20.888Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2931): 
,I/        ( 2931): Cleared service requests
I/        ( 2931): Started peer discovery
,I/jxcore-log( 2931): 2015-12-03T15:02:20.926Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2931): 
I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2931): 2015-12-03T15:02:20.992Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:02:21.130Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:02:21.140Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2931): 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,I/SS      ( 2931): Found 5 peers.
I/SS      ( 2931): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2931): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2931): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2931): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2931): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
,D/WifiP2pManager( 2931): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2931): Added service request
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2931): Started service discovery
,I/        ( 2931): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6584"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6584"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT6584, peerAddress: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT6584, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2931): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8216","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8216","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT8216, peerAddress: B0:C5:59:3F:75:69
,I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT8216, WifiDirectName: , WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 2931): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3573","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3573","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT3573, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT3573, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185ec4 rs_disc_pending=0
,W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3006): dm_pm_timer expires
W/bt-btif ( 3006): dm_pm_timer expires 1
W/bt-btif ( 3006): proc dm_pm_timer expires
,I/jxcore-log( 2931): timeout now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): dun
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): weAreDoneNow , resultArray.length: 1
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): done, now sending data to server
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector sendData called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): -- RESULT DATA {"name:":"LGE-Nexus 5_PT3779","time":1000080,"result":"TIMEOUT","sendList":[{"name":"58:2A:F7:ED:96:BE","time":20839,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:9D:93:0B","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"80:01:84:8A:B3:68","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":1,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":1,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":1,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":1,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":1,"na
,I/jxcore-log( 2931): sendList : 100% : 20839 ms, 99% : 20839 ms, 95 : 20839 ms, 90% : 20839 ms.
I/jxcore-log( 2931): 
I/jxcore-log( 2931): Result count 1, range 20839 ms to  20839 ms.
I/jxcore-log( 2931): 
I/jxcore-log( 2931): sendList failed peers count : 10 [90.9090909090909 %]
I/jxcore-log( 2931): 
I/jxcore-log( 2931): - Peer ID : 44:80:EB:7B:5A:05, Tried : 1
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): - Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
I/jxcore-log( 2931): 
I/jxcore-log( 2931): - Peer ID : B0:C5:59:3F:75:69, Tried : 1
I/jxcore-log( 2931): 
I/jxcore-log( 2931): - Peer ID : 08:EC:A9:50:75:41, Tried : 1
I/jxcore-log( 2931): 
I/jxcore-log( 2931): - Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
I/jxcore-log( 2931): 
I/jxcore-log( 2931): - Peer ID : E0:DB:10:14:E2:C0, Tried : 1
I/jxcore-log( 2931): 
I/jxcore-log( 2931): - Peer ID : 34:FC:EF:11:B1:66, Tried : 1
I/jxcore-log( 2931): 
I/jxcore-log( 2931): - Peer ID : 08:EC:A9:50:76:27, Tried : 1
I/jxcore-log( 2931): 
I/jxcore-log( 2931): - Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
I/jxcore-log( 2931): 
I/jxcore-log( 2931): - Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
I/jxcore-log( 2931): 
I/jxcore-log( 2931): sendList never tried peers count : 6 [35.294117647058826 %]
I/jxcore-log( 2931): 
I/jxcore-log( 2931): - Peer ID : 34:FC:EF:9D:93:0B
I/jxcore-log( 2931): 
I/jxcore-log( 2931): - Peer ID : 7C:F9:0E:34:8A:A0
I/jxcore-log( 2931): 
I/jxcore-log( 2931): - Peer ID : 80:01:84:8A:B3:68
I/jxcore-log( 2931): 
I/jxcore-log( 2931): - Peer ID : 58:3F:54:73:64:C0
I/jxcore-log( 2931): 
I/jxcore-log( 2931): - Peer ID : F8:95:C7:87:3C:51
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): - Peer ID : F8:95:C7:87:85:54
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:02:26.688Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:02:26.688Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 2931): 
I/jxcore-log( 2931): 2015-12-03T15:02:26.688Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2931): 
,I/BtConnectorHelper( 2931): Disconnect outgoing peer: 44:80:EB:7B:5A:05
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
I/BtToSocketBase( 2931): Close local in
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
I/BtToRequestSocket( 2931): Close server socket
I/jxcore-log( 2931): 2015-12-03T15:02:26.694Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2931): 
,I/chromium( 2931): [INFO:CONSOLE(63)] "logCallback *** TIMEOUT ***", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 2931): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 2931): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9611","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9611","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT9611, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT9611, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,W/bt-btif ( 3006): invalid rfc slot id: 104
,I/BtToSocketBase( 2931): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2931): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT4785
I/BtToSocketBase( 2931): Stop ReceivingThread
I/BtToSocketBase( 2931): Stop SendingThread
,I/BtToSocketBase( 2931): Close local in
I/BtToSocketBase( 2931): Close LocalOutputStream
I/BtToSocketBase( 2931): Close localHostSocket
I/BtToSocketBase( 2931): Close bt in
I/BtToSocketBase( 2931): Close bt out
I/BtToSocketBase( 2931): Close bt socket
,I/BtToSocketBase( 2931): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2931): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2931): 2015-12-03T15:02:26.882Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2931): 
,W/bt-btif ( 3006): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,W/bt-rfcomm( 3006): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
W/bt-rfcomm( 3006): RFCOMM_DisconnectInd LCID:0x49
,E/bt-btm  ( 3006): tBTM_SEC_DEV:0xa4185ec4 rs_disc_pending=1
W/bt-btif ( 3006): bta_dm_check_av:0
,W/bt-btif ( 3006): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: Nexus 5
,E/bt-btm  ( 3006): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3006): onReceive
,I/BTConnectionReceiver( 1352): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1352): Bluetooth Device Name: XT1072
,I/        ( 2931): Cleared service requests
I/        ( 2931): Started peer discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2931): Found 6 peers.
I/SS      ( 2931): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2931): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2931): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2931): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2931): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2931): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2931): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2931): Added service request
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2931): Started service discovery
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2931): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT6494"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT6494"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT6494, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT6494, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 2931): Cleared service requests
I/        ( 2931): Started peer discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2931): Found 8 peers.
I/SS      ( 2931): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2931): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
,I/SS      ( 2931): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2931): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2931): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2931): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2931): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2931): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2931): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2931): Added service request
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2931): Started service discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 2931): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2273","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2273","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT2273, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT2273, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 2931): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1345","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1345","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT1345, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT1345, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/        ( 2931): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT6494"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT6494"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT6494, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT6494, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 2931): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT7284","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT7284","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT7284, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT7284, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 2931): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8216","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 2931): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8216","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT8216, peerAddress: B0:C5:59:3F:75:69
,I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT8216, WifiDirectName: , WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 2931): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3573","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 2931): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3573","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT3573, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT3573, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 2931): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8266","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8266","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT8266, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT8266, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 2931): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6666","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6666","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT6666, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT6666, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 2931): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6584"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6584"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT6584, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT6584, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2931): Cleared service requests
I/        ( 2931): Started peer discovery
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2931): Found 12 peers.
I/SS      ( 2931): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2931): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2931): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2931): Peer(4): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2931): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2931): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2931): Peer(7): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2931): Peer(8): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2931): Peer(9): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2931): Peer(10): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2931): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2931): Peer(12): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2931): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2931): Added service request
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2931): Started service discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2931): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2273","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2273","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT2273, peerAddress: 7C:F9:0E:37:96:AB
,I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT2273, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 2931): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9611","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9611","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT9611, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT9611, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 2931): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6666","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6666","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT6666, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT6666, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 2931): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6584"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6584"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT6584, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT6584, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-smp  ( 3006): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3006): Plain text(LSB ~ MSB) = 3e 47 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3006): Encrypted text(LSB ~ MSB) = 3f 17 9b d6 6b d5 63 85 38 d1 d8 1e 76 63 8f a3 
,W/bt-btm  ( 3006): Stopping oneshot timer
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2931): Cleared service requests
I/        ( 2931): Started peer discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2931): Found 13 peers.
I/SS      ( 2931): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2931): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2931): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2931): Peer(4): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2931): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2931): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2931): Peer(7): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2931): Peer(8): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2931): Peer(9): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2931): Peer(10): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2931): Peer(11): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2931): Peer(12): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2931): Peer(13): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2931): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2931): Added service request
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2931): Started service discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2931): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2273","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2273","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT2273, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT2273, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 2931): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9611","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9611","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT9611, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT9611, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 2931): Cleared service requests
I/        ( 2931): Started peer discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2931): Found 13 peers.
,I/SS      ( 2931): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2931): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2931): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2931): Peer(4): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2931): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2931): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2931): Peer(7): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2931): Peer(8): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2931): Peer(9): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2931): Peer(10): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2931): Peer(11): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2931): Peer(12): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2931): Peer(13): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2931): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2931): Added service request
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2931): Started service discovery
,I/        ( 2931): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2273","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2273","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT2273, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT2273, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 2931): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9611","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9611","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT9611, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT9611, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 2931): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT7284","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 2931): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT7284","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT7284, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT7284, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 2931): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8216","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8216","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT8216, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT8216, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 2931): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3573","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3573","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT3573, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT3573, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 2931): Cleared service requests
I/        ( 2931): Started peer discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 2931): Found 13 peers.
,I/SS      ( 2931): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 2931): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2931): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2931): Peer(4): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2931): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2931): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2931): Peer(7): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2931): Peer(8): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2931): Peer(9): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2931): Peer(10): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2931): Peer(11): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2931): Peer(12): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2931): Peer(13): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2931): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2931): Added service request
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2931): Started service discovery
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
,I/        ( 2931): Cleared service requests
I/        ( 2931): Started peer discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2931): Found 10 peers.
I/SS      ( 2931): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2931): Peer(2): A5-1 7e:f9:0e:37:96:ac
,I/SS      ( 2931): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b,
I/SS      ( 2931): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2931): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2931): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 2931): Peer(7): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2931): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2931): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2931): Peer(10): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2931): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2931): Added service request
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2931): Started service discovery
,I/        ( 2931): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT7284","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT7284","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT7284, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT7284, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 2931): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2273","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2273","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT2273, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT2273, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 2931): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT6494"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT6494"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT6494, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT6494, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 2931): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT4731"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT4731"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT4731, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT4731, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 2931): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9611","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 2931): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9611","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT9611, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT9611, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 2931): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6584"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6584"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT6584, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT6584, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 2931): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1345","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1345","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT1345, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT1345, WifiDirectName: , WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2931): Cleared service requests
I/        ( 2931): Started peer discovery
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 2931): Found 13 peers.
I/SS      ( 2931): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2931): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2931): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2931): Peer(4): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2931): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2931): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2931): Peer(7): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2931): Peer(8): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2931): Peer(9): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2931): Peer(10): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2931): Peer(11): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2931): Peer(12): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2931): Peer(13): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2931): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2931): Added service request
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2931): Started service discovery
,I/        ( 2931): Cleared service requests
I/        ( 2931): Started peer discovery
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 2931): Found 13 peers.
I/SS      ( 2931): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2931): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2931): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2931): Peer(4): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2931): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2931): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2931): Peer(7): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2931): Peer(8): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2931): Peer(9): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2931): Peer(10): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2931): Peer(11): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2931): Peer(12): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2931): Peer(13): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2931): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2931): Added service request
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3030): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2931): Started service discovery
,I/wpa_supplicant( 3030): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3030): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2931): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2273","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 2931): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2273","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT2273, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT2273, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 2931): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8266","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 2931): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8266","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT8266, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 2931): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT8266, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/jxcore-log( 2931): DBG, CoordinatorConnector command called
I/jxcore-log( 2931): 
I/jxcore-log( 2931): command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): stop tests now !
I/jxcore-log( 2931): 
I/jxcore-log( 2931): stop current!
I/jxcore-log( 2931): 
I/jxcore-log( 2931): testSendData stopped
I/jxcore-log( 2931): 
I/        ( 2931): Stoping All
I/        ( 2931): Stopping services
I/        ( 2931): Stopping services
,I/wpa_supplicant( 3030): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 3030): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/        ( 2931): Stop Bluetooth
I/        ( 2931): Stop Bluetooth
I/BTListenerThread( 2931): Stopped
,I/jxcore-log( 2931): StopBroadcasting went ok
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): 2015-12-03T15:06:46.932Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 2931): 
I/chromium( 2931): [INFO:CONSOLE(63)] "logCallback stop", source: file:///android_asset/www/js/thali_main.js (63)
I/        ( 2931): Cleared local services
I/        ( 2931): Cleared service requests
I/        ( 2931): Stopped peer discovery
,I/jxcore-log( 2931): DBG, CoordinatorConnector command called
I/jxcore-log( 2931): 
I/jxcore-log( 2931): command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"58:2A:F7:ED:96:BE\",\"time\":20839,\"result\":\"OK\",\"connections\":2,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[{\"connections\":1,\"name\":\"44:80:EB:7B:5A:05\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"00:F4:6F:30:E0:6C\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"B0:C5:59:3F:75:69\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"08:EC:A9:50:75:41\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"7C:F9:0E:37:96:AB\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"E0:DB:10:14:E2:C0\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"34:FC:EF:11:B1:66\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"08:EC:A9:50:76:27\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"B4:CE:F6:AB:A4:6A\",\"time\":0,\"result\":\"Fai
I/jxcore-log( 2931): ****TEST TOOK:  ms ****
I/jxcore-log( 2931): 
I/jxcore-log( 2931): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2931): 
I/jxcore-log( 2931): stop tests now !
I/jxcore-log( 2931): 
I/jxcore-log( 2931): end, event received
I/jxcore-log( 2931): 
I/jxcore-log( 2931): CoordinatorConnector close called
I/jxcore-log( 2931): 
,I/jxcore-log( 2931): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 2931): 
I/jxcore-log( 2931): The Coordinator has disconnected!
I/jxcore-log( 2931): 
I/jxcore-log( 2931): The Coordinator has closed!
I/jxcore-log( 2931): 
I/jxcore-log( 2931): stop tests now !
I/jxcore-log( 2931): 
I/jxcore-log( 2931): turning Radios off
I/jxcore-log( 2931): 
I/jxcore-log( 2931): Toggling radios to false
I/jxcore-log( 2931): 
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  761): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2ac13b9c mBinding = false
,D/BluetoothManagerService(  761): Message: 2
D/BluetoothManagerService(  761): Sending off request.
,D/BluetoothAdapterState( 3006): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3006): Setting state to 13
I/BluetoothAdapterState( 3006): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterProperties( 3006): onBluetoothDisable()
I/BluetoothAdapterState( 3006): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 3006): Scan Mode:20
,D/BluetoothAdapterState( 3006): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,V/BluetoothMapMasInstance( 3006): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3006): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3006): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 3006): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 3006): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 3006): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3006): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3006): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,D/btif_config_util( 3006): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/BtOppRfcommListener( 3006): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,W/bt-btif ( 3006): bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
W/bt-l2cap( 3006): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3006): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothManagerService(  761): Message: 60
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  761): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 3006): onReceive
D/BluetoothMapService( 3006): STATE_TURNING_OFF
V/BluetoothMapService( 3006): Handler(): got msg=4
D/BluetoothMapService( 3006): MAP Service closeService in
D/BluetoothMapMasInstance( 3006): MAP Service shutdown
V/BluetoothMapService( 3006): MAP Service closeService out
,I/BtOppRfcommListener( 3006): stopping Accept Thread
,I/BtOppRfcommListener( 3006): BluetoothSocket listen thread finished
,D/WifiService(  761): setWifiEnabled: false pid=2931, uid=10270
E/WifiService(  761): Invoking mWifiStateMachine.setWifiEnabled
W/ContextImpl( 3038): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,E/WifiStateMachine(  761): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
I/jxcore-log( 2931): Radios toggled
I/jxcore-log( 2931): 
I/chromium( 2931): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
E/native  (  761): do suspend true
,D/DockEventReceiver( 3038): finishStartingService: stopping service
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,W/bt-btif ( 3006): ag scb idx 1 not allocated
E/bt-btif ( 3006): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3006): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3006): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3006): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3006): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3006): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3006): L2CAP - PSM: 0x0017 not found for deregistration
,D/bt_userial( 3006): RX termination
W/bt_userial( 3006): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 3006): Leaving userial_read_thread()
D/bt_userial( 3006): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 3006): hw_epilog_process
,I/bt_userial_vendor( 3006): device fd = 53 close
,I/GKI_LINUX( 3006): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 3006): GKI_exit_task 0 done
I/GKI_LINUX( 3006): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 3006): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,V/NativeCrypto( 1412): Read error: ssl=0x9d37c800: I/O error during system call, Connection timed out
,D/BluetoothAdapterState( 3006): Stopping profile services that were post enabled
,D/AuthorizationBluetoothService( 1412): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,V/NativeCrypto( 1412): SSL shutdown failed: ssl=0x9d37c800: I/O error during system call, Broken pipe
E/WifiStateMachine(  761): scanCount==0 - aborting
,D/WifiNetworkAgent(  761): NetworkAgent: NetworkAgent channel lost
,D/WifiScanningService(  761): SCAN_AVAILABLE : 1
,D/WifiScanningService(  761): StartedState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  761): DefaultState
,D/RttService(  761): SCAN_AVAILABLE : 1
,D/BluetoothPbap( 3038): Proxy object disconnected
D/PbapServerProfile( 3038): Bluetooth service disconnected
,D/HeadsetService( 3006): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3006): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1e8544
,D/HeadsetStateMachine( 3006): Exit Disconnected: -1
,D/A2dpService( 3006): Received stop request...Stopping profile...
,D/BluetoothHeadset(  761): Proxy object disconnected
D/BluetoothAdapterService( 3006): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1e8544
,D/BluetoothHeadset( 1227): Proxy object disconnected
D/BluetoothA2dp(  761): Proxy object disconnected
,E/native  (  761): do suspend true
D/HidService( 3006): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3006): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1e8544
,D/HealthService( 3006): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3006): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1e8544
,D/A2dpStateMachine( 3006): Exit Disconnected: -1
,D/PanService( 3006): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3006): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1e8544
,D/RttService(  761): EnabledState got{ when=-23ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/BluetoothHeadset( 1194): Proxy object disconnected
D/BluetoothHeadset( 1194): Proxy object disconnected
,D/BtGatt.DebugUtils( 3006): handleDebugAction() action=null
D/BtGatt.GattService( 3006): Received stop request...Stopping profile...
D/BtGatt.GattService( 3006): stop()
D/BtGatt.AdvertiseManager( 3006): advertise clients cleared
,D/BluetoothAdapterService( 3006): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1e8544
,D/BluetoothHeadset( 3038): Proxy object disconnected
D/HeadsetProfile( 3038): Bluetooth service disconnected
D/BluetoothA2dp( 3038): Proxy object disconnected
,D/A2dpProfile( 3038): Bluetooth service disconnected
D/BluetoothInputDevice( 3038): Proxy object disconnected
D/HidProfile( 3038): Bluetooth service disconnected
,D/BluetoothPan( 3038): BluetoothPAN Proxy object disconnected
D/PanProfile( 3038): Bluetooth service disconnected
,D/BluetoothMapService( 3006): Received stop request...Stopping profile...
D/BluetoothMapService( 3006): stop()
D/BluetoothMapEmailAppObserver( 3006): deinitObservers()
,D/BluetoothMapEmailAppObserver( 3006): removeReceiver()
D/BluetoothAdapterService( 3006): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1e8544
,D/HeadsetStateMachine( 3006): Unbinding service...
,D/BluetoothMap( 3038): Proxy object disconnected
D/MapProfile( 3038): Bluetooth service disconnected
,W/BluetoothHeadsetServiceJni( 3006): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3006): Cleaning up Bluetooth Handsfree callback object
,D/ConnectivityService(  761): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,I/GKI_LINUX( 3006): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 3006): GKI_exit_task 2 done
I/GKI_LINUX( 3006): GKI_shutdown(): task [A2DP-MEDIA] terminated
,W/BluetoothHidServiceJni( 3006): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3006): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3006): Cleaning up Bluetooth GID callback object
,W/BluetoothHealthServiceJni( 3006): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3006): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3006): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3006): Cleaning up Bluetooth PAN callback object
,V/BluetoothMapService( 3006): Handler(): got msg=4
,D/BluetoothMapService( 3006): MAP Service closeService in
V/BluetoothMapService( 3006): MAP Service closeService out
D/BluetoothMapService( 3006): cleanup()
D/BluetoothMapService( 3006): MAP Service closeService in
V/BluetoothMapService( 3006): MAP Service closeService out
,D/BluetoothAdapterState( 3006): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3006): Setting state to 10
I/BluetoothAdapterState( 3006): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService(  761): Message: 60
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  761): Broadcasting onBluetoothStateChange(false) to 11 receivers.
D/BluetoothHeadset(  761): onBluetoothStateChange: up=false
I/BluetoothAdapterState( 3006): Entering OffState
D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/ConnectivityService(  761): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  761): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  761): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Disconnected - quitting
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524292
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  761): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/BluetoothHeadset( 3038): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1227): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1194): onBluetoothStateChange: up=false
,D/TelephonyNetworkFactory( 1227): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1557): CM callback handler got msg 524292
,D/BluetoothMap( 3038): onBluetoothStateChange: up=false
,D/AndroidRuntime( 4147): 
D/AndroidRuntime( 4147): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/BluetoothPbap( 3038): onBluetoothStateChange: up=false
D/BluetoothA2dp( 3038): onBluetoothStateChange: up=false
,D/AndroidRuntime( 4147): CheckJNI is OFF
,D/BluetoothA2dp(  761): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 3038): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1194): onBluetoothStateChange: up=false
D/BluetoothManagerService(  761): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  761): Broadcasting onBluetoothServiceDown() to 11 receivers.
,D/BluetoothManagerService(  761): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2ac13b9c mBinding = false
D/BluetoothManagerService(  761): Sending unbind request.
,D/BluetoothManagerService(  761): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter(  897): 1048708993: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  897): 1048708993: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  897): 1048708993: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1316): 1013129664: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1316): 1013129664: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 3006): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 3006): GKI_exit_task 1 done
I/GKI_LINUX( 3006): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3006): cleanupNative: return from cleanup
,I/art     ( 3006): System.exit called, status: 0
I/AndroidRuntime( 3006): VM exiting with result code 0, cleanup skipped.
,W/ContextImpl( 3038): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver( 3038): finishStartingService: stopping service
,D/AndroidRuntime( 4147): Calling main entry com.android.commands.pm.Pm
,I/wpa_supplicant( 3030): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 3030): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,I/ActivityManager(  761): Process com.android.bluetooth (pid 3006) has died
,I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
,I/ActivityManager(  761): Killing 2931:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,W/PackageSettings(  761): Skipping PackageSetting{35e5f65f com.example.hello/10277} due to missing metadata
,I/WindowState(  761): WIN DEATH: Window{13018b81 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  761): Client connection lost with reason: 4
,D/Tethering(  761): InitialState.processMessage what=4
I/wpa_supplicant( 3030): wlan0: CTRL-EVENT-TERMINATING 
,I/ActivityManager(  761):   Force finishing activity ActivityRecord{36ad8d52 u0 com.test.thalitest/.MainActivity t214}
,W/ActivityManager(  761): Spurious death for ProcessRecord{6132107 2931:com.test.thalitest/u0a270}, curProc for 2931: null
,I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/ActivityManager(  761):   Force finishing activity ActivityRecord{36ad8d52 u0 com.test.thalitest/.MainActivity t214 f}
W/ActivityManager(  761): Duplicate finish request for ActivityRecord{36ad8d52 u0 com.test.thalitest/.MainActivity t214 f}
,I/art     ( 1275): Explicit concurrent mark sweep GC freed 3977(295KB) AllocSpace objects, 1(126KB) LOS objects, 23% free, 25MB/33MB, paused 224us total 16.589ms
,I/art     ( 1352): Explicit concurrent mark sweep GC freed 101843(5MB) AllocSpace objects, 20(343KB) LOS objects, 24% free, 19MB/25MB, paused 310us total 33.282ms
,I/Keyboard.Facilitator( 1093): resetDictionaries() : en_US
,I/InputReader(  761): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1316): Ignoring removeGeofence because network location is disabled.
,W/Settings( 1796): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/Tethering(  761): sendTetherStateChangedBroadcast 0, 0, 0
,W/Settings( 1316): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/BluetoothAdapter( 3038): 659539828: getState() :  mService = null. Returning STATE_OFF
,I/Adreno-EGL(  942): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/Keyboard.Facilitator.DecoderInitializer( 1093): run()
I/OpenGLRenderer(  942): Initialized EGL, version 1.4
,I/Decoder ( 1093): createOrResetDecoder
,I/art     (  761): Explicit concurrent mark sweep GC freed 93163(4MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 28MB/43MB, paused 1.301ms total 101.825ms
,D/OpenGLRenderer(  942): Enabling debug mode 0
,I/art     (  761): WaitForGcToComplete blocked for 110.739ms for cause Explicit
,I/ActivityManager(  761): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=4215 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/art     (  761): Explicit concurrent mark sweep GC freed 8558(420KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/42MB, paused 1.364ms total 74.336ms
I/art     (  761): WaitForGcToComplete blocked for 47.730ms for cause Explicit
,W/InputMethodManagerService(  761): Got RemoteException sending setActive(false) notification to pid 2931 uid 10270
,I/Keyboard.Facilitator( 1093): onFinishInput()
,D/BackupManagerService(  761): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  761): Receieved: android.intent.action.PACKAGE_REMOVED
,I/art     (  761): Explicit concurrent mark sweep GC freed 10116(498KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/42MB, paused 1.571ms total 73.189ms
,I/ConfigService( 1412): onCreate
,W/ResourcesManager( 4215): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/Launcher( 1275): Deferring update until onResume
,D/TaskPersister(  761): removeObsoleteFile: deleting file=214_task.xml
,W/ResourcesManager( 1275): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/AndroidRuntime( 4147): Shutting down VM
,W/ResourcesManager( 1275): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 1412): Classify the device as Phone.
,D/AdapterServiceConfig( 4215): Adding HeadsetService
D/AdapterServiceConfig( 4215): Adding A2dpService
,D/AdapterServiceConfig( 4215): Adding HidService
D/AdapterServiceConfig( 4215): Adding HealthService
D/AdapterServiceConfig( 4215): Adding PanService
D/AdapterServiceConfig( 4215): Adding GattService
D/AdapterServiceConfig( 4215): Adding BluetoothMapService
,I/ActivityManager(  761): Killing 2760:com.google.android.gms:car/u0a8 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10008/pid_2760/cgroup.procs: No such file or directory
,D/AuthorizationBluetoothService( 1412): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/Launcher( 1275): Deferring update until onResume
,W/FetchTask( 1412): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/VoicemailCleanupService( 1341): Cleaning up data for package: com.test.thalitest
,I/CheckinRequestBuilder( 1412): Classify the device as Phone.
,I/ActivityManager(  761): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=4246 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,W/FetchTask( 1412): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/CheckinRequestBuilder( 1412): Classify the device as Phone.
,W/FetchTask( 1412): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/UpdateIcingCorporaServi( 1352): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1275): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1c1e8544 new=com.google.android.velvet.VelvetApplication@1c1e8544
,I/CheckinRequestBuilder( 1412): Classify the device as Phone.
,I/ActivityManager(  761): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4268 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  761): Killing 2716:com.android.defcontainer/u0a5 (adj 15): empty #17
,W/FetchTask( 1412): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/CheckinRequestBuilder( 1412): Classify the device as Phone.
,W/libprocessgroup(  761): failed to open /acct/uid_10005/pid_2716/cgroup.procs: No such file or directory
,W/FetchTask( 1412): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,W/ContextImpl( 4268): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1093): run()
,D/PackageBroadcastService( 1557): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1557): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1557): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1557): Module APK com.google.android.play.games already loaded
,W/FileUtils( 4268): Failed to chmod(/data/data/com.android.keychain/databases/grants.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,E/SQLiteLog( 4268): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,D/ChimeraCfgMgr( 1557): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1557): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1557): Removing dialog suppression flag for package com.test.thalitest
,E/SQLiteLog( 1412): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 1412): Shutting down VM
,I/UpdateIcingCorporaServi( 1352): UpdateCorporaTask done [took 211 ms] updated apps [took 211 ms] 
,--------- beginning of crash
E/AndroidRuntime( 1412): FATAL EXCEPTION: main
E/AndroidRuntime( 1412): Process: com.google.process.gapps, PID: 1412
E/AndroidRuntime( 1412): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1412): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
E/AndroidRuntime( 1412): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 1412): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1355)
E/AndroidRuntime( 1412): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1412): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1412): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/AndroidRuntime( 1412): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1412): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1412): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/AndroidRuntime( 1412): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
E/AndroidRuntime( 1412): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1412): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1412): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1412): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1412): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1412): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1412): 	at com.google.android.gms.gcm.bq.a(SourceFile:310)
E/AndroidRuntime( 1412): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1412): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1412): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2579)
E/AndroidRuntime( 1412): 	... 9 more
,E/AndroidRuntime( 4268): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4268): Process: com.android.keychain, PID: 4268
E/AndroidRuntime( 4268): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4268): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 4268): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 4268): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 4268): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 4268): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 4268): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 4268): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:404)
E/AndroidRuntime( 4268): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/AndroidRuntime( 4268): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4268): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4268): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4268): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 1557): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/Process ( 1412): Sending signal. PID: 1412 SIG: 9
I/Process ( 4268): Sending signal. PID: 4268 SIG: 9
E/DriveAsyncService( 1557): disk I/O error (code 3850)
E/DriveAsyncService( 1557): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1557): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1557): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1557): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1557): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1557): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1557): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1557): 	at com.google.android.gms.drive.database.k.k(SourceFile:485)
E/DriveAsyncService( 1557): 	at com.google.android.gms.drive.database.k.b(SourceFile:460)
E/DriveAsyncService( 1557): 	at com.google.android.gms.drive.database.f.i(SourceFile:1516)
E/DriveAsyncService( 1557): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1557): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/DriveAsyncService( 1557): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1557): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1557): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1557): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1557): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DropBoxManagerService(  761): Can't write: system_app_crash
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
E/DropBoxManagerService(  761): Can't write: system_app_crash
E/DropBoxManagerService(  761): java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
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
E/SQLiteDatabase( 1557): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1557): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1557): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1557): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1557): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1557): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1557): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1557): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1557): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1557): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1557): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1557): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1557): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1557): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1557): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1557): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1557): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:68)
E/SQLiteDatabase( 1557): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1557): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1557): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1557): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1557): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1557): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1557): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1557): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1557): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1557): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1557): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1557): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1557): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1557): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1557): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1557): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteOpenHelper( 1557): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1557): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1557): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1557): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1557): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:68)
E/SQLiteOpenHelper( 1557): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1557): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1557): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1557): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1557): Opened phenotype.db in read-only mode
I/Keyboard.Facilitator.MainLanguageModelLoader( 1093): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1093): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1093): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1093): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1093): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1093): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1093): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1093): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1093): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1093): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1093): run()
I/StatsUtilsManager( 1093): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1093): shouldRecordStats() = Too Soon
D/WifiService(  761): Client connection lost with reason: 4
E/SQLiteLog( 1557): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/GAv4-SVC( 1557): Failed to update Analytics property: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SharedPreferencesImpl( 1557): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4-SVC( 1557): Job execution failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
E/SharedPreferencesImpl( 1557): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 1557): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 1557): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1557): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1557): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1557): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1557): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1557): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1557): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1557): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1557): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1557): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1557): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1557): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1557): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1557): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1557): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1557): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1557): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteDatabase( 1557): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1557): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1557): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1557): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1557): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1557): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1557): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1557): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1557): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1557): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1557): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1557): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1557): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1557): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1557): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1557): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1557): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1557): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteOpenHelper( 1557): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1557): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1557): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1557): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1557): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1557): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1557): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1557): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1557): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1557): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1557): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1557): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 1557): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1557): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1557): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 1557): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
E/SQLiteLog( 1557): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/GAv4-SVC( 1557): Failed to update Analytics property: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SharedPreferencesImpl( 1557): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
I/ActivityManager(  761): Process com.android.keychain (pid 4268) has died
E/GAv4-SVC( 1557): Job execution failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
E/SharedPreferencesImpl( 1557): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/ActivityManager(  761): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
E/lowmemorykiller(  169): Error opening /proc/1412/oom_score_adj; errno=2
I/ActivityThread( 1557): Removing dead content provider:android.content.ContentProviderProxy@157d8b13

```
