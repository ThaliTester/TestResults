#### Test 513350283842813_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
W/AnalyticsTrackerProxyImpl( 2873): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
,--------- beginning of system
W/ResourcesManager( 2873): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2873): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Finsky  ( 2402): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
I/ActivityManager(  760): Killing 2224:com.google.android.youtube/u0a80 (adj 15): empty #17
V/JNIHelp ( 2873): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
W/System  ( 2873): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2873): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  760): failed to open /acct/uid_10080/pid_2224/cgroup.procs: No such file or directory
V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 2923): 
D/AndroidRuntime( 2923): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2923): CheckJNI is OFF
D/AndroidRuntime( 2923): Calling main entry com.android.commands.am.Am
I/ActivityManager(  760): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  760): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2952 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2923): Shutting down VM
I/Icing   ( 1567): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
V/ActivityManager(  760): Display changed displayId=0
D/Icing   ( 1567): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1567): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/WebViewFactory( 2952): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2952): Time to load native libraries: 3 ms (timestamps 6859-6862)
I/LibraryLoader( 2952): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 2952): Binding Chromium to main looper Looper (main, tid 1) {36c1a320}
,I/LibraryLoader( 2952): Expected native library version number "",actual native library version number ""
,I/chromium( 2952): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 2952): Initializing chromium process, singleProcess=true
,W/art     ( 2952): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 2952): ApplicationContext is null in ApplicationStatus
,W/chromium( 2952): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 2952): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 2952): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2952): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 2952): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d8d3149:true
,D/BluetoothAdapter( 2952): 577152682: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 2952): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2952): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2952): CordovaWebView is running on device made by: LGE
,W/art     ( 2952): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2952): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2952): Render dirty regions requested: true
,D/Atlas   ( 2952): Validating map...
,W/chromium( 2952): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2952): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2952): Enabling debug mode 0
,I/Keyboard.Facilitator( 1070): onFinishInput()
,I/ActivityManager(  760): Displayed com.test.thalitest/.MainActivity: +492ms (total +54s222ms)
,W/IInputConnectionWrapper( 2952): showStatusIcon on inactive InputConnection
,W/BindingManager( 2952): Cannot call determinedVisibility() - never saw a connection for the pid: 2952
,D/JsMessageQueue( 2952): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 2952): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
,D/JX-Cordova( 2952): jxcore cordova android initializing
,I/ActivityManager(  760): Killing 2322:com.google.android.deskclock/u0a38 (adj 15): empty #17
W/libprocessgroup(  760): failed to open /acct/uid_10038/pid_2322/cgroup.procs: No such file or directory
W/jxcore-log( 2952): Initializing JXcore engine
W/jxcore-log( 2952): JXcore engine is ready
W/jxcore-log( 2952): Starting JXcore engine
W/.test.thalitest( 2952): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8448]" dev="sockfs" ino=8448 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 2952): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 2952): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6618]" dev="sockfs" ino=6618 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 2952): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18978]" dev="sockfs" ino=18978 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 2952): Platform android
W/jxcore-log( 2952): 
W/jxcore-log( 2952): Process ARCH arm
W/jxcore-log( 2952): 
,I/jxcore-log( 2952): JXcore Cordova bridge is ready!
I/jxcore-log( 2952): 
W/jxcore-log( 2952): JXcore engine is started
I/Choreographer( 2952): Skipped 107 frames!  The application may be doing too much work on its main thread.
,I/chromium( 2952): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 2952): Toggling radios to true
I/jxcore-log( 2952): 
D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  760): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  760): Message: 1
D/BluetoothManagerService(  760): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  760): New client listening to asynchronous messages
,D/WifiService(  760): setWifiEnabled: true pid=2952, uid=10270
,E/WifiService(  760): Invoking mWifiStateMachine.setWifiEnabled
,D/SoftapController(  179): Softap fwReload - Ok
,D/CommandListener(  179): Setting iface cfg
D/CommandListener(  179): Trying to bring down wlan0
D/CommandListener(  179): Clearing all IP addresses on wlan0
,I/ActivityManager(  760): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3010 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/jxcore-log( 2952): Radios toggled
I/jxcore-log( 2952): 
,D/WifiMonitor(  760): startMonitoring(wlan0) with mConnected = false
,I/ActivityManager(  760): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=3017 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/wpa_supplicant( 3016): Successfully initialized wpa_supplicant
,W/ResourcesManager( 3010): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/wpa_supplicant( 3016): rfkill: Cannot open RFKILL control device
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@31a75544:true
,D/BluetoothAdapter( 3017): 918659872: getState() :  mService = null. Returning STATE_OFF
,D/AdapterServiceConfig( 3010): Adding HeadsetService
D/AdapterServiceConfig( 3010): Adding A2dpService
D/AdapterServiceConfig( 3010): Adding HidService
D/BluetoothManagerService(  760): Message: 30
D/AdapterServiceConfig( 3010): Adding HealthService
D/AdapterServiceConfig( 3010): Adding PanService
D/AdapterServiceConfig( 3010): Adding GattService
D/AdapterServiceConfig( 3010): Adding BluetoothMapService
,D/BluetoothManagerService(  760): Message: 30
,D/LocalBluetoothProfileManager( 3017): Adding local MAP profile
,D/BluetoothMap( 3017): Create BluetoothMap proxy object
,D/BluetoothManagerService(  760): Message: 30
,D/BluetoothManagerService(  760): Message: 30
,D/LocalBluetoothProfileManager( 3017): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 3017): 918659872: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3017): 918659872: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@529fd12:true
D/BluetoothAdapterState( 3010): make
,I/bluedroid( 3010): init
,I/BluetoothAdapterState( 3010): Entering OffState
,I/ActivityManager(  760): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3060 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  760): Killing 2373:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,I/bte_conf( 3010): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3010): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,E/bt_osi_config( 3010): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3010): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3010): get_profile_interface socket
I/bluedroid( 3010): get_profile_interface map_client
,I/GKI_LINUX( 3010): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 3010): Address is:34:FC:EF:11:AE:67
,W/libprocessgroup(  760): failed to open /acct/uid_10069/pid_2373/cgroup.procs: No such file or directory
,D/BluetoothAdapterProperties( 3010): Name is: Nexus 5
,D/BluetoothManagerService(  760): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  760): Stored Bluetooth name: Nexus 5
,D/BluetoothManagerService(  760): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  760): Message: 40
D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 3010): config_hci_snoop_log
,D/BluetoothManagerService(  760): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  760): Broadcasting onBluetoothServiceUp() to 10 receivers.
,D/BluetoothAdapterState( 3010): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3010): Setting state to 11
I/BluetoothAdapterState( 3010): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService(  760): Message: 60
D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  760): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 3010): make
,I/BluetoothBondStateMachine( 3010): StableState(): Entering Off State
,D/BluetoothHeadset(  760): Proxy object connected
,D/HeadsetService( 3010): Received start request. Starting profile...
D/BluetoothHeadset( 1191): Proxy object connected
D/BluetoothHeadset( 1161): Proxy object connected
D/BluetoothHeadset( 1161): Proxy object connected
I/BluetoothAdapterState( 3010): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
I/BluetoothHeadsetServiceJni( 3010): classInitNative: succeeds
D/HeadsetStateMachine( 3010): make
,D/HeadsetStateMachine( 3010): max_hf_connections = 1
I/bluedroid( 3010): get_profile_interface handsfree
,D/BluetoothAdapterService( 3010): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ae664d9
D/BluetoothA2dp(  760): Proxy object connected
,D/A2dpService( 3010): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3010): classInitNative: succeeds
,I/bluedroid( 3010): get_profile_interface avrcp
,D/HeadsetStateMachine( 3010): Enter Disconnected: -2, size: 0
,E/RemoteController( 3010): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3010): classInitNative: succeeds
D/A2dpStateMachine( 3010): make
I/bluedroid( 3010): get_profile_interface a2dp
I/GKI_LINUX( 3010): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothAdapterService( 3010): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ae664d9
,D/A2dpStateMachine( 3010): Enter Disconnected: -2
I/BluetoothHidServiceJni( 3010): classInitNative: succeeds
,D/BluetoothInputDevice( 3017): Proxy object connected
,D/HidService( 3010): Received start request. Starting profile...
I/bluedroid( 3010): get_profile_interface hidhost
D/BluetoothAdapterService( 3010): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ae664d9
D/HidProfile( 3017): Bluetooth service connected
I/BluetoothHealthServiceJni( 3010): classInitNative: succeeds
,D/HealthService( 3010): Received start request. Starting profile...
,I/bluedroid( 3010): get_profile_interface health
,D/BluetoothAdapterService( 3010): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ae664d9
,I/BluetoothPanServiceJni( 3010): classInitNative(L105): succeeds
,D/PanService( 3010): Received start request. Starting profile...
D/BluetoothPan( 3017): BluetoothPAN Proxy object connected
D/BluetoothPanServiceJni( 3010): initializeNative(L110): pan
I/bluedroid( 3010): get_profile_interface pan
D/PanProfile( 3017): Bluetooth service connected
,D/BluetoothAdapterService( 3010): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ae664d9
,I/BtGatt.JNI( 3010): classInitNative(L863): classInitNative: Success!
,D/BtGatt.DebugUtils( 3010): handleDebugAction() action=null
,D/BtGatt.GattService( 3010): Received start request. Starting profile...
,D/BtGatt.GattService( 3010): start()
I/bluedroid( 3010): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 3010): advertise manager created
,D/BluetoothAdapterService( 3010): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ae664d9
,V/BluetoothMapService( 3010): BluetoothMapBinder()
,D/BluetoothMap( 3017): Proxy object connected
,D/BluetoothMapService( 3010): Received start request. Starting profile...
D/BluetoothMapService( 3010): start()
D/MapProfile( 3017): Bluetooth service connected
D/BluetoothMap( 3017): getConnectedDevices()
,D/BluetoothMap( 3017): Bluetooth is Not enabled
,D/BluetoothMapEmailSettingsLoader( 3010): Found 0 applications
D/BluetoothMapEmailAppObserver( 3010): createReceiver()
,D/BluetoothMapEmailAppObserver( 3010): initObservers()
D/BluetoothMapEmailAppObserver( 3010): getEnabledAccountItems()
,D/BluetoothAdapterService( 3010): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ae664d9
D/HeadsetStateMachine( 3010): Proxy object connected
,D/HeadsetStateMachine( 3010): Disconnected process message: 10, size: 0
,D/HeadsetPhoneState( 3010): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/HeadsetStateMachine( 3010): Disconnected process message: 11, size: 0
,V/BluetoothMapService( 3010): Handler(): got msg=1
,D/BluetoothAdapterState( 3010): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 3010): enable
,I/GKI_LINUX( 3010): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3010): btu_task pending for preload complete event
,I/bt_hci_bdroid( 3010): init
,I/bt_vendor( 3010): init
I/bt_vnd_conf( 3010): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,I/bt_vnd_conf( 3010): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3010): userial_init
,I/bt_userial_vendor( 3010): userial vendor open: opening /dev/ttyHS99
,I/bt_userial_vendor( 3010): device fd = 53 open
,D/bt_userial( 3010): Entering userial_read_thread()
,I/art     ( 1343): Explicit concurrent mark sweep GC freed 9966(571KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 19MB/32MB, paused 1.178ms total 42.846ms
,I/bt_hwcfg( 3010): bt vendor lib: set UART baud 4000000
,I/art     (  760): Explicit concurrent mark sweep GC freed 13895(705KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.189ms total 74.231ms
,D/bt_hwcfg( 3010): Chipset BCM4335C0
D/bt_hwcfg( 3010): Target name = [BCM4335C0]
,I/bt_hwcfg( 3010): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,D/AuthorizationBluetoothService( 1343): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager(  760): Killing 1775:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10045/pid_1775/cgroup.procs: No such file or directory
D/Tethering(  760): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 3016): rfkill: Cannot open RFKILL control device
,I/bt_hwcfg( 3010): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 3010): Settlement delay -- 100 ms
I/bt_hwcfg( 3010): Setting fw settlement delay to 100 
,I/wpa_supplicant( 3016): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiConfigStore(  760): Loading config and enabling all networks 
,E/WifiConfigStore(  760): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  760): Setting external_sim to 1
D/WifiStateMachine(  760): Setting OUI to DA-A1-19
I/WifiNative-HAL(  760): startHal
D/wifi    (  760): setting scan oui 0x9ecdcfb8
D/WifiHAL (  760): Sending mac address OUI
E/WifiHAL (  760): failed to set scanning mac OUI; result = -95
,W/Settings( 1800): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/native  (  760): do suspend true
,D/WifiScanningService(  760): SCAN_AVAILABLE : 3
,D/WifiScanningService(  760): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  760): startHal
,D/RttService(  760): SCAN_AVAILABLE : 3
,D/RttService(  760): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiService(  760): New client listening to asynchronous messages
,D/CommandListener(  179): Setting iface cfg
D/CommandListener(  179): Trying to bring up p2p0
,D/WifiMonitor(  760): startMonitoring(p2p0) with mConnected = true
,D/wifi    (  760): getting scan capabilities on interface[1] = 0x9ecdcfb8
D/WifiHAL (  760): Creating message to get scan capablities; iface = 21
,I/wpa_supplicant( 3016): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
D/WifiHAL (  760): In GetCapabilities::handleResponse
D/WifiHAL (  760): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  760): StartedState
,I/bt_hwcfg( 3010): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 3010): Setting local bd addr to 34:FC:EF:11:AE:67
,D/WifiNative-HAL(  760): p2pGetDeviceAddress
,D/WifiNative-HAL(  760): p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,I/bt_hwcfg( 3010): vendor lib fwcfg completed
I/bt-btu  ( 3010): btu_task received preload complete event
,I/        ( 3010): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3010): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3010): BTE_InitTraceLevels -- TRC_RFCOMM
,I/        ( 3010): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3010): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3010): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3010): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3010): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3010): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3010): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3010): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3010): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3010): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3010): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3010): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 3010): BTM_SecRegister:p_cb_info->p_le_callback == 0xa3cd99d5 
,E/bt-btm  ( 3010): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3cd99d5 
,E/bt-btif ( 3010): Calling BTA_HhEnable
E/bt-btif ( 3010): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3010): Address is:34:FC:EF:11:AE:67
,D/BluetoothManagerService(  760): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  760): Stored Bluetooth name: Nexus 5
,D/BluetoothAdapterProperties( 3010): Name is: Nexus 5
W/bt-smp  ( 3010): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3010): Plain text(LSB ~ MSB) = a2 d3 6e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3010): Encrypted text(LSB ~ MSB) = ba 97 00 fc 7d e7 c3 84 70 c8 3e 51 99 08 69 34 
W/bt-btm  ( 3010): Stopping oneshot timer
,D/BluetoothAdapterProperties( 3010): Scan Mode:20
D/BluetoothAdapterProperties( 3010): Discoverable Timeout:120
,D/bte_conf( 3010): Device ID record 1 : primary
D/bte_conf( 3010):   vendorId            = 000f
D/bte_conf( 3010):   vendorIdSource      = 0001
,D/bte_conf( 3010):   product             = 1200
D/bte_conf( 3010):   version             = 1436
D/bte_conf( 3010):   clientExecutableURL = 
D/bte_conf( 3010):   serviceDescription  = 
D/bte_conf( 3010):   documentationURL    = 
D/bte_conf( 3010): bte_load_did_conf no section named DID2.
D/BluetoothAdapterState( 3010): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3010): ScanMode =  20
D/BluetoothAdapterProperties( 3010): State =  11
D/BluetoothAdapterProperties( 3010): Setting state to 12
I/BluetoothAdapterState( 3010): Bluetooth adapter state changed: 11-> 12
I/BluetoothAdapterState( 3010): Entering On State
,D/BluetoothManagerService(  760): Message: 60
D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  760): Broadcasting onBluetoothStateChange(true) to 9 receivers.
D/BluetoothHeadset(  760): onBluetoothStateChange: up=true
,D/BluetoothPan( 3017): onBluetoothStateChange(on) call bindService
,D/BluetoothPanServiceJni( 3010): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,D/BluetoothAdapterProperties( 3010): Scan Mode:21
D/BluetoothAdapterProperties( 3010): Discoverable Timeout:120
,D/BluetoothA2dp(  760): onBluetoothStateChange: up=true
,D/BluetoothInputDevice( 3017): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1161): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1191): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1161): onBluetoothStateChange: up=true
,D/BluetoothMap( 3017): onBluetoothStateChange: up=true
,D/BluetoothPbap( 3017): onBluetoothStateChange: up=true
,D/BluetoothManagerService(  760): Bluetooth State Change Intent: 11 -> 12
,E/bt_h4   ( 3010): vendor lib postload completed
,I/Telecom ( 1161): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/BluetoothMapService( 3010): onReceive
D/BluetoothMapService( 3010): STATE_ON
V/BluetoothMapService( 3010): Handler(): got msg=1
,D/BluetoothManagerService(  760): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothMapMasInstance( 3010): Map Service startRfcommSocketListener
,D/BluetoothManagerService(  760): Message: 40
D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothMapMasInstance( 3010): MAS initSocket()
D/BluetoothMapMasInstance( 3010):   masId = 00
D/BluetoothMapMasInstance( 3010):   msgTypes = 0e
D/BluetoothMapMasInstance( 3010):   masName = SMS/MMS
D/BluetoothMapMasInstance( 3010):   SDP string = 000eSMS/MMS
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3010): getBluetoothService() called with no BluetoothManagerCallback
,D/HeadsetStateMachine( 3010): Disconnected process message: 9, size: 0
D/HeadsetStateMachine( 3010): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 3010): mNumber:  mType: 128
D/HeadsetStateMachine( 3010): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 3010): terminateScoUsingVirtualVoiceCall:No present call to terminate
V/BluetoothMapMasInstance( 3010): Succeed to create listening socket 
D/BluetoothMapMasInstance( 3010): Accepting socket connection...
,D/LocalBluetoothProfileManager( 3017): Adding local A2DP profile
D/BluetoothManagerService(  760): Message: 30
D/LocalBluetoothProfileManager( 3017): Adding local HEADSET profile
D/BluetoothManagerService(  760): Message: 30
,W/ContextImpl( 3017): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3010): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothA2dp( 3017): Proxy object connected
D/A2dpProfile( 3017): Bluetooth service connected
D/BluetoothHeadset( 3017): Proxy object connected
D/HeadsetProfile( 3017): Bluetooth service connected
,D/DockEventReceiver( 3017): finishStartingService: stopping service
,D/BluetoothPbap( 3017): Proxy object connected
D/PbapServerProfile( 3017): Bluetooth service connected
,D/AuthorizationBluetoothService( 1343): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3010): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 3010): Accept thread started.
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 2952): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): my name is : LGE-Nexus 5_PT3721
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): attempting to connect to test coordinator
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): check test folder
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): found test : ./testFindPeers.js
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): found test : ./testReConnect.js
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): found test : ./testSendData.js
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): Test app app.js loaded
I/jxcore-log( 2952): 
,I/chromium( 2952): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/Choreographer( 2952): Skipped 130 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  760): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiStateMachine(  760): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  760): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=1
,E/WifiConfigStore(  760): will read network variables netId=1
,E/WifiStateMachine(  760): CMD_AUTO_CONNECT did save config ->  nid=1
,E/WifiConfigStore(  760): will read network variables netId=1
,I/wpa_supplicant( 3016): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,E/WifiConfigStore(  760): setLastSelectedConfiguration -1
,E/wpa_supplicant( 3016): PNO: In assoc process
,I/wpa_supplicant( 3016): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3016): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3016): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,D/ConnectivityService(  760): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  760): Start Dhcp Watchdog 1
,E/native  (  760): do suspend false
,E/WifiStateMachine(  760): scanCount==0 - aborting
,I/dhcpcd  ( 3177): version 5.5.6 starting
,E/dhcpcd  ( 3177): get_duid: Read-only file system
,I/dhcpcd  ( 3177): wlan0: rebinding lease of 192.168.1.114
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Search.LoginHelper( 1328): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkUtils( 1328): OkHttp exception
,W/EventLoggerService( 1328): Unable to send logs Error code: 262146
,W/Search.LoginHelper( 1328): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,I/dhcpcd  ( 3177): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3177): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  760): do suspend true
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  760): Adding iface wlan0 to network 100
,E/WifiStateMachine(  760): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  760): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  760): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  760): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  760): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  760): Setting Dns servers for network 100 to [/192.168.1.1]
,D/Nat464Xlat(  760): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  760): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  760): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  760): rematching NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  760):    accepting network in place of null
,D/ConnectivityService(  760): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
,D/CSLegacyTypeTracker(  760): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  760): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  760): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  906): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 25 Nov 2015 09:19:39 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1448443180481], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1448443180467]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Validated
D/ConnectivityService(  760): Validated NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  760): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  760): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  760): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  906): CM callback handler got msg 524290
D/TelephonyNetworkFactory( 1191): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 2952): 
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  760): MasterInitialState.processMessage what=3
,D/AlarmManagerService(  760): Setting time of day to sec=1448443182
,W/AlarmManagerService(  760): Unable to set rtc to 1448443182: Invalid argument
,I/NetworkMonitor( 2509): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2509): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/iu.SyncManager( 1567): SYNC; picasa accounts
,D/NetworkLogImpl( 1567): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1567): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1567): num queued entries: 0
,I/iu.UploadsManager( 1567): num updated entries: 0
,I/iu.SyncManager( 1567): NEXT; no task
,D/ChimeraCfgMgr( 1567): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1567): Module APK com.google.android.play.games already loaded
,E/GpsLocationProvider(  760): No APN found to select.
,D/GpsLocationProvider(  760): NTP server returned: 1448443179789 (Wed Nov 25 10:19:39 GMT+01:00 2015) reference: 83931 certainty: 8 system time offset: -3155
E/LocSvc_eng(  760): E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,D/ChimeraCfgMgr( 1567): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1567): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinService( 1567): Checkin interval check for package: unspecified last checkin: 1448344821726 min interval config: 0 actual interval: 98361259
,I/SystemUpdateService( 1567): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,V/AccountUtils( 1567): 0 accounts found with uca feature
,E/Auth.Api.Credentials( 1567): [CredentialSyncAdapter] Unknown sync event.
,I/GamesSyncAdapter( 1567): Starting sync for 3a3529a
,D/SystemUpdateService( 1567): onCreate
,D/SystemUpdateService( 1567): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1567): active receiver: enabled
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SystemUpdateService( 1567): showing system update notification
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GamesSyncAdapter( 1567): User is not G+ enabled. Aborting sync
,I/GamesSyncAdapter( 1567): Sync duration for 3a3529a: 26
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1567): retry (wakeup: false) in 3599984 ms
,I/CheckinService( 1567): Checking schedule, now: 1448443183039 next: 1448386988696
I/CheckinService( 1567): active receiver: enabled
,I/CheckinService( 1567): Preparing to send checkin request
I/EventLogService( 1567): Accumulating logs since 1448443018376
,I/ActivityManager(  760): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3309 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SystemUpdateService( 1567): onDestroy
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel   ( 1800): connection state changed from UNKNOWN to CONNECTED
,D/ChimeraCfgMgr( 1567): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1567): Module APK com.google.android.play.games already loaded
,I/GCM     ( 1343): GCM config loaded
,D/ConnectivityService(  760): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  760): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  760): apparently satisfied.  currentScore=60
,D/ConnectivityManager.CallbackHandler( 1567): CM callback handler got msg 524290
,I/ActivityManager(  760): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=3340 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 1567): Checkin reason type: 12 attempt count: 1
,I/art     (  194): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 186us total 8.483ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 228us total 7.338ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 172us total 7.293ms
,D/ChimeraCfgMgr( 1567): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1567): Module APK com.google.android.play.games already loaded
,D/WifiService(  760): New client listening to asynchronous messages
,I/GAv4    ( 3309): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3309):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3309):   adb logcat -s GAv4
,E/ActivityThread( 1567): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  760): Explicit concurrent mark sweep GC freed 50485(2MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 27MB/41MB, paused 809us total 54.214ms
,W/GAv4    ( 3309): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAv4    ( 3309): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/ResourcesManager( 3340): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3340): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 1343): Explicit concurrent mark sweep GC freed 23661(1264KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 19MB/33MB, paused 4.372ms total 73.975ms
,W/GAv4    ( 3309): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/JNIHelp ( 3340): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/System  ( 3340): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 3340): Installed default security provider GmsCore_OpenSSL
,E/YouTube MDX( 3340): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/dex2oat ( 3403): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-550632780.jar --oat-fd=24 --oat-location=/data/data/com.google.android.youtube/cache/ads-550632780.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/WebViewFactory( 3309): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,W/DriveInitializer( 1567): Awaiting to be initialized
,W/DriveInitializer( 1567): Background init thread started
,I/LibraryLoader( 3309): Time to load native libraries: 1 ms (timestamps 7885-7886)
I/LibraryLoader( 3309): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3309): Binding Chromium to main looper Looper (main, tid 1) {b34ce12}
,I/LibraryLoader( 3309): Expected native library version number "",actual native library version number ""
I/chromium( 3309): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3309): Initializing chromium process, singleProcess=true
,W/art     ( 3309): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3309): ApplicationContext is null in ApplicationStatus
,I/dex2oat ( 3403): dex2oat took 72.784ms (threads: 4)
,W/chromium( 3309): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3309): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3309): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3309): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3309): Requires BLUETOOTH permission
,I/NSApplication( 3309): Starting up...
,W/InstanceID/Rpc( 3340): Found 10008
,I/ActivityManager(  760): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3480 uid=10076 gids={50076, 9997} abi=armeabi-v7a
,I/art     ( 1567): Explicit concurrent mark sweep GC freed 19972(1461KB) AllocSpace objects, 21(336KB) LOS objects, 24% free, 22MB/29MB, paused 602us total 65.311ms
,D/TimeService( 3480): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1448443184038
D/        ( 3480): TimeServiceNative: User Time to be set is 1448443184038
D/QC-time-services( 3480): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3480): Lib:time_genoff_operation: pargs->operation = 0
,D/QC-time-services( 3480): Lib:time_genoff_operation: pargs->ts_val = 1448443184038
D/QC-time-services( 3480): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  197): Daemon: Connection accepted:time_genoff
D/QC-time-services(  197): Daemon:Received base = 2, unit = 1, operation = 0,value = 1448443184038
D/QC-time-services(  197): Daemon:genoff_opr: Base = 2, val = 1448443184038, operation = 0
D/QC-time-services(  197): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS2/29/70 15:10:34
D/QC-time-services(  197): Daemon:Value read from RTC seconds = 7571434000
D/QC-time-services(  197): Daemon:new time 1448443184038 
D/QC-time-services(  197): Daemon: delta 1440871750038 genoff 1440871750038 
D/QC-time-services(  197): Daemon:genoff_persistent_update: Writing genoff = 1440871750038 to memory
D/QC-time-services(  197): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  197): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  197): Updating the TOD offset
D/QC-time-services(  197): Daemon:genoff_persistent_update: Writing genoff = 1440871750038 to memory
D/QC-time-services(  197): Daemon:Opening File: /data/system/time/ats_1
D/QC-time-services(  197): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  197): Daemon:Update to modem bit set
D/QC-time-services(  197): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  197): Daemon: Base = 2, Value being sent to MODEM = 1132478384038
,E/QC-time-services( 3480): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,I/ActivityManager(  760): Killing 2479:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,D/QC-time-services(  197): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,D/QC-time-services(  197): Daemon: Time-services: Waiting to acceptconnection
,W/DriveInitializer( 1567): Background init thread ended
,W/libprocessgroup(  760): failed to open /acct/uid_10003/pid_2479/cgroup.procs: No such file or directory
,I/CheckinService( 1567): Checkin interval check for package: unspecified last checkin: 1448344821726 min interval config: 0 actual interval: 98362380
,I/ActivityManager(  760): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=3519 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/VacuumService( 1343): Vacuum at: now=1448443184313 tag=VacuumService
,I/GAv4    ( 3519): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3519):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3519):   adb logcat -s GAv4
,W/GAv4    ( 3519): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  760): Killing 2344:com.google.android.gm/u0a70 (adj 15): empty #17
,W/GAv4    ( 3519): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3519): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  760): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3542 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
W/libprocessgroup(  760): failed to open /acct/uid_10070/pid_2344/cgroup.procs: No such file or directory
,I/ActivityManager(  760): Killing 1938:com.android.providers.calendar/u0a2 (adj 15): empty #17
,W/art     ( 2604): Attempt to remove local handle scope entry from IRT, ignoring
,W/ResourcesManager( 3542): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3542): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3542): VM with version 2.1.0 has multidex support
I/MultiDex( 3542): install
,I/MultiDex( 3542): VM has multidex support, MultiDex support library is disabled.
,W/libprocessgroup(  760): failed to open /acct/uid_10002/pid_1938/cgroup.procs: No such file or directory
,V/JNIHelp ( 3542): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 3542): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3542): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@7158862: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3542): Installed default security provider GmsCore_OpenSSL
,I/art     ( 3542): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
I/art     ( 3542): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,D/NativeLibraryUtils( 3542): Install completed successfully. count=13 extracted=0
,I/ActivityManager(  760): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3575 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UdcCache:FPQuery( 1567): Bootstrapping UDC settings cache for all accounts
,D/GetConfigurationSnapshotOperation( 1343): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/ActivityManager(  760): Killing 2760:com.google.android.gms:car/u0a8 (adj 15): empty #17
D/WVCdm   (  183): Instantiating CDM.
,I/WVCdm   (  183): CdmEngine::OpenSession
,I/WVCdm   (  183): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  183): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  183): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  183): Service_Initialize: starts!
D/QSEECOMAPI: (  183): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  183): App is not loaded in QSEE
,D/QSEECOMAPI: (  183): Loaded image: APP id = 3
,I/art     (  760): Explicit concurrent mark sweep GC freed 22384(956KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 1.331ms total 82.749ms
D/DrmWidevineDash(  183): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  183): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5911000
E/DrmWidevineDash(  183): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5911000
,D/DrmWidevineDash(  183): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  183): OEMCrypto_APIVersion: starts!
,W/libprocessgroup(  760): failed to open /acct/uid_10008/pid_2760/cgroup.procs: No such file or directory
,D/DrmWidevineDash(  183): hlos api version =  9
,D/DrmWidevineDash(  183): tz api version =  9
D/DrmWidevineDash(  183): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  183): OEMCrypto_IsKeyboxValid: starts!
,W/ResourcesManager( 3575): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/DrmWidevineDash(  183): OEMCrypto_IsKeyboxValid: ends! returns 0,
D/WVCdm   (  183): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  183): OEMCrypto_OpenSession: starts! SID=0xb4bff940
,D/DrmWidevineDash(  183): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  183): OEMCrypto_OpenSession: ends! returns 0
,D/DrmWidevineDash(  183): OEMCrypto_GetRandom: starts! randomData=0xb4a30070, dataLength=8
,D/DrmWidevineDash(  183): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  183): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb4ade000, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  183): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  183): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  183): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  183): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  183): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  183): OEMCrypto_GetDeviceID: starts! deviceID=0xb611d340, idLength=0xb49ff710
,D/DrmWidevineDash(  183): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  183): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  183): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  183): OEMCrypto_SupportsUsageTable: wv_app_version = 21
D/DrmWidevineDash(  183): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  183): OEMCrypto_GetHDCPCapability: starts!
,I/GoogleURLConnFactory( 3542): Using platform SSLCertificateSocketFactory
,D/DrmWidevineDash(  183): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  183): OEMCrypto_APIVersion: starts!
,I/CalendarProvider2( 3575): Created com.android.providers.calendar.CalendarAlarmManager@39bb6223(com.android.providers.calendar.CalendarProvider2@36c1a320)
,D/DrmWidevineDash(  183): hlos api version =  9
D/DrmWidevineDash(  183): tz api version =  9
D/DrmWidevineDash(  183): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  183): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  183): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  183): PrepareKeyRequest: nonce=226966508
D/DrmWidevineDash(  183): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb1901600
,D/DrmWidevineDash(  183): message_length=1596, signature=0xb489d3c0, signature_length=3030382324
I/PhenotypeFlagCommitter( 1343): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,D/WearableService( 1276): callingUid 10008, callindPid: 1276
,I/GoogleURLConnFactory( 1343): Using platform SSLCertificateSocketFactory
,E/MDM     ( 1276): [139] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1567): Restart initialization of location
,D/DrmWidevineDash(  183): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  183): CdmEngine::CloseSession
D/DrmWidevineDash(  183): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  183): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  183): L3 Terminate.
D/DrmWidevineDash(  183): OEMCrypto_Terminate: starts!
,I/art     ( 1343): Explicit concurrent mark sweep GC freed 35321(2MB) AllocSpace objects, 13(208KB) LOS objects, 39% free, 20MB/33MB, paused 2.325ms total 33.612ms
,D/DrmWidevineDash(  183): Service_Uninitialize: starts!
D/QSEECOMAPI: (  183): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  183): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  183): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  183): OEMCrypto_Terminate: ends! returns 0
,D/GCM     ( 1343): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/GetCommittedConfigurationOperation( 1343): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/AuthorizationBluetoothService( 1343): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 1567): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/GCoreFlp( 1276): No location to return for getLastLocation()
,W/FusedLocationProvider( 1343): location=null
,D/GetCommittedConfigurationOperation( 1343): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/WVCdm   (  183): CdmEngine::OpenSession
I/WVCdm   (  183): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  183): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  183): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  183): Service_Initialize: starts!
D/QSEECOMAPI: (  183): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  183): App is not loaded in QSEE
,D/QSEECOMAPI: (  183): Loaded image: APP id = 3
,D/DrmWidevineDash(  183): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  183): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5911000
E/DrmWidevineDash(  183): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5911000
,D/DrmWidevineDash(  183): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  183): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  183): hlos api version =  9
D/DrmWidevineDash(  183): tz api version =  9
D/DrmWidevineDash(  183): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  183): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  183): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  183): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  183): OEMCrypto_OpenSession: starts! SID=0xbe911500
,D/DrmWidevineDash(  183): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  183): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  183): OEMCrypto_GetRandom: starts! randomData=0xb6172348, dataLength=8
,D/DrmWidevineDash(  183): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  183): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb61aac00, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  183): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  183): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  183): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  183): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  183): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  183): OEMCrypto_GetDeviceID: starts! deviceID=0xb611d380, idLength=0xb49ff710
,D/DrmWidevineDash(  183): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  183): OEMCrypto_SupportsUsageTable: starts!
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
D/WVCdm   (  183): PrepareKeyRequest: nonce=2766177783
D/DrmWidevineDash(  183): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb1901600
,D/DrmWidevineDash(  183): message_length=1632, signature=0xb489d3c0, signature_length=3030382324
,D/DrmWidevineDash(  183): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  183): CdmEngine::CloseSession
,D/DrmWidevineDash(  183): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  183): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  183): L3 Terminate.
D/DrmWidevineDash(  183): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  183): Service_Uninitialize: starts!
D/QSEECOMAPI: (  183): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  183): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  183): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  183): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 3624): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=41 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 3624): dex2oat took 33.529ms (threads: 4)
,D/GetCommittedConfigurationOperation( 1343): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/Adreno-EGL( 3542): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/Adreno-EGL( 3542): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/CalendarProvider2( 3575): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 3575): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/Adreno-EGL( 3542): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/CheckinRequestBuilder( 1567): Classify the device as Phone.
,D/GetCommittedConfigurationOperation( 1343): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/CheckinTask( 1567): Sending checkin request (9424 bytes)
,D/GetCommittedConfigurationOperation( 1343): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/Uploader( 1343):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1343): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1343): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/CheckinRequestBuilder( 1567): Checkin reason type: 12 attempt count: 1
E/ActivityThread( 1567): Failed to find provider info for com.google.android.wearable.settings
,D/GetCommittedConfigurationOperation( 1343): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/CheckinRequestBuilder( 1567): Classify the device as Phone.
,I/CheckinTask( 1567): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1567): Checking schedule, now: 1448443186645 next: 1448485353642
I/CheckinService( 1567): active receiver: disabled
,D/CheckinService( 1567): Recording last checkin time for package unspecified as 1448443186671
,D/ChimeraCfgMgr( 1567): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1567): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/GCM     ( 1343): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GetCommittedConfigurationOperation( 1343): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1343): no corresponding serverToken: com.google.android.gms.playlog.uploader
,E/SQLiteLog( 3575): (284) automatic index on view_events(_id)
,D/Finsky  ( 2402): [230] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2402): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/ActivityManager(  760): Killing 1306:android.process.acore/u0a4 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10004/pid_1306/cgroup.procs: No such file or directory
,I/ActivityManager(  760): Killing 1461:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10013/pid_1461/cgroup.procs: No such file or directory
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,W/SQLiteConnectionPool( 1567): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/InputReader(  760): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  760): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=3665 uid=10004 gids={50004, 9997} abi=armeabi-v7a
,D/BackupManagerService(  760): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  760): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  760): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  760): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  760): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@e3e454
,V/GmsNetworkLocationProvi( 1276): DISABLE
,I/GCoreNlp( 1276): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1253): Deferring update until onResume
,W/ResourcesManager( 1253): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1328): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1253): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1ae664d9 new=com.google.android.velvet.VelvetApplication@1ae664d9
,D/PackageBroadcastService( 1567): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1567): Null package name or gms related package.  Ignoreing.
,W/ResourcesManager( 1253): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Icing   ( 1567): updateResources: need to parse f{com.google.android.gms}
,I/Launcher( 1253): Deferring update until onResume
,I/ContactLocale( 3665): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/art     (  760): Explicit concurrent mark sweep GC freed 28132(1284KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 864us total 53.861ms
,I/UpdateIcingCorporaServi( 1328): UpdateCorporaTask done [took 272 ms] updated apps [took 272 ms] 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/ActivityManager(  760): Killing 2838:com.android.musicfx/u0a15 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10015/pid_2838/cgroup.procs: No such file or directory
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/Keyboard.Facilitator.LanguageModelFlusher( 1070): run()
I/Keyboard.Facilitator( 1070): flushDynamicLanguageModels()
,I/ConfigService( 1343): onCreate
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/ConfigService( 1343): onDestroy
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/ClearcutLoggerApiImpl( 1276): disconnect managed GoogleApiClient
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,E/DataBuffer( 1343): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@21b947e7)
,E/DataBuffer( 1343): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@13762f94)
E/DataBuffer( 1343): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2c498a3d)
,E/DataBuffer( 1343): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2b9ca232)
E/DataBuffer( 1343): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2fc87b83)
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  760): Killing 2873:com.google.android.apps.docs/u0a40 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10040/pid_2873/cgroup.procs: No such file or directory
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/UdcCache:FPQuery( 1567): Bootstrapping UDC settings cache for all accounts
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector connect called
I/jxcore-log( 2952): 
I/jxcore-log( 2952): Coordinator is now connected to the server!
I/jxcore-log( 2952): 
,I/chromium( 2952): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2952): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector command called
I/jxcore-log( 2952): 
I/jxcore-log( 2952): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":19,"addressList":[{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"50:2E:6C:AC:21:50","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"00:F4:6F:30:E0:6C","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"F4:F1:E1:5C:3B:E2","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"34:FC:EF:9D:93:0B","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"B4:CE:F6:AB:A4:6A","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"
,I/jxcore-log( 2952): Start now : testSendData.js
I/jxcore-log( 2952): 
I/jxcore-log( 2952): stop tests now !
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 19
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): check server
I/jxcore-log( 2952): 
I/jxcore-log( 2952): serverPort is 52776
I/jxcore-log( 2952): 
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 2952): Stoping All
I/        ( 2952): Stopping services
I/        ( 2952): Stop Bluetooth
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 2952): Start-My BT: 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 2952):  mInstanceString : {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT3721","ra":"34:FC:EF:11:AE:67"}
,I/        ( 2952): All stuff available and enabled
I/        ( 2952): Stoping All
I/        ( 2952): Stopping services
I/        ( 2952): Stop Bluetooth
I/        ( 2952): Starting All
I/        ( 2952): Stopping services
I/        ( 2952): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT3721","ra":"34:FC:EF:11:AE:67"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@1aff4abb
I/        ( 2952): Stopping services
I/        ( 2952): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT3721","ra":"34:FC:EF:11:AE:67"}
I/        ( 2952): Add local service :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT3721","ra":"34:FC:EF:11:AE:67"}, length : 77
,I/        ( 2952): peerDiscoveryTimer timeout value:6702
,I/        ( 2952): Stop Bluetooth
I/        ( 2952): StartBluetooth listener
I/        ( 2952): StartBluetooth listener
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 2952): StartBroadcasting started ok
I/jxcore-log( 2952): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2952): do fake peer & start
I/jxcore-log( 2952): 
I/jxcore-log( 2952): Connect to fake peer: B4:CE:F6:AB:A4:6A
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:26:49.733Z SendDataConnector.js: Start called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:26:49.734Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:26:49.734Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/        ( 2952): Connecting to null, at B4:CE:F6:AB:A4:6A
I/jxcore-log( 2952): 2015-11-25T09:26:49.739Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
I/jxcore-log( 2952): 
,I/chromium( 2952): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/WB      ( 2952): We already were running, thus doing nothing
I/        ( 2952): Added local service
I/        ( 2952): Cleared service requests
I/        ( 2952): Stopped peer discovery
I/        ( 2952): Started peer discovery
I/        ( 2952): Discovery state changed to Started.
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BTListenerThread( 2952): starting to listen
,I/BTListenerThread( 2952): waiting to accept incoming Connection
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:5, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 5
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2952): 2015-11-25T09:26:50.189Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:26:50.189Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:26:50.191Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 2952): Found 1 peers.
I/SS      ( 2952): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pManager( 2952): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2952): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2952): Started service discovery
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2952): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8656","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8656","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT8656, peerAddress: F8:CF:C5:D9:E5:61
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT8656, WifiDirectName: Android_50a5, WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2952): 2015-11-25T09:26:55.193Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:26:55.195Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2952): 
,I/        ( 2952): Cleared service requests
I/        ( 2952): Started peer discovery
,I/jxcore-log( 2952): 2015-11-25T09:27:00.202Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:27:00.202Z SendDataConnector.js: Connect (retry count 1) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:27:00.204Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:27:00.204Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/        ( 2952): Connecting to null, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2952): Found 3 peers.
I/SS      ( 2952): Peer(1): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2952): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2952): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 2952): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2952): Added service request
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=0
,W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:6, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 6
I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2952): 2015-11-25T09:27:05.378Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:27:05.378Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:27:05.378Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 3010): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3010): Entering PendingCommandState State
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3010): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/BluetoothBondStateMachine( 3010): StableState(): Entering Off State
,I/        ( 2952): Started service discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2952): we got incoming connection
I/BTHandshakeSocketThread( 2952): Creating BTHandshakeSocketThread
I/BTListenerThread( 2952): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread started
,I/BTListenerThread( 2952): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 2952): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6069","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2952): MESSAGE_WRITE 77 bytes.
I/HS      ( 2952): Incoming connection Hand Shake finished for : LGE-LG-D722_PT6069
,I/BtConnectorHelper( 2952): Starting the connected thread incoming : true, LGE-LG-D722_PT6069
,I/BtToSocketBase( 2952): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2952): Creating BTConnectedThread
I/BtConnectorHelper( 2952): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2952): --DoOneRunRound started
,I/jxcore-log( 2952): 2015-11-25T09:27:06.204Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2952): 
,I/BtToRequestSocket( 2952): LocalHost address: localhost/127.0.0.1, port: 52776
,I/BtToRequestSocket( 2952): --DoOneRunRound ended
,I/jxcore-log( 2952): 2015-11-25T09:27:06.640Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:06.667Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:06.674Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:06.724Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:06.780Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:06.793Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:06.812Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:06.872Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:06.937Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 2952): 
I/        ( 2952): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4529"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4529"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4529, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4529, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/jxcore-log( 2952): 2015-11-25T09:27:06.976Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:07.074Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:07.106Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:07.132Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:07.168Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:07.335Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:07.360Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:07.388Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:07.412Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:07.449Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:07.456Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:07.473Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:07.485Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:07.499Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:07.538Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:07.585Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:07.594Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:07.643Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:07.679Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:07.700Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:07.712Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:07.759Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:07.801Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:07.845Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:07.937Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:07.943Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:07.961Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:08.000Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:08.051Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:08.080Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:08.112Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:08.138Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:08.170Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:08.200Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:08.222Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:08.232Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:08.268Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:08.276Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2952): 
,W/bt-btif ( 3010): invalid rfc slot id: 4
,I/BtToSocketBase( 2952): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2952): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2952): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT6069
I/BtToSocketBase( 2952): Stop ReceivingThread
I/BtToSocketBase( 2952): Stop SendingThread
I/BtToSocketBase( 2952): Close local in
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2952): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2952): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT6069,
I/BtToSocketBase( 2952): Close LocalOutputStream
,I/BtToSocketBase( 2952): Close localHostSocket
I/BtToSocketBase( 2952): Close bt in
I/BtToSocketBase( 2952): Close bt out
I/BtToSocketBase( 2952): Close bt socket
,I/BtToSocketBase( 2952): Close bt in
I/BtToSocketBase( 2952): Close bt out
,I/BtToSocketBase( 2952): Close bt socket
,I/jxcore-log( 2952): 2015-11-25T09:27:08.376Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2952): 
,W/bt-rfcomm( 3010): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
W/bt-rfcomm( 3010): RFCOMM_DisconnectInd LCID:0x43
,I/jxcore-log( 2952): 2015-11-25T09:27:10.378Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:27:10.379Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2952): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@309f7312:true
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: G3s-1
,I/        ( 2952): Cleared service requests
I/        ( 2952): Started peer discovery
,I/jxcore-log( 2952): 2015-11-25T09:27:15.384Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:27:15.384Z SendDataConnector.js: Connect (retry count 2) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:27:15.385Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:27:15.385Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/        ( 2952): Connecting to null, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [b4:ce:f6:ab:a4:6a]: 6, f, 410d
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 1
E/bt-btif ( 3010): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3010): Entering PendingCommandState State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device B4:CE:F6:AB:A4:6A not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for B4:CE:F6:AB:A4:6A, but we have no record of that device.
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 0
,D/BluetoothAdapterProperties( 3010): Failed to remove device: B4:CE:F6:AB:A4:6A
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3010): StableState(): Entering Off State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device B4:CE:F6:AB:A4:6A not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for B4:CE:F6:AB:A4:6A, but we have no record of that device.
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2952): Starting to Handshake
I/BTHandshakeSocketThread( 2952): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2952): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread started
,I/BTConnectToThread( 2952): got MESSAGE_READ 84 bytes.
I/BTConnectToThread( 2952): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3716"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2952): HandshakeOk : HTC-HTC Desire 820_PT3716
I/HS      ( 2952): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT3716
,I/BtConnectorHelper( 2952): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT3716
I/BtToSocketBase( 2952): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2952): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2952): mHTTPPort  set to : 46999
I/BtConnectorHelper( 2952): Request socket is using : 46999
I/BtToRequestSocket( 2952): Now accepting connections
,I/BtConnectorHelper( 2952): Calling ConnectionStatusUpdate with port :46999
I/jxcore-log( 2952): 2015-11-25T09:27:17.193Z SendDataConnector.js: CLIENT connected to 46999, error: null
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:27:17.194Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2952): 
,I/BtToRequestSocket( 2952): incoming data from: /127.0.0.1, port: 46999
I/BtToRequestSocket( 2952): Set local streams
I/BtToRequestSocket( 2952): rin ended ---------------------------;
,I/jxcore-log( 2952): 2015-11-25T09:27:17.225Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:17.375Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:17.466Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2952): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2952): 2015-11-25T09:27:17.666Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:17.809Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:17.923Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2952): 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2952): Found 5 peers.
I/SS      ( 2952): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2952): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2952): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2952): Peer(4): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2952): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 2952): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2952): Added service request
,I/jxcore-log( 2952): 2015-11-25T09:27:18.117Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2952): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2952): 2015-11-25T09:27:18.354Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:18.449Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2952): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2952): 2015-11-25T09:27:18.688Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:18.813Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:27:18.815Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:18.834Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:27:18.835Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2952): 
,I/BtConnectorHelper( 2952): Disconnect outgoing peer: B4:CE:F6:AB:A4:6A
I/BtToSocketBase( 2952): Stop ReceivingThread
I/BtToSocketBase( 2952): Stop SendingThread
I/BtToSocketBase( 2952): Close local in
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2952): Close LocalOutputStream
I/BtToSocketBase( 2952): Close localHostSocket
I/BtToSocketBase( 2952): Close bt in
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2952): Close bt out
I/BtToSocketBase( 2952): Close bt socket
I/BtToRequestSocket( 2952): Close server socket
,I/jxcore-log( 2952): 2015-11-25T09:27:18.862Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2952): 
I/jxcore-log( 2952): ---- round done--------
I/jxcore-log( 2952): 
I/jxcore-log( 2952): do fake peer & start
I/jxcore-log( 2952): 
I/jxcore-log( 2952): Connect to fake peer: 7C:F9:0E:34:8A:A0
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:27:18.863Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:27:18.863Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:27:18.863Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 7C:F9:0E:34:8A:A0, name: null
,I/        ( 2952): Connecting to null, at 7C:F9:0E:34:8A:A0
I/chromium( 2952): [INFO:CONSOLE(63)] "logCallback round[0] time: 29087 ms, rnd: 3, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2952): Started service discovery
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=0
,W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: HTC Desire 820
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
E/bt-btif ( 3010): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3010): Entering PendingCommandState State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device 7C:F9:0E:34:8A:A0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for 7C:F9:0E:34:8A:A0, but we have no record of that device.
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 3010): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3010): StableState(): Entering Off State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device 7C:F9:0E:34:8A:A0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for 7C:F9:0E:34:8A:A0, but we have no record of that device.
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2952): Starting to Handshake
I/BTHandshakeSocketThread( 2952): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2952): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread started
,I/BTConnectToThread( 2952): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 2952): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8206","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2952): HandshakeOk : samsung-SM-G900F_PT8206
I/HS      ( 2952): Hand Shake finished outgoing for : samsung-SM-G900F_PT8206
I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2952): Starting the connected thread incoming : false, samsung-SM-G900F_PT8206
I/BtToSocketBase( 2952): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2952): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2952): mHTTPPort  set to : 48506
I/BtConnectorHelper( 2952): Request socket is using : 48506
I/BtToRequestSocket( 2952): Now accepting connections
,I/BtConnectorHelper( 2952): Calling ConnectionStatusUpdate with port :48506
I/jxcore-log( 2952): 2015-11-25T09:27:25.472Z SendDataConnector.js: CLIENT connected to 48506, error: null
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:27:25.473Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2952): 
,I/BtToRequestSocket( 2952): incoming data from: /127.0.0.1, port: 48506
I/BtToRequestSocket( 2952): Set local streams
I/BtToRequestSocket( 2952): rin ended ---------------------------;
,I/jxcore-log( 2952): 2015-11-25T09:27:25.496Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:25.911Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:26.080Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:26.141Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:26.296Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:26.500Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:26.629Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:26.692Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:26.785Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:26.866Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:26.956Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:27:26.959Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:26.976Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:27:26.977Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2952): 
I/BtConnectorHelper( 2952): Disconnect outgoing peer: 7C:F9:0E:34:8A:A0
I/BtToSocketBase( 2952): Stop ReceivingThread
I/BtToSocketBase( 2952): Stop SendingThread
I/BtToSocketBase( 2952): Close local in
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2952): Close LocalOutputStream
I/BtToSocketBase( 2952): Close localHostSocket
,I/BtToSocketBase( 2952): Close bt in
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2952): Close bt out
,I/BtToSocketBase( 2952): Close bt socket
I/BtToRequestSocket( 2952): Close server socket
I/jxcore-log( 2952): 2015-11-25T09:27:27.001Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2952): 
I/jxcore-log( 2952): ---- round done--------
I/jxcore-log( 2952): 
I/jxcore-log( 2952): do fake peer & start
I/jxcore-log( 2952): 
I/jxcore-log( 2952): Connect to fake peer: 7C:F9:0E:37:96:AB
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:27.011Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:27.012Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:27:27.012Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/        ( 2952): Connecting to null, at 7C:F9:0E:37:96:AB
I/chromium( 2952): [INFO:CONSOLE(63)] "logCallback round[0] time: 8097 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3010): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
E/bt-btif ( 3010): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3010): Entering PendingCommandState State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothAdapterProperties( 3010): Failed to remove device: 7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3010): StableState(): Entering Off State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: S5-1
,W/bt-rfcomm( 3010): PORT_StartCnf failed result:5
E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 3010): invalid rfc slot id: 10
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:27:35.632Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:27:35.633Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:27:35.634Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: A5-1
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2952): 2015-11-25T09:27:40.636Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:27:40.638Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:45.644Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:27:45.645Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:27:45.645Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:27:45.646Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 2952): Connecting to A5-1, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:11, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 11
I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:27:50.819Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:27:50.819Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:27:50.819Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:27:55.820Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:27:55.820Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2952): 
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2952): 2015-11-25T09:28:00.824Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:28:00.825Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:28:00.826Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:00.826Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 2952): Connecting to A5-1, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
E/bt-btif ( 3010): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3010): Entering PendingCommandState State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
,D/BluetoothAdapterProperties( 3010): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3010): StableState(): Entering Off State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: A5-1
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2952): we got incoming connection
I/BTHandshakeSocketThread( 2952): Creating BTHandshakeSocketThread
I/BTListenerThread( 2952): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread started
,I/BTListenerThread( 2952): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 2952): Got JSON from encryption:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4529"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2952): MESSAGE_WRITE 77 bytes.
I/HS      ( 2952): Incoming connection Hand Shake finished for : LGE-LG-D802_PT4529
I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 2952): Starting the connected thread incoming : true, LGE-LG-D802_PT4529
,I/BtToSocketBase( 2952): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2952): Creating BTConnectedThread
I/BtConnectorHelper( 2952): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2952): --DoOneRunRound started
,I/BtToRequestSocket( 2952): LocalHost address: localhost/127.0.0.1, port: 52776
I/BtToRequestSocket( 2952): --DoOneRunRound ended
,I/jxcore-log( 2952): 2015-11-25T09:28:02.792Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2952): 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2952): 2015-11-25T09:28:04.643Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:04.654Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:04.663Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2952): 
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,I/jxcore-log( 2952): 2015-11-25T09:28:04.711Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:04.758Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:04.992Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:05.020Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:05.082Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:05.196Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:05.285Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:05.444Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:05.535Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:05.641Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:05.694Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:05.730Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:05.765Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:06.057Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 2952): 
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,I/jxcore-log( 2952): 2015-11-25T09:28:06.245Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:06.302Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:06.349Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:06.519Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:06.635Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 2952): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2952): 2015-11-25T09:28:06.772Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:06.818Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:06.848Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:06.878Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:06.970Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:06.976Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:07.048Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:07.092Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:07.128Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:07.232Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:07.360Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:07.443Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:07.613Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:07.652Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:07.702Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:07.977Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:08.157Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:08.318Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:08.402Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:08.547Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:08.725Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:08.766Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:08.970Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:09.008Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:09.042Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:09.362Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:09.560Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2952): 
,W/bt-btif ( 3010): invalid rfc slot id: 7
,I/BtToSocketBase( 2952): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2952): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2952): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT4529
,I/BtToSocketBase( 2952): Stop ReceivingThread
I/BtToSocketBase( 2952): Stop SendingThread
,I/BtToSocketBase( 2952): Close local in
I/BtToSocketBase( 2952): Close LocalOutputStream
I/BtToSocketBase( 2952): Close localHostSocket
I/BtToSocketBase( 2952): Close bt in
I/BtToSocketBase( 2952): Close bt out
I/BtToSocketBase( 2952): Close bt socket
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2952): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2952): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT4529
I/BtToSocketBase( 2952): Close bt in
I/BtToSocketBase( 2952): Close bt out
I/BtToSocketBase( 2952): Close bt socket
,I/jxcore-log( 2952): 2015-11-25T09:28:09.780Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2952): 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3010): rfc_find_lcid_mcb LCID reused LCID:0x40 current:0x0
W/bt-rfcomm( 3010): RFCOMM_DisconnectInd LCID:0x40
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=0
,W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: Thali Test's G2
,I/        ( 2952): Cleared service requests
I/        ( 2952): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2952): Found 3 peers.
I/SS      ( 2952): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2952): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2952): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 2952): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2952): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2952): Started service discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2952): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT124"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT124"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT124, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT124, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 2952): Cleared service requests
I/        ( 2952): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2952): Found 4 peers.
I/SS      ( 2952): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2952): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2952): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2952): Peer(4): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2952): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2952): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2952): Started service discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-rfcomm( 3010): PORT_StartCnf failed result:5
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 3010): invalid rfc slot id: 12
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:28:35.701Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:28:35.701Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:28:35.702Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: A5-1
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,I/jxcore-log( 2952): 2015-11-25T09:28:40.703Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:28:40.704Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:45.708Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:28:45.709Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:28:45.710Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:28:45.710Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 2952): Connecting to A5-1, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [7c:f9:0e:37:96:ab]: 6, f, 4106
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: A5-1
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2952): Starting to Handshake
,I/BTHandshakeSocketThread( 2952): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2952): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread started
,I/BTConnectToThread( 2952): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 2952): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6627","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2952): HandshakeOk : samsung-SM-A500FU_PT6627
I/HS      ( 2952): Hand Shake finished outgoing for : samsung-SM-A500FU_PT6627
I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2952): Starting the connected thread incoming : false, samsung-SM-A500FU_PT6627
I/BtToSocketBase( 2952): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2952): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2952): mHTTPPort  set to : 33190
I/BtConnectorHelper( 2952): Request socket is using : 33190
I/BtToRequestSocket( 2952): Now accepting connections
,I/BtConnectorHelper( 2952): Calling ConnectionStatusUpdate with port :33190
I/jxcore-log( 2952): 2015-11-25T09:28:50.724Z SendDataConnector.js: CLIENT connected to 33190, error: null
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:28:50.725Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2952): 
,I/BtToRequestSocket( 2952): incoming data from: /127.0.0.1, port: 33190
I/BtToRequestSocket( 2952): Set local streams
,I/BtToRequestSocket( 2952): rin ended ---------------------------;
,I/jxcore-log( 2952): 2015-11-25T09:28:50.772Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2952): 
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24979
,I/jxcore-log( 2952): 2015-11-25T09:28:52.673Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2952): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2952): 2015-11-25T09:28:53.353Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2952): 
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14089
,I/jxcore-log( 2952): 2015-11-25T09:28:53.893Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:54.040Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2952): 
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4189
,I/jxcore-log( 2952): 2015-11-25T09:28:54.135Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:54.233Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:54.302Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:54.373Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:54.455Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:54.535Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:28:54.536Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:54.555Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:54.556Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2952): 
,I/BtConnectorHelper( 2952): Disconnect outgoing peer: 7C:F9:0E:37:96:AB
I/BtToSocketBase( 2952): Stop ReceivingThread
,I/BtToSocketBase( 2952): Stop SendingThread
I/BtToSocketBase( 2952): Close local in
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2952): Close LocalOutputStream
,I/BtToSocketBase( 2952): Close localHostSocket
I/BtToSocketBase( 2952): Close bt in
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2952): Close bt out
I/BtToSocketBase( 2952): Close bt socket
I/BtToRequestSocket( 2952): Close server socket
I/jxcore-log( 2952): 2015-11-25T09:28:54.588Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2952): 
I/jxcore-log( 2952): ---- round done--------
I/jxcore-log( 2952): 
I/jxcore-log( 2952): do fake peer & start
I/jxcore-log( 2952): 
I/jxcore-log( 2952): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:28:54.593Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:28:54.594Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:28:54.595Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 2952): Connecting to null, at 08:EC:A9:50:76:27
I/chromium( 2952): [INFO:CONSOLE(63)] "logCallback round[0] time: 87524 ms, rnd: 4, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 3010): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
E/bt-btif ( 3010): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3010): Entering PendingCommandState State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device 08:EC:A9:50:76:27 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for 08:EC:A9:50:76:27, but we have no record of that device.
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/BluetoothAdapterProperties( 3010): Failed to remove device: 08:EC:A9:50:76:27
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3010): StableState(): Entering Off State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device 08:EC:A9:50:76:27 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for 08:EC:A9:50:76:27, but we have no record of that device.
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2952): Starting to Handshake
,I/BTHandshakeSocketThread( 2952): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2952): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread started
,I/BTConnectToThread( 2952): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 2952): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4190","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2952): HandshakeOk : samsung-SM-A300FU_PT4190
I/HS      ( 2952): Hand Shake finished outgoing for : samsung-SM-A300FU_PT4190
,I/BtConnectorHelper( 2952): Starting the connected thread incoming : false, samsung-SM-A300FU_PT4190
I/BtToSocketBase( 2952): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2952): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2952): mHTTPPort  set to : 38724
I/BtConnectorHelper( 2952): Request socket is using : 38724
I/BtToRequestSocket( 2952): Now accepting connections
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/BtConnectorHelper( 2952): Calling ConnectionStatusUpdate with port :38724
I/jxcore-log( 2952): 2015-11-25T09:28:57.723Z SendDataConnector.js: CLIENT connected to 38724, error: null
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:28:57.724Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2952): 
,I/BtToRequestSocket( 2952): incoming data from: /127.0.0.1, port: 38724
I/BtToRequestSocket( 2952): Set local streams
I/BtToRequestSocket( 2952): rin ended ---------------------------;
,I/jxcore-log( 2952): 2015-11-25T09:28:57.746Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2952): 
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 2952): 2015-11-25T09:28:57.926Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:57.968Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2952): 
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12827
,I/jxcore-log( 2952): 2015-11-25T09:28:58.002Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:58.056Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2952): 
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3917
,I/jxcore-log( 2952): 2015-11-25T09:28:58.115Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:58.213Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:58.270Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:58.414Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:58.469Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2952): 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/jxcore-log( 2952): 2015-11-25T09:28:58.547Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:28:58.548Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:28:58.558Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:28:58.559Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2952): 
I/BtConnectorHelper( 2952): Disconnect outgoing peer: 08:EC:A9:50:76:27
I/BtToSocketBase( 2952): Stop ReceivingThread
I/BtToSocketBase( 2952): Stop SendingThread
I/BtToSocketBase( 2952): Close local in
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2952): Close LocalOutputStream
I/BtToSocketBase( 2952): Close localHostSocket
I/BtToSocketBase( 2952): Close bt in
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2952): Close bt out
I/BtToSocketBase( 2952): Close bt socket
I/BtToRequestSocket( 2952): Close server socket
,I/jxcore-log( 2952): 2015-11-25T09:28:58.583Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2952): 
I/jxcore-log( 2952): ---- round done--------
I/jxcore-log( 2952): 
I/jxcore-log( 2952): do fake peer & start
I/jxcore-log( 2952): 
I/jxcore-log( 2952): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:28:58.584Z SendDataConnector.js: Start called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:28:58.584Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:28:58.584Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 58:2A:F7:ED:96:BE, name: null
,W/bt-btif ( 3010): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,I/        ( 2952): Connecting to null, at 58:2A:F7:ED:96:BE
I/chromium( 2952): [INFO:CONSOLE(63)] "logCallback round[0] time: 3954 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: A5-1
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e5196c rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 1
E/bt-btif ( 3010): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3010): Entering PendingCommandState State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device 58:2A:F7:ED:96:BE not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for 58:2A:F7:ED:96:BE, but we have no record of that device.
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 0
,D/BluetoothAdapterProperties( 3010): Failed to remove device: 58:2A:F7:ED:96:BE
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3010): StableState(): Entering Off State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device 58:2A:F7:ED:96:BE not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for 58:2A:F7:ED:96:BE, but we have no record of that device.
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2952): Starting to Handshake
I/BTHandshakeSocketThread( 2952): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2952): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread started
,I/BTConnectToThread( 2952): got MESSAGE_READ 80 bytes.
I/BTConnectToThread( 2952): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT5854","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2952): HandshakeOk : HUAWEI-ALE-L21_PT5854
I/HS      ( 2952): Hand Shake finished outgoing for : HUAWEI-ALE-L21_PT5854
I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2952): Starting the connected thread incoming : false, HUAWEI-ALE-L21_PT5854
I/BtToSocketBase( 2952): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2952): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2952): mHTTPPort  set to : 51795
I/BtConnectorHelper( 2952): Request socket is using : 51795
,I/BtToRequestSocket( 2952): Now accepting connections
,I/BtConnectorHelper( 2952): Calling ConnectionStatusUpdate with port :51795
I/jxcore-log( 2952): 2015-11-25T09:29:00.993Z SendDataConnector.js: CLIENT connected to 51795, error: null
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:29:00.993Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:00.995Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2952): 
,I/BtToRequestSocket( 2952): incoming data from: /127.0.0.1, port: 51795
I/BtToRequestSocket( 2952): Set local streams
I/BtToRequestSocket( 2952): rin ended ---------------------------;
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 2952): 2015-11-25T09:29:01.143Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2952): 
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:16787
,I/jxcore-log( 2952): 2015-11-25T09:29:01.179Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2952): 
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13817
,I/jxcore-log( 2952): 2015-11-25T09:29:01.194Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:01.221Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2952): 
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3917
,I/jxcore-log( 2952): 2015-11-25T09:29:01.275Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:01.335Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:01.384Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2952): ,
,I/jxcore-log( 2952): 2015-11-25T09:29:01.413Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:01.423Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:01.485Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:01.486Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:01.504Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:29:01.504Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2952): 
,I/BtConnectorHelper( 2952): Disconnect outgoing peer: 58:2A:F7:ED:96:BE
I/BtToSocketBase( 2952): Stop ReceivingThread
I/BtToSocketBase( 2952): Stop SendingThread
I/BtToSocketBase( 2952): Close local in
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2952): Close LocalOutputStream
,I/BtToSocketBase( 2952): Close localHostSocket
I/BtToSocketBase( 2952): Close bt in
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/BtToSocketBase( 2952): Close bt out
I/BtToSocketBase( 2952): Close bt socket
I/BtToRequestSocket( 2952): Close server socket
,I/jxcore-log( 2952): 2015-11-25T09:29:01.543Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2952): 
I/jxcore-log( 2952): ---- round done--------
I/jxcore-log( 2952): 
I/jxcore-log( 2952): do fake peer & start
I/jxcore-log( 2952): 
I/jxcore-log( 2952): Connect to fake peer: F4:F1:E1:5C:3B:E2
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:29:01.546Z SendDataConnector.js: Start called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2952): 
,W/bt-btif ( 3010): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,I/jxcore-log( 2952): 2015-11-25T09:29:01.557Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:29:01.558Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: F4:F1:E1:5C:3B:E2, name: null
,I/        ( 2952): Connecting to null, at F4:F1:E1:5C:3B:E2
I/chromium( 2952): [INFO:CONSOLE(63)] "logCallback round[0] time: 2905 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: ALE-L21
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,W/bt-rfcomm( 3010): PORT_StartCnf failed result:5
,W/bt-btif ( 3010): invalid rfc slot id: 17
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btif ( 3010): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 3010): No record of the device:null
I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 9 Address: F4:F1:E1:5C:3B:E2 newState: 0
,E/BluetoothBondStateMachine( 3010): In stable state, received invalid newState: 10
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2952): 2015-11-25T09:29:06.740Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:29:06.741Z SendDataConnector.js: CLIENT Can not Connect: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:29:06.741Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
E/bt-btif ( 3010): Do not find the bg connection mask for the remote device
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2952): 2015-11-25T09:29:11.742Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:11.743Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:16.746Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:29:16.748Z SendDataConnector.js: Connect (retry count 1) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:29:16.749Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:29:16.750Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: F4:F1:E1:5C:3B:E2, name: null
,I/        ( 2952): Connecting to null, at F4:F1:E1:5C:3B:E2
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btm  ( 3010): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=2
,W/bt-btif ( 3010): bta_dm_check_av:0
W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 1
E/bt-btif ( 3010): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3010): Entering PendingCommandState State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device F4:F1:E1:5C:3B:E2 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for F4:F1:E1:5C:3B:E2, but we have no record of that device.
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 0
,D/BluetoothAdapterProperties( 3010): Failed to remove device: F4:F1:E1:5C:3B:E2
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3010): StableState(): Entering Off State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device F4:F1:E1:5C:3B:E2 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for F4:F1:E1:5C:3B:E2, but we have no record of that device.
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2952): Starting to Handshake
I/BTHandshakeSocketThread( 2952): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2952): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread started
,I/BTConnectToThread( 2952): got MESSAGE_READ 80 bytes.
I/BTConnectToThread( 2952): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT124"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2952): HandshakeOk : motorola-XT1039_PT124
I/HS      ( 2952): Hand Shake finished outgoing for : motorola-XT1039_PT124
I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2952): Starting the connected thread incoming : false, motorola-XT1039_PT124
I/BtToSocketBase( 2952): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2952): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2952): mHTTPPort  set to : 53383
I/BtConnectorHelper( 2952): Request socket is using : 53383
I/BtToRequestSocket( 2952): Now accepting connections
,I/BtConnectorHelper( 2952): Calling ConnectionStatusUpdate with port :53383
I/jxcore-log( 2952): 2015-11-25T09:29:28.503Z SendDataConnector.js: CLIENT connected to 53383, error: null
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:29:28.504Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2952): 
,I/BtToRequestSocket( 2952): incoming data from: /127.0.0.1, port: 53383
I/BtToRequestSocket( 2952): Set local streams
I/BtToRequestSocket( 2952): rin ended ---------------------------;
,I/jxcore-log( 2952): 2015-11-25T09:29:28.524Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2952): 
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 2952): 2015-11-25T09:29:28.746Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:28.768Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2952): 
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13817
,I/jxcore-log( 2952): 2015-11-25T09:29:28.806Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:28.895Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2952): 
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:1937
,I/jxcore-log( 2952): 2015-11-25T09:29:28.943Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:28.955Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:29.045Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:29.121Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:29.126Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:29.223Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:29:29.224Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:29.241Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:29:29.246Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2952): 
I/BtConnectorHelper( 2952): Disconnect outgoing peer: F4:F1:E1:5C:3B:E2
I/BtToSocketBase( 2952): Stop ReceivingThread
I/BtToSocketBase( 2952): Stop SendingThread
I/BtToSocketBase( 2952): Close local in
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2952): Close LocalOutputStream
I/BtToSocketBase( 2952): Close localHostSocket
I/BtToSocketBase( 2952): Close bt in
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2952): Close bt out
I/BtToSocketBase( 2952): Close bt socket
I/BtToRequestSocket( 2952): Close server socket
I/jxcore-log( 2952): 2015-11-25T09:29:29.269Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2952): 
,W/bt-btif ( 3010): bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND
,I/jxcore-log( 2952): ---- round done--------
I/jxcore-log( 2952): 
I/jxcore-log( 2952): do fake peer & start
I/jxcore-log( 2952): 
I/jxcore-log( 2952): Connect to fake peer: 80:01:84:8A:B3:68
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:29:29.279Z SendDataConnector.js: Start called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:29:29.280Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:29:29.281Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 80:01:84:8A:B3:68, name: null
,I/        ( 2952): Connecting to null, at 80:01:84:8A:B3:68
,I/chromium( 2952): [INFO:CONSOLE(63)] "logCallback round[0] time: 27669 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/        ( 2952): Cleared service requests
I/        ( 2952): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e51cfc rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2952): Found 4 peers.
I/SS      ( 2952): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2952): Peer(2): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2952): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2952): Peer(4): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2952): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2952): Added service request
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 1
E/bt-btif ( 3010): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3010): Entering PendingCommandState State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device 80:01:84:8A:B3:68 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for 80:01:84:8A:B3:68, but we have no record of that device.
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 0
,D/BluetoothAdapterProperties( 3010): Failed to remove device: 80:01:84:8A:B3:68
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3010): StableState(): Entering Off State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device 80:01:84:8A:B3:68 not found, calling readPairedDevices().
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2952): Started service discovery
,E/BluetoothEventManager( 3017): Got bonding state changed for 80:01:84:8A:B3:68, but we have no record of that device.
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2952): Starting to Handshake
I/BTHandshakeSocketThread( 2952): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2952): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread started
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e51cfc rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 2952): got MESSAGE_READ 84 bytes.
I/BTConnectToThread( 2952): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT8406"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2952): HandshakeOk : HTC-HTC Desire 820_PT8406
I/HS      ( 2952): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT8406
I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2952): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT8406
I/BtToSocketBase( 2952): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2952): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2952): mHTTPPort  set to : 56724
,I/BtConnectorHelper( 2952): Request socket is using : 56724
I/BtToRequestSocket( 2952): Now accepting connections
,I/BtConnectorHelper( 2952): Calling ConnectionStatusUpdate with port :56724
,I/jxcore-log( 2952): 2015-11-25T09:29:32.747Z SendDataConnector.js: CLIENT connected to 56724, error: null
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:29:32.748Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2952): 
,I/BtToRequestSocket( 2952): incoming data from: /127.0.0.1, port: 56724
I/BtToRequestSocket( 2952): Set local streams
I/BtToRequestSocket( 2952): rin ended ---------------------------;
,I/jxcore-log( 2952): 2015-11-25T09:29:32.778Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2952): 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: XT1039
,I/jxcore-log( 2952): 2015-11-25T09:29:33.488Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:33.795Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:34.099Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:34.142Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:34.183Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:34.333Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:34.406Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:34.586Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:34.707Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:34.754Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:29:34.755Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:34.771Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:29:34.772Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2952): 
I/BtConnectorHelper( 2952): Disconnect outgoing peer: 80:01:84:8A:B3:68
I/BtToSocketBase( 2952): Stop ReceivingThread
I/BtToSocketBase( 2952): Stop SendingThread
I/BtToSocketBase( 2952): Close local in
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2952): Close LocalOutputStream
I/BtToSocketBase( 2952): Close localHostSocket
,I/BtToSocketBase( 2952): Close bt in
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2952): Close bt out
I/BtToSocketBase( 2952): Close bt socket
I/BtToRequestSocket( 2952): Close server socket
I/jxcore-log( 2952): 2015-11-25T09:29:34.803Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 2952): 
I/jxcore-log( 2952): ---- round done--------
I/jxcore-log( 2952): 
I/jxcore-log( 2952): do fake peer & start
I/jxcore-log( 2952): 
I/jxcore-log( 2952): Connect to fake peer: 50:2E:6C:AC:21:50
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:29:34.806Z SendDataConnector.js: Start called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:34.812Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:34.812Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 50:2E:6C:AC:21:50, name: null,
,I/        ( 2952): Connecting to null, at 50:2E:6C:AC:21:50
,I/chromium( 2952): [INFO:CONSOLE(63)] "logCallback round[0] time: 5475 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 3010): bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e51cfc rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: HTC Desire 820
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:20, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 20
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:29:40.025Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:40.026Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:40.030Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 1
E/bt-btif ( 3010): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3010): Entering PendingCommandState State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device F8:CF:C5:D9:E5:61 not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 0
,D/BluetoothAdapterProperties( 3010): Failed to remove device: F8:CF:C5:D9:E5:61
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3010): StableState(): Entering Off State
,E/BluetoothEventManager( 3017): Got bonding state changed for F8:CF:C5:D9:E5:61, but we have no record of that device.
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device F8:CF:C5:D9:E5:61 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for F8:CF:C5:D9:E5:61, but we have no record of that device.
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2952): we got incoming connection
I/BTHandshakeSocketThread( 2952): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2952): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread started
,I/BTListenerThread( 2952): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 2952): Got JSON from encryption:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8656","ra":"F8:CF:C5:D9:E5:61"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2952): MESSAGE_WRITE 77 bytes.
I/HS      ( 2952): Incoming connection Hand Shake finished for : motorola-Nexus 6_PT8656
I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2952): Starting the connected thread incoming : true, motorola-Nexus 6_PT8656
,I/BtToSocketBase( 2952): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2952): Creating BTConnectedThread
,I/BtConnectorHelper( 2952): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2952): --DoOneRunRound started
,I/BtToRequestSocket( 2952): LocalHost address: localhost/127.0.0.1, port: 52776
,I/BtToRequestSocket( 2952): --DoOneRunRound ended
,I/jxcore-log( 2952): 2015-11-25T09:29:40.976Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:41.313Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:41.319Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:41.332Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:41.341Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:41.354Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:41.388Z SendDataTCPServer.js: TCP/IP server has received 22052 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:41.394Z SendDataTCPServer.js: TCP/IP server has received 24032 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:41.500Z SendDataTCPServer.js: TCP/IP server has received 26012 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:41.525Z SendDataTCPServer.js: TCP/IP server has received 27992 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:41.529Z SendDataTCPServer.js: TCP/IP server has received 29972 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:41.560Z SendDataTCPServer.js: TCP/IP server has received 31952 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:41.562Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:41.599Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:41.682Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:41.732Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:41.795Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:41.846Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:41.895Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:41.923Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:41.956Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:41.987Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:42.016Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:42.060Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:42.091Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:42.102Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:42.138Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:42.146Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 2952): 
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,I/jxcore-log( 2952): 2015-11-25T09:29:42.160Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:42.188Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:42.192Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:42.213Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:42.225Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:42.258Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2952): 
,W/bt-btif ( 3010): invalid rfc slot id: 13
,I/BtToSocketBase( 2952): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2952): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2952): Disconnect:::Stop : mBtToServerSocket :motorola-Nexus 6_PT8656
I/BtToSocketBase( 2952): Stop ReceivingThread
I/BtToSocketBase( 2952): Stop SendingThread
,I/BtToSocketBase( 2952): Close local in
I/BtToSocketBase( 2952): Close LocalOutputStream
I/BtToSocketBase( 2952): Close localHostSocket
I/BtToSocketBase( 2952): Close bt in
I/BtToSocketBase( 2952): Close bt out
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2952): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2952): Disconnect:::Stop : mBtToServerSocket :motorola-Nexus 6_PT8656
I/BtToSocketBase( 2952): Close bt in
I/BtToSocketBase( 2952): Close bt out
I/BtToSocketBase( 2952): Close bt socket
,I/BtToSocketBase( 2952): Close bt socket
,I/jxcore-log( 2952): 2015-11-25T09:29:42.336Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2952): 
,W/bt-rfcomm( 3010): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
W/bt-rfcomm( 3010): RFCOMM_DisconnectInd LCID:0x46
,I/jxcore-log( 2952): 2015-11-25T09:29:45.035Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:45.036Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 2952): 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: Nexus 6
,I/jxcore-log( 2952): 2015-11-25T09:29:50.043Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:29:50.043Z SendDataConnector.js: Connect (retry count 1) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:29:50.044Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:29:50.045Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 50:2E:6C:AC:21:50, name: null
,I/        ( 2952): Connecting to null, at 50:2E:6C:AC:21:50
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,W/bt-rfcomm( 3010): PORT_StartCnf failed result:5
,W/bt-btif ( 3010): invalid rfc slot id: 22
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btif ( 3010): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 3010): No record of the device:null
I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 9 Address: 50:2E:6C:AC:21:50 newState: 0
,E/BluetoothBondStateMachine( 3010): In stable state, received invalid newState: 10
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:29:53.504Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:29:53.505Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:29:53.506Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
E/bt-btif ( 3010): Do not find the bg connection mask for the remote device
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2952): 2015-11-25T09:29:58.507Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:29:58.508Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 2952): 
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2952): 2015-11-25T09:30:03.512Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:30:03.513Z SendDataConnector.js: Connect (retry count 2) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:30:03.513Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:30:03.514Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 50:2E:6C:AC:21:50, name: null
,I/        ( 2952): Connecting to null, at 50:2E:6C:AC:21:50
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 1
E/bt-btif ( 3010): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3010): Entering PendingCommandState State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device 50:2E:6C:AC:21:50 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for 50:2E:6C:AC:21:50, but we have no record of that device.
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 0
,D/BluetoothAdapterProperties( 3010): Failed to remove device: 50:2E:6C:AC:21:50
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3010): StableState(): Entering Off State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device 50:2E:6C:AC:21:50 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for 50:2E:6C:AC:21:50, but we have no record of that device.
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2952): Starting to Handshake
I/BTHandshakeSocketThread( 2952): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2952): we got incoming connection
I/BTHandshakeSocketThread( 2952): Creating BTHandshakeSocketThread
I/BTListenerThread( 2952): waiting to accept incoming Connection
,I/BTConnectToThread( 2952): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread started
,I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread started
,I/BTListenerThread( 2952): got MESSAGE_READ 80 bytes.
I/BTListenerThread( 2952): Got JSON from encryption:{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT7367","ra":"50:2E:6C:AC:21:50"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2952): MESSAGE_WRITE 77 bytes.
I/HS      ( 2952): Incoming connection Hand Shake finished for : HTC-HTC One_M8_PT7367
I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2952): Starting the connected thread incoming : true, HTC-HTC One_M8_PT7367
I/BtToSocketBase( 2952): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2952): Creating BTConnectedThread
I/BtConnectorHelper( 2952): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2952): --DoOneRunRound started
,I/BTConnectToThread( 2952): got MESSAGE_READ 80 bytes.
I/BTConnectToThread( 2952): Got JSON from encryption:{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT7367","ra":"50:2E:6C:AC:21:50"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2952): HandshakeOk : HTC-HTC One_M8_PT7367
I/HS      ( 2952): Hand Shake finished outgoing for : HTC-HTC One_M8_PT7367
I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2952): Starting the connected thread incoming : false, HTC-HTC One_M8_PT7367
,I/BtToSocketBase( 2952): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2952): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2952): mHTTPPort  set to : 59777
I/BtConnectorHelper( 2952): Request socket is using : 59777
I/BtToRequestSocket( 2952): Now accepting connections
,I/BtToRequestSocket( 2952): LocalHost address: localhost/127.0.0.1, port: 52776
,I/jxcore-log( 2952): 2015-11-25T09:30:07.346Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2952): 
,I/BtToRequestSocket( 2952): --DoOneRunRound ended
,I/BtConnectorHelper( 2952): Calling ConnectionStatusUpdate with port :59777
I/jxcore-log( 2952): 2015-11-25T09:30:07.644Z SendDataConnector.js: CLIENT connected to 59777, error: null
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:30:07.645Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2952): 
,I/BtToRequestSocket( 2952): incoming data from: /127.0.0.1, port: 59777
I/BtToRequestSocket( 2952): Set local streams
I/BtToRequestSocket( 2952): rin ended ---------------------------;
,I/jxcore-log( 2952): 2015-11-25T09:30:07.666Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:07.779Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:07.821Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:07.832Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:07.880Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:07.918Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:07.930Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:07.973Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:08.068Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:08.157Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 2952): 
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 2952): 2015-11-25T09:30:08.163Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:08.214Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:08.412Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:08.464Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:08.505Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:08.544Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:08.555Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:08.598Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:30:08.601Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2952): 
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13817
,I/jxcore-log( 2952): 2015-11-25T09:30:08.633Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:08.642Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:08.681Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:08.729Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:08.807Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:08.860Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:08.899Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:08.953Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2952): 
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3917
,I/jxcore-log( 2952): 2015-11-25T09:30:09.044Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:09.071Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:09.098Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:09.142Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:09.188Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:09.238Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:09.279Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:09.326Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:09.369Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:09.412Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 2952): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2952): 2015-11-25T09:30:09.478Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:09.484Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:09.503Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:09.553Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:09.582Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:09.609Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:09.650Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:09.659Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:09.710Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:09.866Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:09.878Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:09.917Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:09.960Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:10.014Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:10.051Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:10.097Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:30:10.099Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:10.144Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:10.190Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:10.228Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:10.236Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:10.244Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:30:10.245Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:10.262Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:30:10.263Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2952): 
,I/BtConnectorHelper( 2952): Disconnect outgoing peer: 50:2E:6C:AC:21:50
I/BtToSocketBase( 2952): Stop ReceivingThread
I/BtToSocketBase( 2952): Stop SendingThread
I/BtToSocketBase( 2952): Close local in
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2952): Close LocalOutputStream
I/BtToSocketBase( 2952): Close localHostSocket
I/BtToSocketBase( 2952): Close bt in
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2952): Close bt out
I/BtToSocketBase( 2952): Close bt socket
I/BtToRequestSocket( 2952): Close server socket
,I/jxcore-log( 2952): 2015-11-25T09:30:10.301Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 2952): 
I/jxcore-log( 2952): ---- round done--------
I/jxcore-log( 2952): 
I/jxcore-log( 2952): do fake peer & start
I/jxcore-log( 2952): 
I/jxcore-log( 2952): Connect to fake peer: F8:CF:C5:D9:E5:61
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:30:10.302Z SendDataConnector.js: Start called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:30:10.302Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:30:10.302Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: F8:CF:C5:D9:E5:61, name: Nexus 6
,I/        ( 2952): Connecting to Nexus 6, at F8:CF:C5:D9:E5:61
,I/chromium( 2952): [INFO:CONSOLE(63)] "logCallback round[0] time: 35440 ms, rnd: 3, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2952): 2015-11-25T09:30:10.309Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 2952): 
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 2952): 2015-11-25T09:30:10.319Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:10.328Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 2952): 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e51ec4 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2952): 2015-11-25T09:30:10.581Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2952): 
,W/bt-btif ( 3010): bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND
,W/bt-btif ( 3010): invalid rfc slot id: 21
,I/BtToSocketBase( 2952): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2952): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2952): Disconnect:::Stop : mBtToServerSocket :HTC-HTC One_M8_PT7367
I/BtToSocketBase( 2952): Stop ReceivingThread
I/BtToSocketBase( 2952): Stop SendingThread
I/BtToSocketBase( 2952): Close local in
I/BtToSocketBase( 2952): Close LocalOutputStream
I/BtToSocketBase( 2952): Close localHostSocket
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2952): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2952): Disconnect:::Stop : mBtToServerSocket :HTC-HTC One_M8_PT7367
I/BtToSocketBase( 2952): Close bt in
I/BtToSocketBase( 2952): Close bt out
I/BtToSocketBase( 2952): Close bt socket
,I/BtToSocketBase( 2952): Close bt in
I/BtToSocketBase( 2952): Close bt out
I/BtToSocketBase( 2952): Close bt socket
,I/jxcore-log( 2952): 2015-11-25T09:30:10.697Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2952): 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e51ec4 rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f8:cf:c5:d9:e5:61]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: Nexus 6
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-rfcomm( 3010): PORT_StartCnf failed result:5
E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 3010): invalid rfc slot id: 25
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/BluetoothMapService( 3010): onReceive
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2952): 2015-11-25T09:30:16.634Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:30:16.635Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:30:16.635Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: Nexus 6
,W/bt-btm  ( 3010): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e51ec4 rs_disc_pending=2
E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: HTC One_M8
,I/jxcore-log( 2952): 2015-11-25T09:30:21.638Z SendDataConnector.js: re-try now : F8:CF:C5:D9:E5:61
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:30:21.639Z SendDataConnector.js: ReStart called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:26.643Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:30:26.644Z SendDataConnector.js: Connect (retry count 1) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:30:26.644Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:30:26.645Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: F8:CF:C5:D9:E5:61, name: Nexus 6
,I/        ( 2952): Connecting to Nexus 6, at F8:CF:C5:D9:E5:61
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f8:cf:c5:d9:e5:61]: 6, 1d, 7d3
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: Nexus 6
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2952): Starting to Handshake
I/BTHandshakeSocketThread( 2952): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2952): MESSAGE_WRITE 77 bytes.
I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread started
,I/BTConnectToThread( 2952): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 2952): Got JSON from encryption:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8656","ra":"F8:CF:C5:D9:E5:61"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2952): HandshakeOk : motorola-Nexus 6_PT8656
I/HS      ( 2952): Hand Shake finished outgoing for : motorola-Nexus 6_PT8656
I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2952): Starting the connected thread incoming : false, motorola-Nexus 6_PT8656
I/BtToSocketBase( 2952): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2952): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2952): mHTTPPort  set to : 42291
I/BtConnectorHelper( 2952): Request socket is using : 42291
I/BtToRequestSocket( 2952): Now accepting connections
,I/BtConnectorHelper( 2952): Calling ConnectionStatusUpdate with port :42291
I/jxcore-log( 2952): 2015-11-25T09:30:29.265Z SendDataConnector.js: CLIENT connected to 42291, error: null
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:30:29.265Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2952): 
,I/BtToRequestSocket( 2952): incoming data from: /127.0.0.1, port: 42291
I/BtToRequestSocket( 2952): Set local streams
I/BtToRequestSocket( 2952): rin ended ---------------------------;
,I/jxcore-log( 2952): 2015-11-25T09:30:29.287Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2952): 
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 2952): 2015-11-25T09:30:29.912Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2952): 
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18767
,I/jxcore-log( 2952): 2015-11-25T09:30:30.116Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:30.593Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2952): 
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8867
,I/jxcore-log( 2952): 2015-11-25T09:30:30.998Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2952): 
,I/        ( 2952): Cleared service requests
I/        ( 2952): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2952): Found 3 peers.
I/SS      ( 2952): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2952): Peer(2): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2952): Peer(3): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2952): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2952): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2952): 2015-11-25T09:30:31.799Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:31.975Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2952): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2952): 2015-11-25T09:30:32.380Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2952): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2952): Started service discovery
,I/jxcore-log( 2952): 2015-11-25T09:30:32.546Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:32.933Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:32.983Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:30:32.984Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:33.000Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:30:33.000Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2952): 
I/BtConnectorHelper( 2952): Disconnect outgoing peer: F8:CF:C5:D9:E5:61
I/BtToSocketBase( 2952): Stop ReceivingThread
I/BtToSocketBase( 2952): Stop SendingThread
I/BtToSocketBase( 2952): Close local in
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2952): Close LocalOutputStream
I/BtToSocketBase( 2952): Close localHostSocket
I/BtToSocketBase( 2952): Close bt in
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2952): Close bt out
I/BtToSocketBase( 2952): Close bt socket
I/BtToRequestSocket( 2952): Close server socket
I/jxcore-log( 2952): 2015-11-25T09:30:33.035Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): ---- round done--------
I/jxcore-log( 2952): 
I/jxcore-log( 2952): do fake peer & start
I/jxcore-log( 2952): 
I/jxcore-log( 2952): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:30:33.036Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:30:33.036Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:30:33.036Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 2952): Connecting to null, at 08:EC:A9:50:75:41
I/chromium( 2952): [INFO:CONSOLE(63)] "logCallback round[0] time: 22682 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 2952): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3716"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3716"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT3716, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT3716, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e5208c rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3010): bta_jv_rfc_port_to_cb(port_handle:0x19):jv handle:0x0 not FOUND
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: Nexus 6
,I/        ( 2952): Cleared service requests
I/        ( 2952): Started peer discovery
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/SS      ( 2952): Found 3 peers.
I/SS      ( 2952): Peer(1): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2952): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2952): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
,D/WifiP2pManager( 2952): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2952): Added service request
,I/        ( 2952): Started service discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2952): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4529"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4529"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4529, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4529, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 2952): Cleared service requests
I/        ( 2952): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2952): Found 5 peers.
I/SS      ( 2952): Peer(1): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2952): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2952): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2952): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2952): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 2952): Ignored { when=-9ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2952): Added service request
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
E/bt-btif ( 3010): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3010): Entering PendingCommandState State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2952): Started service discovery
,E/BluetoothEventManager( 3017): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 3010): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3010): StableState(): Entering Off State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2952): Starting to Handshake
I/BTHandshakeSocketThread( 2952): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2952): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread started
,I/BTConnectToThread( 2952): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 2952): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7055","ra":"08:EC:A9:50:75:41"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2952): HandshakeOk : samsung-SM-A300FU_PT7055
I/HS      ( 2952): Hand Shake finished outgoing for : samsung-SM-A300FU_PT7055
I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2952): Starting the connected thread incoming : false, samsung-SM-A300FU_PT7055
I/BtToSocketBase( 2952): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2952): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2952): mHTTPPort  set to : 53008
I/BtConnectorHelper( 2952): Request socket is using : 53008
I/BtToRequestSocket( 2952): Now accepting connections
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2952): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8316","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8316","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT8316, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT8316, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 2952): Calling ConnectionStatusUpdate with port :53008
I/jxcore-log( 2952): 2015-11-25T09:30:54.943Z SendDataConnector.js: CLIENT connected to 53008, error: null
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:30:54.944Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2952): 
,I/BtToRequestSocket( 2952): incoming data from: /127.0.0.1, port: 53008
I/BtToRequestSocket( 2952): Set local streams
I/BtToRequestSocket( 2952): rin ended ---------------------------;
,I/jxcore-log( 2952): 2015-11-25T09:30:54.970Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2952): 
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 2952): 2015-11-25T09:30:55.344Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:55.546Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2952): 
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12827
,I/jxcore-log( 2952): 2015-11-25T09:30:55.614Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:55.638Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2952): 
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2927
,I/jxcore-log( 2952): 2015-11-25T09:30:55.678Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:55.771Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:55.823Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:55.830Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:55.958Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:56.225Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:30:56.226Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:30:56.251Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:30:56.252Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2952): 
I/BtConnectorHelper( 2952): Disconnect outgoing peer: 08:EC:A9:50:75:41
I/BtToSocketBase( 2952): Stop ReceivingThread
I/BtToSocketBase( 2952): Stop SendingThread
I/BtToSocketBase( 2952): Close local in
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2952): Close LocalOutputStream
I/BtToSocketBase( 2952): Close localHostSocket
I/BtToSocketBase( 2952): Close bt in
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2952): Close bt out
I/BtToSocketBase( 2952): Close bt socket
I/BtToRequestSocket( 2952): Close server socket
,I/jxcore-log( 2952): 2015-11-25T09:30:56.281Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 2952): 
I/jxcore-log( 2952): ---- round done--------
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): do fake peer & start
I/jxcore-log( 2952): 
I/jxcore-log( 2952): Connect to fake peer: 58:3F:54:73:64:C0
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:30:56.283Z SendDataConnector.js: Start called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:30:56.284Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:30:56.284Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 58:3F:54:73:64:C0, name: null
,I/        ( 2952): Connecting to null, at 58:3F:54:73:64:C0
I/chromium( 2952): [INFO:CONSOLE(63)] "logCallback round[0] time: 23190 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e52254 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3010): bta_jv_rfc_port_to_cb(port_handle:0x1a):jv handle:0x0 not FOUND
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e5241c rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: A3-1
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,I/        ( 2952): Cleared service requests
,I/        ( 2952): Started peer discovery
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e5241c rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
E/bt-btif ( 3010): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3010): Entering PendingCommandState State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device 58:3F:54:73:64:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for 58:3F:54:73:64:C0, but we have no record of that device.
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
,D/BluetoothAdapterProperties( 3010): Failed to remove device: 58:3F:54:73:64:C0
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3010): StableState(): Entering Off State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device 58:3F:54:73:64:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for 58:3F:54:73:64:C0, but we have no record of that device.
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2952): Starting to Handshake
I/BTHandshakeSocketThread( 2952): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2952): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread started
,I/BTConnectToThread( 2952): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 2952): Got JSON from encryption:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5918","ra":"58:3F:54:73:64:C0"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2952): HandshakeOk : LGE-LG-D855_PT5918
I/HS      ( 2952): Hand Shake finished outgoing for : LGE-LG-D855_PT5918
I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2952): Starting the connected thread incoming : false, LGE-LG-D855_PT5918
,I/BtToSocketBase( 2952): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2952): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2952): mHTTPPort  set to : 41250
I/BtConnectorHelper( 2952): Request socket is using : 41250
I/BtToRequestSocket( 2952): Now accepting connections
,I/BtConnectorHelper( 2952): Calling ConnectionStatusUpdate with port :41250
I/jxcore-log( 2952): 2015-11-25T09:31:03.868Z SendDataConnector.js: CLIENT connected to 41250, error: null
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:31:03.869Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2952): 
,I/BtToRequestSocket( 2952): incoming data from: /127.0.0.1, port: 41250
I/BtToRequestSocket( 2952): Set local streams
I/BtToRequestSocket( 2952): rin ended ---------------------------;
,I/jxcore-log( 2952): 2015-11-25T09:31:03.899Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2952): 
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e5241c rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 2952): 2015-11-25T09:31:04.968Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2952): 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e525e4 rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2952): 2015-11-25T09:31:05.093Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2952): 
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12827
,I/jxcore-log( 2952): 2015-11-25T09:31:05.445Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2952): 
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:7877
,I/jxcore-log( 2952): 2015-11-25T09:31:05.539Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2952): 
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
E/bt-btif ( 3010): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3010): Entering PendingCommandState State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.
,I/jxcore-log( 2952): 2015-11-25T09:31:05.727Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2952): 
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 3010): Failed to remove device: E0:DB:10:14:E2:C0
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3010): StableState(): Entering Off State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2952): we got incoming connection
I/BTHandshakeSocketThread( 2952): Creating BTHandshakeSocketThread
I/BTListenerThread( 2952): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread started
,I/jxcore-log( 2952): 2015-11-25T09:31:05.986Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2952): 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e525e4 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2952): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 2952): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1533","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2952): MESSAGE_WRITE 77 bytes.
I/HS      ( 2952): Incoming connection Hand Shake finished for : samsung-SM-N910C_PT1533
I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2952): Starting the connected thread incoming : true, samsung-SM-N910C_PT1533
,I/BtToSocketBase( 2952): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2952): Creating BTConnectedThread
I/BtConnectorHelper( 2952): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2952): --DoOneRunRound started
,I/jxcore-log( 2952): 2015-11-25T09:31:06.255Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2952): 
,I/BtToRequestSocket( 2952): LocalHost address: localhost/127.0.0.1, port: 52776
,I/BtToRequestSocket( 2952): --DoOneRunRound ended
,I/jxcore-log( 2952): 2015-11-25T09:31:06.308Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:06.322Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:06.464Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:06.583Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:31:06.584Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:06.607Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:31:06.607Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2952): 
I/BtConnectorHelper( 2952): Disconnect outgoing peer: 58:3F:54:73:64:C0
I/BtToSocketBase( 2952): Stop ReceivingThread
I/BtToSocketBase( 2952): Stop SendingThread
I/BtToSocketBase( 2952): Close local in
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2952): Close LocalOutputStream
I/BtToSocketBase( 2952): Close localHostSocket
,I/BtToSocketBase( 2952): Close bt in
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2952): Close bt out
I/BtToSocketBase( 2952): Close bt socket
I/BtToRequestSocket( 2952): Close server socket
,I/jxcore-log( 2952): 2015-11-25T09:31:06.644Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): ---- round done--------
I/jxcore-log( 2952): 
I/jxcore-log( 2952): do fake peer & start
I/jxcore-log( 2952): 
I/jxcore-log( 2952): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:31:06.645Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:31:06.645Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:31:06.645Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 2952): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,I/chromium( 2952): [INFO:CONSOLE(63)] "logCallback round[0] time: 10308 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 2952): 2015-11-25T09:31:06.666Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:06.674Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:06.682Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:06.705Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:06.726Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:06.742Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:06.760Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2952): 
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,I/jxcore-log( 2952): 2015-11-25T09:31:06.803Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:06.804Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:06.813Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:06.848Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:06.876Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:06.879Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:06.923Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:06.933Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:06.946Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 2952): 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e5241c rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3010): bta_jv_rfc_port_to_cb(port_handle:0x1b):jv handle:0x0 not FOUND
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e525e4 rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2952): 2015-11-25T09:31:07.163Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:07.174Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 2952): 
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2952): Starting to Handshake
I/BTHandshakeSocketThread( 2952): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2952): MESSAGE_WRITE 77 bytes.
,I/jxcore-log( 2952): 2015-11-25T09:31:07.212Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 2952): 
,I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread started
,I/jxcore-log( 2952): 2015-11-25T09:31:07.241Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:07.250Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:07.260Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:07.318Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:07.364Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:07.403Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:07.439Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:07.445Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 2952): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2952): 2015-11-25T09:31:07.474Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:07.491Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 2952): 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e5241c rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2952): 2015-11-25T09:31:07.537Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 2952): 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e525e4 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 2952): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 2952): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1533","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2952): HandshakeOk : samsung-SM-N910C_PT1533
I/HS      ( 2952): Hand Shake finished outgoing for : samsung-SM-N910C_PT1533
I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread fully stopped
,I/jxcore-log( 2952): 2015-11-25T09:31:07.766Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 2952): 
I/BtConnectorHelper( 2952): Starting the connected thread incoming : false, samsung-SM-N910C_PT1533
I/BtToSocketBase( 2952): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2952): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2952): mHTTPPort  set to : 40716
,I/BtConnectorHelper( 2952): Request socket is using : 40716
I/BtToRequestSocket( 2952): Now accepting connections
,I/jxcore-log( 2952): 2015-11-25T09:31:07.798Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:07.808Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:07.851Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:07.892Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2952): 
,W/bt-btif ( 3010): invalid rfc slot id: 24
,I/BtToSocketBase( 2952): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2952): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2952): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N910C_PT1533
I/BtToSocketBase( 2952): Stop ReceivingThread
I/BtToSocketBase( 2952): Stop SendingThread
I/BtToSocketBase( 2952): Close local in
I/BtToSocketBase( 2952): Close LocalOutputStream
I/BtToSocketBase( 2952): Close localHostSocket
I/BtToSocketBase( 2952): Close bt in
I/BtToSocketBase( 2952): Close bt out
I/BtToSocketBase( 2952): Close bt socket
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2952): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2952): 2015-11-25T09:31:08.042Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2952): 
,I/BtConnectorHelper( 2952): Calling ConnectionStatusUpdate with port :40716
I/jxcore-log( 2952): 2015-11-25T09:31:08.085Z SendDataConnector.js: CLIENT connected to 40716, error: null
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:08.086Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2952): 
,I/BtToRequestSocket( 2952): incoming data from: /127.0.0.1, port: 40716
I/BtToRequestSocket( 2952): Set local streams
I/BtToRequestSocket( 2952): rin ended ---------------------------;
,I/jxcore-log( 2952): 2015-11-25T09:31:08.110Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2952): 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e525e4 rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2952): 2015-11-25T09:31:09.195Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2952): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2952): 2015-11-25T09:31:09.945Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2952): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2952): 2015-11-25T09:31:10.323Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2952): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2952): Found 6 peers.
I/SS      ( 2952): Peer(1): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2952): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2952): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2952): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2952): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2952): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2952): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2952): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/jxcore-log( 2952): 2015-11-25T09:31:11.483Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2952): 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: G3-1
,I/jxcore-log( 2952): 2015-11-25T09:31:12.071Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:12.258Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2952): 
,I/        ( 2952): Started service discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2952): 2015-11-25T09:31:12.606Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2952): 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2952): 2015-11-25T09:31:13.754Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:13.828Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:13.982Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:31:13.983Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:14.000Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:31:14.000Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2952): 
I/BtConnectorHelper( 2952): Disconnect outgoing peer: E0:DB:10:14:E2:C0
I/BtToSocketBase( 2952): Stop ReceivingThread
I/BtToSocketBase( 2952): Stop SendingThread
I/BtToSocketBase( 2952): Close local in
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2952): Close LocalOutputStream
I/BtToSocketBase( 2952): Close localHostSocket
,I/BtToSocketBase( 2952): Close bt in
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2952): Close bt out
I/BtToSocketBase( 2952): Close bt socket
I/BtToRequestSocket( 2952): Close server socket
,I/jxcore-log( 2952): 2015-11-25T09:31:14.026Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): ---- round done--------
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): do fake peer & start
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:14.041Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
,W/bt-btif ( 3010): bta_jv_rfc_port_to_cb(port_handle:0x1d):jv handle:0x0 not FOUND
,I/jxcore-log( 2952): 2015-11-25T09:31:14.052Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:31:14.052Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2952): Connecting to null, at 34:FC:EF:11:B1:66
I/chromium( 2952): [INFO:CONSOLE(63)] "logCallback round[0] time: 7338 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e525e4 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e525e4 rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:31, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 31
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:31:15.202Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:15.222Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:31:15.223Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e525e4 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e527ac rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e525e4 rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: Note4-1
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2952): 2015-11-25T09:31:20.225Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:31:20.226Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 2205
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: S5-1
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2952): we got incoming connection
I/BTHandshakeSocketThread( 2952): Creating BTHandshakeSocketThread
I/BTListenerThread( 2952): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread started
,I/BTListenerThread( 2952): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 2952): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8206","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2952): MESSAGE_WRITE 77 bytes.
I/HS      ( 2952): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT8206
,I/BtConnectorHelper( 2952): Starting the connected thread incoming : true, samsung-SM-G900F_PT8206
,I/BtToSocketBase( 2952): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2952): Creating BTConnectedThread
I/BtConnectorHelper( 2952): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2952): --DoOneRunRound started
,I/BtToRequestSocket( 2952): LocalHost address: localhost/127.0.0.1, port: 52776
,I/jxcore-log( 2952): 2015-11-25T09:31:24.100Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2952): 
,I/BtToRequestSocket( 2952): --DoOneRunRound ended
,I/jxcore-log( 2952): 2015-11-25T09:31:24.536Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:24.562Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:24.580Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:24.593Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:24.601Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:24.609Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:24.629Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:24.670Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:24.687Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:24.694Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:24.720Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:24.735Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:24.770Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:24.791Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:24.845Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:24.870Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:24.933Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:24.971Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:24.978Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:24.994Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:25.028Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:25.051Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:25.073Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:25.111Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:25.123Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:25.160Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:25.173Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:25.193Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:25.205Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:25.212Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:25.233Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:31:25.234Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:31:25.234Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:31:25.235Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2952): Connecting to null, at 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 2015-11-25T09:31:25.259Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 2952): 
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 2952): 2015-11-25T09:31:25.293Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:25.306Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 2952): 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2952): 2015-11-25T09:31:25.514Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:25.549Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:25.569Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:25.595Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:25.627Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:25.694Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:26.082Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:26.207Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:26.217Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2952): 
,W/bt-btif ( 3010): invalid rfc slot id: 29
,I/BtToSocketBase( 2952): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2952): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2952): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT8206
I/BtToSocketBase( 2952): Stop ReceivingThread
I/BtToSocketBase( 2952): Stop SendingThread
I/BtToSocketBase( 2952): Close local in
I/BtToSocketBase( 2952): Close LocalOutputStream
I/BtToSocketBase( 2952): Close localHostSocket
I/BtToSocketBase( 2952): Close bt in
I/BtToSocketBase( 2952): Close bt out
I/BtToSocketBase( 2952): Close bt socket
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2952): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2952): 2015-11-25T09:31:26.349Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2952): 
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:33, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 33
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2952): 2015-11-25T09:31:26.453Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:31:26.453Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:31:26.455Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3010): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
W/bt-rfcomm( 3010): RFCOMM_DisconnectInd LCID:0x48
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e527ac rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: S5-1
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2952): 2015-11-25T09:31:31.457Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:31:31.459Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:36.465Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:31:36.466Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:36.466Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:36.472Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2952): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2952): Starting to connect
,W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [34:fc:ef:11:b1:66]: 7, f, 610c
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:34, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 34
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:31:37.580Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:31:37.581Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:31:37.581Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
,I/jxcore-log( 2952): 2015-11-25T09:31:42.582Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:31:42.583Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:47.586Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:31:47.587Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:31:47.588Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:31:47.588Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2952): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:35, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 35
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:31:48.869Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:31:48.870Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:31:48.871Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2952): 2015-11-25T09:31:53.871Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:31:53.872Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:58.874Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:31:58.874Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:31:58.874Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:31:58.874Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2952): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:36, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 36
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:31:59.274Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:31:59.275Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:59.291Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:31:59.293Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): ---- round done--------
I/jxcore-log( 2952): 
I/jxcore-log( 2952): ---- gotta redo : 34:FC:EF:11:B1:66, try count now: 1
I/jxcore-log( 2952): 
I/jxcore-log( 2952): do fake peer & start
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): Connect to fake peer: E0:DB:10:1F:C9:5E
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:31:59.301Z SendDataConnector.js: Start called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:31:59.304Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:31:59.305Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: E0:DB:10:1F:C9:5E, name: null
,I/        ( 2952): Connecting to null, at E0:DB:10:1F:C9:5E
,I/chromium( 2952): [INFO:CONSOLE(63)] "logCallback round[0] time: 45233 ms, rnd: 5, ex: Connection to 34:FC:EF:11:B1:66 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e52974 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 1
E/bt-btif ( 3010): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3010): Entering PendingCommandState State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device E0:DB:10:1F:C9:5E not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for E0:DB:10:1F:C9:5E, but we have no record of that device.
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 0
,D/BluetoothAdapterProperties( 3010): Failed to remove device: E0:DB:10:1F:C9:5E
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3010): StableState(): Entering Off State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device E0:DB:10:1F:C9:5E not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for E0:DB:10:1F:C9:5E, but we have no record of that device.
,I/BTConnectToThread( 2952): Starting to Handshake
I/BTHandshakeSocketThread( 2952): Creating BTHandshakeSocketThread
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2952): MESSAGE_WRITE 77 bytes.
I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread started
,I/BTConnectToThread( 2952): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 2952): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2740","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2952): HandshakeOk : samsung-SM-N9005_PT2740
I/HS      ( 2952): Hand Shake finished outgoing for : samsung-SM-N9005_PT2740
I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2952): Starting the connected thread incoming : false, samsung-SM-N9005_PT2740
I/BtToSocketBase( 2952): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2952): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2952): mHTTPPort  set to : 36239
I/BtConnectorHelper( 2952): Request socket is using : 36239
I/BtToRequestSocket( 2952): Now accepting connections
,I/BtConnectorHelper( 2952): Calling ConnectionStatusUpdate with port :36239
I/jxcore-log( 2952): 2015-11-25T09:32:01.121Z SendDataConnector.js: CLIENT connected to 36239, error: null
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:32:01.121Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2952): 
,I/BtToRequestSocket( 2952): incoming data from: /127.0.0.1, port: 36239
I/BtToRequestSocket( 2952): Set local streams
I/BtToRequestSocket( 2952): rin ended ---------------------------;
,I/jxcore-log( 2952): 2015-11-25T09:32:01.146Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:01.591Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:01.707Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:01.746Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:01.811Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:01.898Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:01.957Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:02.045Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:02.151Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:02.160Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:02.230Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:32:02.230Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:02.246Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:32:02.246Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2952): 
I/BtConnectorHelper( 2952): Disconnect outgoing peer: E0:DB:10:1F:C9:5E
I/BtToSocketBase( 2952): Stop ReceivingThread
I/BtToSocketBase( 2952): Stop SendingThread
I/BtToSocketBase( 2952): Close local in
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2952): Close LocalOutputStream
,I/BtToSocketBase( 2952): Close localHostSocket
I/BtToSocketBase( 2952): Close bt in
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2952): Close bt out
I/BtToSocketBase( 2952): Close bt socket
I/BtToRequestSocket( 2952): Close server socket
I/jxcore-log( 2952): 2015-11-25T09:32:02.272Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2952): 
I/jxcore-log( 2952): ---- round done--------
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): do fake peer & start
I/jxcore-log( 2952): 
W/bt-btif ( 3010): bta_jv_rfc_port_to_cb(port_handle:0x1):jv handle:0x0 not FOUND
,I/jxcore-log( 2952): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:32:02.282Z SendDataConnector.js: Start called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:32:02.282Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:32:02.282Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 34:FC:EF:9D:93:0B, name: Thali Test's G2
,I/        ( 2952): Connecting to Thali Test's G2, at 34:FC:EF:9D:93:0B
I/chromium( 2952): [INFO:CONSOLE(63)] "logCallback round[0] time: 2927 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [34:fc:ef:9d:93:0b]: 0, 0, 0
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,I/BluetoothClassifier( 1328): Bluetooth Device Name: Thali Test's G2
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
E/bt-btif ( 3010): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3010): Entering PendingCommandState State,
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
,D/BluetoothAdapterProperties( 3010): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3010): StableState(): Entering Off State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2952): Starting to Handshake
,I/BTHandshakeSocketThread( 2952): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2952): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread started
,I/BTConnectToThread( 2952): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 2952): Got JSON from encryption:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4529"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2952): HandshakeOk : LGE-LG-D802_PT4529
I/HS      ( 2952): Hand Shake finished outgoing for : LGE-LG-D802_PT4529
I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2952): Starting the connected thread incoming : false, LGE-LG-D802_PT4529
I/BtToSocketBase( 2952): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2952): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2952): mHTTPPort  set to : 33745
I/BtConnectorHelper( 2952): Request socket is using : 33745
I/BtToRequestSocket( 2952): Now accepting connections
,I/BtConnectorHelper( 2952): Calling ConnectionStatusUpdate with port :33745
I/jxcore-log( 2952): 2015-11-25T09:32:05.084Z SendDataConnector.js: CLIENT connected to 33745, error: null
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:32:05.085Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2952): 
,I/BtToRequestSocket( 2952): incoming data from: /127.0.0.1, port: 33745
I/BtToRequestSocket( 2952): Set local streams
I/BtToRequestSocket( 2952): rin ended ---------------------------;
,I/jxcore-log( 2952): 2015-11-25T09:32:05.105Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:05.451Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:05.520Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:05.590Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:05.802Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2952): 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: Note3-1
,I/jxcore-log( 2952): 2015-11-25T09:32:06.572Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:07.407Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:08.013Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2952): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2952): 2015-11-25T09:32:08.458Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:08.961Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2952): 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2952): 2015-11-25T09:32:09.276Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:32:09.279Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:09.294Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:32:09.295Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2952): 
,I/BtConnectorHelper( 2952): Disconnect outgoing peer: 34:FC:EF:9D:93:0B
I/BtToSocketBase( 2952): Stop ReceivingThread
I/BtToSocketBase( 2952): Stop SendingThread
I/BtToSocketBase( 2952): Close local in
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2952): Close LocalOutputStream
,I/BtToSocketBase( 2952): Close localHostSocket
I/BtToSocketBase( 2952): Close bt in
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2952): Close bt out
I/BtToSocketBase( 2952): Close bt socket
I/BtToRequestSocket( 2952): Close server socket
,I/jxcore-log( 2952): 2015-11-25T09:32:09.323Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B,
I/jxcore-log( 2952): 
I/jxcore-log( 2952): ---- round done--------
I/jxcore-log( 2952): 
I/jxcore-log( 2952): do fake peer & start
I/jxcore-log( 2952): 
I/jxcore-log( 2952): Connect to fake peer: F8:95:C7:87:3C:51
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:32:09.325Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:32:09.326Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 2952): 
W/bt-btif ( 3010): bta_jv_rfc_port_to_cb(port_handle:0x7):jv handle:0x0 not FOUND
,I/jxcore-log( 2952): 2015-11-25T09:32:09.326Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: F8:95:C7:87:3C:51, name: null
,I/        ( 2952): Connecting to null, at F8:95:C7:87:3C:51
I/chromium( 2952): [INFO:CONSOLE(63)] "logCallback round[0] time: 6997 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e52b3c rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/        ( 2952): Cleared service requests
I/        ( 2952): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3010): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3010): Entering PendingCommandState State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3010): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 3010): StableState(): Entering Off State
,E/BluetoothEventManager( 3017): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 2952): Found 6 peers.
I/SS      ( 2952): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2952): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2952): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2952): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2952): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2952): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2952): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2952): Added service request
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2952): Starting to Handshake
,I/BTHandshakeSocketThread( 2952): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2952): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread started
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BTConnectToThread( 2952): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 2952): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8316","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2952): HandshakeOk : LGE-LG-H815_PT8316
I/HS      ( 2952): Hand Shake finished outgoing for : LGE-LG-H815_PT8316
I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2952): Starting the connected thread incoming : false, LGE-LG-H815_PT8316
I/BtToSocketBase( 2952): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2952): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2952): mHTTPPort  set to : 57692
I/BtConnectorHelper( 2952): Request socket is using : 57692
I/BtToRequestSocket( 2952): Now accepting connections
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/BtConnectorHelper( 2952): Calling ConnectionStatusUpdate with port :57692
I/jxcore-log( 2952): 2015-11-25T09:32:12.567Z SendDataConnector.js: CLIENT connected to 57692, error: null
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:32:12.568Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2952): 
,I/BtToRequestSocket( 2952): incoming data from: /127.0.0.1, port: 57692
I/BtToRequestSocket( 2952): Set local streams
,I/BtToRequestSocket( 2952): rin ended ---------------------------;
,I/jxcore-log( 2952): 2015-11-25T09:32:12.606Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2952): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2952): Started service discovery
,I/jxcore-log( 2952): 2015-11-25T09:32:13.247Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2952): 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: Thali Test's G2
,I/jxcore-log( 2952): 2015-11-25T09:32:13.350Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:13.455Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:13.525Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2952): 
,I/        ( 2952): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT124"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT124"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT124, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT124, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/jxcore-log( 2952): 2015-11-25T09:32:13.673Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:13.762Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:14.424Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:15.128Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:15.248Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:15.322Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:32:15.323Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:15.341Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:15.349Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2952): 
,I/BtConnectorHelper( 2952): Disconnect outgoing peer: F8:95:C7:87:3C:51
I/BtToSocketBase( 2952): Stop ReceivingThread
I/BtToSocketBase( 2952): Stop SendingThread
I/BtToSocketBase( 2952): Close local in
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2952): Close LocalOutputStream
I/BtToSocketBase( 2952): Close localHostSocket
,I/BtToSocketBase( 2952): Close bt in
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2952): Close bt out
I/BtToSocketBase( 2952): Close bt socket
I/BtToRequestSocket( 2952): Close server socket
I/jxcore-log( 2952): 2015-11-25T09:32:15.372Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 2952): 
I/jxcore-log( 2952): ---- round done--------
I/jxcore-log( 2952): 
I/jxcore-log( 2952): do fake peer & start
I/jxcore-log( 2952): 
I/jxcore-log( 2952): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:15.373Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:32:15.374Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:32:15.374Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2952): Connecting to null, at 00:F4:6F:30:E0:6C
I/chromium( 2952): [INFO:CONSOLE(63)] "logCallback round[0] time: 5997 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:40, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 40
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:32:17.019Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:32:17.020Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:32:17.020Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: G4-1
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 2952): Cleared service requests
I/        ( 2952): Started peer discovery
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2952): 2015-11-25T09:32:22.022Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:32:22.022Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2952): Found 4 peers.
I/SS      ( 2952): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2952): Peer(2): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2952): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2952): Peer(4): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 2952): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2952): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2952): Started service discovery
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2952): 2015-11-25T09:32:27.026Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:27.026Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:27.030Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:27.033Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2952): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [00:f4:6f:30:e0:6c]: 7, f, 6109
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:41, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 41
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2952): 2015-11-25T09:32:29.429Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:32:29.430Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:32:29.431Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e52d04 rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/        ( 2952): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6627","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6627","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT6627, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT6627, WifiDirectName: , WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/jxcore-log( 2952): 2015-11-25T09:32:34.432Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:32:34.433Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
,I/        ( 2952): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT124"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT124"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT124, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT124, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2952): 2015-11-25T09:32:39.437Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:32:39.438Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:32:39.438Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:32:39.439Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2952): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:42, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 42
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2952): 2015-11-25T09:32:40.689Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:32:40.689Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:32:40.689Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2952): Cleared service requests
I/        ( 2952): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2952): Found 7 peers.
I/SS      ( 2952): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2952): Peer(2): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2952): Peer(3): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2952): Peer(4): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2952): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2952): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2952): Peer(7): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 2952): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2952): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2952): Started service discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2952): 2015-11-25T09:32:45.690Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:45.691Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:50.706Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:32:50.708Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:32:50.709Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:32:50.709Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2952): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:43, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 43
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2952): 2015-11-25T09:32:51.270Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:32:51.271Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:32:51.271Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [e0:db:10:1f:c9:5e]: 6, f, 410d
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: Note3-1
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e52974 rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2952): we got incoming connection
I/BTHandshakeSocketThread( 2952): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2952): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread started
,I/BTListenerThread( 2952): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 2952): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2740","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2952): MESSAGE_WRITE 77 bytes.
I/HS      ( 2952): Incoming connection Hand Shake finished for : samsung-SM-N9005_PT2740
I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2952): Starting the connected thread incoming : true, samsung-SM-N9005_PT2740
I/BtToSocketBase( 2952): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2952): Creating BTConnectedThread
,I/BtConnectorHelper( 2952): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2952): --DoOneRunRound started
,I/jxcore-log( 2952): 2015-11-25T09:32:55.110Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2952): 
,I/BtToRequestSocket( 2952): LocalHost address: localhost/127.0.0.1, port: 52776
,I/BtToRequestSocket( 2952): --DoOneRunRound ended
,I/jxcore-log( 2952): 2015-11-25T09:32:55.505Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:55.508Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:55.514Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:55.551Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:55.552Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:55.560Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:55.568Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:55.610Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:55.641Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:55.649Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:55.676Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:55.724Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:55.734Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:55.770Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:55.799Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:55.818Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:55.830Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:55.835Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:55.839Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:55.878Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:55.906Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:55.910Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:55.918Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:55.922Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:55.925Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:55.957Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:55.966Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:55.997Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:56.000Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:56.045Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:56.095Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:56.117Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:56.123Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:56.131Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:56.142Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:56.151Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2952): 
,W/bt-btif ( 3010): invalid rfc slot id: 32
,I/BtToSocketBase( 2952): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2952): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2952): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N9005_PT2740
I/BtToSocketBase( 2952): Stop ReceivingThread
,I/BtToSocketBase( 2952): Stop SendingThread
I/BtToSocketBase( 2952): Close local in
I/BtToSocketBase( 2952): Close LocalOutputStream
I/BtToSocketBase( 2952): Close localHostSocket
I/BtToSocketBase( 2952): Close bt in
I/BtToSocketBase( 2952): Close bt out
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2952): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2952): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N9005_PT2740
I/BtToSocketBase( 2952): Close bt in
I/BtToSocketBase( 2952): Close bt out
I/BtToSocketBase( 2952): Close bt socket
,I/BtToSocketBase( 2952): Close bt socket
,I/jxcore-log( 2952): 2015-11-25T09:32:56.279Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:32:56.280Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:32:56.291Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2952): 
,W/bt-rfcomm( 3010): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
W/bt-rfcomm( 3010): RFCOMM_DisconnectInd LCID:0x4a
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: Note3-1
,I/jxcore-log( 2952): 2015-11-25T09:33:01.290Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:33:01.291Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:33:01.291Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:33:01.292Z SendDataConnector.js: do connect now,
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2952): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:45, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 45
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:33:01.565Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:33:01.566Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:33:01.582Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:33:01.584Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): ---- round done--------
I/jxcore-log( 2952): 
I/jxcore-log( 2952): ---- gotta redo : 00:F4:6F:30:E0:6C, try count now: 1
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): do fake peer & start
I/jxcore-log( 2952): 
I/jxcore-log( 2952): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:33:01.594Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:33:01.597Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:33:01.597Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 2952): Connecting to null, at 44:80:EB:7B:5A:05
I/chromium( 2952): [INFO:CONSOLE(63)] "logCallback round[0] time: 46192 ms, rnd: 5, ex: Connection to 00:F4:6F:30:E0:6C failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e52ecc rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:46, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 46
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:33:05.775Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:33:05.776Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:33:05.780Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2952): 2015-11-25T09:33:10.783Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:33:10.784Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:33:15.790Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:33:15.790Z SendDataConnector.js: Connect (retry count 1) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:33:15.791Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:33:15.791Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 2952): Connecting to null, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [44:80:eb:7b:5a:05]: 6, f, 410d
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:47, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 47
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:33:18.981Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:33:18.982Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:33:18.983Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2952): 2015-11-25T09:33:23.983Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:33:23.984Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:33:28.988Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:33:28.989Z SendDataConnector.js: Connect (retry count 2) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:33:28.990Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:33:28.990Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 2952): Connecting to null, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:48, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 48
I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:33:29.451Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:33:29.451Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:33:29.451Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2952): 2015-11-25T09:33:34.453Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:33:34.454Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:33:39.459Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:33:39.459Z SendDataConnector.js: Connect (retry count 3) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:33:39.460Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:33:39.461Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 2952): Connecting to null, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:49, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 49
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:33:43.299Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:33:43.299Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:33:43.300Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,I/        ( 2952): Cleared service requests
I/        ( 2952): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 2952): Found 7 peers.
I/SS      ( 2952): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2952): Peer(2): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2952): Peer(3): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2952): Peer(4): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2952): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2952): Peer(6): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2952): Peer(7): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 2952): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2952): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2952): Started service discovery
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e52ecc rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/        ( 2952): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2740","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2740","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT2740, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT2740, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 2952): 2015-11-25T09:33:48.302Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:33:48.303Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
,I/        ( 2952): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT8406"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT8406"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT8406, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT8406, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/jxcore-log( 2952): 2015-11-25T09:33:53.306Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:33:53.309Z SendDataConnector.js: Connect (retry count 4) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:33:53.309Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:33:53.310Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 2952): Connecting to null, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 2952): Cleared service requests
I/        ( 2952): Started peer discovery
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:50, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 50
I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:33:58.482Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:33:58.482Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:33:58.483Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:33:58.485Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
I/jxcore-log( 2952): ---- round done--------
I/jxcore-log( 2952): 
I/jxcore-log( 2952): ---- gotta redo : 44:80:EB:7B:5A:05, try count now: 1
I/jxcore-log( 2952): 
I/jxcore-log( 2952): do fake peer & start
I/jxcore-log( 2952): 
I/jxcore-log( 2952): Connect to fake peer: F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:33:58.486Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:33:58.486Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:33:58.486Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 2952): Connecting to G3s-1, at F8:95:C7:87:85:54
I/chromium( 2952): [INFO:CONSOLE(63)] "logCallback round[0] time: 56888 ms, rnd: 5, ex: Connection to 44:80:EB:7B:5A:05 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2952): Found 8 peers.
I/SS      ( 2952): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2952): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2952): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2952): Peer(4): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2952): Peer(5): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2952): Peer(6): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2952): Peer(7): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2952): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2952): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2952): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2952): Started service discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2952): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2740","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2740","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT2740, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT2740, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 2952): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT8406"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT8406"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT8406, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT8406, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/        ( 2952): Cleared service requests
,I/        ( 2952): Started peer discovery
I/SS      ( 2952): Found 8 peers.
I/SS      ( 2952): Peer(1): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2952): Peer(2): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2952): Peer(3): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2952): Peer(4): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2952): Peer(5): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2952): Peer(6): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2952): Peer(7): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2952): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2952): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2952): Added service request
,I/        ( 2952): Started service discovery
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [80:01:84:8a:b3:68]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: HTC Desire 820
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2952): we got incoming connection
I/BTHandshakeSocketThread( 2952): Creating BTHandshakeSocketThread
I/BTListenerThread( 2952): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread started
,I/BTListenerThread( 2952): got MESSAGE_READ 84 bytes.
I/BTListenerThread( 2952): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT8406"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2952): MESSAGE_WRITE 77 bytes.
I/HS      ( 2952): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT8406
I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 2952): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT8406
I/BtToSocketBase( 2952): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2952): Creating BTConnectedThread
I/BtConnectorHelper( 2952): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2952): --DoOneRunRound started
,I/BtToRequestSocket( 2952): LocalHost address: localhost/127.0.0.1, port: 52776
I/BtToRequestSocket( 2952): --DoOneRunRound ended
,I/jxcore-log( 2952): 2015-11-25T09:34:15.179Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:15.624Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:15.652Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:15.661Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:15.670Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:15.699Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:15.709Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:15.743Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:15.781Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:15.789Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:15.798Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:15.841Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:15.879Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:15.890Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:15.932Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:15.941Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:15.982Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:16.018Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:16.025Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:16.031Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:16.040Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:16.073Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:16.111Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:16.118Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:16.145Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:16.154Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:16.187Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:16.220Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:16.238Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:16.265Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:16.283Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:16.320Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:16.327Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:16.335Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:16.344Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:16.385Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:16.418Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:16.430Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:16.470Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:16.486Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:16.519Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:16.531Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:16.536Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:16.566Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:16.582Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:16.612Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:16.644Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:16.728Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:16.734Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2952): 
,W/bt-btif ( 3010): invalid rfc slot id: 44
,I/BtToSocketBase( 2952): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2952): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2952): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT8406
I/BtToSocketBase( 2952): Stop ReceivingThread
I/BtToSocketBase( 2952): Stop SendingThread
I/BtToSocketBase( 2952): Close local in
I/BtToSocketBase( 2952): Close LocalOutputStream
I/BtToSocketBase( 2952): Close localHostSocket
I/BtToSocketBase( 2952): Close bt in
I/BtToSocketBase( 2952): Close bt out
I/BtToSocketBase( 2952): Close bt socket
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2952): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2952): 2015-11-25T09:34:16.799Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2952): 
,W/bt-rfcomm( 3010): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 3010): RFCOMM_DisconnectInd LCID:0x47
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: HTC Desire 820
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0x22  CID 0x44
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:51, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 51
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:34:29.982Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:34:29.983Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:34:29.983Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:34.985Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:34:34.985Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: HTC Desire 820
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2952): we got incoming connection
I/BTHandshakeSocketThread( 2952): Creating BTHandshakeSocketThread
I/BTListenerThread( 2952): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread started
,I/BTListenerThread( 2952): got MESSAGE_READ 84 bytes.
I/BTListenerThread( 2952): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3716"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2952): MESSAGE_WRITE 77 bytes.
I/HS      ( 2952): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT3716
I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2952): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT3716
I/BtToSocketBase( 2952): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2952): Creating BTConnectedThread
I/BtConnectorHelper( 2952): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2952): --DoOneRunRound started
,I/BtToRequestSocket( 2952): LocalHost address: localhost/127.0.0.1, port: 52776
I/BtToRequestSocket( 2952): --DoOneRunRound ended
,I/jxcore-log( 2952): 2015-11-25T09:34:37.657Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:38.064Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:38.072Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:38.085Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:38.129Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:38.136Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:38.151Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:38.179Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:38.194Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:38.228Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:38.245Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:38.258Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:38.294Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:38.304Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:38.310Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:38.340Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:38.349Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:38.392Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:38.409Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:38.416Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:38.448Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:38.465Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2952): 
,W/bt-btif ( 3010): invalid rfc slot id: 52
,I/BtToSocketBase( 2952): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2952): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2952): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT3716
,I/BtToSocketBase( 2952): Stop ReceivingThread
I/BtToSocketBase( 2952): Stop SendingThread
I/BtToSocketBase( 2952): Close local in
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2952): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2952): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT3716
I/BtToSocketBase( 2952): Close LocalOutputStream
,I/BtToSocketBase( 2952): Close localHostSocket
I/BtToSocketBase( 2952): Close bt in
I/BtToSocketBase( 2952): Close bt out
I/BtToSocketBase( 2952): Close bt socket
,I/BtToSocketBase( 2952): Close bt in
I/BtToSocketBase( 2952): Close bt out
I/BtToSocketBase( 2952): Close bt socket
,I/jxcore-log( 2952): 2015-11-25T09:34:38.580Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2952): 
,W/bt-rfcomm( 3010): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
W/bt-rfcomm( 3010): RFCOMM_DisconnectInd LCID:0x46
,I/jxcore-log( 2952): 2015-11-25T09:34:39.988Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:34:39.989Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:34:39.990Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:34:39.990Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 2952): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: HTC Desire 820
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0x10  CID 0x45
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:54, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 54
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:34:46.323Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:34:46.324Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:34:46.324Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:51.325Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:34:51.326Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:56.335Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:34:56.336Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:34:56.336Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:34:56.342Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 2952): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,I/        ( 2952): Cleared service requests
,I/        ( 2952): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2952): Found 1 peers.
I/SS      ( 2952): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2952): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2952): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2952): Started service discovery
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2952): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8206","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8206","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8206, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8206, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 2952): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT124"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT124"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT124, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT124, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 2952): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7055","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7055","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT7055, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT7055, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 2952): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5918","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5918","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT5918, peerAddress: 58:3F:54:73:64:C0
,I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT5918, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0x22  CID 0x49
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:55, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 55
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2952): 2015-11-25T09:35:27.408Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:35:27.409Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:35:27.409Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,I/        ( 2952): Cleared service requests
I/        ( 2952): Started peer discovery
,I/jxcore-log( 2952): 2015-11-25T09:35:32.418Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:35:32.419Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2952): Found 5 peers.
I/SS      ( 2952): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2952): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2952): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2952): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2952): Peer(5): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 2952): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2952): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2952): Started service discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2952): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2740","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2740","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT2740, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT2740, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 2952): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT8406"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT8406"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT8406, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT8406, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/jxcore-log( 2952): 2015-11-25T09:35:37.423Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:35:37.424Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:35:37.428Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:35:37.432Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 2952): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 2952): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8206","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8206","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8206, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8206, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0x10  CID 0x4b
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:56, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 56
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2952): 2015-11-25T09:35:43.843Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:35:43.844Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:35:43.845Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,I/        ( 2952): Cleared service requests
I/        ( 2952): Started peer discovery
,I/jxcore-log( 2952): 2015-11-25T09:35:48.846Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:35:48.847Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2952): Found 8 peers.
I/SS      ( 2952): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2952): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2952): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2952): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2952): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 2952): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2952): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2952): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2952): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2952): Added service request
,I/jxcore-log( 2952): 2015-11-25T09:35:53.849Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:35:53.849Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:35:53.849Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:35:53.851Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 2952): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2952): Started service discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f8:95:c7:87:85:54]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: G3s-1
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:57, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 57
I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2952): 2015-11-25T09:35:55.508Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:35:55.508Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:35:55.509Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:35:55.509Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): ---- round done--------
I/jxcore-log( 2952): 
I/jxcore-log( 2952): ---- gotta redo : F8:95:C7:87:85:54, try count now: 1
I/jxcore-log( 2952): 
I/jxcore-log( 2952): do fake peer & start
I/jxcore-log( 2952): 
I/jxcore-log( 2952): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:35:55.509Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:35:55.509Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:35:55.510Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2952): Connecting to null, at 34:FC:EF:11:B1:66
I/chromium( 2952): [INFO:CONSOLE(63)] "logCallback round[0] time: 117022 ms, rnd: 5, ex: Connection to F8:95:C7:87:85:54 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [34:fc:ef:11:b1:66]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/        ( 2952): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2740","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2740","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT2740, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT2740, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e527ac rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:58, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 58
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:35:58.382Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:35:58.383Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:35:58.383Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: G3s-1
,I/        ( 2952): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT8406"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT8406"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT8406, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT8406, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 2952): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8206","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8206","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8206, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8206, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2952): 2015-11-25T09:36:03.384Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:36:03.385Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
,I/        ( 2952): Cleared service requests
I/        ( 2952): Started peer discovery
,I/jxcore-log( 2952): 2015-11-25T09:36:08.391Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:36:08.391Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:36:08.392Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:36:08.392Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2952): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [34:fc:ef:11:b1:66]: 6, f, 410d
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:59, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 59
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2952): 2015-11-25T09:36:08.962Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:36:08.962Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:36:08.963Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2952): Found 9 peers.
I/SS      ( 2952): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2952): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2952): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2952): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2952): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 2952): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2952): Peer(7): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2952): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2952): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2952): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2952): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 2952): Started service discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2952): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8656","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8656","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT8656, peerAddress: F8:CF:C5:D9:E5:61
,I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT8656, WifiDirectName: Android_50a5, WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,I/jxcore-log( 2952): 2015-11-25T09:36:13.965Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:36:13.966Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
,I/        ( 2952): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2740","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2740","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT2740, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT2740, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 2952): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT8406"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT8406"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT8406, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT8406, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 2952): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8206","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 2952): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8206","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8206, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8206, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/jxcore-log( 2952): 2015-11-25T09:36:18.969Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:36:18.969Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:36:18.970Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:36:18.970Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2952): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:60, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 60
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:36:19.581Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:36:19.581Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:36:19.582Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,I/        ( 2952): Cleared service requests
I/        ( 2952): Started peer discovery
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2952): 2015-11-25T09:36:24.582Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:36:24.583Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2952): Found 9 peers.
I/SS      ( 2952): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2952): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2952): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2952): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2952): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 2952): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2952): Peer(7): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2952): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2952): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2952): Ignored { when=-6ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2952): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2952): Started service discovery
,I/        ( 2952): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8656","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8656","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT8656, peerAddress: F8:CF:C5:D9:E5:61
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT8656, WifiDirectName: Android_50a5, WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,I/jxcore-log( 2952): 2015-11-25T09:36:29.587Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:36:29.588Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:36:29.588Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:36:29.589Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2952): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:61, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 61
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2952): 2015-11-25T09:36:32.000Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:36:32.001Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:36:32.002Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/        ( 2952): Cleared service requests
I/        ( 2952): Started peer discovery
,I/jxcore-log( 2952): 2015-11-25T09:36:37.004Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:36:37.005Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [58:3f:54:73:64:c0]: 6, f, 6109
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: G3-1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2952): Found 9 peers.
I/SS      ( 2952): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2952): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2952): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2952): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2952): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 2952): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2952): Peer(7): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2952): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2952): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2952): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2952): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2952): 2015-11-25T09:36:42.011Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:36:42.012Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:36:42.019Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:36:42.020Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2952): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e5241c rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2952): Started service discovery
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e527ac rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:62, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 62
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:36:44.050Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:36:44.050Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:36:44.066Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:36:44.071Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): ---- round done--------
I/jxcore-log( 2952): 
I/jxcore-log( 2952): ---- gotta redo : 34:FC:EF:11:B1:66, try count now: 2
I/jxcore-log( 2952): 
I/jxcore-log( 2952): do fake peer & start
I/jxcore-log( 2952): 
I/jxcore-log( 2952): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:36:44.073Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:36:44.074Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:36:44.074Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2952): Connecting to null, at 00:F4:6F:30:E0:6C
I/chromium( 2952): [INFO:CONSOLE(63)] "logCallback round[0] time: 48542 ms, rnd: 5, ex: Connection to 34:FC:EF:11:B1:66 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2952): Starting to connect
,W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [00:f4:6f:30:e0:6c]: 6, f, 4106
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e52d04 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:63, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 63
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2952): 2015-11-25T09:36:45.956Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:36:45.957Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:36:45.958Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e5241c rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2952): 2015-11-25T09:36:50.960Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:36:50.960Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:36:55.963Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:36:55.964Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:36:55.965Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:36:55.965Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2952): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e5241c rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [00:f4:6f:30:e0:6c]: 6, f, 6109
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e52d04 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:64, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 64
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2952): 2015-11-25T09:36:57.876Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:36:57.877Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:36:57.877Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2952): 2015-11-25T09:37:02.879Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:37:02.879Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:07.882Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:37:07.883Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:37:07.883Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:37:07.884Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2952): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f8:95:c7:87:3c:51]: 6, f, 410d
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: G4-1
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e5241c rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e52b3c rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e5241c rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e52d04 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:65, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 65
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:37:11.403Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:37:11.404Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:37:11.404Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3010): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3010): Entering PendingCommandState State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3010): Failed to remove device: F8:95:C7:87:3C:51
I/BluetoothBondStateMachine( 3010): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3010): StableState(): Entering Off State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e52b3c rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2952): 2015-11-25T09:37:16.406Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:37:16.407Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2952): we got incoming connection
I/BTHandshakeSocketThread( 2952): Creating BTHandshakeSocketThread
I/BTListenerThread( 2952): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread started
,I/BTListenerThread( 2952): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 2952): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8316","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2952): MESSAGE_WRITE 77 bytes.
I/HS      ( 2952): Incoming connection Hand Shake finished for : LGE-LG-H815_PT8316
I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2952): Starting the connected thread incoming : true, LGE-LG-H815_PT8316
,I/BtToSocketBase( 2952): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2952): Creating BTConnectedThread
,I/BtConnectorHelper( 2952): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2952): --DoOneRunRound started
,I/BtToRequestSocket( 2952): LocalHost address: localhost/127.0.0.1, port: 52776
,I/jxcore-log( 2952): 2015-11-25T09:37:17.035Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2952): 
,I/BtToRequestSocket( 2952): --DoOneRunRound ended
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2952): 2015-11-25T09:37:17.583Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:17.596Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:17.871Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:18.295Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:18.341Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:18.353Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:18.473Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:18.508Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:18.533Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:18.540Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:18.943Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:18.955Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:19.196Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:19.201Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:19.262Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:19.401Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:19.407Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:19.441Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:19.478Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:19.486Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:19.495Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:19.531Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:19.560Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 2952): 
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/jxcore-log( 2952): 2015-11-25T09:37:19.602Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:19.640Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:19.654Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:19.690Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:19.701Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:19.724Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:19.734Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:19.776Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:19.808Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:19.829Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:19.840Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:19.880Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:19.904Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2952): 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e52b3c rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3010): invalid rfc slot id: 53
,I/BtToSocketBase( 2952): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2952): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2952): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT8316
I/BtToSocketBase( 2952): Stop ReceivingThread
I/BtToSocketBase( 2952): Stop SendingThread
I/BtToSocketBase( 2952): Close local in
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 2952): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 2952): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT8316
I/BtToSocketBase( 2952): Close LocalOutputStream
,I/BtToSocketBase( 2952): Close localHostSocket
I/BtToSocketBase( 2952): Close bt in
,I/BtToSocketBase( 2952): Close bt out
I/BtToSocketBase( 2952): Close bt socket
,I/BtToSocketBase( 2952): Close bt in
I/BtToSocketBase( 2952): Close bt out
I/BtToSocketBase( 2952): Close bt socket
,I/jxcore-log( 2952): 2015-11-25T09:37:20.234Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2952): 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e52b3c rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3010): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
W/bt-rfcomm( 3010): RFCOMM_DisconnectInd LCID:0x44
,I/jxcore-log( 2952): 2015-11-25T09:37:21.410Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:37:21.411Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:37:21.411Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:21.412Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2952): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e5241c rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e52b3c rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: G4-1
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [00:f4:6f:30:e0:6c]: 7, f, 6109
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:67, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 67
I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:37:24.363Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:37:24.363Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:37:24.363Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e5241c rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2952): 2015-11-25T09:37:29.364Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:37:29.364Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:34.368Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:37:34.369Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:37:34.369Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:37:34.370Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2952): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:68, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 68
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:37:36.054Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:37:36.055Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:36.073Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:37:36.075Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): ---- round done--------
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): ---- gotta redo : 00:F4:6F:30:E0:6C, try count now: 2
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): do fake peer & start
I/jxcore-log( 2952): 
I/jxcore-log( 2952): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:36.086Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:36.090Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:36.093Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 2952): Connecting to null, at 44:80:EB:7B:5A:05
I/chromium( 2952): [INFO:CONSOLE(63)] "logCallback round[0] time: 51981 ms, rnd: 5, ex: Connection to 00:F4:6F:30:E0:6C failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e5241c rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: G3-1
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:69, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 69
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2952): 2015-11-25T09:37:41.266Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:41.269Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:41.272Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,I/        ( 2952): Cleared service requests
I/        ( 2952): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 2952): Found 7 peers.
I/SS      ( 2952): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2952): Peer(2): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2952): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2952): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2952): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2952): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2952): Peer(7): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 2952): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2952): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2952): Started service discovery
,I/jxcore-log( 2952): 2015-11-25T09:37:46.277Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:46.278Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,I/jxcore-log( 2952): 2015-11-25T09:37:51.285Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:37:51.286Z SendDataConnector.js: Connect (retry count 1) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:51.286Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:37:51.290Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 2952): Connecting to null, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 2952): Starting to connect
,W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:70, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 70
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:37:51.620Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:37:51.620Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:37:51.621Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2952): 2015-11-25T09:37:56.622Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:37:56.622Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:38:01.622Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:38:01.623Z SendDataConnector.js: Connect (retry count 2) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:38:01.623Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:38:01.623Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 2952): Connecting to null, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:71, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 71
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:38:01.857Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:38:01.858Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:38:01.858Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2952): 2015-11-25T09:38:06.859Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:38:06.859Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:38:11.859Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:38:11.859Z SendDataConnector.js: Connect (retry count 3) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:38:11.859Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:38:11.859Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 2952): Connecting to null, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 2952): Starting to connect
,W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:72, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 72
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:38:12.095Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:38:12.095Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:38:12.096Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2952): 2015-11-25T09:38:17.096Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:38:17.096Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:38:22.097Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:38:22.097Z SendDataConnector.js: Connect (retry count 4) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:38:22.097Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:38:22.097Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 2952): Connecting to null, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 2952): Starting to connect
,W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:73, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 73
I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2952): 2015-11-25T09:38:22.331Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:38:22.332Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:38:22.343Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:38:22.345Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
I/jxcore-log( 2952): ---- round done--------
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): ---- gotta redo : 44:80:EB:7B:5A:05, try count now: 2
I/jxcore-log( 2952): 
I/jxcore-log( 2952): do fake peer & start
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): Connect to fake peer: F8:95:C7:87:85:54
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:38:22.352Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:38:22.355Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:38:22.355Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 2952): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/chromium( 2952): [INFO:CONSOLE(63)] "logCallback round[0] time: 46242 ms, rnd: 5, ex: Connection to 44:80:EB:7B:5A:05 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: G3s-1
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:74, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 74
I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:38:23.029Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:38:23.029Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:38:23.029Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: G3s-1
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: XT1039
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2952): we got incoming connection
I/BTHandshakeSocketThread( 2952): Creating BTHandshakeSocketThread
I/BTListenerThread( 2952): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread started
,I/BTListenerThread( 2952): got MESSAGE_READ 80 bytes.
I/BTListenerThread( 2952): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT124"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2952): MESSAGE_WRITE 77 bytes.
I/HS      ( 2952): Incoming connection Hand Shake finished for : motorola-XT1039_PT124
,I/BtConnectorHelper( 2952): Starting the connected thread incoming : true, motorola-XT1039_PT124
I/BtToSocketBase( 2952): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2952): Creating BTConnectedThread
I/BtConnectorHelper( 2952): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2952): --DoOneRunRound started
,I/BtToRequestSocket( 2952): LocalHost address: localhost/127.0.0.1, port: 52776
,I/jxcore-log( 2952): 2015-11-25T09:38:26.926Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2952): 
,I/BtToRequestSocket( 2952): --DoOneRunRound ended
,I/jxcore-log( 2952): 2015-11-25T09:38:27.334Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:38:27.338Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:38:27.342Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:38:27.346Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:38:27.347Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:38:27.352Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:38:27.355Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:38:27.391Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:38:27.400Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:38:27.442Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:38:27.453Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:38:27.493Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:38:27.503Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:38:27.542Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:38:27.554Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:38:27.584Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:38:27.620Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:38:27.632Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:38:27.671Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:38:27.690Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:38:27.718Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2952): 
,W/bt-btif ( 3010): invalid rfc slot id: 66
,I/BtToSocketBase( 2952): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2952): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2952): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT124
I/BtToSocketBase( 2952): Stop ReceivingThread
I/BtToSocketBase( 2952): Stop SendingThread
I/BtToSocketBase( 2952): Close local in
I/BtToSocketBase( 2952): Close LocalOutputStream
I/BtToSocketBase( 2952): Close localHostSocket
I/BtToSocketBase( 2952): Close bt in
I/BtToSocketBase( 2952): Close bt out
I/BtToSocketBase( 2952): Close bt socket
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2952): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2952): 2015-11-25T09:38:27.806Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:38:28.031Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:38:28.032Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
,W/bt-rfcomm( 3010): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
W/bt-rfcomm( 3010): RFCOMM_DisconnectInd LCID:0x4c
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: XT1039
,I/jxcore-log( 2952): 2015-11-25T09:38:33.035Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:38:33.035Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:38:33.036Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:38:33.036Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 2952): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f8:95:c7:87:85:54]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: G3s-1
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:76, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 76
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:38:34.078Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:38:34.078Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:38:34.078Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/UsageStatsService(  760): User[0] Flushing usage stats to disk
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: G3s-1
,I/jxcore-log( 2952): 2015-11-25T09:38:39.080Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:38:39.081Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
,I/        ( 2952): Cleared service requests
I/        ( 2952): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2952): Found 5 peers.
I/SS      ( 2952): Peer(1): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2952): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2952): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2952): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2952): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 2952): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2952): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 2952): Started service discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2952): 2015-11-25T09:38:44.085Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:38:44.086Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:38:44.086Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:38:44.090Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 2952): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: G3s-1
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:77, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 77
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:38:44.683Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:38:44.684Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:38:44.684Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,I/        ( 2952): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2740","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2740","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT2740, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT2740, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 2952): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT124"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT124"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT124, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT124, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: G3s-1
,I/art     (  760): Explicit concurrent mark sweep GC freed 58922(2MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 28MB/42MB, paused 1.094ms total 98.216ms
,I/jxcore-log( 2952): 2015-11-25T09:38:49.684Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:38:49.685Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,I/        ( 2952): Cleared service requests
I/        ( 2952): Started peer discovery
,I/jxcore-log( 2952): 2015-11-25T09:38:54.689Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:38:54.689Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:38:54.690Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:38:54.690Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 2952): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: G3s-1
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:78, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 78
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2952): 2015-11-25T09:38:55.223Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:38:55.223Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:38:55.223Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2952): Found 5 peers.
I/SS      ( 2952): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2952): Peer(2): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2952): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2952): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2952): Peer(5): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 2952): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2952): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: G3s-1
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2952): Started service discovery
,I/        ( 2952): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4529"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4529"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4529, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4529, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 2952): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2740","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2740","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT2740, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT2740, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 2952): 2015-11-25T09:39:00.223Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:39:00.224Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
,I/        ( 2952): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT124"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT124"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT124, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT124, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 2952): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3716"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3716"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT3716, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT3716, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/jxcore-log( 2952): 2015-11-25T09:39:05.226Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:39:05.228Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:39:05.229Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:39:05.229Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 2952): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: G3s-1
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:79, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 79
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2952): 2015-11-25T09:39:06.653Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:39:06.653Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:39:06.655Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:39:06.657Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): ---- round done--------
I/jxcore-log( 2952): 
I/jxcore-log( 2952): ---- gotta redo : F8:95:C7:87:85:54, try count now: 2
I/jxcore-log( 2952): 
I/jxcore-log( 2952): do fake peer & start
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:39:06.658Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:39:06.658Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:39:06.659Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2952): Connecting to null, at 34:FC:EF:11:B1:66
,I/chromium( 2952): [INFO:CONSOLE(63)] "logCallback round[0] time: 44298 ms, rnd: 5, ex: Connection to F8:95:C7:87:85:54 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [34:fc:ef:11:b1:66]: 6, f, 410d
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e527ac rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:80, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 80
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:39:07.944Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:39:07.944Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:39:07.945Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/        ( 2952): Cleared service requests
I/        ( 2952): Started peer discovery
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: G3s-1
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 2952): Found 6 peers.
I/SS      ( 2952): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2952): Peer(2): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2952): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2952): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2952): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2952): Peer(6): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 2952): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2952): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2952): 2015-11-25T09:39:12.948Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:39:12.949Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2952): Started service discovery
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2952): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4529"}, typeCordovap2p._tcp.local.:
,I/        ( 2952): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4529"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4529, peerAddress: 34:FC:EF:9D:93:0B
,I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4529, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 2952): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2740","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2740","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT2740, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT2740, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 2952): 2015-11-25T09:39:17.951Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:39:17.952Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:39:17.952Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:39:17.953Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2952): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [34:fc:ef:11:b1:66]: 6, f, 410d
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:81, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 81
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:39:19.771Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:39:19.772Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:39:19.772Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,I/        ( 2952): Cleared service requests
I/        ( 2952): Started peer discovery
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2952): 2015-11-25T09:39:24.774Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:39:24.774Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2952): Found 6 peers.
I/SS      ( 2952): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2952): Peer(2): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2952): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2952): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2952): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2952): Peer(6): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 2952): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2952): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2952): Started service discovery
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 2952): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4529"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4529"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4529, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4529, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/jxcore-log( 2952): 2015-11-25T09:39:29.778Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:39:29.779Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:39:29.779Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:39:29.780Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2952): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2952): Starting to connect
,W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:82, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 82
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2952): 2015-11-25T09:39:30.932Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:39:30.932Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:39:30.933Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,I/        ( 2952): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT124"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT124"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT124, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT124, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2952): 2015-11-25T09:39:35.935Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:39:35.936Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
,I/        ( 2952): Cleared service requests
I/        ( 2952): Started peer discovery
,I/jxcore-log( 2952): 2015-11-25T09:39:40.940Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:39:40.940Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:39:40.941Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:39:40.941Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2952): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:83, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 83
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:39:41.680Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:39:41.681Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:39:41.681Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2952): Found 6 peers.
I/SS      ( 2952): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2952): Peer(2): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2952): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2952): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2952): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2952): Peer(6): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 2952): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2952): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2952): Started service discovery
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2952): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8316","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8316","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT8316, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT8316, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2952): 2015-11-25T09:39:46.682Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:39:46.683Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
,I/        ( 2952): Cleared service requests
I/        ( 2952): Started peer discovery
,I/jxcore-log( 2952): 2015-11-25T09:39:51.687Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:39:51.688Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:39:51.689Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:39:51.689Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2952): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:84, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 84
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:39:52.720Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:39:52.721Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:39:52.741Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:39:52.744Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): ---- round done--------
I/jxcore-log( 2952): 
I/jxcore-log( 2952): ---- gotta redo : 34:FC:EF:11:B1:66, try count now: 3
I/jxcore-log( 2952): 
I/jxcore-log( 2952): do fake peer & start
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:39:52.751Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:39:52.754Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:39:52.757Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2952): Connecting to null, at 00:F4:6F:30:E0:6C
,I/chromium( 2952): [INFO:CONSOLE(63)] "logCallback round[0] time: 46063 ms, rnd: 5, ex: Connection to 34:FC:EF:11:B1:66 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [00:f4:6f:30:e0:6c]: 6, f, 6109
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:85, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 85
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:39:53.472Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:39:53.473Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:39:53.474Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e52d04 rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2952): Found 7 peers.
I/SS      ( 2952): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2952): Peer(2): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2952): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2952): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2952): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2952): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2952): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2952): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2952): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/        ( 2952): Started service discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2952): 2015-11-25T09:39:58.474Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:39:58.475Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2952): 2015-11-25T09:40:03.478Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:40:03.479Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:40:03.479Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:40:03.480Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2952): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [00:f4:6f:30:e0:6c]: 6, f, 6109
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:86, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 86
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:40:04.105Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:40:04.106Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:40:04.110Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2952): 2015-11-25T09:40:09.113Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:40:09.114Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:40:14.119Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:40:14.120Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:40:14.120Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:40:14.121Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2952): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:87, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 87
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:40:14.860Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:40:14.860Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:40:14.861Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2952): 2015-11-25T09:40:19.862Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:40:19.863Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/jxcore-log( 2952): 2015-11-25T09:40:24.866Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:40:24.867Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:40:24.867Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:40:24.868Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2952): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:88, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 88
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:40:26.493Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:40:26.494Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:40:26.494Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2952): 2015-11-25T09:40:31.496Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:40:31.501Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:40:36.508Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:40:36.509Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:40:36.509Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:40:36.510Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2952): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:89, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 89
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:40:37.042Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:40:37.042Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:40:37.059Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:40:37.061Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2952): 
I/jxcore-log( 2952): ---- round done--------
I/jxcore-log( 2952): 
I/jxcore-log( 2952): ---- gotta redo : 00:F4:6F:30:E0:6C, try count now: 3
I/jxcore-log( 2952): 
I/jxcore-log( 2952): do fake peer & start
I/jxcore-log( 2952): 
I/jxcore-log( 2952): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:40:37.064Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:40:37.064Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:40:37.065Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 2952): Connecting to null, at 44:80:EB:7B:5A:05
I/chromium( 2952): [INFO:CONSOLE(63)] "logCallback round[0] time: 44289 ms, rnd: 5, ex: Connection to 00:F4:6F:30:E0:6C failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e52d04 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e52d04 rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:90, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 90
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2952): 2015-11-25T09:40:42.418Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:40:42.418Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:40:42.419Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:40:47.420Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:40:47.421Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/jxcore-log( 2952): 2015-11-25T09:40:52.425Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:40:52.425Z SendDataConnector.js: Connect (retry count 1) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:40:52.426Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:40:52.431Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 2952): Connecting to null, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [44:80:eb:7b:5a:05]: 6, f, 410d
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:91, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 91
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:40:53.381Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:40:53.382Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:40:53.382Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [08:ec:a9:50:75:41]: 6, f, 410d
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: A3-1
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2952): we got incoming connection
I/BTHandshakeSocketThread( 2952): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2952): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread started
,I/BTListenerThread( 2952): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 2952): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7055","ra":"08:EC:A9:50:75:41"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 2952): MESSAGE_WRITE 77 bytes.
I/HS      ( 2952): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT7055
I/BTHandshakeSocketThread( 2952): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2952): Starting the connected thread incoming : true, samsung-SM-A300FU_PT7055
I/BtToSocketBase( 2952): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2952): Creating BTConnectedThread
I/BtConnectorHelper( 2952): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 2952): --DoOneRunRound started
,I/BtToRequestSocket( 2952): LocalHost address: localhost/127.0.0.1, port: 52776
I/BtToRequestSocket( 2952): --DoOneRunRound ended
,I/jxcore-log( 2952): 2015-11-25T09:40:55.717Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2952): 
,I/        ( 2952): Cleared service requests
I/        ( 2952): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e52ecc rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2952): 2015-11-25T09:40:56.273Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:40:56.357Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:40:56.369Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:40:56.401Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:40:56.439Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 2952): 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2952): Found 5 peers.
I/SS      ( 2952): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2952): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 2952): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2952): Peer(4): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 2952): Peer(5): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 2952): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2952): Added service request
,I/jxcore-log( 2952): 2015-11-25T09:40:56.591Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:40:56.632Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 2952): 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2952): 2015-11-25T09:40:56.794Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 2952): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2952): 2015-11-25T09:40:56.820Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:40:56.841Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:40:56.921Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:40:56.928Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:40:56.934Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:40:56.945Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:40:56.978Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:40:56.995Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 2952): 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2952): 2015-11-25T09:40:57.057Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:40:57.079Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:40:57.106Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:40:57.139Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:40:57.165Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:40:57.253Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 2952): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2952): 2015-11-25T09:40:57.315Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:40:57.319Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:40:57.321Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:40:57.370Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:40:57.407Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2952): 
,I/        ( 2952): Started service discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e52254 rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2952): 2015-11-25T09:40:58.383Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:40:58.384Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
,W/bt-btif ( 3010): invalid rfc slot id: 75
,I/BtToSocketBase( 2952): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2952): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2952): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT7055
I/BtToSocketBase( 2952): Stop ReceivingThread
I/BtToSocketBase( 2952): Stop SendingThread
I/BtToSocketBase( 2952): Close local in
I/BtToSocketBase( 2952): Close LocalOutputStream
I/BtToSocketBase( 2952): Close localHostSocket
I/BtToSocketBase( 2952): Close bt in
I/BtToSocketBase( 2952): Close bt out
I/BtToSocketBase( 2952): Close bt socket
,I/BtToSocketBase( 2952): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2952): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2952): 2015-11-25T09:40:58.457Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2952): 
,W/bt-rfcomm( 3010): rfc_find_lcid_mcb LCID reused LCID:0x40 current:0x0
W/bt-rfcomm( 3010): RFCOMM_DisconnectInd LCID:0x40
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: A3-1
,I/jxcore-log( 2952): 2015-11-25T09:41:03.388Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:41:03.389Z SendDataConnector.js: Connect (retry count 2) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:41:03.389Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:41:03.389Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 2952): Connecting to null, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:93, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 93
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:41:03.613Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:41:03.613Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:41:03.614Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e52ecc rs_disc_pending=0
E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2952): 2015-11-25T09:41:08.615Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:41:08.616Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:41:13.621Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:41:13.621Z SendDataConnector.js: Connect (retry count 3) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:41:13.621Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:41:13.621Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 2952): Connecting to null, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 2952): Starting to connect
,W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0x8  CID 0x47
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:94, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 94
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2952): 2015-11-25T09:41:44.480Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:41:44.480Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:41:44.481Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:41:49.482Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:41:49.482Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:41:54.485Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:41:54.486Z SendDataConnector.js: Connect (retry count 4) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:41:54.494Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:41:54.495Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 2952): Connecting to null, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 2952): Cleared service requests
I/        ( 2952): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2952): Found 6 peers.
I/SS      ( 2952): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2952): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2952): Peer(3): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2952): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2952): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2952): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2952): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2952): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2952): Started service discovery
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0x8  CID 0x42
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:95, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 95
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2952): 2015-11-25T09:42:25.416Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:42:25.419Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:42:25.440Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:42:25.443Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2952): 
I/jxcore-log( 2952): ---- round done--------
I/jxcore-log( 2952): 
I/jxcore-log( 2952): ---- gotta redo : 44:80:EB:7B:5A:05, try count now: 3
I/jxcore-log( 2952): 
I/jxcore-log( 2952): do fake peer & start
I/jxcore-log( 2952): 
I/jxcore-log( 2952): Connect to fake peer: F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:42:25.445Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:42:25.446Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:42:25.452Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 2952): Connecting to G3s-1, at F8:95:C7:87:85:54
I/chromium( 2952): [INFO:CONSOLE(63)] "logCallback round[0] time: 108358 ms, rnd: 5, ex: Connection to 44:80:EB:7B:5A:05 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2952): Starting to connect
,W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f8:95:c7:87:85:54]: 6, 1d, 7d3
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:96, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 96
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2952): 2015-11-25T09:42:26.399Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:42:26.400Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:42:26.401Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: G3s-1
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=0
E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: G3s-1
,I/jxcore-log( 2952): 2015-11-25T09:42:31.401Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:42:31.402Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:42:36.405Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:42:36.406Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:42:36.406Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:42:36.410Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 2952): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/BTConnectToThread( 2952): Starting to connect
,W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:97, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 97
I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:42:36.862Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:42:36.862Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:42:36.862Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
I/BluetoothClassifier( 1328): Bluetooth Device Name: G3s-1
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: G3s-1
,I/jxcore-log( 2952): 2015-11-25T09:42:41.864Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:42:41.864Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:42:46.872Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:42:46.873Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:42:46.874Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:42:46.874Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 2952): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: G3s-1
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:98, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 98
I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:42:47.631Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:42:47.631Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:42:47.631Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: G3s-1
,I/jxcore-log( 2952): 2015-11-25T09:42:52.631Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:42:52.632Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:42:57.635Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:42:57.635Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:42:57.636Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:42:57.636Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 2952): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 2952): Cleared service requests
I/        ( 2952): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: G3s-1
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:99, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 99
I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2952): 2015-11-25T09:42:58.767Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:42:58.767Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:42:58.768Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2952): Found 1 peers.
I/SS      ( 2952): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2952): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2952): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2952): Started service discovery
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 2952): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT124"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT124"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT124, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT124, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 2952): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4529"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4529"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4529, peerAddress: 34:FC:EF:9D:93:0B
,I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4529, WifiDirectName: , WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: G3s-1
,I/jxcore-log( 2952): 2015-11-25T09:43:03.769Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:43:03.770Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:43:08.772Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:43:08.773Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:43:08.773Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:43:08.774Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 2952): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: G3s-1
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:100, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 100
I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:43:09.049Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:43:09.049Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:43:09.051Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:43:09.053Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2952): 
I/jxcore-log( 2952): ---- round done--------
I/jxcore-log( 2952): 
I/jxcore-log( 2952): ---- gotta redo : F8:95:C7:87:85:54, try count now: 3
I/jxcore-log( 2952): 
I/jxcore-log( 2952): do fake peer & start
I/jxcore-log( 2952): 
I/jxcore-log( 2952): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:43:09.054Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:43:09.054Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:43:09.054Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2952): Connecting to null, at 34:FC:EF:11:B1:66
,I/chromium( 2952): [INFO:CONSOLE(63)] "logCallback round[0] time: 43603 ms, rnd: 5, ex: Connection to F8:95:C7:87:85:54 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2952): Starting to connect
,W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 2952): Cleared service requests
,I/        ( 2952): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2952): Found 3 peers.
I/SS      ( 2952): Peer(1): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2952): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2952): Peer(3): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 2952): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2952): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1328): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1328): Bluetooth Device Name: G3s-1
,I/        ( 2952): Started service discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2952): timeout now
I/jxcore-log( 2952): 
I/jxcore-log( 2952): dun
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): weAreDoneNow , resultArray.length: 15
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): done, now sending data to server
I/jxcore-log( 2952): 
I/jxcore-log( 2952): DBG, CoordinatorConnector sendData called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): -- RESULT DATA {"name:":"LGE-Nexus 5_PT3721","time":1000071,"result":"TIMEOUT","sendList":[{"name":"B4:CE:F6:AB:A4:6A","time":29087,"result":"OK","connections":3,"tryCount":1},{"name":"7C:F9:0E:34:8A:A0","time":8097,"result":"OK","connections":1,"tryCount":1},{"name":"7C:F9:0E:37:96:AB","time":87524,"result":"OK","connections":4,"tryCount":1},{"name":"08:EC:A9:50:76:27","time":3954,"result":"OK","connections":1,"tryCount":1},{"name":"58:2A:F7:ED:96:BE","time":2905,"result":"OK","connections":1,"tryCount":1},{"name":"F4:F1:E1:5C:3B:E2","time":27669,"result":"OK","connections":2,"tryCount":1},{"name":"80:01:84:8A:B3:68","time":5475,"result":"OK","connections":1,"tryCount":1},{"name":"50:2E:6C:AC:21:50","time":35440,"result":"OK","connections":3,"tryCount":1},{"name":"F8:CF:C5:D9:E5:61","time":22682,"result":"OK","connections":2,"tryCount":1},{"name":"08:EC:A9:50:75:41","time":23190,"result":"OK","connections":1,"tryCount":1},{"name":"58:3F:54:73:64:C0","time":10308,"result":"OK","connections":1,"tryCount":1},{
I/jxcore-log( 2952): sendList : 100% : 87524 ms, 99% : 87524 ms, 95 : 35440 ms, 90% : 35440 ms.
I/jxcore-log( 2952): 
I/jxcore-log( 2952): Result count 15, range 2905 ms to  87524 ms.
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): sendList failed peers count : 4 [21.05263157894737 %]
I/jxcore-log( 2952): 
I/jxcore-log( 2952): - Peer ID : 34:FC:EF:11:B1:66, Tried : 4
I/jxcore-log( 2952): 
I/jxcore-log( 2952): - Peer ID : 00:F4:6F:30:E0:6C, Tried : 3
I/jxcore-log( 2952): 
I/jxcore-log( 2952): - Peer ID : 44:80:EB:7B:5A:05, Tried : 3
I/jxcore-log( 2952): 
I/jxcore-log( 2952): - Peer ID : F8:95:C7:87:85:54, Tried : 3
I/jxcore-log( 2952): 
I/jxcore-log( 2952): sendList never tried peers count : 0 [0 %]
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:43:29.808Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:43:29.809Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
,I/chromium( 2952): [INFO:CONSOLE(63)] "logCallback *** TIMEOUT ***", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 2952): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0x8  CID 0x4b
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:101, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 101
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:44:00.718Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:44:00.719Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:44:00.719Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:44:05.721Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:44:05.721Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:44:10.724Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:44:10.725Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:44:10.725Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:44:10.726Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2952): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [34:fc:ef:11:b1:66]: 6, f, 410d
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:102, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 102
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:44:12.082Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:44:12.083Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:44:12.084Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,I/        ( 2952): Cleared service requests
I/        ( 2952): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2952): Found 4 peers.
I/SS      ( 2952): Peer(1): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2952): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2952): Peer(3): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2952): Peer(4): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 2952): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2952): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2952): Started service discovery
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2952): 2015-11-25T09:44:17.084Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:44:17.085Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:44:22.086Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:44:22.086Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:44:22.086Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:44:22.086Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2952): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:103, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 103
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:44:22.451Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:44:22.452Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:44:22.452Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2952): 2015-11-25T09:44:27.453Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:44:27.453Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:44:32.453Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:44:32.453Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:44:32.453Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:44:32.453Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2952): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2952): Starting to connect
,W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:104, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 104
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:44:32.671Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:44:32.672Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:44:32.673Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2952): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2952): 2015-11-25T09:44:37.673Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:44:37.673Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:44:42.675Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:44:42.675Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:44:42.675Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:44:42.675Z SendDataConnector.js: do connect now
I/jxcore-log( 2952): 
,I/        ( 2952): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2952): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2952): Starting to connect
W/BluetoothAdapter( 2952): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:105, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 105
,I/BTConnectToThread( 2952): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2952): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2952): 2015-11-25T09:44:43.862Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:44:43.863Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2952): 
I/jxcore-log( 2952): 2015-11-25T09:44:43.864Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:44:43.866Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2952): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/        ( 2952): Cleared service requests
I/        ( 2952): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 2952): Found 6 peers.
I/SS      ( 2952): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2952): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2952): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2952): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2952): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2952): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2952): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2952): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2952): Started service discovery
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2952): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2740","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2740","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT2740, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT2740, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 2952): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT8406"}, typeCordovap2p._tcp.local.:
,I/        ( 2952): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT8406"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT8406, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT8406, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 2952): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3716"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3716"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT3716, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT3716, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 2952): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8316","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 2952): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8316","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT8316, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT8316, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 2952): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT124"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT124"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT124, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT124, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 2952): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4529"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4529"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4529, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4529, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 2952): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8206","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 2952): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8206","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8206, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8206, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2952): Cleared service requests
I/        ( 2952): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2952): Found 8 peers.
I/SS      ( 2952): Peer(1): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2952): Peer(2): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 2952): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2952): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2952): Peer(5): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2952): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2952): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2952): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2952): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2952): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 2952): Started service discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2952): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8206","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 2952): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8206","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8206, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8206, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 2952): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8656","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8656","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT8656, peerAddress: F8:CF:C5:D9:E5:61
,I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT8656, WifiDirectName: , WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,I/        ( 2952): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5918","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5918","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT5918, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT5918, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 2952): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3716"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3716"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT3716, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT3716, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 2952): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT124"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT124"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT124, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT124, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 2952): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4529"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4529"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4529, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4529, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 2952): Cleared service requests
I/        ( 2952): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2952): Found 10 peers.
I/SS      ( 2952): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2952): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2952): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2952): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2952): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 2952): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2952): Peer(7): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2952): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2952): Peer(9): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2952): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2952): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2952): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2952): Started service discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2952): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7055","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 2952): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7055","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT7055, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT7055, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 2952): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8206","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8206","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8206, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8206, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 2952): Cleared service requests
,I/        ( 2952): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2952): Found 11 peers.
I/SS      ( 2952): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2952): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2952): Peer(3): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 2952): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2952): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 2952): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2952): Peer(7): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2952): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2952): Peer(9): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2952): Peer(10): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2952): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2952): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2952): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2952): Started service discovery
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,I/        ( 2952): Cleared service requests
,I/        ( 2952): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 2952): Found 10 peers.
I/SS      ( 2952): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2952): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2952): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2952): Peer(4): A3-1 0a:ec:a9:50:75:42
I/SS      ( 2952): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2952): Peer(6): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2952): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2952): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2952): Peer(9): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2952): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2952): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2952): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2952): Started service discovery
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2952): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5918","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 2952): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5918","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT5918, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT5918, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 2952): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3716"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3716"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT3716, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT3716, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 2952): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8316","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8316","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT8316, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT8316, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 2952): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT124"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT124"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT124, peerAddress: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT124, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 2952): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4529"}, typeCordovap2p._tcp.local.:
,I/        ( 2952): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4529"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4529, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4529, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2952): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT8406"}, typeCordovap2p._tcp.local.:
,I/        ( 2952): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT8406"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT8406, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT8406, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2952): Cleared service requests
I/        ( 2952): Started peer discovery
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2952): Found 11 peers.
I/SS      ( 2952): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2952): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2952): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2952): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2952): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 2952): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2952): Peer(7): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2952): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2952): Peer(9): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2952): Peer(10): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2952): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2952): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2952): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 2952): Started service discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 2952): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT8406"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT8406"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT8406, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT8406, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 2952): Cleared service requests
I/        ( 2952): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 2952): Found 11 peers.
I/SS      ( 2952): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2952): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2952): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2952): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2952): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 2952): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2952): Peer(7): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2952): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2952): Peer(9): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2952): Peer(10): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2952): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2952): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2952): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2952): Started service discovery
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2952): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT8406"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT8406"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT8406, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT8406, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 2952): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2740","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 2952): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2740","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT2740, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT2740, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 2952): Cleared service requests
I/        ( 2952): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2952): Found 11 peers.
I/SS      ( 2952): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2952): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2952): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2952): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 2952): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 2952): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2952): Peer(7): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2952): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2952): Peer(9): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2952): Peer(10): Android_50a5 fa:cf:c5:d9:e5:62
,I/SS      ( 2952): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2952): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2952): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2952): Started service discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2952): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT8406"}, typeCordovap2p._tcp.local.:
,I/        ( 2952): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT8406"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT8406, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 2952): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT8406, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/jxcore-log( 2952): DBG, CoordinatorConnector command called
I/jxcore-log( 2952): 
I/jxcore-log( 2952): command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): stop tests now !
I/jxcore-log( 2952): 
I/jxcore-log( 2952): stop current!
I/jxcore-log( 2952): 
I/jxcore-log( 2952): testSendData stopped
I/jxcore-log( 2952): 
,I/        ( 2952): Stoping All
I/        ( 2952): Stopping services
I/        ( 2952): Stopping services
,I/        ( 2952): Stop Bluetooth
I/        ( 2952): Stop Bluetooth
I/BTListenerThread( 2952): Stopped
,I/jxcore-log( 2952): StopBroadcasting went ok
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): 2015-11-25T09:47:49.492Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 2952): 
I/chromium( 2952): [INFO:CONSOLE(63)] "logCallback stop", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2952): DBG, CoordinatorConnector command called
I/jxcore-log( 2952): 
I/jxcore-log( 2952): command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"58:2A:F7:ED:96:BE\",\"time\":2905,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"E0:DB:10:1F:C9:5E\",\"time\":2927,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"08:EC:A9:50:76:27\",\"time\":3954,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"80:01:84:8A:B3:68\",\"time\":5475,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"F8:95:C7:87:3C:51\",\"time\":5997,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"34:FC:EF:9D:93:0B\",\"time\":6997,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"E0:DB:10:14:E2:C0\",\"time\":7338,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"7C:F9:0E:34:8A:A0\",\"time\":8097,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"58:3F:54:73:64:C0\",\"time\":10308,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"F8:CF:C5:D9:E5:61\",\"time\":226
I/jxcore-log( 2952): ****TEST TOOK:  ms ****
I/jxcore-log( 2952): 
I/jxcore-log( 2952): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2952): 
I/jxcore-log( 2952): stop tests now !
I/jxcore-log( 2952): 
I/jxcore-log( 2952): end, event received
I/jxcore-log( 2952): 
I/jxcore-log( 2952): CoordinatorConnector close called
I/jxcore-log( 2952): 
,I/jxcore-log( 2952): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 2952): 
I/jxcore-log( 2952): The Coordinator has disconnected!
I/jxcore-log( 2952): 
I/jxcore-log( 2952): The Coordinator has closed!
I/jxcore-log( 2952): 
I/jxcore-log( 2952): stop tests now !
I/jxcore-log( 2952): 
I/jxcore-log( 2952): turning Radios off
I/jxcore-log( 2952): 
I/jxcore-log( 2952): Toggling radios to false
I/jxcore-log( 2952): 
D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  760): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1cd37855 mBinding = false
,D/BluetoothManagerService(  760): Message: 2
,D/BluetoothManagerService(  760): Sending off request.
D/BluetoothAdapterState( 3010): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3010): Setting state to 13
I/BluetoothAdapterState( 3010): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 3010): onBluetoothDisable()
I/BluetoothAdapterState( 3010): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothAdapterProperties( 3010): Scan Mode:20
D/BluetoothAdapterState( 3010): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/BtOppRfcommListener( 3010): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,V/BluetoothMapMasInstance( 3010): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3010): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3010): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 3010): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 3010): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 3010): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3010): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3010): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,W/bt-smp  ( 3010): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3010): Plain text(LSB ~ MSB) = ff a4 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3010): Encrypted text(LSB ~ MSB) = 82 91 95 8b ea a8 33 52 23 56 c1 d1 11 bf 7b 34 
W/bt-btm  ( 3010): Stopping oneshot timer
W/bt-btif ( 3010): bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
,W/bt-l2cap( 3010): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3010): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothManagerService(  760): Message: 60
D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  760): Bluetooth State Change Intent: 12 -> 13
,D/WifiService(  760): setWifiEnabled: false pid=2952, uid=10270
E/WifiService(  760): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothMapService( 3010): onReceive
D/BluetoothMapService( 3010): STATE_TURNING_OFF
V/BluetoothMapService( 3010): Handler(): got msg=4
D/BluetoothMapService( 3010): MAP Service closeService in
D/BluetoothMapMasInstance( 3010): MAP Service shutdown
V/BluetoothMapService( 3010): MAP Service closeService out
I/BtOppRfcommListener( 3010): stopping Accept Thread
,I/BtOppRfcommListener( 3010): BluetoothSocket listen thread finished
,W/ContextImpl( 3017): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver( 3017): finishStartingService: stopping service
,E/WifiStateMachine(  760): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,I/jxcore-log( 2952): Radios toggled
I/jxcore-log( 2952): 
I/chromium( 2952): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
,D/AuthorizationBluetoothService( 1343): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothPbap( 3017): Proxy object disconnected
D/PbapServerProfile( 3017): Bluetooth service disconnected
,W/bt-btif ( 3010): ag scb idx 1 not allocated
E/bt-btif ( 3010): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3010): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3010): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3010): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3010): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3010): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3010): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial( 3010): RX termination
W/bt_userial( 3010): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 3010): Leaving userial_read_thread()
D/bt_userial( 3010): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 3010): hw_epilog_process
I/bt_userial_vendor( 3010): device fd = 53 close
,I/GKI_LINUX( 3010): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 3010): GKI_exit_task 0 done
I/GKI_LINUX( 3010): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 3010): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 3010): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3010): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ae664d9
D/HeadsetStateMachine( 3010): Exit Disconnected: -1
D/AndroidRuntime( 4056): 
D/AndroidRuntime( 4056): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/BluetoothHeadset( 3017): Proxy object disconnected
D/HeadsetProfile( 3017): Bluetooth service disconnected
D/BluetoothHeadset( 1161): Proxy object disconnected
,D/AndroidRuntime( 4056): CheckJNI is OFF
D/BluetoothHeadset( 1161): Proxy object disconnected
D/BluetoothHeadset( 1191): Proxy object disconnected
D/BluetoothHeadset(  760): Proxy object disconnected
,D/A2dpService( 3010): Received stop request...Stopping profile...
,D/BluetoothAdapterState( 3010): Stopping profile services that were post enabled
D/A2dpStateMachine( 3010): Exit Disconnected: -1
D/BluetoothAdapterService( 3010): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ae664d9
,D/BluetoothA2dp(  760): Proxy object disconnected
,D/BluetoothA2dp( 3017): Proxy object disconnected
D/A2dpProfile( 3017): Bluetooth service disconnected
D/HidService( 3010): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3010): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ae664d9
D/BluetoothInputDevice( 3017): Proxy object disconnected
D/HidProfile( 3017): Bluetooth service disconnected
D/HeadsetStateMachine( 3010): Unbinding service...
W/BluetoothHeadsetServiceJni( 3010): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3010): Cleaning up Bluetooth Handsfree callback object
D/HealthService( 3010): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3010): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ae664d9
,D/PanService( 3010): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3010): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ae664d9
,D/BtGatt.DebugUtils( 3010): handleDebugAction() action=null
D/BtGatt.GattService( 3010): Received stop request...Stopping profile...
,D/BtGatt.GattService( 3010): stop()
D/BtGatt.AdvertiseManager( 3010): advertise clients cleared
D/BluetoothPan( 3017): BluetoothPAN Proxy object disconnected
D/PanProfile( 3017): Bluetooth service disconnected
D/BluetoothAdapterService( 3010): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ae664d9
D/BluetoothMapService( 3010): Received stop request...Stopping profile...
D/BluetoothMapService( 3010): stop()
,D/BluetoothMapEmailAppObserver( 3010): deinitObservers()
D/BluetoothMapEmailAppObserver( 3010): removeReceiver()
D/BluetoothAdapterService( 3010): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ae664d9
,I/GKI_LINUX( 3010): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3010): GKI_exit_task 2 done
I/GKI_LINUX( 3010): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 3010): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3010): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3010): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3010): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3010): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3010): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3010): Cleaning up Bluetooth PAN callback object
,D/BluetoothMap( 3017): Proxy object disconnected
V/BluetoothMapService( 3010): Handler(): got msg=4
,D/BluetoothMapService( 3010): MAP Service closeService in
V/BluetoothMapService( 3010): MAP Service closeService out
D/BluetoothMapService( 3010): cleanup()
D/BluetoothMapService( 3010): MAP Service closeService in
V/BluetoothMapService( 3010): MAP Service closeService out
D/BluetoothAdapterState( 3010): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3010): Setting state to 10
I/BluetoothAdapterState( 3010): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService(  760): Message: 60
D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  760): Broadcasting onBluetoothStateChange(false) to 11 receivers.
D/BluetoothHeadset(  760): onBluetoothStateChange: up=false
I/BluetoothAdapterState( 3010): Entering OffState
,D/MapProfile( 3017): Bluetooth service disconnected
D/BluetoothA2dp(  760): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 3017): onBluetoothStateChange: up=false
D/BluetoothA2dp( 3017): onBluetoothStateChange: up=false
D/BluetoothHeadset( 3017): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1161): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1191): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1161): onBluetoothStateChange: up=false
D/BluetoothMap( 3017): onBluetoothStateChange: up=false
,D/BluetoothPbap( 3017): onBluetoothStateChange: up=false
,D/BluetoothManagerService(  760): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  760): Broadcasting onBluetoothServiceDown() to 11 receivers.
,D/BluetoothManagerService(  760): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1cd37855 mBinding = false
D/BluetoothManagerService(  760): Sending unbind request.
,D/BluetoothManagerService(  760): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter(  906): 962421922: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  906): 962421922: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  906): 962421922: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 3010): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 3010): GKI_exit_task 1 done
I/GKI_LINUX( 3010): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3010): cleanupNative: return from cleanup
,D/BluetoothAdapter( 1276): 366712786: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1276): 366712786: getState() :  mService = null. Returning STATE_OFF
,W/ContextImpl( 3017): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/art     ( 3010): System.exit called, status: 0
I/AndroidRuntime( 3010): VM exiting with result code 0, cleanup skipped.
,D/DockEventReceiver( 3017): finishStartingService: stopping service
,D/AndroidRuntime( 4056): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  760): Process com.android.bluetooth (pid 3010) has died
,I/ActivityManager(  760): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
,I/ActivityManager(  760): Killing 2952:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,W/PackageSettings(  760): Skipping PackageSetting{52ef708 com.example.hello/10277} due to missing metadata
,I/WindowState(  760): WIN DEATH: Window{3507feb9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  760): Client connection lost with reason: 4
,I/ActivityManager(  760):   Force finishing activity ActivityRecord{ecbb5aa u0 com.test.thalitest/.MainActivity t214}
,W/ActivityManager(  760): Spurious death for ProcessRecord{1a5b2b36 2952:com.test.thalitest/u0a270}, curProc for 2952: null
I/ActivityManager(  760): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  760):   Force finishing activity ActivityRecord{ecbb5aa u0 com.test.thalitest/.MainActivity t214 f}
W/ActivityManager(  760): Duplicate finish request for ActivityRecord{ecbb5aa u0 com.test.thalitest/.MainActivity t214 f}
,I/art     ( 1328): Explicit concurrent mark sweep GC freed 110676(4MB) AllocSpace objects, 23(368KB) LOS objects, 25% free, 19MB/25MB, paused 314us total 28.926ms
,I/InputReader(  760): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1276): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1070): resetDictionaries() : en_US
,I/Adreno-EGL(  944): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  944): Initialized EGL, version 1.4
,D/BluetoothAdapter( 3017): 918659872: getState() :  mService = null. Returning STATE_OFF
,I/Keyboard.Facilitator.DecoderInitializer( 1070): run()
I/Decoder ( 1070): createOrResetDecoder
,D/OpenGLRenderer(  944): Enabling debug mode 0
,I/ActivityManager(  760): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=4118 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/art     ( 1253): Explicit concurrent mark sweep GC freed 7274(472KB) AllocSpace objects, 2(207KB) LOS objects, 38% free, 26MB/42MB, paused 8.060ms total 92.562ms
,I/art     (  760): Explicit concurrent mark sweep GC freed 51768(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 28MB/42MB, paused 1.208ms total 113.391ms
,I/art     (  760): WaitForGcToComplete blocked for 31.980ms for cause Explicit
,I/ConfigService( 1343): onCreate
,W/InputMethodManagerService(  760): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@3ebd1b6c (uid=10034 pid=944)
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1070): run()
W/ResourcesManager( 4118): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1070): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1070): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1070): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1070): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1070): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1070): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1070): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1070): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1070): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1070): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1070): run()
I/StatsUtilsManager( 1070): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1070): shouldRecordStats() = Too Soon
,W/InputMethodManagerService(  760): Got RemoteException sending setActive(false) notification to pid 2952 uid 10270
D/BackupManagerService(  760): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  760): Receieved: android.intent.action.PACKAGE_REMOVED
I/Keyboard.Facilitator( 1070): onFinishInput()
,I/Launcher( 1253): Deferring update until onResume
,D/TaskPersister(  760): removeObsoleteFile: deleting file=214_task.xml
,D/AdapterServiceConfig( 4118): Adding HeadsetService
D/AdapterServiceConfig( 4118): Adding A2dpService
D/AdapterServiceConfig( 4118): Adding HidService
,D/AdapterServiceConfig( 4118): Adding HealthService,
D/AdapterServiceConfig( 4118): Adding PanService
,D/AdapterServiceConfig( 4118): Adding GattService
D/AdapterServiceConfig( 4118): Adding BluetoothMapService
I/ActivityManager(  760): Killing 2735:com.android.defcontainer/u0a5 (adj 15): empty #17
,W/ResourcesManager( 1253): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     (  760): Explicit concurrent mark sweep GC freed 10008(536KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 28MB/42MB, paused 1.803ms total 160.997ms
,W/ResourcesManager( 1253): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1253): Deferring update until onResume
,D/AndroidRuntime( 4056): Shutting down VM
,W/libprocessgroup(  760): failed to open /acct/uid_10005/pid_2735/cgroup.procs: No such file or directory
D/AuthorizationBluetoothService( 1343): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/VoicemailCleanupService( 3665): Cleaning up data for package: com.test.thalitest
,I/ActivityManager(  760): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=4145 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,W/Launcher( 1253): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1ae664d9 new=com.google.android.velvet.VelvetApplication@1ae664d9
I/UpdateIcingCorporaServi( 1328): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager(  760): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4165 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  760): Killing 2509:com.google.android.music:main/u0a60 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10060/pid_2509/cgroup.procs: No such file or directory
,W/ContextImpl( 4165): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,I/UpdateIcingCorporaServi( 1328): UpdateCorporaTask done [took 159 ms] updated apps [took 159 ms] 
,D/PackageBroadcastService( 1567): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1567): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1567): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1567): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1567): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1567): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1343): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1343): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/ActivityManager(  760): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4195 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/LocationSettingsChecker( 1567): Removing dialog suppression flag for package com.test.thalitest
,E/SQLiteDatabase( 1567): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1567): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1567): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1567): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1567): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1567): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1567): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1567): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1567): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1567): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1567): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1567): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1567): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1567): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1567): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1567): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1567): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:68)
E/SQLiteDatabase( 1567): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1567): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1567): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1567): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 1567): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1567): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1567): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1567): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1567): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1567): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1567): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1567): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1567): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1567): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1567): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1567): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteOpenHelper( 1567): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1567): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1567): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1567): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1567): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:68)
E/SQLiteOpenHelper( 1567): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1567): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1567): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1567): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1567): Opened phenotype.db in read-only mode
E/SQLiteDatabase( 1567): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1567): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1567): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1567): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1567): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1567): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1567): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1567): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1567): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1567): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1567): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1567): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1567): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1567): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1567): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1567): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1567): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteDatabase( 1567): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1567): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1567): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1567): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1567): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1567): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1567): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1567): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1567): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1567): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1567): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1567): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1567): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1567): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1567): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1567): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1567): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1567): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteOpenHelper( 1567): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1567): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1567): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1567): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1567): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1567): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1567): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1567): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1567): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1567): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1567): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1567): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 1567): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1567): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1567): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 1567): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/BaseAppContext( 1567): Using Auth Proxy for data requests.
W/BaseAppContext( 1567): Using Auth Proxy for data requests.
E/SQLiteLog( 1567): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/GAv4-SVC( 1567): Failed to update Analytics property: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SharedPreferencesImpl( 1567): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4-SVC( 1567): Job execution failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
E/SharedPreferencesImpl( 1567): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 1567): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 1567): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 1567): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1567): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1567): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1567): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1567): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1567): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1567): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1567): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1567): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1567): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1567): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1567): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1567): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1567): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1567): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
E/SQLiteDatabase( 1567): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/SQLiteDatabase( 1567): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/SQLiteDatabase( 1567): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/SQLiteDatabase( 1567): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/SQLiteDatabase( 1567): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/SQLiteDatabase( 1567): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1567): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1567): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/SQLiteDatabase( 1567): 	at java.lang.Thread.run(Thread.java:818)
E/ClearPendingStateOp( 1567): Runtime exception while performing operation
E/ClearPendingStateOp( 1567): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 1567): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 1567): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/ClearPendingStateOp( 1567): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/ClearPendingStateOp( 1567): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 1567): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 1567): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 1567): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/ClearPendingStateOp( 1567): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/ClearPendingStateOp( 1567): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/ClearPendingStateOp( 1567): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/ClearPendingStateOp( 1567): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/ClearPendingStateOp( 1567): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearPendingStateOp( 1567): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearPendingStateOp( 1567): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
E/ClearPendingStateOp( 1567): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/ClearPendingStateOp( 1567): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/ClearPendingStateOp( 1567): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 1567): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 1567): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/ClearPendingStateOp( 1567): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 1567): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 1567): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 1567): 	at java.lang.Thread.run(Thread.java:818)
F/ClearPendingStateOp( 1567): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1567): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 1567): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 1567): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
F/ClearPendingStateOp( 1567): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
F/ClearPendingStateOp( 1567): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 1567): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 1567): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 1567): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
F/ClearPendingStateOp( 1567): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
F/ClearPendingStateOp( 1567): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
F/ClearPendingStateOp( 1567): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
F/ClearPendingStateOp( 1567): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
F/ClearPendingStateOp( 1567): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
F/ClearPendingStateOp( 1567): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
F/ClearPendingStateOp( 1567): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
F/ClearPendingStateOp( 1567): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
F/ClearPendingStateOp( 1567): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
F/ClearPendingStateOp( 1567): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 1567): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 1567): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
F/ClearPendingStateOp( 1567): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 1567): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 1567): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 1567): 	at java.lang.Thread.run(Thread.java:818)
I/GMPM-SVC( 1567): App measurement is starting up
I/PeopleContactsSync( 1567): CP2 sync disabled
I/Icing   ( 1567): doRemovePackageData com.test.thalitest
E/DropBoxManagerService(  760): Can't write: system_app_wtf
E/DropBoxManagerService(  760): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  760): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  760): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  760): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  760): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  760): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  760): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  760): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  760): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  760): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  760): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  760): 	... 5 more

```
