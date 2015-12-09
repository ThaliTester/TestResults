#### Test 506502789252e15_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 2894): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2894):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2894):   adb logcat -s GAv4
W/GAv4    ( 2894): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2894): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2894): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 2894): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2381): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 2894): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2894): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  735): Killing 2288:com.google.android.deskclock/u0a38 (adj 15): empty #17
V/JNIHelp ( 2894): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 2894): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2894): Installed default security provider GmsCore_OpenSSL
D/AndroidRuntime( 2947): 
D/AndroidRuntime( 2947): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2947): CheckJNI is OFF
W/libprocessgroup(  735): failed to open /acct/uid_10038/pid_2288/cgroup.procs: No such file or directory
V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 2947): Calling main entry com.android.commands.am.Am
I/ActivityManager(  735): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  735): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2974 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2947): Shutting down VM
V/ActivityManager(  735): Display changed displayId=0
I/Icing   ( 1565): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/WebViewFactory( 2974): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2974): Time to load native libraries: 2 ms (timestamps 6499-6501)
I/LibraryLoader( 2974): Expected native library version number "",actual native library version number ""
I/Icing   ( 1565): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
V/WebViewChromiumFactoryProvider( 2974): Binding Chromium to main looper Looper (main, tid 1) {2ba2bcd0}
I/LibraryLoader( 2974): Expected native library version number "",actual native library version number ""
I/chromium( 2974): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2974): Initializing chromium process, singleProcess=true
W/art     ( 2974): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2974): ApplicationContext is null in ApplicationStatus
,W/chromium( 2974): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 2974): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 2974): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2974): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 2974): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/Icing   ( 1565): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
,I/Icing   ( 1565): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/BluetoothManagerService(  735): Message: 20
D/BluetoothManagerService(  735): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9aca4be:true
,D/BluetoothAdapter( 2974): 877884122: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 2974): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2974): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2974): CordovaWebView is running on device made by: LGE
,W/art     ( 2974): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2974): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2974): Render dirty regions requested: true
,D/Atlas   ( 2974): Validating map...
,W/chromium( 2974): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2974): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2974): Enabling debug mode 0
,I/Keyboard.Facilitator( 1085): onFinishInput()
,W/IInputConnectionWrapper( 2974): showStatusIcon on inactive InputConnection
,I/ActivityManager(  735): Displayed com.test.thalitest/.MainActivity: +424ms (total +55s37ms)
,W/BindingManager( 2974): Cannot call determinedVisibility() - never saw a connection for the pid: 2974
,D/JsMessageQueue( 2974): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 2974): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 2974): jxcore cordova android initializing
I/ActivityManager(  735): Killing 2344:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
W/libprocessgroup(  735): failed to open /acct/uid_10069/pid_2344/cgroup.procs: No such file or directory
W/jxcore-log( 2974): Initializing JXcore engine
W/jxcore-log( 2974): JXcore engine is ready
W/jxcore-log( 2974): Starting JXcore engine
,W/.test.thalitest( 2974): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8056]" dev="sockfs" ino=8056 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 2974): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 2974): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8121]" dev="sockfs" ino=8121 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 2974): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18415]" dev="sockfs" ino=18415 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 2974): Platform android
W/jxcore-log( 2974): 
W/jxcore-log( 2974): Process ARCH arm
W/jxcore-log( 2974): 
,I/jxcore-log( 2974): JXcore Cordova bridge is ready!
I/jxcore-log( 2974): 
,W/jxcore-log( 2974): JXcore engine is started
I/Choreographer( 2974): Skipped 110 frames!  The application may be doing too much work on its main thread.
I/chromium( 2974): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 2974): Toggling radios to true
I/jxcore-log( 2974): 
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  735): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  735): Message: 1
D/BluetoothManagerService(  735): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  735): New client listening to asynchronous messages
,D/WifiService(  735): setWifiEnabled: true pid=2974, uid=10270
E/WifiService(  735): Invoking mWifiStateMachine.setWifiEnabled
,I/ActivityManager(  735): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3040 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/SoftapController(  181): Softap fwReload - Ok
,D/CommandListener(  181): Setting iface cfg
,D/CommandListener(  181): Trying to bring down wlan0
D/CommandListener(  181): Clearing all IP addresses on wlan0
,I/jxcore-log( 2974): Radios toggled
I/jxcore-log( 2974): 
,D/WifiMonitor(  735): startMonitoring(wlan0) with mConnected = false
,I/ActivityManager(  735): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=3064 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/wpa_supplicant( 3050): Successfully initialized wpa_supplicant
,W/ResourcesManager( 3040): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/wpa_supplicant( 3050): rfkill: Cannot open RFKILL control device
,D/AdapterServiceConfig( 3040): Adding HeadsetService
D/AdapterServiceConfig( 3040): Adding A2dpService
D/AdapterServiceConfig( 3040): Adding HidService
D/AdapterServiceConfig( 3040): Adding HealthService
D/AdapterServiceConfig( 3040): Adding PanService
D/AdapterServiceConfig( 3040): Adding GattService
,D/AdapterServiceConfig( 3040): Adding BluetoothMapService
D/BluetoothManagerService(  735): Message: 20
,D/BluetoothManagerService(  735): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@269ce95d:true
,D/BluetoothAdapter( 3064): 732085456: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothManagerService(  735): Message: 30
,D/BluetoothManagerService(  735): Message: 20
D/BluetoothManagerService(  735): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2ed0fa2a:true
,D/BluetoothAdapterState( 3040): make
,D/BluetoothManagerService(  735): Message: 30
,D/LocalBluetoothProfileManager( 3064): Adding local MAP profile
D/BluetoothMap( 3064): Create BluetoothMap proxy object
D/BluetoothManagerService(  735): Message: 30
I/bluedroid( 3040): init
,D/BluetoothManagerService(  735): Message: 30
,I/BluetoothAdapterState( 3040): Entering OffState
,D/LocalBluetoothProfileManager( 3064): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 3064): 732085456: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3064): 732085456: getState() :  mService = null. Returning STATE_OFF
,I/bte_conf( 3040): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3040): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3040): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3040): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3040): get_profile_interface socket
,I/bluedroid( 3040): get_profile_interface map_client
I/GKI_LINUX( 3040): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 3040): Address is:34:FC:EF:11:AE:67
,I/ActivityManager(  735): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3093 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  735): Killing 1764:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
D/BluetoothManagerService(  735): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  735): Stored Bluetooth name: Nexus 5
D/BluetoothAdapterProperties( 3040): Name is: Nexus 5
,W/libprocessgroup(  735): failed to open /acct/uid_10045/pid_1764/cgroup.procs: No such file or directory
,D/BluetoothManagerService(  735): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  735): Message: 40
D/BluetoothManagerService(  735): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 3040): config_hci_snoop_log
,D/BluetoothManagerService(  735): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  735): Broadcasting onBluetoothServiceUp() to 9 receivers.
,D/BluetoothAdapterState( 3040): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3040): Setting state to 11
I/BluetoothAdapterState( 3040): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService(  735): Message: 60
D/BluetoothManagerService(  735): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothBondStateMachine( 3040): make
D/BluetoothManagerService(  735): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothHeadset( 1190): Proxy object connected
I/BluetoothBondStateMachine( 3040): StableState(): Entering Off State
,D/BluetoothHeadset( 1171): Proxy object connected
D/BluetoothHeadset(  735): Proxy object connected
D/BluetoothHeadset( 1171): Proxy object connected
,D/HeadsetService( 3040): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni( 3040): classInitNative: succeeds
,D/HeadsetStateMachine( 3040): make
,I/BluetoothAdapterState( 3040): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetStateMachine( 3040): max_hf_connections = 1
I/bluedroid( 3040): get_profile_interface handsfree
,D/BluetoothAdapterService( 3040): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b1f4c9
D/HeadsetStateMachine( 3040): Enter Disconnected: -2, size: 0
D/BluetoothA2dp(  735): Proxy object connected
,D/A2dpService( 3040): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3040): classInitNative: succeeds
I/bluedroid( 3040): get_profile_interface avrcp
,E/RemoteController( 3040): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3040): classInitNative: succeeds
D/A2dpStateMachine( 3040): make
,I/bluedroid( 3040): get_profile_interface a2dp
I/GKI_LINUX( 3040): gki_task_entry task_id=2 [A2DP-MEDIA] starting
D/BluetoothAdapterService( 3040): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b1f4c9
I/BluetoothHidServiceJni( 3040): classInitNative: succeeds
D/A2dpStateMachine( 3040): Enter Disconnected: -2
,D/BluetoothInputDevice( 3064): Proxy object connected
D/HidService( 3040): Received start request. Starting profile...
I/bluedroid( 3040): get_profile_interface hidhost
D/BluetoothAdapterService( 3040): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b1f4c9
D/HidProfile( 3064): Bluetooth service connected
I/BluetoothHealthServiceJni( 3040): classInitNative: succeeds
,D/HealthService( 3040): Received start request. Starting profile...
,I/bluedroid( 3040): get_profile_interface health
D/BluetoothAdapterService( 3040): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b1f4c9
I/BluetoothPanServiceJni( 3040): classInitNative(L105): succeeds
,D/PanService( 3040): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3040): initializeNative(L110): pan
I/bluedroid( 3040): get_profile_interface pan
,D/BluetoothPan( 3064): BluetoothPAN Proxy object connected
D/PanProfile( 3064): Bluetooth service connected
,D/BluetoothAdapterService( 3040): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b1f4c9
I/BtGatt.JNI( 3040): classInitNative(L863): classInitNative: Success!
D/BtGatt.DebugUtils( 3040): handleDebugAction() action=null
D/BtGatt.GattService( 3040): Received start request. Starting profile...
D/BtGatt.GattService( 3040): start()
I/bluedroid( 3040): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 3040): advertise manager created
,D/BluetoothAdapterService( 3040): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b1f4c9
,V/BluetoothMapService( 3040): BluetoothMapBinder()
,I/art     (  735): Explicit concurrent mark sweep GC freed 14208(715KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.147ms total 49.358ms
,D/BluetoothMapService( 3040): Received start request. Starting profile...
D/BluetoothMapService( 3040): start()
,D/BluetoothMap( 3064): Proxy object connected
D/MapProfile( 3064): Bluetooth service connected
D/BluetoothMap( 3064): getConnectedDevices()
,D/BluetoothMap( 3064): Bluetooth is Not enabled
,D/BluetoothMapEmailSettingsLoader( 3040): Found 0 applications
D/BluetoothMapEmailAppObserver( 3040): createReceiver()
,D/BluetoothMapEmailAppObserver( 3040): initObservers()
D/BluetoothMapEmailAppObserver( 3040): getEnabledAccountItems()
,D/BluetoothAdapterService( 3040): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b1f4c9
,D/HeadsetStateMachine( 3040): Proxy object connected
V/BluetoothMapService( 3040): Handler(): got msg=1
,D/BluetoothAdapterState( 3040): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3040): enable
D/HeadsetStateMachine( 3040): Disconnected process message: 10, size: 0
,D/HeadsetPhoneState( 3040): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,I/GKI_LINUX( 3040): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3040): btu_task pending for preload complete event
I/bt_hci_bdroid( 3040): init
D/HeadsetStateMachine( 3040): Disconnected process message: 11, size: 0
,I/bt_vendor( 3040): init
I/bt_vnd_conf( 3040): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3040): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3040): userial_init
,I/bt_userial_vendor( 3040): userial vendor open: opening /dev/ttyHS99
,I/bt_userial_vendor( 3040): device fd = 53 open
D/bt_userial( 3040): Entering userial_read_thread()
,D/AuthorizationBluetoothService( 1301): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager(  735): Killing 2435:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,I/bt_hwcfg( 3040): bt vendor lib: set UART baud 4000000
,D/bt_hwcfg( 3040): Chipset BCM4335C0
D/bt_hwcfg( 3040): Target name = [BCM4335C0]
I/bt_hwcfg( 3040): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,W/libprocessgroup(  735): failed to open /acct/uid_10003/pid_2435/cgroup.procs: No such file or directory
,D/Tethering(  735): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 3050): rfkill: Cannot open RFKILL control device
,I/wpa_supplicant( 3050): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiConfigStore(  735): Loading config and enabling all networks 
,I/bt_hwcfg( 3040): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 3040): Settlement delay -- 100 ms
I/bt_hwcfg( 3040): Setting fw settlement delay to 100 
,D/WifiService(  735): New client listening to asynchronous messages
,E/WifiConfigStore(  735): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,W/Settings( 2252): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-HAL(  735): Setting external_sim to 1
,D/WifiStateMachine(  735): Setting OUI to DA-A1-19
I/WifiNative-HAL(  735): startHal
D/wifi    (  735): setting scan oui 0x9bd905f8
D/WifiHAL (  735): Sending mac address OUI
E/WifiHAL (  735): failed to set scanning mac OUI; result = -95
,E/native  (  735): do suspend true
,D/CommandListener(  181): Setting iface cfg
D/CommandListener(  181): Trying to bring up p2p0
,D/WifiMonitor(  735): startMonitoring(p2p0) with mConnected = true
,D/WifiScanningService(  735): SCAN_AVAILABLE : 3
,D/RttService(  735): SCAN_AVAILABLE : 3
D/WifiScanningService(  735): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  735): startHal
D/RttService(  735): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/wifi    (  735): getting scan capabilities on interface[1] = 0x9bd905f8
D/WifiHAL (  735): Creating message to get scan capablities; iface = 21
,D/WifiHAL (  735): In GetCapabilities::handleResponse
D/WifiHAL (  735): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  735): StartedState
,D/WifiNative-HAL(  735): p2pGetDeviceAddress
D/WifiNative-HAL(  735): p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,I/wpa_supplicant( 3050): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,I/bt_hwcfg( 3040): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 3040): Setting local bd addr to 34:FC:EF:11:AE:67
,I/bt_hwcfg( 3040): vendor lib fwcfg completed
I/bt-btu  ( 3040): btu_task received preload complete event
,I/        ( 3040): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3040): BTE_InitTraceLevels -- TRC_L2CAP
,I/        ( 3040): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3040): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3040): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3040): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3040): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3040): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3040): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3040): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3040): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3040): BTE_InitTraceLevels -- TRC_GATT
,I/        ( 3040): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3040): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3040): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 3040): BTM_SecRegister:p_cb_info->p_le_callback == 0xa3cd99d5 
E/bt-btm  ( 3040): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3cd99d5 
,I/ActivityManager(  735): Killing 2318:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10070/pid_2318/cgroup.procs: No such file or directory
,E/bt-btif ( 3040): Calling BTA_HhEnable
E/bt-btif ( 3040): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3040): Address is:34:FC:EF:11:AE:67
,D/BluetoothAdapterProperties( 3040): Name is: Nexus 5
,D/BluetoothAdapterProperties( 3040): Scan Mode:20
D/BluetoothAdapterProperties( 3040): Discoverable Timeout:120
,D/bte_conf( 3040): Device ID record 1 : primary
D/bte_conf( 3040):   vendorId            = 000f
D/bte_conf( 3040):   vendorIdSource      = 0001
D/bte_conf( 3040):   product             = 1200
D/bte_conf( 3040):   version             = 1436
D/bte_conf( 3040):   clientExecutableURL = 
D/bte_conf( 3040):   serviceDescription  = 
D/bte_conf( 3040):   documentationURL    = 
D/bte_conf( 3040): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 3040): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,D/BluetoothAdapterState( 3040): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3040): ScanMode =  20
D/BluetoothAdapterProperties( 3040): State =  11
D/BluetoothAdapterProperties( 3040): Setting state to 12
I/BluetoothAdapterState( 3040): Bluetooth adapter state changed: 11-> 12
W/bt-smp  ( 3040): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3040): Plain text(LSB ~ MSB) = ab c8 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3040): Encrypted text(LSB ~ MSB) = a8 b7 e4 bf 77 03 ae f9 73 4b 29 90 6a 14 6a 7e 
W/bt-btm  ( 3040): Stopping oneshot timer
,D/BluetoothManagerService(  735): Message: 60
D/BluetoothManagerService(  735): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  735): Broadcasting onBluetoothStateChange(true) to 9 receivers.
D/BluetoothPan( 3064): onBluetoothStateChange(on) call bindService
,I/BluetoothAdapterState( 3040): Entering On State
D/BluetoothManagerService(  735): Bluetooth Adapter name changed to Nexus 5
,D/BluetoothManagerService(  735): Stored Bluetooth name: Nexus 5
,D/BluetoothAdapterProperties( 3040): Scan Mode:21
D/BluetoothAdapterProperties( 3040): Discoverable Timeout:120
,D/BluetoothMap( 3064): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1171): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1190): onBluetoothStateChange: up=true
D/BluetoothHeadset(  735): onBluetoothStateChange: up=true
D/BluetoothPbap( 3064): onBluetoothStateChange: up=true
,D/BluetoothA2dp(  735): onBluetoothStateChange: up=true
,D/BluetoothInputDevice( 3064): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1171): onBluetoothStateChange: up=true
,D/BluetoothManagerService(  735): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService(  735): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothMapService( 3040): onReceive
D/BluetoothMapService( 3040): STATE_ON
V/BluetoothMapService( 3040): Handler(): got msg=1
,E/bt_h4   ( 3040): vendor lib postload completed
,D/BluetoothMapMasInstance( 3040): Map Service startRfcommSocketListener
,D/BluetoothMapMasInstance( 3040): MAS initSocket()
,D/BluetoothMapMasInstance( 3040):   masId = 00
D/BluetoothMapMasInstance( 3040):   msgTypes = 0e
D/BluetoothMapMasInstance( 3040):   masName = SMS/MMS
D/BluetoothMapMasInstance( 3040):   SDP string = 000eSMS/MMS
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  735): Message: 40
,D/BluetoothManagerService(  735): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
I/Telecom ( 1171): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
W/bt-smp  ( 3040): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
,W/bt-smp  ( 3040): Plain text(LSB ~ MSB) = 55 16 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3040): Encrypted text(LSB ~ MSB) = 65 f9 31 86 b6 c2 bb 5a 27 96 e0 76 21 fa 4f 2a 
W/bt-btm  ( 3040): Stopping oneshot timer
D/HeadsetStateMachine( 3040): Disconnected process message: 9, size: 0
D/HeadsetStateMachine( 3040): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 3040): mNumber:  mType: 128
D/HeadsetStateMachine( 3040): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 3040): terminateScoUsingVirtualVoiceCall:No present call to terminate
W/bt-smp  ( 3040): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3040): Plain text(LSB ~ MSB) = 5d 17 41 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3040): Encrypted text(LSB ~ MSB) = 66 fd 0c a6 38 d6 5e 04 03 7e 7c bf 7d 91 1c 6c 
W/bt-btm  ( 3040): Stopping oneshot timer
,W/BluetoothAdapter( 3040): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothMapMasInstance( 3040): Succeed to create listening socket 
,D/BluetoothMapMasInstance( 3040): Accepting socket connection...
W/bt-smp  ( 3040): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3040): Plain text(LSB ~ MSB) = 54 42 48 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3040): Encrypted text(LSB ~ MSB) = 3e d7 79 62 1e 72 cb bb 9d d7 2d 33 c0 78 6b 7a 
W/bt-btm  ( 3040): Stopping oneshot timer
D/LocalBluetoothProfileManager( 3064): Adding local A2DP profile
D/BluetoothManagerService(  735): Message: 30
W/bt-smp  ( 3040): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3040): Plain text(LSB ~ MSB) = 9e cc 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3040): Encrypted text(LSB ~ MSB) = 75 f5 99 59 f2 51 66 f4 e3 b1 44 fe ca 9d 98 5f 
W/bt-btm  ( 3040): Stopping oneshot timer
D/LocalBluetoothProfileManager( 3064): Adding local HEADSET profile
D/BluetoothManagerService(  735): Message: 30
,W/ContextImpl( 3064): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothA2dp( 3064): Proxy object connected
,W/BluetoothAdapter( 3040): getBluetoothService() called with no BluetoothManagerCallback
,D/A2dpProfile( 3064): Bluetooth service connected
D/BluetoothHeadset( 3064): Proxy object connected
D/HeadsetProfile( 3064): Bluetooth service connected
D/DockEventReceiver( 3064): finishStartingService: stopping service
D/BluetoothPbap( 3064): Proxy object connected
D/PbapServerProfile( 3064): Bluetooth service connected
,D/AuthorizationBluetoothService( 1301): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3040): getBluetoothService() called with no BluetoothManagerCallback
I/BtOppRfcommListener( 3040): Accept thread started.
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  735): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiStateMachine(  735): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  735): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=1
,E/WifiConfigStore(  735): writeKnownNetworkHistory write linked 1
E/WifiConfigStore(  735): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  735): will read network variables netId=1
E/WifiStateMachine(  735): CMD_AUTO_CONNECT did save config ->  nid=1
E/WifiConfigStore(  735): will read network variables netId=1
,I/wpa_supplicant( 3050): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,E/WifiConfigStore(  735): setLastSelectedConfiguration -1
,E/wpa_supplicant( 3050): PNO: In assoc process
,I/wpa_supplicant( 3050): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3050): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3050): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  735): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  181): Setting iface cfg
,E/WifiStateMachine(  735): Start Dhcp Watchdog 1
,E/native  (  735): do suspend false
,E/WifiStateMachine(  735): scanCount==0 - aborting
,I/dhcpcd  ( 3187): version 5.5.6 starting
E/dhcpcd  ( 3187): get_duid: Read-only file system
,I/dhcpcd  ( 3187): wlan0: rebinding lease of 192.168.1.114
,W/NetworkUtils( 1368): OkHttp exception
W/EventLoggerService( 1368): Unable to send logs Error code: 262146
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dhcpcd  ( 3187): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3187): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  735): do suspend true
,D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  735): Adding iface wlan0 to network 100
,E/WifiStateMachine(  735): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  735): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  735): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  735): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  735): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  735): Setting Dns servers for network 100 to [/192.168.1.1]
,D/Nat464Xlat(  735): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  735): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  735): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  735): rematching NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  735):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  735): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
,D/CSLegacyTypeTracker(  735): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  735): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  735): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler(  902): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 09 Dec 2015 17:53:32 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449683612389], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449683612370]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Validated
,D/ConnectivityService(  735): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  735): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  735): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  735): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1190): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler(  902): CM callback handler got msg 524290
,I/jxcore-log( 2974): Test app app.js loaded
I/jxcore-log( 2974): 
,I/chromium( 2974): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  735): MasterInitialState.processMessage what=3
,D/AlarmManagerService(  735): Setting time of day to sec=1449683615
,W/AlarmManagerService(  735): Unable to set rtc to 1449683615: Invalid argument
,I/NetworkMonitor( 2455): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2455): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1565): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1565): onCreate
,D/SystemUpdateService( 1565): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1565): active receiver: enabled
,I/SystemUpdateService( 1565): showing system update notification
,I/ValidateNoPeople(  735): skipping global notification
,V/SystemUpdateService( 1565): retry (wakeup: false) in 3599984 ms
,E/GpsLocationProvider(  735): No APN found to select.
,I/iu.SyncManager( 1565): SYNC; picasa accounts
,E/ActivityThread( 1565): Failed to find provider info for com.android.contacts.metadata
,D/GpsLocationProvider(  735): NTP server returned: 1449683612764 (Wed Dec 09 18:53:32 GMT+01:00 2015) reference: 83368 certainty: 9 system time offset: -3077
E/LocSvc_eng(  735): E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,D/SyncManager(  735): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 25424, reason: UserStart, SyncResult: databaseError: true stats []
D/SyncManager(  735): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 116459, reason: UserStart
,D/NetworkLogImpl( 1565): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1565): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1565): num queued entries: 0
,I/iu.UploadsManager( 1565): num updated entries: 0
,I/iu.SyncManager( 1565): NEXT; no task
,D/SystemUpdateService( 1565): onDestroy
,E/Auth.Api.Credentials( 1565): [CredentialSyncAdapter] Unknown sync event.
,I/ActivityManager(  735): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3288 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  196): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 977us total 9.043ms
,I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 167us total 7.462ms
,I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 170us total 7.719ms
,I/Babel   ( 2252): connection state changed from UNKNOWN to CONNECTED
,I/GAv4    ( 3288): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3288):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3288):   adb logcat -s GAv4
,W/GAv4    ( 3288): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3288): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3288): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/GCM     ( 1301): GCM config loaded
,D/ConnectivityService(  735): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  735): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  735): apparently satisfied.  currentScore=60
,D/ConnectivityManager.CallbackHandler( 1565): CM callback handler got msg 524290
,W/DriveInitializer( 1565): Awaiting to be initialized
W/DriveInitializer( 1565): Background init thread started
,I/WebViewFactory( 3288): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3288): Time to load native libraries: 1 ms (timestamps 6836-6837)
,I/LibraryLoader( 3288): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3288): Binding Chromium to main looper Looper (main, tid 1) {70b442}
,I/LibraryLoader( 3288): Expected native library version number "",actual native library version number ""
I/chromium( 3288): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3288): Initializing chromium process, singleProcess=true
W/art     ( 3288): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3288): ApplicationContext is null in ApplicationStatus
,W/chromium( 3288): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3288): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3288): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3288): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3288): Requires BLUETOOTH permission
,W/DriveInitializer( 1565): Background init thread ended
,I/NSApplication( 3288): Starting up...
,I/art     (  735): Explicit concurrent mark sweep GC freed 51725(2MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 27MB/41MB, paused 1.023ms total 58.124ms
,I/ActivityManager(  735): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3379 uid=10076 gids={50076, 9997} abi=armeabi-v7a
,D/TimeService( 3379): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449683616489
D/        ( 3379): TimeServiceNative: User Time to be set is 1449683616489
,D/QC-time-services( 3379): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3379): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3379): Lib:time_genoff_operation: pargs->ts_val = 1449683616489
D/QC-time-services(  199): Daemon: Connection accepted:time_genoff
D/QC-time-services( 3379): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  199): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449683616489
D/QC-time-services(  199): Daemon:genoff_opr: Base = 2, val = 1449683616489, operation = 0
,D/QC-time-services(  199): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/12/70 23:44:20
D/QC-time-services(  199): Daemon:Value read from RTC seconds = 8811860000
D/QC-time-services(  199): Daemon:new time 1449683616489 
D/QC-time-services(  199): Daemon: delta 1440871756489 genoff 1440871756489 
D/QC-time-services(  199): Daemon:genoff_persistent_update: Writing genoff = 1440871756489 to memory
D/QC-time-services(  199): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  199): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  199): Updating the TOD offset
,D/QC-time-services(  199): Daemon:genoff_persistent_update: Writing genoff = 1440871756489 to memory
D/QC-time-services(  199): Daemon:Opening File: /data/system/time/ats_1
D/QC-time-services(  199): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  199): Daemon:Update to modem bit set
D/QC-time-services(  199): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  199): Daemon: Base = 2, Value being sent to MODEM = 1133718816489
,E/QC-time-services( 3379): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/QC-time-services(  199): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
D/QC-time-services(  199): Daemon: Time-services: Waiting to acceptconnection
,I/CheckinService( 1565): Checkin interval check for package: unspecified last checkin: 1449673064750 min interval config: 0 actual interval: 10551766
,I/ActivityManager(  735): Killing 1898:com.android.providers.calendar/u0a2 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10002/pid_1898/cgroup.procs: No such file or directory
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  735): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=3399 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,W/art     ( 2591): Attempt to remove local handle scope entry from IRT, ignoring
,I/GAv4    ( 3399): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3399):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3399):   adb logcat -s GAv4
,W/GAv4    ( 3399): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3399): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3399): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  735): Killing 2761:com.google.android.gms:car/u0a8 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10008/pid_2761/cgroup.procs: No such file or directory
,I/ActivityManager(  735): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3432 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  735): Killing 2552:android.process.acore/u0a4 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10004/pid_2552/cgroup.procs: No such file or directory
,W/ResourcesManager( 3432): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 3432): Created com.android.providers.calendar.CalendarAlarmManager@294f1493(com.android.providers.calendar.CalendarProvider2@2ba2bcd0)
,I/CalendarProvider2( 3432): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 3432): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/Finsky  ( 2381): [230] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2381): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/SQLiteLog( 3432): (284) automatic index on view_events(_id)
,I/ActivityManager(  735): Killing 1453:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10013/pid_1453/cgroup.procs: No such file or directory
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1301): Vacuum at: now=1449683625292 tag=VacuumService
,E/ActivityThread( 1565): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  735): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 116459, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  735): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 176653, reason: UserStart
,I/Keyboard.Facilitator.LanguageModelFlusher( 1085): run()
I/Keyboard.Facilitator( 1085): flushDynamicLanguageModels()
,I/ConfigService( 1301): onCreate
,I/ConfigService( 1301): onDestroy
,I/ClearcutLoggerApiImpl( 1301): disconnect managed GoogleApiClient
,D/HeadsetStateMachine( 3040): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3040): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/HeadsetStateMachine( 3040): Disconnected process message: 11, size: 0
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 2974): Toggling radios to false
I/jxcore-log( 2974): 
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  735): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@c68752b mBinding = false
,D/BluetoothManagerService(  735): Message: 2
D/BluetoothManagerService(  735): Sending off request.
,D/BluetoothAdapterState( 3040): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3040): Setting state to 13
I/BluetoothAdapterState( 3040): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterProperties( 3040): onBluetoothDisable()
I/BluetoothAdapterState( 3040): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 3040): Scan Mode:20
,D/BluetoothAdapterState( 3040): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,V/BluetoothMapMasInstance( 3040): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3040): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3040): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 3040): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 3040): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 3040): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3040): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3040): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,E/BtOppRfcommListener( 3040): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/btif_config_util( 3040): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3040): bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
,D/BluetoothManagerService(  735): Message: 60
D/BluetoothManagerService(  735): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
,W/bt-l2cap( 3040): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3040): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothManagerService(  735): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 3040): onReceive
D/BluetoothMapService( 3040): STATE_TURNING_OFF
V/BluetoothMapService( 3040): Handler(): got msg=4
D/BluetoothMapService( 3040): MAP Service closeService in
D/BluetoothMapMasInstance( 3040): MAP Service shutdown
V/BluetoothMapService( 3040): MAP Service closeService out
,I/BtOppRfcommListener( 3040): stopping Accept Thread
,I/BtOppRfcommListener( 3040): BluetoothSocket listen thread finished
,D/WifiService(  735): setWifiEnabled: false pid=2974, uid=10270
E/WifiService(  735): Invoking mWifiStateMachine.setWifiEnabled
,W/ContextImpl( 3064): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver( 3064): finishStartingService: stopping service
,E/WifiStateMachine(  735): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,I/jxcore-log( 2974): Radios toggled
I/jxcore-log( 2974): 
,E/native  (  735): do suspend true
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1301): Read error: ssl=0x9a684200: I/O error during system call, Connection timed out
,V/NativeCrypto( 1301): SSL shutdown failed: ssl=0x9a684200: I/O error during system call, Broken pipe
D/AuthorizationBluetoothService( 1301): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothPbap( 3064): Proxy object disconnected
D/PbapServerProfile( 3064): Bluetooth service disconnected
,D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
D/bt_userial( 3040): RX termination
W/bt_userial( 3040): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 3040): Leaving userial_read_thread()
,W/bt-btif ( 3040): ag scb idx 1 not allocated
E/bt-btif ( 3040): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3040): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 3040): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3040): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3040): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3040): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3040): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial( 3040): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 3040): hw_epilog_process
I/bt_userial_vendor( 3040): device fd = 53 close
,I/GKI_LINUX( 3040): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 3040): GKI_exit_task 0 done
I/GKI_LINUX( 3040): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 3040): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  735): scanCount==0 - aborting
,D/WifiScanningService(  735): SCAN_AVAILABLE : 1
D/RttService(  735): SCAN_AVAILABLE : 1
,D/WifiScanningService(  735): StartedState got{ when=-2ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  735): DefaultState
,D/RttService(  735): EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNetworkAgent(  735): NetworkAgent: NetworkAgent channel lost
,D/ConnectivityService(  735): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,E/native  (  735): do suspend true
,D/HeadsetService( 3040): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3040): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b1f4c9
,D/HeadsetStateMachine( 3040): Exit Disconnected: -1
,D/BluetoothHeadset(  735): Proxy object disconnected
,D/BluetoothHeadset( 1190): Proxy object disconnected
,D/BluetoothHeadset( 1171): Proxy object disconnected
,D/BluetoothHeadset( 1171): Proxy object disconnected
,D/A2dpService( 3040): Received stop request...Stopping profile...
,D/A2dpStateMachine( 3040): Exit Disconnected: -1
,D/BluetoothAdapterService( 3040): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b1f4c9
,D/BluetoothHeadset( 3064): Proxy object disconnected
,D/BluetoothAdapterState( 3040): Stopping profile services that were post enabled
D/BluetoothA2dp(  735): Proxy object disconnected
,D/HeadsetProfile( 3064): Bluetooth service disconnected
,D/BluetoothA2dp( 3064): Proxy object disconnected
D/A2dpProfile( 3064): Bluetooth service disconnected
D/HidService( 3040): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3040): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b1f4c9
,D/HealthService( 3040): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3040): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b1f4c9
,D/BluetoothInputDevice( 3064): Proxy object disconnected
D/HidProfile( 3064): Bluetooth service disconnected
,D/HeadsetStateMachine( 3040): Unbinding service...
,W/BluetoothHeadsetServiceJni( 3040): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3040): Cleaning up Bluetooth Handsfree callback object
,D/PanService( 3040): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3040): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b1f4c9
,D/BluetoothPan( 3064): BluetoothPAN Proxy object disconnected
D/PanProfile( 3064): Bluetooth service disconnected
,D/BtGatt.DebugUtils( 3040): handleDebugAction() action=null
,D/BtGatt.GattService( 3040): Received stop request...Stopping profile...
D/BtGatt.GattService( 3040): stop()
,D/BtGatt.AdvertiseManager( 3040): advertise clients cleared
,D/BluetoothAdapterService( 3040): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b1f4c9
,D/BluetoothMapService( 3040): Received stop request...Stopping profile...
D/BluetoothMapService( 3040): stop()
,D/BluetoothMapEmailAppObserver( 3040): deinitObservers()
D/BluetoothMapEmailAppObserver( 3040): removeReceiver()
,D/BluetoothAdapterService( 3040): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b1f4c9
,I/GKI_LINUX( 3040): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 3040): GKI_exit_task 2 done
I/GKI_LINUX( 3040): GKI_shutdown(): task [A2DP-MEDIA] terminated
,D/BluetoothMap( 3064): Proxy object disconnected
D/MapProfile( 3064): Bluetooth service disconnected
W/BluetoothHidServiceJni( 3040): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3040): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3040): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3040): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3040): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3040): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3040): Cleaning up Bluetooth PAN callback object
,V/BluetoothMapService( 3040): Handler(): got msg=4
,D/BluetoothMapService( 3040): MAP Service closeService in
V/BluetoothMapService( 3040): MAP Service closeService out
D/BluetoothAdapterState( 3040): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3040): Setting state to 10
,I/BluetoothAdapterState( 3040): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService(  735): Message: 60
D/BluetoothManagerService(  735): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  735): Broadcasting onBluetoothStateChange(false) to 11 receivers.
I/BluetoothAdapterState( 3040): Entering OffState
,D/BluetoothMapService( 3040): cleanup()
,D/BluetoothMapService( 3040): MAP Service closeService in
V/BluetoothMapService( 3040): MAP Service closeService out
D/BluetoothMap( 3064): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 3064): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1171): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1190): onBluetoothStateChange: up=false
D/BluetoothHeadset(  735): onBluetoothStateChange: up=false
D/BluetoothA2dp( 3064): onBluetoothStateChange: up=false
D/BluetoothPbap( 3064): onBluetoothStateChange: up=false
D/BluetoothA2dp(  735): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 3064): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1171): onBluetoothStateChange: up=false
,D/BluetoothManagerService(  735): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  735): Broadcasting onBluetoothServiceDown() to 9 receivers.
,D/BluetoothManagerService(  735): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@c68752b mBinding = false
D/BluetoothManagerService(  735): Sending unbind request.
D/ConnectivityService(  735): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler(  902): CM callback handler got msg 524292
D/Nat464Xlat(  735): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  735): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/CommandListener(  181): Clearing all IP addresses on wlan0
D/ConnectivityManager.CallbackHandler( 1565): CM callback handler got msg 524292
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Disconnected - quitting
,D/BluetoothManagerService(  735): Bluetooth State Change Intent: 13 -> 10
,D/ConnectivityService(  735): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1190): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  735): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/BluetoothAdapter(  902): 821522130: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter(  902): 821522130: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  902): 821522130: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1301): 167632746: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1301): 167632746: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 3040): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 3040): GKI_exit_task 1 done
,I/GKI_LINUX( 3040): GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 3040): cleanupNative: return from cleanup
W/ContextImpl( 3064): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/art     ( 3040): System.exit called, status: 0
I/AndroidRuntime( 3040): VM exiting with result code 0, cleanup skipped.
,D/DockEventReceiver( 3064): finishStartingService: stopping service
,I/ActivityManager(  735): Process com.android.bluetooth (pid 3040) has died
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 3050): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,D/BluetoothAdapter( 3064): 732085456: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager(  735): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=3551 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,W/ResourcesManager( 3551): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/AdapterServiceConfig( 3551): Adding HeadsetService
D/AdapterServiceConfig( 3551): Adding A2dpService
D/AdapterServiceConfig( 3551): Adding HidService
D/AdapterServiceConfig( 3551): Adding HealthService
D/AdapterServiceConfig( 3551): Adding PanService
,D/AdapterServiceConfig( 3551): Adding GattService
D/AdapterServiceConfig( 3551): Adding BluetoothMapService
,D/AuthorizationBluetoothService( 1301): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothAdapter( 3064): 732085456: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager(  735): Killing 2865:com.android.musicfx/u0a15 (adj 15): empty #17
,D/Tethering(  735): InitialState.processMessage what=4
I/wpa_supplicant( 3050): wlan0: CTRL-EVENT-TERMINATING 
,W/libprocessgroup(  735): failed to open /acct/uid_10015/pid_2865/cgroup.procs: No such file or directory
,D/Tethering(  735): sendTetherStateChangedBroadcast 0, 0, 0
,I/PhenotypeConfigurator( 1301): Scheduling Phenotype for one-off execution 7049 seconds from now (1449683892242)
,D/GetConfigurationSnapshotOperation( 1301): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1301): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1301): Using platform SSLCertificateSocketFactory
,W/Settings( 2252): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1301): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/BluetoothAdapter( 3064): 732085456: getState() :  mService = null. Returning STATE_OFF
,D/Uploader( 1301): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1301): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1301): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1301): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1301): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1301): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1301): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Auth    ( 1301): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.gms, Service: oauth2:https://www.googleapis.com/auth/cclog
,E/Uploader( 1301): Failed to get auth token: NetworkError
E/Uploader( 1301): java.io.IOException: NetworkError
E/Uploader( 1301): 	at com.google.android.gms.auth.t.a(SourceFile:498)
E/Uploader( 1301): 	at com.google.android.gms.auth.s.a(SourceFile:908)
E/Uploader( 1301): 	at com.google.android.gms.auth.s.e(SourceFile:528)
E/Uploader( 1301): 	at com.google.android.gms.auth.q.f(SourceFile:315)
E/Uploader( 1301): 	at com.google.android.gms.auth.q.b(SourceFile:195)
E/Uploader( 1301): 	at com.google.android.gms.auth.q.a(SourceFile:146)
E/Uploader( 1301): 	at com.google.android.gms.auth.q.a(SourceFile:73)
E/Uploader( 1301): 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:761)
E/Uploader( 1301): 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:582)
E/Uploader( 1301): 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:471)
E/Uploader( 1301): 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:386)
E/Uploader( 1301): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
E/Uploader( 1301): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:69)
E/Uploader( 1301): 	at com.google.android.gms.gcm.au.run(SourceFile:140)
,D/Uploader( 1301): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1301): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,I/art     ( 1301): Explicit concurrent mark sweep GC freed 79443(4MB) AllocSpace objects, 31(496KB) LOS objects, 40% free, 22MB/37MB, paused 814us total 74.889ms
,E/DataBuffer( 1301): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@a96720c)
E/DataBuffer( 1301): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1a166755)
E/DataBuffer( 1301): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2fc4156a)
E/DataBuffer( 1301): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@eff9a5b)
E/DataBuffer( 1301): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@13ea2f8)
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  735): MasterInitialState.processMessage what=3
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  735): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2455): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1565): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/art     (  735): Explicit concurrent mark sweep GC freed 41292(1862KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 783us total 56.602ms
,E/GpsLocationProvider(  735): No APN found to select.
,D/SystemUpdateService( 1565): onCreate
,D/SystemUpdateService( 1565): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1565): active receiver: enabled
,I/SystemUpdateService( 1565): showing system update notification
,I/iu.Environment( 1565): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1565): num queued entries: 0
I/iu.UploadsManager( 1565): num updated entries: 0
I/iu.SyncManager( 1565): NEXT; no task
,I/ValidateNoPeople(  735): skipping global notification
,V/SystemUpdateService( 1565): retry (wakeup: false) in 3599989 ms
,D/SystemUpdateService( 1565): onDestroy
,I/Babel   ( 2252): connection state changed from CONNECTED to DISCONNECTED
,E/GpsLocationProvider(  735): No APN found to select.
,V/MusicLeanback( 2455): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1565): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1565): onCreate
,D/SystemUpdateService( 1565): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1565): active receiver: enabled
,I/SystemUpdateService( 1565): showing system update notification
,I/ValidateNoPeople(  735): skipping global notification
,V/SystemUpdateService( 1565): retry (wakeup: false) in 3599982 ms
,D/SystemUpdateService( 1565): onDestroy
,D/ConnectivityService(  735): Failed to find a new network - expiring NetTransition Wakelock
,I/UsageStatsService(  735): User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1800000ms)
```
