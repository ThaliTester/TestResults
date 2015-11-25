#### Test 51790364c93db41_thali02_LGE-Nexus 5 Logs


```
--------- beginning of system
W/ResourcesManager( 2880): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2880): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,--------- beginning of main
D/Finsky  ( 2395): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
I/ActivityManager(  759): Killing 2109:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
V/JNIHelp ( 2880): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
W/System  ( 2880): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2880): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  759): failed to open /acct/uid_1000/pid_2109/cgroup.procs: No such file or directory
V/GLSActivity( 1392): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 2943): 
D/AndroidRuntime( 2943): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2943): CheckJNI is OFF
D/AndroidRuntime( 2943): Calling main entry com.android.commands.am.Am
I/ActivityManager(  759): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/Icing   ( 1558): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/ActivityManager(  759): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2961 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2943): Shutting down VM
D/Icing   ( 1558): Loaded CLD2 Version V2.0 - 20141016
V/ActivityManager(  759): Display changed displayId=0
I/Icing   ( 1558): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/WebViewFactory( 2961): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2961): Time to load native libraries: 1 ms (timestamps 6903-6904)
I/LibraryLoader( 2961): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2961): Binding Chromium to main looper Looper (main, tid 1) {180412da}
I/LibraryLoader( 2961): Expected native library version number "",actual native library version number ""
I/chromium( 2961): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2961): Initializing chromium process, singleProcess=true
W/art     ( 2961): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2961): ApplicationContext is null in ApplicationStatus
,W/chromium( 2961): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 2961): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 2961): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2961): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 2961): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
D/BluetoothManagerService(  759): Message: 20
D/BluetoothManagerService(  759): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@17462846:true
D/BluetoothAdapter( 2961): 567642260: getState() :  mService = null. Returning STATE_OFF
W/art     ( 2961): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 2961): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 2961): CordovaWebView is running on device made by: LGE
W/art     ( 2961): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2961): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 2961): Render dirty regions requested: true
D/Atlas   ( 2961): Validating map...
W/chromium( 2961): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 2961): Initialized EGL, version 1.4
D/OpenGLRenderer( 2961): Enabling debug mode 0
I/Keyboard.Facilitator( 1060): onFinishInput()
W/IInputConnectionWrapper( 2961): showStatusIcon on inactive InputConnection
I/ActivityManager(  759): Displayed com.test.thalitest/.MainActivity: +433ms (total +54s809ms)
W/BindingManager( 2961): Cannot call determinedVisibility() - never saw a connection for the pid: 2961
D/JsMessageQueue( 2961): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 2961): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 2961): jxcore cordova android initializing
I/ActivityManager(  759): Killing 2200:com.google.android.youtube/u0a80 (adj 15): empty #17
W/libprocessgroup(  759): failed to open /acct/uid_10080/pid_2200/cgroup.procs: No such file or directory
,W/jxcore-log( 2961): Initializing JXcore engine
W/jxcore-log( 2961): JXcore engine is ready
,W/jxcore-log( 2961): Starting JXcore engine
,W/.test.thalitest( 2961): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7873]" dev="sockfs" ino=7873 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 2961): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/.test.thalitest( 2961): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9605]" dev="sockfs" ino=9605 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 2961): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18808]" dev="sockfs" ino=18808 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 2961): Platform android
W/jxcore-log( 2961): 
W/jxcore-log( 2961): Process ARCH arm
W/jxcore-log( 2961): 
,I/jxcore-log( 2961): JXcore Cordova bridge is ready!
I/jxcore-log( 2961): 
,W/jxcore-log( 2961): JXcore engine is started
I/Choreographer( 2961): Skipped 105 frames!  The application may be doing too much work on its main thread.
I/chromium( 2961): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 2961): Toggling radios to true
I/jxcore-log( 2961): 
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  759): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  759): Message: 1
D/BluetoothManagerService(  759): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  759): New client listening to asynchronous messages
D/WifiService(  759): setWifiEnabled: true pid=2961, uid=10270
E/WifiService(  759): Invoking mWifiStateMachine.setWifiEnabled
,I/ActivityManager(  759): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3030 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/SoftapController(  179): Softap fwReload - Ok
,D/CommandListener(  179): Setting iface cfg
D/CommandListener(  179): Trying to bring down wlan0
D/CommandListener(  179): Clearing all IP addresses on wlan0
I/jxcore-log( 2961): Radios toggled
I/jxcore-log( 2961): 
,W/ResourcesManager( 3030): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/AdapterServiceConfig( 3030): Adding HeadsetService
D/AdapterServiceConfig( 3030): Adding A2dpService
D/AdapterServiceConfig( 3030): Adding HidService
D/AdapterServiceConfig( 3030): Adding HealthService
D/AdapterServiceConfig( 3030): Adding PanService
D/AdapterServiceConfig( 3030): Adding GattService
D/AdapterServiceConfig( 3030): Adding BluetoothMapService
,I/wpa_supplicant( 3052): Successfully initialized wpa_supplicant
,D/BluetoothManagerService(  759): Message: 20
D/BluetoothManagerService(  759): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3a21df85:true
,D/BluetoothAdapterState( 3030): make
,I/bluedroid( 3030): init
,I/BluetoothAdapterState( 3030): Entering OffState
,I/bte_conf( 3030): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3030): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3030): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3030): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3030): get_profile_interface socket
I/bluedroid( 3030): get_profile_interface map_client
,I/GKI_LINUX( 3030): gki_task_entry task_id=1 [BTIF] starting
D/BluetoothAdapterProperties( 3030): Address is:34:FC:EF:11:AE:67
,D/BluetoothManagerService(  759): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  759): Stored Bluetooth name: Nexus 5
,D/BluetoothAdapterProperties( 3030): Name is: Nexus 5
,D/BluetoothManagerService(  759): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  759): Message: 40
,D/BluetoothManagerService(  759): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
I/bluedroid( 3030): config_hci_snoop_log
D/BluetoothManagerService(  759): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  759): Broadcasting onBluetoothServiceUp() to 9 receivers.
,D/BluetoothAdapterState( 3030): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3030): Setting state to 11
I/BluetoothAdapterState( 3030): Bluetooth adapter state changed: 10-> 11
,I/wpa_supplicant( 3052): rfkill: Cannot open RFKILL control device
,D/BluetoothBondStateMachine( 3030): make
D/BluetoothManagerService(  759): Message: 60
D/BluetoothManagerService(  759): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  759): Bluetooth State Change Intent: 10 -> 11
,I/BluetoothBondStateMachine( 3030): StableState(): Entering Off State
,I/ActivityManager(  759): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=3063 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
D/WifiMonitor(  759): startMonitoring(wlan0) with mConnected = false
,D/HeadsetService( 3030): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni( 3030): classInitNative: succeeds
D/BluetoothHeadset( 1233): Proxy object connected
D/BluetoothHeadset( 1187): Proxy object connected
,D/BluetoothHeadset( 1187): Proxy object connected
,D/BluetoothHeadset(  759): Proxy object connected
D/HeadsetStateMachine( 3030): make
,I/BluetoothAdapterState( 3030): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetStateMachine( 3030): max_hf_connections = 1
I/bluedroid( 3030): get_profile_interface handsfree
,D/BluetoothAdapterService( 3030): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2616a30b
,D/BluetoothA2dp(  759): Proxy object connected
D/A2dpService( 3030): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni( 3030): classInitNative: succeeds
I/bluedroid( 3030): get_profile_interface avrcp
,D/HeadsetStateMachine( 3030): Enter Disconnected: -2, size: 0
,E/RemoteController( 3030): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3030): classInitNative: succeeds
D/A2dpStateMachine( 3030): make
,I/bluedroid( 3030): get_profile_interface a2dp
,I/GKI_LINUX( 3030): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothAdapterService( 3030): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2616a30b
,I/BluetoothHidServiceJni( 3030): classInitNative: succeeds
,D/A2dpStateMachine( 3030): Enter Disconnected: -2
,D/HidService( 3030): Received start request. Starting profile...
,I/bluedroid( 3030): get_profile_interface hidhost
D/BluetoothAdapterService( 3030): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2616a30b
I/BluetoothHealthServiceJni( 3030): classInitNative: succeeds
D/HealthService( 3030): Received start request. Starting profile...
I/bluedroid( 3030): get_profile_interface health
D/BluetoothAdapterService( 3030): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2616a30b
I/BluetoothPanServiceJni( 3030): classInitNative(L105): succeeds
D/PanService( 3030): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3030): initializeNative(L110): pan
I/bluedroid( 3030): get_profile_interface pan
,D/BluetoothAdapterService( 3030): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2616a30b
,I/BtGatt.JNI( 3030): classInitNative(L863): classInitNative: Success!
,D/BtGatt.DebugUtils( 3030): handleDebugAction() action=null
,D/BtGatt.GattService( 3030): Received start request. Starting profile...
D/BtGatt.GattService( 3030): start()
I/bluedroid( 3030): get_profile_interface gatt
,D/BtGatt.AdvertiseManager( 3030): advertise manager created
,D/BluetoothAdapterService( 3030): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2616a30b
,V/BluetoothMapService( 3030): BluetoothMapBinder()
,D/BluetoothMapService( 3030): Received start request. Starting profile...
D/BluetoothMapService( 3030): start()
,D/BluetoothMapEmailSettingsLoader( 3030): Found 0 applications
D/BluetoothMapEmailAppObserver( 3030): createReceiver()
,D/BluetoothMapEmailAppObserver( 3030): initObservers()
,D/BluetoothMapEmailAppObserver( 3030): getEnabledAccountItems()
,D/BluetoothAdapterService( 3030): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2616a30b
,D/HeadsetStateMachine( 3030): Disconnected process message: 10, size: 0
D/HeadsetStateMachine( 3030): Proxy object connected
D/HeadsetPhoneState( 3030): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3030): Disconnected process message: 11, size: 0
,V/BluetoothMapService( 3030): Handler(): got msg=1
,D/BluetoothAdapterState( 3030): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3030): enable
I/bt_hci_bdroid( 3030): init
I/GKI_LINUX( 3030): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3030): btu_task pending for preload complete event
,I/bt_vendor( 3030): init
I/bt_vnd_conf( 3030): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3030): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3030): userial_init
,I/ActivityManager(  759): Killing 2305:com.google.android.deskclock/u0a38 (adj 15): empty #17
,I/bt_userial_vendor( 3030): userial vendor open: opening /dev/ttyHS99
,I/bt_userial_vendor( 3030): device fd = 53 open
D/bt_userial( 3030): Entering userial_read_thread()
,I/bt_hwcfg( 3030): bt vendor lib: set UART baud 4000000
,W/libprocessgroup(  759): failed to open /acct/uid_10038/pid_2305/cgroup.procs: No such file or directory
,D/WifiService(  759): New client listening to asynchronous messages
,D/bt_hwcfg( 3030): Chipset BCM4335C0
,D/bt_hwcfg( 3030): Target name = [BCM4335C0]
I/bt_hwcfg( 3030): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,D/AuthorizationBluetoothService( 1392): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager(  759): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3102 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 1392): Explicit concurrent mark sweep GC freed 13045(767KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 19MB/32MB, paused 665us total 24.414ms
,I/ActivityManager(  759): Killing 2360:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,I/bt_hwcfg( 3030): bt vendor lib: set UART baud 115200
,D/bt_hwcfg( 3030): Settlement delay -- 100 ms
I/bt_hwcfg( 3030): Setting fw settlement delay to 100 
,W/libprocessgroup(  759): failed to open /acct/uid_10069/pid_2360/cgroup.procs: No such file or directory
,D/Tethering(  759): sendTetherStateChangedBroadcast 1, 0, 0
,I/bt_hwcfg( 3030): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 3030): Setting local bd addr to 34:FC:EF:11:AE:67
,I/bt_hwcfg( 3030): vendor lib fwcfg completed
,I/bt-btu  ( 3030): btu_task received preload complete event
,I/        ( 3030): BTE_InitTraceLevels -- TRC_HCI
,I/        ( 3030): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3030): BTE_InitTraceLevels -- TRC_RFCOMM
,I/        ( 3030): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3030): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3030): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3030): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3030): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3030): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3030): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3030): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3030): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3030): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3030): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3030): BTE_InitTraceLevels -- TRC_BTIF
I/wpa_supplicant( 3052): rfkill: Cannot open RFKILL control device
,I/wpa_supplicant( 3052): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiConfigStore(  759): Loading config and enabling all networks 
,E/WifiConfigStore(  759): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  759): Setting external_sim to 1
,D/WifiStateMachine(  759): Setting OUI to DA-A1-19
I/WifiNative-HAL(  759): startHal
D/wifi    (  759): setting scan oui 0x9e6a6160
D/WifiHAL (  759): Sending mac address OUI
E/WifiHAL (  759): failed to set scanning mac OUI; result = -95
,W/Settings( 1803): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/native  (  759): do suspend true
,D/CommandListener(  179): Setting iface cfg
D/CommandListener(  179): Trying to bring up p2p0
,D/WifiMonitor(  759): startMonitoring(p2p0) with mConnected = true
,D/WifiScanningService(  759): SCAN_AVAILABLE : 3
D/RttService(  759): SCAN_AVAILABLE : 3
,D/WifiScanningService(  759): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  759): startHal
,D/RttService(  759): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/wifi    (  759): getting scan capabilities on interface[1] = 0x9e6a6160
D/WifiHAL (  759): Creating message to get scan capablities; iface = 21
D/WifiHAL (  759): In GetCapabilities::handleResponse
D/WifiHAL (  759): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  759): StartedState
,D/WifiNative-HAL(  759): p2pGetDeviceAddress
,D/WifiNative-HAL(  759): p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,I/wpa_supplicant( 3052): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,E/bt-btm  ( 3030): BTM_SecRegister:p_cb_info->p_le_callback == 0xa3fee9d5 
E/bt-btm  ( 3030): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3fee9d5 
,I/ActivityManager(  759): Killing 1785:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10045/pid_1785/cgroup.procs: No such file or directory
,E/bt-btif ( 3030): Calling BTA_HhEnable
E/bt-btif ( 3030): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3030): Address is:34:FC:EF:11:AE:67
,D/BluetoothManagerService(  759): Bluetooth Adapter name changed to Nexus 5
D/BluetoothAdapterProperties( 3030): Name is: Nexus 5
D/BluetoothManagerService(  759): Stored Bluetooth name: Nexus 5
,D/BluetoothAdapterProperties( 3030): Scan Mode:20
D/BluetoothAdapterProperties( 3030): Discoverable Timeout:120
,D/bte_conf( 3030): Device ID record 1 : primary
,D/bte_conf( 3030):   vendorId            = 000f
D/bte_conf( 3030):   vendorIdSource      = 0001
D/bte_conf( 3030):   product             = 1200
,D/bte_conf( 3030):   version             = 1436
D/bte_conf( 3030):   clientExecutableURL = 
D/bte_conf( 3030):   serviceDescription  = 
D/bte_conf( 3030):   documentationURL    = 
,D/bte_conf( 3030): bte_load_did_conf no section named DID2.
,D/BluetoothPanServiceJni( 3030): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 3030): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3030): ScanMode =  20
D/BluetoothAdapterProperties( 3030): State =  11
D/BluetoothAdapterProperties( 3030): Setting state to 12
I/BluetoothAdapterState( 3030): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService(  759): Message: 60
D/BluetoothManagerService(  759): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
I/BluetoothAdapterState( 3030): Entering On State
D/BluetoothAdapterProperties( 3030): Scan Mode:21
,D/BluetoothAdapterProperties( 3030): Discoverable Timeout:120
D/BluetoothManagerService(  759): Broadcasting onBluetoothStateChange(true) to 5 receivers.
D/BluetoothHeadset(  759): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1187): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1233): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1187): onBluetoothStateChange: up=true
D/BluetoothA2dp(  759): onBluetoothStateChange: up=true
D/BluetoothManagerService(  759): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothMapService( 3030): onReceive
D/BluetoothMapService( 3030): STATE_ON
V/BluetoothMapService( 3030): Handler(): got msg=1
D/BluetoothMapMasInstance( 3030): Map Service startRfcommSocketListener
D/BluetoothManagerService(  759): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  759): Message: 40
D/BluetoothManagerService(  759): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
I/Telecom ( 1187): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
E/bt_h4   ( 3030): vendor lib postload completed
W/bt-smp  ( 3030): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3030): Plain text(LSB ~ MSB) = ad 8a 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3030): Encrypted text(LSB ~ MSB) = 5d 99 15 4d f9 03 00 b9 01 01 8c ed 84 a1 18 19 
W/bt-btm  ( 3030): Stopping oneshot timer
D/HeadsetStateMachine( 3030): Disconnected process message: 9, size: 0
D/HeadsetStateMachine( 3030): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 3030): mNumber:  mType: 128
D/HeadsetStateMachine( 3030): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 3030): terminateScoUsingVirtualVoiceCall:No present call to terminate
D/BluetoothMapMasInstance( 3030): MAS initSocket()
D/BluetoothMapMasInstance( 3030):   masId = 00
D/BluetoothMapMasInstance( 3030):   msgTypes = 0e
D/BluetoothMapMasInstance( 3030):   masName = SMS/MMS
D/BluetoothMapMasInstance( 3030):   SDP string = 000eSMS/MMS
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3030): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothMapMasInstance( 3030): Succeed to create listening socket 
D/BluetoothMapMasInstance( 3030): Accepting socket connection...
W/bt-smp  ( 3030): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3030): Plain text(LSB ~ MSB) = 46 99 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3030): Encrypted text(LSB ~ MSB) = 61 a7 6c b3 f3 a4 c1 39 3a fe b7 7f 6e 6f ef 22 
W/bt-btm  ( 3030): Stopping oneshot timer
W/ContextImpl( 3063): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,W/bt-smp  ( 3030): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3030): Plain text(LSB ~ MSB) = fb 8b 5f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3030): Encrypted text(LSB ~ MSB) = c9 7c 67 52 8c a5 6b 84 ac eb 52 0a 4e 81 86 f5 
W/bt-btm  ( 3030): Stopping oneshot timer
,W/bt-smp  ( 3030): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3030): Plain text(LSB ~ MSB) = fa 52 5e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3030): Encrypted text(LSB ~ MSB) = 2c ef 6a a1 0c 86 42 bb af 1e 36 8d 38 54 10 4c 
W/bt-btm  ( 3030): Stopping oneshot timer
,W/bt-smp  ( 3030): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3030): Plain text(LSB ~ MSB) = 0a ce 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3030): Encrypted text(LSB ~ MSB) = 43 a1 c9 0f 1b 7c bc 17 76 97 1f 3e ec d2 05 5f 
W/bt-btm  ( 3030): Stopping oneshot timer
,W/bt-smp  ( 3030): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3030): Plain text(LSB ~ MSB) = 33 36 55 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3030): Encrypted text(LSB ~ MSB) = 0d 3b 1a 22 64 10 4c fc 46 4e fb d6 ab 50 6d 89 
,W/bt-btm  ( 3030): Stopping oneshot timer
,W/bt-smp  ( 3030): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3030): Plain text(LSB ~ MSB) = 8f de 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3030): Encrypted text(LSB ~ MSB) = 38 dd 64 fd 9a 44 22 f2 5d 7c 73 87 46 ac 52 11 
W/bt-btm  ( 3030): Stopping oneshot timer
,D/BluetoothManagerService(  759): Message: 20
,D/BluetoothManagerService(  759): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f77f4de:true
I/art     (  759): Explicit concurrent mark sweep GC freed 26061(1308KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 1.129ms total 57.717ms
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3030): getBluetoothService() called with no BluetoothManagerCallback
,D/LocalBluetoothProfileManager( 3063): Adding local A2DP profile
,D/BluetoothManagerService(  759): Message: 30
,D/LocalBluetoothProfileManager( 3063): Adding local HEADSET profile
,D/BluetoothManagerService(  759): Message: 30
,D/BluetoothManagerService(  759): Message: 30
,D/BluetoothManagerService(  759): Message: 30
,D/LocalBluetoothProfileManager( 3063): Adding local MAP profile
,D/BluetoothMap( 3063): Create BluetoothMap proxy object
,D/BluetoothManagerService(  759): Message: 30
,D/BluetoothManagerService(  759): Message: 30
,D/LocalBluetoothProfileManager( 3063): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3063): finishStartingService: stopping service
,D/BluetoothA2dp( 3063): Proxy object connected
,D/A2dpProfile( 3063): Bluetooth service connected
,D/BluetoothHeadset( 3063): Proxy object connected
,D/HeadsetProfile( 3063): Bluetooth service connected
,D/BluetoothInputDevice( 3063): Proxy object connected
,D/HidProfile( 3063): Bluetooth service connected
,D/AuthorizationBluetoothService( 1392): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothPan( 3063): BluetoothPAN Proxy object connected
D/PanProfile( 3063): Bluetooth service connected
,D/BluetoothMap( 3063): Proxy object connected
D/MapProfile( 3063): Bluetooth service connected
D/BluetoothMap( 3063): getConnectedDevices()
,V/BluetoothMapService( 3030): getConnectedDevices()
,D/BluetoothPbap( 3063): Proxy object connected
,D/PbapServerProfile( 3063): Bluetooth service connected
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3030): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 3030): Accept thread started.
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 2961): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): my name is : LGE-Nexus 5_PT6456
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): attempting to connect to test coordinator
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): check test folder
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): found test : ./testFindPeers.js
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): found test : ./testReConnect.js
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): found test : ./testSendData.js
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): Test app app.js loaded
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/chromium( 2961): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  759): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiStateMachine(  759): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  759): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=1
,E/WifiConfigStore(  759): writeKnownNetworkHistory write linked 1
E/WifiConfigStore(  759): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  759): will read network variables netId=1
,E/WifiStateMachine(  759): CMD_AUTO_CONNECT did save config ->  nid=1
,E/WifiConfigStore(  759): will read network variables netId=1
,I/wpa_supplicant( 3052): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,E/WifiConfigStore(  759): setLastSelectedConfiguration -1
,E/wpa_supplicant( 3052): PNO: In assoc process
,I/wpa_supplicant( 3052): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3052): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3052): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  759): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  759): Start Dhcp Watchdog 1
,E/native  (  759): do suspend false
,E/WifiStateMachine(  759): scanCount==0 - aborting
,I/dhcpcd  ( 3189): version 5.5.6 starting
,E/dhcpcd  ( 3189): get_duid: Read-only file system
,I/dhcpcd  ( 3189): wlan0: rebinding lease of 192.168.1.114
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/dhcpcd  ( 3189): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3189): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  759): do suspend true
,D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  759): Adding iface wlan0 to network 100
,E/ConnectivityService(  759): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  759): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  759): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  759): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  759): Setting Dns servers for network 100 to [/192.168.1.1]
,D/Nat464Xlat(  759): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  759): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  759): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  759): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  759):    accepting network in place of null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  759): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
E/WifiStateMachine(  759): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/CSLegacyTypeTracker(  759): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  759): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  759): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 25 Nov 2015 13:27:10 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1448458030394], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1448458030378]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Validated
D/ConnectivityService(  759): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  759): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  759): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  759): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
D/TelephonyNetworkFactory( 1233): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 2961): 
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  759): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2477): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2477): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/AlarmManagerService(  759): Setting time of day to sec=1448458033
,W/AlarmManagerService(  759): Unable to set rtc to 1448458033: Invalid argument
,I/iu.SyncManager( 1558): SYNC; picasa accounts
,D/NetworkLogImpl( 1558): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1558): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1558): num queued entries: 0
,I/iu.UploadsManager( 1558): num updated entries: 0
,I/iu.SyncManager( 1558): NEXT; no task
,D/ChimeraCfgMgr( 1558): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1558): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/SystemUpdateService( 1558): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1558): onCreate
,D/SystemUpdateService( 1558): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1558): active receiver: enabled
,I/SystemUpdateService( 1558): showing system update notification
,V/GLSActivity( 1392): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1392): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ValidateNoPeople(  759): skipping global notification
,V/SystemUpdateService( 1558): retry (wakeup: false) in 3599990 ms
,D/SystemUpdateService( 1558): onDestroy
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/ActivityManager(  759): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3292 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  759): No APN found to select.
,V/GLSActivity( 1392): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1392): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GpsLocationProvider(  759): NTP server returned: 1448458033559 (Wed Nov 25 14:27:13 GMT+01:00 2015) reference: 87115 certainty: 18 system time offset: -198
E/LocSvc_eng(  759): E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,I/Babel   ( 1803): connection state changed from UNKNOWN to CONNECTED
,E/Auth.Api.Credentials( 1558): [CredentialSyncAdapter] Unknown sync event.
,I/GCM     ( 1392): GCM config loaded
,I/GAv4    ( 3292): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3292):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3292):   adb logcat -s GAv4
,W/GAv4    ( 3292): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/ConnectivityService(  759): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  759): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  759): apparently satisfied.  currentScore=60
,D/ConnectivityManager.CallbackHandler( 1558): CM callback handler got msg 524290
,W/GAv4    ( 3292): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3292): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/DriveInitializer( 1558): Awaiting to be initialized
,W/DriveInitializer( 1558): Background init thread started
I/WebViewFactory( 3292): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3292): Time to load native libraries: 2 ms (timestamps 7629-7631)
I/LibraryLoader( 3292): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3292): Binding Chromium to main looper Looper (main, tid 1) {a307ebc}
I/LibraryLoader( 3292): Expected native library version number "",actual native library version number ""
I/chromium( 3292): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3292): Initializing chromium process, singleProcess=true
,W/art     ( 3292): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3292): ApplicationContext is null in ApplicationStatus
,W/chromium( 3292): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3292): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3292): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3292): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/DriveInitializer( 1558): Background init thread ended
,W/AudioManagerAndroid( 3292): Requires BLUETOOTH permission
,I/NSApplication( 3292): Starting up...
,I/art     ( 1392): Explicit concurrent mark sweep GC freed 7337(402KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 19MB/32MB, paused 1.062ms total 50.974ms
,I/art     (  195): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 243us total 10.359ms
,I/ActivityManager(  759): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3377 uid=10076 gids={50076, 9997} abi=armeabi-v7a
,I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 233us total 9.923ms
,I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 229us total 9.812ms
,I/ActivityManager(  759): Killing 2446:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10003/pid_2446/cgroup.procs: No such file or directory
,D/TimeService( 3377): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1448458034392
D/        ( 3377): TimeServiceNative: User Time to be set is 1448458034392
,D/QC-time-services( 3377): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3377): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3377): Lib:time_genoff_operation: pargs->ts_val = 1448458034392
D/QC-time-services(  198): Daemon: Connection accepted:time_genoff
D/QC-time-services( 3377): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  198): Daemon:Received base = 2, unit = 1, operation = 0,value = 1448458034392
D/QC-time-services(  198): Daemon:genoff_opr: Base = 2, val = 1448458034392, operation = 0
D/QC-time-services(  198): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS2/29/70 19:18:4
D/QC-time-services(  198): Daemon:Value read from RTC seconds = 7586284000
,D/QC-time-services(  198): Daemon:new time 1448458034392 
D/QC-time-services(  198): Daemon: delta 1440871750392 genoff 1440871750392 
D/QC-time-services(  198): Daemon:genoff_persistent_update: Writing genoff = 1440871750392 to memory
D/QC-time-services(  198): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  198): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  198): Updating the TOD offset
D/QC-time-services(  198): Daemon:genoff_persistent_update: Writing genoff = 1440871750392 to memory
D/QC-time-services(  198): Daemon:Opening File: /data/system/time/ats_1
D/QC-time-services(  198): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  198): Daemon:Update to modem bit set
,D/QC-time-services(  198): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  198): Daemon: Base = 2, Value being sent to MODEM = 1132493234392
E/QC-time-services( 3377): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/QC-time-services(  198): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
D/QC-time-services(  198): Daemon: Time-services: Waiting to acceptconnection
,I/art     (  759): Explicit concurrent mark sweep GC freed 36910(1837KB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 27MB/41MB, paused 878us total 53.232ms
,I/CheckinService( 1558): Checkin interval check for package: unspecified last checkin: 1448443186671 min interval config: 0 actual interval: 14847802
,I/ActivityManager(  759): Killing 2334:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10070/pid_2334/cgroup.procs: No such file or directory
,I/ActivityManager(  759): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=3404 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3404): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3404):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3404):   adb logcat -s GAv4
,W/GAv4    ( 3404): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3404): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3404): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  759): Killing 1938:com.android.providers.calendar/u0a2 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10002/pid_1938/cgroup.procs: No such file or directory
,I/ActivityManager(  759): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3426 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  759): Killing 1471:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10013/pid_1471/cgroup.procs: No such file or directory
,W/ResourcesManager( 3426): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 3426): Created com.android.providers.calendar.CalendarAlarmManager@3eeb3485(com.android.providers.calendar.CalendarProvider2@180412da)
,I/CalendarProvider2( 3426): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 3426): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/Finsky  ( 2395): [230] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2395): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/SQLiteLog( 3426): (284) automatic index on view_events(_id)
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,V/GLSActivity( 1392): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1392): Vacuum at: now=1448458049769 tag=VacuumService
,D/UdcCache:FPQuery( 1558): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 1392): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1392): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GetConfigurationSnapshotOperation( 1392): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1392): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1392): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 1392): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1392): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1392): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/Uploader( 1392):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1392): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1392): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1392): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1392): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1392): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/Keyboard.Facilitator.LanguageModelFlusher( 1060): run()
I/Keyboard.Facilitator( 1060): flushDynamicLanguageModels()
,I/ConfigService( 1392): onCreate
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/ConfigService( 1392): onDestroy
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/ClearcutLoggerApiImpl( 1135): disconnect managed GoogleApiClient
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,E/DataBuffer( 1392): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@20b70000)
,E/DataBuffer( 1392): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2feb3039)
E/DataBuffer( 1392): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@14eb167e)
,E/DataBuffer( 1392): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2c6727df)
E/DataBuffer( 1392): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@b8c1c2c)
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): DBG, CoordinatorConnector connect called
I/jxcore-log( 2961): 
I/jxcore-log( 2961): Coordinator is now connected to the server!
I/jxcore-log( 2961): 
,I/chromium( 2961): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,V/GLSActivity( 1392): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1392): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1392): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 2961): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): DBG, CoordinatorConnector command called
I/jxcore-log( 2961): 
I/jxcore-log( 2961): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":20,"addressList":[{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"34:FC:EF:9D:93:0B","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"50:2E:6C:AC:21:50","tryCount":0},{"address":"B4:CE:F6:AB:A4
I/jxcore-log( 2961): Start now : testSendData.js
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 20
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): check server
I/jxcore-log( 2961): 
I/jxcore-log( 2961): serverPort is 58707
I/jxcore-log( 2961): 
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 2961): Stoping All
I/        ( 2961): Stopping services
I/        ( 2961): Stop Bluetooth
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 2961): Start-My BT: 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 2961):  mInstanceString : {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6456","ra":"34:FC:EF:11:AE:67"}
,I/        ( 2961): All stuff available and enabled
I/        ( 2961): Stoping All
I/        ( 2961): Stopping services
I/        ( 2961): Stop Bluetooth
I/        ( 2961): Starting All
I/        ( 2961): Stopping services
I/        ( 2961): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6456","ra":"34:FC:EF:11:AE:67"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@312baca3
I/        ( 2961): Stopping services
I/        ( 2961): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6456","ra":"34:FC:EF:11:AE:67"}
,I/        ( 2961): Add local service :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6456","ra":"34:FC:EF:11:AE:67"}, length : 77
,I/        ( 2961): peerDiscoveryTimer timeout value:8924
,I/        ( 2961): Stop Bluetooth
I/        ( 2961): StartBluetooth listener
,I/        ( 2961): StartBluetooth listener
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2961): StartBroadcasting started ok
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): do fake peer & start
I/jxcore-log( 2961): 
I/jxcore-log( 2961): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:35.043Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:35.044Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:32:35.044Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 2961): Connecting to null, at E0:DB:10:14:E2:C0
I/jxcore-log( 2961): 2015-11-25T13:32:35.049Z SendDataTCPServer.js: TCP/IP server is bound to port: 58707
I/jxcore-log( 2961): 
I/chromium( 2961): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/WB      ( 2961): We already were running, thus doing nothing
,I/        ( 2961): Added local service
I/        ( 2961): Cleared service requests
I/        ( 2961): Stopped peer discovery
I/        ( 2961): Started peer discovery
I/        ( 2961): Discovery state changed to Started.
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,I/BTListenerThread( 2961): starting to listen
I/BTListenerThread( 2961): waiting to accept incoming Connection
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2961): Found 1 peers.
I/SS      ( 2961): Peer(1): Android_50a5 fa:cf:c5:d9:e5:62
,D/WifiP2pManager( 2961): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2961): Added service request
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2961): Started service discovery
,I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
E/bt-btif ( 3030): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3030): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3030): Entering PendingCommandState State
,W/BluetoothEventManager( 3063): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3063): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.
,I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 3030): Failed to remove device: E0:DB:10:14:E2:C0
,I/BluetoothBondStateMachine( 3030): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,W/BluetoothEventManager( 3063): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3063): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.
,I/BluetoothBondStateMachine( 3030): StableState(): Entering Off State
,W/bt-btif ( 3030): new conn_srvc id:26, app_id:1
W/bt-btif ( 3030): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3030): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2961): Starting to Handshake
,I/BTHandshakeSocketThread( 2961): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2961): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread started
,I/BTConnectToThread( 2961): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 2961): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1287","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2961): HandshakeOk : samsung-SM-N910C_PT1287
I/HS      ( 2961): Hand Shake finished outgoing for : samsung-SM-N910C_PT1287
,I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2961): Starting the connected thread incoming : false, samsung-SM-N910C_PT1287
I/BtToSocketBase( 2961): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2961): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2961): mHTTPPort  set to : 43988
,I/BtConnectorHelper( 2961): Request socket is using : 43988
,I/BtToRequestSocket( 2961): Now accepting connections
,I/BtConnectorHelper( 2961): Calling ConnectionStatusUpdate with port :43988
I/jxcore-log( 2961): 2015-11-25T13:32:41.438Z SendDataConnector.js: CLIENT connected to 43988, error: null
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:32:41.439Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2961): 
,I/BtToRequestSocket( 2961): incoming data from: /127.0.0.1, port: 43988
,I/BtToRequestSocket( 2961): Set local streams
,I/BtToRequestSocket( 2961): rin ended ---------------------------;
,I/jxcore-log( 2961): 2015-11-25T13:32:41.475Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2961): 
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2961): 2015-11-25T13:32:43.127Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2961): 
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
E/bt-btif ( 3030): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3030): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3030): Entering PendingCommandState State
,W/BluetoothEventManager( 3063): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3063): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 3030): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 3030): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3030): StableState(): Entering Off State
,W/BluetoothEventManager( 3063): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3063): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,W/bt-btif ( 3030): new conn_srvc id:26, app_id:255
W/bt-btif ( 3030): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3030): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2961): we got incoming connection
I/BTHandshakeSocketThread( 2961): Creating BTHandshakeSocketThread
I/BTListenerThread( 2961): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread started
,I/BTListenerThread( 2961): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 2961): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2961): MESSAGE_WRITE 77 bytes.
I/HS      ( 2961): Incoming connection Hand Shake finished for : motorola-XT1072_PT9583
I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2961): Starting the connected thread incoming : true, motorola-XT1072_PT9583
I/BtToSocketBase( 2961): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2961): Creating BTConnectedThread
I/BtConnectorHelper( 2961): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2961): --DoOneRunRound started
,I/jxcore-log( 2961): 2015-11-25T13:32:45.431Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2961): 
,I/BtToRequestSocket( 2961): LocalHost address: localhost/127.0.0.1, port: 58707
,I/BtToRequestSocket( 2961): --DoOneRunRound ended
,I/jxcore-log( 2961): 2015-11-25T13:32:45.887Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:45.899Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:47.487Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:47.512Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:47.523Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:47.969Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:48.004Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:48.418Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:48.459Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:48.940Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:48.951Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 2961): 
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4165ebc rs_disc_pending=1
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,I/BtToSocketBase( 2961): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2961): Disconnect outgoing peer: samsung-SM-N910C_PT1287
I/BtToSocketBase( 2961): Stop ReceivingThread
I/BtToSocketBase( 2961): Stop SendingThread
I/BtToSocketBase( 2961): Close local in
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2961): Close LocalOutputStream
I/BtToSocketBase( 2961): Close localHostSocket
I/BtToSocketBase( 2961): Close bt in
,I/BtToSocketBase( 2961): Close bt out
I/BtToSocketBase( 2961): Close bt socket
I/BtToRequestSocket( 2961): Close server socket
,D/BluetoothMapService( 3030): onReceive
,D/BluetoothManagerService(  759): Message: 20
D/BluetoothManagerService(  759): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@293c8acd:true
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: Note4-1
,I/jxcore-log( 2961): 2015-11-25T13:32:49.392Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 2961): 
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2961): 2015-11-25T13:32:49.846Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:49.854Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:50.268Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:50.305Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:51.621Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:51.627Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:51.637Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:51.650Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:51.685Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:52.520Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:52.529Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:32:52.532Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:52.545Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:52.552Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:53.006Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:53.015Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:53.022Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:53.028Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:53.039Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:53.128Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:32:53.129Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:32:53.131Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:32:53.131Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:53.133Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:32:53.140Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:53.197Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:53.205Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:53.211Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:53.223Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:53.255Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:53.300Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:53.308Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:53.319Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:53.355Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:53.538Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:53.575Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:32:53.947Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2961): 
,W/bt-btif ( 3030): invalid rfc slot id: 4
,I/BtToSocketBase( 2961): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2961): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2961): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT9583
I/BtToSocketBase( 2961): Stop ReceivingThread
I/BtToSocketBase( 2961): Stop SendingThread
I/BtToSocketBase( 2961): Close local in
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2961): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2961): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT9583
I/BtToSocketBase( 2961): Close LocalOutputStream
,I/BtToSocketBase( 2961): Close localHostSocket
I/BtToSocketBase( 2961): Close bt in
,I/BtToSocketBase( 2961): Close bt out
I/BtToSocketBase( 2961): Close bt socket
,I/BtToSocketBase( 2961): Close bt in
I/BtToSocketBase( 2961): Close bt out
I/BtToSocketBase( 2961): Close bt socket
,I/jxcore-log( 2961): 2015-11-25T13:32:54.036Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2961): 
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4166084 rs_disc_pending=0
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3030): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
W/bt-rfcomm( 3030): RFCOMM_DisconnectInd LCID:0x43
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3030): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: XT1072
,I/jxcore-log( 2961): 2015-11-25T13:32:58.133Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:32:58.134Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:32:58.134Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2961): 
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
E/bt-btif ( 3030): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3030): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3030): Entering PendingCommandState State
,W/BluetoothEventManager( 3063): CachedBluetoothDevice for device 08:EC:A9:50:76:27 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3063): Got bonding state changed for 08:EC:A9:50:76:27, but we have no record of that device.
,I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/BluetoothAdapterProperties( 3030): Failed to remove device: 08:EC:A9:50:76:27
,I/BluetoothBondStateMachine( 3030): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
,W/BluetoothEventManager( 3063): CachedBluetoothDevice for device 08:EC:A9:50:76:27 not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 3030): StableState(): Entering Off State
,E/BluetoothEventManager( 3063): Got bonding state changed for 08:EC:A9:50:76:27, but we have no record of that device.
,W/bt-btif ( 3030): new conn_srvc id:26, app_id:255
W/bt-btif ( 3030): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3030): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2961): we got incoming connection
I/BTHandshakeSocketThread( 2961): Creating BTHandshakeSocketThread
I/BTListenerThread( 2961): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread started
,I/BTListenerThread( 2961): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 2961): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT1985","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2961): MESSAGE_WRITE 77 bytes.
I/HS      ( 2961): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT1985
I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2961): Starting the connected thread incoming : true, samsung-SM-A300FU_PT1985
I/BtToSocketBase( 2961): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2961): Creating BTConnectedThread
I/BtConnectorHelper( 2961): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2961): --DoOneRunRound started
,I/BtToRequestSocket( 2961): LocalHost address: localhost/127.0.0.1, port: 58707
I/BtToRequestSocket( 2961): --DoOneRunRound ended
,I/jxcore-log( 2961): 2015-11-25T13:33:01.238Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:01.607Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:01.647Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:01.701Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:01.714Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:01.728Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:01.739Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:01.793Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:01.825Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:01.862Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:01.896Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:01.939Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:01.949Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:01.968Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:02.006Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:02.127Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:02.165Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:02.176Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:02.185Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:02.227Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:02.243Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:02.269Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:02.274Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:02.306Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:02.319Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:02.330Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:02.341Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:02.357Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:02.386Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:02.394Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:02.428Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:02.472Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:02.528Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:02.567Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2961): 
,W/bt-btif ( 3030): invalid rfc slot id: 6
,I/BtToSocketBase( 2961): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2961): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2961): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT1985
I/BtToSocketBase( 2961): Stop ReceivingThread
I/BtToSocketBase( 2961): Stop SendingThread
I/BtToSocketBase( 2961): Close local in
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2961): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2961): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT1985
I/BtToSocketBase( 2961): Close LocalOutputStream
,I/BtToSocketBase( 2961): Close localHostSocket
I/BtToSocketBase( 2961): Close bt in
,I/BtToSocketBase( 2961): Close bt out
I/BtToSocketBase( 2961): Close bt socket
,I/BtToSocketBase( 2961): Close bt in
I/BtToSocketBase( 2961): Close bt out
I/BtToSocketBase( 2961): Close bt socket
,I/jxcore-log( 2961): 2015-11-25T13:33:02.826Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2961): 
,W/bt-rfcomm( 3030): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
W/bt-rfcomm( 3030): RFCOMM_DisconnectInd LCID:0x45
,I/jxcore-log( 2961): 2015-11-25T13:33:03.134Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:33:03.134Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:33:03.134Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:33:03.134Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 2961): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa416624c rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [e0:db:10:14:e2:c0]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: Note4-1
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa416624c rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3030): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: Thali Test (Galaxy A3)
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4165ebc rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,W/bt-btif ( 3030): new conn_srvc id:26, app_id:1
W/bt-btif ( 3030): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3030): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2961): Starting to Handshake
,I/BTHandshakeSocketThread( 2961): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2961): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread started
,I/BTConnectToThread( 2961): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 2961): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1287","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2961): HandshakeOk : samsung-SM-N910C_PT1287
I/HS      ( 2961): Hand Shake finished outgoing for : samsung-SM-N910C_PT1287
I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2961): Starting the connected thread incoming : false, samsung-SM-N910C_PT1287
I/BtToSocketBase( 2961): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2961): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2961): mHTTPPort  set to : 51980
I/BtConnectorHelper( 2961): Request socket is using : 51980
I/BtToRequestSocket( 2961): Now accepting connections
,I/BtConnectorHelper( 2961): Calling ConnectionStatusUpdate with port :51980
I/jxcore-log( 2961): 2015-11-25T13:33:08.574Z SendDataConnector.js: CLIENT connected to 51980, error: null
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:33:08.574Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2961): 
,I/BtToRequestSocket( 2961): incoming data from: /127.0.0.1, port: 51980
I/BtToRequestSocket( 2961): Set local streams
I/BtToRequestSocket( 2961): rin ended ---------------------------;
,I/jxcore-log( 2961): 2015-11-25T13:33:08.596Z SendDataConnector.js: CLIENT now sending 90000 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:08.818Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:08.821Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:09.092Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:09.398Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2961): 
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2961): 2015-11-25T13:33:09.626Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:09.830Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:09.837Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:09.889Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:33:09.890Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:09.910Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:33:09.911Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2961): 
,I/BtConnectorHelper( 2961): Disconnect outgoing peer: E0:DB:10:14:E2:C0
I/BtToSocketBase( 2961): Stop ReceivingThread
I/BtToSocketBase( 2961): Stop SendingThread
I/BtToSocketBase( 2961): Close local in
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2961): Close LocalOutputStream
I/BtToSocketBase( 2961): Close localHostSocket
I/BtToSocketBase( 2961): Close bt in
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2961): Close bt out
I/BtToSocketBase( 2961): Close bt socket
I/BtToRequestSocket( 2961): Close server socket
I/jxcore-log( 2961): 2015-11-25T13:33:09.941Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): ---- round done--------
I/jxcore-log( 2961): 
I/jxcore-log( 2961): do fake peer & start
I/jxcore-log( 2961): 
I/jxcore-log( 2961): Connect to fake peer: 50:2E:6C:AC:21:50
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:33:09.950Z SendDataConnector.js: Start called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:33:09.951Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:33:09.951Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: 50:2E:6C:AC:21:50, name: null
,I/        ( 2961): Connecting to null, at 50:2E:6C:AC:21:50
I/chromium( 2961): [INFO:CONSOLE(63)] "logCallback Round of send data to peer E0:DB:10:14:E2:C0 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2961): Starting to connect
,W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3030): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4165ebc rs_disc_pending=0
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3030): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: Note4-1
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa41665dc rs_disc_pending=0
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 1
E/bt-btif ( 3030): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3030): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3030): Entering PendingCommandState State
,W/BluetoothEventManager( 3063): CachedBluetoothDevice for device B4:CE:F6:AB:A4:6A not found, calling readPairedDevices().
,E/BluetoothEventManager( 3063): Got bonding state changed for B4:CE:F6:AB:A4:6A, but we have no record of that device.
,I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 0
,D/BluetoothAdapterProperties( 3030): Failed to remove device: B4:CE:F6:AB:A4:6A
,I/BluetoothBondStateMachine( 3030): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3030): StableState(): Entering Off State
,W/BluetoothEventManager( 3063): CachedBluetoothDevice for device B4:CE:F6:AB:A4:6A not found, calling readPairedDevices().
,E/BluetoothEventManager( 3063): Got bonding state changed for B4:CE:F6:AB:A4:6A, but we have no record of that device.
,I/BTListenerThread( 2961): we got incoming connection
I/BTHandshakeSocketThread( 2961): Creating BTHandshakeSocketThread
I/BTListenerThread( 2961): waiting to accept incoming Connection
,W/bt-btif ( 3030): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3030): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3030): bta_dm_pm_ssr:2, lat:1200
,I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread started
,I/BTListenerThread( 2961): got MESSAGE_READ 84 bytes.
I/BTListenerThread( 2961): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2961): MESSAGE_WRITE 77 bytes.
I/HS      ( 2961): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT2890
I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2961): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT2890
I/BtToSocketBase( 2961): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2961): Creating BTConnectedThread
I/BtConnectorHelper( 2961): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2961): --DoOneRunRound started
,I/jxcore-log( 2961): 2015-11-25T13:33:20.975Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2961): 
,I/BtToRequestSocket( 2961): LocalHost address: localhost/127.0.0.1, port: 58707
,I/BtToRequestSocket( 2961): --DoOneRunRound ended
,I/jxcore-log( 2961): 2015-11-25T13:33:21.354Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:21.396Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:21.402Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:21.443Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:21.450Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:21.484Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:21.512Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:21.545Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:21.588Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:21.594Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:21.633Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:21.674Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:21.688Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:21.718Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:21.728Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:21.818Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:21.855Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:21.862Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:21.890Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:21.969Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:21.980Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:22.026Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:22.085Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:22.129Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:22.171Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:22.181Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:22.249Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:22.263Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:22.297Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:22.307Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:22.379Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:22.416Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:22.432Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:22.467Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:22.474Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:22.546Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:22.587Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:22.629Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:22.699Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:22.726Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:22.735Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:22.777Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:33:22.779Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:22.878Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:22.888Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:22.952Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:23.048Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:23.056Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:23.104Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2961): 
,W/bt-btif ( 3030): invalid rfc slot id: 7
,I/BtToSocketBase( 2961): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2961): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2961): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT2890
I/BtToSocketBase( 2961): Stop ReceivingThread
,I/BtToSocketBase( 2961): Stop SendingThread
I/BtToSocketBase( 2961): Close local in
I/BtToSocketBase( 2961): Close LocalOutputStream
I/BtToSocketBase( 2961): Close localHostSocket
I/BtToSocketBase( 2961): Close bt in
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2961): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2961): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT2890
I/BtToSocketBase( 2961): Close bt in
I/BtToSocketBase( 2961): Close bt out
I/BtToSocketBase( 2961): Close bt socket
,I/BtToSocketBase( 2961): Close bt out
I/BtToSocketBase( 2961): Close bt socket
,I/jxcore-log( 2961): 2015-11-25T13:33:23.191Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2961): 
,W/bt-rfcomm( 3030): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
W/bt-rfcomm( 3030): RFCOMM_DisconnectInd LCID:0x4b
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3030): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: HTC Desire 820
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,W/bt-rfcomm( 3030): PORT_StartCnf failed result:5
,W/bt-btif ( 3030): invalid rfc slot id: 9
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3030): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 3030): No record of the device:null
I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 9 Address: 50:2E:6C:AC:21:50 newState: 0
,E/BluetoothBondStateMachine( 3030): In stable state, received invalid newState: 10
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2961): 2015-11-25T13:33:35.612Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:33:35.613Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:35.620Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2961): 
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
E/bt-btif ( 3030): Do not find the bg connection mask for the remote device
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,I/        ( 2961): Cleared service requests
I/        ( 2961): Started peer discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2961): Found 4 peers.
I/SS      ( 2961): Peer(1): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2961): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
,I/SS      ( 2961): Peer(3): Android_50a5 fa:cf:c5:d9:e5:62
,I/SS      ( 2961): Peer(4): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2961): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2961): Added service request
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2961): Started service discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2961): 2015-11-25T13:33:40.620Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:33:40.620Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 2961): 
,I/        ( 2961): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2848, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2848, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/jxcore-log( 2961): 2015-11-25T13:33:45.626Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:33:45.627Z SendDataConnector.js: Connect (retry count 1) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:33:45.628Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:33:45.628Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: 50:2E:6C:AC:21:50, name: null
,I/        ( 2961): Connecting to null, at 50:2E:6C:AC:21:50
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 1
E/bt-btif ( 3030): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3030): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3030): Entering PendingCommandState State
,W/BluetoothEventManager( 3063): CachedBluetoothDevice for device 50:2E:6C:AC:21:50 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3063): Got bonding state changed for 50:2E:6C:AC:21:50, but we have no record of that device.
,I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 0
,D/BluetoothAdapterProperties( 3030): Failed to remove device: 50:2E:6C:AC:21:50
,I/BluetoothBondStateMachine( 3030): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3030): StableState(): Entering Off State
,W/BluetoothEventManager( 3063): CachedBluetoothDevice for device 50:2E:6C:AC:21:50 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3063): Got bonding state changed for 50:2E:6C:AC:21:50, but we have no record of that device.
,W/bt-btif ( 3030): new conn_srvc id:26, app_id:1
W/bt-btif ( 3030): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3030): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2961): Starting to Handshake
I/BTHandshakeSocketThread( 2961): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2961): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread started
,I/BTConnectToThread( 2961): got MESSAGE_READ 79 bytes.
I/BTConnectToThread( 2961): Got JSON from encryption:{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2961): HandshakeOk : HTC-HTC One_M8_PT382
I/HS      ( 2961): Hand Shake finished outgoing for : HTC-HTC One_M8_PT382
I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2961): Starting the connected thread incoming : false, HTC-HTC One_M8_PT382
I/BtToSocketBase( 2961): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2961): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2961): mHTTPPort  set to : 60817
I/BtConnectorHelper( 2961): Request socket is using : 60817
I/BtToRequestSocket( 2961): Now accepting connections
,I/BtConnectorHelper( 2961): Calling ConnectionStatusUpdate with port :60817
,I/jxcore-log( 2961): 2015-11-25T13:33:47.623Z SendDataConnector.js: CLIENT connected to 60817, error: null
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:33:47.625Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2961): 
,I/BtToRequestSocket( 2961): incoming data from: /127.0.0.1, port: 60817
I/BtToRequestSocket( 2961): Set local streams
I/BtToRequestSocket( 2961): rin ended ---------------------------;
,I/jxcore-log( 2961): 2015-11-25T13:33:47.644Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2961): 
,D/        ( 3030): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24979
,I/jxcore-log( 2961): 2015-11-25T13:33:47.853Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2961): 
,D/        ( 3030): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18049
,I/jxcore-log( 2961): 2015-11-25T13:33:47.894Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2961): 
,D/        ( 3030): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:15079
,I/jxcore-log( 2961): 2015-11-25T13:33:47.898Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2961): 
,D/        ( 3030): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8149
,I/jxcore-log( 2961): 2015-11-25T13:33:47.960Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:47.999Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:48.035Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:48.068Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:48.079Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:48.127Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:33:48.128Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:33:48.143Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:33:48.144Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2961): 
I/BtConnectorHelper( 2961): Disconnect outgoing peer: 50:2E:6C:AC:21:50
I/BtToSocketBase( 2961): Stop ReceivingThread
I/BtToSocketBase( 2961): Stop SendingThread
I/BtToSocketBase( 2961): Close local in
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2961): Close LocalOutputStream
I/BtToSocketBase( 2961): Close localHostSocket
,I/BtToSocketBase( 2961): Close bt in
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2961): Close bt out
I/BtToSocketBase( 2961): Close bt socket
I/BtToRequestSocket( 2961): Close server socket
,I/jxcore-log( 2961): 2015-11-25T13:33:48.169Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 2961): 
I/jxcore-log( 2961): ---- round done--------
I/jxcore-log( 2961): 
I/jxcore-log( 2961): do fake peer & start
I/jxcore-log( 2961): 
I/jxcore-log( 2961): Connect to fake peer: B4:CE:F6:AB:A4:6A
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:33:48.172Z SendDataConnector.js: Start called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:33:48.172Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2961): 
,W/bt-btif ( 3030): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
I/jxcore-log( 2961): 2015-11-25T13:33:48.173Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: B4:CE:F6:AB:A4:6A, name: HTC Desire 820
,I/        ( 2961): Connecting to HTC Desire 820, at B4:CE:F6:AB:A4:6A
I/chromium( 2961): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 50:2E:6C:AC:21:50 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4166414 rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0,
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,I/        ( 2961): Cleared service requests
,I/        ( 2961): Started peer discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3030): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: HTC One_M8
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3030): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:12, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3030): invalid rfc slot id: 12
,I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2961): 2015-11-25T13:33:54.090Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:33:54.091Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:33:54.091Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 2961): Found 5 peers.
I/SS      ( 2961): Peer(1): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2961): Peer(2): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2961): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2961): Peer(4): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2961): Peer(5): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2961): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2961): Added service request
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2961): Started service discovery
,I/        ( 2961): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT4505, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT4505, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/jxcore-log( 2961): 2015-11-25T13:33:59.093Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:33:59.094Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2961): 
,I/        ( 2961): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"}, typeCordovap2p._tcp.local.:
,I/        ( 2961): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2890, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2890, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/jxcore-log( 2961): 2015-11-25T13:34:04.100Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:34:04.101Z SendDataConnector.js: Connect (retry count 1) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:34:04.102Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:34:04.102Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: B4:CE:F6:AB:A4:6A, name: HTC Desire 820
,I/        ( 2961): Connecting to HTC Desire 820, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [b4:ce:f6:ab:a4:6a]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: HTC Desire 820
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,W/bt-btif ( 3030): new conn_srvc id:26, app_id:1
W/bt-btif ( 3030): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3030): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2961): Starting to Handshake
,I/BTHandshakeSocketThread( 2961): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2961): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread started
,I/BTConnectToThread( 2961): got MESSAGE_READ 84 bytes.
I/BTConnectToThread( 2961): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2961): HandshakeOk : HTC-HTC Desire 820_PT2890
I/HS      ( 2961): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT2890
,I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2961): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT2890
,I/BtToSocketBase( 2961): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2961): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2961): mHTTPPort  set to : 46014
I/BtConnectorHelper( 2961): Request socket is using : 46014
I/BtToRequestSocket( 2961): Now accepting connections
,I/BtConnectorHelper( 2961): Calling ConnectionStatusUpdate with port :46014
I/jxcore-log( 2961): 2015-11-25T13:34:05.588Z SendDataConnector.js: CLIENT connected to 46014, error: null
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:34:05.589Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2961): 
,I/BtToRequestSocket( 2961): incoming data from: /127.0.0.1, port: 46014
I/BtToRequestSocket( 2961): Set local streams
I/BtToRequestSocket( 2961): rin ended ---------------------------;
,I/jxcore-log( 2961): 2015-11-25T13:34:05.612Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:05.771Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:05.804Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:05.961Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:06.089Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:06.163Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:06.237Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:06.313Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:06.475Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2961): 
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
,I/        ( 2961): Cleared service requests
I/        ( 2961): Started peer discovery
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa41665dc rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa41667a4 rs_disc_pending=0
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2961): 2015-11-25T13:34:09.882Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2961): 
,I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 1
E/bt-btif ( 3030): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3030): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3030): Entering PendingCommandState State
,W/BluetoothEventManager( 3063): CachedBluetoothDevice for device F8:CF:C5:D9:E5:61 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3063): Got bonding state changed for F8:CF:C5:D9:E5:61, but we have no record of that device.
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 0
,D/BluetoothAdapterProperties( 3030): Failed to remove device: F8:CF:C5:D9:E5:61
,I/BluetoothBondStateMachine( 3030): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3030): StableState(): Entering Off State
,W/BluetoothEventManager( 3063): CachedBluetoothDevice for device F8:CF:C5:D9:E5:61 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3063): Got bonding state changed for F8:CF:C5:D9:E5:61, but we have no record of that device.
,W/bt-btif ( 3030): new conn_srvc id:26, app_id:255
W/bt-btif ( 3030): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3030): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2961): we got incoming connection
I/BTHandshakeSocketThread( 2961): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2961): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread started
,I/jxcore-log( 2961): 2015-11-25T13:34:10.816Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:34:10.816Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:10.832Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:34:10.833Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2961): 
,I/BtConnectorHelper( 2961): Disconnect outgoing peer: B4:CE:F6:AB:A4:6A
I/BtToSocketBase( 2961): Stop ReceivingThread
I/BtToSocketBase( 2961): Stop SendingThread
I/BtToSocketBase( 2961): Close local in
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2961): Close LocalOutputStream
I/BtToSocketBase( 2961): Close localHostSocket
I/BtToSocketBase( 2961): Close bt in
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2961): Close bt out
I/BtToSocketBase( 2961): Close bt socket
I/BtToRequestSocket( 2961): Close server socket
,I/jxcore-log( 2961): 2015-11-25T13:34:10.860Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2961): 
I/jxcore-log( 2961): ---- round done--------
I/jxcore-log( 2961): 
I/jxcore-log( 2961): do fake peer & start
I/jxcore-log( 2961): 
I/jxcore-log( 2961): Connect to fake peer: 80:01:84:8A:B3:68
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:34:10.861Z SendDataConnector.js: Start called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:34:10.861Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:34:10.861Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: 80:01:84:8A:B3:68, name: null
,I/        ( 2961): Connecting to null, at 80:01:84:8A:B3:68
I/chromium( 2961): [INFO:CONSOLE(63)] "logCallback Round of send data to peer B4:CE:F6:AB:A4:6A done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa41667a4 rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BTListenerThread( 2961): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 2961): Got JSON from encryption:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT7950","ra":"F8:CF:C5:D9:E5:61"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2961): MESSAGE_WRITE 77 bytes.
I/HS      ( 2961): Incoming connection Hand Shake finished for : motorola-Nexus 6_PT7950
I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2961): Starting the connected thread incoming : true, motorola-Nexus 6_PT7950
I/BtToSocketBase( 2961): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2961): Creating BTConnectedThread
I/BtConnectorHelper( 2961): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2961): --DoOneRunRound started
,I/BtToRequestSocket( 2961): LocalHost address: localhost/127.0.0.1, port: 58707
,I/jxcore-log( 2961): 2015-11-25T13:34:11.309Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2961): 
,I/BtToRequestSocket( 2961): --DoOneRunRound ended
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2961): 2015-11-25T13:34:11.780Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2961): 
,W/bt-btif ( 3030): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,I/jxcore-log( 2961): 2015-11-25T13:34:11.790Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2961): 2015-11-25T13:34:12.747Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:12.756Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:12.798Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:12.829Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:12.842Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:12.856Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2961): 2015-11-25T13:34:13.028Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2961): 2015-11-25T13:34:15.058Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:15.068Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:15.110Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:15.116Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:15.127Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:15.169Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:15.210Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:15.215Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:15.224Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:15.232Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:15.239Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:15.294Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:15.325Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:15.390Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:15.397Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:15.638Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:15.650Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:15.796Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:15.803Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:15.811Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:15.957Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:15.970Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:16.005Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 2961): 
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3030): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: HTC Desire 820
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 2961): Found 5 peers.
I/SS      ( 2961): Peer(1): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2961): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2961): Peer(3): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2961): Peer(4): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2961): Peer(5): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/jxcore-log( 2961): 2015-11-25T13:34:16.392Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 2961): 
,D/WifiP2pManager( 2961): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2961): Added service request
,I/jxcore-log( 2961): 2015-11-25T13:34:16.490Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:16.556Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:16.627Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:16.668Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:16.696Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 2961): 
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2961): 2015-11-25T13:34:16.855Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:16.920Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:16.956Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:17.037Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:17.097Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2961): 
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa41667a4 rs_disc_pending=0
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2961): Started service discovery
,W/bt-btif ( 3030): invalid rfc slot id: 10
,I/BtToSocketBase( 2961): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2961): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2961): Disconnect:::Stop : mBtToServerSocket :motorola-Nexus 6_PT7950
,I/BtToSocketBase( 2961): Stop ReceivingThread
I/BtToSocketBase( 2961): Stop SendingThread
I/BtToSocketBase( 2961): Close local in
I/BtToSocketBase( 2961): Close LocalOutputStream
I/BtToSocketBase( 2961): Close localHostSocket
I/BtToSocketBase( 2961): Close bt in
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2961): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2961): Disconnect:::Stop : mBtToServerSocket :motorola-Nexus 6_PT7950
I/BtToSocketBase( 2961): Close bt in
I/BtToSocketBase( 2961): Close bt out
I/BtToSocketBase( 2961): Close bt socket
,I/BtToSocketBase( 2961): Close bt out
I/BtToSocketBase( 2961): Close bt socket
,I/jxcore-log( 2961): 2015-11-25T13:34:17.701Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2961): 
,W/bt-rfcomm( 3030): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
W/bt-rfcomm( 3030): RFCOMM_DisconnectInd LCID:0x44
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3030): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: Nexus 6
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4166b34 rs_disc_pending=1
E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:15, failed to find channle,                                       status:1, scn:0
E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): invalid rfc slot id: 15
,I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2961): 2015-11-25T13:34:23.285Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:34:23.286Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:34:23.286Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:28.287Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:34:28.287Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:33.292Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:33.293Z SendDataConnector.js: Connect (retry count 1) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:33.297Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:34:33.300Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: 80:01:84:8A:B3:68, name: null
,I/        ( 2961): Connecting to null, at 80:01:84:8A:B3:68
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 1
E/bt-btif ( 3030): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3030): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3030): Entering PendingCommandState State
,W/BluetoothEventManager( 3063): CachedBluetoothDevice for device 80:01:84:8A:B3:68 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3063): Got bonding state changed for 80:01:84:8A:B3:68, but we have no record of that device.
,I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 0
,D/BluetoothAdapterProperties( 3030): Failed to remove device: 80:01:84:8A:B3:68
,I/BluetoothBondStateMachine( 3030): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3030): StableState(): Entering Off State
,W/BluetoothEventManager( 3063): CachedBluetoothDevice for device 80:01:84:8A:B3:68 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3063): Got bonding state changed for 80:01:84:8A:B3:68, but we have no record of that device.
,W/bt-btif ( 3030): new conn_srvc id:26, app_id:1
W/bt-btif ( 3030): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3030): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2961): Starting to Handshake
,I/BTHandshakeSocketThread( 2961): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2961): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread started
,I/BTConnectToThread( 2961): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 2961): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT501"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2961): HandshakeOk : HTC-HTC Desire 820_PT501
I/HS      ( 2961): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT501
I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2961): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT501
I/BtToSocketBase( 2961): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2961): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2961): mHTTPPort  set to : 51329
I/BtConnectorHelper( 2961): Request socket is using : 51329
,I/BtToRequestSocket( 2961): Now accepting connections
,I/BtConnectorHelper( 2961): Calling ConnectionStatusUpdate with port :51329
I/jxcore-log( 2961): 2015-11-25T13:34:40.072Z SendDataConnector.js: CLIENT connected to 51329, error: null
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:34:40.072Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2961): 
,I/BtToRequestSocket( 2961): incoming data from: /127.0.0.1, port: 51329
I/BtToRequestSocket( 2961): Set local streams
I/BtToRequestSocket( 2961): rin ended ---------------------------;
,I/jxcore-log( 2961): 2015-11-25T13:34:40.094Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2961): 
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,D/        ( 3030): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:403
,I/jxcore-log( 2961): 2015-11-25T13:34:43.311Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2961): 
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2961): 2015-11-25T13:34:43.610Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:43.905Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:44.521Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:44.914Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:45.025Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:45.821Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:46.120Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:46.723Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:47.425Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:34:47.426Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:47.441Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:34:47.442Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2961): 
,I/BtConnectorHelper( 2961): Disconnect outgoing peer: 80:01:84:8A:B3:68
I/BtToSocketBase( 2961): Stop ReceivingThread
I/BtToSocketBase( 2961): Stop SendingThread
I/BtToSocketBase( 2961): Close local in
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2961): Close LocalOutputStream
I/BtToSocketBase( 2961): Close localHostSocket
,I/BtToSocketBase( 2961): Close bt in
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2961): Close bt out
I/BtToSocketBase( 2961): Close bt socket
I/BtToRequestSocket( 2961): Close server socket
I/jxcore-log( 2961): 2015-11-25T13:34:47.469Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): ---- round done--------
I/jxcore-log( 2961): 
I/jxcore-log( 2961): do fake peer & start
I/jxcore-log( 2961): 
I/jxcore-log( 2961): Connect to fake peer: F4:F1:E1:5C:3B:E2
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:34:47.472Z SendDataConnector.js: Start called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:34:47.473Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:47.481Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: F4:F1:E1:5C:3B:E2, name: null
,I/        ( 2961): Connecting to null, at F4:F1:E1:5C:3B:E2
I/chromium( 2961): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 80:01:84:8A:B3:68 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3030): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,W/bt-btif ( 3030): No ag scb for peer addr
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4166cfc rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3030): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: HTC Desire 820
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [58:2a:f7:ed:96:be]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4166cfc rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 1
E/bt-btif ( 3030): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3030): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3030): Entering PendingCommandState State
,W/BluetoothEventManager( 3063): CachedBluetoothDevice for device 58:2A:F7:ED:96:BE not found, calling readPairedDevices().
,E/BluetoothEventManager( 3063): Got bonding state changed for 58:2A:F7:ED:96:BE, but we have no record of that device.
,I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 0
,D/BluetoothAdapterProperties( 3030): Failed to remove device: 58:2A:F7:ED:96:BE
,I/BluetoothBondStateMachine( 3030): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3030): StableState(): Entering Off State
,W/BluetoothEventManager( 3063): CachedBluetoothDevice for device 58:2A:F7:ED:96:BE not found, calling readPairedDevices().
,E/BluetoothEventManager( 3063): Got bonding state changed for 58:2A:F7:ED:96:BE, but we have no record of that device.
,W/bt-rfcomm( 3030): PORT_StartCnf failed result:5
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3030): invalid rfc slot id: 17
I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2961): 2015-11-25T13:34:53.818Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:34:53.818Z SendDataConnector.js: CLIENT Can not Connect: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:34:53.818Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2961): 
,E/bt-btif ( 3030): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 3030): No record of the device:null
I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 9 Address: F4:F1:E1:5C:3B:E2 newState: 0
,E/BluetoothBondStateMachine( 3030): In stable state, received invalid newState: 10
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
E/bt-btif ( 3030): Do not find the bg connection mask for the remote device
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3030): new conn_srvc id:26, app_id:255
W/bt-btif ( 3030): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3030): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2961): we got incoming connection
I/BTHandshakeSocketThread( 2961): Creating BTHandshakeSocketThread
I/BTListenerThread( 2961): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread started
,I/BTListenerThread( 2961): got MESSAGE_READ 80 bytes.
I/BTListenerThread( 2961): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT9762","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2961): MESSAGE_WRITE 77 bytes.
I/HS      ( 2961): Incoming connection Hand Shake finished for : HUAWEI-ALE-L21_PT9762
I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2961): Starting the connected thread incoming : true, HUAWEI-ALE-L21_PT9762
I/BtToSocketBase( 2961): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2961): Creating BTConnectedThread
I/BtConnectorHelper( 2961): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2961): --DoOneRunRound started
,I/BtToRequestSocket( 2961): LocalHost address: localhost/127.0.0.1, port: 58707
,I/jxcore-log( 2961): 2015-11-25T13:34:54.466Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2961): 
,I/BtToRequestSocket( 2961): --DoOneRunRound ended
,I/jxcore-log( 2961): 2015-11-25T13:34:54.922Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:54.925Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:34:55.256Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2961): 
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [80:01:84:8a:b3:68]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: HTC Desire 820
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4166b34 rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2961): 2015-11-25T13:34:58.819Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:34:58.819Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2961): 
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3030): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: HTC Desire 820
,W/bt-btif ( 3030): dm_pm_timer expires,
W/bt-btif ( 3030): dm_pm_timer expires 0
W/bt-btif ( 3030): proc dm_pm_timer expires
,I/jxcore-log( 2961): 2015-11-25T13:35:03.827Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:35:03.829Z SendDataConnector.js: Connect (retry count 1) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:03.835Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:03.836Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: F4:F1:E1:5C:3B:E2, name: null
,I/        ( 2961): Connecting to null, at F4:F1:E1:5C:3B:E2
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3030): No ag scb for peer addr
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4166cfc rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,W/bt-rfcomm( 3030): PORT_StartCnf failed result:5
,W/bt-btif ( 3030): invalid rfc slot id: 19
,I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btif ( 3030): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3030): No record of the device:null
I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 9 Address: F4:F1:E1:5C:3B:E2 newState: 0
,E/BluetoothBondStateMachine( 3030): In stable state, received invalid newState: 10
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2961): 2015-11-25T13:35:05.361Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:05.362Z SendDataConnector.js: CLIENT Can not Connect: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:35:05.362Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2961): 
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
E/bt-btif ( 3030): Do not find the bg connection mask for the remote device
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
,I/jxcore-log( 2961): 2015-11-25T13:35:10.363Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:35:10.364Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2961): 
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [80:01:84:8a:b3:68]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: HTC Desire 820
,W/bt-btif ( 3030): new conn_srvc id:26, app_id:255
W/bt-btif ( 3030): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3030): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2961): we got incoming connection
I/BTHandshakeSocketThread( 2961): Creating BTHandshakeSocketThread
I/BTListenerThread( 2961): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread started
,I/BTListenerThread( 2961): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 2961): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT501"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2961): MESSAGE_WRITE 77 bytes.
I/HS      ( 2961): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT501
,I/BtConnectorHelper( 2961): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT501
I/BtToSocketBase( 2961): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2961): Creating BTConnectedThread
I/BtConnectorHelper( 2961): Server socket is using : 0, and is now connected.
I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2961): --DoOneRunRound started
,I/jxcore-log( 2961): 2015-11-25T13:35:13.658Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2961): 
,I/BtToRequestSocket( 2961): LocalHost address: localhost/127.0.0.1, port: 58707
I/BtToRequestSocket( 2961): --DoOneRunRound ended
,I/jxcore-log( 2961): 2015-11-25T13:35:14.011Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:14.020Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:14.032Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:14.040Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:14.126Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:14.158Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:14.226Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:14.320Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:14.332Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:14.365Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:14.428Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:14.437Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:14.525Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:14.624Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:14.659Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:14.727Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:14.733Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:14.744Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:14.923Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:14.932Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:14.938Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:15.027Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:15.040Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:15.075Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:15.233Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:15.239Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:15.330Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:15.349Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:15.367Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:35:15.368Z SendDataConnector.js: Connect (retry count 2) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:35:15.368Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:35:15.369Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: F4:F1:E1:5C:3B:E2, name: null
,I/        ( 2961): Connecting to null, at F4:F1:E1:5C:3B:E2
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 2961): 2015-11-25T13:35:15.631Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 2961): ,
,W/bt-btif ( 3030): No ag scb for peer addr
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4166cfc rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2961): 2015-11-25T13:35:16.029Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:16.036Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 2961): 
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,I/jxcore-log( 2961): 2015-11-25T13:35:16.139Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:16.249Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:16.339Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 2961): 
,I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 1
E/bt-btif ( 3030): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3030): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3030): Entering PendingCommandState State
,I/        ( 2961): Cleared service requests
I/        ( 2961): Started peer discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/BluetoothEventManager( 3063): CachedBluetoothDevice for device F4:F1:E1:5C:3B:E2 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3063): Got bonding state changed for F4:F1:E1:5C:3B:E2, but we have no record of that device.
,I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 0
,D/BluetoothAdapterProperties( 3030): Failed to remove device: F4:F1:E1:5C:3B:E2
,I/BluetoothBondStateMachine( 3030): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3030): StableState(): Entering Off State
,W/BluetoothEventManager( 3063): CachedBluetoothDevice for device F4:F1:E1:5C:3B:E2 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3063): Got bonding state changed for F4:F1:E1:5C:3B:E2, but we have no record of that device.
,I/jxcore-log( 2961): 2015-11-25T13:35:16.635Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:16.836Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:16.849Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2961): 2015-11-25T13:35:17.438Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:17.475Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2961): 2015-11-25T13:35:17.747Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2961): Found 2 peers.
I/SS      ( 2961): Peer(1): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2961): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 2961): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2961): Added service request
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2961): 2015-11-25T13:35:18.158Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:18.257Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 2961): 2015-11-25T13:35:18.361Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:18.446Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2961): Started service discovery
,I/        ( 2961): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT501"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT501"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT501, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT501, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/jxcore-log( 2961): 2015-11-25T13:35:19.471Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 2961): 
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2961): 2015-11-25T13:35:19.553Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2961): 
,W/bt-btif ( 3030): invalid rfc slot id: 18
,I/BtToSocketBase( 2961): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2961): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2961): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT501
I/BtToSocketBase( 2961): Stop ReceivingThread
,I/BtToSocketBase( 2961): Stop SendingThread
I/BtToSocketBase( 2961): Close local in
I/BtToSocketBase( 2961): Close LocalOutputStream
I/BtToSocketBase( 2961): Close localHostSocket
I/BtToSocketBase( 2961): Close bt in
I/BtToSocketBase( 2961): Close bt out
I/BtToSocketBase( 2961): Close bt socket
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2961): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2961): 2015-11-25T13:35:20.290Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2961): 
,W/bt-rfcomm( 3030): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
W/bt-rfcomm( 3030): RFCOMM_DisconnectInd LCID:0x49
,W/bt-btif ( 3030): new conn_srvc id:26, app_id:255
W/bt-btif ( 3030): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3030): bta_dm_pm_ssr:2, lat:1200
,W/bt-btif ( 3030): new conn_srvc id:26, app_id:1
W/bt-btif ( 3030): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3030): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3030): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2961): Starting to Handshake
,I/BTListenerThread( 2961): we got incoming connection
I/BTHandshakeSocketThread( 2961): Creating BTHandshakeSocketThread
I/BTListenerThread( 2961): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2961): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2961): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread started
,I/BTListenerThread( 2961): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 2961): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3278"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread started
I/BTConnectToThread( 2961): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 2961): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3278"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3030): onReceive
,I/BTListenerThread( 2961): MESSAGE_WRITE 77 bytes.
I/HS      ( 2961): Incoming connection Hand Shake finished for : motorola-XT1039_PT3278
I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2961): Starting the connected thread incoming : true, motorola-XT1039_PT3278
I/BtToSocketBase( 2961): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2961): Creating BTConnectedThread
,I/BtConnectorHelper( 2961): Server socket is using : 0, and is now connected.
,I/BTConnectToThread( 2961): HandshakeOk : motorola-XT1039_PT3278
I/HS      ( 2961): Hand Shake finished outgoing for : motorola-XT1039_PT3278
,I/BtConnectorHelper( 2961): Starting the connected thread incoming : false, motorola-XT1039_PT3278
I/BtToSocketBase( 2961): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2961): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2961): --DoOneRunRound started
,I/BtToRequestSocket( 2961): mHTTPPort  set to : 42898
I/BtConnectorHelper( 2961): Request socket is using : 42898
I/BtToRequestSocket( 2961): Now accepting connections
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: HTC Desire 820
,I/BtToRequestSocket( 2961): LocalHost address: localhost/127.0.0.1, port: 58707
I/BtToRequestSocket( 2961): --DoOneRunRound ended
,I/jxcore-log( 2961): 2015-11-25T13:35:26.258Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2961): 
,I/BtConnectorHelper( 2961): Calling ConnectionStatusUpdate with port :42898
I/jxcore-log( 2961): 2015-11-25T13:35:26.553Z SendDataConnector.js: CLIENT connected to 42898, error: null
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:35:26.553Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2961): 
,I/BtToRequestSocket( 2961): incoming data from: /127.0.0.1, port: 42898
I/BtToRequestSocket( 2961): Set local streams
I/BtToRequestSocket( 2961): rin ended ---------------------------;
,I/jxcore-log( 2961): 2015-11-25T13:35:26.564Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:26.683Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:26.798Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:26.849Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:26.859Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:26.907Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:26.926Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:26.934Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 2961): 
,D/        ( 3030): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24979
,I/jxcore-log( 2961): 2015-11-25T13:35:26.954Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:26.967Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:26.979Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:26.991Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:27.075Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:27.106Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:27.121Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:27.133Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:27.139Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:27.165Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:27.171Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data,
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:27.221Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 2961): 
,D/        ( 3030): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13099
,I/jxcore-log( 2961): 2015-11-25T13:35:27.243Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:27.258Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:27.396Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:27.444Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:27.470Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:27.490Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 2961): 
,D/        ( 3030): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4189
,I/jxcore-log( 2961): 2015-11-25T13:35:27.504Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:27.542Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:27.548Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:27.574Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:27.614Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:27.629Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:27.690Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:27.692Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:27.772Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:27.811Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:27.835Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:27.846Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 2961): 
,I/        ( 2961): Cleared service requests
I/        ( 2961): Started peer discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2961): 2015-11-25T13:35:27.888Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:27.938Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:28.208Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:28.219Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:28.255Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:28.275Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 2961): 2015-11-25T13:35:28.338Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:28.350Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:35:28.351Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:28.353Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:35:28.353Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2961): 
I/BtConnectorHelper( 2961): Disconnect outgoing peer: F4:F1:E1:5C:3B:E2
I/BtToSocketBase( 2961): Stop ReceivingThread
I/BtToSocketBase( 2961): Stop SendingThread
I/BtToSocketBase( 2961): Close local in
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2961): Close LocalOutputStream
I/BtToSocketBase( 2961): Close localHostSocket
I/BtToSocketBase( 2961): Close bt in
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2961): Close bt out
I/BtToSocketBase( 2961): Close bt socket
I/BtToRequestSocket( 2961): Close server socket
I/jxcore-log( 2961): 2015-11-25T13:35:28.358Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): ---- round done--------
I/jxcore-log( 2961): 
I/jxcore-log( 2961): do fake peer & start
I/jxcore-log( 2961): 
I/jxcore-log( 2961): Connect to fake peer: 58:3F:54:73:64:C0
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:35:28.359Z SendDataConnector.js: Start called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:28.359Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:35:28.360Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: 58:3F:54:73:64:C0, name: null
,I/        ( 2961): Connecting to null, at 58:3F:54:73:64:C0
,I/SS      ( 2961): Found 4 peers.
I/SS      ( 2961): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2961): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2961): Peer(3): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2961): Peer(4): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/chromium( 2961): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F4:F1:E1:5C:3B:E2 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
D/WifiP2pManager( 2961): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2961): Added service request
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2961): Started service discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3030): bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3030): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:23, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3030): invalid rfc slot id: 23
,I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2961): 2015-11-25T13:35:33.521Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:35:33.522Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:35:33.522Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:33.567Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:34.675Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 2961): 
I/        ( 2961): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT1985","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT1985","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT1985, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT1985, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/jxcore-log( 2961): 2015-11-25T13:35:35.243Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:35.260Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:35.294Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:35.306Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:35.335Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:35.343Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2961): 
,W/bt-btif ( 3030): invalid rfc slot id: 20
,I/BtToSocketBase( 2961): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2961): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2961): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT3278
I/BtToSocketBase( 2961): Stop ReceivingThread
I/BtToSocketBase( 2961): Stop SendingThread
I/BtToSocketBase( 2961): Close local in
I/BtToSocketBase( 2961): Close LocalOutputStream
I/BtToSocketBase( 2961): Close localHostSocket
I/BtToSocketBase( 2961): Close bt in
I/BtToSocketBase( 2961): Close bt out
I/BtToSocketBase( 2961): Close bt socket
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2961): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2961): 2015-11-25T13:35:35.406Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2961): 
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4166cfc rs_disc_pending=0
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2961): 2015-11-25T13:35:38.527Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:35:38.527Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2961): 
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3030): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: XT1039
,I/jxcore-log( 2961): 2015-11-25T13:35:43.531Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:35:43.531Z SendDataConnector.js: Connect (retry count 1) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:35:43.532Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:35:43.532Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: 58:3F:54:73:64:C0, name: null
,I/        ( 2961): Connecting to null, at 58:3F:54:73:64:C0
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 2961): Cleared service requests
I/        ( 2961): Started peer discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3030): SDP - Rcvd conn cnf with error: 0x1f  CID 0x48
E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:24, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3030): invalid rfc slot id: 24
,I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2961): 2015-11-25T13:35:48.498Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:35:48.499Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:35:48.500Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 2961): Found 4 peers.
I/SS      ( 2961): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2961): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2961): Peer(3): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2961): Peer(4): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 2961): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2961): Added service request
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 2961): Started service discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 2961): 2015-11-25T13:35:53.501Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:35:53.502Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:35:58.507Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:35:58.508Z SendDataConnector.js: Connect (retry count 2) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:35:58.508Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:35:58.509Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: 58:3F:54:73:64:C0, name: null
,I/        ( 2961): Connecting to null, at 58:3F:54:73:64:C0
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4166ec4 rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
,E/bt-btif ( 3030): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3030): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3030): Entering PendingCommandState State
,W/BluetoothEventManager( 3063): CachedBluetoothDevice for device 58:3F:54:73:64:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3063): Got bonding state changed for 58:3F:54:73:64:C0, but we have no record of that device.
,I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
,D/BluetoothAdapterProperties( 3030): Failed to remove device: 58:3F:54:73:64:C0
,I/BluetoothBondStateMachine( 3030): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3030): StableState(): Entering Off State
,W/BluetoothEventManager( 3063): CachedBluetoothDevice for device 58:3F:54:73:64:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3063): Got bonding state changed for 58:3F:54:73:64:C0, but we have no record of that device.
,W/bt-rfcomm( 3030): PORT_StartCnf failed result:3
,W/bt-btif ( 3030): invalid rfc slot id: 25
I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2961): 2015-11-25T13:36:02.012Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:36:02.012Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:36:02.012Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2961): 
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3030): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: G3-1
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2961): 2015-11-25T13:36:07.012Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:07.013Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:12.021Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:36:12.022Z SendDataConnector.js: Connect (retry count 3) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:36:12.022Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:12.023Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: 58:3F:54:73:64:C0, name: G3-1
,I/        ( 2961): Connecting to G3-1, at 58:3F:54:73:64:C0
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: G3-1,
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4166ec4 rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,W/bt-btif ( 3030): new conn_srvc id:26, app_id:1
W/bt-btif ( 3030): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3030): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2961): Starting to Handshake
I/BTHandshakeSocketThread( 2961): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2961): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread started
,I/BTConnectToThread( 2961): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 2961): Got JSON from encryption:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2961): HandshakeOk : LGE-LG-D855_PT4505
I/HS      ( 2961): Hand Shake finished outgoing for : LGE-LG-D855_PT4505
I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2961): Starting the connected thread incoming : false, LGE-LG-D855_PT4505
,I/BtToSocketBase( 2961): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2961): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2961): mHTTPPort  set to : 45481
I/BtConnectorHelper( 2961): Request socket is using : 45481
I/BtToRequestSocket( 2961): Now accepting connections
,I/BtConnectorHelper( 2961): Calling ConnectionStatusUpdate with port :45481
I/jxcore-log( 2961): 2015-11-25T13:36:13.277Z SendDataConnector.js: CLIENT connected to 45481, error: null
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:36:13.278Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2961): 
,I/BtToRequestSocket( 2961): incoming data from: /127.0.0.1, port: 45481
I/BtToRequestSocket( 2961): Set local streams
I/BtToRequestSocket( 2961): rin ended ---------------------------;
,I/jxcore-log( 2961): 2015-11-25T13:36:13.299Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2961): 
,D/        ( 3030): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 2961): 2015-11-25T13:36:13.414Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2961): 
,D/        ( 3030): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:15797
,I/jxcore-log( 2961): 2015-11-25T13:36:13.469Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2961): 
,D/        ( 3030): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13817
,I/jxcore-log( 2961): 2015-11-25T13:36:13.474Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2961): 
,D/        ( 3030): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:6887
,I/jxcore-log( 2961): 2015-11-25T13:36:13.552Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:13.605Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:13.685Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:13.730Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:13.788Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:36:13.792Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:13.913Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:36:13.914Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:13.929Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:36:13.930Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2961): 
I/BtConnectorHelper( 2961): Disconnect outgoing peer: 58:3F:54:73:64:C0
I/BtToSocketBase( 2961): Stop ReceivingThread
I/BtToSocketBase( 2961): Stop SendingThread
I/BtToSocketBase( 2961): Close local in
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2961): Close LocalOutputStream
I/BtToSocketBase( 2961): Close localHostSocket
,I/BtToSocketBase( 2961): Close bt in
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2961): Close bt out
I/BtToSocketBase( 2961): Close bt socket
I/BtToRequestSocket( 2961): Close server socket
,I/jxcore-log( 2961): 2015-11-25T13:36:13.960Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 2961): 
I/jxcore-log( 2961): ---- round done--------
I/jxcore-log( 2961): 
I/jxcore-log( 2961): do fake peer & start
I/jxcore-log( 2961): 
I/jxcore-log( 2961): Connect to fake peer: F8:95:C7:87:85:54
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:36:13.960Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:36:13.960Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:13.960Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 2961): Connecting to null, at F8:95:C7:87:85:54
I/chromium( 2961): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 58:3F:54:73:64:C0 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3030): bta_jv_rfc_port_to_cb(port_handle:0x19):jv handle:0x0 not FOUND
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4166ec4 rs_disc_pending=0
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:27, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3030): invalid rfc slot id: 27
,I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2961): 2015-11-25T13:36:15.452Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:15.453Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:15.456Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2961): 
,W/bt-btm  ( 3030): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4166ec4 rs_disc_pending=2
E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3030): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: G3-1
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2961): 2015-11-25T13:36:20.461Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:36:20.461Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:25.465Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:36:25.467Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:36:25.467Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:36:25.468Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 2961): Connecting to null, at F8:95:C7:87:85:54
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [f8:95:c7:87:85:54]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:28, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3030): invalid rfc slot id: 28
,I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2961): 2015-11-25T13:36:26.910Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:36:26.911Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:26.913Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2961): 
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4167254 rs_disc_pending=0
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
E/bt-btif ( 3030): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3030): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3030): Entering PendingCommandState State
,W/BluetoothEventManager( 3063): CachedBluetoothDevice for device B0:C5:59:3F:75:69 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3063): Got bonding state changed for B0:C5:59:3F:75:69, but we have no record of that device.
,I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,D/BluetoothAdapterProperties( 3030): Failed to remove device: B0:C5:59:3F:75:69
,I/BluetoothBondStateMachine( 3030): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3030): StableState(): Entering Off State
,W/BluetoothEventManager( 3063): CachedBluetoothDevice for device B0:C5:59:3F:75:69 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3063): Got bonding state changed for B0:C5:59:3F:75:69, but we have no record of that device.
,W/bt-btif ( 3030): new conn_srvc id:26, app_id:255
W/bt-btif ( 3030): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3030): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2961): we got incoming connection
I/BTHandshakeSocketThread( 2961): Creating BTHandshakeSocketThread
I/BTListenerThread( 2961): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread started
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4167254 rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4167254 rs_disc_pending=0
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2961): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 2961): Got JSON from encryption:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2961): MESSAGE_WRITE 77 bytes.
I/HS      ( 2961): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT2848
I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2961): Starting the connected thread incoming : true, samsung-SM-G900F_PT2848
I/BtToSocketBase( 2961): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2961): Creating BTConnectedThread
I/BtConnectorHelper( 2961): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2961): --DoOneRunRound started
,I/jxcore-log( 2961): 2015-11-25T13:36:29.751Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2961): 
,I/BtToRequestSocket( 2961): LocalHost address: localhost/127.0.0.1, port: 58707
,I/BtToRequestSocket( 2961): --DoOneRunRound ended
,I/jxcore-log( 2961): 2015-11-25T13:36:30.252Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:30.259Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:30.309Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:30.324Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:30.452Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:30.486Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:30.525Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:30.571Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:30.616Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:30.623Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:30.626Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:30.664Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:30.668Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:30.676Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 2961): 
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2961): 2015-11-25T13:36:30.723Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:30.727Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2961): 
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4167254 rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2961): 2015-11-25T13:36:30.918Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:30.931Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:30.938Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:31.006Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:31.073Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:31.172Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:31.179Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:31.187Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:31.193Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:31.247Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:31.285Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:31.327Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:31.336Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:31.345Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:31.377Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:31.387Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:31.394Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:31.428Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:31.436Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:31.443Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:31.453Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:31.487Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2961): 
,W/bt-btif ( 3030): invalid rfc slot id: 22
,I/BtToSocketBase( 2961): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2961): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2961): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT2848
I/BtToSocketBase( 2961): Stop ReceivingThread
I/BtToSocketBase( 2961): Stop SendingThread
I/BtToSocketBase( 2961): Close local in
I/BtToSocketBase( 2961): Close LocalOutputStream
I/BtToSocketBase( 2961): Close localHostSocket
I/BtToSocketBase( 2961): Close bt in
I/BtToSocketBase( 2961): Close bt out
I/BtToSocketBase( 2961): Close bt socket
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2961): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,W/bt-rfcomm( 3030): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
W/bt-rfcomm( 3030): RFCOMM_DisconnectInd LCID:0x4a
,I/jxcore-log( 2961): 2015-11-25T13:36:31.610Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2961): 
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4167254 rs_disc_pending=0
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2961): 2015-11-25T13:36:31.923Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:36:31.926Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 2961): 
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3030): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/jxcore-log( 2961): 2015-11-25T13:36:36.931Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:36:36.931Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:36:36.932Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:36:36.932Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 2961): Connecting to null, at F8:95:C7:87:85:54
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa416708c rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:30, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3030): invalid rfc slot id: 30
,I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2961): 2015-11-25T13:36:38.854Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:36:38.855Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:36:38.856Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2961): 
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa416708c rs_disc_pending=0
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2961): 2015-11-25T13:36:43.857Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:36:43.857Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:36:48.860Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:36:48.861Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:36:48.861Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:36:48.862Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 2961): Connecting to null, at F8:95:C7:87:85:54
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 2961): Cleared service requests
I/        ( 2961): Started peer discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa416708c rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:31, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3030): invalid rfc slot id: 31
,I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2961): 2015-11-25T13:36:52.079Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:36:52.079Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:36:52.080Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 2961): Found 3 peers.
I/SS      ( 2961): Peer(1): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2961): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2961): Peer(3): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 2961): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2961): Added service request
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2961): Started service discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2961): 2015-11-25T13:36:57.081Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:36:57.082Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:37:02.083Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:37:02.084Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:37:02.084Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:37:02.084Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 2961): Connecting to null, at F8:95:C7:87:85:54
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:32, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3030): invalid rfc slot id: 32
,I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2961): 2015-11-25T13:37:03.499Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:37:03.500Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:37:03.516Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:37:03.519Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2961): 
I/jxcore-log( 2961): ---- round done--------
I/jxcore-log( 2961): 
I/jxcore-log( 2961): ---- gotta redo : F8:95:C7:87:85:54, try count now: 1
I/jxcore-log( 2961): 
I/jxcore-log( 2961): do fake peer & start
I/jxcore-log( 2961): 
I/jxcore-log( 2961): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:37:03.522Z SendDataConnector.js: Start called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:37:03.523Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:37:03.523Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 2961): Connecting to null, at 34:FC:EF:9D:93:0B
,I/chromium( 2961): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F8:95:C7:87:85:54 done with result: Connection to F8:95:C7:87:85:54 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa416741c rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa416741c rs_disc_pending=0
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
E/bt-btif ( 3030): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3030): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3030): Entering PendingCommandState State
,W/BluetoothEventManager( 3063): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 3063): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
,D/BluetoothAdapterProperties( 3030): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 3030): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3030): StableState(): Entering Off State
,W/BluetoothEventManager( 3063): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 3063): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,W/bt-btif ( 3030): new conn_srvc id:26, app_id:1
W/bt-btif ( 3030): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3030): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2961): Starting to Handshake
,I/BTHandshakeSocketThread( 2961): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2961): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread started
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa416741c rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 2961): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 2961): Got JSON from encryption:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2961): HandshakeOk : LGE-LG-D802_PT4660
,I/HS      ( 2961): Hand Shake finished outgoing for : LGE-LG-D802_PT4660
I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2961): Starting the connected thread incoming : false, LGE-LG-D802_PT4660
I/BtToSocketBase( 2961): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2961): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2961): mHTTPPort  set to : 50083
I/BtConnectorHelper( 2961): Request socket is using : 50083
I/BtToRequestSocket( 2961): Now accepting connections
,I/BtConnectorHelper( 2961): Calling ConnectionStatusUpdate with port :50083
I/jxcore-log( 2961): 2015-11-25T13:37:11.407Z SendDataConnector.js: CLIENT connected to 50083, error: null
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:37:11.407Z SendDataConnector.js: CLIENT starting client ,
I/jxcore-log( 2961): 
,I/BtToRequestSocket( 2961): incoming data from: /127.0.0.1, port: 50083
I/BtToRequestSocket( 2961): Set local streams
I/BtToRequestSocket( 2961): rin ended ---------------------------;
,I/jxcore-log( 2961): 2015-11-25T13:37:11.429Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:37:11.678Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:37:11.893Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:37:12.155Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:37:12.338Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2961): 
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa416741c rs_disc_pending=0
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2961): 2015-11-25T13:37:13.285Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:37:13.683Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:37:14.076Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:37:15.273Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:37:16.049Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:37:16.315Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:37:16.316Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:37:16.332Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:37:16.333Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2961): 
,I/BtConnectorHelper( 2961): Disconnect outgoing peer: 34:FC:EF:9D:93:0B
I/BtToSocketBase( 2961): Stop ReceivingThread
I/BtToSocketBase( 2961): Stop SendingThread
I/BtToSocketBase( 2961): Close local in
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2961): Close LocalOutputStream
,I/BtToSocketBase( 2961): Close localHostSocket
I/BtToSocketBase( 2961): Close bt in
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2961): Close bt out
,I/BtToSocketBase( 2961): Close bt socket
,I/BtToRequestSocket( 2961): Close server socket
,I/jxcore-log( 2961): 2015-11-25T13:37:16.368Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2961): 
I/jxcore-log( 2961): ---- round done--------
I/jxcore-log( 2961): 
I/jxcore-log( 2961): do fake peer & start
I/jxcore-log( 2961): 
I/jxcore-log( 2961): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:37:16.369Z SendDataConnector.js: Start called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:37:16.369Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:37:16.369Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 2961): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
I/chromium( 2961): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 34:FC:EF:9D:93:0B done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa416741c rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3030): bta_jv_rfc_port_to_cb(port_handle:0x1b):jv handle:0x0 not FOUND
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa416741c rs_disc_pending=0
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3030): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: Thali Test's G2
,I/        ( 2961): Cleared service requests
I/        ( 2961): Started peer discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2961): Found 4 peers.
I/SS      ( 2961): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2961): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2961): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2961): Peer(4): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 2961): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2961): Added service request
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2961): Started service discovery
,I/        ( 2961): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8472, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8472, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 2961): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3278"}, typeCordovap2p._tcp.local.:
,I/        ( 2961): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3278"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT3278, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT3278, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2961): Cleared service requests
I/        ( 2961): Started peer discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 2961): Found 6 peers.
I/SS      ( 2961): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2961): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2961): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2961): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2961): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2961): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2961): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2961): Added service request
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3030): SDP - Rcvd conn cnf with error: 0xeeee  CID 0x42
E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:34, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3030): invalid rfc slot id: 34
,I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2961): 2015-11-25T13:38:16.327Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:38:16.328Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:38:16.328Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2961): Started service discovery
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa41675e4 rs_disc_pending=0
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,I/        ( 2961): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT382, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT382, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
E/bt-btif ( 3030): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3030): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3030): Entering PendingCommandState State
,W/BluetoothEventManager( 3063): CachedBluetoothDevice for device 7C:F9:0E:34:8A:A0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3063): Got bonding state changed for 7C:F9:0E:34:8A:A0, but we have no record of that device.
,I/        ( 2961): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1965, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1965, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 2961): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8472, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8472, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 3030): Failed to remove device: 7C:F9:0E:34:8A:A0
,W/BluetoothEventManager( 3063): CachedBluetoothDevice for device 7C:F9:0E:34:8A:A0 not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 3030): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3030): StableState(): Entering Off State
,E/BluetoothEventManager( 3063): Got bonding state changed for 7C:F9:0E:34:8A:A0, but we have no record of that device.
,W/bt-btif ( 3030): new conn_srvc id:26, app_id:255
W/bt-btif ( 3030): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3030): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2961): we got incoming connection
I/BTHandshakeSocketThread( 2961): Creating BTHandshakeSocketThread
I/BTListenerThread( 2961): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread started
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa41675e4 rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2961): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 2961): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2961): MESSAGE_WRITE 77 bytes.
I/HS      ( 2961): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT8472
I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2961): Starting the connected thread incoming : true, samsung-SM-G900F_PT8472
I/BtToSocketBase( 2961): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2961): Creating BTConnectedThread
I/BtConnectorHelper( 2961): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2961): --DoOneRunRound started
,I/jxcore-log( 2961): 2015-11-25T13:38:19.513Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2961): 
,I/BtToRequestSocket( 2961): LocalHost address: localhost/127.0.0.1, port: 58707
,I/BtToRequestSocket( 2961): --DoOneRunRound ended
,I/jxcore-log( 2961): 2015-11-25T13:38:20.154Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:38:20.180Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:38:20.246Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:38:20.339Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:38:20.348Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:38:20.389Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:38:20.415Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:38:20.450Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:38:20.542Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 2961): 
,I/        ( 2961): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3278"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3278"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT3278, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT3278, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/jxcore-log( 2961): 2015-11-25T13:38:20.662Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:38:20.736Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:38:20.879Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:38:21.028Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:38:21.101Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:38:21.138Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:38:21.155Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:38:21.160Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:38:21.267Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:38:21.308Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:38:21.329Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:38:21.330Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:38:21.383Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:38:21.446Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:38:21.479Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:38:21.556Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:38:21.599Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:38:21.611Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:38:21.647Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:38:21.715Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:38:21.770Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:38:21.841Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:38:21.844Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:38:21.848Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:38:21.851Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:38:22.128Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:38:22.184Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:38:22.297Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:38:22.306Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:38:22.315Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:38:22.357Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2961): 
,W/bt-btif ( 3030): invalid rfc slot id: 29
,I/BtToSocketBase( 2961): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2961): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2961): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT8472
,I/BtToSocketBase( 2961): Stop ReceivingThread
I/BtToSocketBase( 2961): Stop SendingThread
I/BtToSocketBase( 2961): Close local in
I/BtToSocketBase( 2961): Close LocalOutputStream
I/BtToSocketBase( 2961): Close localHostSocket
I/BtToSocketBase( 2961): Close bt in
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2961): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2961): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT8472
I/BtToSocketBase( 2961): Close bt in
I/BtToSocketBase( 2961): Close bt out
I/BtToSocketBase( 2961): Close bt socket
,I/BtToSocketBase( 2961): Close bt out
I/BtToSocketBase( 2961): Close bt socket
,I/jxcore-log( 2961): 2015-11-25T13:38:22.490Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2961): 
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa41675e4 rs_disc_pending=0
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3030): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
W/bt-rfcomm( 3030): RFCOMM_DisconnectInd LCID:0x43
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2961): 2015-11-25T13:38:26.333Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:38:26.335Z SendDataConnector.js: Connect (retry count 1) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:38:26.336Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:38:26.336Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 2961): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3030): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: S5-1
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2961): Cleared service requests
I/        ( 2961): Started peer discovery
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2961): Found 7 peers.
I/SS      ( 2961): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2961): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2961): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2961): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2961): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2961): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2961): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2961): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2961): Added service request
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2961): Started service discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3030): SDP - Rcvd conn cnf with error: 0xeeee  CID 0x45
E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:36, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3030): invalid rfc slot id: 36
,I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2961): 2015-11-25T13:39:25.510Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:39:25.511Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:39:25.511Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2961): 
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa41677ac rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 2961): Cleared service requests
I/        ( 2961): Started peer discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2961): Found 8 peers.
I/SS      ( 2961): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2961): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2961): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
,I/SS      ( 2961): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2961): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2961): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2961): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2961): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 2961): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2961): Added service request
,I/jxcore-log( 2961): 2015-11-25T13:39:30.512Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:39:30.513Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2961): Started service discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3030): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3030): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3030): Entering PendingCommandState State
,W/BluetoothEventManager( 3063): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3063): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3030): Failed to remove device: F8:95:C7:87:3C:51
,W/BluetoothEventManager( 3063): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 3030): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3030): StableState(): Entering Off State
,E/BluetoothEventManager( 3063): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,W/bt-btif ( 3030): new conn_srvc id:26, app_id:255
W/bt-btif ( 3030): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3030): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 2961): we got incoming connection
I/BTHandshakeSocketThread( 2961): Creating BTHandshakeSocketThread
I/BTListenerThread( 2961): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread started
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 2961): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT382, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT382, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 2961): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1965, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1965, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/BTListenerThread( 2961): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 2961): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2961): MESSAGE_WRITE 77 bytes.
I/HS      ( 2961): Incoming connection Hand Shake finished for : LGE-LG-H815_PT1965
I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2961): Starting the connected thread incoming : true, LGE-LG-H815_PT1965
I/BtToSocketBase( 2961): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2961): Creating BTConnectedThread
I/BtConnectorHelper( 2961): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2961): --DoOneRunRound started
,I/jxcore-log( 2961): 2015-11-25T13:39:35.297Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2961): 
,I/BtToRequestSocket( 2961): LocalHost address: localhost/127.0.0.1, port: 58707
,I/BtToRequestSocket( 2961): --DoOneRunRound ended
,I/jxcore-log( 2961): 2015-11-25T13:39:35.519Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:39:35.520Z SendDataConnector.js: Connect (retry count 2) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:39:35.521Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:39:35.521Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 2961): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 2961): 2015-11-25T13:39:35.891Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:36.318Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:36.327Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:36.336Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2961): 
,I/        ( 2961): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8472, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8472, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/jxcore-log( 2961): 2015-11-25T13:39:36.914Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:36.974Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:37.312Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:37.458Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 2961): 
,I/        ( 2961): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"}, typeCordovap2p._tcp.local.:
,I/        ( 2961): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4660, peerAddress: 34:FC:EF:9D:93:0B
,I/jxcore-log( 2961): 2015-11-25T13:39:37.690Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 2961): 
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4660, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/jxcore-log( 2961): 2015-11-25T13:39:38.212Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:38.534Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:38.544Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:38.983Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:39.408Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:39.709Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:39.712Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:40.067Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2961): 
,I/        ( 2961): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3278"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3278"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT3278, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT3278, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/jxcore-log( 2961): 2015-11-25T13:39:40.451Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:40.772Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:40.782Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:41.334Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:41.860Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:42.956Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:42.961Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:42.972Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:43.335Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
,I/jxcore-log( 2961): 2015-11-25T13:39:43.677Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:43.684Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:43.696Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:44.051Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:44.063Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:44.399Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:44.407Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:44.583Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:44.924Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:44.966Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:45.006Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:45.318Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:45.327Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:45.334Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:45.598Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:45.635Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:45.690Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:46.023Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:46.032Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:46.388Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:46.406Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:46.543Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:39:46.844Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa41677ac rs_disc_pending=0
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3030): invalid rfc slot id: 35
,I/BtToSocketBase( 2961): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2961): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2961): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT1965
I/BtToSocketBase( 2961): Stop ReceivingThread
I/BtToSocketBase( 2961): Stop SendingThread
I/BtToSocketBase( 2961): Close local in
I/BtToSocketBase( 2961): Close LocalOutputStream
I/BtToSocketBase( 2961): Close localHostSocket
I/BtToSocketBase( 2961): Close bt in
I/BtToSocketBase( 2961): Close bt out
I/BtToSocketBase( 2961): Close bt socket
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2961): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2961): 2015-11-25T13:39:49.246Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2961): 
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa41677ac rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,I/        ( 2961): Cleared service requests
I/        ( 2961): Started peer discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2961): Found 4 peers.
I/SS      ( 2961): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2961): Peer(2): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2961): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2961): Peer(4): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2961): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2961): Added service request
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2961): Started service discovery
,I/        ( 2961): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8472, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8472, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 2961): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1965, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1965, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3030): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: G4-1
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2961): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2848, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2848, WifiDirectName: , WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2961): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3278"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3278"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT3278, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT3278, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [34:fc:ef:9d:93:0b]: 7, f, 6109
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: Thali Test's G2
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa416741c rs_disc_pending=0
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
E/bt-btif ( 3030): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3030): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3030): Entering PendingCommandState State
,W/BluetoothEventManager( 3063): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 3063): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
,D/BluetoothAdapterProperties( 3030): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 3030): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,W/BluetoothEventManager( 3063): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 3030): StableState(): Entering Off State
,E/BluetoothEventManager( 3063): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,W/bt-btif ( 3030): new conn_srvc id:26, app_id:255
W/bt-btif ( 3030): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3030): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2961): we got incoming connection
,I/BTHandshakeSocketThread( 2961): Creating BTHandshakeSocketThread
I/BTListenerThread( 2961): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread started
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa416741c rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa416741c rs_disc_pending=0
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2961): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 2961): Got JSON from encryption:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2961): MESSAGE_WRITE 77 bytes.
I/HS      ( 2961): Incoming connection Hand Shake finished for : LGE-LG-D802_PT4660
I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2961): Starting the connected thread incoming : true, LGE-LG-D802_PT4660
,I/BtToSocketBase( 2961): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2961): Creating BTConnectedThread
,I/BtConnectorHelper( 2961): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2961): --DoOneRunRound started
,I/jxcore-log( 2961): 2015-11-25T13:40:06.137Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2961): 
,I/BtToRequestSocket( 2961): LocalHost address: localhost/127.0.0.1, port: 58707
I/BtToRequestSocket( 2961): --DoOneRunRound ended
,I/jxcore-log( 2961): 2015-11-25T13:40:06.700Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:06.781Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:06.833Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:06.842Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:06.935Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:06.954Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:07.022Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:07.062Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:07.065Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:07.090Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:07.238Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:07.328Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:07.357Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:07.450Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:07.486Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:07.570Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:07.605Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:07.649Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:07.707Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:07.747Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:07.834Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 2961): 
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2961): 2015-11-25T13:40:07.938Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:07.966Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:08.059Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:08.095Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:08.135Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:08.385Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:08.470Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 2961): 
,I/        ( 2961): Cleared service requests
I/        ( 2961): Started peer discovery
,I/jxcore-log( 2961): 2015-11-25T13:40:08.779Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:08.845Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 2961): 2015-11-25T13:40:09.086Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:09.152Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:09.199Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:09.314Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2961): 2015-11-25T13:40:09.439Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 2961): 
,I/SS      ( 2961): Found 9 peers.
I/SS      ( 2961): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2961): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2961): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2961): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2961): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2961): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2961): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2961): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2961): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2961): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2961): Added service request
,I/jxcore-log( 2961): 2015-11-25T13:40:09.454Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:09.625Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:09.770Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:09.979Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:10.018Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:10.047Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:10.135Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:10.205Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:10.346Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 2961): 
,I/        ( 2961): Started service discovery
,I/jxcore-log( 2961): 2015-11-25T13:40:10.466Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:10.547Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:10.659Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 2961): 2015-11-25T13:40:10.770Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:10.840Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:11.090Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2961): 2015-11-25T13:40:11.189Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:11.401Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:11.486Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2961): 
,W/bt-btif ( 3030): invalid rfc slot id: 37
,I/BtToSocketBase( 2961): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2961): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2961): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT4660
I/BtToSocketBase( 2961): Stop ReceivingThread
I/BtToSocketBase( 2961): Stop SendingThread
I/BtToSocketBase( 2961): Close local in
I/BtToSocketBase( 2961): Close LocalOutputStream
I/BtToSocketBase( 2961): Close localHostSocket
I/BtToSocketBase( 2961): Close bt in
I/BtToSocketBase( 2961): Close bt out
I/BtToSocketBase( 2961): Close bt socket
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2961): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2961): 2015-11-25T13:40:11.647Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2961): 
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa416741c rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3030): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
W/bt-rfcomm( 3030): RFCOMM_DisconnectInd LCID:0x4c
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa416741c rs_disc_pending=0
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3030): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: Thali Test's G2
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4167974 rs_disc_pending=0
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 1
E/bt-btif ( 3030): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3030): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3030): Entering PendingCommandState State
,W/BluetoothEventManager( 3063): CachedBluetoothDevice for device E0:DB:10:1F:C9:5E not found, calling readPairedDevices().
,E/BluetoothEventManager( 3063): Got bonding state changed for E0:DB:10:1F:C9:5E, but we have no record of that device.
,I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 0
,D/BluetoothAdapterProperties( 3030): Failed to remove device: E0:DB:10:1F:C9:5E
,I/BluetoothBondStateMachine( 3030): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3030): StableState(): Entering Off State
,W/BluetoothEventManager( 3063): CachedBluetoothDevice for device E0:DB:10:1F:C9:5E not found, calling readPairedDevices().
,E/BluetoothEventManager( 3063): Got bonding state changed for E0:DB:10:1F:C9:5E, but we have no record of that device.
,W/bt-btif ( 3030): new conn_srvc id:26, app_id:255
W/bt-btif ( 3030): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3030): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2961): we got incoming connection
I/BTHandshakeSocketThread( 2961): Creating BTHandshakeSocketThread
I/BTListenerThread( 2961): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread started
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4167974 rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4167974 rs_disc_pending=0
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2961): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 2961): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT760","ra":"E0:DB:10:1F:C9:5E"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2961): MESSAGE_WRITE 77 bytes.
I/HS      ( 2961): Incoming connection Hand Shake finished for : samsung-SM-N9005_PT760
I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2961): Starting the connected thread incoming : true, samsung-SM-N9005_PT760
I/BtToSocketBase( 2961): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2961): Creating BTConnectedThread
I/BtConnectorHelper( 2961): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2961): --DoOneRunRound started
,I/BtToRequestSocket( 2961): LocalHost address: localhost/127.0.0.1, port: 58707
,I/jxcore-log( 2961): 2015-11-25T13:40:20.995Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2961): 
,I/BtToRequestSocket( 2961): --DoOneRunRound ended
,I/jxcore-log( 2961): 2015-11-25T13:40:21.478Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:21.483Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:21.537Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:21.578Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:21.586Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:21.598Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:21.642Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:21.674Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:21.683Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:21.689Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:21.711Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:21.748Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:21.806Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:21.847Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:21.851Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:21.879Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:21.889Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:21.968Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:22.007Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:22.015Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:22.022Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:22.064Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:22.073Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:22.087Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:22.120Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:22.130Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:40:22.132Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:22.164Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:22.176Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:22.184Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:22.206Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:22.246Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:22.266Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:22.478Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:22.486Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2961): 
,W/bt-btif ( 3030): invalid rfc slot id: 39
,I/BtToSocketBase( 2961): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2961): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2961): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N9005_PT760
,I/BtToSocketBase( 2961): Stop ReceivingThread
I/BtToSocketBase( 2961): Stop SendingThread
I/BtToSocketBase( 2961): Close local in
I/BtToSocketBase( 2961): Close LocalOutputStream
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2961): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2961): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N9005_PT760
I/BtToSocketBase( 2961): Close bt in
I/BtToSocketBase( 2961): Close bt out
I/BtToSocketBase( 2961): Close bt socket
,I/BtToSocketBase( 2961): Close localHostSocket
I/BtToSocketBase( 2961): Close bt in
,I/BtToSocketBase( 2961): Close bt out
I/BtToSocketBase( 2961): Close bt socket
,I/jxcore-log( 2961): 2015-11-25T13:40:22.636Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2961): 
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4167974 rs_disc_pending=1
,W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3030): rfc_find_lcid_mcb LCID reused LCID:0x4e current:0x0
W/bt-rfcomm( 3030): RFCOMM_DisconnectInd LCID:0x4e
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3030): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: Note3-1
,I/BtConnection( 2961): connectionTimeoutTimer
,I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3030): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:38, channel:-1
,I/CONNEC  ( 2961): Error: Cancelled
I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2961): 2015-11-25T13:40:35.547Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:40:35.548Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:40:35.549Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2961): 
W/jxcore-log( 2961): $$jxcore_callback_52 wasn't registered
W/jxcore-log( 2961): 
,W/bt-sdp  ( 3030): SDP - Rcvd conn cnf with error: 0xeeee  CID 0x47
E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:38, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3030): invalid rfc slot id: 38
,I/jxcore-log( 2961): 2015-11-25T13:40:40.550Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:40:40.551Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:40:45.556Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:40:45.556Z SendDataConnector.js: Connect (retry count 3) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:40:45.557Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:40:45.557Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 2961): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [58:3f:54:73:64:c0]: 7, f, 6109
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: G3-1
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4166ec4 rs_disc_pending=0
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3030): new conn_srvc id:26, app_id:255
W/bt-btif ( 3030): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3030): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2961): we got incoming connection
I/BTHandshakeSocketThread( 2961): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2961): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread started
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4166ec4 rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4166ec4 rs_disc_pending=0
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,I/        ( 2961): Cleared service requests
,I/        ( 2961): Started peer discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BTListenerThread( 2961): got MESSAGE_READ 77 bytes.
,I/BTListenerThread( 2961): Got JSON from encryption:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2961): MESSAGE_WRITE 77 bytes.
I/HS      ( 2961): Incoming connection Hand Shake finished for : LGE-LG-D855_PT4505
I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2961): Starting the connected thread incoming : true, LGE-LG-D855_PT4505
,I/BtToSocketBase( 2961): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2961): Creating BTConnectedThread
,I/BtConnectorHelper( 2961): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2961): --DoOneRunRound started
,I/jxcore-log( 2961): 2015-11-25T13:41:09.540Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2961): 
,I/BtToRequestSocket( 2961): LocalHost address: localhost/127.0.0.1, port: 58707
,I/BtToRequestSocket( 2961): --DoOneRunRound ended
,I/jxcore-log( 2961): 2015-11-25T13:41:10.085Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:10.107Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:10.111Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:10.113Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:10.145Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:10.152Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:10.199Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:10.206Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:10.222Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:10.233Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2961): 2015-11-25T13:41:10.269Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:10.396Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:10.441Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:10.449Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2961): 2015-11-25T13:41:10.540Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 2961): 
,I/SS      ( 2961): Found 9 peers.
I/SS      ( 2961): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2961): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2961): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2961): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2961): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2961): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2961): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2961): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2961): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2961): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2961): Added service request
,I/jxcore-log( 2961): 2015-11-25T13:41:10.672Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2961): 2015-11-25T13:41:10.862Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:10.904Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:41:10.906Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:10.916Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:11.004Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:11.046Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:11.180Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:11.285Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2961): 2015-11-25T13:41:11.325Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:11.372Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:11.384Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:11.455Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:11.462Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:11.506Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:11.637Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:11.709Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:11.764Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:11.838Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:11.928Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:12.079Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:12.185Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:12.198Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:12.222Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:12.261Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:12.376Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:12.385Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:12.426Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:12.466Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:12.472Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:12.479Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:12.492Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:12.563Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:12.607Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:12.615Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:12.649Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:12.656Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2961): 
,W/bt-btif ( 3030): invalid rfc slot id: 40
,I/BtToSocketBase( 2961): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2961): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2961): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D855_PT4505
I/BtToSocketBase( 2961): Stop ReceivingThread
I/BtToSocketBase( 2961): Stop SendingThread
I/BtToSocketBase( 2961): Close local in
I/BtToSocketBase( 2961): Close LocalOutputStream
I/BtToSocketBase( 2961): Close localHostSocket
I/BtToSocketBase( 2961): Close bt in
I/BtToSocketBase( 2961): Close bt out
I/BtToSocketBase( 2961): Close bt socket
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2961): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2961): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D855_PT4505
I/BtToSocketBase( 2961): Close bt in
I/BtToSocketBase( 2961): Close bt out
I/BtToSocketBase( 2961): Close bt socket
,I/jxcore-log( 2961): 2015-11-25T13:41:12.897Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2961): Started service discovery
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4166ec4 rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2961): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2848, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2848, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3030): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: G3-1
,I/        ( 2961): Cleared service requests
I/        ( 2961): Started peer discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2961): Found 3 peers.
I/SS      ( 2961): Peer(1): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2961): Peer(2): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 2961): Peer(3): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2961): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2961): Added service request
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2961): Started service discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 2961): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"}, typeCordovap2p._tcp.local.:
,I/        ( 2961): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4660, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4660, WifiDirectName: , WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 2961): Cleared service requests
I/        ( 2961): Started peer discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2961): Found 4 peers.
I/SS      ( 2961): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2961): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2961): Peer(3): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 2961): Peer(4): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2961): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2961): Added service request
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2961): Started service discovery
,I/        ( 2961): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4660, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4660, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/BtConnection( 2961): connectionTimeoutTimer
,I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3030): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:41, channel:-1
,I/CONNEC  ( 2961): Error: Cancelled
I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2961): 2015-11-25T13:41:45.586Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:45.591Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:45.592Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2961): 
,W/jxcore-log( 2961): $$jxcore_callback_54 wasn't registered
W/jxcore-log( 2961): 
,W/bt-sdp  ( 3030): SDP - Rcvd conn cnf with error: 0xeeee  CID 0x48
E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:41, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3030): invalid rfc slot id: 41
,I/        ( 2961): Cleared service requests
I/        ( 2961): Started peer discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2961): Found 5 peers.
I/SS      ( 2961): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2961): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2961): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2961): Peer(4): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 2961): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2961): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2961): Added service request
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2961): Started service discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2961): 2015-11-25T13:41:50.598Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:41:50.599Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2961): 
,I/        ( 2961): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6613","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6613","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT6613, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT6613, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/jxcore-log( 2961): 2015-11-25T13:41:55.602Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:55.603Z SendDataConnector.js: Connect (retry count 4) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:55.606Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:41:55.609Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 2961): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 2961): Cleared service requests
I/        ( 2961): Started peer discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2961): Found 6 peers.
I/SS      ( 2961): Peer(1): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2961): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 2961): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2961): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2961): Peer(5): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 2961): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2961): Ignored { when=-6ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2961): Added service request,
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2961): Started service discovery
,I/        ( 2961): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8472, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8472, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 2961): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT9583, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT9583, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 2961): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6613","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6613","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT6613, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT6613, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 2961): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3278"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3278"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT3278, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT3278, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/art     (  759): Explicit concurrent mark sweep GC freed 54245(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 28MB/42MB, paused 1.119ms total 86.194ms
,I/EventLogService( 1558): Aggregate from 1448457016924 (log), 1448457016924 (data)
,I/        ( 2961): Cleared service requests
I/        ( 2961): Started peer discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2961): Found 7 peers.
I/SS      ( 2961): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2961): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2961): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2961): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2961): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2961): Peer(6): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 2961): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2961): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2961): Added service request
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2961): Started service discovery
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2961): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT7950","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT7950","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT7950, peerAddress: F8:CF:C5:D9:E5:61
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT7950, WifiDirectName: , WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,I/        ( 2961): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6613","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6613","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT6613, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT6613, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 2961): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3278"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3278"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT3278, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT3278, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 2961): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4660, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4660, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 2961): Cleared service requests
I/        ( 2961): Started peer discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2961): Found 7 peers.
I/SS      ( 2961): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2961): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2961): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2961): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2961): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2961): Peer(6): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 2961): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2961): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2961): Added service request
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2961): Started service discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2961): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT7950","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT7950","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT7950, peerAddress: F8:CF:C5:D9:E5:61
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT7950, WifiDirectName: , WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,I/        ( 2961): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 2961): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8472, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8472, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 2961): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3278"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3278"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT3278, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT3278, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/BtConnection( 2961): connectionTimeoutTimer
,I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3030): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:43, channel:-1
,I/CONNEC  ( 2961): Error: Cancelled
I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2961): 2015-11-25T13:42:55.636Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:42:55.637Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:42:55.653Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:42:55.658Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2961): 
I/jxcore-log( 2961): ---- round done--------
I/jxcore-log( 2961): 
I/jxcore-log( 2961): ---- gotta redo : 58:2A:F7:ED:96:BE, try count now: 1
I/jxcore-log( 2961): 
I/jxcore-log( 2961): do fake peer & start
I/jxcore-log( 2961): 
I/jxcore-log( 2961): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:42:55.660Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:42:55.661Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:42:55.662Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2961): Connecting to null, at 00:F4:6F:30:E0:6C
,W/bt-sdp  ( 3030): SDP - Rcvd conn cnf with error: 0xeeee  CID 0x44
E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:43, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3030): invalid rfc slot id: 43
,I/jxcore-log( 2961): 2015-11-25T13:42:55.692Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 2961): 
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 2961): 2015-11-25T13:42:55.693Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:42:55.706Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2961): 
I/chromium( 2961): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 58:2A:F7:ED:96:BE done with result: Connection to 58:2A:F7:ED:96:BE failed", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4167b3c rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,I/        ( 2961): Cleared service requests
I/        ( 2961): Started peer discovery
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4167b3c rs_disc_pending=0
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:44, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3030): invalid rfc slot id: 44
,I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/jxcore-log( 2961): $$jxcore_callback_58 wasn't registered
W/jxcore-log( 2961): 
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2961): Found 8 peers.
,I/SS      ( 2961): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2961): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2961): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2961): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2961): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2961): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2961): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 2961): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2961): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2961): Added service request
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2961): 2015-11-25T13:43:00.711Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:43:00.711Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2961): Started service discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2961): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8472, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8472, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/jxcore-log( 2961): 2015-11-25T13:43:05.718Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:43:05.718Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:43:05.719Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:43:05.719Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2961): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4167b3c rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:45, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3030): invalid rfc slot id: 45
,I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2961): 2015-11-25T13:43:06.821Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:43:06.822Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:43:06.822Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2961): 
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4167b3c rs_disc_pending=0
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,I/        ( 2961): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3278"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3278"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT3278, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT3278, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/jxcore-log( 2961): 2015-11-25T13:43:11.823Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:43:11.824Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2961): 
,I/        ( 2961): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2848, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2848, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 2961): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1965, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1965, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2961): 2015-11-25T13:43:16.827Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
,I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:43:16.828Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:43:16.829Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:43:16.829Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2961): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4167b3c rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:46, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3030): invalid rfc slot id: 46
,I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2961): 2015-11-25T13:43:18.314Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:43:18.314Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:43:18.315Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 2961): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT382, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT382, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4167b3c rs_disc_pending=0
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2961): 2015-11-25T13:43:23.316Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:43:23.317Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/        ( 2961): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT4505, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT4505, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2961): 2015-11-25T13:43:28.320Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:43:28.321Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:43:28.322Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:43:28.322Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2961): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4167b3c rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:47, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3030): invalid rfc slot id: 47
,I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2961): 2015-11-25T13:43:30.297Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:43:30.297Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:43:30.298Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4167b3c rs_disc_pending=0
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2961): Cleared service requests
I/        ( 2961): Started peer discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2961): Found 11 peers.
I/SS      ( 2961): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2961): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
,I/SS      ( 2961): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2961): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2961): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2961): Peer(6): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2961): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2961): Peer(8): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2961): Peer(9): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2961): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2961): Peer(11): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2961): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2961): Added service request
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2961): Started service discovery
,I/jxcore-log( 2961): 2015-11-25T13:43:35.299Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:43:35.300Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:43:40.304Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:43:40.305Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:43:40.305Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:43:40.306Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2961): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4167b3c rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:48, failed to find channle,                                       status:1, scn:0
,I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,W/bt-btif ( 3030): invalid rfc slot id: 48
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2961): 2015-11-25T13:43:42.362Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:43:42.363Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:43:42.381Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:43:42.387Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2961): 
I/jxcore-log( 2961): ---- round done--------
I/jxcore-log( 2961): 
I/jxcore-log( 2961): ---- gotta redo : 00:F4:6F:30:E0:6C, try count now: 1
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): do fake peer & start
I/jxcore-log( 2961): 
I/jxcore-log( 2961): Connect to fake peer: 7C:F9:0E:37:96:AB
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:43:42.390Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:43:42.391Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:43:42.392Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/        ( 2961): Connecting to null, at 7C:F9:0E:37:96:AB
,I/chromium( 2961): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 00:F4:6F:30:E0:6C done with result: Connection to 00:F4:6F:30:E0:6C failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4167b3c rs_disc_pending=0
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3030): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:49, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3030): invalid rfc slot id: 49
,I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2961): 2015-11-25T13:43:47.547Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:43:47.548Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:43:47.549Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
,I/jxcore-log( 2961): 2015-11-25T13:43:52.550Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:43:52.551Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:43:57.556Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:43:57.557Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:43:57.558Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:43:57.558Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/        ( 2961): Connecting to null, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4167d04 rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:50, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3030): invalid rfc slot id: 50
,I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2961): 2015-11-25T13:44:00.110Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:44:00.111Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:44:00.111Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2961): 
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2961): 2015-11-25T13:44:05.112Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:44:05.113Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:44:10.121Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:44:10.122Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:44:10.123Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:44:10.127Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/        ( 2961): Connecting to null, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4167d04 rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:51, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3030): invalid rfc slot id: 51
,I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2961): 2015-11-25T13:44:13.304Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:44:13.305Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:44:13.305Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2961): 
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2961): 2015-11-25T13:44:18.306Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:44:18.307Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:44:23.308Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:44:23.308Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:44:23.308Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:44:23.308Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/        ( 2961): Connecting to null, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:52, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3030): invalid rfc slot id: 52
,I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2961): 2015-11-25T13:44:26.309Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:44:26.309Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:44:26.310Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2961): 
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2961): 2015-11-25T13:44:31.311Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:44:31.312Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2961): 
,I/        ( 2961): Cleared service requests
I/        ( 2961): Started peer discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 2961): Found 10 peers.
I/SS      ( 2961): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2961): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
,I/SS      ( 2961): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2961): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2961): Peer(5): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2961): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2961): Peer(7): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2961): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2961): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2961): Peer(10): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2961): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2961): Added service request
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2961): Started service discovery
,I/jxcore-log( 2961): 2015-11-25T13:44:36.315Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:44:36.316Z SendDataConnector.js: Connect (retry count 4) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:44:36.316Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:44:36.317Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/        ( 2961): Connecting to null, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:53, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3030): invalid rfc slot id: 53
,I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2961): 2015-11-25T13:44:39.135Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:44:39.136Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:44:39.170Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:44:39.177Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2961): 
I/jxcore-log( 2961): ---- round done--------
I/jxcore-log( 2961): 
I/jxcore-log( 2961): ---- gotta redo : 7C:F9:0E:37:96:AB, try count now: 1
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): do fake peer & start
I/jxcore-log( 2961): 
I/jxcore-log( 2961): Connect to fake peer: F8:CF:C5:D9:E5:61
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:44:39.189Z SendDataConnector.js: Start called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:44:39.190Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:44:39.191Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: F8:CF:C5:D9:E5:61, name: Nexus 6
,I/        ( 2961): Connecting to Nexus 6, at F8:CF:C5:D9:E5:61
,I/chromium( 2961): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 7C:F9:0E:37:96:AB done with result: Connection to 7C:F9:0E:37:96:AB failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [f8:cf:c5:d9:e5:61]: 6, f, 4106
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: Nexus 6
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,W/bt-btif ( 3030): new conn_srvc id:26, app_id:1
W/bt-btif ( 3030): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3030): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2961): Starting to Handshake
,I/BTHandshakeSocketThread( 2961): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2961): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread started
,I/BTConnectToThread( 2961): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 2961): Got JSON from encryption:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT7950","ra":"F8:CF:C5:D9:E5:61"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2961): HandshakeOk : motorola-Nexus 6_PT7950
I/HS      ( 2961): Hand Shake finished outgoing for : motorola-Nexus 6_PT7950
I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2961): Starting the connected thread incoming : false, motorola-Nexus 6_PT7950
,I/BtToSocketBase( 2961): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2961): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2961): mHTTPPort  set to : 39873
I/BtConnectorHelper( 2961): Request socket is using : 39873
I/BtToRequestSocket( 2961): Now accepting connections
,I/BtConnectorHelper( 2961): Calling ConnectionStatusUpdate with port :39873
I/jxcore-log( 2961): 2015-11-25T13:44:41.520Z SendDataConnector.js: CLIENT connected to 39873, error: null
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:44:41.520Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2961): 
,I/BtToRequestSocket( 2961): incoming data from: /127.0.0.1, port: 39873
I/BtToRequestSocket( 2961): Set local streams
I/BtToRequestSocket( 2961): rin ended ---------------------------;
,I/jxcore-log( 2961): 2015-11-25T13:44:41.524Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2961): 
,D/        ( 3030): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24979
,I/jxcore-log( 2961): 2015-11-25T13:44:41.787Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:44:42.120Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2961): 
,D/        ( 3030): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14089
,I/jxcore-log( 2961): 2015-11-25T13:44:42.364Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:44:42.593Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2961): 
,D/        ( 3030): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3199
,I/jxcore-log( 2961): 2015-11-25T13:44:42.762Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:44:42.929Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:44:42.977Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:44:43.101Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2961): 
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2961): 2015-11-25T13:44:43.187Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:44:43.256Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:44:43.273Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:44:43.290Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:44:43.291Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2961): 
,I/BtConnectorHelper( 2961): Disconnect outgoing peer: F8:CF:C5:D9:E5:61
I/BtToSocketBase( 2961): Stop ReceivingThread
I/BtToSocketBase( 2961): Stop SendingThread
I/BtToSocketBase( 2961): Close local in
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2961): Close LocalOutputStream
I/BtToSocketBase( 2961): Close localHostSocket
I/BtToSocketBase( 2961): Close bt in
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2961): Close bt out
,I/BtToSocketBase( 2961): Close bt socket
I/BtToRequestSocket( 2961): Close server socket
I/jxcore-log( 2961): 2015-11-25T13:44:43.324Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2961): 
,W/bt-btif ( 3030): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,I/jxcore-log( 2961): ---- round done--------
I/jxcore-log( 2961): 
I/jxcore-log( 2961): do fake peer & start
I/jxcore-log( 2961): 
I/jxcore-log( 2961): Connect to fake peer: B0:C5:59:3F:75:69
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:44:43.339Z SendDataConnector.js: Start called with peer B0:C5:59:3F:75:69
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:44:43.339Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:44:43.339Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: B0:C5:59:3F:75:69, name: Thali Test (Galaxy S5)
,I/        ( 2961): Connecting to Thali Test (Galaxy S5), at B0:C5:59:3F:75:69
,I/chromium( 2961): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F8:CF:C5:D9:E5:61 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [b0:c5:59:3f:75:69]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: Thali Test (Galaxy S5)
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4167254 rs_disc_pending=0
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,W/bt-btif ( 3030): new conn_srvc id:26, app_id:1
W/bt-btif ( 3030): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3030): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2961): Starting to Handshake
I/BTHandshakeSocketThread( 2961): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2961): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread started
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4167254 rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 2961): got MESSAGE_READ 82 bytes.,
I/BTConnectToThread( 2961): Got JSON from encryption:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2961): HandshakeOk : samsung-SM-G900F_PT2848
I/HS      ( 2961): Hand Shake finished outgoing for : samsung-SM-G900F_PT2848
I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2961): Starting the connected thread incoming : false, samsung-SM-G900F_PT2848
I/BtToSocketBase( 2961): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2961): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2961): mHTTPPort  set to : 55129
,I/BtConnectorHelper( 2961): Request socket is using : 55129
,I/BtToRequestSocket( 2961): Now accepting connections
,I/BtConnectorHelper( 2961): Calling ConnectionStatusUpdate with port :55129
,I/jxcore-log( 2961): 2015-11-25T13:44:46.273Z SendDataConnector.js: CLIENT connected to 55129, error: null
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:44:46.276Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2961): 
,I/BtToRequestSocket( 2961): incoming data from: /127.0.0.1, port: 55129
I/BtToRequestSocket( 2961): Set local streams
,I/BtToRequestSocket( 2961): rin ended ---------------------------;
,I/jxcore-log( 2961): 2015-11-25T13:44:46.303Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2961): 
,D/        ( 3030): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:403
,I/jxcore-log( 2961): 2015-11-25T13:44:46.782Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2961): 
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa41667a4 rs_disc_pending=0
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2961): 2015-11-25T13:44:47.178Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2961): 
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3030): onReceive
,I/jxcore-log( 2961): 2015-11-25T13:44:47.403Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2961): 
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: Nexus 6
,I/jxcore-log( 2961): 2015-11-25T13:44:47.643Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:44:47.768Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2961): 2015-11-25T13:44:48.081Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:44:48.551Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:44:49.157Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:44:49.480Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:44:50.081Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:44:50.082Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:44:50.097Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:44:50.098Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2961): 
I/BtConnectorHelper( 2961): Disconnect outgoing peer: B0:C5:59:3F:75:69
I/BtToSocketBase( 2961): Stop ReceivingThread
I/BtToSocketBase( 2961): Stop SendingThread
I/BtToSocketBase( 2961): Close local in
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2961): Close LocalOutputStream
,I/BtToSocketBase( 2961): Close localHostSocket
I/BtToSocketBase( 2961): Close bt in
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2961): Close bt out
I/BtToSocketBase( 2961): Close bt socket
I/BtToRequestSocket( 2961): Close server socket
I/jxcore-log( 2961): 2015-11-25T13:44:50.127Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 2961): 
I/jxcore-log( 2961): ---- round done--------
I/jxcore-log( 2961): 
I/jxcore-log( 2961): do fake peer & start
I/jxcore-log( 2961): 
I/jxcore-log( 2961): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:44:50.129Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:44:50.129Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:44:50.130Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2961): Connecting to null, at 34:FC:EF:11:B1:66
I/chromium( 2961): [INFO:CONSOLE(63)] "logCallback Round of send data to peer B0:C5:59:3F:75:69 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 3030): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3030): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: Thali Test (Galaxy S5)
,W/bt-sdp  ( 3030): SDP - Rcvd conn cnf with error: 0x22  CID 0x44
E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:56, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3030): invalid rfc slot id: 56
,I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2961): 2015-11-25T13:45:21.079Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:45:21.080Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:45:21.080Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:45:26.115Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:45:26.116Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:45:31.120Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:45:31.120Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:45:31.121Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:45:31.121Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2961): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2961): Starting to connect
,W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3030): No ag scb for peer addr
,I/        ( 2961): Cleared service requests
I/        ( 2961): Started peer discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2961): Found 5 peers.
I/SS      ( 2961): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2961): Peer(2): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2961): Peer(3): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2961): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2961): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2961): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2961): Added service request
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2961): Started service discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,I/UsageStatsService(  759): User[0] Flushing usage stats to disk
,I/BtConnection( 2961): connectionTimeoutTimer
,I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3030): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:57, channel:-1
,I/CONNEC  ( 2961): Error: Cancelled
I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2961): 2015-11-25T13:46:31.147Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:46:31.148Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:46:31.148Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2961): 
W/jxcore-log( 2961): $$jxcore_callback_84 wasn't registered
W/jxcore-log( 2961): 
,E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:57, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3030): invalid rfc slot id: 57
,I/        ( 2961): Cleared service requests
I/        ( 2961): Started peer discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2961): Found 4 peers.
I/SS      ( 2961): Peer(1): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2961): Peer(2): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2961): Peer(3): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 2961): Peer(4): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2961): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2961): Added service request
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2961): 2015-11-25T13:46:36.149Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:46:36.150Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 2961): Started service discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 2961): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2890, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2890, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 2961): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2848, peerAddress: B0:C5:59:3F:75:69
,I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2848, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 2961): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT4505, peerAddress: 58:3F:54:73:64:C0
,I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT4505, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 2961): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4660, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4660, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/jxcore-log( 2961): 2015-11-25T13:46:41.153Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:46:41.155Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:46:41.156Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:46:41.156Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2961): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 2961): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1965, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1965, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2961): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2961): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8472, peerAddress: 7C:F9:0E:34:8A:A0
I/        ( 2961): Cleared service requests
I/        ( 2961): Started peer discovery
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8472, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2961): Found 8 peers.
I/SS      ( 2961): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2961): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2961): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2961): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2961): Peer(5): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2961): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2961): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2961): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2961): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2961): Added service request
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2961): Started service discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2961): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8472, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8472, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 2961): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2890, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2890, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 2961): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2848, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2848, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 2961): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT4505, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT4505, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
E/bt-btif ( 3030): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3030): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3030): Entering PendingCommandState State
,W/BluetoothEventManager( 3063): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3063): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 3030): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 3030): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3030): StableState(): Entering Off State
,W/BluetoothEventManager( 3063): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3063): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,W/bt-btif ( 3030): new conn_srvc id:26, app_id:255
W/bt-btif ( 3030): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3030): bta_dm_pm_ssr:2, lat:1200
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BTListenerThread( 2961): we got incoming connection
,I/BTHandshakeSocketThread( 2961): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2961): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread started
,I/BTListenerThread( 2961): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 2961): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6613","ra":"08:EC:A9:50:75:41"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2961): MESSAGE_WRITE 77 bytes.
I/HS      ( 2961): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT6613
I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2961): Starting the connected thread incoming : true, samsung-SM-A300FU_PT6613
,I/BtToSocketBase( 2961): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2961): Creating BTConnectedThread
,I/BtConnectorHelper( 2961): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2961): --DoOneRunRound started
,I/jxcore-log( 2961): 2015-11-25T13:47:07.281Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2961): 
,I/BtToRequestSocket( 2961): LocalHost address: localhost/127.0.0.1, port: 58707
,I/BtToRequestSocket( 2961): --DoOneRunRound ended
,I/jxcore-log( 2961): 2015-11-25T13:47:07.856Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:07.975Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2961): 
,I/        ( 2961): Cleared service requests
I/        ( 2961): Started peer discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2961): 2015-11-25T13:47:08.096Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:08.338Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:08.397Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:08.412Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:08.474Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2961): Found 8 peers.
I/SS      ( 2961): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2961): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2961): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2961): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2961): Peer(5): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2961): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2961): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2961): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2961): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2961): Added service request
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2961): 2015-11-25T13:47:08.958Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:08.967Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:08.973Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:09.020Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2961): 2015-11-25T13:47:09.092Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:09.197Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:09.234Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:09.260Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:09.294Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:09.322Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:09.329Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:09.337Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:09.375Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:09.505Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:09.520Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 2961): 
,I/        ( 2961): Started service discovery
,I/jxcore-log( 2961): 2015-11-25T13:47:09.572Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:09.846Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 2961): 2015-11-25T13:47:10.080Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:10.089Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:10.110Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:10.244Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:10.255Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:10.298Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2961): 2015-11-25T13:47:10.391Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:10.422Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:10.670Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:10.893Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:10.925Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:10.976Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:10.986Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:11.025Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:11.042Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2961): 
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4168094 rs_disc_pending=0
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3030): invalid rfc slot id: 42
,I/BtToSocketBase( 2961): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2961): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2961): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT6613
I/BtToSocketBase( 2961): Stop ReceivingThread
I/BtToSocketBase( 2961): Stop SendingThread
,I/BtToSocketBase( 2961): Close local in
I/BtToSocketBase( 2961): Close LocalOutputStream
I/BtToSocketBase( 2961): Close localHostSocket
I/BtToSocketBase( 2961): Close bt in
I/BtToSocketBase( 2961): Close bt out
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2961): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2961): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT6613
I/BtToSocketBase( 2961): Close bt in
I/BtToSocketBase( 2961): Close bt out
I/BtToSocketBase( 2961): Close bt socket
,I/BtToSocketBase( 2961): Close bt socket
,I/jxcore-log( 2961): 2015-11-25T13:47:11.531Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2961): 
,W/bt-sdp  ( 3030): SDP - Rcvd conn cnf with error: 0x22  CID 0x45
E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:58, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3030): invalid rfc slot id: 58
,I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2961): 2015-11-25T13:47:14.410Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:47:14.411Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:47:14.411Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2961): 
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4168094 rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3030): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: A3-1
,I/jxcore-log( 2961): 2015-11-25T13:47:19.413Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:47:19.414Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:24.417Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:47:24.418Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:47:24.419Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:47:24.419Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2961): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3030): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:60, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3030): invalid rfc slot id: 60
I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2961): 2015-11-25T13:47:29.589Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:47:29.589Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:47:29.589Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:34.590Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:34.590Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:39.593Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:47:39.595Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:47:39.596Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:47:39.596Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2961): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3030): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:61, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3030): invalid rfc slot id: 61
I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2961): 2015-11-25T13:47:44.767Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:47:44.768Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:44.769Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:44.771Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2961): 
I/jxcore-log( 2961): ---- round done--------
I/jxcore-log( 2961): 
I/jxcore-log( 2961): ---- gotta redo : 34:FC:EF:11:B1:66, try count now: 1
I/jxcore-log( 2961): 
I/jxcore-log( 2961): do fake peer & start
I/jxcore-log( 2961): 
I/jxcore-log( 2961): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:47:44.772Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:47:44.772Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:47:44.772Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: 08:EC:A9:50:75:41, name: A3-1
,I/        ( 2961): Connecting to A3-1, at 08:EC:A9:50:75:41
,I/chromium( 2961): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 34:FC:EF:11:B1:66 done with result: Connection to 34:FC:EF:11:B1:66 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: A3-1
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4168094 rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,W/bt-btif ( 3030): new conn_srvc id:26, app_id:1
W/bt-btif ( 3030): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3030): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2961): Starting to Handshake
,I/BTHandshakeSocketThread( 2961): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2961): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread started
,I/BTConnectToThread( 2961): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 2961): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6613","ra":"08:EC:A9:50:75:41"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2961): HandshakeOk : samsung-SM-A300FU_PT6613
I/HS      ( 2961): Hand Shake finished outgoing for : samsung-SM-A300FU_PT6613
I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2961): Starting the connected thread incoming : false, samsung-SM-A300FU_PT6613
I/BtToSocketBase( 2961): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2961): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2961): mHTTPPort  set to : 35230
I/BtConnectorHelper( 2961): Request socket is using : 35230
I/BtToRequestSocket( 2961): Now accepting connections
,I/BtConnectorHelper( 2961): Calling ConnectionStatusUpdate with port :35230
,I/jxcore-log( 2961): 2015-11-25T13:47:51.258Z SendDataConnector.js: CLIENT connected to 35230, error: null
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:47:51.259Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2961): 
,I/BtToRequestSocket( 2961): incoming data from: /127.0.0.1, port: 35230
I/BtToRequestSocket( 2961): Set local streams
I/BtToRequestSocket( 2961): rin ended ---------------------------;
,I/jxcore-log( 2961): 2015-11-25T13:47:51.277Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2961): 
,D/        ( 3030): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24979
,I/jxcore-log( 2961): 2015-11-25T13:47:51.591Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:51.747Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2961): 
,D/        ( 3030): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14089
,I/jxcore-log( 2961): 2015-11-25T13:47:51.782Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:51.919Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2961): 
,D/        ( 3030): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4189
,I/jxcore-log( 2961): 2015-11-25T13:47:51.962Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:52.075Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:52.169Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:52.218Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2961): 
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2961): 2015-11-25T13:47:52.348Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:52.414Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:47:52.415Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:52.438Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:47:52.439Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2961): 
I/BtConnectorHelper( 2961): Disconnect outgoing peer: 08:EC:A9:50:75:41
I/BtToSocketBase( 2961): Stop ReceivingThread
I/BtToSocketBase( 2961): Stop SendingThread
I/BtToSocketBase( 2961): Close local in
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2961): Close LocalOutputStream
I/BtToSocketBase( 2961): Close localHostSocket
I/BtToSocketBase( 2961): Close bt in
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2961): Close bt out
I/BtToSocketBase( 2961): Close bt socket
I/BtToRequestSocket( 2961): Close server socket
,W/bt-btif ( 3030): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,I/jxcore-log( 2961): 2015-11-25T13:47:52.463Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 2961): 
I/jxcore-log( 2961): ---- round done--------
I/jxcore-log( 2961): 
I/jxcore-log( 2961): do fake peer & start
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): Connect to fake peer: E0:DB:10:1F:C9:5E
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:47:52.472Z SendDataConnector.js: Start called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:52.473Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:47:52.480Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: E0:DB:10:1F:C9:5E, name: Note3-1
,I/        ( 2961): Connecting to Note3-1, at E0:DB:10:1F:C9:5E
I/chromium( 2961): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 08:EC:A9:50:75:41 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4168094 rs_disc_pending=0
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [e0:db:10:1f:c9:5e]: 7, f, 230f
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: Note3-1
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4168094 rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3030): new conn_srvc id:26, app_id:1
W/bt-btif ( 3030): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3030): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2961): Starting to Handshake
I/BTHandshakeSocketThread( 2961): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2961): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread started
,I/BTConnectToThread( 2961): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 2961): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT760","ra":"E0:DB:10:1F:C9:5E"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2961): HandshakeOk : samsung-SM-N9005_PT760
I/HS      ( 2961): Hand Shake finished outgoing for : samsung-SM-N9005_PT760
I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2961): Starting the connected thread incoming : false, samsung-SM-N9005_PT760
I/BtToSocketBase( 2961): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2961): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2961): mHTTPPort  set to : 40574
I/BtConnectorHelper( 2961): Request socket is using : 40574
,I/BtToRequestSocket( 2961): Now accepting connections
,I/BtConnectorHelper( 2961): Calling ConnectionStatusUpdate with port :40574
I/jxcore-log( 2961): 2015-11-25T13:47:55.064Z SendDataConnector.js: CLIENT connected to 40574, error: null
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:47:55.065Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2961): 
,I/BtToRequestSocket( 2961): incoming data from: /127.0.0.1, port: 40574
I/BtToRequestSocket( 2961): Set local streams
I/BtToRequestSocket( 2961): rin ended ---------------------------;
,I/jxcore-log( 2961): 2015-11-25T13:47:55.092Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2961): 
,D/        ( 3030): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:403
,I/jxcore-log( 2961): 2015-11-25T13:47:55.243Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:55.314Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:55.419Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:55.525Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:55.707Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:55.809Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:55.906Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:55.997Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:56.098Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:56.200Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:47:56.201Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:47:56.222Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:47:56.222Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2961): 
,I/BtConnectorHelper( 2961): Disconnect outgoing peer: E0:DB:10:1F:C9:5E
I/BtToSocketBase( 2961): Stop ReceivingThread
I/BtToSocketBase( 2961): Stop SendingThread
I/BtToSocketBase( 2961): Close local in
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2961): Close LocalOutputStream
I/BtToSocketBase( 2961): Close localHostSocket
I/BtToSocketBase( 2961): Close bt in
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2961): Close bt out
I/BtToSocketBase( 2961): Close bt socket
I/BtToRequestSocket( 2961): Close server socket
I/jxcore-log( 2961): 2015-11-25T13:47:56.249Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2961): 
I/jxcore-log( 2961): ---- round done--------
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): do fake peer & start
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:47:56.259Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:47:56.259Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:47:56.259Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: 08:EC:A9:50:76:27, name: Thali Test (Galaxy A3)
,I/        ( 2961): Connecting to Thali Test (Galaxy A3), at 08:EC:A9:50:76:27
,I/chromium( 2961): [INFO:CONSOLE(63)] "logCallback Round of send data to peer E0:DB:10:1F:C9:5E done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3030): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [08:ec:a9:50:76:27]: 0, 0, 0
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:64, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3030): invalid rfc slot id: 64
I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2961): 2015-11-25T13:47:56.927Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:47:56.927Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:47:56.927Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2961): 
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3030): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: A3-1
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa4167974 rs_disc_pending=0
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3030): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: Note3-1
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3030): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/jxcore-log( 2961): 2015-11-25T13:48:01.927Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:48:01.927Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:48:06.931Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:48:06.932Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:48:06.932Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:48:06.933Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: 08:EC:A9:50:76:27, name: Thali Test (Galaxy A3)
,I/        ( 2961): Connecting to Thali Test (Galaxy A3), at 08:EC:A9:50:76:27
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:65, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3030): invalid rfc slot id: 65
I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2961): 2015-11-25T13:48:08.395Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:48:08.395Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:48:08.396Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2961): 
,I/        ( 2961): Cleared service requests
,I/        ( 2961): Started peer discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2961): Found 9 peers.
I/SS      ( 2961): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2961): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2961): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2961): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2961): Peer(5): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2961): Peer(6): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2961): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2961): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2961): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2961): Ignored { when=-9ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2961): Added service request
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2961): Started service discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3030): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/jxcore-log( 2961): 2015-11-25T13:48:13.397Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:48:13.397Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:48:18.400Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:48:18.401Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:48:18.402Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:48:18.402Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: 08:EC:A9:50:76:27, name: Thali Test (Galaxy A3)
,I/        ( 2961): Connecting to Thali Test (Galaxy A3), at 08:EC:A9:50:76:27
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,I/BluetoothClassifier( 1375): Bluetooth Device Name: Thali Test (Galaxy A3)
,E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:66, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3030): invalid rfc slot id: 66
I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2961): 2015-11-25T13:48:19.892Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:48:19.892Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:48:19.892Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3030): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/jxcore-log( 2961): 2015-11-25T13:48:24.893Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:48:24.894Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2961): 
,W/bt-btif ( 3030): invalid rfc slot id: 14
,I/BtToSocketBase( 2961): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2961): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2961): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT9762
I/BtToSocketBase( 2961): Stop ReceivingThread
I/BtToSocketBase( 2961): Stop SendingThread
I/BtToSocketBase( 2961): Close local in
I/BtToSocketBase( 2961): Close LocalOutputStream
I/BtToSocketBase( 2961): Close localHostSocket
I/BtToSocketBase( 2961): Close bt in
I/BtToSocketBase( 2961): Close bt out
I/BtToSocketBase( 2961): Close bt socket
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2961): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,D/BluetoothMapService( 3030): onReceive
,I/jxcore-log( 2961): 2015-11-25T13:48:27.477Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2961): 
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: ALE-L21
,I/jxcore-log( 2961): 2015-11-25T13:48:29.898Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:48:29.898Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:48:29.899Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:48:29.899Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: 08:EC:A9:50:76:27, name: Thali Test (Galaxy A3)
,I/        ( 2961): Connecting to Thali Test (Galaxy A3), at 08:EC:A9:50:76:27
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [08:ec:a9:50:76:27]: 6, 10f, 608
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:67, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3030): invalid rfc slot id: 67
,I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2961): 2015-11-25T13:48:33.105Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:48:33.106Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:48:33.106Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2961): 
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3030): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/jxcore-log( 2961): 2015-11-25T13:48:38.108Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:48:38.109Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:48:43.113Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:48:43.116Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:48:43.117Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:48:43.120Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: 08:EC:A9:50:76:27, name: Thali Test (Galaxy A3)
,I/        ( 2961): Connecting to Thali Test (Galaxy A3), at 08:EC:A9:50:76:27
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:68, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3030): invalid rfc slot id: 68
,I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2961): 2015-11-25T13:48:44.171Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:48:44.171Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:48:44.172Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:48:44.175Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2961): 
I/jxcore-log( 2961): ---- round done--------
I/jxcore-log( 2961): 
I/jxcore-log( 2961): ---- gotta redo : 08:EC:A9:50:76:27, try count now: 1
I/jxcore-log( 2961): 
I/jxcore-log( 2961): do fake peer & start
I/jxcore-log( 2961): 
I/jxcore-log( 2961): Connect to fake peer: 7C:F9:0E:34:8A:A0
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:48:44.175Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:48:44.175Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:48:44.175Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: 7C:F9:0E:34:8A:A0, name: S5-1
,I/        ( 2961): Connecting to S5-1, at 7C:F9:0E:34:8A:A0
I/chromium( 2961): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 08:EC:A9:50:76:27 done with result: Connection to 08:EC:A9:50:76:27 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [7c:f9:0e:34:8a:a0]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: S5-1
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa41675e4 rs_disc_pending=0
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,W/bt-btif ( 3030): new conn_srvc id:26, app_id:1
W/bt-btif ( 3030): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3030): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2961): Starting to Handshake
,I/BTHandshakeSocketThread( 2961): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2961): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread started
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa41675e4 rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 2961): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 2961): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2961): HandshakeOk : samsung-SM-G900F_PT8472
I/HS      ( 2961): Hand Shake finished outgoing for : samsung-SM-G900F_PT8472
I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2961): Starting the connected thread incoming : false, samsung-SM-G900F_PT8472
I/BtToSocketBase( 2961): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2961): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2961): mHTTPPort  set to : 51218
I/BtConnectorHelper( 2961): Request socket is using : 51218
,I/BtToRequestSocket( 2961): Now accepting connections
,I/BtConnectorHelper( 2961): Calling ConnectionStatusUpdate with port :51218
I/jxcore-log( 2961): 2015-11-25T13:48:47.647Z SendDataConnector.js: CLIENT connected to 51218, error: null
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:48:47.648Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2961): 
,I/BtToRequestSocket( 2961): incoming data from: /127.0.0.1, port: 51218
I/BtToRequestSocket( 2961): Set local streams
I/BtToRequestSocket( 2961): rin ended ---------------------------;
,I/jxcore-log( 2961): 2015-11-25T13:48:47.667Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2961): 
,D/        ( 3030): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:403
,I/jxcore-log( 2961): 2015-11-25T13:48:47.977Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:48:48.066Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:48:48.216Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2961): 
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3030): onReceive
,I/jxcore-log( 2961): 2015-11-25T13:48:48.284Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2961): 
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/jxcore-log( 2961): 2015-11-25T13:48:48.363Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:48:48.431Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:48:48.435Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:48:48.491Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:48:48.622Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:48:48.701Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:48:48.701Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:48:48.717Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:48:48.718Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2961): 
I/BtConnectorHelper( 2961): Disconnect outgoing peer: 7C:F9:0E:34:8A:A0
I/BtToSocketBase( 2961): Stop ReceivingThread
I/BtToSocketBase( 2961): Stop SendingThread
I/BtToSocketBase( 2961): Close local in
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2961): Close LocalOutputStream
I/BtToSocketBase( 2961): Close localHostSocket
,I/BtToSocketBase( 2961): Close bt in
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2961): Close bt out
I/BtToSocketBase( 2961): Close bt socket
I/BtToRequestSocket( 2961): Close server socket
,I/jxcore-log( 2961): 2015-11-25T13:48:48.750Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2961): 
I/jxcore-log( 2961): ---- round done--------
I/jxcore-log( 2961): 
I/jxcore-log( 2961): do fake peer & start
I/jxcore-log( 2961): 
I/jxcore-log( 2961): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:48:48.751Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:48:48.751Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:48:48.751Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: 44:80:EB:7B:5A:05, name: XT1072
,I/        ( 2961): Connecting to XT1072, at 44:80:EB:7B:5A:05
I/chromium( 2961): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 7C:F9:0E:34:8A:A0 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3030): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [44:80:eb:7b:5a:05]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: XT1072
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,W/bt-btif ( 3030): new conn_srvc id:26, app_id:1
W/bt-btif ( 3030): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3030): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2961): Starting to Handshake
I/BTHandshakeSocketThread( 2961): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2961): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread started
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3030): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: S5-1
,I/BTConnectToThread( 2961): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 2961): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2961): HandshakeOk : motorola-XT1072_PT9583
I/HS      ( 2961): Hand Shake finished outgoing for : motorola-XT1072_PT9583
I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2961): Starting the connected thread incoming : false, motorola-XT1072_PT9583
I/BtToSocketBase( 2961): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2961): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2961): mHTTPPort  set to : 33874
I/BtConnectorHelper( 2961): Request socket is using : 33874
I/BtToRequestSocket( 2961): Now accepting connections
,I/BtConnectorHelper( 2961): Calling ConnectionStatusUpdate with port :33874
I/jxcore-log( 2961): 2015-11-25T13:48:52.662Z SendDataConnector.js: CLIENT connected to 33874, error: null
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:48:52.662Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2961): 
,I/BtToRequestSocket( 2961): incoming data from: /127.0.0.1, port: 33874
I/BtToRequestSocket( 2961): Set local streams
I/BtToRequestSocket( 2961): rin ended ---------------------------;
,I/jxcore-log( 2961): 2015-11-25T13:48:52.681Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2961): 
,D/        ( 3030): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24979
,I/jxcore-log( 2961): 2015-11-25T13:48:52.776Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2961): 
,D/        ( 3030): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:17059
,I/jxcore-log( 2961): 2015-11-25T13:48:52.807Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:48:52.810Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2961): 
,D/        ( 3030): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:7159
,I/jxcore-log( 2961): 2015-11-25T13:48:52.870Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2961): 
,D/        ( 3030): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:5179
,I/jxcore-log( 2961): 2015-11-25T13:48:52.878Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:48:52.919Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:48:52.959Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:48:52.965Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:48:53.023Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:48:53.033Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:48:53.034Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:48:53.053Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:48:53.054Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2961): 
I/BtConnectorHelper( 2961): Disconnect outgoing peer: 44:80:EB:7B:5A:05
I/BtToSocketBase( 2961): Stop ReceivingThread
I/BtToSocketBase( 2961): Stop SendingThread
I/BtToSocketBase( 2961): Close local in
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2961): Close LocalOutputStream
I/BtToSocketBase( 2961): Close localHostSocket
I/BtToSocketBase( 2961): Close bt in
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2961): Close bt out
I/BtToSocketBase( 2961): Close bt socket
I/BtToRequestSocket( 2961): Close server socket
,I/jxcore-log( 2961): 2015-11-25T13:48:53.078Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2961): 
I/jxcore-log( 2961): ---- round done--------
I/jxcore-log( 2961): 
I/jxcore-log( 2961): do fake peer & start
I/jxcore-log( 2961): 
I/jxcore-log( 2961): Connect to fake peer: F8:95:C7:87:3C:51
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:48:53.079Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:48:53.079Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:48:53.079Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,W/bt-btif ( 3030): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,I/        ( 2961): Connecting to G4-1, at F8:95:C7:87:3C:51
,I/chromium( 2961): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 44:80:EB:7B:5A:05 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [f8:95:c7:87:3c:51]: 7, f, 610c
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: G4-1
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3030): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: XT1072
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa41677ac rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3030): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3030): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3030): Entering PendingCommandState State
,W/BluetoothEventManager( 3063): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3063): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/BluetoothBondStateMachine( 3030): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3030): Failed to remove device: F8:95:C7:87:3C:51
,W/BluetoothEventManager( 3063): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 3030): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3030): StableState(): Entering Off State
,E/BluetoothEventManager( 3063): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa41677ac rs_disc_pending=0
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3030): new conn_srvc id:26, app_id:1
W/bt-btif ( 3030): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3030): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2961): Starting to Handshake
,I/BTHandshakeSocketThread( 2961): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2961): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread started
,I/BTConnectToThread( 2961): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 2961): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2961): HandshakeOk : LGE-LG-H815_PT1965
I/HS      ( 2961): Hand Shake finished outgoing for : LGE-LG-H815_PT1965
I/BTHandshakeSocketThread( 2961): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2961): Starting the connected thread incoming : false, LGE-LG-H815_PT1965
,I/BtToSocketBase( 2961): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2961): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2961): mHTTPPort  set to : 54211
I/BtConnectorHelper( 2961): Request socket is using : 54211
I/BtToRequestSocket( 2961): Now accepting connections
,I/BtConnectorHelper( 2961): Calling ConnectionStatusUpdate with port :54211
I/jxcore-log( 2961): 2015-11-25T13:49:04.128Z SendDataConnector.js: CLIENT connected to 54211, error: null
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:49:04.128Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2961): 
,I/BtToRequestSocket( 2961): incoming data from: /127.0.0.1, port: 54211
I/BtToRequestSocket( 2961): Set local streams
I/BtToRequestSocket( 2961): rin ended ---------------------------;
,I/jxcore-log( 2961): 2015-11-25T13:49:04.152Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:49:04.253Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:49:04.292Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:49:04.336Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:49:04.371Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:49:04.378Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:49:04.433Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:49:04.474Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:49:04.489Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:49:04.526Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:49:04.527Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:49:04.542Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:49:04.542Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2961): 
,I/BtConnectorHelper( 2961): Disconnect outgoing peer: F8:95:C7:87:3C:51
I/BtToSocketBase( 2961): Stop ReceivingThread
I/BtToSocketBase( 2961): Stop SendingThread
I/BtToSocketBase( 2961): Close local in
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2961): Close LocalOutputStream
I/BtToSocketBase( 2961): Close localHostSocket
,I/BtToSocketBase( 2961): Close bt in
,I/BtToSocketBase( 2961): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2961): Close bt out
I/BtToSocketBase( 2961): Close bt socket
I/BtToRequestSocket( 2961): Close server socket
,I/jxcore-log( 2961): 2015-11-25T13:49:04.581Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 2961): 
I/jxcore-log( 2961): ---- round done--------
I/jxcore-log( 2961): 
I/jxcore-log( 2961): do fake peer & start
I/jxcore-log( 2961): 
I/jxcore-log( 2961): Connect to fake peer: F8:95:C7:87:85:54
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:49:04.581Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:49:04.582Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:49:04.582Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 2961): Connecting to null, at F8:95:C7:87:85:54
,I/chromium( 2961): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F8:95:C7:87:3C:51 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 3030): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa41677ac rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [f8:95:c7:87:85:54]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa416708c rs_disc_pending=1
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:72, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3030): invalid rfc slot id: 72
,I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2961): 2015-11-25T13:49:05.908Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:49:05.909Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:49:05.909Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2961): 
,E/bt-btm  ( 3030): tBTM_SEC_DEV:0xa416708c rs_disc_pending=0
W/bt-btif ( 3030): bta_dm_check_av:0
,W/bt-btif ( 3030): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3030): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: G4-1
,I/        ( 2961): Cleared service requests
I/        ( 2961): Started peer discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2961): Found 4 peers.
I/SS      ( 2961): Peer(1): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2961): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2961): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2961): Peer(4): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2961): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2961): Added service request
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2961): Started service discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2961): 2015-11-25T13:49:10.915Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:49:10.916Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 2961): 
I/        ( 2961): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT7950","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT7950","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT7950, peerAddress: F8:CF:C5:D9:E5:61
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT7950, WifiDirectName: Android_50a5, WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,I/        ( 2961): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT760","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT760","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT760, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT760, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 2961): timeout now
I/jxcore-log( 2961): 
I/jxcore-log( 2961): dun
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): weAreDoneNow , resultArray.length: 14
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): done, now sending data to server
I/jxcore-log( 2961): 
I/jxcore-log( 2961): DBG, CoordinatorConnector sendData called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): -- RESULT DATA {"name:":"LGE-Nexus 5_PT6456","time":1000138,"result":"TIMEOUT","sendList":[{"name":"E0:DB:10:14:E2:C0","time":34848,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"50:2E:6C:AC:21:50","time":38178,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B4:CE:F6:AB:A4:6A","time":22645,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"80:01:84:8A:B3:68","time":36565,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F4:F1:E1:5C:3B:E2","time":40879,"result":"OK","connections":3,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"58:3F:54:73:64:C0","time":45555,"result":"OK","connections":4,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:9D:93:0B","time":12794,"result":"OK","connections":1,"tryCount
,I/jxcore-log( 2961): sendList : 100% : 45555 ms, 99% : 45555 ms, 95 : 40879 ms, 90% : 40879 ms.
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): Result count 14, range 3729 ms to  45555 ms.
I/jxcore-log( 2961): 
I/jxcore-log( 2961): sendList failed peers count : 6 [30 %]
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): - Peer ID : F8:95:C7:87:85:54, Tried : 2
I/jxcore-log( 2961): 
I/jxcore-log( 2961): - Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
I/jxcore-log( 2961): 
I/jxcore-log( 2961): - Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
I/jxcore-log( 2961): 
I/jxcore-log( 2961): - Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
I/jxcore-log( 2961): 
I/jxcore-log( 2961): - Peer ID : 34:FC:EF:11:B1:66, Tried : 1
I/jxcore-log( 2961): 
I/jxcore-log( 2961): - Peer ID : 08:EC:A9:50:76:27, Tried : 1
I/jxcore-log( 2961): 
I/jxcore-log( 2961): sendList never tried peers count : 0 [0 %]
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:49:15.142Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:49:15.143Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2961): 
,I/chromium( 2961): [INFO:CONSOLE(63)] "logCallback *** TIMEOUT ***", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 2961): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2961): 2015-11-25T13:49:15.920Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:49:15.920Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:49:15.921Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:49:15.921Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 2961): Connecting to null, at F8:95:C7:87:85:54
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:73, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3030): invalid rfc slot id: 73
,I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2961): 2015-11-25T13:49:17.319Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:49:17.320Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:49:17.321Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2961): 
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 2961): Cleared service requests
I/        ( 2961): Started peer discovery
,I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,I/SS      ( 2961): Found 3 peers.
I/SS      ( 2961): Peer(1): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2961): Peer(2): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2961): Peer(3): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2961): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2961): Added service request
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2961): Started service discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2961): 2015-11-25T13:49:22.322Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:49:22.323Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 2961): 
,I/        ( 2961): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8472, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8472, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/jxcore-log( 2961): 2015-11-25T13:49:27.336Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:49:27.336Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:49:27.337Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:49:27.337Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 2961): Connecting to null, at F8:95:C7:87:85:54
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:74, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3030): invalid rfc slot id: 74
,I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2961): 2015-11-25T13:49:28.818Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:49:28.819Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:49:28.820Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 2961): Cleared service requests
,I/        ( 2961): Started peer discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2961): Found 5 peers.
I/SS      ( 2961): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2961): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2961): Peer(3): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2961): Peer(4): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2961): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2961): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2961): Added service request
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2961): Started service discovery
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2961): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT382, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT382, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 2961): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2890, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2890, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/jxcore-log( 2961): 2015-11-25T13:49:33.821Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:49:33.822Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 2961): 
,I/        ( 2961): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4660, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4660, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 2961): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8472, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8472, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/jxcore-log( 2961): 2015-11-25T13:49:38.828Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:49:38.829Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:49:38.829Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:49:38.830Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 2961): Connecting to null, at F8:95:C7:87:85:54
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:75, failed to find channle,                                       status:1, scn:0
,I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,W/bt-btif ( 3030): invalid rfc slot id: 75
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2961): 2015-11-25T13:49:39.292Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:49:39.293Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:49:39.296Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2961): 
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,I/        ( 2961): Cleared service requests
I/        ( 2961): Started peer discovery
,I/jxcore-log( 2961): 2015-11-25T13:49:44.300Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:49:44.300Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2961): Found 7 peers.
I/SS      ( 2961): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2961): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2961): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2961): Peer(4): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2961): Peer(5): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2961): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2961): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2961): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2961): Added service request
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2961): Started service discovery
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 2961): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2848, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2848, WifiDirectName: , WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 2961): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT382, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT382, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 2961): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1965, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1965, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2961): 2015-11-25T13:49:49.305Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:49:49.305Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:49:49.306Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:49:49.306Z SendDataConnector.js: do connect now
I/jxcore-log( 2961): 
,I/        ( 2961): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 2961): Connecting to null, at F8:95:C7:87:85:54
,I/BTConnectToThread( 2961): Starting to connect
W/BluetoothAdapter( 2961): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3030): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3030): info:x10
,D/        ( 3030): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3030): process_service_search_attr_rsp
,E/bt-btif ( 3030): DISCOVERY_COMP_EVT slot id:76, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3030): invalid rfc slot id: 76
,I/BTConnectToThread( 2961): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2961): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2961): 2015-11-25T13:49:51.390Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:49:51.391Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2961): 
I/jxcore-log( 2961): 2015-11-25T13:49:51.391Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:49:51.398Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2961): 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3030): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3030): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2961): Cleared service requests
I/        ( 2961): Started peer discovery
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2961): Found 9 peers.
I/SS      ( 2961): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2961): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2961): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2961): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2961): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2961): Peer(6): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2961): Peer(7): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2961): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2961): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2961): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2961): Added service request
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2961): Started service discovery
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
,I/        ( 2961): Cleared service requests
I/        ( 2961): Started peer discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2961): Found 8 peers.
I/SS      ( 2961): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2961): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2961): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2961): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2961): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2961): Peer(6): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2961): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2961): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2961): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2961): Added service request
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2961): Started service discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2961): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT9583, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT9583, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 2961): Cleared service requests
,I/        ( 2961): Started peer discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2961): Found 9 peers.
I/SS      ( 2961): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2961): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2961): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2961): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2961): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2961): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2961): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2961): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2961): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2961): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2961): Added service request
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2961): Started service discovery
,W/bt-smp  ( 3030): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3030): Plain text(LSB ~ MSB) = c2 97 41 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3030): Encrypted text(LSB ~ MSB) = f4 32 d5 b6 04 0d bd ad 1c e0 26 22 51 92 25 91 
,W/bt-btm  ( 3030): Stopping oneshot timer
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2961): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2890, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2890, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 2961): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4660, peerAddress: 34:FC:EF:9D:93:0B
,I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4660, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 2961): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8472, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8472, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2961): Cleared service requests
I/        ( 2961): Started peer discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2961): Found 7 peers.
I/SS      ( 2961): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2961): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2961): Peer(3): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2961): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2961): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2961): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2961): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2961): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2961): Added service request
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2961): Started service discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2961): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT760","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT760","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT760, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT760, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 2961): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT9583, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT9583, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 2961): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2890, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2890, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 2961): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"}, typeCordovap2p._tcp.local.:
,I/        ( 2961): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4660, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4660, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 2961): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8472, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8472, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 2961): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 2961): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1965, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 2961): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1965, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2961): Cleared service requests
I/        ( 2961): Started peer discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2961): Found 9 peers.
I/SS      ( 2961): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2961): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2961): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2961): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2961): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2961): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2961): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2961): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2961): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2961): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2961): Added service request
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2961): Started service discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 2961): Cleared service requests
I/        ( 2961): Started peer discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3052): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2961): Found 9 peers.,
I/SS      ( 2961): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2961): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2961): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2961): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2961): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2961): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2961): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2961): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2961): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2961): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2961): Added service request
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2961): Started service discovery
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3052): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,I/jxcore-log( 2961): DBG, CoordinatorConnector command called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): stop tests now !
I/jxcore-log( 2961): 
I/jxcore-log( 2961): stop current!
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): testSendData stopped
I/jxcore-log( 2961): 
,I/        ( 2961): Stoping All
,I/        ( 2961): Stopping services
I/        ( 2961): Stopping services
,I/wpa_supplicant( 3052): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3052): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/        ( 2961): Stop Bluetooth
I/        ( 2961): Stop Bluetooth
I/BTListenerThread( 2961): Stopped
,I/jxcore-log( 2961): StopBroadcasting went ok
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): 2015-11-25T13:53:35.592Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 2961): 
I/chromium( 2961): [INFO:CONSOLE(63)] "logCallback stop", source: file:///android_asset/www/js/thali_main.js (63)
I/        ( 2961): Cleared local services
I/        ( 2961): Cleared service requests
I/        ( 2961): Stopped peer discovery
,I/jxcore-log( 2961): DBG, CoordinatorConnector command called
I/jxcore-log( 2961): 
I/jxcore-log( 2961): command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"E0:DB:10:1F:C9:5E\",\"time\":3729,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"F8:CF:C5:D9:E5:61\",\"time\":4083,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"44:80:EB:7B:5A:05\",\"time\":4283,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"7C:F9:0E:34:8A:A0\",\"time\":4527,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"B0:C5:59:3F:75:69\",\"time\":6743,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"08:EC:A9:50:75:41\",\"time\":7643,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAm
I/jxcore-log( 2961): ****TEST TOOK:  ms ****
I/jxcore-log( 2961): 
I/jxcore-log( 2961): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2961): 
I/jxcore-log( 2961): stop tests now !
I/jxcore-log( 2961): 
I/jxcore-log( 2961): end, event received
I/jxcore-log( 2961): 
I/jxcore-log( 2961): CoordinatorConnector close called
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 2961): 
I/jxcore-log( 2961): The Coordinator has disconnected!
I/jxcore-log( 2961): 
I/jxcore-log( 2961): The Coordinator has closed!
I/jxcore-log( 2961): 
I/jxcore-log( 2961): stop tests now !
I/jxcore-log( 2961): 
I/jxcore-log( 2961): turning Radios off
I/jxcore-log( 2961): 
I/jxcore-log( 2961): Toggling radios to false
I/jxcore-log( 2961): 
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  759): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@220e51ce mBinding = false
,D/BluetoothManagerService(  759): Message: 2
,D/WifiService(  759): setWifiEnabled: false pid=2961, uid=10270
E/WifiService(  759): Invoking mWifiStateMachine.setWifiEnabled
,D/BluetoothManagerService(  759): Sending off request.
,D/BluetoothAdapterState( 3030): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3030): Setting state to 13
I/BluetoothAdapterState( 3030): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterProperties( 3030): onBluetoothDisable()
I/BluetoothAdapterState( 3030): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 3030): Scan Mode:20
,D/BluetoothAdapterState( 3030): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,V/BluetoothMapMasInstance( 3030): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3030): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3030): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 3030): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 3030): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 3030): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3030): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3030): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,E/BtOppRfcommListener( 3030): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/btif_config_util( 3030): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3030): bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
,W/bt-l2cap( 3030): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3030): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothManagerService(  759): Message: 60
D/BluetoothManagerService(  759): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  759): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 3030): onReceive
D/BluetoothMapService( 3030): STATE_TURNING_OFF
V/BluetoothMapService( 3030): Handler(): got msg=4
D/BluetoothMapService( 3030): MAP Service closeService in
D/BluetoothMapMasInstance( 3030): MAP Service shutdown
V/BluetoothMapService( 3030): MAP Service closeService out
,I/BtOppRfcommListener( 3030): stopping Accept Thread
,I/BtOppRfcommListener( 3030): BluetoothSocket listen thread finished
,W/ContextImpl( 3063): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/jxcore-log( 2961): Radios toggled
I/jxcore-log( 2961): 
,I/chromium( 2961): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
,E/WifiStateMachine(  759): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  759): do suspend true
,D/DockEventReceiver( 3063): finishStartingService: stopping service
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/BluetoothPbap( 3063): Proxy object disconnected
D/PbapServerProfile( 3063): Bluetooth service disconnected
,V/NativeCrypto( 1392): Read error: ssl=0xafe49200: I/O error during system call, Connection timed out
,D/AuthorizationBluetoothService( 1392): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/bt_userial( 3030): RX termination
W/bt_userial( 3030): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 3030): Leaving userial_read_thread()
,E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
W/bt-btif ( 3030): ag scb idx 1 not allocated
E/bt-btif ( 3030): BTA AG is already disabled, ignoring ...
,W/bt-l2cap( 3030): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3030): L2CAP - PSM: 0x0017 not found for deregistration
,W/bt-l2cap( 3030): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3030): L2CAP - PSM: 0x0017 not found for deregistration
,W/bt-l2cap( 3030): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3030): L2CAP - PSM: 0x0017 not found for deregistration
D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
D/bt_userial( 3030): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 3030): hw_epilog_process
I/bt_userial_vendor( 3030): device fd = 53 close
,E/WifiStateMachine(  759): scanCount==0 - aborting
,I/GKI_LINUX( 3030): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 3030): GKI_exit_task 0 done
I/GKI_LINUX( 3030): GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 3030): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 3030): Received stop request...Stopping profile...
,D/WifiNetworkAgent(  759): NetworkAgent: NetworkAgent channel lost
D/BluetoothAdapterService( 3030): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2616a30b
,D/HeadsetStateMachine( 3030): Exit Disconnected: -1
,E/native  (  759): do suspend true
,D/BluetoothHeadset( 1233): Proxy object disconnected
D/BluetoothHeadset(  759): Proxy object disconnected
D/WifiScanningService(  759): SCAN_AVAILABLE : 1
D/RttService(  759): SCAN_AVAILABLE : 1
D/BluetoothHeadset( 1187): Proxy object disconnected
D/A2dpService( 3030): Received stop request...Stopping profile...
D/WifiScanningService(  759): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  759): DefaultState
,D/RttService(  759): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
V/NativeCrypto( 1392): SSL shutdown failed: ssl=0xafe49200: I/O error during system call, Broken pipe
,D/BluetoothAdapterService( 3030): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2616a30b
,D/BluetoothAdapterState( 3030): Stopping profile services that were post enabled
,D/BluetoothHeadset( 1187): Proxy object disconnected
,D/BluetoothHeadset( 3063): Proxy object disconnected
,D/A2dpStateMachine( 3030): Exit Disconnected: -1
,D/BluetoothA2dp(  759): Proxy object disconnected
,D/HeadsetStateMachine( 3030): Unbinding service...
,D/HeadsetProfile( 3063): Bluetooth service disconnected
,D/BluetoothA2dp( 3063): Proxy object disconnected
,D/A2dpProfile( 3063): Bluetooth service disconnected
D/ConnectivityService(  759): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  759): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524292
,W/BluetoothHeadsetServiceJni( 3030): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3030): Cleaning up Bluetooth Handsfree callback object
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  759): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/HidService( 3030): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3030): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2616a30b
,D/HealthService( 3030): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3030): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2616a30b
D/PanService( 3030): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3030): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2616a30b
,D/ConnectivityManager.CallbackHandler( 1558): CM callback handler got msg 524292
D/BluetoothInputDevice( 3063): Proxy object disconnected
D/HidProfile( 3063): Bluetooth service disconnected
D/BluetoothPan( 3063): BluetoothPAN Proxy object disconnected
D/PanProfile( 3063): Bluetooth service disconnected
D/CSLegacyTypeTracker(  759): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=-6ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=-6ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Disconnected - quitting
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/BtGatt.DebugUtils( 3030): handleDebugAction() action=null
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  759): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1233): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/BtGatt.GattService( 3030): Received stop request...Stopping profile...
D/BtGatt.GattService( 3030): stop()
D/BtGatt.AdvertiseManager( 3030): advertise clients cleared
,D/BluetoothAdapterService( 3030): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2616a30b
,D/BluetoothMapService( 3030): Received stop request...Stopping profile...
D/BluetoothMapService( 3030): stop()
,D/BluetoothMapEmailAppObserver( 3030): deinitObservers()
,D/BluetoothMapEmailAppObserver( 3030): removeReceiver()
,D/BluetoothAdapterService( 3030): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2616a30b
,I/GKI_LINUX( 3030): gki_task task_id=2 [A2DP-MEDIA] terminating
,D/BluetoothMap( 3063): Proxy object disconnected
D/MapProfile( 3063): Bluetooth service disconnected
I/GKI_LINUX( 3030): GKI_exit_task 2 done
,I/GKI_LINUX( 3030): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 3030): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3030): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3030): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3030): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3030): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3030): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3030): Cleaning up Bluetooth PAN callback object
,V/BluetoothMapService( 3030): Handler(): got msg=4
D/BluetoothMapService( 3030): MAP Service closeService in
V/BluetoothMapService( 3030): MAP Service closeService out
D/BluetoothMapService( 3030): cleanup()
D/BluetoothMapService( 3030): MAP Service closeService in
V/BluetoothMapService( 3030): MAP Service closeService out
D/BluetoothAdapterState( 3030): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3030): Setting state to 10
I/BluetoothAdapterState( 3030): Bluetooth adapter state changed: 13-> 10
,D/BluetoothManagerService(  759): Message: 60
D/BluetoothManagerService(  759): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  759): Broadcasting onBluetoothStateChange(false) to 11 receivers.
I/BluetoothAdapterState( 3030): Entering OffState
,D/BluetoothInputDevice( 3063): onBluetoothStateChange: up=false
,D/BluetoothHeadset(  759): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1187): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1233): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 3063): onBluetoothStateChange: up=false
,D/BluetoothPbap( 3063): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 3063): onBluetoothStateChange: up=false
,D/BluetoothMap( 3063): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1187): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  759): onBluetoothStateChange: up=false
,D/BluetoothManagerService(  759): Calling onBluetoothServiceDown callbacks
,D/BluetoothManagerService(  759): Broadcasting onBluetoothServiceDown() to 11 receivers.
,D/BluetoothManagerService(  759): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@220e51ce mBinding = false
,D/BluetoothManagerService(  759): Sending unbind request.
,D/BluetoothManagerService(  759): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter(  898): 555410636: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  898): 555410636: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  898): 555410636: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 3030): gki_task task_id=1 [BTIF] terminating
,D/BluetoothAdapter( 1135): 456088101: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1135): 456088101: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 3030): GKI_exit_task 1 done
I/GKI_LINUX( 3030): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3030): cleanupNative: return from cleanup
,I/art     ( 3030): System.exit called, status: 0
I/AndroidRuntime( 3030): VM exiting with result code 0, cleanup skipped.
,D/AndroidRuntime( 3786): 
D/AndroidRuntime( 3786): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3786): CheckJNI is OFF
,W/ContextImpl( 3063): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver( 3063): finishStartingService: stopping service
,I/wpa_supplicant( 3052): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 3052): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,I/ActivityManager(  759): Process com.android.bluetooth (pid 3030) has died
,D/AndroidRuntime( 3786): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  759): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  759): Killing 2961:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,W/PackageSettings(  759): Skipping PackageSetting{2be6f182 com.example.hello/10277} due to missing metadata
,I/WindowState(  759): WIN DEATH: Window{280f2ef6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  759): Client connection lost with reason: 4
,D/Tethering(  759): InitialState.processMessage what=4
,I/wpa_supplicant( 3052): wlan0: CTRL-EVENT-TERMINATING 
,E/libprocessgroup(  759): failed to kill 1 processes for processgroup 2961
,I/ActivityManager(  759):   Force finishing activity ActivityRecord{23c2a3b3 u0 com.test.thalitest/.MainActivity t214}
,W/ActivityManager(  759): Spurious death for ProcessRecord{3720c601 2961:com.test.thalitest/u0a270}, curProc for 2961: null
,D/Tethering(  759): sendTetherStateChangedBroadcast 0, 0, 0
,I/ActivityManager(  759): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/art     ( 1375): Explicit concurrent mark sweep GC freed 96630(3MB) AllocSpace objects, 23(368KB) LOS objects, 24% free, 18MB/25MB, paused 389us total 27.497ms
,I/art     ( 1288): Explicit concurrent mark sweep GC freed 4010(296KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 643us total 33.685ms
,I/Keyboard.Facilitator( 1060): resetDictionaries() : en_US
,W/GeofencerStateMachine( 1135): Ignoring removeGeofence because network location is disabled.
I/InputReader(  759): Reconfiguring input devices.  changes=0x00000010
,W/Settings( 1803): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1135): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Keyboard.Facilitator.DecoderInitializer( 1060): run()
,I/Decoder ( 1060): createOrResetDecoder
,D/BluetoothAdapter( 3063): 918243573: getState() :  mService = null. Returning STATE_OFF
,I/art     (  759): Explicit concurrent mark sweep GC freed 67315(3MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 28MB/42MB, paused 2.251ms total 77.677ms
,I/art     (  759): WaitForGcToComplete blocked for 15.982ms for cause Explicit
,I/ActivityManager(  759): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=3847 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/Adreno-EGL(  942): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/OpenGLRenderer(  942): Initialized EGL, version 1.4
,I/ConfigService( 1392): onCreate
,D/OpenGLRenderer(  942): Enabling debug mode 0
,D/BackupManagerService(  759): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  759): Receieved: android.intent.action.PACKAGE_REMOVED
,W/ResourcesManager( 3847): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/art     (  759): Explicit concurrent mark sweep GC freed 11083(564KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/42MB, paused 1.989ms total 110.157ms
D/TaskPersister(  759): removeObsoleteFile: deleting file=214_task.xml
,W/InputMethodManagerService(  759): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@1a9198bc (uid=10034 pid=942)
,I/CheckinRequestBuilder( 1392): Classify the device as Phone.
,D/AdapterServiceConfig( 3847): Adding HeadsetService
,D/AdapterServiceConfig( 3847): Adding A2dpService
,D/AdapterServiceConfig( 3847): Adding HidService
,D/AdapterServiceConfig( 3847): Adding HealthService
D/AdapterServiceConfig( 3847): Adding PanService
D/AdapterServiceConfig( 3847): Adding GattService
D/AdapterServiceConfig( 3847): Adding BluetoothMapService
,I/ActivityManager(  759): Killing 2853:com.android.musicfx/u0a15 (adj 15): empty #17
,W/InputMethodManagerService(  759): Got RemoteException sending setActive(false) notification to pid 2961 uid 10270
,I/Keyboard.Facilitator( 1060): onFinishInput()
,D/AndroidRuntime( 3786): Shutting down VM
,D/AuthorizationBluetoothService( 1392): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/libprocessgroup(  759): failed to open /acct/uid_10015/pid_2853/cgroup.procs: No such file or directory
,I/Launcher( 1288): Deferring update until onResume
,W/FetchTask( 1392): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/BluetoothAdapter( 3063): 918243573: getState() :  mService = null. Returning STATE_OFF
,D/VoicemailCleanupService( 1411): Cleaning up data for package: com.test.thalitest
,W/ResourcesManager( 1288): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1288): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  759): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=3876 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,I/Launcher( 1288): Deferring update until onResume
,I/CheckinRequestBuilder( 1392): Classify the device as Phone.
,W/FetchTask( 1392): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/CheckinRequestBuilder( 1392): Classify the device as Phone.
,W/Launcher( 1288): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2616a30b new=com.google.android.velvet.VelvetApplication@2616a30b
,I/UpdateIcingCorporaServi( 1375): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/FetchTask( 1392): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/ActivityManager(  759): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3900 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  759): Killing 2880:com.google.android.apps.docs/u0a40 (adj 15): empty #17
,I/CheckinRequestBuilder( 1392): Classify the device as Phone.
,W/libprocessgroup(  759): failed to open /acct/uid_10040/pid_2880/cgroup.procs: No such file or directory
,W/FetchTask( 1392): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,E/SQLiteLog( 1392): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,D/AndroidRuntime( 1392): Shutting down VM
,--------- beginning of crash
E/AndroidRuntime( 1392): FATAL EXCEPTION: main
E/AndroidRuntime( 1392): Process: com.google.process.gapps, PID: 1392
E/AndroidRuntime( 1392): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1392): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1392): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1392): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1392): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1392): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1392): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1392): 	at com.google.android.gms.config.g.onPostExecute(SourceFile:1113)
E/AndroidRuntime( 1392): 	at android.os.AsyncTask.finish(AsyncTask.java:632)
E/AndroidRuntime( 1392): 	at android.os.AsyncTask.access$600(AsyncTask.java:177)
E/AndroidRuntime( 1392): 	at android.os.AsyncTask$InternalHandler.handleMessage(AsyncTask.java:645)
E/AndroidRuntime( 1392): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1392): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1392): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/AndroidRuntime( 1392): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1392): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1392): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/AndroidRuntime( 1392): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,I/Process ( 1392): Sending signal. PID: 1392 SIG: 9
E/DropBoxManagerService(  759): Can't write: system_app_crash
E/DropBoxManagerService(  759): java.io.FileNotFoundException: /data/system/dropbox/drop99.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  759): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  759): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  759): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  759): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  759): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  759): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  759): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  759): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  759): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  759): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  759): 	... 5 more
W/ContextImpl( 3900): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
E/lowmemorykiller(  168): Error writing /proc/1392/oom_score_adj; errno=22
E/JavaBinder(  759): !!! FAILED BINDER TRANSACTION !!!
W/BroadcastQueue(  759): Exception when sending broadcast to ComponentInfo{com.google.android.gms/com.google.android.gms.app.receiver.SystemBroadcastReceiver}
W/BroadcastQueue(  759): android.os.TransactionTooLargeException
W/BroadcastQueue(  759): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue(  759): 	at android.os.BinderProxy.transact(Binder.java:496)
W/BroadcastQueue(  759): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:857)
W/BroadcastQueue(  759): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:245)
W/BroadcastQueue(  759): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:898)
W/BroadcastQueue(  759): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:16008)
W/BroadcastQueue(  759): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:470)
W/BroadcastQueue(  759): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2407)
W/BroadcastQueue(  759): 	at android.os.Binder.execTransact(Binder.java:446)
D/WifiService(  759): Client connection lost with reason: 4

```
